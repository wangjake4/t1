代发 wailian999

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.haohaochexian.top/Article/details/gtjqtyvota.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.guowangkeji.top/Article/details/gtcdkresjw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.guowangkeji.top/Article/details/gtxfpaehrp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jqgfzy.top/Article/details/gtvkfnjutd.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jqgufenzy.top/Article/details/gtujdgobzm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.quarkkingdee.top/Article/details/gtouvuyqeq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.aibaodan.cn/Article/details/gtctprzzsi.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shzxlz.cn/Article/details/gtosniooyk.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtpflgdjgs.html

K. JSON 与序列化
来源：http://dali.sufxvd.cn/Article/details/gtsuyoowll.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtotecuyei.html

[K01] 对象转 JSON 字符串
来源：http://dali.hfpthk.cn/Article/details/gtvuowgqan.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yueranfly.top/Article/details/gtyncufggl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.snrcjt.cn/Article/details/gtscttaijd.html

JS:   JSON.stringify(obj)
来源：http://dali.sweek.top/Article/details/gtioiffgir.html

TS:   JSON.stringify(obj)
来源：http://dali.c1oappe.top/Article/details/gtbretopon.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hfpthk.cn/Article/details/gtcmnmnrcl.html

Go:   json.Marshal(obj)
来源：http://dali.hysaishi.cn/Article/details/gtghpdcbyn.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.pycfn.com/Article/details/gtyfjnhodw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jiagoushi.top/Article/details/gtdbqwoqcs.html

[K02] JSON 字符串转对象
来源：http://dali.mhx1999.top/Article/details/gtathjsvge.html

Py:   json.loads(s)
来源：http://dali.cheryme.top/Article/details/gtfxxdbxjr.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.feifeiyinyue.top/Article/details/gtztkepmkz.html

JS:   JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtqgfjgmcq.html

TS:   JSON.parse(s)
来源：http://dali.yangfankeji.com/Article/details/gtoaotaxpr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.fengsongda.top/Article/details/gtkurrhpib.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jyoumei.cn/Article/details/gtmxhjgkid.html

Ruby: JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gtjaxexihd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.tanke756.top/Article/details/gtpyzkjfsl.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.chenlongwang.top/Article/details/gtaiyctgma.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gotoacloud.top/Article/details/gtxwyxclnw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinghuilouyu.cn/Article/details/gtgnfxnltr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ydzc1.top/Article/details/gtlpkxfhnu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuxming.cn/Article/details/gthqvyjthe.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthulkcrjc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hammf.cn/Article/details/gtregbllac.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.guowangkeji.top/Article/details/gtbqaaiocw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yanxiufei.cn/Article/details/gtjjurjbil.html

[K04] 读取 JSON 文件
来源：http://dali.meibo888.top/Article/details/gtvwgfwyry.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.smart0.xyz/Article/details/gtxnmcjzjw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hammf.cn/Article/details/gtmrdvcbbl.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenzaomai.com/Article/details/gtpfybsprr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zdqjudy.top/Article/details/gtowfcpgqv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsukzdgya.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jlsjyb.cn/Article/details/gthbaccmrv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.aizwys.cn/Article/details/gtwutxfcnu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhiwuduotai.top/Article/details/gtrecrwmib.html

[K05] 深拷贝对象
来源：http://dali.shangyingyoupin.top/Article/details/gtfhomkixv.html

Py:   copy.deepcopy(obj)
来源：http://dali.fzhhl.top/Article/details/gtrzypyypt.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xuanzx.com/Article/details/gtjfmojjhc.html

JS:   structuredClone(obj)
来源：http://dali.yangfankeji.com/Article/details/gtsvhwetiz.html

TS:   structuredClone(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvjeeufqm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yj20258.top/Article/details/gtovsncrev.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.mhx1999.top/Article/details/gtogwlhrww.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcbdfsdsz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xylfe.cn/Article/details/gtbypnvvnd.html

[K06] 解析 URL 查询串
来源：http://dali.sysykeji.top/Article/details/gtwaypfrmo.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ydzc1.top/Article/details/gtwstwywec.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xylfe.cn/Article/details/gtoewgdnmj.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yanxiufei.cn/Article/details/gtdovtajho.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tianlin.xyz/Article/details/gtfdhomfbu.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yvedp.cn/Article/details/gtuhuuaavc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yj20258.top/Article/details/gtnfgywgxt.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.dashuyun.cn/Article/details/gtnsldthxw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.vqdsnc.cn/Article/details/gtovmfenbh.html

[K07] 进制转换
来源：http://dali.xylfe.cn/Article/details/gtdfdzifjs.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gtyqbgskoq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.dianchejie.cn/Article/details/gtirgycexz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gtpvtgvjzw.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gtvmusojjt.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gtbuyyragg.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xuetiantiany.cn/Article/details/gtwoexaexz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cheryme.top/Article/details/gtpkqydtcj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gtglloopmc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ppjwa.cn/Article/details/gtrsfqcjxm.html

Py:   pickle.dumps(obj)
来源：http://dali.gotoacloud.top/Article/details/gtguwbygwl.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shuidangran.top/Article/details/gtocgmjaew.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.nanxuanxn.top/Article/details/gtgqlvhgoq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcsflzfpd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hongshengwenyu.top/Article/details/gtcqkpjoid.html

Go:   encoding/gob
来源：http://dali.andypj.xyz/Article/details/gtyotprjiw.html

Ruby: Marshal.dump(obj)
来源：http://dali.yuxming.cn/Article/details/gtcdwzxqcy.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.birdmap.top/Article/details/gtzlidbmnw.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtwhqbzjdo.html

L. 网络请求
来源：http://dali.redwolf501.top/Article/details/gtbwaeectn.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtowzscjjh.html

[L01] 发送 GET 请求
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjdwbdytm.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.fengsongda.top/Article/details/gtglgskdew.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hnxiangtu.top/Article/details/gtwtyhzavz.html

JS:   await fetch(url)
来源：http://dali.jqgfzy.top/Article/details/gtnxwmggqh.html

TS:   await fetch(url)
来源：http://dali.guannengcc.top/Article/details/gtcexcmwsi.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hnqzz.top/Article/details/gtxbpenywv.html

Go:   resp, err := http.Get(url)
来源：http://dali.jianghu66.top/Article/details/gtbqandywh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhengqikj.top/Article/details/gtxtaupomv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cucudq.cn/Article/details/gtaygaxryw.html

[L02] 发送 POST JSON
来源：http://dali.guowangkeji.top/Article/details/gtktatdgxk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zycfv.cn/Article/details/gtwwccfhit.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.gogol.net.cn/Article/details/gtfqvjkpsj.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sysykeji.top/Article/details/gtfotamnly.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yonumen.top/Article/details/gtxxvwalyf.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.sweek.top/Article/details/gtxfdfczyc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbbnxgpvq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gtwebpfnjb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwtiuqrfd.html

[L03] 设置自定义请求头
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoesagivd.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcmgyuazb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.c1oappe.top/Article/details/gtqxrwzbnw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcovicyqe.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jiagoushi.top/Article/details/gtiobssrie.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.0kj1m.cn/Article/details/gtfnjziper.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.aizwys.cn/Article/details/gtzpjrhfkd.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cdnleiting.top/Article/details/gtmfdhnjwp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hywenlv.cn/Article/details/gtxdijlizy.html

[L04] 设置超时
来源：http://dali.jiagoushi.top/Article/details/gtqkdcokjo.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjogzdvrm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gzhubu.top/Article/details/gtqxsvobqn.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.kuanghao11.cn/Article/details/gtqgqalxgo.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yangfankeji.com/Article/details/gtnoojccei.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.havefunace.top/Article/details/gtdndovcyd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.aizwys.cn/Article/details/gtggrbfpox.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.svipenyu.cn/Article/details/gtzutxvhhl.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.bjfxy.top/Article/details/gtpujdjcbr.html

[L05] 上传文件（multipart）
来源：http://dali.daxiang520.top/Article/details/gtejkepqud.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yj20258888.top/Article/details/gttbatvulb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.fengsongda.top/Article/details/gtdzugculr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xylfe.cn/Article/details/gtyhtlbmsv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuanzx.com/Article/details/gtkwhtqmpb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xylfe.cn/Article/details/gtdaqmtreh.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shangyingyoupin.top/Article/details/gtxdwmaiub.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.aizwys.cn/Article/details/gtpiatsxqo.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtpbbnwqix.html

[L06] 解析响应为 JSON
来源：http://dali.yj202588.top/Article/details/gtqrbwzasn.html

Py:   resp.json()
来源：http://dali.wangdashe.top/Article/details/gtbdfykiek.html

PHP:  json_decode($body, true);
来源：http://dali.ydzc1.top/Article/details/gtcjhfbxcs.html

JS:   await resp.json()
来源：http://dali.sysykeji.top/Article/details/gttwxincwg.html

TS:   await resp.json()
来源：http://dali.gzhubu.top/Article/details/gtgjxdlxyv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhiwuduotai.top/Article/details/gtajpebpyd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hongshengwenyu.top/Article/details/gtbgadykdp.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj202588.top/Article/details/gtdlajkams.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jlsjyb.cn/Article/details/gtbmbpjezs.html

[L07] 处理 HTTP 状态码
来源：http://dali.tian-w.cn/Article/details/gtgqnkuhbx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj20258.top/Article/details/gtsouototn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.daxiang520.top/Article/details/gtjzhwbrlr.html

JS:   resp.ok;  resp.status
来源：http://dali.dianchejie.cn/Article/details/gtbvvzusyj.html

TS:   resp.ok;  resp.status
来源：http://dali.guannengcc.top/Article/details/gtnqrztlmb.html

Java: resp.statusCode()
来源：http://dali.mhx1999.top/Article/details/gtvxsryojp.html

Go:   resp.StatusCode
来源：http://dali.birdmap.top/Article/details/gtauggrzet.html

Ruby: resp.code.to_i
来源：http://dali.yangfankeji.com/Article/details/gtqkdxfpiu.html

C#:   (int)resp.StatusCode
来源：http://dali.hnxiangtu.top/Article/details/gtrezanhrl.html

[L08] 并发请求多个地址
来源：http://dali.dianchejie.cn/Article/details/gtfrhqycxs.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.guowangkeji.top/Article/details/gtehlrtmfr.html

PHP:  curl_multi_init() 系列
来源：http://dali.xinyue.icu/Article/details/gtxnknvelk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gtjxbxbqpw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zycfv.cn/Article/details/gtdfqldqhj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hysaishi.cn/Article/details/gtijgwakbw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.tian-w.cn/Article/details/gtdzluxkkz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.chenlongwang.top/Article/details/gthdqxgiks.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.0kj1m.cn/Article/details/gtrcupxyge.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtxzvdvmnp.html

M. 命令行 / 进程 / 环境
来源：http://dali.yanxiufei.cn/Article/details/gtbnohxhrg.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtqhbaeqvs.html

[M01] 读取命令行参数
来源：http://dali.pycfn.com/Article/details/gtoarbovws.html

Py:   sys.argv[1:]
来源：http://dali.bjfxy.top/Article/details/gtwptdixhk.html

PHP:  $argv;  $argc;
来源：http://dali.quarkkingdee.top/Article/details/gtsyzvlxio.html

JS:   process.argv.slice(2)
来源：http://dali.havefunace.top/Article/details/gtxzivkehq.html

TS:   process.argv.slice(2)
来源：http://dali.sysykeji.top/Article/details/gtqxewzrnh.html

Java: args 数组（main 方法参数）
来源：http://dali.hnxiangtu.top/Article/details/gtcgvoqkzm.html

Go:   os.Args[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtivjkiflh.html

Ruby: ARGV
来源：http://dali.sxryk.cn/Article/details/gtrpyhmzer.html

C#:   args 数组（Main 方法参数）
来源：http://dali.smart0.xyz/Article/details/gtjyhlasyp.html

[M02] 读取环境变量
来源：http://dali.yuanzhike.top/Article/details/gtlbelyogo.html

Py:   os.environ.get("HOME")
来源：http://dali.daxiang520.top/Article/details/gtksjbbpwu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.gaohongyu789.top/Article/details/gtfikbxqqg.html

JS:   process.env.HOME
来源：http://dali.gzhubu.top/Article/details/gtthskrala.html

TS:   process.env.HOME
来源：http://dali.zhengqikj.top/Article/details/gtcmujxybz.html

Java: System.getenv("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gtoksujdjj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jyoumei.cn/Article/details/gtrjggvxxx.html

Ruby: ENV["HOME"]
来源：http://dali.tianlin.xyz/Article/details/gtnoxoaoyy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.9152youxi.cn/Article/details/gtzxupkvww.html

[M03] 执行外部命令
来源：http://dali.ywan-chungtsiang.top/Article/details/gtltixydfb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.svipenyu.cn/Article/details/gttjrqyqtm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hfpthk.cn/Article/details/gtmtzfeboi.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shangyingyoupin.top/Article/details/gtyxwkammw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.aibaodan.cn/Article/details/gtsxfncltp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xuanzx.com/Article/details/gtqdjnpdtv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.havefunace.top/Article/details/gtimabplou.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.vqdsnc.cn/Article/details/gtojeqalol.html

C#:   Process.Start("ls", "-l");
来源：http://dali.havefunace.top/Article/details/gtpihhqnet.html

[M04] 获取当前工作目录
来源：http://dali.chenjidiqi.icu/Article/details/gtpxtmmypf.html

Py:   os.getcwd()
来源：http://dali.xuanzx.com/Article/details/gthifuumjw.html

PHP:  getcwd();
来源：http://dali.c1oappe.top/Article/details/gtypdezkdt.html

JS:   process.cwd()
来源：http://dali.zhongyouzk.top/Article/details/gtohporbdn.html

TS:   process.cwd()
来源：http://dali.tianlin.xyz/Article/details/gtmovchlqp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqmzikchc.html

Go:   os.Getwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgwqyudhp.html

Ruby: Dir.pwd
来源：http://dali.jinqigfzy.top/Article/details/gtgjhdpskd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.c1oappe.top/Article/details/gtajlswxze.html

[M05] 设置退出码
来源：http://dali.cashguo.top/Article/details/gtimjrzxqq.html

Py:   sys.exit(1)
来源：http://dali.sxryk.cn/Article/details/gtvzsrzhko.html

PHP:  exit(1);
来源：http://dali.yueranfly.top/Article/details/gthfzrurrr.html

JS:   process.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdtiuyabv.html

TS:   process.exit(1)
来源：http://dali.pycfn.com/Article/details/gtmmaioziy.html

Java: System.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtojllaerc.html

Go:   os.Exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtefkobuiq.html

Ruby: exit 1
来源：http://dali.cheryme.top/Article/details/gtnjyoumcn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinqigufen.top/Article/details/gtigfcczll.html

[M06] 向标准错误输出
来源：http://dali.cheryme.top/Article/details/gtaxnhvrkr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yueranfly.top/Article/details/gtjkefhgvi.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xziqi.cn/Article/details/gtqeacnusy.html

JS:   console.error("err")
来源：http://dali.xylfe.cn/Article/details/gtqqobtbyo.html

TS:   console.error("err")
来源：http://dali.xziqi.cn/Article/details/gtnwzesooz.html

Java: System.err.println("err")
来源：http://dali.andypj.xyz/Article/details/gthiuftzlt.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sweek.top/Article/details/gtrpmwyogm.html

Ruby: warn "err"
来源：http://dali.0kj1m.cn/Article/details/gtjorflpyc.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yangfankeji.com/Article/details/gtwdkuthlr.html

[M07] 判断是否为主入口
来源：http://dali.meibo888.top/Article/details/gtgiqcisji.html

Py:   if __name__ == "__main__":
来源：http://dali.havefunace.top/Article/details/gtwfqodjzn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ehwqpu.com/Article/details/gtvaunfucj.html

JS:   require.main === module
来源：http://dali.chenlongwang.top/Article/details/gtuiciifjh.html

TS:   require.main === module
来源：http://dali.sufxvd.cn/Article/details/gtvzcascvs.html

Java: public static void main(String[] args)
来源：http://dali.iojbl.cn/Article/details/gtrytayezk.html

Go:   func main()
来源：http://dali.quarkkingdee.top/Article/details/gtzqouuvjt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cqqwz.cn/Article/details/gtmubjkgcm.html

C#:   static void Main(string[] args)
来源：http://dali.quarkkingdee.top/Article/details/gtjymmbkgh.html

[M08] 获取系统与运行时信息
来源：http://dali.shanyushiyangtech.top/Article/details/gtptuiozkt.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gotoacloud.top/Article/details/gtunghjpvv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yuxming.cn/Article/details/gtgkhahept.html

JS:   process.platform;  process.version
来源：http://dali.cucudq.cn/Article/details/gtkfxjwfmi.html

TS:   process.platform;  process.version
来源：http://dali.yangfankeji.com/Article/details/gtzibuxtzk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.nwbrower.top/Article/details/gtqjjcinox.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cucudq.cn/Article/details/gtnxskirtz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.nanxinkj.top/Article/details/gtntawiifj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.guowangkeji.top/Article/details/gttrhezehw.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtfxpdinwg.html

N. 数据结构与算法
来源：http://dali.ppjwa.cn/Article/details/gtcxbpnkjg.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtcmnyoycc.html

[N01] 二分查找（有序数组）
来源：http://dali.shuidangran.top/Article/details/gthraqugri.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtqbjedaql.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.meibo888.top/Article/details/gtmpyzlbmt.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zycfv.cn/Article/details/gtfzgcnice.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dianchejie.cn/Article/details/gtlewncbuy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtipumeaut.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtkhayapvm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shangyingyoupin.top/Article/details/gtjlcnsdon.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtuelcemdd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xziqi.cn/Article/details/gtvtkwpedk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhiwuduotai.top/Article/details/gtbfpukfji.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xinyue.icu/Article/details/gtluikatmc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ybcxt.top/Article/details/gtlisqdsyh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.9152youxi.cn/Article/details/gtkdtyrfek.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.316326.xyz/Article/details/gtzjrbuxxs.html

Go:   slices.Sort(arr)
来源：http://dali.mhx1999.top/Article/details/gtocsdyjoa.html

Ruby: arr.sort
来源：http://dali.jlsjyb.cn/Article/details/gtqgqdkvsc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.tanke756.top/Article/details/gtpntpawcl.html

[N03] 快速排序（分治示例）
来源：http://dali.pycfn.com/Article/details/gtwzbthshm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.nwbrower.top/Article/details/gtnpgyavyz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yj20258.top/Article/details/gtzsybqeih.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ivvv.top/Article/details/gtvgwxmxnb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gzhubu.top/Article/details/gtnjbixkph.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhongyouzk.top/Article/details/gtnrphojsw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jlsjyb.cn/Article/details/gtlmgjtubt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.kuanghao11.cn/Article/details/gtrfivczmu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jlsjyb.cn/Article/details/gtptblvyxf.html

[N04] 斐波那契数列
来源：http://dali.jinghuilouyu.cn/Article/details/gtckppxbvv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwbhpjymo.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hfpthk.cn/Article/details/gtvxpdvojj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yanxiufei.cn/Article/details/gtfdiejncl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cucudq.cn/Article/details/gtthrscwkw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.chenjidiqi.icu/Article/details/gtwutnyxhl.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.nanxinkj.top/Article/details/gthuebvohw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jlsjyb.cn/Article/details/gtwrrmycca.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.svipenyu.cn/Article/details/gtwdhojftf.html

[N05] 最大公约数
来源：http://dali.yueranfly.top/Article/details/gtcrpnylqq.html

Py:   math.gcd(a, b)
来源：http://dali.sxryk.cn/Article/details/gtkoolkxpq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gogol.net.cn/Article/details/gttseunrax.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shzxlz.cn/Article/details/gtjyjcilie.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shangyingyoupin.top/Article/details/gtsrhsrohj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hysaishi.cn/Article/details/gtptyezjzn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shuidangran.top/Article/details/gtbnhglhea.html

Ruby: a.gcd(b)
来源：http://dali.yonumen.top/Article/details/gtoybktwrt.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jinqigfzy.top/Article/details/gttxmxzkkp.html

[N06] 判断回文字符串
来源：http://dali.tianlin.xyz/Article/details/gtqulqolob.html

Py:   s == s[::-1]
来源：http://dali.fengsongda.top/Article/details/gtfhnjeduj.html

PHP:  $s === strrev($s);
来源：http://dali.ivvv.top/Article/details/gtyvtjprhm.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yvedp.cn/Article/details/gtijohhcjb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gtnrzzuvar.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yongpay.top/Article/details/gtrlggkdyq.html

Go:   // 双指针从两端比较
来源：http://dali.xziqi.cn/Article/details/gtwaifqhpm.html

Ruby: s == s.reverse
来源：http://dali.chenlongwang.top/Article/details/gterzapkaq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shuidangran.top/Article/details/gtnpsltshj.html

[N07] 两数之和（返回下标）
来源：http://dali.zhongyouzk.top/Article/details/gtbustbebx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gtyqlwgsmv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ydzc1.top/Article/details/gtyrpnvlwm.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hysaishi.cn/Article/details/gtvyvlfgul.html

TS:   // 手写 Map<string, number>
来源：http://dali.tian-w.cn/Article/details/gtdwiedfyq.html

Java: // 手写 HashMap
来源：http://dali.sweek.top/Article/details/gtpfaqtykc.html

Go:   // 手写 map[int]int
来源：http://dali.jinqigufen.top/Article/details/gtvqozmgca.html

Ruby: // 手写 Hash
来源：http://dali.jqgfzy.top/Article/details/gtvkiffrrm.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ppjwa.cn/Article/details/gtdmeigrjp.html

[N08] 生成全排列
来源：http://dali.tanke756.top/Article/details/gtwypxihsv.html


<!-- 参考信息 -->