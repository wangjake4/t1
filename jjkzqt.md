代发 wailian999

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zycfv.cn/Article/details/gt2xdgpvepf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jlsjyb.cn/Article/details/gt2olrrlfzx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2mxscskxa.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qwioxiep.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.andypj.xyz/Article/details/gt2rajwqaej.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zycfv.cn/Article/details/gt2czmvkueq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sysykeji.top/Article/details/gt2cbzfnlzq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.birdmap.top/Article/details/gt2emrjnhut.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2uhjmrwzd.html

K. JSON 与序列化
来源：http://dali.birdmap.top/Article/details/gt2izxlpucg.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2gjeffmhc.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2prmnaupd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xinyue.icu/Article/details/gt2uqwrjsct.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.haohaochexian.top/Article/details/gt2ufninius.html

JS:   JSON.stringify(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2mducqbpr.html

TS:   JSON.stringify(obj)
来源：http://dali.fengsongda.top/Article/details/gt2tyfboqhi.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinqigufen.top/Article/details/gt2qnithadp.html

Go:   json.Marshal(obj)
来源：http://dali.tanke756.top/Article/details/gt2ncorglbz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jianghu66.top/Article/details/gt2spaghffn.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sweek.top/Article/details/gt2hwrsvkyt.html

[K02] JSON 字符串转对象
来源：http://dali.mhx1999.top/Article/details/gt2hfzrzyca.html

Py:   json.loads(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2guepcncn.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jqgufenzy.top/Article/details/gt2vgsaserf.html

JS:   JSON.parse(s)
来源：http://dali.hnqzz.top/Article/details/gt2ipgtvvnm.html

TS:   JSON.parse(s)
来源：http://dali.ivvv.top/Article/details/gt2ywrtdoiv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lfuvfkjs.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.meibo888.top/Article/details/gt2rsaxlbfr.html

Ruby: JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gt2xibugobm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ybcxt.top/Article/details/gt2michrxwu.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.nanxuanxn.top/Article/details/gt2neisvhvv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nanxuanxn.top/Article/details/gt2kgixywhf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jyoumei.cn/Article/details/gt2lrgtshof.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hfpthk.cn/Article/details/gt2jkstelzk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gotoacloud.top/Article/details/gt2kvuzkrlr.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yuxming.cn/Article/details/gt2rcsrhrms.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cheryme.top/Article/details/gt2yicoejiu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wsmkqmau.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tianlin.xyz/Article/details/gt2llrfrhik.html

[K04] 读取 JSON 文件
来源：http://dali.ydzc1.top/Article/details/gt2fzaevpun.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.mhx1999.top/Article/details/gt2zpbmsyvv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.nwbrower.top/Article/details/gt2luryovbl.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.c1oappe.top/Article/details/gt2hvgmapfz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.c1oappe.top/Article/details/gt2frquckgw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.c1oappe.top/Article/details/gt2zdleekap.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yj20258888.top/Article/details/gt2gwrnpivb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.snrcjt.cn/Article/details/gt2lveseqcc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ppjwa.cn/Article/details/gt2ecribfke.html

[K05] 深拷贝对象
来源：http://dali.jqgufenzy.top/Article/details/gt2pfeejylz.html

Py:   copy.deepcopy(obj)
来源：http://dali.birdmap.top/Article/details/gt2micwrens.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lwuvlsms.html

JS:   structuredClone(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2njirrrcq.html

TS:   structuredClone(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2quvoyxnc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yj20258.top/Article/details/gt2jnsaachz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.chenzaomai.com/Article/details/gt2pavevlkf.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xylfe.cn/Article/details/gt2yhqgtbyq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yanxiufei.cn/Article/details/gt2xmlbpkvi.html

[K06] 解析 URL 查询串
来源：http://dali.mhx1999.top/Article/details/gt2juiukysg.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.bjfxy.top/Article/details/gt2lzgvgphi.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.nwbrower.top/Article/details/gt2lijgqayt.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.meibo888.top/Article/details/gt2mqupnotn.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wvayvtsd.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.guowangkeji.top/Article/details/gt2fudcgkcy.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ybcxt.top/Article/details/gt2napyiboh.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ivvv.top/Article/details/gt2bwneiwxg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yongpay.top/Article/details/gt2ejilurwm.html

[K07] 进制转换
来源：http://dali.yueranfly.top/Article/details/gt2luhfozpf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gt2riagtilo.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.guowangkeji.top/Article/details/gt2xjgjchhn.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gt2ycajyecy.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gt2kcxpsuha.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gt2hesquaqd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.dashuyun.cn/Article/details/gt2deoazlia.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xqzxixft.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gt2cyqsagke.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xuanzx.com/Article/details/gt2kvdyvwqj.html

Py:   pickle.dumps(obj)
来源：http://dali.nwbrower.top/Article/details/gt2dfzckovs.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cdnleiting.top/Article/details/gt2nqzvcelj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nyzkjtrk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yueranfly.top/Article/details/gt2lmlsibxg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cheryme.top/Article/details/gt2lutheenz.html

Go:   encoding/gob
来源：http://dali.gaohongyu789.top/Article/details/gt2zllmjest.html

Ruby: Marshal.dump(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2mdfnfifh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2szsnknuv.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2egtkgkbh.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2qtkvpreb.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2xjrctbyq.html

[L01] 发送 GET 请求
来源：http://dali.hongshengwenyu.top/Article/details/gt2mepfryil.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ivvv.top/Article/details/gt2mbfhrvdp.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.aibaodan.cn/Article/details/gt2iixnpemp.html

JS:   await fetch(url)
来源：http://dali.zycfv.cn/Article/details/gt2tjjzcufr.html

TS:   await fetch(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2syjemfcn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gotoacloud.top/Article/details/gt2sfaqxndo.html

Go:   resp, err := http.Get(url)
来源：http://dali.fzhhl.top/Article/details/gt2fcqglicx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.c1oappe.top/Article/details/gt2txoacyax.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hysaishi.cn/Article/details/gt2dehfsowf.html

[L02] 发送 POST JSON
来源：http://dali.yonumen.top/Article/details/gt2ypzvymag.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.daria6918.cn/Article/details/gt2kpwxdzav.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ybcxt.top/Article/details/gt2dplhttng.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.9152youxi.cn/Article/details/gt2hbkbuakp.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sysykeji.top/Article/details/gt2tastaazv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinqigfzy.top/Article/details/gt2plkwirop.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hnqzz.top/Article/details/gt2ndpvvrkj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ydzc1.top/Article/details/gt2tjtaehka.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.snrcjt.cn/Article/details/gt2kuzqhrga.html

[L03] 设置自定义请求头
来源：http://dali.cdnleiting.top/Article/details/gt2leewqypq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cptqrkmk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.redwolf501.top/Article/details/gt2eviqgjlc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shuidangran.top/Article/details/gt2uexlazfl.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.feifeiyinyue.top/Article/details/gt2yhacsjjp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ivvv.top/Article/details/gt2ndixsirs.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hammf.cn/Article/details/gt2bpccdvnn.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shzxlz.cn/Article/details/gt2keaeqpyv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.guannengcc.top/Article/details/gt2srvpbffj.html

[L04] 设置超时
来源：http://dali.chenzaomai.com/Article/details/gt2mwqiyzae.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jyoumei.cn/Article/details/gt2bjpdoqhw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yj20258888.top/Article/details/gt2leetwocc.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.iojbl.cn/Article/details/gt2htajwiba.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gaohongyu789.top/Article/details/gt2xwshcych.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.tianlin.xyz/Article/details/gt2stqfvjno.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xuanzx.com/Article/details/gt2mgyntlfs.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.aizwys.cn/Article/details/gt2jnoboylx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gzhubu.top/Article/details/gt2ijmekqxx.html

[L05] 上传文件（multipart）
来源：http://dali.jqgfzy.top/Article/details/gt2ufkcyuqb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shangyingyoupin.top/Article/details/gt2aiwsxkhk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yomlrhva.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnqzz.top/Article/details/gt2ppvikpmi.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.pengpengdd.cyou/Article/details/gt2kxnxoqlx.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhiwuduotai.top/Article/details/gt2pkwrojra.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.pycfn.com/Article/details/gt2afwasarq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jlsjyb.cn/Article/details/gt2kngigxup.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yangfankeji.com/Article/details/gt2ahfpejgy.html

[L06] 解析响应为 JSON
来源：http://dali.ehwqpu.com/Article/details/gt2gmtnzxgy.html

Py:   resp.json()
来源：http://dali.zhiwuduotai.top/Article/details/gt2yxrbclaz.html

PHP:  json_decode($body, true);
来源：http://dali.jinqigfzy.top/Article/details/gt2cyjbspmp.html

JS:   await resp.json()
来源：http://dali.haohaochexian.top/Article/details/gt2tkfgugnv.html

TS:   await resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gt2jbrhjcio.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.aibaodan.cn/Article/details/gt2dctaxnwm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.tianlin.xyz/Article/details/gt2klvkzcsn.html

Ruby: JSON.parse(resp.body)
来源：http://dali.iojbl.cn/Article/details/gt2adduskhe.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shzxlz.cn/Article/details/gt2dtavpive.html

[L07] 处理 HTTP 状态码
来源：http://dali.birdmap.top/Article/details/gt2agrvenng.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hnxiangtu.top/Article/details/gt2wvdqtgwq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jlsjyb.cn/Article/details/gt2cyjakzrr.html

JS:   resp.ok;  resp.status
来源：http://dali.yongpay.top/Article/details/gt2gucjgzye.html

TS:   resp.ok;  resp.status
来源：http://dali.gzhubu.top/Article/details/gt2snbjfaoa.html

Java: resp.statusCode()
来源：http://dali.c1oappe.top/Article/details/gt2wzjoqzej.html

Go:   resp.StatusCode
来源：http://dali.feifeiyinyue.top/Article/details/gt2yykggobp.html

Ruby: resp.code.to_i
来源：http://dali.hywenlv.cn/Article/details/gt2bnhufhmm.html

C#:   (int)resp.StatusCode
来源：http://dali.ybcxt.top/Article/details/gt2jxytzkjy.html

[L08] 并发请求多个地址
来源：http://dali.cdnleiting.top/Article/details/gt2eeqbmksz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.dianchejie.cn/Article/details/gt2miwebjhr.html

PHP:  curl_multi_init() 系列
来源：http://dali.aizwys.cn/Article/details/gt2mgicwvpu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.birdmap.top/Article/details/gt2mxclbzxc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ybcxt.top/Article/details/gt2aoxbbzad.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.guannengcc.top/Article/details/gt2nnvjslah.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.snrcjt.cn/Article/details/gt2kilayche.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.havefunace.top/Article/details/gt2fmdblmzs.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.birdmap.top/Article/details/gt2jgspeahq.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2zronwfoe.html

M. 命令行 / 进程 / 环境
来源：http://dali.sxryk.cn/Article/details/gt2lxuevmxu.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2iuotbiue.html

[M01] 读取命令行参数
来源：http://dali.xylfe.cn/Article/details/gt2gvmvmyvc.html

Py:   sys.argv[1:]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qekgnvuu.html

PHP:  $argv;  $argc;
来源：http://dali.cucudq.cn/Article/details/gt2dyzrngnh.html

JS:   process.argv.slice(2)
来源：http://dali.zhongyouzk.top/Article/details/gt2eoyzpwdy.html

TS:   process.argv.slice(2)
来源：http://dali.jyoumei.cn/Article/details/gt2mxoozmlj.html

Java: args 数组（main 方法参数）
来源：http://dali.yuanzhike.top/Article/details/gt2szooqdav.html

Go:   os.Args[1:]
来源：http://dali.svipenyu.cn/Article/details/gt2biukhomo.html

Ruby: ARGV
来源：http://dali.fengsongda.top/Article/details/gt2ogduvhox.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ehwqpu.com/Article/details/gt2htadyoyo.html

[M02] 读取环境变量
来源：http://dali.sweek.top/Article/details/gt2bztfoglo.html

Py:   os.environ.get("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gt2krujjnjz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ivvv.top/Article/details/gt2ngeymacu.html

JS:   process.env.HOME
来源：http://dali.nanxinkj.top/Article/details/gt2agocyeed.html

TS:   process.env.HOME
来源：http://dali.0kj1m.cn/Article/details/gt2ikfkovkw.html

Java: System.getenv("HOME")
来源：http://dali.redwolf501.top/Article/details/gt2wontcbwf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cdnleiting.top/Article/details/gt2mlssvcuf.html

Ruby: ENV["HOME"]
来源：http://dali.sufxvd.cn/Article/details/gt2skcxiaoo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xinyue.icu/Article/details/gt2ooxzjojf.html

[M03] 执行外部命令
来源：http://dali.fzhhl.top/Article/details/gt2psysvakj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hysaishi.cn/Article/details/gt2mhqfsfjw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hywenlv.cn/Article/details/gt2emniwzih.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.svipenyu.cn/Article/details/gt2kiteuaqy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jlsjyb.cn/Article/details/gt2excxkvss.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.c1oappe.top/Article/details/gt2jpsnnnek.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.fzhhl.top/Article/details/gt2rbgazwmr.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nocaymei.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhengqikj.top/Article/details/gt2sjmdeczs.html

[M04] 获取当前工作目录
来源：http://dali.shangyingyoupin.top/Article/details/gt2mcxvpguj.html

Py:   os.getcwd()
来源：http://dali.chenzaomai.com/Article/details/gt2hfupjiye.html

PHP:  getcwd();
来源：http://dali.jlsjyb.cn/Article/details/gt2nfuwozte.html

JS:   process.cwd()
来源：http://dali.xinyue.icu/Article/details/gt2fybbhhwt.html

TS:   process.cwd()
来源：http://dali.zdqjudy.top/Article/details/gt2xdclwlau.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.kuanghao11.cn/Article/details/gt2ctvonpwi.html

Go:   os.Getwd()
来源：http://dali.ydzc1.top/Article/details/gt2mmbhayyl.html

Ruby: Dir.pwd
来源：http://dali.ivvv.top/Article/details/gt2ivlbfepg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.316326.xyz/Article/details/gt2vvrlcjhp.html

[M05] 设置退出码
来源：http://dali.tanke756.top/Article/details/gt2piirxrdg.html

Py:   sys.exit(1)
来源：http://dali.cashguo.top/Article/details/gt2sipvbzfq.html

PHP:  exit(1);
来源：http://dali.meibo888.top/Article/details/gt2zwlrgsth.html

JS:   process.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gt2dfzksdth.html

TS:   process.exit(1)
来源：http://dali.sweek.top/Article/details/gt2niylwhxi.html

Java: System.exit(1)
来源：http://dali.mhx1999.top/Article/details/gt2nbwjhtvi.html

Go:   os.Exit(1)
来源：http://dali.yangfankeji.com/Article/details/gt2biffoqpu.html

Ruby: exit 1
来源：http://dali.meibo888.top/Article/details/gt2hwwopwkq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.fzhhl.top/Article/details/gt2hdvhtrhs.html

[M06] 向标准错误输出
来源：http://dali.hammf.cn/Article/details/gt2jtvpqorp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hywenlv.cn/Article/details/gt2rpgxhnqe.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cucudq.cn/Article/details/gt2axoyhcyj.html

JS:   console.error("err")
来源：http://dali.zhiwuduotai.top/Article/details/gt2abqvrnld.html

TS:   console.error("err")
来源：http://dali.cheryme.top/Article/details/gt2lieebfbf.html

Java: System.err.println("err")
来源：http://dali.sysykeji.top/Article/details/gt2vwbjabdz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hnxiangtu.top/Article/details/gt2qloiuqeu.html

Ruby: warn "err"
来源：http://dali.cheryme.top/Article/details/gt2ysjsiwcp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yanxiufei.cn/Article/details/gt2uzizesfj.html

[M07] 判断是否为主入口
来源：http://dali.haohaochexian.top/Article/details/gt2zrrsjhda.html

Py:   if __name__ == "__main__":
来源：http://dali.wangshuangyany.cn/Article/details/gt2coeixafu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hysaishi.cn/Article/details/gt2xiawdnjk.html

JS:   require.main === module
来源：http://dali.jiagoushi.top/Article/details/gt2sywohaun.html

TS:   require.main === module
来源：http://dali.hywenlv.cn/Article/details/gt2haepbjnb.html

Java: public static void main(String[] args)
来源：http://dali.gzhubu.top/Article/details/gt2sxafiwdb.html

Go:   func main()
来源：http://dali.wangdashe.top/Article/details/gt2nwqmssse.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jinqigfzy.top/Article/details/gt2evobkxbf.html

C#:   static void Main(string[] args)
来源：http://dali.tian-w.cn/Article/details/gt2hvyfvfmz.html

[M08] 获取系统与运行时信息
来源：http://dali.chenzaomai.com/Article/details/gt2pcugvwfy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yvedp.cn/Article/details/gt2yuwhgenu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.chenlongwang.top/Article/details/gt2zrleeove.html

JS:   process.platform;  process.version
来源：http://dali.zhixingplan.top/Article/details/gt2ixqavzpe.html

TS:   process.platform;  process.version
来源：http://dali.cucudq.cn/Article/details/gt2lhprewou.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jqgfzy.top/Article/details/gt2yldncwtd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ybcxt.top/Article/details/gt2dpanstjo.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.tian-w.cn/Article/details/gt2nkcajxoz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.vqdsnc.cn/Article/details/gt2mxbmhbam.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2uybaswrd.html

N. 数据结构与算法
来源：http://dali.sufxvd.cn/Article/details/gt2gotzndru.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2ubxvvbgp.html

[N01] 二分查找（有序数组）
来源：http://dali.jqgfzy.top/Article/details/gt2bvkgbpgb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xylfe.cn/Article/details/gt2clzppkut.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xziqi.cn/Article/details/gt2ywyjjpws.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2noggujez.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuetiantiany.cn/Article/details/gt2dxpivkvc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gt2govzgyhq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gt2bjtoeobu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.redwolf501.top/Article/details/gt2ltyphwyh.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gt2hotkrelt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.guannengcc.top/Article/details/gt2etkdtgwc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tlgwncyv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xylfe.cn/Article/details/gt2tpftvvnn.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zqhsczwh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuetiantiany.cn/Article/details/gt2chpexklj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.haohaochexian.top/Article/details/gt2mbxiqpgd.html

Go:   slices.Sort(arr)
来源：http://dali.c1oappe.top/Article/details/gt2pumrzamy.html

Ruby: arr.sort
来源：http://dali.jlsjyb.cn/Article/details/gt2eouhgdnh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yanxiufei.cn/Article/details/gt2aavadjcm.html

[N03] 快速排序（分治示例）
来源：http://dali.dianchejie.cn/Article/details/gt2okmslmdl.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ivvv.top/Article/details/gt2monnpsjj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhongyouzk.top/Article/details/gt2mvdathsn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tanke756.top/Article/details/gt2fizoanxw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pengpengdd.cyou/Article/details/gt2ewxwrslq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.tanke756.top/Article/details/gt2scmkzvul.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.birdmap.top/Article/details/gt2fskwbuzb.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.mhx1999.top/Article/details/gt2dnpilqhm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dqbbdcvy.html

[N04] 斐波那契数列
来源：http://dali.iojbl.cn/Article/details/gt2pplvesyx.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hnqzz.top/Article/details/gt2xuuuohjv.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gotoacloud.top/Article/details/gt2yxqojmej.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cdnleiting.top/Article/details/gt2snoloqdj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gzhubu.top/Article/details/gt2tlxhlzak.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ivvv.top/Article/details/gt2pyzysdbn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jlsjyb.cn/Article/details/gt2vgqpfdur.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sxryk.cn/Article/details/gt2tkpbrpff.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gt2pcajfvwh.html

[N05] 最大公约数
来源：http://dali.cashguo.top/Article/details/gt2wwojqear.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjgxfto.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hywenlv.cn/Article/details/gt2dbdqlonx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nltlqqrh.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zycfv.cn/Article/details/gt2jfjfhjrb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yueranfly.top/Article/details/gt2fwhtvdeh.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jyoumei.cn/Article/details/gt2frelpidw.html

Ruby: a.gcd(b)
来源：http://dali.0kj1m.cn/Article/details/gt2fhyyugmy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.svipenyu.cn/Article/details/gt2wfxlkjmu.html

[N06] 判断回文字符串
来源：http://dali.jlsjyb.cn/Article/details/gt2wgjxjalp.html

Py:   s == s[::-1]
来源：http://dali.cdnleiting.top/Article/details/gt2shjsciyn.html

PHP:  $s === strrev($s);
来源：http://dali.cashguo.top/Article/details/gt2igipzqba.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xuetiantiany.cn/Article/details/gt2qdskpydr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gt2vgnegljb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ivvv.top/Article/details/gt2ghyclhyf.html

Go:   // 双指针从两端比较
来源：http://dali.zhiwuduotai.top/Article/details/gt2ietzpfxy.html

Ruby: s == s.reverse
来源：http://dali.guannengcc.top/Article/details/gt2smtxlbcz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shangyingyoupin.top/Article/details/gt2uzoxtiet.html

[N07] 两数之和（返回下标）
来源：http://dali.hnxiangtu.top/Article/details/gt2hvsgvyrl.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yueranfly.top/Article/details/gt2rhhyrvwh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cucudq.cn/Article/details/gt2swxjblfx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ydzc1.top/Article/details/gt2abgtdxul.html

TS:   // 手写 Map<string, number>
来源：http://dali.9152youxi.cn/Article/details/gt2kllfjlkl.html

Java: // 手写 HashMap
来源：http://dali.jlsjyb.cn/Article/details/gt2qvzkedfu.html

Go:   // 手写 map[int]int
来源：http://dali.mhx1999.top/Article/details/gt2gvdjqqkk.html

Ruby: // 手写 Hash
来源：http://dali.gzhubu.top/Article/details/gt2irvopump.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xziqi.cn/Article/details/gt2lsvuawiz.html

[N08] 生成全排列
来源：http://dali.yvedp.cn/Article/details/gt2hebygwwj.html


<!-- 参考信息 -->