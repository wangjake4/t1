代发 wailian999

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhoulong.xyz/Article/details/gt2jqwxtzde.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xuanzx.com/Article/details/gt2vneugbvh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jlsjyb.cn/Article/details/gt2bprpqjrr.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zdqjudy.top/Article/details/gt2tjpcmihv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.sweek.top/Article/details/gt2wcgpztdj.html

[J08] 提取年月日与星期
来源：http://dali.chenzaomai.com/Article/details/gt2buwkhzyn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yuanzhike.top/Article/details/gt2jwhwrzyc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yueranfly.top/Article/details/gt2nprnfsiu.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.tianlin.xyz/Article/details/gt2tjdjbuye.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ydzc1.top/Article/details/gt2xlemumpn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rnwwkryb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hnxiangtu.top/Article/details/gt2pyghopwj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.nanxinkj.top/Article/details/gt2ibgpafvm.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sxryk.cn/Article/details/gt2jcaucawy.html

[J09] 时区处理
来源：http://dali.316326.xyz/Article/details/gt2bckamzyg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wbahmiyn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yueranfly.top/Article/details/gt2nzmqtxze.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yongpay.top/Article/details/gt2awwljdou.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuanzx.com/Article/details/gt2gkflayce.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.fengsongda.top/Article/details/gt2siqwrogl.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinqigfzy.top/Article/details/gt2gbdnptzb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.svipenyu.cn/Article/details/gt2ikqiedef.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.tanke756.top/Article/details/gt2saasrrwf.html

[J10] 取今天 / 本月第一天
来源：http://dali.iojbl.cn/Article/details/gt2ckhqtusu.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2snkknvwr.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.iojbl.cn/Article/details/gt2mrueyrvc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.c1oappe.top/Article/details/gt2cuqwazos.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shuidangran.top/Article/details/gt2wgfanwgy.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.tian-w.cn/Article/details/gt2oafspgvq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xuanzx.com/Article/details/gt2ecbzllfk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yueranfly.top/Article/details/gt2sillfrcl.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhoulong.xyz/Article/details/gt2fppleqvs.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2mbojvlzh.html

K. JSON 与序列化
来源：http://dali.c1oappe.top/Article/details/gt2uebadeoy.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2oukwoxxl.html

[K01] 对象转 JSON 字符串
来源：http://dali.fzhhl.top/Article/details/gt2tazupgnn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.kuanghao11.cn/Article/details/gt2ujjmfuzi.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.sysykeji.top/Article/details/gt2euqihedr.html

JS:   JSON.stringify(obj)
来源：http://dali.shuidangran.top/Article/details/gt2drfhhggy.html

TS:   JSON.stringify(obj)
来源：http://dali.nwbrower.top/Article/details/gt2rjaulvco.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yangfankeji.com/Article/details/gt2sjewqqbq.html

Go:   json.Marshal(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2kwwzbjkw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yangfankeji.com/Article/details/gt2hgypxxhs.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jujqcunf.html

[K02] JSON 字符串转对象
来源：http://dali.xuetiantiany.cn/Article/details/gt2fhsuvpoq.html

Py:   json.loads(s)
来源：http://dali.zycfv.cn/Article/details/gt2dguefykh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.aizwys.cn/Article/details/gt2yufplyce.html

JS:   JSON.parse(s)
来源：http://dali.yvedp.cn/Article/details/gt2xilgpjim.html

TS:   JSON.parse(s)
来源：http://dali.gzhubu.top/Article/details/gt2syhzpdjf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.daria6918.cn/Article/details/gt2eaiqsucs.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yj20258888.top/Article/details/gt2haoffrex.html

Ruby: JSON.parse(s)
来源：http://dali.sufxvd.cn/Article/details/gt2wilkmuij.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.daxiang520.top/Article/details/gt2pxgwcqvl.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sxryk.cn/Article/details/gt2zyqhwqlu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yanxiufei.cn/Article/details/gt2mlcwehjh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sxryk.cn/Article/details/gt2zgiygcpq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2tpcfunya.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cheryme.top/Article/details/gt2vrdfpvmn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iimvjgme.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ehdnmtcc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ivvv.top/Article/details/gt2hnrblnkz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.andypj.xyz/Article/details/gt2vmijudzk.html

[K04] 读取 JSON 文件
来源：http://dali.cashguo.top/Article/details/gt2dggsqylk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hnqzz.top/Article/details/gt2lldutfvt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sysykeji.top/Article/details/gt2qrpcgfer.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.kuanghao11.cn/Article/details/gt2cxjppgik.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangdashe.top/Article/details/gt2feihofln.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hnqzz.top/Article/details/gt2tgjkujna.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjzbrkp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xylfe.cn/Article/details/gt2heehasub.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.fengsongda.top/Article/details/gt2dzxqrtvv.html

[K05] 深拷贝对象
来源：http://dali.yj20258888.top/Article/details/gt2pzlmajfb.html

Py:   copy.deepcopy(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2mvnhsxbs.html

PHP:  unserialize(serialize($obj));
来源：http://dali.redwolf501.top/Article/details/gt2rcjtwgev.html

JS:   structuredClone(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qcjdiapi.html

TS:   structuredClone(obj)
来源：http://dali.yj20258.top/Article/details/gt2lpjeefym.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cashguo.top/Article/details/gt2axrwgpys.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.c1oappe.top/Article/details/gt2dqgdzczn.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gotoacloud.top/Article/details/gt2iydtiwng.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sufxvd.cn/Article/details/gt2zrqqdciz.html

[K06] 解析 URL 查询串
来源：http://dali.wangshuangyany.cn/Article/details/gt2edbgfmbw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hongshengwenyu.top/Article/details/gt2jaxhoabl.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj20258.top/Article/details/gt2ocwiogid.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuxming.cn/Article/details/gt2wfsivddk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cashguo.top/Article/details/gt2lvoggtrd.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vjjwaxog.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gt2dyehsxkq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.svipenyu.cn/Article/details/gt2meeowbni.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yvedp.cn/Article/details/gt2dttveajv.html

[K07] 进制转换
来源：http://dali.hywenlv.cn/Article/details/gt2nhbtlsan.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2emxrkcfb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.dianchejie.cn/Article/details/gt2bvgaouqt.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gt2epyakrgg.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gt2ailckpyc.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hammf.cn/Article/details/gt2spdgdorh.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shuidangran.top/Article/details/gt2ukahegvq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yanxiufei.cn/Article/details/gt2vekgzapk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gt2aoxpnouw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.redwolf501.top/Article/details/gt2mpoignyo.html

Py:   pickle.dumps(obj)
来源：http://dali.sxryk.cn/Article/details/gt2qgwciyln.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.tian-w.cn/Article/details/gt2vzhowtqx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yuanzhike.top/Article/details/gt2fawrmvjg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.snrcjt.cn/Article/details/gt2evvpwerv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.daxiang520.top/Article/details/gt2onvixiwu.html

Go:   encoding/gob
来源：http://dali.iojbl.cn/Article/details/gt2pbzcawmy.html

Ruby: Marshal.dump(obj)
来源：http://dali.hnqzz.top/Article/details/gt2vteafwyo.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.wangdashe.top/Article/details/gt2nrpplsjp.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2tyoecadz.html

L. 网络请求
来源：http://dali.jyoumei.cn/Article/details/gt2hkurupjg.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2lgjxddzg.html

[L01] 发送 GET 请求
来源：http://dali.havefunace.top/Article/details/gt2nudvjhul.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xylfe.cn/Article/details/gt2hzyubccd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.birdmap.top/Article/details/gt2ifcmqjni.html

JS:   await fetch(url)
来源：http://dali.zhiwuduotai.top/Article/details/gt2gcmfhyld.html

TS:   await fetch(url)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vqxmzsvi.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shzxlz.cn/Article/details/gt2polsorqz.html

Go:   resp, err := http.Get(url)
来源：http://dali.nanxinkj.top/Article/details/gt2dtskmvch.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cashguo.top/Article/details/gt2rnzetwvw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yj202588.top/Article/details/gt2bvfixttk.html

[L02] 发送 POST JSON
来源：http://dali.sweek.top/Article/details/gt2hisisgnd.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenzaomai.com/Article/details/gt2tkvsjmko.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.haohaochexian.top/Article/details/gt2ehzjybha.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pengpengdd.cyou/Article/details/gt2dzwnjeua.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nwbrower.top/Article/details/gt2crapcrqi.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.9152youxi.cn/Article/details/gt2lvjjycym.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cucudq.cn/Article/details/gt2gayqjsxo.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yongpay.top/Article/details/gt2goacasxc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2yqzmcdjy.html

[L03] 设置自定义请求头
来源：http://dali.redwolf501.top/Article/details/gt2sntinmvr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jqgufenzy.top/Article/details/gt2xgfhjddh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ydzc1.top/Article/details/gt2yzagchrh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.svipenyu.cn/Article/details/gt2blgehfpz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigfzy.top/Article/details/gt2xzmsnapx.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.aizwys.cn/Article/details/gt2euuyjkmd.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.nanxinkj.top/Article/details/gt2blzczydp.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.havefunace.top/Article/details/gt2dpsofkdv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinqigufen.top/Article/details/gt2auvnqjbu.html

[L04] 设置超时
来源：http://dali.jinqigufen.top/Article/details/gt2ubkuabrc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zaktduey.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uomptcbk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ivvv.top/Article/details/gt2vjypkxwy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ppjwa.cn/Article/details/gt2zmtpacse.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lbyyudgm.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fxnedgtq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qzvjcnwc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yongpay.top/Article/details/gt2tdwcyewj.html

[L05] 上传文件（multipart）
来源：http://dali.yj20258888.top/Article/details/gt2qgomrqur.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hongshengwenyu.top/Article/details/gt2ogrvdpql.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sxryk.cn/Article/details/gt2dcbwbycm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258888.top/Article/details/gt2fqdcuccx.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cashguo.top/Article/details/gt2vfvbxoen.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cashguo.top/Article/details/gt2wghcwupb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.fzhhl.top/Article/details/gt2wdwqwrxc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yj202588.top/Article/details/gt2vjwuvwci.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.316326.xyz/Article/details/gt2sbvvtvbi.html

[L06] 解析响应为 JSON
来源：http://dali.redwolf501.top/Article/details/gt2gwxydiyw.html

Py:   resp.json()
来源：http://dali.fengsongda.top/Article/details/gt2xrwtjnvq.html

PHP:  json_decode($body, true);
来源：http://dali.smart0.xyz/Article/details/gt2tagcprxg.html

JS:   await resp.json()
来源：http://dali.sweek.top/Article/details/gt2issrryss.html

TS:   await resp.json()
来源：http://dali.guannengcc.top/Article/details/gt2mcvsttlm.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cdnleiting.top/Article/details/gt2esznzeqm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ybcxt.top/Article/details/gt2urdxbjim.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yvedp.cn/Article/details/gt2kizhzync.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jqgfzy.top/Article/details/gt2aosvqjqb.html

[L07] 处理 HTTP 状态码
来源：http://dali.daria6918.cn/Article/details/gt2ieowqghr.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.daria6918.cn/Article/details/gt2rvtphndr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ppjwa.cn/Article/details/gt2ulfojmmp.html

JS:   resp.ok;  resp.status
来源：http://dali.gogol.net.cn/Article/details/gt2zzvqzvue.html

TS:   resp.ok;  resp.status
来源：http://dali.yangfankeji.com/Article/details/gt2obhtgbji.html

Java: resp.statusCode()
来源：http://dali.cdnleiting.top/Article/details/gt2qgllagax.html

Go:   resp.StatusCode
来源：http://dali.cheryme.top/Article/details/gt2kgrirsyu.html

Ruby: resp.code.to_i
来源：http://dali.gaohongyu789.top/Article/details/gt2ycibpyvl.html

C#:   (int)resp.StatusCode
来源：http://dali.hywenlv.cn/Article/details/gt2sdfjbnec.html

[L08] 并发请求多个地址
来源：http://dali.xuetiantiany.cn/Article/details/gt2prmenidq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.kuanghao11.cn/Article/details/gt2yqeezioh.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhoulong.xyz/Article/details/gt2iqswpbej.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jlsjyb.cn/Article/details/gt2mqviujbu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hammf.cn/Article/details/gt2qkxfzplb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.wangshuangyany.cn/Article/details/gt2zoaqyevs.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.chenlongwang.top/Article/details/gt2ajhwqnst.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.kuanghao11.cn/Article/details/gt2xgcmwoul.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hywenlv.cn/Article/details/gt2spaemukd.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2ftpvkmyh.html

M. 命令行 / 进程 / 环境
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ubprxymz.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2ocxajfal.html

[M01] 读取命令行参数
来源：http://dali.sysykeji.top/Article/details/gt2jxrjvgxj.html

Py:   sys.argv[1:]
来源：http://dali.chenjidiqi.icu/Article/details/gt2iojtbjrc.html

PHP:  $argv;  $argc;
来源：http://dali.vqdsnc.cn/Article/details/gt2rvdorugo.html

JS:   process.argv.slice(2)
来源：http://dali.gaohongyu789.top/Article/details/gt2vickqqqp.html

TS:   process.argv.slice(2)
来源：http://dali.cashguo.top/Article/details/gt2dwumqjca.html

Java: args 数组（main 方法参数）
来源：http://dali.kuanghao11.cn/Article/details/gt2limotisy.html

Go:   os.Args[1:]
来源：http://dali.guannengcc.top/Article/details/gt2mphgllwf.html

Ruby: ARGV
来源：http://dali.chenlongwang.top/Article/details/gt2yiwdbkka.html

C#:   args 数组（Main 方法参数）
来源：http://dali.mhx1999.top/Article/details/gt2qybjrgyf.html

[M02] 读取环境变量
来源：http://dali.hongshengwenyu.top/Article/details/gt2kwnvgqtc.html

Py:   os.environ.get("HOME")
来源：http://dali.cqqwz.cn/Article/details/gt2vobsweyh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.snrcjt.cn/Article/details/gt2mkfbzqkh.html

JS:   process.env.HOME
来源：http://dali.yangfankeji.com/Article/details/gt2pebvkwnx.html

TS:   process.env.HOME
来源：http://dali.gzhubu.top/Article/details/gt2ulmasyfw.html

Java: System.getenv("HOME")
来源：http://dali.zhixingplan.top/Article/details/gt2ctouvduc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.smart0.xyz/Article/details/gt2ayuylkgi.html

Ruby: ENV["HOME"]
来源：http://dali.hammf.cn/Article/details/gt2ivpcrvoh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.0kj1m.cn/Article/details/gt2llsuadvw.html

[M03] 执行外部命令
来源：http://dali.sxryk.cn/Article/details/gt2yjhpgicv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yj20258.top/Article/details/gt2lojstley.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.daxiang520.top/Article/details/gt2giocpqle.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.daxiang520.top/Article/details/gt2izsortwa.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shzxlz.cn/Article/details/gt2dxkcqvxq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hnqzz.top/Article/details/gt2mpfsgsmf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nwbrower.top/Article/details/gt2fpdqjjsi.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.nanxinkj.top/Article/details/gt2jrmdsyqr.html

C#:   Process.Start("ls", "-l");
来源：http://dali.tanke756.top/Article/details/gt2plkctilj.html

[M04] 获取当前工作目录
来源：http://dali.yueranfly.top/Article/details/gt2wegkbnyd.html

Py:   os.getcwd()
来源：http://dali.chenjidiqi.icu/Article/details/gt2qkzpjrcp.html

PHP:  getcwd();
来源：http://dali.ppjwa.cn/Article/details/gt2bdokvlpc.html

JS:   process.cwd()
来源：http://dali.shangyingyoupin.top/Article/details/gt2xyiqhyym.html

TS:   process.cwd()
来源：http://dali.yangfankeji.com/Article/details/gt2deraciri.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bwkwyvdg.html

Go:   os.Getwd()
来源：http://dali.sweek.top/Article/details/gt2wuudwvhk.html

Ruby: Dir.pwd
来源：http://dali.sysykeji.top/Article/details/gt2kjmhpyql.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.guannengcc.top/Article/details/gt2lylaxscm.html

[M05] 设置退出码
来源：http://dali.guannengcc.top/Article/details/gt2xrqfrvrv.html

Py:   sys.exit(1)
来源：http://dali.sysykeji.top/Article/details/gt2ytgpyfux.html

PHP:  exit(1);
来源：http://dali.yueranfly.top/Article/details/gt2zzjtjlxk.html

JS:   process.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gt2lcuicelr.html

TS:   process.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gt2bnqckpyq.html

Java: System.exit(1)
来源：http://dali.iojbl.cn/Article/details/gt2cypxznll.html

Go:   os.Exit(1)
来源：http://dali.hysaishi.cn/Article/details/gt2nhlqgfdm.html

Ruby: exit 1
来源：http://dali.gaohongyu789.top/Article/details/gt2vmzdyczc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.quarkkingdee.top/Article/details/gt2ckbgqrrp.html

[M06] 向标准错误输出
来源：http://dali.haohaochexian.top/Article/details/gt2chyphwws.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xylfe.cn/Article/details/gt2tcbawumx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qqjvrfee.html

JS:   console.error("err")
来源：http://dali.sufxvd.cn/Article/details/gt2kdeahjtr.html

TS:   console.error("err")
来源：http://dali.c1oappe.top/Article/details/gt2ddmyibmq.html

Java: System.err.println("err")
来源：http://dali.ppjwa.cn/Article/details/gt2ommpzavo.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.vqdsnc.cn/Article/details/gt2prvlbane.html

Ruby: warn "err"
来源：http://dali.svipenyu.cn/Article/details/gt2umawynnh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.guowangkeji.top/Article/details/gt2jftbvalm.html

[M07] 判断是否为主入口
来源：http://dali.feifeiyinyue.top/Article/details/gt2rajxllbn.html

Py:   if __name__ == "__main__":
来源：http://dali.fengsongda.top/Article/details/gt2nwpxfywi.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.bjfxy.top/Article/details/gt2cgkedevw.html

JS:   require.main === module
来源：http://dali.c1oappe.top/Article/details/gt2sgtrlebl.html

TS:   require.main === module
来源：http://dali.jiagoushi.top/Article/details/gt2qvzesbbw.html

Java: public static void main(String[] args)
来源：http://dali.yj20258888.top/Article/details/gt2fjgclqfq.html

Go:   func main()
来源：http://dali.birdmap.top/Article/details/gt2nnrtllqf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yuxming.cn/Article/details/gt2pjukvfzl.html

C#:   static void Main(string[] args)
来源：http://dali.gotoacloud.top/Article/details/gt2blwhognf.html

[M08] 获取系统与运行时信息
来源：http://dali.sxryk.cn/Article/details/gt2prhsxceg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hywenlv.cn/Article/details/gt2jhcfnnbx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2vqpaijpf.html

JS:   process.platform;  process.version
来源：http://dali.pengpengdd.cyou/Article/details/gt2oxrcgcqe.html

TS:   process.platform;  process.version
来源：http://dali.shangyingyoupin.top/Article/details/gt2khboeiuk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.chenjidiqi.icu/Article/details/gt2jwvdrhyf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.meibo888.top/Article/details/gt2hswajuiv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hfpthk.cn/Article/details/gt2yezsynng.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fyvbtpvn.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2kfaizlpp.html

N. 数据结构与算法
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pqombksg.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2ysbizsda.html

[N01] 二分查找（有序数组）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ujbvvwpj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.iojbl.cn/Article/details/gt2fmjsxuqr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sysykeji.top/Article/details/gt2nwbqtfop.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.bjfxy.top/Article/details/gt2finlobmp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenzaomai.com/Article/details/gt2vmgbofja.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gt2pudufcam.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gt2ajeqvyuv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zdqjudy.top/Article/details/gt2uwqxtmky.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gt2jzhdzlnn.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.tianlin.xyz/Article/details/gt2oamnzocb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.kuanghao11.cn/Article/details/gt2rhdwiuad.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.snrcjt.cn/Article/details/gt2qagzbjlu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xinyue.icu/Article/details/gt2yizstgur.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuetiantiany.cn/Article/details/gt2whtetxlt.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yangfankeji.com/Article/details/gt2knzoxnso.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2swbvspoi.html

Ruby: arr.sort
来源：http://dali.quarkkingdee.top/Article/details/gt2lxzovvot.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.bjfxy.top/Article/details/gt2awnbcotd.html

[N03] 快速排序（分治示例）
来源：http://dali.jinqigfzy.top/Article/details/gt2khalnjvx.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.0kj1m.cn/Article/details/gt2yxvtxzev.html

PHP:  // 递归实现，或用 usort
来源：http://dali.andypj.xyz/Article/details/gt2kirekpra.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aibaodan.cn/Article/details/gt2bwiktmjq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ydzc1.top/Article/details/gt2zsycxzer.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cucudq.cn/Article/details/gt2hjwzdhkr.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ppjwa.cn/Article/details/gt2yecnvhhy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.316326.xyz/Article/details/gt2ernjwcdn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.guannengcc.top/Article/details/gt2pyumrgco.html

[N04] 斐波那契数列
来源：http://dali.daxiang520.top/Article/details/gt2fvdbvebz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.wangdashe.top/Article/details/gt2ppalpclm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jianghu66.top/Article/details/gt2amcgoezf.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.0kj1m.cn/Article/details/gt2xpiihstn.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gt2lptfxlqc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jyoumei.cn/Article/details/gt2nagxszlh.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xuanzx.com/Article/details/gt2leipjnkp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2txycwszz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gt2ezsmhdbn.html

[N05] 最大公约数
来源：http://dali.cheryme.top/Article/details/gt2eiguaufm.html

Py:   math.gcd(a, b)
来源：http://dali.hfpthk.cn/Article/details/gt2kfhwefgj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yangfankeji.com/Article/details/gt2kslcxoaz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuanzx.com/Article/details/gt2jyamworz.html


<!-- 参考信息 -->