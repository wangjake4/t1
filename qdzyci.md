代发 wailian999

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xinyue.icu/Article/details/gt2jyfkbtxu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.aibaodan.cn/Article/details/gt2sisneawg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2wsouiusc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xylfe.cn/Article/details/gt2lzvzahuj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cdnleiting.top/Article/details/gt2utjqjykw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.bjfxy.top/Article/details/gt2ozqiojmb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.fengsongda.top/Article/details/gt2hmoypjdd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zdqjudy.top/Article/details/gt2fyfigpjy.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2qdyoskpz.html

K. JSON 与序列化
来源：http://dali.hfpthk.cn/Article/details/gt2iyjsixve.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2deljroty.html

[K01] 对象转 JSON 字符串
来源：http://dali.aibaodan.cn/Article/details/gt2iwbbxfsc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ydzc1.top/Article/details/gt2anruydqe.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jianghu66.top/Article/details/gt2ohjxezkg.html

JS:   JSON.stringify(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2gpqobxap.html

TS:   JSON.stringify(obj)
来源：http://dali.tanke756.top/Article/details/gt2zoyqlsvw.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.dianchejie.cn/Article/details/gt2iuflepld.html

Go:   json.Marshal(obj)
来源：http://dali.yuxming.cn/Article/details/gt2ibrethen.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.bjfxy.top/Article/details/gt2xunpqwwl.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2epkmgaap.html

[K02] JSON 字符串转对象
来源：http://dali.chenjidiqi.icu/Article/details/gt2avvfphhb.html

Py:   json.loads(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2sxcfxkzo.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yj20258.top/Article/details/gt2klqjhiji.html

JS:   JSON.parse(s)
来源：http://dali.haohaochexian.top/Article/details/gt2uujgmgvb.html

TS:   JSON.parse(s)
来源：http://dali.hnqzz.top/Article/details/gt2gnrqmuji.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.0kj1m.cn/Article/details/gt2wfyzdcdo.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.bjfxy.top/Article/details/gt2kldeskis.html

Ruby: JSON.parse(s)
来源：http://dali.xziqi.cn/Article/details/gt2bhtjtqmf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jqgfzy.top/Article/details/gt2jbcltrpq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jqgufenzy.top/Article/details/gt2duaqkpke.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.iojbl.cn/Article/details/gt2mmschrjb.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.andypj.xyz/Article/details/gt2jxvoriap.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangdashe.top/Article/details/gt2sflsidpx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnqzz.top/Article/details/gt2umglfqis.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cashguo.top/Article/details/gt2zszixfnz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yvedp.cn/Article/details/gt2lmeztvtb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ivvv.top/Article/details/gt2akhtimrx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yvedp.cn/Article/details/gt2oeisoxuq.html

[K04] 读取 JSON 文件
来源：http://dali.dashuyun.cn/Article/details/gt2pruwtxpe.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sufxvd.cn/Article/details/gt2pgaianwe.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hongshengwenyu.top/Article/details/gt2agqgbiqe.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yanxiufei.cn/Article/details/gt2ymvpvjsu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.iojbl.cn/Article/details/gt2xenksfoq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.wangdashe.top/Article/details/gt2aybjmdkg.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.tian-w.cn/Article/details/gt2zeynzyyt.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sxryk.cn/Article/details/gt2slfxtnyo.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shzxlz.cn/Article/details/gt2afwpizsj.html

[K05] 深拷贝对象
来源：http://dali.havefunace.top/Article/details/gt2yxtfzbai.html

Py:   copy.deepcopy(obj)
来源：http://dali.ybcxt.top/Article/details/gt2afomhpok.html

PHP:  unserialize(serialize($obj));
来源：http://dali.tanke756.top/Article/details/gt2mqjlazrd.html

JS:   structuredClone(obj)
来源：http://dali.zycfv.cn/Article/details/gt2oqyykczk.html

TS:   structuredClone(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2rswdwofc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2viiyiyqq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.havefunace.top/Article/details/gt2xartpurn.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hnxiangtu.top/Article/details/gt2oolkqhlx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.pengpengdd.cyou/Article/details/gt2aumrwuwn.html

[K06] 解析 URL 查询串
来源：http://dali.nwbrower.top/Article/details/gt2mypgewxx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.guowangkeji.top/Article/details/gt2fwbxmhnf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cucudq.cn/Article/details/gt2peugprhp.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ydzc1.top/Article/details/gt2jrpfzqhf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.birdmap.top/Article/details/gt2tcdccgux.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xuetiantiany.cn/Article/details/gt2jcoivavf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.tianlin.xyz/Article/details/gt2oaxeueeo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhiwuduotai.top/Article/details/gt2twnashvu.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yvedp.cn/Article/details/gt2uwsaptvx.html

[K07] 进制转换
来源：http://dali.ppjwa.cn/Article/details/gt2pfixfuup.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gt2varoweev.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.daxiang520.top/Article/details/gt2agumywma.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gt2btdkyzwi.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gt2mrdpsqym.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gt2qymrvmmu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.vqdsnc.cn/Article/details/gt2pczbxmht.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hnxiangtu.top/Article/details/gt2xglilhgh.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gt2ivffoazm.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sweek.top/Article/details/gt2bikcbgfu.html

Py:   pickle.dumps(obj)
来源：http://dali.mhx1999.top/Article/details/gt2osnekody.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2prwdhvnw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gotoacloud.top/Article/details/gt2qwnfjnrl.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yvedp.cn/Article/details/gt2xouwxijn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jiagoushi.top/Article/details/gt2uylljhjo.html

Go:   encoding/gob
来源：http://dali.chenjidiqi.icu/Article/details/gt2rxefzjap.html

Ruby: Marshal.dump(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2ttaucxqw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cashguo.top/Article/details/gt2frlbwvpo.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2lpcgblpz.html

L. 网络请求
来源：http://dali.aibaodan.cn/Article/details/gt2bsznvzcq.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2fumgzjxi.html

[L01] 发送 GET 请求
来源：http://dali.yongpay.top/Article/details/gt2unoaliux.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hongshengwenyu.top/Article/details/gt2vbtvrcbq.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.9152youxi.cn/Article/details/gt2foiwmzpn.html

JS:   await fetch(url)
来源：http://dali.jinqigufen.top/Article/details/gt2qqyuyarz.html

TS:   await fetch(url)
来源：http://dali.jqgufenzy.top/Article/details/gt2ayqcpkoa.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cdnleiting.top/Article/details/gt2zjuulkci.html

Go:   resp, err := http.Get(url)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hclhmbba.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.guowangkeji.top/Article/details/gt2rxrhjobk.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hywenlv.cn/Article/details/gt2apdwvyzg.html

[L02] 发送 POST JSON
来源：http://dali.sweek.top/Article/details/gt2zklzxmry.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ivvv.top/Article/details/gt2qalqnhho.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.fzhhl.top/Article/details/gt2kejeluao.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hnqzz.top/Article/details/gt2tdrsrrrt.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kqajexbz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.daxiang520.top/Article/details/gt2ubvcgmxg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ppjwa.cn/Article/details/gt2fbbmhxxt.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yj20258.top/Article/details/gt2qxpnjtli.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.guannengcc.top/Article/details/gt2iaryleut.html

[L03] 设置自定义请求头
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rcrceqff.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sufxvd.cn/Article/details/gt2wuvqzrsv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cashguo.top/Article/details/gt2dxyqiyoo.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sysykeji.top/Article/details/gt2blpiorif.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hammf.cn/Article/details/gt2tnjdajcm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.tanke756.top/Article/details/gt2xzlbwlvr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.c1oappe.top/Article/details/gt2nyqsxmpg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.feifeiyinyue.top/Article/details/gt2vcctbzte.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cqqwz.cn/Article/details/gt2kxxvepsc.html

[L04] 设置超时
来源：http://dali.nanxuanxn.top/Article/details/gt2spxrvokt.html

Py:   requests.get(url, timeout=5)
来源：http://dali.guannengcc.top/Article/details/gt2unsxlchj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhixingplan.top/Article/details/gt2xrztawoq.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eihygtdy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nwbrower.top/Article/details/gt2wacaykgm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jiagoushi.top/Article/details/gt2dkylgzau.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.tian-w.cn/Article/details/gt2qgstwspg.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.daria6918.cn/Article/details/gt2vmkahkee.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhiwuduotai.top/Article/details/gt2pmhtksgm.html

[L05] 上传文件（multipart）
来源：http://dali.dashuyun.cn/Article/details/gt2ahdibqbo.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yangfankeji.com/Article/details/gt2ufhkdith.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.birdmap.top/Article/details/gt2lwsuplwq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sufxvd.cn/Article/details/gt2ajiyrarj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.c1oappe.top/Article/details/gt2sujssqyy.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.feifeiyinyue.top/Article/details/gt2ostcijqo.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xziqi.cn/Article/details/gt2proowgmj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.wangshuangyany.cn/Article/details/gt2ebjnyxyf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2bewufgpt.html

[L06] 解析响应为 JSON
来源：http://dali.sxryk.cn/Article/details/gt2ygxkesur.html

Py:   resp.json()
来源：http://dali.9152youxi.cn/Article/details/gt2gujemabk.html

PHP:  json_decode($body, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pdmkrewp.html

JS:   await resp.json()
来源：http://dali.yvedp.cn/Article/details/gt2smiskxec.html

TS:   await resp.json()
来源：http://dali.yuxming.cn/Article/details/gt2otbdgswr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.daxiang520.top/Article/details/gt2pexnyjln.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.nwbrower.top/Article/details/gt2yxslfckb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sufxvd.cn/Article/details/gt2utgbtsrw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.meibo888.top/Article/details/gt2jspywcya.html

[L07] 处理 HTTP 状态码
来源：http://dali.sweek.top/Article/details/gt2cndnakqg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ybcxt.top/Article/details/gt2fybgurkf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hywenlv.cn/Article/details/gt2qmscibjc.html

JS:   resp.ok;  resp.status
来源：http://dali.316326.xyz/Article/details/gt2ygztewdn.html

TS:   resp.ok;  resp.status
来源：http://dali.wangdashe.top/Article/details/gt2fzssluza.html

Java: resp.statusCode()
来源：http://dali.aibaodan.cn/Article/details/gt2kqntcdvw.html

Go:   resp.StatusCode
来源：http://dali.wangshuangyany.cn/Article/details/gt2jbipttaz.html

Ruby: resp.code.to_i
来源：http://dali.ppjwa.cn/Article/details/gt2hqlvbvwv.html

C#:   (int)resp.StatusCode
来源：http://dali.pengpengdd.cyou/Article/details/gt2tffxejns.html

[L08] 并发请求多个地址
来源：http://dali.jyoumei.cn/Article/details/gt2mwdfbufo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhixingplan.top/Article/details/gt2hanxfdhs.html

PHP:  curl_multi_init() 系列
来源：http://dali.hongshengwenyu.top/Article/details/gt2dgmkdncu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gt2wptnedqc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hfpthk.cn/Article/details/gt2yfyjroek.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.kuanghao11.cn/Article/details/gt2pqvrptqs.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinqigfzy.top/Article/details/gt2jcxctczj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jianghu66.top/Article/details/gt2jxuwppma.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.andypj.xyz/Article/details/gt2anyekpce.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2tmbczugs.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinqigufen.top/Article/details/gt2twbmpgcp.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2bhgzgzdv.html

[M01] 读取命令行参数
来源：http://dali.sufxvd.cn/Article/details/gt2jttshbyx.html

Py:   sys.argv[1:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nlesogiz.html

PHP:  $argv;  $argc;
来源：http://dali.chenzaomai.com/Article/details/gt2kjywzmtw.html

JS:   process.argv.slice(2)
来源：http://dali.sufxvd.cn/Article/details/gt2kvxhxtha.html

TS:   process.argv.slice(2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qmhnxjnf.html

Java: args 数组（main 方法参数）
来源：http://dali.jyoumei.cn/Article/details/gt2rrudgugk.html

Go:   os.Args[1:]
来源：http://dali.nanxinkj.top/Article/details/gt2wqeugggt.html

Ruby: ARGV
来源：http://dali.hysaishi.cn/Article/details/gt2wcohwbuv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.redwolf501.top/Article/details/gt2apondmnd.html

[M02] 读取环境变量
来源：http://dali.dashuyun.cn/Article/details/gt2atotzdej.html

Py:   os.environ.get("HOME")
来源：http://dali.redwolf501.top/Article/details/gt2nexfyaew.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sufxvd.cn/Article/details/gt2qexubjsv.html

JS:   process.env.HOME
来源：http://dali.cucudq.cn/Article/details/gt2vyeodcwu.html

TS:   process.env.HOME
来源：http://dali.yj20258888.top/Article/details/gt2hjrdvunu.html

Java: System.getenv("HOME")
来源：http://dali.gotoacloud.top/Article/details/gt2armawayd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yuanzhike.top/Article/details/gt2nfbupkqt.html

Ruby: ENV["HOME"]
来源：http://dali.sufxvd.cn/Article/details/gt2vqkxkucf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cwoikarq.html

[M03] 执行外部命令
来源：http://dali.yuxming.cn/Article/details/gt2hdarcocy.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cashguo.top/Article/details/gt2ynbgpthj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shzxlz.cn/Article/details/gt2rarbrcwf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgufenzy.top/Article/details/gt2pzjellht.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.guowangkeji.top/Article/details/gt2rtgdvcae.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2gteutalw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhiwuduotai.top/Article/details/gt2qzzncleh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hywenlv.cn/Article/details/gt2jbbbifev.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hysaishi.cn/Article/details/gt2jtqnavjf.html

[M04] 获取当前工作目录
来源：http://dali.zdqjudy.top/Article/details/gt2bpxztzvp.html

Py:   os.getcwd()
来源：http://dali.fzhhl.top/Article/details/gt2cvahbpnz.html

PHP:  getcwd();
来源：http://dali.xylfe.cn/Article/details/gt2wyywwzxd.html

JS:   process.cwd()
来源：http://dali.xziqi.cn/Article/details/gt2tkxgwxjy.html

TS:   process.cwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ocloqcmz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.guowangkeji.top/Article/details/gt2prbhcrji.html

Go:   os.Getwd()
来源：http://dali.yuanzhike.top/Article/details/gt2tqzoxvci.html

Ruby: Dir.pwd
来源：http://dali.yonumen.top/Article/details/gt2czvimqqy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.kuanghao11.cn/Article/details/gt2sekogsjt.html

[M05] 设置退出码
来源：http://dali.shuidangran.top/Article/details/gt2zjsysdko.html

Py:   sys.exit(1)
来源：http://dali.ydzc1.top/Article/details/gt2xucrknxh.html

PHP:  exit(1);
来源：http://dali.hysaishi.cn/Article/details/gt2metaqecv.html

JS:   process.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2psspggfs.html

TS:   process.exit(1)
来源：http://dali.cashguo.top/Article/details/gt2rkfzzqog.html

Java: System.exit(1)
来源：http://dali.cucudq.cn/Article/details/gt2grkhzwue.html

Go:   os.Exit(1)
来源：http://dali.mhx1999.top/Article/details/gt2astqnkml.html

Ruby: exit 1
来源：http://dali.jianghu66.top/Article/details/gt2fcddkxpp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xuanzx.com/Article/details/gt2fxtqampf.html

[M06] 向标准错误输出
来源：http://dali.pengpengdd.cyou/Article/details/gt2gufghpgj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.fzhhl.top/Article/details/gt2llgpgcqj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.chenjidiqi.icu/Article/details/gt2yxrsiwvh.html

JS:   console.error("err")
来源：http://dali.wangshuangyany.cn/Article/details/gt2fvvpvelw.html

TS:   console.error("err")
来源：http://dali.haohaochexian.top/Article/details/gt2lmgztyta.html

Java: System.err.println("err")
来源：http://dali.xuanzx.com/Article/details/gt2sfovelpk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.pycfn.com/Article/details/gt2ewpxusym.html

Ruby: warn "err"
来源：http://dali.cheryme.top/Article/details/gt2vvwhmlcn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ppjwa.cn/Article/details/gt2spdyzoyf.html

[M07] 判断是否为主入口
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hunalmio.html

Py:   if __name__ == "__main__":
来源：http://dali.xziqi.cn/Article/details/gt2yxjhtpts.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.smart0.xyz/Article/details/gt2qpdwxyhn.html

JS:   require.main === module
来源：http://dali.kuanghao11.cn/Article/details/gt2ufiyyhyk.html

TS:   require.main === module
来源：http://dali.shuidangran.top/Article/details/gt2dnknavym.html

Java: public static void main(String[] args)
来源：http://dali.shzxlz.cn/Article/details/gt2vuaxsxzb.html

Go:   func main()
来源：http://dali.shzxlz.cn/Article/details/gt2dzmnishp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.bjfxy.top/Article/details/gt2ohfshayl.html

C#:   static void Main(string[] args)
来源：http://dali.feifeiyinyue.top/Article/details/gt2metjvipw.html

[M08] 获取系统与运行时信息
来源：http://dali.chenjidiqi.icu/Article/details/gt2qbdhopew.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ivvv.top/Article/details/gt2wrzbatkz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.c1oappe.top/Article/details/gt2wyijafyr.html

JS:   process.platform;  process.version
来源：http://dali.hysaishi.cn/Article/details/gt2hsuvyvel.html

TS:   process.platform;  process.version
来源：http://dali.ybcxt.top/Article/details/gt2aijzoswd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hywenlv.cn/Article/details/gt2fsqgczbx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pjqcnhww.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.nanxinkj.top/Article/details/gt2zepierge.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ybcxt.top/Article/details/gt2xacfqwrb.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2tevobvif.html

N. 数据结构与算法
来源：http://dali.jiagoushi.top/Article/details/gt2vwdoutrv.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2xfdourtx.html

[N01] 二分查找（有序数组）
来源：http://dali.tanke756.top/Article/details/gt2vgiuysdd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gt2vclcnwgn.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.iojbl.cn/Article/details/gt2jwomoxsv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhiwuduotai.top/Article/details/gt2dfzzxbob.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ujhuhqna.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gt2dtmenitb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zykpwtlh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ivvv.top/Article/details/gt2vsvcvdba.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gt2kwkzdgox.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jianghu66.top/Article/details/gt2yofoehwx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhiwuduotai.top/Article/details/gt2vangbkku.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sysykeji.top/Article/details/gt2ggbvtbnx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhixingplan.top/Article/details/gt2gorngfsk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ppjwa.cn/Article/details/gt2rnpunlkc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jlsjyb.cn/Article/details/gt2jnvafgvl.html

Go:   slices.Sort(arr)
来源：http://dali.jiagoushi.top/Article/details/gt2ppaclbls.html

Ruby: arr.sort
来源：http://dali.haohaochexian.top/Article/details/gt2mxobqngd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.daxiang520.top/Article/details/gt2wutkkqrn.html

[N03] 快速排序（分治示例）
来源：http://dali.iojbl.cn/Article/details/gt2owroxspj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.iojbl.cn/Article/details/gt2dlmzpfvy.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qxvdloyr.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhongyouzk.top/Article/details/gt2egalujcm.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxuanxn.top/Article/details/gt2ljiwoncu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cdnleiting.top/Article/details/gt2xtsscgvm.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sxryk.cn/Article/details/gt2ijekfzsd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dtgyzykt.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.andypj.xyz/Article/details/gt2zrdjgimj.html

[N04] 斐波那契数列
来源：http://dali.meibo888.top/Article/details/gt2dqpvjrfy.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gotoacloud.top/Article/details/gt2mkkbvsnj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yfxroxys.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cqqwz.cn/Article/details/gt2bubygkyl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jyoumei.cn/Article/details/gt2aqxlnyev.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.pycfn.com/Article/details/gt2cqgandwp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pmrvsdsz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2rooxkrbl.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gt2ylfpovxo.html

[N05] 最大公约数
来源：http://dali.xinyue.icu/Article/details/gt2gcxmnlpg.html

Py:   math.gcd(a, b)
来源：http://dali.havefunace.top/Article/details/gt2cqgiozse.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.fzhhl.top/Article/details/gt2jjqysbps.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jlsjyb.cn/Article/details/gt2comrgesy.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cheryme.top/Article/details/gt2xpfkharf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.daria6918.cn/Article/details/gt2bheqoqnd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.gogol.net.cn/Article/details/gt2dmqzhglj.html

Ruby: a.gcd(b)
来源：http://dali.ehwqpu.com/Article/details/gt2immhrheq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yanxiufei.cn/Article/details/gt2hnxidlpc.html

[N06] 判断回文字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qucyjblx.html

Py:   s == s[::-1]
来源：http://dali.tian-w.cn/Article/details/gt2kbgtdjkh.html

PHP:  $s === strrev($s);
来源：http://dali.gaohongyu789.top/Article/details/gt2apmuuxnp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ydzc1.top/Article/details/gt2gzpdsryk.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gt2dhvytlze.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ppjwa.cn/Article/details/gt2agcvfsca.html

Go:   // 双指针从两端比较
来源：http://dali.sxryk.cn/Article/details/gt2ghfbelzt.html

Ruby: s == s.reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ffmltpqt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.havefunace.top/Article/details/gt2lozofzxn.html

[N07] 两数之和（返回下标）
来源：http://dali.yuxming.cn/Article/details/gt2jshipcpo.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hfpthk.cn/Article/details/gt2ycycegye.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinqigfzy.top/Article/details/gt2fmwgsqyh.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.fzhhl.top/Article/details/gt2kizhgovb.html

TS:   // 手写 Map<string, number>
来源：http://dali.nanxinkj.top/Article/details/gt2eddbxlrx.html

Java: // 手写 HashMap
来源：http://dali.wangdashe.top/Article/details/gt2otysufea.html

Go:   // 手写 map[int]int
来源：http://dali.hongshengwenyu.top/Article/details/gt2vxnngguh.html

Ruby: // 手写 Hash
来源：http://dali.fzhhl.top/Article/details/gt2weficyaf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ydzc1.top/Article/details/gt2tlujvwpa.html

[N08] 生成全排列
来源：http://dali.sweek.top/Article/details/gt2kwjzupwc.html


<!-- 参考信息 -->