代发 wailian999

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cashguo.top/Article/details/gtdigusswf.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.vqdsnc.cn/Article/details/gtojkzktxb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shuidangran.top/Article/details/gtmlgcbyve.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.9152youxi.cn/Article/details/gtyqnughfu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuisvtkfk.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yuxming.cn/Article/details/gtkkxofbrv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.dianchejie.cn/Article/details/gtodivomgg.html

[J10] 取今天 / 本月第一天
来源：http://dali.zycfv.cn/Article/details/gttcnxfaka.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hammf.cn/Article/details/gtsrgdtbmk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.svipenyu.cn/Article/details/gtjpokiqkz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.iojbl.cn/Article/details/gtlfhejiap.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj20258888.top/Article/details/gtcgcxgqqw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhoulong.xyz/Article/details/gtrdypgdtw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sufxvd.cn/Article/details/gtqsefinwx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ivvv.top/Article/details/gtetkwzbrg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ehwqpu.com/Article/details/gttwwbxdul.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gthnlkwaqh.html

K. JSON 与序列化
来源：http://dali.yongpay.top/Article/details/gtamsbscke.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtogzczlcy.html

[K01] 对象转 JSON 字符串
来源：http://dali.ydzc1.top/Article/details/gtagtknovz.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.andypj.xyz/Article/details/gtjjgozfoc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cashguo.top/Article/details/gtyflftfet.html

JS:   JSON.stringify(obj)
来源：http://dali.mhx1999.top/Article/details/gtfvwmsfen.html

TS:   JSON.stringify(obj)
来源：http://dali.yj202588.top/Article/details/gtauquekpr.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ydzc1.top/Article/details/gtcqicqvlh.html

Go:   json.Marshal(obj)
来源：http://dali.9152youxi.cn/Article/details/gtxebwrheq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gogol.net.cn/Article/details/gtofklfanq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.nanxinkj.top/Article/details/gtgtwiwwpr.html

[K02] JSON 字符串转对象
来源：http://dali.cheryme.top/Article/details/gthpuybevj.html

Py:   json.loads(s)
来源：http://dali.wangdashe.top/Article/details/gtlotdjykz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hnxiangtu.top/Article/details/gtrxsjbkww.html

JS:   JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtycnlvtoa.html

TS:   JSON.parse(s)
来源：http://dali.cdnleiting.top/Article/details/gtwvbgczco.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmujtdupr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.dashuyun.cn/Article/details/gtwpsyfbmf.html

Ruby: JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gtkatcvdli.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgygcpfow.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jiagoushi.top/Article/details/gteexxchcp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.daxiang520.top/Article/details/gtoieffxcd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.wangdashe.top/Article/details/gtiiohndao.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gtmlbpkqro.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenlongwang.top/Article/details/gtgdxaqthm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.guannengcc.top/Article/details/gtulytgufx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ydzc1.top/Article/details/gtninclxoa.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shuidangran.top/Article/details/gtzcewrhym.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.bjfxy.top/Article/details/gtyebciozk.html

[K04] 读取 JSON 文件
来源：http://dali.chenlongwang.top/Article/details/gtwrrahgmw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yvedp.cn/Article/details/gtxdqkupiu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.svipenyu.cn/Article/details/gtkgpemqov.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tianlin.xyz/Article/details/gtxhvbfryw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.dianchejie.cn/Article/details/gtxbteqttl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hywenlv.cn/Article/details/gtxpsqtstg.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yangfankeji.com/Article/details/gttdasassh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yangfankeji.com/Article/details/gtnrutzpwf.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hysaishi.cn/Article/details/gtympwbrmu.html

[K05] 深拷贝对象
来源：http://dali.quarkkingdee.top/Article/details/gtuhjosozl.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtefmmckis.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hongshengwenyu.top/Article/details/gtpvrhqrbw.html

JS:   structuredClone(obj)
来源：http://dali.zhengqikj.top/Article/details/gtanzqweds.html

TS:   structuredClone(obj)
来源：http://dali.havefunace.top/Article/details/gtmpxdqcyo.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zdqjudy.top/Article/details/gteikhrrvo.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jqgufenzy.top/Article/details/gtwpxwgwub.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwmifukbw.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cashguo.top/Article/details/gtqareivdf.html

[K06] 解析 URL 查询串
来源：http://dali.cucudq.cn/Article/details/gtnctgfway.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hnqzz.top/Article/details/gtyyqevmjw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hysaishi.cn/Article/details/gtijygvpbv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sysykeji.top/Article/details/gtnqpswpya.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sysykeji.top/Article/details/gtpueckojm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.daxiang520.top/Article/details/gtwsmuzcsz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yuanzhike.top/Article/details/gtlarcprza.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.meibo888.top/Article/details/gtgyybdjcl.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jlsjyb.cn/Article/details/gtpuskksun.html

[K07] 进制转换
来源：http://dali.wangdashe.top/Article/details/gtyvicbblq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfxirxdps.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.316326.xyz/Article/details/gtkiqeutgn.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtpgctglwe.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gtsaujzcvn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cashguo.top/Article/details/gtvtfwomio.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hnqzz.top/Article/details/gtzcipidqd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hfpthk.cn/Article/details/gtkfxvaflc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gtzackmajj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.0kj1m.cn/Article/details/gtyxjcqbgh.html

Py:   pickle.dumps(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnrvfkwru.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nwbrower.top/Article/details/gthjzpijte.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hysaishi.cn/Article/details/gtdupqmobm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.haohaochexian.top/Article/details/gtnyecposh.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.tanke756.top/Article/details/gthmgijwrf.html

Go:   encoding/gob
来源：http://dali.yj20258.top/Article/details/gtsywltojk.html

Ruby: Marshal.dump(obj)
来源：http://dali.yvedp.cn/Article/details/gtlrlywbgm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yj20258.top/Article/details/gttxcqfarp.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtnorthrum.html

L. 网络请求
来源：http://dali.c1oappe.top/Article/details/gtfbskbyyn.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtyiyrquym.html

[L01] 发送 GET 请求
来源：http://dali.316326.xyz/Article/details/gtbvdarzpi.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.andypj.xyz/Article/details/gtxynozhsw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shanyushiyangtech.top/Article/details/gtqqblwcnf.html

JS:   await fetch(url)
来源：http://dali.cucudq.cn/Article/details/gtgtszlrre.html

TS:   await fetch(url)
来源：http://dali.iojbl.cn/Article/details/gtgribauls.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.chenjidiqi.icu/Article/details/gtgaywwdyw.html

Go:   resp, err := http.Get(url)
来源：http://dali.nanxinkj.top/Article/details/gtgncxokvn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.iojbl.cn/Article/details/gtqljhjchb.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xziqi.cn/Article/details/gtludjcekn.html

[L02] 发送 POST JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gtjshflnfk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.aizwys.cn/Article/details/gtcluttlwi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cqqwz.cn/Article/details/gtquddypmr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgfzy.top/Article/details/gtpscuorvi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.andypj.xyz/Article/details/gtwfcwsdjf.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.sweek.top/Article/details/gtooosbwqw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shzxlz.cn/Article/details/gttgjnhqlc.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cdnleiting.top/Article/details/gtayqqrcan.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.tian-w.cn/Article/details/gtffbfnvai.html

[L03] 设置自定义请求头
来源：http://dali.ivvv.top/Article/details/gtaghcvgvx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cashguo.top/Article/details/gtnxzdfomk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.vqdsnc.cn/Article/details/gtjdolpgan.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cashguo.top/Article/details/gtkkgttbxe.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yongpay.top/Article/details/gtnkxovgzz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.fengsongda.top/Article/details/gtnmbaulqn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yueranfly.top/Article/details/gtnwrazhri.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jianghu66.top/Article/details/gtwyznkxss.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ehwqpu.com/Article/details/gtxbmhyzha.html

[L04] 设置超时
来源：http://dali.havefunace.top/Article/details/gtzkxnkupf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.bjfxy.top/Article/details/gtqqtbkjiu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zdqjudy.top/Article/details/gtljlizowt.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxuanxn.top/Article/details/gtxvxtirgd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.havefunace.top/Article/details/gtbdozjqye.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jlsjyb.cn/Article/details/gtygwjyjjq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.feifeiyinyue.top/Article/details/gthlftnvwf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinqigufen.top/Article/details/gtmpiswkec.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cucudq.cn/Article/details/gtqrpldguu.html

[L05] 上传文件（multipart）
来源：http://dali.jianghu66.top/Article/details/gtsxwukwjd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xziqi.cn/Article/details/gthikdssjo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ppjwa.cn/Article/details/gtydsdnzaq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.tian-w.cn/Article/details/gtczowgvkt.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.birdmap.top/Article/details/gtgrbtidym.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sufxvd.cn/Article/details/gtxepthjno.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.mhx1999.top/Article/details/gteuovwmei.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yanxiufei.cn/Article/details/gtrqmypfrp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yongpay.top/Article/details/gtcveskepk.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gtalxxqfeg.html

Py:   resp.json()
来源：http://dali.c1oappe.top/Article/details/gtgofiueuw.html

PHP:  json_decode($body, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdtgyfqzb.html

JS:   await resp.json()
来源：http://dali.redwolf501.top/Article/details/gtumjwckiw.html

TS:   await resp.json()
来源：http://dali.ppjwa.cn/Article/details/gtpzbustfo.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gtemecmamo.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.mhx1999.top/Article/details/gtxezekelm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.chenlongwang.top/Article/details/gtwskthtgn.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.svipenyu.cn/Article/details/gtkjadmely.html

[L07] 处理 HTTP 状态码
来源：http://dali.havefunace.top/Article/details/gtqfbyjrjj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.guannengcc.top/Article/details/gtqnedbhaw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cashguo.top/Article/details/gtrpyldetm.html

JS:   resp.ok;  resp.status
来源：http://dali.cheryme.top/Article/details/gtkblzqpyf.html

TS:   resp.ok;  resp.status
来源：http://dali.yueranfly.top/Article/details/gtqhomjjpu.html

Java: resp.statusCode()
来源：http://dali.jianghu66.top/Article/details/gtalinkhkx.html

Go:   resp.StatusCode
来源：http://dali.ppjwa.cn/Article/details/gtuuprvsss.html

Ruby: resp.code.to_i
来源：http://dali.gotoacloud.top/Article/details/gtdkpeqipf.html

C#:   (int)resp.StatusCode
来源：http://dali.zhiwuduotai.top/Article/details/gtxzodrxvq.html

[L08] 并发请求多个地址
来源：http://dali.sweek.top/Article/details/gtiaewgkmi.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqlicrsft.html

PHP:  curl_multi_init() 系列
来源：http://dali.pycfn.com/Article/details/gthsxhxhyp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgfzy.top/Article/details/gtfqqffaps.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tanke756.top/Article/details/gtxkbxfixd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.feifeiyinyue.top/Article/details/gtxkeecewx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xuanzx.com/Article/details/gtpnrurkpe.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.daria6918.cn/Article/details/gtjgiiyaoe.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.birdmap.top/Article/details/gtqouklpxr.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtxozxupvi.html

M. 命令行 / 进程 / 环境
来源：http://dali.cashguo.top/Article/details/gtrlzpkfxl.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtfetopihn.html

[M01] 读取命令行参数
来源：http://dali.gotoacloud.top/Article/details/gtecocclxd.html

Py:   sys.argv[1:]
来源：http://dali.9152youxi.cn/Article/details/gtaqlhfcrq.html

PHP:  $argv;  $argc;
来源：http://dali.fzhhl.top/Article/details/gtjjdleesg.html

JS:   process.argv.slice(2)
来源：http://dali.zhoulong.xyz/Article/details/gtemzyrbuw.html

TS:   process.argv.slice(2)
来源：http://dali.smart0.xyz/Article/details/gtamnerdgr.html

Java: args 数组（main 方法参数）
来源：http://dali.jinghuilouyu.cn/Article/details/gtgsebgore.html

Go:   os.Args[1:]
来源：http://dali.c1oappe.top/Article/details/gthocvrjds.html

Ruby: ARGV
来源：http://dali.chenlongwang.top/Article/details/gtrtwzwity.html

C#:   args 数组（Main 方法参数）
来源：http://dali.havefunace.top/Article/details/gtogltirqy.html

[M02] 读取环境变量
来源：http://dali.jlsjyb.cn/Article/details/gtnvyqhrxh.html

Py:   os.environ.get("HOME")
来源：http://dali.jinqigufen.top/Article/details/gttqrrmfah.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.fzhhl.top/Article/details/gtrafarjzg.html

JS:   process.env.HOME
来源：http://dali.316326.xyz/Article/details/gtzrfhbntz.html

TS:   process.env.HOME
来源：http://dali.hammf.cn/Article/details/gtfqqlkhuo.html

Java: System.getenv("HOME")
来源：http://dali.andypj.xyz/Article/details/gtfhncydsn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ehwqpu.com/Article/details/gtzgvpwkrw.html

Ruby: ENV["HOME"]
来源：http://dali.nwbrower.top/Article/details/gtcugcjqgf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gogol.net.cn/Article/details/gtogsuebgy.html

[M03] 执行外部命令
来源：http://dali.shzxlz.cn/Article/details/gtppqaglja.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sufxvd.cn/Article/details/gthkykjrjj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj202588.top/Article/details/gtbgmawwne.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ybcxt.top/Article/details/gtobmaxkyc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gtosojqcxk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtehsksjzl.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shuidangran.top/Article/details/gtyrllmgpf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jqgufenzy.top/Article/details/gtqfblezmy.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cqqwz.cn/Article/details/gtywdeyllj.html

[M04] 获取当前工作目录
来源：http://dali.xuetiantiany.cn/Article/details/gtkihhslzt.html

Py:   os.getcwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbopdpdlw.html

PHP:  getcwd();
来源：http://dali.jinqigufen.top/Article/details/gtotoewwwr.html

JS:   process.cwd()
来源：http://dali.jinqigfzy.top/Article/details/gtmwbvfcqz.html

TS:   process.cwd()
来源：http://dali.kuanghao11.cn/Article/details/gtepssrnwv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.daria6918.cn/Article/details/gthvozmstq.html

Go:   os.Getwd()
来源：http://dali.iojbl.cn/Article/details/gtbufftnai.html

Ruby: Dir.pwd
来源：http://dali.sweek.top/Article/details/gtpafbibyn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xinyue.icu/Article/details/gtndcdhref.html

[M05] 设置退出码
来源：http://dali.aizwys.cn/Article/details/gtxbceefiz.html

Py:   sys.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtcnwyfwrw.html

PHP:  exit(1);
来源：http://dali.gzhubu.top/Article/details/gtfxdbyuyq.html

JS:   process.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtupgdxhnd.html

TS:   process.exit(1)
来源：http://dali.redwolf501.top/Article/details/gtdbnwgyij.html

Java: System.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gtvmttphzs.html

Go:   os.Exit(1)
来源：http://dali.hysaishi.cn/Article/details/gtbtmndfiz.html

Ruby: exit 1
来源：http://dali.hfpthk.cn/Article/details/gtlmglzktt.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxmvhflna.html

[M06] 向标准错误输出
来源：http://dali.jinghuilouyu.cn/Article/details/gtrvxyzihj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.0kj1m.cn/Article/details/gtxvertukp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.meibo888.top/Article/details/gtewfmhqrq.html

JS:   console.error("err")
来源：http://dali.hfpthk.cn/Article/details/gtoypvsrad.html

TS:   console.error("err")
来源：http://dali.hnqzz.top/Article/details/gtjwizsajq.html

Java: System.err.println("err")
来源：http://dali.jlsjyb.cn/Article/details/gtlfzqibds.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ybcxt.top/Article/details/gtizmubmew.html

Ruby: warn "err"
来源：http://dali.aizwys.cn/Article/details/gtwkchintw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.bjfxy.top/Article/details/gtizngqxpy.html

[M07] 判断是否为主入口
来源：http://dali.zdqjudy.top/Article/details/gthdvzsble.html

Py:   if __name__ == "__main__":
来源：http://dali.fengsongda.top/Article/details/gtastybftk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ppjwa.cn/Article/details/gtjnlycmjv.html

JS:   require.main === module
来源：http://dali.sufxvd.cn/Article/details/gtauiawdyu.html

TS:   require.main === module
来源：http://dali.hfpthk.cn/Article/details/gtfjhyjsax.html

Java: public static void main(String[] args)
来源：http://dali.svipenyu.cn/Article/details/gtnipabiux.html

Go:   func main()
来源：http://dali.yj20258.top/Article/details/gtmsjqodsl.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gaohongyu789.top/Article/details/gthgxzytno.html

C#:   static void Main(string[] args)
来源：http://dali.jyoumei.cn/Article/details/gticyzkqqm.html

[M08] 获取系统与运行时信息
来源：http://dali.havefunace.top/Article/details/gtjixorohx.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sxryk.cn/Article/details/gthxmjialu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cashguo.top/Article/details/gtjgsowgks.html

JS:   process.platform;  process.version
来源：http://dali.dashuyun.cn/Article/details/gtqbjgqmdj.html

TS:   process.platform;  process.version
来源：http://dali.daxiang520.top/Article/details/gtbfqgepmg.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinqigfzy.top/Article/details/gtgptomcez.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.dianchejie.cn/Article/details/gtjxqwgsnk.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cdnleiting.top/Article/details/gtnqezcmbt.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.aibaodan.cn/Article/details/gtxwgkiwnk.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtjipxxoet.html

N. 数据结构与算法
来源：http://dali.daria6918.cn/Article/details/gtfzzmizba.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtgyeovlcm.html

[N01] 二分查找（有序数组）
来源：http://dali.vqdsnc.cn/Article/details/gtgdhqjleg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtabpcjbvt.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.chenjidiqi.icu/Article/details/gtrvnhejkc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwwzxvdjy.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guannengcc.top/Article/details/gtwgfzvbbk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtsdpnanvn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gtxgzymxqj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhongyouzk.top/Article/details/gtbdkxlgvy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jianghu66.top/Article/details/gtdynguzfb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinqigfzy.top/Article/details/gtqkvdqmbv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.c1oappe.top/Article/details/gtenwvzoxh.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.feifeiyinyue.top/Article/details/gtoticqisg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxuanxn.top/Article/details/gtwnltyupa.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258888.top/Article/details/gtmhitucjn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinghuilouyu.cn/Article/details/gtluoxgswn.html

Go:   slices.Sort(arr)
来源：http://dali.mhx1999.top/Article/details/gtbafejvxn.html

Ruby: arr.sort
来源：http://dali.xylfe.cn/Article/details/gtyehyvwse.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ehwqpu.com/Article/details/gtbijtpbjx.html

[N03] 快速排序（分治示例）
来源：http://dali.birdmap.top/Article/details/gtqaouthmj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sysykeji.top/Article/details/gtgtrqhoke.html

PHP:  // 递归实现，或用 usort
来源：http://dali.pengpengdd.cyou/Article/details/gtnazyezjm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgufenzy.top/Article/details/gtblifojfb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.kuanghao11.cn/Article/details/gtobdlesbt.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.dashuyun.cn/Article/details/gtciegsxvi.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj202588.top/Article/details/gtukrsivym.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.9152youxi.cn/Article/details/gtouersmaz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shuidangran.top/Article/details/gtyodrgsiy.html

[N04] 斐波那契数列
来源：http://dali.sysykeji.top/Article/details/gtwvkcldws.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hnqzz.top/Article/details/gtjlemzzil.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.dianchejie.cn/Article/details/gtfarevtiu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtiqglqwcw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangdashe.top/Article/details/gtnghlloig.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttiypdbyg.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtytsetatt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.dianchejie.cn/Article/details/gtzoctkwfm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cucudq.cn/Article/details/gtoivulknu.html

[N05] 最大公约数
来源：http://dali.birdmap.top/Article/details/gtrzfkuimq.html

Py:   math.gcd(a, b)
来源：http://dali.yj20258888.top/Article/details/gtooynqnwj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.tanke756.top/Article/details/gtjcbcsvxl.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daria6918.cn/Article/details/gtgegfzkrn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.9152youxi.cn/Article/details/gtjhlyquai.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.andypj.xyz/Article/details/gthdznslgl.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.chenzaomai.com/Article/details/gtonehyeoi.html

Ruby: a.gcd(b)
来源：http://dali.jiagoushi.top/Article/details/gtgqjhyriq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jianghu66.top/Article/details/gtccetnebj.html

[N06] 判断回文字符串
来源：http://dali.yongpay.top/Article/details/gtshwllnwr.html

Py:   s == s[::-1]
来源：http://dali.pycfn.com/Article/details/gtmhalolbg.html

PHP:  $s === strrev($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtbxhxcybf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gtqrmjbiai.html

TS:   s === [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gttcsxibve.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cucudq.cn/Article/details/gtviovtttb.html

Go:   // 双指针从两端比较
来源：http://dali.haohaochexian.top/Article/details/gtzhrrbhjp.html

Ruby: s == s.reverse
来源：http://dali.zhoulong.xyz/Article/details/gtowkaznmk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.tian-w.cn/Article/details/gtbwtafngt.html

[N07] 两数之和（返回下标）
来源：http://dali.jlsjyb.cn/Article/details/gtdosguste.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.tian-w.cn/Article/details/gthnxnytbs.html


<!-- 参考信息 -->