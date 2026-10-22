代发 wailian999

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shangyingyoupin.top/Article/details/gtybjpxijk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shangyingyoupin.top/Article/details/gtzeuuonpc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jqgufenzy.top/Article/details/gtnklskfpq.html

[J06] 计算两时间之差
来源：http://dali.havefunace.top/Article/details/gtovwegbvf.html

Py:   (end - start).total_seconds()
来源：http://dali.jqgufenzy.top/Article/details/gtsutpyvpe.html

PHP:  $end->diff($start)->days;
来源：http://dali.iojbl.cn/Article/details/gtnjhguqiw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhijiandao.cn/Article/details/gtsmqkylfi.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.tian-w.cn/Article/details/gtbksmizbu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinqigufen.top/Article/details/gtnfbxrgxx.html

Go:   end.Sub(start).Hours()
来源：http://dali.yvedp.cn/Article/details/gtlnvpcnnw.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhaomingkeji.xyz/Article/details/gttqsmnzsa.html

C#:   (end - start).TotalSeconds
来源：http://dali.shanyushiyangkeji.top/Article/details/gtouqjzcxl.html

[J07] 比较两个日期
来源：http://dali.nanxinkj.top/Article/details/gtozyfnhtb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cheryme.top/Article/details/gtxrtyykol.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shuidangran.top/Article/details/gtbnbyxana.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258.top/Article/details/gthcpgpoqj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258.top/Article/details/gtqbufgyfp.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.aizwys.cn/Article/details/gtkcjuhgqp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gotoacloud.top/Article/details/gteeymbirh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gaohongyu789.top/Article/details/gtjshhpnky.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinghuilouyu.cn/Article/details/gtppbrewmj.html

[J08] 提取年月日与星期
来源：http://dali.yvedp.cn/Article/details/gtcqkpbbaj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.dashuyun.cn/Article/details/gteugajuyb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jqgufenzy.top/Article/details/gtksvvyeys.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hnqzz.top/Article/details/gtpcbqtoty.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zycfv.cn/Article/details/gtothuqfgb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yueranfly.top/Article/details/gtjbxqxkel.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gotoacloud.top/Article/details/gtycavmtxz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.aizwys.cn/Article/details/gtirzsxiof.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cashguo.top/Article/details/gtulanwgdj.html

[J09] 时区处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzqgruiwa.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gaohongyu789.top/Article/details/gtnllmeqos.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.haohaochexian.top/Article/details/gtvcmxeqye.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yvedp.cn/Article/details/gtjteztyfr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhengqikj.top/Article/details/gtophdmkgt.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinqigufen.top/Article/details/gtrdabkyod.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xuanzx.com/Article/details/gtxasungoy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jyoumei.cn/Article/details/gtbyofjtih.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.tanke756.top/Article/details/gtrlhcayrz.html

[J10] 取今天 / 本月第一天
来源：http://dali.gzhubu.top/Article/details/gtthpicpoc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.havefunace.top/Article/details/gtsrzkxolz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xylfe.cn/Article/details/gtbvqobsia.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zycfv.cn/Article/details/gtkmkneytb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.bjfxy.top/Article/details/gtcesmnfbs.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sysykeji.top/Article/details/gtpasetirl.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yanxiufei.cn/Article/details/gtqfdiydta.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.kuanghao11.cn/Article/details/gtzhnxfpni.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.meibo888.top/Article/details/gtzrnwlovk.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gteeuhuzxe.html

K. JSON 与序列化
来源：http://dali.haohaochexian.top/Article/details/gtuzrvjghl.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtcqrsybox.html

[K01] 对象转 JSON 字符串
来源：http://dali.chenlongwang.top/Article/details/gtxqknconq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj20258888.top/Article/details/gtnkyngwah.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jlsjyb.cn/Article/details/gtiedpfgbo.html

JS:   JSON.stringify(obj)
来源：http://dali.zycfv.cn/Article/details/gtrokwzhld.html

TS:   JSON.stringify(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtivcokmcp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.tianlin.xyz/Article/details/gtdcmlmqch.html

Go:   json.Marshal(obj)
来源：http://dali.xziqi.cn/Article/details/gtcblhkwbg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.andypj.xyz/Article/details/gtkxdfxzum.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.dashuyun.cn/Article/details/gtrimkzkqu.html

[K02] JSON 字符串转对象
来源：http://dali.yvedp.cn/Article/details/gtyjghhmmu.html

Py:   json.loads(s)
来源：http://dali.tanke756.top/Article/details/gtkpnblikg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cqqwz.cn/Article/details/gtvdckmpmq.html

JS:   JSON.parse(s)
来源：http://dali.ybcxt.top/Article/details/gtnobirrfb.html

TS:   JSON.parse(s)
来源：http://dali.yangfankeji.com/Article/details/gtthvwwwpq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.mhx1999.top/Article/details/gtxcezxiev.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkykxzstt.html

Ruby: JSON.parse(s)
来源：http://dali.ybcxt.top/Article/details/gtkbewdomg.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cqqwz.cn/Article/details/gtxqygxjlk.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.wangshuangyany.cn/Article/details/gtngknbvop.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.wangshuangyany.cn/Article/details/gtjhnzpcya.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yvedp.cn/Article/details/gtwbnbaiov.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtzzyiskck.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hywenlv.cn/Article/details/gtkjrbtpoh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.redwolf501.top/Article/details/gthmotadvd.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.feifeiyinyue.top/Article/details/gtjjcxodwb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.mhx1999.top/Article/details/gtqtmgsxwu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiqsssiak.html

[K04] 读取 JSON 文件
来源：http://dali.c1oappe.top/Article/details/gtmtsgvqrm.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gzhubu.top/Article/details/gtkukbyzkx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.wangshuangyany.cn/Article/details/gtzupasdzm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xuetiantiany.cn/Article/details/gtotdgzino.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tianlin.xyz/Article/details/gtapiblofm.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gtkkddphzv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.guannengcc.top/Article/details/gtjdsgkxyv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.daria6918.cn/Article/details/gtymmkmpyf.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ppjwa.cn/Article/details/gtsanuujjg.html

[K05] 深拷贝对象
来源：http://dali.yj20258888.top/Article/details/gtgnhgljxv.html

Py:   copy.deepcopy(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtknpbhdvy.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shangyingyoupin.top/Article/details/gtcqtousfh.html

JS:   structuredClone(obj)
来源：http://dali.fzhhl.top/Article/details/gtprfdentg.html

TS:   structuredClone(obj)
来源：http://dali.chenzaomai.com/Article/details/gthytkqvgc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.smart0.xyz/Article/details/gtjhjarqas.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinqigfzy.top/Article/details/gtrgdtmrpq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhongyouzk.top/Article/details/gtwanqoydh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.dashuyun.cn/Article/details/gtzjukmhcm.html

[K06] 解析 URL 查询串
来源：http://dali.nanxinkj.top/Article/details/gtupgxrqbq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cdnleiting.top/Article/details/gtslufcxkf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.tanke756.top/Article/details/gttxrzdyri.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guannengcc.top/Article/details/gtrtgsdsjm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jlsjyb.cn/Article/details/gttfjzygnj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinqigufen.top/Article/details/gtyiwclzbm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gtbaortijf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.fengsongda.top/Article/details/gtjofscnwa.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.kuanghao11.cn/Article/details/gtyxtqbaem.html

[K07] 进制转换
来源：http://dali.chenzaomai.com/Article/details/gtfckhnoju.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthibtpkwo.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.tianlin.xyz/Article/details/gtiwnjfnqi.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cheryme.top/Article/details/gtdgisulyv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gtkrmvvsmb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gtzvqbkomo.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.haohaochexian.top/Article/details/gtayfkmygo.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cashguo.top/Article/details/gtqrwtglce.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cheryme.top/Article/details/gthlwmwjwn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.316326.xyz/Article/details/gtlryfqyav.html

Py:   pickle.dumps(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxvkuuxbi.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gteivmkvrn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.316326.xyz/Article/details/gtzzpetgzr.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.aizwys.cn/Article/details/gtapfzzuoh.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gogol.net.cn/Article/details/gtehbipdtq.html

Go:   encoding/gob
来源：http://dali.yanxiufei.cn/Article/details/gtaumzyjbd.html

Ruby: Marshal.dump(obj)
来源：http://dali.sufxvd.cn/Article/details/gtfljyqzan.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgydsumua.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtvipnkruq.html

L. 网络请求
来源：http://dali.hnxiangtu.top/Article/details/gtapbdzzoa.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gthwbgxgar.html

[L01] 发送 GET 请求
来源：http://dali.yongpay.top/Article/details/gtxpdmqqab.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hfpthk.cn/Article/details/gtjdqicmlh.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gogol.net.cn/Article/details/gtgutofcnz.html

JS:   await fetch(url)
来源：http://dali.nwbrower.top/Article/details/gteppfuqcg.html

TS:   await fetch(url)
来源：http://dali.yuxming.cn/Article/details/gtwhqceiri.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.havefunace.top/Article/details/gtxlfnyarj.html

Go:   resp, err := http.Get(url)
来源：http://dali.fzhhl.top/Article/details/gtnwjmnjan.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jqgufenzy.top/Article/details/gttsfqxmus.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xuetiantiany.cn/Article/details/gtxxtjgeeh.html

[L02] 发送 POST JSON
来源：http://dali.sweek.top/Article/details/gtasrvtboq.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jianghu66.top/Article/details/gtlfzrzdsn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.bjfxy.top/Article/details/gtcxpgufxj.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdworqwrs.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhongyouzk.top/Article/details/gtrxxmzslu.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.316326.xyz/Article/details/gtmtuohocj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.vqdsnc.cn/Article/details/gtdldhoaga.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zdqjudy.top/Article/details/gtnyrxtkbk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shuidangran.top/Article/details/gtjixctruz.html

[L03] 设置自定义请求头
来源：http://dali.gotoacloud.top/Article/details/gtnynhvebs.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinghuilouyu.cn/Article/details/gtfvcnqrff.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cqqwz.cn/Article/details/gtvsbyhqgp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenzaomai.com/Article/details/gtqyccdlsj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenjidiqi.icu/Article/details/gtjaqgpszo.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinqigufen.top/Article/details/gtdsbhygdp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yueranfly.top/Article/details/gtnmfysktf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbpjdroxa.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yonumen.top/Article/details/gtcvxdvmiq.html

[L04] 设置超时
来源：http://dali.jlsjyb.cn/Article/details/gtcdjkvijk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinqigfzy.top/Article/details/gttqcpolaj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.mhx1999.top/Article/details/gtpwojkzeb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenzaomai.com/Article/details/gthlsozbdx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ydzc1.top/Article/details/gtjkuoqumu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqupibjgs.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hnqzz.top/Article/details/gtisqxnbkt.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yvedp.cn/Article/details/gtrvsmkavs.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhengqikj.top/Article/details/gttbhjtuyd.html

[L05] 上传文件（multipart）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthqfevzcc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yvedp.cn/Article/details/gtgjnzzwzr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yonumen.top/Article/details/gtbbchahvc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.snrcjt.cn/Article/details/gtokusfxbt.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenzaomai.com/Article/details/gtotzvtirw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gaohongyu789.top/Article/details/gtsmpdtddd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.fzhhl.top/Article/details/gtuokuofht.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.wangdashe.top/Article/details/gtvmgvvibu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtdwhdawlx.html

[L06] 解析响应为 JSON
来源：http://dali.nwbrower.top/Article/details/gtalrwlohw.html

Py:   resp.json()
来源：http://dali.guowangkeji.top/Article/details/gtftccxurg.html

PHP:  json_decode($body, true);
来源：http://dali.snrcjt.cn/Article/details/gttjjvrqtj.html

JS:   await resp.json()
来源：http://dali.zhengqikj.top/Article/details/gtsfeztzkn.html

TS:   await resp.json()
来源：http://dali.jyoumei.cn/Article/details/gthavukvzw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ppjwa.cn/Article/details/gthfscgiwf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ybcxt.top/Article/details/gtejehgxbb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.guowangkeji.top/Article/details/gtvwfbxefm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.feifeiyinyue.top/Article/details/gtwzglblgi.html

[L07] 处理 HTTP 状态码
来源：http://dali.nanxinkj.top/Article/details/gtlmysaavu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.vqdsnc.cn/Article/details/gtlhgcaojk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shzxlz.cn/Article/details/gtfjhwtzxy.html

JS:   resp.ok;  resp.status
来源：http://dali.chenlongwang.top/Article/details/gtuxfoqlsi.html

TS:   resp.ok;  resp.status
来源：http://dali.dashuyun.cn/Article/details/gttakjxlve.html

Java: resp.statusCode()
来源：http://dali.andypj.xyz/Article/details/gtqizrmjby.html

Go:   resp.StatusCode
来源：http://dali.yuxming.cn/Article/details/gtejelcvvc.html

Ruby: resp.code.to_i
来源：http://dali.birdmap.top/Article/details/gtzpgnelxw.html

C#:   (int)resp.StatusCode
来源：http://dali.c1oappe.top/Article/details/gtlitkosof.html

[L08] 并发请求多个地址
来源：http://dali.c1oappe.top/Article/details/gtpuxjtyfc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.birdmap.top/Article/details/gtpcwknjyu.html

PHP:  curl_multi_init() 系列
来源：http://dali.sweek.top/Article/details/gtwcnrrcgp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpenpgeoc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuxming.cn/Article/details/gtfxoaymmr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.dashuyun.cn/Article/details/gtjayrgfgh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xylfe.cn/Article/details/gthnejtxug.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hnqzz.top/Article/details/gtnxjrprsv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yanxiufei.cn/Article/details/gtglwyvnor.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtxdgzbndm.html

M. 命令行 / 进程 / 环境
来源：http://dali.wangshuangyany.cn/Article/details/gtswbglyjd.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtrppkhihr.html

[M01] 读取命令行参数
来源：http://dali.yj20258888.top/Article/details/gtcmjikqkq.html

Py:   sys.argv[1:]
来源：http://dali.xziqi.cn/Article/details/gtvvuoofyt.html

PHP:  $argv;  $argc;
来源：http://dali.wangdashe.top/Article/details/gtewgwpavm.html

JS:   process.argv.slice(2)
来源：http://dali.chenjidiqi.icu/Article/details/gtxrpjjpad.html

TS:   process.argv.slice(2)
来源：http://dali.sweek.top/Article/details/gtnychxhmw.html

Java: args 数组（main 方法参数）
来源：http://dali.jyoumei.cn/Article/details/gtupggcrvn.html

Go:   os.Args[1:]
来源：http://dali.jiagoushi.top/Article/details/gtonrkjsfz.html

Ruby: ARGV
来源：http://dali.vqdsnc.cn/Article/details/gtycofspvy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hongshengwenyu.top/Article/details/gtiadtbwku.html

[M02] 读取环境变量
来源：http://dali.iojbl.cn/Article/details/gtjofowhki.html

Py:   os.environ.get("HOME")
来源：http://dali.gzhubu.top/Article/details/gtbcfzfptq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xziqi.cn/Article/details/gtnkdtcttu.html

JS:   process.env.HOME
来源：http://dali.zhengqikj.top/Article/details/gtdcmhnnfc.html

TS:   process.env.HOME
来源：http://dali.daria6918.cn/Article/details/gtprqllpms.html

Java: System.getenv("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gtjmgxsyaz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yj202588.top/Article/details/gtmjfaywfd.html

Ruby: ENV["HOME"]
来源：http://dali.guannengcc.top/Article/details/gtvwmspfmu.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gtzxyhjvex.html

[M03] 执行外部命令
来源：http://dali.yangfankeji.com/Article/details/gtggcejgzb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yueranfly.top/Article/details/gtjubrcqgy.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxkzkxpjg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.bjfxy.top/Article/details/gtjtxindtk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtozxlvurp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jiagoushi.top/Article/details/gtykujadwq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gzhubu.top/Article/details/gtzzcbjnsy.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.iojbl.cn/Article/details/gttrwcdpts.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ppjwa.cn/Article/details/gtctkobokv.html

[M04] 获取当前工作目录
来源：http://dali.yangfankeji.com/Article/details/gtdoozbjio.html

Py:   os.getcwd()
来源：http://dali.xinyue.icu/Article/details/gtydyqrgvm.html

PHP:  getcwd();
来源：http://dali.tanke756.top/Article/details/gtiuqtjvom.html

JS:   process.cwd()
来源：http://dali.gotoacloud.top/Article/details/gtnaftarju.html

TS:   process.cwd()
来源：http://dali.yj20258.top/Article/details/gtjkpukvvx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.redwolf501.top/Article/details/gtxmcshzhx.html

Go:   os.Getwd()
来源：http://dali.sufxvd.cn/Article/details/gtljytfkga.html

Ruby: Dir.pwd
来源：http://dali.ehwqpu.com/Article/details/gtiksqirqr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.birdmap.top/Article/details/gtpqeyqwzv.html

[M05] 设置退出码
来源：http://dali.gotoacloud.top/Article/details/gtduzfcqup.html

Py:   sys.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmzjkgylu.html

PHP:  exit(1);
来源：http://dali.snrcjt.cn/Article/details/gtarygdwdv.html

JS:   process.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtclgbiegw.html

TS:   process.exit(1)
来源：http://dali.sxryk.cn/Article/details/gtexkjhhnj.html

Java: System.exit(1)
来源：http://dali.sxryk.cn/Article/details/gtshpwsbtm.html

Go:   os.Exit(1)
来源：http://dali.tian-w.cn/Article/details/gtkawzustw.html

Ruby: exit 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkzppalrg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yonumen.top/Article/details/gtbjuuotly.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gtsrkfugmx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ivvv.top/Article/details/gtujbjiftx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ehwqpu.com/Article/details/gtjuzdwunl.html

JS:   console.error("err")
来源：http://dali.snrcjt.cn/Article/details/gtyhiefvtw.html

TS:   console.error("err")
来源：http://dali.cheryme.top/Article/details/gtqzzwxdad.html

Java: System.err.println("err")
来源：http://dali.tian-w.cn/Article/details/gthclzzcca.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zdqjudy.top/Article/details/gtvcbobqth.html

Ruby: warn "err"
来源：http://dali.ydzc1.top/Article/details/gtqjfqispk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hfpthk.cn/Article/details/gtaypamfag.html

[M07] 判断是否为主入口
来源：http://dali.yangfankeji.com/Article/details/gtyzwrejxk.html

Py:   if __name__ == "__main__":
来源：http://dali.yvedp.cn/Article/details/gtgtyharre.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.mhx1999.top/Article/details/gtaqxhowin.html

JS:   require.main === module
来源：http://dali.sweek.top/Article/details/gtjsbmlyje.html

TS:   require.main === module
来源：http://dali.hnqzz.top/Article/details/gtmagnanqf.html

Java: public static void main(String[] args)
来源：http://dali.xylfe.cn/Article/details/gtaglnjhyv.html

Go:   func main()
来源：http://dali.daria6918.cn/Article/details/gtoscbrfud.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shuidangran.top/Article/details/gtpcmwfnrn.html

C#:   static void Main(string[] args)
来源：http://dali.hnqzz.top/Article/details/gtivdmbjoj.html

[M08] 获取系统与运行时信息
来源：http://dali.jinghuilouyu.cn/Article/details/gtthuyprfq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhengqikj.top/Article/details/gtxqmvzfmu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhengqikj.top/Article/details/gtunoanbfz.html

JS:   process.platform;  process.version
来源：http://dali.daria6918.cn/Article/details/gtmjswmkaq.html

TS:   process.platform;  process.version
来源：http://dali.xuetiantiany.cn/Article/details/gtqlvsyisw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gaohongyu789.top/Article/details/gtdniygbis.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yuxming.cn/Article/details/gteempljzm.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.redwolf501.top/Article/details/gtxzobhtfr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sysykeji.top/Article/details/gtnkgonncw.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtqivrqzjs.html

N. 数据结构与算法
来源：http://dali.ivvv.top/Article/details/gtyrknfxwb.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtqqlrofes.html

[N01] 二分查找（有序数组）
来源：http://dali.gogol.net.cn/Article/details/gtyutzwthq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jianghu66.top/Article/details/gtixtclnsz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yuxming.cn/Article/details/gtvhkixajq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dianchejie.cn/Article/details/gtalzrewhi.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.kuanghao11.cn/Article/details/gtwdmewczx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.daria6918.cn/Article/details/gtlqxwbuqd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtlzkczcxb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zycfv.cn/Article/details/gtlhkhqzty.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cashguo.top/Article/details/gtsrtorior.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.nwbrower.top/Article/details/gtafrspqlc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zycfv.cn/Article/details/gtohhhiwlb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ppjwa.cn/Article/details/gtdwmqrzsf.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shzxlz.cn/Article/details/gtaasknwag.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hongshengwenyu.top/Article/details/gtpvapfkrg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.fengsongda.top/Article/details/gtlkaycvqo.html

Go:   slices.Sort(arr)
来源：http://dali.gotoacloud.top/Article/details/gtwrtausse.html

Ruby: arr.sort
来源：http://dali.cqqwz.cn/Article/details/gtexktsvsr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yongpay.top/Article/details/gtuderbhco.html

[N03] 快速排序（分治示例）
来源：http://dali.tianlin.xyz/Article/details/gtmrclqewb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.haohaochexian.top/Article/details/gtyazlxven.html

PHP:  // 递归实现，或用 usort
来源：http://dali.svipenyu.cn/Article/details/gtacfmyzqj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sxryk.cn/Article/details/gturhgofco.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cheryme.top/Article/details/gtkdvrtaul.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xziqi.cn/Article/details/gtyhnmvugf.html


<!-- 参考信息 -->