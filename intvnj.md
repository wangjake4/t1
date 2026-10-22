代发 wailian999

TS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ormoxrld.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfxrkay.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqvwkcd.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkqitpn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjqowgg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gt2ljtwekij.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmsjdnwl.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgcnaexd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oplswnok.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvirbvte.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipcddwal.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gt2easjfmtd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhofrbjo.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjdcktl.html

[K04] 读取 JSON 文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hjdxdctt.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2uapjiroo.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gt2eforzpgw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xuekxury.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2clqohrne.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwlwwmmx.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2srjinphc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mncrpqxf.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tuwuokeu.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gt2gehsfmme.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjvmzbjh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2jtekhrge.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzsvvnfw.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqcrgij.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzqtkwd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gt2sdknxtyo.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2qpolyfre.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gt2mleintdt.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjejuyw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2kkjoaspc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2veljkukb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2qiginyff.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2corvyjao.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxerpml.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2bpgmnpra.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2pskbmoug.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxxpaac.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kaxloojx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ervneahr.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2vcnbmdxw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddzlermx.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjyotrx.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgvbfzjx.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2kntjdiwj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2snxwmksm.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxyvveb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2juwndsex.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnjaacji.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhzhlhjt.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2mctbpyip.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2pbztqamj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2buxkgdzv.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2vxkpbblt.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdelnopo.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2jwcwdcpz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2scgmiudv.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ypdrgonn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvowbvv.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ryabbkix.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2zkrbyzri.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2cycbixbd.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2afnwvjsy.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2knkbyjyr.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2znnwhaqa.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmkjbls.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2jklmuwqx.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrhqeav.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ptoqazkd.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtoxucg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2jusvdglr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2cglwwdfj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2jdajknfu.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2brissfdm.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxrdztq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtpcaie.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2eqakenpb.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwxyftj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2cjgkqgfk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvrikxq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2yepipwlm.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrifzta.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2hwtjbemb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohytsevm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2expugyvc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2iiouvzqm.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2hdepfrva.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvndefsk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmhqkag.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2gspizokn.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2crnfaweu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2giktuvdo.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2ipssouoo.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnqvnbm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxbbpuh.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2iionrqbf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2aejvmimp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwhchqa.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2ggihsiav.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxtxiah.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2kcyicqtt.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ashozmiv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2vpauyyzq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xqyrrqnf.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jfdgkfhf.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2jukrsszw.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmzgpqka.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2tgxglawk.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrxcikx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2fndirell.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2adkeonae.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2saiusrkn.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2umdrhxto.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2hrtutbzj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2qlkcfnrs.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2odyjqbvt.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2zxnmrool.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2httexrvi.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2ixddtivj.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2oodkzfbi.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2vcqughxs.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrgvibn.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2ehfiserb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2fewpcvrc.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2qhyeixgf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2zobwueab.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvsajet.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2jkjowzdg.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2znjydcvl.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpevkylm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lsevkpqf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vuptxoft.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2okmjgoog.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvwxlza.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ggplpoyt.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ckevgucx.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2fznvblnb.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmrdysje.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvynmhi.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2ozearxff.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2aseydyie.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2lylrdbvk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwzgzed.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jcycfuvs.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ijlskgcz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2leyjxhre.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2lpyyfvqv.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2vmpjyfgi.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2wucqzjlp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2yocbtlfq.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2sjdwpcbp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnrhjqn.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwxxxko.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2abiprcik.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2wovibyil.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2pilcccxw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dlnemuzk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2teyksnxb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzdnwbf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2hjqttvre.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmhbfnh.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2sbvlkgos.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2werqmasm.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2uholpfzp.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2qtblpdzs.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2vspsnkdb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2raomnbkr.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxshdiu.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2ttvpufco.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2ijsdwjwf.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2nymkvvuw.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgdqgvr.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2llortylh.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnksrjic.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrunibf.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhwfkcm.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzyzepbq.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bnyypvmb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwamvpb.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jhyjvcdv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2efcgzoyb.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2qnulnnqm.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdaxvty.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhjurgz.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhenueoc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2idqexoia.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtyhwzi.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtcskyw.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2fpzcgyud.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2jmjpoqqk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jmpickle.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2sirrcvez.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2oircdrsf.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2hefynozt.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2eukwlumz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2tilhrxhk.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpyblvug.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2jnrqjwuq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2twqgasbz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2jrorawug.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdoahcg.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqilvfg.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehsdedtu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtehkmv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2rvghtcmu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2mdorfxoz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwszcsj.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2czxhjncx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tmjsyjxy.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2qwaccfjr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2catpjlih.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2redvuajz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwmtlvh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzscxslz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tahddrpz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eeuujdom.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2obpebhpn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrabwscu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2yiqdqacj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2enjrzkzd.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2skokgcpd.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhklqqsh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcermzwu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2injulfms.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2swmjrsgi.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2cwjsegwn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2bqunmcyr.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2uspttwmm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqnbrfx.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbbtzqu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqaiajs.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2owxopfxp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ymsxgctw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2rppldqwv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2xnqvqsub.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2eflnzuvc.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2neoyzznw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndikghbe.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwwxrfz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2swscsztg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2irzbamab.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpaqzdbz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2aycqrwtx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lafmbeur.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnekfgxb.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2ldkxgitq.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2afhpkgvx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pthulmaw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrcengs.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yziuupyz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2blzxlujz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhlozxt.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqqxbnx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnivhpox.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wvnkqhle.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2gvrxlefl.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhuaply.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2uafpqndr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2pesbxsxh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2sjsjcgao.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uxirolhc.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2qkyupzpr.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfthbus.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2qeltboql.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2nvaaulci.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2xornfknc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvlaolyw.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2qpewgkgl.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhufavf.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2navkwder.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2sscmrzkt.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqhgvpl.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2zmkbpjfl.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmewdtu.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2rotixjdw.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bodolgli.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qxfhsomz.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mfupnbqm.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cihhuzoc.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvlprxv.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ytchunxv.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gaoazpoa.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqlormt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ogzwoyty.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wacplpvv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2fnaadyzn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2whivghoq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2gtlmjlds.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lienshfn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2aappfqmr.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2szinydyg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2uwbiuidk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbartiyb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbopzoz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxowhfap.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxafzqqu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqyzmzn.html


<!-- 参考信息 -->