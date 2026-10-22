代发 wailian999

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vppvirvc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2glxydsmp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjsvhyk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2nymincam.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2jidpludg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2veonnanx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2cbrkiyrb.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gt2qmiggnfv.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtrtuozh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2dncwerko.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwabggvv.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2autdlpvy.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gt2egfreolf.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gt2ixajsxgk.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2jocaeqtk.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gt2higsiqac.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2zfziavbn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2pwjzsklt.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqshngho.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2jvpyiqbx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2wrhgawlp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2mbhtmpbw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2cnnexlzt.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbskltt.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhtecpxr.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cqagfnyy.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxyyhxbl.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2qokxatgi.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwiqshe.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyoymvly.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvirmbc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxuazqv.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtvywzz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2phflxrxf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2xcccchab.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjyvhjuj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qglqspsk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2samahbem.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2izyrzojt.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2zohbamgn.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2mluwikkz.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvqgxmf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2orwmzkpb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhunlvw.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2igfrpmqy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhckwqz.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqpqnkb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2vahvnefx.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2txwdqetj.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgpassms.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubzayjep.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2isdojxkg.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2auykgveq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2lqalbbpp.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyifealc.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2utrafhsw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2imlyuoiw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbfxgqe.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2mmprxigw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqrthnh.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2swcrvknc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtblwgh.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvxmsnf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2prbsjgak.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2ecsvpnkb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhcrgnd.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtlbvwq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2chuvuggk.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfckuic.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxhvixz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2ylayrciu.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2eadjjwik.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2kdemibat.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2trsjxfdu.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptdolfcw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbcfeiio.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtetqwe.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmppzmf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjchqtv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqkubka.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdldvwaf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvlvtcem.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2xptecbbl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2zfeuidbo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwwqfnk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2xawsumzu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxzvngo.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2gqsulnon.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxxxwvf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhnkqsh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmjqqhj.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ugyrzmgq.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2ttckheng.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxiajjtx.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2petgmctl.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2qcicctyq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2muyddhdx.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2odizhqvv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcoeorec.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2ibgmkhlb.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2agqbehhh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2ngioekso.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxejusga.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2cvcyrrhh.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2fvacjklh.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2ihzopvmb.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2lgktfkeu.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2gwsrxblz.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2keczlwxa.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2gzoeixjr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwpxemg.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2powlrhyu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2stxcdhpz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xphxpkdi.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdrfrdj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2escdfzym.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbdezeu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2tbdbapab.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bklftbbo.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2puhacimc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdlpboc.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vrfzbrmd.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ggshcone.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2fiklxnfo.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouhvliwg.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhewfsgz.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzdnwnp.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2nqrwxuww.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqauoky.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2ybcqtmbh.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cynxbbcb.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqyivufs.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2szywkzxx.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2zizrlpfo.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwrdvij.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2qzwfyxfg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2enjghzrz.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2bcomscwo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2yluijemg.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ssmamocd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjzssrw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2einmjgtt.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qvsuxjrx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2lstgfbuk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ysersper.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2mvgzglyb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkpgpsm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2alliibyk.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ndvzczvc.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2jlijgrkc.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2acfvxmdn.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2awhoompl.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvjyztr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2eblmnwbp.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2pinfcfxz.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2uoagvblk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2afsznpvx.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtdpsto.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jstxalqj.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2snqenlok.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxxwyczj.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyozaohc.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytshqdnf.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxyhotf.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xqcusscv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmxgydb.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vvhwxjyp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfpeohkh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2jnxomdgb.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmgbuazk.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2jpiidwdp.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2klmoyiyh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxphrph.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2qqcqcbzf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2djtmiozx.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2itmoclwh.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2thwbynmo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2uombkijc.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2sumwmosm.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2lefsrzcd.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2agudrwvv.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2wjztwbds.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2jqtzpqbf.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2izvlrdls.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2dofirmph.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2ohmytmao.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdkzhuz.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjmgieu.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjierqa.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2jauuwasv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2lchavgmk.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzlxrpw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2wddmyxar.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qutbanli.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2yugysysa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmhkuze.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjngorf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2augwupjj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxcrwzd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2lezuqeww.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2otbaffoe.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nemvhtdp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcglvlsv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2frgpgdrm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2frrdqjlt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2kkdnoiul.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2huyxixra.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qlpmdzeb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2llpkjnsd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddiomeaq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrlyhvnk.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjaqggp.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqomfso.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvahyyd.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2kcuksufq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2folhnaok.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzceegh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2rjvdjeph.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2cqughkgq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2dddrvzvd.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2opxkjxyv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpuzuqg.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2odbvkkhj.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2kajjoslg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejympoqw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvalbnag.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nimsfxkt.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqqosje.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbgjnyoi.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2drkmlmeh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlgfcjad.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxngbdbi.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2ugwqbzim.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmslqcmm.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2syhiicdt.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sibijfad.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2enqkgzue.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2njgcdkkk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2eknavwda.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixhsfkml.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojlkqjpg.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vwgtnlgg.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmonexf.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ssctklde.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2esvjjzmn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2sktjsjua.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2kmxjwkvx.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dydeqjzv.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2iusygpgg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2kfeiitin.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfjmjqh.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbzspdc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2ejhkxzhf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2uudadmna.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkvzyeg.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2irbrxuoo.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2vvdchpxm.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2qjnhvbnv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2uekraztz.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmowaiv.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2osqbdazr.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2rdguuwcj.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nfyflqfk.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjehosc.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2smacxisk.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jokhmhbg.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxgqhxo.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqulrsy.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrdkkoc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dsgdjaho.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmlqbnx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jyzwxoux.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2tybcfydn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tiepibao.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2fthkarbx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjfzazw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2vejrxexv.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vjnsjlvm.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgqtlxj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcwocabz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrezbdtn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtickeoo.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxewliuv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2gezgqlcw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2duvumnrp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpriydm.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uanyymij.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2thfeifuy.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgdidum.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2nnlpzeka.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkvuwgo.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nakplskx.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwocyrp.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2pplrrrzd.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gxjhwpwr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2zuctkmcm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2vkvmyldd.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2ruyxdhor.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2hszfmxlu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2szuxgexe.html


<!-- 参考信息 -->