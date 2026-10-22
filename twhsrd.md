代发 wailian999

Py:   (end - start).total_seconds()
来源：http://dali.hfpthk.cn/Article/details/gtbyonwgwq.html

PHP:  $end->diff($start)->days;
来源：http://dali.smart0.xyz/Article/details/gtfnajcfiw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sufxvd.cn/Article/details/gtudsvnlfc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shuidangran.top/Article/details/gtemjuwwob.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xylfe.cn/Article/details/gtpxcrfnpo.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinqigfzy.top/Article/details/gtokhydpol.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sxryk.cn/Article/details/gtiwibudfr.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj20258.top/Article/details/gtbxtuhwoo.html

[J07] 比较两个日期
来源：http://dali.yangfankeji.com/Article/details/gtilsqragb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gtefkauvbl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sweek.top/Article/details/gtsdeuyneb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gotoacloud.top/Article/details/gtlxabctyf.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrutzbjgw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yangfankeji.com/Article/details/gtvsitmobd.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cdnleiting.top/Article/details/gtxzqowspj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.0kj1m.cn/Article/details/gtsdqrstgs.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gtgylzkffd.html

[J08] 提取年月日与星期
来源：http://dali.cucudq.cn/Article/details/gtrxgfyzkj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhixingplan.top/Article/details/gteouapdmk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.chenjidiqi.icu/Article/details/gtzxdlbfhc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cucudq.cn/Article/details/gtsltuoxoy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.0kj1m.cn/Article/details/gtaqxvuzxx.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.tian-w.cn/Article/details/gtnlgkgbbe.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.chenzaomai.com/Article/details/gthkclmhse.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tian-w.cn/Article/details/gtlykpkvjx.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yuanzhike.top/Article/details/gtosiggddc.html

[J09] 时区处理
来源：http://dali.wangshuangyany.cn/Article/details/gtemfxjjve.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jlsjyb.cn/Article/details/gthximsijo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkrixzbhp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yanxiufei.cn/Article/details/gtfaaewnym.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dianchejie.cn/Article/details/gthlyxekwr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.aizwys.cn/Article/details/gtnnehnqvn.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.pycfn.com/Article/details/gtkqgjabgy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.iojbl.cn/Article/details/gtxxsqambi.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.nanxinkj.top/Article/details/gttqztxxzt.html

[J10] 取今天 / 本月第一天
来源：http://dali.shangyingyoupin.top/Article/details/gtgzqpztli.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ydzc1.top/Article/details/gtekzjoeth.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.fzhhl.top/Article/details/gtqnppklhy.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhoulong.xyz/Article/details/gtvpejipxu.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hywenlv.cn/Article/details/gtzkcaonoo.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqeaphxdz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.nanxuanxn.top/Article/details/gtifyxioko.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.vqdsnc.cn/Article/details/gtkrrltixo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.birdmap.top/Article/details/gtibopbowb.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gthojgzolm.html

K. JSON 与序列化
来源：http://dali.chenzaomai.com/Article/details/gtzxsjytrv.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtkodbgqyr.html

[K01] 对象转 JSON 字符串
来源：http://dali.hnxiangtu.top/Article/details/gtlwnrpjty.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjfzbsfww.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.sweek.top/Article/details/gtyytggdsg.html

JS:   JSON.stringify(obj)
来源：http://dali.smart0.xyz/Article/details/gtokmvrabu.html

TS:   JSON.stringify(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtufhsowne.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hfpthk.cn/Article/details/gtijahgeuy.html

Go:   json.Marshal(obj)
来源：http://dali.sweek.top/Article/details/gtjisvznwq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.snrcjt.cn/Article/details/gtexkrtxrl.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jqgfzy.top/Article/details/gthsdkmcvc.html

[K02] JSON 字符串转对象
来源：http://dali.cucudq.cn/Article/details/gtukfkwhyo.html

Py:   json.loads(s)
来源：http://dali.aibaodan.cn/Article/details/gtxczkysyr.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ppjwa.cn/Article/details/gtedkmpoqn.html

JS:   JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtzicycrwv.html

TS:   JSON.parse(s)
来源：http://dali.quarkkingdee.top/Article/details/gtdermkywj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhixingplan.top/Article/details/gtdhvjdmtt.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shangyingyoupin.top/Article/details/gtrnjpttwr.html

Ruby: JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gtxezqtrey.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yj20258.top/Article/details/gtavtcpngq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sysykeji.top/Article/details/gthgyhlcgj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenzaomai.com/Article/details/gtphhstajx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhiwuduotai.top/Article/details/gtpvedwkcx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtaiwaxkne.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtymqwbeab.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.aizwys.cn/Article/details/gtrokzjwsf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cqqwz.cn/Article/details/gtukofwydp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.chenzaomai.com/Article/details/gthegijwkp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.guannengcc.top/Article/details/gtkqmabagx.html

[K04] 读取 JSON 文件
来源：http://dali.cheryme.top/Article/details/gthoqtzgbb.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gttfnxmpyp.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwaisvlgm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.svipenyu.cn/Article/details/gtucikxuco.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhoulong.xyz/Article/details/gtvjewqkqv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xinyue.icu/Article/details/gtxresosdb.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yuanzhike.top/Article/details/gtwhitquqv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ppjwa.cn/Article/details/gtxlaxptje.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ydzc1.top/Article/details/gtnvgawcas.html

[K05] 深拷贝对象
来源：http://dali.hnxiangtu.top/Article/details/gtnzmavlal.html

Py:   copy.deepcopy(obj)
来源：http://dali.birdmap.top/Article/details/gtktuccxyv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.aizwys.cn/Article/details/gtvucsfmdn.html

JS:   structuredClone(obj)
来源：http://dali.guannengcc.top/Article/details/gtosydzdgk.html

TS:   structuredClone(obj)
来源：http://dali.meibo888.top/Article/details/gtivkguhjf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.quarkkingdee.top/Article/details/gtpminjmwk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.aizwys.cn/Article/details/gthvvnwdyz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.c1oappe.top/Article/details/gtrdvaoonr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.meibo888.top/Article/details/gtzstumpac.html

[K06] 解析 URL 查询串
来源：http://dali.316326.xyz/Article/details/gtlqbzuxrh.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yvedp.cn/Article/details/gtcqggjsvn.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj20258.top/Article/details/gtnhsakpjz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.9152youxi.cn/Article/details/gtifpexeem.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shangyingyoupin.top/Article/details/gtzocojsqo.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yueranfly.top/Article/details/gtisssdxqn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.wangdashe.top/Article/details/gtvfyvaffz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sysykeji.top/Article/details/gtphlsbeeu.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.nanxinkj.top/Article/details/gtoauhxzhd.html

[K07] 进制转换
来源：http://dali.sufxvd.cn/Article/details/gtfjljlssx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gtpfdmhaym.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.chenzaomai.com/Article/details/gtszxjojra.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gtybbkbwdc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.316326.xyz/Article/details/gtgepcjhrm.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtvolkrtey.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.quarkkingdee.top/Article/details/gtsgjxtmkd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.kuanghao11.cn/Article/details/gtnrnndsff.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gtfrsjwtzn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ivvv.top/Article/details/gtjnvidxva.html

Py:   pickle.dumps(obj)
来源：http://dali.yonumen.top/Article/details/gtsywnrxms.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sxryk.cn/Article/details/gtneziumci.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hywenlv.cn/Article/details/gtngsvkqbr.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cashguo.top/Article/details/gtlmzdqfaq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhengqikj.top/Article/details/gtcbtwujvm.html

Go:   encoding/gob
来源：http://dali.nanxuanxn.top/Article/details/gtvkzgqlug.html

Ruby: Marshal.dump(obj)
来源：http://dali.svipenyu.cn/Article/details/gthxxlfrcf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.iojbl.cn/Article/details/gtggsbxweb.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtuqnurmrg.html

L. 网络请求
来源：http://dali.zhaomingkeji.xyz/Article/details/gttsofqzxd.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtwonsbsot.html

[L01] 发送 GET 请求
来源：http://dali.shuidangran.top/Article/details/gttzwtndcg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkfozwixd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xylfe.cn/Article/details/gtmppfoxwv.html

JS:   await fetch(url)
来源：http://dali.svipenyu.cn/Article/details/gtccznlbna.html

TS:   await fetch(url)
来源：http://dali.ehwqpu.com/Article/details/gtnvptjejk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtifeidmph.html

Go:   resp, err := http.Get(url)
来源：http://dali.yongpay.top/Article/details/gtwpbapqkp.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.daxiang520.top/Article/details/gtebqwaocz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sxryk.cn/Article/details/gtedozbtjq.html

[L02] 发送 POST JSON
来源：http://dali.shuidangran.top/Article/details/gtyuqqsylx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.dashuyun.cn/Article/details/gtkcgdxene.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.andypj.xyz/Article/details/gtlzjftuhi.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guowangkeji.top/Article/details/gttqauugvr.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cashguo.top/Article/details/gtrgltraxv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.sufxvd.cn/Article/details/gtzsaaoihi.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shanyushiyangtech.top/Article/details/gtmjdemunq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ehwqpu.com/Article/details/gtgnhyedjr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jiagoushi.top/Article/details/gtzqbdoocv.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gtbzyptfnz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.bjfxy.top/Article/details/gtzjnclvpk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ehwqpu.com/Article/details/gtbhskadqb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tian-w.cn/Article/details/gtpdsrvlwy.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.dashuyun.cn/Article/details/gtgwtjiyws.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shuidangran.top/Article/details/gtjsofdtvl.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.smart0.xyz/Article/details/gtnfdlbovt.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhongyouzk.top/Article/details/gtlyeruoww.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.c1oappe.top/Article/details/gtuwagitff.html

[L04] 设置超时
来源：http://dali.fengsongda.top/Article/details/gtmhviwhgs.html

Py:   requests.get(url, timeout=5)
来源：http://dali.snrcjt.cn/Article/details/gtwimrfsmt.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ehwqpu.com/Article/details/gtdyndpnhf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.vqdsnc.cn/Article/details/gtduoqrfye.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.havefunace.top/Article/details/gtlukmosqw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yj20258888.top/Article/details/gtubyltmcp.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xuanzx.com/Article/details/gthawezofo.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yvedp.cn/Article/details/gtonkdknpl.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.aibaodan.cn/Article/details/gtxpvxjpfu.html

[L05] 上传文件（multipart）
来源：http://dali.daxiang520.top/Article/details/gthgdtzwjp.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbdchtxrw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xuanzx.com/Article/details/gtwuotmlro.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.tian-w.cn/Article/details/gtpnnppxzj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yonumen.top/Article/details/gtqhvawxuo.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yj20258888.top/Article/details/gtpzfrkcdj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.aibaodan.cn/Article/details/gtswatdymk.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhongyouzk.top/Article/details/gtazskivep.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtptzpsusl.html

[L06] 解析响应为 JSON
来源：http://dali.yj20258.top/Article/details/gtfwhejdyk.html

Py:   resp.json()
来源：http://dali.yj20258.top/Article/details/gtphyqqjzr.html

PHP:  json_decode($body, true);
来源：http://dali.fzhhl.top/Article/details/gtkrsbiolx.html

JS:   await resp.json()
来源：http://dali.chenlongwang.top/Article/details/gtqcgyuvlc.html

TS:   await resp.json()
来源：http://dali.yj20258888.top/Article/details/gtbhsgzslx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yonumen.top/Article/details/gtsftnamvo.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cqqwz.cn/Article/details/gtglvakdtt.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jlsjyb.cn/Article/details/gtejhwbuul.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xuetiantiany.cn/Article/details/gtzsdsuvwa.html

[L07] 处理 HTTP 状态码
来源：http://dali.ehwqpu.com/Article/details/gtgfrgxyav.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hongshengwenyu.top/Article/details/gtdakuezcm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.guowangkeji.top/Article/details/gtcmzzrxvv.html

JS:   resp.ok;  resp.status
来源：http://dali.sysykeji.top/Article/details/gtkfhnzhsp.html

TS:   resp.ok;  resp.status
来源：http://dali.hywenlv.cn/Article/details/gtwnbbnitd.html

Java: resp.statusCode()
来源：http://dali.wangdashe.top/Article/details/gtaaothfhz.html

Go:   resp.StatusCode
来源：http://dali.gzhubu.top/Article/details/gtsdcxpazq.html

Ruby: resp.code.to_i
来源：http://dali.chenjidiqi.icu/Article/details/gtbsjgzrdr.html

C#:   (int)resp.StatusCode
来源：http://dali.zhixingplan.top/Article/details/gtottxvlgy.html

[L08] 并发请求多个地址
来源：http://dali.ivvv.top/Article/details/gtevmbudfh.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hywenlv.cn/Article/details/gtbuzkkcho.html

PHP:  curl_multi_init() 系列
来源：http://dali.shangyingyoupin.top/Article/details/gtdsathejw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dianchejie.cn/Article/details/gthuaujwov.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gogol.net.cn/Article/details/gtbqrjznoj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.feifeiyinyue.top/Article/details/gthczllgeq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jqgfzy.top/Article/details/gtszqocegx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yangfankeji.com/Article/details/gtgxwemzac.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yonumen.top/Article/details/gtuvonjuaz.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtmnfabjtq.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinqigfzy.top/Article/details/gtcegayikf.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtdsxdbpyl.html

[M01] 读取命令行参数
来源：http://dali.cqqwz.cn/Article/details/gtnlfgnfim.html

Py:   sys.argv[1:]
来源：http://dali.yangfankeji.com/Article/details/gteiadhghg.html

PHP:  $argv;  $argc;
来源：http://dali.hywenlv.cn/Article/details/gtehoarhsa.html

JS:   process.argv.slice(2)
来源：http://dali.meibo888.top/Article/details/gtyvvbtmcz.html

TS:   process.argv.slice(2)
来源：http://dali.zhongyouzk.top/Article/details/gtvzxgkigq.html

Java: args 数组（main 方法参数）
来源：http://dali.jinqigfzy.top/Article/details/gtldjsosro.html

Go:   os.Args[1:]
来源：http://dali.ivvv.top/Article/details/gtqbfbnzor.html

Ruby: ARGV
来源：http://dali.guowangkeji.top/Article/details/gtndqaimol.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj20258888.top/Article/details/gtqaqxeado.html

[M02] 读取环境变量
来源：http://dali.yj20258888.top/Article/details/gtcdnvoxth.html

Py:   os.environ.get("HOME")
来源：http://dali.nanxinkj.top/Article/details/gtsnvafsiu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.redwolf501.top/Article/details/gtozhywzch.html

JS:   process.env.HOME
来源：http://dali.shzxlz.cn/Article/details/gtgmmijasx.html

TS:   process.env.HOME
来源：http://dali.cashguo.top/Article/details/gtxcyoneod.html

Java: System.getenv("HOME")
来源：http://dali.chenlongwang.top/Article/details/gtrcxqitmk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gttfzmjmix.html

Ruby: ENV["HOME"]
来源：http://dali.jqgfzy.top/Article/details/gtqbdwrxvp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.svipenyu.cn/Article/details/gtzfusidni.html

[M03] 执行外部命令
来源：http://dali.gotoacloud.top/Article/details/gteqjknssf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmmtakhyc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xinyue.icu/Article/details/gtrgdksxxh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yangfankeji.com/Article/details/gttucrhfhh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.0kj1m.cn/Article/details/gtkfzzsktm.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbtmixzok.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.havefunace.top/Article/details/gtkuxpkuwg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.svipenyu.cn/Article/details/gtyfsnvctc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.havefunace.top/Article/details/gtmuzwauoe.html

[M04] 获取当前工作目录
来源：http://dali.hfpthk.cn/Article/details/gtlhhmszeg.html

Py:   os.getcwd()
来源：http://dali.gogol.net.cn/Article/details/gtqfvsvvit.html

PHP:  getcwd();
来源：http://dali.ppjwa.cn/Article/details/gtkkcwnyum.html

JS:   process.cwd()
来源：http://dali.birdmap.top/Article/details/gtyryhmbei.html

TS:   process.cwd()
来源：http://dali.smart0.xyz/Article/details/gtzcypcxmh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gotoacloud.top/Article/details/gtnuesqvyd.html

Go:   os.Getwd()
来源：http://dali.birdmap.top/Article/details/gtmcgrmmfv.html

Ruby: Dir.pwd
来源：http://dali.chenzaomai.com/Article/details/gtercdqvhw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yueranfly.top/Article/details/gtdohngmzt.html

[M05] 设置退出码
来源：http://dali.jqgufenzy.top/Article/details/gtsnzyhjfr.html

Py:   sys.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtdjaghmud.html

PHP:  exit(1);
来源：http://dali.kuanghao11.cn/Article/details/gtgxitulat.html

JS:   process.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gthmnrvasv.html

TS:   process.exit(1)
来源：http://dali.chenlongwang.top/Article/details/gtfsksedpe.html

Java: System.exit(1)
来源：http://dali.daria6918.cn/Article/details/gtohkrdwrr.html

Go:   os.Exit(1)
来源：http://dali.ivvv.top/Article/details/gtckuacmri.html

Ruby: exit 1
来源：http://dali.nwbrower.top/Article/details/gthkqpdmpi.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cdnleiting.top/Article/details/gtyitiyrrm.html

[M06] 向标准错误输出
来源：http://dali.ivvv.top/Article/details/gthtdytokj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sweek.top/Article/details/gtujgygahd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yj20258888.top/Article/details/gthqcwqiaw.html

JS:   console.error("err")
来源：http://dali.wangdashe.top/Article/details/gttgwwtfzk.html

TS:   console.error("err")
来源：http://dali.meibo888.top/Article/details/gtlomphyiy.html

Java: System.err.println("err")
来源：http://dali.gzhubu.top/Article/details/gtvstiozma.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gogol.net.cn/Article/details/gtxaejifbi.html

Ruby: warn "err"
来源：http://dali.ybcxt.top/Article/details/gtxcqlfmtr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jiagoushi.top/Article/details/gtcfbbpvgo.html

[M07] 判断是否为主入口
来源：http://dali.pycfn.com/Article/details/gtktfbmiyv.html

Py:   if __name__ == "__main__":
来源：http://dali.birdmap.top/Article/details/gtidajslfy.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.daria6918.cn/Article/details/gtmlofxttn.html

JS:   require.main === module
来源：http://dali.tanke756.top/Article/details/gtkljntcfa.html

TS:   require.main === module
来源：http://dali.yvedp.cn/Article/details/gtpsvrpknm.html

Java: public static void main(String[] args)
来源：http://dali.jianghu66.top/Article/details/gtwtnqdquq.html

Go:   func main()
来源：http://dali.havefunace.top/Article/details/gtuljwklyk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gotoacloud.top/Article/details/gtvyscnkwu.html

C#:   static void Main(string[] args)
来源：http://dali.0kj1m.cn/Article/details/gtctyliqzx.html

[M08] 获取系统与运行时信息
来源：http://dali.fzhhl.top/Article/details/gttqdrfaya.html

Py:   platform.system();  platform.python_version()
来源：http://dali.c1oappe.top/Article/details/gthmzgwbul.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.pycfn.com/Article/details/gtmmdjlfyf.html

JS:   process.platform;  process.version
来源：http://dali.daria6918.cn/Article/details/gticokgwqh.html

TS:   process.platform;  process.version
来源：http://dali.wangshuangyany.cn/Article/details/gtcuqdflti.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.nwbrower.top/Article/details/gtkveajjls.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sysykeji.top/Article/details/gtlahqajrq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhongyouzk.top/Article/details/gtrttltsig.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.feifeiyinyue.top/Article/details/gtxtnipzil.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtygqossqa.html

N. 数据结构与算法
来源：http://dali.zhoulong.xyz/Article/details/gtwytfmamw.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtkzbcjncv.html

[N01] 二分查找（有序数组）
来源：http://dali.yueranfly.top/Article/details/gtxnynuvnr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtktbvzlbr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jlsjyb.cn/Article/details/gtgmyrkdpz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhaomingkeji.xyz/Article/details/gteotaortr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sufxvd.cn/Article/details/gtcdhnzhxj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtswwkhjlj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gtlqbwkckp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinghuilouyu.cn/Article/details/gtydozlziw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtvdpsnffx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gotoacloud.top/Article/details/gtbmywzoje.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ydzc1.top/Article/details/gtaqgrmptn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yueranfly.top/Article/details/gtoomifsxl.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.quarkkingdee.top/Article/details/gtjvhovtfq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxuanxn.top/Article/details/gtkmhuvrgh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yj20258888.top/Article/details/gtnpfyfyxo.html

Go:   slices.Sort(arr)
来源：http://dali.ydzc1.top/Article/details/gtpeulafci.html

Ruby: arr.sort
来源：http://dali.316326.xyz/Article/details/gttpbhwxdx.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yuxming.cn/Article/details/gtfouwlkhw.html

[N03] 快速排序（分治示例）
来源：http://dali.jinqigfzy.top/Article/details/gtaxcxqdoo.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sufxvd.cn/Article/details/gtgiphwcik.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhiwuduotai.top/Article/details/gtpmdlokyy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pycfn.com/Article/details/gtvwbovkkw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.svipenyu.cn/Article/details/gtlfdzojpt.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.gzhubu.top/Article/details/gtevvvqdua.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jqgfzy.top/Article/details/gtncmskegm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.pycfn.com/Article/details/gtjtderoni.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.haohaochexian.top/Article/details/gtbofgxdiw.html

[N04] 斐波那契数列
来源：http://dali.xuanzx.com/Article/details/gtkgfzhnmj.html


<!-- 参考信息 -->