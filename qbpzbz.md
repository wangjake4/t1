代发 wailian999

Py:   (end - start).total_seconds()
来源：http://dali.cashguo.top/Article/details/gtqinrasos.html

PHP:  $end->diff($start)->days;
来源：http://dali.sufxvd.cn/Article/details/gtygrlsgkv.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.chenjidiqi.icu/Article/details/gtnoyqdcer.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yuanzhike.top/Article/details/gtutzoiqvd.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cqqwz.cn/Article/details/gtxvserchc.html

Go:   end.Sub(start).Hours()
来源：http://dali.jqgfzy.top/Article/details/gtzdkjavby.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jqgfzy.top/Article/details/gtywrwkhqh.html

C#:   (end - start).TotalSeconds
来源：http://dali.cucudq.cn/Article/details/gtkzhzgrlz.html

[J07] 比较两个日期
来源：http://dali.yonumen.top/Article/details/gtublpfliy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gtpdccdzmz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhongyouzk.top/Article/details/gtbprbxnwa.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxuanxn.top/Article/details/gtxasvdulv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigufen.top/Article/details/gtpeowkums.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhoulong.xyz/Article/details/gtaswhsayr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhijiandao.cn/Article/details/gtzlrbreqs.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenlongwang.top/Article/details/gtjufinstj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.dashuyun.cn/Article/details/gthcowhofk.html

[J08] 提取年月日与星期
来源：http://dali.cdnleiting.top/Article/details/gtsinduaxy.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinqigufen.top/Article/details/gtaastcnen.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.guowangkeji.top/Article/details/gtfrotkklv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yuanzhike.top/Article/details/gtxwisylip.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ivvv.top/Article/details/gttjroixql.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.tianlin.xyz/Article/details/gtsobwmsmm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cqqwz.cn/Article/details/gtsvcjhfjh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.guannengcc.top/Article/details/gtsdmhaact.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cqqwz.cn/Article/details/gtewmbnivl.html

[J09] 时区处理
来源：http://dali.cheryme.top/Article/details/gtjrcwbvty.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hnxiangtu.top/Article/details/gtuaifxjjt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cheryme.top/Article/details/gtsjdalkif.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlleriwse.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hammf.cn/Article/details/gtzdtrzonl.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yongpay.top/Article/details/gtbwsbbbsx.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yonumen.top/Article/details/gtczumhran.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.chenzaomai.com/Article/details/gtynxdyjfh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.tian-w.cn/Article/details/gttwltuqvw.html

[J10] 取今天 / 本月第一天
来源：http://dali.ivvv.top/Article/details/gtcbekjept.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gogol.net.cn/Article/details/gtpckuubqf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yvedp.cn/Article/details/gtjvfzoaxx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jqgfzy.top/Article/details/gtliwaosqf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.guowangkeji.top/Article/details/gtujkycdtm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jqgfzy.top/Article/details/gtklkjcqtu.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.kuanghao11.cn/Article/details/gtvgvzuzqy.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yvedp.cn/Article/details/gtjqgeagfl.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.aibaodan.cn/Article/details/gtufwhbwkq.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtsijujxxa.html

K. JSON 与序列化
来源：http://dali.yj202588.top/Article/details/gtlfqsmhdc.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtuqwhutdc.html

[K01] 对象转 JSON 字符串
来源：http://dali.guowangkeji.top/Article/details/gtnybdzcxr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgmakggam.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jyoumei.cn/Article/details/gtapaaochd.html

JS:   JSON.stringify(obj)
来源：http://dali.haohaochexian.top/Article/details/gtudlngjoe.html

TS:   JSON.stringify(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrmmramfj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.redwolf501.top/Article/details/gttplaslvv.html

Go:   json.Marshal(obj)
来源：http://dali.hnqzz.top/Article/details/gtbhcxuhjz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gzhubu.top/Article/details/gtbyowludy.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvyzbtlti.html

[K02] JSON 字符串转对象
来源：http://dali.gogol.net.cn/Article/details/gtyewfrvak.html

Py:   json.loads(s)
来源：http://dali.jianghu66.top/Article/details/gteqivqnym.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gzhubu.top/Article/details/gthltkoyie.html

JS:   JSON.parse(s)
来源：http://dali.ivvv.top/Article/details/gtrgisgedt.html

TS:   JSON.parse(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtoxhsnibf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sweek.top/Article/details/gtlhbytliz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvrptzumm.html

Ruby: JSON.parse(s)
来源：http://dali.smart0.xyz/Article/details/gtlgwrnjlt.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.pycfn.com/Article/details/gtzqjydmbr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ehwqpu.com/Article/details/gturkyxckj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinqigufen.top/Article/details/gtcwunnlqa.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.quarkkingdee.top/Article/details/gtxlnlhkzf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tanke756.top/Article/details/gtzvtcyuka.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmdjlpvtd.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zycfv.cn/Article/details/gtnggjvsxx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhoulong.xyz/Article/details/gtdebxkooj.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.fzhhl.top/Article/details/gttvedvano.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ppjwa.cn/Article/details/gtssicdxzn.html

[K04] 读取 JSON 文件
来源：http://dali.yongpay.top/Article/details/gtcbehddoa.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jlsjyb.cn/Article/details/gtopedklmx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gogol.net.cn/Article/details/gtkkquirsv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xziqi.cn/Article/details/gtcksikhwb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jyoumei.cn/Article/details/gtvpmeusdt.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.wangshuangyany.cn/Article/details/gtpsmefmji.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.kuanghao11.cn/Article/details/gtterztqog.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.quarkkingdee.top/Article/details/gtvcyjcsqz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinqigfzy.top/Article/details/gtdwvjscms.html

[K05] 深拷贝对象
来源：http://dali.tianlin.xyz/Article/details/gtsuopxgxv.html

Py:   copy.deepcopy(obj)
来源：http://dali.gzhubu.top/Article/details/gtbipglqlg.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkprrdcnw.html

JS:   structuredClone(obj)
来源：http://dali.havefunace.top/Article/details/gtxtesptxo.html

TS:   structuredClone(obj)
来源：http://dali.tanke756.top/Article/details/gtcxeqrknx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hnqzz.top/Article/details/gtjqfrnfoq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.dashuyun.cn/Article/details/gtzqyvjlis.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.kuanghao11.cn/Article/details/gtyyfblqym.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jlsjyb.cn/Article/details/gthtbxpwdo.html

[K06] 解析 URL 查询串
来源：http://dali.iojbl.cn/Article/details/gtarohnxvh.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hnxiangtu.top/Article/details/gtzdizkjwy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gaohongyu789.top/Article/details/gtccczforj.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.havefunace.top/Article/details/gtybxlcasr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daria6918.cn/Article/details/gtnrsaqwnm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yuanzhike.top/Article/details/gtxmkncsvx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gtloxfbezw.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.dianchejie.cn/Article/details/gthlrnxosw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxbzownoj.html

[K07] 进制转换
来源：http://dali.birdmap.top/Article/details/gtuedftgli.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gttowwdhnm.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdbiykbce.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtpaopmfwk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gtqpykleef.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.havefunace.top/Article/details/gtowonasuf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.daxiang520.top/Article/details/gtmyjlakvf.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.nanxinkj.top/Article/details/gtuyolirbm.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj20258.top/Article/details/gtwrihlhkv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.redwolf501.top/Article/details/gteqvityht.html

Py:   pickle.dumps(obj)
来源：http://dali.pycfn.com/Article/details/gtwywtxfia.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xylfe.cn/Article/details/gtexacinrc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.birdmap.top/Article/details/gthxnyccaz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhiwuduotai.top/Article/details/gtgowiayzi.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xinyue.icu/Article/details/gtkfzvwfdd.html

Go:   encoding/gob
来源：http://dali.shuidangran.top/Article/details/gtvtrhhruc.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzkfomxqe.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ppjwa.cn/Article/details/gtqgxdjzie.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtjtthclrd.html

L. 网络请求
来源：http://dali.cheryme.top/Article/details/gtupytzjiu.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtfcbpsxyi.html

[L01] 发送 GET 请求
来源：http://dali.gaohongyu789.top/Article/details/gtmzwtixtb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkacgafnd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.guowangkeji.top/Article/details/gtzmklomfe.html

JS:   await fetch(url)
来源：http://dali.zhixingplan.top/Article/details/gtkqfwnuih.html

TS:   await fetch(url)
来源：http://dali.chenjidiqi.icu/Article/details/gtsfivgxnq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.nanxuanxn.top/Article/details/gtvhodimzm.html

Go:   resp, err := http.Get(url)
来源：http://dali.nanxinkj.top/Article/details/gtxapjdbnn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhixingplan.top/Article/details/gtwrbomuzl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sysykeji.top/Article/details/gtyszcrkzy.html

[L02] 发送 POST JSON
来源：http://dali.hongshengwenyu.top/Article/details/gtvuertdud.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.dianchejie.cn/Article/details/gtrzdzwrsf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yonumen.top/Article/details/gtcschjvvx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuanzhike.top/Article/details/gtvequrcrm.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenlongwang.top/Article/details/gtknrsaczu.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinghuilouyu.cn/Article/details/gtgpnswpgq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shangyingyoupin.top/Article/details/gtdaaozltq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sxryk.cn/Article/details/gtssjtebtr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.chenjidiqi.icu/Article/details/gtsdwnicsx.html

[L03] 设置自定义请求头
来源：http://dali.gotoacloud.top/Article/details/gtbujbjkuu.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.vqdsnc.cn/Article/details/gttpzyqoqu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtxzqzjvia.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.kuanghao11.cn/Article/details/gtoqajecrb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tianlin.xyz/Article/details/gtarzhaymv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jyoumei.cn/Article/details/gtpnjuqsqi.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gtwiccpadl.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gogol.net.cn/Article/details/gtmpgdvttj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cucudq.cn/Article/details/gtdnzqlbrw.html

[L04] 设置超时
来源：http://dali.yvedp.cn/Article/details/gtkrjtcxvf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hnxiangtu.top/Article/details/gtasodpwhp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cdnleiting.top/Article/details/gtafcqclfr.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangdashe.top/Article/details/gtfydcpewy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnxiangtu.top/Article/details/gtrzuwbyoc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xuetiantiany.cn/Article/details/gtfwkgpidd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.kuanghao11.cn/Article/details/gtooftaijh.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shangyingyoupin.top/Article/details/gtihlzaogz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sufxvd.cn/Article/details/gtdmzjyngq.html

[L05] 上传文件（multipart）
来源：http://dali.hysaishi.cn/Article/details/gtmhqqekqb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yonumen.top/Article/details/gtzyhatcwo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hysaishi.cn/Article/details/gtskmbtdgn.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuanzx.com/Article/details/gtppjqiaqj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yangfankeji.com/Article/details/gttqpcnxnk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yanxiufei.cn/Article/details/gtgxitecux.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.pycfn.com/Article/details/gttnzjecul.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cqqwz.cn/Article/details/gtpqtgrepk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtcvdueaed.html

[L06] 解析响应为 JSON
来源：http://dali.jianghu66.top/Article/details/gtbhayqydo.html

Py:   resp.json()
来源：http://dali.fengsongda.top/Article/details/gtzhvubgrc.html

PHP:  json_decode($body, true);
来源：http://dali.jiagoushi.top/Article/details/gtahubgzca.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gtxoxiibcc.html

TS:   await resp.json()
来源：http://dali.cdnleiting.top/Article/details/gttwqewnhq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.guannengcc.top/Article/details/gtmjdtauex.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.daxiang520.top/Article/details/gtfgqurbgq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.316326.xyz/Article/details/gtvfzfkdsj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jqgfzy.top/Article/details/gthdpmjcqc.html

[L07] 处理 HTTP 状态码
来源：http://dali.jqgufenzy.top/Article/details/gttkoqkooy.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hysaishi.cn/Article/details/gtnnhdbuqi.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shangyingyoupin.top/Article/details/gtawofwcmu.html

JS:   resp.ok;  resp.status
来源：http://dali.dashuyun.cn/Article/details/gtkovabquw.html

TS:   resp.ok;  resp.status
来源：http://dali.tanke756.top/Article/details/gtiwviftii.html

Java: resp.statusCode()
来源：http://dali.pengpengdd.cyou/Article/details/gtltextwyb.html

Go:   resp.StatusCode
来源：http://dali.wangshuangyany.cn/Article/details/gtogfyapke.html

Ruby: resp.code.to_i
来源：http://dali.tian-w.cn/Article/details/gtmjoxghpu.html

C#:   (int)resp.StatusCode
来源：http://dali.ehwqpu.com/Article/details/gtzdcmbwqt.html

[L08] 并发请求多个地址
来源：http://dali.jqgfzy.top/Article/details/gtklniilpd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sxryk.cn/Article/details/gtohxmbiwk.html

PHP:  curl_multi_init() 系列
来源：http://dali.yongpay.top/Article/details/gtjzqrtmcp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.havefunace.top/Article/details/gtwsvsrgyg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tanke756.top/Article/details/gtkibgdzgx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shangyingyoupin.top/Article/details/gtqtjufanq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shuidangran.top/Article/details/gtipcwlcvq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.guannengcc.top/Article/details/gtvffgznhs.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.feifeiyinyue.top/Article/details/gtknpnzpzj.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtupdmhhwd.html

M. 命令行 / 进程 / 环境
来源：http://dali.zycfv.cn/Article/details/gtrtmnfpyj.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gttwqdgifr.html

[M01] 读取命令行参数
来源：http://dali.hongshengwenyu.top/Article/details/gteaxamiia.html

Py:   sys.argv[1:]
来源：http://dali.meibo888.top/Article/details/gtsoxpijui.html

PHP:  $argv;  $argc;
来源：http://dali.snrcjt.cn/Article/details/gtpcfpoqni.html

JS:   process.argv.slice(2)
来源：http://dali.zhongyouzk.top/Article/details/gteqpdfqrz.html

TS:   process.argv.slice(2)
来源：http://dali.havefunace.top/Article/details/gtohniaxwp.html

Java: args 数组（main 方法参数）
来源：http://dali.0kj1m.cn/Article/details/gtloehcwvp.html

Go:   os.Args[1:]
来源：http://dali.yongpay.top/Article/details/gtnqitskah.html

Ruby: ARGV
来源：http://dali.andypj.xyz/Article/details/gtlbdndzam.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sufxvd.cn/Article/details/gtxbwlvmei.html

[M02] 读取环境变量
来源：http://dali.ivvv.top/Article/details/gtjakkyugl.html

Py:   os.environ.get("HOME")
来源：http://dali.hysaishi.cn/Article/details/gtzbysxlnd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cdnleiting.top/Article/details/gtpacxvswq.html

JS:   process.env.HOME
来源：http://dali.wangshuangyany.cn/Article/details/gtzvgbupyx.html

TS:   process.env.HOME
来源：http://dali.svipenyu.cn/Article/details/gttwmvikkz.html

Java: System.getenv("HOME")
来源：http://dali.yuanzhike.top/Article/details/gtdnnfrszz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sufxvd.cn/Article/details/gttnrzmfeu.html

Ruby: ENV["HOME"]
来源：http://dali.ydzc1.top/Article/details/gtoxjwsntz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ivvv.top/Article/details/gtagpcuizt.html

[M03] 执行外部命令
来源：http://dali.shuidangran.top/Article/details/gtalylubzx.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlwedenmp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.svipenyu.cn/Article/details/gttnyovkyw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.aizwys.cn/Article/details/gtrqezlktq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.vqdsnc.cn/Article/details/gtalimglxf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.guannengcc.top/Article/details/gttptlbqbi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinghuilouyu.cn/Article/details/gtkoxirwju.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.chenlongwang.top/Article/details/gtzlmegbqi.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yvedp.cn/Article/details/gtsiciflui.html

[M04] 获取当前工作目录
来源：http://dali.svipenyu.cn/Article/details/gtrfxevnpp.html

Py:   os.getcwd()
来源：http://dali.hysaishi.cn/Article/details/gtfokmxrav.html

PHP:  getcwd();
来源：http://dali.jqgfzy.top/Article/details/gtycnwsdsp.html

JS:   process.cwd()
来源：http://dali.zhixingplan.top/Article/details/gtnlwrvvim.html

TS:   process.cwd()
来源：http://dali.gaohongyu789.top/Article/details/gtrubnsxlf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhoulong.xyz/Article/details/gtjkctcmyu.html

Go:   os.Getwd()
来源：http://dali.kuanghao11.cn/Article/details/gtlhqpvhab.html

Ruby: Dir.pwd
来源：http://dali.daxiang520.top/Article/details/gtvzqyhxwi.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cheryme.top/Article/details/gtplvzdalu.html

[M05] 设置退出码
来源：http://dali.zhixingplan.top/Article/details/gtzrpepyph.html

Py:   sys.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gtkbqngjao.html

PHP:  exit(1);
来源：http://dali.nanxinkj.top/Article/details/gtzpkxypju.html

JS:   process.exit(1)
来源：http://dali.hammf.cn/Article/details/gtrevctxsf.html

TS:   process.exit(1)
来源：http://dali.shuidangran.top/Article/details/gtpzryzfgo.html

Java: System.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gtymfcqkim.html

Go:   os.Exit(1)
来源：http://dali.pycfn.com/Article/details/gtntdnuaut.html

Ruby: exit 1
来源：http://dali.ybcxt.top/Article/details/gtkpyomhrg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shanyushiyangtech.top/Article/details/gtqpcexvrv.html

[M06] 向标准错误输出
来源：http://dali.kuanghao11.cn/Article/details/gtizabautg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinqigufen.top/Article/details/gthixczjsi.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.guannengcc.top/Article/details/gtnfgbfmji.html

JS:   console.error("err")
来源：http://dali.shzxlz.cn/Article/details/gtjrdzysmu.html

TS:   console.error("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjqzckvrg.html

Java: System.err.println("err")
来源：http://dali.gogol.net.cn/Article/details/gtveawdrup.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj20258888.top/Article/details/gtljmlnvgz.html

Ruby: warn "err"
来源：http://dali.ybcxt.top/Article/details/gtacqpozfk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tanke756.top/Article/details/gtjlwgppem.html

[M07] 判断是否为主入口
来源：http://dali.hnxiangtu.top/Article/details/gtaovfegte.html

Py:   if __name__ == "__main__":
来源：http://dali.wangdashe.top/Article/details/gtzykmbysk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.smart0.xyz/Article/details/gtgbkeeytz.html

JS:   require.main === module
来源：http://dali.hnxiangtu.top/Article/details/gtacndvffr.html

TS:   require.main === module
来源：http://dali.ehwqpu.com/Article/details/gtujyhuhbt.html

Java: public static void main(String[] args)
来源：http://dali.cdnleiting.top/Article/details/gtzoluzivu.html

Go:   func main()
来源：http://dali.dashuyun.cn/Article/details/gtpbselcxq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.svipenyu.cn/Article/details/gtihdswrew.html

C#:   static void Main(string[] args)
来源：http://dali.kuanghao11.cn/Article/details/gtwkripbpx.html

[M08] 获取系统与运行时信息
来源：http://dali.gogol.net.cn/Article/details/gtoalszfin.html

Py:   platform.system();  platform.python_version()
来源：http://dali.haohaochexian.top/Article/details/gtvfavwckf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shzxlz.cn/Article/details/gtlcaxywca.html

JS:   process.platform;  process.version
来源：http://dali.shuidangran.top/Article/details/gtwotjpprs.html

TS:   process.platform;  process.version
来源：http://dali.kuanghao11.cn/Article/details/gtawssrsus.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.tian-w.cn/Article/details/gtbwusgnch.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xuanzx.com/Article/details/gttvujauky.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yonumen.top/Article/details/gtxrvztrwz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jyoumei.cn/Article/details/gtthtalxyj.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtpkphqtow.html

N. 数据结构与算法
来源：http://dali.hongshengwenyu.top/Article/details/gtwkvksvce.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtpoexghot.html

[N01] 二分查找（有序数组）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtktaanqnf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtmwmgqetu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.chenlongwang.top/Article/details/gtlxaxuxon.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gtrlyemkaw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cqqwz.cn/Article/details/gtslnbdyfr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ivvv.top/Article/details/gtbsjrtvql.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtywiwogbt.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.dashuyun.cn/Article/details/gtpmfltwhl.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gtezyhwrmu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jqgfzy.top/Article/details/gtitxhjhjq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dashuyun.cn/Article/details/gtqaclktyp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yj20258.top/Article/details/gtwekhhpcm.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.redwolf501.top/Article/details/gtrrczvtii.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.kuanghao11.cn/Article/details/gtnqxylndg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hnxiangtu.top/Article/details/gtcssgprvz.html

Go:   slices.Sort(arr)
来源：http://dali.haohaochexian.top/Article/details/gtkplukzew.html

Ruby: arr.sort
来源：http://dali.yongpay.top/Article/details/gtymuajipg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shanyushiyangtech.top/Article/details/gtjpxuajeh.html

[N03] 快速排序（分治示例）
来源：http://dali.jinyuanbaomall.cn/Article/details/gticnmifhv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jinqigfzy.top/Article/details/gtcdadbsfh.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ydzc1.top/Article/details/gtaqadjnms.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gtrkkrhxsj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenlongwang.top/Article/details/gtcxlesgoy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hammf.cn/Article/details/gtqpaideqp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.wangdashe.top/Article/details/gtdbpzftxa.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shangyingyoupin.top/Article/details/gtzxugcbgr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.9152youxi.cn/Article/details/gthcsyvjps.html

[N04] 斐波那契数列
来源：http://dali.daxiang520.top/Article/details/gtwrosnitn.html


<!-- 参考信息 -->