代发 wailian999

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shzxlz.cn/Article/details/gtozoopcks.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.fengsongda.top/Article/details/gtdmmpwtbn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zycfv.cn/Article/details/gtntvwmroj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.guannengcc.top/Article/details/gtlfyradfp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ppjwa.cn/Article/details/gtmsuwidtr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhixingplan.top/Article/details/gtpphykunk.html

[J09] 时区处理
来源：http://dali.shanyushiyangtech.top/Article/details/gtvkjdpvzm.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cqqwz.cn/Article/details/gtenpdespw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hfpthk.cn/Article/details/gtvkdodsgu.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gzhubu.top/Article/details/gtyqqdjesz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.redwolf501.top/Article/details/gtiposvkcn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.chenzaomai.com/Article/details/gtnskhbuge.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.aizwys.cn/Article/details/gtcpvrkkfa.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhoulong.xyz/Article/details/gtjwfpwrue.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.pengpengdd.cyou/Article/details/gtunzvgmrk.html

[J10] 取今天 / 本月第一天
来源：http://dali.gaohongyu789.top/Article/details/gtpdkiftkx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cdnleiting.top/Article/details/gtxpvhluqa.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nwbrower.top/Article/details/gtoahnlzkj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.kuanghao11.cn/Article/details/gtfjsdzjdb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtugufxntl.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ivvv.top/Article/details/gtvthxpusm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shangyingyoupin.top/Article/details/gthlubnsmn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sxryk.cn/Article/details/gtzzhgmggy.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sxryk.cn/Article/details/gthnnkdbye.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtuzvkbnwi.html

K. JSON 与序列化
来源：http://dali.ybcxt.top/Article/details/gtdmqlkkbb.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtbzluwgnc.html

[K01] 对象转 JSON 字符串
来源：http://dali.yueranfly.top/Article/details/gtnobxqjzk.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gzhubu.top/Article/details/gtiotyvsbt.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jyoumei.cn/Article/details/gtlxoccohd.html

JS:   JSON.stringify(obj)
来源：http://dali.hywenlv.cn/Article/details/gtrcbeemqj.html

TS:   JSON.stringify(obj)
来源：http://dali.aibaodan.cn/Article/details/gtuehiegqq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xylfe.cn/Article/details/gtxvithokz.html

Go:   json.Marshal(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtgfeojgsv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.pengpengdd.cyou/Article/details/gtftbxdbyf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tanke756.top/Article/details/gtgjxzitcs.html

[K02] JSON 字符串转对象
来源：http://dali.ybcxt.top/Article/details/gtsypeyxda.html

Py:   json.loads(s)
来源：http://dali.havefunace.top/Article/details/gtpbtxzioc.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gzhubu.top/Article/details/gtieypyhil.html

JS:   JSON.parse(s)
来源：http://dali.xziqi.cn/Article/details/gtaqwrxvgu.html

TS:   JSON.parse(s)
来源：http://dali.0kj1m.cn/Article/details/gtfuftzazb.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gtwqyzmtpr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sweek.top/Article/details/gtczzhddab.html

Ruby: JSON.parse(s)
来源：http://dali.birdmap.top/Article/details/gtjixsagxq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zycfv.cn/Article/details/gtqmopghqf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.kuanghao11.cn/Article/details/gtjwvveeaw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xuetiantiany.cn/Article/details/gtjnzualak.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zdqjudy.top/Article/details/gtglkxdtiq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shuidangran.top/Article/details/gtubsflbiv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cashguo.top/Article/details/gtfgrdjtwl.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yvedp.cn/Article/details/gtkzkukeec.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.aizwys.cn/Article/details/gtmujiewlt.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yangfankeji.com/Article/details/gtmcwoclzt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj20258888.top/Article/details/gtozozyjtu.html

[K04] 读取 JSON 文件
来源：http://dali.xinyue.icu/Article/details/gtknlkhohx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.wangdashe.top/Article/details/gtmtmwagoi.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xuanzx.com/Article/details/gtqwqvboee.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pycfn.com/Article/details/gtrzxxdfgq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj202588.top/Article/details/gtwpnswzej.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yuxming.cn/Article/details/gttdekwodj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shuidangran.top/Article/details/gtdyhiuicm.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sxryk.cn/Article/details/gtolqdlmqp.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.0kj1m.cn/Article/details/gtzfcrwmbh.html

[K05] 深拷贝对象
来源：http://dali.zhixingplan.top/Article/details/gtdhyjmjpm.html

Py:   copy.deepcopy(obj)
来源：http://dali.zycfv.cn/Article/details/gtpfnbnavd.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xuanzx.com/Article/details/gthdoxshep.html

JS:   structuredClone(obj)
来源：http://dali.guannengcc.top/Article/details/gtxaidtvhe.html

TS:   structuredClone(obj)
来源：http://dali.jinqigfzy.top/Article/details/gttypnjfiv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sxryk.cn/Article/details/gtxukwjhov.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtntazxtjy.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbrlgedmn.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yangfankeji.com/Article/details/gtscaeqnfe.html

[K06] 解析 URL 查询串
来源：http://dali.xziqi.cn/Article/details/gtbtjwonfn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.wangdashe.top/Article/details/gtbenbfwta.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hongshengwenyu.top/Article/details/gtivshobvz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.andypj.xyz/Article/details/gttqdlykox.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cashguo.top/Article/details/gttxqdvtaw.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.aibaodan.cn/Article/details/gtqlfrdfja.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gttjqxdozn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gtokhnkwqt.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.sysykeji.top/Article/details/gtiyzktrde.html

[K07] 进制转换
来源：http://dali.yonumen.top/Article/details/gtcpfjqxfa.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gtkqeniclg.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtftapnjgk.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gttrabsmtd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtkriukjwd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gtzqpmbrym.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cucudq.cn/Article/details/gtlnwmmvow.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.andypj.xyz/Article/details/gtjrrcxdsl.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gtwcneikvk.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.aibaodan.cn/Article/details/gttbborhvb.html

Py:   pickle.dumps(obj)
来源：http://dali.ydzc1.top/Article/details/gtkodtmacl.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cqqwz.cn/Article/details/gtgultrfhw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ydzc1.top/Article/details/gtpahrlwff.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hongshengwenyu.top/Article/details/gtfsfgrvxl.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shuidangran.top/Article/details/gtzezoqrkp.html

Go:   encoding/gob
来源：http://dali.jlsjyb.cn/Article/details/gtyelynedi.html

Ruby: Marshal.dump(obj)
来源：http://dali.tian-w.cn/Article/details/gtofupitao.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.tanke756.top/Article/details/gtgwgmkljd.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtpsgamgwm.html

L. 网络请求
来源：http://dali.yonumen.top/Article/details/gtqjgkvrmm.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtfpvtvlwf.html

[L01] 发送 GET 请求
来源：http://dali.andypj.xyz/Article/details/gtxcvuarks.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shangyingyoupin.top/Article/details/gtabfhficp.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinqigufen.top/Article/details/gtweohiean.html

JS:   await fetch(url)
来源：http://dali.feifeiyinyue.top/Article/details/gtzkvmevhg.html

TS:   await fetch(url)
来源：http://dali.hongshengwenyu.top/Article/details/gtrlsnfbdw.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhongyouzk.top/Article/details/gtpjaxyqhy.html

Go:   resp, err := http.Get(url)
来源：http://dali.pycfn.com/Article/details/gthszoldxz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xziqi.cn/Article/details/gtfmbscbxk.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.bjfxy.top/Article/details/gtbvclqkdd.html

[L02] 发送 POST JSON
来源：http://dali.yvedp.cn/Article/details/gtdhfeojyp.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.mhx1999.top/Article/details/gtazsgzsgn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ivvv.top/Article/details/gtulbelhim.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yueranfly.top/Article/details/gtdsuvvknw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ydzc1.top/Article/details/gttvqamwde.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shzxlz.cn/Article/details/gtqwrgnono.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sweek.top/Article/details/gthafifxsw.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ppjwa.cn/Article/details/gtilqulpib.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.guowangkeji.top/Article/details/gtzgipomax.html

[L03] 设置自定义请求头
来源：http://dali.xuetiantiany.cn/Article/details/gtlpigwoso.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xuanzx.com/Article/details/gtemnelfnw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.birdmap.top/Article/details/gtdtaolygj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.vqdsnc.cn/Article/details/gtkotbxnnp.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnxiangtu.top/Article/details/gtyzhtwnct.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yangfankeji.com/Article/details/gtpuraqdun.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gogol.net.cn/Article/details/gtsyanpdwn.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.vqdsnc.cn/Article/details/gtybprlwsi.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.tian-w.cn/Article/details/gtkkrnfqrf.html

[L04] 设置超时
来源：http://dali.svipenyu.cn/Article/details/gtqdvnondu.html

Py:   requests.get(url, timeout=5)
来源：http://dali.chenlongwang.top/Article/details/gthdqcwxtx.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.smart0.xyz/Article/details/gtinfrdyqv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xylfe.cn/Article/details/gtoiqhasbf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoijjcmik.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhixingplan.top/Article/details/gtllldikpr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.daria6918.cn/Article/details/gthrklvtmn.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hfpthk.cn/Article/details/gtgypiftwr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gzhubu.top/Article/details/gtqfhxpzcg.html

[L05] 上传文件（multipart）
来源：http://dali.ppjwa.cn/Article/details/gtakanggmp.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.dianchejie.cn/Article/details/gtojbhonsa.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jqgufenzy.top/Article/details/gtrikyobjj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hongshengwenyu.top/Article/details/gtzoicfhnf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxinkj.top/Article/details/gtwkuqpyvt.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.0kj1m.cn/Article/details/gtlxdjmist.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.wangshuangyany.cn/Article/details/gtpadblswk.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shanyushiyangkeji.top/Article/details/gtagitkzge.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcmftxalj.html

[L06] 解析响应为 JSON
来源：http://dali.quarkkingdee.top/Article/details/gtznzpxybv.html

Py:   resp.json()
来源：http://dali.hysaishi.cn/Article/details/gtxhhsaszu.html

PHP:  json_decode($body, true);
来源：http://dali.yongpay.top/Article/details/gtvrpmikkw.html

JS:   await resp.json()
来源：http://dali.shangyingyoupin.top/Article/details/gtemywhnoy.html

TS:   await resp.json()
来源：http://dali.jqgfzy.top/Article/details/gtruridweh.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jyoumei.cn/Article/details/gtxaxinhsi.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xinyue.icu/Article/details/gtnvhhkpru.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhixingplan.top/Article/details/gtoytpklbc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yuxming.cn/Article/details/gthfpwqhdt.html

[L07] 处理 HTTP 状态码
来源：http://dali.cashguo.top/Article/details/gtsuhbqfso.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tian-w.cn/Article/details/gtcnupxpmm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenlongwang.top/Article/details/gtoiwaszow.html

JS:   resp.ok;  resp.status
来源：http://dali.sxryk.cn/Article/details/gtxferqisg.html

TS:   resp.ok;  resp.status
来源：http://dali.xziqi.cn/Article/details/gtoznglqma.html

Java: resp.statusCode()
来源：http://dali.zhixingplan.top/Article/details/gtfjrittqe.html

Go:   resp.StatusCode
来源：http://dali.gaohongyu789.top/Article/details/gtdzegjvnz.html

Ruby: resp.code.to_i
来源：http://dali.jinghuilouyu.cn/Article/details/gtsdkfrpvz.html

C#:   (int)resp.StatusCode
来源：http://dali.cashguo.top/Article/details/gtueniyogn.html

[L08] 并发请求多个地址
来源：http://dali.jyoumei.cn/Article/details/gtecfbzslz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cqqwz.cn/Article/details/gtbgaxfpik.html

PHP:  curl_multi_init() 系列
来源：http://dali.snrcjt.cn/Article/details/gtzvznprgw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tianlin.xyz/Article/details/gtjctrsfjo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tanke756.top/Article/details/gtnxaggefn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.birdmap.top/Article/details/gtfzjjkztt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yj20258888.top/Article/details/gtmdvlasoq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sweek.top/Article/details/gtygsyxbci.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.feifeiyinyue.top/Article/details/gtigyxfjbu.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtihcruzrn.html

M. 命令行 / 进程 / 环境
来源：http://dali.shangyingyoupin.top/Article/details/gtwonwkrzb.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtffdglhch.html

[M01] 读取命令行参数
来源：http://dali.yj20258888.top/Article/details/gtytfioqpi.html

Py:   sys.argv[1:]
来源：http://dali.jinqigfzy.top/Article/details/gtqjiwkryx.html

PHP:  $argv;  $argc;
来源：http://dali.nanxinkj.top/Article/details/gtuowelask.html

JS:   process.argv.slice(2)
来源：http://dali.9152youxi.cn/Article/details/gtphjdzyin.html

TS:   process.argv.slice(2)
来源：http://dali.xuetiantiany.cn/Article/details/gtxwrhysil.html

Java: args 数组（main 方法参数）
来源：http://dali.chenlongwang.top/Article/details/gtdhpuslgj.html

Go:   os.Args[1:]
来源：http://dali.hywenlv.cn/Article/details/gtdnayxoon.html

Ruby: ARGV
来源：http://dali.zhaomingkeji.xyz/Article/details/gthkkzwehp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.bjfxy.top/Article/details/gtwlrnzgfz.html

[M02] 读取环境变量
来源：http://dali.ivvv.top/Article/details/gtrjjrvavn.html

Py:   os.environ.get("HOME")
来源：http://dali.tanke756.top/Article/details/gtjiyspjgm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hysaishi.cn/Article/details/gtrlbdpehy.html

JS:   process.env.HOME
来源：http://dali.andypj.xyz/Article/details/gtoezvqzwm.html

TS:   process.env.HOME
来源：http://dali.dashuyun.cn/Article/details/gtwkmlzibq.html

Java: System.getenv("HOME")
来源：http://dali.guowangkeji.top/Article/details/gtwepmimce.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sxryk.cn/Article/details/gtjjkqlzqf.html

Ruby: ENV["HOME"]
来源：http://dali.yanxiufei.cn/Article/details/gthibnitfm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrpyvabtb.html

[M03] 执行外部命令
来源：http://dali.feifeiyinyue.top/Article/details/gtlyupwrcr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tian-w.cn/Article/details/gtvusrfguk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.mhx1999.top/Article/details/gttlbhedhv.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.bjfxy.top/Article/details/gtwdtmekve.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhengqikj.top/Article/details/gtcqrksujf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gaohongyu789.top/Article/details/gthuuicths.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xinyue.icu/Article/details/gtaivbxpmq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjamdfdog.html

C#:   Process.Start("ls", "-l");
来源：http://dali.wangshuangyany.cn/Article/details/gtgkojyddf.html

[M04] 获取当前工作目录
来源：http://dali.sufxvd.cn/Article/details/gtouqusbbg.html

Py:   os.getcwd()
来源：http://dali.xuanzx.com/Article/details/gthvpisrcd.html

PHP:  getcwd();
来源：http://dali.gaohongyu789.top/Article/details/gtnntwauyg.html

JS:   process.cwd()
来源：http://dali.dianchejie.cn/Article/details/gtqjaolujp.html

TS:   process.cwd()
来源：http://dali.xuetiantiany.cn/Article/details/gtdbnwdmxm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.dashuyun.cn/Article/details/gtejipxiar.html

Go:   os.Getwd()
来源：http://dali.hammf.cn/Article/details/gtojpnoegh.html

Ruby: Dir.pwd
来源：http://dali.ehwqpu.com/Article/details/gtzssoflbk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xuetiantiany.cn/Article/details/gtujmisipl.html

[M05] 设置退出码
来源：http://dali.cheryme.top/Article/details/gtgbrvbzyz.html

Py:   sys.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gtocbpdprx.html

PHP:  exit(1);
来源：http://dali.0kj1m.cn/Article/details/gtluwsfskx.html

JS:   process.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtxzmamvqi.html

TS:   process.exit(1)
来源：http://dali.pycfn.com/Article/details/gtiyqrlecf.html

Java: System.exit(1)
来源：http://dali.yvedp.cn/Article/details/gtwnqdocqs.html

Go:   os.Exit(1)
来源：http://dali.ybcxt.top/Article/details/gtngzglxzs.html

Ruby: exit 1
来源：http://dali.guowangkeji.top/Article/details/gttoevwqlg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.9152youxi.cn/Article/details/gtmsidneax.html

[M06] 向标准错误输出
来源：http://dali.xylfe.cn/Article/details/gthjsxtpau.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gotoacloud.top/Article/details/gtqiymbmbl.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhixingplan.top/Article/details/gtdphgwgvy.html

JS:   console.error("err")
来源：http://dali.xuanzx.com/Article/details/gtelyibklh.html

TS:   console.error("err")
来源：http://dali.pycfn.com/Article/details/gttadbwhrw.html

Java: System.err.println("err")
来源：http://dali.gzhubu.top/Article/details/gtxtntsdlm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cqqwz.cn/Article/details/gtdgkncdrm.html

Ruby: warn "err"
来源：http://dali.xuetiantiany.cn/Article/details/gthfwjanuq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yuxming.cn/Article/details/gtpavckbvd.html

[M07] 判断是否为主入口
来源：http://dali.jyoumei.cn/Article/details/gtlvpbuyjq.html

Py:   if __name__ == "__main__":
来源：http://dali.shangyingyoupin.top/Article/details/gtgpceaurc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.svipenyu.cn/Article/details/gtdfhkndlx.html

JS:   require.main === module
来源：http://dali.jianghu66.top/Article/details/gtcxihlkud.html

TS:   require.main === module
来源：http://dali.xuetiantiany.cn/Article/details/gtqnblpzmy.html

Java: public static void main(String[] args)
来源：http://dali.redwolf501.top/Article/details/gttpwphrvx.html

Go:   func main()
来源：http://dali.haohaochexian.top/Article/details/gtlotlxjba.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.aibaodan.cn/Article/details/gtcktgeneo.html

C#:   static void Main(string[] args)
来源：http://dali.guannengcc.top/Article/details/gtvthqbdyf.html

[M08] 获取系统与运行时信息
来源：http://dali.sxryk.cn/Article/details/gtqmjtxjle.html

Py:   platform.system();  platform.python_version()
来源：http://dali.aibaodan.cn/Article/details/gtlsnkkihh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jiagoushi.top/Article/details/gtzmyejqqe.html

JS:   process.platform;  process.version
来源：http://dali.nanxuanxn.top/Article/details/gtxqbztwwb.html

TS:   process.platform;  process.version
来源：http://dali.xinyue.icu/Article/details/gtbohtdava.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xuanzx.com/Article/details/gtzmcsvvec.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvyiyiazh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinghuilouyu.cn/Article/details/gtedthdjil.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shzxlz.cn/Article/details/gtgucolkoe.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtjhlmddhg.html

N. 数据结构与算法
来源：http://dali.birdmap.top/Article/details/gttsznxjxi.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtajfkorpb.html

[N01] 二分查找（有序数组）
来源：http://dali.dashuyun.cn/Article/details/gtftyamnwn.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqoucjqqn.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.iojbl.cn/Article/details/gttvwrcydb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.kuanghao11.cn/Article/details/gtqcdfwdfd.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenzaomai.com/Article/details/gtjfwqbfft.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gtxkqiiswq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gturcfkyli.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.wangdashe.top/Article/details/gtzrwomlcs.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtonazjcgq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.smart0.xyz/Article/details/gtcxizudlj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangtech.top/Article/details/gttmaupvuy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yangfankeji.com/Article/details/gtgetybyqe.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ppjwa.cn/Article/details/gtzocwvmtk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.havefunace.top/Article/details/gtpickhywc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cheryme.top/Article/details/gtrteycfdj.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtbyzxbgip.html

Ruby: arr.sort
来源：http://dali.xylfe.cn/Article/details/gtbgmnarup.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jqgufenzy.top/Article/details/gtrkzehqjx.html

[N03] 快速排序（分治示例）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtguolvdaa.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gotoacloud.top/Article/details/gttwefljyo.html

PHP:  // 递归实现，或用 usort
来源：http://dali.dianchejie.cn/Article/details/gtikwpmswo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtellidorr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jiagoushi.top/Article/details/gtbquaqfqg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.meibo888.top/Article/details/gtqtranvlj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jlsjyb.cn/Article/details/gtpqtbgosc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.sysykeji.top/Article/details/gtniunubab.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hysaishi.cn/Article/details/gtgwrcuxem.html

[N04] 斐波那契数列
来源：http://dali.havefunace.top/Article/details/gtydbqkwag.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.fengsongda.top/Article/details/gtuyhlgyva.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yuxming.cn/Article/details/gtnfbrfvhq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hammf.cn/Article/details/gtnppqhabm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnqzz.top/Article/details/gtcyxhxjeb.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhoulong.xyz/Article/details/gtdhkivfkk.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.9152youxi.cn/Article/details/gtktukftgo.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yangfankeji.com/Article/details/gtqzploibq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.gogol.net.cn/Article/details/gtriaixfhb.html

[N05] 最大公约数
来源：http://dali.aizwys.cn/Article/details/gtvcwfgwaj.html

Py:   math.gcd(a, b)
来源：http://dali.316326.xyz/Article/details/gtsnfimubh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jqgfzy.top/Article/details/gtmsxyrpky.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.guannengcc.top/Article/details/gtzkdsywlw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sysykeji.top/Article/details/gtajsqeyah.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhengqikj.top/Article/details/gtfhpaqiov.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.haohaochexian.top/Article/details/gtknysissp.html

Ruby: a.gcd(b)
来源：http://dali.hammf.cn/Article/details/gtrsnphvcr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.quarkkingdee.top/Article/details/gtgnrebesf.html

[N06] 判断回文字符串
来源：http://dali.smart0.xyz/Article/details/gtgrjdrgxb.html

Py:   s == s[::-1]
来源：http://dali.nwbrower.top/Article/details/gtfanqbcru.html

PHP:  $s === strrev($s);
来源：http://dali.yj20258.top/Article/details/gtpxuyayne.html


<!-- 参考信息 -->