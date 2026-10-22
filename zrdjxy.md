代发 wailian999

Py:   (end - start).total_seconds()
来源：http://dali.chenzaomai.com/Article/details/gt2daxnixwf.html

PHP:  $end->diff($start)->days;
来源：http://dali.guowangkeji.top/Article/details/gt2fngmxlrf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ieboqazq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.snrcjt.cn/Article/details/gt2hkvkmdvz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.bjfxy.top/Article/details/gt2slndhxpg.html

Go:   end.Sub(start).Hours()
来源：http://dali.guowangkeji.top/Article/details/gt2wrvjtrci.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yangfankeji.com/Article/details/gt2ypdtugby.html

C#:   (end - start).TotalSeconds
来源：http://dali.pycfn.com/Article/details/gt2sscnxacf.html

[J07] 比较两个日期
来源：http://dali.yangfankeji.com/Article/details/gt2mshtwtdk.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jqgfzy.top/Article/details/gt2oopjryxt.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xziqi.cn/Article/details/gt2xrqdsvqr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.bjfxy.top/Article/details/gt2iysfdoqq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.redwolf501.top/Article/details/gt2jghthsai.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yvedp.cn/Article/details/gt2rbhvaknk.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zdqjudy.top/Article/details/gt2qupdmfnn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gt2rlbbfbvb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hfpthk.cn/Article/details/gt2aqaflpxv.html

[J08] 提取年月日与星期
来源：http://dali.cashguo.top/Article/details/gt2tocdyggf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cqqwz.cn/Article/details/gt2mzudfqkn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hfpthk.cn/Article/details/gt2laurdbgd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinqigfzy.top/Article/details/gt2ptpusiam.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sysykeji.top/Article/details/gt2gzfpatbr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.bjfxy.top/Article/details/gt2xdnseahe.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinqigufen.top/Article/details/gt2yonbvtle.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.daxiang520.top/Article/details/gt2ymzorcoa.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhixingplan.top/Article/details/gt2ikttrjhn.html

[J09] 时区处理
来源：http://dali.zhoulong.xyz/Article/details/gt2jxfrsxqp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wffwdyuq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jiagoushi.top/Article/details/gt2vvqxdmep.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ffmhehxu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oidclzfn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yuanzhike.top/Article/details/gt2gesjqtfj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinqigufen.top/Article/details/gt2tchkdxaq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sufxvd.cn/Article/details/gt2shnsufiq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinqigufen.top/Article/details/gt2kvoitvwp.html

[J10] 取今天 / 本月第一天
来源：http://dali.cqqwz.cn/Article/details/gt2rsinztvy.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.dianchejie.cn/Article/details/gt2kplhvxtc.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hfpthk.cn/Article/details/gt2zekrvehd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cqqwz.cn/Article/details/gt2ebdqtbox.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zycfv.cn/Article/details/gt2unbwgidl.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.redwolf501.top/Article/details/gt2ervsmxsq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.nwbrower.top/Article/details/gt2ohiocbyz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ivvv.top/Article/details/gt2ldlthvts.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cashguo.top/Article/details/gt2prjxotst.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vyicxvie.html

K. JSON 与序列化
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zetmtagd.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vxmisldl.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2avkymrvo.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.nanxuanxn.top/Article/details/gt2ggrsxpio.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hysaishi.cn/Article/details/gt2ttfkkvpa.html

JS:   JSON.stringify(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2cuzrbzex.html

TS:   JSON.stringify(obj)
来源：http://dali.xuanzx.com/Article/details/gt2werrlgnx.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gzhubu.top/Article/details/gt2doneqmma.html

Go:   json.Marshal(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2tmkawlhj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sysykeji.top/Article/details/gt2khirxiiu.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qljvvymj.html

[K02] JSON 字符串转对象
来源：http://dali.gaohongyu789.top/Article/details/gt2gusqbuow.html

Py:   json.loads(s)
来源：http://dali.jinqigufen.top/Article/details/gt2jptnhbrb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenjidiqi.icu/Article/details/gt2btcfvjnz.html

JS:   JSON.parse(s)
来源：http://dali.0kj1m.cn/Article/details/gt2ovijqvii.html

TS:   JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gt2wuiluwzs.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gogol.net.cn/Article/details/gt2yixxdifv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ytysllzp.html

Ruby: JSON.parse(s)
来源：http://dali.jyoumei.cn/Article/details/gt2einqiltc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.wangdashe.top/Article/details/gt2jzzuijbv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yj202588.top/Article/details/gt2jvikdjsc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zdqjudy.top/Article/details/gt2exlmcfvk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.chenzaomai.com/Article/details/gt2mijamqwl.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2rfmzcamg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yvedp.cn/Article/details/gt2wnpguqen.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.sxryk.cn/Article/details/gt2vilpmbnv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.fzhhl.top/Article/details/gt2sjmnbrgb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yvedp.cn/Article/details/gt2gsvzktvc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.guowangkeji.top/Article/details/gt2kdodfnek.html

[K04] 读取 JSON 文件
来源：http://dali.hysaishi.cn/Article/details/gt2yzsiuzqx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hammf.cn/Article/details/gt2xfjckebs.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhiwuduotai.top/Article/details/gt2dtjwsodu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnqzz.top/Article/details/gt2zltfyifz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.bjfxy.top/Article/details/gt2yiwdbtct.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.meibo888.top/Article/details/gt2gdzbxztr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zycfv.cn/Article/details/gt2mukfmzuu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hywenlv.cn/Article/details/gt2fqvlnomx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yongpay.top/Article/details/gt2uysyvoei.html

[K05] 深拷贝对象
来源：http://dali.sufxvd.cn/Article/details/gt2fwgpxlnw.html

Py:   copy.deepcopy(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2vioqmbwi.html

PHP:  unserialize(serialize($obj));
来源：http://dali.wangdashe.top/Article/details/gt2hjyldhiy.html

JS:   structuredClone(obj)
来源：http://dali.yuxming.cn/Article/details/gt2iwybxawd.html

TS:   structuredClone(obj)
来源：http://dali.yonumen.top/Article/details/gt2loirfrgm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cucudq.cn/Article/details/gt2mvucjncb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hammf.cn/Article/details/gt2xtvozbmb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hnxiangtu.top/Article/details/gt2idlzqisz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwcvfex.html

[K06] 解析 URL 查询串
来源：http://dali.tanke756.top/Article/details/gt2vwbjcnju.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.meibo888.top/Article/details/gt2qnagaiec.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.daxiang520.top/Article/details/gt2cafflncv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangshuangyany.cn/Article/details/gt2efqgcenm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zycfv.cn/Article/details/gt2lvpuvtzg.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.smart0.xyz/Article/details/gt2qeawjykx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.fengsongda.top/Article/details/gt2mjbusmcg.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhongyouzk.top/Article/details/gt2ksvyievh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.aizwys.cn/Article/details/gt2grhuddls.html

[K07] 进制转换
来源：http://dali.yuanzhike.top/Article/details/gt2tkyrowmg.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.birdmap.top/Article/details/gt2vtcsbyei.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinqigufen.top/Article/details/gt2zfuegmay.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gt2dhyqavut.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.tanke756.top/Article/details/gt2zgsjjwrn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gt2clqucfbl.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2finnquxx.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yanxiufei.cn/Article/details/gt2jijrkogc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gt2nfgzwgrx.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.wangdashe.top/Article/details/gt2xzcmhbir.html

Py:   pickle.dumps(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2pigkljqg.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nanxuanxn.top/Article/details/gt2pchbivkz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.dianchejie.cn/Article/details/gt2udetsmuq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.mhx1999.top/Article/details/gt2vnbimqwm.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhiwuduotai.top/Article/details/gt2kypmwufz.html

Go:   encoding/gob
来源：http://dali.shangyingyoupin.top/Article/details/gt2bddzldbp.html

Ruby: Marshal.dump(obj)
来源：http://dali.yj202588.top/Article/details/gt2xilkpgsg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.iojbl.cn/Article/details/gt2zltmlver.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2kctaegtl.html

L. 网络请求
来源：http://dali.ppjwa.cn/Article/details/gt2gmailpxy.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2djusgdse.html

[L01] 发送 GET 请求
来源：http://dali.birdmap.top/Article/details/gt2oqmpmscm.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.snrcjt.cn/Article/details/gt2rhgtxhed.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhiwuduotai.top/Article/details/gt2axvsehpy.html

JS:   await fetch(url)
来源：http://dali.cheryme.top/Article/details/gt2xasztlpg.html

TS:   await fetch(url)
来源：http://dali.quarkkingdee.top/Article/details/gt2hlhfdsba.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sxryk.cn/Article/details/gt2bmbjvojj.html

Go:   resp, err := http.Get(url)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jhpoqkcc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yueranfly.top/Article/details/gt2kzncyvvw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jyoumei.cn/Article/details/gt2ajhpenzf.html

[L02] 发送 POST JSON
来源：http://dali.zhongyouzk.top/Article/details/gt2lsdyhesk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2qbujqkus.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ydzc1.top/Article/details/gt2prchxfas.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigufen.top/Article/details/gt2xriyvkgn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigfzy.top/Article/details/gt2qqizgfpi.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hywenlv.cn/Article/details/gt2mzxddqlb.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.9152youxi.cn/Article/details/gt2wuftxmtr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.pycfn.com/Article/details/gt2tbabfxui.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhongyouzk.top/Article/details/gt2xseqebyo.html

[L03] 设置自定义请求头
来源：http://dali.316326.xyz/Article/details/gt2cohoyany.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ybcxt.top/Article/details/gt2rcgbxlkd.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sxryk.cn/Article/details/gt2ofjhgtfj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenjidiqi.icu/Article/details/gt2crlalumf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sufxvd.cn/Article/details/gt2oqtqzpzn.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ppjwa.cn/Article/details/gt2shesbzem.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.0kj1m.cn/Article/details/gt2esdjdiyc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ydzc1.top/Article/details/gt2nthqfgvr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.chenzaomai.com/Article/details/gt2wsgsnify.html

[L04] 设置超时
来源：http://dali.meibo888.top/Article/details/gt2kwmzopzp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.c1oappe.top/Article/details/gt2ttxrqtjx.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zycfv.cn/Article/details/gt2qqxlqmpp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gaohongyu789.top/Article/details/gt2qvfthdym.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hammf.cn/Article/details/gt2lgmlzrod.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ehwqpu.com/Article/details/gt2fruslmbv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhongyouzk.top/Article/details/gt2cfscaxcc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ivvv.top/Article/details/gt2nqsgwofz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zggbgvyq.html

[L05] 上传文件（multipart）
来源：http://dali.chenlongwang.top/Article/details/gt2mhqwivfh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.chenjidiqi.icu/Article/details/gt2dlyipwuy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2stchsdwl.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.iojbl.cn/Article/details/gt2msmrsrat.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2fxmauznh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hammf.cn/Article/details/gt2jxthrfoj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yvedp.cn/Article/details/gt2lcfjsfqh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.dashuyun.cn/Article/details/gt2tuboulib.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.aibaodan.cn/Article/details/gt2czvcvrtd.html

[L06] 解析响应为 JSON
来源：http://dali.mhx1999.top/Article/details/gt2sxrfwyaa.html

Py:   resp.json()
来源：http://dali.birdmap.top/Article/details/gt2yqyqrgsn.html

PHP:  json_decode($body, true);
来源：http://dali.jqgufenzy.top/Article/details/gt2qmyaipwr.html

JS:   await resp.json()
来源：http://dali.sxryk.cn/Article/details/gt2rrfziyle.html

TS:   await resp.json()
来源：http://dali.iojbl.cn/Article/details/gt2soawuqjg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.dashuyun.cn/Article/details/gt2pixxtolk.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.9152youxi.cn/Article/details/gt2ojrhulbf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.birdmap.top/Article/details/gt2xzteapro.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ydzc1.top/Article/details/gt2cotjpbno.html

[L07] 处理 HTTP 状态码
来源：http://dali.xuanzx.com/Article/details/gt2blucdnwl.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tanke756.top/Article/details/gt2cujegbpw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yvedp.cn/Article/details/gt2ihdqjzky.html

JS:   resp.ok;  resp.status
来源：http://dali.jyoumei.cn/Article/details/gt2yftdvxos.html

TS:   resp.ok;  resp.status
来源：http://dali.sxryk.cn/Article/details/gt2rpqbisif.html

Java: resp.statusCode()
来源：http://dali.guannengcc.top/Article/details/gt2lyldalns.html

Go:   resp.StatusCode
来源：http://dali.wangshuangyany.cn/Article/details/gt2kthnorxd.html

Ruby: resp.code.to_i
来源：http://dali.aizwys.cn/Article/details/gt2ijazdost.html

C#:   (int)resp.StatusCode
来源：http://dali.chenzaomai.com/Article/details/gt2dsztmpgj.html

[L08] 并发请求多个地址
来源：http://dali.jinqigufen.top/Article/details/gt2krtqjjww.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.9152youxi.cn/Article/details/gt2xyecgkyf.html

PHP:  curl_multi_init() 系列
来源：http://dali.aibaodan.cn/Article/details/gt2hjiwxgvo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gt2sojivnei.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.birdmap.top/Article/details/gt2lrduuuqd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhongyouzk.top/Article/details/gt2mnsobfuj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.0kj1m.cn/Article/details/gt2yvrzjqzf.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.fengsongda.top/Article/details/gt2uatiedkp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.chenzaomai.com/Article/details/gt2piehfazo.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2dqnnoeai.html

M. 命令行 / 进程 / 环境
来源：http://dali.kuanghao11.cn/Article/details/gt2rdfqhnhj.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2nbxhxeyr.html

[M01] 读取命令行参数
来源：http://dali.cheryme.top/Article/details/gt2tkcagnaj.html

Py:   sys.argv[1:]
来源：http://dali.gaohongyu789.top/Article/details/gt2xdyqiefd.html

PHP:  $argv;  $argc;
来源：http://dali.wangdashe.top/Article/details/gt2pzjsdxjn.html

JS:   process.argv.slice(2)
来源：http://dali.kuanghao11.cn/Article/details/gt2hwzwadzh.html

TS:   process.argv.slice(2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2rhtvenju.html

Java: args 数组（main 方法参数）
来源：http://dali.ppjwa.cn/Article/details/gt2yofbuadj.html

Go:   os.Args[1:]
来源：http://dali.yj202588.top/Article/details/gt2uviukvkn.html

Ruby: ARGV
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ouqjmvfw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2atievfsz.html

[M02] 读取环境变量
来源：http://dali.nanxuanxn.top/Article/details/gt2pouzbduf.html

Py:   os.environ.get("HOME")
来源：http://dali.cheryme.top/Article/details/gt2mpabijxr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shangyingyoupin.top/Article/details/gt2atdgnvnd.html

JS:   process.env.HOME
来源：http://dali.haohaochexian.top/Article/details/gt2iysowwlq.html

TS:   process.env.HOME
来源：http://dali.jyoumei.cn/Article/details/gt2ozjazsng.html

Java: System.getenv("HOME")
来源：http://dali.zhixingplan.top/Article/details/gt2qqiyapfd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cashguo.top/Article/details/gt2pvnyqzbs.html

Ruby: ENV["HOME"]
来源：http://dali.nwbrower.top/Article/details/gt2nqupndkq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gt2dfpnknws.html

[M03] 执行外部命令
来源：http://dali.tianlin.xyz/Article/details/gt2ueqnbdke.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhengqikj.top/Article/details/gt2zyrsvftk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hnxiangtu.top/Article/details/gt2mqfqvqmc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hammf.cn/Article/details/gt2nyyupuut.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.iojbl.cn/Article/details/gt2ugztkmcj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.dianchejie.cn/Article/details/gt2dnzjuhrs.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yangfankeji.com/Article/details/gt2zajeqwqx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yueranfly.top/Article/details/gt2hdhunoud.html

C#:   Process.Start("ls", "-l");
来源：http://dali.bjfxy.top/Article/details/gt2rckvsjly.html

[M04] 获取当前工作目录
来源：http://dali.feifeiyinyue.top/Article/details/gt2gvqzxrck.html

Py:   os.getcwd()
来源：http://dali.tanke756.top/Article/details/gt2uofflqcz.html

PHP:  getcwd();
来源：http://dali.jianghu66.top/Article/details/gt2afhngriu.html

JS:   process.cwd()
来源：http://dali.chenjidiqi.icu/Article/details/gt2fzgndzsg.html

TS:   process.cwd()
来源：http://dali.redwolf501.top/Article/details/gt2mfzdcbfr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ycwbaeel.html

Go:   os.Getwd()
来源：http://dali.ybcxt.top/Article/details/gt2ncsnaaep.html

Ruby: Dir.pwd
来源：http://dali.quarkkingdee.top/Article/details/gt2cvtcmqgd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xuanzx.com/Article/details/gt2zceqoxdf.html

[M05] 设置退出码
来源：http://dali.ydzc1.top/Article/details/gt2mefwvcby.html

Py:   sys.exit(1)
来源：http://dali.tian-w.cn/Article/details/gt2ncjmvgcv.html

PHP:  exit(1);
来源：http://dali.zhoulong.xyz/Article/details/gt2nepzikno.html

JS:   process.exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pbeiupqx.html

TS:   process.exit(1)
来源：http://dali.pycfn.com/Article/details/gt2mpcqwdtt.html

Java: System.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2nqxiiziz.html

Go:   os.Exit(1)
来源：http://dali.sysykeji.top/Article/details/gt2xwkiwooa.html

Ruby: exit 1
来源：http://dali.yueranfly.top/Article/details/gt2eunxolwn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yuanzhike.top/Article/details/gt2pkxgwngr.html

[M06] 向标准错误输出
来源：http://dali.zhongyouzk.top/Article/details/gt2ptrxfqqm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj20258.top/Article/details/gt2mnsofxgt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yj202588.top/Article/details/gt2rtiustns.html

JS:   console.error("err")
来源：http://dali.tanke756.top/Article/details/gt2vwiplhmo.html

TS:   console.error("err")
来源：http://dali.xinyue.icu/Article/details/gt2vbiiwhwr.html

Java: System.err.println("err")
来源：http://dali.jyoumei.cn/Article/details/gt2gvuvjkew.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jlsjyb.cn/Article/details/gt2jcloaaqf.html

Ruby: warn "err"
来源：http://dali.meibo888.top/Article/details/gt2beiferrz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tanke756.top/Article/details/gt2goougyum.html

[M07] 判断是否为主入口
来源：http://dali.zhoulong.xyz/Article/details/gt2wyjrtbvb.html

Py:   if __name__ == "__main__":
来源：http://dali.sufxvd.cn/Article/details/gt2mbqdktii.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cjmwlmnf.html

JS:   require.main === module
来源：http://dali.aibaodan.cn/Article/details/gt2qimqvkxu.html

TS:   require.main === module
来源：http://dali.nwbrower.top/Article/details/gt2ufwhzdnp.html

Java: public static void main(String[] args)
来源：http://dali.pengpengdd.cyou/Article/details/gt2hyeybhal.html

Go:   func main()
来源：http://dali.jinqigufen.top/Article/details/gt2nhvhsxkp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.guowangkeji.top/Article/details/gt2blkurwwd.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlczcqdt.html

[M08] 获取系统与运行时信息
来源：http://dali.yj20258.top/Article/details/gt2zpxyumbm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shangyingyoupin.top/Article/details/gt2znhorwcs.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.pycfn.com/Article/details/gt2mwugcyeh.html

JS:   process.platform;  process.version
来源：http://dali.sxryk.cn/Article/details/gt2wltjiehy.html

TS:   process.platform;  process.version
来源：http://dali.vqdsnc.cn/Article/details/gt2ptsgmoej.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shuidangran.top/Article/details/gt2pwtyxppo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sufxvd.cn/Article/details/gt2zmtgkkam.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.wangshuangyany.cn/Article/details/gt2lydxaoty.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hnxiangtu.top/Article/details/gt2lgjfrgss.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2fvhjpuno.html

N. 数据结构与算法
来源：http://dali.jyoumei.cn/Article/details/gt2qvvzjccv.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2glmecymt.html

[N01] 二分查找（有序数组）
来源：http://dali.nanxinkj.top/Article/details/gt2fwlnkrcd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gt2uphbyhef.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.mhx1999.top/Article/details/gt2uklflhbq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hammf.cn/Article/details/gt2wlnyrscg.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.meibo888.top/Article/details/gt2mjsroakw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2htpyggsb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.wangdashe.top/Article/details/gt2xvnatisk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yonumen.top/Article/details/gt2apolajfk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fhsfradk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hongshengwenyu.top/Article/details/gt2fytctlso.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.mhx1999.top/Article/details/gt2nzrjlyci.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xuanzx.com/Article/details/gt2ujqgeahr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuanzx.com/Article/details/gt2uepihscy.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnxiangtu.top/Article/details/gt2dznyywcy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.smart0.xyz/Article/details/gt2ormnuznn.html

Go:   slices.Sort(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2nebvumvj.html

Ruby: arr.sort
来源：http://dali.mhx1999.top/Article/details/gt2kxpogufe.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.aizwys.cn/Article/details/gt2gexaxsqm.html

[N03] 快速排序（分治示例）
来源：http://dali.zhixingplan.top/Article/details/gt2qzmydnbc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.guowangkeji.top/Article/details/gt2guinyljd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gaohongyu789.top/Article/details/gt2tqowfcbj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hnxiangtu.top/Article/details/gt2cyciqftj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj202588.top/Article/details/gt2csnjhjfr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hysaishi.cn/Article/details/gt2dmeomkgt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mcroltjo.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yanxiufei.cn/Article/details/gt2kteskzqi.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yvedp.cn/Article/details/gt2hywzjpqx.html

[N04] 斐波那契数列
来源：http://dali.gaohongyu789.top/Article/details/gt2ndlgfrmu.html


<!-- 参考信息 -->