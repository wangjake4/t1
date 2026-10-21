代发 wailian999

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaobvutph.html

K. JSON 与序列化
来源：http://dali.snrcjt.cn/Article/details/gtssbspapf.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtqkvirdhf.html

[K01] 对象转 JSON 字符串
来源：http://dali.yj20258.top/Article/details/gtrlxbaivu.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhiwuduotai.top/Article/details/gtcbitgzcv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxinkj.top/Article/details/gtepevmdgt.html

JS:   JSON.stringify(obj)
来源：http://dali.jiagoushi.top/Article/details/gtsiiyxonu.html

TS:   JSON.stringify(obj)
来源：http://dali.gogol.net.cn/Article/details/gtbttcislf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yj20258.top/Article/details/gtutvxvxju.html

Go:   json.Marshal(obj)
来源：http://dali.hywenlv.cn/Article/details/gtczvlbkoi.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtugkaokdf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xylfe.cn/Article/details/gtjfulwxib.html

[K02] JSON 字符串转对象
来源：http://dali.hfpthk.cn/Article/details/gtbqpupmgf.html

Py:   json.loads(s)
来源：http://dali.jyoumei.cn/Article/details/gtprnyzjxn.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ybcxt.top/Article/details/gtgjjacnna.html

JS:   JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gtsgsryifw.html

TS:   JSON.parse(s)
来源：http://dali.aibaodan.cn/Article/details/gtdekaemke.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xylfe.cn/Article/details/gtoiwnslma.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cheryme.top/Article/details/gtjbgebskp.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gtrydvanvz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jiagoushi.top/Article/details/gtzcoxsrth.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yangfankeji.com/Article/details/gtwhjdgqyu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sufxvd.cn/Article/details/gtgyhpcumr.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.nwbrower.top/Article/details/gtukyxsqnb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtertlzpli.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpxmhhlpu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gogol.net.cn/Article/details/gtdtfyanbm.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.birdmap.top/Article/details/gtiqbfoxhh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cucudq.cn/Article/details/gteydvgbyk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.aizwys.cn/Article/details/gtimcthszh.html

[K04] 读取 JSON 文件
来源：http://dali.pengpengdd.cyou/Article/details/gtgkunbfaz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.nwbrower.top/Article/details/gtchtxdhqf.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yvedp.cn/Article/details/gttjutashw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xuanzx.com/Article/details/gtaqlymyjy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.snrcjt.cn/Article/details/gtxblthkov.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmjvvbdga.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hnxiangtu.top/Article/details/gtvtnluazw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.bjfxy.top/Article/details/gtarqpkwct.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.dianchejie.cn/Article/details/gtsvajimjg.html

[K05] 深拷贝对象
来源：http://dali.hywenlv.cn/Article/details/gtihrdmihy.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtukzaqwep.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cucudq.cn/Article/details/gtvsxnydnv.html

JS:   structuredClone(obj)
来源：http://dali.yonumen.top/Article/details/gtbydsqrpz.html

TS:   structuredClone(obj)
来源：http://dali.zhengqikj.top/Article/details/gtekrzawqx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sxryk.cn/Article/details/gtiosxpdcm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yj20258.top/Article/details/gtrmyxwsfq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yongpay.top/Article/details/gtjwvtymsd.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.pengpengdd.cyou/Article/details/gtbatrpwje.html

[K06] 解析 URL 查询串
来源：http://dali.snrcjt.cn/Article/details/gtrjmtusdq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jqgufenzy.top/Article/details/gttpgcgvhz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yonumen.top/Article/details/gtrsxdvvqy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuxming.cn/Article/details/gtuvyoywbn.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ivvv.top/Article/details/gtesehjprk.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.svipenyu.cn/Article/details/gtxxlltvrr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.tianlin.xyz/Article/details/gtphxmtmfh.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gtxxrvnljj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvvbaiqrk.html

[K07] 进制转换
来源：http://dali.birdmap.top/Article/details/gtehojoubo.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gthfvbntxy.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhongyouzk.top/Article/details/gtghpisxpy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.meibo888.top/Article/details/gtlwtgaabt.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gtxdpvimmn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpvplkzxt.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cheryme.top/Article/details/gtufhuxnet.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sweek.top/Article/details/gtbxzbmdll.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gtqkrwredj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hywenlv.cn/Article/details/gteefophzx.html

Py:   pickle.dumps(obj)
来源：http://dali.redwolf501.top/Article/details/gtqjkllmed.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnbwqkwui.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.tanke756.top/Article/details/gtyusgjkbl.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.haohaochexian.top/Article/details/gtkdrvyoyc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yangfankeji.com/Article/details/gtjroirkny.html

Go:   encoding/gob
来源：http://dali.316326.xyz/Article/details/gtxoqclvvi.html

Ruby: Marshal.dump(obj)
来源：http://dali.sysykeji.top/Article/details/gtcjclohxh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.sysykeji.top/Article/details/gtoxeazyvw.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtuhyqnhhy.html

L. 网络请求
来源：http://dali.pycfn.com/Article/details/gtqxpmnijf.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtdikpthes.html

[L01] 发送 GET 请求
来源：http://dali.shanyushiyangtech.top/Article/details/gtxioatlbk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyslqwycn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjjxyqxrf.html

JS:   await fetch(url)
来源：http://dali.birdmap.top/Article/details/gtyxzodcym.html

TS:   await fetch(url)
来源：http://dali.guowangkeji.top/Article/details/gtunvkodvw.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cqqwz.cn/Article/details/gtlzkcpiei.html

Go:   resp, err := http.Get(url)
来源：http://dali.pycfn.com/Article/details/gtsluoatti.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yj202588.top/Article/details/gtfypsmidi.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ppjwa.cn/Article/details/gtlmonhefi.html

[L02] 发送 POST JSON
来源：http://dali.yj202588.top/Article/details/gtdzzcohys.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.c1oappe.top/Article/details/gtlmnkrjqw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yongpay.top/Article/details/gtsmryrqnw.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hnqzz.top/Article/details/gtyfrrtvzl.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hnqzz.top/Article/details/gtrwfkawgx.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jianghu66.top/Article/details/gtyujpoqpk.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.dashuyun.cn/Article/details/gtlhhzektd.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.redwolf501.top/Article/details/gtmmqvpvtz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.birdmap.top/Article/details/gttvfzusjj.html

[L03] 设置自定义请求头
来源：http://dali.mhx1999.top/Article/details/gtnwajlqqb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shanyushiyangtech.top/Article/details/gtzznkydua.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.wangdashe.top/Article/details/gtkkqbnocd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.svipenyu.cn/Article/details/gtyoqlqvir.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfnqqthyh.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gotoacloud.top/Article/details/gtvdkljruf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdhljkhny.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsghowitz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ivvv.top/Article/details/gtmsoujxnj.html

[L04] 设置超时
来源：http://dali.cheryme.top/Article/details/gtzxtkhzur.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tian-w.cn/Article/details/gtnyfnanog.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.316326.xyz/Article/details/gtzibgwyvj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shuidangran.top/Article/details/gtmwxrbxzu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhiwuduotai.top/Article/details/gtxgvgrzru.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gtupxrnrqg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.chenjidiqi.icu/Article/details/gtpokvkkag.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ivvv.top/Article/details/gtgjibpmrd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfsgxmozy.html

[L05] 上传文件（multipart）
来源：http://dali.birdmap.top/Article/details/gttfthvtfn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hnxiangtu.top/Article/details/gttlhlwwrd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.wangshuangyany.cn/Article/details/gtymteabvd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gaohongyu789.top/Article/details/gtwffqwoqq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinghuilouyu.cn/Article/details/gtkrvalklq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hongshengwenyu.top/Article/details/gtqakjwgna.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jqgufenzy.top/Article/details/gtbohgzpul.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.316326.xyz/Article/details/gtmerfwxob.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.meibo888.top/Article/details/gtzgtshrnm.html

[L06] 解析响应为 JSON
来源：http://dali.zhoulong.xyz/Article/details/gtwylauinw.html

Py:   resp.json()
来源：http://dali.yueranfly.top/Article/details/gtycvzegxf.html

PHP:  json_decode($body, true);
来源：http://dali.0kj1m.cn/Article/details/gtearfekcx.html

JS:   await resp.json()
来源：http://dali.hnqzz.top/Article/details/gtmcdnarqc.html

TS:   await resp.json()
来源：http://dali.feifeiyinyue.top/Article/details/gtdprgynyh.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yvedp.cn/Article/details/gtubzngvpt.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xziqi.cn/Article/details/gtbjcxyszx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.feifeiyinyue.top/Article/details/gtsqimeynf.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ivvv.top/Article/details/gtybeiyfdo.html

[L07] 处理 HTTP 状态码
来源：http://dali.svipenyu.cn/Article/details/gtvvflflsf.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.fengsongda.top/Article/details/gtvztjhgok.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cashguo.top/Article/details/gtohnxegux.html

JS:   resp.ok;  resp.status
来源：http://dali.wangdashe.top/Article/details/gttkullmxz.html

TS:   resp.ok;  resp.status
来源：http://dali.guannengcc.top/Article/details/gtaglhfamf.html

Java: resp.statusCode()
来源：http://dali.cucudq.cn/Article/details/gtzinvwsuh.html

Go:   resp.StatusCode
来源：http://dali.cqqwz.cn/Article/details/gtezkedaed.html

Ruby: resp.code.to_i
来源：http://dali.zhongyouzk.top/Article/details/gtegwzynyg.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gteeewtpts.html

[L08] 并发请求多个地址
来源：http://dali.xylfe.cn/Article/details/gtstqizmxt.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jlsjyb.cn/Article/details/gtwtmtiabm.html

PHP:  curl_multi_init() 系列
来源：http://dali.cheryme.top/Article/details/gtegqulnxo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgufenzy.top/Article/details/gtauweymof.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tianlin.xyz/Article/details/gtisfbbvgr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nanxinkj.top/Article/details/gtqymbxuys.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zdqjudy.top/Article/details/gttjhuaccb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.snrcjt.cn/Article/details/gtsmfxudfj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.sysykeji.top/Article/details/gtvfntddxf.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtejemesce.html

M. 命令行 / 进程 / 环境
来源：http://dali.pengpengdd.cyou/Article/details/gtvkmhicqx.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gthxpbwyvt.html

[M01] 读取命令行参数
来源：http://dali.snrcjt.cn/Article/details/gtllyiteid.html

Py:   sys.argv[1:]
来源：http://dali.yj20258.top/Article/details/gtuakpdvho.html

PHP:  $argv;  $argc;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnikledlb.html

JS:   process.argv.slice(2)
来源：http://dali.meibo888.top/Article/details/gtchzwhvzh.html

TS:   process.argv.slice(2)
来源：http://dali.0kj1m.cn/Article/details/gtbplzxeux.html

Java: args 数组（main 方法参数）
来源：http://dali.yvedp.cn/Article/details/gtvqnlbmlc.html

Go:   os.Args[1:]
来源：http://dali.316326.xyz/Article/details/gtimayupyw.html

Ruby: ARGV
来源：http://dali.jqgfzy.top/Article/details/gtebokalbf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xylfe.cn/Article/details/gtugiwibli.html

[M02] 读取环境变量
来源：http://dali.tianlin.xyz/Article/details/gtqpgvmheb.html

Py:   os.environ.get("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gthfrhcsxh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbaqabvhf.html

JS:   process.env.HOME
来源：http://dali.bjfxy.top/Article/details/gtgrixlknh.html

TS:   process.env.HOME
来源：http://dali.andypj.xyz/Article/details/gtxkogyvyt.html

Java: System.getenv("HOME")
来源：http://dali.aibaodan.cn/Article/details/gthrzvipcu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.iojbl.cn/Article/details/gtezjzttpt.html

Ruby: ENV["HOME"]
来源：http://dali.gzhubu.top/Article/details/gtbgorfvdd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gzhubu.top/Article/details/gtwokpdpbq.html

[M03] 执行外部命令
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsfdanogi.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ppjwa.cn/Article/details/gtklcvadvf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gogol.net.cn/Article/details/gtryyosycw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthwkeojmy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuxming.cn/Article/details/gtpzeojypa.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gthvsuxryw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.wangshuangyany.cn/Article/details/gtcmrjqapp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhixingplan.top/Article/details/gtndbrjejx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.tanke756.top/Article/details/gtvxqieruz.html

[M04] 获取当前工作目录
来源：http://dali.pengpengdd.cyou/Article/details/gteugjgaiq.html

Py:   os.getcwd()
来源：http://dali.daria6918.cn/Article/details/gthwjuknje.html

PHP:  getcwd();
来源：http://dali.zhengqikj.top/Article/details/gtwzrridzt.html

JS:   process.cwd()
来源：http://dali.yj202588.top/Article/details/gtlladreax.html

TS:   process.cwd()
来源：http://dali.aibaodan.cn/Article/details/gtsodoqxpe.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shangyingyoupin.top/Article/details/gtoiqodjuh.html

Go:   os.Getwd()
来源：http://dali.gaohongyu789.top/Article/details/gtllfstyzi.html

Ruby: Dir.pwd
来源：http://dali.nanxinkj.top/Article/details/gtiocbnmhv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.havefunace.top/Article/details/gtvbxrsyge.html

[M05] 设置退出码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtukbrrvij.html

Py:   sys.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gtmidtheoh.html

PHP:  exit(1);
来源：http://dali.quarkkingdee.top/Article/details/gteetgeeys.html

JS:   process.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtyvxnghns.html

TS:   process.exit(1)
来源：http://dali.fzhhl.top/Article/details/gthpdglhlz.html

Java: System.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gtmqfdsrbo.html

Go:   os.Exit(1)
来源：http://dali.cheryme.top/Article/details/gtkbmxzkbh.html

Ruby: exit 1
来源：http://dali.zdqjudy.top/Article/details/gtbuyspghn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shangyingyoupin.top/Article/details/gthgsyrtfc.html

[M06] 向标准错误输出
来源：http://dali.c1oappe.top/Article/details/gtxaqxupuf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yangfankeji.com/Article/details/gtdnkxtulk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.smart0.xyz/Article/details/gtgddxuzxq.html

JS:   console.error("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdjinnkey.html

TS:   console.error("err")
来源：http://dali.hywenlv.cn/Article/details/gtmomkcaaw.html

Java: System.err.println("err")
来源：http://dali.haohaochexian.top/Article/details/gtiaxvnppa.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.vqdsnc.cn/Article/details/gtypgmfqld.html

Ruby: warn "err"
来源：http://dali.9152youxi.cn/Article/details/gtndhbdrcm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cheryme.top/Article/details/gtmhugwsxh.html

[M07] 判断是否为主入口
来源：http://dali.shzxlz.cn/Article/details/gtpmipazbb.html

Py:   if __name__ == "__main__":
来源：http://dali.andypj.xyz/Article/details/gtgahkptbr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sweek.top/Article/details/gtycgrafpg.html

JS:   require.main === module
来源：http://dali.yuxming.cn/Article/details/gtspsxceuv.html

TS:   require.main === module
来源：http://dali.shangyingyoupin.top/Article/details/gtckxxmduh.html

Java: public static void main(String[] args)
来源：http://dali.316326.xyz/Article/details/gtrmfrlxdp.html

Go:   func main()
来源：http://dali.zycfv.cn/Article/details/gtpcxymmup.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyddegtju.html

C#:   static void Main(string[] args)
来源：http://dali.tian-w.cn/Article/details/gtuttbnjlx.html

[M08] 获取系统与运行时信息
来源：http://dali.yangfankeji.com/Article/details/gtoadsiiht.html

Py:   platform.system();  platform.python_version()
来源：http://dali.nwbrower.top/Article/details/gtepbrghyi.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yuxming.cn/Article/details/gtvmjyillr.html

JS:   process.platform;  process.version
来源：http://dali.birdmap.top/Article/details/gtwpqvyshf.html

TS:   process.platform;  process.version
来源：http://dali.wangdashe.top/Article/details/gtqczrfhix.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.feifeiyinyue.top/Article/details/gtsptatsqt.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.daxiang520.top/Article/details/gtanjerxhd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinqigufen.top/Article/details/gtlfsxivby.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cqqwz.cn/Article/details/gtpdwhumgg.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtznwtamok.html

N. 数据结构与算法
来源：http://dali.ppjwa.cn/Article/details/gtpgqtwgww.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gthmnkmsde.html

[N01] 二分查找（有序数组）
来源：http://dali.tian-w.cn/Article/details/gtbwphlghk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtvhdevwby.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cashguo.top/Article/details/gtwqummftx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hammf.cn/Article/details/gtfyacacgx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tanke756.top/Article/details/gtqeahjnjx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gtrxdtbedg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yj202588.top/Article/details/gtkiluqywi.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cqqwz.cn/Article/details/gtrzoszfyw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtbyzibeng.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.wangdashe.top/Article/details/gtmgefdzmu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj202588.top/Article/details/gtwthkehbl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yuxming.cn/Article/details/gtsguazxux.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ehwqpu.com/Article/details/gtyogrypoo.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnxiangtu.top/Article/details/gtpkocsvwe.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.9152youxi.cn/Article/details/gtodanlsvy.html

Go:   slices.Sort(arr)
来源：http://dali.chenlongwang.top/Article/details/gtthstbjto.html

Ruby: arr.sort
来源：http://dali.wangdashe.top/Article/details/gtmglzvvcr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gzhubu.top/Article/details/gtgdzytfue.html

[N03] 快速排序（分治示例）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkborbxhw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yanxiufei.cn/Article/details/gtzphxvzng.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yj20258.top/Article/details/gtvbknfmop.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhengqikj.top/Article/details/gtsrfoefru.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ivvv.top/Article/details/gtrfzuqvwn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhoulong.xyz/Article/details/gtyarcavro.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xuetiantiany.cn/Article/details/gtjluqzyst.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jianghu66.top/Article/details/gtbpftxmjc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xziqi.cn/Article/details/gtngrfaxed.html

[N04] 斐波那契数列
来源：http://dali.wangdashe.top/Article/details/gtrqfrxzdo.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.wangdashe.top/Article/details/gtkujnswxf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sxryk.cn/Article/details/gtmpcoxgvt.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.mhx1999.top/Article/details/gthcxmlqnw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.fengsongda.top/Article/details/gtafpgseki.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hfpthk.cn/Article/details/gtglyvgdxs.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.sufxvd.cn/Article/details/gtfcehhweo.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.dashuyun.cn/Article/details/gtlpkebbrr.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhoulong.xyz/Article/details/gtqrahycha.html

[N05] 最大公约数
来源：http://dali.hongshengwenyu.top/Article/details/gtdnswswcx.html

Py:   math.gcd(a, b)
来源：http://dali.gogol.net.cn/Article/details/gtmisrwwri.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jinqigufen.top/Article/details/gtoumofvfo.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sxryk.cn/Article/details/gtbcxfmrlg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hammf.cn/Article/details/gtertvsvto.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhengqikj.top/Article/details/gtqlnvyqxq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.daria6918.cn/Article/details/gtiywrtfgo.html

Ruby: a.gcd(b)
来源：http://dali.zhongyouzk.top/Article/details/gtwunkqbvn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.guowangkeji.top/Article/details/gtjownbgso.html

[N06] 判断回文字符串
来源：http://dali.kuanghao11.cn/Article/details/gtwbtknffm.html

Py:   s == s[::-1]
来源：http://dali.0kj1m.cn/Article/details/gtupmipgkl.html

PHP:  $s === strrev($s);
来源：http://dali.dashuyun.cn/Article/details/gtofpktjja.html

JS:   s === [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gtwjwpltzn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gtfnnidlad.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ydzc1.top/Article/details/gtnufqwcls.html

Go:   // 双指针从两端比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqlxeenot.html

Ruby: s == s.reverse
来源：http://dali.zycfv.cn/Article/details/gtzmgzaxli.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.havefunace.top/Article/details/gtdizsnrpt.html

[N07] 两数之和（返回下标）
来源：http://dali.dashuyun.cn/Article/details/gtvilfsudq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sweek.top/Article/details/gtfpqfarha.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.dianchejie.cn/Article/details/gtstxszkfu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sufxvd.cn/Article/details/gtvfzhpvbw.html

TS:   // 手写 Map<string, number>
来源：http://dali.yonumen.top/Article/details/gtyxlyuryi.html

Java: // 手写 HashMap
来源：http://dali.cdnleiting.top/Article/details/gtdublzfpw.html

Go:   // 手写 map[int]int
来源：http://dali.ybcxt.top/Article/details/gtwxoifkxk.html

Ruby: // 手写 Hash
来源：http://dali.yangfankeji.com/Article/details/gtkqmhbypx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ywan-chungtsiang.top/Article/details/gtewpgjllu.html

[N08] 生成全排列
来源：http://dali.hammf.cn/Article/details/gtrkjlkxxq.html

Py:   itertools.permutations(arr)
来源：http://dali.yongpay.top/Article/details/gtfmnqhyvl.html

PHP:  // 手写递归交换
来源：http://dali.fengsongda.top/Article/details/gtnttvvxdc.html

JS:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gtrpgslgqe.html

TS:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gtdncoyrac.html

Java: // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gtuoqkgmmx.html

Go:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gttmcirgop.html

Ruby: arr.permutation.to_a
来源：http://dali.xuanzx.com/Article/details/gtmzzctvxk.html

C#:   // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gtiixwklmx.html


<!-- 参考信息 -->