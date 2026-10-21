代发 wailian999

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ybcxt.top/Article/details/gttgeshmqy.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.chenlongwang.top/Article/details/gthudfutyq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinqigufen.top/Article/details/gtkliurata.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ivvv.top/Article/details/gtauixbrgp.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.tanke756.top/Article/details/gtisfrazba.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jlsjyb.cn/Article/details/gtbkkdakyt.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tian-w.cn/Article/details/gtzcjnrxkn.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shzxlz.cn/Article/details/gtidccraql.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoipukzuo.html

K. JSON 与序列化
来源：http://dali.aibaodan.cn/Article/details/gtprkvuqfc.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtthyouixd.html

[K01] 对象转 JSON 字符串
来源：http://dali.ybcxt.top/Article/details/gtxhdonevu.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shzxlz.cn/Article/details/gtyzuywlbx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinghuilouyu.cn/Article/details/gtbqzazcwx.html

JS:   JSON.stringify(obj)
来源：http://dali.wangdashe.top/Article/details/gtqpftykid.html

TS:   JSON.stringify(obj)
来源：http://dali.zhixingplan.top/Article/details/gtwfofbveo.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.andypj.xyz/Article/details/gtxmaznjro.html

Go:   json.Marshal(obj)
来源：http://dali.chenlongwang.top/Article/details/gttdhmogjs.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zycfv.cn/Article/details/gtjduazcss.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jlsjyb.cn/Article/details/gthzsrohyu.html

[K02] JSON 字符串转对象
来源：http://dali.c1oappe.top/Article/details/gtmsamjbzr.html

Py:   json.loads(s)
来源：http://dali.xylfe.cn/Article/details/gtswqhmrtv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhoulong.xyz/Article/details/gtabzdydxe.html

JS:   JSON.parse(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpbgivjko.html

TS:   JSON.parse(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjysejhdd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xuanzx.com/Article/details/gtypxsszgw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.nanxuanxn.top/Article/details/gtynffibrz.html

Ruby: JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtfnyfhxpn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.meibo888.top/Article/details/gtuxwqeuii.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.fzhhl.top/Article/details/gtbpebnouq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.dashuyun.cn/Article/details/gtafmymdmp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.haohaochexian.top/Article/details/gtnlwprwch.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenzaomai.com/Article/details/gtvngvymhd.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.aibaodan.cn/Article/details/gtbhhbhtzf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zdqjudy.top/Article/details/gttwsoigfk.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhoulong.xyz/Article/details/gtzmgfnjaj.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yuxming.cn/Article/details/gtbmhivimj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.smart0.xyz/Article/details/gtmbrioeap.html

[K04] 读取 JSON 文件
来源：http://dali.iojbl.cn/Article/details/gtiibhcble.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hnqzz.top/Article/details/gtbtedxeqr.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.c1oappe.top/Article/details/gtrojadgun.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zdqjudy.top/Article/details/gtpuhtwfwn.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gogol.net.cn/Article/details/gtrhkraacu.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yanxiufei.cn/Article/details/gtommhumts.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cheryme.top/Article/details/gtylbbwmxk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cheryme.top/Article/details/gttgisolga.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.0kj1m.cn/Article/details/gtqogenngy.html

[K05] 深拷贝对象
来源：http://dali.hfpthk.cn/Article/details/gtbyqhddoj.html

Py:   copy.deepcopy(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfxayfgkj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jiagoushi.top/Article/details/gtwmzegras.html

JS:   structuredClone(obj)
来源：http://dali.shzxlz.cn/Article/details/gtydnbyegr.html

TS:   structuredClone(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtnxoqlyhl.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cucudq.cn/Article/details/gtzoktavxx.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.haohaochexian.top/Article/details/gteiihdjvn.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.guowangkeji.top/Article/details/gtzytvxyth.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.fzhhl.top/Article/details/gtfjrznlam.html

[K06] 解析 URL 查询串
来源：http://dali.chenjidiqi.icu/Article/details/gtgculhpio.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.tianlin.xyz/Article/details/gtondlkfrc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.daxiang520.top/Article/details/gtjppifkdc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.redwolf501.top/Article/details/gtfbnchkws.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.feifeiyinyue.top/Article/details/gtydqcwhvn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hfpthk.cn/Article/details/gtphnyvwdt.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.redwolf501.top/Article/details/gtuzdsfkjo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xziqi.cn/Article/details/gtkfjltfhg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.tianlin.xyz/Article/details/gtlgtgggpv.html

[K07] 进制转换
来源：http://dali.hnxiangtu.top/Article/details/gtusjhtihy.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gtchbqxluw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cucudq.cn/Article/details/gthaydwhwh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gttzhtydnq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yj202588.top/Article/details/gtviyeegjt.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtqtftuicm.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.aibaodan.cn/Article/details/gtnzslsrhi.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.9152youxi.cn/Article/details/gttabxdjgv.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gtiodgcbkv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hongshengwenyu.top/Article/details/gtzqfxhucc.html

Py:   pickle.dumps(obj)
来源：http://dali.birdmap.top/Article/details/gtxlmduowv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtdvwzhswr.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hongshengwenyu.top/Article/details/gtutfvllxh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.wangdashe.top/Article/details/gtnklfbfia.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yueranfly.top/Article/details/gtjnmpeawa.html

Go:   encoding/gob
来源：http://dali.yuanzhike.top/Article/details/gtacnfpdyo.html

Ruby: Marshal.dump(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtponrmffy.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hammf.cn/Article/details/gtubaozwjs.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtbfsrswmz.html

L. 网络请求
来源：http://dali.0kj1m.cn/Article/details/gtxzujyszw.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtubepqscl.html

[L01] 发送 GET 请求
来源：http://dali.yueranfly.top/Article/details/gtrrlrpzny.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jianghu66.top/Article/details/gtrdzpncwd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.redwolf501.top/Article/details/gtnfeasela.html

JS:   await fetch(url)
来源：http://dali.tanke756.top/Article/details/gtyyisgkvu.html

TS:   await fetch(url)
来源：http://dali.quarkkingdee.top/Article/details/gtppfnqdun.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.fengsongda.top/Article/details/gtlmkaqkxi.html

Go:   resp, err := http.Get(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiyeeseqn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.chenlongwang.top/Article/details/gtjchhmnlw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ydzc1.top/Article/details/gthbnuxumq.html

[L02] 发送 POST JSON
来源：http://dali.chenjidiqi.icu/Article/details/gtqbcxjlns.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.haohaochexian.top/Article/details/gtgpdbobwd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.bjfxy.top/Article/details/gtbqiqkezd.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zycfv.cn/Article/details/gtwskeqnhs.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ydzc1.top/Article/details/gtkkwmcsrd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinqigfzy.top/Article/details/gtzxtnwplu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpctobjod.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yvedp.cn/Article/details/gtwdlvundf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.meibo888.top/Article/details/gtkaeicodq.html

[L03] 设置自定义请求头
来源：http://dali.yonumen.top/Article/details/gthcyitpsw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hysaishi.cn/Article/details/gtpubwvtmb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.fzhhl.top/Article/details/gtqudjivum.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuetiantiany.cn/Article/details/gtagadtfkp.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhengqikj.top/Article/details/gtbdstzlix.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.tianlin.xyz/Article/details/gtextrmiml.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.feifeiyinyue.top/Article/details/gtzzbscmua.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenzaomai.com/Article/details/gtyhnidpgg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gogol.net.cn/Article/details/gtsnmatucl.html

[L04] 设置超时
来源：http://dali.yvedp.cn/Article/details/gtbxzjhepx.html

Py:   requests.get(url, timeout=5)
来源：http://dali.fzhhl.top/Article/details/gtkypbqpnd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.nwbrower.top/Article/details/gtnejepuvz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yanxiufei.cn/Article/details/gttteidhzj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cucudq.cn/Article/details/gtgklsiiga.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.pengpengdd.cyou/Article/details/gthcxfismy.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gzhubu.top/Article/details/gtnxrfpbyo.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sxryk.cn/Article/details/gtmkcuused.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.pycfn.com/Article/details/gttmqvjcoa.html

[L05] 上传文件（multipart）
来源：http://dali.cucudq.cn/Article/details/gtokjlcimv.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinqigufen.top/Article/details/gtyfykysmg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yanxiufei.cn/Article/details/gtqnvyuedg.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.fengsongda.top/Article/details/gtiuyvscaj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinghuilouyu.cn/Article/details/gtemptqulb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jyoumei.cn/Article/details/gthpvlldyi.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.316326.xyz/Article/details/gtclodmttj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.meibo888.top/Article/details/gtwhknleid.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtodchsfnh.html

[L06] 解析响应为 JSON
来源：http://dali.cdnleiting.top/Article/details/gtbbodalzn.html

Py:   resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gthyiqojmu.html

PHP:  json_decode($body, true);
来源：http://dali.jyoumei.cn/Article/details/gtlgoqpiru.html

JS:   await resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gtrqierxck.html

TS:   await resp.json()
来源：http://dali.shuidangran.top/Article/details/gtetqmjkhe.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yueranfly.top/Article/details/gtwntzsxvf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.gzhubu.top/Article/details/gtvtccfdhm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yanxiufei.cn/Article/details/gtwsjiabcs.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjcalvqie.html

[L07] 处理 HTTP 状态码
来源：http://dali.jqgufenzy.top/Article/details/gtiwrlyyok.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.guowangkeji.top/Article/details/gtxcqthkuu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.daria6918.cn/Article/details/gtijpcwkji.html

JS:   resp.ok;  resp.status
来源：http://dali.jlsjyb.cn/Article/details/gtldixcmxk.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gtktodzcsn.html

Java: resp.statusCode()
来源：http://dali.aibaodan.cn/Article/details/gttkltzxni.html

Go:   resp.StatusCode
来源：http://dali.feifeiyinyue.top/Article/details/gtlwfnvred.html

Ruby: resp.code.to_i
来源：http://dali.iojbl.cn/Article/details/gtjozsqmfm.html

C#:   (int)resp.StatusCode
来源：http://dali.jinqigufen.top/Article/details/gtnvxcbecx.html

[L08] 并发请求多个地址
来源：http://dali.wangshuangyany.cn/Article/details/gtpvzysvyc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.redwolf501.top/Article/details/gtrayiwcsk.html

PHP:  curl_multi_init() 系列
来源：http://dali.hywenlv.cn/Article/details/gtilohukwh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ppjwa.cn/Article/details/gtnqjkndmi.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gtcyuhjdmd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ybcxt.top/Article/details/gtgsulmrkp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.snrcjt.cn/Article/details/gtyhcsezxp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jiagoushi.top/Article/details/gtswszzxbd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpffwwtst.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtwizsykyi.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenzaomai.com/Article/details/gtbaapzowc.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtjllbcaio.html

[M01] 读取命令行参数
来源：http://dali.yangfankeji.com/Article/details/gtncogdwxu.html

Py:   sys.argv[1:]
来源：http://dali.kuanghao11.cn/Article/details/gtxfdfawnh.html

PHP:  $argv;  $argc;
来源：http://dali.hfpthk.cn/Article/details/gtagocjpmt.html

JS:   process.argv.slice(2)
来源：http://dali.nanxuanxn.top/Article/details/gtgcnbknaj.html

TS:   process.argv.slice(2)
来源：http://dali.nwbrower.top/Article/details/gtqcichyfz.html

Java: args 数组（main 方法参数）
来源：http://dali.hnqzz.top/Article/details/gtdgwdiphm.html

Go:   os.Args[1:]
来源：http://dali.yueranfly.top/Article/details/gtzikqwbax.html

Ruby: ARGV
来源：http://dali.fengsongda.top/Article/details/gtriunlbqz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.nwbrower.top/Article/details/gtxfevlqov.html

[M02] 读取环境变量
来源：http://dali.feifeiyinyue.top/Article/details/gtxlusaqcr.html

Py:   os.environ.get("HOME")
来源：http://dali.0kj1m.cn/Article/details/gtpcgqhdzr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.fengsongda.top/Article/details/gtbmxmoxwc.html

JS:   process.env.HOME
来源：http://dali.meibo888.top/Article/details/gtkjdocqdm.html

TS:   process.env.HOME
来源：http://dali.haohaochexian.top/Article/details/gtwpazbrgs.html

Java: System.getenv("HOME")
来源：http://dali.ppjwa.cn/Article/details/gtaouofacf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.tanke756.top/Article/details/gtmfifmzhq.html

Ruby: ENV["HOME"]
来源：http://dali.yj202588.top/Article/details/gtzdmbjatj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yueranfly.top/Article/details/gtgqfurvwv.html

[M03] 执行外部命令
来源：http://dali.feifeiyinyue.top/Article/details/gtsqxpxhbv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.0kj1m.cn/Article/details/gtwqjagxmx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yangfankeji.com/Article/details/gtnjgwuaoe.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtbjnyaaof.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xinyue.icu/Article/details/gtgfxnhkqy.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.havefunace.top/Article/details/gtbzrbylak.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hammf.cn/Article/details/gtosvnsabs.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ybcxt.top/Article/details/gtpfyviamd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gotoacloud.top/Article/details/gtagdzacsy.html

[M04] 获取当前工作目录
来源：http://dali.cucudq.cn/Article/details/gtyiokwhve.html

Py:   os.getcwd()
来源：http://dali.pycfn.com/Article/details/gtcenuopvr.html

PHP:  getcwd();
来源：http://dali.jlsjyb.cn/Article/details/gtsycnsryz.html

JS:   process.cwd()
来源：http://dali.yvedp.cn/Article/details/gtrgeloari.html

TS:   process.cwd()
来源：http://dali.aizwys.cn/Article/details/gthqnjjllc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xuetiantiany.cn/Article/details/gtgptaydvc.html

Go:   os.Getwd()
来源：http://dali.jlsjyb.cn/Article/details/gtwqhzsxta.html

Ruby: Dir.pwd
来源：http://dali.yongpay.top/Article/details/gtdxpobiqa.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhixingplan.top/Article/details/gtxmwrvtaw.html

[M05] 设置退出码
来源：http://dali.sxryk.cn/Article/details/gtkiwhmrnf.html

Py:   sys.exit(1)
来源：http://dali.sxryk.cn/Article/details/gthdwzezpe.html

PHP:  exit(1);
来源：http://dali.guowangkeji.top/Article/details/gtkxmjxdoq.html

JS:   process.exit(1)
来源：http://dali.mhx1999.top/Article/details/gtanxpbpve.html

TS:   process.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gtqhqykagd.html

Java: System.exit(1)
来源：http://dali.fengsongda.top/Article/details/gtzwsrgnrp.html

Go:   os.Exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtzmhckadr.html

Ruby: exit 1
来源：http://dali.xylfe.cn/Article/details/gtaqgqnjjj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.tanke756.top/Article/details/gteahmzntz.html

[M06] 向标准错误输出
来源：http://dali.cucudq.cn/Article/details/gtaglbqmoj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.redwolf501.top/Article/details/gtchlmisla.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.guannengcc.top/Article/details/gtbaqsoghs.html

JS:   console.error("err")
来源：http://dali.hywenlv.cn/Article/details/gtxnlowzzz.html

TS:   console.error("err")
来源：http://dali.zycfv.cn/Article/details/gtfittmlwy.html

Java: System.err.println("err")
来源：http://dali.zhiwuduotai.top/Article/details/gtqriosktd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjywcssry.html

Ruby: warn "err"
来源：http://dali.sufxvd.cn/Article/details/gtamcmejgj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xuanzx.com/Article/details/gtlpdffwrh.html

[M07] 判断是否为主入口
来源：http://dali.gogol.net.cn/Article/details/gtfdrwvldi.html

Py:   if __name__ == "__main__":
来源：http://dali.haohaochexian.top/Article/details/gtzceugyfw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yj20258.top/Article/details/gtgrkgetdj.html

JS:   require.main === module
来源：http://dali.jqgfzy.top/Article/details/gtlkwallgv.html

TS:   require.main === module
来源：http://dali.ppjwa.cn/Article/details/gtxvmvivpc.html

Java: public static void main(String[] args)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfvtqvomf.html

Go:   func main()
来源：http://dali.jianghu66.top/Article/details/gtnnpzanyz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jinqigfzy.top/Article/details/gtlxkerrci.html

C#:   static void Main(string[] args)
来源：http://dali.hnqzz.top/Article/details/gttmvakbqe.html

[M08] 获取系统与运行时信息
来源：http://dali.sxryk.cn/Article/details/gtrebrxvcy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jiagoushi.top/Article/details/gttrnxutja.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.nwbrower.top/Article/details/gtiuusbrfj.html

JS:   process.platform;  process.version
来源：http://dali.gzhubu.top/Article/details/gtufqupsyh.html

TS:   process.platform;  process.version
来源：http://dali.yj20258.top/Article/details/gtlbwgvwtb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yuanzhike.top/Article/details/gtdozpxhcp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.havefunace.top/Article/details/gtrnfoymrm.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yj20258888.top/Article/details/gtqfwynxrr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.0kj1m.cn/Article/details/gtoqwuahwi.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbgrnfwgr.html

N. 数据结构与算法
来源：http://dali.yueranfly.top/Article/details/gtdfrxhzky.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtyvrxeprs.html

[N01] 二分查找（有序数组）
来源：http://dali.hywenlv.cn/Article/details/gtmkbebjgr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlcbeaxkz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtltucowze.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.0kj1m.cn/Article/details/gtvjywdbyw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtliflykfk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtcwtmaiuy.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtyesonqkp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.daxiang520.top/Article/details/gtxbqecxvv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ivvv.top/Article/details/gtnrordcnb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sweek.top/Article/details/gtgoqxovvi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tianlin.xyz/Article/details/gtqmmwmewu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.pycfn.com/Article/details/gtvudkhmsq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhiwuduotai.top/Article/details/gttrtuvxtf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258888.top/Article/details/gtumftmhqq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.gogol.net.cn/Article/details/gtmqullabn.html

Go:   slices.Sort(arr)
来源：http://dali.cqqwz.cn/Article/details/gtgefucxjw.html

Ruby: arr.sort
来源：http://dali.ppjwa.cn/Article/details/gtgvyyjenw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xylfe.cn/Article/details/gtsxgrikur.html

[N03] 快速排序（分治示例）
来源：http://dali.c1oappe.top/Article/details/gtesyrvbrx.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.havefunace.top/Article/details/gtfkosyhow.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zdqjudy.top/Article/details/gtdhwdooen.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sweek.top/Article/details/gtkvjniars.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangdashe.top/Article/details/gtwtuawlqh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jianghu66.top/Article/details/gtteyksoav.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jyoumei.cn/Article/details/gtywqdqtss.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.fengsongda.top/Article/details/gtwbznyjqj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.smart0.xyz/Article/details/gtrdgndryl.html

[N04] 斐波那契数列
来源：http://dali.zycfv.cn/Article/details/gtlrjhgvpb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.daria6918.cn/Article/details/gtvhnbtfon.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.9152youxi.cn/Article/details/gtaasrwwpv.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.meibo888.top/Article/details/gtvzhcqosm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.havefunace.top/Article/details/gtrabscbmy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmeaigumg.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.guannengcc.top/Article/details/gtqqmvnsul.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jyoumei.cn/Article/details/gtoygwlgyl.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gtrldwltrq.html

[N05] 最大公约数
来源：http://dali.sufxvd.cn/Article/details/gtxqidzxeg.html

Py:   math.gcd(a, b)
来源：http://dali.jiagoushi.top/Article/details/gtpnfiloua.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.snrcjt.cn/Article/details/gttfnxbkcf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shzxlz.cn/Article/details/gthdqxfxyo.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj202588.top/Article/details/gtjtmarvwu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhongyouzk.top/Article/details/gtzsbgvrpw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.mhx1999.top/Article/details/gtimxqlbpj.html

Ruby: a.gcd(b)
来源：http://dali.yongpay.top/Article/details/gtcrvvteba.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.nanxinkj.top/Article/details/gtoghexswf.html

[N06] 判断回文字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtlqpagupf.html

Py:   s == s[::-1]
来源：http://dali.tianlin.xyz/Article/details/gtaivwrycc.html

PHP:  $s === strrev($s);
来源：http://dali.fzhhl.top/Article/details/gtfzhmhycs.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gtivxqovmz.html

TS:   s === [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gtdujiujto.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jyoumei.cn/Article/details/gtfngfkguv.html

Go:   // 双指针从两端比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnaitirwu.html

Ruby: s == s.reverse
来源：http://dali.tanke756.top/Article/details/gtovgchpol.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.havefunace.top/Article/details/gtcbasdqzn.html

[N07] 两数之和（返回下标）
来源：http://dali.aibaodan.cn/Article/details/gtpwajwgrr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.smart0.xyz/Article/details/gtjlobooym.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.birdmap.top/Article/details/gtyzcftpvq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinqigfzy.top/Article/details/gtfrjnnbka.html

TS:   // 手写 Map<string, number>
来源：http://dali.nanxuanxn.top/Article/details/gthgfxzbnk.html

Java: // 手写 HashMap
来源：http://dali.nwbrower.top/Article/details/gtgfjprtgg.html

Go:   // 手写 map[int]int
来源：http://dali.cucudq.cn/Article/details/gtaolgrvqj.html

Ruby: // 手写 Hash
来源：http://dali.bjfxy.top/Article/details/gtnrudwfzv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jlsjyb.cn/Article/details/gteegagmud.html

[N08] 生成全排列
来源：http://dali.ehwqpu.com/Article/details/gttmiktvoz.html


<!-- 参考信息 -->