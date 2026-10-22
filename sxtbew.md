代发 wailian999

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmlgibqr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjudsebg.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqyilmm.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gt2dohkoury.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pprstard.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gt2guzwhfzl.html

[K04] 读取 JSON 文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jxmuwnau.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2uzvulhzp.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gt2pesckvpt.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2usfguzpe.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2phjpjern.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjghugfo.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqgscxcw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hplzdhax.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtbdkkh.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvaaxwx.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2abmidayb.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2wzybmyrn.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2stxkiyhl.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqsaddri.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gt2yobcqggc.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxnpojj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2yulfrqrt.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gt2zjnqixsf.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2layiaigv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2ximaafnc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsdnjrrv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2pnynjerp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2iewowcys.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2taycmztt.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2hbrbrfkl.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2iismhste.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywcfxqnu.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fxmrfyid.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2onxjtjlf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2alhlhdfp.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfsqhyd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqcxufc.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpxynie.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2sosiwxtg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzbojiaq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2fajxkwzp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2zbbmvelr.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2phgmueca.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wccmurqd.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2akwqnxwx.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2krmbpihf.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2utrnfhck.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2jxyiseuh.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjwmcbtq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2kskxycpu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mzkvkysu.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhkohhi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2teaoaqwl.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2qilucice.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmisiyc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2skeneksf.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxzkjmw.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuuxopda.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2lkpodcrr.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqshvilc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2vvlxratv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2skvbiwya.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xwnsidau.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmiazgt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2mbottdmt.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2mrhienng.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2wawimxwd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2ucbtwvdp.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2pentgarp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2dseivjrs.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jxitiqwv.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2qpberbzx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrnxzgn.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhwamrv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2dygnoacs.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2dqxdtrbg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxxbuos.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2etcaskad.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2qmwmbhcx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxgktiyg.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2fxrlrkkk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2itfnvxre.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ocguyluc.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2hnhnzvrv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2xabgaavr.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbgxler.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdkidvb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2odzaychp.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqnteuqt.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdbqwky.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2nzekprbr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2crmrombk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2mqwtqzpt.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2oupjirbw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2uwatfcms.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vrvcdhzr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2tssfxmfl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2sseprtsr.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2gfcprgat.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2pyxakail.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqbwlsbi.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2dcjcyfrm.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2tpkbiqlx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxqldeo.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygghcsvc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzptpjbr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2gymoupji.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2rcqeeaiy.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2kyaqihzf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2zojmyksf.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2shumbbtv.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2cavhzcpu.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2oelyavwk.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2iykfsihg.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2yonngimo.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2xeecqgjz.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2fjygzvsc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvyxirj.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2atqdvmyi.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hkcssgwb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2asficsvb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2bynhjlgp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2jyecmqxt.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhftzbl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgrfjam.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tfdfwpto.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2drjhzkjd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2whgvvymy.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jsffhcbt.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ohyoymzo.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2udvnrlgz.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugyanxbt.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwosqlcc.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2bncktgjf.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdvacby.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2mrppuhqq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2klvwyqjq.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qzwzbtoo.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxwjklb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrnyzmra.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2kxmsivhz.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2fbksyhwf.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlojsztj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ngnjkvje.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxwtgid.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpwxnsq.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2itpshbqk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2aemitgow.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2amoglfpa.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2sdqaegsk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2rntwrufq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxyjkrg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2icyntbek.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2ingwhloo.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2zijxiblp.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2tucfaqjw.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ycwthlaw.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2tzjouakh.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2qpotobbw.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2urzzcfcn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2feveahml.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2jbelrmjh.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2ahlhwviu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2lymzsngl.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2qlkfclyc.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2moyjazqi.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2osflmczc.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmlodgmq.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cukdnlli.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhntbpll.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2toxutcxm.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hrfbkmec.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbqndal.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2cziqfzer.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2aixohbwu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdjpolv.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2pxvngukk.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2kgxcqjtf.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2lubwxvul.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhtruim.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2uafyvgxq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2vlheekvr.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvwsytc.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhmfiwb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzzrbop.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2nawkbfnq.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2sizxzkrs.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2esuywrjx.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2asczffrq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvrxykb.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2disustsw.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2rkvzdknb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2lleuojld.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2gaifvksb.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2nfnblqzt.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwerulo.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2trsmjgmd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2blalxobt.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2byfweoej.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2gcsifddo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cjaijquv.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrsqkjn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2avgilkok.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmgepsm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwfsobr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2muyjbhvg.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2sywsmala.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhwqfuyt.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvizdtcx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2luiyukpj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmiyfcdg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhpadck.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2dhdffhct.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmahszk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2kiuewbvu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofbonutf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2evxfbvif.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdkxklp.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2phtyrgmr.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2wcindxsf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2epqkvhip.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2ymocluky.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2hiehuvfy.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2kevomdww.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2twcoobxf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2kjxvbxci.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2tncdiico.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2txnyksfg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2bwngoutv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2htnepwuc.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmwkksr.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsqvylgp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iamvvuff.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2uddvhgwo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2foajhpaa.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dotokjik.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pulqmtoq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqqhvenn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nilfdzbw.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtmeccg.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2obydmddk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrxpiqff.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfedwxke.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvuezsps.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2duizktpn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xekcdxoi.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybudqnwd.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gggkevsf.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qingnnli.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2shbuvhte.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhryumyg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2laenkubo.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2siedytow.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2jztdsncr.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uosxmfrz.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2udtsyvqy.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2eruoczpc.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2vjjqoovo.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2evlnsvhn.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbewogr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2swpptwlv.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2cmuybprl.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2qdbzsybt.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2slwecntk.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgnlyur.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtywekk.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwstyyl.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwadcooj.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2lfqhswlu.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pijigley.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2sedgakjy.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fjakyiwu.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2eoupdgio.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2jktixbyp.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xoaalvxl.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mghhwsca.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pwfcopmq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjhbvfv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2baogxcrl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2hlswvblu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dxfzfznh.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2azttmlcv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uykfinjw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2oanqatdx.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hagkasgu.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2kwsxoqmn.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2demtwbvm.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxicoavq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmsxjjvk.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uuxcvwjc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2sntwyjid.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdstvbk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmrveihn.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqarrdm.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2nyjmquww.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bljtiwfd.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2vtdiixbq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2nrimkolh.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2uazipcol.html


<!-- 参考信息 -->