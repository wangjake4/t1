代发 wailian999

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.guannengcc.top/Article/details/gt2ochoobmj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jianghu66.top/Article/details/gt2zqtgsrlm.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.chenlongwang.top/Article/details/gt2hzznrjsc.html

[J06] 计算两时间之差
来源：http://dali.pycfn.com/Article/details/gt2crgqwwjk.html

Py:   (end - start).total_seconds()
来源：http://dali.shzxlz.cn/Article/details/gt2fuyaqleq.html

PHP:  $end->diff($start)->days;
来源：http://dali.0kj1m.cn/Article/details/gt2joptyinq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ehwqpu.com/Article/details/gt2jqmxbzcd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.aibaodan.cn/Article/details/gt2ijjzsbiv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vphqvbcd.html

Go:   end.Sub(start).Hours()
来源：http://dali.shzxlz.cn/Article/details/gt2jurcefnf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.daria6918.cn/Article/details/gt2jnauvzwv.html

C#:   (end - start).TotalSeconds
来源：http://dali.wangdashe.top/Article/details/gt2zujcvvgz.html

[J07] 比较两个日期
来源：http://dali.sysykeji.top/Article/details/gt2jmusuxkm.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xyvnyzcc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.pycfn.com/Article/details/gt2hqqvqifa.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sufxvd.cn/Article/details/gt2codioqew.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yongpay.top/Article/details/gt2efilecpl.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.daria6918.cn/Article/details/gt2vlsfkqnk.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.guowangkeji.top/Article/details/gt2osziuoky.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qkmkhmqe.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.tian-w.cn/Article/details/gt2btfijntc.html

[J08] 提取年月日与星期
来源：http://dali.quarkkingdee.top/Article/details/gt2yhgjbxhi.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hfpthk.cn/Article/details/gt2jchmhxyo.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yangfankeji.com/Article/details/gt2rhnubicx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xuetiantiany.cn/Article/details/gt2fchmopxy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zycfv.cn/Article/details/gt2cvrohdaj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hysaishi.cn/Article/details/gt2vrrmgwlk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinqigfzy.top/Article/details/gt2zrhexuyh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.havefunace.top/Article/details/gt2jbwkxccc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.guannengcc.top/Article/details/gt2gfxfdbkg.html

[J09] 时区处理
来源：http://dali.vqdsnc.cn/Article/details/gt2orykfpyb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gogol.net.cn/Article/details/gt2amzifffs.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yanxiufei.cn/Article/details/gt2oldpqobr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jlsjyb.cn/Article/details/gt2lxtwlpid.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hywenlv.cn/Article/details/gt2stpkodph.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yanxiufei.cn/Article/details/gt2atcjbwka.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cdnleiting.top/Article/details/gt2fnslhufl.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xuetiantiany.cn/Article/details/gt2putodqcw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zycfv.cn/Article/details/gt2ctgaowmo.html

[J10] 取今天 / 本月第一天
来源：http://dali.smart0.xyz/Article/details/gt2trjokzij.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.aibaodan.cn/Article/details/gt2yxvopzwg.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yuanzhike.top/Article/details/gt2kkbodbmb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.aibaodan.cn/Article/details/gt2fzgkyiao.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ehwqpu.com/Article/details/gt2tlanzitn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2gkbsfwyh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.aibaodan.cn/Article/details/gt2gltdmqsz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.chenlongwang.top/Article/details/gt2nyjjfmep.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.316326.xyz/Article/details/gt2nxjyafbq.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2cfiexhet.html

K. JSON 与序列化
来源：http://dali.haohaochexian.top/Article/details/gt2ylboqmlp.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2stygywfv.html

[K01] 对象转 JSON 字符串
来源：http://dali.yuxming.cn/Article/details/gt2jqftkwdp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinqigfzy.top/Article/details/gt2sqxkiamk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hongshengwenyu.top/Article/details/gt2muxropga.html

JS:   JSON.stringify(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2ittibdwx.html

TS:   JSON.stringify(obj)
来源：http://dali.redwolf501.top/Article/details/gt2ypcsxwat.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yj20258888.top/Article/details/gt2ojnthnxu.html

Go:   json.Marshal(obj)
来源：http://dali.yvedp.cn/Article/details/gt2muhhogji.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ybcxt.top/Article/details/gt2tkjhbsgw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2apatufvo.html

[K02] JSON 字符串转对象
来源：http://dali.dashuyun.cn/Article/details/gt2yypqgrpi.html

Py:   json.loads(s)
来源：http://dali.hammf.cn/Article/details/gt2zitqavar.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jlsjyb.cn/Article/details/gt2dqltlnxj.html

JS:   JSON.parse(s)
来源：http://dali.gogol.net.cn/Article/details/gt2lvzhzqox.html

TS:   JSON.parse(s)
来源：http://dali.haohaochexian.top/Article/details/gt2bgeibyhw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pyfbhufr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2babkaouv.html

Ruby: JSON.parse(s)
来源：http://dali.xuanzx.com/Article/details/gt2haordkxg.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xuanzx.com/Article/details/gt2ynwevrnz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ehwqpu.com/Article/details/gt2nqryxspq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.dianchejie.cn/Article/details/gt2eaznwaen.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258888.top/Article/details/gt2iuswnkow.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jyoumei.cn/Article/details/gt2wdbmwcfd.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.guannengcc.top/Article/details/gt2mfxhpojb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhsbaol.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xylfe.cn/Article/details/gt2rjrimonv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oawtvulk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tanke756.top/Article/details/gt2iviovdlh.html

[K04] 读取 JSON 文件
来源：http://dali.zhongyouzk.top/Article/details/gt2ysqljpzi.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tian-w.cn/Article/details/gt2ydmjaqsh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xinyue.icu/Article/details/gt2wwnhyqzx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258.top/Article/details/gt2zanylrhw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cdnleiting.top/Article/details/gt2hioegklr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.guannengcc.top/Article/details/gt2rzolvsqk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.dianchejie.cn/Article/details/gt2wxvrvadx.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hnqzz.top/Article/details/gt2vhznzfif.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ppjwa.cn/Article/details/gt2fpjnodby.html

[K05] 深拷贝对象
来源：http://dali.feifeiyinyue.top/Article/details/gt2vljbsnqq.html

Py:   copy.deepcopy(obj)
来源：http://dali.yongpay.top/Article/details/gt2zzszavpp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.tianlin.xyz/Article/details/gt2tytpemwj.html

JS:   structuredClone(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2gugepeky.html

TS:   structuredClone(obj)
来源：http://dali.iojbl.cn/Article/details/gt2dovgjlnj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.haohaochexian.top/Article/details/gt2shpxrlhw.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cdnleiting.top/Article/details/gt2lkswafnn.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.wangshuangyany.cn/Article/details/gt2kvggpoum.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shzxlz.cn/Article/details/gt2ntvlqlgq.html

[K06] 解析 URL 查询串
来源：http://dali.yonumen.top/Article/details/gt2nyoybktm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yj20258888.top/Article/details/gt2uowrevry.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.dashuyun.cn/Article/details/gt2mdivrfyl.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cdnleiting.top/Article/details/gt2vywudnqh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cucudq.cn/Article/details/gt2wmvbskzr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.fengsongda.top/Article/details/gt2vjfnjegb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gt2tbvjpans.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.9152youxi.cn/Article/details/gt2mabldypr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ybcxt.top/Article/details/gt2fckjotzo.html

[K07] 进制转换
来源：http://dali.wangshuangyany.cn/Article/details/gt2iuzbetla.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gt2lqqkgmqz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.chenzaomai.com/Article/details/gt2qoxjmlss.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gt2hbzduyje.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gt2nlgtugos.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gt2esvrbpfe.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jqgfzy.top/Article/details/gt2iiuwphwm.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.gogol.net.cn/Article/details/gt2jgfigyqt.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gt2dypqzkrr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sysykeji.top/Article/details/gt2bnymaacx.html

Py:   pickle.dumps(obj)
来源：http://dali.xylfe.cn/Article/details/gt2hulzvjht.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gzhubu.top/Article/details/gt2mtqrlnqr.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.daria6918.cn/Article/details/gt2mkqvxtkc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhongyouzk.top/Article/details/gt2pumgylbu.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cdnleiting.top/Article/details/gt2nijavojg.html

Go:   encoding/gob
来源：http://dali.tianlin.xyz/Article/details/gt2dxpapabh.html

Ruby: Marshal.dump(obj)
来源：http://dali.yongpay.top/Article/details/gt2xqnczkfh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.smart0.xyz/Article/details/gt2kfxmggrh.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ytxzbcom.html

L. 网络请求
来源：http://dali.jlsjyb.cn/Article/details/gt2hgahahtg.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2vzxbenhj.html

[L01] 发送 GET 请求
来源：http://dali.0kj1m.cn/Article/details/gt2gtgtxaof.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zycfv.cn/Article/details/gt2lbwzhnjg.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hnqzz.top/Article/details/gt2rkdwutse.html

JS:   await fetch(url)
来源：http://dali.yonumen.top/Article/details/gt2ikzlliwc.html

TS:   await fetch(url)
来源：http://dali.havefunace.top/Article/details/gt2pazkpjjc.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xuetiantiany.cn/Article/details/gt2nqiasmsr.html

Go:   resp, err := http.Get(url)
来源：http://dali.yuxming.cn/Article/details/gt2axnirdno.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.fengsongda.top/Article/details/gt2kpqdwhka.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ehwqpu.com/Article/details/gt2pikffjra.html

[L02] 发送 POST JSON
来源：http://dali.jqgfzy.top/Article/details/gt2lfuhoxgc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhengqikj.top/Article/details/gt2zjdwvgry.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nmsufaem.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kehtpryn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pengpengdd.cyou/Article/details/gt2vmgrnkjj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hnqzz.top/Article/details/gt2jvkbhthi.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hysaishi.cn/Article/details/gt2vtwezsqv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.svipenyu.cn/Article/details/gt2emvfrriu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhoulong.xyz/Article/details/gt2wcmnrqtz.html

[L03] 设置自定义请求头
来源：http://dali.wangdashe.top/Article/details/gt2nhmqgveu.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2equidled.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hysaishi.cn/Article/details/gt2tdumbnhi.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuxming.cn/Article/details/gt2faxepwae.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daria6918.cn/Article/details/gt2sqszprle.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.dashuyun.cn/Article/details/gt2owxbcuhr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jqgfzy.top/Article/details/gt2fyepyuos.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yonumen.top/Article/details/gt2koiqbjqp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xuanzx.com/Article/details/gt2uykpexld.html

[L04] 设置超时
来源：http://dali.nanxuanxn.top/Article/details/gt2tlnxldwa.html

Py:   requests.get(url, timeout=5)
来源：http://dali.guannengcc.top/Article/details/gt2wdoqiudk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cashguo.top/Article/details/gt2izgqerjh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daxiang520.top/Article/details/gt2oxxswkiz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shzxlz.cn/Article/details/gt2nkjnbfgx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xuetiantiany.cn/Article/details/gt2uztyekzc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shuidangran.top/Article/details/gt2eebhjaxt.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.316326.xyz/Article/details/gt2mmabghyq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hongshengwenyu.top/Article/details/gt2gxmhrznm.html

[L05] 上传文件（multipart）
来源：http://dali.jinqigfzy.top/Article/details/gt2ofgfdmfl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhiwuduotai.top/Article/details/gt2cjvrezhx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hongshengwenyu.top/Article/details/gt2mqggkbxz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.nwbrower.top/Article/details/gt2pmvvjreo.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xinyue.icu/Article/details/gt2emuqhraw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhiwuduotai.top/Article/details/gt2kbkeyxkp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yonumen.top/Article/details/gt2yponundt.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.aizwys.cn/Article/details/gt2gwamwpbu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2dpohykdm.html

[L06] 解析响应为 JSON
来源：http://dali.haohaochexian.top/Article/details/gt2hudqzgqg.html

Py:   resp.json()
来源：http://dali.jqgufenzy.top/Article/details/gt2awgsvvtb.html

PHP:  json_decode($body, true);
来源：http://dali.jqgufenzy.top/Article/details/gt2cqkvfzpy.html

JS:   await resp.json()
来源：http://dali.0kj1m.cn/Article/details/gt2iypzfuwz.html

TS:   await resp.json()
来源：http://dali.quarkkingdee.top/Article/details/gt2ghqpgjka.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hysaishi.cn/Article/details/gt2iuesebjr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qvjzshww.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2svzrxyeo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ehwqpu.com/Article/details/gt2opylprew.html

[L07] 处理 HTTP 状态码
来源：http://dali.smart0.xyz/Article/details/gt2wygotpxr.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhengqikj.top/Article/details/gt2spzebctz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hywenlv.cn/Article/details/gt2zfdcchug.html

JS:   resp.ok;  resp.status
来源：http://dali.yongpay.top/Article/details/gt2oaluxjoy.html

TS:   resp.ok;  resp.status
来源：http://dali.jinqigfzy.top/Article/details/gt2pezefjha.html

Java: resp.statusCode()
来源：http://dali.xuanzx.com/Article/details/gt2ercktzmk.html

Go:   resp.StatusCode
来源：http://dali.9152youxi.cn/Article/details/gt2hfenhsxr.html

Ruby: resp.code.to_i
来源：http://dali.ehwqpu.com/Article/details/gt2qwvylddp.html

C#:   (int)resp.StatusCode
来源：http://dali.hammf.cn/Article/details/gt2kwcsdbhz.html

[L08] 并发请求多个地址
来源：http://dali.tianlin.xyz/Article/details/gt2cywxdlyz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rogrghcb.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sfntltex.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.vqdsnc.cn/Article/details/gt2pkkrtmrk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aizwys.cn/Article/details/gt2urzfpmvj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rglwhouf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.wangshuangyany.cn/Article/details/gt2hrtwpmdi.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.vqdsnc.cn/Article/details/gt2lgtozjbe.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yongpay.top/Article/details/gt2wrthapsi.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2owdmdjhk.html

M. 命令行 / 进程 / 环境
来源：http://dali.dashuyun.cn/Article/details/gt2qbjxjtrz.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2uvnzjmln.html

[M01] 读取命令行参数
来源：http://dali.yj20258888.top/Article/details/gt2rghtrbve.html

Py:   sys.argv[1:]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lissmgeu.html

PHP:  $argv;  $argc;
来源：http://dali.xylfe.cn/Article/details/gt2rksqtprg.html

JS:   process.argv.slice(2)
来源：http://dali.guannengcc.top/Article/details/gt2irufnlfc.html

TS:   process.argv.slice(2)
来源：http://dali.gotoacloud.top/Article/details/gt2hfkcsbjk.html

Java: args 数组（main 方法参数）
来源：http://dali.gotoacloud.top/Article/details/gt2vgffcadu.html

Go:   os.Args[1:]
来源：http://dali.quarkkingdee.top/Article/details/gt2ptegezbj.html

Ruby: ARGV
来源：http://dali.cqqwz.cn/Article/details/gt2fokoxgnk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zycfv.cn/Article/details/gt2dblpqmbj.html

[M02] 读取环境变量
来源：http://dali.gotoacloud.top/Article/details/gt2jjpaftyb.html

Py:   os.environ.get("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gt2moesbptw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xinyue.icu/Article/details/gt2edleayfq.html

JS:   process.env.HOME
来源：http://dali.hysaishi.cn/Article/details/gt2krqclzlv.html

TS:   process.env.HOME
来源：http://dali.hysaishi.cn/Article/details/gt2lbvknkkb.html

Java: System.getenv("HOME")
来源：http://dali.iojbl.cn/Article/details/gt2guuscuww.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.pycfn.com/Article/details/gt2kgprmgig.html

Ruby: ENV["HOME"]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iidnmtoe.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zycfv.cn/Article/details/gt2wsaqmiaz.html

[M03] 执行外部命令
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uwtunctj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jyoumei.cn/Article/details/gt2gysuewje.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yongpay.top/Article/details/gt2womhbttf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kaukfkma.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wcqfqcry.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.wangdashe.top/Article/details/gt2lffizuwl.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.dianchejie.cn/Article/details/gt2cipuymmf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.wangdashe.top/Article/details/gt2etdtpydb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ppjwa.cn/Article/details/gt2zlkkhkrm.html

[M04] 获取当前工作目录
来源：http://dali.0kj1m.cn/Article/details/gt2seldpuxl.html

Py:   os.getcwd()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ycgktvvl.html

PHP:  getcwd();
来源：http://dali.nanxinkj.top/Article/details/gt2xdkmukvv.html

JS:   process.cwd()
来源：http://dali.redwolf501.top/Article/details/gt2mrknsbvr.html

TS:   process.cwd()
来源：http://dali.xuanzx.com/Article/details/gt2ndaqpiuj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sysykeji.top/Article/details/gt2djjxgtku.html

Go:   os.Getwd()
来源：http://dali.xinyue.icu/Article/details/gt2vuoqgzlh.html

Ruby: Dir.pwd
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rxcrnkbp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.chenzaomai.com/Article/details/gt2apmsxgmo.html

[M05] 设置退出码
来源：http://dali.ivvv.top/Article/details/gt2yyribwpa.html

Py:   sys.exit(1)
来源：http://dali.hnqzz.top/Article/details/gt2ljtkgvxm.html

PHP:  exit(1);
来源：http://dali.nanxinkj.top/Article/details/gt2fvphrkvb.html

JS:   process.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2wbqypjlw.html

TS:   process.exit(1)
来源：http://dali.ydzc1.top/Article/details/gt2fsqycilk.html

Java: System.exit(1)
来源：http://dali.c1oappe.top/Article/details/gt2awtnoqom.html

Go:   os.Exit(1)
来源：http://dali.hywenlv.cn/Article/details/gt2okwjwxcn.html

Ruby: exit 1
来源：http://dali.xziqi.cn/Article/details/gt2llzbaeky.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2apdedmrx.html

[M06] 向标准错误输出
来源：http://dali.svipenyu.cn/Article/details/gt2cniexnlw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.snrcjt.cn/Article/details/gt2qnbpxhdv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.fzhhl.top/Article/details/gt2zytficpg.html

JS:   console.error("err")
来源：http://dali.jinqigfzy.top/Article/details/gt2lqbmaklz.html

TS:   console.error("err")
来源：http://dali.feifeiyinyue.top/Article/details/gt2cacqjjqa.html

Java: System.err.println("err")
来源：http://dali.birdmap.top/Article/details/gt2kcmgzcon.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.feifeiyinyue.top/Article/details/gt2omsskplt.html

Ruby: warn "err"
来源：http://dali.cucudq.cn/Article/details/gt2gaaknmpn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.aizwys.cn/Article/details/gt2omtmixxo.html

[M07] 判断是否为主入口
来源：http://dali.xinyue.icu/Article/details/gt2kjrwlleh.html

Py:   if __name__ == "__main__":
来源：http://dali.jqgfzy.top/Article/details/gt2omvpglqu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.chenzaomai.com/Article/details/gt2xqeodndb.html

JS:   require.main === module
来源：http://dali.jqgufenzy.top/Article/details/gt2idsbboud.html

TS:   require.main === module
来源：http://dali.shuidangran.top/Article/details/gt2cpmaxgio.html

Java: public static void main(String[] args)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wmjjbxfp.html

Go:   func main()
来源：http://dali.andypj.xyz/Article/details/gt2yzkowcgv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sysykeji.top/Article/details/gt2tnhdglpv.html

C#:   static void Main(string[] args)
来源：http://dali.yanxiufei.cn/Article/details/gt2gvfsjxkq.html

[M08] 获取系统与运行时信息
来源：http://dali.guannengcc.top/Article/details/gt2fcdeguyx.html

Py:   platform.system();  platform.python_version()
来源：http://dali.wangdashe.top/Article/details/gt2zviwywya.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hysaishi.cn/Article/details/gt2nfnfyter.html

JS:   process.platform;  process.version
来源：http://dali.0kj1m.cn/Article/details/gt2knnmgqfn.html

TS:   process.platform;  process.version
来源：http://dali.haohaochexian.top/Article/details/gt2jlqiruak.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hfpthk.cn/Article/details/gt2hvowvxzj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shuidangran.top/Article/details/gt2mubazlmc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhongyouzk.top/Article/details/gt2rctauasi.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shangyingyoupin.top/Article/details/gt2cxcjzunc.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2zoqugrvy.html

N. 数据结构与算法
来源：http://dali.hongshengwenyu.top/Article/details/gt2zxmuykal.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2yztmvqar.html

[N01] 二分查找（有序数组）
来源：http://dali.yj202588.top/Article/details/gt2fspnwski.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2mslmtoro.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.guowangkeji.top/Article/details/gt2tgtvwbpl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daria6918.cn/Article/details/gt2saoycomu.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuxming.cn/Article/details/gt2lqzqbzcy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gt2kgjumqgc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gt2ctddjxsb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ehwqpu.com/Article/details/gt2lryyzhkq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yvedp.cn/Article/details/gt2hqdejczp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hxjssngh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ybcxt.top/Article/details/gt2wgyxnxdw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinqigfzy.top/Article/details/gt2guhnwdda.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj202588.top/Article/details/gt2flecqhoq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yongpay.top/Article/details/gt2itjysthk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jyoumei.cn/Article/details/gt2mqjerjnx.html

Go:   slices.Sort(arr)
来源：http://dali.hammf.cn/Article/details/gt2ygmgujcx.html

Ruby: arr.sort
来源：http://dali.sufxvd.cn/Article/details/gt2dovpvxhg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cashguo.top/Article/details/gt2jwkimyzc.html

[N03] 快速排序（分治示例）
来源：http://dali.gaohongyu789.top/Article/details/gt2qtpwtrrw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yj20258.top/Article/details/gt2agdgodzj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jqgufenzy.top/Article/details/gt2xrrmefug.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ydzc1.top/Article/details/gt2yelyszll.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shangyingyoupin.top/Article/details/gt2wnrraipu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ivvv.top/Article/details/gt2reitlojh.html


<!-- 参考信息 -->