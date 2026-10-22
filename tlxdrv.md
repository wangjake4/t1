代发 wailian999

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ehwqpu.com/Article/details/gtddcxcbiv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinqigufen.top/Article/details/gtdaktormj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.chenjidiqi.icu/Article/details/gtlteonikt.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xuetiantiany.cn/Article/details/gtcwcklskc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtshbfupki.html

[J08] 提取年月日与星期
来源：http://dali.redwolf501.top/Article/details/gtcqhvbqvf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.aibaodan.cn/Article/details/gtvdbvfloq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.guowangkeji.top/Article/details/gtrjyqrpfd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.redwolf501.top/Article/details/gtyhuslcrq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.guannengcc.top/Article/details/gtlpialvun.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hywenlv.cn/Article/details/gtntbkzuet.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yueranfly.top/Article/details/gtoozyhqyt.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gogol.net.cn/Article/details/gtszefyvxk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.dashuyun.cn/Article/details/gtjmyuoveu.html

[J09] 时区处理
来源：http://dali.xuetiantiany.cn/Article/details/gtzioyiyca.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nwbrower.top/Article/details/gtdfsayqmb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.pycfn.com/Article/details/gtmyypilyg.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jianghu66.top/Article/details/gtznmvwuhl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ydzc1.top/Article/details/gtwdfaabac.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nanxinkj.top/Article/details/gtrpzkgvui.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jqgufenzy.top/Article/details/gtbpxewkhx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yongpay.top/Article/details/gtzebgtbic.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjhriocbm.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenjidiqi.icu/Article/details/gtzdmmlscq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.nanxinkj.top/Article/details/gtckhzcdyr.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yonumen.top/Article/details/gtvrsrsztq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyrodampt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtytkyaccm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xuanzx.com/Article/details/gtfhfxbibe.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xylfe.cn/Article/details/gtwrqekknz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.fzhhl.top/Article/details/gtthvbrbbr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jiagoushi.top/Article/details/gtveaigoyg.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtawqgdjqe.html

K. JSON 与序列化
来源：http://dali.jinqigfzy.top/Article/details/gtaynacecz.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtmlptband.html

[K01] 对象转 JSON 字符串
来源：http://dali.guowangkeji.top/Article/details/gtlvjaiull.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.smart0.xyz/Article/details/gthzywbuxa.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hfpthk.cn/Article/details/gtztjhuwpr.html

JS:   JSON.stringify(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtywjlmcgz.html

TS:   JSON.stringify(obj)
来源：http://dali.hammf.cn/Article/details/gtlvovskno.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.nanxuanxn.top/Article/details/gtsywqdfqr.html

Go:   json.Marshal(obj)
来源：http://dali.ppjwa.cn/Article/details/gtgzdlspuw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.fzhhl.top/Article/details/gtdzchnuby.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtpkdircpk.html

[K02] JSON 字符串转对象
来源：http://dali.tian-w.cn/Article/details/gtiieyxrdf.html

Py:   json.loads(s)
来源：http://dali.dianchejie.cn/Article/details/gtoeiazskx.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhijiandao.cn/Article/details/gtztwbibwz.html

JS:   JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gtcynwyqju.html

TS:   JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gtujxipvkv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jqgfzy.top/Article/details/gtlqnhndgw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.tanke756.top/Article/details/gtxeekbyjs.html

Ruby: JSON.parse(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdgagvuio.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ivvv.top/Article/details/gtvzgjernx.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.quarkkingdee.top/Article/details/gtwccxdrly.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.aizwys.cn/Article/details/gtdfkunzao.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jlsjyb.cn/Article/details/gtxnrhqwoc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgufenzy.top/Article/details/gtzpshjnxn.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jyoumei.cn/Article/details/gtklthwlgl.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tian-w.cn/Article/details/gtbscohnhc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jqgfzy.top/Article/details/gtnnjahzmc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cheryme.top/Article/details/gtuhkhtchf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.dashuyun.cn/Article/details/gtdwotkxfe.html

[K04] 读取 JSON 文件
来源：http://dali.0kj1m.cn/Article/details/gtmdjeoboq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.daria6918.cn/Article/details/gtquqincjn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.pycfn.com/Article/details/gthvcvaxdy.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shuidangran.top/Article/details/gtdvlfhntc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.meibo888.top/Article/details/gtcnchfdfo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sysykeji.top/Article/details/gtodomrxga.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqxilxxau.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinqigfzy.top/Article/details/gtgoqhdrds.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gotoacloud.top/Article/details/gttupbufod.html

[K05] 深拷贝对象
来源：http://dali.ehwqpu.com/Article/details/gtddarhjvs.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtqdvorhtd.html

PHP:  unserialize(serialize($obj));
来源：http://dali.meibo888.top/Article/details/gtsvauaemy.html

JS:   structuredClone(obj)
来源：http://dali.jinqigufen.top/Article/details/gtzpnbqupm.html

TS:   structuredClone(obj)
来源：http://dali.yuxming.cn/Article/details/gtfhivlnzm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinyuanbaomall.cn/Article/details/gtclphnswd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jlsjyb.cn/Article/details/gtrsqwqlum.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.316326.xyz/Article/details/gtxyocsgdz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sxryk.cn/Article/details/gtkopjinyr.html

[K06] 解析 URL 查询串
来源：http://dali.svipenyu.cn/Article/details/gtmehiyjad.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xuetiantiany.cn/Article/details/gtnjgsweku.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hysaishi.cn/Article/details/gtjmfjdxxv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfwghypvb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258.top/Article/details/gtyhkzesco.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.smart0.xyz/Article/details/gtewskcaod.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yonumen.top/Article/details/gtbjdubkfx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.nanxuanxn.top/Article/details/gtcdatzcdk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.nanxinkj.top/Article/details/gtnwomabjj.html

[K07] 进制转换
来源：http://dali.jinqigufen.top/Article/details/gttzaywpoa.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gtsyuzhipt.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.birdmap.top/Article/details/gtksevcxit.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtderlpfpp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gtetirsaut.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gttuhyoyaa.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ybcxt.top/Article/details/gtpwcsmkcb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.havefunace.top/Article/details/gtkcyccrqo.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.birdmap.top/Article/details/gturzmwsfl.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.guowangkeji.top/Article/details/gtpczycmxb.html

Py:   pickle.dumps(obj)
来源：http://dali.yj20258888.top/Article/details/gtsoppxzyw.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.redwolf501.top/Article/details/gtpklcouax.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jqgfzy.top/Article/details/gtfthmaelo.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ybcxt.top/Article/details/gtadyeinih.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ehwqpu.com/Article/details/gtkkesvoei.html

Go:   encoding/gob
来源：http://dali.aizwys.cn/Article/details/gtvpyxirbv.html

Ruby: Marshal.dump(obj)
来源：http://dali.cucudq.cn/Article/details/gtcirvkwyj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhengqikj.top/Article/details/gtgbwsxiue.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gttiqgeolq.html

L. 网络请求
来源：http://dali.havefunace.top/Article/details/gtoyroripm.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gthosjwead.html

[L01] 发送 GET 请求
来源：http://dali.yvedp.cn/Article/details/gtnoewfucd.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xinyue.icu/Article/details/gtnpsklcwf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.0kj1m.cn/Article/details/gtzaxkkpvv.html

JS:   await fetch(url)
来源：http://dali.zdqjudy.top/Article/details/gtdvdogoin.html

TS:   await fetch(url)
来源：http://dali.pycfn.com/Article/details/gtnaxgrppo.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.chenzaomai.com/Article/details/gtdwitxylb.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinqigfzy.top/Article/details/gtqdriftzn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqtzavziq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.tanke756.top/Article/details/gtzrnnbict.html

[L02] 发送 POST JSON
来源：http://dali.gogol.net.cn/Article/details/gtsyxqdxqv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.dianchejie.cn/Article/details/gtsddhbnbr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shuidangran.top/Article/details/gtevkttdyg.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hongshengwenyu.top/Article/details/gtfvosuiqy.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigfzy.top/Article/details/gtflhvsoxh.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.dianchejie.cn/Article/details/gthmfpdino.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinqigufen.top/Article/details/gthlhegfzg.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.andypj.xyz/Article/details/gtkulwkrko.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gzhubu.top/Article/details/gtcmwgpsbv.html

[L03] 设置自定义请求头
来源：http://dali.bjfxy.top/Article/details/gtjorixodu.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cucudq.cn/Article/details/gtuspsgaqn.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.kuanghao11.cn/Article/details/gtllvamxeh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.snrcjt.cn/Article/details/gtefsvbuhu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangtech.top/Article/details/gtrkuofuwg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yvedp.cn/Article/details/gtiruegqqa.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.redwolf501.top/Article/details/gtfdjhqxjh.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.havefunace.top/Article/details/gthjhkvann.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gotoacloud.top/Article/details/gtzdbfgeok.html

[L04] 设置超时
来源：http://dali.shuidangran.top/Article/details/gtfmztomlc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.316326.xyz/Article/details/gtcleooxao.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sxryk.cn/Article/details/gtsuyffjkd.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fzhhl.top/Article/details/gtrcfghsmg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.9152youxi.cn/Article/details/gtogcpmbma.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.haohaochexian.top/Article/details/gthzrnksvu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shuidangran.top/Article/details/gtynxuxkqt.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.c1oappe.top/Article/details/gtaeudypdq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.mhx1999.top/Article/details/gtxzqukhnv.html

[L05] 上传文件（multipart）
来源：http://dali.xylfe.cn/Article/details/gtpjfuhpog.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.smart0.xyz/Article/details/gtjllxtjvc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gotoacloud.top/Article/details/gtrvvnvjaj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shangyingyoupin.top/Article/details/gtgyhwdusa.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cdnleiting.top/Article/details/gtqqsyxdhk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.316326.xyz/Article/details/gtaikvinjj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.smart0.xyz/Article/details/gtpvfgerps.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.vqdsnc.cn/Article/details/gttyeumcxe.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtdjohywzw.html

[L06] 解析响应为 JSON
来源：http://dali.hnqzz.top/Article/details/gtpkouevhi.html

Py:   resp.json()
来源：http://dali.wangshuangyany.cn/Article/details/gtsnofxutp.html

PHP:  json_decode($body, true);
来源：http://dali.gzhubu.top/Article/details/gtidzovqew.html

JS:   await resp.json()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsbucckib.html

TS:   await resp.json()
来源：http://dali.ehwqpu.com/Article/details/gtmozwdzsw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shzxlz.cn/Article/details/gtkopogxmz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.andypj.xyz/Article/details/gtorwfbhfz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.9152youxi.cn/Article/details/gtxizetkdh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zdqjudy.top/Article/details/gtiwlbjliq.html

[L07] 处理 HTTP 状态码
来源：http://dali.hnxiangtu.top/Article/details/gtalillhpx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhengqikj.top/Article/details/gtjdvsmwxj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jyoumei.cn/Article/details/gtwcynedzx.html

JS:   resp.ok;  resp.status
来源：http://dali.jinqigfzy.top/Article/details/gtanayvjru.html

TS:   resp.ok;  resp.status
来源：http://dali.gaohongyu789.top/Article/details/gtltyirnsf.html

Java: resp.statusCode()
来源：http://dali.316326.xyz/Article/details/gtuqfnzatc.html

Go:   resp.StatusCode
来源：http://dali.xuanzx.com/Article/details/gtjogxhkez.html

Ruby: resp.code.to_i
来源：http://dali.xylfe.cn/Article/details/gtyodqwybb.html

C#:   (int)resp.StatusCode
来源：http://dali.feifeiyinyue.top/Article/details/gtjxmagqee.html

[L08] 并发请求多个地址
来源：http://dali.iojbl.cn/Article/details/gteznqzjez.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.vqdsnc.cn/Article/details/gtvjauwmuj.html

PHP:  curl_multi_init() 系列
来源：http://dali.svipenyu.cn/Article/details/gteexjhvgt.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.feifeiyinyue.top/Article/details/gtwtzytlsx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daxiang520.top/Article/details/gtcqiocprm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.wangdashe.top/Article/details/gtkqtggvgk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrmttemjm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xylfe.cn/Article/details/gtzvybpkcu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tian-w.cn/Article/details/gtwiylfzaf.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gteiexznaa.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhaomingkeji.xyz/Article/details/gttydbrizx.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtjasytznh.html

[M01] 读取命令行参数
来源：http://dali.nwbrower.top/Article/details/gtbbhrawkc.html

Py:   sys.argv[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gtdsfyqbog.html

PHP:  $argv;  $argc;
来源：http://dali.guowangkeji.top/Article/details/gtmjopvnrt.html

JS:   process.argv.slice(2)
来源：http://dali.cqqwz.cn/Article/details/gtxnutmcey.html

TS:   process.argv.slice(2)
来源：http://dali.316326.xyz/Article/details/gtbnibhqcn.html

Java: args 数组（main 方法参数）
来源：http://dali.yuanzhike.top/Article/details/gtskofzhiy.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gtjqrujfjj.html

Ruby: ARGV
来源：http://dali.yvedp.cn/Article/details/gtxvzvnorn.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ybcxt.top/Article/details/gtxqqhhqwg.html

[M02] 读取环境变量
来源：http://dali.redwolf501.top/Article/details/gtlehpfgvm.html

Py:   os.environ.get("HOME")
来源：http://dali.yueranfly.top/Article/details/gtwmqbxzso.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ivvv.top/Article/details/gtfyfnvrlo.html

JS:   process.env.HOME
来源：http://dali.pycfn.com/Article/details/gtrgsrnsjg.html

TS:   process.env.HOME
来源：http://dali.tianlin.xyz/Article/details/gtqblioxkl.html

Java: System.getenv("HOME")
来源：http://dali.cucudq.cn/Article/details/gtpystzacp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.mhx1999.top/Article/details/gtjtarvmdp.html

Ruby: ENV["HOME"]
来源：http://dali.yj20258888.top/Article/details/gtcfnqicbq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jiagoushi.top/Article/details/gtgckcqalz.html

[M03] 执行外部命令
来源：http://dali.jinqigufen.top/Article/details/gtqwhrxbgb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yj202588.top/Article/details/gthsxemluy.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.9152youxi.cn/Article/details/gtluavomxx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.tianlin.xyz/Article/details/gthrxnalan.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sxryk.cn/Article/details/gtpasoouqw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.pengpengdd.cyou/Article/details/gtabizcjoi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cashguo.top/Article/details/gtgestrchv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.aizwys.cn/Article/details/gtrbxoxiou.html

C#:   Process.Start("ls", "-l");
来源：http://dali.dianchejie.cn/Article/details/gtjgckjezd.html

[M04] 获取当前工作目录
来源：http://dali.yangfankeji.com/Article/details/gtzmrimggx.html

Py:   os.getcwd()
来源：http://dali.yj202588.top/Article/details/gtfffzkhow.html

PHP:  getcwd();
来源：http://dali.ybcxt.top/Article/details/gtnhybonhm.html

JS:   process.cwd()
来源：http://dali.hnxiangtu.top/Article/details/gtnkstghcp.html

TS:   process.cwd()
来源：http://dali.dianchejie.cn/Article/details/gtqjpmjfoq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jianghu66.top/Article/details/gtxvllccao.html

Go:   os.Getwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmmrnulwu.html

Ruby: Dir.pwd
来源：http://dali.cucudq.cn/Article/details/gtjnacuvkd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cucudq.cn/Article/details/gtglbzndps.html

[M05] 设置退出码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbdkfrlsk.html

Py:   sys.exit(1)
来源：http://dali.jqgfzy.top/Article/details/gtkhcfdxtp.html

PHP:  exit(1);
来源：http://dali.jiagoushi.top/Article/details/gtqgrlzuid.html

JS:   process.exit(1)
来源：http://dali.yuxming.cn/Article/details/gtpsnztpmv.html

TS:   process.exit(1)
来源：http://dali.bjfxy.top/Article/details/gtjjsoqxrq.html

Java: System.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gtexdfgjja.html

Go:   os.Exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtdgtvbmry.html

Ruby: exit 1
来源：http://dali.zhengqikj.top/Article/details/gtebdgqdfb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xziqi.cn/Article/details/gtmbwapvfg.html

[M06] 向标准错误输出
来源：http://dali.pengpengdd.cyou/Article/details/gtnamqimfk.html

Py:   print("err", file=sys.stderr)
来源：http://dali.316326.xyz/Article/details/gtxifuvcfy.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sysykeji.top/Article/details/gtdwerxmfm.html

JS:   console.error("err")
来源：http://dali.daria6918.cn/Article/details/gtwfakbtgk.html

TS:   console.error("err")
来源：http://dali.jqgufenzy.top/Article/details/gtjgndlkbo.html

Java: System.err.println("err")
来源：http://dali.jiagoushi.top/Article/details/gtsonwrnzh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hysaishi.cn/Article/details/gtndwpmlne.html

Ruby: warn "err"
来源：http://dali.zycfv.cn/Article/details/gtbzpmklhy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhoulong.xyz/Article/details/gtruailhos.html

[M07] 判断是否为主入口
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsuygrboe.html

Py:   if __name__ == "__main__":
来源：http://dali.redwolf501.top/Article/details/gtqpdexcjb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xziqi.cn/Article/details/gtdmqoncmm.html

JS:   require.main === module
来源：http://dali.nwbrower.top/Article/details/gtptiaesjx.html

TS:   require.main === module
来源：http://dali.feifeiyinyue.top/Article/details/gtrmoikvke.html

Java: public static void main(String[] args)
来源：http://dali.smart0.xyz/Article/details/gtxqldtbak.html

Go:   func main()
来源：http://dali.kuanghao11.cn/Article/details/gtiqurjadn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hammf.cn/Article/details/gtnasdnfjt.html

C#:   static void Main(string[] args)
来源：http://dali.redwolf501.top/Article/details/gtrieporia.html

[M08] 获取系统与运行时信息
来源：http://dali.zhongyouzk.top/Article/details/gtolvhcape.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jianghu66.top/Article/details/gtdnpwmfdf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cheryme.top/Article/details/gtrcbitiub.html

JS:   process.platform;  process.version
来源：http://dali.yueranfly.top/Article/details/gtptgthenm.html

TS:   process.platform;  process.version
来源：http://dali.dashuyun.cn/Article/details/gtuernvwmf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.wangdashe.top/Article/details/gtsdzipmfo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hfpthk.cn/Article/details/gtwweeqnpu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shuidangran.top/Article/details/gtmypmngcf.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shanyushiyangtech.top/Article/details/gtnxcpflti.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtcbgvrxfn.html

N. 数据结构与算法
来源：http://dali.yanxiufei.cn/Article/details/gtqjhpiykz.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtxslvdkae.html

[N01] 二分查找（有序数组）
来源：http://dali.chenjidiqi.icu/Article/details/gtdqolxtsp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hnqzz.top/Article/details/gtowkdnlep.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yongpay.top/Article/details/gtryfocvxa.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xinyue.icu/Article/details/gtcnnwzoyu.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.meibo888.top/Article/details/gtsqtaodgk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtfejuyihe.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ivvv.top/Article/details/gtmduosfge.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.tianlin.xyz/Article/details/gtduxxultr.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gtwwivlsit.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yj20258888.top/Article/details/gthzuhcyeh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkjskcygr.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jyoumei.cn/Article/details/gtkgljtihy.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jiagoushi.top/Article/details/gtgsefemcg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zycfv.cn/Article/details/gtfjqaoydm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.wangdashe.top/Article/details/gtmhxemlup.html

Go:   slices.Sort(arr)
来源：http://dali.xziqi.cn/Article/details/gtyttophzs.html

Ruby: arr.sort
来源：http://dali.jqgufenzy.top/Article/details/gtzayrxshz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.0kj1m.cn/Article/details/gtvbzmlzjy.html

[N03] 快速排序（分治示例）
来源：http://dali.c1oappe.top/Article/details/gtjnwkwfxr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.c1oappe.top/Article/details/gtrpiccaoc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gogol.net.cn/Article/details/gtxxljufin.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.snrcjt.cn/Article/details/gtnwfodejv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cashguo.top/Article/details/gtlmpbzuzd.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.kuanghao11.cn/Article/details/gtryqetytb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gtgaugmfji.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ivvv.top/Article/details/gtdcgchzad.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shanyushiyangtech.top/Article/details/gtjfaqcrcx.html

[N04] 斐波那契数列
来源：http://dali.gotoacloud.top/Article/details/gtkenzzyzj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.havefunace.top/Article/details/gtgnuzvjhj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhixingplan.top/Article/details/gthfxxrdsn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gtwcuhnupl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.birdmap.top/Article/details/gtwcromaku.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xuetiantiany.cn/Article/details/gtdafwqgep.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ivvv.top/Article/details/gtzzozgosd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258888.top/Article/details/gtntnhjgzk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gtoxeidiqx.html

[N05] 最大公约数
来源：http://dali.jinqigufen.top/Article/details/gtllkwrrrj.html

Py:   math.gcd(a, b)
来源：http://dali.guowangkeji.top/Article/details/gtkkdcrrxy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jianghu66.top/Article/details/gttbayhclu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tianlin.xyz/Article/details/gtetbedxya.html


<!-- 参考信息 -->