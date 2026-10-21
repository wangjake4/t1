代发 wailian999

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.c1oappe.top/Article/details/gtlngjftwg.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jqgufenzy.top/Article/details/gtbdgqdjyz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cdnleiting.top/Article/details/gtcnevbpzd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtobgduegx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jyoumei.cn/Article/details/gtexvtsvte.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gzhubu.top/Article/details/gtpbfceedu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shanyushiyangtech.top/Article/details/gtzlqtxduj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenzaomai.com/Article/details/gtdwzfvfdv.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtpiymigav.html

K. JSON 与序列化
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiyszamey.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtyuuczvvl.html

[K01] 对象转 JSON 字符串
来源：http://dali.c1oappe.top/Article/details/gtjtwyufvp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ybcxt.top/Article/details/gtpuawbblh.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.chenlongwang.top/Article/details/gtdkmrrgmc.html

JS:   JSON.stringify(obj)
来源：http://dali.daxiang520.top/Article/details/gthqqjuzez.html

TS:   JSON.stringify(obj)
来源：http://dali.dianchejie.cn/Article/details/gtknxdwkej.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gogol.net.cn/Article/details/gtufhjnfak.html

Go:   json.Marshal(obj)
来源：http://dali.chenlongwang.top/Article/details/gtnjsjhzah.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.c1oappe.top/Article/details/gtjomvivdr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.aibaodan.cn/Article/details/gtjnupvndl.html

[K02] JSON 字符串转对象
来源：http://dali.zhoulong.xyz/Article/details/gtcktlgtbv.html

Py:   json.loads(s)
来源：http://dali.xuanzx.com/Article/details/gtrhcwcwzn.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.nanxinkj.top/Article/details/gtmhhbdudb.html

JS:   JSON.parse(s)
来源：http://dali.xuanzx.com/Article/details/gtrbuyasdg.html

TS:   JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gtqpafkuol.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.meibo888.top/Article/details/gtomnpyivn.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.fengsongda.top/Article/details/gtziliidwa.html

Ruby: JSON.parse(s)
来源：http://dali.nwbrower.top/Article/details/gtygdhcyfc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hysaishi.cn/Article/details/gtsoudrzvf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yueranfly.top/Article/details/gtqloycrfj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.andypj.xyz/Article/details/gtlzaooinw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhongyouzk.top/Article/details/gtnbgkmebg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hysaishi.cn/Article/details/gtsdwppbpk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sweek.top/Article/details/gttnashybv.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yuxming.cn/Article/details/gtfmawwkvj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.c1oappe.top/Article/details/gthlqvymax.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtitwopajf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhongyouzk.top/Article/details/gtdxqfsqry.html

[K04] 读取 JSON 文件
来源：http://dali.wangshuangyany.cn/Article/details/gtbrtowwjg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.snrcjt.cn/Article/details/gtlmkacwvt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.aibaodan.cn/Article/details/gtfpzhhxgt.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ppjwa.cn/Article/details/gtjneknijs.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daria6918.cn/Article/details/gtgtrffjnw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yueranfly.top/Article/details/gtqcghkakf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.9152youxi.cn/Article/details/gtaqjiwses.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.nwbrower.top/Article/details/gtaivlqpgy.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jlsjyb.cn/Article/details/gtyatcanod.html

[K05] 深拷贝对象
来源：http://dali.ydzc1.top/Article/details/gtbotahfdg.html

Py:   copy.deepcopy(obj)
来源：http://dali.tian-w.cn/Article/details/gtcxwylpvm.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhongyouzk.top/Article/details/gttwvczdor.html

JS:   structuredClone(obj)
来源：http://dali.jqgfzy.top/Article/details/gtgwpxfwse.html

TS:   structuredClone(obj)
来源：http://dali.jianghu66.top/Article/details/gtxqcaiibc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmxgakmae.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaelibaue.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.kuanghao11.cn/Article/details/gtjpakuklm.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jiagoushi.top/Article/details/gthzwpyibv.html

[K06] 解析 URL 查询串
来源：http://dali.pycfn.com/Article/details/gtofxhhdkm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sysykeji.top/Article/details/gtwmnnresi.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xuetiantiany.cn/Article/details/gtkfebclxw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hammf.cn/Article/details/gtbmbxajgw.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.quarkkingdee.top/Article/details/gtmwoprudp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yj20258.top/Article/details/gttodxzbuo.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gtwbwsvjwg.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jiagoushi.top/Article/details/gtreshkkrv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.nwbrower.top/Article/details/gttlokuien.html

[K07] 进制转换
来源：http://dali.nanxuanxn.top/Article/details/gthasmjfsf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tanke756.top/Article/details/gtlqnbcklo.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhongyouzk.top/Article/details/gtftvqzhgx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtrvmdhzsd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gtrmlststn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtsctxgfsw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.snrcjt.cn/Article/details/gtspopzojl.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hysaishi.cn/Article/details/gtemnxxqqk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gtrvgukmvj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.aibaodan.cn/Article/details/gthzcwuinv.html

Py:   pickle.dumps(obj)
来源：http://dali.cqqwz.cn/Article/details/gtcdqbgbee.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.dashuyun.cn/Article/details/gtdwlkoybm.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gtyznkujxl.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoytlwhct.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yanxiufei.cn/Article/details/gtyforwbzu.html

Go:   encoding/gob
来源：http://dali.vqdsnc.cn/Article/details/gtwyirmnek.html

Ruby: Marshal.dump(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gthtlqgmsq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.dashuyun.cn/Article/details/gtjvnncxmx.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gttirynhrt.html

L. 网络请求
来源：http://dali.shanyushiyangtech.top/Article/details/gtncvvvisd.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtdpyxiyux.html

[L01] 发送 GET 请求
来源：http://dali.ehwqpu.com/Article/details/gtgifjmqef.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.iojbl.cn/Article/details/gtktxdjzup.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.quarkkingdee.top/Article/details/gtbaymjqos.html

JS:   await fetch(url)
来源：http://dali.jqgfzy.top/Article/details/gthnturlxz.html

TS:   await fetch(url)
来源：http://dali.xuanzx.com/Article/details/gtzcdtfneg.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ehwqpu.com/Article/details/gtazsjsamm.html

Go:   resp, err := http.Get(url)
来源：http://dali.yangfankeji.com/Article/details/gtyotkpdfe.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jianghu66.top/Article/details/gtldjzkmuj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthyobtrii.html

[L02] 发送 POST JSON
来源：http://dali.haohaochexian.top/Article/details/gtpankpgmo.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxmiymjvc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.smart0.xyz/Article/details/gtgypkczsm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yangfankeji.com/Article/details/gtdwwpqjem.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nanxuanxn.top/Article/details/gtawpaqiwp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenlongwang.top/Article/details/gtgbsfbpce.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hfpthk.cn/Article/details/gtxfvrkeuz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.chenlongwang.top/Article/details/gtefsgjlpu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gotoacloud.top/Article/details/gtwnjrmxcw.html

[L03] 设置自定义请求头
来源：http://dali.zhongyouzk.top/Article/details/gtdbtqefwc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.daria6918.cn/Article/details/gtdpzokpzj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.0kj1m.cn/Article/details/gtamsbbhaq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.haohaochexian.top/Article/details/gtxofmxmvc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sweek.top/Article/details/gtbeeosfvt.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yueranfly.top/Article/details/gtihooemnf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hnqzz.top/Article/details/gtjgflkeuh.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.kuanghao11.cn/Article/details/gtrlmgfovv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.9152youxi.cn/Article/details/gttdkxgugd.html

[L04] 设置超时
来源：http://dali.xuetiantiany.cn/Article/details/gtffjysgjk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hammf.cn/Article/details/gtntmdvnsl.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.nanxuanxn.top/Article/details/gtqijqzarw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangshuangyany.cn/Article/details/gtqzwfcnit.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jianghu66.top/Article/details/gthtjqriyz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hysaishi.cn/Article/details/gtcawhvyax.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.tianlin.xyz/Article/details/gthajpprsa.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.birdmap.top/Article/details/gtzgtiapdu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.birdmap.top/Article/details/gtqwlulgxj.html

[L05] 上传文件（multipart）
来源：http://dali.mhx1999.top/Article/details/gtxckyevnk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.dianchejie.cn/Article/details/gtrfdncikh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cdnleiting.top/Article/details/gtxidxqgsj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhiwuduotai.top/Article/details/gtfluhuxtr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.daria6918.cn/Article/details/gtldelpiel.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gzhubu.top/Article/details/gtisclmvrx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.nanxinkj.top/Article/details/gtxkgfeieh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ydzc1.top/Article/details/gtygtwzqcl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.c1oappe.top/Article/details/gtvbirdudu.html

[L06] 解析响应为 JSON
来源：http://dali.shuidangran.top/Article/details/gtwadbzmfj.html

Py:   resp.json()
来源：http://dali.hongshengwenyu.top/Article/details/gtqnswuxya.html

PHP:  json_decode($body, true);
来源：http://dali.wangshuangyany.cn/Article/details/gtlwdwgchd.html

JS:   await resp.json()
来源：http://dali.feifeiyinyue.top/Article/details/gtgbjyrxqd.html

TS:   await resp.json()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvzalmzkd.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yueranfly.top/Article/details/gtmmraoakz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.tianlin.xyz/Article/details/gtfkilljqb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jqgfzy.top/Article/details/gtwgtsrheu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shanyushiyangtech.top/Article/details/gtcbwoevzi.html

[L07] 处理 HTTP 状态码
来源：http://dali.ybcxt.top/Article/details/gtalsiilmq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.0kj1m.cn/Article/details/gtwdwycpqx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gogol.net.cn/Article/details/gthkcgwgey.html

JS:   resp.ok;  resp.status
来源：http://dali.sysykeji.top/Article/details/gtmzkgllpa.html

TS:   resp.ok;  resp.status
来源：http://dali.zhongyouzk.top/Article/details/gtgzwwfcrd.html

Java: resp.statusCode()
来源：http://dali.shangyingyoupin.top/Article/details/gtgmqixbpa.html

Go:   resp.StatusCode
来源：http://dali.smart0.xyz/Article/details/gtuvcvfnjl.html

Ruby: resp.code.to_i
来源：http://dali.xinyue.icu/Article/details/gtpjjayisd.html

C#:   (int)resp.StatusCode
来源：http://dali.sysykeji.top/Article/details/gtnvzpfnga.html

[L08] 并发请求多个地址
来源：http://dali.ybcxt.top/Article/details/gtlhdhwcps.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shuidangran.top/Article/details/gtsusuanrk.html

PHP:  curl_multi_init() 系列
来源：http://dali.guannengcc.top/Article/details/gtpshpukyn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hammf.cn/Article/details/gtlhoryuyn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sysykeji.top/Article/details/gtxvvgxsfo.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gotoacloud.top/Article/details/gtmqxelcch.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cqqwz.cn/Article/details/gtjzsiowxx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.redwolf501.top/Article/details/gtzmgzzqsb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.c1oappe.top/Article/details/gtrqokzgya.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtimsccxlw.html

M. 命令行 / 进程 / 环境
来源：http://dali.tian-w.cn/Article/details/gtuygmmfbl.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtsyajtejl.html

[M01] 读取命令行参数
来源：http://dali.kuanghao11.cn/Article/details/gthsjwgcbg.html

Py:   sys.argv[1:]
来源：http://dali.havefunace.top/Article/details/gtjvpohuos.html

PHP:  $argv;  $argc;
来源：http://dali.zdqjudy.top/Article/details/gtxnuqbjfy.html

JS:   process.argv.slice(2)
来源：http://dali.nanxinkj.top/Article/details/gtjxjdrxlp.html

TS:   process.argv.slice(2)
来源：http://dali.0kj1m.cn/Article/details/gtyfcdlheb.html

Java: args 数组（main 方法参数）
来源：http://dali.jyoumei.cn/Article/details/gtrchvsmxl.html

Go:   os.Args[1:]
来源：http://dali.dianchejie.cn/Article/details/gtxnvlwwbp.html

Ruby: ARGV
来源：http://dali.sxryk.cn/Article/details/gtoatzugto.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shuidangran.top/Article/details/gtvsbxtoda.html

[M02] 读取环境变量
来源：http://dali.yj20258888.top/Article/details/gtefohnaxd.html

Py:   os.environ.get("HOME")
来源：http://dali.snrcjt.cn/Article/details/gtbtyanlzv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinqigfzy.top/Article/details/gtnrdrkkvo.html

JS:   process.env.HOME
来源：http://dali.smart0.xyz/Article/details/gtcnbdxlev.html

TS:   process.env.HOME
来源：http://dali.yj20258888.top/Article/details/gtjvxjmqcr.html

Java: System.getenv("HOME")
来源：http://dali.xziqi.cn/Article/details/gtfwacwigo.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ydzc1.top/Article/details/gtsjhzhyxm.html

Ruby: ENV["HOME"]
来源：http://dali.aizwys.cn/Article/details/gtrxbtqzks.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cucudq.cn/Article/details/gtjvmlgthu.html

[M03] 执行外部命令
来源：http://dali.jinghuilouyu.cn/Article/details/gtxjpvyaad.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hfpthk.cn/Article/details/gtrrnflspx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hywenlv.cn/Article/details/gthtzooplw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhongyouzk.top/Article/details/gtjmrptvhk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.kuanghao11.cn/Article/details/gthormkiht.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.vqdsnc.cn/Article/details/gtmuawpiad.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.meibo888.top/Article/details/gtpgittjtk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.meibo888.top/Article/details/gtizrjrsri.html

C#:   Process.Start("ls", "-l");
来源：http://dali.svipenyu.cn/Article/details/gtgeqlhdmt.html

[M04] 获取当前工作目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqhmbuzub.html

Py:   os.getcwd()
来源：http://dali.wangdashe.top/Article/details/gtocmtthjh.html

PHP:  getcwd();
来源：http://dali.chenzaomai.com/Article/details/gtdfgescon.html

JS:   process.cwd()
来源：http://dali.yuanzhike.top/Article/details/gtnpqgakpf.html

TS:   process.cwd()
来源：http://dali.ydzc1.top/Article/details/gtogitefjg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.feifeiyinyue.top/Article/details/gttgenvvuo.html

Go:   os.Getwd()
来源：http://dali.pengpengdd.cyou/Article/details/gtmmmwdfpf.html

Ruby: Dir.pwd
来源：http://dali.kuanghao11.cn/Article/details/gtqiqetcwz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cdnleiting.top/Article/details/gtqhimdeim.html

[M05] 设置退出码
来源：http://dali.wangshuangyany.cn/Article/details/gtamxojdzz.html

Py:   sys.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtasbjcdlx.html

PHP:  exit(1);
来源：http://dali.xuanzx.com/Article/details/gtunfgawxy.html

JS:   process.exit(1)
来源：http://dali.havefunace.top/Article/details/gtypomltbl.html

TS:   process.exit(1)
来源：http://dali.316326.xyz/Article/details/gtalnqvncg.html

Java: System.exit(1)
来源：http://dali.daria6918.cn/Article/details/gtacjkamte.html

Go:   os.Exit(1)
来源：http://dali.jqgfzy.top/Article/details/gtclrbidog.html

Ruby: exit 1
来源：http://dali.hfpthk.cn/Article/details/gtdfgcuqxf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhixingplan.top/Article/details/gtdwskmhwn.html

[M06] 向标准错误输出
来源：http://dali.c1oappe.top/Article/details/gtybazjjlb.html

Py:   print("err", file=sys.stderr)
来源：http://dali.iojbl.cn/Article/details/gtuuvwnsex.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.vqdsnc.cn/Article/details/gtnypyrivu.html

JS:   console.error("err")
来源：http://dali.daxiang520.top/Article/details/gtzlufvugo.html

TS:   console.error("err")
来源：http://dali.nanxuanxn.top/Article/details/gtqpqaewdz.html

Java: System.err.println("err")
来源：http://dali.ivvv.top/Article/details/gtrorhssbd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhtksesn.html

Ruby: warn "err"
来源：http://dali.yuxming.cn/Article/details/gtdcajasvk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.fzhhl.top/Article/details/gtlsqwdblh.html

[M07] 判断是否为主入口
来源：http://dali.nanxinkj.top/Article/details/gtelkieprw.html

Py:   if __name__ == "__main__":
来源：http://dali.shanyushiyangtech.top/Article/details/gtcefqaexv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.snrcjt.cn/Article/details/gtwgxsjmjb.html

JS:   require.main === module
来源：http://dali.cdnleiting.top/Article/details/gtnfqqbxsz.html

TS:   require.main === module
来源：http://dali.gotoacloud.top/Article/details/gtitffcbhf.html

Java: public static void main(String[] args)
来源：http://dali.smart0.xyz/Article/details/gtwxizptwq.html

Go:   func main()
来源：http://dali.kuanghao11.cn/Article/details/gtqlrgfqql.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yuanzhike.top/Article/details/gtmmmsnejr.html

C#:   static void Main(string[] args)
来源：http://dali.yj20258.top/Article/details/gtyguzylpq.html

[M08] 获取系统与运行时信息
来源：http://dali.smart0.xyz/Article/details/gtselitpxx.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xinyue.icu/Article/details/gtgzssnqlk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.mhx1999.top/Article/details/gtificrkjz.html

JS:   process.platform;  process.version
来源：http://dali.xuetiantiany.cn/Article/details/gtqfciaskt.html

TS:   process.platform;  process.version
来源：http://dali.smart0.xyz/Article/details/gtwhqqlxzp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hnxiangtu.top/Article/details/gtsczwusmo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yuxming.cn/Article/details/gtlvzfjdcp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.nwbrower.top/Article/details/gtzolxumxu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.pengpengdd.cyou/Article/details/gtqgytlcda.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtepracfkc.html

N. 数据结构与算法
来源：http://dali.kuanghao11.cn/Article/details/gtpdlawkre.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtdylqfsiw.html

[N01] 二分查找（有序数组）
来源：http://dali.yj20258.top/Article/details/gtbtvvwiyf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtnhjzdunu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hysaishi.cn/Article/details/gtcuqyocqj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hysaishi.cn/Article/details/gtidbqvmpv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.0kj1m.cn/Article/details/gttcqsxxiv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hnqzz.top/Article/details/gtkarzckla.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ivvv.top/Article/details/gtvtrsqjus.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.chenzaomai.com/Article/details/gtufcodhaj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.c1oappe.top/Article/details/gtojxeolpk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.aibaodan.cn/Article/details/gtpbpmdico.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.wangshuangyany.cn/Article/details/gttigdgvck.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.aibaodan.cn/Article/details/gtpcbhjwab.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuxming.cn/Article/details/gtlqnpdiby.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cucudq.cn/Article/details/gtdmbgspvq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.nwbrower.top/Article/details/gtkjjpwbaf.html

Go:   slices.Sort(arr)
来源：http://dali.316326.xyz/Article/details/gtpagiiwzm.html

Ruby: arr.sort
来源：http://dali.shzxlz.cn/Article/details/gtbsstoksq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yongpay.top/Article/details/gtmhntwtch.html

[N03] 快速排序（分治示例）
来源：http://dali.feifeiyinyue.top/Article/details/gtojmvjafk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sweek.top/Article/details/gtjtqdnqlt.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqjuajfxt.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ehwqpu.com/Article/details/gtpzccamyb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuanzx.com/Article/details/gtihqipuib.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yanxiufei.cn/Article/details/gtzamxswyn.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.kuanghao11.cn/Article/details/gtgdijcgjn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.c1oappe.top/Article/details/gtlcsciulb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sweek.top/Article/details/gthryclbhe.html

[N04] 斐波那契数列
来源：http://dali.sxryk.cn/Article/details/gtmjnjyotl.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtymxgypez.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yuxming.cn/Article/details/gttyrvlneq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.316326.xyz/Article/details/gtkcomtpac.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgfzy.top/Article/details/gtseorbsqv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.kuanghao11.cn/Article/details/gtxlerqaro.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yvedp.cn/Article/details/gtfldvdflp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhoulong.xyz/Article/details/gtjmcasrkz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtbrqxnkzr.html

[N05] 最大公约数
来源：http://dali.sufxvd.cn/Article/details/gtnsixlvfi.html

Py:   math.gcd(a, b)
来源：http://dali.pengpengdd.cyou/Article/details/gtgbjbpejl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yangfankeji.com/Article/details/gtefkvytrr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dashuyun.cn/Article/details/gtxrgvrtin.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zycfv.cn/Article/details/gtxgjmnrqm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.meibo888.top/Article/details/gtfruuygqj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yj20258888.top/Article/details/gtlidlkkrn.html

Ruby: a.gcd(b)
来源：http://dali.xylfe.cn/Article/details/gtlmwmtexc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.0kj1m.cn/Article/details/gtkibzcvam.html

[N06] 判断回文字符串
来源：http://dali.snrcjt.cn/Article/details/gttkisdoyx.html

Py:   s == s[::-1]
来源：http://dali.smart0.xyz/Article/details/gtwrvdinwx.html

PHP:  $s === strrev($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtaegxncdn.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yuxming.cn/Article/details/gthifjfbiu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ehwqpu.com/Article/details/gtnyuxasou.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.vqdsnc.cn/Article/details/gtaadxajho.html

Go:   // 双指针从两端比较
来源：http://dali.zhengqikj.top/Article/details/gtnbmxjnua.html

Ruby: s == s.reverse
来源：http://dali.yvedp.cn/Article/details/gtwaxmvisl.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yvedp.cn/Article/details/gtwynxnvhq.html

[N07] 两数之和（返回下标）
来源：http://dali.ppjwa.cn/Article/details/gtifpbgeox.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhoulong.xyz/Article/details/gtmousazve.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.gotoacloud.top/Article/details/gtbealdzni.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zycfv.cn/Article/details/gtahfkmsnz.html

TS:   // 手写 Map<string, number>
来源：http://dali.gaohongyu789.top/Article/details/gtqzrwcazx.html

Java: // 手写 HashMap
来源：http://dali.nanxinkj.top/Article/details/gthcwlyixa.html

Go:   // 手写 map[int]int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmzllydjd.html

Ruby: // 手写 Hash
来源：http://dali.hnqzz.top/Article/details/gtsnjicfxs.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ehwqpu.com/Article/details/gtvfjcnokm.html

[N08] 生成全排列
来源：http://dali.xylfe.cn/Article/details/gtiltaeote.html


<!-- 参考信息 -->