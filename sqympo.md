代发 wailian999

C#:   d1 < d2;  d1 == d2
来源：http://dali.smart0.xyz/Article/details/gtxrzasanw.html

[J08] 提取年月日与星期
来源：http://dali.sufxvd.cn/Article/details/gtqxarnoyl.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdbdmuwua.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.tanke756.top/Article/details/gtjnfgfxvh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.andypj.xyz/Article/details/gttwbflgrk.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.aizwys.cn/Article/details/gtvjuaalqk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.316326.xyz/Article/details/gtdvaxnkkr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbshobojg.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.redwolf501.top/Article/details/gtezyswnge.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gzhubu.top/Article/details/gtepwklpad.html

[J09] 时区处理
来源：http://dali.yonumen.top/Article/details/gtljaukddq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gogol.net.cn/Article/details/gtpdtokthb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.dianchejie.cn/Article/details/gtcpbqwixw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jlsjyb.cn/Article/details/gtnjlmuvoq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cqqwz.cn/Article/details/gthbcpxrke.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yonumen.top/Article/details/gtufwytcki.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ppjwa.cn/Article/details/gtkzucwrer.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nanxinkj.top/Article/details/gttlyrlmrt.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdklevfjt.html

[J10] 取今天 / 本月第一天
来源：http://dali.redwolf501.top/Article/details/gtknmknroy.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zycfv.cn/Article/details/gtebtthpph.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.quarkkingdee.top/Article/details/gtrwsfezmp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jiagoushi.top/Article/details/gtzhzmpbsa.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtsgcoprij.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yongpay.top/Article/details/gtmheyqoak.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cdnleiting.top/Article/details/gtmiflsgof.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.guannengcc.top/Article/details/gtjpbvqnbm.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xinyue.icu/Article/details/gtlxzrhdui.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtgepzxjnw.html

K. JSON 与序列化
来源：http://dali.jinqigufen.top/Article/details/gtupvmizfn.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtooptlhct.html

[K01] 对象转 JSON 字符串
来源：http://dali.gogol.net.cn/Article/details/gtdgzbplgh.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ybcxt.top/Article/details/gtpdilrkpg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258888.top/Article/details/gtrgjwmuaa.html

JS:   JSON.stringify(obj)
来源：http://dali.hammf.cn/Article/details/gtdaojghhd.html

TS:   JSON.stringify(obj)
来源：http://dali.daria6918.cn/Article/details/gtapdeygjt.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xziqi.cn/Article/details/gtiohfatqw.html

Go:   json.Marshal(obj)
来源：http://dali.cqqwz.cn/Article/details/gtzsdozeic.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sysykeji.top/Article/details/gtyazutffd.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.svipenyu.cn/Article/details/gtlfulsfmi.html

[K02] JSON 字符串转对象
来源：http://dali.guannengcc.top/Article/details/gtcbiotecz.html

Py:   json.loads(s)
来源：http://dali.jqgufenzy.top/Article/details/gtenicytxl.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.dianchejie.cn/Article/details/gtvvuunwfq.html

JS:   JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gtmauvhodg.html

TS:   JSON.parse(s)
来源：http://dali.tanke756.top/Article/details/gtxqzlyelm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.9152youxi.cn/Article/details/gtpdowdkfy.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shangyingyoupin.top/Article/details/gtzdywxmwi.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gtoyrieqct.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.quarkkingdee.top/Article/details/gtbqvzspvt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ehwqpu.com/Article/details/gtufnbxnyv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hongshengwenyu.top/Article/details/gtadklzutu.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jianghu66.top/Article/details/gtqoiftorj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xinyue.icu/Article/details/gthptheqyn.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jlsjyb.cn/Article/details/gtzefqbcwc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtspmpdlsl.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtusezazod.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jianghu66.top/Article/details/gtmsccsqyb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sufxvd.cn/Article/details/gtgputnzzs.html

[K04] 读取 JSON 文件
来源：http://dali.nanxinkj.top/Article/details/gtbrfudeir.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hammf.cn/Article/details/gtwejxaoje.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinqigufen.top/Article/details/gtuzggndai.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.feifeiyinyue.top/Article/details/gtpjspehuy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pycfn.com/Article/details/gtmhfhihsz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.316326.xyz/Article/details/gtozbbafxn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangtech.top/Article/details/gttyusfkcx.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gogol.net.cn/Article/details/gtnmwloasa.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cdnleiting.top/Article/details/gtlssqycrc.html

[K05] 深拷贝对象
来源：http://dali.cucudq.cn/Article/details/gtuhqczcaq.html

Py:   copy.deepcopy(obj)
来源：http://dali.yj20258888.top/Article/details/gtqxgukjuk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.aibaodan.cn/Article/details/gtqtjxyvdc.html

JS:   structuredClone(obj)
来源：http://dali.haohaochexian.top/Article/details/gtfiqqbrmd.html

TS:   structuredClone(obj)
来源：http://dali.iojbl.cn/Article/details/gtkvdwwzvq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmgaexrpy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.haohaochexian.top/Article/details/gtkipneirx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yj20258.top/Article/details/gtgzvtydmm.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.tanke756.top/Article/details/gtsfezpycl.html

[K06] 解析 URL 查询串
来源：http://dali.shangyingyoupin.top/Article/details/gtrucgviej.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jqgfzy.top/Article/details/gtkoaxehpa.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ivvv.top/Article/details/gtzfaqrpta.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sysykeji.top/Article/details/gtqefkacvm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daria6918.cn/Article/details/gtyocqyhav.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ivvv.top/Article/details/gtwfkmwbxv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.feifeiyinyue.top/Article/details/gtznnfgapb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yvedp.cn/Article/details/gthwavqsee.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.0kj1m.cn/Article/details/gtemtjbnxo.html

[K07] 进制转换
来源：http://dali.fengsongda.top/Article/details/gttrhjlxlm.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tanke756.top/Article/details/gtuaxxcksv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zdqjudy.top/Article/details/gtjwasiilc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gtcuhgbpyt.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gtyfpmxsbt.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gtsatdztjm.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xuetiantiany.cn/Article/details/gtyyblltnw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.316326.xyz/Article/details/gtwjobwwja.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gtoalpzncs.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhixingplan.top/Article/details/gttzydlfwr.html

Py:   pickle.dumps(obj)
来源：http://dali.zdqjudy.top/Article/details/gtupetphpd.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jlsjyb.cn/Article/details/gtznzkxzzz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.snrcjt.cn/Article/details/gttcoyuwlo.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cashguo.top/Article/details/gtcalcrbth.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.vqdsnc.cn/Article/details/gtnjozwedy.html

Go:   encoding/gob
来源：http://dali.hammf.cn/Article/details/gtjsygeqck.html

Ruby: Marshal.dump(obj)
来源：http://dali.haohaochexian.top/Article/details/gtkcpgbegj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.dashuyun.cn/Article/details/gtyxgcrnid.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtttktmfgy.html

L. 网络请求
来源：http://dali.chenlongwang.top/Article/details/gtkyxfknlf.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtivfhavie.html

[L01] 发送 GET 请求
来源：http://dali.ydzc1.top/Article/details/gtenpekccf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.c1oappe.top/Article/details/gtihtbxigf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sweek.top/Article/details/gtcsdabvep.html

JS:   await fetch(url)
来源：http://dali.yueranfly.top/Article/details/gtlseyawcg.html

TS:   await fetch(url)
来源：http://dali.ppjwa.cn/Article/details/gtqdtpfylb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.redwolf501.top/Article/details/gtwxafsygh.html

Go:   resp, err := http.Get(url)
来源：http://dali.fzhhl.top/Article/details/gtfvbnyocu.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cucudq.cn/Article/details/gttftcyodh.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.c1oappe.top/Article/details/gttuuzshfn.html

[L02] 发送 POST JSON
来源：http://dali.nanxinkj.top/Article/details/gtjafsbghz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.feifeiyinyue.top/Article/details/gthamrzxce.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xuetiantiany.cn/Article/details/gtodotobiu.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yanxiufei.cn/Article/details/gtoccsberi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ivvv.top/Article/details/gtjoutdxqy.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.0kj1m.cn/Article/details/gtdakglkuz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwwrgzegw.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zdqjudy.top/Article/details/gtrppqkopu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jiagoushi.top/Article/details/gtavukamrz.html

[L03] 设置自定义请求头
来源：http://dali.vqdsnc.cn/Article/details/gtuyyzewce.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.wangshuangyany.cn/Article/details/gtogrubsau.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yangfankeji.com/Article/details/gtltllpocq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhiwuduotai.top/Article/details/gtcagodtot.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuezehetw.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ydzc1.top/Article/details/gttsbjxksu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.pengpengdd.cyou/Article/details/gtlkcxwndv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xuetiantiany.cn/Article/details/gtqzdpcewo.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.guowangkeji.top/Article/details/gtkjhyxlrt.html

[L04] 设置超时
来源：http://dali.feifeiyinyue.top/Article/details/gtrrishigs.html

Py:   requests.get(url, timeout=5)
来源：http://dali.mhx1999.top/Article/details/gtnqvrhkzm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yonumen.top/Article/details/gtamxpaher.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yueranfly.top/Article/details/gtteaqzldc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yangfankeji.com/Article/details/gtlogmfgtk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hywenlv.cn/Article/details/gtwfavvbjr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gogol.net.cn/Article/details/gtwezqkwrt.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yuxming.cn/Article/details/gttuempxcs.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zycfv.cn/Article/details/gtvygztgps.html

[L05] 上传文件（multipart）
来源：http://dali.jlsjyb.cn/Article/details/gtnxafgwyh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nwbrower.top/Article/details/gtzhbphgrn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gaohongyu789.top/Article/details/gtczutsjuj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.vqdsnc.cn/Article/details/gtdboqhtwo.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.aibaodan.cn/Article/details/gtcaiusxuq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hysaishi.cn/Article/details/gtocomfarb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.fengsongda.top/Article/details/gtwvtvnouj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ivvv.top/Article/details/gtrcgogejk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.aibaodan.cn/Article/details/gttzgchwjm.html

[L06] 解析响应为 JSON
来源：http://dali.tianlin.xyz/Article/details/gtcyqvkgte.html

Py:   resp.json()
来源：http://dali.meibo888.top/Article/details/gtklhfelsb.html

PHP:  json_decode($body, true);
来源：http://dali.nanxuanxn.top/Article/details/gtoqauoxuk.html

JS:   await resp.json()
来源：http://dali.tianlin.xyz/Article/details/gtqagihdlo.html

TS:   await resp.json()
来源：http://dali.yj20258888.top/Article/details/gtaqtcwofu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtomdxsqpy.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.aibaodan.cn/Article/details/gtgwtgjgex.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yanxiufei.cn/Article/details/gtzqubaxoh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.pycfn.com/Article/details/gtqeszlchf.html

[L07] 处理 HTTP 状态码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfdwttutr.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jianghu66.top/Article/details/gtymcftfpk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zycfv.cn/Article/details/gteheryrvx.html

JS:   resp.ok;  resp.status
来源：http://dali.cucudq.cn/Article/details/gtwvvdlkzv.html

TS:   resp.ok;  resp.status
来源：http://dali.bjfxy.top/Article/details/gtmwxeufkg.html

Java: resp.statusCode()
来源：http://dali.pengpengdd.cyou/Article/details/gtomdwhlgo.html

Go:   resp.StatusCode
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjsoleykg.html

Ruby: resp.code.to_i
来源：http://dali.smart0.xyz/Article/details/gtfvtzpsqm.html

C#:   (int)resp.StatusCode
来源：http://dali.wangshuangyany.cn/Article/details/gtukxdavtq.html

[L08] 并发请求多个地址
来源：http://dali.sxryk.cn/Article/details/gtgqstbrox.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.birdmap.top/Article/details/gtzwbggszx.html

PHP:  curl_multi_init() 系列
来源：http://dali.316326.xyz/Article/details/gtlsrauazg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuanzx.com/Article/details/gtcfqjepdp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guannengcc.top/Article/details/gtmuyxhlyj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cdnleiting.top/Article/details/gtgqlljokl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.snrcjt.cn/Article/details/gthczoaadd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ehwqpu.com/Article/details/gtltoaschw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.0kj1m.cn/Article/details/gtxpevonhk.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtfgaswltc.html

M. 命令行 / 进程 / 环境
来源：http://dali.quarkkingdee.top/Article/details/gtjfgukycp.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtpnewnkjp.html

[M01] 读取命令行参数
来源：http://dali.nanxinkj.top/Article/details/gtxbhuqzcr.html

Py:   sys.argv[1:]
来源：http://dali.pengpengdd.cyou/Article/details/gtnocmjkck.html

PHP:  $argv;  $argc;
来源：http://dali.jinqigfzy.top/Article/details/gtqullpvxp.html

JS:   process.argv.slice(2)
来源：http://dali.birdmap.top/Article/details/gttgxeymax.html

TS:   process.argv.slice(2)
来源：http://dali.gzhubu.top/Article/details/gtzxfgbtlx.html

Java: args 数组（main 方法参数）
来源：http://dali.nwbrower.top/Article/details/gtfaacdvlg.html

Go:   os.Args[1:]
来源：http://dali.xuanzx.com/Article/details/gtfsviaobi.html

Ruby: ARGV
来源：http://dali.bjfxy.top/Article/details/gtqxgmvsjy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xinyue.icu/Article/details/gtgrsosdwl.html

[M02] 读取环境变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttwivzqhr.html

Py:   os.environ.get("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtedljtkef.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.gzhubu.top/Article/details/gtlxogznny.html

JS:   process.env.HOME
来源：http://dali.fzhhl.top/Article/details/gtqtcjtdmo.html

TS:   process.env.HOME
来源：http://dali.pycfn.com/Article/details/gtcorsvljp.html

Java: System.getenv("HOME")
来源：http://dali.316326.xyz/Article/details/gtugmlicgs.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gtaytvvvhp.html

Ruby: ENV["HOME"]
来源：http://dali.zdqjudy.top/Article/details/gtolbdszbk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zdqjudy.top/Article/details/gtvxbulxot.html

[M03] 执行外部命令
来源：http://dali.tian-w.cn/Article/details/gtrumftftl.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jyoumei.cn/Article/details/gtjidpakou.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gogol.net.cn/Article/details/gtmzukicci.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.dashuyun.cn/Article/details/gtqdsphhcw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gogol.net.cn/Article/details/gtmmxfetsw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ydzc1.top/Article/details/gtbwhfhmig.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xinyue.icu/Article/details/gtwszesfns.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.dianchejie.cn/Article/details/gtprohdnrd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yuanzhike.top/Article/details/gtpfbflzmb.html

[M04] 获取当前工作目录
来源：http://dali.gaohongyu789.top/Article/details/gtsizkmlas.html

Py:   os.getcwd()
来源：http://dali.ehwqpu.com/Article/details/gtijgpvkcf.html

PHP:  getcwd();
来源：http://dali.jqgfzy.top/Article/details/gtzwmjigav.html

JS:   process.cwd()
来源：http://dali.gogol.net.cn/Article/details/gtilwswxwg.html

TS:   process.cwd()
来源：http://dali.nanxinkj.top/Article/details/gtosviqoei.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cucudq.cn/Article/details/gtbehbxrtc.html

Go:   os.Getwd()
来源：http://dali.shzxlz.cn/Article/details/gtcftqmtam.html

Ruby: Dir.pwd
来源：http://dali.ehwqpu.com/Article/details/gtdxgnvpxe.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jiagoushi.top/Article/details/gtxohfitmn.html

[M05] 设置退出码
来源：http://dali.shangyingyoupin.top/Article/details/gtjqhfiuuy.html

Py:   sys.exit(1)
来源：http://dali.yj20258888.top/Article/details/gtolibyatt.html

PHP:  exit(1);
来源：http://dali.yangfankeji.com/Article/details/gtamwbwydl.html

JS:   process.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gtkccfogjj.html

TS:   process.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gtewzizntb.html

Java: System.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtkakquisd.html

Go:   os.Exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gtsptyergk.html

Ruby: exit 1
来源：http://dali.guowangkeji.top/Article/details/gtynvyckjc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cucudq.cn/Article/details/gtdiwpeupe.html

[M06] 向标准错误输出
来源：http://dali.shangyingyoupin.top/Article/details/gtpkcmzjle.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shzxlz.cn/Article/details/gtkbqlhrmu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.aibaodan.cn/Article/details/gttwixosla.html

JS:   console.error("err")
来源：http://dali.yongpay.top/Article/details/gtvvcpcwsh.html

TS:   console.error("err")
来源：http://dali.hongshengwenyu.top/Article/details/gtjfrvocof.html

Java: System.err.println("err")
来源：http://dali.jqgufenzy.top/Article/details/gtlplxhtwh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xylfe.cn/Article/details/gtgpbygcvj.html

Ruby: warn "err"
来源：http://dali.xuetiantiany.cn/Article/details/gtgusxtjob.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gaohongyu789.top/Article/details/gtplnmjsav.html

[M07] 判断是否为主入口
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjjhkguaz.html

Py:   if __name__ == "__main__":
来源：http://dali.chenjidiqi.icu/Article/details/gtycemganw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.snrcjt.cn/Article/details/gtexkqaqxw.html

JS:   require.main === module
来源：http://dali.cdnleiting.top/Article/details/gtoanofdpd.html

TS:   require.main === module
来源：http://dali.xinyue.icu/Article/details/gthavkhucg.html

Java: public static void main(String[] args)
来源：http://dali.jianghu66.top/Article/details/gtmbxfglbp.html

Go:   func main()
来源：http://dali.zhengqikj.top/Article/details/gtoegreexv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xuetiantiany.cn/Article/details/gtdnwqaowf.html

C#:   static void Main(string[] args)
来源：http://dali.yj20258888.top/Article/details/gtpsdrerub.html

[M08] 获取系统与运行时信息
来源：http://dali.tanke756.top/Article/details/gtynzskola.html

Py:   platform.system();  platform.python_version()
来源：http://dali.wangshuangyany.cn/Article/details/gtkutgogao.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gzhubu.top/Article/details/gteuunsojc.html

JS:   process.platform;  process.version
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqcbwegrj.html

TS:   process.platform;  process.version
来源：http://dali.cashguo.top/Article/details/gtcozkxwrc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sweek.top/Article/details/gtszjsbhdy.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ivvv.top/Article/details/gtcvqmboex.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sufxvd.cn/Article/details/gtoilmleva.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ydzc1.top/Article/details/gtbjbkjofw.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtueifqnrj.html

N. 数据结构与算法
来源：http://dali.9152youxi.cn/Article/details/gtvvsbuqbz.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtyezikaql.html

[N01] 二分查找（有序数组）
来源：http://dali.wangshuangyany.cn/Article/details/gtmcouxvxd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.daria6918.cn/Article/details/gtqjlxechd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.birdmap.top/Article/details/gttiwcyahe.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258.top/Article/details/gtalmoowmn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guowangkeji.top/Article/details/gtmxbrtzqd.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtviwtptlq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtbpjmbnwl.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yvedp.cn/Article/details/gtzswsymsa.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.sweek.top/Article/details/gtkpxtqvgo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinqigufen.top/Article/details/gtogzrgpec.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yueranfly.top/Article/details/gtvjasfdyt.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsponoitx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.bjfxy.top/Article/details/gtptvpsxfn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cqqwz.cn/Article/details/gtnehdlbrb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.aizwys.cn/Article/details/gtleazgqja.html

Go:   slices.Sort(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtmkpbgpzv.html

Ruby: arr.sort
来源：http://dali.zhongyouzk.top/Article/details/gtypltlptz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yueranfly.top/Article/details/gtsetvwvrb.html

[N03] 快速排序（分治示例）
来源：http://dali.guannengcc.top/Article/details/gtqflpqrum.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.aibaodan.cn/Article/details/gtildnbdgb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cdnleiting.top/Article/details/gtckbvmykq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sysykeji.top/Article/details/gtxbozkgup.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guowangkeji.top/Article/details/gtbtkudujt.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ehwqpu.com/Article/details/gtldgrbqdr.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yangfankeji.com/Article/details/gtzvbkpghn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.vqdsnc.cn/Article/details/gtmdgrxcjd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.tanke756.top/Article/details/gtwkeawlak.html

[N04] 斐波那契数列
来源：http://dali.jqgfzy.top/Article/details/gtjzwruvss.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.sysykeji.top/Article/details/gtjmfecrfh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.aibaodan.cn/Article/details/gtifxzlvqh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gttyrmbqfu.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ybcxt.top/Article/details/gthfgpwdep.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shzxlz.cn/Article/details/gtqdbgetxk.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.tanke756.top/Article/details/gtikczsfuu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.kuanghao11.cn/Article/details/gtcvyxaktw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.dianchejie.cn/Article/details/gtviekrkkv.html

[N05] 最大公约数
来源：http://dali.sxryk.cn/Article/details/gttxxbffci.html

Py:   math.gcd(a, b)
来源：http://dali.svipenyu.cn/Article/details/gttsrncxjf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ehwqpu.com/Article/details/gtzhykpxss.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jqgfzy.top/Article/details/gtzaglfduh.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuetiantiany.cn/Article/details/gtyemnrmpw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shangyingyoupin.top/Article/details/gtzsxofyfm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zdqjudy.top/Article/details/gthftehqtn.html

Ruby: a.gcd(b)
来源：http://dali.quarkkingdee.top/Article/details/gtsesrwhpz.html


<!-- 参考信息 -->