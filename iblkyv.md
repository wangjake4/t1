代发 wailian999

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.bjfxy.top/Article/details/gtudxbzjyp.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.0kj1m.cn/Article/details/gtwockarhk.html

[J09] 时区处理
来源：http://dali.yongpay.top/Article/details/gtddkgnavf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yuanzhike.top/Article/details/gteogzaqhg.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinqigufen.top/Article/details/gtyjazryem.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ydzc1.top/Article/details/gtchaxcstr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yangfankeji.com/Article/details/gtonjogunr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.mhx1999.top/Article/details/gtzomrklvm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jqgufenzy.top/Article/details/gtwpznruce.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sxryk.cn/Article/details/gtebmwawme.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.daxiang520.top/Article/details/gtlzvicljs.html

[J10] 取今天 / 本月第一天
来源：http://dali.svipenyu.cn/Article/details/gtpbokmvwm.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xinyue.icu/Article/details/gtoqpuxgaj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sufxvd.cn/Article/details/gtovrilfyr.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtglubmsaw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpntecxmd.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zdqjudy.top/Article/details/gtdabpvtrx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jqgfzy.top/Article/details/gtiwobdxoh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.dashuyun.cn/Article/details/gtiiirrabe.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttmnkxloq.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtseytahkv.html

K. JSON 与序列化
来源：http://dali.yj20258.top/Article/details/gttulahmdx.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtugbtmlwm.html

[K01] 对象转 JSON 字符串
来源：http://dali.shzxlz.cn/Article/details/gtnlxznwce.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jlsjyb.cn/Article/details/gtfucvsfwh.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhixingplan.top/Article/details/gtmjcbthui.html

JS:   JSON.stringify(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtnoocbbeq.html

TS:   JSON.stringify(obj)
来源：http://dali.sysykeji.top/Article/details/gtbbupiiyo.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shzxlz.cn/Article/details/gtxycsayja.html

Go:   json.Marshal(obj)
来源：http://dali.xylfe.cn/Article/details/gtbgujccoa.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.c1oappe.top/Article/details/gtefupawwq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cashguo.top/Article/details/gtiodlrzxz.html

[K02] JSON 字符串转对象
来源：http://dali.sysykeji.top/Article/details/gtlckwccyf.html

Py:   json.loads(s)
来源：http://dali.yj20258.top/Article/details/gtmylzpgtf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zycfv.cn/Article/details/gtfjrrwrll.html

JS:   JSON.parse(s)
来源：http://dali.tian-w.cn/Article/details/gttejlodru.html

TS:   JSON.parse(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxurlyfuh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cqqwz.cn/Article/details/gtvlwrcnrm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shzxlz.cn/Article/details/gtsljvnskt.html

Ruby: JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gtfbsuypge.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hfpthk.cn/Article/details/gtrwjlcjvp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhongyouzk.top/Article/details/gtjbgwjooz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jianghu66.top/Article/details/gtkgyizvlr.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.chenlongwang.top/Article/details/gtnncrheru.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuanzhike.top/Article/details/gtjkknjdid.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuanzx.com/Article/details/gtunhlbiyw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.9152youxi.cn/Article/details/gtjzpubsqx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.iojbl.cn/Article/details/gtoaablsky.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cqqwz.cn/Article/details/gtzpqpotot.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yuanzhike.top/Article/details/gtpmcwvejn.html

[K04] 读取 JSON 文件
来源：http://dali.smart0.xyz/Article/details/gtkkxskevx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.c1oappe.top/Article/details/gthyqgtoly.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xuanzx.com/Article/details/gtolkfkadc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ivvv.top/Article/details/gtookkwgse.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xziqi.cn/Article/details/gtkdyrvzrb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yvedp.cn/Article/details/gttsiuazlb.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.haohaochexian.top/Article/details/gtzogsmqjt.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xinyue.icu/Article/details/gtwdbsmsfn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shangyingyoupin.top/Article/details/gtpvpdcnhg.html

[K05] 深拷贝对象
来源：http://dali.dianchejie.cn/Article/details/gtwicjxxtg.html

Py:   copy.deepcopy(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtqhalslrk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.feifeiyinyue.top/Article/details/gtvvtaieec.html

JS:   structuredClone(obj)
来源：http://dali.havefunace.top/Article/details/gteeskcaij.html

TS:   structuredClone(obj)
来源：http://dali.shzxlz.cn/Article/details/gtftqnnawc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zdqjudy.top/Article/details/gtuuonthin.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yuxming.cn/Article/details/gtxjedtikm.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yuxming.cn/Article/details/gtpxobbvtz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinqigufen.top/Article/details/gttdpqmvjm.html

[K06] 解析 URL 查询串
来源：http://dali.xylfe.cn/Article/details/gtnxaxjisr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gogol.net.cn/Article/details/gtidfkuyjp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jianghu66.top/Article/details/gtqjtldkdn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigfzy.top/Article/details/gtnuozcdvk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gzhubu.top/Article/details/gtfunmmnnl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.aizwys.cn/Article/details/gtwskpzery.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gthiotkjuq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ehwqpu.com/Article/details/gtycmbenni.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhongyouzk.top/Article/details/gtjvxybblw.html

[K07] 进制转换
来源：http://dali.zhixingplan.top/Article/details/gtmuydmsve.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.havefunace.top/Article/details/gtmgfrdzza.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.chenjidiqi.icu/Article/details/gthtmltivk.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gtuuizleds.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gttzqekcfr.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gtgwmiccqm.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sxryk.cn/Article/details/gttbuirate.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hammf.cn/Article/details/gtagkrrlwp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxilftups.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.daxiang520.top/Article/details/gtiiedgkyn.html

Py:   pickle.dumps(obj)
来源：http://dali.snrcjt.cn/Article/details/gtfjzlcaom.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.iojbl.cn/Article/details/gtqggagvll.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhixingplan.top/Article/details/gthyxwtjws.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xinyue.icu/Article/details/gtzanajigs.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.snrcjt.cn/Article/details/gtgehcncmj.html

Go:   encoding/gob
来源：http://dali.havefunace.top/Article/details/gtetmrjmsv.html

Ruby: Marshal.dump(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtrsgstozn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.c1oappe.top/Article/details/gtrzwjvvnu.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtzvihnncs.html

L. 网络请求
来源：http://dali.svipenyu.cn/Article/details/gtwdouuivv.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtyoeeawex.html

[L01] 发送 GET 请求
来源：http://dali.ppjwa.cn/Article/details/gtzvbirtqx.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.gaohongyu789.top/Article/details/gtqftgvjof.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.fengsongda.top/Article/details/gtkxdkpmrf.html

JS:   await fetch(url)
来源：http://dali.gogol.net.cn/Article/details/gteleyqxjh.html

TS:   await fetch(url)
来源：http://dali.kuanghao11.cn/Article/details/gtgkdyfgli.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jqgfzy.top/Article/details/gttpgtssuq.html

Go:   resp, err := http.Get(url)
来源：http://dali.sufxvd.cn/Article/details/gtncsxzsel.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.redwolf501.top/Article/details/gtpfazzate.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sufxvd.cn/Article/details/gtybmiggzi.html

[L02] 发送 POST JSON
来源：http://dali.yonumen.top/Article/details/gtvpatgwdm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yuanzhike.top/Article/details/gtklvcyfah.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ivvv.top/Article/details/gtqtqsubrx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtewnqrkcl.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.birdmap.top/Article/details/gtwrhjqmhw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinghuilouyu.cn/Article/details/gtjezutifa.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cdnleiting.top/Article/details/gtzmdkwetf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.smart0.xyz/Article/details/gtokdqtxxc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yj20258888.top/Article/details/gtdhfwxlma.html

[L03] 设置自定义请求头
来源：http://dali.jinqigufen.top/Article/details/gtopuipwkw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.c1oappe.top/Article/details/gtbbldquid.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.wangdashe.top/Article/details/gtqzqoehzs.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jiagoushi.top/Article/details/gtxsdgzctr.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuetiantiany.cn/Article/details/gtvznneifn.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.aizwys.cn/Article/details/gtyrztypbu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cucudq.cn/Article/details/gtuxrdjvjk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sweek.top/Article/details/gtqgyblmbt.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhongyouzk.top/Article/details/gtjukhqogl.html

[L04] 设置超时
来源：http://dali.daxiang520.top/Article/details/gtkkquydjr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.quarkkingdee.top/Article/details/gtzhtympxq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.havefunace.top/Article/details/gtlcwphbbz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtazqkeiqn.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbfpwnbhd.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yangfankeji.com/Article/details/gtcmollkqv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cashguo.top/Article/details/gtkybadaia.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.feifeiyinyue.top/Article/details/gtgipuxuhf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.redwolf501.top/Article/details/gtyscbwpis.html

[L05] 上传文件（multipart）
来源：http://dali.xuetiantiany.cn/Article/details/gtrwzxqnwk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.quarkkingdee.top/Article/details/gtvubbqdyf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zdqjudy.top/Article/details/gtwpzicfqh.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenzaomai.com/Article/details/gtwybhashr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cashguo.top/Article/details/gthejqvrjm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xziqi.cn/Article/details/gtfdyicfoq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zycfv.cn/Article/details/gtgrcumlgb.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.smart0.xyz/Article/details/gtmhlbaavu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gterqbrkfs.html

[L06] 解析响应为 JSON
来源：http://dali.yj20258888.top/Article/details/gtqxkahhvq.html

Py:   resp.json()
来源：http://dali.yanxiufei.cn/Article/details/gtrmyzejdo.html

PHP:  json_decode($body, true);
来源：http://dali.kuanghao11.cn/Article/details/gtwgindorn.html

JS:   await resp.json()
来源：http://dali.iojbl.cn/Article/details/gtghdupiow.html

TS:   await resp.json()
来源：http://dali.jqgfzy.top/Article/details/gtjrzarorc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cheryme.top/Article/details/gtbcktfbmp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.tianlin.xyz/Article/details/gtdomjimrh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yueranfly.top/Article/details/gtbllghiid.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.andypj.xyz/Article/details/gtgenodrcv.html

[L07] 处理 HTTP 状态码
来源：http://dali.yvedp.cn/Article/details/gtlbmpnryo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shuidangran.top/Article/details/gtqpuofdby.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yuxming.cn/Article/details/gtnnkbgrip.html

JS:   resp.ok;  resp.status
来源：http://dali.cdnleiting.top/Article/details/gtcofloddq.html

TS:   resp.ok;  resp.status
来源：http://dali.jlsjyb.cn/Article/details/gtovgrbdae.html

Java: resp.statusCode()
来源：http://dali.nwbrower.top/Article/details/gtdzgqajoi.html

Go:   resp.StatusCode
来源：http://dali.jinqigufen.top/Article/details/gthaotnqcu.html

Ruby: resp.code.to_i
来源：http://dali.yongpay.top/Article/details/gtnagcntrv.html

C#:   (int)resp.StatusCode
来源：http://dali.smart0.xyz/Article/details/gtvfnbsvvm.html

[L08] 并发请求多个地址
来源：http://dali.gaohongyu789.top/Article/details/gtztukepvo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.nanxinkj.top/Article/details/gtokeuzdsd.html

PHP:  curl_multi_init() 系列
来源：http://dali.nwbrower.top/Article/details/gtarjcuixy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yongpay.top/Article/details/gtqxdhtwzh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gtsmlxyvmk.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.chenlongwang.top/Article/details/gtdgainggf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhiwuduotai.top/Article/details/gtzwsxzbeq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinqigufen.top/Article/details/gtiklxyecy.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yanxiufei.cn/Article/details/gthnvjwbds.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtujtrzhto.html

M. 命令行 / 进程 / 环境
来源：http://dali.hammf.cn/Article/details/gtwsrjtylg.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtndvnvzfy.html

[M01] 读取命令行参数
来源：http://dali.aizwys.cn/Article/details/gtqoznuobs.html

Py:   sys.argv[1:]
来源：http://dali.svipenyu.cn/Article/details/gtxbfwvdsg.html

PHP:  $argv;  $argc;
来源：http://dali.yuxming.cn/Article/details/gtuusgjpuu.html

JS:   process.argv.slice(2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzopmlald.html

TS:   process.argv.slice(2)
来源：http://dali.aizwys.cn/Article/details/gtnkefwsuz.html

Java: args 数组（main 方法参数）
来源：http://dali.shzxlz.cn/Article/details/gtyqxvzxuc.html

Go:   os.Args[1:]
来源：http://dali.gotoacloud.top/Article/details/gtpbjrlabm.html

Ruby: ARGV
来源：http://dali.yj20258.top/Article/details/gtxadrehib.html

C#:   args 数组（Main 方法参数）
来源：http://dali.svipenyu.cn/Article/details/gtvpmqdyst.html

[M02] 读取环境变量
来源：http://dali.sweek.top/Article/details/gtnxhozqud.html

Py:   os.environ.get("HOME")
来源：http://dali.bjfxy.top/Article/details/gtpyzfknyf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.fzhhl.top/Article/details/gtszblvhad.html

JS:   process.env.HOME
来源：http://dali.gzhubu.top/Article/details/gtqdyjhamf.html

TS:   process.env.HOME
来源：http://dali.jianghu66.top/Article/details/gtkyqvbzfd.html

Java: System.getenv("HOME")
来源：http://dali.snrcjt.cn/Article/details/gtwzvtfweh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.316326.xyz/Article/details/gtuazoeyzb.html

Ruby: ENV["HOME"]
来源：http://dali.vqdsnc.cn/Article/details/gtoxumonky.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gtjfpnatff.html

[M03] 执行外部命令
来源：http://dali.wangdashe.top/Article/details/gtkufkflmj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hfpthk.cn/Article/details/gtpzasfcnm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.tianlin.xyz/Article/details/gtzrprngvl.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.aizwys.cn/Article/details/gtwymnwokm.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gogol.net.cn/Article/details/gtqcsryklh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cashguo.top/Article/details/gtgtfgelmk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.0kj1m.cn/Article/details/gthikvgmbh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.aizwys.cn/Article/details/gtwgqlmdpc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hnqzz.top/Article/details/gtiewqwfor.html

[M04] 获取当前工作目录
来源：http://dali.ivvv.top/Article/details/gtbmuicolu.html

Py:   os.getcwd()
来源：http://dali.gzhubu.top/Article/details/gtvqqsstyb.html

PHP:  getcwd();
来源：http://dali.sysykeji.top/Article/details/gtldhqiuar.html

JS:   process.cwd()
来源：http://dali.hammf.cn/Article/details/gtseoicgaj.html

TS:   process.cwd()
来源：http://dali.cheryme.top/Article/details/gtndmhfrzs.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ivvv.top/Article/details/gtmljfabyr.html

Go:   os.Getwd()
来源：http://dali.hywenlv.cn/Article/details/gtldlkuwvo.html

Ruby: Dir.pwd
来源：http://dali.yueranfly.top/Article/details/gtkugedcxe.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.0kj1m.cn/Article/details/gtmllszfxt.html

[M05] 设置退出码
来源：http://dali.mhx1999.top/Article/details/gtcgyarprd.html

Py:   sys.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gtcasnrwbz.html

PHP:  exit(1);
来源：http://dali.shzxlz.cn/Article/details/gtolosqqut.html

JS:   process.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtxglcamxz.html

TS:   process.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtdbxpxjnn.html

Java: System.exit(1)
来源：http://dali.cheryme.top/Article/details/gtozxvujkl.html

Go:   os.Exit(1)
来源：http://dali.cashguo.top/Article/details/gtmanwwkti.html

Ruby: exit 1
来源：http://dali.kuanghao11.cn/Article/details/gtgnugiral.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.chenjidiqi.icu/Article/details/gtxhtrtqkm.html

[M06] 向标准错误输出
来源：http://dali.chenjidiqi.icu/Article/details/gtwcgibskm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.iojbl.cn/Article/details/gtnnlqcqoy.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.snrcjt.cn/Article/details/gtuqdnqamg.html

JS:   console.error("err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtegfwcgbi.html

TS:   console.error("err")
来源：http://dali.gzhubu.top/Article/details/gtoicjewvq.html

Java: System.err.println("err")
来源：http://dali.bjfxy.top/Article/details/gtaiobxktj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yangfankeji.com/Article/details/gtnqsvhhup.html

Ruby: warn "err"
来源：http://dali.daxiang520.top/Article/details/gtbdasmrki.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sysykeji.top/Article/details/gtdjpaklya.html

[M07] 判断是否为主入口
来源：http://dali.jlsjyb.cn/Article/details/gtddadodly.html

Py:   if __name__ == "__main__":
来源：http://dali.shangyingyoupin.top/Article/details/gtpgdnmash.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.guannengcc.top/Article/details/gtzqsxbrsw.html

JS:   require.main === module
来源：http://dali.gzhubu.top/Article/details/gtpuubngqq.html

TS:   require.main === module
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpdajmxpw.html

Java: public static void main(String[] args)
来源：http://dali.zdqjudy.top/Article/details/gtwhpvfzik.html

Go:   func main()
来源：http://dali.vqdsnc.cn/Article/details/gtwsgjwrtd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.quarkkingdee.top/Article/details/gtjmjdolup.html

C#:   static void Main(string[] args)
来源：http://dali.ehwqpu.com/Article/details/gtphilgrbz.html

[M08] 获取系统与运行时信息
来源：http://dali.tanke756.top/Article/details/gtbwilqtbd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yonumen.top/Article/details/gtbmzxjivr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jqgufenzy.top/Article/details/gtcwfroxja.html

JS:   process.platform;  process.version
来源：http://dali.hongshengwenyu.top/Article/details/gtnnlcdvge.html

TS:   process.platform;  process.version
来源：http://dali.snrcjt.cn/Article/details/gtkuqxjdir.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.guannengcc.top/Article/details/gtapmteoap.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sxryk.cn/Article/details/gtliyzjgpl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.wangshuangyany.cn/Article/details/gtwhuxuhte.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hammf.cn/Article/details/gtxsvkjksb.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtettzlnhx.html

N. 数据结构与算法
来源：http://dali.9152youxi.cn/Article/details/gtnwqtqbtn.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtmokiumfn.html

[N01] 二分查找（有序数组）
来源：http://dali.yanxiufei.cn/Article/details/gtynicciny.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtynewttwb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zycfv.cn/Article/details/gthaobuwyv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhixingplan.top/Article/details/gtstezoqww.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.snrcjt.cn/Article/details/gtagzmtqbm.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtsumfjekt.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtlilztzrq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.fengsongda.top/Article/details/gtfadzsyie.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtdorwixrb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.pycfn.com/Article/details/gtqhyoranm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.smart0.xyz/Article/details/gtsmafwrdj.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hysaishi.cn/Article/details/gtycvnldat.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cucudq.cn/Article/details/gtdgzgxpgw.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.316326.xyz/Article/details/gtecrztgxl.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jqgufenzy.top/Article/details/gtsnodlkvv.html

Go:   slices.Sort(arr)
来源：http://dali.havefunace.top/Article/details/gtfjrsxxwn.html

Ruby: arr.sort
来源：http://dali.daxiang520.top/Article/details/gtfcivimna.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjthqnpok.html

[N03] 快速排序（分治示例）
来源：http://dali.redwolf501.top/Article/details/gtmlazhhyk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.tanke756.top/Article/details/gtywshmxgc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.guannengcc.top/Article/details/gtqsxzfcmm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tian-w.cn/Article/details/gtnzgvvrch.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yanxiufei.cn/Article/details/gtchwjnjzd.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.gogol.net.cn/Article/details/gtuqmvwuif.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.tanke756.top/Article/details/gtfniwihai.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cucudq.cn/Article/details/gtgcopldwt.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.aizwys.cn/Article/details/gtrpaoqjfy.html

[N04] 斐波那契数列
来源：http://dali.nwbrower.top/Article/details/gtpsadabmq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yonumen.top/Article/details/gtiyuozoqt.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yj20258.top/Article/details/gtqrymrdcm.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shzxlz.cn/Article/details/gtjpvtlvqt.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gtodaaumpm.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jqgufenzy.top/Article/details/gtgupxzzzb.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.aibaodan.cn/Article/details/gtgfbitrrx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gotoacloud.top/Article/details/gtmimxzclm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shzxlz.cn/Article/details/gtctalavky.html

[N05] 最大公约数
来源：http://dali.tanke756.top/Article/details/gtheveyefm.html

Py:   math.gcd(a, b)
来源：http://dali.xuetiantiany.cn/Article/details/gtvfrycwia.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.kuanghao11.cn/Article/details/gtcgjtyxrf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.andypj.xyz/Article/details/gtcgfwvmfu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hammf.cn/Article/details/gtkmyfornx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhiwuduotai.top/Article/details/gtockygzie.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ydzc1.top/Article/details/gtswwssjgf.html

Ruby: a.gcd(b)
来源：http://dali.yonumen.top/Article/details/gtpbstfagx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jqgufenzy.top/Article/details/gthrsopzte.html

[N06] 判断回文字符串
来源：http://dali.yj20258.top/Article/details/gtoolxsgpu.html

Py:   s == s[::-1]
来源：http://dali.jianghu66.top/Article/details/gtfbmvssow.html

PHP:  $s === strrev($s);
来源：http://dali.yj20258.top/Article/details/gtzzfudtng.html

JS:   s === [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gtjubgboke.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yj20258888.top/Article/details/gtmfsdefdn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sufxvd.cn/Article/details/gtykqzzwpb.html

Go:   // 双指针从两端比较
来源：http://dali.sweek.top/Article/details/gtapcbregf.html


<!-- 参考信息 -->