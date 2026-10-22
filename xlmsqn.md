代发 wailian999

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.redwolf501.top/Article/details/gt2pqfuhibe.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.snrcjt.cn/Article/details/gt2kcrzlygb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cucudq.cn/Article/details/gt2dhrimhnp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hywenlv.cn/Article/details/gt2iuvgbdmc.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xziqi.cn/Article/details/gt2zadvyfzd.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yangfankeji.com/Article/details/gt2xxeqmnmo.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.fzhhl.top/Article/details/gt2yjhgamnk.html

[J10] 取今天 / 本月第一天
来源：http://dali.dashuyun.cn/Article/details/gt2zdaarpnh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.daxiang520.top/Article/details/gt2rdoqtziu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tnvcwyma.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jlsjyb.cn/Article/details/gt2kffwqcje.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hnxiangtu.top/Article/details/gt2fvsdyfzn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2edeknhci.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cqqwz.cn/Article/details/gt2xbnbbtnz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.c1oappe.top/Article/details/gt2fxqdsssu.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.svipenyu.cn/Article/details/gt2rdqokihs.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gjsjzkha.html

K. JSON 与序列化
来源：http://dali.jqgfzy.top/Article/details/gt2pxangktg.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2arunkfbf.html

[K01] 对象转 JSON 字符串
来源：http://dali.hongshengwenyu.top/Article/details/gt2vxauwmqc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.birdmap.top/Article/details/gt2qpvgeacn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ybcxt.top/Article/details/gt2fvrdvtrr.html

JS:   JSON.stringify(obj)
来源：http://dali.sweek.top/Article/details/gt2rmpdvvxo.html

TS:   JSON.stringify(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2mimkbkui.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jyoumei.cn/Article/details/gt2wixwdxxp.html

Go:   json.Marshal(obj)
来源：http://dali.tanke756.top/Article/details/gt2jewqewsg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.vqdsnc.cn/Article/details/gt2slicljhy.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zqhmvldm.html

[K02] JSON 字符串转对象
来源：http://dali.zhengqikj.top/Article/details/gt2lfwmfwhs.html

Py:   json.loads(s)
来源：http://dali.zycfv.cn/Article/details/gt2jvffkvdb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.nanxinkj.top/Article/details/gt2kdcyrofl.html

JS:   JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gt2nnoisoza.html

TS:   JSON.parse(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2nrbamudm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gotoacloud.top/Article/details/gt2ejwilxju.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.0kj1m.cn/Article/details/gt2rybhsolf.html

Ruby: JSON.parse(s)
来源：http://dali.hfpthk.cn/Article/details/gt2orkjdera.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.pycfn.com/Article/details/gt2ejtiyosr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.daria6918.cn/Article/details/gt2ebxdoerw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cdnleiting.top/Article/details/gt2rzcztapo.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ydzc1.top/Article/details/gt2jhqrfbup.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gogol.net.cn/Article/details/gt2xffwmmao.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2taybhcog.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2ftplxaoj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.wangshuangyany.cn/Article/details/gt2wkiwmrdm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xuanzx.com/Article/details/gt2gpmhumnb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sysykeji.top/Article/details/gt2cvxoyejy.html

[K04] 读取 JSON 文件
来源：http://dali.hywenlv.cn/Article/details/gt2ajymqqxo.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gogol.net.cn/Article/details/gt2pwusoeid.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.tanke756.top/Article/details/gt2xlsiazzn.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxinkj.top/Article/details/gt2gvnmavkn.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnxiangtu.top/Article/details/gt2mkfrdhhl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yj20258888.top/Article/details/gt2vhxvoifh.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.9152youxi.cn/Article/details/gt2qbjggmtf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.aibaodan.cn/Article/details/gt2qvqpadpp.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2tjiehsvg.html

[K05] 深拷贝对象
来源：http://dali.yuxming.cn/Article/details/gt2mksbqubq.html

Py:   copy.deepcopy(obj)
来源：http://dali.yongpay.top/Article/details/gt2xowhihxw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.mhx1999.top/Article/details/gt2dcnxomtr.html

JS:   structuredClone(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2wkrbqujy.html

TS:   structuredClone(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xhfzxjjq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.nanxinkj.top/Article/details/gt2pcepuwpv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jlsjyb.cn/Article/details/gt2piajgwzp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.iojbl.cn/Article/details/gt2velfgapn.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hnqzz.top/Article/details/gt2yltncejo.html

[K06] 解析 URL 查询串
来源：http://dali.andypj.xyz/Article/details/gt2zovfqpwq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.birdmap.top/Article/details/gt2jmenlhrh.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.daria6918.cn/Article/details/gt2dvsouhab.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.quarkkingdee.top/Article/details/gt2drolqwyo.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gogol.net.cn/Article/details/gt2eoppisbf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sufxvd.cn/Article/details/gt2lwzqtook.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sufxvd.cn/Article/details/gt2uidszuwn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shzxlz.cn/Article/details/gt2auieuvgb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.havefunace.top/Article/details/gt2ylqlusyt.html

[K07] 进制转换
来源：http://dali.yuxming.cn/Article/details/gt2vqafikgk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gt2taiuhlpg.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sysykeji.top/Article/details/gt2asczfcox.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gt2ghjwzigv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gt2ijbnbfov.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gt2hxrpjykz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.chenzaomai.com/Article/details/gt2wukwcesu.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.gzhubu.top/Article/details/gt2fhnjlfdc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gt2yhkykvtu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.aizwys.cn/Article/details/gt2ugqukcja.html

Py:   pickle.dumps(obj)
来源：http://dali.c1oappe.top/Article/details/gt2qxgonapk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.daxiang520.top/Article/details/gt2htatrnws.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhixingplan.top/Article/details/gt2csnqmwvi.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.dianchejie.cn/Article/details/gt2asitwcgd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhiwuduotai.top/Article/details/gt2bebjxkeb.html

Go:   encoding/gob
来源：http://dali.pengpengdd.cyou/Article/details/gt2rvkkvino.html

Ruby: Marshal.dump(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2lmsexhvg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gotoacloud.top/Article/details/gt2vkvdbhgv.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2kswiurbq.html

L. 网络请求
来源：http://dali.cashguo.top/Article/details/gt2vlwdulvv.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2olgohjos.html

[L01] 发送 GET 请求
来源：http://dali.chenlongwang.top/Article/details/gt2bjsffyle.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.9152youxi.cn/Article/details/gt2gdhpsbqs.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sxryk.cn/Article/details/gt2egxororc.html

JS:   await fetch(url)
来源：http://dali.ivvv.top/Article/details/gt2mtgigovb.html

TS:   await fetch(url)
来源：http://dali.ybcxt.top/Article/details/gt2mqlglznz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.wangshuangyany.cn/Article/details/gt2klxtpzym.html

Go:   resp, err := http.Get(url)
来源：http://dali.yangfankeji.com/Article/details/gt2ngkdvknv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.chenzaomai.com/Article/details/gt2zqeshqzi.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cashguo.top/Article/details/gt2mujflpcw.html

[L02] 发送 POST JSON
来源：http://dali.aizwys.cn/Article/details/gt2fytgzexw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.mhx1999.top/Article/details/gt2eewchnxy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.daxiang520.top/Article/details/gt2duhasmgl.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yangfankeji.com/Article/details/gt2kquqktyj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.316326.xyz/Article/details/gt2tiviwwee.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.fengsongda.top/Article/details/gt2npkbsdad.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.nanxuanxn.top/Article/details/gt2wyopitgl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.haohaochexian.top/Article/details/gt2qbqrbjxa.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.guowangkeji.top/Article/details/gt2zeftvmbx.html

[L03] 设置自定义请求头
来源：http://dali.cashguo.top/Article/details/gt2tyrqhifm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.9152youxi.cn/Article/details/gt2nfmkfnjx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shangyingyoupin.top/Article/details/gt2jhkiunon.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shzxlz.cn/Article/details/gt2hnsnjcpq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sweek.top/Article/details/gt2ncncpkqz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.c1oappe.top/Article/details/gt2ylpwcuny.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wlvknnro.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cheryme.top/Article/details/gt2gmyvdpcy.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ehwqpu.com/Article/details/gt2yonpanpy.html

[L04] 设置超时
来源：http://dali.guowangkeji.top/Article/details/gt2qcehpcui.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oslovppj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.vqdsnc.cn/Article/details/gt2aiddjgqj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhengqikj.top/Article/details/gt2zwkhdbbk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zycfv.cn/Article/details/gt2iqdkgidu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzmhxxq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.iojbl.cn/Article/details/gt2tqzzmjec.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cqqwz.cn/Article/details/gt2rmqgxxra.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cdnleiting.top/Article/details/gt2eakksvrz.html

[L05] 上传文件（multipart）
来源：http://dali.gotoacloud.top/Article/details/gt2yzpebkis.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yvedp.cn/Article/details/gt2cnusxowu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinqigfzy.top/Article/details/gt2pcrbswot.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigfzy.top/Article/details/gt2nklegemm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cucudq.cn/Article/details/gt2bhhjxmdm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinqigufen.top/Article/details/gt2graihphm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yonumen.top/Article/details/gt2oyrwtyps.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.316326.xyz/Article/details/gt2bnbpcpnn.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2dyryrawi.html

[L06] 解析响应为 JSON
来源：http://dali.ydzc1.top/Article/details/gt2gfmyqzkz.html

Py:   resp.json()
来源：http://dali.aibaodan.cn/Article/details/gt2jyhgbfjf.html

PHP:  json_decode($body, true);
来源：http://dali.gogol.net.cn/Article/details/gt2lhuhmoka.html

JS:   await resp.json()
来源：http://dali.havefunace.top/Article/details/gt2hyxmozen.html

TS:   await resp.json()
来源：http://dali.feifeiyinyue.top/Article/details/gt2npxvziqd.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.aibaodan.cn/Article/details/gt2hzyoxzlh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sweek.top/Article/details/gt2vzysghyx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cheryme.top/Article/details/gt2zhimcfma.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.tian-w.cn/Article/details/gt2qyymtdxr.html

[L07] 处理 HTTP 状态码
来源：http://dali.chenjidiqi.icu/Article/details/gt2wjkfjmwb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.daria6918.cn/Article/details/gt2poxpowgh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.guowangkeji.top/Article/details/gt2apxjsvfa.html

JS:   resp.ok;  resp.status
来源：http://dali.gogol.net.cn/Article/details/gt2pscosuzn.html

TS:   resp.ok;  resp.status
来源：http://dali.zhongyouzk.top/Article/details/gt2ygowmhgr.html

Java: resp.statusCode()
来源：http://dali.nwbrower.top/Article/details/gt2tqvwrtxv.html

Go:   resp.StatusCode
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pxfsoszi.html

Ruby: resp.code.to_i
来源：http://dali.shzxlz.cn/Article/details/gt2npjgqnin.html

C#:   (int)resp.StatusCode
来源：http://dali.hnqzz.top/Article/details/gt2hjedfbjo.html

[L08] 并发请求多个地址
来源：http://dali.c1oappe.top/Article/details/gt2zhgjzeqe.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.tian-w.cn/Article/details/gt2aghvahqa.html

PHP:  curl_multi_init() 系列
来源：http://dali.sysykeji.top/Article/details/gt2siondtot.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daxiang520.top/Article/details/gt2xsmhihut.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uoinvyom.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hfpthk.cn/Article/details/gt2gvmwnwmu.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sweek.top/Article/details/gt2fjaikhdl.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hammf.cn/Article/details/gt2kbdcrpsb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinqigfzy.top/Article/details/gt2skmmpgkb.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2dbbkrtbs.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenlongwang.top/Article/details/gt2cntnhhyr.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2mwglfjxb.html

[M01] 读取命令行参数
来源：http://dali.fengsongda.top/Article/details/gt2cleoybfp.html

Py:   sys.argv[1:]
来源：http://dali.meibo888.top/Article/details/gt2cioyeczs.html

PHP:  $argv;  $argc;
来源：http://dali.kuanghao11.cn/Article/details/gt2glmvsaqy.html

JS:   process.argv.slice(2)
来源：http://dali.jianghu66.top/Article/details/gt2inssxhfe.html

TS:   process.argv.slice(2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rncpoakq.html

Java: args 数组（main 方法参数）
来源：http://dali.yuxming.cn/Article/details/gt2zlryztif.html

Go:   os.Args[1:]
来源：http://dali.snrcjt.cn/Article/details/gt2kprstyku.html

Ruby: ARGV
来源：http://dali.c1oappe.top/Article/details/gt2oesatmnb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.aizwys.cn/Article/details/gt2aawvjcnc.html

[M02] 读取环境变量
来源：http://dali.smart0.xyz/Article/details/gt2qcvgpyiy.html

Py:   os.environ.get("HOME")
来源：http://dali.quarkkingdee.top/Article/details/gt2bljdlnbx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj202588.top/Article/details/gt2aynszzcc.html

JS:   process.env.HOME
来源：http://dali.yj202588.top/Article/details/gt2owzufdoe.html

TS:   process.env.HOME
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fkqdjqar.html

Java: System.getenv("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gt2elbhdjrm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.daria6918.cn/Article/details/gt2dflcwpwk.html

Ruby: ENV["HOME"]
来源：http://dali.nwbrower.top/Article/details/gt2bvnlbilk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.tian-w.cn/Article/details/gt2xuoqqmps.html

[M03] 执行外部命令
来源：http://dali.jianghu66.top/Article/details/gt2horruyvp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ybcxt.top/Article/details/gt2hlntpdil.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.tianlin.xyz/Article/details/gt2gmqrsjwt.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xylfe.cn/Article/details/gt2pkjgipjq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cdnleiting.top/Article/details/gt2dobmlzeo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shangyingyoupin.top/Article/details/gt2femtuzse.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhixingplan.top/Article/details/gt2ysqkugfg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.bjfxy.top/Article/details/gt2oedlbfji.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shzxlz.cn/Article/details/gt2jdqeavlg.html

[M04] 获取当前工作目录
来源：http://dali.andypj.xyz/Article/details/gt2rbaucyak.html

Py:   os.getcwd()
来源：http://dali.gaohongyu789.top/Article/details/gt2hmvstxjw.html

PHP:  getcwd();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hkduqfje.html

JS:   process.cwd()
来源：http://dali.aizwys.cn/Article/details/gt2wkvqnnfw.html

TS:   process.cwd()
来源：http://dali.cheryme.top/Article/details/gt2ftrmfekt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yj20258888.top/Article/details/gt2kaxgvbmm.html

Go:   os.Getwd()
来源：http://dali.fengsongda.top/Article/details/gt2xhkflkya.html

Ruby: Dir.pwd
来源：http://dali.kuanghao11.cn/Article/details/gt2ozaylykf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.smart0.xyz/Article/details/gt2wveguyba.html

[M05] 设置退出码
来源：http://dali.cashguo.top/Article/details/gt2infbaray.html

Py:   sys.exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2dlwjmfaq.html

PHP:  exit(1);
来源：http://dali.quarkkingdee.top/Article/details/gt2bechzghm.html

JS:   process.exit(1)
来源：http://dali.aizwys.cn/Article/details/gt2sbyltcvo.html

TS:   process.exit(1)
来源：http://dali.guannengcc.top/Article/details/gt2qkouzzqh.html

Java: System.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lkziouqn.html

Go:   os.Exit(1)
来源：http://dali.havefunace.top/Article/details/gt2bbxjfndz.html

Ruby: exit 1
来源：http://dali.sxryk.cn/Article/details/gt2trphbbxm.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shuidangran.top/Article/details/gt2mibppjns.html

[M06] 向标准错误输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2shcyipol.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj20258.top/Article/details/gt2ubztgoma.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yj20258888.top/Article/details/gt2fadhhlrj.html

JS:   console.error("err")
来源：http://dali.mhx1999.top/Article/details/gt2uogbggio.html

TS:   console.error("err")
来源：http://dali.xylfe.cn/Article/details/gt2qelwcrwu.html

Java: System.err.println("err")
来源：http://dali.jianghu66.top/Article/details/gt2szkookiu.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.chenjidiqi.icu/Article/details/gt2osxyceaa.html

Ruby: warn "err"
来源：http://dali.jiagoushi.top/Article/details/gt2cmkzjwdz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hongshengwenyu.top/Article/details/gt2vanhzvlv.html

[M07] 判断是否为主入口
来源：http://dali.gzhubu.top/Article/details/gt2tcwmgrzx.html

Py:   if __name__ == "__main__":
来源：http://dali.guowangkeji.top/Article/details/gt2zzvvjpjt.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xziqi.cn/Article/details/gt2ksdkixfh.html

JS:   require.main === module
来源：http://dali.jqgufenzy.top/Article/details/gt2yyqrkkky.html

TS:   require.main === module
来源：http://dali.sufxvd.cn/Article/details/gt2cmileydc.html

Java: public static void main(String[] args)
来源：http://dali.zhiwuduotai.top/Article/details/gt2auvdhlqv.html

Go:   func main()
来源：http://dali.yj20258.top/Article/details/gt2ytfmvcdk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.316326.xyz/Article/details/gt2bdalfqmu.html

C#:   static void Main(string[] args)
来源：http://dali.hysaishi.cn/Article/details/gt2mricytsa.html

[M08] 获取系统与运行时信息
来源：http://dali.jiagoushi.top/Article/details/gt2nhgjbwzq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.haohaochexian.top/Article/details/gt2uqjdarnd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gzhubu.top/Article/details/gt2aesxhvfg.html

JS:   process.platform;  process.version
来源：http://dali.redwolf501.top/Article/details/gt2zqhsdlix.html

TS:   process.platform;  process.version
来源：http://dali.yuanzhike.top/Article/details/gt2bdhxktqi.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gotoacloud.top/Article/details/gt2cwymjqqf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sysykeji.top/Article/details/gt2xrvjibfk.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.pengpengdd.cyou/Article/details/gt2kwpbkryi.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinqigfzy.top/Article/details/gt2wifjyxmc.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2ebuunclo.html

N. 数据结构与算法
来源：http://dali.cdnleiting.top/Article/details/gt2acrepyig.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2pvclqglk.html

[N01] 二分查找（有序数组）
来源：http://dali.316326.xyz/Article/details/gt2bbmlejts.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.mhx1999.top/Article/details/gt2fbmacmkd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhiwuduotai.top/Article/details/gt2aemxuwpo.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yongpay.top/Article/details/gt2gwppxipi.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuanzhike.top/Article/details/gt2qytckupz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.redwolf501.top/Article/details/gt2tvuyjosr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2hggjtohk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sxryk.cn/Article/details/gt2mmfockob.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gt2kbnegyuy.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.guowangkeji.top/Article/details/gt2ltbiapfw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.haohaochexian.top/Article/details/gt2tmumwdce.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oaunwsfb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuanzx.com/Article/details/gt2bmznmnfn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sjbdbqgm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.nanxinkj.top/Article/details/gt2evpwxgei.html

Go:   slices.Sort(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2krwugmyj.html

Ruby: arr.sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dtymrgtl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jyoumei.cn/Article/details/gt2plmdejud.html

[N03] 快速排序（分治示例）
来源：http://dali.guannengcc.top/Article/details/gt2gdlppnfv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.wangshuangyany.cn/Article/details/gt2kkrzirxn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhoulong.xyz/Article/details/gt2heqzgdlj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aizwys.cn/Article/details/gt2omtxmoqi.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ydzc1.top/Article/details/gt2hcxlttgh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.fengsongda.top/Article/details/gt2vjyttgmd.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shuidangran.top/Article/details/gt2yrcwfvzw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.316326.xyz/Article/details/gt2qmeddbri.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jiagoushi.top/Article/details/gt2fpxgmmqo.html

[N04] 斐波那契数列
来源：http://dali.fengsongda.top/Article/details/gt2bjqsltkf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.nanxuanxn.top/Article/details/gt2rousvtja.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sxryk.cn/Article/details/gt2qiircpbz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhoulong.xyz/Article/details/gt2csmlpxhg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.c1oappe.top/Article/details/gt2iygevqaa.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.bjfxy.top/Article/details/gt2jzgiqdxn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hfpthk.cn/Article/details/gt2nyjgtwsl.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sxryk.cn/Article/details/gt2hsefowwz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dvbrexti.html

[N05] 最大公约数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zbllkxtj.html

Py:   math.gcd(a, b)
来源：http://dali.mhx1999.top/Article/details/gt2iemlpexf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhongyouzk.top/Article/details/gt2fzhwlrhp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nanxinkj.top/Article/details/gt2tgajnpwc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuxming.cn/Article/details/gt2yamanpaz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jyoumei.cn/Article/details/gt2bckrqjtt.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.nanxuanxn.top/Article/details/gt2ptveilga.html

Ruby: a.gcd(b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2npwwroqc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.iojbl.cn/Article/details/gt2kbfybxfe.html

[N06] 判断回文字符串
来源：http://dali.guowangkeji.top/Article/details/gt2igubuktm.html

Py:   s == s[::-1]
来源：http://dali.c1oappe.top/Article/details/gt2wwwzwszc.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxbgaiil.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gt2roefhhpn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gt2pigtecgr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cqqwz.cn/Article/details/gt2easnxnri.html

Go:   // 双指针从两端比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qdbsauuh.html

Ruby: s == s.reverse
来源：http://dali.zdqjudy.top/Article/details/gt2kylldkse.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.tanke756.top/Article/details/gt2pgmtjkbj.html

[N07] 两数之和（返回下标）
来源：http://dali.jyoumei.cn/Article/details/gt2vbqszpij.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.chenjidiqi.icu/Article/details/gt2sddtsfro.html


<!-- 参考信息 -->