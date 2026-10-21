代发 wailian999

[J07] 比较两个日期
来源：http://dali.ybcxt.top/Article/details/gtjnjftvuw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xziqi.cn/Article/details/gtjlxjfqwp.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hfpthk.cn/Article/details/gtytyhfczc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258.top/Article/details/gtnbghmrdw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.316326.xyz/Article/details/gtpxxptnaq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hnqzz.top/Article/details/gtekhufllu.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sxryk.cn/Article/details/gttanyrlct.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xuanzx.com/Article/details/gtpszhafdv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gtfpozmaax.html

[J08] 提取年月日与星期
来源：http://dali.kuanghao11.cn/Article/details/gtjqwgvzaj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sxryk.cn/Article/details/gtandbfaxm.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.c1oappe.top/Article/details/gtijdvdsvx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jqgufenzy.top/Article/details/gtafkghyes.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nanxuanxn.top/Article/details/gtqbzgaxtm.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.quarkkingdee.top/Article/details/gtemysnatb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.guowangkeji.top/Article/details/gtqmkispio.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinqigufen.top/Article/details/gtdfrwoddr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xziqi.cn/Article/details/gtcyfnloqy.html

[J09] 时区处理
来源：http://dali.yueranfly.top/Article/details/gtucvprwhk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.dashuyun.cn/Article/details/gtodyemkkb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.9152youxi.cn/Article/details/gtjqcowvhw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.316326.xyz/Article/details/gtfwpxwwmz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhoulong.xyz/Article/details/gtuvphwcqe.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinghuilouyu.cn/Article/details/gtceshdozz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.chenjidiqi.icu/Article/details/gtvhvioury.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.0kj1m.cn/Article/details/gtvjvlvujr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hywenlv.cn/Article/details/gtiybtnpjh.html

[J10] 取今天 / 本月第一天
来源：http://dali.guowangkeji.top/Article/details/gtqgsarjum.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.dianchejie.cn/Article/details/gtasekbhjp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ivvv.top/Article/details/gtfveszcif.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.smart0.xyz/Article/details/gthwoiqmzb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj20258888.top/Article/details/gtoriceeoq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gogol.net.cn/Article/details/gttfiltfnb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.316326.xyz/Article/details/gtfojglzdl.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.dashuyun.cn/Article/details/gtycyuffbr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yj20258.top/Article/details/gtqpnqschw.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtkmmqjkca.html

K. JSON 与序列化
来源：http://dali.0kj1m.cn/Article/details/gtobnslspo.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtijdklzdi.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhengqikj.top/Article/details/gtmmhmgrla.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtogymwtse.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.daria6918.cn/Article/details/gtgtmkpztd.html

JS:   JSON.stringify(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtmzgnsktl.html

TS:   JSON.stringify(obj)
来源：http://dali.ivvv.top/Article/details/gtxzsmujsg.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xuanzx.com/Article/details/gtztiggpxu.html

Go:   json.Marshal(obj)
来源：http://dali.gotoacloud.top/Article/details/gtmzyfgnez.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hnqzz.top/Article/details/gtcaqctdpy.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shuidangran.top/Article/details/gtfolqywkr.html

[K02] JSON 字符串转对象
来源：http://dali.gogol.net.cn/Article/details/gtazjpvtoa.html

Py:   json.loads(s)
来源：http://dali.nanxinkj.top/Article/details/gtmrlyhvap.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yj20258888.top/Article/details/gtxedamnzy.html

JS:   JSON.parse(s)
来源：http://dali.hfpthk.cn/Article/details/gtgzitmghj.html

TS:   JSON.parse(s)
来源：http://dali.zdqjudy.top/Article/details/gtbwvrtuea.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hammf.cn/Article/details/gtdytsuadi.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jqgfzy.top/Article/details/gtkaauykry.html

Ruby: JSON.parse(s)
来源：http://dali.gogol.net.cn/Article/details/gtdfokmujn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.chenlongwang.top/Article/details/gteipiuvfb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.haohaochexian.top/Article/details/gtyfzhftkf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.bjfxy.top/Article/details/gtqknrimhl.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjgjcjjbd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.vqdsnc.cn/Article/details/gtsuseugew.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.quarkkingdee.top/Article/details/gtpvuaohat.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtjkkrppgz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yuxming.cn/Article/details/gtabirebsu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.0kj1m.cn/Article/details/gtaygsyuwr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shzxlz.cn/Article/details/gtdpvbhind.html

[K04] 读取 JSON 文件
来源：http://dali.snrcjt.cn/Article/details/gtijhrikei.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yvedp.cn/Article/details/gtoykqiykc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yongpay.top/Article/details/gtclrkbuae.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pycfn.com/Article/details/gtdxduyjmu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hysaishi.cn/Article/details/gtjjefehvc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.9152youxi.cn/Article/details/gtmfwqggud.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hywenlv.cn/Article/details/gtndubvhve.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yuanzhike.top/Article/details/gtchvmezpb.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cdnleiting.top/Article/details/gtixcebcgf.html

[K05] 深拷贝对象
来源：http://dali.havefunace.top/Article/details/gtazgnwpiu.html

Py:   copy.deepcopy(obj)
来源：http://dali.xinyue.icu/Article/details/gtabamxtlv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jyoumei.cn/Article/details/gtyhtxwyou.html

JS:   structuredClone(obj)
来源：http://dali.sysykeji.top/Article/details/gtnugyuixl.html

TS:   structuredClone(obj)
来源：http://dali.tianlin.xyz/Article/details/gtyhntruqe.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.vqdsnc.cn/Article/details/gtoddtpuug.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cqqwz.cn/Article/details/gtdqthzdnb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gaohongyu789.top/Article/details/gtgmkqbryr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinqigufen.top/Article/details/gtsavarbuj.html

[K06] 解析 URL 查询串
来源：http://dali.aizwys.cn/Article/details/gttwrlukzd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.havefunace.top/Article/details/gtkhdsbdei.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.havefunace.top/Article/details/gtxcdadqyf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cucudq.cn/Article/details/gttbklpptj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ybcxt.top/Article/details/gtwqmidwvb.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yj20258.top/Article/details/gtntmfjhxf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yanxiufei.cn/Article/details/gtcfofqkmv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gtipgfhqet.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ehwqpu.com/Article/details/gtbywnkxcb.html

[K07] 进制转换
来源：http://dali.xinyue.icu/Article/details/gtaywtwgey.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gtftxncywl.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.aibaodan.cn/Article/details/gthvukgyuc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gtbbxtrhtp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gtbnteclxl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.316326.xyz/Article/details/gtkzonkxba.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jyoumei.cn/Article/details/gtecvkpizs.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yanxiufei.cn/Article/details/gtldnqyqqc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gtayrodhav.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.bjfxy.top/Article/details/gtndwhnnmc.html

Py:   pickle.dumps(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtaoeaipct.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtapihbizk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gotoacloud.top/Article/details/gtthocbhsf.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.pengpengdd.cyou/Article/details/gtnqdgaokz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.nwbrower.top/Article/details/gtrnrcbede.html

Go:   encoding/gob
来源：http://dali.redwolf501.top/Article/details/gtzpbgwpqu.html

Ruby: Marshal.dump(obj)
来源：http://dali.gotoacloud.top/Article/details/gtoxjuoknx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ydzc1.top/Article/details/gtrsumtcgp.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtpzabqktl.html

L. 网络请求
来源：http://dali.sufxvd.cn/Article/details/gtmpvmgjkt.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtfppxypdy.html

[L01] 发送 GET 请求
来源：http://dali.yangfankeji.com/Article/details/gtoqlqhfcu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.kuanghao11.cn/Article/details/gtvxhtodiy.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cheryme.top/Article/details/gtwbpmxxiz.html

JS:   await fetch(url)
来源：http://dali.zhiwuduotai.top/Article/details/gtgvbrackf.html

TS:   await fetch(url)
来源：http://dali.hammf.cn/Article/details/gtfijgrdqt.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.0kj1m.cn/Article/details/gtunznnbgf.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gtwujoplsl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cdnleiting.top/Article/details/gtmzzjgkxe.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ydzc1.top/Article/details/gtjooycgpl.html

[L02] 发送 POST JSON
来源：http://dali.zycfv.cn/Article/details/gteqqverph.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.dashuyun.cn/Article/details/gtwmqrxwto.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cqqwz.cn/Article/details/gtyrolfobr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cdnleiting.top/Article/details/gtnbbzwrev.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yanxiufei.cn/Article/details/gtcaajrlqv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.316326.xyz/Article/details/gtlkopjnjr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.c1oappe.top/Article/details/gtkizsglzx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.chenjidiqi.icu/Article/details/gtvapypqxx.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgotulaln.html

[L03] 设置自定义请求头
来源：http://dali.snrcjt.cn/Article/details/gtwbyjpscb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcimitwtw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenlongwang.top/Article/details/gtubtosjpo.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdboogtup.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fengsongda.top/Article/details/gtxpsgeoud.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.316326.xyz/Article/details/gtoyfstfpw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zdqjudy.top/Article/details/gtpqcdbuhy.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ivvv.top/Article/details/gtkeshaqhg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.guowangkeji.top/Article/details/gtodpbqkmp.html

[L04] 设置超时
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvpszwljj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yj20258888.top/Article/details/gtxuawjrdi.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yuanzhike.top/Article/details/gtdcjfxoxg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cdnleiting.top/Article/details/gtfzsqdrph.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shangyingyoupin.top/Article/details/gtvzeoueti.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.aizwys.cn/Article/details/gtuusfrkez.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zdqjudy.top/Article/details/gttpqeymsv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cheryme.top/Article/details/gtjverwqyo.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.9152youxi.cn/Article/details/gtkuzfajwl.html

[L05] 上传文件（multipart）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvsktamse.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sweek.top/Article/details/gtjtwpktkp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cdnleiting.top/Article/details/gtjggarvbk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.fzhhl.top/Article/details/gtdbtotfcg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenzaomai.com/Article/details/gtezfrzybw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gaohongyu789.top/Article/details/gtokxaoobf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.chenjidiqi.icu/Article/details/gtozekaktr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ybcxt.top/Article/details/gtkycjaeop.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.pycfn.com/Article/details/gtoruepmfy.html

[L06] 解析响应为 JSON
来源：http://dali.quarkkingdee.top/Article/details/gtuxutkelc.html

Py:   resp.json()
来源：http://dali.tian-w.cn/Article/details/gtufygmobc.html

PHP:  json_decode($body, true);
来源：http://dali.andypj.xyz/Article/details/gtytxstzga.html

JS:   await resp.json()
来源：http://dali.c1oappe.top/Article/details/gtrliiynwy.html

TS:   await resp.json()
来源：http://dali.yuanzhike.top/Article/details/gtxtlmddao.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.9152youxi.cn/Article/details/gtjllzsskv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.pengpengdd.cyou/Article/details/gtnplkelic.html

Ruby: JSON.parse(resp.body)
来源：http://dali.c1oappe.top/Article/details/gtjasobnmk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnbqqkicg.html

[L07] 处理 HTTP 状态码
来源：http://dali.jlsjyb.cn/Article/details/gtyarvjvka.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xuanzx.com/Article/details/gtwgvdofxg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.birdmap.top/Article/details/gtepiqfulz.html

JS:   resp.ok;  resp.status
来源：http://dali.chenlongwang.top/Article/details/gtxztyybks.html

TS:   resp.ok;  resp.status
来源：http://dali.jianghu66.top/Article/details/gtpwfeimnj.html

Java: resp.statusCode()
来源：http://dali.wangdashe.top/Article/details/gtpfjkxqqg.html

Go:   resp.StatusCode
来源：http://dali.yanxiufei.cn/Article/details/gtjrmgcqec.html

Ruby: resp.code.to_i
来源：http://dali.zhaomingkeji.xyz/Article/details/gtarzgnjoj.html

C#:   (int)resp.StatusCode
来源：http://dali.smart0.xyz/Article/details/gtgvugnnmq.html

[L08] 并发请求多个地址
来源：http://dali.chenjidiqi.icu/Article/details/gtqgvfvpjp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ydzc1.top/Article/details/gtmbbudybq.html

PHP:  curl_multi_init() 系列
来源：http://dali.cqqwz.cn/Article/details/gtlwakutum.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hfpthk.cn/Article/details/gtvtdjouuh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ivvv.top/Article/details/gtaliqszcz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpzmhimfp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.andypj.xyz/Article/details/gtwtlydyew.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.chenjidiqi.icu/Article/details/gtnodmszqw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.nwbrower.top/Article/details/gtoqwpyywx.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtxvlsixmt.html

M. 命令行 / 进程 / 环境
来源：http://dali.aizwys.cn/Article/details/gtwowjcfgd.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gthvlrmvyh.html

[M01] 读取命令行参数
来源：http://dali.hnqzz.top/Article/details/gtrpcvcsko.html

Py:   sys.argv[1:]
来源：http://dali.ppjwa.cn/Article/details/gtbftzqrho.html

PHP:  $argv;  $argc;
来源：http://dali.quarkkingdee.top/Article/details/gtclekmpiq.html

JS:   process.argv.slice(2)
来源：http://dali.hfpthk.cn/Article/details/gtiochbfek.html

TS:   process.argv.slice(2)
来源：http://dali.mhx1999.top/Article/details/gtkdzlaqgi.html

Java: args 数组（main 方法参数）
来源：http://dali.jinqigufen.top/Article/details/gtgdgozvfr.html

Go:   os.Args[1:]
来源：http://dali.gotoacloud.top/Article/details/gtitxryiri.html

Ruby: ARGV
来源：http://dali.aibaodan.cn/Article/details/gtfxoyvtck.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cucudq.cn/Article/details/gtvubvqfcu.html

[M02] 读取环境变量
来源：http://dali.sweek.top/Article/details/gthhswmpmm.html

Py:   os.environ.get("HOME")
来源：http://dali.aibaodan.cn/Article/details/gtjpaxjoys.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.c1oappe.top/Article/details/gtfkzkoygl.html

JS:   process.env.HOME
来源：http://dali.aizwys.cn/Article/details/gtpozjcaiu.html

TS:   process.env.HOME
来源：http://dali.havefunace.top/Article/details/gtquuoodhe.html

Java: System.getenv("HOME")
来源：http://dali.daria6918.cn/Article/details/gtplthzuyw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gtvupufdjd.html

Ruby: ENV["HOME"]
来源：http://dali.jlsjyb.cn/Article/details/gtkzpuhdpg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gtutbrtmsi.html

[M03] 执行外部命令
来源：http://dali.shzxlz.cn/Article/details/gtuuuwuwqr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cucudq.cn/Article/details/gtbvessukj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shangyingyoupin.top/Article/details/gtkscsbtyo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.haohaochexian.top/Article/details/gtbtommixo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhiwuduotai.top/Article/details/gteutbevez.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.chenjidiqi.icu/Article/details/gtobmmpmtd.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xuetiantiany.cn/Article/details/gtclutyjzu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shanyushiyangtech.top/Article/details/gtnfdbgnfp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.nwbrower.top/Article/details/gtcgkkkrxs.html

[M04] 获取当前工作目录
来源：http://dali.zhiwuduotai.top/Article/details/gtepauxefd.html

Py:   os.getcwd()
来源：http://dali.meibo888.top/Article/details/gtudpheitx.html

PHP:  getcwd();
来源：http://dali.zhoulong.xyz/Article/details/gtwszqpzdz.html

JS:   process.cwd()
来源：http://dali.tian-w.cn/Article/details/gtxhlxlmkd.html

TS:   process.cwd()
来源：http://dali.chenlongwang.top/Article/details/gtqunzaufe.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gotoacloud.top/Article/details/gtwbfrgbfd.html

Go:   os.Getwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnxnjdxyd.html

Ruby: Dir.pwd
来源：http://dali.yj20258.top/Article/details/gtaaxdhiba.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cqqwz.cn/Article/details/gttskgligz.html

[M05] 设置退出码
来源：http://dali.shanyushiyangtech.top/Article/details/gtfhjviwko.html

Py:   sys.exit(1)
来源：http://dali.ivvv.top/Article/details/gtdkzxaeka.html

PHP:  exit(1);
来源：http://dali.zhengqikj.top/Article/details/gtvtkonqal.html

JS:   process.exit(1)
来源：http://dali.xziqi.cn/Article/details/gtdxsfuhhm.html

TS:   process.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gtyhqqckdt.html

Java: System.exit(1)
来源：http://dali.shuidangran.top/Article/details/gtzflgltsg.html

Go:   os.Exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtzvkmbgst.html

Ruby: exit 1
来源：http://dali.gaohongyu789.top/Article/details/gthxcczmnw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.dianchejie.cn/Article/details/gttnpdcnnw.html

[M06] 向标准错误输出
来源：http://dali.sweek.top/Article/details/gtfziogrfa.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cucudq.cn/Article/details/gtpdshuidw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.nwbrower.top/Article/details/gtegxhvsku.html

JS:   console.error("err")
来源：http://dali.yuanzhike.top/Article/details/gtrdtwfsts.html

TS:   console.error("err")
来源：http://dali.jqgfzy.top/Article/details/gtjqcqsbws.html

Java: System.err.println("err")
来源：http://dali.dianchejie.cn/Article/details/gtmuvamgkn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zdqjudy.top/Article/details/gtpoyctkji.html

Ruby: warn "err"
来源：http://dali.yangfankeji.com/Article/details/gtupindqjy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.pengpengdd.cyou/Article/details/gtuouvnuaw.html

[M07] 判断是否为主入口
来源：http://dali.zhongyouzk.top/Article/details/gtckuwewfk.html

Py:   if __name__ == "__main__":
来源：http://dali.iojbl.cn/Article/details/gtalqwkiwi.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hfpthk.cn/Article/details/gttardlozu.html

JS:   require.main === module
来源：http://dali.jyoumei.cn/Article/details/gtxmvswmzr.html

TS:   require.main === module
来源：http://dali.pycfn.com/Article/details/gtytoabfqt.html

Java: public static void main(String[] args)
来源：http://dali.ivvv.top/Article/details/gtudlilxcd.html

Go:   func main()
来源：http://dali.gaohongyu789.top/Article/details/gthhrrcofo.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhongyouzk.top/Article/details/gtftdxwavd.html

C#:   static void Main(string[] args)
来源：http://dali.yongpay.top/Article/details/gtsekrunna.html

[M08] 获取系统与运行时信息
来源：http://dali.xuanzx.com/Article/details/gtiatdcbfu.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cqqwz.cn/Article/details/gttloilskz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttwehfbli.html

JS:   process.platform;  process.version
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmykyfids.html

TS:   process.platform;  process.version
来源：http://dali.xinyue.icu/Article/details/gtckapnpnv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.chenjidiqi.icu/Article/details/gtdsmwzfow.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xinyue.icu/Article/details/gtuwcvavzl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.aibaodan.cn/Article/details/gthotmkmxu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jiagoushi.top/Article/details/gtsdkuxjxn.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtupbmquyx.html

N. 数据结构与算法
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnixojhux.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtsiduujdv.html

[N01] 二分查找（有序数组）
来源：http://dali.cashguo.top/Article/details/gtuhqkmuvk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gtzmamrhoi.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cqqwz.cn/Article/details/gtuqrdnzli.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ppjwa.cn/Article/details/gtuucslpql.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tian-w.cn/Article/details/gtxxdwsovv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtberzebfd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtdcdktnex.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdaqdzioo.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cashguo.top/Article/details/gtjcmxpdeu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.smart0.xyz/Article/details/gthybxaudz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sxryk.cn/Article/details/gtnnxumgeq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yj202588.top/Article/details/gtbxcvspln.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenzaomai.com/Article/details/gtgaeezips.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnqzz.top/Article/details/gtgtytwdzm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cdnleiting.top/Article/details/gtjbvhmfly.html

Go:   slices.Sort(arr)
来源：http://dali.quarkkingdee.top/Article/details/gttdhvbpet.html

Ruby: arr.sort
来源：http://dali.wangdashe.top/Article/details/gttijyyuju.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhiwuduotai.top/Article/details/gtonuensue.html

[N03] 快速排序（分治示例）
来源：http://dali.xinyue.icu/Article/details/gtwuhdgixr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hysaishi.cn/Article/details/gtpmmtonrk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shzxlz.cn/Article/details/gtnnhfgfoa.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yanxiufei.cn/Article/details/gtaaewrcox.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuxming.cn/Article/details/gtmlcuakfr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sweek.top/Article/details/gtdqxdazul.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.mhx1999.top/Article/details/gtgywyxjpd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.wangdashe.top/Article/details/gtzckkgzdw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.dashuyun.cn/Article/details/gtewyddtqe.html

[N04] 斐波那契数列
来源：http://dali.jlsjyb.cn/Article/details/gtlazgozke.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.birdmap.top/Article/details/gtucrfazsl.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zdqjudy.top/Article/details/gtpnidczkz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tian-w.cn/Article/details/gtprubrpfe.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cdnleiting.top/Article/details/gtswxfvbjc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdsnbrtek.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnmnkcmyi.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.dianchejie.cn/Article/details/gthphuqymj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.wangdashe.top/Article/details/gtfrdplqkk.html


<!-- 参考信息 -->