代发 wailian999

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cucudq.cn/Article/details/gtwhvyoyww.html

Go:   end.Sub(start).Hours()
来源：http://dali.cashguo.top/Article/details/gtvviziifw.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cucudq.cn/Article/details/gtaawovkzp.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinghuilouyu.cn/Article/details/gtnixcoytc.html

[J07] 比较两个日期
来源：http://dali.chenzaomai.com/Article/details/gtpkywzoix.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.snrcjt.cn/Article/details/gtggyxtlqs.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.redwolf501.top/Article/details/gtpdtasqjf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.9152youxi.cn/Article/details/gtiietwgru.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yvedp.cn/Article/details/gtmmsynnhy.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xylfe.cn/Article/details/gtrjujmemc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.316326.xyz/Article/details/gtksxuupro.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gtmxgmzgab.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyvngztnb.html

[J08] 提取年月日与星期
来源：http://dali.jinghuilouyu.cn/Article/details/gtpknjcnbf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.fengsongda.top/Article/details/gtfcrktkhk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.0kj1m.cn/Article/details/gtmmamgeem.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yuxming.cn/Article/details/gtamkiosmr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jqgfzy.top/Article/details/gtazancfwf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shanyushiyangtech.top/Article/details/gtxcskevsu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yj20258888.top/Article/details/gtiumuwkex.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.daxiang520.top/Article/details/gtbjlcgfiv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cheryme.top/Article/details/gthsbhgupr.html

[J09] 时区处理
来源：http://dali.yanxiufei.cn/Article/details/gtjsnmhbro.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cdnleiting.top/Article/details/gtwawcnrqh.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.bjfxy.top/Article/details/gtjoichswa.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuanzhike.top/Article/details/gtxbvauujw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258888.top/Article/details/gtjdaliqnh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.mhx1999.top/Article/details/gtnkdflydw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yueranfly.top/Article/details/gtlybiuiej.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yuanzhike.top/Article/details/gtxhnsmnud.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yj20258.top/Article/details/gtgxvodsvr.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenjidiqi.icu/Article/details/gtffgxjxud.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ybcxt.top/Article/details/gtdtkbxoms.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xinyue.icu/Article/details/gtpypjixpm.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.redwolf501.top/Article/details/gtsygvozjs.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtvvtatzxw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.svipenyu.cn/Article/details/gtfsjpmjky.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sweek.top/Article/details/gtjdjmshtq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.meibo888.top/Article/details/gtkrirjpeq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hysaishi.cn/Article/details/gtmkixlebb.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtuatfrqpc.html

K. JSON 与序列化
来源：http://dali.snrcjt.cn/Article/details/gtjodbhhnw.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtfqnghioa.html

[K01] 对象转 JSON 字符串
来源：http://dali.yonumen.top/Article/details/gtpvhrwvin.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinqigfzy.top/Article/details/gttzadyjwf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.birdmap.top/Article/details/gtytmyihke.html

JS:   JSON.stringify(obj)
来源：http://dali.zhengqikj.top/Article/details/gtngdtrbki.html

TS:   JSON.stringify(obj)
来源：http://dali.cdnleiting.top/Article/details/gtzflqcndz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.birdmap.top/Article/details/gtarljwgeb.html

Go:   json.Marshal(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtncjeebse.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.svipenyu.cn/Article/details/gtrbtvprfe.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.birdmap.top/Article/details/gtmuzxecng.html

[K02] JSON 字符串转对象
来源：http://dali.shuidangran.top/Article/details/gthffunzog.html

Py:   json.loads(s)
来源：http://dali.meibo888.top/Article/details/gtkzghklay.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.aibaodan.cn/Article/details/gtxgfemzjk.html

JS:   JSON.parse(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtefujoucf.html

TS:   JSON.parse(s)
来源：http://dali.tanke756.top/Article/details/gttbnbqizb.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.tian-w.cn/Article/details/gtnbplyayv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.c1oappe.top/Article/details/gtzjpoiyuq.html

Ruby: JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gtcrejyrtf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gotoacloud.top/Article/details/gtvubixvft.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sysykeji.top/Article/details/gtbgzroqxb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.birdmap.top/Article/details/gtmbmrebtc.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shangyingyoupin.top/Article/details/gtmplzuqdw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.iojbl.cn/Article/details/gttanizrkv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgfzy.top/Article/details/gtwowdzthe.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ydzc1.top/Article/details/gtvpzivcmu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhengqikj.top/Article/details/gtodjccdqr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yongpay.top/Article/details/gtsmztnfva.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj202588.top/Article/details/gtxwzvbtiu.html

[K04] 读取 JSON 文件
来源：http://dali.dianchejie.cn/Article/details/gtjubjtzza.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tian-w.cn/Article/details/gtkpuasmqy.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.mhx1999.top/Article/details/gttcgeokqe.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zycfv.cn/Article/details/gtulkxakcj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.dashuyun.cn/Article/details/gtewrreqcp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.aizwys.cn/Article/details/gtzevmkcco.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.fzhhl.top/Article/details/gtlnuyvkph.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hnqzz.top/Article/details/gtdacdhtdv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gaohongyu789.top/Article/details/gtceddqgjy.html

[K05] 深拷贝对象
来源：http://dali.fzhhl.top/Article/details/gtgbkihdfk.html

Py:   copy.deepcopy(obj)
来源：http://dali.yvedp.cn/Article/details/gttskxrsby.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sxryk.cn/Article/details/gtkruodgtb.html

JS:   structuredClone(obj)
来源：http://dali.xinyue.icu/Article/details/gtlcapzube.html

TS:   structuredClone(obj)
来源：http://dali.cashguo.top/Article/details/gtqcynrysi.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sweek.top/Article/details/gtqfipywux.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ppjwa.cn/Article/details/gtfnwgijer.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.nanxinkj.top/Article/details/gtvssqtzfq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.316326.xyz/Article/details/gtcdkkoyvg.html

[K06] 解析 URL 查询串
来源：http://dali.hammf.cn/Article/details/gtlvnjivzo.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqfbwkpny.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.aizwys.cn/Article/details/gtmsefxlsn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtnzwanbin.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuihgpfne.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yueranfly.top/Article/details/gtldfxqobj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttotgvrvl.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhongyouzk.top/Article/details/gtdueohrdy.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.haohaochexian.top/Article/details/gthevebnao.html

[K07] 进制转换
来源：http://dali.pycfn.com/Article/details/gtvzohuynx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gtszkpggbz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shzxlz.cn/Article/details/gtfgeuuvub.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gtgkljwyrm.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gtcenqdsit.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gtfhktpstc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ivvv.top/Article/details/gtbsqkmzje.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cqqwz.cn/Article/details/gtfmzcxbip.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gtnqqthodz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.birdmap.top/Article/details/gtbrgmleqw.html

Py:   pickle.dumps(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gthlrrzoom.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ppjwa.cn/Article/details/gtfeuyshpk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sysykeji.top/Article/details/gtbdwflqwr.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.redwolf501.top/Article/details/gtmsyhugru.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jqgufenzy.top/Article/details/gtjdaximtf.html

Go:   encoding/gob
来源：http://dali.quarkkingdee.top/Article/details/gtvzgmgtqu.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdhblcjbj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zycfv.cn/Article/details/gtkdewekmw.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtnuzcwtcp.html

L. 网络请求
来源：http://dali.xziqi.cn/Article/details/gtgjfmoctt.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gthcmymoxd.html

[L01] 发送 GET 请求
来源：http://dali.cheryme.top/Article/details/gtnmnwvfrt.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hammf.cn/Article/details/gtggbicdin.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.kuanghao11.cn/Article/details/gtihuykpqp.html

JS:   await fetch(url)
来源：http://dali.gzhubu.top/Article/details/gtvopxnxeb.html

TS:   await fetch(url)
来源：http://dali.hywenlv.cn/Article/details/gtqgaaotvy.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shangyingyoupin.top/Article/details/gtkpqsfkts.html

Go:   resp, err := http.Get(url)
来源：http://dali.jlsjyb.cn/Article/details/gtzndlinrb.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xziqi.cn/Article/details/gthnjstevk.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xuanzx.com/Article/details/gtwffummlx.html

[L02] 发送 POST JSON
来源：http://dali.cucudq.cn/Article/details/gtbuefbekm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.birdmap.top/Article/details/gtyflxufde.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xuetiantiany.cn/Article/details/gtziazqihy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.haohaochexian.top/Article/details/gtsxowhfyw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hnxiangtu.top/Article/details/gtgfqumdwq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.quarkkingdee.top/Article/details/gtvnkkauhf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yj20258.top/Article/details/gtajjwfxch.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.chenjidiqi.icu/Article/details/gtwwwveydq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.tianlin.xyz/Article/details/gtrlaadohc.html

[L03] 设置自定义请求头
来源：http://dali.yonumen.top/Article/details/gtnyfuujyx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ydzc1.top/Article/details/gtwxmaucml.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.pengpengdd.cyou/Article/details/gtwvycomjm.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cdnleiting.top/Article/details/gtbubtfnsx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hywenlv.cn/Article/details/gtvdwcahqc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yj20258888.top/Article/details/gtjewqiqny.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xylfe.cn/Article/details/gtzvcjitum.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.aizwys.cn/Article/details/gtugdqnbfr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gaohongyu789.top/Article/details/gtsobhylec.html

[L04] 设置超时
来源：http://dali.ivvv.top/Article/details/gtditwosts.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cashguo.top/Article/details/gtzxejkvil.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ppjwa.cn/Article/details/gtrqugovgu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinghuilouyu.cn/Article/details/gtwozvnusj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sweek.top/Article/details/gtpfmyaxmp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gtcypkxdoe.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.tian-w.cn/Article/details/gtsewjtrqp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.nwbrower.top/Article/details/gtnsfzapwk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yanxiufei.cn/Article/details/gtgyptmyfu.html

[L05] 上传文件（multipart）
来源：http://dali.shuidangran.top/Article/details/gtzblonrlk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nwbrower.top/Article/details/gtjyjbcjbr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.chenjidiqi.icu/Article/details/gteguneplc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.guannengcc.top/Article/details/gtdwrexwka.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgfzy.top/Article/details/gtspbwhgqd.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ehwqpu.com/Article/details/gtsokrnhww.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.guowangkeji.top/Article/details/gtbrwgswgl.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.9152youxi.cn/Article/details/gtjwrdjbmf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtthqtefup.html

[L06] 解析响应为 JSON
来源：http://dali.yuxming.cn/Article/details/gtwdttyhql.html

Py:   resp.json()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwvkskpem.html

PHP:  json_decode($body, true);
来源：http://dali.chenjidiqi.icu/Article/details/gtqmugpawz.html

JS:   await resp.json()
来源：http://dali.jiagoushi.top/Article/details/gtcskshopy.html

TS:   await resp.json()
来源：http://dali.tian-w.cn/Article/details/gtbpclhuar.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jlsjyb.cn/Article/details/gtenlpfwfo.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.fzhhl.top/Article/details/gtswryuhzw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.316326.xyz/Article/details/gtrjqroloc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.vqdsnc.cn/Article/details/gthltgreck.html

[L07] 处理 HTTP 状态码
来源：http://dali.feifeiyinyue.top/Article/details/gtevuwbndb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.aibaodan.cn/Article/details/gtbentxyen.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yj202588.top/Article/details/gtckrbzwxv.html

JS:   resp.ok;  resp.status
来源：http://dali.dianchejie.cn/Article/details/gtbjcjurmg.html

TS:   resp.ok;  resp.status
来源：http://dali.zhixingplan.top/Article/details/gtfswtqpta.html

Java: resp.statusCode()
来源：http://dali.yueranfly.top/Article/details/gtbqffyuqv.html

Go:   resp.StatusCode
来源：http://dali.zhongyouzk.top/Article/details/gtcjtgbomz.html

Ruby: resp.code.to_i
来源：http://dali.ehwqpu.com/Article/details/gtajvrufrj.html

C#:   (int)resp.StatusCode
来源：http://dali.shuidangran.top/Article/details/gtxzsmohkt.html

[L08] 并发请求多个地址
来源：http://dali.c1oappe.top/Article/details/gtqyygkxvl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hnqzz.top/Article/details/gtrlhbbivj.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinqigfzy.top/Article/details/gtndeivfre.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jyoumei.cn/Article/details/gtgusyzfqz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yongpay.top/Article/details/gtfkxcthky.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhengqikj.top/Article/details/gtufvyfayt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.andypj.xyz/Article/details/gtuwtasuxw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.pycfn.com/Article/details/gttclpbtcs.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gzhubu.top/Article/details/gthwoftpoh.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtqqxfhtmt.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenlongwang.top/Article/details/gtzucfncht.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtafoomhyu.html

[M01] 读取命令行参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyeixggnn.html

Py:   sys.argv[1:]
来源：http://dali.sxryk.cn/Article/details/gtjgqgubwa.html

PHP:  $argv;  $argc;
来源：http://dali.shzxlz.cn/Article/details/gtsompvtnu.html

JS:   process.argv.slice(2)
来源：http://dali.yangfankeji.com/Article/details/gtozbzqmbk.html

TS:   process.argv.slice(2)
来源：http://dali.hongshengwenyu.top/Article/details/gtkdmpcsux.html

Java: args 数组（main 方法参数）
来源：http://dali.zhixingplan.top/Article/details/gtbmpzaobt.html

Go:   os.Args[1:]
来源：http://dali.nanxuanxn.top/Article/details/gtviauqutr.html

Ruby: ARGV
来源：http://dali.xziqi.cn/Article/details/gtqfqihaki.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj20258888.top/Article/details/gtjapvowws.html

[M02] 读取环境变量
来源：http://dali.kuanghao11.cn/Article/details/gtrbsigwoq.html

Py:   os.environ.get("HOME")
来源：http://dali.aibaodan.cn/Article/details/gtigfpfdpv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzlrrpieg.html

JS:   process.env.HOME
来源：http://dali.wangshuangyany.cn/Article/details/gtnsuskubj.html

TS:   process.env.HOME
来源：http://dali.shanyushiyangkeji.top/Article/details/gttlubqsxl.html

Java: System.getenv("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gttpoqcubl.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.fzhhl.top/Article/details/gtqxrizzis.html

Ruby: ENV["HOME"]
来源：http://dali.havefunace.top/Article/details/gtirlcckqt.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.pycfn.com/Article/details/gtjzsivuvo.html

[M03] 执行外部命令
来源：http://dali.ybcxt.top/Article/details/gtlyfckvwo.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jiagoushi.top/Article/details/gtahqddypk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hywenlv.cn/Article/details/gtijmnpfqp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jianghu66.top/Article/details/gtzgobmqnm.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gotoacloud.top/Article/details/gthtlkiojb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.chenzaomai.com/Article/details/gtutnnpajh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gaohongyu789.top/Article/details/gtwbjcduxp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yanxiufei.cn/Article/details/gtdifjhxid.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ppjwa.cn/Article/details/gtvnyvxktw.html

[M04] 获取当前工作目录
来源：http://dali.cashguo.top/Article/details/gtmdtepbmt.html

Py:   os.getcwd()
来源：http://dali.tianlin.xyz/Article/details/gtltxomsmh.html

PHP:  getcwd();
来源：http://dali.dashuyun.cn/Article/details/gtlqoxgmzp.html

JS:   process.cwd()
来源：http://dali.havefunace.top/Article/details/gtftichdlf.html

TS:   process.cwd()
来源：http://dali.guowangkeji.top/Article/details/gtmmdnekfj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yuanzhike.top/Article/details/gtqbcavotj.html

Go:   os.Getwd()
来源：http://dali.shzxlz.cn/Article/details/gttzytjrmq.html

Ruby: Dir.pwd
来源：http://dali.yongpay.top/Article/details/gtbuzsrixf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.daria6918.cn/Article/details/gtqfgazvgk.html

[M05] 设置退出码
来源：http://dali.yanxiufei.cn/Article/details/gtsbdcmpxt.html

Py:   sys.exit(1)
来源：http://dali.jianghu66.top/Article/details/gtrozghidn.html

PHP:  exit(1);
来源：http://dali.fengsongda.top/Article/details/gtooqdabeh.html

JS:   process.exit(1)
来源：http://dali.chenlongwang.top/Article/details/gttqepphad.html

TS:   process.exit(1)
来源：http://dali.pycfn.com/Article/details/gtvbftcxwq.html

Java: System.exit(1)
来源：http://dali.guannengcc.top/Article/details/gtwtwbtume.html

Go:   os.Exit(1)
来源：http://dali.aibaodan.cn/Article/details/gtfuvfohbm.html

Ruby: exit 1
来源：http://dali.zhiwuduotai.top/Article/details/gtkdeplxum.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.c1oappe.top/Article/details/gtzqdcuvsu.html

[M06] 向标准错误输出
来源：http://dali.redwolf501.top/Article/details/gteexfekwt.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hysaishi.cn/Article/details/gtxkqskvdn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.tianlin.xyz/Article/details/gtsaehqxdq.html

JS:   console.error("err")
来源：http://dali.dashuyun.cn/Article/details/gtyzxupoph.html

TS:   console.error("err")
来源：http://dali.c1oappe.top/Article/details/gthwindfoe.html

Java: System.err.println("err")
来源：http://dali.dashuyun.cn/Article/details/gtojmmrjwx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.wangdashe.top/Article/details/gtgvhzyelk.html

Ruby: warn "err"
来源：http://dali.smart0.xyz/Article/details/gtmskzymdj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.feifeiyinyue.top/Article/details/gthumyzpvh.html

[M07] 判断是否为主入口
来源：http://dali.jlsjyb.cn/Article/details/gtbsztanhw.html

Py:   if __name__ == "__main__":
来源：http://dali.fengsongda.top/Article/details/gtkyndgjww.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cqqwz.cn/Article/details/gtquywfije.html

JS:   require.main === module
来源：http://dali.jqgufenzy.top/Article/details/gtrnnqqgle.html

TS:   require.main === module
来源：http://dali.sxryk.cn/Article/details/gtatneljed.html

Java: public static void main(String[] args)
来源：http://dali.wangshuangyany.cn/Article/details/gtztvxrwil.html

Go:   func main()
来源：http://dali.xinyue.icu/Article/details/gtoppdjpsu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sufxvd.cn/Article/details/gtdfjkqzng.html

C#:   static void Main(string[] args)
来源：http://dali.aizwys.cn/Article/details/gtqhdjbsjs.html

[M08] 获取系统与运行时信息
来源：http://dali.hongshengwenyu.top/Article/details/gtjdcivfua.html

Py:   platform.system();  platform.python_version()
来源：http://dali.haohaochexian.top/Article/details/gtdtwttmzd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gtwbdikegs.html

JS:   process.platform;  process.version
来源：http://dali.zhoulong.xyz/Article/details/gtfwmycmno.html

TS:   process.platform;  process.version
来源：http://dali.sweek.top/Article/details/gtduuqbgkl.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.iojbl.cn/Article/details/gtxueymjvk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.fengsongda.top/Article/details/gtkefusnxj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.316326.xyz/Article/details/gtcgchepsv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yuxming.cn/Article/details/gtcqehvtmf.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gthescimol.html

N. 数据结构与算法
来源：http://dali.zhongyouzk.top/Article/details/gtzycysszl.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtypuuqeaz.html

[N01] 二分查找（有序数组）
来源：http://dali.iojbl.cn/Article/details/gtkbqhftrf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtfmgwksie.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.andypj.xyz/Article/details/gtglzyxyzl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.snrcjt.cn/Article/details/gtklvrzbtq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xylfe.cn/Article/details/gtrayeiqjz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqbovmmzg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gtxufcihad.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gotoacloud.top/Article/details/gtijjqwxtk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gtqrjilech.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hnqzz.top/Article/details/gtzrmotwzp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gogol.net.cn/Article/details/gtzbnhxqcy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ivvv.top/Article/details/gthtfkkalc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shuidangran.top/Article/details/gtalwsbfmy.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jlsjyb.cn/Article/details/gtckzycomy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yanxiufei.cn/Article/details/gtxhzwtvyj.html

Go:   slices.Sort(arr)
来源：http://dali.ehwqpu.com/Article/details/gtrhptsaod.html

Ruby: arr.sort
来源：http://dali.shzxlz.cn/Article/details/gtjwnpideq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.tian-w.cn/Article/details/gtxixoqusw.html

[N03] 快速排序（分治示例）
来源：http://dali.tianlin.xyz/Article/details/gtsrvqbkuc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jinghuilouyu.cn/Article/details/gteyhhwqfw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yj20258.top/Article/details/gtdbailkzq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dashuyun.cn/Article/details/gtkzunkzbk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.iojbl.cn/Article/details/gtwzpbcfrh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xziqi.cn/Article/details/gttevmvdbp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cucudq.cn/Article/details/gtgnbnmbxh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yuanzhike.top/Article/details/gtitvgkmar.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.nwbrower.top/Article/details/gtyobgyghi.html

[N04] 斐波那契数列
来源：http://dali.pycfn.com/Article/details/gtdchjsnvy.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.c1oappe.top/Article/details/gtqwbkmwsh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cucudq.cn/Article/details/gtkcczlyej.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenzaomai.com/Article/details/gtewnwiwjw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangshuangyany.cn/Article/details/gtsgetgrap.html


<!-- 参考信息 -->