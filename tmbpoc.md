代发 wailian999

[K02] JSON 字符串转对象
来源：http://dali.zhijiandao.cn/Article/details/gt2vhndgkef.html

Py:   json.loads(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnoxabzl.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhijiandao.cn/Article/details/gt2lrleqjfd.html

JS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgddmagv.html

TS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcmimlu.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2iphjtpic.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqdercb.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjacufgp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2grpdzoeg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxybvun.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfdykyi.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbigmbvp.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwnsvgam.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dppxobma.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtquuewx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvrnkzr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvcspjnl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqbbgim.html

[K04] 读取 JSON 文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ueaevyjw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wqztemhx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gt2dshojkdt.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2onnitggr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2waalfbbc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2mctynncx.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpcqmtvv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2igyojyty.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xbgiimov.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gt2hiztqnyh.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfxyvgg.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhzihul.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wifcnjpw.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvkyhod.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gt2arbejhdj.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gt2dyldqxqd.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnodqep.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gt2bspjfqad.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxkohji.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2hhlmnyyj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdigfysl.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2wndkojeo.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmfeifa.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjdtamu.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrwhzojj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2weccdqfw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbbpybo.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lxnlzzyl.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnhrfdu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2kjjkdzhy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjfcsoko.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2iroqplpk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejcefzug.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2kksokdkt.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2bclwgadk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkoabtu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2ieffesvp.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2delgycli.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2recdaftf.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2vfliiprv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ismyglho.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2hsqfjlxt.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjtzxdi.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2upojnzuv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdrqaiw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hrerwdtv.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnwzkrf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvnqdbp.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2oezyrvsd.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2sisuozhy.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2hnexlibu.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2wemdefvk.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbngkyuu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2yxsqpumj.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgdppnbt.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzikofr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxbborj.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2domianyf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2ghlctomu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2nzansefy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ujotkejr.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2clanpybq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2lfqbcrqr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2nxnmlvda.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2pqkzkcaw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fkbuquhy.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2ffktrzua.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2kivnohks.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtvcuuy.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnrkjya.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2dkzjious.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2fotniydo.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxgplwvu.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfphawf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2jgxspszg.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2inyunfzj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrleuzme.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2faafopab.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2tyeeqcoc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxlunip.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2scpatpyl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2qvlotyvy.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkspqrk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibkjrjok.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2koqitmzz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2kjlrzpen.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjqkhdyd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2fznqgtls.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2aeaatobj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2avhplgvz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2injggbab.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2xpusxvus.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnxctki.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzlsnto.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2jsueqfrc.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tsnuqehr.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2nwtqoyex.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2avhxicsw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfopbjv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfxmoqp.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2wajmbgpt.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2sqaabnng.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbjbjxx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2jozgrjdw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2efqcttps.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2gdrcxqmc.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2rpvlnytb.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2xycjoclc.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2psgmbbjl.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvnyxni.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2vwgnigbe.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2cctatahu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2akbowumb.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxqosfe.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2bjcuuygy.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jrmkduoz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbofbwa.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2nipvtrtp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2hobfkmvo.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhukfqy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ruenhjbh.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2whfndprm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxgrrwb.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ycaqkmim.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2jjtpvwma.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbcibxz.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlioefmc.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbysnqqp.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2uinhqjpi.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2krglgies.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2jgmbtrop.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2avcorfaq.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2myllhxqe.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2vszlauvi.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2claahlat.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2lqkmqlvt.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2qrwslkcc.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghajpgqe.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2uppnyehp.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2ilaunstz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttlbcsxx.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2sacngtjb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ognowqks.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2vtdabkkj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2fkbbhjua.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bmnyjugp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2yvuaydlg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2bziztory.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2xlypipyd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2rddgrhtw.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgeqmkh.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2jpoxajso.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2fpyxvabi.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ikeowzkw.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ysffozsm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2kfgvsddt.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2tseprlhp.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2fplnlrvg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2seugtcsi.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2vytxxptd.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxqeithd.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vyrzhpfn.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrazvsno.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojpbctua.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvppirzt.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtitdfuu.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kchaenlx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2xhiysvke.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ygkgkktg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2edjnrbho.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgzshuu.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2topcsdjf.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2nlihsxzk.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2wrqbxfcl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2canqulos.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2eeodqerd.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxsrsugw.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgebvhs.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2akwpptkm.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2djksmmrx.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2ovexjbqg.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2bukoutug.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfpdsbxo.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2dxsxhbkv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxxdofe.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlehvpsh.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2pinnzrhn.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbatpul.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2vzucajxt.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxzpruy.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhhrlzd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2llqyuspz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2qffdalzn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2tisonlyn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxdzklc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lyicebgx.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2dgnqgwwz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhyteua.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2rdawiylv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmrlief.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2yanmmifx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtqbgic.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2kudfxgob.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymezwxly.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdiegcdl.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2uausbsvm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfcsltm.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2fmpdpvjg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2bvwagdrg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnrokro.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dryjltrp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhcmuwn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymmbmrse.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dagjamhc.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2dcmpksdz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2tqlkyifz.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2tblqdpgo.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2aepjrqew.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2iwnchuag.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2apmmjhlv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2jbkjwzap.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2nivhqnkp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjlzpoj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxtjqtp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ozslhfph.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2blxivnww.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpbsqjpj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eteflvds.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgepnhwz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrzqahlw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tczuldhz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kraeuvcg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsvsiuta.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqdtmse.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2vbeaprhl.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibomvkjf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjstwxs.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oeaznvfj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tauhuomb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2yhcpquhw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuyijjak.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qakmwgrw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iavptnlt.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2srixhqte.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvobpqq.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jlawhlql.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywadksoi.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxjbcmf.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2vmrduqbw.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gmbftciw.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2jewviqxp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2zobapzbi.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2vchxvsod.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2alrrbfyb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2aftxqrwy.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2isbatfuo.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2shbtzzqq.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2obmaydod.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2rahxewed.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2vcoeific.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2jqtttqlq.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhfvoyk.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjnrqcr.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2ojoplpzo.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hslkjrhs.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqhhacp.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rdgjneux.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2sihccsdd.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2ralkmigk.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmliqzk.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fcpvttym.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2anvweppl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbjpgtn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlyswix.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdewdxa.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mgidnrpp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2cykzscxo.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pihgzmfb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2wgwfgiiy.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dldqzfsw.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrvroow.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hegtwnzv.html


<!-- 参考信息 -->