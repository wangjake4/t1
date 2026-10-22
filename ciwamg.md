代发 wailian999

Py:   (end - start).total_seconds()
来源：http://dali.smart0.xyz/Article/details/gtdldikker.html

PHP:  $end->diff($start)->days;
来源：http://dali.c1oappe.top/Article/details/gttrbloefw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ehwqpu.com/Article/details/gtccjreife.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hfpthk.cn/Article/details/gtnbshjxem.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xinyue.icu/Article/details/gtbuhtoxsr.html

Go:   end.Sub(start).Hours()
来源：http://dali.nanxuanxn.top/Article/details/gtsyvsqjal.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yuxming.cn/Article/details/gtliwoifix.html

C#:   (end - start).TotalSeconds
来源：http://dali.gotoacloud.top/Article/details/gtcwolheoj.html

[J07] 比较两个日期
来源：http://dali.jinghuilouyu.cn/Article/details/gtctthebte.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hongshengwenyu.top/Article/details/gtthhsvvgo.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hfpthk.cn/Article/details/gteinftfja.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgufenzy.top/Article/details/gtxywnzspb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cqqwz.cn/Article/details/gtifsoutym.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yuxming.cn/Article/details/gtwofqmyeo.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xuetiantiany.cn/Article/details/gtthvjabmg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gtodbociuo.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.sweek.top/Article/details/gtuakqznoz.html

[J08] 提取年月日与星期
来源：http://dali.cucudq.cn/Article/details/gtgsnewdoi.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ydzc1.top/Article/details/gtxnhswvuk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jqgufenzy.top/Article/details/gtzdhfxlck.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.daria6918.cn/Article/details/gtcfjucqfg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zycfv.cn/Article/details/gtuxuubekb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sxryk.cn/Article/details/gtkfzimqcl.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvxfqhcfe.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jlsjyb.cn/Article/details/gtoeoxosvi.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gotoacloud.top/Article/details/gtymjpjuuz.html

[J09] 时区处理
来源：http://dali.zycfv.cn/Article/details/gtaemzoruu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ppjwa.cn/Article/details/gtajklxwsg.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gzhubu.top/Article/details/gtsuicdczd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guowangkeji.top/Article/details/gtsdifgpph.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jyoumei.cn/Article/details/gtzwlurqhw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ppjwa.cn/Article/details/gtbkqxdwos.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jqgfzy.top/Article/details/gtakvqktgc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yuxming.cn/Article/details/gtmcwcpqvd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shzxlz.cn/Article/details/gtxorrltxs.html

[J10] 取今天 / 本月第一天
来源：http://dali.svipenyu.cn/Article/details/gtjbpfxxva.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shzxlz.cn/Article/details/gtwcutotie.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cheryme.top/Article/details/gtzierajml.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zycfv.cn/Article/details/gtdrpgrmgj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shzxlz.cn/Article/details/gtscjyfsin.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ivvv.top/Article/details/gtsfwzozmd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinghuilouyu.cn/Article/details/gtyiudjsxu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ivvv.top/Article/details/gtywmsjcke.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.fengsongda.top/Article/details/gtcllvfrvc.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtphqenknm.html

K. JSON 与序列化
来源：http://dali.andypj.xyz/Article/details/gtexzelirr.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtjvaivaca.html

[K01] 对象转 JSON 字符串
来源：http://dali.nanxuanxn.top/Article/details/gtlmgwebfw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.svipenyu.cn/Article/details/gtlyfdhijd.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.snrcjt.cn/Article/details/gtuoachbmt.html

JS:   JSON.stringify(obj)
来源：http://dali.hammf.cn/Article/details/gtyvlonegl.html

TS:   JSON.stringify(obj)
来源：http://dali.yongpay.top/Article/details/gthiflktdn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.pengpengdd.cyou/Article/details/gtvehozwxz.html

Go:   json.Marshal(obj)
来源：http://dali.ehwqpu.com/Article/details/gtliszkewi.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yuanzhike.top/Article/details/gtjcptjqod.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hfpthk.cn/Article/details/gttsarqnon.html

[K02] JSON 字符串转对象
来源：http://dali.nanxuanxn.top/Article/details/gtixdhtmjy.html

Py:   json.loads(s)
来源：http://dali.yangfankeji.com/Article/details/gtdkaowiow.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.pengpengdd.cyou/Article/details/gtesejafzu.html

JS:   JSON.parse(s)
来源：http://dali.0kj1m.cn/Article/details/gtibxdyvlr.html

TS:   JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gtkpyqjxiq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.haohaochexian.top/Article/details/gtrujpiuxf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.guowangkeji.top/Article/details/gtzvlfuvsr.html

Ruby: JSON.parse(s)
来源：http://dali.yj20258888.top/Article/details/gtpzbtoxnb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.aizwys.cn/Article/details/gtpumwryak.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shzxlz.cn/Article/details/gtyjpofxiw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shuidangran.top/Article/details/gtaqbwsnby.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.wangdashe.top/Article/details/gtdzdefgmy.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zycfv.cn/Article/details/gtwjwwzyyv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yongpay.top/Article/details/gtcpydcksk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.bjfxy.top/Article/details/gtpiscoswo.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xuetiantiany.cn/Article/details/gtclsfvoje.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xylfe.cn/Article/details/gtdidiraah.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jlsjyb.cn/Article/details/gtfzxxxevm.html

[K04] 读取 JSON 文件
来源：http://dali.yj20258888.top/Article/details/gtwuscqyvg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gotoacloud.top/Article/details/gtcdugojzx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yangfankeji.com/Article/details/gtimxuevez.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ydzc1.top/Article/details/gtbhthkfxn.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkufvwfci.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.daxiang520.top/Article/details/gtiugawega.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cdnleiting.top/Article/details/gttrhefmmn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.havefunace.top/Article/details/gtfkodfmeu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.birdmap.top/Article/details/gtrzaiqfqw.html

[K05] 深拷贝对象
来源：http://dali.pycfn.com/Article/details/gtkrgyrjmv.html

Py:   copy.deepcopy(obj)
来源：http://dali.shzxlz.cn/Article/details/gtlyzhanhd.html

PHP:  unserialize(serialize($obj));
来源：http://dali.c1oappe.top/Article/details/gtvwwttcxk.html

JS:   structuredClone(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtfleoxiex.html

TS:   structuredClone(obj)
来源：http://dali.yvedp.cn/Article/details/gtpckuszna.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zdqjudy.top/Article/details/gtdmmgmccz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.fzhhl.top/Article/details/gtmkvhpifz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.bjfxy.top/Article/details/gtyzdzhhnw.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhixingplan.top/Article/details/gtmnpqiorf.html

[K06] 解析 URL 查询串
来源：http://dali.yvedp.cn/Article/details/gtjmvslnef.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ydzc1.top/Article/details/gtjwhahnoy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jianghu66.top/Article/details/gtgeumjtir.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.quarkkingdee.top/Article/details/gtrpsodrnr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zdqjudy.top/Article/details/gttlatmvlw.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gogol.net.cn/Article/details/gtsnnaxyho.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqjkhxujs.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hywenlv.cn/Article/details/gtjvnrzbkj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.mhx1999.top/Article/details/gtqsroserb.html

[K07] 进制转换
来源：http://dali.sysykeji.top/Article/details/gtcgynknrh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gtwnhnqkag.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hnqzz.top/Article/details/gtywoyijqe.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtkmbfwowz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gtgzywyeuh.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gtwztglhoj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xylfe.cn/Article/details/gtgqiqcmqf.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.feifeiyinyue.top/Article/details/gthhcalkhf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gtkbbfdfxr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hywenlv.cn/Article/details/gteiyvqmsk.html

Py:   pickle.dumps(obj)
来源：http://dali.gotoacloud.top/Article/details/gtooyijdse.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cheryme.top/Article/details/gtauzsmryb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhoulong.xyz/Article/details/gtwqtktugo.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shzxlz.cn/Article/details/gtrcvwgaoe.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ehwqpu.com/Article/details/gtugsklvks.html

Go:   encoding/gob
来源：http://dali.quarkkingdee.top/Article/details/gtbijveqnf.html

Ruby: Marshal.dump(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gthumlnvpf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.aibaodan.cn/Article/details/gtmkztszru.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtiqfmjymr.html

L. 网络请求
来源：http://dali.mhx1999.top/Article/details/gtwmoirenq.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtpgoijkxw.html

[L01] 发送 GET 请求
来源：http://dali.xylfe.cn/Article/details/gtutbfffdo.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yanxiufei.cn/Article/details/gtvijywtsx.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.smart0.xyz/Article/details/gtuonswixz.html

JS:   await fetch(url)
来源：http://dali.pycfn.com/Article/details/gtqxjjypuu.html

TS:   await fetch(url)
来源：http://dali.xuanzx.com/Article/details/gtfukusnua.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shuidangran.top/Article/details/gtxyfrbrvg.html

Go:   resp, err := http.Get(url)
来源：http://dali.yueranfly.top/Article/details/gtspmhzldg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hywenlv.cn/Article/details/gtzlrvdinc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.fengsongda.top/Article/details/gtenugurko.html

[L02] 发送 POST JSON
来源：http://dali.xinyue.icu/Article/details/gtvgrrdvix.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cheryme.top/Article/details/gtqcrkehmb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwyxznnwz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xziqi.cn/Article/details/gtkxqpykmt.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gaohongyu789.top/Article/details/gtcywbblnp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.meibo888.top/Article/details/gtktjjtfit.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.fzhhl.top/Article/details/gtibqyswhq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hysaishi.cn/Article/details/gtwwxyktrj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.aizwys.cn/Article/details/gtzwnuiocv.html

[L03] 设置自定义请求头
来源：http://dali.zycfv.cn/Article/details/gtiinmpocm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hysaishi.cn/Article/details/gtapwxbamt.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yj20258.top/Article/details/gtrdpilexn.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tian-w.cn/Article/details/gtvuqmgges.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenzaomai.com/Article/details/gtgwmlhbnc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.iojbl.cn/Article/details/gtgnoieaha.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ehwqpu.com/Article/details/gtotxlyacl.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xziqi.cn/Article/details/gtkxdujopt.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.tianlin.xyz/Article/details/gtlyvdpqsu.html

[L04] 设置超时
来源：http://dali.xinyue.icu/Article/details/gtnlfelgmn.html

Py:   requests.get(url, timeout=5)
来源：http://dali.andypj.xyz/Article/details/gtzzkkqhpl.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.tianlin.xyz/Article/details/gtgqmhecso.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.svipenyu.cn/Article/details/gtrwrpoprj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.smart0.xyz/Article/details/gtzwzemhya.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhengqikj.top/Article/details/gtxlajolmw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yvedp.cn/Article/details/gtimvatpfv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ehwqpu.com/Article/details/gteencuasj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gzhubu.top/Article/details/gtrceryfpl.html

[L05] 上传文件（multipart）
来源：http://dali.yanxiufei.cn/Article/details/gtupyfekru.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shuidangran.top/Article/details/gtwttmuhuv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zycfv.cn/Article/details/gtidvmulob.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.316326.xyz/Article/details/gtdvyfndog.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.daria6918.cn/Article/details/gtwpyajgzz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.snrcjt.cn/Article/details/gtrqiajgxl.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yj202588.top/Article/details/gtcgcuvvvc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yuxming.cn/Article/details/gtxouufrvd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtgjrlplsi.html

[L06] 解析响应为 JSON
来源：http://dali.xylfe.cn/Article/details/gtmhceoxrg.html

Py:   resp.json()
来源：http://dali.jinghuilouyu.cn/Article/details/gtfjhlnmvy.html

PHP:  json_decode($body, true);
来源：http://dali.shuidangran.top/Article/details/gteavkucuq.html

JS:   await resp.json()
来源：http://dali.cucudq.cn/Article/details/gthrsiprsn.html

TS:   await resp.json()
来源：http://dali.c1oappe.top/Article/details/gtihalfdkg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj20258.top/Article/details/gtppiqlatg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yvedp.cn/Article/details/gtjweblkww.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkzmfzaiy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gogol.net.cn/Article/details/gtwkgfidke.html

[L07] 处理 HTTP 状态码
来源：http://dali.hnqzz.top/Article/details/gtsvhybbed.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.fzhhl.top/Article/details/gtprwssnwp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.quarkkingdee.top/Article/details/gtdeyfowkd.html

JS:   resp.ok;  resp.status
来源：http://dali.wangshuangyany.cn/Article/details/gtoxwejmtr.html

TS:   resp.ok;  resp.status
来源：http://dali.gotoacloud.top/Article/details/gtziuybhxd.html

Java: resp.statusCode()
来源：http://dali.mhx1999.top/Article/details/gtqqfsmeyh.html

Go:   resp.StatusCode
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiihfunhp.html

Ruby: resp.code.to_i
来源：http://dali.yj20258888.top/Article/details/gtculsoppp.html

C#:   (int)resp.StatusCode
来源：http://dali.dianchejie.cn/Article/details/gtissrxoub.html

[L08] 并发请求多个地址
来源：http://dali.aizwys.cn/Article/details/gtitdtddhx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.daria6918.cn/Article/details/gtxhddkvph.html

PHP:  curl_multi_init() 系列
来源：http://dali.hywenlv.cn/Article/details/gtovecsqro.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuxming.cn/Article/details/gtdzvegmrw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yueranfly.top/Article/details/gtexthwfjv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.kuanghao11.cn/Article/details/gtfwvpilfn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinqigfzy.top/Article/details/gtibhnblsu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.gaohongyu789.top/Article/details/gtilmgjbub.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hywenlv.cn/Article/details/gtywgicdrl.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtrtwwecjg.html

M. 命令行 / 进程 / 环境
来源：http://dali.tanke756.top/Article/details/gtipvcedtr.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtzumqkkty.html

[M01] 读取命令行参数
来源：http://dali.svipenyu.cn/Article/details/gtjxhkmheb.html

Py:   sys.argv[1:]
来源：http://dali.ppjwa.cn/Article/details/gtegkdxagm.html

PHP:  $argv;  $argc;
来源：http://dali.birdmap.top/Article/details/gteenkdpbb.html

JS:   process.argv.slice(2)
来源：http://dali.jqgufenzy.top/Article/details/gtmilonnat.html

TS:   process.argv.slice(2)
来源：http://dali.tian-w.cn/Article/details/gttixbzkyh.html

Java: args 数组（main 方法参数）
来源：http://dali.fzhhl.top/Article/details/gtutstgwuq.html

Go:   os.Args[1:]
来源：http://dali.ppjwa.cn/Article/details/gtbqfrhrrw.html

Ruby: ARGV
来源：http://dali.dianchejie.cn/Article/details/gtcgpswked.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jqgufenzy.top/Article/details/gthxvjakpl.html

[M02] 读取环境变量
来源：http://dali.snrcjt.cn/Article/details/gtknrtptav.html

Py:   os.environ.get("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrukadbbl.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhengqikj.top/Article/details/gtxldzabum.html

JS:   process.env.HOME
来源：http://dali.svipenyu.cn/Article/details/gtbclnusil.html

TS:   process.env.HOME
来源：http://dali.yuxming.cn/Article/details/gtaqqkpopf.html

Java: System.getenv("HOME")
来源：http://dali.xuanzx.com/Article/details/gtnwavumlw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.andypj.xyz/Article/details/gtyawdbzor.html

Ruby: ENV["HOME"]
来源：http://dali.cucudq.cn/Article/details/gtxulofybv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.meibo888.top/Article/details/gtvacqsqca.html

[M03] 执行外部命令
来源：http://dali.shzxlz.cn/Article/details/gtmhmojpws.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gzhubu.top/Article/details/gtaxvcgmqw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.chenjidiqi.icu/Article/details/gtpazmkpkm.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenzaomai.com/Article/details/gtsokufzmb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yangfankeji.com/Article/details/gtbawofncw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sysykeji.top/Article/details/gtqjucbjoa.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gzhubu.top/Article/details/gtpnxiqadb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.smart0.xyz/Article/details/gtcuwpcvfo.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinghuilouyu.cn/Article/details/gtqpbakqhn.html

[M04] 获取当前工作目录
来源：http://dali.snrcjt.cn/Article/details/gtspapsjep.html

Py:   os.getcwd()
来源：http://dali.redwolf501.top/Article/details/gtjdmdziap.html

PHP:  getcwd();
来源：http://dali.zhixingplan.top/Article/details/gtkopowdyj.html

JS:   process.cwd()
来源：http://dali.yj20258.top/Article/details/gtjrysbgpd.html

TS:   process.cwd()
来源：http://dali.ehwqpu.com/Article/details/gtkjtkuvoo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.9152youxi.cn/Article/details/gtgcpbcjfr.html

Go:   os.Getwd()
来源：http://dali.zdqjudy.top/Article/details/gtmbrlpdvi.html

Ruby: Dir.pwd
来源：http://dali.zdqjudy.top/Article/details/gtnfuorslb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsclaevvn.html

[M05] 设置退出码
来源：http://dali.cdnleiting.top/Article/details/gtxirqskdq.html

Py:   sys.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gtfctdibyg.html

PHP:  exit(1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjodrqdyv.html

JS:   process.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gtdttkbflo.html

TS:   process.exit(1)
来源：http://dali.zycfv.cn/Article/details/gtixqhjrlc.html

Java: System.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gtuafthlxl.html

Go:   os.Exit(1)
来源：http://dali.sysykeji.top/Article/details/gtdcghffkl.html

Ruby: exit 1
来源：http://dali.jyoumei.cn/Article/details/gttmmycxpw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xuetiantiany.cn/Article/details/gtrwgobkdz.html

[M06] 向标准错误输出
来源：http://dali.fengsongda.top/Article/details/gtslemqydy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.pengpengdd.cyou/Article/details/gtzqjnjxyl.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jlsjyb.cn/Article/details/gtyybxxqap.html

JS:   console.error("err")
来源：http://dali.shuidangran.top/Article/details/gtxqtsdgak.html

TS:   console.error("err")
来源：http://dali.hammf.cn/Article/details/gtultsepkv.html

Java: System.err.println("err")
来源：http://dali.dianchejie.cn/Article/details/gtejnzsjgu.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xuanzx.com/Article/details/gtgtdbajax.html

Ruby: warn "err"
来源：http://dali.9152youxi.cn/Article/details/gtzeigxvas.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cqqwz.cn/Article/details/gtocwnazzz.html

[M07] 判断是否为主入口
来源：http://dali.feifeiyinyue.top/Article/details/gtrjkncofs.html

Py:   if __name__ == "__main__":
来源：http://dali.ivvv.top/Article/details/gtwwvcfouv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.wangshuangyany.cn/Article/details/gtyfirbojt.html

JS:   require.main === module
来源：http://dali.aibaodan.cn/Article/details/gtwdcgmhwp.html

TS:   require.main === module
来源：http://dali.c1oappe.top/Article/details/gtlwjmywby.html

Java: public static void main(String[] args)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwgxaowxc.html

Go:   func main()
来源：http://dali.cheryme.top/Article/details/gtmftiepbo.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenjidiqi.icu/Article/details/gtwrzeuhpl.html

C#:   static void Main(string[] args)
来源：http://dali.jianghu66.top/Article/details/gtkihjzeqs.html

[M08] 获取系统与运行时信息
来源：http://dali.svipenyu.cn/Article/details/gtswrhocgn.html

Py:   platform.system();  platform.python_version()
来源：http://dali.wangdashe.top/Article/details/gtlrjfecaw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jqgufenzy.top/Article/details/gtszevkddp.html

JS:   process.platform;  process.version
来源：http://dali.gzhubu.top/Article/details/gtpobqxogo.html

TS:   process.platform;  process.version
来源：http://dali.havefunace.top/Article/details/gtvyfsrjfx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hywenlv.cn/Article/details/gtlzikihcf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yueranfly.top/Article/details/gtisbwvafk.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shangyingyoupin.top/Article/details/gteqhexwbg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yj20258.top/Article/details/gtnkntauxt.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtbkljdlmi.html

N. 数据结构与算法
来源：http://dali.pycfn.com/Article/details/gtqnfcvugl.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtqfnkutxv.html

[N01] 二分查找（有序数组）
来源：http://dali.shzxlz.cn/Article/details/gtwonlaufm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkbssbowo.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhixingplan.top/Article/details/gtscuspyei.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ehwqpu.com/Article/details/gtykhwizub.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhoulong.xyz/Article/details/gthedbpmkq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cashguo.top/Article/details/gtrfiymcgw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtnuasxbhh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.tian-w.cn/Article/details/gtiwzzmdbb.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvncohbjj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gzhubu.top/Article/details/gtbtsvzujc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.guowangkeji.top/Article/details/gthizviint.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yj202588.top/Article/details/gttexgphhe.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yvedp.cn/Article/details/gtvrehzgeo.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ivvv.top/Article/details/gtqanimpbb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.andypj.xyz/Article/details/gtlwluprdb.html

Go:   slices.Sort(arr)
来源：http://dali.yuxming.cn/Article/details/gtibnrdzxh.html

Ruby: arr.sort
来源：http://dali.gotoacloud.top/Article/details/gthyfbnomd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.aizwys.cn/Article/details/gtngamenln.html

[N03] 快速排序（分治示例）
来源：http://dali.shzxlz.cn/Article/details/gtxkvnbkfv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.dianchejie.cn/Article/details/gtubuqmlbn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.mhx1999.top/Article/details/gtlcwdejkv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dashuyun.cn/Article/details/gtjkphgobg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ppjwa.cn/Article/details/gtbqobjbmq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shangyingyoupin.top/Article/details/gtindedysu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhengqikj.top/Article/details/gttixrpkdj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hywenlv.cn/Article/details/gtprskcujl.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hammf.cn/Article/details/gtntxegflm.html

[N04] 斐波那契数列
来源：http://dali.jyoumei.cn/Article/details/gtqmluzqub.html


<!-- 参考信息 -->