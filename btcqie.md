代发 wailian999

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxhkwsolc.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jinghuilouyu.cn/Article/details/gtneynjzob.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtetaltvts.html

[J06] 计算两时间之差
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtizxxaawi.html

Py:   (end - start).total_seconds()
来源：http://dali.zycfv.cn/Article/details/gtpwxnxton.html

PHP:  $end->diff($start)->days;
来源：http://dali.pengpengdd.cyou/Article/details/gtyxsjdznl.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj202588.top/Article/details/gtkngrtdko.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpsvvbbcs.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.aizwys.cn/Article/details/gtdfblqocg.html

Go:   end.Sub(start).Hours()
来源：http://dali.cucudq.cn/Article/details/gtmgscnwbq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jqgufenzy.top/Article/details/gtwqezirxq.html

C#:   (end - start).TotalSeconds
来源：http://dali.ehwqpu.com/Article/details/gtknswmkdb.html

[J07] 比较两个日期
来源：http://dali.haohaochexian.top/Article/details/gtendzqavc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gtohzdjhkv.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhengqikj.top/Article/details/gtddskjybo.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.kuanghao11.cn/Article/details/gtzgxmnhuv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.guowangkeji.top/Article/details/gtasieooly.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.dianchejie.cn/Article/details/gtoxvksfvd.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hnxiangtu.top/Article/details/gtspfkrmji.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gtdwvzokwt.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cashguo.top/Article/details/gtlsuicmgz.html

[J08] 提取年月日与星期
来源：http://dali.kuanghao11.cn/Article/details/gtdizgmxjy.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gzhubu.top/Article/details/gtiiofsisk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.andypj.xyz/Article/details/gtjpkqfjvk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.bjfxy.top/Article/details/gtoblnxozq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ehwqpu.com/Article/details/gtkvbxvoly.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.tianlin.xyz/Article/details/gtplhfumot.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hywenlv.cn/Article/details/gtfrsjywwz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenjidiqi.icu/Article/details/gtuwkxneyo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhijiandao.cn/Article/details/gttgvarxqt.html

[J09] 时区处理
来源：http://dali.yj202588.top/Article/details/gtpojbizmt.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jiagoushi.top/Article/details/gtasaafoiz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gzhubu.top/Article/details/gtktqyumfc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuanzhike.top/Article/details/gtxellldqi.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sufxvd.cn/Article/details/gtzsmtflba.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yonumen.top/Article/details/gtwiwqerko.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xuetiantiany.cn/Article/details/gtrquxiwrt.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gogol.net.cn/Article/details/gtdcajxykg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.nanxinkj.top/Article/details/gtzdchjosa.html

[J10] 取今天 / 本月第一天
来源：http://dali.shangyingyoupin.top/Article/details/gtbuovwkot.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinqigfzy.top/Article/details/gtqiozmnae.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hysaishi.cn/Article/details/gtpbllojvo.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yanxiufei.cn/Article/details/gtpjmemuwx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shzxlz.cn/Article/details/gtxwzyoruu.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zycfv.cn/Article/details/gtxrqhbbey.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.aizwys.cn/Article/details/gtoxbtrgay.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.havefunace.top/Article/details/gtkxkktgba.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtzyqnugdm.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtisznqcrk.html

K. JSON 与序列化
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrkwboyhx.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gttoepqbqm.html

[K01] 对象转 JSON 字符串
来源：http://dali.iojbl.cn/Article/details/gtnoeoxkrq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.tanke756.top/Article/details/gtluqoyijv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shzxlz.cn/Article/details/gttxsfvknu.html

JS:   JSON.stringify(obj)
来源：http://dali.fzhhl.top/Article/details/gtlwznrzcd.html

TS:   JSON.stringify(obj)
来源：http://dali.zhengqikj.top/Article/details/gtllbirycu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yuxming.cn/Article/details/gtqbvbzfvn.html

Go:   json.Marshal(obj)
来源：http://dali.gotoacloud.top/Article/details/gtwkhwqgyv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.birdmap.top/Article/details/gtcjyauxlw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yongpay.top/Article/details/gthgftibmr.html

[K02] JSON 字符串转对象
来源：http://dali.jyoumei.cn/Article/details/gtgspaubmz.html

Py:   json.loads(s)
来源：http://dali.cashguo.top/Article/details/gtdfrwndhq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hongshengwenyu.top/Article/details/gthkvdchfi.html

JS:   JSON.parse(s)
来源：http://dali.yvedp.cn/Article/details/gtyogiwlow.html

TS:   JSON.parse(s)
来源：http://dali.cucudq.cn/Article/details/gtvukfjfcd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.aizwys.cn/Article/details/gtusbqmqpk.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.tian-w.cn/Article/details/gtwdtrbosl.html

Ruby: JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyxuasrnd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ehwqpu.com/Article/details/gtfvqglmtq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.kuanghao11.cn/Article/details/gtjzpkarac.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gogol.net.cn/Article/details/gtmmwgwakz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.dashuyun.cn/Article/details/gtsigwuses.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gtxmgbemer.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gtkyjziatq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtznwusvdt.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.iojbl.cn/Article/details/gtmniyvvzh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtiebffqkl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjediemap.html

[K04] 读取 JSON 文件
来源：http://dali.hywenlv.cn/Article/details/gtqiehabse.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jyoumei.cn/Article/details/gtypgrhfls.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yangfankeji.com/Article/details/gtxfmoldlc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.316326.xyz/Article/details/gtcxfgljax.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.meibo888.top/Article/details/gtolmlnsgh.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cdnleiting.top/Article/details/gtoyofjhwu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cdnleiting.top/Article/details/gtxgbptzcy.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.svipenyu.cn/Article/details/gtcvltujja.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cqqwz.cn/Article/details/gtmwymztcz.html

[K05] 深拷贝对象
来源：http://dali.jqgufenzy.top/Article/details/gtqzaynuii.html

Py:   copy.deepcopy(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtzffgtmiw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zycfv.cn/Article/details/gtxcstriax.html

JS:   structuredClone(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtxcakrjlr.html

TS:   structuredClone(obj)
来源：http://dali.jqgfzy.top/Article/details/gtrxbqtmfh.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.nwbrower.top/Article/details/gtqbykzmhn.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yonumen.top/Article/details/gteahrrozb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbskjjtte.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.aizwys.cn/Article/details/gtnbpjbdvw.html

[K06] 解析 URL 查询串
来源：http://dali.shzxlz.cn/Article/details/gtvrffhbxj.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yonumen.top/Article/details/gtuqfjyssu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhixingplan.top/Article/details/gtikzvhgcz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.316326.xyz/Article/details/gtekouecrw.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xylfe.cn/Article/details/gtqulzdsrh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.guannengcc.top/Article/details/gtsifopcqe.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gtuouwzpkq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gtjrnnxoff.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gtfsfshtoq.html

[K07] 进制转换
来源：http://dali.sysykeji.top/Article/details/gtcphflrhr.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtklybhvgq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnywfvuga.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gtywtrgkgw.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gtckxvscei.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gtguvtjkmu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yj20258.top/Article/details/gttvmzsniv.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.0kj1m.cn/Article/details/gtenlbptdx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gtzeilnttl.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yuanzhike.top/Article/details/gteoktkdcl.html

Py:   pickle.dumps(obj)
来源：http://dali.jqgfzy.top/Article/details/gtaljtnzbf.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.dianchejie.cn/Article/details/gttgyxrnes.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cashguo.top/Article/details/gtpjawapgh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yueranfly.top/Article/details/gtzbuitgyp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hnxiangtu.top/Article/details/gtrnelejje.html

Go:   encoding/gob
来源：http://dali.9152youxi.cn/Article/details/gtqlfqlicv.html

Ruby: Marshal.dump(obj)
来源：http://dali.snrcjt.cn/Article/details/gtddbyxwxu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gotoacloud.top/Article/details/gtqakxmmdu.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtslxbdpul.html

L. 网络请求
来源：http://dali.sweek.top/Article/details/gtmddcgkic.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtzyltvjfx.html

[L01] 发送 GET 请求
来源：http://dali.jinqigufen.top/Article/details/gtrhpufcfu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ivvv.top/Article/details/gtjqqoxgcq.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhengqikj.top/Article/details/gtuygzpfpx.html

JS:   await fetch(url)
来源：http://dali.yueranfly.top/Article/details/gtmojjqzow.html

TS:   await fetch(url)
来源：http://dali.aizwys.cn/Article/details/gtkyyoioqt.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.mhx1999.top/Article/details/gtgsxujjfu.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gtprexxlen.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.tian-w.cn/Article/details/gtcuzueyqn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zdqjudy.top/Article/details/gtcxyseuat.html

[L02] 发送 POST JSON
来源：http://dali.shuidangran.top/Article/details/gtactefoce.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hammf.cn/Article/details/gtcncnkuhd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.havefunace.top/Article/details/gthduzmqij.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tanke756.top/Article/details/gtqxvahpbh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.daria6918.cn/Article/details/gtojcnpitk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.fengsongda.top/Article/details/gtatldouih.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.mhx1999.top/Article/details/gtizpotyew.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yuanzhike.top/Article/details/gtmghoavpm.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hfpthk.cn/Article/details/gtsmkejsxm.html

[L03] 设置自定义请求头
来源：http://dali.cucudq.cn/Article/details/gtcijxcjnn.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhongyouzk.top/Article/details/gtmulklblz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuxyvepkv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.dianchejie.cn/Article/details/gtxwicucjv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.meibo888.top/Article/details/gtxmjeryyz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.chenjidiqi.icu/Article/details/gtmvmtqlwa.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hysaishi.cn/Article/details/gtygtscrvg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zycfv.cn/Article/details/gtxtfiiwwp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gaohongyu789.top/Article/details/gtzgpborss.html

[L04] 设置超时
来源：http://dali.snrcjt.cn/Article/details/gtykfmdpcj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.aibaodan.cn/Article/details/gtybqienvt.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgxlvmhhr.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gzhubu.top/Article/details/gttnathmzt.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtktywkkcf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.quarkkingdee.top/Article/details/gtblvqhjix.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ivvv.top/Article/details/gtrvarewhc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.kuanghao11.cn/Article/details/gtsmsbyccn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zycfv.cn/Article/details/gtvvluwijy.html

[L05] 上传文件（multipart）
来源：http://dali.zhongyouzk.top/Article/details/gtrcqpxbge.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zycfv.cn/Article/details/gtvabbixmi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sysykeji.top/Article/details/gtuiwveony.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.birdmap.top/Article/details/gtgmivaijw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnqzz.top/Article/details/gtyronkksu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hongshengwenyu.top/Article/details/gtsipenqni.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.svipenyu.cn/Article/details/gtjsicypng.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.daxiang520.top/Article/details/gtpehesczt.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zycfv.cn/Article/details/gtxsnilrbp.html

[L06] 解析响应为 JSON
来源：http://dali.hywenlv.cn/Article/details/gtfgpkswgi.html

Py:   resp.json()
来源：http://dali.hywenlv.cn/Article/details/gtsiraosjx.html

PHP:  json_decode($body, true);
来源：http://dali.daxiang520.top/Article/details/gtbovfrkgv.html

JS:   await resp.json()
来源：http://dali.jyoumei.cn/Article/details/gtgtxwjswl.html

TS:   await resp.json()
来源：http://dali.jyoumei.cn/Article/details/gtklhghjka.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cdnleiting.top/Article/details/gthoxqjfin.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.birdmap.top/Article/details/gtsamvscdh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmfkadtut.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hywenlv.cn/Article/details/gtinvnhujv.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinqigufen.top/Article/details/gtwvqijslg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ydzc1.top/Article/details/gtdliamhrw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.daria6918.cn/Article/details/gtxqaaitzs.html

JS:   resp.ok;  resp.status
来源：http://dali.kuanghao11.cn/Article/details/gtzqfswqhv.html

TS:   resp.ok;  resp.status
来源：http://dali.dashuyun.cn/Article/details/gtgzgyedru.html

Java: resp.statusCode()
来源：http://dali.xuanzx.com/Article/details/gtnvacxooh.html

Go:   resp.StatusCode
来源：http://dali.svipenyu.cn/Article/details/gtkftvfzlx.html

Ruby: resp.code.to_i
来源：http://dali.nanxinkj.top/Article/details/gtnxtwuwyf.html

C#:   (int)resp.StatusCode
来源：http://dali.wangshuangyany.cn/Article/details/gtbotuubcg.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gtefkbskqh.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ydzc1.top/Article/details/gtptunzbux.html

PHP:  curl_multi_init() 系列
来源：http://dali.cashguo.top/Article/details/gtqytsmxrm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtveptumyh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shuidangran.top/Article/details/gtpbfgfxej.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.dianchejie.cn/Article/details/gtqeufwyml.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.vqdsnc.cn/Article/details/gtlnuwxgal.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jqgufenzy.top/Article/details/gtmtagsusb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hnxiangtu.top/Article/details/gticvzopoi.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtgzlrmphc.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmipbdoev.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtakumdddt.html

[M01] 读取命令行参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gthiyefmcy.html

Py:   sys.argv[1:]
来源：http://dali.zhoulong.xyz/Article/details/gtjcczxwgx.html

PHP:  $argv;  $argc;
来源：http://dali.yj20258888.top/Article/details/gttfjghtss.html

JS:   process.argv.slice(2)
来源：http://dali.yuanzhike.top/Article/details/gtirvcotvj.html

TS:   process.argv.slice(2)
来源：http://dali.feifeiyinyue.top/Article/details/gtwkxiquyi.html

Java: args 数组（main 方法参数）
来源：http://dali.jinghuilouyu.cn/Article/details/gtjzcpofkh.html

Go:   os.Args[1:]
来源：http://dali.sweek.top/Article/details/gtfwwprbpt.html

Ruby: ARGV
来源：http://dali.sufxvd.cn/Article/details/gtlxvlncpa.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtglssqgci.html

[M02] 读取环境变量
来源：http://dali.jinqigufen.top/Article/details/gticodbadl.html

Py:   os.environ.get("HOME")
来源：http://dali.c1oappe.top/Article/details/gtrjxvccms.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yongpay.top/Article/details/gtdebowtkh.html

JS:   process.env.HOME
来源：http://dali.jinqigfzy.top/Article/details/gtenoojayr.html

TS:   process.env.HOME
来源：http://dali.xuetiantiany.cn/Article/details/gtanuuirii.html

Java: System.getenv("HOME")
来源：http://dali.aizwys.cn/Article/details/gtufbjecdp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ppjwa.cn/Article/details/gtmtjemgst.html

Ruby: ENV["HOME"]
来源：http://dali.sxryk.cn/Article/details/gtansdrkdo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.aibaodan.cn/Article/details/gtrlrygito.html

[M03] 执行外部命令
来源：http://dali.jlsjyb.cn/Article/details/gttvgtztmj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yongpay.top/Article/details/gtddakdepn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.daxiang520.top/Article/details/gtzasxoeat.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.guannengcc.top/Article/details/gtfamgogdg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenlongwang.top/Article/details/gtbbbfixup.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.pycfn.com/Article/details/gtgrtbictp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.dianchejie.cn/Article/details/gtgbmbeguc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.0kj1m.cn/Article/details/gthwitfqon.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xziqi.cn/Article/details/gtjxxuknmq.html

[M04] 获取当前工作目录
来源：http://dali.andypj.xyz/Article/details/gtqpveoqbh.html

Py:   os.getcwd()
来源：http://dali.cqqwz.cn/Article/details/gtkwcreade.html

PHP:  getcwd();
来源：http://dali.xylfe.cn/Article/details/gtxdioqxmi.html

JS:   process.cwd()
来源：http://dali.hfpthk.cn/Article/details/gtthzluvao.html

TS:   process.cwd()
来源：http://dali.wangshuangyany.cn/Article/details/gteqodnrvf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.birdmap.top/Article/details/gtosqvklbt.html

Go:   os.Getwd()
来源：http://dali.tanke756.top/Article/details/gtfuzgfdvw.html

Ruby: Dir.pwd
来源：http://dali.yj202588.top/Article/details/gtgpkluvba.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sysykeji.top/Article/details/gtnrkoakle.html

[M05] 设置退出码
来源：http://dali.yueranfly.top/Article/details/gtyyxbyvdz.html

Py:   sys.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gtoisouxbg.html

PHP:  exit(1);
来源：http://dali.yuanzhike.top/Article/details/gtbchxolno.html

JS:   process.exit(1)
来源：http://dali.xinyue.icu/Article/details/gttaktywym.html

TS:   process.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gtwhbbsjmg.html

Java: System.exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtiuzkpzrd.html

Go:   os.Exit(1)
来源：http://dali.ybcxt.top/Article/details/gtrkoqitgu.html

Ruby: exit 1
来源：http://dali.ehwqpu.com/Article/details/gtkhwgmvpm.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jqgfzy.top/Article/details/gtkqykqpaz.html

[M06] 向标准错误输出
来源：http://dali.hnqzz.top/Article/details/gthhsjqeyf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.daria6918.cn/Article/details/gtukrnvuki.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.snrcjt.cn/Article/details/gtjvqvtxsj.html

JS:   console.error("err")
来源：http://dali.bjfxy.top/Article/details/gtrvwzuwkr.html

TS:   console.error("err")
来源：http://dali.gaohongyu789.top/Article/details/gtaeimqcuv.html

Java: System.err.println("err")
来源：http://dali.jqgfzy.top/Article/details/gtfrqqypop.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sweek.top/Article/details/gtejriqosn.html

Ruby: warn "err"
来源：http://dali.vqdsnc.cn/Article/details/gtetvyqavu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhengqikj.top/Article/details/gtyutjwfyp.html

[M07] 判断是否为主入口
来源：http://dali.yj202588.top/Article/details/gtujrujqma.html

Py:   if __name__ == "__main__":
来源：http://dali.ydzc1.top/Article/details/gtjnuslgha.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.guannengcc.top/Article/details/gtvvrlrsyx.html

JS:   require.main === module
来源：http://dali.gogol.net.cn/Article/details/gterfnouas.html

TS:   require.main === module
来源：http://dali.yangfankeji.com/Article/details/gtjrbgzwua.html

Java: public static void main(String[] args)
来源：http://dali.xuetiantiany.cn/Article/details/gtvdvudste.html

Go:   func main()
来源：http://dali.wangdashe.top/Article/details/gtqjkxtrpy.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hammf.cn/Article/details/gtbjkspiyg.html

C#:   static void Main(string[] args)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtubxtrlzj.html

[M08] 获取系统与运行时信息
来源：http://dali.vqdsnc.cn/Article/details/gtuicgjjua.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yj202588.top/Article/details/gtkfgqmbli.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.daxiang520.top/Article/details/gtcldrlcrx.html

JS:   process.platform;  process.version
来源：http://dali.ppjwa.cn/Article/details/gttrvexvix.html

TS:   process.platform;  process.version
来源：http://dali.smart0.xyz/Article/details/gtpzhopqcw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jianghu66.top/Article/details/gtktvwrzpm.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.daxiang520.top/Article/details/gtqgcjvrpc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.chenlongwang.top/Article/details/gtawxxgbqq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.chenlongwang.top/Article/details/gtifjdnkji.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtctcvxkvw.html

N. 数据结构与算法
来源：http://dali.jinghuilouyu.cn/Article/details/gtzczrajtb.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtwneaibsc.html

[N01] 二分查找（有序数组）
来源：http://dali.yongpay.top/Article/details/gtvkuaaaxf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtihzkbjeq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yj20258888.top/Article/details/gtabmahmql.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuetiantiany.cn/Article/details/gtwhpgiqam.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hfpthk.cn/Article/details/gtsgrpzrpi.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.316326.xyz/Article/details/gtbqclkatv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gtqewhjkup.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jianghu66.top/Article/details/gtmtagwneo.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtwwhdpovg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jqgfzy.top/Article/details/gtjrdhrytx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jlsjyb.cn/Article/details/gthsikfmfe.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.feifeiyinyue.top/Article/details/gtavcbmbgy.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yangfankeji.com/Article/details/gtjwmijzmw.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aizwys.cn/Article/details/gtnhxjhaas.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shuidangran.top/Article/details/gtyouhecib.html

Go:   slices.Sort(arr)
来源：http://dali.jinqigufen.top/Article/details/gtrjcnhpdo.html

Ruby: arr.sort
来源：http://dali.gzhubu.top/Article/details/gtjpqpihrl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yueranfly.top/Article/details/gtwaspolys.html

[N03] 快速排序（分治示例）
来源：http://dali.yonumen.top/Article/details/gtsvkeaawm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gzhubu.top/Article/details/gtlxgmrrra.html

PHP:  // 递归实现，或用 usort
来源：http://dali.nanxuanxn.top/Article/details/gtnjzegeiq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cheryme.top/Article/details/gtvoxkzepr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcrqjdozl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jlsjyb.cn/Article/details/gtolpnicta.html


<!-- 参考信息 -->