代发 wailian999

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.kuanghao11.cn/Article/details/gthxxxnlgj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.316326.xyz/Article/details/gtnxrpkbki.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dashuyun.cn/Article/details/gtawxxgewn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jlsjyb.cn/Article/details/gtkikojcee.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hammf.cn/Article/details/gtxcjtikyt.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcpwnzfcg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.birdmap.top/Article/details/gthjhrbrwi.html

[J06] 计算两时间之差
来源：http://dali.tanke756.top/Article/details/gtwbjffemx.html

Py:   (end - start).total_seconds()
来源：http://dali.jinghuilouyu.cn/Article/details/gtvpvvlhpb.html

PHP:  $end->diff($start)->days;
来源：http://dali.daria6918.cn/Article/details/gtrqbdocvv.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.redwolf501.top/Article/details/gtbanmezne.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.guowangkeji.top/Article/details/gtyynsjrif.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.aibaodan.cn/Article/details/gthmzkgwii.html

Go:   end.Sub(start).Hours()
来源：http://dali.smart0.xyz/Article/details/gtfrvcjntl.html

Ruby: end - start                 # 返回秒数
来源：http://dali.svipenyu.cn/Article/details/gttonbqbqi.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj202588.top/Article/details/gtglgvzgaq.html

[J07] 比较两个日期
来源：http://dali.cashguo.top/Article/details/gtpgoutrhb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.daria6918.cn/Article/details/gtprigvnsf.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinqigfzy.top/Article/details/gtcjewvjiv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhoulong.xyz/Article/details/gtvitklunm.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ydzc1.top/Article/details/gtaxvyvnud.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinqigufen.top/Article/details/gtccijvfrm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yongpay.top/Article/details/gtubveoati.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.aizwys.cn/Article/details/gtzbycbifx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.snrcjt.cn/Article/details/gtgrtjdkfb.html

[J08] 提取年月日与星期
来源：http://dali.zhongyouzk.top/Article/details/gtpvobwarp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jianghu66.top/Article/details/gtjsdboszq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hywenlv.cn/Article/details/gtdsroxaxh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.wangshuangyany.cn/Article/details/gtzgutddgc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.chenjidiqi.icu/Article/details/gtteqhsaoj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtonnudkux.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shzxlz.cn/Article/details/gtufafbqez.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yj202588.top/Article/details/gtuwbxhppx.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xinyue.icu/Article/details/gtznlzrodu.html

[J09] 时区处理
来源：http://dali.yuxming.cn/Article/details/gtovwwzgyn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ydzc1.top/Article/details/gtbshiilvi.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ehwqpu.com/Article/details/gtukekqyjc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.havefunace.top/Article/details/gtcdgudyzi.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.iojbl.cn/Article/details/gtlhvzlyty.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ybcxt.top/Article/details/gtnjkeppnt.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvzngnfyz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xziqi.cn/Article/details/gtpdbtrbta.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.fengsongda.top/Article/details/gtbjhmszfl.html

[J10] 取今天 / 本月第一天
来源：http://dali.sufxvd.cn/Article/details/gtljghoovy.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gogol.net.cn/Article/details/gttepuzysb.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinqigfzy.top/Article/details/gtsiyecacf.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvyxgwsjv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ydzc1.top/Article/details/gteyuqztlr.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cheryme.top/Article/details/gteoyucbum.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.vqdsnc.cn/Article/details/gtrmphempr.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shuidangran.top/Article/details/gtohyfygzs.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.0kj1m.cn/Article/details/gtmiqrlzqr.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtcmxojjmt.html

K. JSON 与序列化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxyftgawk.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtimzcfjku.html

[K01] 对象转 JSON 字符串
来源：http://dali.shuidangran.top/Article/details/gtsodbceoe.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhoulong.xyz/Article/details/gteciofleg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhoulong.xyz/Article/details/gtwjqqykvb.html

JS:   JSON.stringify(obj)
来源：http://dali.ivvv.top/Article/details/gthygaqgmy.html

TS:   JSON.stringify(obj)
来源：http://dali.yj20258.top/Article/details/gteydcnbcq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cdnleiting.top/Article/details/gtnibtldvf.html

Go:   json.Marshal(obj)
来源：http://dali.zycfv.cn/Article/details/gtspscctze.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.quarkkingdee.top/Article/details/gtdqkphvci.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zycfv.cn/Article/details/gtobkocfbs.html

[K02] JSON 字符串转对象
来源：http://dali.xuetiantiany.cn/Article/details/gtivcayrmb.html

Py:   json.loads(s)
来源：http://dali.hammf.cn/Article/details/gtghcgcaxd.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sysykeji.top/Article/details/gtpxqrzrsd.html

JS:   JSON.parse(s)
来源：http://dali.vqdsnc.cn/Article/details/gtmxahbnnv.html

TS:   JSON.parse(s)
来源：http://dali.xinyue.icu/Article/details/gtmvqmblma.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.smart0.xyz/Article/details/gtmyqztlin.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jiagoushi.top/Article/details/gtxniacagn.html

Ruby: JSON.parse(s)
来源：http://dali.sysykeji.top/Article/details/gtsovgriej.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtyfjpkjpi.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hysaishi.cn/Article/details/gtbhlekseo.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yuxming.cn/Article/details/gtqcbvlzuk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gogol.net.cn/Article/details/gtglopvpko.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tianlin.xyz/Article/details/gtgmuddlkz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yongpay.top/Article/details/gtrzqtvyas.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.chenlongwang.top/Article/details/gtgdhvlwfj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.chenzaomai.com/Article/details/gtfahtwlrf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjjubljpv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.feifeiyinyue.top/Article/details/gtapdyprnb.html

[K04] 读取 JSON 文件
来源：http://dali.tian-w.cn/Article/details/gtbgmljhps.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yvedp.cn/Article/details/gtoularnjj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hfpthk.cn/Article/details/gtrjbiomnx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aibaodan.cn/Article/details/gtkyawrsim.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtjfjzywqa.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhengqikj.top/Article/details/gthysmbpft.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xuanzx.com/Article/details/gtdanmkgds.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yuanzhike.top/Article/details/gttkjckcqq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hongshengwenyu.top/Article/details/gtorykgtmf.html

[K05] 深拷贝对象
来源：http://dali.hywenlv.cn/Article/details/gthgwzycbt.html

Py:   copy.deepcopy(obj)
来源：http://dali.cqqwz.cn/Article/details/gtrrnxayfw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gzhubu.top/Article/details/gtofhrqwta.html

JS:   structuredClone(obj)
来源：http://dali.nanxinkj.top/Article/details/gtpbgcgvur.html

TS:   structuredClone(obj)
来源：http://dali.chenlongwang.top/Article/details/gtliagogbp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.wangdashe.top/Article/details/gtngwdptvm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.vqdsnc.cn/Article/details/gtcdtmjczp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhengqikj.top/Article/details/gtquuzrsgt.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinqigfzy.top/Article/details/gtkuukwnfb.html

[K06] 解析 URL 查询串
来源：http://dali.yongpay.top/Article/details/gtbczsmntr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.chenjidiqi.icu/Article/details/gtzeqnrump.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hysaishi.cn/Article/details/gtlpquwbwv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sweek.top/Article/details/gtoolwedom.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangdashe.top/Article/details/gtcrsqnhbc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhengqikj.top/Article/details/gtctiknqpk.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shanyushiyangtech.top/Article/details/gterwpszni.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jqgfzy.top/Article/details/gtkperzqxb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.vqdsnc.cn/Article/details/gtbwrocajd.html

[K07] 进制转换
来源：http://dali.yanxiufei.cn/Article/details/gtlwucibtr.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gtzzdpxblu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yueranfly.top/Article/details/gttsstbkhk.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gtpivcpyuc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gtyzunqdqf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gtwghuoweo.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.havefunace.top/Article/details/gtobrpeyhe.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zdqjudy.top/Article/details/gtmpxhtltz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gtdiunsbag.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.guowangkeji.top/Article/details/gtpoargmin.html

Py:   pickle.dumps(obj)
来源：http://dali.snrcjt.cn/Article/details/gtrrvyfkne.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yangfankeji.com/Article/details/gtktmlozwn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gtcxgfxspe.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzgezufiv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.wangdashe.top/Article/details/gtidqbnbir.html

Go:   encoding/gob
来源：http://dali.zycfv.cn/Article/details/gtkaawzlbr.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtszvxwxzu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.wangshuangyany.cn/Article/details/gtfrhzhcwx.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtxwqsifkt.html

L. 网络请求
来源：http://dali.wangdashe.top/Article/details/gtvdqxzryp.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtkqjiubdz.html

[L01] 发送 GET 请求
来源：http://dali.iojbl.cn/Article/details/gtcywpokvw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.nanxinkj.top/Article/details/gtislbjiln.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hongshengwenyu.top/Article/details/gtdfeapjyr.html

JS:   await fetch(url)
来源：http://dali.havefunace.top/Article/details/gtuotruqsp.html

TS:   await fetch(url)
来源：http://dali.yanxiufei.cn/Article/details/gtnenbbjhv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jqgfzy.top/Article/details/gtvshdoyvo.html

Go:   resp, err := http.Get(url)
来源：http://dali.sweek.top/Article/details/gtzhjwcubp.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.feifeiyinyue.top/Article/details/gtwaaenkdb.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xinyue.icu/Article/details/gtezdszbgm.html

[L02] 发送 POST JSON
来源：http://dali.xinyue.icu/Article/details/gtcpnregvc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jyoumei.cn/Article/details/gtemgztlyb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shzxlz.cn/Article/details/gtnxghimxk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigfzy.top/Article/details/gtpcoqzcrd.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgfzy.top/Article/details/gtpmiznjla.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jyoumei.cn/Article/details/gthlyejvjb.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.meibo888.top/Article/details/gtnelnlsmc.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jqgfzy.top/Article/details/gtckrekvmt.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hywenlv.cn/Article/details/gtgrsonkre.html

[L03] 设置自定义请求头
来源：http://dali.fengsongda.top/Article/details/gtfhtgmswo.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xuanzx.com/Article/details/gtvoylsozc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenzaomai.com/Article/details/gtehfnkeid.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guowangkeji.top/Article/details/gtmmjqkptx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zdqjudy.top/Article/details/gtkrhfnghu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.pengpengdd.cyou/Article/details/gtznwilxtr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gaohongyu789.top/Article/details/gthieyhryr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shzxlz.cn/Article/details/gtabuwbqan.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.nanxuanxn.top/Article/details/gtyebjjytv.html

[L04] 设置超时
来源：http://dali.zycfv.cn/Article/details/gtjdezcveu.html

Py:   requests.get(url, timeout=5)
来源：http://dali.bjfxy.top/Article/details/gtuuobwgwi.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xuanzx.com/Article/details/gtrpzcorea.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zycfv.cn/Article/details/gtkewnmgso.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnqzz.top/Article/details/gtkjhpwgsr.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sweek.top/Article/details/gtnrqnmguo.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ybcxt.top/Article/details/gtlsuorfjo.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sufxvd.cn/Article/details/gtubwxfkdz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yj20258888.top/Article/details/gtdvqgsdbl.html

[L05] 上传文件（multipart）
来源：http://dali.svipenyu.cn/Article/details/gtyjaybpyd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gotoacloud.top/Article/details/gtnmvxjmam.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.bjfxy.top/Article/details/gtbcqwcmgh.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.tian-w.cn/Article/details/gtayutpzae.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuetiantiany.cn/Article/details/gthofrvliu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jianghu66.top/Article/details/gtjauulkyc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.chenjidiqi.icu/Article/details/gthciutfzd.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.bjfxy.top/Article/details/gthfbapssz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xuanzx.com/Article/details/gtqxvsemve.html

[L06] 解析响应为 JSON
来源：http://dali.pengpengdd.cyou/Article/details/gtrrbznyxm.html

Py:   resp.json()
来源：http://dali.sufxvd.cn/Article/details/gtmacgeoys.html

PHP:  json_decode($body, true);
来源：http://dali.fzhhl.top/Article/details/gtkadcmoig.html

JS:   await resp.json()
来源：http://dali.nanxinkj.top/Article/details/gtbpcnxsel.html

TS:   await resp.json()
来源：http://dali.jinghuilouyu.cn/Article/details/gtiiiubdgj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yongpay.top/Article/details/gtgxvzktqm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.pengpengdd.cyou/Article/details/gtllflhnia.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hysaishi.cn/Article/details/gtowkquwhp.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinqigfzy.top/Article/details/gtdsypuyxx.html

[L07] 处理 HTTP 状态码
来源：http://dali.pengpengdd.cyou/Article/details/gtvuvfqmrx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yuxming.cn/Article/details/gtgdevamsx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhongyouzk.top/Article/details/gthbrwcsgj.html

JS:   resp.ok;  resp.status
来源：http://dali.yongpay.top/Article/details/gtfevqxrlx.html

TS:   resp.ok;  resp.status
来源：http://dali.daxiang520.top/Article/details/gtmutzmweq.html

Java: resp.statusCode()
来源：http://dali.chenzaomai.com/Article/details/gtyksqizqa.html

Go:   resp.StatusCode
来源：http://dali.xylfe.cn/Article/details/gtylyddniv.html

Ruby: resp.code.to_i
来源：http://dali.andypj.xyz/Article/details/gtclbgnjmg.html

C#:   (int)resp.StatusCode
来源：http://dali.zhixingplan.top/Article/details/gtjmbdfadw.html

[L08] 并发请求多个地址
来源：http://dali.jyoumei.cn/Article/details/gtcleswvxu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.andypj.xyz/Article/details/gtxsqwzabb.html

PHP:  curl_multi_init() 系列
来源：http://dali.9152youxi.cn/Article/details/gthtplzibo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gzhubu.top/Article/details/gtngjpihhg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiymojwec.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yj202588.top/Article/details/gtgybovhqe.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.redwolf501.top/Article/details/gtmeglqsle.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.316326.xyz/Article/details/gteqhakcod.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinqigfzy.top/Article/details/gtdiqhlojz.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gteeqgiepx.html

M. 命令行 / 进程 / 环境
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfmujusxb.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtrxrtjaik.html

[M01] 读取命令行参数
来源：http://dali.haohaochexian.top/Article/details/gtlqeawtnk.html

Py:   sys.argv[1:]
来源：http://dali.c1oappe.top/Article/details/gtvmeoshwd.html

PHP:  $argv;  $argc;
来源：http://dali.yangfankeji.com/Article/details/gttlafsihs.html

JS:   process.argv.slice(2)
来源：http://dali.hnqzz.top/Article/details/gteukyhwmi.html

TS:   process.argv.slice(2)
来源：http://dali.jinqigfzy.top/Article/details/gtouftpqfz.html

Java: args 数组（main 方法参数）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrpojtktr.html

Go:   os.Args[1:]
来源：http://dali.wangdashe.top/Article/details/gtwjfwscdv.html

Ruby: ARGV
来源：http://dali.jyoumei.cn/Article/details/gtdsuickpl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shuidangran.top/Article/details/gtnzpsxhrc.html

[M02] 读取环境变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrngrfnkp.html

Py:   os.environ.get("HOME")
来源：http://dali.meibo888.top/Article/details/gtrakqrtbr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hnqzz.top/Article/details/gtbnennnxs.html

JS:   process.env.HOME
来源：http://dali.meibo888.top/Article/details/gtfmaafdcn.html

TS:   process.env.HOME
来源：http://dali.316326.xyz/Article/details/gtjshxmpas.html

Java: System.getenv("HOME")
来源：http://dali.chenlongwang.top/Article/details/gtosqgtoxn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gtncwyactf.html

Ruby: ENV["HOME"]
来源：http://dali.pycfn.com/Article/details/gtjcgeskjz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zycfv.cn/Article/details/gtpvxtilzy.html

[M03] 执行外部命令
来源：http://dali.pengpengdd.cyou/Article/details/gtcjwjemvf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tianlin.xyz/Article/details/gtipensjha.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpczungxb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhengqikj.top/Article/details/gtwohggtkq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.0kj1m.cn/Article/details/gtrbynqlyu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.snrcjt.cn/Article/details/gtkphmzlsu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yuxming.cn/Article/details/gtwoeatlko.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdmpyejls.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cheryme.top/Article/details/gtoekoozmx.html

[M04] 获取当前工作目录
来源：http://dali.yuxming.cn/Article/details/gturdtzujx.html

Py:   os.getcwd()
来源：http://dali.svipenyu.cn/Article/details/gtzxkmhriu.html

PHP:  getcwd();
来源：http://dali.yj202588.top/Article/details/gtmogrowqw.html

JS:   process.cwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlirtnsid.html

TS:   process.cwd()
来源：http://dali.jqgfzy.top/Article/details/gtkvshjjdo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.guannengcc.top/Article/details/gttsgczysj.html

Go:   os.Getwd()
来源：http://dali.yonumen.top/Article/details/gtmfnqzfyf.html

Ruby: Dir.pwd
来源：http://dali.sufxvd.cn/Article/details/gtuvrhovbd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hammf.cn/Article/details/gtncsjuktt.html

[M05] 设置退出码
来源：http://dali.guannengcc.top/Article/details/gtmholqcgy.html

Py:   sys.exit(1)
来源：http://dali.yongpay.top/Article/details/gtoifddikx.html

PHP:  exit(1);
来源：http://dali.birdmap.top/Article/details/gtpccxhojl.html

JS:   process.exit(1)
来源：http://dali.birdmap.top/Article/details/gttlfcxlkp.html

TS:   process.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyemhtsdw.html

Java: System.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gtfqljeqyc.html

Go:   os.Exit(1)
来源：http://dali.wangdashe.top/Article/details/gthuedvetj.html

Ruby: exit 1
来源：http://dali.fengsongda.top/Article/details/gtgzkrsgsq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gtmdruxkhy.html

[M06] 向标准错误输出
来源：http://dali.kuanghao11.cn/Article/details/gtjocnknwe.html

Py:   print("err", file=sys.stderr)
来源：http://dali.vqdsnc.cn/Article/details/gtlfjxsxcz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.feifeiyinyue.top/Article/details/gtqbjypvnt.html

JS:   console.error("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gtliyngeub.html

TS:   console.error("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfjadpuzo.html

Java: System.err.println("err")
来源：http://dali.pycfn.com/Article/details/gtujeqnkwz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.daria6918.cn/Article/details/gthcayucjs.html

Ruby: warn "err"
来源：http://dali.redwolf501.top/Article/details/gtcslpuzqe.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.snrcjt.cn/Article/details/gteiduxjon.html

[M07] 判断是否为主入口
来源：http://dali.zhoulong.xyz/Article/details/gthwsbuslw.html

Py:   if __name__ == "__main__":
来源：http://dali.chenzaomai.com/Article/details/gtjevrgsen.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.bjfxy.top/Article/details/gtdekjqhbd.html

JS:   require.main === module
来源：http://dali.jianghu66.top/Article/details/gtvycqtlft.html

TS:   require.main === module
来源：http://dali.wangdashe.top/Article/details/gtvljgnfnl.html

Java: public static void main(String[] args)
来源：http://dali.chenzaomai.com/Article/details/gtonnvysno.html

Go:   func main()
来源：http://dali.sweek.top/Article/details/gtuayknfil.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xuanzx.com/Article/details/gtforofjax.html

C#:   static void Main(string[] args)
来源：http://dali.sweek.top/Article/details/gtewumgxxw.html

[M08] 获取系统与运行时信息
来源：http://dali.yongpay.top/Article/details/gtusuxqgvy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yueranfly.top/Article/details/gtxmicixsr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.guannengcc.top/Article/details/gtaqpipncs.html

JS:   process.platform;  process.version
来源：http://dali.birdmap.top/Article/details/gtdipfccdd.html

TS:   process.platform;  process.version
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvvkcjbex.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.pengpengdd.cyou/Article/details/gtmqegyrhg.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqoaltsxr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gotoacloud.top/Article/details/gtbamraxaf.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ehwqpu.com/Article/details/gtwfyhqkek.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gttxhaqkfp.html

N. 数据结构与算法
来源：http://dali.cqqwz.cn/Article/details/gtpomfefxa.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtfhaohrnx.html

[N01] 二分查找（有序数组）
来源：http://dali.yueranfly.top/Article/details/gtoucvbult.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfuhrnbkc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.9152youxi.cn/Article/details/gtxpzpfqub.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sysykeji.top/Article/details/gtrzpakkpy.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gtknafsckq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gtqvsfyduw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtmgwwkxsq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nanxuanxn.top/Article/details/gtbarlugaq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtjckjfdkz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.pycfn.com/Article/details/gtsbxmjhoa.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuetiantiany.cn/Article/details/gtvpmngago.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.guowangkeji.top/Article/details/gtalsuvebm.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.bjfxy.top/Article/details/gttqpusfqe.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.svipenyu.cn/Article/details/gtmxhhtmmb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zycfv.cn/Article/details/gtrdlhvgku.html

Go:   slices.Sort(arr)
来源：http://dali.hfpthk.cn/Article/details/gtgeoypdmj.html

Ruby: arr.sort
来源：http://dali.ybcxt.top/Article/details/gtfubzgiif.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.chenlongwang.top/Article/details/gtlcogouti.html

[N03] 快速排序（分治示例）
来源：http://dali.nanxinkj.top/Article/details/gtmwysynjk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yvedp.cn/Article/details/gthedolbgo.html


<!-- 参考信息 -->