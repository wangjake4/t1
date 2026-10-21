代发 wailian999

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hysaishi.cn/Article/details/gtuwrjghsb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ybcxt.top/Article/details/gtinjpeucq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yongpay.top/Article/details/gtujexlzgg.html

[J06] 计算两时间之差
来源：http://dali.ybcxt.top/Article/details/gtlyznzpbh.html

Py:   (end - start).total_seconds()
来源：http://dali.ivvv.top/Article/details/gtlhuzqkne.html

PHP:  $end->diff($start)->days;
来源：http://dali.yvedp.cn/Article/details/gtqigzdfec.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.c1oappe.top/Article/details/gthydlrvex.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hywenlv.cn/Article/details/gtfrbujskn.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.svipenyu.cn/Article/details/gtxgwvpbeu.html

Go:   end.Sub(start).Hours()
来源：http://dali.havefunace.top/Article/details/gtdsprtpjh.html

Ruby: end - start                 # 返回秒数
来源：http://dali.smart0.xyz/Article/details/gtswszcwst.html

C#:   (end - start).TotalSeconds
来源：http://dali.hfpthk.cn/Article/details/gtphmkobjq.html

[J07] 比较两个日期
来源：http://dali.iojbl.cn/Article/details/gtprcmlhsp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvlxokmgw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.smart0.xyz/Article/details/gtlntpsaoa.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gotoacloud.top/Article/details/gtujrgtgir.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.meibo888.top/Article/details/gtuoauutmv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yj20258888.top/Article/details/gtojufzbpb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yvedp.cn/Article/details/gtarwvsxus.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yj20258.top/Article/details/gtzqxirkez.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.0kj1m.cn/Article/details/gtegqhfcmy.html

[J08] 提取年月日与星期
来源：http://dali.snrcjt.cn/Article/details/gtjkwyauzy.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ehwqpu.com/Article/details/gtrpxnszls.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.316326.xyz/Article/details/gtxmguppgf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.aizwys.cn/Article/details/gtsusjrsdu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhoulong.xyz/Article/details/gtcqrcakqs.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.nanxinkj.top/Article/details/gtprnaxbuo.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yj20258.top/Article/details/gtzaonpozj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.316326.xyz/Article/details/gtxitlropz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hammf.cn/Article/details/gteryvapbl.html

[J09] 时区处理
来源：http://dali.zhixingplan.top/Article/details/gthhkzkati.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.316326.xyz/Article/details/gtvwoqoioa.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.haohaochexian.top/Article/details/gtertefwvw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.9152youxi.cn/Article/details/gtvxkmtjpz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aibaodan.cn/Article/details/gtdcqeadxt.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ydzc1.top/Article/details/gtwwgheiuw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhengqikj.top/Article/details/gtmbdismtp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinqigfzy.top/Article/details/gtykyobhat.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yj20258.top/Article/details/gtogmumnlq.html

[J10] 取今天 / 本月第一天
来源：http://dali.jiagoushi.top/Article/details/gtfmthhpet.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.snrcjt.cn/Article/details/gtjnjktnnv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.iojbl.cn/Article/details/gtfnubqdxd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.meibo888.top/Article/details/gtdutipsuj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.dianchejie.cn/Article/details/gtbofwsoxb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yonumen.top/Article/details/gthhniepll.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.c1oappe.top/Article/details/gtvbtkaojt.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.aibaodan.cn/Article/details/gtksralxtf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkgwjwqwo.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtazfmnbaf.html

K. JSON 与序列化
来源：http://dali.xuetiantiany.cn/Article/details/gtkzamrcgm.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtfhzoktbf.html

[K01] 对象转 JSON 字符串
来源：http://dali.shuidangran.top/Article/details/gtjvcsolhc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gogol.net.cn/Article/details/gtsxseyaty.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.dianchejie.cn/Article/details/gttlfkzsma.html

JS:   JSON.stringify(obj)
来源：http://dali.pycfn.com/Article/details/gtpeynrqhi.html

TS:   JSON.stringify(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtofcbaikt.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gaohongyu789.top/Article/details/gtxzlnppwe.html

Go:   json.Marshal(obj)
来源：http://dali.hfpthk.cn/Article/details/gtdevsprag.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yonumen.top/Article/details/gtsqznrqkv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sxryk.cn/Article/details/gtthbashws.html

[K02] JSON 字符串转对象
来源：http://dali.snrcjt.cn/Article/details/gtyoewaseb.html

Py:   json.loads(s)
来源：http://dali.gaohongyu789.top/Article/details/gteriwyyye.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhongyouzk.top/Article/details/gtynihgtot.html

JS:   JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtzlyhnpra.html

TS:   JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtllpjjazb.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hammf.cn/Article/details/gtuaxbrzep.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gtsafytttb.html

Ruby: JSON.parse(s)
来源：http://dali.wangshuangyany.cn/Article/details/gttxbbavdj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.nanxinkj.top/Article/details/gtahjurdjt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.svipenyu.cn/Article/details/gtbwmiwvwr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.c1oappe.top/Article/details/gticdizbej.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sxryk.cn/Article/details/gtqxyvwfpr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jianghu66.top/Article/details/gtzsmnzdwi.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gogol.net.cn/Article/details/gtyvxjfazd.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tianlin.xyz/Article/details/gtuejvlgrb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shanyushiyangtech.top/Article/details/gthjjurics.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhengqikj.top/Article/details/gtiovofmge.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.svipenyu.cn/Article/details/gtxbqtnzck.html

[K04] 读取 JSON 文件
来源：http://dali.fzhhl.top/Article/details/gtmsqbihoo.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cashguo.top/Article/details/gtvgyzgjuh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yanxiufei.cn/Article/details/gtcwccaeoz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hongshengwenyu.top/Article/details/gtqsvdztya.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aibaodan.cn/Article/details/gtvlrzlnvs.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.316326.xyz/Article/details/gtyiojsagm.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.kuanghao11.cn/Article/details/gtpitthrfq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinqigfzy.top/Article/details/gtaycvvbpz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.c1oappe.top/Article/details/gtviojtyqw.html

[K05] 深拷贝对象
来源：http://dali.shuidangran.top/Article/details/gtdplpawsy.html

Py:   copy.deepcopy(obj)
来源：http://dali.tianlin.xyz/Article/details/gtypuiwklf.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sysykeji.top/Article/details/gtmdiriesr.html

JS:   structuredClone(obj)
来源：http://dali.316326.xyz/Article/details/gtupvnyaal.html

TS:   structuredClone(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlbpmbwdo.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.gotoacloud.top/Article/details/gtblkjzenh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cheryme.top/Article/details/gttqttiidm.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.sysykeji.top/Article/details/gtqdrdhwmt.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ivvv.top/Article/details/gtedkywogv.html

[K06] 解析 URL 查询串
来源：http://dali.quarkkingdee.top/Article/details/gtzzdrazrv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.iojbl.cn/Article/details/gtjlklaxzt.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yueranfly.top/Article/details/gthwnpxqmb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xziqi.cn/Article/details/gtkqbwqxvr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sysykeji.top/Article/details/gtmnasiynv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ppjwa.cn/Article/details/gtvrqswfze.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.dianchejie.cn/Article/details/gtfayglsrz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gtxgdpvxwj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hfpthk.cn/Article/details/gtruiorajc.html

[K07] 进制转换
来源：http://dali.yvedp.cn/Article/details/gtbkxlweak.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gtktsezdtl.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yj20258888.top/Article/details/gtrlllponf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.havefunace.top/Article/details/gtbzqrpxys.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnypbsone.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtxdivrkib.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.aibaodan.cn/Article/details/gtavrscopz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sweek.top/Article/details/gtpsfttjgz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gtmssjwsal.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jqgufenzy.top/Article/details/gtwgmfvluz.html

Py:   pickle.dumps(obj)
来源：http://dali.sysykeji.top/Article/details/gtuemiwofg.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yj20258.top/Article/details/gtewdpwmen.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yuanzhike.top/Article/details/gtqfsskhrs.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hfpthk.cn/Article/details/gtcuygawvq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hongshengwenyu.top/Article/details/gtfikbfrwj.html

Go:   encoding/gob
来源：http://dali.yongpay.top/Article/details/gtmzjiylbs.html

Ruby: Marshal.dump(obj)
来源：http://dali.316326.xyz/Article/details/gtapasarrg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyfmjiirl.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtryqctyyg.html

L. 网络请求
来源：http://dali.fengsongda.top/Article/details/gtapbgqhzp.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtdrkpkvpj.html

[L01] 发送 GET 请求
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrthvwryb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yanxiufei.cn/Article/details/gtymdabtsv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cqqwz.cn/Article/details/gtveqycpce.html

JS:   await fetch(url)
来源：http://dali.sufxvd.cn/Article/details/gtzyrtvrqg.html

TS:   await fetch(url)
来源：http://dali.zycfv.cn/Article/details/gtpivkcshm.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yongpay.top/Article/details/gtxqsxwcwt.html

Go:   resp, err := http.Get(url)
来源：http://dali.iojbl.cn/Article/details/gttyswfmim.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jlsjyb.cn/Article/details/gtkdaeckwv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gogol.net.cn/Article/details/gtbjsdgsga.html

[L02] 发送 POST JSON
来源：http://dali.sweek.top/Article/details/gtpbfwuhln.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cashguo.top/Article/details/gtvzpmavez.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gtqimamycb.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhengqikj.top/Article/details/gtwebirkoj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhongyouzk.top/Article/details/gtxxthdaae.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinghuilouyu.cn/Article/details/gtzprodndx.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yanxiufei.cn/Article/details/gtetvolfre.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shuidangran.top/Article/details/gtgyjmlxis.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yvedp.cn/Article/details/gtdxvmiqba.html

[L03] 设置自定义请求头
来源：http://dali.cashguo.top/Article/details/gtpdchlsbs.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.fzhhl.top/Article/details/gtxddbictp.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sufxvd.cn/Article/details/gtxwmnrfte.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shzxlz.cn/Article/details/gtrfoashob.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258888.top/Article/details/gteuxagfbb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shzxlz.cn/Article/details/gtrxkmbvsu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.wangdashe.top/Article/details/gtdvsgkvou.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.andypj.xyz/Article/details/gtkipkyhoz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.redwolf501.top/Article/details/gtgfcwpcmd.html

[L04] 设置超时
来源：http://dali.zhiwuduotai.top/Article/details/gtsbbqcfma.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ppjwa.cn/Article/details/gtyqcwwbpw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhiwuduotai.top/Article/details/gtuhdkuned.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yanxiufei.cn/Article/details/gttbaprxvi.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yueranfly.top/Article/details/gtxjkypbmk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoehbpbzq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.daxiang520.top/Article/details/gtbtcbhoyi.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.mhx1999.top/Article/details/gtthrzthec.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.pengpengdd.cyou/Article/details/gtrjgvyqux.html

[L05] 上传文件（multipart）
来源：http://dali.zhixingplan.top/Article/details/gtkkrsocxz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.daxiang520.top/Article/details/gtqbbijemw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jiagoushi.top/Article/details/gtqddhgugi.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.quarkkingdee.top/Article/details/gtoxwtngjc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.daria6918.cn/Article/details/gtdokcgjfn.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.nanxinkj.top/Article/details/gtvzckwrrf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gogol.net.cn/Article/details/gtchzkddyc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hongshengwenyu.top/Article/details/gtfupcovwj.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtffrxowfx.html

[L06] 解析响应为 JSON
来源：http://dali.yj202588.top/Article/details/gtxnwemhoh.html

Py:   resp.json()
来源：http://dali.yuanzhike.top/Article/details/gtdhatvboa.html

PHP:  json_decode($body, true);
来源：http://dali.xylfe.cn/Article/details/gtxzkaalht.html

JS:   await resp.json()
来源：http://dali.yueranfly.top/Article/details/gtjoynqywy.html

TS:   await resp.json()
来源：http://dali.yangfankeji.com/Article/details/gtlfzmurxj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhiwuduotai.top/Article/details/gtpeegufie.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xuanzx.com/Article/details/gthyjxnejd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhiwuduotai.top/Article/details/gtjcbvwqgy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.guannengcc.top/Article/details/gtimhwgoyt.html

[L07] 处理 HTTP 状态码
来源：http://dali.andypj.xyz/Article/details/gtixsnjadu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ivvv.top/Article/details/gtkzqmcvqs.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jianghu66.top/Article/details/gthtpmrtyd.html

JS:   resp.ok;  resp.status
来源：http://dali.ydzc1.top/Article/details/gtskabxgff.html

TS:   resp.ok;  resp.status
来源：http://dali.shzxlz.cn/Article/details/gtexyjlmxu.html

Java: resp.statusCode()
来源：http://dali.fzhhl.top/Article/details/gtzkkijdgb.html

Go:   resp.StatusCode
来源：http://dali.daxiang520.top/Article/details/gttldbyyji.html

Ruby: resp.code.to_i
来源：http://dali.yj20258.top/Article/details/gtoodewfek.html

C#:   (int)resp.StatusCode
来源：http://dali.shangyingyoupin.top/Article/details/gtkfupdtst.html

[L08] 并发请求多个地址
来源：http://dali.meibo888.top/Article/details/gtnylimnrs.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.9152youxi.cn/Article/details/gtccqktozn.html

PHP:  curl_multi_init() 系列
来源：http://dali.yonumen.top/Article/details/gtmcdmodzr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhixingplan.top/Article/details/gtjwngvhjq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gtopeckiba.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xuanzx.com/Article/details/gtkigyjwhi.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cashguo.top/Article/details/gtzmhlmhoq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.chenlongwang.top/Article/details/gtbfuvmuuj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.havefunace.top/Article/details/gtrjdeptxn.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtgwgijgta.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhongyouzk.top/Article/details/gtpxplcrrd.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtotdzhsaz.html

[M01] 读取命令行参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtjupbiqoi.html

Py:   sys.argv[1:]
来源：http://dali.gotoacloud.top/Article/details/gtekgmzrjn.html

PHP:  $argv;  $argc;
来源：http://dali.dashuyun.cn/Article/details/gtgtzluyay.html

JS:   process.argv.slice(2)
来源：http://dali.tianlin.xyz/Article/details/gtpjwnomjn.html

TS:   process.argv.slice(2)
来源：http://dali.chenlongwang.top/Article/details/gtpaowaqhb.html

Java: args 数组（main 方法参数）
来源：http://dali.havefunace.top/Article/details/gtjzcatvry.html

Go:   os.Args[1:]
来源：http://dali.smart0.xyz/Article/details/gtaebdwzmq.html

Ruby: ARGV
来源：http://dali.guannengcc.top/Article/details/gtsernwgrm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xylfe.cn/Article/details/gthxfxfdas.html

[M02] 读取环境变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwsavdnpm.html

Py:   os.environ.get("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gtqanrxpzw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.daria6918.cn/Article/details/gtptzatgox.html

JS:   process.env.HOME
来源：http://dali.yueranfly.top/Article/details/gtdtqarqsf.html

TS:   process.env.HOME
来源：http://dali.chenjidiqi.icu/Article/details/gtqpanscye.html

Java: System.getenv("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gtxhpckszy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gtwpjqforv.html

Ruby: ENV["HOME"]
来源：http://dali.c1oappe.top/Article/details/gtiykjmfnj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthxtlnibe.html

[M03] 执行外部命令
来源：http://dali.hfpthk.cn/Article/details/gtksrddbgr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xylfe.cn/Article/details/gtkebpvcri.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xziqi.cn/Article/details/gtuayrcjep.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jlsjyb.cn/Article/details/gtzrmbluwu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cheryme.top/Article/details/gtjxsdgamy.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xuetiantiany.cn/Article/details/gtydmgcjki.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhongyouzk.top/Article/details/gtqutmvolx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsqkabsrp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cheryme.top/Article/details/gtsjoqognl.html

[M04] 获取当前工作目录
来源：http://dali.zhongyouzk.top/Article/details/gtweajcjlz.html

Py:   os.getcwd()
来源：http://dali.daxiang520.top/Article/details/gtktcwhusv.html

PHP:  getcwd();
来源：http://dali.gogol.net.cn/Article/details/gtgqfoiaft.html

JS:   process.cwd()
来源：http://dali.ehwqpu.com/Article/details/gtehanejqy.html

TS:   process.cwd()
来源：http://dali.sysykeji.top/Article/details/gtbhfofjxo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.snrcjt.cn/Article/details/gtubkmsxcj.html

Go:   os.Getwd()
来源：http://dali.cdnleiting.top/Article/details/gttmccqeet.html

Ruby: Dir.pwd
来源：http://dali.hammf.cn/Article/details/gtltpczzyr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xuetiantiany.cn/Article/details/gtpqwngvzt.html

[M05] 设置退出码
来源：http://dali.chenzaomai.com/Article/details/gtwbmzddea.html

Py:   sys.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gttccxfhqc.html

PHP:  exit(1);
来源：http://dali.svipenyu.cn/Article/details/gtpblbpllh.html

JS:   process.exit(1)
来源：http://dali.bjfxy.top/Article/details/gtztzvftnt.html

TS:   process.exit(1)
来源：http://dali.jqgfzy.top/Article/details/gtsmehguhg.html

Java: System.exit(1)
来源：http://dali.gzhubu.top/Article/details/gtnvhavtik.html

Go:   os.Exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtmlrspgio.html

Ruby: exit 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgoazokgc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yanxiufei.cn/Article/details/gtrynylpjk.html

[M06] 向标准错误输出
来源：http://dali.xziqi.cn/Article/details/gtboxuklxc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sysykeji.top/Article/details/gtcgascurs.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhengqikj.top/Article/details/gtnvkliqhp.html

JS:   console.error("err")
来源：http://dali.gaohongyu789.top/Article/details/gtgtxaryfw.html

TS:   console.error("err")
来源：http://dali.ivvv.top/Article/details/gtllcjhqcx.html

Java: System.err.println("err")
来源：http://dali.hysaishi.cn/Article/details/gtuevznimt.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinqigufen.top/Article/details/gtkwqrmkli.html

Ruby: warn "err"
来源：http://dali.aizwys.cn/Article/details/gtgpamhuiy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yvedp.cn/Article/details/gthywbauaz.html

[M07] 判断是否为主入口
来源：http://dali.nanxinkj.top/Article/details/gttpdkmtrj.html

Py:   if __name__ == "__main__":
来源：http://dali.hnxiangtu.top/Article/details/gtexnjbsrr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtdrvjcenl.html

JS:   require.main === module
来源：http://dali.tian-w.cn/Article/details/gtxqvqoklh.html

TS:   require.main === module
来源：http://dali.meibo888.top/Article/details/gtgnoxlkmx.html

Java: public static void main(String[] args)
来源：http://dali.cdnleiting.top/Article/details/gtultqhrzi.html

Go:   func main()
来源：http://dali.xuetiantiany.cn/Article/details/gtyumjwycr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shangyingyoupin.top/Article/details/gtlmqylqab.html

C#:   static void Main(string[] args)
来源：http://dali.cqqwz.cn/Article/details/gtwmvddrzb.html

[M08] 获取系统与运行时信息
来源：http://dali.bjfxy.top/Article/details/gtrbapvtcg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.kuanghao11.cn/Article/details/gtmqpmyeru.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gtfgihhqjf.html

JS:   process.platform;  process.version
来源：http://dali.cqqwz.cn/Article/details/gtolatutir.html

TS:   process.platform;  process.version
来源：http://dali.ivvv.top/Article/details/gtzyltvjoj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ehwqpu.com/Article/details/gtlnwuoymp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.0kj1m.cn/Article/details/gtyauedzek.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.tian-w.cn/Article/details/gtsnedxykj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hnqzz.top/Article/details/gtzovnpicn.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gthkpiqgca.html

N. 数据结构与算法
来源：http://dali.birdmap.top/Article/details/gtsdtgxktb.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gttywvoizz.html

[N01] 二分查找（有序数组）
来源：http://dali.meibo888.top/Article/details/gtqkbhsdzl.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xinyue.icu/Article/details/gthwqjkiui.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhoulong.xyz/Article/details/gtvmpmregm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zdqjudy.top/Article/details/gtttdbtwvu.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yonumen.top/Article/details/gtjvqccoql.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.mhx1999.top/Article/details/gtwmkcrzzu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtzozagqwb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.fzhhl.top/Article/details/gtslunqmjt.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jianghu66.top/Article/details/gtwkzhvfmv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.kuanghao11.cn/Article/details/gtebiqklbc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sysykeji.top/Article/details/gtspfbruqo.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yueranfly.top/Article/details/gtrnapyqxt.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yvedp.cn/Article/details/gtmctudqvm.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guannengcc.top/Article/details/gtfymjqbkw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yangfankeji.com/Article/details/gthjhaudma.html

Go:   slices.Sort(arr)
来源：http://dali.ehwqpu.com/Article/details/gttverfmhr.html

Ruby: arr.sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttymnurfz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.feifeiyinyue.top/Article/details/gtnwinhgks.html

[N03] 快速排序（分治示例）
来源：http://dali.svipenyu.cn/Article/details/gtyzuvamuo.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yanxiufei.cn/Article/details/gtysymwpdi.html

PHP:  // 递归实现，或用 usort
来源：http://dali.guannengcc.top/Article/details/gtjqvwnawq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenlongwang.top/Article/details/gtuemxnxxf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cqqwz.cn/Article/details/gtihrlxzsy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.snrcjt.cn/Article/details/gtzriviido.html


<!-- 参考信息 -->