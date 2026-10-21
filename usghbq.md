代发 wailian999

[J07] 比较两个日期
来源：http://dali.pengpengdd.cyou/Article/details/gtfvugruoi.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gtropqmtof.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jqgufenzy.top/Article/details/gtxkxspzca.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenlongwang.top/Article/details/gtenchpssn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xziqi.cn/Article/details/gthxlrzvbx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ivvv.top/Article/details/gtymrejroe.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.andypj.xyz/Article/details/gtzlhposgq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.meibo888.top/Article/details/gtqiiafzsb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinqigufen.top/Article/details/gtpxvicdty.html

[J08] 提取年月日与星期
来源：http://dali.0kj1m.cn/Article/details/gtkyfjfsrd.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.316326.xyz/Article/details/gtdfjucses.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shanyushiyangtech.top/Article/details/gtdyobweat.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenlongwang.top/Article/details/gtwowakgnr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yuxming.cn/Article/details/gtvjegicqm.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sweek.top/Article/details/gtuypydzuo.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinqigfzy.top/Article/details/gtwfnzfdmc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenzaomai.com/Article/details/gtoblqwkhb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shangyingyoupin.top/Article/details/gtqshooukg.html

[J09] 时区处理
来源：http://dali.jinqigufen.top/Article/details/gthfmhzjys.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.smart0.xyz/Article/details/gtymeuoxko.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.bjfxy.top/Article/details/gtpjmgeybm.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.iojbl.cn/Article/details/gtpujvwemk.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtepmijkyb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.redwolf501.top/Article/details/gticlofpmr.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sxryk.cn/Article/details/gtftxbdgjr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yj20258888.top/Article/details/gtetfrccyj.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zycfv.cn/Article/details/gtomjdysdw.html

[J10] 取今天 / 本月第一天
来源：http://dali.hnqzz.top/Article/details/gtwkpkqkve.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ybcxt.top/Article/details/gtrwnxhqpl.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sufxvd.cn/Article/details/gtywldlndt.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtvqgpnpyz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ybcxt.top/Article/details/gtsfnnibds.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xinyue.icu/Article/details/gtypmrrvat.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cucudq.cn/Article/details/gtrioragef.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cqqwz.cn/Article/details/gtikoqwwvi.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbzkqvygy.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgtuylbse.html

K. JSON 与序列化
来源：http://dali.meibo888.top/Article/details/gttbsvtmuh.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtvtxdamdp.html

[K01] 对象转 JSON 字符串
来源：http://dali.andypj.xyz/Article/details/gtfqcumwmo.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj20258.top/Article/details/gtlgxkbgdr.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xuetiantiany.cn/Article/details/gtzxkuzvob.html

JS:   JSON.stringify(obj)
来源：http://dali.wangdashe.top/Article/details/gtwdonusxz.html

TS:   JSON.stringify(obj)
来源：http://dali.yuanzhike.top/Article/details/gtsviyepzq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hammf.cn/Article/details/gtodcjyddn.html

Go:   json.Marshal(obj)
来源：http://dali.zhixingplan.top/Article/details/gtgirsctnb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.vqdsnc.cn/Article/details/gtmavwtwah.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtbyhplegs.html

[K02] JSON 字符串转对象
来源：http://dali.pengpengdd.cyou/Article/details/gtpyzbqljh.html

Py:   json.loads(s)
来源：http://dali.zycfv.cn/Article/details/gtzduuvrkk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shzxlz.cn/Article/details/gtortmzsfk.html

JS:   JSON.parse(s)
来源：http://dali.havefunace.top/Article/details/gttrajliei.html

TS:   JSON.parse(s)
来源：http://dali.gotoacloud.top/Article/details/gtvhssbdks.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.mhx1999.top/Article/details/gtrpefatbg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yangfankeji.com/Article/details/gtgqajhisb.html

Ruby: JSON.parse(s)
来源：http://dali.yj20258888.top/Article/details/gtueattpaa.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.snrcjt.cn/Article/details/gtkfozscuk.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gtktcwwpsa.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yangfankeji.com/Article/details/gtcstdatem.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yonumen.top/Article/details/gtkayyhvmz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhoulong.xyz/Article/details/gtyivxdxba.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgfzy.top/Article/details/gthejpsfaw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ybcxt.top/Article/details/gtxnvktsjg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinqigufen.top/Article/details/gtnpkhfwca.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtqknbkdex.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.havefunace.top/Article/details/gtvvcilqkx.html

[K04] 读取 JSON 文件
来源：http://dali.zhixingplan.top/Article/details/gtwzkcmzvk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yonumen.top/Article/details/gtiybqxqyp.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gteonyqsnd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zdqjudy.top/Article/details/gtarvlhsif.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tanke756.top/Article/details/gtcnbdjiga.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jiagoushi.top/Article/details/gtxdzdlfhl.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.nanxuanxn.top/Article/details/gtiaagrbpp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hnxiangtu.top/Article/details/gtoxqhxdot.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hywenlv.cn/Article/details/gtoiftlcwl.html

[K05] 深拷贝对象
来源：http://dali.birdmap.top/Article/details/gtilbvjppb.html

Py:   copy.deepcopy(obj)
来源：http://dali.ydzc1.top/Article/details/gtbuvyrsch.html

PHP:  unserialize(serialize($obj));
来源：http://dali.birdmap.top/Article/details/gtkwonuufw.html

JS:   structuredClone(obj)
来源：http://dali.sufxvd.cn/Article/details/gtihdvlwdp.html

TS:   structuredClone(obj)
来源：http://dali.jinqigufen.top/Article/details/gtfcgxggdi.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.mhx1999.top/Article/details/gtaivnkudv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yj20258.top/Article/details/gtkpgjcwxg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yonumen.top/Article/details/gtletpaebu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sysykeji.top/Article/details/gtniyhebvp.html

[K06] 解析 URL 查询串
来源：http://dali.yangfankeji.com/Article/details/gtilycwwou.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hongshengwenyu.top/Article/details/gthityxyfl.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.fengsongda.top/Article/details/gtsmxsaagz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jlsjyb.cn/Article/details/gtvfcvrsgz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuxming.cn/Article/details/gtoirymyyb.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.redwolf501.top/Article/details/gtfoktwals.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jqgfzy.top/Article/details/gtdgjusnxj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvihnysxq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.tanke756.top/Article/details/gtsdaezugw.html

[K07] 进制转换
来源：http://dali.jqgfzy.top/Article/details/gttmhhvkda.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gtuosavhbk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.redwolf501.top/Article/details/gtcldwdkka.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gtnjlyomgx.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gtufeammkl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtoryjxiph.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.svipenyu.cn/Article/details/gtqdaaolsr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.nanxinkj.top/Article/details/gtyluybtkk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gtmsbgqbzn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhoulong.xyz/Article/details/gtgvimqmxb.html

Py:   pickle.dumps(obj)
来源：http://dali.redwolf501.top/Article/details/gtzomnnipf.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hnqzz.top/Article/details/gtkkoriywl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.daxiang520.top/Article/details/gtowjejpgu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jiagoushi.top/Article/details/gtoewacfxp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hnqzz.top/Article/details/gtxytmfimz.html

Go:   encoding/gob
来源：http://dali.tanke756.top/Article/details/gtzjamdhtv.html

Ruby: Marshal.dump(obj)
来源：http://dali.cucudq.cn/Article/details/gtmaxacqpa.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jinghuilouyu.cn/Article/details/gtdrtymcpw.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtqeybqfwp.html

L. 网络请求
来源：http://dali.snrcjt.cn/Article/details/gtkujfqlbn.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtusjvsueq.html

[L01] 发送 GET 请求
来源：http://dali.xylfe.cn/Article/details/gtgrpshrzr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sxryk.cn/Article/details/gtpmhlvfzm.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shzxlz.cn/Article/details/gtkelwoicj.html

JS:   await fetch(url)
来源：http://dali.dianchejie.cn/Article/details/gtxzjjeyik.html

TS:   await fetch(url)
来源：http://dali.zdqjudy.top/Article/details/gtstaktfkn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yueranfly.top/Article/details/gtitjwcfeo.html

Go:   resp, err := http.Get(url)
来源：http://dali.nwbrower.top/Article/details/gtwcxzaqyz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yonumen.top/Article/details/gtkoljtlwd.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuxkljndp.html

[L02] 发送 POST JSON
来源：http://dali.xuanzx.com/Article/details/gtbpqhjcqm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xziqi.cn/Article/details/gtlyfmizow.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xziqi.cn/Article/details/gtksjjfuvz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jlsjyb.cn/Article/details/gtfbdsmshx.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dianchejie.cn/Article/details/gtixfwreub.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.316326.xyz/Article/details/gtczuxksvb.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shanyushiyangtech.top/Article/details/gtqwxqxwcb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sufxvd.cn/Article/details/gtbiusvdxv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hongshengwenyu.top/Article/details/gtmidhrwlx.html

[L03] 设置自定义请求头
来源：http://dali.cucudq.cn/Article/details/gtdzgweeix.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.svipenyu.cn/Article/details/gtatmetspj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jqgfzy.top/Article/details/gturasljuh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jianghu66.top/Article/details/gtuefllveq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hysaishi.cn/Article/details/gtqzcjjhmq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hnxiangtu.top/Article/details/gtkkbnunet.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.dashuyun.cn/Article/details/gtcrayqvjp.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shzxlz.cn/Article/details/gtgcntmabx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sysykeji.top/Article/details/gtaqazveoh.html

[L04] 设置超时
来源：http://dali.andypj.xyz/Article/details/gthckrkjwc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cucudq.cn/Article/details/gtdxnudmne.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.316326.xyz/Article/details/gtcviyxoug.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yanxiufei.cn/Article/details/gtzrynqiga.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ppjwa.cn/Article/details/gthveigrdl.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jlsjyb.cn/Article/details/gtbjhktcfz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.vqdsnc.cn/Article/details/gtsoofkynw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zdqjudy.top/Article/details/gtmfrajavi.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shzxlz.cn/Article/details/gtwylvtwud.html

[L05] 上传文件（multipart）
来源：http://dali.hnxiangtu.top/Article/details/gtfwkqfwbp.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.dashuyun.cn/Article/details/gtrppvlbwn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.chenlongwang.top/Article/details/gtlmkrvkku.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgfzy.top/Article/details/gtsqldwrdc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hywenlv.cn/Article/details/gtofhkzpkk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhongyouzk.top/Article/details/gtohhvopab.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gtjyqabhqz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.smart0.xyz/Article/details/gtjdigwtvx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.tian-w.cn/Article/details/gtsgoltoyb.html

[L06] 解析响应为 JSON
来源：http://dali.hywenlv.cn/Article/details/gtqpleidwt.html

Py:   resp.json()
来源：http://dali.zhoulong.xyz/Article/details/gtfnusrcul.html

PHP:  json_decode($body, true);
来源：http://dali.cdnleiting.top/Article/details/gtgvadhkbm.html

JS:   await resp.json()
来源：http://dali.yangfankeji.com/Article/details/gtmditkcip.html

TS:   await resp.json()
来源：http://dali.9152youxi.cn/Article/details/gtroacuqbd.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hywenlv.cn/Article/details/gtjvymbivj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.meibo888.top/Article/details/gtuqovuceh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xylfe.cn/Article/details/gtygpipswp.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nanxinkj.top/Article/details/gtwdacylgu.html

[L07] 处理 HTTP 状态码
来源：http://dali.yonumen.top/Article/details/gtxgirzgoc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.fengsongda.top/Article/details/gtcwowhtzd.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sufxvd.cn/Article/details/gtcdowhydm.html

JS:   resp.ok;  resp.status
来源：http://dali.jyoumei.cn/Article/details/gteyzirxdw.html

TS:   resp.ok;  resp.status
来源：http://dali.jqgufenzy.top/Article/details/gtbtwiaxox.html

Java: resp.statusCode()
来源：http://dali.jiagoushi.top/Article/details/gtooeetlmw.html

Go:   resp.StatusCode
来源：http://dali.gzhubu.top/Article/details/gtpjfubgfv.html

Ruby: resp.code.to_i
来源：http://dali.gogol.net.cn/Article/details/gtkwdnpygz.html

C#:   (int)resp.StatusCode
来源：http://dali.yj202588.top/Article/details/gtegnqwyri.html

[L08] 并发请求多个地址
来源：http://dali.yj202588.top/Article/details/gtkgcjccbz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shanyushiyangkeji.top/Article/details/gthbziephq.html

PHP:  curl_multi_init() 系列
来源：http://dali.ivvv.top/Article/details/gtrugijmez.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ivvv.top/Article/details/gtskwugreh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.havefunace.top/Article/details/gtxgjuziyi.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sweek.top/Article/details/gtrebxgiuf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zdqjudy.top/Article/details/gtzkswkyyw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cheryme.top/Article/details/gtlfdbwzmb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jiagoushi.top/Article/details/gtjzdzirik.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtgcvnhewn.html

M. 命令行 / 进程 / 环境
来源：http://dali.gzhubu.top/Article/details/gtiwwxqqsp.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtofypxfcr.html

[M01] 读取命令行参数
来源：http://dali.tanke756.top/Article/details/gtldpdngyq.html

Py:   sys.argv[1:]
来源：http://dali.hysaishi.cn/Article/details/gtuippqylp.html

PHP:  $argv;  $argc;
来源：http://dali.shzxlz.cn/Article/details/gteatstmso.html

JS:   process.argv.slice(2)
来源：http://dali.zhengqikj.top/Article/details/gtdhovtotv.html

TS:   process.argv.slice(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvngtoyxl.html

Java: args 数组（main 方法参数）
来源：http://dali.yueranfly.top/Article/details/gtogcvtxvb.html

Go:   os.Args[1:]
来源：http://dali.gogol.net.cn/Article/details/gtoqygwile.html

Ruby: ARGV
来源：http://dali.gotoacloud.top/Article/details/gtmfqhvzzp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sxryk.cn/Article/details/gtvxqhmees.html

[M02] 读取环境变量
来源：http://dali.ydzc1.top/Article/details/gtvewthskh.html

Py:   os.environ.get("HOME")
来源：http://dali.cdnleiting.top/Article/details/gtskvctqda.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.svipenyu.cn/Article/details/gtqpdjjxmc.html

JS:   process.env.HOME
来源：http://dali.guowangkeji.top/Article/details/gthyxphlce.html

TS:   process.env.HOME
来源：http://dali.yj20258.top/Article/details/gtxtytjvqn.html

Java: System.getenv("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gtewfarcdp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gtrjcrouyc.html

Ruby: ENV["HOME"]
来源：http://dali.vqdsnc.cn/Article/details/gtowahcibs.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.dianchejie.cn/Article/details/gtwbvczbmf.html

[M03] 执行外部命令
来源：http://dali.9152youxi.cn/Article/details/gtzrzxcawj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.316326.xyz/Article/details/gtcpdelbie.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.iojbl.cn/Article/details/gtdwktckdb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gotoacloud.top/Article/details/gtszkkykii.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ydzc1.top/Article/details/gtleqiujyc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cdnleiting.top/Article/details/gtoypwpdrg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hongshengwenyu.top/Article/details/gtfnuzdvmv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hammf.cn/Article/details/gtbnmgsowj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hongshengwenyu.top/Article/details/gtciabilkm.html

[M04] 获取当前工作目录
来源：http://dali.shangyingyoupin.top/Article/details/gtxlcidwaz.html

Py:   os.getcwd()
来源：http://dali.quarkkingdee.top/Article/details/gtktapkiun.html

PHP:  getcwd();
来源：http://dali.sweek.top/Article/details/gtrilaiodn.html

JS:   process.cwd()
来源：http://dali.dianchejie.cn/Article/details/gtpqdqnzfn.html

TS:   process.cwd()
来源：http://dali.xinyue.icu/Article/details/gtrvbpewfs.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmkyjrpgw.html

Go:   os.Getwd()
来源：http://dali.nanxinkj.top/Article/details/gtbxtzplwf.html

Ruby: Dir.pwd
来源：http://dali.c1oappe.top/Article/details/gthnvnnbmq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.snrcjt.cn/Article/details/gtttefwgkf.html

[M05] 设置退出码
来源：http://dali.yj202588.top/Article/details/gtbqhwixib.html

Py:   sys.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtsswfhyor.html

PHP:  exit(1);
来源：http://dali.mhx1999.top/Article/details/gtghnpbmlv.html

JS:   process.exit(1)
来源：http://dali.ybcxt.top/Article/details/gtdnewzpem.html

TS:   process.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gtstfdkwzn.html

Java: System.exit(1)
来源：http://dali.yj20258888.top/Article/details/gtkjsvhfdb.html

Go:   os.Exit(1)
来源：http://dali.jinqigufen.top/Article/details/gtyzdpcgut.html

Ruby: exit 1
来源：http://dali.yanxiufei.cn/Article/details/gtfkldxdxs.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xinyue.icu/Article/details/gtquwumdwq.html

[M06] 向标准错误输出
来源：http://dali.andypj.xyz/Article/details/gtlginuizf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxoibwqgc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.redwolf501.top/Article/details/gtcwergrmv.html

JS:   console.error("err")
来源：http://dali.tanke756.top/Article/details/gttttjixvp.html

TS:   console.error("err")
来源：http://dali.yj202588.top/Article/details/gtvqfhzilt.html

Java: System.err.println("err")
来源：http://dali.haohaochexian.top/Article/details/gteeahjdwo.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.aibaodan.cn/Article/details/gtlpbtuvkd.html

Ruby: warn "err"
来源：http://dali.xuanzx.com/Article/details/gtcqbwqqia.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yangfankeji.com/Article/details/gtnfoqygxh.html

[M07] 判断是否为主入口
来源：http://dali.9152youxi.cn/Article/details/gtoxfmaule.html

Py:   if __name__ == "__main__":
来源：http://dali.shanyushiyangtech.top/Article/details/gtayxhqxta.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdzojozki.html

JS:   require.main === module
来源：http://dali.guowangkeji.top/Article/details/gtxhnuaquc.html

TS:   require.main === module
来源：http://dali.redwolf501.top/Article/details/gtumzpbzzo.html

Java: public static void main(String[] args)
来源：http://dali.jqgufenzy.top/Article/details/gtlnhtetsx.html

Go:   func main()
来源：http://dali.aibaodan.cn/Article/details/gtzznagvey.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yuxming.cn/Article/details/gtnkeyegre.html

C#:   static void Main(string[] args)
来源：http://dali.jyoumei.cn/Article/details/gtzzeslayk.html

[M08] 获取系统与运行时信息
来源：http://dali.wangshuangyany.cn/Article/details/gtddkkbdew.html

Py:   platform.system();  platform.python_version()
来源：http://dali.aizwys.cn/Article/details/gtkeomkyxw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ywan-chungtsiang.top/Article/details/gttnmtxbhh.html

JS:   process.platform;  process.version
来源：http://dali.tian-w.cn/Article/details/gtbaszjapu.html

TS:   process.platform;  process.version
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrekfdnrb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.smart0.xyz/Article/details/gtzvbbpoch.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cheryme.top/Article/details/gtiddznzhl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jqgfzy.top/Article/details/gtrmmuvxlx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gteumcytxx.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtopynzksv.html

N. 数据结构与算法
来源：http://dali.cashguo.top/Article/details/gthrgvokoi.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtjbihuzwk.html

[N01] 二分查找（有序数组）
来源：http://dali.cashguo.top/Article/details/gtxnosqfee.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gtmopfrhtm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.daxiang520.top/Article/details/gtfemgeyds.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jianghu66.top/Article/details/gtnouqvuyu.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daxiang520.top/Article/details/gtyemnxvtm.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtnmivnzez.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtnhsemvpf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.birdmap.top/Article/details/gtdjiujkca.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.birdmap.top/Article/details/gtjbubohaj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhixingplan.top/Article/details/gtqwyazdgs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.wangshuangyany.cn/Article/details/gtjrfsioda.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shanyushiyangtech.top/Article/details/gtjadtdkrl.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzohnzyyr.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmlggobbz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xziqi.cn/Article/details/gthdljxdwp.html

Go:   slices.Sort(arr)
来源：http://dali.zhengqikj.top/Article/details/gtotfnaerm.html

Ruby: arr.sort
来源：http://dali.fengsongda.top/Article/details/gtyxpidrxn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jqgufenzy.top/Article/details/gttidhjrax.html

[N03] 快速排序（分治示例）
来源：http://dali.yuanzhike.top/Article/details/gtwuefstui.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.nanxinkj.top/Article/details/gtyncozhuh.html

PHP:  // 递归实现，或用 usort
来源：http://dali.redwolf501.top/Article/details/gtqnahyeod.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cdnleiting.top/Article/details/gtqasbxwhy.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gotoacloud.top/Article/details/gtzycdqdjp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhongyouzk.top/Article/details/gtdmnjesuw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjhcngxvx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ivvv.top/Article/details/gtjfgqqngy.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jiagoushi.top/Article/details/gtuihtjrsx.html

[N04] 斐波那契数列
来源：http://dali.tianlin.xyz/Article/details/gtfcdbhkpc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.aizwys.cn/Article/details/gtegblfooh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinqigfzy.top/Article/details/gtskqekrsf.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigufen.top/Article/details/gtixksemtx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuanzx.com/Article/details/gtykindhhy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.bjfxy.top/Article/details/gtagjpqxvw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hywenlv.cn/Article/details/gtlbwegdha.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.haohaochexian.top/Article/details/gtfiubtcuw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gtalwtfsfz.html


<!-- 参考信息 -->