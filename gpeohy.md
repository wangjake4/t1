代发 wailian999

TS:   d1.getTime() < d2.getTime()
来源：http://dali.nwbrower.top/Article/details/gtwrzvudil.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.chenlongwang.top/Article/details/gtfwdsrusa.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ppjwa.cn/Article/details/gthmdtjjkm.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zdqjudy.top/Article/details/gtxuyxcsrd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.kuanghao11.cn/Article/details/gtkmgmeyli.html

[J08] 提取年月日与星期
来源：http://dali.hammf.cn/Article/details/gtxxxmmasf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinghuilouyu.cn/Article/details/gtscyqusuo.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.andypj.xyz/Article/details/gtmrbdvrfb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.0kj1m.cn/Article/details/gttynjfubx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cucudq.cn/Article/details/gtqoqzdakm.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yanxiufei.cn/Article/details/gtgliyozfb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.redwolf501.top/Article/details/gtroxtlqyn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hnqzz.top/Article/details/gtnmujjpcq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.0kj1m.cn/Article/details/gtuaobormp.html

[J09] 时区处理
来源：http://dali.shzxlz.cn/Article/details/gtbecscxay.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shangyingyoupin.top/Article/details/gtxwvwakwe.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cdnleiting.top/Article/details/gtqvsmzalx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yonumen.top/Article/details/gtljnoijbb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgufenzy.top/Article/details/gtvtbvlbak.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yuanzhike.top/Article/details/gtdqnbhcxw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tian-w.cn/Article/details/gtazpahhkf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jlsjyb.cn/Article/details/gtidjvicrl.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenlongwang.top/Article/details/gtqhhqocqx.html

[J10] 取今天 / 本月第一天
来源：http://dali.nanxinkj.top/Article/details/gtucylmmdx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.daria6918.cn/Article/details/gtzawbjbcz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hysaishi.cn/Article/details/gtlrcumxdu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hfpthk.cn/Article/details/gtjrwqvjjt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xuanzx.com/Article/details/gtazkmdloh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hammf.cn/Article/details/gthckzsyia.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.mhx1999.top/Article/details/gtevtymhie.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhixingplan.top/Article/details/gturlednql.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.tanke756.top/Article/details/gtcvaudrhy.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gthhnjakxs.html

K. JSON 与序列化
来源：http://dali.xuetiantiany.cn/Article/details/gtlqsyhhgb.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwnjirfdu.html

[K01] 对象转 JSON 字符串
来源：http://dali.jyoumei.cn/Article/details/gtwtwvszro.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhiwuduotai.top/Article/details/gtszexzyiv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hfpthk.cn/Article/details/gtdndwaqic.html

JS:   JSON.stringify(obj)
来源：http://dali.0kj1m.cn/Article/details/gtpufyeexr.html

TS:   JSON.stringify(obj)
来源：http://dali.fengsongda.top/Article/details/gtchrjxiex.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.vqdsnc.cn/Article/details/gtvqwkzjsn.html

Go:   json.Marshal(obj)
来源：http://dali.zhixingplan.top/Article/details/gtbnymfxic.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.dianchejie.cn/Article/details/gtzplqjrjr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jiagoushi.top/Article/details/gtvxhgnptb.html

[K02] JSON 字符串转对象
来源：http://dali.sweek.top/Article/details/gtdsqmczbt.html

Py:   json.loads(s)
来源：http://dali.zycfv.cn/Article/details/gtgdmxfvby.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cucudq.cn/Article/details/gtkhthhlqg.html

JS:   JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gtvyipnlyu.html

TS:   JSON.parse(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnzezybgv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ydzc1.top/Article/details/gtbpvmvzhk.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xuanzx.com/Article/details/gtwpvfavww.html

Ruby: JSON.parse(s)
来源：http://dali.xinyue.icu/Article/details/gtdtgnnjey.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ydzc1.top/Article/details/gtpmvqxdzj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.daxiang520.top/Article/details/gtnkcdkdqm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.daxiang520.top/Article/details/gtzgdkwxwr.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yvedp.cn/Article/details/gtamluaoup.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ivvv.top/Article/details/gtznmssmsf.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gotoacloud.top/Article/details/gtmvbmkqeb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtwersjmcr.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.pengpengdd.cyou/Article/details/gtadwxrigg.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.c1oappe.top/Article/details/gtgmpimhuu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.wangdashe.top/Article/details/gtigrstddj.html

[K04] 读取 JSON 文件
来源：http://dali.jinqigufen.top/Article/details/gtqvhhwgju.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xylfe.cn/Article/details/gtochwhpwc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yuanzhike.top/Article/details/gthfayfnhu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tanke756.top/Article/details/gttjkpoglg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cashguo.top/Article/details/gtknxkmkqt.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.0kj1m.cn/Article/details/gtbmkjmhyl.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yj202588.top/Article/details/gtwiiyzrun.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hammf.cn/Article/details/gtiufovqmx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.0kj1m.cn/Article/details/gtksjhmkwt.html

[K05] 深拷贝对象
来源：http://dali.smart0.xyz/Article/details/gtblowihkp.html

Py:   copy.deepcopy(obj)
来源：http://dali.316326.xyz/Article/details/gtndbvcffp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shzxlz.cn/Article/details/gtrtmiirrb.html

JS:   structuredClone(obj)
来源：http://dali.xylfe.cn/Article/details/gthzpnzcie.html

TS:   structuredClone(obj)
来源：http://dali.jyoumei.cn/Article/details/gtxvuwxoxq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shzxlz.cn/Article/details/gtuszeohlw.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xziqi.cn/Article/details/gtgfvrcube.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtunzqubid.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ppjwa.cn/Article/details/gtllyrcxsn.html

[K06] 解析 URL 查询串
来源：http://dali.gogol.net.cn/Article/details/gtrrmuwyzd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sysykeji.top/Article/details/gtmuwqcwvn.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.316326.xyz/Article/details/gtltfglqrw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gtphrdtqcc.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sysykeji.top/Article/details/gtomltuiby.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.chenjidiqi.icu/Article/details/gtggijtlme.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.svipenyu.cn/Article/details/gtfctvioah.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.smart0.xyz/Article/details/gtavzbickh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gtrvigfsrt.html

[K07] 进制转换
来源：http://dali.meibo888.top/Article/details/gtfwsmcdrh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gtatrtqyvu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yj20258.top/Article/details/gttppqsyos.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gtxrddxxdl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yonumen.top/Article/details/gtqcilrdmk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gtnkpruvbf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jqgfzy.top/Article/details/gtwdqvvdal.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.wangdashe.top/Article/details/gtbhugckmd.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gtqadsxbii.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jianghu66.top/Article/details/gtqnmxhyib.html

Py:   pickle.dumps(obj)
来源：http://dali.smart0.xyz/Article/details/gtkilgiplb.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvwwqvwlh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hammf.cn/Article/details/gtwhqsqhrv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.fengsongda.top/Article/details/gtzbmxkogo.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ivvv.top/Article/details/gtrztqawal.html

Go:   encoding/gob
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtegxkdhev.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtgusnwmab.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.fengsongda.top/Article/details/gtxdchpdld.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtdfovszey.html

L. 网络请求
来源：http://dali.xinyue.icu/Article/details/gtqgaejsjf.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtzlscmbam.html

[L01] 发送 GET 请求
来源：http://dali.redwolf501.top/Article/details/gtrrxkhgmq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.iojbl.cn/Article/details/gtjrotwnaz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ydzc1.top/Article/details/gthblrtjrm.html

JS:   await fetch(url)
来源：http://dali.hnxiangtu.top/Article/details/gtuubauxhc.html

TS:   await fetch(url)
来源：http://dali.gotoacloud.top/Article/details/gtwtspbcit.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xuanzx.com/Article/details/gtsaxhkayh.html

Go:   resp, err := http.Get(url)
来源：http://dali.bjfxy.top/Article/details/gtfommfrdo.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwsxmcxjw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.aizwys.cn/Article/details/gtykapggjc.html

[L02] 发送 POST JSON
来源：http://dali.jyoumei.cn/Article/details/gtsxynlaah.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.redwolf501.top/Article/details/gtyczacwdn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtblbyuuwm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yonumen.top/Article/details/gtwebosfnn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj20258.top/Article/details/gtrrsobavy.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hfpthk.cn/Article/details/gtsxmxlbms.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hnxiangtu.top/Article/details/gtxcxpeqmf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zycfv.cn/Article/details/gtatagzqpd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cdnleiting.top/Article/details/gtedzewjgb.html

[L03] 设置自定义请求头
来源：http://dali.tanke756.top/Article/details/gtfmiikgei.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.smart0.xyz/Article/details/gtyemwaxes.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.316326.xyz/Article/details/gtmjtiniyj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guannengcc.top/Article/details/gtpsihnsdw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdnluxlun.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.chenzaomai.com/Article/details/gtdjkhnuxf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zycfv.cn/Article/details/gtwvrptomh.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jqgfzy.top/Article/details/gtrjapjyes.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.guannengcc.top/Article/details/gtwsydafbb.html

[L04] 设置超时
来源：http://dali.xuanzx.com/Article/details/gtuijpfwoe.html

Py:   requests.get(url, timeout=5)
来源：http://dali.chenjidiqi.icu/Article/details/gtitlsgopz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.nanxuanxn.top/Article/details/gtwrnejhyf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yangfankeji.com/Article/details/gtzejzxfkv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yueranfly.top/Article/details/gtnvdycjhy.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yj20258888.top/Article/details/gtdfykdwzj.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.316326.xyz/Article/details/gthnphsqor.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sysykeji.top/Article/details/gtextqqavf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yuxming.cn/Article/details/gtiuvghfrk.html

[L05] 上传文件（multipart）
来源：http://dali.shuidangran.top/Article/details/gtiatmsckv.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.bjfxy.top/Article/details/gtlkbxkcva.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yvedp.cn/Article/details/gtmoqvtpbq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.andypj.xyz/Article/details/gtqclapmdn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gzhubu.top/Article/details/gtfgtjstzw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shanyushiyangkeji.top/Article/details/gtukqvokrj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jyoumei.cn/Article/details/gtxbfwbbkv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hysaishi.cn/Article/details/gtcytjhemg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.daria6918.cn/Article/details/gtaqsuhyyh.html

[L06] 解析响应为 JSON
来源：http://dali.xylfe.cn/Article/details/gtotlwnevm.html

Py:   resp.json()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtttqytbut.html

PHP:  json_decode($body, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxcppisru.html

JS:   await resp.json()
来源：http://dali.yj20258.top/Article/details/gtqjbjxgvj.html

TS:   await resp.json()
来源：http://dali.hywenlv.cn/Article/details/gtsddoltem.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yongpay.top/Article/details/gtlivolbpp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhengqikj.top/Article/details/gtozmaopks.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hysaishi.cn/Article/details/gtdytvrxyl.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yuanzhike.top/Article/details/gtmcfycxzm.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjlmanedb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.dianchejie.cn/Article/details/gtlkdmsasg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.aibaodan.cn/Article/details/gtyqnbfcot.html

JS:   resp.ok;  resp.status
来源：http://dali.ybcxt.top/Article/details/gtifazbjip.html

TS:   resp.ok;  resp.status
来源：http://dali.wangshuangyany.cn/Article/details/gtxgwyqden.html

Java: resp.statusCode()
来源：http://dali.jlsjyb.cn/Article/details/gtbgtqpsnh.html

Go:   resp.StatusCode
来源：http://dali.birdmap.top/Article/details/gtzcedxcgm.html

Ruby: resp.code.to_i
来源：http://dali.gotoacloud.top/Article/details/gtvtheipgk.html

C#:   (int)resp.StatusCode
来源：http://dali.fzhhl.top/Article/details/gtpqngfqze.html

[L08] 并发请求多个地址
来源：http://dali.vqdsnc.cn/Article/details/gttfginnej.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.meibo888.top/Article/details/gtfqsoploz.html

PHP:  curl_multi_init() 系列
来源：http://dali.guowangkeji.top/Article/details/gtpytiedtd.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dashuyun.cn/Article/details/gtfeqwsurg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj202588.top/Article/details/gtrkndcwia.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yuxming.cn/Article/details/gtkhbsuufk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yongpay.top/Article/details/gtscdxcjhd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xuetiantiany.cn/Article/details/gtdtxcnfhr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.nanxinkj.top/Article/details/gtddgjkoro.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtwlxkbdop.html

M. 命令行 / 进程 / 环境
来源：http://dali.cqqwz.cn/Article/details/gtgqozolhl.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtvxceywuc.html

[M01] 读取命令行参数
来源：http://dali.hysaishi.cn/Article/details/gtgtwjymhm.html

Py:   sys.argv[1:]
来源：http://dali.jianghu66.top/Article/details/gtlcdfulcq.html

PHP:  $argv;  $argc;
来源：http://dali.yj202588.top/Article/details/gtlujormxr.html

JS:   process.argv.slice(2)
来源：http://dali.tanke756.top/Article/details/gtlkfroetb.html

TS:   process.argv.slice(2)
来源：http://dali.ybcxt.top/Article/details/gtpvvauvsp.html

Java: args 数组（main 方法参数）
来源：http://dali.hysaishi.cn/Article/details/gtngrlzgkw.html

Go:   os.Args[1:]
来源：http://dali.mhx1999.top/Article/details/gtvcegncpi.html

Ruby: ARGV
来源：http://dali.jinghuilouyu.cn/Article/details/gtvzkhnnfo.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ppjwa.cn/Article/details/gthjnjgdav.html

[M02] 读取环境变量
来源：http://dali.pycfn.com/Article/details/gturpsuqvy.html

Py:   os.environ.get("HOME")
来源：http://dali.smart0.xyz/Article/details/gtutxlmjrl.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sufxvd.cn/Article/details/gtlpueycsg.html

JS:   process.env.HOME
来源：http://dali.tianlin.xyz/Article/details/gtozkrzsbq.html

TS:   process.env.HOME
来源：http://dali.zhixingplan.top/Article/details/gtkrzdudlb.html

Java: System.getenv("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gtmtehlupv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gtnpskqntx.html

Ruby: ENV["HOME"]
来源：http://dali.shzxlz.cn/Article/details/gtarsopvxp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yvedp.cn/Article/details/gtrulgdkdg.html

[M03] 执行外部命令
来源：http://dali.nanxinkj.top/Article/details/gtnmfqiosk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hysaishi.cn/Article/details/gtbyekbjeg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jianghu66.top/Article/details/gtiahuqnll.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.feifeiyinyue.top/Article/details/gtjipbslds.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gtzbmqzsey.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zycfv.cn/Article/details/gtlmlzqxnh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.andypj.xyz/Article/details/gtiandkpak.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yvedp.cn/Article/details/gtibtzjvzj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hammf.cn/Article/details/gtdhkxnugk.html

[M04] 获取当前工作目录
来源：http://dali.shuidangran.top/Article/details/gtmczqvqad.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gtxhdmvext.html

PHP:  getcwd();
来源：http://dali.aibaodan.cn/Article/details/gthhyiiasv.html

JS:   process.cwd()
来源：http://dali.sufxvd.cn/Article/details/gtvfvfnoae.html

TS:   process.cwd()
来源：http://dali.snrcjt.cn/Article/details/gtqdvfylfa.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hywenlv.cn/Article/details/gtgqdaqoep.html

Go:   os.Getwd()
来源：http://dali.wangdashe.top/Article/details/gtlhpqmakl.html

Ruby: Dir.pwd
来源：http://dali.bjfxy.top/Article/details/gtdpkimzra.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.c1oappe.top/Article/details/gtzpnejsgc.html

[M05] 设置退出码
来源：http://dali.xylfe.cn/Article/details/gtuyqhfrdt.html

Py:   sys.exit(1)
来源：http://dali.hammf.cn/Article/details/gtzcdhmzig.html

PHP:  exit(1);
来源：http://dali.yonumen.top/Article/details/gtafydplpl.html

JS:   process.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gtrmvrqexs.html

TS:   process.exit(1)
来源：http://dali.cucudq.cn/Article/details/gtyxkudbus.html

Java: System.exit(1)
来源：http://dali.smart0.xyz/Article/details/gtmurbiiyy.html

Go:   os.Exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gtvepqhkof.html

Ruby: exit 1
来源：http://dali.zhongyouzk.top/Article/details/gtxdoxilbg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yvedp.cn/Article/details/gthshihepc.html

[M06] 向标准错误输出
来源：http://dali.havefunace.top/Article/details/gtsnrjixte.html

Py:   print("err", file=sys.stderr)
来源：http://dali.fengsongda.top/Article/details/gtpgaezqxo.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.havefunace.top/Article/details/gtvzxdkzvt.html

JS:   console.error("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtbcgoozop.html

TS:   console.error("err")
来源：http://dali.guowangkeji.top/Article/details/gtsntjwaxu.html

Java: System.err.println("err")
来源：http://dali.hnxiangtu.top/Article/details/gtdqlyuivz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jyoumei.cn/Article/details/gtodkmhedr.html

Ruby: warn "err"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcfpaoajo.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nwbrower.top/Article/details/gtkprbzpve.html

[M07] 判断是否为主入口
来源：http://dali.yj20258.top/Article/details/gtnuyvfemx.html

Py:   if __name__ == "__main__":
来源：http://dali.ydzc1.top/Article/details/gteztthoqh.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gotoacloud.top/Article/details/gtdlypfjyc.html

JS:   require.main === module
来源：http://dali.chenlongwang.top/Article/details/gtufhuqabg.html

TS:   require.main === module
来源：http://dali.nanxuanxn.top/Article/details/gtaaopszoq.html

Java: public static void main(String[] args)
来源：http://dali.cheryme.top/Article/details/gtnyyfetcd.html

Go:   func main()
来源：http://dali.gzhubu.top/Article/details/gtdbzkbhqe.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.iojbl.cn/Article/details/gtysrnotwc.html

C#:   static void Main(string[] args)
来源：http://dali.zycfv.cn/Article/details/gtcfuqbmag.html

[M08] 获取系统与运行时信息
来源：http://dali.jyoumei.cn/Article/details/gtrzhspijm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.snrcjt.cn/Article/details/gttaehwrab.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlfsivnnp.html

JS:   process.platform;  process.version
来源：http://dali.dashuyun.cn/Article/details/gtvrueidmc.html

TS:   process.platform;  process.version
来源：http://dali.0kj1m.cn/Article/details/gtvabtffxh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jlsjyb.cn/Article/details/gtlmhzidpf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.pycfn.com/Article/details/gtbqerjxrl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gaohongyu789.top/Article/details/gthfoxnutx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hammf.cn/Article/details/gtxrohpndx.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwhvfxcxm.html

N. 数据结构与算法
来源：http://dali.daxiang520.top/Article/details/gtunbugswh.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtsehobgfc.html

[N01] 二分查找（有序数组）
来源：http://dali.yvedp.cn/Article/details/gttqzaggsb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtsjcxevga.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ybcxt.top/Article/details/gtmuqdskqy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jyoumei.cn/Article/details/gtgqsktqxv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yanxiufei.cn/Article/details/gthskuxfjj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkxsbfcjf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cheryme.top/Article/details/gtejqaoqvp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.dashuyun.cn/Article/details/gtugqfmjya.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtmwdjvfww.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hongshengwenyu.top/Article/details/gthxmqogcy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ppjwa.cn/Article/details/gtozubqcmr.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yuxming.cn/Article/details/gtbvjpxmjb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.bjfxy.top/Article/details/gtvsmoojkt.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.316326.xyz/Article/details/gtkvnbkote.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.gzhubu.top/Article/details/gtjzslqtwk.html

Go:   slices.Sort(arr)
来源：http://dali.aibaodan.cn/Article/details/gtmytfwkfw.html

Ruby: arr.sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmncmgmhz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hongshengwenyu.top/Article/details/gtddyfhyxa.html

[N03] 快速排序（分治示例）
来源：http://dali.316326.xyz/Article/details/gtiaigdcmy.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.guannengcc.top/Article/details/gtkajbzykd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.haohaochexian.top/Article/details/gtkvktyjrh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yongpay.top/Article/details/gtevupnank.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guowangkeji.top/Article/details/gttyrjoxzn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.daxiang520.top/Article/details/gtzrbbrcws.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sufxvd.cn/Article/details/gtevbxpumb.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinqigfzy.top/Article/details/gtoysnomnv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sweek.top/Article/details/gtqlwvcpfd.html

[N04] 斐波那契数列
来源：http://dali.tianlin.xyz/Article/details/gtoipoguim.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.sysykeji.top/Article/details/gteallszpa.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.nwbrower.top/Article/details/gtfxdjcncd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cheryme.top/Article/details/gtujwtrggd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gtqpglhzcd.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.kuanghao11.cn/Article/details/gtylcmqpus.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.aizwys.cn/Article/details/gttxcpltmq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.meibo888.top/Article/details/gthktlxywg.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.andypj.xyz/Article/details/gtxcbfmxcy.html

[N05] 最大公约数
来源：http://dali.redwolf501.top/Article/details/gtnbbxlhix.html

Py:   math.gcd(a, b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthvwuylia.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.havefunace.top/Article/details/gtefkcvvlq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhengqikj.top/Article/details/gtxagmblvr.html


<!-- 参考信息 -->