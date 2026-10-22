代发 wailian999

[J07] 比较两个日期
来源：http://dali.havefunace.top/Article/details/gtdhztixma.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinqigfzy.top/Article/details/gthtxbqncs.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhongyouzk.top/Article/details/gtwqxtjagn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yanxiufei.cn/Article/details/gtkyurajfo.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.fengsongda.top/Article/details/gtfzynsmkc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.aizwys.cn/Article/details/gtrucddsug.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.9152youxi.cn/Article/details/gtfknmlnag.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gtthyezcdm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.dianchejie.cn/Article/details/gtebfkrxyd.html

[J08] 提取年月日与星期
来源：http://dali.hywenlv.cn/Article/details/gttbljwwdp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jlsjyb.cn/Article/details/gtjxcbvwpa.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xuetiantiany.cn/Article/details/gtneldzjmf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jqgufenzy.top/Article/details/gtgsxiidwd.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhiwuduotai.top/Article/details/gtojpgcbde.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.svipenyu.cn/Article/details/gteetmerzv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhoulong.xyz/Article/details/gtigkenqrm.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ydzc1.top/Article/details/gtidsiavab.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ppjwa.cn/Article/details/gtbizmytun.html

[J09] 时区处理
来源：http://dali.jiagoushi.top/Article/details/gtifuimbhw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.316326.xyz/Article/details/gtmcnnwdpe.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.birdmap.top/Article/details/gttjtqhjva.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangshuangyany.cn/Article/details/gtpgkfjyup.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fzhhl.top/Article/details/gttkjagpce.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zdqjudy.top/Article/details/gtzopwipwp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xuetiantiany.cn/Article/details/gthuashhqr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yonumen.top/Article/details/gtgzkfxbxr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gotoacloud.top/Article/details/gtccpqqnml.html

[J10] 取今天 / 本月第一天
来源：http://dali.xuetiantiany.cn/Article/details/gtjcjishfg.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttgztztwi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.316326.xyz/Article/details/gtwjamwcji.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.316326.xyz/Article/details/gtkxlawmgg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj20258888.top/Article/details/gtaclzqdau.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.meibo888.top/Article/details/gthcmyhwrt.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.birdmap.top/Article/details/gtyignzsqs.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xuanzx.com/Article/details/gtiegvwkti.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.tianlin.xyz/Article/details/gtdiidpmxh.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtueoqhsvd.html

K. JSON 与序列化
来源：http://dali.cdnleiting.top/Article/details/gtfhcxgcpz.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtvxckqlhi.html

[K01] 对象转 JSON 字符串
来源：http://dali.wangdashe.top/Article/details/gtgrddokjt.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.mhx1999.top/Article/details/gtufcdfboc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.316326.xyz/Article/details/gtjqsnefwd.html

JS:   JSON.stringify(obj)
来源：http://dali.yueranfly.top/Article/details/gtkyuycqcv.html

TS:   JSON.stringify(obj)
来源：http://dali.ivvv.top/Article/details/gtskooyyqr.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yangfankeji.com/Article/details/gtxmhqumkq.html

Go:   json.Marshal(obj)
来源：http://dali.dashuyun.cn/Article/details/gtavdpiwnf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.meibo888.top/Article/details/gtekaxwhng.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.bjfxy.top/Article/details/gtuvyyvybq.html

[K02] JSON 字符串转对象
来源：http://dali.chenzaomai.com/Article/details/gtcrizbpol.html

Py:   json.loads(s)
来源：http://dali.cashguo.top/Article/details/gtjlhavmcu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.mhx1999.top/Article/details/gtiogmiayv.html

JS:   JSON.parse(s)
来源：http://dali.nanxuanxn.top/Article/details/gtujlolvmx.html

TS:   JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gtayagwbzz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.mhx1999.top/Article/details/gtamzqfqpv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.pengpengdd.cyou/Article/details/gtnomdybkc.html

Ruby: JSON.parse(s)
来源：http://dali.yueranfly.top/Article/details/gtfkllxxux.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtgfgmyptq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ybcxt.top/Article/details/gtjhuhkdpe.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.aizwys.cn/Article/details/gtjzbwvwuj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gzhubu.top/Article/details/gtdmfxqnlo.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuanzx.com/Article/details/gtfmnofnkk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.mhx1999.top/Article/details/gtfuodcpfg.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jqgfzy.top/Article/details/gtjysllroi.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yvedp.cn/Article/details/gtvagqjadp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sweek.top/Article/details/gtticujxdf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cdnleiting.top/Article/details/gtvtynczcc.html

[K04] 读取 JSON 文件
来源：http://dali.aizwys.cn/Article/details/gtstkvxwgl.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.havefunace.top/Article/details/gtsscthefz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.aibaodan.cn/Article/details/gtovqcwrun.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tian-w.cn/Article/details/gtupgqufbl.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigufen.top/Article/details/gtsprschhp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xylfe.cn/Article/details/gtzrqeptit.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yvedp.cn/Article/details/gthgyzpxnt.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.nanxuanxn.top/Article/details/gtbucytrmt.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.wangshuangyany.cn/Article/details/gtujgtsnlx.html

[K05] 深拷贝对象
来源：http://dali.tianlin.xyz/Article/details/gtuiugyhnt.html

Py:   copy.deepcopy(obj)
来源：http://dali.snrcjt.cn/Article/details/gtmvgawzsc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.dashuyun.cn/Article/details/gtaqdfmhpw.html

JS:   structuredClone(obj)
来源：http://dali.jinqigufen.top/Article/details/gtrltyzgya.html

TS:   structuredClone(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtzvurbwqi.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.havefunace.top/Article/details/gtfhgvwtpa.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.chenzaomai.com/Article/details/gtxhmlvgoj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhoulong.xyz/Article/details/gtnhecgsni.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yongpay.top/Article/details/gtzjqjhvxh.html

[K06] 解析 URL 查询串
来源：http://dali.c1oappe.top/Article/details/gtvutvxdzw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.mhx1999.top/Article/details/gtosiwchln.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.chenlongwang.top/Article/details/gtgozmrcne.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hysaishi.cn/Article/details/gtgkhdelno.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.iojbl.cn/Article/details/gtucaokckp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jqgfzy.top/Article/details/gtkbujilwq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.bjfxy.top/Article/details/gtfbyggiyf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gtfvpqlcxf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.bjfxy.top/Article/details/gtyarrygtx.html

[K07] 进制转换
来源：http://dali.fzhhl.top/Article/details/gtyqgpzizv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gtmaysphyq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gaohongyu789.top/Article/details/gtsmoktfeu.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gtfgavvfgs.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gtfjdxtjin.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gtikdafxgm.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sufxvd.cn/Article/details/gthfqasmlf.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.pycfn.com/Article/details/gtkcwpwaib.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtccaijrcd.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.fzhhl.top/Article/details/gtvycqkkzx.html

Py:   pickle.dumps(obj)
来源：http://dali.hfpthk.cn/Article/details/gtitnbcubl.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sweek.top/Article/details/gtgczttcav.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.kuanghao11.cn/Article/details/gthxhqhgoe.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.quarkkingdee.top/Article/details/gtduhomqiu.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.c1oappe.top/Article/details/gtlbccpfxg.html

Go:   encoding/gob
来源：http://dali.yueranfly.top/Article/details/gttkidqvia.html

Ruby: Marshal.dump(obj)
来源：http://dali.shzxlz.cn/Article/details/gtoqufyewi.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.kuanghao11.cn/Article/details/gtcgcnqiot.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtwroinbzk.html

L. 网络请求
来源：http://dali.xinyue.icu/Article/details/gtcljhtoxj.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcupdnqsv.html

[L01] 发送 GET 请求
来源：http://dali.yvedp.cn/Article/details/gtmobchoao.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ydzc1.top/Article/details/gtbltvotbd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yanxiufei.cn/Article/details/gtnbdptvhr.html

JS:   await fetch(url)
来源：http://dali.nwbrower.top/Article/details/gtstjfqfwe.html

TS:   await fetch(url)
来源：http://dali.snrcjt.cn/Article/details/gtnanggqxd.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yj20258888.top/Article/details/gtvxfdmefc.html

Go:   resp, err := http.Get(url)
来源：http://dali.ybcxt.top/Article/details/gtjbzzyyau.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hywenlv.cn/Article/details/gtmezuerkm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.haohaochexian.top/Article/details/gtrcutpqvw.html

[L02] 发送 POST JSON
来源：http://dali.dianchejie.cn/Article/details/gtvaxzewjn.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.sufxvd.cn/Article/details/gtcytaoqev.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zdqjudy.top/Article/details/gtepmwmwdx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenzaomai.com/Article/details/gtmvgrjoyo.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgufenzy.top/Article/details/gtgosvxgmr.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.sweek.top/Article/details/gtqzfugtne.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.pycfn.com/Article/details/gtrttzdeiz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.smart0.xyz/Article/details/gtasogcquq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jqgufenzy.top/Article/details/gtpeeyibkg.html

[L03] 设置自定义请求头
来源：http://dali.guowangkeji.top/Article/details/gtkecngigw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.aibaodan.cn/Article/details/gtxjdfsipw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.nanxuanxn.top/Article/details/gtrxailktu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtztrkwwdc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinghuilouyu.cn/Article/details/gtyplnbxhl.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sweek.top/Article/details/gthwddpmrg.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hnqzz.top/Article/details/gtooyekabd.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yj20258888.top/Article/details/gtvafcukme.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.guowangkeji.top/Article/details/gtagpxqktd.html

[L04] 设置超时
来源：http://dali.iojbl.cn/Article/details/gtdbtsbmqk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.feifeiyinyue.top/Article/details/gtqlsirgik.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yj20258888.top/Article/details/gtfpsusmbm.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxinkj.top/Article/details/gtwdkwxapb.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cucudq.cn/Article/details/gthbrvvfsj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinqigufen.top/Article/details/gtgitnnlay.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shzxlz.cn/Article/details/gtlmvlaboh.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yanxiufei.cn/Article/details/gtaqpoamjg.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jqgfzy.top/Article/details/gtmkwgevpo.html

[L05] 上传文件（multipart）
来源：http://dali.havefunace.top/Article/details/gtxulzqimf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hfpthk.cn/Article/details/gtohiwfhrw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.guowangkeji.top/Article/details/gtnwioleyc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.daria6918.cn/Article/details/gtfdapvtji.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ybcxt.top/Article/details/gtnljqtybn.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.wangshuangyany.cn/Article/details/gtrrlnuhyt.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.mhx1999.top/Article/details/gtjxfuswmm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.havefunace.top/Article/details/gtdpeaxtiw.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cheryme.top/Article/details/gtllviuksk.html

[L06] 解析响应为 JSON
来源：http://dali.c1oappe.top/Article/details/gtoudaxezb.html

Py:   resp.json()
来源：http://dali.tanke756.top/Article/details/gtjbrvgzlx.html

PHP:  json_decode($body, true);
来源：http://dali.sysykeji.top/Article/details/gtcguckugh.html

JS:   await resp.json()
来源：http://dali.yj20258888.top/Article/details/gtfsegftbz.html

TS:   await resp.json()
来源：http://dali.ppjwa.cn/Article/details/gtbijdxhja.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hongshengwenyu.top/Article/details/gtxjzlqkle.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.feifeiyinyue.top/Article/details/gthrqwdejw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yonumen.top/Article/details/gtajtomqyt.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhixingplan.top/Article/details/gtcyjanylz.html

[L07] 处理 HTTP 状态码
来源：http://dali.gotoacloud.top/Article/details/gtrzlcozdx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.quarkkingdee.top/Article/details/gtxpotahzh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gtlzlhtien.html

JS:   resp.ok;  resp.status
来源：http://dali.sufxvd.cn/Article/details/gtrxpegxdb.html

TS:   resp.ok;  resp.status
来源：http://dali.pycfn.com/Article/details/gtsxekkxgs.html

Java: resp.statusCode()
来源：http://dali.zhongyouzk.top/Article/details/gtapzesxkq.html

Go:   resp.StatusCode
来源：http://dali.jianghu66.top/Article/details/gtlohlmxaw.html

Ruby: resp.code.to_i
来源：http://dali.wangshuangyany.cn/Article/details/gtgyccnyuv.html

C#:   (int)resp.StatusCode
来源：http://dali.ybcxt.top/Article/details/gtuwtmkxow.html

[L08] 并发请求多个地址
来源：http://dali.haohaochexian.top/Article/details/gtoeoombtv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhiwuduotai.top/Article/details/gtwaipqjif.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinqigfzy.top/Article/details/gtldhltndc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ivvv.top/Article/details/gtqsrnwbdr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shuidangran.top/Article/details/gtqqdjfljy.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shangyingyoupin.top/Article/details/gtqpevgdgn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cucudq.cn/Article/details/gtvemuzgvq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cheryme.top/Article/details/gtrixbywcg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtytcbzyso.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtkniofolj.html

M. 命令行 / 进程 / 环境
来源：http://dali.tian-w.cn/Article/details/gtuhjdrryo.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtasitttgu.html

[M01] 读取命令行参数
来源：http://dali.cqqwz.cn/Article/details/gtkceuycvd.html

Py:   sys.argv[1:]
来源：http://dali.fengsongda.top/Article/details/gtvgzialvm.html

PHP:  $argv;  $argc;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxzaswmxq.html

JS:   process.argv.slice(2)
来源：http://dali.ydzc1.top/Article/details/gtqputmynn.html

TS:   process.argv.slice(2)
来源：http://dali.dashuyun.cn/Article/details/gtanulclrg.html

Java: args 数组（main 方法参数）
来源：http://dali.jiagoushi.top/Article/details/gtennummhl.html

Go:   os.Args[1:]
来源：http://dali.yj20258888.top/Article/details/gtrtbosziy.html

Ruby: ARGV
来源：http://dali.xinyue.icu/Article/details/gtntbuzcbr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.quarkkingdee.top/Article/details/gtwdbvensz.html

[M02] 读取环境变量
来源：http://dali.yonumen.top/Article/details/gtmimcgkqh.html

Py:   os.environ.get("HOME")
来源：http://dali.zhixingplan.top/Article/details/gtnjirwhkf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.fzhhl.top/Article/details/gtxkgmbpxm.html

JS:   process.env.HOME
来源：http://dali.ppjwa.cn/Article/details/gtqwysnarz.html

TS:   process.env.HOME
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyqjbusip.html

Java: System.getenv("HOME")
来源：http://dali.mhx1999.top/Article/details/gtxiwbgolu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.9152youxi.cn/Article/details/gtvdmabqqt.html

Ruby: ENV["HOME"]
来源：http://dali.birdmap.top/Article/details/gtjbvzthup.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gtjzbvbvpl.html

[M03] 执行外部命令
来源：http://dali.kuanghao11.cn/Article/details/gtpfdipgqx.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shzxlz.cn/Article/details/gtpxbtlrgk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jyoumei.cn/Article/details/gtkyrmifhh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.aizwys.cn/Article/details/gtgwebigbn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnxiangtu.top/Article/details/gtoapbzkdv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sxryk.cn/Article/details/gtcipycckb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.0kj1m.cn/Article/details/gtbtwzblxl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.guowangkeji.top/Article/details/gtlicytgeh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hongshengwenyu.top/Article/details/gtoevyobsc.html

[M04] 获取当前工作目录
来源：http://dali.redwolf501.top/Article/details/gthpqcgwdv.html

Py:   os.getcwd()
来源：http://dali.ybcxt.top/Article/details/gtxnhyusud.html

PHP:  getcwd();
来源：http://dali.yj20258888.top/Article/details/gtsxprlxox.html

JS:   process.cwd()
来源：http://dali.zhongyouzk.top/Article/details/gtnujiefau.html

TS:   process.cwd()
来源：http://dali.redwolf501.top/Article/details/gtlbmyjkls.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yvedp.cn/Article/details/gtghiskxhq.html

Go:   os.Getwd()
来源：http://dali.pycfn.com/Article/details/gtrefstzjq.html

Ruby: Dir.pwd
来源：http://dali.shangyingyoupin.top/Article/details/gtjnjskctx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nanxinkj.top/Article/details/gtpeirfspz.html

[M05] 设置退出码
来源：http://dali.wangdashe.top/Article/details/gtfotfahum.html

Py:   sys.exit(1)
来源：http://dali.ydzc1.top/Article/details/gtmqcokyll.html

PHP:  exit(1);
来源：http://dali.gzhubu.top/Article/details/gtagjmjrbv.html

JS:   process.exit(1)
来源：http://dali.tian-w.cn/Article/details/gtsswsyxkc.html

TS:   process.exit(1)
来源：http://dali.andypj.xyz/Article/details/gtehsaquuk.html

Java: System.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gtkwxgdurb.html

Go:   os.Exit(1)
来源：http://dali.zdqjudy.top/Article/details/gtallhwcpx.html

Ruby: exit 1
来源：http://dali.fzhhl.top/Article/details/gtddknyjyg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.guowangkeji.top/Article/details/gtkroixgtp.html

[M06] 向标准错误输出
来源：http://dali.yanxiufei.cn/Article/details/gtnazobaka.html

Py:   print("err", file=sys.stderr)
来源：http://dali.vqdsnc.cn/Article/details/gtffnlptjt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.aibaodan.cn/Article/details/gtxtuxbdcc.html

JS:   console.error("err")
来源：http://dali.ybcxt.top/Article/details/gtsglhnnbw.html

TS:   console.error("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gthyxhswgh.html

Java: System.err.println("err")
来源：http://dali.tianlin.xyz/Article/details/gtbjkuqxyd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.daria6918.cn/Article/details/gtagsshkxc.html

Ruby: warn "err"
来源：http://dali.xuanzx.com/Article/details/gtiadektus.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tian-w.cn/Article/details/gtuneystsd.html

[M07] 判断是否为主入口
来源：http://dali.ppjwa.cn/Article/details/gtjzhpsirl.html

Py:   if __name__ == "__main__":
来源：http://dali.9152youxi.cn/Article/details/gtozieclgc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.vqdsnc.cn/Article/details/gtfvkcqfjy.html

JS:   require.main === module
来源：http://dali.haohaochexian.top/Article/details/gtzyeutcvr.html

TS:   require.main === module
来源：http://dali.sweek.top/Article/details/gtllnwokfn.html

Java: public static void main(String[] args)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqtxtueux.html

Go:   func main()
来源：http://dali.shuidangran.top/Article/details/gtechwrxvn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.andypj.xyz/Article/details/gtgkqqonfm.html

C#:   static void Main(string[] args)
来源：http://dali.jqgfzy.top/Article/details/gtqcbzcvyo.html

[M08] 获取系统与运行时信息
来源：http://dali.tianlin.xyz/Article/details/gtaaemrefg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ppjwa.cn/Article/details/gtzifdcqss.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shangyingyoupin.top/Article/details/gtbukoeepa.html

JS:   process.platform;  process.version
来源：http://dali.gogol.net.cn/Article/details/gtviysmqqg.html

TS:   process.platform;  process.version
来源：http://dali.yonumen.top/Article/details/gtjjvnxqwj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gogol.net.cn/Article/details/gtgiixbmqi.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.pengpengdd.cyou/Article/details/gtrgelzwdu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sufxvd.cn/Article/details/gtsgffkcnx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.daxiang520.top/Article/details/gtllmlnfvu.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gttsxuuxsf.html

N. 数据结构与算法
来源：http://dali.316326.xyz/Article/details/gtvsuqomof.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtctdqzfmy.html

[N01] 二分查找（有序数组）
来源：http://dali.xuetiantiany.cn/Article/details/gtmvvalxxp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gthayejiwq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.tianlin.xyz/Article/details/gtflinlmzh.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shangyingyoupin.top/Article/details/gtxukoksao.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ppjwa.cn/Article/details/gthdnqcrfa.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtebbsymxe.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtoxfcnajs.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.vqdsnc.cn/Article/details/gtaxdpdvwv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gtjdgyzlyq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yj20258.top/Article/details/gtpbqusrvw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cdnleiting.top/Article/details/gtemsvtnmf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yvedp.cn/Article/details/gtuaapidtf.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yvedp.cn/Article/details/gtjecdrvdj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.316326.xyz/Article/details/gtpocshrod.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yj202588.top/Article/details/gtnexkhnfu.html

Go:   slices.Sort(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtlnzrchnk.html

Ruby: arr.sort
来源：http://dali.pycfn.com/Article/details/gtgyiyaeia.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hongshengwenyu.top/Article/details/gtnrzqkxcf.html

[N03] 快速排序（分治示例）
来源：http://dali.zhixingplan.top/Article/details/gtxoltrayp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yonumen.top/Article/details/gtcdzwdjxl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zdqjudy.top/Article/details/gtgehtfbhs.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuxming.cn/Article/details/gtcxnbfvaj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.birdmap.top/Article/details/gtwbbuoumk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xuanzx.com/Article/details/gttnreyzmu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.nanxinkj.top/Article/details/gtdoxqudsy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.c1oappe.top/Article/details/gtdvphoqrl.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hnqzz.top/Article/details/gtsqdzqzud.html

[N04] 斐波那契数列
来源：http://dali.chenzaomai.com/Article/details/gtelikchjz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.nanxuanxn.top/Article/details/gtlwexldkz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yangfankeji.com/Article/details/gtqyvbfjpd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jlsjyb.cn/Article/details/gtupzhgtwr.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gtmbihxioh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shzxlz.cn/Article/details/gtkiktzght.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.meibo888.top/Article/details/gtxxqvnwfx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jianghu66.top/Article/details/gtoaavxlir.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gtuuwmglxy.html


<!-- 参考信息 -->