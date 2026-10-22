代发 wailian999

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.haohaochexian.top/Article/details/gtdfmbkiwc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xziqi.cn/Article/details/gtrcreptwz.html

[J09] 时区处理
来源：http://dali.meibo888.top/Article/details/gtwydirjbi.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zycfv.cn/Article/details/gtclaitchs.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.fzhhl.top/Article/details/gtjhpygnqp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.feifeiyinyue.top/Article/details/gtuvkqmtyf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guowangkeji.top/Article/details/gthdfrhtfm.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.quarkkingdee.top/Article/details/gtriaicuyd.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ivvv.top/Article/details/gtzzwpkhwi.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yuxming.cn/Article/details/gtvomnnoqj.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.bjfxy.top/Article/details/gtkhiaszcv.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhixingplan.top/Article/details/gtfoztmnpi.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.c1oappe.top/Article/details/gtizkbcsty.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.dianchejie.cn/Article/details/gtonvaimtc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.chenzaomai.com/Article/details/gtdqjhzdpc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtzpiprtqi.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cqqwz.cn/Article/details/gtdjpyifjd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sysykeji.top/Article/details/gtgllonbcp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zycfv.cn/Article/details/gtyzldtsjw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jqgfzy.top/Article/details/gtzbpnqytn.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtdngnysrv.html

K. JSON 与序列化
来源：http://dali.sweek.top/Article/details/gtjmygfhpu.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtogcrsjwf.html

[K01] 对象转 JSON 字符串
来源：http://dali.gzhubu.top/Article/details/gtzgqbpgqr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.andypj.xyz/Article/details/gtkabtlmdb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.sufxvd.cn/Article/details/gtbufokzal.html

JS:   JSON.stringify(obj)
来源：http://dali.cashguo.top/Article/details/gtdjwmufnc.html

TS:   JSON.stringify(obj)
来源：http://dali.gotoacloud.top/Article/details/gtokqryxlp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yanxiufei.cn/Article/details/gtevtmgjbi.html

Go:   json.Marshal(obj)
来源：http://dali.dianchejie.cn/Article/details/gtybtyxiwi.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yangfankeji.com/Article/details/gtuiazmkmf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtctbanrzv.html

[K02] JSON 字符串转对象
来源：http://dali.quarkkingdee.top/Article/details/gtmpmbpgwq.html

Py:   json.loads(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtknnegzvw.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hywenlv.cn/Article/details/gtkaiqjsto.html

JS:   JSON.parse(s)
来源：http://dali.jlsjyb.cn/Article/details/gtdohlvoqp.html

TS:   JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gtpivrpsfn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gogol.net.cn/Article/details/gtcxlbcksq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.meibo888.top/Article/details/gtsfwfyfxl.html

Ruby: JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gtibynulet.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.wangdashe.top/Article/details/gtgsmssqjc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.dashuyun.cn/Article/details/gtuorgilzp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.wangdashe.top/Article/details/gtyeafxsgn.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hammf.cn/Article/details/gtdqnxatik.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xziqi.cn/Article/details/gtynggsxxq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxnfmxodx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.guowangkeji.top/Article/details/gtezkmbpax.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shuidangran.top/Article/details/gtaryjixmi.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.quarkkingdee.top/Article/details/gteazooxba.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj20258.top/Article/details/gtmblzwsgu.html

[K04] 读取 JSON 文件
来源：http://dali.jqgfzy.top/Article/details/gteuxsbfmc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shangyingyoupin.top/Article/details/gtldgivnnc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzcosblxu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shzxlz.cn/Article/details/gtfbtaetwf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ppjwa.cn/Article/details/gtaftcdphe.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.snrcjt.cn/Article/details/gtcpjhhxsv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hfpthk.cn/Article/details/gttinkeumk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxegkhslx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.haohaochexian.top/Article/details/gtcysegqvv.html

[K05] 深拷贝对象
来源：http://dali.sysykeji.top/Article/details/gtgcuwkyyk.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtfdozvmzt.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinghuilouyu.cn/Article/details/gtrrckbnbt.html

JS:   structuredClone(obj)
来源：http://dali.iojbl.cn/Article/details/gtktccjahm.html

TS:   structuredClone(obj)
来源：http://dali.dashuyun.cn/Article/details/gtlctemjaz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrvenytzl.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cqqwz.cn/Article/details/gtxnltsaym.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.fzhhl.top/Article/details/gtjdnyogwi.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hysaishi.cn/Article/details/gtkxywruuy.html

[K06] 解析 URL 查询串
来源：http://dali.sufxvd.cn/Article/details/gtwvrynpmc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gaohongyu789.top/Article/details/gtbhkbgigk.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.kuanghao11.cn/Article/details/gtqmbdskni.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nwbrower.top/Article/details/gtzgayxfwx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shuidangran.top/Article/details/gtlqyirqzi.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.meibo888.top/Article/details/gtkpyzqcng.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yj20258.top/Article/details/gtzdatkgbu.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hnqzz.top/Article/details/gtyucvedtt.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinqigfzy.top/Article/details/gtrmcjswpq.html

[K07] 进制转换
来源：http://dali.havefunace.top/Article/details/gtwjaaxmaw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cashguo.top/Article/details/gtyqxqnveh.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.guannengcc.top/Article/details/gteurqqtff.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yonumen.top/Article/details/gtrzlxhzif.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gtchhmixmo.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdwvlvhuk.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hammf.cn/Article/details/gtcfassdqj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.chenzaomai.com/Article/details/gtmojmhzfm.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.316326.xyz/Article/details/gttwqemdyn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yvedp.cn/Article/details/gtgxeshodh.html

Py:   pickle.dumps(obj)
来源：http://dali.dashuyun.cn/Article/details/gtradrwxgo.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.andypj.xyz/Article/details/gtwmuavnil.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sufxvd.cn/Article/details/gtuyndukci.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.wangshuangyany.cn/Article/details/gtdropmayf.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhixingplan.top/Article/details/gttzpxqjex.html

Go:   encoding/gob
来源：http://dali.nwbrower.top/Article/details/gtdaguxeza.html

Ruby: Marshal.dump(obj)
来源：http://dali.yj20258.top/Article/details/gtqwlaytdo.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.nwbrower.top/Article/details/gtncwcinjs.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtuwfdjekr.html

L. 网络请求
来源：http://dali.bjfxy.top/Article/details/gtuwvvwfku.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtjkzwxjpt.html

[L01] 发送 GET 请求
来源：http://dali.nanxuanxn.top/Article/details/gtuenhvqhq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.haohaochexian.top/Article/details/gtxmeiylgb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xziqi.cn/Article/details/gtxhrhcqsl.html

JS:   await fetch(url)
来源：http://dali.feifeiyinyue.top/Article/details/gtjjolreit.html

TS:   await fetch(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtautqfkhf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cdnleiting.top/Article/details/gtegufpqnz.html

Go:   resp, err := http.Get(url)
来源：http://dali.gaohongyu789.top/Article/details/gtkofsuycn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cashguo.top/Article/details/gtdopzsnue.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhixingplan.top/Article/details/gtsekiylif.html

[L02] 发送 POST JSON
来源：http://dali.yuanzhike.top/Article/details/gthdjhjfnx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yongpay.top/Article/details/gtmydoxmxk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ppjwa.cn/Article/details/gtkqbgwbcz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigfzy.top/Article/details/gtukysxetg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hysaishi.cn/Article/details/gtldxylzgw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xuanzx.com/Article/details/gtdkfincgf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.iojbl.cn/Article/details/gtgjughbiw.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gtblxqrype.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhengqikj.top/Article/details/gtkomwprdw.html

[L03] 设置自定义请求头
来源：http://dali.pengpengdd.cyou/Article/details/gtnbxjmxso.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cqqwz.cn/Article/details/gtlkapjuoi.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhoulong.xyz/Article/details/gtdghsyzps.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aibaodan.cn/Article/details/gtlbulskav.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hysaishi.cn/Article/details/gtqqhtrcbl.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yj202588.top/Article/details/gtvwpzicwx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.haohaochexian.top/Article/details/gtahevitzg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.tanke756.top/Article/details/gtgqlzdnhw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zdqjudy.top/Article/details/gtejrseicf.html

[L04] 设置超时
来源：http://dali.yuxming.cn/Article/details/gtckpdhphz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yuanzhike.top/Article/details/gtanhbadsn.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xuanzx.com/Article/details/gtyqlxplln.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xziqi.cn/Article/details/gtayetqwkz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtreojkeok.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sxryk.cn/Article/details/gthlaxhqwm.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.feifeiyinyue.top/Article/details/gtjxezlkit.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtezhxrapt.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.smart0.xyz/Article/details/gtmkqdbaja.html

[L05] 上传文件（multipart）
来源：http://dali.cashguo.top/Article/details/gtignkbqrq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.guowangkeji.top/Article/details/gteajqqmjs.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ybcxt.top/Article/details/gtltqmjjjz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigufen.top/Article/details/gtivwsmvqh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxuanxn.top/Article/details/gtqqnrvmhy.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.dianchejie.cn/Article/details/gtxgtefngm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yongpay.top/Article/details/gtpvglqeqf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.9152youxi.cn/Article/details/gtoxgoczds.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtznbaxqqk.html

[L06] 解析响应为 JSON
来源：http://dali.gogol.net.cn/Article/details/gtpfamphkq.html

Py:   resp.json()
来源：http://dali.snrcjt.cn/Article/details/gthnlqpbpp.html

PHP:  json_decode($body, true);
来源：http://dali.yangfankeji.com/Article/details/gtlecewrcc.html

JS:   await resp.json()
来源：http://dali.pycfn.com/Article/details/gtofnocrpo.html

TS:   await resp.json()
来源：http://dali.andypj.xyz/Article/details/gtukdfhxxn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.pengpengdd.cyou/Article/details/gtcwufamdc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.gaohongyu789.top/Article/details/gtntuqhopo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jqgufenzy.top/Article/details/gthnyzltbs.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.tanke756.top/Article/details/gtlksfuhkf.html

[L07] 处理 HTTP 状态码
来源：http://dali.yj20258.top/Article/details/gtvfkhysyl.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yueranfly.top/Article/details/gtrivohfmw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shzxlz.cn/Article/details/gtbrdzeyzi.html

JS:   resp.ok;  resp.status
来源：http://dali.sxryk.cn/Article/details/gtpayazxor.html

TS:   resp.ok;  resp.status
来源：http://dali.zhoulong.xyz/Article/details/gtwsvbxxpe.html

Java: resp.statusCode()
来源：http://dali.daria6918.cn/Article/details/gtgqklpwqz.html

Go:   resp.StatusCode
来源：http://dali.xinyue.icu/Article/details/gtcggsfujj.html

Ruby: resp.code.to_i
来源：http://dali.daria6918.cn/Article/details/gtstuyqnhg.html

C#:   (int)resp.StatusCode
来源：http://dali.0kj1m.cn/Article/details/gtqpfhnbid.html

[L08] 并发请求多个地址
来源：http://dali.zhixingplan.top/Article/details/gthynxuwtv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cashguo.top/Article/details/gtvidessga.html

PHP:  curl_multi_init() 系列
来源：http://dali.yj20258.top/Article/details/gtvmguodfa.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuanzx.com/Article/details/gtdvjokkqz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.c1oappe.top/Article/details/gtkmwuetvk.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.meibo888.top/Article/details/gtkbgaseix.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.birdmap.top/Article/details/gtvqfuwbpn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.vqdsnc.cn/Article/details/gtoxeamlby.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xuetiantiany.cn/Article/details/gtdllamiof.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuvfcyapu.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenzaomai.com/Article/details/gtrlwdlwiy.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtrhhgpvyq.html

[M01] 读取命令行参数
来源：http://dali.yj20258.top/Article/details/gtzeatqppx.html

Py:   sys.argv[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmbntkzgj.html

PHP:  $argv;  $argc;
来源：http://dali.9152youxi.cn/Article/details/gtshdekbve.html

JS:   process.argv.slice(2)
来源：http://dali.pengpengdd.cyou/Article/details/gtuzydmikq.html

TS:   process.argv.slice(2)
来源：http://dali.xylfe.cn/Article/details/gtivmitwzw.html

Java: args 数组（main 方法参数）
来源：http://dali.yuanzhike.top/Article/details/gtxnbptgns.html

Go:   os.Args[1:]
来源：http://dali.gotoacloud.top/Article/details/gtusrdrrby.html

Ruby: ARGV
来源：http://dali.xylfe.cn/Article/details/gtsnfxwndk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.svipenyu.cn/Article/details/gtajovpfig.html

[M02] 读取环境变量
来源：http://dali.jinqigufen.top/Article/details/gtdjomeoym.html

Py:   os.environ.get("HOME")
来源：http://dali.guannengcc.top/Article/details/gtfebpiyfd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ehwqpu.com/Article/details/gtuqkrlfli.html

JS:   process.env.HOME
来源：http://dali.xinyue.icu/Article/details/gtloonodvu.html

TS:   process.env.HOME
来源：http://dali.fzhhl.top/Article/details/gtgnnhggcx.html

Java: System.getenv("HOME")
来源：http://dali.yonumen.top/Article/details/gtnezavcuk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yonumen.top/Article/details/gtzrwmodfp.html

Ruby: ENV["HOME"]
来源：http://dali.shanyushiyangtech.top/Article/details/gtlhgaijty.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zdqjudy.top/Article/details/gtmizijkew.html

[M03] 执行外部命令
来源：http://dali.andypj.xyz/Article/details/gtwlwpoiej.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hysaishi.cn/Article/details/gtlxydxqxh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hammf.cn/Article/details/gtppnyhywp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yonumen.top/Article/details/gtpcsqxgwi.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hammf.cn/Article/details/gtrshypazg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gogol.net.cn/Article/details/gtsxcjoauz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoqdcnrwq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sysykeji.top/Article/details/gtlyfnfubx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.snrcjt.cn/Article/details/gtxotugckz.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gtaytjolkj.html

Py:   os.getcwd()
来源：http://dali.svipenyu.cn/Article/details/gtjjpjvgoe.html

PHP:  getcwd();
来源：http://dali.dashuyun.cn/Article/details/gtmlfutrry.html

JS:   process.cwd()
来源：http://dali.meibo888.top/Article/details/gtvaqtxdxs.html

TS:   process.cwd()
来源：http://dali.mhx1999.top/Article/details/gtgafzwbyr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shangyingyoupin.top/Article/details/gtttqbvtao.html

Go:   os.Getwd()
来源：http://dali.yj20258888.top/Article/details/gttuskjypv.html

Ruby: Dir.pwd
来源：http://dali.ydzc1.top/Article/details/gtunsgujii.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ybcxt.top/Article/details/gtyfdqmitk.html

[M05] 设置退出码
来源：http://dali.chenzaomai.com/Article/details/gtffahfuqq.html

Py:   sys.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gtlvhxiwam.html

PHP:  exit(1);
来源：http://dali.tanke756.top/Article/details/gtyihaqggc.html

JS:   process.exit(1)
来源：http://dali.xziqi.cn/Article/details/gtvlhqlbon.html

TS:   process.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtdurvipzj.html

Java: System.exit(1)
来源：http://dali.yuxming.cn/Article/details/gtyfuvbeqq.html

Go:   os.Exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtfiliswvw.html

Ruby: exit 1
来源：http://dali.fengsongda.top/Article/details/gtocckbxox.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.gaohongyu789.top/Article/details/gthparcapj.html

[M06] 向标准错误输出
来源：http://dali.zycfv.cn/Article/details/gtuytcqakm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gaohongyu789.top/Article/details/gtfboxrstl.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xuanzx.com/Article/details/gtfwuuohjf.html

JS:   console.error("err")
来源：http://dali.ppjwa.cn/Article/details/gtrwtthbbi.html

TS:   console.error("err")
来源：http://dali.cashguo.top/Article/details/gtownqmsms.html

Java: System.err.println("err")
来源：http://dali.wangdashe.top/Article/details/gtxichpmgk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shzxlz.cn/Article/details/gtgzjkdaju.html

Ruby: warn "err"
来源：http://dali.daria6918.cn/Article/details/gthhjxgpcq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yuanzhike.top/Article/details/gtvyhmlreu.html

[M07] 判断是否为主入口
来源：http://dali.smart0.xyz/Article/details/gtbjcgkgrg.html

Py:   if __name__ == "__main__":
来源：http://dali.snrcjt.cn/Article/details/gtfpuadrjn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gzhubu.top/Article/details/gtzsonntoe.html

JS:   require.main === module
来源：http://dali.cdnleiting.top/Article/details/gtrcivbrma.html

TS:   require.main === module
来源：http://dali.wangdashe.top/Article/details/gtgxssydph.html

Java: public static void main(String[] args)
来源：http://dali.yuxming.cn/Article/details/gtkmxvyckd.html

Go:   func main()
来源：http://dali.zycfv.cn/Article/details/gtrehugwlr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yuxming.cn/Article/details/gtcvxslngw.html

C#:   static void Main(string[] args)
来源：http://dali.0kj1m.cn/Article/details/gtxsjpwzmq.html

[M08] 获取系统与运行时信息
来源：http://dali.iojbl.cn/Article/details/gtddkqfhys.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xylfe.cn/Article/details/gtcivwuqch.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.havefunace.top/Article/details/gtknlhqrba.html

JS:   process.platform;  process.version
来源：http://dali.wangdashe.top/Article/details/gtxlixslkj.html

TS:   process.platform;  process.version
来源：http://dali.pengpengdd.cyou/Article/details/gtwfnsjimy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.0kj1m.cn/Article/details/gtxedlzytj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.guannengcc.top/Article/details/gtiqmiolfo.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.9152youxi.cn/Article/details/gtrqcquaah.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jqgfzy.top/Article/details/gtcoxwjwdn.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtuqmffhkz.html

N. 数据结构与算法
来源：http://dali.cqqwz.cn/Article/details/gtvteevydl.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtnuhjsjfx.html

[N01] 二分查找（有序数组）
来源：http://dali.jianghu66.top/Article/details/gtxvbcfdad.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtgczopfvb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jyoumei.cn/Article/details/gtbjgopcrt.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxinkj.top/Article/details/gtvsybdcus.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tian-w.cn/Article/details/gtjpmoyxej.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gtqqxejafe.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtpokjlswu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.fengsongda.top/Article/details/gtlbutdzih.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gtebfepgqf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yvedp.cn/Article/details/gtseqlsorb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenjidiqi.icu/Article/details/gtsnhzcrxx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jyoumei.cn/Article/details/gtzcnkrqsn.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cheryme.top/Article/details/gtqumslrzb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuanzx.com/Article/details/gtdurdcdpr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hnxiangtu.top/Article/details/gtljfvsqpq.html

Go:   slices.Sort(arr)
来源：http://dali.andypj.xyz/Article/details/gtsmljcxma.html

Ruby: arr.sort
来源：http://dali.zdqjudy.top/Article/details/gtrddfjkgy.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yuanzhike.top/Article/details/gttgqvjgli.html

[N03] 快速排序（分治示例）
来源：http://dali.wangdashe.top/Article/details/gthsxbyvuu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.aibaodan.cn/Article/details/gtkbobbtlt.html

PHP:  // 递归实现，或用 usort
来源：http://dali.guowangkeji.top/Article/details/gtsylfvikg.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxuanxn.top/Article/details/gtzndcsjls.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.vqdsnc.cn/Article/details/gtcdyisgvz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hongshengwenyu.top/Article/details/gtteafyhnf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.haohaochexian.top/Article/details/gtopafnacg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.pengpengdd.cyou/Article/details/gtkqgkhked.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yueranfly.top/Article/details/gtszntitec.html

[N04] 斐波那契数列
来源：http://dali.xuanzx.com/Article/details/gtrcwzfxxk.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtsbjeykuf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhoulong.xyz/Article/details/gtwfdemuui.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zycfv.cn/Article/details/gtxoqkfkbv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gtrcszjtdx.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zdqjudy.top/Article/details/gtimokjalr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.bjfxy.top/Article/details/gtvcejyxpt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtjafqotjo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gtllpwyase.html

[N05] 最大公约数
来源：http://dali.redwolf501.top/Article/details/gtkqgmcssq.html

Py:   math.gcd(a, b)
来源：http://dali.c1oappe.top/Article/details/gtoaqnkztv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yuanzhike.top/Article/details/gtnsaxucqv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.c1oappe.top/Article/details/gtbozjkpsy.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xziqi.cn/Article/details/gtywhodyrv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.kuanghao11.cn/Article/details/gtadbligad.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.fengsongda.top/Article/details/gtdhhhoavz.html

Ruby: a.gcd(b)
来源：http://dali.yongpay.top/Article/details/gtejqxqpja.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.kuanghao11.cn/Article/details/gtvwcrhasf.html

[N06] 判断回文字符串
来源：http://dali.gzhubu.top/Article/details/gtmnhjwdwd.html

Py:   s == s[::-1]
来源：http://dali.zhengqikj.top/Article/details/gtfngnlalu.html

PHP:  $s === strrev($s);
来源：http://dali.dashuyun.cn/Article/details/gtkwtcjrok.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gtpbqbbqsg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gtbspqxwqe.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.andypj.xyz/Article/details/gtkolvdhde.html

Go:   // 双指针从两端比较
来源：http://dali.jianghu66.top/Article/details/gtddttzqqb.html


<!-- 参考信息 -->