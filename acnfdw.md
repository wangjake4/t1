代发 wailian999

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2abjjkaej.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gt2blwnmzzy.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlautkyr.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqidggnn.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2trpnrtnh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyopkxrn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lidiwdyx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gt2arjdavan.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2noodqyns.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gt2scufolfs.html

[K04] 读取 JSON 文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mqcbtntd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbfqrvq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtptwfcn.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2spgrlqfd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2anheusya.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2nudglvpb.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhzkmri.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2yhlgzlma.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jgbzcdre.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gt2snjhllaj.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwltwafk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2coesyrpb.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2llyjvyqu.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2yerkngkr.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gt2afhkgwys.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gt2fpufjanu.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2aljszwwr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gt2jqefmlni.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2htcpskyt.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2owmisfry.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjfldfrh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjymncy.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxpssdft.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2bcwtknbu.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmboleo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2sagphrre.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvoczpx.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqsxenu.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtudktdu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2ddklaflf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnkrsgv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbitngm.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvjyyix.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzimhus.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2aobobokg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytnchssc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2zeavwyft.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqnhvto.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvzsamxe.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2tlwezqbf.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2nyolbwyc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2eeraseke.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgtlery.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmnfmkr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2srtknkhi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlczesc.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvlbfnb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qtmgfewc.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2rwcytxxl.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2xxybnake.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2eijeinej.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdfdwptx.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2zblvmfge.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2thaetlsh.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2bskloqpy.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2oaacdefy.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrcmkuem.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2bicpcghu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvsmlxw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhmvnli.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvvqwoh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2kvtidojp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdcqqlp.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2kmlwnkbj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2yqajvyio.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2snhjzwfs.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2ctpchaqc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2vxthvqdv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzddzfnv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2agvtrdyp.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2ozkvuiws.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2skkfcbjk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxlnwsf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2ykcnkpfb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2qofppgvc.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2xsacsnjc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2jskbagsx.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwnnjkd.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2uxwaqckg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2urehfimn.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2trenlnhs.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2uuyshhab.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfcsootb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2udashpvt.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2eplfmobf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2eydjgwul.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnogxeug.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2okmmtlyg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2gwijbemk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2fxfqrzqh.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwxgdoe.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqaifzk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xztvhiij.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqpejjp.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2tkomvbnv.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfebomgq.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2soucpsop.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2gutjrjxj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2nburjkib.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2aupbkpdy.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkveldwo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2pshqoami.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2kmpqkfoh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjjcaxq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffqgbpcm.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2dzhvchax.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2arvnhvmr.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2vdoqashe.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjrqlio.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvhkvic.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2pcmcdcgc.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzcjobi.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2kpusqega.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2yoiaqndz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ffecyfyn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2vrebgmch.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2efarbxoy.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2djfmfmvr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2jztipfcq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2yagxmguc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvfavhk.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqaetkc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wpetkyyo.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sarvnmgf.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2pypknmrp.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2erzkcnzb.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iekfefky.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncvkjzjf.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2isporkdh.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2rwiquefe.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmmanzb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2flfgxyop.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jwskbiji.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbqxyzj.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlgwahbe.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2zlrabyam.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2omatbzpt.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdfpcci.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2gceckfnm.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfufrkr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2bydqvqpf.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2kenxhbcz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2echyxawj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2kjyqgczb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2cqkbbrgr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xymlmjnc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2vavpszcq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmjkqqa.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2edzcmwog.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxwfqow.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2bklcgopf.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ehluddmh.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2ldfletjw.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2dvzjbmqx.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2efynbzid.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjtlqzg.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2oasgzjym.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2nlihpdkq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2mmeolgwq.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2gumivrss.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxlpnkv.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2djuxwpup.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzfwjkxa.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhphjryg.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrcuejjr.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmatvvm.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2iypdknxh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2nqhkvord.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwjduxq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jltwadam.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2tqssnbdx.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2jieeybqp.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2xsuihmhh.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2sftqcpca.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2haqwvide.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmeulag.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2jedntqfz.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2oxnsxqwy.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2jajqoypf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ecdslspn.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfatwuv.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2otsorbgs.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdilohoo.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2czvmhyuc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2ebzwfbgn.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfixzzma.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnvxask.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2axxeftuk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2yvdvlxdi.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2xxffcmqy.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhzrcwm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2sgihnadq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2vjcwxhrc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2wnctvols.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2ktczksoa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dxpoihhd.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2wfkshfyp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rbnfcbnz.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2imnpayah.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fujnqibb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmlzqxfl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2yusqqewe.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2sekxltuu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vspcmefk.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjvykqb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvutckur.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fghtjtar.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdrbrhe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2wwgoelkj.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhsnuhhu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrsfdzvk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfrlotxs.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2xykwjroa.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqdhvdjp.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2xblizmvu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2koqkdfpy.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2tikjhlzj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqkezwk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2sycuvlcp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2lksykmbu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2bnuukbbm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2jyofpxea.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2nxphgwme.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2xgnxdztr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2csrehlti.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2nkcjwxqz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdifxda.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jszhpfun.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvoputc.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxnzict.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2louvjovi.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmwvykhe.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayiqhbvh.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tiazeyjv.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2vmanddbn.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jebzkyxu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vocaidoh.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxzknybd.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjpdyusu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2zzbkceuu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2urjumnyz.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2knpntwfe.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmeufqvu.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2etsxwxuq.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2wrdqmnbs.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2aevqzqgf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ifumwvxu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpioegb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2pmxzznjx.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2txplgvhy.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2coqclxss.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2rvintcox.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdahhjc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2iydxvhqo.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2wvyaczeu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2mevmfidk.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2yslzqojk.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2nsrapecq.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2jkibtqpo.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2tcraubzb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2ndysqqii.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2ixlonpkt.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2codmisji.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbblxsb.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ixzakhcs.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2iavssnji.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvaezlo.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vtsvhckk.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2vdoxkczo.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lqozjluz.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jvyrfseo.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gtpnjjuh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkfeocx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wxuredhc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ashjssef.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmyuawq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfmzhwp.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xngdlmor.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2faslxghw.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhklxmx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2ecdcjaib.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fknkbalo.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkgyhgye.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzcizjm.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrjhogj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpxgertr.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2popahdhu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2udoclzcm.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sovysvib.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2zyjwrplq.html


<!-- 参考信息 -->