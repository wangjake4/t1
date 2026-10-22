代发 wailian999

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2dqrwnwzp.html

K. JSON 与序列化
来源：http://dali.ehwqpu.com/Article/details/gt2wcnuabnl.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2pxntgdif.html

[K01] 对象转 JSON 字符串
来源：http://dali.hysaishi.cn/Article/details/gt2yltwksuy.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.birdmap.top/Article/details/gt2joohtbzl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.kuanghao11.cn/Article/details/gt2nwfmliiy.html

JS:   JSON.stringify(obj)
来源：http://dali.havefunace.top/Article/details/gt2jqjhuyat.html

TS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ujktldzb.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.redwolf501.top/Article/details/gt2vqybzwma.html

Go:   json.Marshal(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2grjwbbmt.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinqigfzy.top/Article/details/gt2pamvzxcl.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2hcpraify.html

[K02] JSON 字符串转对象
来源：http://dali.snrcjt.cn/Article/details/gt2whuguwiy.html

Py:   json.loads(s)
来源：http://dali.cdnleiting.top/Article/details/gt2gpohwhwv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.meibo888.top/Article/details/gt2bnxkmgpe.html

JS:   JSON.parse(s)
来源：http://dali.xuanzx.com/Article/details/gt2eaoblxzg.html

TS:   JSON.parse(s)
来源：http://dali.fzhhl.top/Article/details/gt2pjstsrkk.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yj20258888.top/Article/details/gt2dfwmxzwq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sysykeji.top/Article/details/gt2bpknijiw.html

Ruby: JSON.parse(s)
来源：http://dali.daxiang520.top/Article/details/gt2oxjmaqvq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2gbehfnkc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ivvv.top/Article/details/gt2hsbazpts.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ppjwa.cn/Article/details/gt2kulqscoq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yj202588.top/Article/details/gt2migojwxj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xinyue.icu/Article/details/gt2ykktuytg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kcieliap.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.meibo888.top/Article/details/gt2zyqmlvic.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.meibo888.top/Article/details/gt2kbdrxphe.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hammf.cn/Article/details/gt2gtoanhjw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.vqdsnc.cn/Article/details/gt2uorzhvni.html

[K04] 读取 JSON 文件
来源：http://dali.xuanzx.com/Article/details/gt2zlegirri.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cqqwz.cn/Article/details/gt2ffwsmeva.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.fengsongda.top/Article/details/gt2pyjpduux.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxinkj.top/Article/details/gt2kzdffadn.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.quarkkingdee.top/Article/details/gt2dhjzainc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hnqzz.top/Article/details/gt2zjymwenw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sysykeji.top/Article/details/gt2exwwqlos.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.birdmap.top/Article/details/gt2iunaeasm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xylfe.cn/Article/details/gt2eqkubvwi.html

[K05] 深拷贝对象
来源：http://dali.zhiwuduotai.top/Article/details/gt2gjzqoddk.html

Py:   copy.deepcopy(obj)
来源：http://dali.wangdashe.top/Article/details/gt2cpquhhwu.html

PHP:  unserialize(serialize($obj));
来源：http://dali.nanxuanxn.top/Article/details/gt2zrfoqjuf.html

JS:   structuredClone(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2tysybajy.html

TS:   structuredClone(obj)
来源：http://dali.tanke756.top/Article/details/gt2dzryfawt.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.gotoacloud.top/Article/details/gt2memfksii.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.c1oappe.top/Article/details/gt2hdejtbek.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.iojbl.cn/Article/details/gt2oiornmtd.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shuidangran.top/Article/details/gt2zrdgtoqc.html

[K06] 解析 URL 查询串
来源：http://dali.jqgfzy.top/Article/details/gt2ppxhngrg.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yj202588.top/Article/details/gt2tdslcmbl.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ybcxt.top/Article/details/gt2brvfkjqa.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hammf.cn/Article/details/gt2unmgojpv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.c1oappe.top/Article/details/gt2cmwezwfz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.meibo888.top/Article/details/gt2dpmvbugw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.daxiang520.top/Article/details/gt2vcitiuee.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinqigfzy.top/Article/details/gt2slcoctma.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gt2plsnnxza.html

[K07] 进制转换
来源：http://dali.tianlin.xyz/Article/details/gt2owtorhaq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gt2stcfnhnz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhiwuduotai.top/Article/details/gt2onuithnw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.birdmap.top/Article/details/gt2mbpotvzi.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cashguo.top/Article/details/gt2bxqenety.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gt2nyzugetq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.kuanghao11.cn/Article/details/gt2aibntjxt.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2sijvbjcu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gt2ilmfvfmy.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.nanxuanxn.top/Article/details/gt2ntyrjwfg.html

Py:   pickle.dumps(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2ttfdhlfn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lhmeyiqb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.wangdashe.top/Article/details/gt2xyxuixtg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.daxiang520.top/Article/details/gt2uezpyuqf.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhixingplan.top/Article/details/gt2lvrewofr.html

Go:   encoding/gob
来源：http://dali.iojbl.cn/Article/details/gt2ykwnbtli.html

Ruby: Marshal.dump(obj)
来源：http://dali.mhx1999.top/Article/details/gt2inzxiobi.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.vqdsnc.cn/Article/details/gt2podpinrc.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2tttvsgrk.html

L. 网络请求
来源：http://dali.zhengqikj.top/Article/details/gt2ouolmkez.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2glamqivz.html

[L01] 发送 GET 请求
来源：http://dali.shangyingyoupin.top/Article/details/gt2ryisbxgp.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jianghu66.top/Article/details/gt2dkacafno.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cheryme.top/Article/details/gt2xlzmluga.html

JS:   await fetch(url)
来源：http://dali.nwbrower.top/Article/details/gt2mlfhkrny.html

TS:   await fetch(url)
来源：http://dali.sweek.top/Article/details/gt2bzeqbbxo.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.fzhhl.top/Article/details/gt2ulkdbrrb.html

Go:   resp, err := http.Get(url)
来源：http://dali.jqgufenzy.top/Article/details/gt2igbiujlj.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.dashuyun.cn/Article/details/gt2iuzshqnv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.nanxinkj.top/Article/details/gt2pobhstog.html

[L02] 发送 POST JSON
来源：http://dali.sysykeji.top/Article/details/gt2zwehglff.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.sxryk.cn/Article/details/gt2brtnyngq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cqqwz.cn/Article/details/gt2gvmgokvg.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.c1oappe.top/Article/details/gt2oclvsmvg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangshuangyany.cn/Article/details/gt2hwerncbs.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shzxlz.cn/Article/details/gt2jvdxdrox.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.daxiang520.top/Article/details/gt2ajfvuval.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.chenlongwang.top/Article/details/gt2muckhjaq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sxryk.cn/Article/details/gt2erurnnap.html

[L03] 设置自定义请求头
来源：http://dali.cashguo.top/Article/details/gt2ewoayayp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhiwuduotai.top/Article/details/gt2vmysriwv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hywenlv.cn/Article/details/gt2qpwlsojs.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuetiantiany.cn/Article/details/gt2aqqkbsvg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hhwvzxxi.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhixingplan.top/Article/details/gt2uwshigqc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.bjfxy.top/Article/details/gt2tpquurar.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.quarkkingdee.top/Article/details/gt2qmghkdyc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jqgfzy.top/Article/details/gt2rlrfesfo.html

[L04] 设置超时
来源：http://dali.sufxvd.cn/Article/details/gt2ssofxvje.html

Py:   requests.get(url, timeout=5)
来源：http://dali.sxryk.cn/Article/details/gt2zbzadtkv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cdnleiting.top/Article/details/gt2euokubec.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cheryme.top/Article/details/gt2xcefegyb.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shangyingyoupin.top/Article/details/gt2riesgema.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhengqikj.top/Article/details/gt2avgwvobv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.aibaodan.cn/Article/details/gt2kjhqgcgv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.nwbrower.top/Article/details/gt2fnlowwef.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jqgufenzy.top/Article/details/gt2mqzachnn.html

[L05] 上传文件（multipart）
来源：http://dali.xuanzx.com/Article/details/gt2xbybpxvu.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zycfv.cn/Article/details/gt2zuhxkkew.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhengqikj.top/Article/details/gt2crbblhgj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hywenlv.cn/Article/details/gt2duhwobce.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.pengpengdd.cyou/Article/details/gt2eirsszhr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.snrcjt.cn/Article/details/gt2dydtoytb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kkyehngg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.wangdashe.top/Article/details/gt2pllohcgg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2cmtrbpkj.html

[L06] 解析响应为 JSON
来源：http://dali.svipenyu.cn/Article/details/gt2rtughhnc.html

Py:   resp.json()
来源：http://dali.andypj.xyz/Article/details/gt2wtlmumbk.html

PHP:  json_decode($body, true);
来源：http://dali.zhoulong.xyz/Article/details/gt2fefguawj.html

JS:   await resp.json()
来源：http://dali.iojbl.cn/Article/details/gt2pdtdlgmp.html

TS:   await resp.json()
来源：http://dali.ydzc1.top/Article/details/gt2ebgkhqhc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ssteaqct.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hfpthk.cn/Article/details/gt2raxxvyaj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nwbrower.top/Article/details/gt2qopzgjtu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ljykipdu.html

[L07] 处理 HTTP 状态码
来源：http://dali.guowangkeji.top/Article/details/gt2jdshmryc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.gaohongyu789.top/Article/details/gt2afczbipm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shangyingyoupin.top/Article/details/gt2mylbgmif.html

JS:   resp.ok;  resp.status
来源：http://dali.cheryme.top/Article/details/gt2zetiebmq.html

TS:   resp.ok;  resp.status
来源：http://dali.jinqigufen.top/Article/details/gt2xebwrlwc.html

Java: resp.statusCode()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bcbvnsfq.html

Go:   resp.StatusCode
来源：http://dali.gaohongyu789.top/Article/details/gt2oienoien.html

Ruby: resp.code.to_i
来源：http://dali.yonumen.top/Article/details/gt2kruhqwkk.html

C#:   (int)resp.StatusCode
来源：http://dali.chenjidiqi.icu/Article/details/gt2wnpcqkue.html

[L08] 并发请求多个地址
来源：http://dali.quarkkingdee.top/Article/details/gt2yspefpyv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jyoumei.cn/Article/details/gt2oxsxtntq.html

PHP:  curl_multi_init() 系列
来源：http://dali.hfpthk.cn/Article/details/gt2ltycnlcb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gdjwnxkc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rpqcgvhc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.wangshuangyany.cn/Article/details/gt2bbggpwxv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2phshcxef.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.birdmap.top/Article/details/gt2djsvfckp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.kuanghao11.cn/Article/details/gt2hhuutqqe.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2yqhgqstn.html

M. 命令行 / 进程 / 环境
来源：http://dali.snrcjt.cn/Article/details/gt2fniixawe.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2vfyynhfp.html

[M01] 读取命令行参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dhjbhsur.html

Py:   sys.argv[1:]
来源：http://dali.yuanzhike.top/Article/details/gt2egtsikxl.html

PHP:  $argv;  $argc;
来源：http://dali.yvedp.cn/Article/details/gt2xlbvyojl.html

JS:   process.argv.slice(2)
来源：http://dali.9152youxi.cn/Article/details/gt2cwcaoavj.html

TS:   process.argv.slice(2)
来源：http://dali.yuanzhike.top/Article/details/gt2khvisdbj.html

Java: args 数组（main 方法参数）
来源：http://dali.cheryme.top/Article/details/gt2alwntchr.html

Go:   os.Args[1:]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ebkyfyam.html

Ruby: ARGV
来源：http://dali.dashuyun.cn/Article/details/gt2ghaeaywb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhongyouzk.top/Article/details/gt2vvinqesv.html

[M02] 读取环境变量
来源：http://dali.yj20258.top/Article/details/gt2cogolqfp.html

Py:   os.environ.get("HOME")
来源：http://dali.cqqwz.cn/Article/details/gt2tuhgovla.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.redwolf501.top/Article/details/gt2kskaawve.html

JS:   process.env.HOME
来源：http://dali.yonumen.top/Article/details/gt2ekeeknnz.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcwdndc.html

Java: System.getenv("HOME")
来源：http://dali.gzhubu.top/Article/details/gt2jsqsukzf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.c1oappe.top/Article/details/gt2ulsnjwqd.html

Ruby: ENV["HOME"]
来源：http://dali.smart0.xyz/Article/details/gt2yagjrwum.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.birdmap.top/Article/details/gt2pcsxtttm.html

[M03] 执行外部命令
来源：http://dali.gaohongyu789.top/Article/details/gt2wrmhpbjx.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.havefunace.top/Article/details/gt2xgrzepej.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yanxiufei.cn/Article/details/gt2dzuppvww.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258.top/Article/details/gt2wkrjsqsq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxuanxn.top/Article/details/gt2jnspbdfj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hnqzz.top/Article/details/gt2gzalmfcz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shangyingyoupin.top/Article/details/gt2dsmigaew.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ehwqpu.com/Article/details/gt2mkegmrid.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qhhwybvd.html

[M04] 获取当前工作目录
来源：http://dali.yangfankeji.com/Article/details/gt2avtlaadp.html

Py:   os.getcwd()
来源：http://dali.cqqwz.cn/Article/details/gt2inhatmub.html

PHP:  getcwd();
来源：http://dali.aibaodan.cn/Article/details/gt2tymlvcpq.html

JS:   process.cwd()
来源：http://dali.hywenlv.cn/Article/details/gt2drdzoqog.html

TS:   process.cwd()
来源：http://dali.quarkkingdee.top/Article/details/gt2qgowceiz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sufxvd.cn/Article/details/gt2bmgjggzf.html

Go:   os.Getwd()
来源：http://dali.gogol.net.cn/Article/details/gt2dlrenklg.html

Ruby: Dir.pwd
来源：http://dali.jyoumei.cn/Article/details/gt2hgcbhywd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vbavsbxf.html

[M05] 设置退出码
来源：http://dali.vqdsnc.cn/Article/details/gt2rzfmlgau.html

Py:   sys.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2momxoefx.html

PHP:  exit(1);
来源：http://dali.daxiang520.top/Article/details/gt2hsfzllua.html

JS:   process.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gt2pwoiaqli.html

TS:   process.exit(1)
来源：http://dali.yj202588.top/Article/details/gt2fadlvgpi.html

Java: System.exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2ulsezxaj.html

Go:   os.Exit(1)
来源：http://dali.mhx1999.top/Article/details/gt2amtefkgi.html

Ruby: exit 1
来源：http://dali.cdnleiting.top/Article/details/gt2eutnqarn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hywenlv.cn/Article/details/gt2yytofeml.html

[M06] 向标准错误输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pvinpqtx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ppjwa.cn/Article/details/gt2rfihqgrk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yvedp.cn/Article/details/gt2dfbqsujk.html

JS:   console.error("err")
来源：http://dali.zhengqikj.top/Article/details/gt2oofddmyq.html

TS:   console.error("err")
来源：http://dali.sufxvd.cn/Article/details/gt2ujsuvdmr.html

Java: System.err.println("err")
来源：http://dali.yj202588.top/Article/details/gt2bxtllogx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.dianchejie.cn/Article/details/gt2oqupdupx.html

Ruby: warn "err"
来源：http://dali.hnxiangtu.top/Article/details/gt2ggwufsar.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gaohongyu789.top/Article/details/gt2bmiyoryk.html

[M07] 判断是否为主入口
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tdehwrfz.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2ceeijbjl.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.dashuyun.cn/Article/details/gt2jobuflhc.html

JS:   require.main === module
来源：http://dali.hfpthk.cn/Article/details/gt2jlkocgoe.html

TS:   require.main === module
来源：http://dali.ydzc1.top/Article/details/gt2alzzqwmu.html

Java: public static void main(String[] args)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ghhuniyo.html

Go:   func main()
来源：http://dali.xziqi.cn/Article/details/gt2tunjjxyf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gzhubu.top/Article/details/gt2obbqnwxv.html

C#:   static void Main(string[] args)
来源：http://dali.c1oappe.top/Article/details/gt2bwjcizem.html

[M08] 获取系统与运行时信息
来源：http://dali.nwbrower.top/Article/details/gt2devjjtlw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.redwolf501.top/Article/details/gt2kbqwnocj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tzqkfxdx.html

JS:   process.platform;  process.version
来源：http://dali.chenzaomai.com/Article/details/gt2cpjhfpgl.html

TS:   process.platform;  process.version
来源：http://dali.meibo888.top/Article/details/gt2urvbprrj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cdnleiting.top/Article/details/gt2rjonqlhm.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.aizwys.cn/Article/details/gt2tjrxlnit.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.smart0.xyz/Article/details/gt2gncxdrtg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oweeemrg.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2hhksgsto.html

N. 数据结构与算法
来源：http://dali.pengpengdd.cyou/Article/details/gt2oaykbgcb.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2sijspmsl.html

[N01] 二分查找（有序数组）
来源：http://dali.xuanzx.com/Article/details/gt2bwmdsrvf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.redwolf501.top/Article/details/gt2jrjlprqr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtqzkli.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hywenlv.cn/Article/details/gt2bndzxjwv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tian-w.cn/Article/details/gt2ojgftelp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ewkvcxrq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xziqi.cn/Article/details/gt2hbulnnds.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yuxming.cn/Article/details/gt2yokuothx.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hammf.cn/Article/details/gt2acvpyncw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yuanzhike.top/Article/details/gt2grnscuzb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aizwys.cn/Article/details/gt2rqxihhub.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.andypj.xyz/Article/details/gt2pxnnonao.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pycfn.com/Article/details/gt2rvnfpcej.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sxryk.cn/Article/details/gt2dmgsvzxw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.wangdashe.top/Article/details/gt2crmtxzaw.html

Go:   slices.Sort(arr)
来源：http://dali.jinqigfzy.top/Article/details/gt2hbbdllxh.html

Ruby: arr.sort
来源：http://dali.zhiwuduotai.top/Article/details/gt2cnirssgj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jyoumei.cn/Article/details/gt2mcitzrsg.html

[N03] 快速排序（分治示例）
来源：http://dali.cucudq.cn/Article/details/gt2tpsezzfj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xinyue.icu/Article/details/gt2rujdgemu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.pengpengdd.cyou/Article/details/gt2rqkqpgpn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cheryme.top/Article/details/gt2eevlerts.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhongyouzk.top/Article/details/gt2erykvuvm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.gogol.net.cn/Article/details/gt2drsrfpfm.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sufxvd.cn/Article/details/gt2exwfzxwy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hongshengwenyu.top/Article/details/gt2gmegodlc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ybcxt.top/Article/details/gt2vuqmfbgt.html

[N04] 斐波那契数列
来源：http://dali.snrcjt.cn/Article/details/gt2xuqgojnl.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.nanxuanxn.top/Article/details/gt2yliqydpo.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bzbpohcw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gt2jwxyavnr.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yongpay.top/Article/details/gt2zymumgiz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shuidangran.top/Article/details/gt2hnahjtxd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.c1oappe.top/Article/details/gt2jqtemifu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ybcxt.top/Article/details/gt2yginqibr.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ysuswjej.html

[N05] 最大公约数
来源：http://dali.yj20258.top/Article/details/gt2osbeongx.html

Py:   math.gcd(a, b)
来源：http://dali.daxiang520.top/Article/details/gt2jhabpkmk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.daxiang520.top/Article/details/gt2xpycbxqq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shzxlz.cn/Article/details/gt2wjhroxfd.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnxiangtu.top/Article/details/gt2dectpyrv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.redwolf501.top/Article/details/gt2mhfruakj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.guowangkeji.top/Article/details/gt2vrryhebj.html

Ruby: a.gcd(b)
来源：http://dali.hammf.cn/Article/details/gt2fkbxobdm.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.bjfxy.top/Article/details/gt2tndayizy.html

[N06] 判断回文字符串
来源：http://dali.yangfankeji.com/Article/details/gt2eilritap.html

Py:   s == s[::-1]
来源：http://dali.chenzaomai.com/Article/details/gt2mqjxtsmt.html

PHP:  $s === strrev($s);
来源：http://dali.xylfe.cn/Article/details/gt2yffhgolc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhongyouzk.top/Article/details/gt2skmosajy.html

TS:   s === [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gt2txlymsql.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xuetiantiany.cn/Article/details/gt2doilqmmj.html

Go:   // 双指针从两端比较
来源：http://dali.pengpengdd.cyou/Article/details/gt2mhbotzcc.html

Ruby: s == s.reverse
来源：http://dali.mhx1999.top/Article/details/gt2uaiipptb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yj20258.top/Article/details/gt2xtebyxgw.html

[N07] 两数之和（返回下标）
来源：http://dali.yj202588.top/Article/details/gt2csyemtbm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.dashuyun.cn/Article/details/gt2ppngfpws.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nctgqcjh.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.c1oappe.top/Article/details/gt2povnguge.html

TS:   // 手写 Map<string, number>
来源：http://dali.yueranfly.top/Article/details/gt2xwagnkov.html

Java: // 手写 HashMap
来源：http://dali.havefunace.top/Article/details/gt2jadlwqyl.html

Go:   // 手写 map[int]int
来源：http://dali.chenlongwang.top/Article/details/gt2dhjkpaoc.html

Ruby: // 手写 Hash
来源：http://dali.nwbrower.top/Article/details/gt2zglmhpfh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cucudq.cn/Article/details/gt2ssranlmt.html

[N08] 生成全排列
来源：http://dali.zycfv.cn/Article/details/gt2uhryuguf.html

Py:   itertools.permutations(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2enbnzzcw.html

PHP:  // 手写递归交换
来源：http://dali.guowangkeji.top/Article/details/gt2qnidbhsc.html

JS:   // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gt2jbcrbtah.html

TS:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gt2hjxmkneq.html

Java: // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gt2ulgiwrnk.html

Go:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gt2xwjptyvp.html

Ruby: arr.permutation.to_a
来源：http://dali.gzhubu.top/Article/details/gt2uokgwwbf.html

C#:   // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tsgmjaol.html


<!-- 参考信息 -->