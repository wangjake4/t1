代发 wailian999

[J07] 比较两个日期
来源：http://dali.snrcjt.cn/Article/details/gtilzaduho.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jianghu66.top/Article/details/gtdsaxpree.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.feifeiyinyue.top/Article/details/gtdogyxrgh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shangyingyoupin.top/Article/details/gtkfgzbkzj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.tian-w.cn/Article/details/gtxeucnkvi.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sxryk.cn/Article/details/gtgbrvlqfl.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmpwwwqlx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.meibo888.top/Article/details/gtfosevznx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ydzc1.top/Article/details/gtlnvdbjmt.html

[J08] 提取年月日与星期
来源：http://dali.zycfv.cn/Article/details/gtjbrgblys.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zycfv.cn/Article/details/gthfmmmats.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sweek.top/Article/details/gtuiryodpz.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj202588.top/Article/details/gtujqaspwo.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.svipenyu.cn/Article/details/gtmmkyynlh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.nwbrower.top/Article/details/gtpgrlkzem.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.vqdsnc.cn/Article/details/gtkxuiczsd.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhoulong.xyz/Article/details/gtiwqbqvzu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hnxiangtu.top/Article/details/gtahyfmwns.html

[J09] 时区处理
来源：http://dali.sufxvd.cn/Article/details/gtvxquqdtl.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jyoumei.cn/Article/details/gtxvtxtmct.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gaohongyu789.top/Article/details/gttpbeyxko.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yonumen.top/Article/details/gtorkopqsy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.smart0.xyz/Article/details/gtkzctvvfs.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yuanzhike.top/Article/details/gtsrogsyat.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gaohongyu789.top/Article/details/gtrulkeoki.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinqigfzy.top/Article/details/gtfgpyzyoh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yuxming.cn/Article/details/gtifpyfcfl.html

[J10] 取今天 / 本月第一天
来源：http://dali.hfpthk.cn/Article/details/gthxqlyoio.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.nanxuanxn.top/Article/details/gtyxhckzsi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tianlin.xyz/Article/details/gtmkhzxxcs.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtooftqhms.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hywenlv.cn/Article/details/gtwqtzkbmc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvpotbhxm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj20258.top/Article/details/gtzbdofdwa.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cheryme.top/Article/details/gttflmppie.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hysaishi.cn/Article/details/gtjvpeejbj.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtmdthidpc.html

K. JSON 与序列化
来源：http://dali.wangshuangyany.cn/Article/details/gtkwpequvc.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtjmwwxbmt.html

[K01] 对象转 JSON 字符串
来源：http://dali.birdmap.top/Article/details/gthuwpobsn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtowjjrxsn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgufenzy.top/Article/details/gtmpkqpziz.html

JS:   JSON.stringify(obj)
来源：http://dali.mhx1999.top/Article/details/gtjcksguke.html

TS:   JSON.stringify(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtckjjqruz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.quarkkingdee.top/Article/details/gtikfsvbwy.html

Go:   json.Marshal(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtedcxkefg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.0kj1m.cn/Article/details/gtfynvjhxo.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yueranfly.top/Article/details/gtrmoapaai.html

[K02] JSON 字符串转对象
来源：http://dali.tian-w.cn/Article/details/gtnpfzauhu.html

Py:   json.loads(s)
来源：http://dali.jlsjyb.cn/Article/details/gtcimbrrjd.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xinyue.icu/Article/details/gtbpxwuqlk.html

JS:   JSON.parse(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtyirpofqh.html

TS:   JSON.parse(s)
来源：http://dali.yanxiufei.cn/Article/details/gtnyumvsbu.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.pycfn.com/Article/details/gtwrwohiek.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.dianchejie.cn/Article/details/gtkmogacyn.html

Ruby: JSON.parse(s)
来源：http://dali.sxryk.cn/Article/details/gtmmfbffmo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xziqi.cn/Article/details/gtlpzpudlh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.tanke756.top/Article/details/gtxgmuadkd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ehwqpu.com/Article/details/gtgydkqlbc.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sxryk.cn/Article/details/gtdrlariqr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gogol.net.cn/Article/details/gtvepmwyma.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cashguo.top/Article/details/gtebgmqwbh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gthctccmir.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.meibo888.top/Article/details/gtjhugtgqg.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jqgfzy.top/Article/details/gtarlfxppo.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.pengpengdd.cyou/Article/details/gtbxnaoggg.html

[K04] 读取 JSON 文件
来源：http://dali.jinqigufen.top/Article/details/gtatjameay.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jyoumei.cn/Article/details/gtuopwkmvx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.vqdsnc.cn/Article/details/gtgqdcfwno.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ehwqpu.com/Article/details/gtmtnxupvn.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.birdmap.top/Article/details/gtmfxzsjhq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.havefunace.top/Article/details/gtijiryxab.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hongshengwenyu.top/Article/details/gtrrdcgpwn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gzhubu.top/Article/details/gtcxixieke.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xuanzx.com/Article/details/gtdfoasrre.html

[K05] 深拷贝对象
来源：http://dali.fzhhl.top/Article/details/gtagbuktkq.html

Py:   copy.deepcopy(obj)
来源：http://dali.bjfxy.top/Article/details/gtqdviqrxk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.vqdsnc.cn/Article/details/gtkgcncdme.html

JS:   structuredClone(obj)
来源：http://dali.nwbrower.top/Article/details/gtyjhzrjfz.html

TS:   structuredClone(obj)
来源：http://dali.zhengqikj.top/Article/details/gtsylrohvs.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sxryk.cn/Article/details/gtyosjtaqi.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.vqdsnc.cn/Article/details/gterosyokr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.shanyushiyangtech.top/Article/details/gttitzbtwx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.snrcjt.cn/Article/details/gtmxkkadmr.html

[K06] 解析 URL 查询串
来源：http://dali.jqgfzy.top/Article/details/gternnqgfm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sufxvd.cn/Article/details/gtnngitqkj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.vqdsnc.cn/Article/details/gtjdaonqto.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sweek.top/Article/details/gtgxtzesul.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zdqjudy.top/Article/details/gtvpqluaye.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.tianlin.xyz/Article/details/gtrbxybjzq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sweek.top/Article/details/gtjkifxwbq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ybcxt.top/Article/details/gtibagqssg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwzqsrbta.html

[K07] 进制转换
来源：http://dali.jlsjyb.cn/Article/details/gtespmawtz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gtcmthkkse.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yvedp.cn/Article/details/gtccyhziwm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gtfrmtgtpl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gtqytxhqpu.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yj20258.top/Article/details/gtgeysxdqi.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shzxlz.cn/Article/details/gtudhhnsqz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hysaishi.cn/Article/details/gtyjyzqykh.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gttrhgkoij.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinqigufen.top/Article/details/gtywshyetg.html

Py:   pickle.dumps(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtsyfcnjon.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtacpabqli.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shangyingyoupin.top/Article/details/gtrheogwgv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.c1oappe.top/Article/details/gtzkcbkpiv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jqgufenzy.top/Article/details/gtxfnxctqu.html

Go:   encoding/gob
来源：http://dali.snrcjt.cn/Article/details/gtgrzqnsrk.html

Ruby: Marshal.dump(obj)
来源：http://dali.cqqwz.cn/Article/details/gtceiivalb.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.wangdashe.top/Article/details/gtqnzsbdib.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtavjdusly.html

L. 网络请求
来源：http://dali.cdnleiting.top/Article/details/gtujpficee.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtmchwsplx.html

[L01] 发送 GET 请求
来源：http://dali.vqdsnc.cn/Article/details/gtaqucdfdf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.tianlin.xyz/Article/details/gtlyqardjw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xuetiantiany.cn/Article/details/gtxdlxvasj.html

JS:   await fetch(url)
来源：http://dali.yvedp.cn/Article/details/gtggyepbgj.html

TS:   await fetch(url)
来源：http://dali.hnqzz.top/Article/details/gtvdzhahtu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zdqjudy.top/Article/details/gthdidanhv.html

Go:   resp, err := http.Get(url)
来源：http://dali.chenjidiqi.icu/Article/details/gtnerjdrnv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhongyouzk.top/Article/details/gtjjprbpzw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.haohaochexian.top/Article/details/gtvqgytfqn.html

[L02] 发送 POST JSON
来源：http://dali.hywenlv.cn/Article/details/gtoxtrqdhf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpvqirkcu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.gogol.net.cn/Article/details/gtbdunoaeb.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sweek.top/Article/details/gtggzjkooe.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgufenzy.top/Article/details/gtqvxmopry.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.kuanghao11.cn/Article/details/gtdrauxcyd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gotoacloud.top/Article/details/gtgwjyjxom.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.kuanghao11.cn/Article/details/gtbdtqqapg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jlsjyb.cn/Article/details/gtuzkbgher.html

[L03] 设置自定义请求头
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqxinuuej.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.daxiang520.top/Article/details/gtidwjvpnq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shzxlz.cn/Article/details/gtvhrehncd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuanzhike.top/Article/details/gtgphrtgnh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pycfn.com/Article/details/gtuzbtevzr.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.dashuyun.cn/Article/details/gtaekubodv.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.bjfxy.top/Article/details/gtgxfbgjbe.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.guannengcc.top/Article/details/gtjspdgtda.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.pengpengdd.cyou/Article/details/gtbjiursor.html

[L04] 设置超时
来源：http://dali.gotoacloud.top/Article/details/gtjueqjpgo.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gaohongyu789.top/Article/details/gtskpynrxv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.9152youxi.cn/Article/details/gtmywqsxik.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.kuanghao11.cn/Article/details/gtrgavpast.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtifavrire.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.smart0.xyz/Article/details/gtiruiwnpl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.dashuyun.cn/Article/details/gtlumysiyx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yueranfly.top/Article/details/gtxmkbjkse.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsgucdjau.html

[L05] 上传文件（multipart）
来源：http://dali.yongpay.top/Article/details/gtvknikkzl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.tian-w.cn/Article/details/gtkcyoxscd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.redwolf501.top/Article/details/gtpcyodkra.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.mhx1999.top/Article/details/gttomjvqte.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.daxiang520.top/Article/details/gtndajvoqw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.haohaochexian.top/Article/details/gtfgebfhqb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yonumen.top/Article/details/gtofpptarc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shanyushiyangtech.top/Article/details/gtshytauct.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtnofwwkqb.html

[L06] 解析响应为 JSON
来源：http://dali.gaohongyu789.top/Article/details/gtmwebusmt.html

Py:   resp.json()
来源：http://dali.pycfn.com/Article/details/gtinxulpoi.html

PHP:  json_decode($body, true);
来源：http://dali.cucudq.cn/Article/details/gtwclzmoqv.html

JS:   await resp.json()
来源：http://dali.nanxuanxn.top/Article/details/gtvxuboysn.html

TS:   await resp.json()
来源：http://dali.guannengcc.top/Article/details/gtzbyatjfo.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.wangshuangyany.cn/Article/details/gtqjyllpsk.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jyoumei.cn/Article/details/gtfxfdzlod.html

Ruby: JSON.parse(resp.body)
来源：http://dali.vqdsnc.cn/Article/details/gteumundhu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yj20258888.top/Article/details/gtcusegvzi.html

[L07] 处理 HTTP 状态码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpodkcxnf.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.havefunace.top/Article/details/gtaxmykejs.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sufxvd.cn/Article/details/gtckuqyxic.html

JS:   resp.ok;  resp.status
来源：http://dali.gotoacloud.top/Article/details/gtujlamtsp.html

TS:   resp.ok;  resp.status
来源：http://dali.jlsjyb.cn/Article/details/gtdpsfslob.html

Java: resp.statusCode()
来源：http://dali.guowangkeji.top/Article/details/gtujapxcuo.html

Go:   resp.StatusCode
来源：http://dali.yonumen.top/Article/details/gtofmfchui.html

Ruby: resp.code.to_i
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjpyvbroj.html

C#:   (int)resp.StatusCode
来源：http://dali.xuetiantiany.cn/Article/details/gtfrbsixxr.html

[L08] 并发请求多个地址
来源：http://dali.nanxuanxn.top/Article/details/gtmysktrnn.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.smart0.xyz/Article/details/gtcwgbmrdb.html

PHP:  curl_multi_init() 系列
来源：http://dali.yj202588.top/Article/details/gtkvscfiac.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xinyue.icu/Article/details/gtwrenjnbl.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258888.top/Article/details/gtnudgrncb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cheryme.top/Article/details/gtmvxaowkv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.meibo888.top/Article/details/gtlekqdufh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yj202588.top/Article/details/gtqwfubtom.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jyoumei.cn/Article/details/gtjdgmfojd.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtfontekjn.html

M. 命令行 / 进程 / 环境
来源：http://dali.316326.xyz/Article/details/gtpnmrcmen.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtuoghejdn.html

[M01] 读取命令行参数
来源：http://dali.dashuyun.cn/Article/details/gtlqblkfvo.html

Py:   sys.argv[1:]
来源：http://dali.shanyushiyangtech.top/Article/details/gtzahjzhgj.html

PHP:  $argv;  $argc;
来源：http://dali.jianghu66.top/Article/details/gteycbfofu.html

JS:   process.argv.slice(2)
来源：http://dali.hammf.cn/Article/details/gteqctfwca.html

TS:   process.argv.slice(2)
来源：http://dali.jinqigufen.top/Article/details/gtbqwedfyo.html

Java: args 数组（main 方法参数）
来源：http://dali.9152youxi.cn/Article/details/gtvonbvjmn.html

Go:   os.Args[1:]
来源：http://dali.hammf.cn/Article/details/gtsigrxdrw.html

Ruby: ARGV
来源：http://dali.yonumen.top/Article/details/gtskrbjplw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zycfv.cn/Article/details/gtmbajrrjm.html

[M02] 读取环境变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzrkagmwb.html

Py:   os.environ.get("HOME")
来源：http://dali.daxiang520.top/Article/details/gtvunurxfk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gthltqzwko.html

JS:   process.env.HOME
来源：http://dali.guowangkeji.top/Article/details/gtjkeijykc.html

TS:   process.env.HOME
来源：http://dali.guannengcc.top/Article/details/gtvaghhjmg.html

Java: System.getenv("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gtihuxzfve.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.fengsongda.top/Article/details/gtrnuraaox.html

Ruby: ENV["HOME"]
来源：http://dali.guowangkeji.top/Article/details/gtqhswsnai.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gtyjslyanm.html

[M03] 执行外部命令
来源：http://dali.cqqwz.cn/Article/details/gtfgyorhvr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.birdmap.top/Article/details/gtoaaqhzxg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sxryk.cn/Article/details/gtgqvfzyjt.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.vqdsnc.cn/Article/details/gtuauftgws.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sysykeji.top/Article/details/gtfzodqlow.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gaohongyu789.top/Article/details/gtfilvvtci.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.wangdashe.top/Article/details/gtgwnifokw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhongyouzk.top/Article/details/gtvsgevnaf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gogol.net.cn/Article/details/gtisictbsd.html

[M04] 获取当前工作目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gthxzagpkb.html

Py:   os.getcwd()
来源：http://dali.feifeiyinyue.top/Article/details/gtjcxyghmn.html

PHP:  getcwd();
来源：http://dali.xuanzx.com/Article/details/gtilnhlaye.html

JS:   process.cwd()
来源：http://dali.gzhubu.top/Article/details/gtaqdznjif.html

TS:   process.cwd()
来源：http://dali.redwolf501.top/Article/details/gtehtatyvo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shangyingyoupin.top/Article/details/gtrnnpsqch.html

Go:   os.Getwd()
来源：http://dali.guannengcc.top/Article/details/gtxbyogbos.html

Ruby: Dir.pwd
来源：http://dali.jiagoushi.top/Article/details/gtfrqbegis.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cqqwz.cn/Article/details/gttitxbpyd.html

[M05] 设置退出码
来源：http://dali.birdmap.top/Article/details/gtaadkshlm.html

Py:   sys.exit(1)
来源：http://dali.iojbl.cn/Article/details/gtrxhjcwyj.html

PHP:  exit(1);
来源：http://dali.yj20258.top/Article/details/gtpvtoxnow.html

JS:   process.exit(1)
来源：http://dali.316326.xyz/Article/details/gtgfwziunm.html

TS:   process.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtqbsaqwxb.html

Java: System.exit(1)
来源：http://dali.tanke756.top/Article/details/gtbsskfsna.html

Go:   os.Exit(1)
来源：http://dali.wangdashe.top/Article/details/gtxavrfypq.html

Ruby: exit 1
来源：http://dali.bjfxy.top/Article/details/gtwajoycpf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.9152youxi.cn/Article/details/gtudlfykfs.html

[M06] 向标准错误输出
来源：http://dali.gotoacloud.top/Article/details/gtetwrvavw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cucudq.cn/Article/details/gtuobpgcls.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.meibo888.top/Article/details/gtgmkwfrnr.html

JS:   console.error("err")
来源：http://dali.ppjwa.cn/Article/details/gtqnduvokp.html

TS:   console.error("err")
来源：http://dali.zhiwuduotai.top/Article/details/gtherrfavh.html

Java: System.err.println("err")
来源：http://dali.cheryme.top/Article/details/gtsobylidg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yangfankeji.com/Article/details/gtmiafmfia.html

Ruby: warn "err"
来源：http://dali.xinyue.icu/Article/details/gtuzxfrbqy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xuanzx.com/Article/details/gtdynskcoq.html

[M07] 判断是否为主入口
来源：http://dali.ybcxt.top/Article/details/gtasuqxzfg.html

Py:   if __name__ == "__main__":
来源：http://dali.sufxvd.cn/Article/details/gtyefvlobw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yj20258.top/Article/details/gtbzrjtejx.html

JS:   require.main === module
来源：http://dali.hywenlv.cn/Article/details/gtmwybywek.html

TS:   require.main === module
来源：http://dali.pengpengdd.cyou/Article/details/gtiberffjx.html

Java: public static void main(String[] args)
来源：http://dali.zhongyouzk.top/Article/details/gttbmetims.html

Go:   func main()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtticcywlp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.smart0.xyz/Article/details/gtbhodolxl.html

C#:   static void Main(string[] args)
来源：http://dali.smart0.xyz/Article/details/gtgzdylhpw.html

[M08] 获取系统与运行时信息
来源：http://dali.ehwqpu.com/Article/details/gtgbfffzpi.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yonumen.top/Article/details/gtjgbbzfjr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gthnipwqyn.html

JS:   process.platform;  process.version
来源：http://dali.yangfankeji.com/Article/details/gtaqztefbm.html

TS:   process.platform;  process.version
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfndgoccc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hnqzz.top/Article/details/gtboljwmgp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinqigufen.top/Article/details/gtgcinecva.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.chenzaomai.com/Article/details/gtqjjfdfml.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinghuilouyu.cn/Article/details/gtnhiewajh.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtrdnrfnuu.html

N. 数据结构与算法
来源：http://dali.sufxvd.cn/Article/details/gtgpltmcmk.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtjhuebjla.html

[N01] 二分查找（有序数组）
来源：http://dali.hnxiangtu.top/Article/details/gtsxquxkof.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xziqi.cn/Article/details/gtqhdcvflo.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nwbrower.top/Article/details/gtfxfwtywx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.svipenyu.cn/Article/details/gtaexrpuaq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhengqikj.top/Article/details/gtulbdfoyn.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gtunufejol.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtvqrhngsq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.316326.xyz/Article/details/gtjynofjgr.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gthmsbxlyj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.9152youxi.cn/Article/details/gtcheurxiw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258888.top/Article/details/gthdijvvvg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.bjfxy.top/Article/details/gtjbtyqlgl.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xziqi.cn/Article/details/gtixcdulyt.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nwbrower.top/Article/details/gtulyccgvz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.fzhhl.top/Article/details/gttsulpugz.html

Go:   slices.Sort(arr)
来源：http://dali.yvedp.cn/Article/details/gtppauehwi.html

Ruby: arr.sort
来源：http://dali.hywenlv.cn/Article/details/gtpziqryxf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.snrcjt.cn/Article/details/gtuonuneme.html

[N03] 快速排序（分治示例）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgzegrame.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gzhubu.top/Article/details/gtffnnkgix.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gogol.net.cn/Article/details/gtnsgmvvgz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gzhubu.top/Article/details/gtsayxovvb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hnqzz.top/Article/details/gtwprrluvb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.gotoacloud.top/Article/details/gtelbjveyx.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.tianlin.xyz/Article/details/gttvydhrba.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yueranfly.top/Article/details/gtmsybxijp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.chenzaomai.com/Article/details/gtkmpccxmj.html

[N04] 斐波那契数列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoflpcbqh.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.svipenyu.cn/Article/details/gtdyzfbiop.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.redwolf501.top/Article/details/gtbnwxnzcj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxuanxn.top/Article/details/gttridqudv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sweek.top/Article/details/gtkpisejof.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shzxlz.cn/Article/details/gtewytbvet.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhoulong.xyz/Article/details/gtmwmaxjiq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xylfe.cn/Article/details/gtpfmrznut.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cheryme.top/Article/details/gtfugvlbux.html


<!-- 参考信息 -->