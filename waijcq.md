代发 wailian999

Java: Duration.between(start, end).toSeconds()
来源：http://dali.9152youxi.cn/Article/details/gt2cqazdqsl.html

Go:   end.Sub(start).Hours()
来源：http://dali.fzhhl.top/Article/details/gt2tgshukva.html

Ruby: end - start                 # 返回秒数
来源：http://dali.aizwys.cn/Article/details/gt2iezbzpuq.html

C#:   (end - start).TotalSeconds
来源：http://dali.guowangkeji.top/Article/details/gt2ucnqrmep.html

[J07] 比较两个日期
来源：http://dali.hysaishi.cn/Article/details/gt2brxzauca.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.316326.xyz/Article/details/gt2kldhedpj.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xylfe.cn/Article/details/gt2zmobsbbq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hysaishi.cn/Article/details/gt2gnbrelsr.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgfzy.top/Article/details/gt2vltvzhta.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yonumen.top/Article/details/gt2jsncyaxu.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qzaarzrb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hysaishi.cn/Article/details/gt2fgznhikr.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.dashuyun.cn/Article/details/gt2qyijkmsg.html

[J08] 提取年月日与星期
来源：http://dali.xylfe.cn/Article/details/gt2wptwbuiw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cashguo.top/Article/details/gt2cuvplyqu.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xziqi.cn/Article/details/gt2rqedumxx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj202588.top/Article/details/gt2engxnezq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.quarkkingdee.top/Article/details/gt2wsszgfwp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.feifeiyinyue.top/Article/details/gt2czqhxteu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhoulong.xyz/Article/details/gt2wlmpoyxy.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.aizwys.cn/Article/details/gt2cgezlrvb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.haohaochexian.top/Article/details/gt2dzszunuo.html

[J09] 时区处理
来源：http://dali.jinqigfzy.top/Article/details/gt2rnnqftfa.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sxryk.cn/Article/details/gt2jzoqpefi.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yj202588.top/Article/details/gt2lttbiexb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.316326.xyz/Article/details/gt2jelfkjsk.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zweadnwb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xziqi.cn/Article/details/gt2exukaahq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.chenlongwang.top/Article/details/gt2toiodpzg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.quarkkingdee.top/Article/details/gt2nfymahri.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.fengsongda.top/Article/details/gt2axcmrdbh.html

[J10] 取今天 / 本月第一天
来源：http://dali.ehwqpu.com/Article/details/gt2hfxuehfy.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhengqikj.top/Article/details/gt2gmixcels.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.daria6918.cn/Article/details/gt2zgwzsfim.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sysykeji.top/Article/details/gt2qsmapbvk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shuidangran.top/Article/details/gt2ilxlkoqi.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gnshwwhx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj202588.top/Article/details/gt2wdrgepxi.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yj20258.top/Article/details/gt2bcsulnax.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zycfv.cn/Article/details/gt2nxhqcuxb.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2agrqfooo.html

K. JSON 与序列化
来源：http://dali.zhixingplan.top/Article/details/gt2kpnhnwwz.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2yatbcunm.html

[K01] 对象转 JSON 字符串
来源：http://dali.hongshengwenyu.top/Article/details/gt2auirdxix.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xinyue.icu/Article/details/gt2hekimrnr.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.snrcjt.cn/Article/details/gt2vvmosdjp.html

JS:   JSON.stringify(obj)
来源：http://dali.redwolf501.top/Article/details/gt2rbbnepkx.html

TS:   JSON.stringify(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2uubtczjv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.meibo888.top/Article/details/gt2dnshfilz.html

Go:   json.Marshal(obj)
来源：http://dali.andypj.xyz/Article/details/gt2eqntefgm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.fzhhl.top/Article/details/gt2ptalmaik.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ydzc1.top/Article/details/gt2hbylqdoj.html

[K02] JSON 字符串转对象
来源：http://dali.zycfv.cn/Article/details/gt2arrfzefn.html

Py:   json.loads(s)
来源：http://dali.9152youxi.cn/Article/details/gt2enqapwvn.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.guowangkeji.top/Article/details/gt2qdtnvpep.html

JS:   JSON.parse(s)
来源：http://dali.ehwqpu.com/Article/details/gt2gneocnyt.html

TS:   JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gt2abzdstwg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhoulong.xyz/Article/details/gt2ppopewpq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.9152youxi.cn/Article/details/gt2easeavik.html

Ruby: JSON.parse(s)
来源：http://dali.dashuyun.cn/Article/details/gt2seroyctm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hnqzz.top/Article/details/gt2susunkap.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gzhubu.top/Article/details/gt2sawwvloi.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.dashuyun.cn/Article/details/gt2nlsqqroh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hnqzz.top/Article/details/gt2jnbgfcmh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj202588.top/Article/details/gt2rpngcdku.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ouvbkvxi.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2sudktddv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ivvv.top/Article/details/gt2xmyjqbtu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cashguo.top/Article/details/gt2cckeghfe.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gotoacloud.top/Article/details/gt2saruovvd.html

[K04] 读取 JSON 文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2mtbknrzp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2iqcroyfd.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sxryk.cn/Article/details/gt2fbryxist.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ppjwa.cn/Article/details/gt2xjtdzyax.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hammf.cn/Article/details/gt2skpzeyur.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fxznmkro.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yueranfly.top/Article/details/gt2woobhrga.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2nckbcstc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.0kj1m.cn/Article/details/gt2kfsneane.html

[K05] 深拷贝对象
来源：http://dali.havefunace.top/Article/details/gt2sdwptczp.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2pdvxmtqp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhengqikj.top/Article/details/gt2ediywvcy.html

JS:   structuredClone(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2hmhgvczi.html

TS:   structuredClone(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zoicdige.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.havefunace.top/Article/details/gt2jedgcahk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gogol.net.cn/Article/details/gt2omjscmsa.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.guannengcc.top/Article/details/gt2ckyqizag.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jyoumei.cn/Article/details/gt2ompcrjmn.html

[K06] 解析 URL 查询串
来源：http://dali.0kj1m.cn/Article/details/gt2foubytrg.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hammf.cn/Article/details/gt2gudfklsq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cucudq.cn/Article/details/gt2otkvncgy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.dashuyun.cn/Article/details/gt2memixvrz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnqzz.top/Article/details/gt2ibounkxq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.iojbl.cn/Article/details/gt2jblvcaba.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.iojbl.cn/Article/details/gt2dgdqcamv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.guannengcc.top/Article/details/gt2qqmghows.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.pycfn.com/Article/details/gt2jafoebei.html

[K07] 进制转换
来源：http://dali.jyoumei.cn/Article/details/gt2crthhtyh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.birdmap.top/Article/details/gt2wmkjddvn.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hammf.cn/Article/details/gt2mhtnmgpr.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gt2dmifwlae.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gt2qdnktcnq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kxoxioyv.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hfpthk.cn/Article/details/gt2ocreirxy.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.chenlongwang.top/Article/details/gt2zprnowhm.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jscehied.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.smart0.xyz/Article/details/gt2qsocqrza.html

Py:   pickle.dumps(obj)
来源：http://dali.yonumen.top/Article/details/gt2jpdwevbn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cucudq.cn/Article/details/gt2swyheyen.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hongshengwenyu.top/Article/details/gt2kxnwqxus.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.chenjidiqi.icu/Article/details/gt2hehnzvme.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jqgfzy.top/Article/details/gt2vuizpdlk.html

Go:   encoding/gob
来源：http://dali.yj202588.top/Article/details/gt2ahyuhxlj.html

Ruby: Marshal.dump(obj)
来源：http://dali.sweek.top/Article/details/gt2pvooargy.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhoulong.xyz/Article/details/gt2ouvavtev.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2bnqnfzkx.html

L. 网络请求
来源：http://dali.jlsjyb.cn/Article/details/gt2dhllxtiz.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pnfaftar.html

[L01] 发送 GET 请求
来源：http://dali.316326.xyz/Article/details/gt2ydykbkgb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jqgfzy.top/Article/details/gt2iuohkcgu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gotoacloud.top/Article/details/gt2mhddgxdf.html

JS:   await fetch(url)
来源：http://dali.jqgufenzy.top/Article/details/gt2fsvskawj.html

TS:   await fetch(url)
来源：http://dali.yueranfly.top/Article/details/gt2ybbbfhir.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ydzc1.top/Article/details/gt2issdcrtp.html

Go:   resp, err := http.Get(url)
来源：http://dali.yj202588.top/Article/details/gt2aznejqph.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.andypj.xyz/Article/details/gt2glzghzrg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.feifeiyinyue.top/Article/details/gt2aztuyjwn.html

[L02] 发送 POST JSON
来源：http://dali.hfpthk.cn/Article/details/gt2sxzyyhhi.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.tanke756.top/Article/details/gt2eixdxryq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yj20258888.top/Article/details/gt2houvdxsn.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenjidiqi.icu/Article/details/gt2yjapzibi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.c1oappe.top/Article/details/gt2vamqpeah.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.pycfn.com/Article/details/gt2olvyqocc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yanxiufei.cn/Article/details/gt2kblbsfrs.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tgmrpazk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.nwbrower.top/Article/details/gt2sdvifyak.html

[L03] 设置自定义请求头
来源：http://dali.mhx1999.top/Article/details/gt2bwstbbej.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.redwolf501.top/Article/details/gt2ytwtpoqx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.fzhhl.top/Article/details/gt2tavuneif.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.andypj.xyz/Article/details/gt2vdhbnkcl.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnxiangtu.top/Article/details/gt2ezhntcwb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.redwolf501.top/Article/details/gt2qeswlmhy.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zfzagjyq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.daria6918.cn/Article/details/gt2whfuksbq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhengqikj.top/Article/details/gt2gfsxwgsz.html

[L04] 设置超时
来源：http://dali.jqgufenzy.top/Article/details/gt2yxorubjj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cdnleiting.top/Article/details/gt2fqsggcmx.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hywenlv.cn/Article/details/gt2egpbdqjy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxinkj.top/Article/details/gt2coddkjnd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pengpengdd.cyou/Article/details/gt2qodkvxiu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.haohaochexian.top/Article/details/gt2zfkuhntz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yuxming.cn/Article/details/gt2vmalbtnf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sufxvd.cn/Article/details/gt2hiohgbyw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yvedp.cn/Article/details/gt2flimicpg.html

[L05] 上传文件（multipart）
来源：http://dali.birdmap.top/Article/details/gt2otfdvwhp.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hongshengwenyu.top/Article/details/gt2obmnptif.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shuidangran.top/Article/details/gt2ankadfjx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.guannengcc.top/Article/details/gt2oklzbpzc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hfsxnhen.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2kvselulr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xuanzx.com/Article/details/gt2zgepfivf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.aizwys.cn/Article/details/gt2ohwvownu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cheryme.top/Article/details/gt2hxofavnn.html

[L06] 解析响应为 JSON
来源：http://dali.sxryk.cn/Article/details/gt2cuuukxyg.html

Py:   resp.json()
来源：http://dali.redwolf501.top/Article/details/gt2mvswjurk.html

PHP:  json_decode($body, true);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oqpdjyri.html

JS:   await resp.json()
来源：http://dali.ehwqpu.com/Article/details/gt2ayhhcofm.html

TS:   await resp.json()
来源：http://dali.gzhubu.top/Article/details/gt2hcmuzznb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hganijdh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.guannengcc.top/Article/details/gt2mudqffjy.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yuxming.cn/Article/details/gt2unczxetc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jiagoushi.top/Article/details/gt2gquswckt.html

[L07] 处理 HTTP 状态码
来源：http://dali.yuanzhike.top/Article/details/gt2vzjvxxhu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.dashuyun.cn/Article/details/gt2aheqoxvp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.c1oappe.top/Article/details/gt2jphskhbk.html

JS:   resp.ok;  resp.status
来源：http://dali.yongpay.top/Article/details/gt2dxhlttqw.html

TS:   resp.ok;  resp.status
来源：http://dali.c1oappe.top/Article/details/gt2hpamusfw.html

Java: resp.statusCode()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nfnkchuf.html

Go:   resp.StatusCode
来源：http://dali.ivvv.top/Article/details/gt2reygzjgm.html

Ruby: resp.code.to_i
来源：http://dali.gotoacloud.top/Article/details/gt2vdpnubpn.html

C#:   (int)resp.StatusCode
来源：http://dali.shangyingyoupin.top/Article/details/gt2oftfnlxe.html

[L08] 并发请求多个地址
来源：http://dali.nwbrower.top/Article/details/gt2gxhggavi.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jinqigufen.top/Article/details/gt2frcwpasy.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wsbunjpg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yueranfly.top/Article/details/gt2kyegsqrm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cheryme.top/Article/details/gt2ugrrpopl.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.316326.xyz/Article/details/gt2hmdjxuoe.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ydzc1.top/Article/details/gt2klanmlvu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hysaishi.cn/Article/details/gt2sguqoget.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ivvv.top/Article/details/gt2xcjuzovb.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2jmhjawjg.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinqigfzy.top/Article/details/gt2dvlevmvg.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2rlgkryrg.html

[M01] 读取命令行参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nvlbsglc.html

Py:   sys.argv[1:]
来源：http://dali.cashguo.top/Article/details/gt2tlcvvixu.html

PHP:  $argv;  $argc;
来源：http://dali.hywenlv.cn/Article/details/gt2asnwufox.html

JS:   process.argv.slice(2)
来源：http://dali.xziqi.cn/Article/details/gt2nzwnruya.html

TS:   process.argv.slice(2)
来源：http://dali.snrcjt.cn/Article/details/gt2aowehwzj.html

Java: args 数组（main 方法参数）
来源：http://dali.ivvv.top/Article/details/gt2bbgatevz.html

Go:   os.Args[1:]
来源：http://dali.gzhubu.top/Article/details/gt2ovbgluci.html

Ruby: ARGV
来源：http://dali.sweek.top/Article/details/gt2hdyijbrf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.iojbl.cn/Article/details/gt2xmkssxry.html

[M02] 读取环境变量
来源：http://dali.cdnleiting.top/Article/details/gt2ifijqqwi.html

Py:   os.environ.get("HOME")
来源：http://dali.yj20258.top/Article/details/gt2pawrndul.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.birdmap.top/Article/details/gt2pglfluuz.html

JS:   process.env.HOME
来源：http://dali.xuetiantiany.cn/Article/details/gt2cijmanba.html

TS:   process.env.HOME
来源：http://dali.fzhhl.top/Article/details/gt2rsjmkwbq.html

Java: System.getenv("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gt2teayorwp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.guowangkeji.top/Article/details/gt2wreyoxhu.html

Ruby: ENV["HOME"]
来源：http://dali.dashuyun.cn/Article/details/gt2xloqrytu.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinqigufen.top/Article/details/gt2nvwqdvfq.html

[M03] 执行外部命令
来源：http://dali.guannengcc.top/Article/details/gt2lmmvrpbk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.aizwys.cn/Article/details/gt2mppupxfx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yuanzhike.top/Article/details/gt2dtfundsi.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.guowangkeji.top/Article/details/gt2oavrgemg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.316326.xyz/Article/details/gt2eupvuqki.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.haohaochexian.top/Article/details/gt2ookoqbdv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.svipenyu.cn/Article/details/gt2ljzsfyjt.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yongpay.top/Article/details/gt2yokngzne.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yanxiufei.cn/Article/details/gt2ntsfcxas.html

[M04] 获取当前工作目录
来源：http://dali.jiagoushi.top/Article/details/gt2vgllxdwp.html

Py:   os.getcwd()
来源：http://dali.cucudq.cn/Article/details/gt2dukxyvum.html

PHP:  getcwd();
来源：http://dali.pycfn.com/Article/details/gt2vgmesyzs.html

JS:   process.cwd()
来源：http://dali.aibaodan.cn/Article/details/gt2geidpjhv.html

TS:   process.cwd()
来源：http://dali.hnqzz.top/Article/details/gt2wprjpyeb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xziqi.cn/Article/details/gt2jtntfgcm.html

Go:   os.Getwd()
来源：http://dali.andypj.xyz/Article/details/gt2gxufykib.html

Ruby: Dir.pwd
来源：http://dali.zhongyouzk.top/Article/details/gt2rweporoe.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yuanzhike.top/Article/details/gt2krbfvpqx.html

[M05] 设置退出码
来源：http://dali.tianlin.xyz/Article/details/gt2qjcpdngt.html

Py:   sys.exit(1)
来源：http://dali.jqgfzy.top/Article/details/gt2njsgfumf.html

PHP:  exit(1);
来源：http://dali.zhixingplan.top/Article/details/gt2alkzdtzv.html

JS:   process.exit(1)
来源：http://dali.aizwys.cn/Article/details/gt2rwibrxaq.html

TS:   process.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gt2ajxhkzyj.html

Java: System.exit(1)
来源：http://dali.xziqi.cn/Article/details/gt2dduuqlml.html

Go:   os.Exit(1)
来源：http://dali.xinyue.icu/Article/details/gt2soybqhfr.html

Ruby: exit 1
来源：http://dali.sxryk.cn/Article/details/gt2uasrlyqu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj20258888.top/Article/details/gt2ctevpobw.html

[M06] 向标准错误输出
来源：http://dali.hysaishi.cn/Article/details/gt2rzvqvhnb.html

Py:   print("err", file=sys.stderr)
来源：http://dali.meibo888.top/Article/details/gt2dnohfmfl.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shuidangran.top/Article/details/gt2egxiprbv.html

JS:   console.error("err")
来源：http://dali.yj20258888.top/Article/details/gt2lgszeitl.html

TS:   console.error("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2izaticqe.html

Java: System.err.println("err")
来源：http://dali.jianghu66.top/Article/details/gt2lqlnwfnq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hongshengwenyu.top/Article/details/gt2lyhhwknb.html

Ruby: warn "err"
来源：http://dali.smart0.xyz/Article/details/gt2ezsdtzph.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ppjwa.cn/Article/details/gt2yuxvjdms.html

[M07] 判断是否为主入口
来源：http://dali.zhixingplan.top/Article/details/gt2rjatjaxs.html

Py:   if __name__ == "__main__":
来源：http://dali.daxiang520.top/Article/details/gt2ajblkqco.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yangfankeji.com/Article/details/gt2nlksduvq.html

JS:   require.main === module
来源：http://dali.c1oappe.top/Article/details/gt2uwrrqnkk.html

TS:   require.main === module
来源：http://dali.gzhubu.top/Article/details/gt2chzbtbdo.html

Java: public static void main(String[] args)
来源：http://dali.zycfv.cn/Article/details/gt2fdwsptso.html

Go:   func main()
来源：http://dali.bjfxy.top/Article/details/gt2vhidebms.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.guannengcc.top/Article/details/gt2qvxqbvyq.html

C#:   static void Main(string[] args)
来源：http://dali.hnqzz.top/Article/details/gt2jcnddexp.html

[M08] 获取系统与运行时信息
来源：http://dali.aibaodan.cn/Article/details/gt2jpuctutv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ivvv.top/Article/details/gt2yzycmxju.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shuidangran.top/Article/details/gt2uzvffhug.html

JS:   process.platform;  process.version
来源：http://dali.mhx1999.top/Article/details/gt2lgoeulrs.html

TS:   process.platform;  process.version
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mqonlnrd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hongshengwenyu.top/Article/details/gt2vyqgbwwb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gzhubu.top/Article/details/gt2kfizrgib.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zkstllze.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cheryme.top/Article/details/gt2jhffxqpr.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2iravulcv.html

N. 数据结构与算法
来源：http://dali.jinqigufen.top/Article/details/gt2pwcywudf.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2xglkrjib.html

[N01] 二分查找（有序数组）
来源：http://dali.jiagoushi.top/Article/details/gt2fljmpajg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tsqyqccc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.smart0.xyz/Article/details/gt2ojfxctzr.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ydzc1.top/Article/details/gt2anuzvndj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhixingplan.top/Article/details/gt2mgfkacvx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gt2phyytrxd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gt2xvecswmh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.havefunace.top/Article/details/gt2fjnqsphu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gt2zqkqmgam.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yonumen.top/Article/details/gt2ccgdodjn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fzhhl.top/Article/details/gt2lchruoog.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cashguo.top/Article/details/gt2ssojbtot.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ytyxodzo.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jqgufenzy.top/Article/details/gt2icxelayz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2awcvytjh.html

Go:   slices.Sort(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2puquqxum.html

Ruby: arr.sort
来源：http://dali.yonumen.top/Article/details/gt2nykyonge.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cheryme.top/Article/details/gt2pzpvetns.html

[N03] 快速排序（分治示例）
来源：http://dali.sufxvd.cn/Article/details/gt2hpudnzqw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.smart0.xyz/Article/details/gt2cerbzulp.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gaohongyu789.top/Article/details/gt2iblrmvdl.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zycfv.cn/Article/details/gt2evbsxwxq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dianchejie.cn/Article/details/gt2hlsqwboh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yj20258888.top/Article/details/gt2xlutwqdz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cheryme.top/Article/details/gt2qsplgnmt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hfpthk.cn/Article/details/gt2zpatcvig.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.tanke756.top/Article/details/gt2omvrbwub.html

[N04] 斐波那契数列
来源：http://dali.sufxvd.cn/Article/details/gt2cegdalgd.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.birdmap.top/Article/details/gt2yehrxcwm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xziqi.cn/Article/details/gt2eyjbpkcm.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pycfn.com/Article/details/gt2xukpgxuj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ybcxt.top/Article/details/gt2rbojuvvm.html


<!-- 参考信息 -->