代发 wailian999

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjujjovo.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2djiqshke.html

JS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxatsjy.html

TS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdajtppt.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjedstr.html

Go:   json.Marshal(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwwofwn.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrpnatq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlamknyg.html

[K02] JSON 字符串转对象
来源：http://dali.zhijiandao.cn/Article/details/gt2zcmivfib.html

Py:   json.loads(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcllhwpx.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhijiandao.cn/Article/details/gt2yslrdwjx.html

JS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2enleqnjh.html

TS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lftekwga.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2paelqgiz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2kswyzbur.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhmrhsld.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2shjzzluw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gt2bggivefy.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2enamqomj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghtehemu.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgkwanms.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tswvwaua.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnqonjm.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gt2tscudbjc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtzpzffu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gt2tpckwyzw.html

[K04] 读取 JSON 文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nhimyviq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2imssuopd.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jesebslb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bsptpbui.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nfaqubvd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2fycvozek.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvekkfv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2txmtvwcy.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tbflxkxz.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ynfbqjai.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucahschk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2llqdmftr.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxildne.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmlomxmn.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gt2nyxuwoer.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gt2pwddrrvp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2bitotyko.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqfagpa.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2qlrngdhp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2rznvzeze.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwuxoxyi.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2qeqiqguf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2drgupvap.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2ejgvrpgf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2epjiiynt.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ovvbewxm.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2xjxfxfpr.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nmkmyade.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfypsdgz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2knxtoxid.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2vngwljdx.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmrqjwqc.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbranjta.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2utapbjiq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykrntapg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzodjfam.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfwjets.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2updoyieh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dazwdmsu.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2msbsnbye.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2wlieqnhm.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2orekmhpi.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2fplhsgke.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xudjjcux.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2hmblmgkv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tuvnkgqf.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2crnfkcls.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2grcyhpux.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2jwzyqjrk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2pezivmqm.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2amibkuez.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvyvucy.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2jipfogpx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhbdchj.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyuoxmoi.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjerabp.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2leertyee.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwzfipt.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2frnnmjqb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2mhhdgioi.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2xjubgfxz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqfghjw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdcrbjf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2npykbnyd.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwsrfipz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2cjguybec.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2tjfvttwf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2zggbkjpe.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmykuqq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2rppryaqh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2lainkvuq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2mdytssls.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzqklse.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2cdalxhqg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2musmlhsc.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2xwybmren.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2uealvgju.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwgrkdqd.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhqumrs.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2lowgwgba.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrftiqj.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzpiqdr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvsyhcb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnicyroe.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2gjpiorlx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2gheaxciy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rocdkthw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzjomnu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdrnmuw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2drleuwws.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qkircixv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2scpvktwv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bddfxnre.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2erfolfcs.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2xzgvhxet.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2uihxjcqu.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2egatkngn.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2vzhwfvqi.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqpiwpu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2sctkzbdg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdrbhtz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2hfavdyfz.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2retaxozn.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2okfupxqn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdoriqq.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2fwlpoptl.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2higvfykr.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2ygoqjquv.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2tecfiqst.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2wpgjwqsr.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnubdvy.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2qplrjswd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2zflnprqz.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2kubfkpol.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wphxpapm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfmyxyy.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2hjuobwyb.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2yywhepks.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqsgwrh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2kchowltb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nlqslpqa.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ehhrbung.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2finijxvp.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zngqgvij.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2rviusulj.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzrmdung.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvqttngh.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnbrekpq.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2kprhuwyi.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2tnsnjxqm.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2gxutgwwm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2mealrqoy.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dqakpzhf.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2knjerahm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdebtowd.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2fjxcvuon.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2hspkdetg.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2qsexpbey.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwfoljoz.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2fshticcm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2kjucoezo.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ymgbsdgg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqcxlij.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrljpha.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2afxchvku.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2uheqlbwv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjygaiq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2dvoyxvpx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2zhnvsrim.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2awwygint.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ievbanwr.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2kcctxrac.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2vxaepeza.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2afumiviq.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2oivkydiz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2vsiktypc.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2vjnuyruw.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqgxrir.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2hikmbujp.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2ugrbguok.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgeheedw.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kaadmetf.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdajvdfo.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqwkpon.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggfkiicv.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2weloyrvv.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmpkxey.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzeviay.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2cofrhqcn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlvcyiqf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2pfevazhb.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2bszyubat.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2syxvohju.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmucguy.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2puxnsykm.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxwkobs.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2trunrhjx.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2npdbwlky.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2yoexxuzi.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mypecghr.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2yvneahub.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2hwkyrgyu.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2enzjpber.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2swgxuphz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2ayedzwyl.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvzdmhq.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjcijuo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2bdlkcxxb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2wugiokxc.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2smmiymjy.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2pxoghbbq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmuyaaur.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2dilckuen.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2xxwoxvym.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2nhoylbmu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xkfoplcc.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2xfkpmxwh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qbyzpdeb.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2pzytgegl.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjpbugi.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzalfopi.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2icmmowof.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2nibabgli.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2stvudill.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cisusrhu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtlfcxx.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpreixoc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2vitzhbwp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhgvixc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2nylcrnzl.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2apgyfwen.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvlaeoxm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqrhkkmw.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kttfrovi.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfynhzw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2gawdbklo.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmyzeqc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2grewvehz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2nqujgsid.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2ijuqvmpz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2enqnoghi.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2amhrbywc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2gquvskez.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2iugawkwx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2zsnekuts.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2uzuqipzw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2srpjmvbw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uffixhwa.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ruyofvgp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tizflptu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2unpviroi.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzexflrc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfzteizr.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzckvdw.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2odtfrita.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkggkove.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdypxddf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrffrdkq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uyubdrsp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2eebmuzvx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpotcmwc.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2epoumxaq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qchptftg.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ccskcokx.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxlyuus.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvluaxs.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2pibemszi.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vbrxcuhx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqqcdrz.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2umoadzmq.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2kccuptpy.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2eslrxxqd.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhyovml.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2slxckbyi.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2uzyjveoa.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbnzrxu.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2yvgfdgco.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrzdgmy.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2drjgbeew.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2pniqgxiw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2dvqwubbp.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqndhny.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cngkjiax.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqddkev.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xjuzzjlb.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2acdggpoh.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2euldqrnt.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gsmxpubd.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2ambgkouu.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2anvaoqxk.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qrljhllx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2roghcooe.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrdggfe.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ysatqlog.html


<!-- 参考信息 -->