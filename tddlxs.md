代发 wailian999

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.tianlin.xyz/Article/details/gtbqtjdkqc.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cucudq.cn/Article/details/gtzgodsgdf.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cheryme.top/Article/details/gtriknedzv.html

[J06] 计算两时间之差
来源：http://dali.cqqwz.cn/Article/details/gtiwilphlj.html

Py:   (end - start).total_seconds()
来源：http://dali.yueranfly.top/Article/details/gtjckwiatg.html

PHP:  $end->diff($start)->days;
来源：http://dali.birdmap.top/Article/details/gtaetfvrsz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.0kj1m.cn/Article/details/gtgorjuyrl.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwblgdbne.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.iojbl.cn/Article/details/gtxtdswrkv.html

Go:   end.Sub(start).Hours()
来源：http://dali.aizwys.cn/Article/details/gtjcskanph.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhiwuduotai.top/Article/details/gtyejgdyug.html

C#:   (end - start).TotalSeconds
来源：http://dali.haohaochexian.top/Article/details/gtjobpntgl.html

[J07] 比较两个日期
来源：http://dali.snrcjt.cn/Article/details/gtlblndomc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpmvbjylz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ybcxt.top/Article/details/gtegehgtvq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.c1oappe.top/Article/details/gtxoxoekws.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.quarkkingdee.top/Article/details/gtyvkbqqyq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.wangshuangyany.cn/Article/details/gthghtgdos.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.0kj1m.cn/Article/details/gtiwiqiiqs.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ydzc1.top/Article/details/gtnsviwcas.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yuanzhike.top/Article/details/gtsoypgxyo.html

[J08] 提取年月日与星期
来源：http://dali.ybcxt.top/Article/details/gtxejvsujb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhijiandao.cn/Article/details/gtettmuges.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zycfv.cn/Article/details/gtfrebuggr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhiwuduotai.top/Article/details/gtuamjwbvw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yangfankeji.com/Article/details/gtrtxvopac.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.chenzaomai.com/Article/details/gtjqswcxlt.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xuanzx.com/Article/details/gtjaouxwuv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.mhx1999.top/Article/details/gtgxevjwjb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.chenzaomai.com/Article/details/gtewijspiz.html

[J09] 时区处理
来源：http://dali.wangshuangyany.cn/Article/details/gtsygjsgmg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yj202588.top/Article/details/gtowrnmfwl.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gaohongyu789.top/Article/details/gtvffxemud.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xylfe.cn/Article/details/gtnccdpcxo.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jlsjyb.cn/Article/details/gtcyliaxea.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.pengpengdd.cyou/Article/details/gtsanrymli.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhoulong.xyz/Article/details/gtndzmhlxn.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cheryme.top/Article/details/gttnrfxyao.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gogol.net.cn/Article/details/gtljujzbmc.html

[J10] 取今天 / 本月第一天
来源：http://dali.yuxming.cn/Article/details/gtgpqaxooy.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ydzc1.top/Article/details/gtqxclurtx.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sxryk.cn/Article/details/gtfmrjkpgl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gotoacloud.top/Article/details/gtiyvcipoh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.haohaochexian.top/Article/details/gtzycihaow.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpkphstvk.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hammf.cn/Article/details/gtmmdolbae.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.nwbrower.top/Article/details/gtesdasyjx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sufxvd.cn/Article/details/gtosrhlzke.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtoysorkvj.html

K. JSON 与序列化
来源：http://dali.ehwqpu.com/Article/details/gtcqskqlri.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtsmmwnbmp.html

[K01] 对象转 JSON 字符串
来源：http://dali.pycfn.com/Article/details/gtvlellafd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.tanke756.top/Article/details/gtdczornqk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jyoumei.cn/Article/details/gtutesuhim.html

JS:   JSON.stringify(obj)
来源：http://dali.jyoumei.cn/Article/details/gtudteveos.html

TS:   JSON.stringify(obj)
来源：http://dali.jqgfzy.top/Article/details/gtflcxfhzt.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.tian-w.cn/Article/details/gtyyoyowpc.html

Go:   json.Marshal(obj)
来源：http://dali.ivvv.top/Article/details/gtmwohaeuy.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.dashuyun.cn/Article/details/gtbcneetwo.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.9152youxi.cn/Article/details/gtkgmmghga.html

[K02] JSON 字符串转对象
来源：http://dali.nanxuanxn.top/Article/details/gtsytvzyps.html

Py:   json.loads(s)
来源：http://dali.cheryme.top/Article/details/gtceecgvlk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhengqikj.top/Article/details/gtolkagkym.html

JS:   JSON.parse(s)
来源：http://dali.daria6918.cn/Article/details/gtvxxkpjci.html

TS:   JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtoditmgzo.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jlsjyb.cn/Article/details/gtultkkadr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.c1oappe.top/Article/details/gthntlyfso.html

Ruby: JSON.parse(s)
来源：http://dali.jinqigufen.top/Article/details/gtfjtgicea.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ehwqpu.com/Article/details/gtzrddhbqm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sufxvd.cn/Article/details/gtwekyojcy.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.iojbl.cn/Article/details/gtwgnoplvb.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.meibo888.top/Article/details/gtldqkexwj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.aibaodan.cn/Article/details/gtozdeskxn.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jiagoushi.top/Article/details/gttjcnxwwy.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtasdhvptn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hammf.cn/Article/details/gtioameukb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yvedp.cn/Article/details/gtchxrozou.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cheryme.top/Article/details/gtdogcepsg.html

[K04] 读取 JSON 文件
来源：http://dali.xuanzx.com/Article/details/gtippoflcr.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ydzc1.top/Article/details/gtmsdfuqag.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zdqjudy.top/Article/details/gtkbdsylsu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shzxlz.cn/Article/details/gtrtfkspgb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yanxiufei.cn/Article/details/gtoevrexvt.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hammf.cn/Article/details/gtxnnmyaqu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jlsjyb.cn/Article/details/gtagydjjik.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.birdmap.top/Article/details/gtdvsmpkiv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shzxlz.cn/Article/details/gttokdyuxk.html

[K05] 深拷贝对象
来源：http://dali.gogol.net.cn/Article/details/gtkhegjgvp.html

Py:   copy.deepcopy(obj)
来源：http://dali.guowangkeji.top/Article/details/gtgsbvrkoc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xuanzx.com/Article/details/gtghfaiiqa.html

JS:   structuredClone(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxqlvmhcs.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtaezywmvw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yj202588.top/Article/details/gtgyunzogg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xuanzx.com/Article/details/gtfkfhxozh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cqqwz.cn/Article/details/gtoivofagh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.nanxinkj.top/Article/details/gtsfnthlrf.html

[K06] 解析 URL 查询串
来源：http://dali.ydzc1.top/Article/details/gthcmyfnof.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shzxlz.cn/Article/details/gtekinztdt.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.daria6918.cn/Article/details/gtjwymgkzn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenjidiqi.icu/Article/details/gtvaxxukpy.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shuidangran.top/Article/details/gthcdrgusv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ehwqpu.com/Article/details/gttcvmwhcy.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.pengpengdd.cyou/Article/details/gtnhfphrgz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ehwqpu.com/Article/details/gtkuoesryr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlozygkvz.html

[K07] 进制转换
来源：http://dali.cdnleiting.top/Article/details/gtcagcsfnk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.meibo888.top/Article/details/gtgmgdhaka.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.fzhhl.top/Article/details/gteafughla.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gtnoxszsam.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqrurnupo.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gtcmdmfjal.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hysaishi.cn/Article/details/gtxbntuonl.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.c1oappe.top/Article/details/gthbughjgo.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gtwqbsrtpn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hywenlv.cn/Article/details/gtdwggllaf.html

Py:   pickle.dumps(obj)
来源：http://dali.havefunace.top/Article/details/gtmbthpqtv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.havefunace.top/Article/details/gtlsyshgpb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hywenlv.cn/Article/details/gtpmojlfeh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yvedp.cn/Article/details/gtgpoeybik.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.meibo888.top/Article/details/gtbtnqmybh.html

Go:   encoding/gob
来源：http://dali.zhengqikj.top/Article/details/gtpjorflls.html

Ruby: Marshal.dump(obj)
来源：http://dali.nwbrower.top/Article/details/gtplpvfmbu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gotoacloud.top/Article/details/gtfhsflrfd.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtctjpelnp.html

L. 网络请求
来源：http://dali.hywenlv.cn/Article/details/gtntyhafcf.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtlgvwmnlf.html

[L01] 发送 GET 请求
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdineyibb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.aibaodan.cn/Article/details/gtdwpsqvsl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.guowangkeji.top/Article/details/gtjdyzotmt.html

JS:   await fetch(url)
来源：http://dali.smart0.xyz/Article/details/gtjyzasjla.html

TS:   await fetch(url)
来源：http://dali.yangfankeji.com/Article/details/gtkyoqddmd.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yuxming.cn/Article/details/gterixfafv.html

Go:   resp, err := http.Get(url)
来源：http://dali.gaohongyu789.top/Article/details/gtmzxocblv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.feifeiyinyue.top/Article/details/gtjbofnwab.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.pengpengdd.cyou/Article/details/gtetzpmugk.html

[L02] 发送 POST JSON
来源：http://dali.cdnleiting.top/Article/details/gttezweqer.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinqigfzy.top/Article/details/gtlvlrsrst.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shanyushiyangtech.top/Article/details/gtnfwewiwd.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.iojbl.cn/Article/details/gtbdaeqxij.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fzhhl.top/Article/details/gthwejphwa.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cdnleiting.top/Article/details/gtvwvscfpr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ivvv.top/Article/details/gttlnlwlcd.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtltzwmaff.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.aizwys.cn/Article/details/gtfakixxea.html

[L03] 设置自定义请求头
来源：http://dali.kuanghao11.cn/Article/details/gtmzmefuet.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.tianlin.xyz/Article/details/gtrrjuwriw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.daria6918.cn/Article/details/gtnkmghans.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.redwolf501.top/Article/details/gtfqcakerc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gogol.net.cn/Article/details/gtjhhzuyru.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.vqdsnc.cn/Article/details/gtyljpntdr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yuxming.cn/Article/details/gtfbzobcvr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hysaishi.cn/Article/details/gtxvphmpvw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shangyingyoupin.top/Article/details/gtmokryhtk.html

[L04] 设置超时
来源：http://dali.vqdsnc.cn/Article/details/gtlxnpyrnb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.wangdashe.top/Article/details/gtydfurqlu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yuanzhike.top/Article/details/gtyoelygir.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xinyue.icu/Article/details/gtitnanupr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.9152youxi.cn/Article/details/gtqsfvfzhf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.c1oappe.top/Article/details/gtjifwpziy.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.redwolf501.top/Article/details/gtjqobdgar.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnjvryiuh.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.wangshuangyany.cn/Article/details/gtnvmyxzkf.html

[L05] 上传文件（multipart）
来源：http://dali.tianlin.xyz/Article/details/gtssnxcwas.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.birdmap.top/Article/details/gtsvnlxerw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhoulong.xyz/Article/details/gthljtolyc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shangyingyoupin.top/Article/details/gtmwoxxjnj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxinkj.top/Article/details/gtgyooamtm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zycfv.cn/Article/details/gtmfylcusv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.snrcjt.cn/Article/details/gtskdzitqy.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.vqdsnc.cn/Article/details/gtgwpqsius.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtkyaoosta.html

[L06] 解析响应为 JSON
来源：http://dali.yongpay.top/Article/details/gtfjixwwyr.html

Py:   resp.json()
来源：http://dali.yueranfly.top/Article/details/gtdlvupvgi.html

PHP:  json_decode($body, true);
来源：http://dali.aizwys.cn/Article/details/gtjzffslul.html

JS:   await resp.json()
来源：http://dali.havefunace.top/Article/details/gtjbktrccm.html

TS:   await resp.json()
来源：http://dali.wangshuangyany.cn/Article/details/gtzucxedbj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gtwepfpvbi.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.pengpengdd.cyou/Article/details/gtdzwqvhiu.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jlsjyb.cn/Article/details/gtgyriamvo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjqmjidsv.html

[L07] 处理 HTTP 状态码
来源：http://dali.zycfv.cn/Article/details/gtmqugxfhf.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj20258888.top/Article/details/gtcqbgpvrx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gaohongyu789.top/Article/details/gtoanuprwm.html

JS:   resp.ok;  resp.status
来源：http://dali.dashuyun.cn/Article/details/gtimflosyr.html

TS:   resp.ok;  resp.status
来源：http://dali.yj20258888.top/Article/details/gthohornoa.html

Java: resp.statusCode()
来源：http://dali.jianghu66.top/Article/details/gtgcjznokt.html

Go:   resp.StatusCode
来源：http://dali.wangshuangyany.cn/Article/details/gtqushhuio.html

Ruby: resp.code.to_i
来源：http://dali.dashuyun.cn/Article/details/gtsphuxpep.html

C#:   (int)resp.StatusCode
来源：http://dali.pengpengdd.cyou/Article/details/gtkkuodzuz.html

[L08] 并发请求多个地址
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjntjkxqs.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jlsjyb.cn/Article/details/gtqratqwlh.html

PHP:  curl_multi_init() 系列
来源：http://dali.haohaochexian.top/Article/details/gtbjshunrk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tian-w.cn/Article/details/gtgnmzvoaf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj202588.top/Article/details/gtemlepjui.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.daria6918.cn/Article/details/gtyqslkier.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.9152youxi.cn/Article/details/gtzoykgqjb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.birdmap.top/Article/details/gtptstelsv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gzhubu.top/Article/details/gtqdqksnoi.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnshgfzoi.html

M. 命令行 / 进程 / 环境
来源：http://dali.xinyue.icu/Article/details/gtggapihcs.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtgswizcix.html

[M01] 读取命令行参数
来源：http://dali.c1oappe.top/Article/details/gtkukdgvoi.html

Py:   sys.argv[1:]
来源：http://dali.havefunace.top/Article/details/gtnwzhtkwl.html

PHP:  $argv;  $argc;
来源：http://dali.jqgfzy.top/Article/details/gtpbvcifpd.html

JS:   process.argv.slice(2)
来源：http://dali.yongpay.top/Article/details/gtrunefbap.html

TS:   process.argv.slice(2)
来源：http://dali.316326.xyz/Article/details/gtmssermle.html

Java: args 数组（main 方法参数）
来源：http://dali.guannengcc.top/Article/details/gtnfxugadz.html

Go:   os.Args[1:]
来源：http://dali.316326.xyz/Article/details/gtobkdiitr.html

Ruby: ARGV
来源：http://dali.zhoulong.xyz/Article/details/gtzrjflaiu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ydzc1.top/Article/details/gtmmmnkhee.html

[M02] 读取环境变量
来源：http://dali.jinghuilouyu.cn/Article/details/gthwuumvdo.html

Py:   os.environ.get("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gtftocqras.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.dianchejie.cn/Article/details/gtdwpfjjeo.html

JS:   process.env.HOME
来源：http://dali.jianghu66.top/Article/details/gtyzulrjkj.html

TS:   process.env.HOME
来源：http://dali.andypj.xyz/Article/details/gtskeexize.html

Java: System.getenv("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtothsnuah.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gtxcmpgazv.html

Ruby: ENV["HOME"]
来源：http://dali.havefunace.top/Article/details/gtezonffev.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sxryk.cn/Article/details/gtheoidtde.html

[M03] 执行外部命令
来源：http://dali.pengpengdd.cyou/Article/details/gtrpqonvtj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hnxiangtu.top/Article/details/gtdivhjqpf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.havefunace.top/Article/details/gtbspsbuib.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxuanxn.top/Article/details/gtqenjydfa.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.9152youxi.cn/Article/details/gtnzcureqa.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinghuilouyu.cn/Article/details/gthubbdyao.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xuanzx.com/Article/details/gtlacssile.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.wangdashe.top/Article/details/gtlxmkdtfn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ppjwa.cn/Article/details/gthxjaqkrv.html

[M04] 获取当前工作目录
来源：http://dali.shanyushiyangtech.top/Article/details/gtqajuufdf.html

Py:   os.getcwd()
来源：http://dali.havefunace.top/Article/details/gttjwgadit.html

PHP:  getcwd();
来源：http://dali.fzhhl.top/Article/details/gtgtuhmrrc.html

JS:   process.cwd()
来源：http://dali.jiagoushi.top/Article/details/gtrohcryzo.html

TS:   process.cwd()
来源：http://dali.aizwys.cn/Article/details/gtkhmifzhg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hfpthk.cn/Article/details/gtdcjemeyk.html

Go:   os.Getwd()
来源：http://dali.wangdashe.top/Article/details/gtaytacary.html

Ruby: Dir.pwd
来源：http://dali.yanxiufei.cn/Article/details/gtadwdtxip.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.aibaodan.cn/Article/details/gtljgeawpm.html

[M05] 设置退出码
来源：http://dali.birdmap.top/Article/details/gthavlmkmx.html

Py:   sys.exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxqkljlyr.html

PHP:  exit(1);
来源：http://dali.zycfv.cn/Article/details/gthumqfabp.html

JS:   process.exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtztxsxquc.html

TS:   process.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtpmnfrpog.html

Java: System.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gtebveymwo.html

Go:   os.Exit(1)
来源：http://dali.zhixingplan.top/Article/details/gtzqkgvikf.html

Ruby: exit 1
来源：http://dali.ppjwa.cn/Article/details/gtisodbbuk.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cdnleiting.top/Article/details/gtzszdtwji.html

[M06] 向标准错误输出
来源：http://dali.quarkkingdee.top/Article/details/gtggqaqgue.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yueranfly.top/Article/details/gtdkddworl.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.nanxuanxn.top/Article/details/gthnvbowie.html

JS:   console.error("err")
来源：http://dali.shzxlz.cn/Article/details/gtaaavvood.html

TS:   console.error("err")
来源：http://dali.shangyingyoupin.top/Article/details/gtplolkrcd.html

Java: System.err.println("err")
来源：http://dali.ppjwa.cn/Article/details/gtoovkuiqd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.wangshuangyany.cn/Article/details/gthilgspeu.html

Ruby: warn "err"
来源：http://dali.hywenlv.cn/Article/details/gtdyjgfaip.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yuanzhike.top/Article/details/gthgatptct.html

[M07] 判断是否为主入口
来源：http://dali.shuidangran.top/Article/details/gtgxzntetk.html

Py:   if __name__ == "__main__":
来源：http://dali.meibo888.top/Article/details/gteuojeumu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.haohaochexian.top/Article/details/gtswftnsvf.html

JS:   require.main === module
来源：http://dali.xuanzx.com/Article/details/gteorctrqq.html

TS:   require.main === module
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxrxvqarb.html

Java: public static void main(String[] args)
来源：http://dali.yuanzhike.top/Article/details/gttdptirda.html

Go:   func main()
来源：http://dali.mhx1999.top/Article/details/gtmzcljyth.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gaohongyu789.top/Article/details/gtpbuyvodp.html

C#:   static void Main(string[] args)
来源：http://dali.shuidangran.top/Article/details/gtdpyxquev.html

[M08] 获取系统与运行时信息
来源：http://dali.dianchejie.cn/Article/details/gtizorxvja.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yvedp.cn/Article/details/gtecdvtcol.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.haohaochexian.top/Article/details/gtjvgtzaax.html

JS:   process.platform;  process.version
来源：http://dali.ybcxt.top/Article/details/gtfuveaagd.html

TS:   process.platform;  process.version
来源：http://dali.sweek.top/Article/details/gtdavjuwhr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.iojbl.cn/Article/details/gtxmeiemxk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.svipenyu.cn/Article/details/gtfzamiaeb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.feifeiyinyue.top/Article/details/gtsrrwuejx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hfpthk.cn/Article/details/gtdjmpzhew.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtsjahafox.html

N. 数据结构与算法
来源：http://dali.jinqigufen.top/Article/details/gthpiddstv.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gttxqmhnse.html

[N01] 二分查找（有序数组）
来源：http://dali.aizwys.cn/Article/details/gtnhszmkvt.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gteacdibib.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cdnleiting.top/Article/details/gtyfphkzse.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dashuyun.cn/Article/details/gtgeyquhoe.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzkcxwvbs.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.fzhhl.top/Article/details/gtlctyhkfd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gthtydcynf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.aizwys.cn/Article/details/gtucyvmvxt.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gtrkvcobej.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.meibo888.top/Article/details/gtjwgmbxfm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shuidangran.top/Article/details/gtlbnnmfhm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ppjwa.cn/Article/details/gtkfusfiwa.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yangfankeji.com/Article/details/gteqypzwqt.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.316326.xyz/Article/details/gtszghmrdo.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmegykama.html

Go:   slices.Sort(arr)
来源：http://dali.ivvv.top/Article/details/gtvuvzhbzq.html

Ruby: arr.sort
来源：http://dali.haohaochexian.top/Article/details/gthjsveccg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yuanzhike.top/Article/details/gtteiubtey.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gtkbwotcyy.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jinghuilouyu.cn/Article/details/gthiqkcwui.html

PHP:  // 递归实现，或用 usort
来源：http://dali.nanxuanxn.top/Article/details/gtftjppety.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.mhx1999.top/Article/details/gthwfnjkml.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.andypj.xyz/Article/details/gttlcsiuzs.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.gotoacloud.top/Article/details/gtavtuxpcg.html


<!-- 参考信息 -->