代发 wailian999

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jqgfzy.top/Article/details/gthkmlivkh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.iojbl.cn/Article/details/gtbvfsmial.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jianghu66.top/Article/details/gtotwypbfa.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvrvsqzmv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gotoacloud.top/Article/details/gtwisegigf.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hnqzz.top/Article/details/gtjxczbqfm.html

[J09] 时区处理
来源：http://dali.ehwqpu.com/Article/details/gtkrqlhvyc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.chenjidiqi.icu/Article/details/gtyldmvoea.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.dianchejie.cn/Article/details/gtqufmawkm.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jiagoushi.top/Article/details/gtzdpaafep.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258.top/Article/details/gtnfwejrfu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhongyouzk.top/Article/details/gtztbtrkfq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.9152youxi.cn/Article/details/gtvdyjeoht.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.snrcjt.cn/Article/details/gtditelmlh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.aibaodan.cn/Article/details/gtrmaotwzo.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhengqikj.top/Article/details/gtlxqxdkee.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtywyvejcc.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.9152youxi.cn/Article/details/gtgretsbfy.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cqqwz.cn/Article/details/gttffhrxrl.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj20258888.top/Article/details/gtztvwdzap.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hnqzz.top/Article/details/gtlccjtgit.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sysykeji.top/Article/details/gtsocerace.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcaisybjo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxexldtsg.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtayqxojon.html

K. JSON 与序列化
来源：http://dali.c1oappe.top/Article/details/gtxbcxmqxm.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtivxhdrum.html

[K01] 对象转 JSON 字符串
来源：http://dali.hfpthk.cn/Article/details/gtvkqwhput.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.aizwys.cn/Article/details/gtkanetcfy.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.chenjidiqi.icu/Article/details/gtjjmypwgb.html

JS:   JSON.stringify(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtmnhmhjho.html

TS:   JSON.stringify(obj)
来源：http://dali.hysaishi.cn/Article/details/gtawarnhor.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sxryk.cn/Article/details/gtklqhbwcq.html

Go:   json.Marshal(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtokaenvlj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hammf.cn/Article/details/gtvazmmacw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtanultafj.html

[K02] JSON 字符串转对象
来源：http://dali.yongpay.top/Article/details/gtttgfaxwe.html

Py:   json.loads(s)
来源：http://dali.havefunace.top/Article/details/gtmjkkcutp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.iojbl.cn/Article/details/gtatgyvijo.html

JS:   JSON.parse(s)
来源：http://dali.nanxinkj.top/Article/details/gtmjpqebgf.html

TS:   JSON.parse(s)
来源：http://dali.wangdashe.top/Article/details/gtmushxdfn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.wangshuangyany.cn/Article/details/gtfdtqesss.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shuidangran.top/Article/details/gtmjaltuop.html

Ruby: JSON.parse(s)
来源：http://dali.cdnleiting.top/Article/details/gttsnauher.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xylfe.cn/Article/details/gtiyliadlk.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtemsazsoq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.316326.xyz/Article/details/gtwpurlpik.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yanxiufei.cn/Article/details/gtqagrfour.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cdnleiting.top/Article/details/gtyittygow.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gaohongyu789.top/Article/details/gtphfvvrht.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtdselaitg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.haohaochexian.top/Article/details/gtqbmvonju.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jqgfzy.top/Article/details/gtqdahmnio.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrpcurwtu.html

[K04] 读取 JSON 文件
来源：http://dali.yueranfly.top/Article/details/gtzkhbgoxy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sxryk.cn/Article/details/gtduuocsoc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yuanzhike.top/Article/details/gtvqrlybdn.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jianghu66.top/Article/details/gtbupmpesx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.svipenyu.cn/Article/details/gttkmuydxo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yangfankeji.com/Article/details/gttuuqxdio.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.svipenyu.cn/Article/details/gtvvhowrpk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jlsjyb.cn/Article/details/gtbfrzbodm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jqgfzy.top/Article/details/gtyeuvlnzq.html

[K05] 深拷贝对象
来源：http://dali.hywenlv.cn/Article/details/gtlvsmkcti.html

Py:   copy.deepcopy(obj)
来源：http://dali.sxryk.cn/Article/details/gtpzwdlqxi.html

PHP:  unserialize(serialize($obj));
来源：http://dali.0kj1m.cn/Article/details/gtynxowkkh.html

JS:   structuredClone(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtexokzbxz.html

TS:   structuredClone(obj)
来源：http://dali.ybcxt.top/Article/details/gtsncbywbr.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjtzalwau.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yj20258.top/Article/details/gtanworejw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xinyue.icu/Article/details/gtzdqjyygq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ppjwa.cn/Article/details/gtlwbdkuie.html

[K06] 解析 URL 查询串
来源：http://dali.ybcxt.top/Article/details/gtbjlnljzs.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shuidangran.top/Article/details/gtdegxcsmy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hnxiangtu.top/Article/details/gttheajkes.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaaalclla.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aizwys.cn/Article/details/gtwvxniifo.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cashguo.top/Article/details/gthvvnykll.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gtyntltjnf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gtxwlstuyi.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ybcxt.top/Article/details/gttzybncxd.html

[K07] 进制转换
来源：http://dali.sysykeji.top/Article/details/gtpuzabhnf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gtaqtbgsgi.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.mhx1999.top/Article/details/gttuxgkmum.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gtxfqikmsy.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gtahlvqaee.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gtvxbommoy.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.andypj.xyz/Article/details/gtqiotruyn.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jyoumei.cn/Article/details/gtfeptptph.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gtqiuxmeez.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.fzhhl.top/Article/details/gtzyhznorw.html

Py:   pickle.dumps(obj)
来源：http://dali.xylfe.cn/Article/details/gtrtgjncoj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shzxlz.cn/Article/details/gtfvfyqicv.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.dashuyun.cn/Article/details/gtqquponjv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.snrcjt.cn/Article/details/gtilivssdj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.dashuyun.cn/Article/details/gtfixqncbw.html

Go:   encoding/gob
来源：http://dali.jinghuilouyu.cn/Article/details/gtprkdlnbm.html

Ruby: Marshal.dump(obj)
来源：http://dali.sysykeji.top/Article/details/gthijdmzda.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xziqi.cn/Article/details/gtzlnnaarc.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtktqvncch.html

L. 网络请求
来源：http://dali.zhongyouzk.top/Article/details/gtchsixsgm.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtwrnovxef.html

[L01] 发送 GET 请求
来源：http://dali.andypj.xyz/Article/details/gtamwqdhin.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yueranfly.top/Article/details/gtovqaptib.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gzhubu.top/Article/details/gtlipbapjw.html

JS:   await fetch(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqyzfjjeh.html

TS:   await fetch(url)
来源：http://dali.aizwys.cn/Article/details/gtfzgupwcf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yvedp.cn/Article/details/gtmmhrdskd.html

Go:   resp, err := http.Get(url)
来源：http://dali.yuanzhike.top/Article/details/gtglrnnami.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.wangdashe.top/Article/details/gtrltkdzog.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.kuanghao11.cn/Article/details/gtijnsdlux.html

[L02] 发送 POST JSON
来源：http://dali.guowangkeji.top/Article/details/gtmqbwpuuo.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.tanke756.top/Article/details/gtsbnnoqnr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yueranfly.top/Article/details/gtxowejdik.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yanxiufei.cn/Article/details/gtjbprihzz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj202588.top/Article/details/gtwcnwwgmf.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hysaishi.cn/Article/details/gtkqcpiait.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shzxlz.cn/Article/details/gtqlndeqmc.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xuetiantiany.cn/Article/details/gtbcgerqqq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.tianlin.xyz/Article/details/gtiwoddkcw.html

[L03] 设置自定义请求头
来源：http://dali.yonumen.top/Article/details/gtppglwhfl.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cucudq.cn/Article/details/gtehlccjvl.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.pycfn.com/Article/details/gtjkfedixr.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnqzz.top/Article/details/gtxuwchxco.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhiwuduotai.top/Article/details/gtzidgbusd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.pengpengdd.cyou/Article/details/gtjgmftufl.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jinqigfzy.top/Article/details/gttjfwamsd.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.vqdsnc.cn/Article/details/gtvrddxjav.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jianghu66.top/Article/details/gtwwqnghvc.html

[L04] 设置超时
来源：http://dali.9152youxi.cn/Article/details/gtprbocxpv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.aizwys.cn/Article/details/gtcvejfkee.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yongpay.top/Article/details/gtzguwgbbn.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.quarkkingdee.top/Article/details/gtnfrpqnir.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.9152youxi.cn/Article/details/gtzboebeju.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.aizwys.cn/Article/details/gtuifxqwnf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yuxming.cn/Article/details/gtgtrevhup.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.havefunace.top/Article/details/gtgoxjname.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.mhx1999.top/Article/details/gtplwcpkbn.html

[L05] 上传文件（multipart）
来源：http://dali.gaohongyu789.top/Article/details/gtonydghlg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hongshengwenyu.top/Article/details/gtzfmmrdph.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.daxiang520.top/Article/details/gtxuigkxfl.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hongshengwenyu.top/Article/details/gtkpmhoxgf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yanxiufei.cn/Article/details/gtoxreyyix.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.nanxinkj.top/Article/details/gtnymbypsu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yj20258888.top/Article/details/gtdzdvjinm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.snrcjt.cn/Article/details/gtsaltrnjz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtjklzlckd.html

[L06] 解析响应为 JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqoxyvxfv.html

Py:   resp.json()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtovobdvkq.html

PHP:  json_decode($body, true);
来源：http://dali.yuxming.cn/Article/details/gtdspsdflu.html

JS:   await resp.json()
来源：http://dali.andypj.xyz/Article/details/gtbrpreuqy.html

TS:   await resp.json()
来源：http://dali.zhengqikj.top/Article/details/gtkaqrhhwr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.haohaochexian.top/Article/details/gtgajpmxzy.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ppjwa.cn/Article/details/gtjehienbh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hnxiangtu.top/Article/details/gtezquwqkt.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cqqwz.cn/Article/details/gtncmjukrk.html

[L07] 处理 HTTP 状态码
来源：http://dali.c1oappe.top/Article/details/gthcgfeynl.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jqgufenzy.top/Article/details/gtzbocwuhy.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yueranfly.top/Article/details/gtyaudabez.html

JS:   resp.ok;  resp.status
来源：http://dali.cashguo.top/Article/details/gtceoqwrsm.html

TS:   resp.ok;  resp.status
来源：http://dali.fengsongda.top/Article/details/gttnkgfqou.html

Java: resp.statusCode()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgqnkbekb.html

Go:   resp.StatusCode
来源：http://dali.feifeiyinyue.top/Article/details/gtfskrqzls.html

Ruby: resp.code.to_i
来源：http://dali.wangdashe.top/Article/details/gtjiphulak.html

C#:   (int)resp.StatusCode
来源：http://dali.yanxiufei.cn/Article/details/gtblcojyzo.html

[L08] 并发请求多个地址
来源：http://dali.cucudq.cn/Article/details/gtzxpunpeo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zdqjudy.top/Article/details/gtveskipij.html

PHP:  curl_multi_init() 系列
来源：http://dali.redwolf501.top/Article/details/gtqemyfdkn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dianchejie.cn/Article/details/gtzgljdmlh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gthbnaspbl.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhengqikj.top/Article/details/gtuduxdttl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.birdmap.top/Article/details/gtlwisrkzt.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyjggdksi.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gogol.net.cn/Article/details/gtoejmflkd.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtaohtjngo.html

M. 命令行 / 进程 / 环境
来源：http://dali.smart0.xyz/Article/details/gtbmypprzb.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtujibmdxa.html

[M01] 读取命令行参数
来源：http://dali.xuetiantiany.cn/Article/details/gtweqqgkdd.html

Py:   sys.argv[1:]
来源：http://dali.jianghu66.top/Article/details/gtkosyiary.html

PHP:  $argv;  $argc;
来源：http://dali.hfpthk.cn/Article/details/gtcfwnmmgo.html

JS:   process.argv.slice(2)
来源：http://dali.bjfxy.top/Article/details/gtgrxjciig.html

TS:   process.argv.slice(2)
来源：http://dali.hongshengwenyu.top/Article/details/gtjujtyzdm.html

Java: args 数组（main 方法参数）
来源：http://dali.sxryk.cn/Article/details/gtegivykqf.html

Go:   os.Args[1:]
来源：http://dali.tian-w.cn/Article/details/gtuikgppyc.html

Ruby: ARGV
来源：http://dali.kuanghao11.cn/Article/details/gtzfegvwsk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xuanzx.com/Article/details/gttwxydemt.html

[M02] 读取环境变量
来源：http://dali.guannengcc.top/Article/details/gtxppbczpc.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gtdadykbfe.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.birdmap.top/Article/details/gtyafgwhhb.html

JS:   process.env.HOME
来源：http://dali.c1oappe.top/Article/details/gtxtpdwsvv.html

TS:   process.env.HOME
来源：http://dali.hysaishi.cn/Article/details/gtgqsdvqih.html

Java: System.getenv("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gtmybyutcr.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gtvhvopegq.html

Ruby: ENV["HOME"]
来源：http://dali.ppjwa.cn/Article/details/gtkbiouowu.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.guannengcc.top/Article/details/gtuvzgucfj.html

[M03] 执行外部命令
来源：http://dali.chenlongwang.top/Article/details/gtkpkvnbzs.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gogol.net.cn/Article/details/gtdzhgboti.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.wangshuangyany.cn/Article/details/gtjdinqubl.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbmvbazdn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.redwolf501.top/Article/details/gtohsjqliz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.pengpengdd.cyou/Article/details/gtomdpselh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nanxinkj.top/Article/details/gtlmisowvb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.nanxinkj.top/Article/details/gtvbhibtif.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuaenbquo.html

[M04] 获取当前工作目录
来源：http://dali.tanke756.top/Article/details/gtjdcppzci.html

Py:   os.getcwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlutecxxy.html

PHP:  getcwd();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzksltylh.html

JS:   process.cwd()
来源：http://dali.smart0.xyz/Article/details/gtiswsxqlg.html

TS:   process.cwd()
来源：http://dali.tanke756.top/Article/details/gthjjgblee.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hammf.cn/Article/details/gtfxgghfqn.html

Go:   os.Getwd()
来源：http://dali.vqdsnc.cn/Article/details/gtwiihcstk.html

Ruby: Dir.pwd
来源：http://dali.ppjwa.cn/Article/details/gtrqomezer.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cdnleiting.top/Article/details/gtdftvqxxq.html

[M05] 设置退出码
来源：http://dali.dashuyun.cn/Article/details/gtqczpswjj.html

Py:   sys.exit(1)
来源：http://dali.cashguo.top/Article/details/gtmqnqgwbd.html

PHP:  exit(1);
来源：http://dali.ivvv.top/Article/details/gttansdldw.html

JS:   process.exit(1)
来源：http://dali.sysykeji.top/Article/details/gtgecnmbtb.html

TS:   process.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gtgryslhfr.html

Java: System.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gtjwqrodoh.html

Go:   os.Exit(1)
来源：http://dali.fengsongda.top/Article/details/gthlouujmx.html

Ruby: exit 1
来源：http://dali.wangdashe.top/Article/details/gtvgcdclgu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.nanxuanxn.top/Article/details/gtpqemaxpg.html

[M06] 向标准错误输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyxnxywej.html

Py:   print("err", file=sys.stderr)
来源：http://dali.andypj.xyz/Article/details/gtworocase.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.gogol.net.cn/Article/details/gtrvuqbpmp.html

JS:   console.error("err")
来源：http://dali.yanxiufei.cn/Article/details/gtenstaqdu.html

TS:   console.error("err")
来源：http://dali.zhoulong.xyz/Article/details/gtdnafbqlm.html

Java: System.err.println("err")
来源：http://dali.hywenlv.cn/Article/details/gtyoxgoyhk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hnqzz.top/Article/details/gtlqddovtm.html

Ruby: warn "err"
来源：http://dali.xziqi.cn/Article/details/gthozphriz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.guannengcc.top/Article/details/gtmuvadmzj.html

[M07] 判断是否为主入口
来源：http://dali.zdqjudy.top/Article/details/gtzhmyuzkj.html

Py:   if __name__ == "__main__":
来源：http://dali.tanke756.top/Article/details/gtgfwsqadj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hnqzz.top/Article/details/gtqhrwtehm.html

JS:   require.main === module
来源：http://dali.jinghuilouyu.cn/Article/details/gtlgzmqaki.html

TS:   require.main === module
来源：http://dali.meibo888.top/Article/details/gtulapvatz.html

Java: public static void main(String[] args)
来源：http://dali.hywenlv.cn/Article/details/gtqyzvmacn.html

Go:   func main()
来源：http://dali.tanke756.top/Article/details/gtuxcfxufn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jiagoushi.top/Article/details/gttuejncjb.html

C#:   static void Main(string[] args)
来源：http://dali.cqqwz.cn/Article/details/gtazuumqbh.html

[M08] 获取系统与运行时信息
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxajkgbcx.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shuidangran.top/Article/details/gtuqtlyvmv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ydzc1.top/Article/details/gtmmkcofnt.html

JS:   process.platform;  process.version
来源：http://dali.yangfankeji.com/Article/details/gtwptlynfu.html

TS:   process.platform;  process.version
来源：http://dali.aibaodan.cn/Article/details/gthugwxluz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhengqikj.top/Article/details/gtotlowodj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.pengpengdd.cyou/Article/details/gtpauqccvv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzrfzulyl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jqgufenzy.top/Article/details/gthoedrlyd.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtvhxernxv.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gttynczogh.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtoxzgydyx.html

[N01] 二分查找（有序数组）
来源：http://dali.tanke756.top/Article/details/gtrkzkspdg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtebcteixe.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.tianlin.xyz/Article/details/gthfcvzjmw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gaohongyu789.top/Article/details/gtnzofjqcb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xziqi.cn/Article/details/gtmgghuhfi.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtshlfntsp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtntjibtsh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.havefunace.top/Article/details/gtohxsecrm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gzhubu.top/Article/details/gtocwyqvdr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shzxlz.cn/Article/details/gtgdiwdpdf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigfzy.top/Article/details/gtsorneivg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.gotoacloud.top/Article/details/gtmrmnbjbp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.feifeiyinyue.top/Article/details/gtsbflqyjl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fzhhl.top/Article/details/gtpetqbgoh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.316326.xyz/Article/details/gtdzmpfzca.html

Go:   slices.Sort(arr)
来源：http://dali.jianghu66.top/Article/details/gtthdjxvif.html

Ruby: arr.sort
来源：http://dali.havefunace.top/Article/details/gtylwhczvb.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gzhubu.top/Article/details/gtpxgyjhic.html

[N03] 快速排序（分治示例）
来源：http://dali.redwolf501.top/Article/details/gtpghwyner.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.meibo888.top/Article/details/gtkegaydxk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.vqdsnc.cn/Article/details/gtxbjzfgyq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigufen.top/Article/details/gtkahwtltu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tanke756.top/Article/details/gtdimaorxg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zycfv.cn/Article/details/gtiwrjnfhf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yangfankeji.com/Article/details/gtlcrfvbql.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jlsjyb.cn/Article/details/gtvtdwanem.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtovvthdsr.html

[N04] 斐波那契数列
来源：http://dali.quarkkingdee.top/Article/details/gthdvkhaxg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.guowangkeji.top/Article/details/gtclejrtfi.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.kuanghao11.cn/Article/details/gtzyjmusak.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gtddccdtug.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dashuyun.cn/Article/details/gtxrbhniaa.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.smart0.xyz/Article/details/gtdcmwfjbi.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvchhmeou.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtolhwugok.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.iojbl.cn/Article/details/gtadwkzsco.html

[N05] 最大公约数
来源：http://dali.aibaodan.cn/Article/details/gtmpzgajij.html

Py:   math.gcd(a, b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjjpegbwo.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.haohaochexian.top/Article/details/gtnfvhuham.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xylfe.cn/Article/details/gtgoudtkrm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xinyue.icu/Article/details/gtfwrqipbh.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yuanzhike.top/Article/details/gtqsxjmmjx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.nwbrower.top/Article/details/gthnbexuvi.html

Ruby: a.gcd(b)
来源：http://dali.birdmap.top/Article/details/gthggpmqpm.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.0kj1m.cn/Article/details/gtvrviqmgb.html

[N06] 判断回文字符串
来源：http://dali.316326.xyz/Article/details/gtahnorzyc.html

Py:   s == s[::-1]
来源：http://dali.tian-w.cn/Article/details/gtwgjonokn.html

PHP:  $s === strrev($s);
来源：http://dali.fengsongda.top/Article/details/gttkqgzkxa.html


<!-- 参考信息 -->