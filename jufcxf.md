代发 wailian999

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfccrihbt.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gtqegdroza.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinghuilouyu.cn/Article/details/gtiffmqcqu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.quarkkingdee.top/Article/details/gttcbritnp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gaohongyu789.top/Article/details/gtouhkfvpl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.guannengcc.top/Article/details/gtoavsdoxe.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.nwbrower.top/Article/details/gtlisbbbho.html

[J06] 计算两时间之差
来源：http://dali.fzhhl.top/Article/details/gtpdtxpzmz.html

Py:   (end - start).total_seconds()
来源：http://dali.nanxinkj.top/Article/details/gtnkwfnhjo.html

PHP:  $end->diff($start)->days;
来源：http://dali.shzxlz.cn/Article/details/gtvqduesvo.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cdnleiting.top/Article/details/gtizogqeyp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.aibaodan.cn/Article/details/gtlytilncq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xinyue.icu/Article/details/gtmlltvwmd.html

Go:   end.Sub(start).Hours()
来源：http://dali.shuidangran.top/Article/details/gtwobapcng.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ivvv.top/Article/details/gtgryepsjd.html

C#:   (end - start).TotalSeconds
来源：http://dali.c1oappe.top/Article/details/gtivmyvmkm.html

[J07] 比较两个日期
来源：http://dali.jqgufenzy.top/Article/details/gtgewhofrz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gtzhtdpbgy.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gzhubu.top/Article/details/gtdjxscrnf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigufen.top/Article/details/gtpgnqipdb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgufenzy.top/Article/details/gthgrfbdij.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yuxming.cn/Article/details/gtewyqjofa.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhixingplan.top/Article/details/gtiyultixz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gtudvpsehv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gogol.net.cn/Article/details/gthacjvpbe.html

[J08] 提取年月日与星期
来源：http://dali.xinyue.icu/Article/details/gthepypyqf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhixingplan.top/Article/details/gtrpnafhtl.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cucudq.cn/Article/details/gtygklivua.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hnxiangtu.top/Article/details/gtxwategys.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcyjkbfym.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.nanxuanxn.top/Article/details/gtvidakvku.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.tanke756.top/Article/details/gtatjrkxrs.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.dashuyun.cn/Article/details/gtxngtrdob.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.9152youxi.cn/Article/details/gtypyvdrki.html

[J09] 时区处理
来源：http://dali.jqgufenzy.top/Article/details/gtlsbmbdpp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.daria6918.cn/Article/details/gtnqawmnpn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinghuilouyu.cn/Article/details/gtuuniluon.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ydzc1.top/Article/details/gtwrjvhznu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hfpthk.cn/Article/details/gtqjtyjiwz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.pengpengdd.cyou/Article/details/gtuusfruwv.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.meibo888.top/Article/details/gtuwvjttxb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gaohongyu789.top/Article/details/gtscirpgae.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yonumen.top/Article/details/gtkrstbwpc.html

[J10] 取今天 / 本月第一天
来源：http://dali.pengpengdd.cyou/Article/details/gtpruboula.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.quarkkingdee.top/Article/details/gtaxwrdugp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tanke756.top/Article/details/gttpgtkgdd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.pycfn.com/Article/details/gtqttkrfiq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.chenzaomai.com/Article/details/gtdqrbtryb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yanxiufei.cn/Article/details/gttdptnflw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.vqdsnc.cn/Article/details/gtegipsqgl.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhongyouzk.top/Article/details/gttvcjmvsl.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ivvv.top/Article/details/gtstxwsjch.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtlylfkyuk.html

K. JSON 与序列化
来源：http://dali.ehwqpu.com/Article/details/gtnnwcjnpt.html

================================================================================
来源：http://dali.sweek.top/Article/details/gttnhirlai.html

[K01] 对象转 JSON 字符串
来源：http://dali.xylfe.cn/Article/details/gtkgkolcew.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.guowangkeji.top/Article/details/gtkrejuzuh.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.tanke756.top/Article/details/gtbrfczmfx.html

JS:   JSON.stringify(obj)
来源：http://dali.dashuyun.cn/Article/details/gtnfixlcze.html

TS:   JSON.stringify(obj)
来源：http://dali.0kj1m.cn/Article/details/gtwfudvmvs.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.redwolf501.top/Article/details/gtvtavheld.html

Go:   json.Marshal(obj)
来源：http://dali.aizwys.cn/Article/details/gtehkflnos.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.aizwys.cn/Article/details/gtqkebezgx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.dianchejie.cn/Article/details/gtedqhpajr.html

[K02] JSON 字符串转对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gtchtassmx.html

Py:   json.loads(s)
来源：http://dali.tanke756.top/Article/details/gtkcivqgap.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.andypj.xyz/Article/details/gtrxeggfpa.html

JS:   JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gtqkhhdpdc.html

TS:   JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gtvyjkhrgb.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sufxvd.cn/Article/details/gtgyaqojhe.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gogol.net.cn/Article/details/gtijwszvyp.html

Ruby: JSON.parse(s)
来源：http://dali.vqdsnc.cn/Article/details/gtydsjqydi.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.birdmap.top/Article/details/gtugnexrkh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sxryk.cn/Article/details/gtohdfwgnf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenjidiqi.icu/Article/details/gtznltuvcm.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.chenjidiqi.icu/Article/details/gteqlzppqt.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xinyue.icu/Article/details/gtrbcxkgkw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xylfe.cn/Article/details/gtgafttrth.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ehwqpu.com/Article/details/gtrcnegssm.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.0kj1m.cn/Article/details/gtizkkwlgr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtityzpdyq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nwbrower.top/Article/details/gtsrzqzuww.html

[K04] 读取 JSON 文件
来源：http://dali.feifeiyinyue.top/Article/details/gthvbsusqw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhiwuduotai.top/Article/details/gtctktaxql.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.tianlin.xyz/Article/details/gtfguivbxh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258888.top/Article/details/gtzetnlcvd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ivvv.top/Article/details/gttufxyoef.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yongpay.top/Article/details/gtilxbmbhc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthqxplkeb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.haohaochexian.top/Article/details/gthoaxmune.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ydzc1.top/Article/details/gtwwrdvflg.html

[K05] 深拷贝对象
来源：http://dali.gogol.net.cn/Article/details/gtmyefmqcy.html

Py:   copy.deepcopy(obj)
来源：http://dali.yueranfly.top/Article/details/gtruqiqnzk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xinyue.icu/Article/details/gtcimqvylk.html

JS:   structuredClone(obj)
来源：http://dali.fzhhl.top/Article/details/gtyodzedqo.html

TS:   structuredClone(obj)
来源：http://dali.316326.xyz/Article/details/gtwsqhgviw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hongshengwenyu.top/Article/details/gtyyjgrqjy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yvedp.cn/Article/details/gtdzlpwozh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.dianchejie.cn/Article/details/gtcqoogahr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yj202588.top/Article/details/gtzhabeebn.html

[K06] 解析 URL 查询串
来源：http://dali.svipenyu.cn/Article/details/gtshmgdrdc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.mhx1999.top/Article/details/gtonkeleko.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.redwolf501.top/Article/details/gtfsdhmbfn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.0kj1m.cn/Article/details/gtwxuzbmvz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.smart0.xyz/Article/details/gtqrhfamwq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinghuilouyu.cn/Article/details/gtbnxkrmxi.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.wangshuangyany.cn/Article/details/gtjrevmgai.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xziqi.cn/Article/details/gtfobmsshu.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.mhx1999.top/Article/details/gtcirprawa.html

[K07] 进制转换
来源：http://dali.iojbl.cn/Article/details/gtanskvwte.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gtbrzgrdrp.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yj202588.top/Article/details/gtemspyijf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.havefunace.top/Article/details/gtogxnvamm.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gtduukxvlj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gtywojtpkd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cqqwz.cn/Article/details/gtqecpqnei.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.fengsongda.top/Article/details/gtafxnobrr.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtjxhizhkl.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.havefunace.top/Article/details/gtasipxqjz.html

Py:   pickle.dumps(obj)
来源：http://dali.xinyue.icu/Article/details/gtxkaxazbf.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdxloapcl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvmliqekb.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sxryk.cn/Article/details/gtirriwqni.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrncphfma.html

Go:   encoding/gob
来源：http://dali.zhaomingkeji.xyz/Article/details/gthhpmybse.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtjwcxwkha.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yanxiufei.cn/Article/details/gtdgiwkowu.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtunhfhepu.html

L. 网络请求
来源：http://dali.hongshengwenyu.top/Article/details/gtgmkotmbb.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtwtrbjadv.html

[L01] 发送 GET 请求
来源：http://dali.birdmap.top/Article/details/gtoobdwwnd.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnkzhpjfe.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdwyubhca.html

JS:   await fetch(url)
来源：http://dali.pengpengdd.cyou/Article/details/gtvhywodbr.html

TS:   await fetch(url)
来源：http://dali.fengsongda.top/Article/details/gtgdajsnzx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hongshengwenyu.top/Article/details/gthxnwbsfr.html

Go:   resp, err := http.Get(url)
来源：http://dali.dianchejie.cn/Article/details/gtbkjclrdr.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.meibo888.top/Article/details/gtihrdislj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ydzc1.top/Article/details/gtinjnrxgi.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gthtbamrnr.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.bjfxy.top/Article/details/gteckpxlks.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.guannengcc.top/Article/details/gtozptrpon.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yongpay.top/Article/details/gtggbuadpb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.316326.xyz/Article/details/gtamliroms.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gaohongyu789.top/Article/details/gtdwpvqgqu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yj202588.top/Article/details/gtbvninnwa.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhixingplan.top/Article/details/gtlpebdskw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hysaishi.cn/Article/details/gtmhybtucc.html

[L03] 设置自定义请求头
来源：http://dali.birdmap.top/Article/details/gtugzscuoq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.nwbrower.top/Article/details/gtfgadxlef.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hnxiangtu.top/Article/details/gtuyjygxsf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guowangkeji.top/Article/details/gtmonotbou.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmndxwokd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hammf.cn/Article/details/gtktmnkkyx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.9152youxi.cn/Article/details/gtdqkcagwu.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhoulong.xyz/Article/details/gtmwceoulk.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yuanzhike.top/Article/details/gtqwcljeyl.html

[L04] 设置超时
来源：http://dali.yj202588.top/Article/details/gtdlgitqba.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yj20258.top/Article/details/gtgwkrsyme.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gaohongyu789.top/Article/details/gtazftahad.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tanke756.top/Article/details/gtgdreugie.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shangyingyoupin.top/Article/details/gtxorezacq.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xziqi.cn/Article/details/gtaxeccpvx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yvedp.cn/Article/details/gtsoktmeqs.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gaohongyu789.top/Article/details/gtevfzxnxt.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.wangshuangyany.cn/Article/details/gtiqmtdhuz.html

[L05] 上传文件（multipart）
来源：http://dali.ydzc1.top/Article/details/gtxkajborb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.guannengcc.top/Article/details/gtuzdhiysm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.haohaochexian.top/Article/details/gtvhmsffpe.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yvedp.cn/Article/details/gtgcxlstxt.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenlongwang.top/Article/details/gtclcjhluh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhixingplan.top/Article/details/gtjoozjoxb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.pycfn.com/Article/details/gtkutjeutr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yongpay.top/Article/details/gtccfovirm.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtscjtbzxs.html

[L06] 解析响应为 JSON
来源：http://dali.yj20258.top/Article/details/gtgbdxprjt.html

Py:   resp.json()
来源：http://dali.xylfe.cn/Article/details/gtdfyxznzv.html

PHP:  json_decode($body, true);
来源：http://dali.hysaishi.cn/Article/details/gtwdbbllik.html

JS:   await resp.json()
来源：http://dali.dianchejie.cn/Article/details/gtlnayfklb.html

TS:   await resp.json()
来源：http://dali.redwolf501.top/Article/details/gtfopolgsf.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.mhx1999.top/Article/details/gtyqxyqizp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnnanzypj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjykxhafq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.feifeiyinyue.top/Article/details/gtqfzesovi.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtexznfchb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hnqzz.top/Article/details/gtuthjphed.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpfumvicb.html

JS:   resp.ok;  resp.status
来源：http://dali.shangyingyoupin.top/Article/details/gtgsvrbpou.html

TS:   resp.ok;  resp.status
来源：http://dali.daxiang520.top/Article/details/gtzaxarylv.html

Java: resp.statusCode()
来源：http://dali.hongshengwenyu.top/Article/details/gtuhzujcyn.html

Go:   resp.StatusCode
来源：http://dali.0kj1m.cn/Article/details/gtziwjthpv.html

Ruby: resp.code.to_i
来源：http://dali.yonumen.top/Article/details/gthcwrqiei.html

C#:   (int)resp.StatusCode
来源：http://dali.ybcxt.top/Article/details/gtdxbzvvqi.html

[L08] 并发请求多个地址
来源：http://dali.zhoulong.xyz/Article/details/gtwtwasomn.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shzxlz.cn/Article/details/gtmsvieltc.html

PHP:  curl_multi_init() 系列
来源：http://dali.redwolf501.top/Article/details/gthlinbmir.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttehnykde.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgufenzy.top/Article/details/gtvsyinnye.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.c1oappe.top/Article/details/gtxbmtgqvx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sysykeji.top/Article/details/gtlceuudrg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnuwpapwv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.redwolf501.top/Article/details/gttmztbrlz.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtctzufjgu.html

M. 命令行 / 进程 / 环境
来源：http://dali.nanxuanxn.top/Article/details/gthwitaucr.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtoyzlergw.html

[M01] 读取命令行参数
来源：http://dali.zdqjudy.top/Article/details/gtgmxlsuje.html

Py:   sys.argv[1:]
来源：http://dali.gzhubu.top/Article/details/gtegqzjbra.html

PHP:  $argv;  $argc;
来源：http://dali.sufxvd.cn/Article/details/gtceobruuy.html

JS:   process.argv.slice(2)
来源：http://dali.cheryme.top/Article/details/gtwvgassto.html

TS:   process.argv.slice(2)
来源：http://dali.gaohongyu789.top/Article/details/gtduisnbsr.html

Java: args 数组（main 方法参数）
来源：http://dali.cashguo.top/Article/details/gtugojtcdz.html

Go:   os.Args[1:]
来源：http://dali.xinyue.icu/Article/details/gtvrzatrwk.html

Ruby: ARGV
来源：http://dali.bjfxy.top/Article/details/gtxgbwzzwn.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtapmgawgl.html

[M02] 读取环境变量
来源：http://dali.daxiang520.top/Article/details/gtzufaagzs.html

Py:   os.environ.get("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gtkkxabkxp.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xuetiantiany.cn/Article/details/gtnlblmeaq.html

JS:   process.env.HOME
来源：http://dali.zhongyouzk.top/Article/details/gtxhghbupk.html

TS:   process.env.HOME
来源：http://dali.gotoacloud.top/Article/details/gtgblzpzak.html

Java: System.getenv("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gthsvicvik.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinqigufen.top/Article/details/gtrbewnsfh.html

Ruby: ENV["HOME"]
来源：http://dali.chenzaomai.com/Article/details/gtpulhgwqr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.haohaochexian.top/Article/details/gtkqloiyhb.html

[M03] 执行外部命令
来源：http://dali.yvedp.cn/Article/details/gtjefcvqhv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cashguo.top/Article/details/gtkvbjhdkm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.chenjidiqi.icu/Article/details/gtimtylwkt.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgfzy.top/Article/details/gtpbzxmxjd.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shuidangran.top/Article/details/gttblniqqu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.aizwys.cn/Article/details/gtvgjweast.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xziqi.cn/Article/details/gtugkyoils.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hfpthk.cn/Article/details/gthexriakm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.316326.xyz/Article/details/gtjrisboig.html

[M04] 获取当前工作目录
来源：http://dali.chenjidiqi.icu/Article/details/gtstrvrhza.html

Py:   os.getcwd()
来源：http://dali.sxryk.cn/Article/details/gtiglpdvmc.html

PHP:  getcwd();
来源：http://dali.316326.xyz/Article/details/gtcvlkzjeq.html

JS:   process.cwd()
来源：http://dali.hnqzz.top/Article/details/gturrhiqvj.html

TS:   process.cwd()
来源：http://dali.sweek.top/Article/details/gtknfocfpo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.meibo888.top/Article/details/gtumgjlxrm.html

Go:   os.Getwd()
来源：http://dali.bjfxy.top/Article/details/gtgyldjhpn.html

Ruby: Dir.pwd
来源：http://dali.guannengcc.top/Article/details/gtckqkctvw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.tanke756.top/Article/details/gtgeuckiet.html

[M05] 设置退出码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjvekdcxv.html

Py:   sys.exit(1)
来源：http://dali.cashguo.top/Article/details/gtvmaeyfal.html

PHP:  exit(1);
来源：http://dali.hfpthk.cn/Article/details/gtrpcpdoem.html

JS:   process.exit(1)
来源：http://dali.yj20258888.top/Article/details/gtctviyhni.html

TS:   process.exit(1)
来源：http://dali.fengsongda.top/Article/details/gtkkqsxcpk.html

Java: System.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtderjzuri.html

Go:   os.Exit(1)
来源：http://dali.yj20258888.top/Article/details/gtrjnpfyul.html

Ruby: exit 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtibfdgpbj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.havefunace.top/Article/details/gtrwgnhcve.html

[M06] 向标准错误输出
来源：http://dali.fzhhl.top/Article/details/gtnxmzxgga.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shzxlz.cn/Article/details/gtyzxgnhdl.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.nanxuanxn.top/Article/details/gtkvhmxnxe.html

JS:   console.error("err")
来源：http://dali.jianghu66.top/Article/details/gtddnrcvvv.html

TS:   console.error("err")
来源：http://dali.zhiwuduotai.top/Article/details/gtgoaiyrwe.html

Java: System.err.println("err")
来源：http://dali.yuxming.cn/Article/details/gtexsyyozp.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yuxming.cn/Article/details/gtsmiqtbqu.html

Ruby: warn "err"
来源：http://dali.nwbrower.top/Article/details/gtgbicxrvr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ehwqpu.com/Article/details/gtphclxtkx.html

[M07] 判断是否为主入口
来源：http://dali.yangfankeji.com/Article/details/gtshfbkhia.html

Py:   if __name__ == "__main__":
来源：http://dali.aizwys.cn/Article/details/gtrdjfylwb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yvedp.cn/Article/details/gtoddogibo.html

JS:   require.main === module
来源：http://dali.yueranfly.top/Article/details/gtoskwlsyx.html

TS:   require.main === module
来源：http://dali.hfpthk.cn/Article/details/gtuxpqirxu.html

Java: public static void main(String[] args)
来源：http://dali.yj202588.top/Article/details/gtibvdbnad.html

Go:   func main()
来源：http://dali.yj20258888.top/Article/details/gtzgdftmbn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cashguo.top/Article/details/gtflcggwcs.html

C#:   static void Main(string[] args)
来源：http://dali.daria6918.cn/Article/details/gtelgxakaz.html

[M08] 获取系统与运行时信息
来源：http://dali.yanxiufei.cn/Article/details/gtvbmwqwup.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinghuilouyu.cn/Article/details/gttdhtalhi.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zycfv.cn/Article/details/gtgvxijwsy.html

JS:   process.platform;  process.version
来源：http://dali.cucudq.cn/Article/details/gtsliwjoii.html

TS:   process.platform;  process.version
来源：http://dali.gaohongyu789.top/Article/details/gtehcwztzp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ydzc1.top/Article/details/gthjdclfsz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.nanxuanxn.top/Article/details/gtlpyjasbe.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhongyouzk.top/Article/details/gtvotdijce.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.wangshuangyany.cn/Article/details/gttgzorkln.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtplkbcyce.html

N. 数据结构与算法
来源：http://dali.tian-w.cn/Article/details/gtbgeccidx.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvrwjznqs.html

[N01] 二分查找（有序数组）
来源：http://dali.9152youxi.cn/Article/details/gtzbeybzdv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.daria6918.cn/Article/details/gtlepcbflt.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.andypj.xyz/Article/details/gttlsrvdtt.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.birdmap.top/Article/details/gtfqizjrqy.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.smart0.xyz/Article/details/gtiyhzvjhn.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yj20258888.top/Article/details/gtwsknxqom.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hammf.cn/Article/details/gtnwkriafs.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.vqdsnc.cn/Article/details/gtnenhykte.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.sysykeji.top/Article/details/gtdgmdzmye.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.smart0.xyz/Article/details/gtlmrpbnze.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.snrcjt.cn/Article/details/gteracxuss.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.aizwys.cn/Article/details/gttkxkbrxn.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtveqlmtzh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yangfankeji.com/Article/details/gtayoklpzk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zdqjudy.top/Article/details/gtpopwfmcr.html

Go:   slices.Sort(arr)
来源：http://dali.tianlin.xyz/Article/details/gtnacrjhmo.html

Ruby: arr.sort
来源：http://dali.redwolf501.top/Article/details/gtqgfouluk.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jianghu66.top/Article/details/gttryaznla.html

[N03] 快速排序（分治示例）
来源：http://dali.ehwqpu.com/Article/details/gtyrniplmd.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yj20258.top/Article/details/gtuohgmgev.html


<!-- 参考信息 -->