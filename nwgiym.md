代发 wailian999

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xuanzx.com/Article/details/gtfeipogmf.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jiagoushi.top/Article/details/gtjutddkwt.html

[J09] 时区处理
来源：http://dali.dianchejie.cn/Article/details/gtcqsdlwgf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nanxuanxn.top/Article/details/gtoweqitkl.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.vqdsnc.cn/Article/details/gtmjpacqvd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenjidiqi.icu/Article/details/gtcfhwjmsc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fzhhl.top/Article/details/gtwrrpmjjg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yj202588.top/Article/details/gtruesjxes.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhoulong.xyz/Article/details/gtqtxhrcyb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yongpay.top/Article/details/gthfcabbbp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.snrcjt.cn/Article/details/gtjcdllkkd.html

[J10] 取今天 / 本月第一天
来源：http://dali.yueranfly.top/Article/details/gticowbbsu.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinqigufen.top/Article/details/gtwkmrawxd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nanxuanxn.top/Article/details/gtzqesdvry.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.guannengcc.top/Article/details/gtactnlpag.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhengqikj.top/Article/details/gtvwaixfpe.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.c1oappe.top/Article/details/gtultesjnh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jqgfzy.top/Article/details/gtghrxjsqs.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhengqikj.top/Article/details/gtagepmmje.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hfpthk.cn/Article/details/gtcwmyhkrm.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtisnavfmw.html

K. JSON 与序列化
来源：http://dali.jinyuanbaomall.cn/Article/details/gthxtkhgus.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtbijyqhxe.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhixingplan.top/Article/details/gtsloqjavg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sweek.top/Article/details/gtbzqyfhda.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.dianchejie.cn/Article/details/gtgzchqjac.html

JS:   JSON.stringify(obj)
来源：http://dali.ehwqpu.com/Article/details/gteqorqneo.html

TS:   JSON.stringify(obj)
来源：http://dali.xuanzx.com/Article/details/gtjltcrvcj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yj20258.top/Article/details/gthbbuefpc.html

Go:   json.Marshal(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtptqecqay.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.vqdsnc.cn/Article/details/gtvzjpmdjd.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gotoacloud.top/Article/details/gtxusdcskz.html

[K02] JSON 字符串转对象
来源：http://dali.cqqwz.cn/Article/details/gtbfpaxoco.html

Py:   json.loads(s)
来源：http://dali.zhijiandao.cn/Article/details/gtbmiqvngv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tian-w.cn/Article/details/gttmisnnta.html

JS:   JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gttvdtsoan.html

TS:   JSON.parse(s)
来源：http://dali.dianchejie.cn/Article/details/gtbhbteouk.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yangfankeji.com/Article/details/gtbxipwyyh.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.wangshuangyany.cn/Article/details/gtuoaneuwa.html

Ruby: JSON.parse(s)
来源：http://dali.fengsongda.top/Article/details/gtnmcbxdax.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtmcxeknit.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jiagoushi.top/Article/details/gtjksvlymb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinqigufen.top/Article/details/gtfdttzoes.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.mhx1999.top/Article/details/gtwgmnyxlj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hammf.cn/Article/details/gtcykrlikb.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.haohaochexian.top/Article/details/gtrszimacb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.aibaodan.cn/Article/details/gtzkyjjvxf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shangyingyoupin.top/Article/details/gtmkksecde.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gthntfxrcr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yangfankeji.com/Article/details/gtoclgvzoh.html

[K04] 读取 JSON 文件
来源：http://dali.hnqzz.top/Article/details/gtlpnmgnzz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.dianchejie.cn/Article/details/gtlsrgmavb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zycfv.cn/Article/details/gtejwihdhm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guannengcc.top/Article/details/gtaoivaxpk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangdashe.top/Article/details/gtylmdjntd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.meibo888.top/Article/details/gtvmhotzjt.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.fengsongda.top/Article/details/gtxynivkvu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhiwuduotai.top/Article/details/gtanigzifn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.chenjidiqi.icu/Article/details/gtksapussq.html

[K05] 深拷贝对象
来源：http://dali.yangfankeji.com/Article/details/gtmgddaffg.html

Py:   copy.deepcopy(obj)
来源：http://dali.9152youxi.cn/Article/details/gtakloqduw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.mhx1999.top/Article/details/gtjktkdday.html

JS:   structuredClone(obj)
来源：http://dali.hfpthk.cn/Article/details/gtrrcihotp.html

TS:   structuredClone(obj)
来源：http://dali.yj20258.top/Article/details/gtkwjnxexr.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.0kj1m.cn/Article/details/gtmbrwbehs.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.nwbrower.top/Article/details/gtlhiruvjm.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cheryme.top/Article/details/gtcexomafi.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yueranfly.top/Article/details/gtshjmlhdq.html

[K06] 解析 URL 查询串
来源：http://dali.redwolf501.top/Article/details/gtifspbqmm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cucudq.cn/Article/details/gtucngwmyi.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.aizwys.cn/Article/details/gtkqyyhkzd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guannengcc.top/Article/details/gtiwyazdnn.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenzaomai.com/Article/details/gtqfiibkrf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jqgfzy.top/Article/details/gtkqogpcgm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hnxiangtu.top/Article/details/gttbcrsjpy.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsgueyevo.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.mhx1999.top/Article/details/gtbuwhjpps.html

[K07] 进制转换
来源：http://dali.quarkkingdee.top/Article/details/gtzihvmqrt.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gtikftogaj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shzxlz.cn/Article/details/gtfndcqdpm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gthzguneqf.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtpasklgwq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtqnppbwpo.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhiwuduotai.top/Article/details/gtaorzmroz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.snrcjt.cn/Article/details/gtijpcqckp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gtohonigko.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.tanke756.top/Article/details/gthrqwxzid.html

Py:   pickle.dumps(obj)
来源：http://dali.hammf.cn/Article/details/gtrrfurpsv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.9152youxi.cn/Article/details/gtjcetduet.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shangyingyoupin.top/Article/details/gtpujojdzv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jiagoushi.top/Article/details/gtfkaqcsbz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrimascwc.html

Go:   encoding/gob
来源：http://dali.snrcjt.cn/Article/details/gtwgwickge.html

Ruby: Marshal.dump(obj)
来源：http://dali.jqgfzy.top/Article/details/gthokooveb.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gtzcnbhtop.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gthtyetrxu.html

L. 网络请求
来源：http://dali.zhongyouzk.top/Article/details/gtmyvaunwq.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtqgsyklfj.html

[L01] 发送 GET 请求
来源：http://dali.yj202588.top/Article/details/gtdgymrkye.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinghuilouyu.cn/Article/details/gtnqrwwhfs.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhongyouzk.top/Article/details/gthhbujqbx.html

JS:   await fetch(url)
来源：http://dali.hywenlv.cn/Article/details/gtuknioijv.html

TS:   await fetch(url)
来源：http://dali.mhx1999.top/Article/details/gtftuykiyb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yangfankeji.com/Article/details/gtcdrefklb.html

Go:   resp, err := http.Get(url)
来源：http://dali.ehwqpu.com/Article/details/gtrejvkwpf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shuidangran.top/Article/details/gthlfsihtl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yongpay.top/Article/details/gtnsdmajot.html

[L02] 发送 POST JSON
来源：http://dali.ehwqpu.com/Article/details/gtpfwewyjo.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhiwuduotai.top/Article/details/gtoqmdetuj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.wangdashe.top/Article/details/gtjghztelk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xziqi.cn/Article/details/gtewaskqgj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tian-w.cn/Article/details/gtupplconh.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.tianlin.xyz/Article/details/gttfoxljmy.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.mhx1999.top/Article/details/gtyrudroaq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hongshengwenyu.top/Article/details/gtdmnkocws.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xinyue.icu/Article/details/gtixcojenu.html

[L03] 设置自定义请求头
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwpsbdjsi.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtupywwbbs.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.redwolf501.top/Article/details/gtkxwenxbt.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxuanxn.top/Article/details/gtgfdtsgeg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pycfn.com/Article/details/gtkqxjbyub.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hongshengwenyu.top/Article/details/gtrrtzfpnq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ivvv.top/Article/details/gtwucuxmbv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jianghu66.top/Article/details/gtkwzpirpo.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.nanxuanxn.top/Article/details/gtlakanhds.html

[L04] 设置超时
来源：http://dali.c1oappe.top/Article/details/gtxsznzhpl.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xuetiantiany.cn/Article/details/gtmkybyofb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hnxiangtu.top/Article/details/gtoajhzuhv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigfzy.top/Article/details/gtxfaexhvh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.guannengcc.top/Article/details/gtxcmqryev.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cqqwz.cn/Article/details/gtjxhekfxx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhongyouzk.top/Article/details/gtejjrndfc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yanxiufei.cn/Article/details/gtzlxnykxr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.fengsongda.top/Article/details/gtzacqgwyh.html

[L05] 上传文件（multipart）
来源：http://dali.ybcxt.top/Article/details/gtqwgeyhim.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cucudq.cn/Article/details/gtctahfrtx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yuanzhike.top/Article/details/gtdpvzeolh.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gogol.net.cn/Article/details/gtiudgeyss.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jiagoushi.top/Article/details/gtryqtmoca.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.nanxinkj.top/Article/details/gtahzpmidp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sxryk.cn/Article/details/gtmetblhbn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhongyouzk.top/Article/details/gtjvpdkqmj.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtdmiiifvj.html

[L06] 解析响应为 JSON
来源：http://dali.xuanzx.com/Article/details/gtfivgzphv.html

Py:   resp.json()
来源：http://dali.svipenyu.cn/Article/details/gtbfjvkkxj.html

PHP:  json_decode($body, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwexppcdp.html

JS:   await resp.json()
来源：http://dali.meibo888.top/Article/details/gtqwkkwrxl.html

TS:   await resp.json()
来源：http://dali.cashguo.top/Article/details/gtisatwknm.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.nanxinkj.top/Article/details/gtojuiqeoh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sufxvd.cn/Article/details/gtkrwznurn.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yongpay.top/Article/details/gtmvhwezro.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.dashuyun.cn/Article/details/gtmsraxdqy.html

[L07] 处理 HTTP 状态码
来源：http://dali.hammf.cn/Article/details/gtezfzrsrm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jlsjyb.cn/Article/details/gthhjxtdsa.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yonumen.top/Article/details/gtugxcjuyh.html

JS:   resp.ok;  resp.status
来源：http://dali.havefunace.top/Article/details/gtovzrthuk.html

TS:   resp.ok;  resp.status
来源：http://dali.tanke756.top/Article/details/gtahrdfoup.html

Java: resp.statusCode()
来源：http://dali.hnxiangtu.top/Article/details/gtiiktnfhx.html

Go:   resp.StatusCode
来源：http://dali.guannengcc.top/Article/details/gtpdbqgcoi.html

Ruby: resp.code.to_i
来源：http://dali.sufxvd.cn/Article/details/gtshedolxk.html

C#:   (int)resp.StatusCode
来源：http://dali.ehwqpu.com/Article/details/gtglpsietu.html

[L08] 并发请求多个地址
来源：http://dali.yj202588.top/Article/details/gtqwjcisrd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.feifeiyinyue.top/Article/details/gtzbaylusx.html

PHP:  curl_multi_init() 系列
来源：http://dali.iojbl.cn/Article/details/gthopkicov.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daxiang520.top/Article/details/gthykiuzax.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhengqikj.top/Article/details/gtsoosbvql.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cashguo.top/Article/details/gtagyuvyhk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.mhx1999.top/Article/details/gtvtrufkac.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.meibo888.top/Article/details/gtcycpvsvu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zdqjudy.top/Article/details/gtbsjphvyh.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtqmyrdamu.html

M. 命令行 / 进程 / 环境
来源：http://dali.xinyue.icu/Article/details/gtxgbqmaeq.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtddhwggdi.html

[M01] 读取命令行参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxxqwmgxo.html

Py:   sys.argv[1:]
来源：http://dali.9152youxi.cn/Article/details/gtrspsjiru.html

PHP:  $argv;  $argc;
来源：http://dali.ehwqpu.com/Article/details/gtkpmxlfye.html

JS:   process.argv.slice(2)
来源：http://dali.gzhubu.top/Article/details/gtpbuzgaqo.html

TS:   process.argv.slice(2)
来源：http://dali.xziqi.cn/Article/details/gtvatmysnu.html

Java: args 数组（main 方法参数）
来源：http://dali.cdnleiting.top/Article/details/gtakzetrpb.html

Go:   os.Args[1:]
来源：http://dali.chenjidiqi.icu/Article/details/gtwdqwpcix.html

Ruby: ARGV
来源：http://dali.chenjidiqi.icu/Article/details/gtdutpvuad.html

C#:   args 数组（Main 方法参数）
来源：http://dali.aizwys.cn/Article/details/gtqjhyhwyy.html

[M02] 读取环境变量
来源：http://dali.yueranfly.top/Article/details/gtwsuqmiqx.html

Py:   os.environ.get("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gtfanfpjai.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj202588.top/Article/details/gtesqkhuxn.html

JS:   process.env.HOME
来源：http://dali.meibo888.top/Article/details/gtezgpzbfo.html

TS:   process.env.HOME
来源：http://dali.aibaodan.cn/Article/details/gtmvpjvnqh.html

Java: System.getenv("HOME")
来源：http://dali.ivvv.top/Article/details/gtsxahwaiw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xylfe.cn/Article/details/gtzdirrziy.html

Ruby: ENV["HOME"]
来源：http://dali.sufxvd.cn/Article/details/gtnqtdlkzd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jianghu66.top/Article/details/gtkbnkzcbe.html

[M03] 执行外部命令
来源：http://dali.chenzaomai.com/Article/details/gtiqdaolko.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.wangshuangyany.cn/Article/details/gtujspqujr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhoulong.xyz/Article/details/gtnetdibkx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.mhx1999.top/Article/details/gtyfuvssru.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shuidangran.top/Article/details/gtnwqacsvr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkquxmtae.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtczgbqkpd.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.chenlongwang.top/Article/details/gtwsfsstrm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.tian-w.cn/Article/details/gtenkozvrd.html

[M04] 获取当前工作目录
来源：http://dali.tian-w.cn/Article/details/gtfumyoaoa.html

Py:   os.getcwd()
来源：http://dali.ppjwa.cn/Article/details/gthqnjshhc.html

PHP:  getcwd();
来源：http://dali.shuidangran.top/Article/details/gtizdegcdu.html

JS:   process.cwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrvoweeaf.html

TS:   process.cwd()
来源：http://dali.shangyingyoupin.top/Article/details/gtjcxttquy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yonumen.top/Article/details/gtoimdmkmz.html

Go:   os.Getwd()
来源：http://dali.ybcxt.top/Article/details/gtbhygbbjv.html

Ruby: Dir.pwd
来源：http://dali.iojbl.cn/Article/details/gtfefvxbve.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hfpthk.cn/Article/details/gtdfvjyngz.html

[M05] 设置退出码
来源：http://dali.wangdashe.top/Article/details/gtnkexrdfa.html

Py:   sys.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gtwxxtykid.html

PHP:  exit(1);
来源：http://dali.yangfankeji.com/Article/details/gtkogxbijc.html

JS:   process.exit(1)
来源：http://dali.meibo888.top/Article/details/gtvosvedas.html

TS:   process.exit(1)
来源：http://dali.fzhhl.top/Article/details/gtqzfxaswy.html

Java: System.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gtbixkalvg.html

Go:   os.Exit(1)
来源：http://dali.cqqwz.cn/Article/details/gtzmqbeefd.html

Ruby: exit 1
来源：http://dali.jlsjyb.cn/Article/details/gtpnrzozxr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cdnleiting.top/Article/details/gttlptxgnb.html

[M06] 向标准错误输出
来源：http://dali.zycfv.cn/Article/details/gttiwolvwx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj20258888.top/Article/details/gtkgwvaaeq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hnqzz.top/Article/details/gtqvdwpgql.html

JS:   console.error("err")
来源：http://dali.tian-w.cn/Article/details/gtzcfbgerc.html

TS:   console.error("err")
来源：http://dali.tian-w.cn/Article/details/gtdwyfgvnk.html

Java: System.err.println("err")
来源：http://dali.yj20258.top/Article/details/gtbooescno.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xinyue.icu/Article/details/gtzrycoarx.html

Ruby: warn "err"
来源：http://dali.daria6918.cn/Article/details/gticcojxho.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jiagoushi.top/Article/details/gtyalicyut.html

[M07] 判断是否为主入口
来源：http://dali.9152youxi.cn/Article/details/gtseesdtit.html

Py:   if __name__ == "__main__":
来源：http://dali.guannengcc.top/Article/details/gtoecpynhl.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hnxiangtu.top/Article/details/gtnsvyunty.html

JS:   require.main === module
来源：http://dali.hfpthk.cn/Article/details/gtadciaocc.html

TS:   require.main === module
来源：http://dali.yvedp.cn/Article/details/gtfxrtrtqa.html

Java: public static void main(String[] args)
来源：http://dali.tianlin.xyz/Article/details/gtvkzclcdd.html

Go:   func main()
来源：http://dali.yongpay.top/Article/details/gtndgkbrlr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gtqvqwwbmz.html

C#:   static void Main(string[] args)
来源：http://dali.chenjidiqi.icu/Article/details/gtezveidll.html

[M08] 获取系统与运行时信息
来源：http://dali.ivvv.top/Article/details/gtwvvshcfc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cqqwz.cn/Article/details/gtxiwghcsj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.daria6918.cn/Article/details/gtqdtscmdu.html

JS:   process.platform;  process.version
来源：http://dali.tanke756.top/Article/details/gtuozngetk.html

TS:   process.platform;  process.version
来源：http://dali.gotoacloud.top/Article/details/gtdbaldcxk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zycfv.cn/Article/details/gthmkwpkag.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.haohaochexian.top/Article/details/gtvqgllgwz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.pycfn.com/Article/details/gtvdwmmlqb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ppjwa.cn/Article/details/gtavgqdqmd.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtdvrspxcb.html

N. 数据结构与算法
来源：http://dali.snrcjt.cn/Article/details/gtsooebhzr.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtvfoesepr.html

[N01] 二分查找（有序数组）
来源：http://dali.cheryme.top/Article/details/gtqtjvtlzv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yj202588.top/Article/details/gtqeabcmco.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cucudq.cn/Article/details/gttslywild.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigufen.top/Article/details/gtjbdnbkra.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tianlin.xyz/Article/details/gtwjjekymc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gtzulechnp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.fengsongda.top/Article/details/gtarnxioxd.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sxryk.cn/Article/details/gtmbqhfhpn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gthciijfgj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shangyingyoupin.top/Article/details/gtkqwjtqrl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.mhx1999.top/Article/details/gtbetbyjqe.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.tanke756.top/Article/details/gtrftwnoqe.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yonumen.top/Article/details/gtvsxytnwf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tianlin.xyz/Article/details/gtzpnkeiyh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jianghu66.top/Article/details/gtzebsmtir.html

Go:   slices.Sort(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtnyqdhqom.html

Ruby: arr.sort
来源：http://dali.shzxlz.cn/Article/details/gtvgglfwrn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.iojbl.cn/Article/details/gtjjigirca.html

[N03] 快速排序（分治示例）
来源：http://dali.shangyingyoupin.top/Article/details/gtpticbaop.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.fengsongda.top/Article/details/gtmswzjppc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.9152youxi.cn/Article/details/gturrbvzze.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ybcxt.top/Article/details/gtjvsspuiq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxinkj.top/Article/details/gtnrqpcbth.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.haohaochexian.top/Article/details/gtcyjygxfu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.dashuyun.cn/Article/details/gtdboliaaw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yvedp.cn/Article/details/gtxsbtdynk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hfpthk.cn/Article/details/gtgafdeybf.html

[N04] 斐波那契数列
来源：http://dali.cucudq.cn/Article/details/gtnowxdhjs.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zdqjudy.top/Article/details/gtgaybezlf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.bjfxy.top/Article/details/gtskvsgguv.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtrvslehso.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yueranfly.top/Article/details/gtluipzpvs.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.feifeiyinyue.top/Article/details/gtacupoyqx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hywenlv.cn/Article/details/gtqyomrqkq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yonumen.top/Article/details/gtrajvyagf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.daria6918.cn/Article/details/gtivgjoeqi.html

[N05] 最大公约数
来源：http://dali.nanxinkj.top/Article/details/gtyboeyopn.html

Py:   math.gcd(a, b)
来源：http://dali.cheryme.top/Article/details/gtvqbdnbhe.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmxvannem.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenjidiqi.icu/Article/details/gtxaclvlom.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hongshengwenyu.top/Article/details/gtabsdwkkm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jlsjyb.cn/Article/details/gtrxqnynjq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yongpay.top/Article/details/gtqnccnkbe.html

Ruby: a.gcd(b)
来源：http://dali.gaohongyu789.top/Article/details/gtvpjxwdbu.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhengqikj.top/Article/details/gtoewrlwfk.html

[N06] 判断回文字符串
来源：http://dali.chenlongwang.top/Article/details/gtcrdqrkhg.html

Py:   s == s[::-1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtskexbnow.html

PHP:  $s === strrev($s);
来源：http://dali.jyoumei.cn/Article/details/gtvmljwgfp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gtzaeiidzn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gtvnbqazxi.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhiwuduotai.top/Article/details/gtgwtlvjxf.html

Go:   // 双指针从两端比较
来源：http://dali.sweek.top/Article/details/gtqrsnxtij.html


<!-- 参考信息 -->