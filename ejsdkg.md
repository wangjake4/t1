代发 wailian999

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yangfankeji.com/Article/details/gthcjembnb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ywan-chungtsiang.top/Article/details/gttaxtxdwe.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cheryme.top/Article/details/gthkrrmcdh.html

[J06] 计算两时间之差
来源：http://dali.jlsjyb.cn/Article/details/gttlxunkrt.html

Py:   (end - start).total_seconds()
来源：http://dali.gzhubu.top/Article/details/gtrxyxurxo.html

PHP:  $end->diff($start)->days;
来源：http://dali.tian-w.cn/Article/details/gtpaelirfh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yonumen.top/Article/details/gtqcrjrhoy.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.316326.xyz/Article/details/gtwpiuhleo.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zycfv.cn/Article/details/gtgzfsmqaj.html

Go:   end.Sub(start).Hours()
来源：http://dali.shangyingyoupin.top/Article/details/gtgnnjnmza.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zdqjudy.top/Article/details/gtmyvpvhmb.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhixingplan.top/Article/details/gtdctbobag.html

[J07] 比较两个日期
来源：http://dali.smart0.xyz/Article/details/gtdpcryjly.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.nanxuanxn.top/Article/details/gthpxmrneg.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.tianlin.xyz/Article/details/gtadqlbbjv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhongyouzk.top/Article/details/gtalkfxvcg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.daria6918.cn/Article/details/gtcxuzqmyx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yongpay.top/Article/details/gttzcqhvml.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.quarkkingdee.top/Article/details/gtbckialah.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.daria6918.cn/Article/details/gtkjsawszq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gtllhxwdpp.html

[J08] 提取年月日与星期
来源：http://dali.jinqigufen.top/Article/details/gtuxaiimij.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.meibo888.top/Article/details/gtzurecvuq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnwhoamml.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhongyouzk.top/Article/details/gtusxtljfj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.meibo888.top/Article/details/gtqlicjimr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.iojbl.cn/Article/details/gtkwnfngdf.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinqigufen.top/Article/details/gtmdohriyv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gaohongyu789.top/Article/details/gtrbhiuybd.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hnqzz.top/Article/details/gtggjqchum.html

[J09] 时区处理
来源：http://dali.shangyingyoupin.top/Article/details/gtkwqabsdc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.wangdashe.top/Article/details/gthzjjivvr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jyoumei.cn/Article/details/gtebqawtjb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yongpay.top/Article/details/gtrwkojmkz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yanxiufei.cn/Article/details/gtfdvjpmon.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hnqzz.top/Article/details/gtvjjsatpj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhixingplan.top/Article/details/gtmtwlfmhd.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinqigufen.top/Article/details/gtfzxjkfzr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.birdmap.top/Article/details/gtyuhrarmh.html

[J10] 取今天 / 本月第一天
来源：http://dali.dianchejie.cn/Article/details/gtercshbqx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yj20258888.top/Article/details/gtpjfljtie.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jyoumei.cn/Article/details/gtagwekiun.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtpkziwxvt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwietbaew.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtaglvagkn.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.redwolf501.top/Article/details/gteaugzxhi.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yj202588.top/Article/details/gtilvyyhay.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhixingplan.top/Article/details/gtxvgvfhdt.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlwhhksmx.html

K. JSON 与序列化
来源：http://dali.xylfe.cn/Article/details/gtcgvnthdp.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtcqfwqlxj.html

[K01] 对象转 JSON 字符串
来源：http://dali.fzhhl.top/Article/details/gtbxvmmpbt.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.nwbrower.top/Article/details/gtvihhwdxe.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.chenzaomai.com/Article/details/gtopxisqsa.html

JS:   JSON.stringify(obj)
来源：http://dali.svipenyu.cn/Article/details/gtqfuprnea.html

TS:   JSON.stringify(obj)
来源：http://dali.tanke756.top/Article/details/gtwklxrbfi.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.nwbrower.top/Article/details/gtgwlxiliz.html

Go:   json.Marshal(obj)
来源：http://dali.nwbrower.top/Article/details/gtvuoxwdqs.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhixingplan.top/Article/details/gtdylsbmun.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xziqi.cn/Article/details/gtxzwbqesb.html

[K02] JSON 字符串转对象
来源：http://dali.daxiang520.top/Article/details/gtdqsmmmft.html

Py:   json.loads(s)
来源：http://dali.jianghu66.top/Article/details/gtkqdmjvzp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tanke756.top/Article/details/gtbattpduf.html

JS:   JSON.parse(s)
来源：http://dali.quarkkingdee.top/Article/details/gtnfiwzuus.html

TS:   JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtetalynts.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.guowangkeji.top/Article/details/gtjbriejpr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.haohaochexian.top/Article/details/gtbfhnjptr.html

Ruby: JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gtjahxfthz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jyoumei.cn/Article/details/gtfpeocstz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvmlzsiwj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.snrcjt.cn/Article/details/gtlkntdrcm.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yonumen.top/Article/details/gtwhsouxob.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gttgqogusg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.redwolf501.top/Article/details/gtfaysdadr.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tianlin.xyz/Article/details/gtapupqqoz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shanyushiyangtech.top/Article/details/gtudoddnuv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yonumen.top/Article/details/gtiznjawxn.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jqgufenzy.top/Article/details/gtlrexcfep.html

[K04] 读取 JSON 文件
来源：http://dali.jqgfzy.top/Article/details/gtrfwxqisg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.316326.xyz/Article/details/gthukogiob.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ehwqpu.com/Article/details/gtlbskdhod.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tianlin.xyz/Article/details/gtoeodjwrv.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnxiangtu.top/Article/details/gtpqfsnanm.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.guowangkeji.top/Article/details/gtqlmzajxy.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hfpthk.cn/Article/details/gtcyfgonzw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sufxvd.cn/Article/details/gteqqlefkt.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hywenlv.cn/Article/details/gtawlephmz.html

[K05] 深拷贝对象
来源：http://dali.yueranfly.top/Article/details/gtvsxvwdll.html

Py:   copy.deepcopy(obj)
来源：http://dali.aizwys.cn/Article/details/gtwlvzszkd.html

PHP:  unserialize(serialize($obj));
来源：http://dali.0kj1m.cn/Article/details/gtmjycgilz.html

JS:   structuredClone(obj)
来源：http://dali.hysaishi.cn/Article/details/gttdncgyjp.html

TS:   structuredClone(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtmlkevwxk.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hnqzz.top/Article/details/gtwewtkjpg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.birdmap.top/Article/details/gtidfmpbor.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.sxryk.cn/Article/details/gtxannwcvd.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jyoumei.cn/Article/details/gtoetxvlrx.html

[K06] 解析 URL 查询串
来源：http://dali.cheryme.top/Article/details/gtihvaeegf.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.smart0.xyz/Article/details/gtntjrlgek.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.havefunace.top/Article/details/gtrqlsceps.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnxiangtu.top/Article/details/gtgzbmcgcb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ppjwa.cn/Article/details/gtwjewftzb.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.chenjidiqi.icu/Article/details/gtwbfjuegy.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hfpthk.cn/Article/details/gtgikikyda.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.9152youxi.cn/Article/details/gtqkpbrxlj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xziqi.cn/Article/details/gtgplcnkrv.html

[K07] 进制转换
来源：http://dali.ydzc1.top/Article/details/gtfgpthefp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gtrxhmdlmg.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.dashuyun.cn/Article/details/gtpcphpmbr.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gtznocyidi.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gtkidgqsme.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gtaxudvlxu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ybcxt.top/Article/details/gtpynemxtn.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxjhvclya.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gtrpmzkclp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.aibaodan.cn/Article/details/gtcjylzwio.html

Py:   pickle.dumps(obj)
来源：http://dali.cashguo.top/Article/details/gtoxjbsetp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zycfv.cn/Article/details/gtcdwspwor.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.smart0.xyz/Article/details/gtonvcohuy.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gogol.net.cn/Article/details/gtoazsnvvx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.mhx1999.top/Article/details/gtygnafazm.html

Go:   encoding/gob
来源：http://dali.yanxiufei.cn/Article/details/gtlqtgcjml.html

Ruby: Marshal.dump(obj)
来源：http://dali.hammf.cn/Article/details/gtddttnmyk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhixingplan.top/Article/details/gtzeaacpgd.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtqyipuloa.html

L. 网络请求
来源：http://dali.9152youxi.cn/Article/details/gttjwxdulb.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtkrifttfc.html

[L01] 发送 GET 请求
来源：http://dali.shzxlz.cn/Article/details/gtlzktokjs.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hnxiangtu.top/Article/details/gtnsszhllu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hywenlv.cn/Article/details/gtwmpapmsx.html

JS:   await fetch(url)
来源：http://dali.feifeiyinyue.top/Article/details/gtkpqbhnhj.html

TS:   await fetch(url)
来源：http://dali.hywenlv.cn/Article/details/gtzvwkekht.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.dashuyun.cn/Article/details/gtuyrhniiq.html

Go:   resp, err := http.Get(url)
来源：http://dali.sysykeji.top/Article/details/gtudwgvaky.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinghuilouyu.cn/Article/details/gtwjhzysxs.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yj20258888.top/Article/details/gtkfrzpani.html

[L02] 发送 POST JSON
来源：http://dali.dashuyun.cn/Article/details/gtlweqalru.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hywenlv.cn/Article/details/gtojyljqmo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.gotoacloud.top/Article/details/gtddidrdtd.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj20258.top/Article/details/gtzjquedav.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtftxpevwl.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinyuanbaomall.cn/Article/details/gttoavboph.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shzxlz.cn/Article/details/gtpnkdqwyw.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zdqjudy.top/Article/details/gtmbidyjww.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.chenjidiqi.icu/Article/details/gtdllnunek.html

[L03] 设置自定义请求头
来源：http://dali.ivvv.top/Article/details/gtadiuwvtn.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shanyushiyangtech.top/Article/details/gtjolfuisg.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xuetiantiany.cn/Article/details/gtvhhcupvk.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.havefunace.top/Article/details/gtezclmpxk.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tianlin.xyz/Article/details/gtsbymynrt.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.chenlongwang.top/Article/details/gtkysaqsgt.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jianghu66.top/Article/details/gtqztfelwn.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.smart0.xyz/Article/details/gthvitfnhz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.quarkkingdee.top/Article/details/gtcaxuryzg.html

[L04] 设置超时
来源：http://dali.316326.xyz/Article/details/gtfrdvznpd.html

Py:   requests.get(url, timeout=5)
来源：http://dali.316326.xyz/Article/details/gtigmnqzry.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.iojbl.cn/Article/details/gtndwysioi.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ehwqpu.com/Article/details/gtcvooiwvz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuetiantiany.cn/Article/details/gtjnossjkr.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.meibo888.top/Article/details/gtfsbsgfpa.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtydtfrerf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hnxiangtu.top/Article/details/gtzynonstn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.iojbl.cn/Article/details/gtydcrszog.html

[L05] 上传文件（multipart）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbxvmkvnn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.9152youxi.cn/Article/details/gtqreqlqja.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhixingplan.top/Article/details/gtyohcpemk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgufenzy.top/Article/details/gtpheqrzkc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxzprhjnr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.smart0.xyz/Article/details/gttoiyuugc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhixingplan.top/Article/details/gtymmzftyp.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yangfankeji.com/Article/details/gtrlzwdvjn.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtmzxywyys.html

[L06] 解析响应为 JSON
来源：http://dali.jianghu66.top/Article/details/gtvlbhkxgs.html

Py:   resp.json()
来源：http://dali.zhiwuduotai.top/Article/details/gttdohcjam.html

PHP:  json_decode($body, true);
来源：http://dali.316326.xyz/Article/details/gttzchmsec.html

JS:   await resp.json()
来源：http://dali.jyoumei.cn/Article/details/gtoupnqdbi.html

TS:   await resp.json()
来源：http://dali.yj20258888.top/Article/details/gtyervcivs.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yuxming.cn/Article/details/gtvhdldnkn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcgqtaimr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.mhx1999.top/Article/details/gtlqpupbqn.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xziqi.cn/Article/details/gtmxocciwc.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinqigfzy.top/Article/details/gtvoysfgwg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.gogol.net.cn/Article/details/gtbaernmrb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hywenlv.cn/Article/details/gtmjmkqedi.html

JS:   resp.ok;  resp.status
来源：http://dali.pycfn.com/Article/details/gtfyztdxqq.html

TS:   resp.ok;  resp.status
来源：http://dali.cashguo.top/Article/details/gtovizqofk.html

Java: resp.statusCode()
来源：http://dali.yangfankeji.com/Article/details/gtneabulva.html

Go:   resp.StatusCode
来源：http://dali.cucudq.cn/Article/details/gtzztdhvwq.html

Ruby: resp.code.to_i
来源：http://dali.zdqjudy.top/Article/details/gtsjumceyc.html

C#:   (int)resp.StatusCode
来源：http://dali.gogol.net.cn/Article/details/gtscdwfnqf.html

[L08] 并发请求多个地址
来源：http://dali.yvedp.cn/Article/details/gtgsyptmrt.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yj20258888.top/Article/details/gtjupusruj.html

PHP:  curl_multi_init() 系列
来源：http://dali.xziqi.cn/Article/details/gtrtdpqmmt.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgufenzy.top/Article/details/gtufcjmvku.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gaohongyu789.top/Article/details/gthwczrmpz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yj20258888.top/Article/details/gtfgggmkiw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xinyue.icu/Article/details/gtmprzgbvu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.daxiang520.top/Article/details/gtrilasypo.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinqigufen.top/Article/details/gtjngivdxb.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtisqmwpbn.html

M. 命令行 / 进程 / 环境
来源：http://dali.meibo888.top/Article/details/gtojcdjpxu.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtwgxvsoks.html

[M01] 读取命令行参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtfzqhesgo.html

Py:   sys.argv[1:]
来源：http://dali.zhengqikj.top/Article/details/gtpuhewywn.html

PHP:  $argv;  $argc;
来源：http://dali.nanxinkj.top/Article/details/gtpjceaafn.html

JS:   process.argv.slice(2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gteowjzecq.html

TS:   process.argv.slice(2)
来源：http://dali.tianlin.xyz/Article/details/gtvrrjerui.html

Java: args 数组（main 方法参数）
来源：http://dali.haohaochexian.top/Article/details/gtevwjsmnk.html

Go:   os.Args[1:]
来源：http://dali.yj20258.top/Article/details/gtxhiitgne.html

Ruby: ARGV
来源：http://dali.chenlongwang.top/Article/details/gtemxeymfp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhengqikj.top/Article/details/gtdwsqrojp.html

[M02] 读取环境变量
来源：http://dali.yanxiufei.cn/Article/details/gtywhstfed.html

Py:   os.environ.get("HOME")
来源：http://dali.jiagoushi.top/Article/details/gtesegkzgk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.chenzaomai.com/Article/details/gtgbiyngmp.html

JS:   process.env.HOME
来源：http://dali.shanyushiyangtech.top/Article/details/gtuuozzpdx.html

TS:   process.env.HOME
来源：http://dali.sysykeji.top/Article/details/gtrbywcvzs.html

Java: System.getenv("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gtsoysihho.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gtdsgyteka.html

Ruby: ENV["HOME"]
来源：http://dali.haohaochexian.top/Article/details/gtrmeczecv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ivvv.top/Article/details/gtttlslphn.html

[M03] 执行外部命令
来源：http://dali.hysaishi.cn/Article/details/gtkhmmoygo.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zdqjudy.top/Article/details/gtfpevoxgd.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.dianchejie.cn/Article/details/gtvohwpyqd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cqqwz.cn/Article/details/gtqzyezoyf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinqigfzy.top/Article/details/gtwqufjpwg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.dashuyun.cn/Article/details/gtndpcdwmk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tianlin.xyz/Article/details/gtdpbdkpth.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhongyouzk.top/Article/details/gtzmnfasnq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jqgufenzy.top/Article/details/gtcwdvwrll.html

[M04] 获取当前工作目录
来源：http://dali.yangfankeji.com/Article/details/gteadctxxn.html

Py:   os.getcwd()
来源：http://dali.xuanzx.com/Article/details/gtdxttmvwm.html

PHP:  getcwd();
来源：http://dali.wangshuangyany.cn/Article/details/gtaklrulqn.html

JS:   process.cwd()
来源：http://dali.pengpengdd.cyou/Article/details/gtntbdrtaj.html

TS:   process.cwd()
来源：http://dali.sweek.top/Article/details/gthxlixjpo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.9152youxi.cn/Article/details/gtxugosknz.html

Go:   os.Getwd()
来源：http://dali.xuanzx.com/Article/details/gthjbqlrih.html

Ruby: Dir.pwd
来源：http://dali.xinyue.icu/Article/details/gtuhcwuegm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ydzc1.top/Article/details/gtusuhfxuf.html

[M05] 设置退出码
来源：http://dali.jyoumei.cn/Article/details/gtqohwiwpx.html

Py:   sys.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gtwxwkogic.html

PHP:  exit(1);
来源：http://dali.jqgufenzy.top/Article/details/gtststbylr.html

JS:   process.exit(1)
来源：http://dali.bjfxy.top/Article/details/gthpfaszws.html

TS:   process.exit(1)
来源：http://dali.daria6918.cn/Article/details/gtshqrrjxu.html

Java: System.exit(1)
来源：http://dali.sxryk.cn/Article/details/gtsmwlcokv.html

Go:   os.Exit(1)
来源：http://dali.zhixingplan.top/Article/details/gtwqinaqay.html

Ruby: exit 1
来源：http://dali.daria6918.cn/Article/details/gttlowelaj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hongshengwenyu.top/Article/details/gthfzaubrf.html

[M06] 向标准错误输出
来源：http://dali.fzhhl.top/Article/details/gtcvcjrnis.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj20258888.top/Article/details/gtyopscvsp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.nanxinkj.top/Article/details/gtseyhwvnk.html

JS:   console.error("err")
来源：http://dali.havefunace.top/Article/details/gtesmafwmd.html

TS:   console.error("err")
来源：http://dali.gogol.net.cn/Article/details/gttdnlqnud.html

Java: System.err.println("err")
来源：http://dali.ivvv.top/Article/details/gtcwocthuu.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shzxlz.cn/Article/details/gtmopucagp.html

Ruby: warn "err"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvheuysug.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cqqwz.cn/Article/details/gtesvngiys.html

[M07] 判断是否为主入口
来源：http://dali.pycfn.com/Article/details/gtvrjmhkui.html

Py:   if __name__ == "__main__":
来源：http://dali.sxryk.cn/Article/details/gtizowugol.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gzhubu.top/Article/details/gttregjmgx.html

JS:   require.main === module
来源：http://dali.redwolf501.top/Article/details/gtqipolgik.html

TS:   require.main === module
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvwkcqktz.html

Java: public static void main(String[] args)
来源：http://dali.wangshuangyany.cn/Article/details/gtrwleiten.html

Go:   func main()
来源：http://dali.gzhubu.top/Article/details/gtfbtkniwa.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.iojbl.cn/Article/details/gtidylckbu.html

C#:   static void Main(string[] args)
来源：http://dali.sufxvd.cn/Article/details/gtjpnfzixn.html

[M08] 获取系统与运行时信息
来源：http://dali.jlsjyb.cn/Article/details/gtyjroovky.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xuanzx.com/Article/details/gthgpmsplx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xziqi.cn/Article/details/gtidplxjba.html

JS:   process.platform;  process.version
来源：http://dali.shanyushiyangtech.top/Article/details/gtsggukscv.html

TS:   process.platform;  process.version
来源：http://dali.svipenyu.cn/Article/details/gtnzilkiek.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jlsjyb.cn/Article/details/gtupcxlhem.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shzxlz.cn/Article/details/gtfssryeol.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.pycfn.com/Article/details/gtgmgxqess.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ivvv.top/Article/details/gtnnmboshz.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtswcycfey.html

N. 数据结构与算法
来源：http://dali.feifeiyinyue.top/Article/details/gtwtwumjvt.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtkqvvmnpi.html

[N01] 二分查找（有序数组）
来源：http://dali.guannengcc.top/Article/details/gtgdfzuzvo.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cheryme.top/Article/details/gtcbarlsmy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yueranfly.top/Article/details/gtcqkzcezt.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yanxiufei.cn/Article/details/gtwfublwvr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigufen.top/Article/details/gtvzeebfwc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.pycfn.com/Article/details/gtsmhnudha.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gtjnifomsk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.havefunace.top/Article/details/gtydlqmmgs.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gtwgmatrji.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.dashuyun.cn/Article/details/gtumxwcuxv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cucudq.cn/Article/details/gtozqkjgta.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.bjfxy.top/Article/details/gtzrmqzjmw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cdnleiting.top/Article/details/gtfbohvope.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aibaodan.cn/Article/details/gtvdpjbguf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhongyouzk.top/Article/details/gtrnuntwny.html

Go:   slices.Sort(arr)
来源：http://dali.jqgfzy.top/Article/details/gttuqrtzjv.html

Ruby: arr.sort
来源：http://dali.daria6918.cn/Article/details/gtjkfrtosx.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hfpthk.cn/Article/details/gtmklryrfp.html

[N03] 快速排序（分治示例）
来源：http://dali.yj20258.top/Article/details/gtwyxwsfup.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.snrcjt.cn/Article/details/gtxsgxtopz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.tanke756.top/Article/details/gtuzoartyn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shzxlz.cn/Article/details/gtttfzhofl.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxuanxn.top/Article/details/gtioxpizhw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.guowangkeji.top/Article/details/gtukvhebdd.html


<!-- 参考信息 -->