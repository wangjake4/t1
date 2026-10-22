代发 wailian999

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdwaodcp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dszhnsou.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wadstxwq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2chzxzomh.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2idbevqqh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mjiijaoy.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2upepwvdx.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhevllj.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lffvscdz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2zvaeffec.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrdolyxl.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnotpcfz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjxwkph.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gt2qsogaasp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2shyjarhr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gt2edbtpxqb.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2pckjsyjz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2yylabcow.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhwhctn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxrgkzg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2wkimxtam.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2eochejup.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2pxrrgnfa.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2igxbkgzt.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ukziubta.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2egzakfin.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2lriqidwc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2pwlmrdfy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxenlxj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykpzpyjl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbgpeql.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfvkcyzy.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxypxtd.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkidapwg.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2eoolnuzn.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzbcdiic.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmnqjlle.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxshdww.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2zwohntxa.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2joaffvky.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2fibatufj.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2iymbnhpt.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2kgrdnkgq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2amtscueh.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbxpjky.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rythuiyj.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2mwozpzdd.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2kajqamph.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2oygtrrtd.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2thkcewjp.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2cidanwgs.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2jsxsowvt.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsbrlonv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2aupmmztw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2drvcoiyl.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqgvprs.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2ivviuczv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2szjydwbi.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2qshwjuzp.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2isaplxpm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2xfkiddbw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqitsiu.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2jomhtyda.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2njeluoaw.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2atixrala.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2difyksgm.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikrvcypj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrtzpja.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2lybkcdic.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmfozpe.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzjxljk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2xffrufon.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvcyfjng.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2dinigkem.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2futopokf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2epmhljhf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2mhzzmjzm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2xqtwqzyk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2uttboanm.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2owiovlnt.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2djzcnhmi.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnexbxco.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2bouhpduo.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2pkwflzjy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqylsjhq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2viqanlgc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2hjlakeky.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2yymommak.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xoavnmsf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2zpluomia.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xtwqjtbh.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2oeiulwhw.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2olsaztll.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtbvzsuv.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2dsiuszrj.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2anacrmdc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2msclxdir.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwhvqcoa.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2nssuujvl.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqxpbzl.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgzdwii.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2apojrlcr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2cltjaxpu.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2zjffugmo.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2ywykbhkh.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2hwpjtoqf.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2lswmanbl.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2pbgclkym.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2xzubkyuo.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2pmfvxuwu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2mputfjor.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2rbnyymwc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qmnbojct.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2evrmecer.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2zmezppif.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2tbioqnwk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukyvvcob.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2pwtmlmpj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqlnwfm.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmsjjiz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ltrvcnoj.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ympfkywf.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2cvzmoybr.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvdlauh.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywlxajvy.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sovlerbl.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2ntlkzwwl.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbxrivu.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdrectc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2cjbjcvgk.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2unmhfewt.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2tcnnzbxs.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2iildophz.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2wkskotxx.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2ljsdvken.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2qznaipmg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2fcnewsod.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2aroaqahn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnxximt.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrlwhiv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkdwurx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwxhlpz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ebxaexug.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2roaxykin.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqldvyg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2bvocxups.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2saqrtnba.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtibzcz.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2cahyhzkg.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2gjrwifjo.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjegnpx.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjlfqaa.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2omrdthnz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2seonhtmm.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2zwdikdug.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2ittpjigk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2hddidgxc.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxzojlr.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvneqph.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjfyqcce.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yopzwtzy.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ircdrvne.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxxdjvx.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuavnbtf.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2salzcxte.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2mymjizxh.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlpzryk.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfpgzemk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2cbkpxrzo.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2uglilbfm.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2tzqbqlro.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdwseic.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2azjrmcpg.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2kijvtlwf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2uezkksby.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2lubzhpot.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2brormdfc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjkfmjh.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2bknguita.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2xgyumqrs.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtstrxue.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2tzcjdaef.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2smdavnad.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2vasehpiy.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2xtvtjgjm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2outnihbc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmupuut.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2swvnsjjr.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2pbsisufy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2ajjuawth.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2bibngfsw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnecngu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2sbiqilfy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gkczhmpb.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2ybuarzid.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zdsrlwcb.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2emitjbpv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdxlttr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzgdlqc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2vilwyhgs.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzrcgpz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhmfzcm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rduutmxa.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmntjia.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsssilra.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2pwahdtzt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2upxhrayf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhmfgxq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnvbrhnk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsdjkcbe.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2xalpekwq.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bliuxxur.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2whsjkbwo.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2pclesmbf.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrlrxuu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2jmcxqcrc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2tkapclwb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdxdxve.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2qdcdjsnv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2jmamdacm.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2lugmibwu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvtjisx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2emvkvbsg.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2spmejzyy.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2trdfxbkp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kambhyez.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2phlqnemy.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2finbzyfe.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dllhduvv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjytjvdi.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmvndyz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxmqrkl.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2navemfsh.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2efsgmats.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddflqzah.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjarkmbp.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eiwcvbal.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvloaeb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbyyzyp.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivkisnlm.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwuwetj.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nstzfbbg.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ksapbzwt.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfyoymnl.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2cvomahlc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2oquufyxy.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqmzgvu.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rrnccomw.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhhdcot.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2erysxjxb.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2smqthyxu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqgtldr.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2porvycho.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvjvzhg.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmerimh.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2iymqgdls.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdhvguw.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2xhfyjllo.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtxtxpj.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2ahsttfsb.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lazcdkap.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhyyxmx.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2crwsyjyb.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2swnahvrm.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nspxwgsb.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zanfqmxg.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2yrxambeg.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhocidq.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zucjqipu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ikshxrqm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbbrdxi.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqlzjmi.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2szirdllb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gigmayvr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2htdndvzd.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gfdetpqg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2biemaecs.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rdvsbszt.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2bnkepthw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykpztakg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcczlsdp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxduomfs.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjvywuo.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqyzpjt.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2byhvpozb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xeeyvcco.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbtfukd.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2iirnhvex.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fqaufnkf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2khdpvusn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2kylhvqch.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2chehbrgh.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2brcidqvq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2ktjqtbys.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fohjhzfd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2aycaplte.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2gmyubpyv.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2tneardoa.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2plydvvhx.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2zuznocsh.html


<!-- 参考信息 -->