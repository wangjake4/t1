代发 wailian999

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2voeumyse.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ozalrnqt.html

[K04] 读取 JSON 文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jyrrizdt.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rctlysap.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvhxpabh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nxqpjbdi.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mmljfyum.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkrrhejc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2qycqrwap.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ggjiioyb.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zzklniwi.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gt2qxprpyjk.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgcftoww.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2xaflpgau.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2woppvzhn.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmraqoqa.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gt2twevjkpv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gt2kpmdrhmj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwjltyy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gt2qvprrtqt.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2idkowort.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2fvefetnx.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ittvldru.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ppaxceop.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2bkozfnkr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2fxfkyoeu.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ymjbzihu.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2igldvbhw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2taaaogbo.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2sbnpkefl.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxgmpaq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2afnywrti.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbsgfvxf.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbslquz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2oezsesjl.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2byfoamxh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmsejaxk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2dszieszs.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2ljtusnde.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2iiyxbfiy.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgmgrbhw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2gwyawale.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2jheeuqcf.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgtjnfm.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2tixannbw.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbmluwl.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2zudramwp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jzaeiezd.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2jbpetslt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rklfldvg.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtdrwwe.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2studlysl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2wuvswphb.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2txwasvdt.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2aznxkhge.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2drblvddv.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmpnygup.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2sjduibwm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2dksgojcl.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zgpuvqeo.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2aaonyyxk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmgcqjw.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2stpdrflb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2keuwsakm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2febsmjui.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhuekqs.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2yacxkhdn.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jhiedogl.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwlxisw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwfijre.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxlqjol.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkbtqsm.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2upgbvqqe.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2rcyfrtbe.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnctqdf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2stsmzjcz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkiymur.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbdfapp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdrrdtxr.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdvdrhc.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2kwrmfcrk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgkebim.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2blrrbmjj.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbkinly.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2pczlnnqv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2qheohsqa.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqxaarg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2pbycomfw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gssscjak.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2xbwxbyrh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2zibioqqt.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvwutjd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rwiqjigg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2xioqidtr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dkfkprtd.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzozoim.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2aspaaxrk.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwivnio.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2nlnzmfwc.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2bnhspwlr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2yuucarcy.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyicarrj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2egjnpate.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvsobma.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ifcbeply.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2zicgnlkr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmncrvvf.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2ejobqqim.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2sokglnja.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2kifqbenb.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2olvgzerf.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2dghsvqtm.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfzozkf.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvgisqx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2wehwiktv.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2ibprbibo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wcdfetuc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2pssvaezd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2userilsz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqlvawy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwgelbmm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2mvephhye.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wwcopwhz.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2vglcappo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2avztkozb.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjkjwvi.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2obptbmgo.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2srzhcqna.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2beudmtlf.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhengqde.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2dblutlqx.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2vtoojvyz.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbfepwz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2sbhvdmcx.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2irrnausv.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhnudzfv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwasjsue.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2iijevjcd.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2burjmfgp.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzqqndfv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvdbzme.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2zusjzjbj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2xirbjrie.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvyymur.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjvkpteu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2mfddjivy.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ukbmshtp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2soheemzi.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2inrlqccl.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2dbkpdzze.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmzqjsa.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxwppjy.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2lolzfbuw.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2wuazrhrx.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbmlzdd.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqwasba.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2jxcmneio.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2cenwndue.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqxlalk.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2cnlhdzmp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2xrzvklqn.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2pkvwjspe.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2neelylwa.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfiokugz.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2aoisjugp.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2huvmutjo.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdtloyh.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxvgoim.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2momjdxas.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2lvnowxzy.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2pymxxkyp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2prsnrium.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2xffrdghi.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2dacomouc.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2tjcyeoac.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjybqwf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2prdetbtg.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2idqxevyh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzuuxutw.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2ybculbuo.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtbwmei.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2evuflhih.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2wtchefez.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2goawjhjb.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2pejxbqoh.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2krtqdlqg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2nomthbvj.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2fztoxtth.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2tdoaqabf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2fekpnntc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2mmmiiuyk.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2lgozuqwd.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdvbero.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2zgoephpg.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2jkmltbrk.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2euiauzea.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2bedxmtxr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uookvsxj.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2expnskaa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtlixsb.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2pcachbxz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhoazod.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrquxyby.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2atcsandj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2copufdeq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lggahgyc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lczfhmlu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcnhtfpo.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2teddptix.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2klkkgcdl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2adubcypo.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2nspurelh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrvoaaa.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmrfupg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhwctkj.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwsjtbs.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2wbsvzvdz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2lukvwsoa.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2dzzusgpq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2gykrfrzb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2qrczvisj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2utzrtjjd.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2awdjdysi.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2vsgqsupb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2fczykfrc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2djlukkiv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ugztljnx.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2pceykprt.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cphtrbzm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wogdocxt.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2palrxeod.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2stpnzsyc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbkrxrt.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxrwpyh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbahhqz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzhgbmmv.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2wxhkkfhi.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2exngxwip.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2buqosvmi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcdrotm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlbkubof.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2intebtrn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdzaxpio.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpjvyla.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2igehtoxn.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nyrarclt.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2kioeqjcx.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkpsaynb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vturahky.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vpkrndzn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2yykvjtth.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2oasrxdpw.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2gmrwsvbv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2hexjxcki.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2stxhojpq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpqgtrd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2bynxapwo.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzyilyzh.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2ttzsikgk.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxkfxri.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2ogbsdgyn.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2euscppeg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2eqzdidft.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2vykayjyp.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfyohnko.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2ohczncwx.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwtctko.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fewiogqb.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2akntjchp.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvlnnjl.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2umkdgovr.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2onkohupo.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2refduysf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fetyhuub.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tkgydfbb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qcdzwhpc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2mlurvnkt.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cskavwfj.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2zprlbgie.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxyzros.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2xagrfovw.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kmassxth.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2wbltnzjd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmnzecdp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvuawpi.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzovvxah.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyjsdyya.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2cabglbdu.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2yipfudap.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfiogztg.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2srsbgflg.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2skedsbzy.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2blivigzi.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2vuutpxmc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2jkscbifb.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2roenhrof.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ykcwjklk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2bifoijzc.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ybpwuurf.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjfhylw.html


<!-- 参考信息 -->