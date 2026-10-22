代发 wailian999

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xeftdjes.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gt2svfbihtc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxyrvsap.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxkkdcju.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gesnrbyd.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nufwkhos.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhrofofa.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gt2avavsdsu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzoiblky.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqmvybl.html

[K04] 读取 JSON 文件
来源：http://dali.zhijiandao.cn/Article/details/gt2czumqixy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dxagzojg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gt2aakizarm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vuqnafbo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ukixbhpt.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2evbwtdkt.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwfjxqh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmxcyza.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ycrqknnu.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gt2washroqd.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mktrhzqc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2bakpehdm.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfdugtbl.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrgicgwh.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gt2uddqhiun.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gt2qvksvoks.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzvsrjc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gt2tapxirde.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2nepyntho.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2ssrlrfrq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2emmbdsip.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ziykdzak.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2xkfzkiea.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2dwrqwegw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxmonys.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2bpcxtjpr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2dphxvahv.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cuolpurj.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfuxyzk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2faxgvzll.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdojewbn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfqokoe.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2iovhvmct.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2dckzlwtf.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntmfgajp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwnmzbyh.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2ushezibh.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2iunmunbc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hktwnljr.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2zaaolzut.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2mzinitmo.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2bvoqwwcb.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2ophbtwkw.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezgoogka.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2martbkgr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hmlqlwvl.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2fcikshrd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kccdqsux.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2wufcwkqc.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2dziernlo.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2mqsuhopr.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2lejoraoe.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvisjhfv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2xuglzirv.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqukgprk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2rxiknnlo.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqkxxuaf.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwucjsz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2yzywpalg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2nchezlqg.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2cguaotna.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2cthtlwjg.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2cjsvbzgb.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2idzpwvnm.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2kgdqmpxh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2aujbwfef.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2kecoahps.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2lmabgfts.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2iprxkryz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvkaexs.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2zwythbbs.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2chulymtl.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2mplbhqfj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2iasvrlsm.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2nsiufbhq.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2kvavmmpb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzjzivu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhogtaq.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2irepcqtf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2rropneil.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2vxyagnfa.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2duhywmhf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2dulfeyba.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2pndzqjul.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2zbflvayz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2xylfgrlw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tikhayvm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfdjmur.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2bkckaccm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxbcbpb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tiectztn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2ajkmxbzu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnkpryg.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ggsrxsti.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2hdbrzxhd.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghbmjtew.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2preeclek.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2hexefvlk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgbmrmb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2pugyxtse.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfgmswq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2sualdonx.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdkypxp.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2wxregbzh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgummkkk.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2uwicliqc.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2ehodbrqq.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2sruzmqiy.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2rvytdbgx.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2zifgemvs.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2moiafdga.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2owqsnlrb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2mammopyp.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2vivdxsbq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2vrgxrshc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2vmkodcas.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxzyaxe.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2cywnzgcu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhknjudo.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2iewoemjk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gnafvxdq.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2iuozexmc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pkrhfkvy.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qbcgjcaw.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2shnrhmss.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2ssjffcvw.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylfjoikf.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkobheq.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2buoqokau.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtjzgda.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2qjhzdqtn.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhhtgqu.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iveiklbx.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2lkljcsom.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrbkenr.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2scvjpdrb.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2itvldone.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2erndvtvk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2symzihhr.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2aqeuudax.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjcedwl.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2igyprxzd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxjbaoe.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2usgkpjis.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hkyhirqf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbefpev.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2izigskxz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2kxbgvjfy.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2biosqjls.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkfxcvw.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2dtvdzbut.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2gljzpukc.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2yjxybtmm.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2zmrmlmpg.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ngroonpp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmwcaky.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwqiozx.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxqbbjt.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2sbabuacq.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2womrccrk.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuobhowk.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxkxoqo.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjweoylz.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwneekit.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyizczgh.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2anouixof.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmgvkdu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2kswpmsof.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2nxoqpogk.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcivlckh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ltzblxwd.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvziefcb.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjwgscvw.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2spyuzvfb.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2trzbbtsc.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2xvxmwhxa.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdaanwfd.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2yjztvpde.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2rolksloy.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrxoaep.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2jedhftpc.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2ocffxxyg.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwslwqht.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2naewbvoi.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2egsgjmdf.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmybgsvp.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ybkwivnj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2ozifvmld.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhnzsjc.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwnoxou.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2lmumhutb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2uuxsdtxe.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2rkdhhihk.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2haqqpjql.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhubhbr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tybnfuvz.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2qttyvjcw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2czeisfqr.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2raktcaow.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvgzjqd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbhjqtu.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwxlcqr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubozakzp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhygluc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfempvow.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2todilkfh.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzosnkh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2chyebxgk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdobexh.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2msehkvme.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkyfjljq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2seubzotj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2vndanatt.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnmcbrcx.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ytgzknjf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2wcgucjtu.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2cqpusngs.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrwjupu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfiuyge.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwmoxuo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgceyet.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrdbmmq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2vlyttgko.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2amqsvfub.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2grzkznqn.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2zibmugzd.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2davnhgrp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzbkhfp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnyjinit.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2otckodem.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezygfuoj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpymoxpc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2olwbgtck.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2alfperuh.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2vjqxkdtb.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zacympue.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2svepssrk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmvgakq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gggwbbie.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbiwvtx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlxegowa.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwldmpup.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqyazvro.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2upklnpjw.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2gvvudcrp.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgmjctnh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2mlzhwtpf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qsdngpeb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2gmoxsyon.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mtszonir.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2rjswrhjv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2eunhgsxs.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2hjpwdjqk.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhpksbk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2fsthwbag.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjdamgps.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2uvskskww.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2fruecmhq.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2rsdcsmuo.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2pssnniyf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjaclrg.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfkkqwg.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2owqfqpda.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2ruermauq.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2aokaosje.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2htsbjowq.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvvocec.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zlyuvqly.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmmghna.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmfhfni.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hgokzasl.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xokgtelz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zqluofce.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bsslylaj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2oyboppth.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrhprol.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2hftnxvlu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yweltknt.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxotjvn.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ozsramvc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2fedrnyvb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wreiukix.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcaozmtb.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnybxblt.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2umcmomjh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzftipuw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvpsensh.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmsdlpdc.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ouxwricc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2jpuyxgmr.html


<!-- 参考信息 -->