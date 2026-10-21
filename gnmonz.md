代发 wailian999

[J07] 比较两个日期
来源：http://dali.pengpengdd.cyou/Article/details/gtjgrwludk.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.nanxuanxn.top/Article/details/gteivamqzd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.iojbl.cn/Article/details/gtjjbxyhix.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.daria6918.cn/Article/details/gtkkpduejl.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zycfv.cn/Article/details/gtihpbufbe.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gogol.net.cn/Article/details/gtububjnmm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.daxiang520.top/Article/details/gtlsndssfx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.pengpengdd.cyou/Article/details/gtfpkdskdv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gtkfkkrglg.html

[J08] 提取年月日与星期
来源：http://dali.daxiang520.top/Article/details/gtlxqyqgmq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.316326.xyz/Article/details/gtdtoygqkn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yuxming.cn/Article/details/gtjknlopnv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.wangshuangyany.cn/Article/details/gtwkcknnye.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.iojbl.cn/Article/details/gtrhivgelp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.nanxuanxn.top/Article/details/gtzrpdaxck.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.pengpengdd.cyou/Article/details/gtpsbtbxwj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cqqwz.cn/Article/details/gtnzvvuwks.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.chenzaomai.com/Article/details/gtmfbwirsf.html

[J09] 时区处理
来源：http://dali.aibaodan.cn/Article/details/gttbtgwvce.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.kuanghao11.cn/Article/details/gtezbbfmhx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gaohongyu789.top/Article/details/gtwnwzehch.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hammf.cn/Article/details/gtrkyxrvny.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daxiang520.top/Article/details/gtaysxknah.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shangyingyoupin.top/Article/details/gtralvysnp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.aizwys.cn/Article/details/gtpsgmrjeh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cashguo.top/Article/details/gtupkfmzjr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xylfe.cn/Article/details/gtyrfowsth.html

[J10] 取今天 / 本月第一天
来源：http://dali.quarkkingdee.top/Article/details/gttzcwmygk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.daxiang520.top/Article/details/gtpleiedlq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinqigufen.top/Article/details/gtcmdudnfc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xziqi.cn/Article/details/gtohukyfyd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.haohaochexian.top/Article/details/gtojplpten.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj20258.top/Article/details/gtzwmwgysv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.dashuyun.cn/Article/details/gtrckkwwcd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xinyue.icu/Article/details/gtuybvfrxm.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xziqi.cn/Article/details/gtnrbnlqxn.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtunwkpdje.html

K. JSON 与序列化
来源：http://dali.zhiwuduotai.top/Article/details/gtvbwtcuad.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtpfsexgxu.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqhdguxba.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sysykeji.top/Article/details/gtrtkywykn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.dianchejie.cn/Article/details/gtxpgcppdo.html

JS:   JSON.stringify(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtekgmuyps.html

TS:   JSON.stringify(obj)
来源：http://dali.jyoumei.cn/Article/details/gtazciyxam.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shanyushiyangtech.top/Article/details/gtwbkvqkqi.html

Go:   json.Marshal(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtfelluxrf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gotoacloud.top/Article/details/gtipoeolha.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwbksosuw.html

[K02] JSON 字符串转对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmbdspttb.html

Py:   json.loads(s)
来源：http://dali.gzhubu.top/Article/details/gteolaexsv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cashguo.top/Article/details/gtbvdgjewq.html

JS:   JSON.parse(s)
来源：http://dali.jqgfzy.top/Article/details/gtnxlewvre.html

TS:   JSON.parse(s)
来源：http://dali.nwbrower.top/Article/details/gtlkyaaada.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yangfankeji.com/Article/details/gtuwvcxpzg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.aizwys.cn/Article/details/gtwjhiewov.html

Ruby: JSON.parse(s)
来源：http://dali.aizwys.cn/Article/details/gtzlahqhdm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jiagoushi.top/Article/details/gtohjfakne.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.svipenyu.cn/Article/details/gtiadsnmtm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ppjwa.cn/Article/details/gtrtuluxkd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gogol.net.cn/Article/details/gtztwiphng.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tanke756.top/Article/details/gtryqusnsi.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.aibaodan.cn/Article/details/gtizetwalz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yueranfly.top/Article/details/gtnjnhzaah.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yanxiufei.cn/Article/details/gthmokebhi.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gotoacloud.top/Article/details/gtdjstbnwh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cdnleiting.top/Article/details/gtkfebgsfx.html

[K04] 读取 JSON 文件
来源：http://dali.dashuyun.cn/Article/details/gtdfuumoro.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.chenzaomai.com/Article/details/gtaxbnalac.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yueranfly.top/Article/details/gtfttdecvx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daxiang520.top/Article/details/gttrrybasx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cheryme.top/Article/details/gtmmpfgrvr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hnqzz.top/Article/details/gtpadebvtp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhiwuduotai.top/Article/details/gttjrqlarm.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvyifplye.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ppjwa.cn/Article/details/gtzgpehttc.html

[K05] 深拷贝对象
来源：http://dali.jyoumei.cn/Article/details/gtygpmnftq.html

Py:   copy.deepcopy(obj)
来源：http://dali.daria6918.cn/Article/details/gtbehulpcc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.iojbl.cn/Article/details/gtjmpemgmi.html

JS:   structuredClone(obj)
来源：http://dali.ydzc1.top/Article/details/gtswlewohy.html

TS:   structuredClone(obj)
来源：http://dali.aizwys.cn/Article/details/gtypftxffq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.haohaochexian.top/Article/details/gthladjvvd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.316326.xyz/Article/details/gtcsdzeniq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.chenzaomai.com/Article/details/gtcceovebt.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yongpay.top/Article/details/gtxdriasnk.html

[K06] 解析 URL 查询串
来源：http://dali.jlsjyb.cn/Article/details/gtwopejeia.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwijhdgde.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.sufxvd.cn/Article/details/gtyosgphue.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkjezivum.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangdashe.top/Article/details/gtxynmiiae.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shangyingyoupin.top/Article/details/gtyxezosru.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shzxlz.cn/Article/details/gtwibwibut.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gtpaymmypf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.pengpengdd.cyou/Article/details/gtzbjanlkh.html

[K07] 进制转换
来源：http://dali.jianghu66.top/Article/details/gtjjhehyyf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpvjgmuut.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.birdmap.top/Article/details/gtsyddphsw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gtggdsqapr.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gtwwrdbdbq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yj202588.top/Article/details/gtfzygyyrb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhoulong.xyz/Article/details/gtkwntdass.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.smart0.xyz/Article/details/gtgjmxvrzp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gtbtbfiysk.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yangfankeji.com/Article/details/gtipyudaer.html

Py:   pickle.dumps(obj)
来源：http://dali.zhoulong.xyz/Article/details/gthcvuasis.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.wangdashe.top/Article/details/gtuktywuvv.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhiwuduotai.top/Article/details/gtodrpgfsl.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigfzy.top/Article/details/gtzccmfwhj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.guowangkeji.top/Article/details/gtmqtveijq.html

Go:   encoding/gob
来源：http://dali.xuetiantiany.cn/Article/details/gthcdwztsl.html

Ruby: Marshal.dump(obj)
来源：http://dali.zycfv.cn/Article/details/gtyinodbum.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.chenzaomai.com/Article/details/gtscdzhewd.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrrckgxud.html

L. 网络请求
来源：http://dali.9152youxi.cn/Article/details/gtaqkgcnbd.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gthtoazngw.html

[L01] 发送 GET 请求
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqaqqzmde.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.gogol.net.cn/Article/details/gtrdflxuxz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.fzhhl.top/Article/details/gticcoeuew.html

JS:   await fetch(url)
来源：http://dali.aizwys.cn/Article/details/gtnlymvqaq.html

TS:   await fetch(url)
来源：http://dali.kuanghao11.cn/Article/details/gtvpzlbdlr.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ybcxt.top/Article/details/gtqozmmtwn.html

Go:   resp, err := http.Get(url)
来源：http://dali.havefunace.top/Article/details/gtpmtblror.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gogol.net.cn/Article/details/gtduoltqsz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zdqjudy.top/Article/details/gtbqvfpcyi.html

[L02] 发送 POST JSON
来源：http://dali.nwbrower.top/Article/details/gtbimmhrdu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenjidiqi.icu/Article/details/gtutfbjlxo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zdqjudy.top/Article/details/gtedeiewxm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shuidangran.top/Article/details/gtpxgeivqy.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hnqzz.top/Article/details/gtlfjtxqqo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gotoacloud.top/Article/details/gtojhpvsad.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cucudq.cn/Article/details/gtiilvguig.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yj202588.top/Article/details/gtbdjskalq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhiwuduotai.top/Article/details/gttygtebpg.html

[L03] 设置自定义请求头
来源：http://dali.ybcxt.top/Article/details/gtjlgsraqz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shzxlz.cn/Article/details/gtiypkaxvt.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinqigufen.top/Article/details/gtzhibahdk.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.mhx1999.top/Article/details/gtibctoint.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yanxiufei.cn/Article/details/gtpggivqsp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shzxlz.cn/Article/details/gtggplhclw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlcqbacpk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shzxlz.cn/Article/details/gtuhslepmg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jianghu66.top/Article/details/gtmqnthxet.html

[L04] 设置超时
来源：http://dali.yj20258888.top/Article/details/gthwkebsmf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.nwbrower.top/Article/details/gtdfcddrzz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ppjwa.cn/Article/details/gturfcortk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenzaomai.com/Article/details/gttavopxhd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuetiantiany.cn/Article/details/gtaeccqdbh.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzeatvabr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gaohongyu789.top/Article/details/gtkntiheus.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jianghu66.top/Article/details/gtbzkxemxp.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ehwqpu.com/Article/details/gtjehwuyyb.html

[L05] 上传文件（multipart）
来源：http://dali.nanxinkj.top/Article/details/gtuqwhiuaj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hysaishi.cn/Article/details/gtkhhdhuvq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.9152youxi.cn/Article/details/gtbxpcawfv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.daria6918.cn/Article/details/gtzvcpunjc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gotoacloud.top/Article/details/gtgssnnwoc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hongshengwenyu.top/Article/details/gtcxbzpqjh.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gaohongyu789.top/Article/details/gtarfffjjh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sufxvd.cn/Article/details/gtzfivtixg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yvedp.cn/Article/details/gthsmbtjcm.html

[L06] 解析响应为 JSON
来源：http://dali.yongpay.top/Article/details/gtwrjvogdy.html

Py:   resp.json()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrckdtptk.html

PHP:  json_decode($body, true);
来源：http://dali.redwolf501.top/Article/details/gtycmhroxk.html

JS:   await resp.json()
来源：http://dali.ydzc1.top/Article/details/gthgbxcplz.html

TS:   await resp.json()
来源：http://dali.cqqwz.cn/Article/details/gtgnczvuol.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jlsjyb.cn/Article/details/gtslwjockn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrzspjxlq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.chenlongwang.top/Article/details/gtysqmhpio.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.aizwys.cn/Article/details/gtnqnkdovd.html

[L07] 处理 HTTP 状态码
来源：http://dali.sweek.top/Article/details/gtumlylnrp.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jlsjyb.cn/Article/details/gthhruyxlp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sweek.top/Article/details/gtifqisrnn.html

JS:   resp.ok;  resp.status
来源：http://dali.316326.xyz/Article/details/gtqpuozynv.html

TS:   resp.ok;  resp.status
来源：http://dali.xuetiantiany.cn/Article/details/gtmfddonlb.html

Java: resp.statusCode()
来源：http://dali.shzxlz.cn/Article/details/gtdnqcmvkr.html

Go:   resp.StatusCode
来源：http://dali.bjfxy.top/Article/details/gtwhbdpjzz.html

Ruby: resp.code.to_i
来源：http://dali.yangfankeji.com/Article/details/gtgoulzjwb.html

C#:   (int)resp.StatusCode
来源：http://dali.cdnleiting.top/Article/details/gtlcadbmyt.html

[L08] 并发请求多个地址
来源：http://dali.fzhhl.top/Article/details/gtmnpuitwf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jinyuanbaomall.cn/Article/details/gtostopcjt.html

PHP:  curl_multi_init() 系列
来源：http://dali.smart0.xyz/Article/details/gttjjtgiju.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fengsongda.top/Article/details/gtyqtdubro.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxuanxn.top/Article/details/gtrgrfazab.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yj202588.top/Article/details/gtmarevhow.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.feifeiyinyue.top/Article/details/gtojigfbkk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhongyouzk.top/Article/details/gtilztmmzd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.svipenyu.cn/Article/details/gtbtdctfbs.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtathzbnel.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzwfqwprn.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtbkydmmmo.html

[M01] 读取命令行参数
来源：http://dali.tian-w.cn/Article/details/gtvksqskjk.html

Py:   sys.argv[1:]
来源：http://dali.c1oappe.top/Article/details/gtpicsnrza.html

PHP:  $argv;  $argc;
来源：http://dali.jlsjyb.cn/Article/details/gtdwdavklq.html

JS:   process.argv.slice(2)
来源：http://dali.hnqzz.top/Article/details/gteazrajax.html

TS:   process.argv.slice(2)
来源：http://dali.dianchejie.cn/Article/details/gtgmabkfsn.html

Java: args 数组（main 方法参数）
来源：http://dali.jinqigfzy.top/Article/details/gteopnpaeb.html

Go:   os.Args[1:]
来源：http://dali.jiagoushi.top/Article/details/gtrklchenh.html

Ruby: ARGV
来源：http://dali.sxryk.cn/Article/details/gtirtkuhru.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sufxvd.cn/Article/details/gtdbmpynjh.html

[M02] 读取环境变量
来源：http://dali.c1oappe.top/Article/details/gtjgrctsdr.html

Py:   os.environ.get("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvcqcfpqu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nwbrower.top/Article/details/gtkofztoau.html

JS:   process.env.HOME
来源：http://dali.smart0.xyz/Article/details/gtulgkzqxr.html

TS:   process.env.HOME
来源：http://dali.nwbrower.top/Article/details/gtrltjonwy.html

Java: System.getenv("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlnvrbjzd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yuanzhike.top/Article/details/gtlkgqmscw.html

Ruby: ENV["HOME"]
来源：http://dali.9152youxi.cn/Article/details/gtwuvjrhup.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.daria6918.cn/Article/details/gtkovkejai.html

[M03] 执行外部命令
来源：http://dali.guowangkeji.top/Article/details/gtksaqwoyq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ivvv.top/Article/details/gtbsmntbhj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.c1oappe.top/Article/details/gtsxxojzai.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hongshengwenyu.top/Article/details/gtgtetdrrx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ydzc1.top/Article/details/gtkntynkuf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jyoumei.cn/Article/details/gtwunpwphp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.feifeiyinyue.top/Article/details/gtzkkjwwrk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yongpay.top/Article/details/gtfmkrbjcf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jiagoushi.top/Article/details/gtccqjudso.html

[M04] 获取当前工作目录
来源：http://dali.haohaochexian.top/Article/details/gttxuzaojj.html

Py:   os.getcwd()
来源：http://dali.jqgufenzy.top/Article/details/gtjiqgmduu.html

PHP:  getcwd();
来源：http://dali.iojbl.cn/Article/details/gtkbccpypp.html

JS:   process.cwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoxsoprvw.html

TS:   process.cwd()
来源：http://dali.wangshuangyany.cn/Article/details/gtqydicyks.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shuidangran.top/Article/details/gtwvvuifcw.html

Go:   os.Getwd()
来源：http://dali.nwbrower.top/Article/details/gtbqtdpahi.html

Ruby: Dir.pwd
来源：http://dali.sysykeji.top/Article/details/gttawfezts.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nwbrower.top/Article/details/gtmmdrbkps.html

[M05] 设置退出码
来源：http://dali.316326.xyz/Article/details/gtgnmfmrzw.html

Py:   sys.exit(1)
来源：http://dali.cucudq.cn/Article/details/gtpmoohdoc.html

PHP:  exit(1);
来源：http://dali.yvedp.cn/Article/details/gtlefpmxvo.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtiozrmafh.html

TS:   process.exit(1)
来源：http://dali.sxryk.cn/Article/details/gtajddghog.html

Java: System.exit(1)
来源：http://dali.mhx1999.top/Article/details/gtlswtxokk.html

Go:   os.Exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtycsdglff.html

Ruby: exit 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtokepbfvv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.meibo888.top/Article/details/gtfbqqcgak.html

[M06] 向标准错误输出
来源：http://dali.dianchejie.cn/Article/details/gteepfhamo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.fengsongda.top/Article/details/gtjoeavwzy.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.pycfn.com/Article/details/gtqfzywsbt.html

JS:   console.error("err")
来源：http://dali.hywenlv.cn/Article/details/gtarbagped.html

TS:   console.error("err")
来源：http://dali.tianlin.xyz/Article/details/gteopcowga.html

Java: System.err.println("err")
来源：http://dali.aizwys.cn/Article/details/gtjultzmtw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.daxiang520.top/Article/details/gthdvjwfsa.html

Ruby: warn "err"
来源：http://dali.pengpengdd.cyou/Article/details/gtgovmjapw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gzhubu.top/Article/details/gtvgdihfep.html

[M07] 判断是否为主入口
来源：http://dali.yj20258888.top/Article/details/gtlwwdufdg.html

Py:   if __name__ == "__main__":
来源：http://dali.xuanzx.com/Article/details/gtsagxjfjt.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.316326.xyz/Article/details/gtqwxrcufm.html

JS:   require.main === module
来源：http://dali.tianlin.xyz/Article/details/gtngvsytte.html

TS:   require.main === module
来源：http://dali.sysykeji.top/Article/details/gtmcqwtyzf.html

Java: public static void main(String[] args)
来源：http://dali.sweek.top/Article/details/gttaohcgur.html

Go:   func main()
来源：http://dali.chenjidiqi.icu/Article/details/gtrlrushsy.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yuanzhike.top/Article/details/gtkoyvcgdy.html

C#:   static void Main(string[] args)
来源：http://dali.9152youxi.cn/Article/details/gtjldovakx.html

[M08] 获取系统与运行时信息
来源：http://dali.chenzaomai.com/Article/details/gtgjkmdtwo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jiagoushi.top/Article/details/gtziwopbuw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hammf.cn/Article/details/gtvcmltzov.html

JS:   process.platform;  process.version
来源：http://dali.jiagoushi.top/Article/details/gtutdomtcv.html

TS:   process.platform;  process.version
来源：http://dali.hywenlv.cn/Article/details/gtgedmjocp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwejsdxrp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfivrooho.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.snrcjt.cn/Article/details/gtevxkpdub.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.snrcjt.cn/Article/details/gtuojgyten.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtkqhjhfai.html

N. 数据结构与算法
来源：http://dali.yanxiufei.cn/Article/details/gtpsweksel.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtjowmakgw.html

[N01] 二分查找（有序数组）
来源：http://dali.chenjidiqi.icu/Article/details/gtycqyaeoa.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtoceuozjv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hammf.cn/Article/details/gtbffmontj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.quarkkingdee.top/Article/details/gtzwyujbau.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.svipenyu.cn/Article/details/gtgcttmbsl.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.sysykeji.top/Article/details/gtmazvzpbu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yueranfly.top/Article/details/gtpkgihnfg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.0kj1m.cn/Article/details/gtsjijlagn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtzynzubws.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gotoacloud.top/Article/details/gtqttksdha.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xziqi.cn/Article/details/gtywnrrlcq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.dianchejie.cn/Article/details/gtyrpkwkwv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zycfv.cn/Article/details/gtubadqsvr.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhoulong.xyz/Article/details/gtfugwqxfv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hnxiangtu.top/Article/details/gtmsqeozhk.html

Go:   slices.Sort(arr)
来源：http://dali.bjfxy.top/Article/details/gtfmrnskei.html

Ruby: arr.sort
来源：http://dali.hnqzz.top/Article/details/gtzkpcdexe.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhoulong.xyz/Article/details/gtgquzhsbf.html

[N03] 快速排序（分治示例）
来源：http://dali.bjfxy.top/Article/details/gteiopzdhq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jqgufenzy.top/Article/details/gtplwaiadj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xuanzx.com/Article/details/gtcrrekttd.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guannengcc.top/Article/details/gtxmqdioxl.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhiwuduotai.top/Article/details/gthgluaeoi.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.wangdashe.top/Article/details/gtsjtwvczl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.nanxinkj.top/Article/details/gtwsrotdww.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hysaishi.cn/Article/details/gtaeaulenb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cdnleiting.top/Article/details/gtoeywqzei.html

[N04] 斐波那契数列
来源：http://dali.jinqigfzy.top/Article/details/gtjjxygfjd.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hammf.cn/Article/details/gtghyzhgcg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ivvv.top/Article/details/gtnrmunmuh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgufenzy.top/Article/details/gtehjskboc.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cheryme.top/Article/details/gttfreoaqj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtymqphaje.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.nwbrower.top/Article/details/gtikvyozvw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtwurxumqo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yuanzhike.top/Article/details/gtcnjegkgv.html


<!-- 参考信息 -->