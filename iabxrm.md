代发 wailian999

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zdqjudy.top/Article/details/gt2khgnwtvo.html

Go:   end.Sub(start).Hours()
来源：http://dali.vqdsnc.cn/Article/details/gt2wjovyyag.html

Ruby: end - start                 # 返回秒数
来源：http://dali.nwbrower.top/Article/details/gt2vucbleoo.html

C#:   (end - start).TotalSeconds
来源：http://dali.pengpengdd.cyou/Article/details/gt2dbrdamlr.html

[J07] 比较两个日期
来源：http://dali.c1oappe.top/Article/details/gt2doxysyhs.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vpxtjxnj.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yonumen.top/Article/details/gt2ylscahfa.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hywenlv.cn/Article/details/gt2bifoytzp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yuanzhike.top/Article/details/gt2zdxbwciu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cqqwz.cn/Article/details/gt2xmvmfnsd.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hizzhxdg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.haohaochexian.top/Article/details/gt2hceouwix.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gt2kkgwpwik.html

[J08] 提取年月日与星期
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eunhqqos.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ehwqpu.com/Article/details/gt2kryeeepa.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xuanzx.com/Article/details/gt2zffeelea.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2monhornz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hongshengwenyu.top/Article/details/gt2umlzoikr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.fengsongda.top/Article/details/gt2ausgbaho.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ubcjbnze.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hammf.cn/Article/details/gt2dljwvtdl.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ybcxt.top/Article/details/gt2fmsufsgm.html

[J09] 时区处理
来源：http://dali.ehwqpu.com/Article/details/gt2tvgvjbcn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hammf.cn/Article/details/gt2imagjart.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ugydcbzp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.snrcjt.cn/Article/details/gt2qrjcqjmr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hammf.cn/Article/details/gt2kfwpgzvd.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.dashuyun.cn/Article/details/gt2awutlpwd.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xinyue.icu/Article/details/gt2yceqhdro.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sxryk.cn/Article/details/gt2irkejvdn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.dianchejie.cn/Article/details/gt2gmpylfca.html

[J10] 取今天 / 本月第一天
来源：http://dali.ybcxt.top/Article/details/gt2gsjzlqjt.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sxryk.cn/Article/details/gt2gwzmqkal.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ppjwa.cn/Article/details/gt2vdzzrsvp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yueranfly.top/Article/details/gt2imophhlf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qxkuxqgk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cucudq.cn/Article/details/gt2seimwjzx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.mhx1999.top/Article/details/gt2hngpmnyw.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gzhubu.top/Article/details/gt2cizpmmha.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wcsdnutk.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2prqagiwj.html

K. JSON 与序列化
来源：http://dali.zdqjudy.top/Article/details/gt2ogttghzy.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2imtjsppm.html

[K01] 对象转 JSON 字符串
来源：http://dali.meibo888.top/Article/details/gt2qoaudqvf.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.guannengcc.top/Article/details/gt2lyismrtk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yueranfly.top/Article/details/gt2mrglmjbj.html

JS:   JSON.stringify(obj)
来源：http://dali.xziqi.cn/Article/details/gt2rertvitu.html

TS:   JSON.stringify(obj)
来源：http://dali.jianghu66.top/Article/details/gt2moptwobw.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.wangdashe.top/Article/details/gt2uvjbhypc.html

Go:   json.Marshal(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2vutuqson.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hnxiangtu.top/Article/details/gt2igznpnpj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vrpazghp.html

[K02] JSON 字符串转对象
来源：http://dali.yuanzhike.top/Article/details/gt2mpfubffi.html

Py:   json.loads(s)
来源：http://dali.birdmap.top/Article/details/gt2sjzudlsz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.quarkkingdee.top/Article/details/gt2oxxivmak.html

JS:   JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gt2nvzdnhzs.html

TS:   JSON.parse(s)
来源：http://dali.jianghu66.top/Article/details/gt2hrgwxypz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.birdmap.top/Article/details/gt2fljraoxj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sweek.top/Article/details/gt2lwrswshq.html

Ruby: JSON.parse(s)
来源：http://dali.xuanzx.com/Article/details/gt2cjjwccqs.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xuanzx.com/Article/details/gt2sewcxcrz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.guannengcc.top/Article/details/gt2yulgrfoa.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yonumen.top/Article/details/gt2gvjnlnsg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.andypj.xyz/Article/details/gt2ntuisftx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zycfv.cn/Article/details/gt2amedsbau.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sxryk.cn/Article/details/gt2qgdmcymc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.sxryk.cn/Article/details/gt2yfjinkyd.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cucudq.cn/Article/details/gt2vcxctutq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2yrqepclo.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.kuanghao11.cn/Article/details/gt2fwuthcxt.html

[K04] 读取 JSON 文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2tzvcbzky.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cdnleiting.top/Article/details/gt2fylkdbnl.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shzxlz.cn/Article/details/gt2cmcrqyts.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sxryk.cn/Article/details/gt2aikdxwih.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.9152youxi.cn/Article/details/gt2jeuameqv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xuanzx.com/Article/details/gt2xlwbaroe.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sysykeji.top/Article/details/gt2pnsbrkdm.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhoulong.xyz/Article/details/gt2hyxmqfcj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.redwolf501.top/Article/details/gt2axcpkmtp.html

[K05] 深拷贝对象
来源：http://dali.dianchejie.cn/Article/details/gt2jeejdgjy.html

Py:   copy.deepcopy(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rilheoke.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jlsjyb.cn/Article/details/gt2ggizoiyo.html

JS:   structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gt2rrrcrmwb.html

TS:   structuredClone(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2fbnifgmo.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.snrcjt.cn/Article/details/gt2ljkxxzhk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.tanke756.top/Article/details/gt2fhlvtlex.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.vqdsnc.cn/Article/details/gt2wkbngmot.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xylfe.cn/Article/details/gt2whrwiptc.html

[K06] 解析 URL 查询串
来源：http://dali.aizwys.cn/Article/details/gt2ctybvogb.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jqgufenzy.top/Article/details/gt2qzzdxxtd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2epxkccwe.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.haohaochexian.top/Article/details/gt2jaeaayej.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shzxlz.cn/Article/details/gt2mbyeliob.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.svipenyu.cn/Article/details/gt2dhrzhjee.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.vqdsnc.cn/Article/details/gt2rnblwkkd.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gt2jmefrtoa.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gt2bqzmidrx.html

[K07] 进制转换
来源：http://dali.zycfv.cn/Article/details/gt2zispmmzv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gt2onhkgyez.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ydzc1.top/Article/details/gt2idiawhji.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gt2xcfvcxsk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gt2qujqsaee.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aflfailz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jianghu66.top/Article/details/gt2zcerutrf.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yonumen.top/Article/details/gt2xpbqamfg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gt2rztihdmr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhiwuduotai.top/Article/details/gt2itoywcgj.html

Py:   pickle.dumps(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2vsrioqdp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ivvv.top/Article/details/gt2ujzswamr.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cucudq.cn/Article/details/gt2kamhdfmk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.andypj.xyz/Article/details/gt2ioxasvwu.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.nanxuanxn.top/Article/details/gt2wozwpcqn.html

Go:   encoding/gob
来源：http://dali.jlsjyb.cn/Article/details/gt2apjyvwpq.html

Ruby: Marshal.dump(obj)
来源：http://dali.xinyue.icu/Article/details/gt2ntpxbkii.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shangyingyoupin.top/Article/details/gt2sssolbcr.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2ugerouxu.html

L. 网络请求
来源：http://dali.gaohongyu789.top/Article/details/gt2mycrltjw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nmwvymav.html

[L01] 发送 GET 请求
来源：http://dali.jyoumei.cn/Article/details/gt2fbofzzut.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jlsjyb.cn/Article/details/gt2rscawbur.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yj202588.top/Article/details/gt2hoqncegq.html

JS:   await fetch(url)
来源：http://dali.sweek.top/Article/details/gt2jnjcelsc.html

TS:   await fetch(url)
来源：http://dali.gzhubu.top/Article/details/gt2rdtgwtyk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.chenzaomai.com/Article/details/gt2rptwsrzl.html

Go:   resp, err := http.Get(url)
来源：http://dali.guowangkeji.top/Article/details/gt2crclgvif.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yongpay.top/Article/details/gt2aswybscx.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.guannengcc.top/Article/details/gt2jsazqjvq.html

[L02] 发送 POST JSON
来源：http://dali.yanxiufei.cn/Article/details/gt2kzdmgpfv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ivvv.top/Article/details/gt2vkdumkzs.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhoulong.xyz/Article/details/gt2afktrufr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuetiantiany.cn/Article/details/gt2jexenxwv.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yongpay.top/Article/details/gt2fdsfmcgt.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yongpay.top/Article/details/gt2exjnivke.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.chenzaomai.com/Article/details/gt2juwsmoty.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hysaishi.cn/Article/details/gt2gifknanl.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yj20258.top/Article/details/gt2ceqttyiz.html

[L03] 设置自定义请求头
来源：http://dali.tianlin.xyz/Article/details/gt2njnctwyh.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.snrcjt.cn/Article/details/gt2osdqzxxc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xinyue.icu/Article/details/gt2vsnhlltc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jlsjyb.cn/Article/details/gt2illgesss.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yangfankeji.com/Article/details/gt2sdaolsan.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gotoacloud.top/Article/details/gt2kfpjzdrw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2afvtzgim.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xziqi.cn/Article/details/gt2evmvinau.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jlsjyb.cn/Article/details/gt2xbcuoxyw.html

[L04] 设置超时
来源：http://dali.andypj.xyz/Article/details/gt2pkutoosb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.dianchejie.cn/Article/details/gt2nyqhvfqy.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhongyouzk.top/Article/details/gt2qmgsvpnx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yanxiufei.cn/Article/details/gt2aflbiksz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yongpay.top/Article/details/gt2pijhdnvc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ppjwa.cn/Article/details/gt2fpnljwpp.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vilaslsu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.chenlongwang.top/Article/details/gt2npfljccf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yueranfly.top/Article/details/gt2zmlysyhe.html

[L05] 上传文件（multipart）
来源：http://dali.zycfv.cn/Article/details/gt2xdutpwoy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ydzc1.top/Article/details/gt2oazkfdff.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hnxiangtu.top/Article/details/gt2ihuqpmqz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxuanxn.top/Article/details/gt2byfddoxz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.birdmap.top/Article/details/gt2dsrwvfpb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ppjwa.cn/Article/details/gt2hutmwkyi.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uoxfmdvi.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xylfe.cn/Article/details/gt2dzndjbge.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2krxsnnut.html

[L06] 解析响应为 JSON
来源：http://dali.ehwqpu.com/Article/details/gt2pjstlrgt.html

Py:   resp.json()
来源：http://dali.zhongyouzk.top/Article/details/gt2gfrzxkzm.html

PHP:  json_decode($body, true);
来源：http://dali.sweek.top/Article/details/gt2mjmukcto.html

JS:   await resp.json()
来源：http://dali.zhengqikj.top/Article/details/gt2riqnfbtq.html

TS:   await resp.json()
来源：http://dali.bjfxy.top/Article/details/gt2lqcoqvqk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yvedp.cn/Article/details/gt2jlwvtyfj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.nanxuanxn.top/Article/details/gt2wmvegnrn.html

Ruby: JSON.parse(resp.body)
来源：http://dali.smart0.xyz/Article/details/gt2xbgvtwqq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jyoumei.cn/Article/details/gt2mefuytpu.html

[L07] 处理 HTTP 状态码
来源：http://dali.ehwqpu.com/Article/details/gt2sgriropb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yuxming.cn/Article/details/gt2uljjtqya.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.316326.xyz/Article/details/gt2tqptbxdw.html

JS:   resp.ok;  resp.status
来源：http://dali.jqgufenzy.top/Article/details/gt2ygmzabjm.html

TS:   resp.ok;  resp.status
来源：http://dali.fengsongda.top/Article/details/gt2pjcfwsfs.html

Java: resp.statusCode()
来源：http://dali.yvedp.cn/Article/details/gt2rxxvsbbt.html

Go:   resp.StatusCode
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kdiokgwy.html

Ruby: resp.code.to_i
来源：http://dali.aizwys.cn/Article/details/gt2hgrrgvap.html

C#:   (int)resp.StatusCode
来源：http://dali.yueranfly.top/Article/details/gt2zniihxyu.html

[L08] 并发请求多个地址
来源：http://dali.aibaodan.cn/Article/details/gt2anglxexd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jqgufenzy.top/Article/details/gt2nbnokztn.html

PHP:  curl_multi_init() 系列
来源：http://dali.daxiang520.top/Article/details/gt2byskypyr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yighsirz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xibapyzw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hongshengwenyu.top/Article/details/gt2vtxsycol.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xuanzx.com/Article/details/gt2bpkkjnyy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhoulong.xyz/Article/details/gt2fumnjgym.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ybcxt.top/Article/details/gt2gpyiveha.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2uddcibvx.html

M. 命令行 / 进程 / 环境
来源：http://dali.aizwys.cn/Article/details/gt2iqicvlqm.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2xcnacwka.html

[M01] 读取命令行参数
来源：http://dali.ivvv.top/Article/details/gt2uzubdnbs.html

Py:   sys.argv[1:]
来源：http://dali.ehwqpu.com/Article/details/gt2oywxmwze.html

PHP:  $argv;  $argc;
来源：http://dali.quarkkingdee.top/Article/details/gt2mmikzfxy.html

JS:   process.argv.slice(2)
来源：http://dali.zhoulong.xyz/Article/details/gt2ihblxmkz.html

TS:   process.argv.slice(2)
来源：http://dali.zhixingplan.top/Article/details/gt2vsxoofap.html

Java: args 数组（main 方法参数）
来源：http://dali.tianlin.xyz/Article/details/gt2cxdsiccr.html

Go:   os.Args[1:]
来源：http://dali.ivvv.top/Article/details/gt2suxxwasb.html

Ruby: ARGV
来源：http://dali.daxiang520.top/Article/details/gt2ucpmjouj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenlongwang.top/Article/details/gt2lltiqlzo.html

[M02] 读取环境变量
来源：http://dali.hnxiangtu.top/Article/details/gt2hwyiacue.html

Py:   os.environ.get("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gt2hitynxsw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.kuanghao11.cn/Article/details/gt2qctljpik.html

JS:   process.env.HOME
来源：http://dali.redwolf501.top/Article/details/gt2bdelcxlg.html

TS:   process.env.HOME
来源：http://dali.zhongyouzk.top/Article/details/gt2zrueqjnf.html

Java: System.getenv("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gt2ncjkoher.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.dashuyun.cn/Article/details/gt2dgqzdyky.html

Ruby: ENV["HOME"]
来源：http://dali.iojbl.cn/Article/details/gt2djrvrzhf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xziqi.cn/Article/details/gt2gyzefxdv.html

[M03] 执行外部命令
来源：http://dali.aibaodan.cn/Article/details/gt2hqiipgel.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jlsjyb.cn/Article/details/gt2hkvacngh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.aizwys.cn/Article/details/gt2kktcljsn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gotoacloud.top/Article/details/gt2xfvovwmp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxinkj.top/Article/details/gt2lbmypmli.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hywenlv.cn/Article/details/gt2zhwhfwfh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shuidangran.top/Article/details/gt2porbtkiu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.wangdashe.top/Article/details/gt2hgmqdbrh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.nanxuanxn.top/Article/details/gt2ryvyqayk.html

[M04] 获取当前工作目录
来源：http://dali.cdnleiting.top/Article/details/gt2dnslthqg.html

Py:   os.getcwd()
来源：http://dali.shzxlz.cn/Article/details/gt2apfirsyy.html

PHP:  getcwd();
来源：http://dali.cucudq.cn/Article/details/gt2dffjbuki.html

JS:   process.cwd()
来源：http://dali.316326.xyz/Article/details/gt2zjwghxzd.html

TS:   process.cwd()
来源：http://dali.nanxuanxn.top/Article/details/gt2mtlwqtsh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jqgfzy.top/Article/details/gt2rrevuwxa.html

Go:   os.Getwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vzqiogwf.html

Ruby: Dir.pwd
来源：http://dali.hfpthk.cn/Article/details/gt2ttxgvdwc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sxryk.cn/Article/details/gt2jccwsppf.html

[M05] 设置退出码
来源：http://dali.jqgufenzy.top/Article/details/gt2atowrggs.html

Py:   sys.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nygitsbu.html

PHP:  exit(1);
来源：http://dali.vqdsnc.cn/Article/details/gt2trncudhi.html

JS:   process.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2xlpkatgc.html

TS:   process.exit(1)
来源：http://dali.ybcxt.top/Article/details/gt2keadmwjw.html

Java: System.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gt2eanqkfzm.html

Go:   os.Exit(1)
来源：http://dali.bjfxy.top/Article/details/gt2obrskfri.html

Ruby: exit 1
来源：http://dali.nanxinkj.top/Article/details/gt2dwctrtoe.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2newapxqn.html

[M06] 向标准错误输出
来源：http://dali.svipenyu.cn/Article/details/gt2eligbqtd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wbojftct.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hnxiangtu.top/Article/details/gt2vkmfdybt.html

JS:   console.error("err")
来源：http://dali.tian-w.cn/Article/details/gt2ghgwqmoc.html

TS:   console.error("err")
来源：http://dali.tanke756.top/Article/details/gt2pxxfoxpo.html

Java: System.err.println("err")
来源：http://dali.xuetiantiany.cn/Article/details/gt2jmgditxh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jqgfzy.top/Article/details/gt2uayttrkp.html

Ruby: warn "err"
来源：http://dali.zycfv.cn/Article/details/gt2lapfxqmi.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jyoumei.cn/Article/details/gt2sxihtyda.html

[M07] 判断是否为主入口
来源：http://dali.nwbrower.top/Article/details/gt2pqhjmmmm.html

Py:   if __name__ == "__main__":
来源：http://dali.zhiwuduotai.top/Article/details/gt2hohcarkb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.andypj.xyz/Article/details/gt2bybkvojf.html

JS:   require.main === module
来源：http://dali.bjfxy.top/Article/details/gt2vutihege.html

TS:   require.main === module
来源：http://dali.zhengqikj.top/Article/details/gt2rbjgvxct.html

Java: public static void main(String[] args)
来源：http://dali.xuetiantiany.cn/Article/details/gt2vemqxwdl.html

Go:   func main()
来源：http://dali.yvedp.cn/Article/details/gt2zmgevcls.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.bjfxy.top/Article/details/gt2nmwfxzgi.html

C#:   static void Main(string[] args)
来源：http://dali.c1oappe.top/Article/details/gt2mefcoezt.html

[M08] 获取系统与运行时信息
来源：http://dali.hongshengwenyu.top/Article/details/gt2fdirgghk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.tian-w.cn/Article/details/gt2mcddwbxw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.daria6918.cn/Article/details/gt2pqprqmao.html

JS:   process.platform;  process.version
来源：http://dali.tianlin.xyz/Article/details/gt2xwhyxgbn.html

TS:   process.platform;  process.version
来源：http://dali.xylfe.cn/Article/details/gt2vdmqcmwy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.nanxinkj.top/Article/details/gt2nussijka.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gzhubu.top/Article/details/gt2mzwfnmqg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.birdmap.top/Article/details/gt2dtdqnanz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ydzc1.top/Article/details/gt2uhzzuwsl.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2lvyrgfij.html

N. 数据结构与算法
来源：http://dali.ivvv.top/Article/details/gt2aforflnt.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2xwnlpiyq.html

[N01] 二分查找（有序数组）
来源：http://dali.cdnleiting.top/Article/details/gt2vxruatag.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gt2jhltycng.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhoulong.xyz/Article/details/gt2zmntxqbl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.316326.xyz/Article/details/gt2srllwjhq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hfpthk.cn/Article/details/gt2wfripeto.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zsbggotx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gt2mmcsjnto.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jianghu66.top/Article/details/gt2koiezhsc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gt2svrmoxpt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.daria6918.cn/Article/details/gt2zcptkpad.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhixingplan.top/Article/details/gt2fbxnhjeh.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.havefunace.top/Article/details/gt2mceiwqsw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhoulong.xyz/Article/details/gt2acdktybf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuxming.cn/Article/details/gt2rjastsux.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.guannengcc.top/Article/details/gt2mhzlsxwo.html

Go:   slices.Sort(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wttxiigf.html

Ruby: arr.sort
来源：http://dali.shuidangran.top/Article/details/gt2tewcizdf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jianghu66.top/Article/details/gt2fryvhphy.html

[N03] 快速排序（分治示例）
来源：http://dali.wangshuangyany.cn/Article/details/gt2xewmqiab.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhongyouzk.top/Article/details/gt2sclxszub.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hongshengwenyu.top/Article/details/gt2vcdgjyuh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.bjfxy.top/Article/details/gt2qixhsqxr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ehwqpu.com/Article/details/gt2rqjelvil.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhoulong.xyz/Article/details/gt2nqyfcoxf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.quarkkingdee.top/Article/details/gt2gcktygoh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.snrcjt.cn/Article/details/gt2bubqyeon.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ppjwa.cn/Article/details/gt2pelqzdfx.html

[N04] 斐波那契数列
来源：http://dali.kuanghao11.cn/Article/details/gt2isyenmdi.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.daxiang520.top/Article/details/gt2fnfvrgwp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hysaishi.cn/Article/details/gt2zrmykixw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.snrcjt.cn/Article/details/gt2dbuqxqvg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.fengsongda.top/Article/details/gt2idqtkegl.html


<!-- 参考信息 -->