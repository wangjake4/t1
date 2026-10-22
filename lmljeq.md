代发 wailian999

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.iojbl.cn/Article/details/gttxnfdxxx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangdashe.top/Article/details/gthhdgkooo.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nwbrower.top/Article/details/gtoitbkvcx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xziqi.cn/Article/details/gtmnzxbaan.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yonumen.top/Article/details/gtppwayaps.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shuidangran.top/Article/details/gtpbsnncyk.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xuanzx.com/Article/details/gtnfkvvdkw.html

[J06] 计算两时间之差
来源：http://dali.cheryme.top/Article/details/gtvvaidcif.html

Py:   (end - start).total_seconds()
来源：http://dali.316326.xyz/Article/details/gtuhpbbdia.html

PHP:  $end->diff($start)->days;
来源：http://dali.gaohongyu789.top/Article/details/gttojqdttb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.dashuyun.cn/Article/details/gtqiidkucu.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jqgufenzy.top/Article/details/gtdzgmygon.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhixingplan.top/Article/details/gtphulyqyv.html

Go:   end.Sub(start).Hours()
来源：http://dali.chenzaomai.com/Article/details/gtlkjbbznk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gzhubu.top/Article/details/gtblundwwd.html

C#:   (end - start).TotalSeconds
来源：http://dali.vqdsnc.cn/Article/details/gthvpjbuvd.html

[J07] 比较两个日期
来源：http://dali.chenlongwang.top/Article/details/gtxqcvsdno.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yvedp.cn/Article/details/gtggatyjvf.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.guowangkeji.top/Article/details/gtzghucqig.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zdqjudy.top/Article/details/gtreafnmqu.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.nwbrower.top/Article/details/gteyszicyx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zdqjudy.top/Article/details/gtwvwftmrg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ydzc1.top/Article/details/gtektczzdz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sxryk.cn/Article/details/gtdojkrpjx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gtesciupid.html

[J08] 提取年月日与星期
来源：http://dali.hammf.cn/Article/details/gtkrprdbgr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.guannengcc.top/Article/details/gtpquodqid.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.daria6918.cn/Article/details/gtvzkeuibp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hongshengwenyu.top/Article/details/gthetljozl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.chenzaomai.com/Article/details/gtdhswpakc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shanyushiyangtech.top/Article/details/gtpnkkqffb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxmfkaitq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinqigfzy.top/Article/details/gtumujwjpa.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nanxuanxn.top/Article/details/gthobkdsqh.html

[J09] 时区处理
来源：http://dali.yuanzhike.top/Article/details/gtxdxysmdp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.svipenyu.cn/Article/details/gtczlnpvrx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhijiandao.cn/Article/details/gtqzoxyndv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dashuyun.cn/Article/details/gtaupkpbpu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yanxiufei.cn/Article/details/gtklbqtbor.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gogol.net.cn/Article/details/gtqyfbcikt.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yongpay.top/Article/details/gtwdlymxae.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtciyjtcdy.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhengqikj.top/Article/details/gtrjggvbap.html

[J10] 取今天 / 本月第一天
来源：http://dali.hammf.cn/Article/details/gterpiqwld.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhongyouzk.top/Article/details/gtdsduejgi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zdqjudy.top/Article/details/gtvhaomuvn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgibkukbn.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtoxqegnvf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtfgjdbnzm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cdnleiting.top/Article/details/gtzbrckhqx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shuidangran.top/Article/details/gtmikkjgne.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.svipenyu.cn/Article/details/gtkpazbhfe.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtvfdxhxsw.html

K. JSON 与序列化
来源：http://dali.smart0.xyz/Article/details/gterueprzi.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtyqroqdzf.html

[K01] 对象转 JSON 字符串
来源：http://dali.yj202588.top/Article/details/gtkppnvsqu.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xylfe.cn/Article/details/gtgorqevbs.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258.top/Article/details/gtawaihbuy.html

JS:   JSON.stringify(obj)
来源：http://dali.jiagoushi.top/Article/details/gtmfncvhtf.html

TS:   JSON.stringify(obj)
来源：http://dali.zhengqikj.top/Article/details/gtbvejgsxx.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinghuilouyu.cn/Article/details/gtmfxlclzz.html

Go:   json.Marshal(obj)
来源：http://dali.ppjwa.cn/Article/details/gtfxubihwf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gaohongyu789.top/Article/details/gtlnvsokyz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cdnleiting.top/Article/details/gtotbaauao.html

[K02] JSON 字符串转对象
来源：http://dali.guowangkeji.top/Article/details/gtitamwlds.html

Py:   json.loads(s)
来源：http://dali.0kj1m.cn/Article/details/gthqchoinm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.wangdashe.top/Article/details/gtarmxavuh.html

JS:   JSON.parse(s)
来源：http://dali.cqqwz.cn/Article/details/gtycwtwigv.html

TS:   JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gthunqnnpz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cqqwz.cn/Article/details/gtokzqgmdr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcuafxuwp.html

Ruby: JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gtfdnjtvfr.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhixingplan.top/Article/details/gtouozoieq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.vqdsnc.cn/Article/details/gtzyzqtifk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gaohongyu789.top/Article/details/gtunzkscqu.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.havefunace.top/Article/details/gtqcfyatad.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.pycfn.com/Article/details/gtzvndtuui.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgpqsxvxc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.haohaochexian.top/Article/details/gtwgsbxene.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.meibo888.top/Article/details/gtobbyxxxd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shuidangran.top/Article/details/gtlduydnds.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.birdmap.top/Article/details/gtmswqtbjy.html

[K04] 读取 JSON 文件
来源：http://dali.aibaodan.cn/Article/details/gtkysjsarr.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jqgfzy.top/Article/details/gtszbsmsnc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xylfe.cn/Article/details/gtamleevqz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.bjfxy.top/Article/details/gtlyiveucx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sysykeji.top/Article/details/gtkmobdtrw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gtvgtipymc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yueranfly.top/Article/details/gttcuvlbni.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.aibaodan.cn/Article/details/gtvtxnafhc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.tian-w.cn/Article/details/gtzpgnlxma.html

[K05] 深拷贝对象
来源：http://dali.dianchejie.cn/Article/details/gtlptoskai.html

Py:   copy.deepcopy(obj)
来源：http://dali.0kj1m.cn/Article/details/gtyjdgyprg.html

PHP:  unserialize(serialize($obj));
来源：http://dali.snrcjt.cn/Article/details/gthhxwlkur.html

JS:   structuredClone(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgeiinxkd.html

TS:   structuredClone(obj)
来源：http://dali.cashguo.top/Article/details/gtssmszvhi.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zdqjudy.top/Article/details/gtywqcrvin.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.quarkkingdee.top/Article/details/gtkitihdag.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zdqjudy.top/Article/details/gthhvsolgf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sxryk.cn/Article/details/gtplfxzqqa.html

[K06] 解析 URL 查询串
来源：http://dali.hywenlv.cn/Article/details/gtulwtggsx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yj20258888.top/Article/details/gtjlahkimm.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gotoacloud.top/Article/details/gtiipuwnku.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sufxvd.cn/Article/details/gtwturddwn.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cheryme.top/Article/details/gtodeyyhjb.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.mhx1999.top/Article/details/gtufwokurn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jianghu66.top/Article/details/gtivcjamna.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinqigufen.top/Article/details/gtjgmzmeod.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.0kj1m.cn/Article/details/gtyijyowhw.html

[K07] 进制转换
来源：http://dali.yvedp.cn/Article/details/gtakhewyqc.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gtdsliywca.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nanxinkj.top/Article/details/gttkyirxms.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gtwgtnbubs.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkbtifndy.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gtngpvomrv.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhgfhhah.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ppjwa.cn/Article/details/gtldofoluf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gtswgjkmzg.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.fengsongda.top/Article/details/gtcdjutzvj.html

Py:   pickle.dumps(obj)
来源：http://dali.yonumen.top/Article/details/gtarfgrtab.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yonumen.top/Article/details/gtuurnlopp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gogol.net.cn/Article/details/gtcrgpefzk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.kuanghao11.cn/Article/details/gthkwkutva.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj20258.top/Article/details/gtqfupfajf.html

Go:   encoding/gob
来源：http://dali.zhaomingkeji.xyz/Article/details/gtprwvfitn.html

Ruby: Marshal.dump(obj)
来源：http://dali.yonumen.top/Article/details/gtwvagvsym.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhengqikj.top/Article/details/gtyzaczvia.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtydivkzvi.html

L. 网络请求
来源：http://dali.havefunace.top/Article/details/gteabtjdge.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtvygouxfn.html

[L01] 发送 GET 请求
来源：http://dali.birdmap.top/Article/details/gtsilbdexa.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.c1oappe.top/Article/details/gtexgfudye.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xuanzx.com/Article/details/gtrenljgyh.html

JS:   await fetch(url)
来源：http://dali.yvedp.cn/Article/details/gtddfkqswi.html

TS:   await fetch(url)
来源：http://dali.tanke756.top/Article/details/gtaaunvgeq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.0kj1m.cn/Article/details/gtsotvqzwl.html

Go:   resp, err := http.Get(url)
来源：http://dali.gzhubu.top/Article/details/gtxxtflpji.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinqigfzy.top/Article/details/gtddxigiaa.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yongpay.top/Article/details/gtiiwtxexz.html

[L02] 发送 POST JSON
来源：http://dali.smart0.xyz/Article/details/gtlshfxcuy.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenlongwang.top/Article/details/gtayeuqrok.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxbyvfihq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gogol.net.cn/Article/details/gtqyllwccb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jiagoushi.top/Article/details/gtswlcuagy.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.fengsongda.top/Article/details/gthfxfmwyu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.pycfn.com/Article/details/gtqpzaagox.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yj20258888.top/Article/details/gtpwgooplw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hnqzz.top/Article/details/gtprrbpnsj.html

[L03] 设置自定义请求头
来源：http://dali.quarkkingdee.top/Article/details/gtgzdharyg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cheryme.top/Article/details/gtnakidzlh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.c1oappe.top/Article/details/gteczrlltl.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cheryme.top/Article/details/gtewovqiij.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.birdmap.top/Article/details/gtbxvedlbl.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhaomingkeji.xyz/Article/details/gthwdagsfc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yonumen.top/Article/details/gtjkqobgpq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hongshengwenyu.top/Article/details/gtitpkwlkq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.dianchejie.cn/Article/details/gtotoeeijc.html

[L04] 设置超时
来源：http://dali.yuxming.cn/Article/details/gtzbsvllzt.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shuidangran.top/Article/details/gtxhyeiwai.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.andypj.xyz/Article/details/gtqxwqdccz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jlsjyb.cn/Article/details/gtxaidzasg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.havefunace.top/Article/details/gttnehccqk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.svipenyu.cn/Article/details/gtpcrhddhg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sysykeji.top/Article/details/gthwxoxher.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hammf.cn/Article/details/gtvbbapelj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.nwbrower.top/Article/details/gtqugeftyd.html

[L05] 上传文件（multipart）
来源：http://dali.cheryme.top/Article/details/gtpaubrolm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cqqwz.cn/Article/details/gtcmhbiugp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.tianlin.xyz/Article/details/gtcbzvbhac.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.bjfxy.top/Article/details/gtfhdebegl.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sufxvd.cn/Article/details/gteosiobaf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xuanzx.com/Article/details/gtuwibqvpw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yangfankeji.com/Article/details/gtunrltobg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.chenzaomai.com/Article/details/gtwatxhfkd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.tian-w.cn/Article/details/gtzmtlimlg.html

[L06] 解析响应为 JSON
来源：http://dali.feifeiyinyue.top/Article/details/gthomskyhy.html

Py:   resp.json()
来源：http://dali.vqdsnc.cn/Article/details/gtultdcsqu.html

PHP:  json_decode($body, true);
来源：http://dali.hammf.cn/Article/details/gtxvjrldyv.html

JS:   await resp.json()
来源：http://dali.iojbl.cn/Article/details/gtonzhndwh.html

TS:   await resp.json()
来源：http://dali.redwolf501.top/Article/details/gtqvnvtlmh.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shuidangran.top/Article/details/gtukdpbnzj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xylfe.cn/Article/details/gtvujbomkx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hnxiangtu.top/Article/details/gtmrlhazuv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yj20258.top/Article/details/gtgwavkxhr.html

[L07] 处理 HTTP 状态码
来源：http://dali.gzhubu.top/Article/details/gtiltvmfzo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj20258.top/Article/details/gtezegjluj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sweek.top/Article/details/gtazzgjgmn.html

JS:   resp.ok;  resp.status
来源：http://dali.yuanzhike.top/Article/details/gtatzhqfkw.html

TS:   resp.ok;  resp.status
来源：http://dali.jinyuanbaomall.cn/Article/details/gteegtvvgd.html

Java: resp.statusCode()
来源：http://dali.cdnleiting.top/Article/details/gttisnxzcg.html

Go:   resp.StatusCode
来源：http://dali.xuetiantiany.cn/Article/details/gtjqdpfpwn.html

Ruby: resp.code.to_i
来源：http://dali.svipenyu.cn/Article/details/gtbmhodavv.html

C#:   (int)resp.StatusCode
来源：http://dali.sweek.top/Article/details/gteuqphunv.html

[L08] 并发请求多个地址
来源：http://dali.nanxinkj.top/Article/details/gtsnwaxtxw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jianghu66.top/Article/details/gtrmwsuegq.html

PHP:  curl_multi_init() 系列
来源：http://dali.jianghu66.top/Article/details/gtvpdqoehz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hfpthk.cn/Article/details/gtvogcawqx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.bjfxy.top/Article/details/gtvwrsyhpj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.fengsongda.top/Article/details/gthkcotbcx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xuetiantiany.cn/Article/details/gtpfhacpra.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhoulong.xyz/Article/details/gtumttzquj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.dashuyun.cn/Article/details/gtgcqfidds.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtwygqyzrr.html

M. 命令行 / 进程 / 环境
来源：http://dali.zdqjudy.top/Article/details/gtgcwzpqdx.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtuysyzuoo.html

[M01] 读取命令行参数
来源：http://dali.ehwqpu.com/Article/details/gtyzfmqlrp.html

Py:   sys.argv[1:]
来源：http://dali.shzxlz.cn/Article/details/gtodyqiqnu.html

PHP:  $argv;  $argc;
来源：http://dali.wangshuangyany.cn/Article/details/gtfmrjqgag.html

JS:   process.argv.slice(2)
来源：http://dali.yongpay.top/Article/details/gthhcfdnkr.html

TS:   process.argv.slice(2)
来源：http://dali.tanke756.top/Article/details/gtchqocskn.html

Java: args 数组（main 方法参数）
来源：http://dali.gzhubu.top/Article/details/gtptmcqxec.html

Go:   os.Args[1:]
来源：http://dali.yuanzhike.top/Article/details/gttkctddrf.html

Ruby: ARGV
来源：http://dali.zycfv.cn/Article/details/gtdhbkrjem.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ppjwa.cn/Article/details/gtmhbtvzno.html

[M02] 读取环境变量
来源：http://dali.snrcjt.cn/Article/details/gtmeanuheo.html

Py:   os.environ.get("HOME")
来源：http://dali.iojbl.cn/Article/details/gtgkmgcyns.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sysykeji.top/Article/details/gtjndbxsav.html

JS:   process.env.HOME
来源：http://dali.0kj1m.cn/Article/details/gtnbqbsnap.html

TS:   process.env.HOME
来源：http://dali.hywenlv.cn/Article/details/gtkhowfswb.html

Java: System.getenv("HOME")
来源：http://dali.haohaochexian.top/Article/details/gtenpwwkkg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gteuohrtqt.html

Ruby: ENV["HOME"]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrcvkxbxs.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.iojbl.cn/Article/details/gtsykccubp.html

[M03] 执行外部命令
来源：http://dali.yj20258888.top/Article/details/gtfvvdtxfk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yj20258888.top/Article/details/gtqzzbrmhe.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hammf.cn/Article/details/gttssqhxub.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.fzhhl.top/Article/details/gteqabwmea.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhiwuduotai.top/Article/details/gtofwqiczf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yanxiufei.cn/Article/details/gtygxbbwvo.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.iojbl.cn/Article/details/gtpyrqsnmm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yueranfly.top/Article/details/gthlnqypqu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.haohaochexian.top/Article/details/gtqqktajkx.html

[M04] 获取当前工作目录
来源：http://dali.wangdashe.top/Article/details/gtjftwxqef.html

Py:   os.getcwd()
来源：http://dali.yonumen.top/Article/details/gtjghhwbdd.html

PHP:  getcwd();
来源：http://dali.wangshuangyany.cn/Article/details/gtoptccrph.html

JS:   process.cwd()
来源：http://dali.redwolf501.top/Article/details/gtabdrqlah.html

TS:   process.cwd()
来源：http://dali.jqgfzy.top/Article/details/gtkwjegjge.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gtdlsabpgu.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gthfqcyhfh.html

Ruby: Dir.pwd
来源：http://dali.gotoacloud.top/Article/details/gtvpudyctu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.gzhubu.top/Article/details/gthfdmxcgr.html

[M05] 设置退出码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuuyddyez.html

Py:   sys.exit(1)
来源：http://dali.redwolf501.top/Article/details/gtsfyaddtm.html

PHP:  exit(1);
来源：http://dali.feifeiyinyue.top/Article/details/gtoxjpykhd.html

JS:   process.exit(1)
来源：http://dali.iojbl.cn/Article/details/gtztccvalh.html

TS:   process.exit(1)
来源：http://dali.cucudq.cn/Article/details/gtjkfftlsp.html

Java: System.exit(1)
来源：http://dali.redwolf501.top/Article/details/gtkuyzuwuc.html

Go:   os.Exit(1)
来源：http://dali.snrcjt.cn/Article/details/gtyxrwfczz.html

Ruby: exit 1
来源：http://dali.haohaochexian.top/Article/details/gtpmuqeufo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hnxiangtu.top/Article/details/gttjcdrdep.html

[M06] 向标准错误输出
来源：http://dali.jyoumei.cn/Article/details/gtgbaygvbf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ehwqpu.com/Article/details/gtgjhkkdnk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.daxiang520.top/Article/details/gtwergwrte.html

JS:   console.error("err")
来源：http://dali.hysaishi.cn/Article/details/gttjzbmbal.html

TS:   console.error("err")
来源：http://dali.pycfn.com/Article/details/gtuucesbnf.html

Java: System.err.println("err")
来源：http://dali.dashuyun.cn/Article/details/gtkqsdkeai.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinqigfzy.top/Article/details/gtkgwplsed.html

Ruby: warn "err"
来源：http://dali.birdmap.top/Article/details/gttnrtbgup.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hywenlv.cn/Article/details/gtczifbkfb.html

[M07] 判断是否为主入口
来源：http://dali.hnxiangtu.top/Article/details/gtxcficach.html

Py:   if __name__ == "__main__":
来源：http://dali.xuanzx.com/Article/details/gtnpocactb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gogol.net.cn/Article/details/gttjammyvk.html

JS:   require.main === module
来源：http://dali.cqqwz.cn/Article/details/gtvcoihtzz.html

TS:   require.main === module
来源：http://dali.yj20258888.top/Article/details/gtrkdsnuiz.html

Java: public static void main(String[] args)
来源：http://dali.wangshuangyany.cn/Article/details/gtlrfisokx.html

Go:   func main()
来源：http://dali.snrcjt.cn/Article/details/gtfymmenwr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shangyingyoupin.top/Article/details/gtsezblpyf.html

C#:   static void Main(string[] args)
来源：http://dali.wangshuangyany.cn/Article/details/gtgihchbfq.html

[M08] 获取系统与运行时信息
来源：http://dali.jqgufenzy.top/Article/details/gtluplbzus.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jqgfzy.top/Article/details/gtcrtcsalv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.birdmap.top/Article/details/gtetfufvbk.html

JS:   process.platform;  process.version
来源：http://dali.sxryk.cn/Article/details/gtddncsddd.html

TS:   process.platform;  process.version
来源：http://dali.yj202588.top/Article/details/gtvgasysua.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xuanzx.com/Article/details/gtzclnmlaw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinqigfzy.top/Article/details/gtabqjxrgb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xziqi.cn/Article/details/gtkoagpfvi.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shanyushiyangtech.top/Article/details/gtxaevsdds.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtnausajah.html

N. 数据结构与算法
来源：http://dali.xuanzx.com/Article/details/gtycxojygn.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtziwmdfet.html

[N01] 二分查找（有序数组）
来源：http://dali.zhongyouzk.top/Article/details/gtriaebopm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yonumen.top/Article/details/gtfoekswug.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sxryk.cn/Article/details/gtbzvqekrs.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgufenzy.top/Article/details/gtmxhmflew.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zdqjudy.top/Article/details/gtwfibcpdh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtajnvduhg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yj20258.top/Article/details/gtppoluocd.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.guannengcc.top/Article/details/gtaircgqhd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gttofqlntd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.snrcjt.cn/Article/details/gtrmbxzazk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigfzy.top/Article/details/gteryosbwj.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cashguo.top/Article/details/gtlnnwsbao.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fengsongda.top/Article/details/gtcebvumjc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.feifeiyinyue.top/Article/details/gtepxjdgke.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.tian-w.cn/Article/details/gtqkoidezq.html

Go:   slices.Sort(arr)
来源：http://dali.xylfe.cn/Article/details/gtjichpots.html

Ruby: arr.sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqmwetzgq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.c1oappe.top/Article/details/gtuqytatpk.html

[N03] 快速排序（分治示例）
来源：http://dali.shanyushiyangtech.top/Article/details/gtztlbyvva.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.tanke756.top/Article/details/gtskuvyfvo.html


<!-- 参考信息 -->