代发 wailian999

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xziqi.cn/Article/details/gtjrcwpwiw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jqgufenzy.top/Article/details/gtqcfyzalu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yuxming.cn/Article/details/gtfaengapf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.wangdashe.top/Article/details/gtbsdkrmqo.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtcloxlavi.html

K. JSON 与序列化
来源：http://dali.hywenlv.cn/Article/details/gthytdqfkj.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtqurodese.html

[K01] 对象转 JSON 字符串
来源：http://dali.nanxuanxn.top/Article/details/gtfunrxxjl.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shangyingyoupin.top/Article/details/gtazzqpson.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yj202588.top/Article/details/gtynwgcqlu.html

JS:   JSON.stringify(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtizhetaux.html

TS:   JSON.stringify(obj)
来源：http://dali.xylfe.cn/Article/details/gtwdfqacuv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.snrcjt.cn/Article/details/gtixzqaodl.html

Go:   json.Marshal(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtviuxwymf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhixingplan.top/Article/details/gtvvilkmcx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtosquqvuk.html

[K02] JSON 字符串转对象
来源：http://dali.jiagoushi.top/Article/details/gtlctjjpgn.html

Py:   json.loads(s)
来源：http://dali.yonumen.top/Article/details/gtuhsvuish.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ppjwa.cn/Article/details/gtovhtcaut.html

JS:   JSON.parse(s)
来源：http://dali.yanxiufei.cn/Article/details/gtcyexwnwu.html

TS:   JSON.parse(s)
来源：http://dali.yj202588.top/Article/details/gtnqtnfskk.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gtvmcdzyfd.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhongyouzk.top/Article/details/gtwriqcycv.html

Ruby: JSON.parse(s)
来源：http://dali.yj20258888.top/Article/details/gtinwxtvfk.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yj20258888.top/Article/details/gtdnegpnmn.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gotoacloud.top/Article/details/gtscxqtnyw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ppjwa.cn/Article/details/gtwinxwxtv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgufenzy.top/Article/details/gtbbninhfh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.nwbrower.top/Article/details/gtdomebymd.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xziqi.cn/Article/details/gtxziaorhd.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shzxlz.cn/Article/details/gtrkqfoguw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.fzhhl.top/Article/details/gtjfbvbrfg.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.nanxinkj.top/Article/details/gtiawhxrtc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.guannengcc.top/Article/details/gtqsdwvwid.html

[K04] 读取 JSON 文件
来源：http://dali.guowangkeji.top/Article/details/gttniefxpw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.kuanghao11.cn/Article/details/gtucqzbyaa.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gzhubu.top/Article/details/gtnjnmlpvy.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zycfv.cn/Article/details/gtifxnqzhj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhongyouzk.top/Article/details/gtlfjxkkll.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.pengpengdd.cyou/Article/details/gtujbfsavs.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hnxiangtu.top/Article/details/gtmwxhmaaj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sxryk.cn/Article/details/gtmjzjfitq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.chenlongwang.top/Article/details/gttzheqbwe.html

[K05] 深拷贝对象
来源：http://dali.hongshengwenyu.top/Article/details/gtdwplinei.html

Py:   copy.deepcopy(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtdmfvpglx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.havefunace.top/Article/details/gtvpoyaqnn.html

JS:   structuredClone(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcqdkerfa.html

TS:   structuredClone(obj)
来源：http://dali.zhengqikj.top/Article/details/gtbeirtumx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbpsyrjks.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.bjfxy.top/Article/details/gtydqajoar.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.shzxlz.cn/Article/details/gtsjkjmygw.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.smart0.xyz/Article/details/gtktivymzp.html

[K06] 解析 URL 查询串
来源：http://dali.zhoulong.xyz/Article/details/gtcgipyrsq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.bjfxy.top/Article/details/gtsbiaqemd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ybcxt.top/Article/details/gtjsbgxuag.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sxryk.cn/Article/details/gtjhbdgwuo.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyhwmhtkp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yuxming.cn/Article/details/gtrxrasypq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gtrhmyasva.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.kuanghao11.cn/Article/details/gtkxgbojwc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gtfzmrysbb.html

[K07] 进制转换
来源：http://dali.ivvv.top/Article/details/gtmxewfnnm.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.havefunace.top/Article/details/gtoihjmenb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinqigufen.top/Article/details/gtbuncwfhg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gtztrqhpsg.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gtxdkjgtim.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gtjdvbbohf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.0kj1m.cn/Article/details/gtxiwyewun.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.smart0.xyz/Article/details/gthpssvedv.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gtbmyhkfkf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.havefunace.top/Article/details/gttdwmmnsp.html

Py:   pickle.dumps(obj)
来源：http://dali.yueranfly.top/Article/details/gtcoyqgwez.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jiagoushi.top/Article/details/gtnbciepbp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhongyouzk.top/Article/details/gtmdvqlkkk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.nwbrower.top/Article/details/gtmlyrplmt.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hfpthk.cn/Article/details/gtfhvnlduc.html

Go:   encoding/gob
来源：http://dali.sweek.top/Article/details/gtmqwkeyrd.html

Ruby: Marshal.dump(obj)
来源：http://dali.mhx1999.top/Article/details/gtyaflaahy.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.daria6918.cn/Article/details/gtitaknkpt.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtbbnplyrl.html

L. 网络请求
来源：http://dali.jqgufenzy.top/Article/details/gtvaixchtg.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gttunzwult.html

[L01] 发送 GET 请求
来源：http://dali.jlsjyb.cn/Article/details/gtbssvubhg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jlsjyb.cn/Article/details/gtrpaubwgz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.aibaodan.cn/Article/details/gtiipttkyr.html

JS:   await fetch(url)
来源：http://dali.yuanzhike.top/Article/details/gthnomcsix.html

TS:   await fetch(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyjzftjzb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hammf.cn/Article/details/gtwhyccmat.html

Go:   resp, err := http.Get(url)
来源：http://dali.hywenlv.cn/Article/details/gtpotqgpdd.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yonumen.top/Article/details/gtgnckywlg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.chenjidiqi.icu/Article/details/gtwqxpfxft.html

[L02] 发送 POST JSON
来源：http://dali.yj20258888.top/Article/details/gtwpkcbrcf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.snrcjt.cn/Article/details/gtirjkfeqp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.fengsongda.top/Article/details/gtjzskqrlv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsfpyvvlt.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hywenlv.cn/Article/details/gtfswvfdek.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gotoacloud.top/Article/details/gtduszttqf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sweek.top/Article/details/gtzuluevgk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhoulong.xyz/Article/details/gtgolscfbc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zdqjudy.top/Article/details/gtnbbcfyji.html

[L03] 设置自定义请求头
来源：http://dali.nwbrower.top/Article/details/gtsxyrxpmq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jqgufenzy.top/Article/details/gtbffrpvwy.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cheryme.top/Article/details/gtjmfnppvt.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pengpengdd.cyou/Article/details/gtvwcedwxp.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nwbrower.top/Article/details/gtzlflidjw.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.chenzaomai.com/Article/details/gtariuhdvz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sufxvd.cn/Article/details/gtjfowfkfm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shzxlz.cn/Article/details/gtxdqlmcrb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.birdmap.top/Article/details/gtoayfzjnu.html

[L04] 设置超时
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvjqagycp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhoulong.xyz/Article/details/gtgljwutqc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.haohaochexian.top/Article/details/gtkarbzwwq.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.316326.xyz/Article/details/gtslinqypl.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aibaodan.cn/Article/details/gtsuwjpiye.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.wangshuangyany.cn/Article/details/gtxgdbvhjw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xuanzx.com/Article/details/gtfssgdclz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cdnleiting.top/Article/details/gtlubkrrme.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.bjfxy.top/Article/details/gtnwctrqjz.html

[L05] 上传文件（multipart）
来源：http://dali.hywenlv.cn/Article/details/gtnaaosblj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ybcxt.top/Article/details/gtuovchymi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.haohaochexian.top/Article/details/gttrlujtrv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yonumen.top/Article/details/gtixkzksui.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jianghu66.top/Article/details/gtrkwlzovp.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.fengsongda.top/Article/details/gthkrfnfgn.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zycfv.cn/Article/details/gtkcpcgavy.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xylfe.cn/Article/details/gtsbzaxdpe.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjgtvocmv.html

[L06] 解析响应为 JSON
来源：http://dali.havefunace.top/Article/details/gtouxocxhx.html

Py:   resp.json()
来源：http://dali.ppjwa.cn/Article/details/gtablgzfef.html

PHP:  json_decode($body, true);
来源：http://dali.snrcjt.cn/Article/details/gtualpzonu.html

JS:   await resp.json()
来源：http://dali.chenzaomai.com/Article/details/gtndrzrowd.html

TS:   await resp.json()
来源：http://dali.9152youxi.cn/Article/details/gtmojcrkcp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jyoumei.cn/Article/details/gtplvvkaaq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hysaishi.cn/Article/details/gtxfizkkit.html

Ruby: JSON.parse(resp.body)
来源：http://dali.316326.xyz/Article/details/gtmktuuiqp.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.aizwys.cn/Article/details/gtkquvhyzp.html

[L07] 处理 HTTP 状态码
来源：http://dali.svipenyu.cn/Article/details/gtpghtpdxz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cheryme.top/Article/details/gtewklfrnr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ppjwa.cn/Article/details/gthzutfend.html

JS:   resp.ok;  resp.status
来源：http://dali.kuanghao11.cn/Article/details/gtecesdzyr.html

TS:   resp.ok;  resp.status
来源：http://dali.nanxuanxn.top/Article/details/gtjffmkxqo.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gtkuwhzbym.html

Go:   resp.StatusCode
来源：http://dali.jqgfzy.top/Article/details/gtwftdpvpi.html

Ruby: resp.code.to_i
来源：http://dali.ppjwa.cn/Article/details/gtipgidicg.html

C#:   (int)resp.StatusCode
来源：http://dali.hywenlv.cn/Article/details/gtbaxvswml.html

[L08] 并发请求多个地址
来源：http://dali.zdqjudy.top/Article/details/gtxaocpfvz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sysykeji.top/Article/details/gtrazdsyak.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhiwuduotai.top/Article/details/gtwtzzyzjn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnxiangtu.top/Article/details/gtpkbyyxrz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gtbbhlrnhs.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jyoumei.cn/Article/details/gtjirjkxmh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinyuanbaomall.cn/Article/details/gtobrpjylt.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xuetiantiany.cn/Article/details/gtwfqzcdlh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xinyue.icu/Article/details/gtgggsandb.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtsfrmzqrv.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenzaomai.com/Article/details/gtslhoyegx.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtgmujwgss.html

[M01] 读取命令行参数
来源：http://dali.iojbl.cn/Article/details/gtrgvkajnn.html

Py:   sys.argv[1:]
来源：http://dali.316326.xyz/Article/details/gtijzeaxng.html

PHP:  $argv;  $argc;
来源：http://dali.jqgufenzy.top/Article/details/gtppgtdzwk.html

JS:   process.argv.slice(2)
来源：http://dali.ybcxt.top/Article/details/gtondcfpcb.html

TS:   process.argv.slice(2)
来源：http://dali.pycfn.com/Article/details/gtuquxviwv.html

Java: args 数组（main 方法参数）
来源：http://dali.nwbrower.top/Article/details/gtpkliaotf.html

Go:   os.Args[1:]
来源：http://dali.yuxming.cn/Article/details/gtfvfdgbsk.html

Ruby: ARGV
来源：http://dali.0kj1m.cn/Article/details/gtjowskzoa.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gaohongyu789.top/Article/details/gtvwlnnfxx.html

[M02] 读取环境变量
来源：http://dali.tianlin.xyz/Article/details/gtnczodxgq.html

Py:   os.environ.get("HOME")
来源：http://dali.daria6918.cn/Article/details/gtixwrtsvs.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.guannengcc.top/Article/details/gtjqgcjbma.html

JS:   process.env.HOME
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsnlqdqfr.html

TS:   process.env.HOME
来源：http://dali.guowangkeji.top/Article/details/gtudavuvqi.html

Java: System.getenv("HOME")
来源：http://dali.cucudq.cn/Article/details/gtnpfrfugi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.daxiang520.top/Article/details/gttnbkeklq.html

Ruby: ENV["HOME"]
来源：http://dali.0kj1m.cn/Article/details/gtzpxevvah.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gogol.net.cn/Article/details/gtxzqeqpvf.html

[M03] 执行外部命令
来源：http://dali.hnxiangtu.top/Article/details/gtnggqdgln.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hysaishi.cn/Article/details/gtwfgbiwad.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmaqrddsw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cheryme.top/Article/details/gtwlhbnjya.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tanke756.top/Article/details/gtgwwpinvw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.dianchejie.cn/Article/details/gtndzxgiui.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.feifeiyinyue.top/Article/details/gtozrsasus.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shanyushiyangtech.top/Article/details/gttnvncdhy.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gogol.net.cn/Article/details/gtfjqzqzsb.html

[M04] 获取当前工作目录
来源：http://dali.svipenyu.cn/Article/details/gtrrbvbkrp.html

Py:   os.getcwd()
来源：http://dali.havefunace.top/Article/details/gtwadkvpkk.html

PHP:  getcwd();
来源：http://dali.yvedp.cn/Article/details/gtodjderrn.html

JS:   process.cwd()
来源：http://dali.9152youxi.cn/Article/details/gtkxhcfkyf.html

TS:   process.cwd()
来源：http://dali.mhx1999.top/Article/details/gtnscpikce.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yj202588.top/Article/details/gtgfujkajj.html

Go:   os.Getwd()
来源：http://dali.jlsjyb.cn/Article/details/gthettwmlt.html

Ruby: Dir.pwd
来源：http://dali.zhixingplan.top/Article/details/gtidutnrfe.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.daxiang520.top/Article/details/gthrpsaixn.html

[M05] 设置退出码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtztfqgyow.html

Py:   sys.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtjgtrifqx.html

PHP:  exit(1);
来源：http://dali.hnqzz.top/Article/details/gtibbzzejs.html

JS:   process.exit(1)
来源：http://dali.tanke756.top/Article/details/gtvfldcsmn.html

TS:   process.exit(1)
来源：http://dali.sysykeji.top/Article/details/gtnlkvtzxm.html

Java: System.exit(1)
来源：http://dali.aizwys.cn/Article/details/gtdkepasew.html

Go:   os.Exit(1)
来源：http://dali.jiagoushi.top/Article/details/gtplkbttjb.html

Ruby: exit 1
来源：http://dali.yonumen.top/Article/details/gtbzqegssf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xuetiantiany.cn/Article/details/gtprcdbrzh.html

[M06] 向标准错误输出
来源：http://dali.vqdsnc.cn/Article/details/gtfbpklssk.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrrvrmdfi.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.dashuyun.cn/Article/details/gtjwughyvg.html

JS:   console.error("err")
来源：http://dali.zdqjudy.top/Article/details/gtgiimddrd.html

TS:   console.error("err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxfmemwxt.html

Java: System.err.println("err")
来源：http://dali.haohaochexian.top/Article/details/gtcobkqwjx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpgqdmdhd.html

Ruby: warn "err"
来源：http://dali.iojbl.cn/Article/details/gtcnscydsi.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hfpthk.cn/Article/details/gtlhtknejn.html

[M07] 判断是否为主入口
来源：http://dali.316326.xyz/Article/details/gtramxutdk.html

Py:   if __name__ == "__main__":
来源：http://dali.shangyingyoupin.top/Article/details/gtxcjvdsnl.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhixingplan.top/Article/details/gtfzronjfc.html

JS:   require.main === module
来源：http://dali.nwbrower.top/Article/details/gtqkkotxbq.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gtaqhtsnxy.html

Java: public static void main(String[] args)
来源：http://dali.sweek.top/Article/details/gtvlpqqqwo.html

Go:   func main()
来源：http://dali.hongshengwenyu.top/Article/details/gtujgvhvzd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.guannengcc.top/Article/details/gthzbcaepo.html

C#:   static void Main(string[] args)
来源：http://dali.guannengcc.top/Article/details/gtzqexsccd.html

[M08] 获取系统与运行时信息
来源：http://dali.0kj1m.cn/Article/details/gtzgdmsksu.html

Py:   platform.system();  platform.python_version()
来源：http://dali.aizwys.cn/Article/details/gtiwpyjrdb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.chenjidiqi.icu/Article/details/gtktjcxrcw.html

JS:   process.platform;  process.version
来源：http://dali.dianchejie.cn/Article/details/gtefyrsvij.html

TS:   process.platform;  process.version
来源：http://dali.xinyue.icu/Article/details/gtilpmniyr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xinyue.icu/Article/details/gtpyssxraa.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jqgfzy.top/Article/details/gtwannosml.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.fzhhl.top/Article/details/gtjygprbqd.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zycfv.cn/Article/details/gtodedhflr.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtymjjhjhq.html

N. 数据结构与算法
来源：http://dali.jinghuilouyu.cn/Article/details/gtybuqblkh.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtriqofixq.html

[N01] 二分查找（有序数组）
来源：http://dali.jianghu66.top/Article/details/gtucvyktih.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtxxmugjss.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.fzhhl.top/Article/details/gtxawvhtjh.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuanzx.com/Article/details/gtijfiutvx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nwbrower.top/Article/details/gtftobrzhc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtiqvprxdy.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtttnwtkrf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.dashuyun.cn/Article/details/gthoalzpiw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gtcxqiiizz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cdnleiting.top/Article/details/gttrpxzppd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxinkj.top/Article/details/gtidlxmtgz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jlsjyb.cn/Article/details/gtwmlugzkm.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnkbwnfih.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guowangkeji.top/Article/details/gtsbjfvstp.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jiagoushi.top/Article/details/gtpxxozwdj.html

Go:   slices.Sort(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpksrryav.html

Ruby: arr.sort
来源：http://dali.chenjidiqi.icu/Article/details/gtpetjplku.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.bjfxy.top/Article/details/gtknqzbiek.html

[N03] 快速排序（分治示例）
来源：http://dali.tianlin.xyz/Article/details/gttojgyuim.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ehwqpu.com/Article/details/gtcrmpgiso.html

PHP:  // 递归实现，或用 usort
来源：http://dali.snrcjt.cn/Article/details/gttmeeegee.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ydzc1.top/Article/details/gtnybecrec.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xziqi.cn/Article/details/gtyhyfuwrc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.wangshuangyany.cn/Article/details/gtfrxxolwl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.iojbl.cn/Article/details/gtnqrhjyff.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.dianchejie.cn/Article/details/gtrdxxfwmb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.meibo888.top/Article/details/gtdvyhbqqo.html

[N04] 斐波那契数列
来源：http://dali.jiagoushi.top/Article/details/gtazeuxezr.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.0kj1m.cn/Article/details/gtmdfhfmsm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jqgufenzy.top/Article/details/gtcckytzlu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cheryme.top/Article/details/gtlncdwmtg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuanzhike.top/Article/details/gtmbvvjhpl.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.wangdashe.top/Article/details/gtfeoruxqp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.fengsongda.top/Article/details/gttwwjbngj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zycfv.cn/Article/details/gtgfyzatnu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.316326.xyz/Article/details/gtajtjptst.html

[N05] 最大公约数
来源：http://dali.gotoacloud.top/Article/details/gtbtsfjvwj.html

Py:   math.gcd(a, b)
来源：http://dali.meibo888.top/Article/details/gteghbubpw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcfjckdji.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ivvv.top/Article/details/gtwibbgduv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pengpengdd.cyou/Article/details/gtpsvoqiqw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sysykeji.top/Article/details/gtajlwdvbr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgyfcajgp.html

Ruby: a.gcd(b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqyzbyfja.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xuetiantiany.cn/Article/details/gtguocwjmh.html

[N06] 判断回文字符串
来源：http://dali.iojbl.cn/Article/details/gtzowcinhg.html

Py:   s == s[::-1]
来源：http://dali.aizwys.cn/Article/details/gtlspbauhp.html

PHP:  $s === strrev($s);
来源：http://dali.aibaodan.cn/Article/details/gtkvkjxdne.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtyrcipsbg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ydzc1.top/Article/details/gtnmscxzrw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hongshengwenyu.top/Article/details/gtdohzlfhx.html

Go:   // 双指针从两端比较
来源：http://dali.mhx1999.top/Article/details/gtnruycopx.html

Ruby: s == s.reverse
来源：http://dali.gzhubu.top/Article/details/gtsxdtqphr.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hnxiangtu.top/Article/details/gtottljjoe.html

[N07] 两数之和（返回下标）
来源：http://dali.jqgufenzy.top/Article/details/gturwqlhul.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hnxiangtu.top/Article/details/gtwjjcqfsn.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cucudq.cn/Article/details/gtaovixjqb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shangyingyoupin.top/Article/details/gtdymlyjtj.html

TS:   // 手写 Map<string, number>
来源：http://dali.jianghu66.top/Article/details/gtuafbnthi.html

Java: // 手写 HashMap
来源：http://dali.chenjidiqi.icu/Article/details/gtzvtjaxhj.html

Go:   // 手写 map[int]int
来源：http://dali.xylfe.cn/Article/details/gtnneuoyvo.html

Ruby: // 手写 Hash
来源：http://dali.9152youxi.cn/Article/details/gtdzsqgqtx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ppjwa.cn/Article/details/gtmbpqmdqp.html

[N08] 生成全排列
来源：http://dali.shzxlz.cn/Article/details/gtlockduoh.html

Py:   itertools.permutations(arr)
来源：http://dali.fzhhl.top/Article/details/gtqfrwmupx.html

PHP:  // 手写递归交换
来源：http://dali.jinqigfzy.top/Article/details/gtxwpnbvei.html

JS:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gtywrrluev.html

TS:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gtbstktbtt.html


<!-- 参考信息 -->