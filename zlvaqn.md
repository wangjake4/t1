代发 wailian999

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xylfe.cn/Article/details/gt2tadvazkm.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.birdmap.top/Article/details/gt2npkoopsd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yueranfly.top/Article/details/gt2esimodqz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yangfankeji.com/Article/details/gt2fuhbosej.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.c1oappe.top/Article/details/gt2begthudy.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cqqwz.cn/Article/details/gt2aszibgqc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hnqzz.top/Article/details/gt2ifrlbfyr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sweek.top/Article/details/gt2gfzdwjuy.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2daitqslf.html

K. JSON 与序列化
来源：http://dali.xuanzx.com/Article/details/gt2rzskbxrv.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2miiszrav.html

[K01] 对象转 JSON 字符串
来源：http://dali.guannengcc.top/Article/details/gt2dbdummns.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gzhubu.top/Article/details/gt2hailwiam.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.birdmap.top/Article/details/gt2ujapidil.html

JS:   JSON.stringify(obj)
来源：http://dali.mhx1999.top/Article/details/gt2thmtkbhe.html

TS:   JSON.stringify(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2mufxbzcv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xziqi.cn/Article/details/gt2ndcsyagu.html

Go:   json.Marshal(obj)
来源：http://dali.cashguo.top/Article/details/gt2fbxaqblx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.aibaodan.cn/Article/details/gt2zdwxgsxr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hammf.cn/Article/details/gt2berxxdbh.html

[K02] JSON 字符串转对象
来源：http://dali.yuxming.cn/Article/details/gt2uhdbgkqa.html

Py:   json.loads(s)
来源：http://dali.chenzaomai.com/Article/details/gt2jnfmjhvx.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yongpay.top/Article/details/gt2uvmpvhhn.html

JS:   JSON.parse(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sinpcbrz.html

TS:   JSON.parse(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2agtlgrep.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhengqikj.top/Article/details/gt2pbyekmvh.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yueranfly.top/Article/details/gt2sersgvcs.html

Ruby: JSON.parse(s)
来源：http://dali.gzhubu.top/Article/details/gt2oogvzaxl.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gotoacloud.top/Article/details/gt2aigvoohw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shuidangran.top/Article/details/gt2lfxswnvx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.fengsongda.top/Article/details/gt2mnnapumf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xziqi.cn/Article/details/gt2gitunrkb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cqqwz.cn/Article/details/gt2fhsattjr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.0kj1m.cn/Article/details/gt2snwjurmm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.guannengcc.top/Article/details/gt2ziiuifsq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hcykshtb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sweek.top/Article/details/gt2kpdvzhxf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.iojbl.cn/Article/details/gt2uehobasy.html

[K04] 读取 JSON 文件
来源：http://dali.redwolf501.top/Article/details/gt2ljxmfwoe.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.birdmap.top/Article/details/gt2fusqyynh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jqgfzy.top/Article/details/gt2ckvxdlrk.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yanxiufei.cn/Article/details/gt2krwwalyj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.316326.xyz/Article/details/gt2fyhrzhee.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yongpay.top/Article/details/gt2qvttlobz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.vqdsnc.cn/Article/details/gt2aejvjgwe.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jngsxqwf.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xuetiantiany.cn/Article/details/gt2zmurjpfm.html

[K05] 深拷贝对象
来源：http://dali.gaohongyu789.top/Article/details/gt2eibsabqv.html

Py:   copy.deepcopy(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2corfipxp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.kuanghao11.cn/Article/details/gt2fswygoof.html

JS:   structuredClone(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2ihbqbqya.html

TS:   structuredClone(obj)
来源：http://dali.pycfn.com/Article/details/gt2prajejbu.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shangyingyoupin.top/Article/details/gt2hhixnxch.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zycfv.cn/Article/details/gt2zctlsrgv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.pengpengdd.cyou/Article/details/gt2ztmmrlli.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jyoumei.cn/Article/details/gt2szofmyex.html

[K06] 解析 URL 查询串
来源：http://dali.yangfankeji.com/Article/details/gt2anfgfaev.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.aibaodan.cn/Article/details/gt2zklosmie.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xinyue.icu/Article/details/gt2mkqxgswt.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgufenzy.top/Article/details/gt2zladluir.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ehwqpu.com/Article/details/gt2tloibrue.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinqigufen.top/Article/details/gt2sfcagllq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.fengsongda.top/Article/details/gt2xmgvjsng.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gt2pezdapxb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhoulong.xyz/Article/details/gt2bhonbvve.html

[K07] 进制转换
来源：http://dali.sysykeji.top/Article/details/gt2okjblzpy.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gt2umerneee.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2cafkgfzs.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gt2pbynokhp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gt2xdsjxfwh.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.pycfn.com/Article/details/gt2wabsguvf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hysaishi.cn/Article/details/gt2yisipaac.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.gotoacloud.top/Article/details/gt2zrehglho.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cashguo.top/Article/details/gt2vwgicjcv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sufxvd.cn/Article/details/gt2qghbvfwi.html

Py:   pickle.dumps(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2gayzeizd.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cdnleiting.top/Article/details/gt2fchpxquf.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xinyue.icu/Article/details/gt2owjcwflw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhongyouzk.top/Article/details/gt2yqqkbtjf.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hnqzz.top/Article/details/gt2izoztgws.html

Go:   encoding/gob
来源：http://dali.guowangkeji.top/Article/details/gt2cebpsgiq.html

Ruby: Marshal.dump(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2nutpjqsk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cashguo.top/Article/details/gt2mirgjizt.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2nihaipno.html

L. 网络请求
来源：http://dali.ybcxt.top/Article/details/gt2ioltlsml.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2cxmkzqtc.html

[L01] 发送 GET 请求
来源：http://dali.fengsongda.top/Article/details/gt2hijynoja.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yuanzhike.top/Article/details/gt2huglfutu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.0kj1m.cn/Article/details/gt2gmcncdnx.html

JS:   await fetch(url)
来源：http://dali.chenlongwang.top/Article/details/gt2gftvfghg.html

TS:   await fetch(url)
来源：http://dali.gotoacloud.top/Article/details/gt2yheaidbv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jyoumei.cn/Article/details/gt2qnoazsss.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhengqikj.top/Article/details/gt2osrtqlan.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cashguo.top/Article/details/gt2fmzhivuc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.kuanghao11.cn/Article/details/gt2ukotmdcn.html

[L02] 发送 POST JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tsucbgch.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shuidangran.top/Article/details/gt2qtlsvjru.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.c1oappe.top/Article/details/gt2wgovfmsy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yueranfly.top/Article/details/gt2bnmyuttk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.mhx1999.top/Article/details/gt2pgxpcpvp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xziqi.cn/Article/details/gt2mpfzuygr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.aizwys.cn/Article/details/gt2hyvrigdi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.0kj1m.cn/Article/details/gt2kzkqggrj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.dashuyun.cn/Article/details/gt2ifymjjej.html

[L03] 设置自定义请求头
来源：http://dali.tian-w.cn/Article/details/gt2pxkxiphm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ehwqpu.com/Article/details/gt2zmupdkhe.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gogol.net.cn/Article/details/gt2wtwhptmm.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yonumen.top/Article/details/gt2ingkgadc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jlsjyb.cn/Article/details/gt2dhjowxqc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xuanzx.com/Article/details/gt2dwsskaxz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.c1oappe.top/Article/details/gt2jyughusn.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xziqi.cn/Article/details/gt2bhpfjaix.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.meibo888.top/Article/details/gt2jploxvrb.html

[L04] 设置超时
来源：http://dali.yj20258888.top/Article/details/gt2joegegvy.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hammf.cn/Article/details/gt2hfyfltwh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ybcxt.top/Article/details/gt2lhbxsohs.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenlongwang.top/Article/details/gt2wllywkam.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.iojbl.cn/Article/details/gt2rbxhmoac.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yj202588.top/Article/details/gt2coifodnw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.nwbrower.top/Article/details/gt2seanvajj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ybcxt.top/Article/details/gt2thkeprce.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhengqikj.top/Article/details/gt2kkmracga.html

[L05] 上传文件（multipart）
来源：http://dali.yj20258888.top/Article/details/gt2jaufqauv.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sufxvd.cn/Article/details/gt2peyvhsxf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shuidangran.top/Article/details/gt2yiullxfk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenjidiqi.icu/Article/details/gt2lulyrqzy.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.c1oappe.top/Article/details/gt2sobufgiw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ehwqpu.com/Article/details/gt2wxammvtm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.birdmap.top/Article/details/gt2hecdeqxf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kmunbpfy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.wangdashe.top/Article/details/gt2jkhzaayv.html

[L06] 解析响应为 JSON
来源：http://dali.sysykeji.top/Article/details/gt2xkxfivza.html

Py:   resp.json()
来源：http://dali.fzhhl.top/Article/details/gt2julmtabo.html

PHP:  json_decode($body, true);
来源：http://dali.hywenlv.cn/Article/details/gt2mmhiozlm.html

JS:   await resp.json()
来源：http://dali.yvedp.cn/Article/details/gt2yhxbpppk.html

TS:   await resp.json()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tcdscrqi.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.wangdashe.top/Article/details/gt2ywddetin.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ydzc1.top/Article/details/gt2ygqgfyjc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mrfdeozp.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cucudq.cn/Article/details/gt2ibacpavk.html

[L07] 处理 HTTP 状态码
来源：http://dali.shzxlz.cn/Article/details/gt2tdxfwzyo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cucudq.cn/Article/details/gt2waeodzlm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hammf.cn/Article/details/gt2kqaelxju.html

JS:   resp.ok;  resp.status
来源：http://dali.sysykeji.top/Article/details/gt2poiebbpu.html

TS:   resp.ok;  resp.status
来源：http://dali.kuanghao11.cn/Article/details/gt2wzqasdpl.html

Java: resp.statusCode()
来源：http://dali.pengpengdd.cyou/Article/details/gt2njzuslzh.html

Go:   resp.StatusCode
来源：http://dali.yj20258.top/Article/details/gt2ysrgafcg.html

Ruby: resp.code.to_i
来源：http://dali.hfpthk.cn/Article/details/gt2vnxubtva.html

C#:   (int)resp.StatusCode
来源：http://dali.jlsjyb.cn/Article/details/gt2bkjgwxqk.html

[L08] 并发请求多个地址
来源：http://dali.yj20258.top/Article/details/gt2thihkzci.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.9152youxi.cn/Article/details/gt2arhacctu.html

PHP:  curl_multi_init() 系列
来源：http://dali.gotoacloud.top/Article/details/gt2fseenpuf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxinkj.top/Article/details/gt2acbuvmwr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gogol.net.cn/Article/details/gt2ahswghqw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ghddevbh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gaohongyu789.top/Article/details/gt2gneyooga.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uqrmsqll.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhixingplan.top/Article/details/gt2paxlbnwg.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2zxxkbltj.html

M. 命令行 / 进程 / 环境
来源：http://dali.xylfe.cn/Article/details/gt2lmcjeadz.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2bwtirykz.html

[M01] 读取命令行参数
来源：http://dali.ydzc1.top/Article/details/gt2aylpmjau.html

Py:   sys.argv[1:]
来源：http://dali.yvedp.cn/Article/details/gt2iakxjlbd.html

PHP:  $argv;  $argc;
来源：http://dali.jlsjyb.cn/Article/details/gt2spwxopbl.html

JS:   process.argv.slice(2)
来源：http://dali.cheryme.top/Article/details/gt2emtrcrki.html

TS:   process.argv.slice(2)
来源：http://dali.jqgufenzy.top/Article/details/gt2lrtkfnwp.html

Java: args 数组（main 方法参数）
来源：http://dali.haohaochexian.top/Article/details/gt2pzarcdqv.html

Go:   os.Args[1:]
来源：http://dali.guowangkeji.top/Article/details/gt2mmmynkqk.html

Ruby: ARGV
来源：http://dali.hammf.cn/Article/details/gt2lbdjxsbb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qgramwii.html

[M02] 读取环境变量
来源：http://dali.redwolf501.top/Article/details/gt2aucelnck.html

Py:   os.environ.get("HOME")
来源：http://dali.fzhhl.top/Article/details/gt2chggbigb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.aizwys.cn/Article/details/gt2jxqlvhup.html

JS:   process.env.HOME
来源：http://dali.chenzaomai.com/Article/details/gt2krvgxkte.html

TS:   process.env.HOME
来源：http://dali.sysykeji.top/Article/details/gt2xwurplge.html

Java: System.getenv("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gt2xeskmkpi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.c1oappe.top/Article/details/gt2mszvbpli.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2resrxeus.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ysxcyrxg.html

[M03] 执行外部命令
来源：http://dali.bjfxy.top/Article/details/gt2muxaqbpl.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.haohaochexian.top/Article/details/gt2wwdzxbzg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jyoumei.cn/Article/details/gt2rffqkoee.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.daria6918.cn/Article/details/gt2nzduqkaq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.nwbrower.top/Article/details/gt2buhsfqjz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shuidangran.top/Article/details/gt2xgmmxdmr.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yj20258.top/Article/details/gt2pvcsyopq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jyoumei.cn/Article/details/gt2pwhsoqwu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hywenlv.cn/Article/details/gt2khhwxdxk.html

[M04] 获取当前工作目录
来源：http://dali.meibo888.top/Article/details/gt2yvdhjdxt.html

Py:   os.getcwd()
来源：http://dali.jqgfzy.top/Article/details/gt2plujtjjl.html

PHP:  getcwd();
来源：http://dali.tian-w.cn/Article/details/gt2wshwkqgb.html

JS:   process.cwd()
来源：http://dali.nwbrower.top/Article/details/gt2asqifkep.html

TS:   process.cwd()
来源：http://dali.redwolf501.top/Article/details/gt2immbfzrg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.guannengcc.top/Article/details/gt2vmsoaayg.html

Go:   os.Getwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2juvxlygf.html

Ruby: Dir.pwd
来源：http://dali.dianchejie.cn/Article/details/gt2hlzlnsgu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2njofunjv.html

[M05] 设置退出码
来源：http://dali.nanxuanxn.top/Article/details/gt2ogwxhmpj.html

Py:   sys.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gt2rxnuqywk.html

PHP:  exit(1);
来源：http://dali.yuxming.cn/Article/details/gt2czyhonin.html

JS:   process.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2iithusmt.html

TS:   process.exit(1)
来源：http://dali.ybcxt.top/Article/details/gt2nrufvtix.html

Java: System.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gt2jmeifvjv.html

Go:   os.Exit(1)
来源：http://dali.snrcjt.cn/Article/details/gt2yactsgkj.html

Ruby: exit 1
来源：http://dali.pycfn.com/Article/details/gt2ongsmend.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ctxoqdct.html

[M06] 向标准错误输出
来源：http://dali.sufxvd.cn/Article/details/gt2xoqxwuoc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj202588.top/Article/details/gt2cuhgophn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jiagoushi.top/Article/details/gt2dljvodaf.html

JS:   console.error("err")
来源：http://dali.aizwys.cn/Article/details/gt2nfkdguur.html

TS:   console.error("err")
来源：http://dali.pengpengdd.cyou/Article/details/gt2wleoshtg.html

Java: System.err.println("err")
来源：http://dali.andypj.xyz/Article/details/gt2kprtolkb.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sysykeji.top/Article/details/gt2kenqtxge.html

Ruby: warn "err"
来源：http://dali.pengpengdd.cyou/Article/details/gt2masdznqv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.fzhhl.top/Article/details/gt2mxspuplm.html

[M07] 判断是否为主入口
来源：http://dali.feifeiyinyue.top/Article/details/gt2pdgxqhut.html

Py:   if __name__ == "__main__":
来源：http://dali.yuanzhike.top/Article/details/gt2klhpbvbr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.guowangkeji.top/Article/details/gt2oqalixeh.html

JS:   require.main === module
来源：http://dali.yueranfly.top/Article/details/gt2thvoosbm.html

TS:   require.main === module
来源：http://dali.xylfe.cn/Article/details/gt2kgbpkmgm.html

Java: public static void main(String[] args)
来源：http://dali.havefunace.top/Article/details/gt2osfiktdn.html

Go:   func main()
来源：http://dali.vqdsnc.cn/Article/details/gt2uerusyrs.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.iojbl.cn/Article/details/gt2vrjzypwp.html

C#:   static void Main(string[] args)
来源：http://dali.xylfe.cn/Article/details/gt2azyznvrs.html

[M08] 获取系统与运行时信息
来源：http://dali.cheryme.top/Article/details/gt2kezaeqnh.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yonumen.top/Article/details/gt2gzrulksk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhongyouzk.top/Article/details/gt2lompnzvp.html

JS:   process.platform;  process.version
来源：http://dali.yangfankeji.com/Article/details/gt2hjjzspjk.html

TS:   process.platform;  process.version
来源：http://dali.hnqzz.top/Article/details/gt2dpitwfpb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hnxiangtu.top/Article/details/gt2ojjtmvbi.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cucudq.cn/Article/details/gt2iiblezej.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.iojbl.cn/Article/details/gt2abuuekgv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ydzc1.top/Article/details/gt2chlrfpdp.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2onbcuraq.html

N. 数据结构与算法
来源：http://dali.xuetiantiany.cn/Article/details/gt2xuvxgihz.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2dfsuuoyx.html

[N01] 二分查找（有序数组）
来源：http://dali.yvedp.cn/Article/details/gt2agsrqmka.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yonumen.top/Article/details/gt2qmldafsb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.chenzaomai.com/Article/details/gt2wnmxyirt.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnxiangtu.top/Article/details/gt2jjbqaknx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aibaodan.cn/Article/details/gt2txpyfshl.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mrittcmd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2czgesevy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.aibaodan.cn/Article/details/gt2hodsjtay.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gt2dlljfxtb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.redwolf501.top/Article/details/gt2pxrvgydh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yangfankeji.com/Article/details/gt2ylwhjztm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shuidangran.top/Article/details/gt2lhfcvevf.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.birdmap.top/Article/details/gt2tyaicftf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigfzy.top/Article/details/gt2nkodqzzm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.smart0.xyz/Article/details/gt2fydrjgaq.html

Go:   slices.Sort(arr)
来源：http://dali.jianghu66.top/Article/details/gt2tehvnljl.html

Ruby: arr.sort
来源：http://dali.yongpay.top/Article/details/gt2hlvxoghs.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.nwbrower.top/Article/details/gt2zqotxizk.html

[N03] 快速排序（分治示例）
来源：http://dali.gzhubu.top/Article/details/gt2nvfcmbed.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ppjwa.cn/Article/details/gt2cuyzqhep.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinqigfzy.top/Article/details/gt2bpgtglvh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.mhx1999.top/Article/details/gt2sallnowk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yonumen.top/Article/details/gt2bwlcmwyc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.guannengcc.top/Article/details/gt2smgbavmh.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.haohaochexian.top/Article/details/gt2zyywnafg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xuanzx.com/Article/details/gt2eclffoyc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xziqi.cn/Article/details/gt2fhgsnxdz.html

[N04] 斐波那契数列
来源：http://dali.pengpengdd.cyou/Article/details/gt2xkmnenhe.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2lojsohzy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.aizwys.cn/Article/details/gt2azjuqoeu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jlsjyb.cn/Article/details/gt2uscferxu.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gotoacloud.top/Article/details/gt2wpkabmhe.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aeosxxrp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jianghu66.top/Article/details/gt2rcgqnbgp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.pycfn.com/Article/details/gt2sacuvieu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cheryme.top/Article/details/gt2bryoypxd.html

[N05] 最大公约数
来源：http://dali.sweek.top/Article/details/gt2lyorjlem.html

Py:   math.gcd(a, b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ijjmgmkt.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.0kj1m.cn/Article/details/gt2qqftvjml.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cdnleiting.top/Article/details/gt2jarewbye.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigufen.top/Article/details/gt2nzsegiip.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.svipenyu.cn/Article/details/gt2qpujfoen.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.guannengcc.top/Article/details/gt2byshzfqk.html

Ruby: a.gcd(b)
来源：http://dali.yj20258888.top/Article/details/gt2ibcuunah.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.snrcjt.cn/Article/details/gt2qvbrupnw.html

[N06] 判断回文字符串
来源：http://dali.fengsongda.top/Article/details/gt2jhkbrsuq.html

Py:   s == s[::-1]
来源：http://dali.chenjidiqi.icu/Article/details/gt2ttvtimvo.html

PHP:  $s === strrev($s);
来源：http://dali.hywenlv.cn/Article/details/gt2ehughmrt.html

JS:   s === [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gt2mjvsoqmr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gt2eoovckho.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.smart0.xyz/Article/details/gt2rnoiszfw.html

Go:   // 双指针从两端比较
来源：http://dali.xziqi.cn/Article/details/gt2euonzrov.html

Ruby: s == s.reverse
来源：http://dali.9152youxi.cn/Article/details/gt2lwjsonpz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zdqjudy.top/Article/details/gt2zpljxcwi.html

[N07] 两数之和（返回下标）
来源：http://dali.chenjidiqi.icu/Article/details/gt2qjlticdj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yj20258.top/Article/details/gt2yrpmurvm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.wangshuangyany.cn/Article/details/gt2wosnlxul.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jqgfzy.top/Article/details/gt2tstdvxxy.html

TS:   // 手写 Map<string, number>
来源：http://dali.yj20258888.top/Article/details/gt2guwkoijx.html

Java: // 手写 HashMap
来源：http://dali.guannengcc.top/Article/details/gt2dtghoteb.html

Go:   // 手写 map[int]int
来源：http://dali.jinqigfzy.top/Article/details/gt2abxlrpre.html

Ruby: // 手写 Hash
来源：http://dali.hnqzz.top/Article/details/gt2mlectpfv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cheryme.top/Article/details/gt2ztictjbl.html

[N08] 生成全排列
来源：http://dali.yuxming.cn/Article/details/gt2nhkhzwrx.html


<!-- 参考信息 -->