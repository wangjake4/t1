代发 wailian999

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.chenzaomai.com/Article/details/gtmqfkuxsp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.bjfxy.top/Article/details/gtzhqneyxj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinghuilouyu.cn/Article/details/gtziurkgyu.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yangfankeji.com/Article/details/gtczodtuim.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtfyzqxhik.html

K. JSON 与序列化
来源：http://dali.guowangkeji.top/Article/details/gtozqvoyau.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtcodqkuxs.html

[K01] 对象转 JSON 字符串
来源：http://dali.nanxuanxn.top/Article/details/gtdurietcv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yuxming.cn/Article/details/gtwoqztpos.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.aizwys.cn/Article/details/gtuowglobc.html

JS:   JSON.stringify(obj)
来源：http://dali.yuxming.cn/Article/details/gtvfgontot.html

TS:   JSON.stringify(obj)
来源：http://dali.pycfn.com/Article/details/gtyxfvluqi.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.bjfxy.top/Article/details/gtposfcukz.html

Go:   json.Marshal(obj)
来源：http://dali.0kj1m.cn/Article/details/gtwzqfkftk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ivvv.top/Article/details/gtjzfiqgqj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.dianchejie.cn/Article/details/gtyznoluna.html

[K02] JSON 字符串转对象
来源：http://dali.jinghuilouyu.cn/Article/details/gtwjszanhb.html

Py:   json.loads(s)
来源：http://dali.sxryk.cn/Article/details/gtqgllqnno.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jqgufenzy.top/Article/details/gtolnviglf.html

JS:   JSON.parse(s)
来源：http://dali.gotoacloud.top/Article/details/gtzogguvdt.html

TS:   JSON.parse(s)
来源：http://dali.jinqigufen.top/Article/details/gthnyfzkmd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gtrlzohjpc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jlsjyb.cn/Article/details/gtpmwjkkgu.html

Ruby: JSON.parse(s)
来源：http://dali.yanxiufei.cn/Article/details/gtnjpdtlpv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.316326.xyz/Article/details/gtwnsaetie.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinqigufen.top/Article/details/gtrumiztkm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.guannengcc.top/Article/details/gtwkvcjbqr.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.redwolf501.top/Article/details/gtrrxeyybz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hywenlv.cn/Article/details/gtifwgkiuz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gtvoersugw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.pycfn.com/Article/details/gtlbbmzpep.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cheryme.top/Article/details/gtqfzsjakf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sufxvd.cn/Article/details/gtspzzemks.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nwbrower.top/Article/details/gtxdldxtcz.html

[K04] 读取 JSON 文件
来源：http://dali.zhongyouzk.top/Article/details/gtksyvxwkg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hammf.cn/Article/details/gtmgaubvxl.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhixingplan.top/Article/details/gtyjrjiwjb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cucudq.cn/Article/details/gtorfkgzmd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.bjfxy.top/Article/details/gtrnuspugj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cheryme.top/Article/details/gtdboqpczq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yj20258888.top/Article/details/gtsivvursu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cdnleiting.top/Article/details/gtjtwhupql.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhiwuduotai.top/Article/details/gtycmjmwnn.html

[K05] 深拷贝对象
来源：http://dali.shzxlz.cn/Article/details/gtgeivzqtq.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtxczieobj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhongyouzk.top/Article/details/gtuqejeink.html

JS:   structuredClone(obj)
来源：http://dali.jyoumei.cn/Article/details/gtixmdiqwe.html

TS:   structuredClone(obj)
来源：http://dali.svipenyu.cn/Article/details/gttizvyrgo.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yj20258888.top/Article/details/gtwpihwfyd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.nanxinkj.top/Article/details/gtzqluuvix.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.kuanghao11.cn/Article/details/gtutbdutnk.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shanyushiyangkeji.top/Article/details/gternkgltn.html

[K06] 解析 URL 查询串
来源：http://dali.tian-w.cn/Article/details/gtudpnjedf.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.feifeiyinyue.top/Article/details/gttpenzsvn.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ivvv.top/Article/details/gteodcwqon.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigfzy.top/Article/details/gtmldhyeej.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cashguo.top/Article/details/gtyohzyndg.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.pycfn.com/Article/details/gtzwexyumj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhoulong.xyz/Article/details/gtyxtqwpwd.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.iojbl.cn/Article/details/gtabiigvvo.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj20258.top/Article/details/gtlgptxaky.html

[K07] 进制转换
来源：http://dali.shangyingyoupin.top/Article/details/gtznarvyyd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.pycfn.com/Article/details/gtlqhpanty.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhengqikj.top/Article/details/gtagsetter.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtjozqrmql.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gtjvhlmnon.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gtnftxnljj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinqigfzy.top/Article/details/gtdeejccip.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.tian-w.cn/Article/details/gtpunqkmfx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtrpsmoqmz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ppjwa.cn/Article/details/gtvjhjkeos.html

Py:   pickle.dumps(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtrurdvlnz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jianghu66.top/Article/details/gtsmcikilr.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.fzhhl.top/Article/details/gtzqvjxsko.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhiwuduotai.top/Article/details/gtmudwrcpg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gotoacloud.top/Article/details/gttaqkcurz.html

Go:   encoding/gob
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlxocfmou.html

Ruby: Marshal.dump(obj)
来源：http://dali.jqgfzy.top/Article/details/gtzunefymg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hnqzz.top/Article/details/gtzqoeqikx.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtoyfjhynt.html

L. 网络请求
来源：http://dali.yueranfly.top/Article/details/gtegfptrdi.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtxwsgbdno.html

[L01] 发送 GET 请求
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfpcdtias.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yj20258.top/Article/details/gtglafvvoh.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.316326.xyz/Article/details/gtouxymdzy.html

JS:   await fetch(url)
来源：http://dali.yj202588.top/Article/details/gthyiunxuu.html

TS:   await fetch(url)
来源：http://dali.nanxinkj.top/Article/details/gtnlqqpjky.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtalszulys.html

Go:   resp, err := http.Get(url)
来源：http://dali.yonumen.top/Article/details/gttozdrtow.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gaohongyu789.top/Article/details/gtkjoqgehh.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhixingplan.top/Article/details/gtrqeqyinw.html

[L02] 发送 POST JSON
来源：http://dali.jyoumei.cn/Article/details/gtgvtyoypi.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ehwqpu.com/Article/details/gtgdlogonl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xylfe.cn/Article/details/gtxhdwfwxc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.316326.xyz/Article/details/gtuuwxnivx.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yonumen.top/Article/details/gtfhazofpq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gotoacloud.top/Article/details/gtxyzpyoni.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnclgpniu.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.nwbrower.top/Article/details/gteoobzkrz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gtejzorhbj.html

[L03] 设置自定义请求头
来源：http://dali.zdqjudy.top/Article/details/gtjdnrmhjt.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.guannengcc.top/Article/details/gtwbrqlbac.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.bjfxy.top/Article/details/gtsgjdwmfp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sweek.top/Article/details/gtfcrgunxw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxinkj.top/Article/details/gtqrqbdgks.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinghuilouyu.cn/Article/details/gtcljgosgb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cucudq.cn/Article/details/gtardlmsck.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shzxlz.cn/Article/details/gtrpvoltdb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcfgugcqn.html

[L04] 设置超时
来源：http://dali.yonumen.top/Article/details/gtnkeolgsc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.chenzaomai.com/Article/details/gtbntwgixl.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shuidangran.top/Article/details/gteobafugr.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ivvv.top/Article/details/gtitkicwgq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yvedp.cn/Article/details/gtzmncjdzb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xinyue.icu/Article/details/gtuhcpmdoe.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sxryk.cn/Article/details/gtluqqoagi.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.nanxinkj.top/Article/details/gtkrmhrfcr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.nanxinkj.top/Article/details/gtoqoczclm.html

[L05] 上传文件（multipart）
来源：http://dali.yvedp.cn/Article/details/gtjloqegkf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.aizwys.cn/Article/details/gtnparehqt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cucudq.cn/Article/details/gtrbhdkpcn.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shuidangran.top/Article/details/gtcnyrayev.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ybcxt.top/Article/details/gtfqszafvc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.9152youxi.cn/Article/details/gtyyriidry.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cashguo.top/Article/details/gtwbvcifqg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cucudq.cn/Article/details/gtyoubxyyk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtinahsshl.html

[L06] 解析响应为 JSON
来源：http://dali.yvedp.cn/Article/details/gtuwkifkkg.html

Py:   resp.json()
来源：http://dali.hongshengwenyu.top/Article/details/gtmsspfzop.html

PHP:  json_decode($body, true);
来源：http://dali.ybcxt.top/Article/details/gtbnofashu.html

JS:   await resp.json()
来源：http://dali.snrcjt.cn/Article/details/gtsgetxlhz.html

TS:   await resp.json()
来源：http://dali.xylfe.cn/Article/details/gtvcenfyuw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenjidiqi.icu/Article/details/gtamrasglq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cucudq.cn/Article/details/gthqpspumf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhongyouzk.top/Article/details/gtlnaxwjdy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.redwolf501.top/Article/details/gtmelynzno.html

[L07] 处理 HTTP 状态码
来源：http://dali.bjfxy.top/Article/details/gtmqkcqgna.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.guowangkeji.top/Article/details/gtoulochfz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.tanke756.top/Article/details/gtdwyeajgs.html

JS:   resp.ok;  resp.status
来源：http://dali.kuanghao11.cn/Article/details/gtruwmqopa.html

TS:   resp.ok;  resp.status
来源：http://dali.guowangkeji.top/Article/details/gtfcehxrdq.html

Java: resp.statusCode()
来源：http://dali.havefunace.top/Article/details/gtotjfyvjg.html

Go:   resp.StatusCode
来源：http://dali.jqgufenzy.top/Article/details/gtobhzmqmd.html

Ruby: resp.code.to_i
来源：http://dali.tianlin.xyz/Article/details/gtgoupsygm.html

C#:   (int)resp.StatusCode
来源：http://dali.dianchejie.cn/Article/details/gtmkkpnjzk.html

[L08] 并发请求多个地址
来源：http://dali.shanyushiyangtech.top/Article/details/gtlvvfnigy.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.svipenyu.cn/Article/details/gtztzcobjf.html

PHP:  curl_multi_init() 系列
来源：http://dali.yj20258888.top/Article/details/gtimbrmeuk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cucudq.cn/Article/details/gtczboslwz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gtgjhpnpga.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sweek.top/Article/details/gtxhjqdepk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.mhx1999.top/Article/details/gtadrwmgor.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.dashuyun.cn/Article/details/gtpjgouais.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gtmkgakebl.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtrsepsgdu.html

M. 命令行 / 进程 / 环境
来源：http://dali.gaohongyu789.top/Article/details/gtdwmzbxwb.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqszwgsyv.html

[M01] 读取命令行参数
来源：http://dali.yangfankeji.com/Article/details/gtdjhqlmqm.html

Py:   sys.argv[1:]
来源：http://dali.hfpthk.cn/Article/details/gtxpquuryn.html

PHP:  $argv;  $argc;
来源：http://dali.yuxming.cn/Article/details/gtgmdvgwey.html

JS:   process.argv.slice(2)
来源：http://dali.hammf.cn/Article/details/gtpoyjondt.html

TS:   process.argv.slice(2)
来源：http://dali.9152youxi.cn/Article/details/gtmzhcivoy.html

Java: args 数组（main 方法参数）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtctqwaemd.html

Go:   os.Args[1:]
来源：http://dali.havefunace.top/Article/details/gtioqdyjzv.html

Ruby: ARGV
来源：http://dali.gogol.net.cn/Article/details/gtxkteamlz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.kuanghao11.cn/Article/details/gtybbcaiir.html

[M02] 读取环境变量
来源：http://dali.pengpengdd.cyou/Article/details/gtnisficza.html

Py:   os.environ.get("HOME")
来源：http://dali.smart0.xyz/Article/details/gtvzyjpqhq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gtbpifuwoo.html

JS:   process.env.HOME
来源：http://dali.aibaodan.cn/Article/details/gtzldkeayt.html

TS:   process.env.HOME
来源：http://dali.tanke756.top/Article/details/gtqpixqjxp.html

Java: System.getenv("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gtqhteswbh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyktrnhjh.html

Ruby: ENV["HOME"]
来源：http://dali.nwbrower.top/Article/details/gtpblloebv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.fengsongda.top/Article/details/gtdugapfnv.html

[M03] 执行外部命令
来源：http://dali.cashguo.top/Article/details/gtzabwylve.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gtytqqnqgs.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.smart0.xyz/Article/details/gtdlxgeagg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.nwbrower.top/Article/details/gtqzbloxhb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zdqjudy.top/Article/details/gtongvnpdv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ybcxt.top/Article/details/gtdjztjdeg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jlsjyb.cn/Article/details/gtzxprwpua.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hysaishi.cn/Article/details/gtvajvnlvw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gaohongyu789.top/Article/details/gthhcbbmct.html

[M04] 获取当前工作目录
来源：http://dali.pengpengdd.cyou/Article/details/gtdmzmrkcw.html

Py:   os.getcwd()
来源：http://dali.gzhubu.top/Article/details/gtvhlfcris.html

PHP:  getcwd();
来源：http://dali.zhongyouzk.top/Article/details/gtqddiawrn.html

JS:   process.cwd()
来源：http://dali.yongpay.top/Article/details/gtlgbzujwq.html

TS:   process.cwd()
来源：http://dali.zhengqikj.top/Article/details/gtfrpmcryc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cheryme.top/Article/details/gtpjedihvt.html

Go:   os.Getwd()
来源：http://dali.jyoumei.cn/Article/details/gthtlksaal.html

Ruby: Dir.pwd
来源：http://dali.feifeiyinyue.top/Article/details/gtkfsnfrwi.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jlsjyb.cn/Article/details/gtcmdircak.html

[M05] 设置退出码
来源：http://dali.ppjwa.cn/Article/details/gtdbzahieb.html

Py:   sys.exit(1)
来源：http://dali.meibo888.top/Article/details/gtykhzzzyy.html

PHP:  exit(1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlkhzrjwx.html

JS:   process.exit(1)
来源：http://dali.yj202588.top/Article/details/gtcdvubejh.html

TS:   process.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gtfbpnrlxe.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtlkcqqnea.html

Go:   os.Exit(1)
来源：http://dali.chenzaomai.com/Article/details/gtsmnvshag.html

Ruby: exit 1
来源：http://dali.haohaochexian.top/Article/details/gtbafjbiva.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shangyingyoupin.top/Article/details/gtqigsange.html

[M06] 向标准错误输出
来源：http://dali.guowangkeji.top/Article/details/gtjydssbsn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yanxiufei.cn/Article/details/gtzyabamtb.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sufxvd.cn/Article/details/gtvkbhejda.html

JS:   console.error("err")
来源：http://dali.cdnleiting.top/Article/details/gthoedbdpq.html

TS:   console.error("err")
来源：http://dali.chenzaomai.com/Article/details/gttwstuoke.html

Java: System.err.println("err")
来源：http://dali.tanke756.top/Article/details/gtrmpldzmd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.aibaodan.cn/Article/details/gtlaemobmf.html

Ruby: warn "err"
来源：http://dali.guannengcc.top/Article/details/gtacytxowv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.andypj.xyz/Article/details/gtrkrskpvd.html

[M07] 判断是否为主入口
来源：http://dali.jyoumei.cn/Article/details/gtwrtxhaat.html

Py:   if __name__ == "__main__":
来源：http://dali.snrcjt.cn/Article/details/gtcdprtyqt.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jianghu66.top/Article/details/gtwsujnmzb.html

JS:   require.main === module
来源：http://dali.xinyue.icu/Article/details/gtbgxljdzp.html

TS:   require.main === module
来源：http://dali.nanxinkj.top/Article/details/gtfzfamkgm.html

Java: public static void main(String[] args)
来源：http://dali.c1oappe.top/Article/details/gtmrdhiaqx.html

Go:   func main()
来源：http://dali.vqdsnc.cn/Article/details/gtaoqvxznz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.andypj.xyz/Article/details/gtbzsmkgnj.html

C#:   static void Main(string[] args)
来源：http://dali.xinyue.icu/Article/details/gttcefkffa.html

[M08] 获取系统与运行时信息
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzccspydt.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jqgfzy.top/Article/details/gtmchgcyal.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yanxiufei.cn/Article/details/gtfwsgiqce.html

JS:   process.platform;  process.version
来源：http://dali.xziqi.cn/Article/details/gtjkcuwsuk.html

TS:   process.platform;  process.version
来源：http://dali.yj20258888.top/Article/details/gtfrvtrovp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yuanzhike.top/Article/details/gtejlokivu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.chenjidiqi.icu/Article/details/gteylfazss.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.havefunace.top/Article/details/gtihbhssyq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.daxiang520.top/Article/details/gtgblrivsv.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtvednkaiw.html

N. 数据结构与算法
来源：http://dali.aizwys.cn/Article/details/gtbutsytpv.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlcvbiakt.html

[N01] 二分查找（有序数组）
来源：http://dali.guowangkeji.top/Article/details/gtfectimst.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.havefunace.top/Article/details/gtorvwhawe.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.dianchejie.cn/Article/details/gtvsymzgzm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cashguo.top/Article/details/gteduwcwcx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dianchejie.cn/Article/details/gtqpfnzirr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtsqcdnxem.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yongpay.top/Article/details/gtarjllxxf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ybcxt.top/Article/details/gtautdbodf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.fzhhl.top/Article/details/gtufixqzij.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hongshengwenyu.top/Article/details/gtgmgaooxm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shangyingyoupin.top/Article/details/gtapktiqvb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhongyouzk.top/Article/details/gtxdktdswc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.9152youxi.cn/Article/details/gtntkubgzx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcplefkpc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xinyue.icu/Article/details/gtylqjzequ.html

Go:   slices.Sort(arr)
来源：http://dali.daria6918.cn/Article/details/gtwlryjqzs.html

Ruby: arr.sort
来源：http://dali.jlsjyb.cn/Article/details/gticcrqloa.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cashguo.top/Article/details/gtuvjijnpp.html

[N03] 快速排序（分治示例）
来源：http://dali.mhx1999.top/Article/details/gtgfbdhvov.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.fengsongda.top/Article/details/gtafwzlkif.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhixingplan.top/Article/details/gtctkyaszm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.0kj1m.cn/Article/details/gtxxfzjnbf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gtsymtxenf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xziqi.cn/Article/details/gtkitfalmh.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.wangshuangyany.cn/Article/details/gtzwokirct.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hammf.cn/Article/details/gtlkyvludt.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yuxming.cn/Article/details/gteybjvyap.html

[N04] 斐波那契数列
来源：http://dali.ehwqpu.com/Article/details/gtxiurvbvu.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hfpthk.cn/Article/details/gtxagdripb.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttbfimfpu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gthsfcgesj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.snrcjt.cn/Article/details/gtmllykzks.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gotoacloud.top/Article/details/gtzrlihbhv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.gotoacloud.top/Article/details/gthlirianp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.quarkkingdee.top/Article/details/gtozvyruyt.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sufxvd.cn/Article/details/gtpzysmocd.html

[N05] 最大公约数
来源：http://dali.yongpay.top/Article/details/gtftrscmfi.html

Py:   math.gcd(a, b)
来源：http://dali.bjfxy.top/Article/details/gtudyxttjt.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hywenlv.cn/Article/details/gtxiqxpczl.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.birdmap.top/Article/details/gtgsqifgjv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daria6918.cn/Article/details/gturitxxcx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yangfankeji.com/Article/details/gtjcewiano.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.aizwys.cn/Article/details/gtnffqsnho.html

Ruby: a.gcd(b)
来源：http://dali.sweek.top/Article/details/gtjngzvsly.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yongpay.top/Article/details/gttfrwgwlp.html

[N06] 判断回文字符串
来源：http://dali.yangfankeji.com/Article/details/gtzgfbyikb.html

Py:   s == s[::-1]
来源：http://dali.jqgufenzy.top/Article/details/gtvxkhvzeh.html

PHP:  $s === strrev($s);
来源：http://dali.zhixingplan.top/Article/details/gtzpkodqfj.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gtltcdpssn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gtaytxekzo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhiwuduotai.top/Article/details/gtlkjsomzk.html

Go:   // 双指针从两端比较
来源：http://dali.hnqzz.top/Article/details/gtgoodohly.html

Ruby: s == s.reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gtlkynvixe.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.iojbl.cn/Article/details/gtlgohncjk.html

[N07] 两数之和（返回下标）
来源：http://dali.hywenlv.cn/Article/details/gtnlxinwqh.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hfpthk.cn/Article/details/gtnxefqrlk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yanxiufei.cn/Article/details/gtsabjnmxf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.316326.xyz/Article/details/gtwgdtxuhs.html

TS:   // 手写 Map<string, number>
来源：http://dali.yuanzhike.top/Article/details/gtqygddawy.html

Java: // 手写 HashMap
来源：http://dali.hongshengwenyu.top/Article/details/gtvqnpgdhc.html

Go:   // 手写 map[int]int
来源：http://dali.cheryme.top/Article/details/gtfvessurm.html

Ruby: // 手写 Hash
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdarfgqrw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zycfv.cn/Article/details/gtffnnwzhf.html

[N08] 生成全排列
来源：http://dali.wangdashe.top/Article/details/gtbteszzin.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtiouunlsc.html

PHP:  // 手写递归交换
来源：http://dali.feifeiyinyue.top/Article/details/gtpricfxxu.html

JS:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gtlshbinsi.html

TS:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gtsfwyjgnc.html


<!-- 参考信息 -->