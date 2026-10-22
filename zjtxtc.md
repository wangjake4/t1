代发 wailian999

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xylfe.cn/Article/details/gt2hlbwlylk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.smart0.xyz/Article/details/gt2rvltmxhp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.quarkkingdee.top/Article/details/gt2fchfcefv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ybcxt.top/Article/details/gt2leqmlgis.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gt2bsvrgbss.html

[J08] 提取年月日与星期
来源：http://dali.sysykeji.top/Article/details/gt2qkjdizdb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yanxiufei.cn/Article/details/gt2calrenms.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hnqzz.top/Article/details/gt2jukhjjxh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xylfe.cn/Article/details/gt2dqsgibum.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.pengpengdd.cyou/Article/details/gt2euwkkxct.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.nwbrower.top/Article/details/gt2qkthvmlb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.iojbl.cn/Article/details/gt2nmmeewhb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cashguo.top/Article/details/gt2tukemwko.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cheryme.top/Article/details/gt2amzuyyey.html

[J09] 时区处理
来源：http://dali.kuanghao11.cn/Article/details/gt2xonegrtf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nanxinkj.top/Article/details/gt2fkdncsxl.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yj20258.top/Article/details/gt2pkgmpzwh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.kuanghao11.cn/Article/details/gt2xuoihdbi.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dashuyun.cn/Article/details/gt2egqmiddm.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.aizwys.cn/Article/details/gt2jarymjdm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.chenlongwang.top/Article/details/gt2lhqpeshc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.quarkkingdee.top/Article/details/gt2swtqdhti.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sufxvd.cn/Article/details/gt2azpfncdb.html

[J10] 取今天 / 本月第一天
来源：http://dali.smart0.xyz/Article/details/gt2hxpctufc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sysykeji.top/Article/details/gt2nnidtbip.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhiwuduotai.top/Article/details/gt2uphpnoxd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.redwolf501.top/Article/details/gt2nwbiitnn.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.guowangkeji.top/Article/details/gt2annaxxae.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yongpay.top/Article/details/gt2huhpymio.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hnqzz.top/Article/details/gt2oymrefdw.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tanke756.top/Article/details/gt2nmfsfjzc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.daxiang520.top/Article/details/gt2byjlrofy.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2njncppaz.html

K. JSON 与序列化
来源：http://dali.cashguo.top/Article/details/gt2qkfsezxi.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2dmlodune.html

[K01] 对象转 JSON 字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2umxgleph.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jlsjyb.cn/Article/details/gt2fdgtiuua.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zycfv.cn/Article/details/gt2dioiaqpk.html

JS:   JSON.stringify(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2aeaphiff.html

TS:   JSON.stringify(obj)
来源：http://dali.pycfn.com/Article/details/gt2zmnolpsa.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.redwolf501.top/Article/details/gt2ixdxdkqg.html

Go:   json.Marshal(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2rotnjtmr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.andypj.xyz/Article/details/gt2flkepzao.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zycfv.cn/Article/details/gt2chcdrfuj.html

[K02] JSON 字符串转对象
来源：http://dali.xylfe.cn/Article/details/gt2gzdcwjlh.html

Py:   json.loads(s)
来源：http://dali.yangfankeji.com/Article/details/gt2elwxkyvf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gektmqhe.html

JS:   JSON.parse(s)
来源：http://dali.9152youxi.cn/Article/details/gt2lreafcqh.html

TS:   JSON.parse(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2gzgxyyjc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.chenlongwang.top/Article/details/gt2pzgxlwjv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gotoacloud.top/Article/details/gt2lhngetse.html

Ruby: JSON.parse(s)
来源：http://dali.yueranfly.top/Article/details/gt2ixvpgvea.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.pycfn.com/Article/details/gt2kxekabgx.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.mhx1999.top/Article/details/gt2lrhsbvlf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yongpay.top/Article/details/gt2ezfjhopi.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.fzhhl.top/Article/details/gt2tsothwoq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shzxlz.cn/Article/details/gt2uusqezmo.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258.top/Article/details/gt2jsozjnwv.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2uxunoycz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ppjwa.cn/Article/details/gt2lpnrzyfb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2yfamsnmh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.fzhhl.top/Article/details/gt2nylxjvqb.html

[K04] 读取 JSON 文件
来源：http://dali.chenzaomai.com/Article/details/gt2lxdqilxj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jianghu66.top/Article/details/gt2safclxpm.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jlsjyb.cn/Article/details/gt2bzhrrrur.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.c1oappe.top/Article/details/gt2bvisqnsr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cashguo.top/Article/details/gt2oavlldtn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.daria6918.cn/Article/details/gt2dxmyxruj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zdqjudy.top/Article/details/gt2rosowvos.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yuanzhike.top/Article/details/gt2zqbqeiws.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhongyouzk.top/Article/details/gt2vzmxmxbf.html

[K05] 深拷贝对象
来源：http://dali.hongshengwenyu.top/Article/details/gt2viehplhk.html

Py:   copy.deepcopy(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2fotypddj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.dianchejie.cn/Article/details/gt2wmpafbfs.html

JS:   structuredClone(obj)
来源：http://dali.zycfv.cn/Article/details/gt2snpmqefy.html

TS:   structuredClone(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2fywfdeso.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.tianlin.xyz/Article/details/gt2hmtqwinu.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hfpthk.cn/Article/details/gt2rimasogb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ehwqpu.com/Article/details/gt2uzdrojge.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.chenlongwang.top/Article/details/gt2mlnqdgfl.html

[K06] 解析 URL 查询串
来源：http://dali.chenjidiqi.icu/Article/details/gt2hxlpyzyj.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xylfe.cn/Article/details/gt2gwzcshax.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.sysykeji.top/Article/details/gt2oxopyujh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.fengsongda.top/Article/details/gt2flmllczp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ehwqpu.com/Article/details/gt2ucyigkqi.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gaohongyu789.top/Article/details/gt2rlwzdbfp.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.pycfn.com/Article/details/gt2iycfione.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhengqikj.top/Article/details/gt2ytkdzrba.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xuetiantiany.cn/Article/details/gt2lbdfxbva.html

[K07] 进制转换
来源：http://dali.yonumen.top/Article/details/gt2mwhmtcif.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gt2dkcoceek.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xylfe.cn/Article/details/gt2zoesajtd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gt2mhwvzxlc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gt2hupzyihp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xjlbueeo.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xuanzx.com/Article/details/gt2bkgqgcel.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xvwycbdg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gt2rszkgltk.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cdnleiting.top/Article/details/gt2frawnitf.html

Py:   pickle.dumps(obj)
来源：http://dali.birdmap.top/Article/details/gt2fnkdbdse.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.birdmap.top/Article/details/gt2tccyuzam.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.nanxuanxn.top/Article/details/gt2xpophtlw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.mhx1999.top/Article/details/gt2ptlvmokp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.wangshuangyany.cn/Article/details/gt2savhsobd.html

Go:   encoding/gob
来源：http://dali.xuanzx.com/Article/details/gt2hssoghkh.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hvplmxdx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhixingplan.top/Article/details/gt2qknolvtc.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2ihuasvzo.html

L. 网络请求
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qvzlavre.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2pyqezzgx.html

[L01] 发送 GET 请求
来源：http://dali.cucudq.cn/Article/details/gt2cgusddjh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hnqzz.top/Article/details/gt2xmbsbnvb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sbuovufw.html

JS:   await fetch(url)
来源：http://dali.havefunace.top/Article/details/gt2oalwmqnr.html

TS:   await fetch(url)
来源：http://dali.wangdashe.top/Article/details/gt2wbqkinkj.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jqgfzy.top/Article/details/gt2ultjbvyz.html

Go:   resp, err := http.Get(url)
来源：http://dali.hammf.cn/Article/details/gt2niaqexow.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hywenlv.cn/Article/details/gt2dueynsie.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zycfv.cn/Article/details/gt2amofvekz.html

[L02] 发送 POST JSON
来源：http://dali.gzhubu.top/Article/details/gt2rmjvcotv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.pycfn.com/Article/details/gt2rrmonsfv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.gzhubu.top/Article/details/gt2oweozgeo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuetiantiany.cn/Article/details/gt2bavojmyx.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangdashe.top/Article/details/gt2clrmgcjt.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwjerca.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wlonekwd.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yeycaynk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jagqixgc.html

[L03] 设置自定义请求头
来源：http://dali.shuidangran.top/Article/details/gt2uozaeyso.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.0kj1m.cn/Article/details/gt2zkbbiaua.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.fzhhl.top/Article/details/gt2gviifhwf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnqzz.top/Article/details/gt2hesldofq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2niedubva.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wpmewdxp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2krszbtji.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yuxming.cn/Article/details/gt2wfwfeanx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yonumen.top/Article/details/gt2anqjktyz.html

[L04] 设置超时
来源：http://dali.yj202588.top/Article/details/gt2nvleaylr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.birdmap.top/Article/details/gt2dqzhxnrb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hysaishi.cn/Article/details/gt2avmllofw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yonumen.top/Article/details/gt2xhprqbzy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenlongwang.top/Article/details/gt2jvvefaqo.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.chenlongwang.top/Article/details/gt2smzufxyz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ivvv.top/Article/details/gt2mestjazc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hywenlv.cn/Article/details/gt2pkxeklut.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinqigfzy.top/Article/details/gt2tywxssdy.html

[L05] 上传文件（multipart）
来源：http://dali.hnqzz.top/Article/details/gt2aarcomqf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jqgufenzy.top/Article/details/gt2xgdaumau.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yueranfly.top/Article/details/gt2pfmzxhgm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.quarkkingdee.top/Article/details/gt2fgcpchgz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.guannengcc.top/Article/details/gt2dvwjomyr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.guowangkeji.top/Article/details/gt2oliqlghc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2yhurkyyo.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jianghu66.top/Article/details/gt2xhxhnsrh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2tuvrcscy.html

[L06] 解析响应为 JSON
来源：http://dali.chenjidiqi.icu/Article/details/gt2ejrkiuxf.html

Py:   resp.json()
来源：http://dali.ppjwa.cn/Article/details/gt2urmropbr.html

PHP:  json_decode($body, true);
来源：http://dali.smart0.xyz/Article/details/gt2qngrmjjz.html

JS:   await resp.json()
来源：http://dali.zycfv.cn/Article/details/gt2jrwdjzev.html

TS:   await resp.json()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qvohxoaj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.tianlin.xyz/Article/details/gt2enuknsvj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.0kj1m.cn/Article/details/gt2tjvwtewi.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hysaishi.cn/Article/details/gt2ymzesyar.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.bjfxy.top/Article/details/gt2wgpnfilq.html

[L07] 处理 HTTP 状态码
来源：http://dali.pengpengdd.cyou/Article/details/gt2efhrqbre.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.bjfxy.top/Article/details/gt2yhthuqxv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zdqjudy.top/Article/details/gt2dpggwitw.html

JS:   resp.ok;  resp.status
来源：http://dali.cdnleiting.top/Article/details/gt2yvfaidwg.html

TS:   resp.ok;  resp.status
来源：http://dali.chenlongwang.top/Article/details/gt2xmxhqjue.html

Java: resp.statusCode()
来源：http://dali.cqqwz.cn/Article/details/gt2nqlgwjew.html

Go:   resp.StatusCode
来源：http://dali.xinyue.icu/Article/details/gt2mqlounbi.html

Ruby: resp.code.to_i
来源：http://dali.guowangkeji.top/Article/details/gt2kdezyilz.html

C#:   (int)resp.StatusCode
来源：http://dali.shangyingyoupin.top/Article/details/gt2iqrcmzkh.html

[L08] 并发请求多个地址
来源：http://dali.gaohongyu789.top/Article/details/gt2enkaovko.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fufcifrh.html

PHP:  curl_multi_init() 系列
来源：http://dali.yanxiufei.cn/Article/details/gt2llntdubm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.c1oappe.top/Article/details/gt2gescmyzp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuxming.cn/Article/details/gt2fvsxjjns.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zycfv.cn/Article/details/gt2hudhuafj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sxryk.cn/Article/details/gt2wljdlwnx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vhnuqfxn.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zdqjudy.top/Article/details/gt2cjjakpzl.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2uukpbtlx.html

M. 命令行 / 进程 / 环境
来源：http://dali.hammf.cn/Article/details/gt2ddzdcssl.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2wufprhbr.html

[M01] 读取命令行参数
来源：http://dali.cdnleiting.top/Article/details/gt2xpovubsn.html

Py:   sys.argv[1:]
来源：http://dali.kuanghao11.cn/Article/details/gt2vinsszae.html

PHP:  $argv;  $argc;
来源：http://dali.chenlongwang.top/Article/details/gt2qtnqkryr.html

JS:   process.argv.slice(2)
来源：http://dali.aizwys.cn/Article/details/gt2kexwiiug.html

TS:   process.argv.slice(2)
来源：http://dali.zdqjudy.top/Article/details/gt2gdzdjcxr.html

Java: args 数组（main 方法参数）
来源：http://dali.shzxlz.cn/Article/details/gt2tybowelg.html

Go:   os.Args[1:]
来源：http://dali.chenzaomai.com/Article/details/gt2hpiqzgao.html

Ruby: ARGV
来源：http://dali.yanxiufei.cn/Article/details/gt2pzurburj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.tianlin.xyz/Article/details/gt2mgawafdh.html

[M02] 读取环境变量
来源：http://dali.svipenyu.cn/Article/details/gt2fybrivsk.html

Py:   os.environ.get("HOME")
来源：http://dali.cqqwz.cn/Article/details/gt2iadaqrwf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinqigfzy.top/Article/details/gt2hmxnvxmg.html

JS:   process.env.HOME
来源：http://dali.yueranfly.top/Article/details/gt2xwkyqqxg.html

TS:   process.env.HOME
来源：http://dali.daxiang520.top/Article/details/gt2cchznzkd.html

Java: System.getenv("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gt2mzuwtsvy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gt2hlzegjhx.html

Ruby: ENV["HOME"]
来源：http://dali.bjfxy.top/Article/details/gt2lpzpslvy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gt2igkqdpmc.html

[M03] 执行外部命令
来源：http://dali.cqqwz.cn/Article/details/gt2avhfktqu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.meibo888.top/Article/details/gt2nlfeekni.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.mhx1999.top/Article/details/gt2atzjidgd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yueranfly.top/Article/details/gt2ernqvjlb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhixingplan.top/Article/details/gt2iqeypevq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ybcxt.top/Article/details/gt2hstpemuc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yj20258.top/Article/details/gt2bpmmtzri.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sysykeji.top/Article/details/gt2agyqgbkq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jianghu66.top/Article/details/gt2iurfunlh.html

[M04] 获取当前工作目录
来源：http://dali.chenjidiqi.icu/Article/details/gt2tzcgtnhu.html

Py:   os.getcwd()
来源：http://dali.bjfxy.top/Article/details/gt2ngqlvyrt.html

PHP:  getcwd();
来源：http://dali.shuidangran.top/Article/details/gt2fgourpbm.html

JS:   process.cwd()
来源：http://dali.c1oappe.top/Article/details/gt2yvaqovbp.html

TS:   process.cwd()
来源：http://dali.andypj.xyz/Article/details/gt2laxbprtz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.kuanghao11.cn/Article/details/gt2wrxnquqy.html

Go:   os.Getwd()
来源：http://dali.yueranfly.top/Article/details/gt2qnneonrh.html

Ruby: Dir.pwd
来源：http://dali.yangfankeji.com/Article/details/gt2tdlrxfcl.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cdnleiting.top/Article/details/gt2erfraufl.html

[M05] 设置退出码
来源：http://dali.cqqwz.cn/Article/details/gt2bxncmywq.html

Py:   sys.exit(1)
来源：http://dali.ybcxt.top/Article/details/gt2qdoxqiov.html

PHP:  exit(1);
来源：http://dali.hywenlv.cn/Article/details/gt2hgvteskq.html

JS:   process.exit(1)
来源：http://dali.yvedp.cn/Article/details/gt2vajnljmn.html

TS:   process.exit(1)
来源：http://dali.xylfe.cn/Article/details/gt2rtpwlphc.html

Java: System.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2lmocyydr.html

Go:   os.Exit(1)
来源：http://dali.yangfankeji.com/Article/details/gt2twngbppy.html

Ruby: exit 1
来源：http://dali.smart0.xyz/Article/details/gt2yxhvbvyu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.andypj.xyz/Article/details/gt2rvfcqung.html

[M06] 向标准错误输出
来源：http://dali.daria6918.cn/Article/details/gt2rdwcwovx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj20258.top/Article/details/gt2owqzmevk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ehwqpu.com/Article/details/gt2kzardjei.html

JS:   console.error("err")
来源：http://dali.quarkkingdee.top/Article/details/gt2nlpmmetq.html

TS:   console.error("err")
来源：http://dali.pengpengdd.cyou/Article/details/gt2puirtnim.html

Java: System.err.println("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2utaielto.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.haohaochexian.top/Article/details/gt2ueynfzkm.html

Ruby: warn "err"
来源：http://dali.kuanghao11.cn/Article/details/gt2gbzxhgzh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yonumen.top/Article/details/gt2xzeccjis.html

[M07] 判断是否为主入口
来源：http://dali.hongshengwenyu.top/Article/details/gt2ncekozrz.html

Py:   if __name__ == "__main__":
来源：http://dali.svipenyu.cn/Article/details/gt2gyjjqazy.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhoulong.xyz/Article/details/gt2vuxuocnp.html

JS:   require.main === module
来源：http://dali.sxryk.cn/Article/details/gt2aoxnwcbz.html

TS:   require.main === module
来源：http://dali.hnxiangtu.top/Article/details/gt2tmlfjziw.html

Java: public static void main(String[] args)
来源：http://dali.cheryme.top/Article/details/gt2uekrohek.html

Go:   func main()
来源：http://dali.gotoacloud.top/Article/details/gt2fuinhjpl.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gogol.net.cn/Article/details/gt2ugkzlwnb.html

C#:   static void Main(string[] args)
来源：http://dali.hywenlv.cn/Article/details/gt2kivazzre.html

[M08] 获取系统与运行时信息
来源：http://dali.ppjwa.cn/Article/details/gt2gbehevnd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.bjfxy.top/Article/details/gt2svltzqda.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.andypj.xyz/Article/details/gt2sfoirmrc.html

JS:   process.platform;  process.version
来源：http://dali.ydzc1.top/Article/details/gt2mcfzxnpk.html

TS:   process.platform;  process.version
来源：http://dali.yongpay.top/Article/details/gt2ekrayorm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.svipenyu.cn/Article/details/gt2uhxjuepo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.nanxuanxn.top/Article/details/gt2dxzcfska.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gprtgxgq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hongshengwenyu.top/Article/details/gt2uwuapzvz.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2oimgaloy.html

N. 数据结构与算法
来源：http://dali.smart0.xyz/Article/details/gt2awtklhsw.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2gpwzdxeq.html

[N01] 二分查找（有序数组）
来源：http://dali.vqdsnc.cn/Article/details/gt2hwjblnlu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.pycfn.com/Article/details/gt2iuisewjm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.redwolf501.top/Article/details/gt2aniilfya.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tianlin.xyz/Article/details/gt2ohkozckg.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gt2ixotuyta.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2gkpxkaxj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2yfddnxux.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinqigufen.top/Article/details/gt2dlutpxrs.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gt2shqgxsqx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.guannengcc.top/Article/details/gt2xnbvnojl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnqzz.top/Article/details/gt2ttmdrzam.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cucudq.cn/Article/details/gt2bjfrktxv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fzhhl.top/Article/details/gt2xxzuzojn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xylfe.cn/Article/details/gt2odslymtj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jianghu66.top/Article/details/gt2ksqmzttc.html

Go:   slices.Sort(arr)
来源：http://dali.hfpthk.cn/Article/details/gt2angucnvi.html

Ruby: arr.sort
来源：http://dali.xziqi.cn/Article/details/gt2pxkfotxx.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hongshengwenyu.top/Article/details/gt2vjwhnjdn.html

[N03] 快速排序（分治示例）
来源：http://dali.xuanzx.com/Article/details/gt2gjvdtacx.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cheryme.top/Article/details/gt2qftxgkrm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ppjwa.cn/Article/details/gt2ywdlrkna.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ybcxt.top/Article/details/gt2tthtjdkt.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangshuangyany.cn/Article/details/gt2egtfvxdp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ppjwa.cn/Article/details/gt2tuysrmus.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cucudq.cn/Article/details/gt2lyhbfcjm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.meibo888.top/Article/details/gt2dlogrwzi.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sufxvd.cn/Article/details/gt2pgchhkqh.html

[N04] 斐波那契数列
来源：http://dali.smart0.xyz/Article/details/gt2xwctlcej.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xplokvyl.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.nanxuanxn.top/Article/details/gt2cfamlnnn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ppjwa.cn/Article/details/gt2fvzefcuy.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangdashe.top/Article/details/gt2bmmofbto.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ivvv.top/Article/details/gt2dtnxxupq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ydzc1.top/Article/details/gt2vmsyfriq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffslzgju.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.chenzaomai.com/Article/details/gt2dyikeigg.html

[N05] 最大公约数
来源：http://dali.sufxvd.cn/Article/details/gt2vkuttziv.html

Py:   math.gcd(a, b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sumkpatv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.tanke756.top/Article/details/gt2hqmoybmw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuanzx.com/Article/details/gt2eihcsgio.html


<!-- 参考信息 -->