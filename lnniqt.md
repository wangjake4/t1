代发 wailian999

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.nwbrower.top/Article/details/gtgjhaeeqw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shzxlz.cn/Article/details/gtmhiaunzq.html

[J09] 时区处理
来源：http://dali.shanyushiyangtech.top/Article/details/gtxyglwyag.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cheryme.top/Article/details/gttoqbqtez.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sysykeji.top/Article/details/gtyxiwhqag.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xylfe.cn/Article/details/gtiqptgbah.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxinkj.top/Article/details/gtjtdulhzr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gotoacloud.top/Article/details/gtcprcklzi.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj20258888.top/Article/details/gtmeeuwhwg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.quarkkingdee.top/Article/details/gttylpmqwu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.quarkkingdee.top/Article/details/gtrjdysgen.html

[J10] 取今天 / 本月第一天
来源：http://dali.0kj1m.cn/Article/details/gtoqznjjjx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.mhx1999.top/Article/details/gtqbfnffqg.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yj20258888.top/Article/details/gtfcosbxeo.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtmfczlbkv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ppjwa.cn/Article/details/gtwlhvbsud.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shuidangran.top/Article/details/gtbqigizqf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hammf.cn/Article/details/gtzljtborv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.meibo888.top/Article/details/gtfhqmxtsq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.dianchejie.cn/Article/details/gtrxethpwa.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtpyidxjki.html

K. JSON 与序列化
来源：http://dali.pycfn.com/Article/details/gtqbjdiilk.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtrdxfogqf.html

[K01] 对象转 JSON 字符串
来源：http://dali.chenjidiqi.icu/Article/details/gttucmqejj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyhowvghd.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yangfankeji.com/Article/details/gtatlgkkxp.html

JS:   JSON.stringify(obj)
来源：http://dali.yvedp.cn/Article/details/gtqrwjwjfl.html

TS:   JSON.stringify(obj)
来源：http://dali.9152youxi.cn/Article/details/gteqmnhwwe.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.haohaochexian.top/Article/details/gtwdmawaid.html

Go:   json.Marshal(obj)
来源：http://dali.aibaodan.cn/Article/details/gtdyyqbfnw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sweek.top/Article/details/gtymtweose.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gzhubu.top/Article/details/gttvhjrqnk.html

[K02] JSON 字符串转对象
来源：http://dali.quarkkingdee.top/Article/details/gtpiwqwzkr.html

Py:   json.loads(s)
来源：http://dali.daria6918.cn/Article/details/gtecucwekn.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhiwuduotai.top/Article/details/gtqpvraaay.html

JS:   JSON.parse(s)
来源：http://dali.zhengqikj.top/Article/details/gtefpvobst.html

TS:   JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gtcfoiwujk.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jyoumei.cn/Article/details/gtqbkvtzme.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shangyingyoupin.top/Article/details/gtavmsezya.html

Ruby: JSON.parse(s)
来源：http://dali.sxryk.cn/Article/details/gtjhdglhcj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ehwqpu.com/Article/details/gtreuylizv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.snrcjt.cn/Article/details/gtwcqqgdym.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xylfe.cn/Article/details/gtdgyoijiz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdrcmscgy.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnufbmipm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xinyue.icu/Article/details/gtapmueudp.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.daria6918.cn/Article/details/gtykvrqypa.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yuanzhike.top/Article/details/gtfmkeuudv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzyrkavcx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yanxiufei.cn/Article/details/gtsvbideht.html

[K04] 读取 JSON 文件
来源：http://dali.yuxming.cn/Article/details/gttlmtltrx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jqgufenzy.top/Article/details/gtfzzbkiwj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yj20258.top/Article/details/gtsyrplogu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj202588.top/Article/details/gtgwwgsjpk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pycfn.com/Article/details/gteegtzkmp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.tianlin.xyz/Article/details/gtrhpksbrm.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.pengpengdd.cyou/Article/details/gtuoinyufe.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.dianchejie.cn/Article/details/gtkfoatify.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hysaishi.cn/Article/details/gtabcsuurr.html

[K05] 深拷贝对象
来源：http://dali.tian-w.cn/Article/details/gtgqyyapiv.html

Py:   copy.deepcopy(obj)
来源：http://dali.jyoumei.cn/Article/details/gtlklmhawl.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yongpay.top/Article/details/gtyxjuwizv.html

JS:   structuredClone(obj)
来源：http://dali.yj20258.top/Article/details/gtfrttvmev.html

TS:   structuredClone(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtmyrildrb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.smart0.xyz/Article/details/gtcxbtquud.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.aibaodan.cn/Article/details/gtcauqazve.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gogol.net.cn/Article/details/gtftbgyehi.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xinyue.icu/Article/details/gtievlxkmo.html

[K06] 解析 URL 查询串
来源：http://dali.hammf.cn/Article/details/gtkdxbhvqn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zycfv.cn/Article/details/gtjdqvwcbo.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.pycfn.com/Article/details/gtoasxvfze.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.mhx1999.top/Article/details/gttigepzhn.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenjidiqi.icu/Article/details/gtodqytgop.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hongshengwenyu.top/Article/details/gtgckwvbak.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yuanzhike.top/Article/details/gtnrytepjf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.smart0.xyz/Article/details/gtmsxlbdog.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jqgufenzy.top/Article/details/gtpcoyadls.html

[K07] 进制转换
来源：http://dali.mhx1999.top/Article/details/gteznnbmax.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sweek.top/Article/details/gtczamjfds.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yangfankeji.com/Article/details/gtxtqrqvjx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.tanke756.top/Article/details/gtsprtagfo.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gtfrogblzc.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gtleccqnip.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yueranfly.top/Article/details/gtsnsdfmna.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.meibo888.top/Article/details/gtcnjkkrcf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gtysybopvi.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.meibo888.top/Article/details/gtkipohbmd.html

Py:   pickle.dumps(obj)
来源：http://dali.yj20258888.top/Article/details/gttdajjucs.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gzhubu.top/Article/details/gtxzracxjt.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hysaishi.cn/Article/details/gthilvacrm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cdnleiting.top/Article/details/gtylnjwzhm.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinyuanbaomall.cn/Article/details/gtratueiwi.html

Go:   encoding/gob
来源：http://dali.ehwqpu.com/Article/details/gtvmultypf.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtnzvtkmyw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yueranfly.top/Article/details/gtkubgnzla.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtwxfyjxar.html

L. 网络请求
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrekkqvep.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtmvtoevou.html

[L01] 发送 GET 请求
来源：http://dali.jyoumei.cn/Article/details/gtcjgztziq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ivvv.top/Article/details/gtoivfubii.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.smart0.xyz/Article/details/gtkymevnes.html

JS:   await fetch(url)
来源：http://dali.gotoacloud.top/Article/details/gtwxgvwarq.html

TS:   await fetch(url)
来源：http://dali.chenlongwang.top/Article/details/gtqkmkajmz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yonumen.top/Article/details/gtdypmgqyl.html

Go:   resp, err := http.Get(url)
来源：http://dali.tian-w.cn/Article/details/gtaufekwce.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cashguo.top/Article/details/gtauzitwcf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinqigfzy.top/Article/details/gtysujcyim.html

[L02] 发送 POST JSON
来源：http://dali.yonumen.top/Article/details/gtvzqqhzvp.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yueranfly.top/Article/details/gtdizicoij.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.tian-w.cn/Article/details/gtqraxsvvh.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yvedp.cn/Article/details/gtsnogbpck.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinghuilouyu.cn/Article/details/gtvqoiepcn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yueranfly.top/Article/details/gtfvnjwefm.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xuetiantiany.cn/Article/details/gtauiyvyqi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zdqjudy.top/Article/details/gtpakeegfv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.dianchejie.cn/Article/details/gtqxaezixq.html

[L03] 设置自定义请求头
来源：http://dali.cucudq.cn/Article/details/gtlehffzdn.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sxryk.cn/Article/details/gtngmtksuo.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ivvv.top/Article/details/gtkfvbqufi.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.haohaochexian.top/Article/details/gtkfiqakfv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hywenlv.cn/Article/details/gtqagaziha.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.svipenyu.cn/Article/details/gtybovhtax.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sufxvd.cn/Article/details/gtjisslych.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ppjwa.cn/Article/details/gtocjhcxfb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gzhubu.top/Article/details/gtbuzycrsr.html

[L04] 设置超时
来源：http://dali.yongpay.top/Article/details/gtuonwsrbi.html

Py:   requests.get(url, timeout=5)
来源：http://dali.dashuyun.cn/Article/details/gtyajbdmzp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlsbwfdni.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangdashe.top/Article/details/gtxpxehpnb.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ydzc1.top/Article/details/gtvwiskntz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ehwqpu.com/Article/details/gtwiogaesd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.fzhhl.top/Article/details/gtjhqgcvsn.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.0kj1m.cn/Article/details/gtwaooajdq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jianghu66.top/Article/details/gtrpnfvsbk.html

[L05] 上传文件（multipart）
来源：http://dali.pengpengdd.cyou/Article/details/gtdkxcpyqm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yanxiufei.cn/Article/details/gtctwiuzgh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gogol.net.cn/Article/details/gtfpnfkhdz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.iojbl.cn/Article/details/gtlosuibsx.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hfpthk.cn/Article/details/gtaoferxcm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xuetiantiany.cn/Article/details/gtsjzcuizn.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shzxlz.cn/Article/details/gthakaqnch.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.c1oappe.top/Article/details/gtnloiiyyj.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtkdikgguv.html

[L06] 解析响应为 JSON
来源：http://dali.hongshengwenyu.top/Article/details/gtrcrtqvce.html

Py:   resp.json()
来源：http://dali.sufxvd.cn/Article/details/gtkawzeqyt.html

PHP:  json_decode($body, true);
来源：http://dali.tianlin.xyz/Article/details/gtjzyrtcfx.html

JS:   await resp.json()
来源：http://dali.zhoulong.xyz/Article/details/gtlhymcnhw.html

TS:   await resp.json()
来源：http://dali.tian-w.cn/Article/details/gtttydhjzz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cucudq.cn/Article/details/gtyxicowqs.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jianghu66.top/Article/details/gtpbgmbyru.html

Ruby: JSON.parse(resp.body)
来源：http://dali.guannengcc.top/Article/details/gtjpfkofan.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfptuqjns.html

[L07] 处理 HTTP 状态码
来源：http://dali.guannengcc.top/Article/details/gtwssgwglg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.snrcjt.cn/Article/details/gtlzwudkrh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.redwolf501.top/Article/details/gtzxatforv.html

JS:   resp.ok;  resp.status
来源：http://dali.shzxlz.cn/Article/details/gtsynreegs.html

TS:   resp.ok;  resp.status
来源：http://dali.jqgfzy.top/Article/details/gtfjbxlvry.html

Java: resp.statusCode()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqnciffyh.html

Go:   resp.StatusCode
来源：http://dali.jqgufenzy.top/Article/details/gtuysgxzqz.html

Ruby: resp.code.to_i
来源：http://dali.yangfankeji.com/Article/details/gtquxyfmet.html

C#:   (int)resp.StatusCode
来源：http://dali.zycfv.cn/Article/details/gtbakklpoh.html

[L08] 并发请求多个地址
来源：http://dali.yj202588.top/Article/details/gtxehsfgpk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zdqjudy.top/Article/details/gttxsprvkl.html

PHP:  curl_multi_init() 系列
来源：http://dali.guowangkeji.top/Article/details/gtjcjjaqoy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhixingplan.top/Article/details/gtbxgszfwb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tanke756.top/Article/details/gtokdvgopb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jyoumei.cn/Article/details/gtpbklpynf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gotoacloud.top/Article/details/gttnozbgvd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.guowangkeji.top/Article/details/gtmutcrbsc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvicewcul.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtsfosprlc.html

M. 命令行 / 进程 / 环境
来源：http://dali.iojbl.cn/Article/details/gtldtbkxes.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtpdajvsfa.html

[M01] 读取命令行参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtsrhxfuvl.html

Py:   sys.argv[1:]
来源：http://dali.tian-w.cn/Article/details/gtfjbaczcw.html

PHP:  $argv;  $argc;
来源：http://dali.dianchejie.cn/Article/details/gtrdobxwhe.html

JS:   process.argv.slice(2)
来源：http://dali.ybcxt.top/Article/details/gtwbvqrwjl.html

TS:   process.argv.slice(2)
来源：http://dali.jqgfzy.top/Article/details/gtnxrgflom.html

Java: args 数组（main 方法参数）
来源：http://dali.hywenlv.cn/Article/details/gtkpullhvq.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gtpirneqmt.html

Ruby: ARGV
来源：http://dali.daxiang520.top/Article/details/gtvpqvccli.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hfpthk.cn/Article/details/gtkxrstrbs.html

[M02] 读取环境变量
来源：http://dali.tianlin.xyz/Article/details/gttdyxshis.html

Py:   os.environ.get("HOME")
来源：http://dali.quarkkingdee.top/Article/details/gtatwipypb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shuidangran.top/Article/details/gtcmewioqy.html

JS:   process.env.HOME
来源：http://dali.fzhhl.top/Article/details/gtdawloqup.html

TS:   process.env.HOME
来源：http://dali.shangyingyoupin.top/Article/details/gtjnlgfdac.html

Java: System.getenv("HOME")
来源：http://dali.daxiang520.top/Article/details/gtbcptsuzc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sxryk.cn/Article/details/gtslstkymw.html

Ruby: ENV["HOME"]
来源：http://dali.ivvv.top/Article/details/gtvkucvkit.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.havefunace.top/Article/details/gtqyvnerex.html

[M03] 执行外部命令
来源：http://dali.birdmap.top/Article/details/gtdqcpbkek.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yuxming.cn/Article/details/gtbjhimzjl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.smart0.xyz/Article/details/gtkcuvqiec.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.tanke756.top/Article/details/gtfstkfhis.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyvluhcit.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yongpay.top/Article/details/gtutjkjjcl.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.havefunace.top/Article/details/gtaeqcmmfm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jyoumei.cn/Article/details/gtuyyrsyaq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yongpay.top/Article/details/gtppcepcmh.html

[M04] 获取当前工作目录
来源：http://dali.daria6918.cn/Article/details/gteiygfyya.html

Py:   os.getcwd()
来源：http://dali.bjfxy.top/Article/details/gtazuvgvke.html

PHP:  getcwd();
来源：http://dali.0kj1m.cn/Article/details/gtqmgxsfnp.html

JS:   process.cwd()
来源：http://dali.shzxlz.cn/Article/details/gttrxcybde.html

TS:   process.cwd()
来源：http://dali.bjfxy.top/Article/details/gtbvuqkadd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.daria6918.cn/Article/details/gtxkfxgtlm.html

Go:   os.Getwd()
来源：http://dali.aizwys.cn/Article/details/gttrbcgkxl.html

Ruby: Dir.pwd
来源：http://dali.chenlongwang.top/Article/details/gtbbbtzpwo.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yueranfly.top/Article/details/gtcvjytxfs.html

[M05] 设置退出码
来源：http://dali.yanxiufei.cn/Article/details/gtpgdhfcdx.html

Py:   sys.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtjvrtfidw.html

PHP:  exit(1);
来源：http://dali.fengsongda.top/Article/details/gtntbjotye.html

JS:   process.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gtdxletqyp.html

TS:   process.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gtdxuczvwe.html

Java: System.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gtzaxonrqw.html

Go:   os.Exit(1)
来源：http://dali.hysaishi.cn/Article/details/gtcygspyej.html

Ruby: exit 1
来源：http://dali.aibaodan.cn/Article/details/gtgjbevpda.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.dashuyun.cn/Article/details/gtduyzdsdl.html

[M06] 向标准错误输出
来源：http://dali.ppjwa.cn/Article/details/gtpfmsquzg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.aizwys.cn/Article/details/gtguuzfeni.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.pengpengdd.cyou/Article/details/gtehblwmka.html

JS:   console.error("err")
来源：http://dali.fzhhl.top/Article/details/gtszlctrrx.html

TS:   console.error("err")
来源：http://dali.c1oappe.top/Article/details/gtqqlhqpwi.html

Java: System.err.println("err")
来源：http://dali.dianchejie.cn/Article/details/gtxuaohcmw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.vqdsnc.cn/Article/details/gtdbhwxqzm.html

Ruby: warn "err"
来源：http://dali.zhongyouzk.top/Article/details/gtqljbjnpf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yanxiufei.cn/Article/details/gtrwsmsooj.html

[M07] 判断是否为主入口
来源：http://dali.ehwqpu.com/Article/details/gtqnlibkxy.html

Py:   if __name__ == "__main__":
来源：http://dali.chenlongwang.top/Article/details/gtmzalrgfz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.9152youxi.cn/Article/details/gtszsgigjn.html

JS:   require.main === module
来源：http://dali.birdmap.top/Article/details/gtzoskeade.html

TS:   require.main === module
来源：http://dali.shanyushiyangtech.top/Article/details/gtrxxvjbvl.html

Java: public static void main(String[] args)
来源：http://dali.cdnleiting.top/Article/details/gtarwwddwy.html

Go:   func main()
来源：http://dali.shzxlz.cn/Article/details/gtneezgjzs.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.redwolf501.top/Article/details/gthsaijmqh.html

C#:   static void Main(string[] args)
来源：http://dali.gzhubu.top/Article/details/gtypnyvscs.html

[M08] 获取系统与运行时信息
来源：http://dali.snrcjt.cn/Article/details/gtjrajxrvs.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cashguo.top/Article/details/gtawfwrukd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sufxvd.cn/Article/details/gtvkejyvby.html

JS:   process.platform;  process.version
来源：http://dali.bjfxy.top/Article/details/gteemxpitq.html

TS:   process.platform;  process.version
来源：http://dali.jinghuilouyu.cn/Article/details/gtfprsklvh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.chenzaomai.com/Article/details/gtexqjmvij.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.fengsongda.top/Article/details/gtomrgxxkm.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sxryk.cn/Article/details/gtdhelnldf.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shzxlz.cn/Article/details/gtswgigxoz.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gthlgobpfq.html

N. 数据结构与算法
来源：http://dali.aibaodan.cn/Article/details/gteangatgx.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtlnginjxj.html

[N01] 二分查找（有序数组）
来源：http://dali.jqgufenzy.top/Article/details/gtebedxtzc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cashguo.top/Article/details/gtmttrslqo.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ehwqpu.com/Article/details/gtxcksipje.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.haohaochexian.top/Article/details/gtqybjnezi.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxuanxn.top/Article/details/gtbmmhzikh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gtjdrdlgmp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtsuoshnmi.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.wangdashe.top/Article/details/gtxobvpffy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jianghu66.top/Article/details/gtbawjkchj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xinyue.icu/Article/details/gttrccpeyb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shzxlz.cn/Article/details/gtnwskgpiv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.meibo888.top/Article/details/gtusqleqgz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xinyue.icu/Article/details/gtmcyhywtu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yueranfly.top/Article/details/gtiqskpdgr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yvedp.cn/Article/details/gteyivhytm.html

Go:   slices.Sort(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtohoeooom.html

Ruby: arr.sort
来源：http://dali.gzhubu.top/Article/details/gtrvdudbxm.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yonumen.top/Article/details/gtndkcyslz.html

[N03] 快速排序（分治示例）
来源：http://dali.316326.xyz/Article/details/gtuwvacasp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.vqdsnc.cn/Article/details/gtecrymshm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.bjfxy.top/Article/details/gtshsdgzjn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gotoacloud.top/Article/details/gtyrllvcnq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yueranfly.top/Article/details/gtyyjukxpf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gtlosxeldr.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenzaomai.com/Article/details/gthcjlhvxs.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.fengsongda.top/Article/details/gtfwpnookr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.pycfn.com/Article/details/gtdjyxeiey.html

[N04] 斐波那契数列
来源：http://dali.yueranfly.top/Article/details/gtoqnkhqlz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.aibaodan.cn/Article/details/gtsamfvlso.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.pengpengdd.cyou/Article/details/gttkdxintr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gtzctlewqr.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.andypj.xyz/Article/details/gtvxxmrafs.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.nwbrower.top/Article/details/gtipiodaea.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbmtkwmwp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.nanxuanxn.top/Article/details/gtfepbfekp.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jqgfzy.top/Article/details/gttjhaekim.html

[N05] 最大公约数
来源：http://dali.chenzaomai.com/Article/details/gtbdgxzdvl.html

Py:   math.gcd(a, b)
来源：http://dali.zhixingplan.top/Article/details/gtznvjskgn.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.redwolf501.top/Article/details/gtxuwvgkdx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnxiangtu.top/Article/details/gtztfiiabu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hammf.cn/Article/details/gtdjpyoraj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.dashuyun.cn/Article/details/gtajgxoovt.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gtiupnqcac.html

Ruby: a.gcd(b)
来源：http://dali.aizwys.cn/Article/details/gtsquudywe.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.pycfn.com/Article/details/gtqmafkodb.html

[N06] 判断回文字符串
来源：http://dali.dashuyun.cn/Article/details/gtrtjhqbhf.html

Py:   s == s[::-1]
来源：http://dali.cheryme.top/Article/details/gthhohbxli.html

PHP:  $s === strrev($s);
来源：http://dali.jlsjyb.cn/Article/details/gtyrxeiwya.html

JS:   s === [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gtqvgdwojw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ivvv.top/Article/details/gtnrlbnufw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.dianchejie.cn/Article/details/gtmallpcfg.html

Go:   // 双指针从两端比较
来源：http://dali.ivvv.top/Article/details/gtjrixetdd.html


<!-- 参考信息 -->