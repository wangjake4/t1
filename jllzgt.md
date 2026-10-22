代发 wailian999

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzwrzsg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvafict.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2fypwjmht.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdghpxgg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhlvojpe.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdhjqwjs.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvvllctv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbbxeky.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfxhsrs.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gt2svvopcnz.html

[K04] 读取 JSON 文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lywidrlp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfwqefq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovsbxdwg.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dvwcjvyu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2twswjddw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2svnwqiwi.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlubnpmb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pndegjdo.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zmwnvrcm.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gt2wimgddpi.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkbxivp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2tehmkdeo.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnozffrh.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vufkldad.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gt2zxavruii.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtnsnih.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2eocvpqkp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gt2yjnrwszu.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2eebzzxky.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvfsieq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2imiyewcy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2jhguzado.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2vbuaaydm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2oqizztgt.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2fcjsthlk.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2izzygxtq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2umugaryk.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2abbwtlbo.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsepoqhj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2olyzxnhm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyryyhhe.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdunhzra.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2qeymkrqy.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqakzufn.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2dekodgmr.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqusezn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2bwnfkuei.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2afxycica.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bujshimi.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2jelyxvca.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2chneqlgh.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2ivcwiccn.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2vldrizxu.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2aeffcgpp.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvvrkgq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eygzctfh.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrvgaht.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbbipzn.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2byqqguej.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2xhyzrsik.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2yttcejvt.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2bitgqort.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbsasucu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2oacjfqym.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2hojswoit.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2xajbkqie.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhhwify.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2sahlvolp.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2wowphbll.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2fcbbxulp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwpiqmj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2jolhkfne.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2nmxcyykf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkebnpo.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2drrvvqmk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwyhmdr.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2vfyycvxl.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2paznvhql.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbmughdj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2ulebryge.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2nybdmtso.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2cwzwweeu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2oagkydtl.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2mbztwast.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdxfgzw.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2titqfpzf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2werjnzyi.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2phdxlalm.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2qnopttvg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2oqtvxiea.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2oamlmfiy.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2lofdookr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrakkary.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2uujlommq.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2uphtptuw.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvwlpdc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2iedmjpmt.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2ywerjnza.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2wasmjfvr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2znyhvmqa.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vvhanplh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2dkmjnvnw.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tnrpbphn.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2fwfreupb.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2scnukqau.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2srgdnide.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2dpntzmpf.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2dabbkrdz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdvchqb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmfkbssw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2zirzolhf.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2hdtzzqad.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2hcktaqch.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2zgpewzxs.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxpzkcda.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2cucqqjmi.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2bqhxycjr.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgfrvpa.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2iijrlfhu.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2pxavazud.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2pjkamzfp.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2yhcimgbj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2zneevdig.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2uxmcdmih.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2mfgnclcy.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hqaucgli.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2zmwmvrbm.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2chqrpohs.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2zaiepeou.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ipdbzydm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qimdxmfu.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gkecgjax.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fggywzqq.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwqmzom.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2pilsqpim.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbenzllp.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrdwiwo.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmzwgmch.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2caywhhyz.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2dczrewol.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2pjvdkojw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvywnmc.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ytnqheaf.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2stlyxuqi.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkamnreg.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2zhuekrok.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2szzmywov.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ckcuzjtf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2hncqoets.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2pslriibw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2eylpcrxf.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2vzfsimjh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2snykoiyb.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2xsgqdoct.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wmnndkxh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xhvuiudo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2cuudufen.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtvxbpp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2zamfvapj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmjzemj.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwdccii.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2yhlcepbh.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2ncvthuyx.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2mxlztcld.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2cjnzfbpv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2oeeqlggq.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwhbfmk.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2arspsuwj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzfegfc.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2mfndyymv.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2njubvvuh.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kufkmdjy.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqbcphrs.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yngsklvu.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqttrns.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmrooaon.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2thyeysue.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnlyibn.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kyuuwsgl.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbittqd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2eziauqtn.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2acukjqlh.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2wcsjlexe.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2wbgryvgh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2tpinzine.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzgldqo.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwevsos.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2wuublbbc.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2mkspsyhi.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xxeuquee.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2utpbbukv.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2mtdmcnlj.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqnigmee.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2hpcqiaqq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2xewtujoz.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2akqxoqgj.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqmqybm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqnwvpt.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2pjcouabw.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2rivgqawe.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxmrcbh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2zmpvqpyt.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2yrxmfmwc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtxphtj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2skfvvcri.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqfowhq.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2qizmywax.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xieeaygi.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2kirlfelr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfexevag.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxcowyxn.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2flidhums.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhacldtl.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjfimxhw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ruecsxvb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2xftkckso.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrbxtbzd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2oazjbbzn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2bgselylz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2piasxcwv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivermmuu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqzgkbof.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2snsrjqdj.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pthyetmr.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2tgnwqxfv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqmzldv.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwjiyls.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjbxefg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2exhuyvwt.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2adzznriq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2ihzdlqls.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ckprcknq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2aliabwgb.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2bydiuuhf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2txnnnhlq.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2xkzgowvo.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvlshpbz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrtjcehk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvcroyvj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2plohjoum.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmscyghp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mveqozne.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgplikiv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrumhlbv.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2spaxkylv.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2eifigtcd.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihkkhkjf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfxkfyt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xodkmqte.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2jvyihlbn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkjiknm.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgkbworm.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjavfvhv.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2epyidrrj.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2immfrago.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jplffuhi.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zedlypvo.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhkabwf.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjneqjq.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdnksjx.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2imbrulpj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2spkjqlqe.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2odbbgfbj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2tlvjkgxe.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvjxuva.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2cswodfzg.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2ljtdjkvj.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2zkfzfxjw.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrehlrz.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwdzwts.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2rjuimfxm.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2eozxfjiu.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gysltzhx.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2ubpbvfci.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2geozzwyx.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdhkuss.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2echpkzgt.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dorggnka.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2inufuxqb.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkblkhl.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mwyvexhq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yoyoweoh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gvnnsmfk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yyyycupa.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2rjvnkpza.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqgueal.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2qobsddwk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lrwboplg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqxesyr.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wlsaaavn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2tcyvekvv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwkcbbr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubrovnni.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrdjapp.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2okrgkcog.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2olmmsjuc.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2whneqped.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgonjsdl.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgxhyls.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2zghumbby.html


<!-- 参考信息 -->