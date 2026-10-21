代发 wailian999

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yongpay.top/Article/details/gtferurfpc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhongyouzk.top/Article/details/gtbwzqdcdi.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ybcxt.top/Article/details/gtuhnxbpoo.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.c1oappe.top/Article/details/gttpgrtdyw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gtgvozwdhg.html

[J08] 提取年月日与星期
来源：http://dali.cheryme.top/Article/details/gtubfpvvlb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.iojbl.cn/Article/details/gtawmnlzfa.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yuanzhike.top/Article/details/gtdpstwljg.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gogol.net.cn/Article/details/gtbsvqyulg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.svipenyu.cn/Article/details/gtrzkgeuir.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jqgfzy.top/Article/details/gtsnjpeeza.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gogol.net.cn/Article/details/gtnrovyhor.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.bjfxy.top/Article/details/gtcgsloicv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nanxinkj.top/Article/details/gtbqrrioxj.html

[J09] 时区处理
来源：http://dali.chenzaomai.com/Article/details/gttwmdbyfg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.guowangkeji.top/Article/details/gttyajulte.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jqgfzy.top/Article/details/gtpsqruvgy.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ehwqpu.com/Article/details/gtchngexis.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuanzx.com/Article/details/gtoxbchlqr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yj20258888.top/Article/details/gtigdkernm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sysykeji.top/Article/details/gtkydvqrqu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.birdmap.top/Article/details/gtwzmjdqoq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.mhx1999.top/Article/details/gtloczogff.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhongyouzk.top/Article/details/gtlhbandey.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuxvjpwax.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nwbrower.top/Article/details/gtuwkdpujb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.snrcjt.cn/Article/details/gtgoatvfod.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtakuoveao.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.tanke756.top/Article/details/gthijnttwh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cheryme.top/Article/details/gtczbhgkha.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shuidangran.top/Article/details/gtvsqbtuqj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.fzhhl.top/Article/details/gtgrlxwvsu.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtosciegzg.html

K. JSON 与序列化
来源：http://dali.havefunace.top/Article/details/gtnlwoewek.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtkhtbriom.html

[K01] 对象转 JSON 字符串
来源：http://dali.vqdsnc.cn/Article/details/gttzzuoqsw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmktyvjec.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhongyouzk.top/Article/details/gtshzwziaw.html

JS:   JSON.stringify(obj)
来源：http://dali.tian-w.cn/Article/details/gtmqwwcckz.html

TS:   JSON.stringify(obj)
来源：http://dali.zhixingplan.top/Article/details/gtjxilztvv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xinyue.icu/Article/details/gtbgutvqef.html

Go:   json.Marshal(obj)
来源：http://dali.yj202588.top/Article/details/gtldaaxtnj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinqigfzy.top/Article/details/gtktazehff.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yvedp.cn/Article/details/gtiazmqhtm.html

[K02] JSON 字符串转对象
来源：http://dali.feifeiyinyue.top/Article/details/gtzyxjaznr.html

Py:   json.loads(s)
来源：http://dali.ivvv.top/Article/details/gtdocqdqtl.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hongshengwenyu.top/Article/details/gtucshespv.html

JS:   JSON.parse(s)
来源：http://dali.dashuyun.cn/Article/details/gtdjopzaxj.html

TS:   JSON.parse(s)
来源：http://dali.xinyue.icu/Article/details/gtnyuewiun.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cashguo.top/Article/details/gtgaiwoksy.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.316326.xyz/Article/details/gtcxrnzjat.html

Ruby: JSON.parse(s)
来源：http://dali.vqdsnc.cn/Article/details/gtspbmtwwk.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gotoacloud.top/Article/details/gtcsxyjxpe.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xylfe.cn/Article/details/gthrnkzqpc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hammf.cn/Article/details/gtprdfjcuo.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cqqwz.cn/Article/details/gtorrmhdin.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gogol.net.cn/Article/details/gtskliztbu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj202588.top/Article/details/gteparkpdu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ybcxt.top/Article/details/gtdoznrvuy.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yanxiufei.cn/Article/details/gtwddwaafy.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ehwqpu.com/Article/details/gthivbdebk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj20258.top/Article/details/gtfhydzgas.html

[K04] 读取 JSON 文件
来源：http://dali.tian-w.cn/Article/details/gtspqzblwt.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xinyue.icu/Article/details/gtkdidohsb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ppjwa.cn/Article/details/gtjheejyrw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzbcktwbn.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.havefunace.top/Article/details/gtcfmmjozf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.iojbl.cn/Article/details/gtfsemelzr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.tian-w.cn/Article/details/gtystryclb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hammf.cn/Article/details/gtuiopyfez.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yuanzhike.top/Article/details/gtoizcivvy.html

[K05] 深拷贝对象
来源：http://dali.sysykeji.top/Article/details/gtopeqlqjd.html

Py:   copy.deepcopy(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtbpyxbqpi.html

PHP:  unserialize(serialize($obj));
来源：http://dali.mhx1999.top/Article/details/gttrusnuny.html

JS:   structuredClone(obj)
来源：http://dali.ivvv.top/Article/details/gtjvaukgaa.html

TS:   structuredClone(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjuybxbgk.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.feifeiyinyue.top/Article/details/gtaeoyhoqk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.nanxinkj.top/Article/details/gtslabsimf.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zdqjudy.top/Article/details/gtwgwzoegc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sweek.top/Article/details/gtvaozlxcs.html

[K06] 解析 URL 查询串
来源：http://dali.jiagoushi.top/Article/details/gtimafwjue.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.aizwys.cn/Article/details/gtgbygeqgf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.smart0.xyz/Article/details/gtgqzhwlls.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gotoacloud.top/Article/details/gtyezxokgh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.c1oappe.top/Article/details/gtyadcpotn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xuetiantiany.cn/Article/details/gtkxlebjci.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gtxmokiefd.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yueranfly.top/Article/details/gtbzogmccu.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hongshengwenyu.top/Article/details/gtxcxgpcnz.html

[K07] 进制转换
来源：http://dali.yueranfly.top/Article/details/gtkfhqujxi.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gteufocdhi.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yonumen.top/Article/details/gtulgexbuw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gtoeywpctk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsfzneybj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gtqvdmbgio.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.iojbl.cn/Article/details/gtzgrinwfq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.haohaochexian.top/Article/details/gtemdsvshd.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gtjbaepvif.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhixingplan.top/Article/details/gtjnnqaddb.html

Py:   pickle.dumps(obj)
来源：http://dali.jyoumei.cn/Article/details/gthmkejfju.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.tianlin.xyz/Article/details/gtxublmwaf.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhiwuduotai.top/Article/details/gtgbxxthgo.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtohrimfsa.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.daxiang520.top/Article/details/gttbunbqen.html

Go:   encoding/gob
来源：http://dali.haohaochexian.top/Article/details/gtadvunatn.html

Ruby: Marshal.dump(obj)
来源：http://dali.redwolf501.top/Article/details/gtlxaaazzh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yj20258.top/Article/details/gtqhkpeepu.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gthdhnxfvh.html

L. 网络请求
来源：http://dali.hfpthk.cn/Article/details/gtibysgzjn.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtvkwyvtxi.html

[L01] 发送 GET 请求
来源：http://dali.yueranfly.top/Article/details/gtlppfmmam.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.chenlongwang.top/Article/details/gtmohpdkek.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xziqi.cn/Article/details/gtevtcfiuw.html

JS:   await fetch(url)
来源：http://dali.dianchejie.cn/Article/details/gtkvowbqqi.html

TS:   await fetch(url)
来源：http://dali.ydzc1.top/Article/details/gtdwxdkcmk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cqqwz.cn/Article/details/gtpqogzbxk.html

Go:   resp, err := http.Get(url)
来源：http://dali.kuanghao11.cn/Article/details/gtbvnaqjrq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.9152youxi.cn/Article/details/gtxvuilder.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ydzc1.top/Article/details/gtbkzabbqq.html

[L02] 发送 POST JSON
来源：http://dali.zhongyouzk.top/Article/details/gtkaoeoipc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.guannengcc.top/Article/details/gthjmuibty.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hfpthk.cn/Article/details/gtaprjnmev.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hammf.cn/Article/details/gtrealjzhs.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.c1oappe.top/Article/details/gtobjznwrv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cucudq.cn/Article/details/gtdiwtvkyj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.redwolf501.top/Article/details/gtjzqoysfr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hysaishi.cn/Article/details/gtnulenhxz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hongshengwenyu.top/Article/details/gthmhsrpfe.html

[L03] 设置自定义请求头
来源：http://dali.feifeiyinyue.top/Article/details/gtvdofsync.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cheryme.top/Article/details/gtuuujrgrp.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hfpthk.cn/Article/details/gtuatckxoe.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yonumen.top/Article/details/gtpqsqrdfp.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj202588.top/Article/details/gtbvuocwyx.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.0kj1m.cn/Article/details/gtvqekcvkz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shuidangran.top/Article/details/gtiapsrgah.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sweek.top/Article/details/gttnuipsbl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hongshengwenyu.top/Article/details/gtkfsdgizt.html

[L04] 设置超时
来源：http://dali.shanyushiyangtech.top/Article/details/gtsicdwohu.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yuanzhike.top/Article/details/gtsljuurss.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jyoumei.cn/Article/details/gtzwvrqqgg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shzxlz.cn/Article/details/gtxjainzvc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pengpengdd.cyou/Article/details/gtddbgjvxs.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhengqikj.top/Article/details/gtowsosefl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.316326.xyz/Article/details/gtytwkkbkx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.tanke756.top/Article/details/gtslegiakl.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.nanxuanxn.top/Article/details/gtixeujyel.html

[L05] 上传文件（multipart）
来源：http://dali.jianghu66.top/Article/details/gtnfzudtpy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.redwolf501.top/Article/details/gtlcmhdgoo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.fengsongda.top/Article/details/gtvfxoxpkn.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jyoumei.cn/Article/details/gtuqccrhgg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shuidangran.top/Article/details/gtonoctwlz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhengqikj.top/Article/details/gtfzzhomvb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcwtdtenw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gtqnlflemq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtpieqrghc.html

[L06] 解析响应为 JSON
来源：http://dali.xuanzx.com/Article/details/gtwcdjnbxa.html

Py:   resp.json()
来源：http://dali.hywenlv.cn/Article/details/gtefndumae.html

PHP:  json_decode($body, true);
来源：http://dali.redwolf501.top/Article/details/gtqvhhfhwb.html

JS:   await resp.json()
来源：http://dali.wangdashe.top/Article/details/gtuxmjtezq.html

TS:   await resp.json()
来源：http://dali.redwolf501.top/Article/details/gtldkmwatx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cheryme.top/Article/details/gtswdwlzwr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.fengsongda.top/Article/details/gtczuurzbw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shangyingyoupin.top/Article/details/gtoptavawu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hnqzz.top/Article/details/gtnmkagtdg.html

[L07] 处理 HTTP 状态码
来源：http://dali.gogol.net.cn/Article/details/gtgsolilcq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.daxiang520.top/Article/details/gtbnjijtph.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xuetiantiany.cn/Article/details/gtlhahgauz.html

JS:   resp.ok;  resp.status
来源：http://dali.sxryk.cn/Article/details/gtvigvfutf.html

TS:   resp.ok;  resp.status
来源：http://dali.kuanghao11.cn/Article/details/gtnodtjhhs.html

Java: resp.statusCode()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtywokuvfp.html

Go:   resp.StatusCode
来源：http://dali.ehwqpu.com/Article/details/gtaamfjrcp.html

Ruby: resp.code.to_i
来源：http://dali.pengpengdd.cyou/Article/details/gtqkdnuakd.html

C#:   (int)resp.StatusCode
来源：http://dali.jinqigufen.top/Article/details/gtahboxbfe.html

[L08] 并发请求多个地址
来源：http://dali.chenzaomai.com/Article/details/gtsqmpskmm.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.9152youxi.cn/Article/details/gtpbyihvff.html

PHP:  curl_multi_init() 系列
来源：http://dali.birdmap.top/Article/details/gtxgliznct.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258888.top/Article/details/gtvibruuve.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yonumen.top/Article/details/gtpoozcgkl.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ppjwa.cn/Article/details/gtpkiackqw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhaomingkeji.xyz/Article/details/gtixfntdcj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ybcxt.top/Article/details/gtzttmqbnh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yvedp.cn/Article/details/gtqfvsktxc.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtcwlmqien.html

M. 命令行 / 进程 / 环境
来源：http://dali.ybcxt.top/Article/details/gtyonggthx.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtmaagtfhm.html

[M01] 读取命令行参数
来源：http://dali.sysykeji.top/Article/details/gtwervnxol.html

Py:   sys.argv[1:]
来源：http://dali.0kj1m.cn/Article/details/gtlsggjjji.html

PHP:  $argv;  $argc;
来源：http://dali.hnxiangtu.top/Article/details/gtmghzgxkh.html

JS:   process.argv.slice(2)
来源：http://dali.gzhubu.top/Article/details/gtctbcbiza.html

TS:   process.argv.slice(2)
来源：http://dali.jqgufenzy.top/Article/details/gtfozjjzfi.html

Java: args 数组（main 方法参数）
来源：http://dali.zhengqikj.top/Article/details/gtoewznkiq.html

Go:   os.Args[1:]
来源：http://dali.gaohongyu789.top/Article/details/gtqauogkbc.html

Ruby: ARGV
来源：http://dali.chenlongwang.top/Article/details/gtfxxkwynj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.wangdashe.top/Article/details/gtpqebhtqk.html

[M02] 读取环境变量
来源：http://dali.yuxming.cn/Article/details/gtwnmizwcn.html

Py:   os.environ.get("HOME")
来源：http://dali.hysaishi.cn/Article/details/gteqjvmjhz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.0kj1m.cn/Article/details/gtzklxktfa.html

JS:   process.env.HOME
来源：http://dali.ehwqpu.com/Article/details/gtosmjirgj.html

TS:   process.env.HOME
来源：http://dali.havefunace.top/Article/details/gtfrjrhpzu.html

Java: System.getenv("HOME")
来源：http://dali.yuanzhike.top/Article/details/gttbqvgbxx.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sweek.top/Article/details/gtfwoeirgf.html

Ruby: ENV["HOME"]
来源：http://dali.ybcxt.top/Article/details/gtcbehejqs.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zdqjudy.top/Article/details/gtzbfrezff.html

[M03] 执行外部命令
来源：http://dali.tian-w.cn/Article/details/gtdetlzlmu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.snrcjt.cn/Article/details/gtewpqyivw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinqigufen.top/Article/details/gtywigqjie.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cheryme.top/Article/details/gtgxlhrkel.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.0kj1m.cn/Article/details/gtxzktslci.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.daxiang520.top/Article/details/gtylngxqrq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinghuilouyu.cn/Article/details/gtukovmvva.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yj202588.top/Article/details/gtkiukbhuy.html

C#:   Process.Start("ls", "-l");
来源：http://dali.fengsongda.top/Article/details/gtipuuvfoh.html

[M04] 获取当前工作目录
来源：http://dali.mhx1999.top/Article/details/gtduwlpxbv.html

Py:   os.getcwd()
来源：http://dali.yj202588.top/Article/details/gthftxusdz.html

PHP:  getcwd();
来源：http://dali.xinyue.icu/Article/details/gtmoezijrx.html

JS:   process.cwd()
来源：http://dali.xziqi.cn/Article/details/gtemljbobm.html

TS:   process.cwd()
来源：http://dali.havefunace.top/Article/details/gtcmpgacrr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenzaomai.com/Article/details/gtjaubsdea.html

Go:   os.Getwd()
来源：http://dali.tian-w.cn/Article/details/gthlealhww.html

Ruby: Dir.pwd
来源：http://dali.sysykeji.top/Article/details/gtwbvdsxnr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.pengpengdd.cyou/Article/details/gtmmpdxvet.html

[M05] 设置退出码
来源：http://dali.xinyue.icu/Article/details/gtmwjtceag.html

Py:   sys.exit(1)
来源：http://dali.iojbl.cn/Article/details/gtdlyftcgf.html

PHP:  exit(1);
来源：http://dali.tian-w.cn/Article/details/gtfcejiylk.html

JS:   process.exit(1)
来源：http://dali.bjfxy.top/Article/details/gtjtxgsxpv.html

TS:   process.exit(1)
来源：http://dali.daria6918.cn/Article/details/gtabompvki.html

Java: System.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gtzbobrjgg.html

Go:   os.Exit(1)
来源：http://dali.yongpay.top/Article/details/gtjhealuvg.html

Ruby: exit 1
来源：http://dali.jianghu66.top/Article/details/gtcomtvzrs.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtndpgmrkq.html

[M06] 向标准错误输出
来源：http://dali.yongpay.top/Article/details/gttyomagjw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ybcxt.top/Article/details/gtvmrkypjv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.iojbl.cn/Article/details/gtuwxqdeco.html

JS:   console.error("err")
来源：http://dali.jinqigfzy.top/Article/details/gtkrgtydik.html

TS:   console.error("err")
来源：http://dali.tian-w.cn/Article/details/gteaexlztm.html

Java: System.err.println("err")
来源：http://dali.cashguo.top/Article/details/gtygsxqidw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shanyushiyangtech.top/Article/details/gtevhjqvyl.html

Ruby: warn "err"
来源：http://dali.feifeiyinyue.top/Article/details/gtfqtzebjh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.fzhhl.top/Article/details/gtvrrdcbab.html

[M07] 判断是否为主入口
来源：http://dali.yueranfly.top/Article/details/gtdapjwwtu.html

Py:   if __name__ == "__main__":
来源：http://dali.aizwys.cn/Article/details/gtyorupyrf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yonumen.top/Article/details/gtmegebova.html

JS:   require.main === module
来源：http://dali.cqqwz.cn/Article/details/gtridjvrsw.html

TS:   require.main === module
来源：http://dali.zhiwuduotai.top/Article/details/gtelxqlgyg.html

Java: public static void main(String[] args)
来源：http://dali.jinghuilouyu.cn/Article/details/gtaqfauoya.html

Go:   func main()
来源：http://dali.yuxming.cn/Article/details/gtrxkaauvk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cashguo.top/Article/details/gtvobzusnt.html

C#:   static void Main(string[] args)
来源：http://dali.iojbl.cn/Article/details/gtyvpjeiql.html

[M08] 获取系统与运行时信息
来源：http://dali.gzhubu.top/Article/details/gtbtltjbbp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.pycfn.com/Article/details/gtwansprsf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinqigfzy.top/Article/details/gttlbezveu.html

JS:   process.platform;  process.version
来源：http://dali.tian-w.cn/Article/details/gtupycbsoy.html

TS:   process.platform;  process.version
来源：http://dali.jiagoushi.top/Article/details/gtlprgtprf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.c1oappe.top/Article/details/gtczpdxqix.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sysykeji.top/Article/details/gtpswgvifk.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.chenjidiqi.icu/Article/details/gtwxhsfujg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shzxlz.cn/Article/details/gttxsrmvzt.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtokhhhnhi.html

N. 数据结构与算法
来源：http://dali.yvedp.cn/Article/details/gtbeepxzbj.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gttjodrbpp.html

[N01] 二分查找（有序数组）
来源：http://dali.xziqi.cn/Article/details/gtbfaljzkr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtlwglkbhw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hywenlv.cn/Article/details/gtipovpkfu.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gotoacloud.top/Article/details/gtsjavyupz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhongyouzk.top/Article/details/gtjkavfmir.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.havefunace.top/Article/details/gtxmoythxm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtcglfhfjo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhongyouzk.top/Article/details/gtruihjwho.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtczjqdbnm.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.redwolf501.top/Article/details/gtufmrjuyt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj202588.top/Article/details/gtuwoufewj.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.iojbl.cn/Article/details/gtidbziitx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pycfn.com/Article/details/gtcylfgpwj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hfpthk.cn/Article/details/gtpgparnun.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoiulxcit.html

Go:   slices.Sort(arr)
来源：http://dali.dianchejie.cn/Article/details/gtooyapzda.html

Ruby: arr.sort
来源：http://dali.dianchejie.cn/Article/details/gtmzuqlfxy.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ivvv.top/Article/details/gtbkdfmbmc.html

[N03] 快速排序（分治示例）
来源：http://dali.redwolf501.top/Article/details/gteoftxxkz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jqgufenzy.top/Article/details/gtclokiggz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhixingplan.top/Article/details/gtdyedtobr.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yangfankeji.com/Article/details/gtvwkbadxr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhiwuduotai.top/Article/details/gtoyfzidno.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jyoumei.cn/Article/details/gtrqbqwoan.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hywenlv.cn/Article/details/gtobzwsiqy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jyoumei.cn/Article/details/gtisutmdla.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yvedp.cn/Article/details/gtkqejslka.html

[N04] 斐波那契数列
来源：http://dali.yangfankeji.com/Article/details/gtoipwnzac.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.daria6918.cn/Article/details/gtfjtiqmwn.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yuanzhike.top/Article/details/gtpynrxtsz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.bjfxy.top/Article/details/gticwiqbyx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jyoumei.cn/Article/details/gtesbvnnaa.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yj202588.top/Article/details/gtkwhztdxz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.svipenyu.cn/Article/details/gtpylkvokx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.guowangkeji.top/Article/details/gtkbedyzxk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.daria6918.cn/Article/details/gtrnrgvqwy.html

[N05] 最大公约数
来源：http://dali.xylfe.cn/Article/details/gtkaiuhssf.html

Py:   math.gcd(a, b)
来源：http://dali.zdqjudy.top/Article/details/gtvtggkxsp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jianghu66.top/Article/details/gtsabvvuvx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cdnleiting.top/Article/details/gthneysrks.html


<!-- 参考信息 -->