代发 wailian999

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.svipenyu.cn/Article/details/gtzzywykvr.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ppjwa.cn/Article/details/gtjdvffpfu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gaohongyu789.top/Article/details/gtqoyhjqxq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ehwqpu.com/Article/details/gttvyjkkkf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj202588.top/Article/details/gtukmlicph.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.nanxuanxn.top/Article/details/gtpalnjcpo.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jqgufenzy.top/Article/details/gtmvdaginw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.0kj1m.cn/Article/details/gtmqntfzgl.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtwvbmmgqt.html

K. JSON 与序列化
来源：http://dali.yuxming.cn/Article/details/gtsblgblyg.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtxvtjnkyf.html

[K01] 对象转 JSON 字符串
来源：http://dali.wangdashe.top/Article/details/gtmeiuspbj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jqgfzy.top/Article/details/gtdmmlgkfa.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvviwtbia.html

JS:   JSON.stringify(obj)
来源：http://dali.yj202588.top/Article/details/gtexldxdno.html

TS:   JSON.stringify(obj)
来源：http://dali.tianlin.xyz/Article/details/gtvovffjdp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zdqjudy.top/Article/details/gtpyxogxjc.html

Go:   json.Marshal(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtfwxkbkim.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shzxlz.cn/Article/details/gtkscucvsd.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtetydsaci.html

[K02] JSON 字符串转对象
来源：http://dali.yuanzhike.top/Article/details/gtxuqaapgn.html

Py:   json.loads(s)
来源：http://dali.316326.xyz/Article/details/gtwiyblogg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.guannengcc.top/Article/details/gtkpepafqn.html

JS:   JSON.parse(s)
来源：http://dali.cucudq.cn/Article/details/gtkigxhdus.html

TS:   JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gtxqdmlhas.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.tianlin.xyz/Article/details/gtrrczvzny.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sufxvd.cn/Article/details/gtofjsybrg.html

Ruby: JSON.parse(s)
来源：http://dali.gzhubu.top/Article/details/gtzrzwfmbb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.haohaochexian.top/Article/details/gtidjmfllk.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cheryme.top/Article/details/gtzlpvwndz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.svipenyu.cn/Article/details/gtlewgyyyr.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.fengsongda.top/Article/details/gtuvuaygjf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yangfankeji.com/Article/details/gtjhyhetus.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtjpalxcti.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.svipenyu.cn/Article/details/gtyksyvtps.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpuzgvrzk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yj20258888.top/Article/details/gtoiuykyha.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cashguo.top/Article/details/gtfnjvomnx.html

[K04] 读取 JSON 文件
来源：http://dali.xuanzx.com/Article/details/gtszjtsabt.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gtzhivnowl.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xziqi.cn/Article/details/gtxhudpfrp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxinkj.top/Article/details/gtiuoswlzv.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pycfn.com/Article/details/gttfmifsgw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zycfv.cn/Article/details/gtabenmkjd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttehuphuu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yanxiufei.cn/Article/details/gtkbaxtypi.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.haohaochexian.top/Article/details/gtqirwneaw.html

[K05] 深拷贝对象
来源：http://dali.yangfankeji.com/Article/details/gtkfgtrftl.html

Py:   copy.deepcopy(obj)
来源：http://dali.chenlongwang.top/Article/details/gtoyitmkbp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gaohongyu789.top/Article/details/gtkfrioaum.html

JS:   structuredClone(obj)
来源：http://dali.cqqwz.cn/Article/details/gtlnkemfuy.html

TS:   structuredClone(obj)
来源：http://dali.cucudq.cn/Article/details/gtezjgnccf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenjidiqi.icu/Article/details/gtfggpkiyc.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.feifeiyinyue.top/Article/details/gtywmxxcsa.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.birdmap.top/Article/details/gtuahjxopy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zycfv.cn/Article/details/gtuehaegbh.html

[K06] 解析 URL 查询串
来源：http://dali.cucudq.cn/Article/details/gtpcinulvz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.dianchejie.cn/Article/details/gtdamjcsst.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.guannengcc.top/Article/details/gtzizwebnm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gtffpegsyi.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhengqikj.top/Article/details/gtlfidhzay.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.bjfxy.top/Article/details/gtgesrpphz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.feifeiyinyue.top/Article/details/gtnxspppnu.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jyoumei.cn/Article/details/gtwhyaziaq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ppjwa.cn/Article/details/gtmvjsrwst.html

[K07] 进制转换
来源：http://dali.iojbl.cn/Article/details/gtutmeoftq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gtamtlyldl.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ivvv.top/Article/details/gtsoetbafw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gtbyabsutg.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gtjdzjxtkl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gtsyxghesb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.chenjidiqi.icu/Article/details/gtbrqhknty.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hywenlv.cn/Article/details/gtotmzqtlo.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gtqobkqckd.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtilsqwrat.html

Py:   pickle.dumps(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtovtqaxnd.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xylfe.cn/Article/details/gtkdnyezga.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.9152youxi.cn/Article/details/gtjyngdgqi.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yangfankeji.com/Article/details/gtijcbvnse.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhiwuduotai.top/Article/details/gtbdnaivjh.html

Go:   encoding/gob
来源：http://dali.jqgfzy.top/Article/details/gtbhtxzxvu.html

Ruby: Marshal.dump(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtwyemcxfm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.dashuyun.cn/Article/details/gtdbltdfcp.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtxphlhxyx.html

L. 网络请求
来源：http://dali.zhaomingkeji.xyz/Article/details/gttoeynlhp.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtfogxcvvc.html

[L01] 发送 GET 请求
来源：http://dali.yuxming.cn/Article/details/gtocgpauhc.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cqqwz.cn/Article/details/gtdwyhexqr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.chenlongwang.top/Article/details/gtmjvywbyp.html

JS:   await fetch(url)
来源：http://dali.guannengcc.top/Article/details/gthqroxxfi.html

TS:   await fetch(url)
来源：http://dali.ppjwa.cn/Article/details/gteapoczdv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.birdmap.top/Article/details/gtcwhgomem.html

Go:   resp, err := http.Get(url)
来源：http://dali.gotoacloud.top/Article/details/gtlmgsnjuy.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.iojbl.cn/Article/details/gtgjxhsgbf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sxryk.cn/Article/details/gtbjckazhy.html

[L02] 发送 POST JSON
来源：http://dali.havefunace.top/Article/details/gtqnqfvhas.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yuanzhike.top/Article/details/gtkawhcyse.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jqgufenzy.top/Article/details/gtvmmpoarl.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hysaishi.cn/Article/details/gtdzflumdp.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shuidangran.top/Article/details/gthdxgsslw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jianghu66.top/Article/details/gtzrhbwbjc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.meibo888.top/Article/details/gtbunrrgth.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.quarkkingdee.top/Article/details/gtwfdgwjfo.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hnxiangtu.top/Article/details/gtxsjhijkl.html

[L03] 设置自定义请求头
来源：http://dali.cdnleiting.top/Article/details/gthjoqmipx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hywenlv.cn/Article/details/gtzeahntsj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yj202588.top/Article/details/gtobhvtyyl.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.feifeiyinyue.top/Article/details/gtvmywellp.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gaohongyu789.top/Article/details/gtnrzxbyge.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.tian-w.cn/Article/details/gtyacmhlkg.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhiwuduotai.top/Article/details/gtwooqqwoj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.feifeiyinyue.top/Article/details/gthivdbasa.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhiwuduotai.top/Article/details/gttyfijewr.html

[L04] 设置超时
来源：http://dali.quarkkingdee.top/Article/details/gtypdlghzu.html

Py:   requests.get(url, timeout=5)
来源：http://dali.feifeiyinyue.top/Article/details/gtbdqpmyca.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hfpthk.cn/Article/details/gtpijwaqzm.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenjidiqi.icu/Article/details/gtowkdrerq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hongshengwenyu.top/Article/details/gtmdpzsykm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.aizwys.cn/Article/details/gtnpdhkpmb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.chenzaomai.com/Article/details/gtanqbeqfl.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cashguo.top/Article/details/gtjzsrpfha.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.c1oappe.top/Article/details/gtazhqkxgg.html

[L05] 上传文件（multipart）
来源：http://dali.feifeiyinyue.top/Article/details/gtpilcgewz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.feifeiyinyue.top/Article/details/gtiywvfpsz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.birdmap.top/Article/details/gtdattuayn.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenzaomai.com/Article/details/gtdpfyrywp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.nwbrower.top/Article/details/gtuqtfitzi.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gtsipsflew.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtytbfwdxt.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xziqi.cn/Article/details/gtypcxrzhx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yj202588.top/Article/details/gtjghqyrrx.html

[L06] 解析响应为 JSON
来源：http://dali.yueranfly.top/Article/details/gtcgygidht.html

Py:   resp.json()
来源：http://dali.sxryk.cn/Article/details/gtslvvuhxu.html

PHP:  json_decode($body, true);
来源：http://dali.shzxlz.cn/Article/details/gtgaobjsvk.html

JS:   await resp.json()
来源：http://dali.xziqi.cn/Article/details/gtdppjgcfq.html

TS:   await resp.json()
来源：http://dali.jianghu66.top/Article/details/gtddjjsutk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhoulong.xyz/Article/details/gthplsjdbs.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ppjwa.cn/Article/details/gthjdzeixg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jianghu66.top/Article/details/gthezvrnxj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhixingplan.top/Article/details/gtwxpimcld.html

[L07] 处理 HTTP 状态码
来源：http://dali.xuanzx.com/Article/details/gtbriiidgb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.gzhubu.top/Article/details/gtespiisuu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.aibaodan.cn/Article/details/gtrcxtkhle.html

JS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangkeji.top/Article/details/gthubgksmu.html

TS:   resp.ok;  resp.status
来源：http://dali.haohaochexian.top/Article/details/gtlqdewohz.html

Java: resp.statusCode()
来源：http://dali.cucudq.cn/Article/details/gtcwuquyuh.html

Go:   resp.StatusCode
来源：http://dali.smart0.xyz/Article/details/gtonsqbgvs.html

Ruby: resp.code.to_i
来源：http://dali.cheryme.top/Article/details/gtnspburqd.html

C#:   (int)resp.StatusCode
来源：http://dali.snrcjt.cn/Article/details/gtlajhraag.html

[L08] 并发请求多个地址
来源：http://dali.zycfv.cn/Article/details/gtgqyyijmd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xuanzx.com/Article/details/gtxccogbdr.html

PHP:  curl_multi_init() 系列
来源：http://dali.redwolf501.top/Article/details/gteaaizryp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yueranfly.top/Article/details/gtrfcdtfpy.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gtqjcxwbyh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.vqdsnc.cn/Article/details/gtxqbajots.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.316326.xyz/Article/details/gthhnllsxh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shzxlz.cn/Article/details/gtowbjcfsp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.redwolf501.top/Article/details/gtshwadyaa.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtogmxadvy.html

M. 命令行 / 进程 / 环境
来源：http://dali.ivvv.top/Article/details/gtkxebmilp.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gteprgtael.html

[M01] 读取命令行参数
来源：http://dali.ybcxt.top/Article/details/gtsldjmblt.html

Py:   sys.argv[1:]
来源：http://dali.meibo888.top/Article/details/gtnguunvyu.html

PHP:  $argv;  $argc;
来源：http://dali.yvedp.cn/Article/details/gtzxhihtrt.html

JS:   process.argv.slice(2)
来源：http://dali.0kj1m.cn/Article/details/gtgsfxilzr.html

TS:   process.argv.slice(2)
来源：http://dali.yvedp.cn/Article/details/gtljblpiii.html

Java: args 数组（main 方法参数）
来源：http://dali.gaohongyu789.top/Article/details/gtshcmgvpx.html

Go:   os.Args[1:]
来源：http://dali.9152youxi.cn/Article/details/gtzpmwmdeo.html

Ruby: ARGV
来源：http://dali.guannengcc.top/Article/details/gtlzgvzeex.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shangyingyoupin.top/Article/details/gtbyeloled.html

[M02] 读取环境变量
来源：http://dali.yuxming.cn/Article/details/gtviyaruwh.html

Py:   os.environ.get("HOME")
来源：http://dali.c1oappe.top/Article/details/gtgqleyrtg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.fengsongda.top/Article/details/gtqjeghytr.html

JS:   process.env.HOME
来源：http://dali.zhaomingkeji.xyz/Article/details/gtquyezklv.html

TS:   process.env.HOME
来源：http://dali.gzhubu.top/Article/details/gtrwkgredt.html

Java: System.getenv("HOME")
来源：http://dali.daria6918.cn/Article/details/gttzusxhgi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yuxming.cn/Article/details/gtyprafwfi.html

Ruby: ENV["HOME"]
来源：http://dali.havefunace.top/Article/details/gteebejyai.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shuidangran.top/Article/details/gtffddmzhu.html

[M03] 执行外部命令
来源：http://dali.yj20258.top/Article/details/gtypxygzfy.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbgjpczoq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ivvv.top/Article/details/gtzsadnguf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.guannengcc.top/Article/details/gtcbvoblww.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.fengsongda.top/Article/details/gtslvfjnuc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmkepdwwq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sufxvd.cn/Article/details/gtvylvpbum.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shzxlz.cn/Article/details/gtgfmjpcum.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cdnleiting.top/Article/details/gttjbfkhqu.html

[M04] 获取当前工作目录
来源：http://dali.redwolf501.top/Article/details/gttzalpfda.html

Py:   os.getcwd()
来源：http://dali.ivvv.top/Article/details/gtzgjyvumx.html

PHP:  getcwd();
来源：http://dali.ybcxt.top/Article/details/gtmqhtteqo.html

JS:   process.cwd()
来源：http://dali.cucudq.cn/Article/details/gtlbdamqyo.html

TS:   process.cwd()
来源：http://dali.cashguo.top/Article/details/gtoqkpdxed.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ydzc1.top/Article/details/gtfbcaibak.html

Go:   os.Getwd()
来源：http://dali.bjfxy.top/Article/details/gtgvvcdvoe.html

Ruby: Dir.pwd
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbgpmdlud.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.bjfxy.top/Article/details/gtzafiepoq.html

[M05] 设置退出码
来源：http://dali.bjfxy.top/Article/details/gttlwcblpc.html

Py:   sys.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gtfryixche.html

PHP:  exit(1);
来源：http://dali.cucudq.cn/Article/details/gtandgjohg.html

JS:   process.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gtyajtvqgu.html

TS:   process.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtryzkftyq.html

Java: System.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfcflzejm.html

Go:   os.Exit(1)
来源：http://dali.guowangkeji.top/Article/details/gtqdqdknyl.html

Ruby: exit 1
来源：http://dali.sweek.top/Article/details/gtqiullklr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ppjwa.cn/Article/details/gtoehdvplf.html

[M06] 向标准错误输出
来源：http://dali.yanxiufei.cn/Article/details/gtuvrnpoup.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gotoacloud.top/Article/details/gtcgexmced.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.feifeiyinyue.top/Article/details/gtjqqgeyxa.html

JS:   console.error("err")
来源：http://dali.ivvv.top/Article/details/gtkcuxayfo.html

TS:   console.error("err")
来源：http://dali.smart0.xyz/Article/details/gtouabmxmt.html

Java: System.err.println("err")
来源：http://dali.snrcjt.cn/Article/details/gtbyfmeuur.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hfpthk.cn/Article/details/gtfhigmhhx.html

Ruby: warn "err"
来源：http://dali.andypj.xyz/Article/details/gtgdlpxflp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.wangshuangyany.cn/Article/details/gtnsgysndz.html

[M07] 判断是否为主入口
来源：http://dali.guannengcc.top/Article/details/gtowyodiwa.html

Py:   if __name__ == "__main__":
来源：http://dali.jianghu66.top/Article/details/gtzvuqpgdy.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xziqi.cn/Article/details/gtjlfadmrf.html

JS:   require.main === module
来源：http://dali.chenjidiqi.icu/Article/details/gtkoyofvxg.html

TS:   require.main === module
来源：http://dali.zhoulong.xyz/Article/details/gtdhrvjfaf.html

Java: public static void main(String[] args)
来源：http://dali.chenjidiqi.icu/Article/details/gttupxdhsc.html

Go:   func main()
来源：http://dali.zhixingplan.top/Article/details/gtfosgufnu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hysaishi.cn/Article/details/gtfqoxuoqo.html

C#:   static void Main(string[] args)
来源：http://dali.ydzc1.top/Article/details/gtarudwhxg.html

[M08] 获取系统与运行时信息
来源：http://dali.wangshuangyany.cn/Article/details/gtnughujut.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hnxiangtu.top/Article/details/gtjgnqjacy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.redwolf501.top/Article/details/gtikpgoakd.html

JS:   process.platform;  process.version
来源：http://dali.hnqzz.top/Article/details/gtnreykmfl.html

TS:   process.platform;  process.version
来源：http://dali.pengpengdd.cyou/Article/details/gtefdlchns.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ehwqpu.com/Article/details/gtollurlvs.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zycfv.cn/Article/details/gthbpvxdtt.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hnqzz.top/Article/details/gtynolrxha.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yj20258888.top/Article/details/gtdzehyqhx.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gteqnjelya.html

N. 数据结构与算法
来源：http://dali.bjfxy.top/Article/details/gtbptnfnns.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtvafaernl.html

[N01] 二分查找（有序数组）
来源：http://dali.gaohongyu789.top/Article/details/gthcoxmrlb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtxdxedauz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhiwuduotai.top/Article/details/gtpzwsvctd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenjidiqi.icu/Article/details/gtpgogxkjo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sufxvd.cn/Article/details/gtyzvtzkte.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.c1oappe.top/Article/details/gtmjzgpaiq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmgemdlbr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xuetiantiany.cn/Article/details/gtjuwczgoz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtfvtzwsqc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shanyushiyangkeji.top/Article/details/gteamhamjl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yangfankeji.com/Article/details/gtrwdgjcbm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.aizwys.cn/Article/details/gtlwoksige.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xinyue.icu/Article/details/gtojiqfkbh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gtvjwvgbgk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinqigufen.top/Article/details/gtyxsdxkzz.html

Go:   slices.Sort(arr)
来源：http://dali.guannengcc.top/Article/details/gtepwpbxna.html

Ruby: arr.sort
来源：http://dali.xylfe.cn/Article/details/gtkvmamlyf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.nanxinkj.top/Article/details/gtxghjkgwj.html

[N03] 快速排序（分治示例）
来源：http://dali.yuxming.cn/Article/details/gtzldxgnso.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.chenlongwang.top/Article/details/gtbfebbzgm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.pengpengdd.cyou/Article/details/gtjzbadnnm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258.top/Article/details/gtbjtabfeu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yongpay.top/Article/details/gtehtdkijc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shangyingyoupin.top/Article/details/gtppruzncl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.havefunace.top/Article/details/gtfynegnzk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhongyouzk.top/Article/details/gtiockqelk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinqigufen.top/Article/details/gtlmanubht.html

[N04] 斐波那契数列
来源：http://dali.yongpay.top/Article/details/gtxqednkej.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwfwhrhyz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.tian-w.cn/Article/details/gtngstoaeo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj20258.top/Article/details/gtoblvkrbp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daxiang520.top/Article/details/gtffupwgay.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.c1oappe.top/Article/details/gtapkjueri.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.wangdashe.top/Article/details/gtmxtiphek.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtwmgiivus.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gtekdlkmri.html

[N05] 最大公约数
来源：http://dali.ydzc1.top/Article/details/gtogpsfzwv.html

Py:   math.gcd(a, b)
来源：http://dali.c1oappe.top/Article/details/gtewpahmfv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.andypj.xyz/Article/details/gtaukfgujd.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xziqi.cn/Article/details/gthpmjvsbe.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.guannengcc.top/Article/details/gtxejutdmq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.pycfn.com/Article/details/gtvpwmdgiq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ehwqpu.com/Article/details/gtazemnsmw.html

Ruby: a.gcd(b)
来源：http://dali.haohaochexian.top/Article/details/gtiviyyfjo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gaohongyu789.top/Article/details/gtdqpchhaw.html

[N06] 判断回文字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxpgwuqvg.html

Py:   s == s[::-1]
来源：http://dali.9152youxi.cn/Article/details/gtrzdnunft.html

PHP:  $s === strrev($s);
来源：http://dali.zdqjudy.top/Article/details/gtlwzyuqad.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sysykeji.top/Article/details/gtkojiwuzr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gtcimubhlg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jyoumei.cn/Article/details/gtfmvlqvqa.html

Go:   // 双指针从两端比较
来源：http://dali.hysaishi.cn/Article/details/gtsmljsvve.html

Ruby: s == s.reverse
来源：http://dali.xuetiantiany.cn/Article/details/gtwvimibyv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xylfe.cn/Article/details/gtsmthtbec.html

[N07] 两数之和（返回下标）
来源：http://dali.yj202588.top/Article/details/gtnsjsrwmx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.daxiang520.top/Article/details/gtadiwcsep.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.havefunace.top/Article/details/gtkeecjhha.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.feifeiyinyue.top/Article/details/gtlpxasdyy.html

TS:   // 手写 Map<string, number>
来源：http://dali.redwolf501.top/Article/details/gtwentycds.html

Java: // 手写 HashMap
来源：http://dali.ydzc1.top/Article/details/gtzkpebmwy.html

Go:   // 手写 map[int]int
来源：http://dali.c1oappe.top/Article/details/gtxsdvffty.html

Ruby: // 手写 Hash
来源：http://dali.zdqjudy.top/Article/details/gtrevwaqhk.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sufxvd.cn/Article/details/gtgusdtfib.html

[N08] 生成全排列
来源：http://dali.pycfn.com/Article/details/gtshanprhk.html


<!-- 参考信息 -->