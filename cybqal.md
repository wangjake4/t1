代发 wailian999

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.aizwys.cn/Article/details/gt2xibkyjpq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cashguo.top/Article/details/gt2shcfucag.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hongshengwenyu.top/Article/details/gt2fvuiargv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.iojbl.cn/Article/details/gt2qtdqwdcg.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2eylqbrwc.html

K. JSON 与序列化
来源：http://dali.0kj1m.cn/Article/details/gt2nvxiqdvb.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2owqbvxln.html

[K01] 对象转 JSON 字符串
来源：http://dali.shzxlz.cn/Article/details/gt2mipzdsrq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cashguo.top/Article/details/gt2jebwyiof.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yanxiufei.cn/Article/details/gt2uddrkxst.html

JS:   JSON.stringify(obj)
来源：http://dali.sysykeji.top/Article/details/gt2eqttzjbi.html

TS:   JSON.stringify(obj)
来源：http://dali.xuanzx.com/Article/details/gt2gtsuimhl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.pycfn.com/Article/details/gt2eodsaobc.html

Go:   json.Marshal(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2zosemmbj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gotoacloud.top/Article/details/gt2gsxmiosk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2evavytez.html

[K02] JSON 字符串转对象
来源：http://dali.zhijiandao.cn/Article/details/gt2xgealogs.html

Py:   json.loads(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2orcevnoo.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.nwbrower.top/Article/details/gt2jwvvblvq.html

JS:   JSON.parse(s)
来源：http://dali.fzhhl.top/Article/details/gt2erxihmqg.html

TS:   JSON.parse(s)
来源：http://dali.sysykeji.top/Article/details/gt2keiizdve.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.chenjidiqi.icu/Article/details/gt2xinmcezo.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yonumen.top/Article/details/gt2ldlahxiz.html

Ruby: JSON.parse(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2bhebqayn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.havefunace.top/Article/details/gt2rfxttqwe.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gotoacloud.top/Article/details/gt2zhotqdsw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.iojbl.cn/Article/details/gt2opaukjrp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.pycfn.com/Article/details/gt2cdvzsehf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jmvwjajw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.havefunace.top/Article/details/gt2azwazeps.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2haffzmxf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zdqjudy.top/Article/details/gt2yhhvkkdb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2lbqqpvkw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yuanzhike.top/Article/details/gt2axmqaymu.html

[K04] 读取 JSON 文件
来源：http://dali.zhengqikj.top/Article/details/gt2fvcrdxit.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.nwbrower.top/Article/details/gt2flnuxqsj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ijeflhgf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cashguo.top/Article/details/gt2hcicdmrl.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nwbrower.top/Article/details/gt2ddmvexds.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aeywfotx.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.nwbrower.top/Article/details/gt2gvhsobdz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shuidangran.top/Article/details/gt2ljuwjgqi.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.fengsongda.top/Article/details/gt2axboncbk.html

[K05] 深拷贝对象
来源：http://dali.jqgufenzy.top/Article/details/gt2pevgwlnh.html

Py:   copy.deepcopy(obj)
来源：http://dali.yueranfly.top/Article/details/gt2ihkfjoay.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhoulong.xyz/Article/details/gt2prlfbzww.html

JS:   structuredClone(obj)
来源：http://dali.hammf.cn/Article/details/gt2idyboybl.html

TS:   structuredClone(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2kbwtwinf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.fengsongda.top/Article/details/gt2qnofqvqo.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sufxvd.cn/Article/details/gt2qglpqaso.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xylfe.cn/Article/details/gt2nmfxyxef.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yvedp.cn/Article/details/gt2uqcmdgpl.html

[K06] 解析 URL 查询串
来源：http://dali.guannengcc.top/Article/details/gt2tjpypnmm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shzxlz.cn/Article/details/gt2smktqlwl.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.daria6918.cn/Article/details/gt2uijaykte.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sxryk.cn/Article/details/gt2ndnchaop.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shuidangran.top/Article/details/gt2kvlieicd.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhengqikj.top/Article/details/gt2muythqns.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.bjfxy.top/Article/details/gt2yfpqowzb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yuanzhike.top/Article/details/gt2mykbywps.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gotoacloud.top/Article/details/gt2oxelkvpx.html

[K07] 进制转换
来源：http://dali.gaohongyu789.top/Article/details/gt2pszjflrr.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gt2lsuywhiw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ivvv.top/Article/details/gt2zhjbnoxd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gt2rmwkstor.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfqdpho.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gt2pewxsunn.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.nanxuanxn.top/Article/details/gt2dvvcuqon.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.gogol.net.cn/Article/details/gt2yapbuyzw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gt2kbfivonx.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yj20258888.top/Article/details/gt2bzauwvwr.html

Py:   pickle.dumps(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2eholmrpd.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hywenlv.cn/Article/details/gt2ftktvjll.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.guowangkeji.top/Article/details/gt2ohefcnbo.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.guowangkeji.top/Article/details/gt2uxuibnen.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.snrcjt.cn/Article/details/gt2bgslygho.html

Go:   encoding/gob
来源：http://dali.jyoumei.cn/Article/details/gt2gvgxyftf.html

Ruby: Marshal.dump(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jbfjullx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shzxlz.cn/Article/details/gt2rkrlazco.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2vkctjekd.html

L. 网络请求
来源：http://dali.andypj.xyz/Article/details/gt2hdfngjfl.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2ztroeffx.html

[L01] 发送 GET 请求
来源：http://dali.cucudq.cn/Article/details/gt2bqthxtnh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xylfe.cn/Article/details/gt2tzwkpimz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.0kj1m.cn/Article/details/gt2dlsulgxj.html

JS:   await fetch(url)
来源：http://dali.nanxuanxn.top/Article/details/gt2omhiyxod.html

TS:   await fetch(url)
来源：http://dali.316326.xyz/Article/details/gt2goxvtjfk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xuanzx.com/Article/details/gt2hrghmjpo.html

Go:   resp, err := http.Get(url)
来源：http://dali.daria6918.cn/Article/details/gt2grcwwbzs.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yj20258.top/Article/details/gt2hiyrmbgz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.chenjidiqi.icu/Article/details/gt2fessjaft.html

[L02] 发送 POST JSON
来源：http://dali.aizwys.cn/Article/details/gt2zpbjwzvl.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.feifeiyinyue.top/Article/details/gt2cyyhgwjz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.aibaodan.cn/Article/details/gt2mfuacfuo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gaohongyu789.top/Article/details/gt2qphzaddi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jyoumei.cn/Article/details/gt2cbffrixh.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.nanxinkj.top/Article/details/gt2mggbnzlq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cheryme.top/Article/details/gt2mcgdgwgl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.daria6918.cn/Article/details/gt2qgyqxisx.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinqigufen.top/Article/details/gt2jjptvtxo.html

[L03] 设置自定义请求头
来源：http://dali.aizwys.cn/Article/details/gt2dsywonsg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yj20258888.top/Article/details/gt2xgvcfhut.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.fzhhl.top/Article/details/gt2kxtgyoyt.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jianghu66.top/Article/details/gt2lhfjzayv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.bjfxy.top/Article/details/gt2pojcsqqt.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.iojbl.cn/Article/details/gt2ivykcxfl.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gotoacloud.top/Article/details/gt2vxsibiuk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hammf.cn/Article/details/gt2wrtzhlyw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.mhx1999.top/Article/details/gt2swmmngsg.html

[L04] 设置超时
来源：http://dali.guannengcc.top/Article/details/gt2fsvfrfgh.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhoulong.xyz/Article/details/gt2gtlfmjpt.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ydzc1.top/Article/details/gt2jfdlhntw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shuidangran.top/Article/details/gt2xpsjujuu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nmferzrr.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yueranfly.top/Article/details/gt2nxxysiua.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.snrcjt.cn/Article/details/gt2sjhughzh.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wykhiupd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jianghu66.top/Article/details/gt2cgbzsgee.html

[L05] 上传文件（multipart）
来源：http://dali.jqgufenzy.top/Article/details/gt2qsvigexb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ydzc1.top/Article/details/gt2gxawfwoc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.snrcjt.cn/Article/details/gt2bycgvbsx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.tianlin.xyz/Article/details/gt2rjivyote.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sufxvd.cn/Article/details/gt2bvsufgga.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yj20258888.top/Article/details/gt2afpdtshi.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.tian-w.cn/Article/details/gt2tjnsrckd.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.nanxinkj.top/Article/details/gt2ydjiwxxx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gotoacloud.top/Article/details/gt2pkioykyo.html

[L06] 解析响应为 JSON
来源：http://dali.sweek.top/Article/details/gt2ouwfxbmi.html

Py:   resp.json()
来源：http://dali.wangshuangyany.cn/Article/details/gt2yxraoehk.html

PHP:  json_decode($body, true);
来源：http://dali.0kj1m.cn/Article/details/gt2sjuooboj.html

JS:   await resp.json()
来源：http://dali.yueranfly.top/Article/details/gt2wunwebtv.html

TS:   await resp.json()
来源：http://dali.ivvv.top/Article/details/gt2ktfbcujl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hnxiangtu.top/Article/details/gt2zkkaxphu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shzxlz.cn/Article/details/gt2izbjqest.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhiwuduotai.top/Article/details/gt2pfrxzndb.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.daxiang520.top/Article/details/gt2ghyrhbcs.html

[L07] 处理 HTTP 状态码
来源：http://dali.xuanzx.com/Article/details/gt2jduonpqk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yuanzhike.top/Article/details/gt2edmfijug.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yonumen.top/Article/details/gt2fwdrojam.html

JS:   resp.ok;  resp.status
来源：http://dali.nanxuanxn.top/Article/details/gt2yzkucjku.html

TS:   resp.ok;  resp.status
来源：http://dali.mhx1999.top/Article/details/gt2ggxxjtil.html

Java: resp.statusCode()
来源：http://dali.316326.xyz/Article/details/gt2kisswnbz.html

Go:   resp.StatusCode
来源：http://dali.ehwqpu.com/Article/details/gt2sigsegdr.html

Ruby: resp.code.to_i
来源：http://dali.dashuyun.cn/Article/details/gt2bqkbkoqq.html

C#:   (int)resp.StatusCode
来源：http://dali.tian-w.cn/Article/details/gt2pjwbovfg.html

[L08] 并发请求多个地址
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2blpszdej.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.aibaodan.cn/Article/details/gt2subdcbgp.html

PHP:  curl_multi_init() 系列
来源：http://dali.shuidangran.top/Article/details/gt2llgwlknk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aizwys.cn/Article/details/gt2kdaboewm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yueranfly.top/Article/details/gt2uunntamt.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.316326.xyz/Article/details/gt2wtvmyhji.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.tianlin.xyz/Article/details/gt2skbhbdjw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yueranfly.top/Article/details/gt2umlrkzvo.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shangyingyoupin.top/Article/details/gt2yvmamwhr.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2kxtzdqrp.html

M. 命令行 / 进程 / 环境
来源：http://dali.ehwqpu.com/Article/details/gt2rpeqszus.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2dgzkssfp.html

[M01] 读取命令行参数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rzwgvaoa.html

Py:   sys.argv[1:]
来源：http://dali.aizwys.cn/Article/details/gt2mohkqani.html

PHP:  $argv;  $argc;
来源：http://dali.jinqigufen.top/Article/details/gt2gmlbdxyf.html

JS:   process.argv.slice(2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ngaoihsn.html

TS:   process.argv.slice(2)
来源：http://dali.ppjwa.cn/Article/details/gt2mmxkopok.html

Java: args 数组（main 方法参数）
来源：http://dali.yj20258888.top/Article/details/gt2qdoxexlu.html

Go:   os.Args[1:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2urwunwhp.html

Ruby: ARGV
来源：http://dali.sysykeji.top/Article/details/gt2tpnqtwxk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.haohaochexian.top/Article/details/gt2joaeefts.html

[M02] 读取环境变量
来源：http://dali.guowangkeji.top/Article/details/gt2lfnqqqmm.html

Py:   os.environ.get("HOME")
来源：http://dali.andypj.xyz/Article/details/gt2psgzpdcx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhengqikj.top/Article/details/gt2gfhbxmii.html

JS:   process.env.HOME
来源：http://dali.xziqi.cn/Article/details/gt2vknwlqyd.html

TS:   process.env.HOME
来源：http://dali.yvedp.cn/Article/details/gt2acgrkhtu.html

Java: System.getenv("HOME")
来源：http://dali.ppjwa.cn/Article/details/gt2kmpmkmqx.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.snrcjt.cn/Article/details/gt2mpqgbrjm.html

Ruby: ENV["HOME"]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vgswdfni.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jiagoushi.top/Article/details/gt2awnoqctp.html

[M03] 执行外部命令
来源：http://dali.hongshengwenyu.top/Article/details/gt2clfjwvmx.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.guannengcc.top/Article/details/gt2svuscvzf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zdqjudy.top/Article/details/gt2syuewvjb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shangyingyoupin.top/Article/details/gt2lpbglpla.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ydzc1.top/Article/details/gt2iexnkdpu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xziqi.cn/Article/details/gt2ngptgzep.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ivvv.top/Article/details/gt2oxnzfuzg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shuidangran.top/Article/details/gt2vypzebav.html

C#:   Process.Start("ls", "-l");
来源：http://dali.9152youxi.cn/Article/details/gt2oayzmwlp.html

[M04] 获取当前工作目录
来源：http://dali.chenlongwang.top/Article/details/gt2dkrqnboa.html

Py:   os.getcwd()
来源：http://dali.zycfv.cn/Article/details/gt2pbtxvvqz.html

PHP:  getcwd();
来源：http://dali.mhx1999.top/Article/details/gt2kdqxtmhk.html

JS:   process.cwd()
来源：http://dali.jinqigfzy.top/Article/details/gt2jusfgpsg.html

TS:   process.cwd()
来源：http://dali.chenzaomai.com/Article/details/gt2pszgsdqp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shangyingyoupin.top/Article/details/gt2jclidjbw.html

Go:   os.Getwd()
来源：http://dali.yonumen.top/Article/details/gt2kujysurb.html

Ruby: Dir.pwd
来源：http://dali.redwolf501.top/Article/details/gt2ibvcjjjq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ekxzcnal.html

[M05] 设置退出码
来源：http://dali.cashguo.top/Article/details/gt2xyeslxbo.html

Py:   sys.exit(1)
来源：http://dali.sxryk.cn/Article/details/gt2jmhizjjd.html

PHP:  exit(1);
来源：http://dali.xinyue.icu/Article/details/gt2vkgtxizt.html

JS:   process.exit(1)
来源：http://dali.sweek.top/Article/details/gt2sfnygwow.html

TS:   process.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2szxmedul.html

Java: System.exit(1)
来源：http://dali.wangdashe.top/Article/details/gt2bwnasute.html

Go:   os.Exit(1)
来源：http://dali.aibaodan.cn/Article/details/gt2hczfvldu.html

Ruby: exit 1
来源：http://dali.yueranfly.top/Article/details/gt2rrsjqdtl.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.guowangkeji.top/Article/details/gt2xarhjgcg.html

[M06] 向标准错误输出
来源：http://dali.sweek.top/Article/details/gt2hkxjhids.html

Py:   print("err", file=sys.stderr)
来源：http://dali.nanxuanxn.top/Article/details/gt2eouhupwh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.gotoacloud.top/Article/details/gt2hotgdsul.html

JS:   console.error("err")
来源：http://dali.hongshengwenyu.top/Article/details/gt2vpvbpjsq.html

TS:   console.error("err")
来源：http://dali.zhengqikj.top/Article/details/gt2rkjlnopz.html

Java: System.err.println("err")
来源：http://dali.xziqi.cn/Article/details/gt2xzhjrcak.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yangfankeji.com/Article/details/gt2ygktzkrk.html

Ruby: warn "err"
来源：http://dali.ivvv.top/Article/details/gt2wdblzvck.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ehwqpu.com/Article/details/gt2epdmmgkr.html

[M07] 判断是否为主入口
来源：http://dali.xziqi.cn/Article/details/gt2mjrlzuvr.html

Py:   if __name__ == "__main__":
来源：http://dali.chenlongwang.top/Article/details/gt2fkbvksdj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.c1oappe.top/Article/details/gt2fwkueuvr.html

JS:   require.main === module
来源：http://dali.havefunace.top/Article/details/gt2jodrohwg.html

TS:   require.main === module
来源：http://dali.tanke756.top/Article/details/gt2wyilplji.html

Java: public static void main(String[] args)
来源：http://dali.hywenlv.cn/Article/details/gt2itdlopkp.html

Go:   func main()
来源：http://dali.sxryk.cn/Article/details/gt2vorotvls.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.iojbl.cn/Article/details/gt2nyupmalq.html

C#:   static void Main(string[] args)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lhvpzvwv.html

[M08] 获取系统与运行时信息
来源：http://dali.quarkkingdee.top/Article/details/gt2csirbxyy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xuetiantiany.cn/Article/details/gt2sojzsosd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cqqwz.cn/Article/details/gt2vrrqrhll.html

JS:   process.platform;  process.version
来源：http://dali.smart0.xyz/Article/details/gt2kvawvbll.html

TS:   process.platform;  process.version
来源：http://dali.svipenyu.cn/Article/details/gt2ctvvqdxs.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yvedp.cn/Article/details/gt2nzzngvbu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.smart0.xyz/Article/details/gt2mvntbyim.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sxryk.cn/Article/details/gt2leqkynou.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hfpthk.cn/Article/details/gt2eguozzex.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2dzwnteam.html

N. 数据结构与算法
来源：http://dali.chenlongwang.top/Article/details/gt2zlyjxets.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2viwtoath.html

[N01] 二分查找（有序数组）
来源：http://dali.jinqigufen.top/Article/details/gt2suzzglcv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.tanke756.top/Article/details/gt2qrnqhawh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2zagtfdlf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dianchejie.cn/Article/details/gt2irkedecv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ybcxt.top/Article/details/gt2kwfpyefh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.wangdashe.top/Article/details/gt2kkapdete.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2oggzrcyw.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sweek.top/Article/details/gt2mbckwmta.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jeicoqai.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.redwolf501.top/Article/details/gt2izzhgwdg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daxiang520.top/Article/details/gt2nuguffwo.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ivvv.top/Article/details/gt2jrtwlozc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.0kj1m.cn/Article/details/gt2bnkpgsom.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.snrcjt.cn/Article/details/gt2bkofbnoo.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.c1oappe.top/Article/details/gt2cbeqtbjq.html

Go:   slices.Sort(arr)
来源：http://dali.haohaochexian.top/Article/details/gt2cuwbrvdg.html

Ruby: arr.sort
来源：http://dali.cucudq.cn/Article/details/gt2ouynkhwa.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jiagoushi.top/Article/details/gt2gmhmfknc.html

[N03] 快速排序（分治示例）
来源：http://dali.pycfn.com/Article/details/gt2zppkmjso.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhoulong.xyz/Article/details/gt2hjwodneq.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ppjwa.cn/Article/details/gt2jihcyfyy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gogol.net.cn/Article/details/gt2ttfhrtbq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.andypj.xyz/Article/details/gt2vdcknxgf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yvedp.cn/Article/details/gt2humtxlhw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cucudq.cn/Article/details/gt2erefaebx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.chenjidiqi.icu/Article/details/gt2rxpjvsdc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xylfe.cn/Article/details/gt2ebrciruk.html

[N04] 斐波那契数列
来源：http://dali.vqdsnc.cn/Article/details/gt2xpakefcg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigufen.top/Article/details/gt2edhcyurn.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzzmlip.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yonumen.top/Article/details/gt2wktdaiwu.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cheryme.top/Article/details/gt2jzjtwxya.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2bgcnulab.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.smart0.xyz/Article/details/gt2bqaakwcx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258.top/Article/details/gt2bgbhllif.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gt2xuskshtq.html

[N05] 最大公约数
来源：http://dali.dianchejie.cn/Article/details/gt2hrnvlzuh.html

Py:   math.gcd(a, b)
来源：http://dali.jqgufenzy.top/Article/details/gt2qyfjumpk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.fzhhl.top/Article/details/gt2hckbohhi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tianlin.xyz/Article/details/gt2sprpzbme.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sysykeji.top/Article/details/gt2nbbtkrmb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhengqikj.top/Article/details/gt2uondmbme.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shzxlz.cn/Article/details/gt2vhympzgj.html

Ruby: a.gcd(b)
来源：http://dali.birdmap.top/Article/details/gt2cebamuyp.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.iojbl.cn/Article/details/gt2nqzobjtj.html

[N06] 判断回文字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2rduweosp.html

Py:   s == s[::-1]
来源：http://dali.havefunace.top/Article/details/gt2qgtxpzqy.html

PHP:  $s === strrev($s);
来源：http://dali.mhx1999.top/Article/details/gt2onpjhcpe.html

JS:   s === [...s].reverse().join("")
来源：http://dali.bjfxy.top/Article/details/gt2zkurtezd.html

TS:   s === [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gt2avtsdilo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gaohongyu789.top/Article/details/gt2mshfesna.html

Go:   // 双指针从两端比较
来源：http://dali.guannengcc.top/Article/details/gt2glmvfcvd.html

Ruby: s == s.reverse
来源：http://dali.cucudq.cn/Article/details/gt2gfoepyex.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hnqzz.top/Article/details/gt2oyxwmetw.html

[N07] 两数之和（返回下标）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jnpxhmmk.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.tian-w.cn/Article/details/gt2ykacqppm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yj20258888.top/Article/details/gt2pgwbpszl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.nanxinkj.top/Article/details/gt2wxmausxc.html

TS:   // 手写 Map<string, number>
来源：http://dali.jianghu66.top/Article/details/gt2adpsushf.html

Java: // 手写 HashMap
来源：http://dali.iojbl.cn/Article/details/gt2adhcjyui.html

Go:   // 手写 map[int]int
来源：http://dali.hnxiangtu.top/Article/details/gt2dugjbyti.html

Ruby: // 手写 Hash
来源：http://dali.xziqi.cn/Article/details/gt2gozamphm.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yuxming.cn/Article/details/gt2gyzehthr.html

[N08] 生成全排列
来源：http://dali.feifeiyinyue.top/Article/details/gt2yarzfvnc.html

Py:   itertools.permutations(arr)
来源：http://dali.jianghu66.top/Article/details/gt2ifmicfut.html

PHP:  // 手写递归交换
来源：http://dali.fzhhl.top/Article/details/gt2lomthkhs.html

JS:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gt2mvehjifx.html

TS:   // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gt2bxvkladg.html


<!-- 参考信息 -->