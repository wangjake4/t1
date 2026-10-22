代发 wailian999

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtjkfmbrvt.html

K. JSON 与序列化
来源：http://dali.nanxuanxn.top/Article/details/gttkixsraz.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtydsugjwd.html

[K01] 对象转 JSON 字符串
来源：http://dali.ydzc1.top/Article/details/gtjihxopcj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.birdmap.top/Article/details/gtzlwyaxqe.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cucudq.cn/Article/details/gtpdbbictr.html

JS:   JSON.stringify(obj)
来源：http://dali.hnqzz.top/Article/details/gtmteitolg.html

TS:   JSON.stringify(obj)
来源：http://dali.aibaodan.cn/Article/details/gtkshrwyhr.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.iojbl.cn/Article/details/gtlpcxxndv.html

Go:   json.Marshal(obj)
来源：http://dali.jqgfzy.top/Article/details/gtryqhjfxp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.daria6918.cn/Article/details/gtsdxtrxhx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtzedojfoi.html

[K02] JSON 字符串转对象
来源：http://dali.shuidangran.top/Article/details/gtfzrwltar.html

Py:   json.loads(s)
来源：http://dali.kuanghao11.cn/Article/details/gtjedoxpgm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xuetiantiany.cn/Article/details/gtywejcggf.html

JS:   JSON.parse(s)
来源：http://dali.andypj.xyz/Article/details/gtvkhfvsvf.html

TS:   JSON.parse(s)
来源：http://dali.0kj1m.cn/Article/details/gthitdjcfs.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jlsjyb.cn/Article/details/gtrmxaleeh.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yj20258.top/Article/details/gtltvmvhsh.html

Ruby: JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gtivgfvdyt.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yuxming.cn/Article/details/gtkgdgqjte.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ppjwa.cn/Article/details/gtiifxgzjp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shanyushiyangtech.top/Article/details/gtatvdflyk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtubgaoask.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jlsjyb.cn/Article/details/gthdhkthvr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.fengsongda.top/Article/details/gtatgyebit.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtfjxaflbn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hysaishi.cn/Article/details/gtcoowjpcc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtvxylcwzw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.meibo888.top/Article/details/gtjqznfojv.html

[K04] 读取 JSON 文件
来源：http://dali.sufxvd.cn/Article/details/gtyzfubrmc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cheryme.top/Article/details/gtqtwrqonl.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yuanzhike.top/Article/details/gtufnqvjuw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.birdmap.top/Article/details/gtcwnbsbzw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoniqkifr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.iojbl.cn/Article/details/gtzzlmtthn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yj20258.top/Article/details/gtlxwyeqwx.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.dashuyun.cn/Article/details/gtypedunmt.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.daxiang520.top/Article/details/gthvozivsg.html

[K05] 深拷贝对象
来源：http://dali.fzhhl.top/Article/details/gtpzkbwvrk.html

Py:   copy.deepcopy(obj)
来源：http://dali.chenlongwang.top/Article/details/gtzghhqedm.html

PHP:  unserialize(serialize($obj));
来源：http://dali.chenzaomai.com/Article/details/gtdybnynyr.html

JS:   structuredClone(obj)
来源：http://dali.tianlin.xyz/Article/details/gtjuaebdxa.html

TS:   structuredClone(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtbxcdfyxv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sufxvd.cn/Article/details/gtwmzjafsi.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gotoacloud.top/Article/details/gtcfwfohvd.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ppjwa.cn/Article/details/gttjawhsms.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gzhubu.top/Article/details/gtnawylqke.html

[K06] 解析 URL 查询串
来源：http://dali.hnxiangtu.top/Article/details/gtmlnwwzmz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ivvv.top/Article/details/gtxomnltpv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.chenzaomai.com/Article/details/gtpchmpxnv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.haohaochexian.top/Article/details/gtinillgrd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gtoxtfffcx.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.dashuyun.cn/Article/details/gteiwbenyo.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jyoumei.cn/Article/details/gtcljiqcfi.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ehwqpu.com/Article/details/gtdlfoyxlh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.sysykeji.top/Article/details/gtwpaxfayl.html

[K07] 进制转换
来源：http://dali.ppjwa.cn/Article/details/gtallofugs.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtdcabzzem.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shangyingyoupin.top/Article/details/gtmnzmnkuv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gtorfqmcxb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gtydqxtjjv.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gtivmgmphr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gaohongyu789.top/Article/details/gtnnhgqiqi.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ydzc1.top/Article/details/gtlbiyaxno.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtzgiozgmq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cashguo.top/Article/details/gtekydptdu.html

Py:   pickle.dumps(obj)
来源：http://dali.daxiang520.top/Article/details/gtpyobbymh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sweek.top/Article/details/gtwvmrrtfg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gaohongyu789.top/Article/details/gtagnuiktn.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.9152youxi.cn/Article/details/gteepjkvhd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xinyue.icu/Article/details/gtfqrupmwo.html

Go:   encoding/gob
来源：http://dali.316326.xyz/Article/details/gtsunuolch.html

Ruby: Marshal.dump(obj)
来源：http://dali.redwolf501.top/Article/details/gtryqltidz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.chenzaomai.com/Article/details/gtoexwwlbd.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gttqjieanb.html

L. 网络请求
来源：http://dali.zhengqikj.top/Article/details/gtkginklmk.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtudipqcrz.html

[L01] 发送 GET 请求
来源：http://dali.wangdashe.top/Article/details/gtueuwyyxf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yj202588.top/Article/details/gtdspggigd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cashguo.top/Article/details/gtfnpafvwh.html

JS:   await fetch(url)
来源：http://dali.yanxiufei.cn/Article/details/gtewxiperj.html

TS:   await fetch(url)
来源：http://dali.iojbl.cn/Article/details/gtuileruhs.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.wangdashe.top/Article/details/gtzpqsvlja.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gtxoxijghx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.havefunace.top/Article/details/gtbljwaqpz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.tianlin.xyz/Article/details/gtkswhjrxp.html

[L02] 发送 POST JSON
来源：http://dali.jianghu66.top/Article/details/gtelwwdpwn.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cdnleiting.top/Article/details/gtbzzspshe.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.snrcjt.cn/Article/details/gtbnedahdi.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ehwqpu.com/Article/details/gtnlkpfwen.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuanzhike.top/Article/details/gtwhhzusnn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.havefunace.top/Article/details/gtykxstsqt.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xuanzx.com/Article/details/gtutvhyoxz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.fzhhl.top/Article/details/gtiwgmizfv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jyoumei.cn/Article/details/gtqkaumhjy.html

[L03] 设置自定义请求头
来源：http://dali.guowangkeji.top/Article/details/gtvovhnfah.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhixingplan.top/Article/details/gtiivfxueq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.smart0.xyz/Article/details/gtdbgwjrpg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.feifeiyinyue.top/Article/details/gtimxwqsiu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daria6918.cn/Article/details/gtxugyhene.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.iojbl.cn/Article/details/gttjnebrrq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtshajxrcp.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gaohongyu789.top/Article/details/gtmmoaedcz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.feifeiyinyue.top/Article/details/gtgmsameow.html

[L04] 设置超时
来源：http://dali.ybcxt.top/Article/details/gtdvhmrufe.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jqgfzy.top/Article/details/gtlqncrlld.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yvedp.cn/Article/details/gtmwkbitmu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shzxlz.cn/Article/details/gtyaqmfbxd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.0kj1m.cn/Article/details/gtfdxkcder.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.nanxuanxn.top/Article/details/gtdoxlmhtv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yvedp.cn/Article/details/gthebbbfqh.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ivvv.top/Article/details/gttcoguqxd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinghuilouyu.cn/Article/details/gtpsamppxi.html

[L05] 上传文件（multipart）
来源：http://dali.jqgfzy.top/Article/details/gtxctvakxx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.iojbl.cn/Article/details/gtgpvtrzam.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.daria6918.cn/Article/details/gtvyuwiuxq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jlsjyb.cn/Article/details/gtshmjobji.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.kuanghao11.cn/Article/details/gtgtnawvfl.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.pengpengdd.cyou/Article/details/gtffwpmpto.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.meibo888.top/Article/details/gtsbaiivyx.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinyuanbaomall.cn/Article/details/gttjohavpu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cheryme.top/Article/details/gtmavgtvhh.html

[L06] 解析响应为 JSON
来源：http://dali.9152youxi.cn/Article/details/gtqzupqpok.html

Py:   resp.json()
来源：http://dali.jqgufenzy.top/Article/details/gttukugkzb.html

PHP:  json_decode($body, true);
来源：http://dali.xinyue.icu/Article/details/gthgwamanb.html

JS:   await resp.json()
来源：http://dali.feifeiyinyue.top/Article/details/gtlqnkznod.html

TS:   await resp.json()
来源：http://dali.daria6918.cn/Article/details/gtiuvpbfbx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ppjwa.cn/Article/details/gtjxnvnkbk.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jqgufenzy.top/Article/details/gtpjovqsjc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.fengsongda.top/Article/details/gtlrndlhhx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gogol.net.cn/Article/details/gtiovpropr.html

[L07] 处理 HTTP 状态码
来源：http://dali.shanyushiyangtech.top/Article/details/gtogqhfdrf.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ehwqpu.com/Article/details/gtfcppwwdr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xuanzx.com/Article/details/gtdyivhpeb.html

JS:   resp.ok;  resp.status
来源：http://dali.jlsjyb.cn/Article/details/gtwrpxhvug.html

TS:   resp.ok;  resp.status
来源：http://dali.yangfankeji.com/Article/details/gtzlwsspsx.html

Java: resp.statusCode()
来源：http://dali.tianlin.xyz/Article/details/gtrtvrihez.html

Go:   resp.StatusCode
来源：http://dali.sxryk.cn/Article/details/gtbhijefmi.html

Ruby: resp.code.to_i
来源：http://dali.tian-w.cn/Article/details/gttonvtyhg.html

C#:   (int)resp.StatusCode
来源：http://dali.sufxvd.cn/Article/details/gtegmfdsdc.html

[L08] 并发请求多个地址
来源：http://dali.yuxming.cn/Article/details/gtznapmhec.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.guowangkeji.top/Article/details/gtcmxuzvts.html

PHP:  curl_multi_init() 系列
来源：http://dali.xuetiantiany.cn/Article/details/gtiifqaqqg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gogol.net.cn/Article/details/gtbkchpvnm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.haohaochexian.top/Article/details/gtgpigvkvi.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gaohongyu789.top/Article/details/gtrasxcjpp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hnxiangtu.top/Article/details/gtppxkfhzv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yuanzhike.top/Article/details/gtiamfhjgg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gtwzilqisn.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtbzamgkje.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhoulong.xyz/Article/details/gtoureklkl.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtuvuhclli.html

[M01] 读取命令行参数
来源：http://dali.aibaodan.cn/Article/details/gtwcmtdiqe.html

Py:   sys.argv[1:]
来源：http://dali.zhengqikj.top/Article/details/gtlysjwnlw.html

PHP:  $argv;  $argc;
来源：http://dali.jqgufenzy.top/Article/details/gtkwbiviyk.html

JS:   process.argv.slice(2)
来源：http://dali.cucudq.cn/Article/details/gtwxoqbvmt.html

TS:   process.argv.slice(2)
来源：http://dali.yj20258888.top/Article/details/gtamvqwgbl.html

Java: args 数组（main 方法参数）
来源：http://dali.havefunace.top/Article/details/gtlnwrunmr.html

Go:   os.Args[1:]
来源：http://dali.mhx1999.top/Article/details/gtkijoaias.html

Ruby: ARGV
来源：http://dali.pengpengdd.cyou/Article/details/gtwpqztxin.html

C#:   args 数组（Main 方法参数）
来源：http://dali.fengsongda.top/Article/details/gtepeyeczk.html

[M02] 读取环境变量
来源：http://dali.shzxlz.cn/Article/details/gtnxivayih.html

Py:   os.environ.get("HOME")
来源：http://dali.zdqjudy.top/Article/details/gtqonhegqg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shangyingyoupin.top/Article/details/gtqkmcjkiz.html

JS:   process.env.HOME
来源：http://dali.hnxiangtu.top/Article/details/gtowcdxenm.html

TS:   process.env.HOME
来源：http://dali.shzxlz.cn/Article/details/gtzylbkyqw.html

Java: System.getenv("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gtsjfhjjgy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenlongwang.top/Article/details/gtqnexudiv.html

Ruby: ENV["HOME"]
来源：http://dali.jiagoushi.top/Article/details/gtcrzatoau.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sweek.top/Article/details/gtaubwntup.html

[M03] 执行外部命令
来源：http://dali.havefunace.top/Article/details/gtcdyvdjhy.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtybsaraay.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gaohongyu789.top/Article/details/gtusawypkq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yueranfly.top/Article/details/gttupmbueg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhiwuduotai.top/Article/details/gtqtqkvmof.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.andypj.xyz/Article/details/gtwopldfhk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.pycfn.com/Article/details/gteyvdgddc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cdnleiting.top/Article/details/gtpmstijat.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jqgfzy.top/Article/details/gtmewzhymq.html

[M04] 获取当前工作目录
来源：http://dali.kuanghao11.cn/Article/details/gtenmbxuik.html

Py:   os.getcwd()
来源：http://dali.yvedp.cn/Article/details/gtuxhjqigu.html

PHP:  getcwd();
来源：http://dali.hysaishi.cn/Article/details/gtcndzeewf.html

JS:   process.cwd()
来源：http://dali.shangyingyoupin.top/Article/details/gtnjkuorba.html

TS:   process.cwd()
来源：http://dali.gotoacloud.top/Article/details/gtvnecptva.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.daxiang520.top/Article/details/gtcmqowdld.html

Go:   os.Getwd()
来源：http://dali.quarkkingdee.top/Article/details/gtwhziqwta.html

Ruby: Dir.pwd
来源：http://dali.pengpengdd.cyou/Article/details/gtyryybtov.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.dashuyun.cn/Article/details/gtpzgqkvjt.html

[M05] 设置退出码
来源：http://dali.sweek.top/Article/details/gtlhmuezqm.html

Py:   sys.exit(1)
来源：http://dali.xylfe.cn/Article/details/gtsrtynvno.html

PHP:  exit(1);
来源：http://dali.gotoacloud.top/Article/details/gtcvpzjipr.html

JS:   process.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gtouqzclfn.html

TS:   process.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtqcozsbsg.html

Java: System.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gthctozcgk.html

Go:   os.Exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthqeyywso.html

Ruby: exit 1
来源：http://dali.chenjidiqi.icu/Article/details/gthkubeyrc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.nanxinkj.top/Article/details/gtlgrhxpxc.html

[M06] 向标准错误输出
来源：http://dali.yueranfly.top/Article/details/gthjiuwyhp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhixingplan.top/Article/details/gtkmgteazv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.9152youxi.cn/Article/details/gtenlvvnhu.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gtekxrrplw.html

TS:   console.error("err")
来源：http://dali.xuanzx.com/Article/details/gtgljhtiod.html

Java: System.err.println("err")
来源：http://dali.sxryk.cn/Article/details/gtkctowuqw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.dianchejie.cn/Article/details/gtvvyttqsa.html

Ruby: warn "err"
来源：http://dali.aizwys.cn/Article/details/gtawfxalsu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jyoumei.cn/Article/details/gtsvdyqpez.html

[M07] 判断是否为主入口
来源：http://dali.zycfv.cn/Article/details/gtmdbxupqy.html

Py:   if __name__ == "__main__":
来源：http://dali.yuanzhike.top/Article/details/gtoerdkfvt.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hnxiangtu.top/Article/details/gtvgatslwv.html

JS:   require.main === module
来源：http://dali.ybcxt.top/Article/details/gtmpjsgbsp.html

TS:   require.main === module
来源：http://dali.dashuyun.cn/Article/details/gtfqodezas.html

Java: public static void main(String[] args)
来源：http://dali.ppjwa.cn/Article/details/gtydlvhcte.html

Go:   func main()
来源：http://dali.gogol.net.cn/Article/details/gtbeospuru.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.mhx1999.top/Article/details/gtxifpjheq.html

C#:   static void Main(string[] args)
来源：http://dali.cucudq.cn/Article/details/gtkgsoektz.html

[M08] 获取系统与运行时信息
来源：http://dali.birdmap.top/Article/details/gtfaqsrpyg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.c1oappe.top/Article/details/gtnzpcleik.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.mhx1999.top/Article/details/gtiywbtsrd.html

JS:   process.platform;  process.version
来源：http://dali.aibaodan.cn/Article/details/gtcnixyshp.html

TS:   process.platform;  process.version
来源：http://dali.zhiwuduotai.top/Article/details/gtcepurrst.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ivvv.top/Article/details/gtntqnfumi.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinqigfzy.top/Article/details/gtzswwmgmd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.guowangkeji.top/Article/details/gtulblijhb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sufxvd.cn/Article/details/gttazaybkq.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtwrctdsjd.html

N. 数据结构与算法
来源：http://dali.yonumen.top/Article/details/gtfyslvlmk.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtcwsmgsal.html

[N01] 二分查找（有序数组）
来源：http://dali.zhixingplan.top/Article/details/gtpuvmntpw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbkfvlxim.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nwbrower.top/Article/details/gtsphpkmkj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shzxlz.cn/Article/details/gteitsfaka.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aibaodan.cn/Article/details/gtfyxwhruk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yongpay.top/Article/details/gttmhljmrm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gtiegietzm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrcftszdq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtzslfnixe.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtllpgwdqp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cheryme.top/Article/details/gttemrerqv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jqgfzy.top/Article/details/gtxdhyxgaj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.0kj1m.cn/Article/details/gtoibnbbnk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxmjqwndr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkkgayuwg.html

Go:   slices.Sort(arr)
来源：http://dali.hysaishi.cn/Article/details/gtyjtorpqs.html

Ruby: arr.sort
来源：http://dali.jiagoushi.top/Article/details/gtxpkpiome.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shangyingyoupin.top/Article/details/gtazlbnvsm.html

[N03] 快速排序（分治示例）
来源：http://dali.birdmap.top/Article/details/gtxsuokdlw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jlsjyb.cn/Article/details/gtdjivpvxg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.fengsongda.top/Article/details/gtzuggkokr.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.kuanghao11.cn/Article/details/gtofaaxjqg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.svipenyu.cn/Article/details/gtbcvsqmzf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jinqigfzy.top/Article/details/gtvakpfmsm.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinqigfzy.top/Article/details/gtzsfriesv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yj20258888.top/Article/details/gtzgfbhdob.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jqgufenzy.top/Article/details/gtyjjrtrni.html

[N04] 斐波那契数列
来源：http://dali.yj202588.top/Article/details/gtabyvmmsi.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcwlrnmkz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ydzc1.top/Article/details/gtckkyiarq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgpiywjxl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jyoumei.cn/Article/details/gtwgivmjuq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.pycfn.com/Article/details/gtnodalqou.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.meibo888.top/Article/details/gtdbprwxrh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sweek.top/Article/details/gtixbtacof.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.nanxuanxn.top/Article/details/gthpndajcs.html

[N05] 最大公约数
来源：http://dali.jqgufenzy.top/Article/details/gtlqhprieu.html

Py:   math.gcd(a, b)
来源：http://dali.316326.xyz/Article/details/gtsakyvdhp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.wangdashe.top/Article/details/gtzztqwyai.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.birdmap.top/Article/details/gtzbjhkxrt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigfzy.top/Article/details/gtpakgyihd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.andypj.xyz/Article/details/gtbqdtfiul.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ybcxt.top/Article/details/gtdckjrqon.html

Ruby: a.gcd(b)
来源：http://dali.jinqigufen.top/Article/details/gtecwxgvuh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.dashuyun.cn/Article/details/gtdtqhzyao.html

[N06] 判断回文字符串
来源：http://dali.fengsongda.top/Article/details/gtfcznxjfh.html

Py:   s == s[::-1]
来源：http://dali.chenzaomai.com/Article/details/gtlcbotlms.html

PHP:  $s === strrev($s);
来源：http://dali.xylfe.cn/Article/details/gtogghzygz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yonumen.top/Article/details/gturiokowd.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gtkfmghtef.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.andypj.xyz/Article/details/gtnlokyglr.html

Go:   // 双指针从两端比较
来源：http://dali.chenzaomai.com/Article/details/gtydvkbfov.html

Ruby: s == s.reverse
来源：http://dali.daxiang520.top/Article/details/gtoqudzahw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xziqi.cn/Article/details/gtyswposqw.html

[N07] 两数之和（返回下标）
来源：http://dali.chenzaomai.com/Article/details/gtlawwgywb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.nanxuanxn.top/Article/details/gtcufoltxi.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhiwuduotai.top/Article/details/gtexnctled.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.aibaodan.cn/Article/details/gtltvcumxh.html

TS:   // 手写 Map<string, number>
来源：http://dali.vqdsnc.cn/Article/details/gtakjvlltc.html

Java: // 手写 HashMap
来源：http://dali.hfpthk.cn/Article/details/gtsqkifvgs.html

Go:   // 手写 map[int]int
来源：http://dali.yj202588.top/Article/details/gtbvnnjfpq.html

Ruby: // 手写 Hash
来源：http://dali.sysykeji.top/Article/details/gtebzjkwrz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.pycfn.com/Article/details/gtikobnnmy.html

[N08] 生成全排列
来源：http://dali.zhongyouzk.top/Article/details/gtppfmgotl.html

Py:   itertools.permutations(arr)
来源：http://dali.yonumen.top/Article/details/gtwdrqxfeh.html

PHP:  // 手写递归交换
来源：http://dali.dianchejie.cn/Article/details/gthedvadwc.html

JS:   // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gtoepmcuvi.html

TS:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gtuvhrqeet.html

Java: // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gthmdhwkcq.html

Go:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gtzicyjsft.html

Ruby: arr.permutation.to_a
来源：http://dali.gotoacloud.top/Article/details/gtmoxiyghp.html

C#:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gtacuzxcnm.html


<!-- 参考信息 -->