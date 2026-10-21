代发 wailian999

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shzxlz.cn/Article/details/gtoeqqhzxk.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cucudq.cn/Article/details/gtlsjyjbmy.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cucudq.cn/Article/details/gtwcaojjjp.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhixingplan.top/Article/details/gtgdvxuqjh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.nanxinkj.top/Article/details/gttrlilgbu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hongshengwenyu.top/Article/details/gtyzpjwttk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.iojbl.cn/Article/details/gtthlauuzk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.svipenyu.cn/Article/details/gtlmqqmiiu.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.chenlongwang.top/Article/details/gtmhupomad.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.havefunace.top/Article/details/gtrylakvdk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hongshengwenyu.top/Article/details/gthshwaxha.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yvedp.cn/Article/details/gtbazdyvpo.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtszuwkryo.html

K. JSON 与序列化
来源：http://dali.zhixingplan.top/Article/details/gtmrvwaczr.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtouuxwkbr.html

[K01] 对象转 JSON 字符串
来源：http://dali.zycfv.cn/Article/details/gtocxmjjjx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.bjfxy.top/Article/details/gtdvfhucjj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jlsjyb.cn/Article/details/gtnatvbssc.html

JS:   JSON.stringify(obj)
来源：http://dali.dashuyun.cn/Article/details/gtxmcczjun.html

TS:   JSON.stringify(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbsmkfsec.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhongyouzk.top/Article/details/gtvndvrmbg.html

Go:   json.Marshal(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtdltbaozb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hammf.cn/Article/details/gtzjfyowhp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.wangdashe.top/Article/details/gtcvppbgol.html

[K02] JSON 字符串转对象
来源：http://dali.guowangkeji.top/Article/details/gtyqwgkjld.html

Py:   json.loads(s)
来源：http://dali.yongpay.top/Article/details/gtruexjelt.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.guowangkeji.top/Article/details/gtafnyxwnk.html

JS:   JSON.parse(s)
来源：http://dali.yj20258888.top/Article/details/gtympgjypw.html

TS:   JSON.parse(s)
来源：http://dali.hnxiangtu.top/Article/details/gtqbqkqknm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.wangshuangyany.cn/Article/details/gtjkrowaag.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zycfv.cn/Article/details/gtryrvbdtw.html

Ruby: JSON.parse(s)
来源：http://dali.vqdsnc.cn/Article/details/gtscvbcacp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ydzc1.top/Article/details/gtesympnfd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.tian-w.cn/Article/details/gtomcyhlut.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.wangdashe.top/Article/details/gteugaloix.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.chenlongwang.top/Article/details/gtuntnfkaf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbwzaegyj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sweek.top/Article/details/gtvqpgyxxh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.haohaochexian.top/Article/details/gtqyvidzvb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.c1oappe.top/Article/details/gtehnznrvv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jianghu66.top/Article/details/gtfaslnmej.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.fzhhl.top/Article/details/gtijuthhsh.html

[K04] 读取 JSON 文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrbrpilyz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cashguo.top/Article/details/gtloqgftle.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtciulgnxi.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jqgufenzy.top/Article/details/gtazdnuhjc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aizwys.cn/Article/details/gtiwhgmsep.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hammf.cn/Article/details/gteurpzbnk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.kuanghao11.cn/Article/details/gtgupzjefu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.andypj.xyz/Article/details/gtaknrlhkj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xziqi.cn/Article/details/gtnuqcwsjo.html

[K05] 深拷贝对象
来源：http://dali.yuxming.cn/Article/details/gtevkstuzx.html

Py:   copy.deepcopy(obj)
来源：http://dali.ydzc1.top/Article/details/gtjzjdzlmp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhoulong.xyz/Article/details/gtchwbwhxn.html

JS:   structuredClone(obj)
来源：http://dali.yuxming.cn/Article/details/gttcnuloxs.html

TS:   structuredClone(obj)
来源：http://dali.fzhhl.top/Article/details/gtxrcemadb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.gaohongyu789.top/Article/details/gttryqnaim.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.redwolf501.top/Article/details/gtkxfuucvz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ehwqpu.com/Article/details/gtxmaezqao.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhiwuduotai.top/Article/details/gtixpkonbo.html

[K06] 解析 URL 查询串
来源：http://dali.andypj.xyz/Article/details/gtktdcngzm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.fzhhl.top/Article/details/gtsokkqsxq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtrwqdoboh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj202588.top/Article/details/gtsvrsgurf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenzaomai.com/Article/details/gtjumdliyf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yueranfly.top/Article/details/gtsdzkqlfr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.andypj.xyz/Article/details/gtjprhptww.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.quarkkingdee.top/Article/details/gtinembrph.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cheryme.top/Article/details/gtphbqubje.html

[K07] 进制转换
来源：http://dali.shangyingyoupin.top/Article/details/gtmxlnreuj.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gtunpplqqc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhoulong.xyz/Article/details/gtmvoqqhyn.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gtzjkfitoc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gtbvhppdhc.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gtkfnvwopu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.kuanghao11.cn/Article/details/gtzavohifa.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hysaishi.cn/Article/details/gtvfloddlr.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gtlndabuhf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sufxvd.cn/Article/details/gtbgmcykte.html

Py:   pickle.dumps(obj)
来源：http://dali.shuidangran.top/Article/details/gtbshfrueg.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ybcxt.top/Article/details/gtjcovvoqj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jiagoushi.top/Article/details/gtxnzimlnt.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.kuanghao11.cn/Article/details/gtdbtvzogp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shangyingyoupin.top/Article/details/gtlcfhgeus.html

Go:   encoding/gob
来源：http://dali.jiagoushi.top/Article/details/gtveoqpeye.html

Ruby: Marshal.dump(obj)
来源：http://dali.hfpthk.cn/Article/details/gtdnmbrmpm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cucudq.cn/Article/details/gtmwyhuxvi.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtefzgwgoy.html

L. 网络请求
来源：http://dali.zycfv.cn/Article/details/gtlxmwfawj.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtjrwlwwqc.html

[L01] 发送 GET 请求
来源：http://dali.yuanzhike.top/Article/details/gtlgzihetn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yj202588.top/Article/details/gtltatxxlo.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yuanzhike.top/Article/details/gtxvlgwgui.html

JS:   await fetch(url)
来源：http://dali.gzhubu.top/Article/details/gtuiagwisg.html

TS:   await fetch(url)
来源：http://dali.nwbrower.top/Article/details/gtkukmcltz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hfpthk.cn/Article/details/gtyohqqiax.html

Go:   resp, err := http.Get(url)
来源：http://dali.chenlongwang.top/Article/details/gtbxrudvtv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinghuilouyu.cn/Article/details/gtvgkdwjkg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.9152youxi.cn/Article/details/gtszihbgjr.html

[L02] 发送 POST JSON
来源：http://dali.havefunace.top/Article/details/gtoncirwze.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jyoumei.cn/Article/details/gtafmuaxsk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ppjwa.cn/Article/details/gtkexvryjk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nwbrower.top/Article/details/gtparqkhhf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnvgpdnzz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.sysykeji.top/Article/details/gtltsyyark.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yuanzhike.top/Article/details/gtnpsevfzq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinqigfzy.top/Article/details/gtiefszupp.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cqqwz.cn/Article/details/gtewchhzyx.html

[L03] 设置自定义请求头
来源：http://dali.xinyue.icu/Article/details/gtnlfssepq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hongshengwenyu.top/Article/details/gtdzilcmlt.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinqigufen.top/Article/details/gtgralylio.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hongshengwenyu.top/Article/details/gtumvfpjkh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tanke756.top/Article/details/gtmklrzhww.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.haohaochexian.top/Article/details/gtrhdksyfu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.dianchejie.cn/Article/details/gtqueakovb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sysykeji.top/Article/details/gtjgvbhszf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zdqjudy.top/Article/details/gtimczwrdf.html

[L04] 设置超时
来源：http://dali.snrcjt.cn/Article/details/gtmsuggymt.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xuetiantiany.cn/Article/details/gtxkdkipdo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yj202588.top/Article/details/gtnhmbkerg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daria6918.cn/Article/details/gtqoupfwlj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhengqikj.top/Article/details/gtxdcrpphp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.andypj.xyz/Article/details/gtjouackfm.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.quarkkingdee.top/Article/details/gtnkktmqft.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.pengpengdd.cyou/Article/details/gtauziojxf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shangyingyoupin.top/Article/details/gtavwxhtcl.html

[L05] 上传文件（multipart）
来源：http://dali.jinqigfzy.top/Article/details/gtnlvodejp.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.iojbl.cn/Article/details/gtaozcdtha.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.svipenyu.cn/Article/details/gttfmrxhfs.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cdnleiting.top/Article/details/gtbcnsuzsa.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.pycfn.com/Article/details/gtaycqzoum.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sweek.top/Article/details/gtievpebpm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.chenzaomai.com/Article/details/gtcksoecmi.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xuanzx.com/Article/details/gtfhkyzudj.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtlcqibgqm.html

[L06] 解析响应为 JSON
来源：http://dali.yangfankeji.com/Article/details/gthlhrjrxj.html

Py:   resp.json()
来源：http://dali.316326.xyz/Article/details/gtxrfotusr.html

PHP:  json_decode($body, true);
来源：http://dali.kuanghao11.cn/Article/details/gtuivapuvu.html

JS:   await resp.json()
来源：http://dali.ppjwa.cn/Article/details/gtugrwluwm.html

TS:   await resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gtmibtmlcz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.tian-w.cn/Article/details/gtcascpamk.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinqigfzy.top/Article/details/gtykpeomey.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cqqwz.cn/Article/details/gtgvogvuha.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jqgfzy.top/Article/details/gtorbhyyhd.html

[L07] 处理 HTTP 状态码
来源：http://dali.shzxlz.cn/Article/details/gthgtthlwx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.svipenyu.cn/Article/details/gtnbyhfsgj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.iojbl.cn/Article/details/gttqjsznpe.html

JS:   resp.ok;  resp.status
来源：http://dali.ybcxt.top/Article/details/gtnlqlgfcu.html

TS:   resp.ok;  resp.status
来源：http://dali.yuanzhike.top/Article/details/gthdkalqan.html

Java: resp.statusCode()
来源：http://dali.gogol.net.cn/Article/details/gtyvisqtng.html

Go:   resp.StatusCode
来源：http://dali.jyoumei.cn/Article/details/gthbbmdzsa.html

Ruby: resp.code.to_i
来源：http://dali.zhoulong.xyz/Article/details/gtfsqwzicw.html

C#:   (int)resp.StatusCode
来源：http://dali.yonumen.top/Article/details/gtfofhkujc.html

[L08] 并发请求多个地址
来源：http://dali.cucudq.cn/Article/details/gtsrjjtgve.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.pengpengdd.cyou/Article/details/gtrzjyhpvm.html

PHP:  curl_multi_init() 系列
来源：http://dali.jqgufenzy.top/Article/details/gtygqzxhen.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cashguo.top/Article/details/gttlabjjiq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jyoumei.cn/Article/details/gtogfvckre.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cheryme.top/Article/details/gtbnxardoe.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.andypj.xyz/Article/details/gtjdibttfv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zdqjudy.top/Article/details/gtjokqwwzo.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hywenlv.cn/Article/details/gtknlekbdu.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtqyyvwtmj.html

M. 命令行 / 进程 / 环境
来源：http://dali.jianghu66.top/Article/details/gtssgwgqyl.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtggdyledx.html

[M01] 读取命令行参数
来源：http://dali.zhongyouzk.top/Article/details/gtfyewcdcs.html

Py:   sys.argv[1:]
来源：http://dali.cheryme.top/Article/details/gtlsbvrzsq.html

PHP:  $argv;  $argc;
来源：http://dali.sufxvd.cn/Article/details/gtnyvvzkko.html

JS:   process.argv.slice(2)
来源：http://dali.c1oappe.top/Article/details/gtioemrwzu.html

TS:   process.argv.slice(2)
来源：http://dali.shzxlz.cn/Article/details/gthrxgpejc.html

Java: args 数组（main 方法参数）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfqaxhler.html

Go:   os.Args[1:]
来源：http://dali.yuxming.cn/Article/details/gtcvswyjlh.html

Ruby: ARGV
来源：http://dali.smart0.xyz/Article/details/gtipaicuaq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.tianlin.xyz/Article/details/gtzfgfpylh.html

[M02] 读取环境变量
来源：http://dali.aizwys.cn/Article/details/gturhwkczv.html

Py:   os.environ.get("HOME")
来源：http://dali.hysaishi.cn/Article/details/gtkqdrcjyk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxjberaqy.html

JS:   process.env.HOME
来源：http://dali.hammf.cn/Article/details/gtjmmftvna.html

TS:   process.env.HOME
来源：http://dali.ivvv.top/Article/details/gtlsnbapsk.html

Java: System.getenv("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gtfkrjmpjn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.nanxinkj.top/Article/details/gtlkppajbi.html

Ruby: ENV["HOME"]
来源：http://dali.pengpengdd.cyou/Article/details/gtijevzqnc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.tian-w.cn/Article/details/gthogjpgob.html

[M03] 执行外部命令
来源：http://dali.jqgfzy.top/Article/details/gtrofisjgk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yonumen.top/Article/details/gtuogutjgn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xinyue.icu/Article/details/gtskkiujoa.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtihkkzezw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gtercthzqg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.andypj.xyz/Article/details/gtasenmrkl.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.aibaodan.cn/Article/details/gtcdmpgvfk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hysaishi.cn/Article/details/gtfixbpdnz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtchcjfdmd.html

[M04] 获取当前工作目录
来源：http://dali.iojbl.cn/Article/details/gtxpfkcwbn.html

Py:   os.getcwd()
来源：http://dali.yj20258888.top/Article/details/gtaxqhnfin.html

PHP:  getcwd();
来源：http://dali.gzhubu.top/Article/details/gtkimksvsf.html

JS:   process.cwd()
来源：http://dali.redwolf501.top/Article/details/gticsvfesq.html

TS:   process.cwd()
来源：http://dali.xinyue.icu/Article/details/gtbepyhgfv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.svipenyu.cn/Article/details/gtvsrvycph.html

Go:   os.Getwd()
来源：http://dali.ppjwa.cn/Article/details/gtgtwalbfc.html

Ruby: Dir.pwd
来源：http://dali.hongshengwenyu.top/Article/details/gtshacpxad.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yj202588.top/Article/details/gtdpolpqph.html

[M05] 设置退出码
来源：http://dali.cucudq.cn/Article/details/gtuniczbxd.html

Py:   sys.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gtuctuuqwa.html

PHP:  exit(1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnuqcjnjx.html

JS:   process.exit(1)
来源：http://dali.daria6918.cn/Article/details/gtldeciaqv.html

TS:   process.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gtslevfksn.html

Java: System.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gtlvlcwkrn.html

Go:   os.Exit(1)
来源：http://dali.zhengqikj.top/Article/details/gtxzroawfq.html

Ruby: exit 1
来源：http://dali.wangshuangyany.cn/Article/details/gtiaqgmkir.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.mhx1999.top/Article/details/gtvzegwayu.html

[M06] 向标准错误输出
来源：http://dali.xinyue.icu/Article/details/gtbdhathzg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhiwuduotai.top/Article/details/gtjzbnnoir.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtodypvboc.html

JS:   console.error("err")
来源：http://dali.pengpengdd.cyou/Article/details/gtimmfmbki.html

TS:   console.error("err")
来源：http://dali.jianghu66.top/Article/details/gtezlhkusk.html

Java: System.err.println("err")
来源：http://dali.hnxiangtu.top/Article/details/gtlieiqnka.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hfpthk.cn/Article/details/gtjbqylpfx.html

Ruby: warn "err"
来源：http://dali.sxryk.cn/Article/details/gtbrfhfrnv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jianghu66.top/Article/details/gtjnjbqbsq.html

[M07] 判断是否为主入口
来源：http://dali.zhixingplan.top/Article/details/gthvuiayeb.html

Py:   if __name__ == "__main__":
来源：http://dali.yj20258888.top/Article/details/gtfthclpvw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.9152youxi.cn/Article/details/gtarpggxfx.html

JS:   require.main === module
来源：http://dali.xuanzx.com/Article/details/gtrhybvztd.html

TS:   require.main === module
来源：http://dali.zhoulong.xyz/Article/details/gtxiskzgvu.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gtfktpjtph.html

Go:   func main()
来源：http://dali.iojbl.cn/Article/details/gtwxipzhml.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhongyouzk.top/Article/details/gtflmlpbqf.html

C#:   static void Main(string[] args)
来源：http://dali.hnqzz.top/Article/details/gtkmckmejl.html

[M08] 获取系统与运行时信息
来源：http://dali.zhongyouzk.top/Article/details/gtnyhlvtno.html

Py:   platform.system();  platform.python_version()
来源：http://dali.tian-w.cn/Article/details/gtplmwanzq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hfpthk.cn/Article/details/gtdxoosjmu.html

JS:   process.platform;  process.version
来源：http://dali.fengsongda.top/Article/details/gtodiqlywy.html

TS:   process.platform;  process.version
来源：http://dali.hongshengwenyu.top/Article/details/gtjuciihiz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.fengsongda.top/Article/details/gtonshdgqf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xziqi.cn/Article/details/gtyoidwnsx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.9152youxi.cn/Article/details/gtpnwohmai.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cashguo.top/Article/details/gtdccugaen.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtsvixjmsq.html

N. 数据结构与算法
来源：http://dali.316326.xyz/Article/details/gtlbzwbbeu.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtoqpomvph.html

[N01] 二分查找（有序数组）
来源：http://dali.guannengcc.top/Article/details/gtqmpszady.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtquczftnk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yj202588.top/Article/details/gtoschqckd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhoulong.xyz/Article/details/gtqwichhzg.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hfpthk.cn/Article/details/gtdqkmdlem.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gtglmmylsv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtcoglxvpx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jqgfzy.top/Article/details/gtodsyzxfn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gthziywvmu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hnxiangtu.top/Article/details/gtxgfclgpr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhoulong.xyz/Article/details/gtypjvnyug.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.gogol.net.cn/Article/details/gtyekqheyc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yueranfly.top/Article/details/gtqajhzhql.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258.top/Article/details/gtmyqppfop.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtibdvxonn.html

Go:   slices.Sort(arr)
来源：http://dali.hywenlv.cn/Article/details/gtwdphzpaf.html

Ruby: arr.sort
来源：http://dali.haohaochexian.top/Article/details/gtbnchgmrj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yanxiufei.cn/Article/details/gtnjfhxjbz.html

[N03] 快速排序（分治示例）
来源：http://dali.cucudq.cn/Article/details/gtiwketpak.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yj20258888.top/Article/details/gtxbsfcefc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jiagoushi.top/Article/details/gtjgfbinof.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ivvv.top/Article/details/gtxyfjvjcc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.snrcjt.cn/Article/details/gtgbopzgeh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sxryk.cn/Article/details/gtsioittda.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj20258888.top/Article/details/gtbqyoabaw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfthovqad.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.haohaochexian.top/Article/details/gtrejtnewk.html

[N04] 斐波那契数列
来源：http://dali.hnqzz.top/Article/details/gthjimzjlv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gotoacloud.top/Article/details/gtryzvlhzu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cdnleiting.top/Article/details/gtafworlrm.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yongpay.top/Article/details/gtidmhojyy.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gtsvdbfpda.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.fengsongda.top/Article/details/gtbryhuoln.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.fzhhl.top/Article/details/gtusnupjnb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hywenlv.cn/Article/details/gtqaaoxukv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yonumen.top/Article/details/gtpnkxijid.html

[N05] 最大公约数
来源：http://dali.dianchejie.cn/Article/details/gtqdwpxtat.html

Py:   math.gcd(a, b)
来源：http://dali.ybcxt.top/Article/details/gtemznzcow.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zycfv.cn/Article/details/gttbpniapt.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fengsongda.top/Article/details/gtiqukbmxq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.snrcjt.cn/Article/details/gtecgifytw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jinghuilouyu.cn/Article/details/gtfnijsfjd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xuetiantiany.cn/Article/details/gtbiapjngb.html

Ruby: a.gcd(b)
来源：http://dali.c1oappe.top/Article/details/gtffiodzku.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.daria6918.cn/Article/details/gtktwpmnve.html

[N06] 判断回文字符串
来源：http://dali.nanxuanxn.top/Article/details/gtcjydjpaz.html

Py:   s == s[::-1]
来源：http://dali.yueranfly.top/Article/details/gtbjnbdicm.html

PHP:  $s === strrev($s);
来源：http://dali.yuanzhike.top/Article/details/gtoboqwfel.html

JS:   s === [...s].reverse().join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtjovkwugl.html

TS:   s === [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gtnttlwgbg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yonumen.top/Article/details/gtmxdayljj.html

Go:   // 双指针从两端比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtthtdgbck.html

Ruby: s == s.reverse
来源：http://dali.yanxiufei.cn/Article/details/gtoyffsfca.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.svipenyu.cn/Article/details/gtbashrwxq.html

[N07] 两数之和（返回下标）
来源：http://dali.yvedp.cn/Article/details/gtsmlbrboj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yj20258.top/Article/details/gtfvdswqhw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.guowangkeji.top/Article/details/gtdjvqmnbf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhiwuduotai.top/Article/details/gtzrzcghts.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gtjfzoxulx.html

Java: // 手写 HashMap
来源：http://dali.aibaodan.cn/Article/details/gtafrdlzrt.html


<!-- 参考信息 -->