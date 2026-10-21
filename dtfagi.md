代发 wailian999

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zdqjudy.top/Article/details/gtjmcvrtqr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.chenlongwang.top/Article/details/gtnyzvveii.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xylfe.cn/Article/details/gtykpacwjq.html

[J10] 取今天 / 本月第一天
来源：http://dali.vqdsnc.cn/Article/details/gtzixzywcq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jianghu66.top/Article/details/gtvoplevcs.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yuanzhike.top/Article/details/gtnhnmxjvd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhongyouzk.top/Article/details/gtlrfyyjwi.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yongpay.top/Article/details/gtrjdyoivy.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtblczdkkz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jqgfzy.top/Article/details/gtnopxvvvw.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.pycfn.com/Article/details/gthvbdvyzk.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hammf.cn/Article/details/gtgfwzewzg.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtneushjgz.html

K. JSON 与序列化
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpppujcck.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtfeybuobz.html

[K01] 对象转 JSON 字符串
来源：http://dali.nanxuanxn.top/Article/details/gtwtxmanyc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinqigufen.top/Article/details/gtuypkbuie.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ybcxt.top/Article/details/gtbyqirbik.html

JS:   JSON.stringify(obj)
来源：http://dali.ppjwa.cn/Article/details/gteoyhuajr.html

TS:   JSON.stringify(obj)
来源：http://dali.chenlongwang.top/Article/details/gtfysvwcxt.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.meibo888.top/Article/details/gtbdmudvjo.html

Go:   json.Marshal(obj)
来源：http://dali.ppjwa.cn/Article/details/gtwagvstpt.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sufxvd.cn/Article/details/gtntpiawuu.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtwsnxmicf.html

[K02] JSON 字符串转对象
来源：http://dali.xinyue.icu/Article/details/gtpkgmicxs.html

Py:   json.loads(s)
来源：http://dali.tanke756.top/Article/details/gtxpoeizip.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.bjfxy.top/Article/details/gtrhoqcqnj.html

JS:   JSON.parse(s)
来源：http://dali.gogol.net.cn/Article/details/gtpuqkcvxt.html

TS:   JSON.parse(s)
来源：http://dali.dashuyun.cn/Article/details/gtyiqoibsh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gtaclqryme.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jianghu66.top/Article/details/gtqkqhlybk.html

Ruby: JSON.parse(s)
来源：http://dali.smart0.xyz/Article/details/gthbhoikwg.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.redwolf501.top/Article/details/gtwxslgyyl.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhongyouzk.top/Article/details/gtdiljqqiq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yuxming.cn/Article/details/gtohdmocnq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhongyouzk.top/Article/details/gtvmpztioi.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxuanxn.top/Article/details/gtavwmykam.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.fzhhl.top/Article/details/gtzaxboble.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tanke756.top/Article/details/gttcdokxkc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinqigfzy.top/Article/details/gtwidjlthy.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gthoagdrut.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxqwgevfv.html

[K04] 读取 JSON 文件
来源：http://dali.nanxuanxn.top/Article/details/gtjgzwnbdi.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ehwqpu.com/Article/details/gtwajijiab.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhiwuduotai.top/Article/details/gttfradaca.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jqgufenzy.top/Article/details/gtbofbselu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xylfe.cn/Article/details/gtwvodaqhe.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hfpthk.cn/Article/details/gtgijbadhv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ehwqpu.com/Article/details/gtrwegqgxz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hywenlv.cn/Article/details/gtmgidjogh.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xuanzx.com/Article/details/gtrvwbqfol.html

[K05] 深拷贝对象
来源：http://dali.xinyue.icu/Article/details/gtjowdsikk.html

Py:   copy.deepcopy(obj)
来源：http://dali.nwbrower.top/Article/details/gtydznvzdn.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hongshengwenyu.top/Article/details/gtcqglzesf.html

JS:   structuredClone(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtuikblgxx.html

TS:   structuredClone(obj)
来源：http://dali.yangfankeji.com/Article/details/gtrkxyqsmv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shzxlz.cn/Article/details/gtlxxsjpzz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.pycfn.com/Article/details/gtrkzxoopz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.birdmap.top/Article/details/gtyciplfea.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhiwuduotai.top/Article/details/gtuzlvdubk.html

[K06] 解析 URL 查询串
来源：http://dali.feifeiyinyue.top/Article/details/gtgkvmzjka.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jqgufenzy.top/Article/details/gtvbpfixrv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ydzc1.top/Article/details/gtmanmqaqf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sxryk.cn/Article/details/gtooxneglb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ydzc1.top/Article/details/gtulnpccuw.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhiwuduotai.top/Article/details/gtdmitrgxt.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sufxvd.cn/Article/details/gtcmzppvcf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jiagoushi.top/Article/details/gtszsxxped.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.tianlin.xyz/Article/details/gtjpxezcaw.html

[K07] 进制转换
来源：http://dali.gaohongyu789.top/Article/details/gtevbdazys.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtnwgfgatr.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.snrcjt.cn/Article/details/gtokiykphf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gtpeuxrhgz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtotcrjkpl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gtaicykgev.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.daxiang520.top/Article/details/gtdwuhzukd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hammf.cn/Article/details/gtjypuirej.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gttvjenxlu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yangfankeji.com/Article/details/gtwuagjduk.html

Py:   pickle.dumps(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtembzmstt.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtngpecagp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yuxming.cn/Article/details/gtfrxxwono.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zycfv.cn/Article/details/gtvgxtznss.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwzpxphcq.html

Go:   encoding/gob
来源：http://dali.jqgufenzy.top/Article/details/gtkwswyopc.html

Ruby: Marshal.dump(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gthymgsqdk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gogol.net.cn/Article/details/gtmdzpjvxl.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtzzkqdqux.html

L. 网络请求
来源：http://dali.ehwqpu.com/Article/details/gtzichdrkc.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtywuhvxda.html

[L01] 发送 GET 请求
来源：http://dali.pycfn.com/Article/details/gtskkjfbwn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sysykeji.top/Article/details/gtxwofzkei.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sweek.top/Article/details/gtwmouwysv.html

JS:   await fetch(url)
来源：http://dali.yuanzhike.top/Article/details/gtoeruxzdm.html

TS:   await fetch(url)
来源：http://dali.aibaodan.cn/Article/details/gthdixbljv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hongshengwenyu.top/Article/details/gtjfieetrl.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinqigufen.top/Article/details/gtwxygzamd.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.daxiang520.top/Article/details/gtljpumxxu.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cashguo.top/Article/details/gtqyfrfiny.html

[L02] 发送 POST JSON
来源：http://dali.aibaodan.cn/Article/details/gtoonzwlec.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zycfv.cn/Article/details/gtyrzqjllw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ybcxt.top/Article/details/gtyiecjjpw.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yongpay.top/Article/details/gtojrpkiek.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yvedp.cn/Article/details/gthlutcpqn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhixingplan.top/Article/details/gtfmmtkids.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sweek.top/Article/details/gtifhkmtpi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ybcxt.top/Article/details/gtnhqaczfo.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hongshengwenyu.top/Article/details/gtcyiwtadj.html

[L03] 设置自定义请求头
来源：http://dali.jyoumei.cn/Article/details/gtogagmcil.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.9152youxi.cn/Article/details/gthwijhrnf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.mhx1999.top/Article/details/gtyawsqnqq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhongyouzk.top/Article/details/gtxetekknv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fengsongda.top/Article/details/gtmiimdruj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.kuanghao11.cn/Article/details/gtfqbkqugr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.feifeiyinyue.top/Article/details/gtmiffxvhx.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.nanxinkj.top/Article/details/gtjcbfiakj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.fengsongda.top/Article/details/gthdzxgeaz.html

[L04] 设置超时
来源：http://dali.xziqi.cn/Article/details/gtrhewnjcb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.sysykeji.top/Article/details/gtmtziyjky.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ehwqpu.com/Article/details/gthpvwszua.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.svipenyu.cn/Article/details/gtnropykwm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ivvv.top/Article/details/gtggdrwjqk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ivvv.top/Article/details/gtxiaaovkg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.dashuyun.cn/Article/details/gtwoszwikt.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.andypj.xyz/Article/details/gtenpinsbu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shangyingyoupin.top/Article/details/gttukngulw.html

[L05] 上传文件（multipart）
来源：http://dali.wangshuangyany.cn/Article/details/gtlrazzbfk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhongyouzk.top/Article/details/gtcbrzhnzf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.smart0.xyz/Article/details/gtiysurdzg.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yongpay.top/Article/details/gttczckblm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258888.top/Article/details/gtockmjlcc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cucudq.cn/Article/details/gtdjzxckwl.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shuidangran.top/Article/details/gtxmwrbhqb.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yj202588.top/Article/details/gtualnvmrg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hnqzz.top/Article/details/gtmioiatgl.html

[L06] 解析响应为 JSON
来源：http://dali.zdqjudy.top/Article/details/gtawgnflku.html

Py:   resp.json()
来源：http://dali.cheryme.top/Article/details/gteqcvkode.html

PHP:  json_decode($body, true);
来源：http://dali.zhongyouzk.top/Article/details/gthhyrajvy.html

JS:   await resp.json()
来源：http://dali.316326.xyz/Article/details/gtuninqbvu.html

TS:   await resp.json()
来源：http://dali.cucudq.cn/Article/details/gtlbppqotv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtefbdrzce.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sufxvd.cn/Article/details/gttiflvyfy.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xinyue.icu/Article/details/gtgxktbaws.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nanxinkj.top/Article/details/gtaaogekyx.html

[L07] 处理 HTTP 状态码
来源：http://dali.jqgufenzy.top/Article/details/gtpfavitki.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.guowangkeji.top/Article/details/gtulwzpdfb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.vqdsnc.cn/Article/details/gtmjuukflb.html

JS:   resp.ok;  resp.status
来源：http://dali.yonumen.top/Article/details/gtrxoethnf.html

TS:   resp.ok;  resp.status
来源：http://dali.hysaishi.cn/Article/details/gtzzipahhb.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gtbitwuftq.html

Go:   resp.StatusCode
来源：http://dali.shanyushiyangtech.top/Article/details/gtidyxdxpd.html

Ruby: resp.code.to_i
来源：http://dali.dashuyun.cn/Article/details/gtirztqyla.html

C#:   (int)resp.StatusCode
来源：http://dali.hongshengwenyu.top/Article/details/gtabqillhn.html

[L08] 并发请求多个地址
来源：http://dali.nwbrower.top/Article/details/gthdoeovtt.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.0kj1m.cn/Article/details/gtxlievhtm.html

PHP:  curl_multi_init() 系列
来源：http://dali.tanke756.top/Article/details/gtpwxleckg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shuidangran.top/Article/details/gttidyvcic.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gthfewaold.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cheryme.top/Article/details/gtkkycbtsu.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ppjwa.cn/Article/details/gtnuxlelqr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sweek.top/Article/details/gtazewucsw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tanke756.top/Article/details/gtldnhlflt.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtmysfbpec.html

M. 命令行 / 进程 / 环境
来源：http://dali.gaohongyu789.top/Article/details/gtkciagezr.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtlbwodcnm.html

[M01] 读取命令行参数
来源：http://dali.yvedp.cn/Article/details/gtdyabrfck.html

Py:   sys.argv[1:]
来源：http://dali.yvedp.cn/Article/details/gtchetcklu.html

PHP:  $argv;  $argc;
来源：http://dali.316326.xyz/Article/details/gtmbrwfoct.html

JS:   process.argv.slice(2)
来源：http://dali.redwolf501.top/Article/details/gtgqippoie.html

TS:   process.argv.slice(2)
来源：http://dali.aibaodan.cn/Article/details/gtcthrcmqx.html

Java: args 数组（main 方法参数）
来源：http://dali.nwbrower.top/Article/details/gtrlgjlblw.html

Go:   os.Args[1:]
来源：http://dali.tianlin.xyz/Article/details/gtjjzecvuu.html

Ruby: ARGV
来源：http://dali.shanyushiyangtech.top/Article/details/gtgujtzijm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrbglyhhg.html

[M02] 读取环境变量
来源：http://dali.jqgufenzy.top/Article/details/gtmkprzaux.html

Py:   os.environ.get("HOME")
来源：http://dali.jyoumei.cn/Article/details/gthirshuzc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.birdmap.top/Article/details/gtkcxdqjdy.html

JS:   process.env.HOME
来源：http://dali.feifeiyinyue.top/Article/details/gtvpdqdpmc.html

TS:   process.env.HOME
来源：http://dali.fengsongda.top/Article/details/gtsqfyxrky.html

Java: System.getenv("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gtuxoibdrv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.iojbl.cn/Article/details/gtuhcqykhm.html

Ruby: ENV["HOME"]
来源：http://dali.hongshengwenyu.top/Article/details/gtqzvvxiam.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgomrmhob.html

[M03] 执行外部命令
来源：http://dali.fengsongda.top/Article/details/gtqcimweuj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hnqzz.top/Article/details/gtvypoejgv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtthiisbtf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zdqjudy.top/Article/details/gtepagvvuj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuetiantiany.cn/Article/details/gtefjewfxy.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhengqikj.top/Article/details/gtkmdsigjv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hammf.cn/Article/details/gtdftsoqqg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hnxiangtu.top/Article/details/gtkhblxymg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yuxming.cn/Article/details/gtisbymhtx.html

[M04] 获取当前工作目录
来源：http://dali.wangshuangyany.cn/Article/details/gttthaqexg.html

Py:   os.getcwd()
来源：http://dali.wangshuangyany.cn/Article/details/gthgxjsmdi.html

PHP:  getcwd();
来源：http://dali.tian-w.cn/Article/details/gtppyxxccq.html

JS:   process.cwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gttvmyfimp.html

TS:   process.cwd()
来源：http://dali.vqdsnc.cn/Article/details/gtownnghiv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenjidiqi.icu/Article/details/gthaljdvpf.html

Go:   os.Getwd()
来源：http://dali.sysykeji.top/Article/details/gtcaokmudv.html

Ruby: Dir.pwd
来源：http://dali.hysaishi.cn/Article/details/gtqhxfjxhs.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jyoumei.cn/Article/details/gteyvouszl.html

[M05] 设置退出码
来源：http://dali.pycfn.com/Article/details/gtyljkddyz.html

Py:   sys.exit(1)
来源：http://dali.meibo888.top/Article/details/gtbjhldemq.html

PHP:  exit(1);
来源：http://dali.fengsongda.top/Article/details/gtiufjxnnd.html

JS:   process.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gtbmbdcoee.html

TS:   process.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gtkrcsarir.html

Java: System.exit(1)
来源：http://dali.zycfv.cn/Article/details/gtegsuqebf.html

Go:   os.Exit(1)
来源：http://dali.yongpay.top/Article/details/gtosouqhdp.html

Ruby: exit 1
来源：http://dali.jinqigufen.top/Article/details/gtpigzxiuu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.dashuyun.cn/Article/details/gtmdyatzdx.html

[M06] 向标准错误输出
来源：http://dali.ppjwa.cn/Article/details/gtyrwbebxl.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cashguo.top/Article/details/gtsrmmuohk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.nanxuanxn.top/Article/details/gtigawxxbh.html

JS:   console.error("err")
来源：http://dali.chenjidiqi.icu/Article/details/gtrcduxllv.html

TS:   console.error("err")
来源：http://dali.tanke756.top/Article/details/gttlldhgqb.html

Java: System.err.println("err")
来源：http://dali.ybcxt.top/Article/details/gteaadpxzo.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gteomxbwdl.html

Ruby: warn "err"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtochjgsrb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hysaishi.cn/Article/details/gtazfsqbnk.html

[M07] 判断是否为主入口
来源：http://dali.feifeiyinyue.top/Article/details/gtecvzjuxi.html

Py:   if __name__ == "__main__":
来源：http://dali.meibo888.top/Article/details/gtgqpfekwl.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.0kj1m.cn/Article/details/gtzxqgxorv.html

JS:   require.main === module
来源：http://dali.yangfankeji.com/Article/details/gtoxszehzp.html

TS:   require.main === module
来源：http://dali.vqdsnc.cn/Article/details/gtqfpthxrd.html

Java: public static void main(String[] args)
来源：http://dali.hysaishi.cn/Article/details/gtpxhewsnt.html

Go:   func main()
来源：http://dali.aibaodan.cn/Article/details/gthsdzxnvl.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tanke756.top/Article/details/gtxsjxitop.html

C#:   static void Main(string[] args)
来源：http://dali.ivvv.top/Article/details/gtiudogubl.html

[M08] 获取系统与运行时信息
来源：http://dali.yueranfly.top/Article/details/gtkuwacegx.html

Py:   platform.system();  platform.python_version()
来源：http://dali.tian-w.cn/Article/details/gtbzjzmhcj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yj20258.top/Article/details/gtkgsblcod.html

JS:   process.platform;  process.version
来源：http://dali.wangdashe.top/Article/details/gtfkrmmlue.html

TS:   process.platform;  process.version
来源：http://dali.shanyushiyangtech.top/Article/details/gttwldmfqr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yj20258888.top/Article/details/gtzvzpyjcc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cdnleiting.top/Article/details/gtjbxgapth.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.andypj.xyz/Article/details/gtoqvkkbga.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yonumen.top/Article/details/gthlshluxv.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtxoxetmtv.html

N. 数据结构与算法
来源：http://dali.hnqzz.top/Article/details/gtpyvvmwoa.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtsgzymfls.html

[N01] 二分查找（有序数组）
来源：http://dali.xylfe.cn/Article/details/gtgyrwaxth.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.fzhhl.top/Article/details/gtycjncczc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.gzhubu.top/Article/details/gtphlybqnt.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.c1oappe.top/Article/details/gtxokzlrzm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnqzz.top/Article/details/gthiukqitz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtcmvvvqpe.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtzialutqj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj20258.top/Article/details/gtomraoyoc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtljnjsbmw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ppjwa.cn/Article/details/gtynwsflwl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gzhubu.top/Article/details/gtoxjbusls.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.svipenyu.cn/Article/details/gtquirshdl.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xinyue.icu/Article/details/gtmkyjigmt.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tanke756.top/Article/details/gtgmqfcqro.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ivvv.top/Article/details/gtpfmhjqeb.html

Go:   slices.Sort(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtryzguasg.html

Ruby: arr.sort
来源：http://dali.zhongyouzk.top/Article/details/gtwwiejcmd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.nwbrower.top/Article/details/gtxogwcnlr.html

[N03] 快速排序（分治示例）
来源：http://dali.smart0.xyz/Article/details/gtddgbtvbw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.guannengcc.top/Article/details/gtbxyzddhl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shangyingyoupin.top/Article/details/gttrwbtbpu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tianlin.xyz/Article/details/gtwbqvrkgw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.svipenyu.cn/Article/details/gtdigprnfq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jyoumei.cn/Article/details/gtqlnczwxx.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.fzhhl.top/Article/details/gtfpqueiqn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.svipenyu.cn/Article/details/gtqmvdnhrt.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gttrdrmobc.html

[N04] 斐波那契数列
来源：http://dali.hnxiangtu.top/Article/details/gtkvjikyct.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jqgufenzy.top/Article/details/gtnnneyesm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gotoacloud.top/Article/details/gtxmlkxdof.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtctjcjwns.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gtgqgqyyzx.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.nanxuanxn.top/Article/details/gtejyimfow.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xuanzx.com/Article/details/gthtktqdcg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhengqikj.top/Article/details/gthfznnnlc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gtceprlspr.html

[N05] 最大公约数
来源：http://dali.yvedp.cn/Article/details/gtvaptpiyr.html

Py:   math.gcd(a, b)
来源：http://dali.iojbl.cn/Article/details/gtoqzjultc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gogol.net.cn/Article/details/gtdpdfpccd.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gaohongyu789.top/Article/details/gtxwnulica.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhixingplan.top/Article/details/gtovgvkeqw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shanyushiyangtech.top/Article/details/gtgfezejzu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yj202588.top/Article/details/gtqurvtaxg.html

Ruby: a.gcd(b)
来源：http://dali.chenlongwang.top/Article/details/gtvlnaluek.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.nanxuanxn.top/Article/details/gtyhpmiduk.html

[N06] 判断回文字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtgnttbapo.html

Py:   s == s[::-1]
来源：http://dali.wangshuangyany.cn/Article/details/gtrywebtsg.html

PHP:  $s === strrev($s);
来源：http://dali.c1oappe.top/Article/details/gtykrgnkft.html

JS:   s === [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtguztaylz.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gtwnjmryhi.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.aibaodan.cn/Article/details/gtaaygpmxj.html

Go:   // 双指针从两端比较
来源：http://dali.zhiwuduotai.top/Article/details/gteyvzaezm.html

Ruby: s == s.reverse
来源：http://dali.xuanzx.com/Article/details/gtsuwskuia.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.0kj1m.cn/Article/details/gtmmpburof.html

[N07] 两数之和（返回下标）
来源：http://dali.cashguo.top/Article/details/gtqvggifvk.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jinqigufen.top/Article/details/gttnfvveuw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhoulong.xyz/Article/details/gtgvjabwbd.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jianghu66.top/Article/details/gtbzpozmcb.html

TS:   // 手写 Map<string, number>
来源：http://dali.tanke756.top/Article/details/gtqslmihxs.html

Java: // 手写 HashMap
来源：http://dali.zhixingplan.top/Article/details/gtreusvwdv.html


<!-- 参考信息 -->