代发 wailian999

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yangfankeji.com/Article/details/gtjhxokkoe.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aibaodan.cn/Article/details/gteqrlgtcq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gturmsyvdw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjicbppmm.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.quarkkingdee.top/Article/details/gtolbxzjmh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.0kj1m.cn/Article/details/gtpzjiqgbz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.vqdsnc.cn/Article/details/gtrqjafrmg.html

[J06] 计算两时间之差
来源：http://dali.316326.xyz/Article/details/gtbpgzmmve.html

Py:   (end - start).total_seconds()
来源：http://dali.hongshengwenyu.top/Article/details/gtoiiwwglw.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhixingplan.top/Article/details/gtmmkahsdh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sxryk.cn/Article/details/gtvarzllpp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hnqzz.top/Article/details/gttnzhiahy.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hnqzz.top/Article/details/gtubtfgotj.html

Go:   end.Sub(start).Hours()
来源：http://dali.guowangkeji.top/Article/details/gtjbikaiyh.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hongshengwenyu.top/Article/details/gtnvohwkwt.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinqigfzy.top/Article/details/gtathcdylh.html

[J07] 比较两个日期
来源：http://dali.yj20258.top/Article/details/gtqpmwytee.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yj20258.top/Article/details/gtqkqgesny.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.meibo888.top/Article/details/gtmpsgxlcn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.wangdashe.top/Article/details/gtzqsnrjsl.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hfpthk.cn/Article/details/gttrwetmbl.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yuanzhike.top/Article/details/gtasdeimun.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.nanxuanxn.top/Article/details/gtttstmwko.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhongyouzk.top/Article/details/gtwgvgmlip.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shangyingyoupin.top/Article/details/gtsxrfhylk.html

[J08] 提取年月日与星期
来源：http://dali.shanyushiyangtech.top/Article/details/gtipsnembv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.dianchejie.cn/Article/details/gtyhntcwne.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hongshengwenyu.top/Article/details/gtxecmshjc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hongshengwenyu.top/Article/details/gtganhsavo.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.wangshuangyany.cn/Article/details/gtgvsnrzkt.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zycfv.cn/Article/details/gtgfbdtgsf.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.feifeiyinyue.top/Article/details/gtjxtlcpea.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.smart0.xyz/Article/details/gttoqxtfmy.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jlsjyb.cn/Article/details/gtgsyuggda.html

[J09] 时区处理
来源：http://dali.quarkkingdee.top/Article/details/gtxqhillsu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jqgfzy.top/Article/details/gtgmpdqpmc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yueranfly.top/Article/details/gtwwocorcg.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxinkj.top/Article/details/gtkuwmigam.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpjpmazyg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yvedp.cn/Article/details/gtixdcumao.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfshyxjrj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.c1oappe.top/Article/details/gtifoouwee.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.bjfxy.top/Article/details/gtmyvvpkvf.html

[J10] 取今天 / 本月第一天
来源：http://dali.hongshengwenyu.top/Article/details/gtacvfeznx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.fzhhl.top/Article/details/gtidrllqzq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.iojbl.cn/Article/details/gteazjuzjo.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.chenzaomai.com/Article/details/gtejktoaxo.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinqigufen.top/Article/details/gtjsyhurlo.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.daxiang520.top/Article/details/gtptxlouog.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hysaishi.cn/Article/details/gtojufmmzf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yongpay.top/Article/details/gtbynvjsne.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yj20258888.top/Article/details/gtyqxydtnd.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtbwalonxa.html

K. JSON 与序列化
来源：http://dali.guowangkeji.top/Article/details/gtxxtsndng.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtqimzxawn.html

[K01] 对象转 JSON 字符串
来源：http://dali.bjfxy.top/Article/details/gtmhzzormt.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.316326.xyz/Article/details/gtufhpidxa.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.pycfn.com/Article/details/gtxidlvvtt.html

JS:   JSON.stringify(obj)
来源：http://dali.svipenyu.cn/Article/details/gtanbidlzy.html

TS:   JSON.stringify(obj)
来源：http://dali.hfpthk.cn/Article/details/gtrrmfcwty.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sxryk.cn/Article/details/gtsldsvxut.html

Go:   json.Marshal(obj)
来源：http://dali.sxryk.cn/Article/details/gtltunhvja.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhixingplan.top/Article/details/gtugwarbmw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.smart0.xyz/Article/details/gtytastuau.html

[K02] JSON 字符串转对象
来源：http://dali.vqdsnc.cn/Article/details/gtbncanzrz.html

Py:   json.loads(s)
来源：http://dali.sufxvd.cn/Article/details/gtlbshjhbc.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.nwbrower.top/Article/details/gtrstxaapo.html

JS:   JSON.parse(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtnmqbivkt.html

TS:   JSON.parse(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtwpdhmyqx.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.tanke756.top/Article/details/gtjsbhibpk.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cdnleiting.top/Article/details/gtpaxjelsu.html

Ruby: JSON.parse(s)
来源：http://dali.sysykeji.top/Article/details/gtcvwqeisk.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtbivsorrr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cdnleiting.top/Article/details/gtueuxkgux.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhiwuduotai.top/Article/details/gttwylrmui.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258.top/Article/details/gtosflxmix.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sxryk.cn/Article/details/gtilacuuur.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.316326.xyz/Article/details/gtzymorhqx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtgearjtuv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhongyouzk.top/Article/details/gtszinfklx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtkltikuwy.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.daxiang520.top/Article/details/gtqdryeihj.html

[K04] 读取 JSON 文件
来源：http://dali.hywenlv.cn/Article/details/gtczwqhcsc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.fzhhl.top/Article/details/gtaydffmtt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.9152youxi.cn/Article/details/gtsyecsrym.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fzhhl.top/Article/details/gtenkxribn.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.havefunace.top/Article/details/gttweitzro.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.vqdsnc.cn/Article/details/gtvcxhuvwf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shangyingyoupin.top/Article/details/gtavzflqwv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yanxiufei.cn/Article/details/gtbkhikroc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gaohongyu789.top/Article/details/gtcyvlkujj.html

[K05] 深拷贝对象
来源：http://dali.cqqwz.cn/Article/details/gtwldrmtsy.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtlymrofgn.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yongpay.top/Article/details/gtniddbuiq.html

JS:   structuredClone(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlbadbulf.html

TS:   structuredClone(obj)
来源：http://dali.yuanzhike.top/Article/details/gtsckwsxeq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.c1oappe.top/Article/details/gtiisrdylm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shuidangran.top/Article/details/gtzgerveux.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.pengpengdd.cyou/Article/details/gtsxmqslbc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.snrcjt.cn/Article/details/gtoxpokuvj.html

[K06] 解析 URL 查询串
来源：http://dali.zhiwuduotai.top/Article/details/gtngsujixq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.guannengcc.top/Article/details/gtqexeozgc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinqigfzy.top/Article/details/gtgxsvmgpp.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cheryme.top/Article/details/gtvqrsjjwi.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenlongwang.top/Article/details/gtbsfibtkt.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yuxming.cn/Article/details/gtsnifywll.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xinyue.icu/Article/details/gtxtsgzvzi.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.mhx1999.top/Article/details/gtjccqwcbi.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gtskpvovjc.html

[K07] 进制转换
来源：http://dali.shanyushiyangtech.top/Article/details/gthrqxwgnf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkeoiqfww.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gtdyxfivgw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gtcoctvfga.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gthhbzgvxj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtkzpinxum.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.316326.xyz/Article/details/gtsuhusohd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.tianlin.xyz/Article/details/gtcxavdldy.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gtxrlotchb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yueranfly.top/Article/details/gtzzwblszn.html

Py:   pickle.dumps(obj)
来源：http://dali.cashguo.top/Article/details/gtaogvhhra.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gtelclpbjh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cashguo.top/Article/details/gtmpvlvzkv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cucudq.cn/Article/details/gtplvkkfbq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinyuanbaomall.cn/Article/details/gtduqojsqt.html

Go:   encoding/gob
来源：http://dali.hywenlv.cn/Article/details/gtbpjhyorb.html

Ruby: Marshal.dump(obj)
来源：http://dali.tian-w.cn/Article/details/gtzvfwihdz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cashguo.top/Article/details/gtmemqvczz.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtuzybdahg.html

L. 网络请求
来源：http://dali.hfpthk.cn/Article/details/gtyhixrkwc.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtxmwecmab.html

[L01] 发送 GET 请求
来源：http://dali.nanxinkj.top/Article/details/gtaijpewac.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.daxiang520.top/Article/details/gtfjlvwfrt.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xziqi.cn/Article/details/gtolccrpjv.html

JS:   await fetch(url)
来源：http://dali.dianchejie.cn/Article/details/gtlfrpcwne.html

TS:   await fetch(url)
来源：http://dali.hongshengwenyu.top/Article/details/gtvhesqrlx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cheryme.top/Article/details/gttsjhplim.html

Go:   resp, err := http.Get(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtecgzashr.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shanyushiyangtech.top/Article/details/gtgxtfzdkv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.316326.xyz/Article/details/gtgwhrxzti.html

[L02] 发送 POST JSON
来源：http://dali.gotoacloud.top/Article/details/gtarimzudh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jlsjyb.cn/Article/details/gtgiupxocz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqqurfmnb.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.andypj.xyz/Article/details/gtumcplbht.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ppjwa.cn/Article/details/gtzkfjxtjm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.smart0.xyz/Article/details/gtlfzwquqn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jianghu66.top/Article/details/gtklijkcqk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.0kj1m.cn/Article/details/gtkkakwshu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cucudq.cn/Article/details/gtdfpotzxz.html

[L03] 设置自定义请求头
来源：http://dali.redwolf501.top/Article/details/gtkziavyrn.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xinyue.icu/Article/details/gtfyqiiptt.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.birdmap.top/Article/details/gtlgaqsvuj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.haohaochexian.top/Article/details/gtrfpdyrbf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tanke756.top/Article/details/gtcuyhexfh.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ivvv.top/Article/details/gtypeihtng.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xuetiantiany.cn/Article/details/gthsglzvkn.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sweek.top/Article/details/gtshnaovtl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ehwqpu.com/Article/details/gtifwtytza.html

[L04] 设置超时
来源：http://dali.svipenyu.cn/Article/details/gtbditgxeb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.smart0.xyz/Article/details/gtonbnwyhx.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shangyingyoupin.top/Article/details/gtpdemlems.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gaohongyu789.top/Article/details/gtpxvnjgwv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhixingplan.top/Article/details/gtznfqoeis.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.snrcjt.cn/Article/details/gtwttxnvwx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.havefunace.top/Article/details/gtwmdznjjv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhengqikj.top/Article/details/gtkiinndpf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenlongwang.top/Article/details/gtjeyktrxq.html

[L05] 上传文件（multipart）
来源：http://dali.yuxming.cn/Article/details/gtdtihnkme.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.daria6918.cn/Article/details/gtunjuciwr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jqgfzy.top/Article/details/gtwvzufpvf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hammf.cn/Article/details/gtltbwzcje.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.aizwys.cn/Article/details/gtgsicjauk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.dianchejie.cn/Article/details/gtqswowftz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.daxiang520.top/Article/details/gtkcpfmehm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gotoacloud.top/Article/details/gtkhyabohl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtfjyqqstz.html

[L06] 解析响应为 JSON
来源：http://dali.daxiang520.top/Article/details/gtfvqzcltn.html

Py:   resp.json()
来源：http://dali.gzhubu.top/Article/details/gtqticyjle.html

PHP:  json_decode($body, true);
来源：http://dali.yj202588.top/Article/details/gtuohkoqbg.html

JS:   await resp.json()
来源：http://dali.cqqwz.cn/Article/details/gtkahxdbsh.html

TS:   await resp.json()
来源：http://dali.quarkkingdee.top/Article/details/gtvurgdxbe.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yuxming.cn/Article/details/gtuvjuiucm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.guowangkeji.top/Article/details/gtyjeixwke.html

Ruby: JSON.parse(resp.body)
来源：http://dali.c1oappe.top/Article/details/gteaxyfash.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ybcxt.top/Article/details/gtdbtlwkwd.html

[L07] 处理 HTTP 状态码
来源：http://dali.cdnleiting.top/Article/details/gtvqqqldkv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ehwqpu.com/Article/details/gtjwkbhtan.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xylfe.cn/Article/details/gtqlytanar.html

JS:   resp.ok;  resp.status
来源：http://dali.dashuyun.cn/Article/details/gtblgklicw.html

TS:   resp.ok;  resp.status
来源：http://dali.daxiang520.top/Article/details/gtxwoiuigv.html

Java: resp.statusCode()
来源：http://dali.pengpengdd.cyou/Article/details/gtwacuurru.html

Go:   resp.StatusCode
来源：http://dali.gaohongyu789.top/Article/details/gtszpghayk.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gtnhbkjjlk.html

C#:   (int)resp.StatusCode
来源：http://dali.smart0.xyz/Article/details/gtkiimkhpx.html

[L08] 并发请求多个地址
来源：http://dali.zhoulong.xyz/Article/details/gtcikmpeqb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gzhubu.top/Article/details/gtndinpotc.html

PHP:  curl_multi_init() 系列
来源：http://dali.yj202588.top/Article/details/gtlwtwtjkg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cashguo.top/Article/details/gtlnxgbmou.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.haohaochexian.top/Article/details/gtgjlymuof.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xinyue.icu/Article/details/gtptkaohte.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hammf.cn/Article/details/gtyyglvrsu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.guannengcc.top/Article/details/gtyclbjqev.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.c1oappe.top/Article/details/gtfmlzzuac.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtbgecilka.html

M. 命令行 / 进程 / 环境
来源：http://dali.yanxiufei.cn/Article/details/gtchysgwnz.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtumzrlydp.html

[M01] 读取命令行参数
来源：http://dali.ybcxt.top/Article/details/gttktjpvoz.html

Py:   sys.argv[1:]
来源：http://dali.haohaochexian.top/Article/details/gtzhkucgun.html

PHP:  $argv;  $argc;
来源：http://dali.meibo888.top/Article/details/gttswdrfjp.html

JS:   process.argv.slice(2)
来源：http://dali.c1oappe.top/Article/details/gthusequve.html

TS:   process.argv.slice(2)
来源：http://dali.gotoacloud.top/Article/details/gtkfaheizq.html

Java: args 数组（main 方法参数）
来源：http://dali.ppjwa.cn/Article/details/gtoidscwir.html

Go:   os.Args[1:]
来源：http://dali.redwolf501.top/Article/details/gtvbaqgata.html

Ruby: ARGV
来源：http://dali.sweek.top/Article/details/gtyveozjdk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.snrcjt.cn/Article/details/gtzrlnftjj.html

[M02] 读取环境变量
来源：http://dali.cashguo.top/Article/details/gtlzjbsavl.html

Py:   os.environ.get("HOME")
来源：http://dali.shzxlz.cn/Article/details/gtorvprbws.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zdqjudy.top/Article/details/gtumprgsto.html

JS:   process.env.HOME
来源：http://dali.hnqzz.top/Article/details/gtthoaqpcy.html

TS:   process.env.HOME
来源：http://dali.jianghu66.top/Article/details/gtqsmyxyfq.html

Java: System.getenv("HOME")
来源：http://dali.smart0.xyz/Article/details/gtvnhwcmyq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.fzhhl.top/Article/details/gtzxrzcnhk.html

Ruby: ENV["HOME"]
来源：http://dali.andypj.xyz/Article/details/gtpgmlptih.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.guannengcc.top/Article/details/gtspdhvjnl.html

[M03] 执行外部命令
来源：http://dali.shzxlz.cn/Article/details/gtaltseidz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jqgufenzy.top/Article/details/gtwjahrdce.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xuanzx.com/Article/details/gtmszadbxo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangshuangyany.cn/Article/details/gtbbhiobfv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.pengpengdd.cyou/Article/details/gtqjghxydz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shuidangran.top/Article/details/gtvegwcvmz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sysykeji.top/Article/details/gtqyppqlej.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hywenlv.cn/Article/details/gtiylybtdk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yangfankeji.com/Article/details/gtewlcuaoz.html

[M04] 获取当前工作目录
来源：http://dali.zhengqikj.top/Article/details/gtejxhigdu.html

Py:   os.getcwd()
来源：http://dali.gzhubu.top/Article/details/gtojgqoacp.html

PHP:  getcwd();
来源：http://dali.yvedp.cn/Article/details/gtsayzomza.html

JS:   process.cwd()
来源：http://dali.yueranfly.top/Article/details/gtahuqtdes.html

TS:   process.cwd()
来源：http://dali.quarkkingdee.top/Article/details/gtcbtznidh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zdqjudy.top/Article/details/gtosffnwvj.html

Go:   os.Getwd()
来源：http://dali.zhoulong.xyz/Article/details/gtzkzsuzub.html

Ruby: Dir.pwd
来源：http://dali.yvedp.cn/Article/details/gtihwuvdix.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jyoumei.cn/Article/details/gthhsvmedr.html

[M05] 设置退出码
来源：http://dali.ppjwa.cn/Article/details/gtpcsqtycg.html

Py:   sys.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gtlvnercve.html

PHP:  exit(1);
来源：http://dali.haohaochexian.top/Article/details/gtdmucgfzk.html

JS:   process.exit(1)
来源：http://dali.yj202588.top/Article/details/gtwllniqum.html

TS:   process.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gtlmjmnlht.html

Java: System.exit(1)
来源：http://dali.jianghu66.top/Article/details/gtenhzhpia.html

Go:   os.Exit(1)
来源：http://dali.cheryme.top/Article/details/gtdnocnsof.html

Ruby: exit 1
来源：http://dali.aibaodan.cn/Article/details/gthtslvzqc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cucudq.cn/Article/details/gtmbechjjo.html

[M06] 向标准错误输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkndghlrm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yongpay.top/Article/details/gtdvyroxoq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hywenlv.cn/Article/details/gtttctedch.html

JS:   console.error("err")
来源：http://dali.havefunace.top/Article/details/gtspxcxsgg.html

TS:   console.error("err")
来源：http://dali.ybcxt.top/Article/details/gtyhyroizc.html

Java: System.err.println("err")
来源：http://dali.meibo888.top/Article/details/gtbbdreogm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.chenjidiqi.icu/Article/details/gtptpdngmo.html

Ruby: warn "err"
来源：http://dali.smart0.xyz/Article/details/gtmosioffw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.c1oappe.top/Article/details/gthixtmcbm.html

[M07] 判断是否为主入口
来源：http://dali.cashguo.top/Article/details/gtgnuxhqjv.html

Py:   if __name__ == "__main__":
来源：http://dali.havefunace.top/Article/details/gtktzmbsdw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.birdmap.top/Article/details/gtfqazqdwp.html

JS:   require.main === module
来源：http://dali.mhx1999.top/Article/details/gtnrwhydnc.html

TS:   require.main === module
来源：http://dali.316326.xyz/Article/details/gturpzirnr.html

Java: public static void main(String[] args)
来源：http://dali.zhixingplan.top/Article/details/gtysndfvfi.html

Go:   func main()
来源：http://dali.gzhubu.top/Article/details/gtbavpbwnx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.wangdashe.top/Article/details/gtmognjhgq.html

C#:   static void Main(string[] args)
来源：http://dali.zhongyouzk.top/Article/details/gtymuhssmt.html

[M08] 获取系统与运行时信息
来源：http://dali.fzhhl.top/Article/details/gtlvfvjvpc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yj20258888.top/Article/details/gtmjzrpnie.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hywenlv.cn/Article/details/gtdbzqsxot.html

JS:   process.platform;  process.version
来源：http://dali.gotoacloud.top/Article/details/gtvzldtvbx.html

TS:   process.platform;  process.version
来源：http://dali.zhengqikj.top/Article/details/gthmthwaau.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jqgufenzy.top/Article/details/gtmyzpufiw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hywenlv.cn/Article/details/gtxuthuswl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shuidangran.top/Article/details/gthzsryxpy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yj20258888.top/Article/details/gtqdiqoabn.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtyhtrgoea.html

N. 数据结构与算法
来源：http://dali.yongpay.top/Article/details/gtzeieiszy.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtbrhvennu.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gtvgtsgrep.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gtkyuymfrr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yj202588.top/Article/details/gtykkxwaox.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.c1oappe.top/Article/details/gtnihhdofi.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tanke756.top/Article/details/gtzkaqwfwa.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtefsznltf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gtsgwhrjbu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nanxuanxn.top/Article/details/gtcemavogp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cashguo.top/Article/details/gtidpfmiah.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cashguo.top/Article/details/gtundmjfjl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhixingplan.top/Article/details/gtqyigzlnl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.gaohongyu789.top/Article/details/gtsnmwfkas.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhongyouzk.top/Article/details/gtnhxrfmye.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvkxuucfl.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttoycgyhm.html

Go:   slices.Sort(arr)
来源：http://dali.yvedp.cn/Article/details/gtdjvpowyq.html

Ruby: arr.sort
来源：http://dali.hnqzz.top/Article/details/gtmsgavbuu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yj20258.top/Article/details/gtmyzfmirz.html

[N03] 快速排序（分治示例）
来源：http://dali.ivvv.top/Article/details/gtdrfflxdq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hongshengwenyu.top/Article/details/gthjddcldu.html


<!-- 参考信息 -->