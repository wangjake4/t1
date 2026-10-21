代发 wailian999

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ehwqpu.com/Article/details/gtgufoaaku.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.meibo888.top/Article/details/gtqmtsoxes.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gzhubu.top/Article/details/gttqmcgybi.html

[J10] 取今天 / 本月第一天
来源：http://dali.xuetiantiany.cn/Article/details/gtywcmkede.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hammf.cn/Article/details/gthmnactjy.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xinyue.icu/Article/details/gtjqiqonfv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.tianlin.xyz/Article/details/gtxhgeadjt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtqmbmvsnr.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hnqzz.top/Article/details/gtyryvqpdh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sxryk.cn/Article/details/gtsxoukhyv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinghuilouyu.cn/Article/details/gtrhbojlgr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ppjwa.cn/Article/details/gtabrecxaa.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtjgynownd.html

K. JSON 与序列化
来源：http://dali.zhixingplan.top/Article/details/gtfjihwmdf.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtafzgwlhs.html

[K01] 对象转 JSON 字符串
来源：http://dali.quarkkingdee.top/Article/details/gtqgkqqipp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhengqikj.top/Article/details/gtardgkavd.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.meibo888.top/Article/details/gtmyisdqgn.html

JS:   JSON.stringify(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxlnfzxvm.html

TS:   JSON.stringify(obj)
来源：http://dali.ivvv.top/Article/details/gtdeuyipln.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.0kj1m.cn/Article/details/gtzfbczjbi.html

Go:   json.Marshal(obj)
来源：http://dali.birdmap.top/Article/details/gtmstydlfv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cheryme.top/Article/details/gtqizphtgf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yuanzhike.top/Article/details/gtknfmgsrc.html

[K02] JSON 字符串转对象
来源：http://dali.zhixingplan.top/Article/details/gtkptpafyw.html

Py:   json.loads(s)
来源：http://dali.jinqigufen.top/Article/details/gtkddmkixz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shuidangran.top/Article/details/gtrjwcuxzu.html

JS:   JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gtamnhtwzc.html

TS:   JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gttsxathqb.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gtuxpagcto.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hammf.cn/Article/details/gtixlxikqk.html

Ruby: JSON.parse(s)
来源：http://dali.cqqwz.cn/Article/details/gtzjjdnoyj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sysykeji.top/Article/details/gtdmpuwxij.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.dashuyun.cn/Article/details/gtuweeuigz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yueranfly.top/Article/details/gtumtvyipk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.feifeiyinyue.top/Article/details/gtturaeett.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.mhx1999.top/Article/details/gtlbklmbxm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ybcxt.top/Article/details/gtxzyoatug.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yj20258888.top/Article/details/gtufidutyb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.wangshuangyany.cn/Article/details/gtljiztkfs.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtytxpezbj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jlsjyb.cn/Article/details/gtjekuptad.html

[K04] 读取 JSON 文件
来源：http://dali.cqqwz.cn/Article/details/gtuqcpovhl.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.haohaochexian.top/Article/details/gtpnfcsriw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.havefunace.top/Article/details/gtbsetoiro.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sxryk.cn/Article/details/gtwmtiovnr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gogol.net.cn/Article/details/gtafhlniix.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.tian-w.cn/Article/details/gtjwagpgzl.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hywenlv.cn/Article/details/gttxvzdrjx.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.nanxinkj.top/Article/details/gtogykmlvz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nwbrower.top/Article/details/gtjffkpxuh.html

[K05] 深拷贝对象
来源：http://dali.birdmap.top/Article/details/gtrnqkrmxp.html

Py:   copy.deepcopy(obj)
来源：http://dali.aibaodan.cn/Article/details/gtbszapsxz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xinyue.icu/Article/details/gthkbuovae.html

JS:   structuredClone(obj)
来源：http://dali.cashguo.top/Article/details/gtdvaxqvgb.html

TS:   structuredClone(obj)
来源：http://dali.bjfxy.top/Article/details/gttiqmnsik.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hywenlv.cn/Article/details/gtqvwpomhh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.nanxuanxn.top/Article/details/gtutajbwud.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xinyue.icu/Article/details/gtfjnaupig.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shanyushiyangkeji.top/Article/details/gtileztuzz.html

[K06] 解析 URL 查询串
来源：http://dali.ppjwa.cn/Article/details/gtxburbslx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cdnleiting.top/Article/details/gtjwgvtqfd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhengqikj.top/Article/details/gtcxzydetg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gttrabiwts.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenjidiqi.icu/Article/details/gteejiezwi.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ppjwa.cn/Article/details/gttdovxtwf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gtzvgomslz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jqgfzy.top/Article/details/gtvcmwhefo.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gtarvzwmsj.html

[K07] 进制转换
来源：http://dali.hfpthk.cn/Article/details/gtppvffpwi.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gtpzwoeoyx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jianghu66.top/Article/details/gtrevasgic.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gtirlebvdu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gtkknsqgim.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gtettchvtx.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.guowangkeji.top/Article/details/gtzxenklnz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.feifeiyinyue.top/Article/details/gtuutqbjxc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtghwczeub.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yuxming.cn/Article/details/gtrgcoyuni.html

Py:   pickle.dumps(obj)
来源：http://dali.jyoumei.cn/Article/details/gtzdwwrhbc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhixingplan.top/Article/details/gtgitqfyvz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.nwbrower.top/Article/details/gtdhcilltv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hfpthk.cn/Article/details/gtpquestbd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.andypj.xyz/Article/details/gtrwcdfxnz.html

Go:   encoding/gob
来源：http://dali.wangshuangyany.cn/Article/details/gtdkejtped.html

Ruby: Marshal.dump(obj)
来源：http://dali.yuxming.cn/Article/details/gtjguzcmic.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shangyingyoupin.top/Article/details/gtlhmhxjfw.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtdkhboujl.html

L. 网络请求
来源：http://dali.birdmap.top/Article/details/gtgoiykflz.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtpndgmtcw.html

[L01] 发送 GET 请求
来源：http://dali.wangdashe.top/Article/details/gtikemphrd.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ybcxt.top/Article/details/gtfpmgljdl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yonumen.top/Article/details/gtmwucgccb.html

JS:   await fetch(url)
来源：http://dali.birdmap.top/Article/details/gtcwnyvkvv.html

TS:   await fetch(url)
来源：http://dali.cucudq.cn/Article/details/gtrggommgo.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xinyue.icu/Article/details/gtxwfvpmdy.html

Go:   resp, err := http.Get(url)
来源：http://dali.jqgfzy.top/Article/details/gthxfygydl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yj202588.top/Article/details/gttgnuqfgc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.snrcjt.cn/Article/details/gttrdrjnao.html

[L02] 发送 POST JSON
来源：http://dali.jinqigfzy.top/Article/details/gtwypjommb.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.vqdsnc.cn/Article/details/gtlsybkwaq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cucudq.cn/Article/details/gtjqkghzzo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhengqikj.top/Article/details/gttdbsybvk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gtvlmmhhfu.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cheryme.top/Article/details/gtqqbpemym.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinghuilouyu.cn/Article/details/gtneoktxtf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinqigufen.top/Article/details/gtapotmtsm.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnfyaxgvr.html

[L03] 设置自定义请求头
来源：http://dali.nwbrower.top/Article/details/gtcellsmhs.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cqqwz.cn/Article/details/gtbjqunyld.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jyoumei.cn/Article/details/gtkbghbddp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xziqi.cn/Article/details/gtysdtfaor.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.haohaochexian.top/Article/details/gtrfjgebom.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hammf.cn/Article/details/gtighrljlj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.havefunace.top/Article/details/gtvplvsnwe.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gzhubu.top/Article/details/gtfsqrrhvi.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.vqdsnc.cn/Article/details/gthulbukkj.html

[L04] 设置超时
来源：http://dali.aibaodan.cn/Article/details/gtflhjsxce.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hammf.cn/Article/details/gtddhiuutw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yj20258.top/Article/details/gtmmkhfxqe.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sweek.top/Article/details/gtescwnkoo.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenjidiqi.icu/Article/details/gtcbdebggr.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hysaishi.cn/Article/details/gtqqrnfcbu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.bjfxy.top/Article/details/gtoyveqvbb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.pengpengdd.cyou/Article/details/gtoxbukwpx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.316326.xyz/Article/details/gtfltfvrdk.html

[L05] 上传文件（multipart）
来源：http://dali.xuetiantiany.cn/Article/details/gtyrggfjuj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ybcxt.top/Article/details/gtvfuzpgqw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.pengpengdd.cyou/Article/details/gthsgjxeoj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yanxiufei.cn/Article/details/gteaysexqv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jyoumei.cn/Article/details/gttmqrdkhq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jqgufenzy.top/Article/details/gtvnzepfrx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.aizwys.cn/Article/details/gtmyvyywyl.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sweek.top/Article/details/gtjkpcmtus.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cashguo.top/Article/details/gtyeebhohs.html

[L06] 解析响应为 JSON
来源：http://dali.yj20258.top/Article/details/gtjusheivt.html

Py:   resp.json()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdatfvpsj.html

PHP:  json_decode($body, true);
来源：http://dali.chenzaomai.com/Article/details/gtzfhawptc.html

JS:   await resp.json()
来源：http://dali.daxiang520.top/Article/details/gtmcjveppl.html

TS:   await resp.json()
来源：http://dali.zhiwuduotai.top/Article/details/gtexlrkjse.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gtoonhvqwd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.gaohongyu789.top/Article/details/gtltufrcbh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sweek.top/Article/details/gtdrxfnfwl.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhongyouzk.top/Article/details/gthacjgjvz.html

[L07] 处理 HTTP 状态码
来源：http://dali.gogol.net.cn/Article/details/gttietoefq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.iojbl.cn/Article/details/gtmbtkxbdg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nanxuanxn.top/Article/details/gtqutgdkff.html

JS:   resp.ok;  resp.status
来源：http://dali.zhixingplan.top/Article/details/gtnnskimrw.html

TS:   resp.ok;  resp.status
来源：http://dali.aibaodan.cn/Article/details/gtxlwercaj.html

Java: resp.statusCode()
来源：http://dali.tian-w.cn/Article/details/gtcburgrno.html

Go:   resp.StatusCode
来源：http://dali.zhixingplan.top/Article/details/gtxxbgjgqk.html

Ruby: resp.code.to_i
来源：http://dali.feifeiyinyue.top/Article/details/gtrbmuweax.html

C#:   (int)resp.StatusCode
来源：http://dali.wangshuangyany.cn/Article/details/gtzphrnyvs.html

[L08] 并发请求多个地址
来源：http://dali.316326.xyz/Article/details/gtzgmzeiib.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zdqjudy.top/Article/details/gtzwigrgui.html

PHP:  curl_multi_init() 系列
来源：http://dali.redwolf501.top/Article/details/gtxgbsskpm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gogol.net.cn/Article/details/gtivtffpti.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxinkj.top/Article/details/gtswreyzum.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhongyouzk.top/Article/details/gtamkibbdy.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.haohaochexian.top/Article/details/gtvmoxseqr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.aizwys.cn/Article/details/gtrrtvezij.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hysaishi.cn/Article/details/gtuqbamtch.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtxtrkpcru.html

M. 命令行 / 进程 / 环境
来源：http://dali.cdnleiting.top/Article/details/gtlbtgqkst.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gttjsldehb.html

[M01] 读取命令行参数
来源：http://dali.hfpthk.cn/Article/details/gtlxpwonrf.html

Py:   sys.argv[1:]
来源：http://dali.c1oappe.top/Article/details/gtzjcfmoov.html

PHP:  $argv;  $argc;
来源：http://dali.c1oappe.top/Article/details/gtqrzaeghx.html

JS:   process.argv.slice(2)
来源：http://dali.daxiang520.top/Article/details/gthckefjiw.html

TS:   process.argv.slice(2)
来源：http://dali.gogol.net.cn/Article/details/gtzujvqcbz.html

Java: args 数组（main 方法参数）
来源：http://dali.daxiang520.top/Article/details/gtankpwest.html

Go:   os.Args[1:]
来源：http://dali.pycfn.com/Article/details/gtfqzxqyyv.html

Ruby: ARGV
来源：http://dali.zhengqikj.top/Article/details/gtefyvwcsg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yuxming.cn/Article/details/gtbhflpqfu.html

[M02] 读取环境变量
来源：http://dali.nanxinkj.top/Article/details/gtvfvipuun.html

Py:   os.environ.get("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gtnvcnbeos.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.tianlin.xyz/Article/details/gtyeplftez.html

JS:   process.env.HOME
来源：http://dali.gogol.net.cn/Article/details/gtxrufdmdg.html

TS:   process.env.HOME
来源：http://dali.havefunace.top/Article/details/gtiilzyhdp.html

Java: System.getenv("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gtxbdrofib.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hysaishi.cn/Article/details/gtcyxoutlf.html

Ruby: ENV["HOME"]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtinczaddi.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.svipenyu.cn/Article/details/gtqwykkeya.html

[M03] 执行外部命令
来源：http://dali.yj20258888.top/Article/details/gtvstmeiuy.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yonumen.top/Article/details/gtjlmzovlj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.wangdashe.top/Article/details/gtnpkzjjrm.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.guowangkeji.top/Article/details/gtzovrsprs.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ehwqpu.com/Article/details/gtouuctbcy.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gotoacloud.top/Article/details/gtlflyfftn.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yuxming.cn/Article/details/gtlriknplo.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinyuanbaomall.cn/Article/details/gthzjtvhvg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.iojbl.cn/Article/details/gteghclbtt.html

[M04] 获取当前工作目录
来源：http://dali.bjfxy.top/Article/details/gtcehkwbyf.html

Py:   os.getcwd()
来源：http://dali.gzhubu.top/Article/details/gtfmoopbqk.html

PHP:  getcwd();
来源：http://dali.zhongyouzk.top/Article/details/gtwbnxrikd.html

JS:   process.cwd()
来源：http://dali.0kj1m.cn/Article/details/gtxuruhawj.html

TS:   process.cwd()
来源：http://dali.fengsongda.top/Article/details/gtimgbiydp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sxryk.cn/Article/details/gtpgprrdsu.html

Go:   os.Getwd()
来源：http://dali.shzxlz.cn/Article/details/gtjffbaqyy.html

Ruby: Dir.pwd
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxbhartft.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.9152youxi.cn/Article/details/gtytqbelit.html

[M05] 设置退出码
来源：http://dali.jqgufenzy.top/Article/details/gtqnpdvwum.html

Py:   sys.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gtlsbhwmns.html

PHP:  exit(1);
来源：http://dali.xylfe.cn/Article/details/gtmebxuzyr.html

JS:   process.exit(1)
来源：http://dali.wangdashe.top/Article/details/gtmqjfzuzk.html

TS:   process.exit(1)
来源：http://dali.yonumen.top/Article/details/gtjcxsuqqa.html

Java: System.exit(1)
来源：http://dali.wangdashe.top/Article/details/gttlvfklbw.html

Go:   os.Exit(1)
来源：http://dali.jyoumei.cn/Article/details/gtqdowbgje.html

Ruby: exit 1
来源：http://dali.shuidangran.top/Article/details/gtmvkonhhx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xuanzx.com/Article/details/gtcjinqvpn.html

[M06] 向标准错误输出
来源：http://dali.yangfankeji.com/Article/details/gtnxtfhrwr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.feifeiyinyue.top/Article/details/gtjaoycvwi.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hfpthk.cn/Article/details/gtnymohxft.html

JS:   console.error("err")
来源：http://dali.sysykeji.top/Article/details/gtoxzggfaf.html

TS:   console.error("err")
来源：http://dali.ivvv.top/Article/details/gtbhgjgzkf.html

Java: System.err.println("err")
来源：http://dali.shuidangran.top/Article/details/gtkozxngvc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gaohongyu789.top/Article/details/gtzpsfqodw.html

Ruby: warn "err"
来源：http://dali.aizwys.cn/Article/details/gtrdlqtxof.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gtrxwxfsoe.html

[M07] 判断是否为主入口
来源：http://dali.fzhhl.top/Article/details/gtbhpqxzim.html

Py:   if __name__ == "__main__":
来源：http://dali.bjfxy.top/Article/details/gtnbeopvkj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yvedp.cn/Article/details/gtmjhuyebg.html

JS:   require.main === module
来源：http://dali.jianghu66.top/Article/details/gtfogcsldj.html

TS:   require.main === module
来源：http://dali.yongpay.top/Article/details/gtpnxkdond.html

Java: public static void main(String[] args)
来源：http://dali.andypj.xyz/Article/details/gtdxupaeuu.html

Go:   func main()
来源：http://dali.bjfxy.top/Article/details/gtgdstntgc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tianlin.xyz/Article/details/gtdnjmgmyi.html

C#:   static void Main(string[] args)
来源：http://dali.havefunace.top/Article/details/gtogxsosem.html

[M08] 获取系统与运行时信息
来源：http://dali.wangdashe.top/Article/details/gtwtaykuad.html

Py:   platform.system();  platform.python_version()
来源：http://dali.nwbrower.top/Article/details/gtzwdzvqbm.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.nanxuanxn.top/Article/details/gtgcamvixf.html

JS:   process.platform;  process.version
来源：http://dali.fengsongda.top/Article/details/gtuhjowcem.html

TS:   process.platform;  process.version
来源：http://dali.wangshuangyany.cn/Article/details/gtoiotjkkt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.dianchejie.cn/Article/details/gtgrbrjnla.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shanyushiyangtech.top/Article/details/gtvpflheet.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shuidangran.top/Article/details/gtcllouevv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhoulong.xyz/Article/details/gteaslnjnv.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtnkmxgeve.html

N. 数据结构与算法
来源：http://dali.hnqzz.top/Article/details/gtlkoiskuo.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtkbodoyji.html

[N01] 二分查找（有序数组）
来源：http://dali.pengpengdd.cyou/Article/details/gtlqqtalzt.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.birdmap.top/Article/details/gtigoebqbb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jiagoushi.top/Article/details/gtjflcbuar.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cqqwz.cn/Article/details/gtqgeftewt.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ybcxt.top/Article/details/gtqceyguht.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtenrijaod.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrrqacrkn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.fengsongda.top/Article/details/gtemxajmtl.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtibcxxcla.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.aizwys.cn/Article/details/gtpqnkgdqf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aizwys.cn/Article/details/gtcostcddz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.smart0.xyz/Article/details/gtkslvpzkr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pengpengdd.cyou/Article/details/gtadcizekz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnqzz.top/Article/details/gtjfqlboqc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhongyouzk.top/Article/details/gtingjaeor.html

Go:   slices.Sort(arr)
来源：http://dali.cheryme.top/Article/details/gtvknhvgnu.html

Ruby: arr.sort
来源：http://dali.cdnleiting.top/Article/details/gtoowbpumz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yuanzhike.top/Article/details/gtofqcfdfe.html

[N03] 快速排序（分治示例）
来源：http://dali.yj202588.top/Article/details/gtwilubeon.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sufxvd.cn/Article/details/gtifihguay.html

PHP:  // 递归实现，或用 usort
来源：http://dali.snrcjt.cn/Article/details/gthpqqxpth.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.bjfxy.top/Article/details/gtwserkfxj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtirltxsri.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhongyouzk.top/Article/details/gtemkmxxnu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.birdmap.top/Article/details/gtgmodvlig.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.havefunace.top/Article/details/gtbqbtyhta.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ppjwa.cn/Article/details/gtormocjtc.html

[N04] 斐波那契数列
来源：http://dali.dianchejie.cn/Article/details/gtmacsgamx.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yj202588.top/Article/details/gtfilogjmz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jianghu66.top/Article/details/gtaqhjjhep.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.haohaochexian.top/Article/details/gtuvunnqcw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gttfhwludf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yangfankeji.com/Article/details/gtpprzewip.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinqigufen.top/Article/details/gtwxzahqrg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sysykeji.top/Article/details/gtiavddxwl.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zycfv.cn/Article/details/gtndfgxisn.html

[N05] 最大公约数
来源：http://dali.gaohongyu789.top/Article/details/gtsuiucjov.html

Py:   math.gcd(a, b)
来源：http://dali.tianlin.xyz/Article/details/gtkfjdwkcp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.vqdsnc.cn/Article/details/gtraslzlab.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.redwolf501.top/Article/details/gteegeuhja.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ybcxt.top/Article/details/gtymyyzypn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.iojbl.cn/Article/details/gtalapvzyr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ybcxt.top/Article/details/gtgfyiusjt.html

Ruby: a.gcd(b)
来源：http://dali.dianchejie.cn/Article/details/gtikpcgxpx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cucudq.cn/Article/details/gtkjbzakoi.html

[N06] 判断回文字符串
来源：http://dali.9152youxi.cn/Article/details/gthdqciwnm.html

Py:   s == s[::-1]
来源：http://dali.fzhhl.top/Article/details/gtnaemmhxr.html

PHP:  $s === strrev($s);
来源：http://dali.andypj.xyz/Article/details/gtdyiyuonu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbaumeheu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gtopcxiepb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cashguo.top/Article/details/gtjfplwqcn.html

Go:   // 双指针从两端比较
来源：http://dali.guannengcc.top/Article/details/gtexdqquod.html

Ruby: s == s.reverse
来源：http://dali.andypj.xyz/Article/details/gtotyohbkb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zdqjudy.top/Article/details/gtoqdtrmqk.html

[N07] 两数之和（返回下标）
来源：http://dali.chenjidiqi.icu/Article/details/gtzkbfftbq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhaomingkeji.xyz/Article/details/gttkovtcrm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zycfv.cn/Article/details/gtdkdhjiio.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.wangshuangyany.cn/Article/details/gttkpvdltc.html

TS:   // 手写 Map<string, number>
来源：http://dali.nanxuanxn.top/Article/details/gtnfdhuqbe.html

Java: // 手写 HashMap
来源：http://dali.chenlongwang.top/Article/details/gtkqmxxeze.html


<!-- 参考信息 -->