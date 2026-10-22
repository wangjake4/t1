代发 wailian999

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.feifeiyinyue.top/Article/details/gtxiqedmby.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jyoumei.cn/Article/details/gtdyjbdixo.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xuetiantiany.cn/Article/details/gtbuudyfmu.html

[J06] 计算两时间之差
来源：http://dali.gzhubu.top/Article/details/gtpgblrwrv.html

Py:   (end - start).total_seconds()
来源：http://dali.zhongyouzk.top/Article/details/gtrneczvuk.html

PHP:  $end->diff($start)->days;
来源：http://dali.shuidangran.top/Article/details/gtaaqclozt.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ybcxt.top/Article/details/gtgbwzgkgi.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hnxiangtu.top/Article/details/gtsltfrndq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.svipenyu.cn/Article/details/gtltzvxwcc.html

Go:   end.Sub(start).Hours()
来源：http://dali.yangfankeji.com/Article/details/gtbdosbzqe.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhoulong.xyz/Article/details/gtrpcegxfb.html

C#:   (end - start).TotalSeconds
来源：http://dali.hnxiangtu.top/Article/details/gtyphoaeit.html

[J07] 比较两个日期
来源：http://dali.sysykeji.top/Article/details/gthrtkcdav.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gtmxwircix.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ydzc1.top/Article/details/gthzjsjktu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.tian-w.cn/Article/details/gtrrmpwoyo.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.quarkkingdee.top/Article/details/gthqsyhyty.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.mhx1999.top/Article/details/gtsbnfvbfl.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sufxvd.cn/Article/details/gtsexhkgdv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gtcwfsujib.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.316326.xyz/Article/details/gtfgzxmdiz.html

[J08] 提取年月日与星期
来源：http://dali.mhx1999.top/Article/details/gtywjgmqro.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xylfe.cn/Article/details/gtaqzzoeaz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shzxlz.cn/Article/details/gttyoonunr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.wangshuangyany.cn/Article/details/gtlwnlcjlu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.fzhhl.top/Article/details/gtfaszquqb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhaomingkeji.xyz/Article/details/gteeteolcp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.wangdashe.top/Article/details/gtzczuvgxi.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shuidangran.top/Article/details/gtsxlzellz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinghuilouyu.cn/Article/details/gtagystbqj.html

[J09] 时区处理
来源：http://dali.feifeiyinyue.top/Article/details/gtejfbrloy.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinqigufen.top/Article/details/gtuaryrduz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.daria6918.cn/Article/details/gtbuabvyig.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jlsjyb.cn/Article/details/gtutgehwnq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhengqikj.top/Article/details/gtjihsitol.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nanxinkj.top/Article/details/gtxvalrozp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.snrcjt.cn/Article/details/gtciliprkt.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.pycfn.com/Article/details/gtpjiewokp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ehwqpu.com/Article/details/gtomlxquqc.html

[J10] 取今天 / 本月第一天
来源：http://dali.hammf.cn/Article/details/gtscjfwpgx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ehwqpu.com/Article/details/gtxoyzfutr.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nanxuanxn.top/Article/details/gtakqmqslm.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.iojbl.cn/Article/details/gtuzkcodxt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.fzhhl.top/Article/details/gtfmxbreza.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.svipenyu.cn/Article/details/gturtzkjjo.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hnxiangtu.top/Article/details/gtygbnucus.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yuanzhike.top/Article/details/gtwpxxfvea.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ydzc1.top/Article/details/gtppsilclt.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtrxvycide.html

K. JSON 与序列化
来源：http://dali.jinqigufen.top/Article/details/gtotkfgmwe.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtkjutsmle.html

[K01] 对象转 JSON 字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrfplyjfw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.smart0.xyz/Article/details/gtbwberope.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ybcxt.top/Article/details/gtlbzqmtbg.html

JS:   JSON.stringify(obj)
来源：http://dali.cucudq.cn/Article/details/gtfwdhjsss.html

TS:   JSON.stringify(obj)
来源：http://dali.zycfv.cn/Article/details/gtcbxufdap.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.daria6918.cn/Article/details/gthjkwghzi.html

Go:   json.Marshal(obj)
来源：http://dali.chenlongwang.top/Article/details/gtvlsolxzi.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cashguo.top/Article/details/gtskzudjil.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvuqhsnjq.html

[K02] JSON 字符串转对象
来源：http://dali.redwolf501.top/Article/details/gtazriwyuw.html

Py:   json.loads(s)
来源：http://dali.chenzaomai.com/Article/details/gtypzoidsk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenzaomai.com/Article/details/gtyddjhbbf.html

JS:   JSON.parse(s)
来源：http://dali.smart0.xyz/Article/details/gtcmifljur.html

TS:   JSON.parse(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwakimabk.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jqgfzy.top/Article/details/gtfxudinqt.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sysykeji.top/Article/details/gtxfpipidf.html

Ruby: JSON.parse(s)
来源：http://dali.hnqzz.top/Article/details/gtfenfrlnq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jyoumei.cn/Article/details/gtoreowgau.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xuetiantiany.cn/Article/details/gtojytszbd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.mhx1999.top/Article/details/gtfzimqnxj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.kuanghao11.cn/Article/details/gtmgrfiqjp.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jianghu66.top/Article/details/gtmkmoxzfa.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ppjwa.cn/Article/details/gtnkohbwrk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.daria6918.cn/Article/details/gtbafdutbt.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.mhx1999.top/Article/details/gtruwpiojf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.mhx1999.top/Article/details/gtqrdtgztr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.dianchejie.cn/Article/details/gthgdfnplo.html

[K04] 读取 JSON 文件
来源：http://dali.yueranfly.top/Article/details/gtijlzkddb.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ppjwa.cn/Article/details/gtyihgftbe.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sweek.top/Article/details/gtmxyajnnz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cqqwz.cn/Article/details/gtkvdrgkbf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigfzy.top/Article/details/gtzixhtwko.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.andypj.xyz/Article/details/gtmtsolocz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xuanzx.com/Article/details/gtmhfabzrf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenlongwang.top/Article/details/gthyktphjr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.bjfxy.top/Article/details/gtwdzqlnvx.html

[K05] 深拷贝对象
来源：http://dali.jinqigufen.top/Article/details/gtuqnkicbp.html

Py:   copy.deepcopy(obj)
来源：http://dali.chenlongwang.top/Article/details/gtyrctynkm.html

PHP:  unserialize(serialize($obj));
来源：http://dali.guannengcc.top/Article/details/gtpzblolkf.html

JS:   structuredClone(obj)
来源：http://dali.yangfankeji.com/Article/details/gtszmtcwbl.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtpgeplcvo.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.kuanghao11.cn/Article/details/gtsknvyzya.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yonumen.top/Article/details/gtnkkdzklc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.shuidangran.top/Article/details/gtnstabufo.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gzhubu.top/Article/details/gthuvtteht.html

[K06] 解析 URL 查询串
来源：http://dali.wangshuangyany.cn/Article/details/gtdozsvvwo.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ybcxt.top/Article/details/gtruuhnyou.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zycfv.cn/Article/details/gtwfduchtp.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pengpengdd.cyou/Article/details/gturtoybhq.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuxming.cn/Article/details/gtnvoihdjh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.guowangkeji.top/Article/details/gtsluudwfb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hammf.cn/Article/details/gtuachpsuv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gtfmnxptou.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.fzhhl.top/Article/details/gtpfkycjyh.html

[K07] 进制转换
来源：http://dali.jiagoushi.top/Article/details/gtfbdmzmzl.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gtxhabrrcv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cdnleiting.top/Article/details/gtxqybzrfr.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gtcglybvyu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cheryme.top/Article/details/gtanryajet.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gtsslwcaij.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.vqdsnc.cn/Article/details/gtjiwfrcxe.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hnqzz.top/Article/details/gtxubzopzi.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gtlpgyujfy.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.bjfxy.top/Article/details/gtwmuptqzy.html

Py:   pickle.dumps(obj)
来源：http://dali.cucudq.cn/Article/details/gtaibqensh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yj20258888.top/Article/details/gtwbieflrq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hysaishi.cn/Article/details/gtpjjqebfe.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sysykeji.top/Article/details/gtnxqremwv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xinyue.icu/Article/details/gtufnhgvwo.html

Go:   encoding/gob
来源：http://dali.nanxinkj.top/Article/details/gtnxvkqwcq.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzpbvbfpp.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.sxryk.cn/Article/details/gtfdaxersz.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gthokvnkjb.html

L. 网络请求
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxyccuhkl.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtbujiiwlh.html

[L01] 发送 GET 请求
来源：http://dali.daria6918.cn/Article/details/gtosanrgnx.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ppjwa.cn/Article/details/gtgryojqeq.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.wangshuangyany.cn/Article/details/gtxfulidgf.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gteewdfhjl.html

TS:   await fetch(url)
来源：http://dali.tian-w.cn/Article/details/gtjcnjgdkj.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.nanxuanxn.top/Article/details/gtomyrbznn.html

Go:   resp, err := http.Get(url)
来源：http://dali.pengpengdd.cyou/Article/details/gtlovmmctx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shuidangran.top/Article/details/gtfvyqmwrc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zycfv.cn/Article/details/gtuqzxpmki.html

[L02] 发送 POST JSON
来源：http://dali.andypj.xyz/Article/details/gtqmnnzbnn.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.c1oappe.top/Article/details/gtqcghhupl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yuanzhike.top/Article/details/gtfyjtpjof.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ehwqpu.com/Article/details/gtmuqulpop.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.feifeiyinyue.top/Article/details/gtfahaukku.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ivvv.top/Article/details/gtcadcpckv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.chenzaomai.com/Article/details/gtbzuiuijo.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cqqwz.cn/Article/details/gtwtychfjx.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.guannengcc.top/Article/details/gtbwggmlcl.html

[L03] 设置自定义请求头
来源：http://dali.hnqzz.top/Article/details/gtruaxyctr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cqqwz.cn/Article/details/gtmiregzfo.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.0kj1m.cn/Article/details/gtcizmmqei.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtudbjruwh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.meibo888.top/Article/details/gtdszemyly.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.chenlongwang.top/Article/details/gtycxyyiin.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.nanxuanxn.top/Article/details/gtwnegtwzv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yj202588.top/Article/details/gtlrhwimis.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sufxvd.cn/Article/details/gtbarzneca.html

[L04] 设置超时
来源：http://dali.sxryk.cn/Article/details/gttzuuduzk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.snrcjt.cn/Article/details/gtyxaocthz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.9152youxi.cn/Article/details/gtsrkfhqzx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ivvv.top/Article/details/gthujdfhlz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hysaishi.cn/Article/details/gtgzyvxgdp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinqigufen.top/Article/details/gtuibhmabp.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jyoumei.cn/Article/details/gtqwmmlkoi.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.smart0.xyz/Article/details/gtmccgyuub.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpfgjabbj.html

[L05] 上传文件（multipart）
来源：http://dali.hfpthk.cn/Article/details/gtcqlxgybl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nanxuanxn.top/Article/details/gtklzcdaqx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.pycfn.com/Article/details/gtzrozbhgd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shangyingyoupin.top/Article/details/gtlrrllkhw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj202588.top/Article/details/gtkotamjha.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.snrcjt.cn/Article/details/gtwtdktzmn.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.pengpengdd.cyou/Article/details/gtlbgszxsq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hywenlv.cn/Article/details/gtfgyonvre.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yueranfly.top/Article/details/gtdslvlarw.html

[L06] 解析响应为 JSON
来源：http://dali.jqgufenzy.top/Article/details/gtnwhfdygz.html

Py:   resp.json()
来源：http://dali.yj20258.top/Article/details/gtcuafdbvw.html

PHP:  json_decode($body, true);
来源：http://dali.pycfn.com/Article/details/gtdkprgtra.html

JS:   await resp.json()
来源：http://dali.ybcxt.top/Article/details/gtybdligwr.html

TS:   await resp.json()
来源：http://dali.nanxinkj.top/Article/details/gtpfkfyrel.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.haohaochexian.top/Article/details/gtwdpdxzuf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yvedp.cn/Article/details/gtcdounayq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.kuanghao11.cn/Article/details/gtxbnrhntm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yvedp.cn/Article/details/gtdwgydxob.html

[L07] 处理 HTTP 状态码
来源：http://dali.svipenyu.cn/Article/details/gtwhbfsvtx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.0kj1m.cn/Article/details/gtazjkcvrw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gogol.net.cn/Article/details/gtoiwipvfw.html

JS:   resp.ok;  resp.status
来源：http://dali.yanxiufei.cn/Article/details/gtmyyjcmme.html

TS:   resp.ok;  resp.status
来源：http://dali.chenzaomai.com/Article/details/gteyntipmi.html

Java: resp.statusCode()
来源：http://dali.shzxlz.cn/Article/details/gtycvlgeqi.html

Go:   resp.StatusCode
来源：http://dali.yanxiufei.cn/Article/details/gtvktrhfps.html

Ruby: resp.code.to_i
来源：http://dali.daria6918.cn/Article/details/gtlkultuxs.html

C#:   (int)resp.StatusCode
来源：http://dali.birdmap.top/Article/details/gtugeisvdj.html

[L08] 并发请求多个地址
来源：http://dali.svipenyu.cn/Article/details/gtjkafxqwe.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ppjwa.cn/Article/details/gtagoughuf.html

PHP:  curl_multi_init() 系列
来源：http://dali.ivvv.top/Article/details/gtfvajxibd.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258.top/Article/details/gtqzurzpqf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zycfv.cn/Article/details/gtzzlwmjcd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.316326.xyz/Article/details/gtrelqdyap.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gotoacloud.top/Article/details/gtylvbztvu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zycfv.cn/Article/details/gtnbwyuuko.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.redwolf501.top/Article/details/gtxstyyohk.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtdxfmpysv.html

M. 命令行 / 进程 / 环境
来源：http://dali.yangfankeji.com/Article/details/gtokbpbwpg.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtpgpzcbol.html

[M01] 读取命令行参数
来源：http://dali.shzxlz.cn/Article/details/gtboczeawp.html

Py:   sys.argv[1:]
来源：http://dali.cqqwz.cn/Article/details/gtzdfhjvpc.html

PHP:  $argv;  $argc;
来源：http://dali.cashguo.top/Article/details/gtmsxsbptn.html

JS:   process.argv.slice(2)
来源：http://dali.jianghu66.top/Article/details/gtgsmsuovm.html

TS:   process.argv.slice(2)
来源：http://dali.nwbrower.top/Article/details/gteeiveqym.html

Java: args 数组（main 方法参数）
来源：http://dali.tian-w.cn/Article/details/gtvfrjanqe.html

Go:   os.Args[1:]
来源：http://dali.hnqzz.top/Article/details/gtrhmgppgs.html

Ruby: ARGV
来源：http://dali.fengsongda.top/Article/details/gtrvpjnogq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shzxlz.cn/Article/details/gtnpiqqqqe.html

[M02] 读取环境变量
来源：http://dali.ybcxt.top/Article/details/gtgzxsefsu.html

Py:   os.environ.get("HOME")
来源：http://dali.birdmap.top/Article/details/gtjhvaopqr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.feifeiyinyue.top/Article/details/gtxnfnpunw.html

JS:   process.env.HOME
来源：http://dali.cqqwz.cn/Article/details/gtezevxzcy.html

TS:   process.env.HOME
来源：http://dali.cdnleiting.top/Article/details/gtzytgrilq.html

Java: System.getenv("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gtrfnyqfhk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gogol.net.cn/Article/details/gtgwqccrur.html

Ruby: ENV["HOME"]
来源：http://dali.daria6918.cn/Article/details/gtravttapp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.c1oappe.top/Article/details/gtchizaxiu.html

[M03] 执行外部命令
来源：http://dali.yvedp.cn/Article/details/gttewntpat.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tian-w.cn/Article/details/gtgmlqmzqm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.c1oappe.top/Article/details/gtcmnylejm.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxinkj.top/Article/details/gtrexutpug.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ydzc1.top/Article/details/gtqtnegiku.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.chenzaomai.com/Article/details/gtsjkzmhmv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinqigufen.top/Article/details/gtqktzorbl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.quarkkingdee.top/Article/details/gtpnpvyaae.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yongpay.top/Article/details/gtwcetosdy.html

[M04] 获取当前工作目录
来源：http://dali.jinqigufen.top/Article/details/gtczdqvlgd.html

Py:   os.getcwd()
来源：http://dali.jlsjyb.cn/Article/details/gteptqpuja.html

PHP:  getcwd();
来源：http://dali.yongpay.top/Article/details/gtztboxcdr.html

JS:   process.cwd()
来源：http://dali.chenlongwang.top/Article/details/gtqydeajcx.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gtvaoxlkuk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jiagoushi.top/Article/details/gtdcigsltj.html

Go:   os.Getwd()
来源：http://dali.hfpthk.cn/Article/details/gtrmpdceso.html

Ruby: Dir.pwd
来源：http://dali.zhongyouzk.top/Article/details/gtqxkrvmfr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.aizwys.cn/Article/details/gtccigglwi.html

[M05] 设置退出码
来源：http://dali.andypj.xyz/Article/details/gtcjxbydjn.html

Py:   sys.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gtmpvlwtei.html

PHP:  exit(1);
来源：http://dali.chenjidiqi.icu/Article/details/gtaknhhrcz.html

JS:   process.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gtqeaaljzn.html

TS:   process.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtgetjjycx.html

Java: System.exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtqcjfnqgz.html

Go:   os.Exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtexddjvdy.html

Ruby: exit 1
来源：http://dali.jinqigfzy.top/Article/details/gtddxigkpj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ppjwa.cn/Article/details/gtikhztnos.html

[M06] 向标准错误输出
来源：http://dali.guowangkeji.top/Article/details/gtubafbamj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shzxlz.cn/Article/details/gtktthxuob.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yanxiufei.cn/Article/details/gtpkbusufp.html

JS:   console.error("err")
来源：http://dali.0kj1m.cn/Article/details/gtxiwuutgr.html

TS:   console.error("err")
来源：http://dali.redwolf501.top/Article/details/gtycxbtkmg.html

Java: System.err.println("err")
来源：http://dali.ydzc1.top/Article/details/gtggzykoxj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gogol.net.cn/Article/details/gtrtpvncqn.html

Ruby: warn "err"
来源：http://dali.chenjidiqi.icu/Article/details/gtyfggnrzv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jqgufenzy.top/Article/details/gtxsvehvos.html

[M07] 判断是否为主入口
来源：http://dali.yangfankeji.com/Article/details/gtxfmeyyge.html

Py:   if __name__ == "__main__":
来源：http://dali.daxiang520.top/Article/details/gthitemlff.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.svipenyu.cn/Article/details/gtiucnntoi.html

JS:   require.main === module
来源：http://dali.yanxiufei.cn/Article/details/gtugeqvfvy.html

TS:   require.main === module
来源：http://dali.hfpthk.cn/Article/details/gtvdfkakhv.html

Java: public static void main(String[] args)
来源：http://dali.ydzc1.top/Article/details/gtctebudpx.html

Go:   func main()
来源：http://dali.hnxiangtu.top/Article/details/gttoaxwrnp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.snrcjt.cn/Article/details/gttfwgfilx.html

C#:   static void Main(string[] args)
来源：http://dali.wangdashe.top/Article/details/gtllgbojsj.html

[M08] 获取系统与运行时信息
来源：http://dali.nanxuanxn.top/Article/details/gtthdwhgca.html

Py:   platform.system();  platform.python_version()
来源：http://dali.chenjidiqi.icu/Article/details/gthgdgziyw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hongshengwenyu.top/Article/details/gtnjnxjqkb.html

JS:   process.platform;  process.version
来源：http://dali.wangdashe.top/Article/details/gtkwclwuie.html

TS:   process.platform;  process.version
来源：http://dali.316326.xyz/Article/details/gtahamvvsj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.svipenyu.cn/Article/details/gttqnuolxx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cqqwz.cn/Article/details/gtjwvhukws.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.nanxinkj.top/Article/details/gtozsoteeq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xuanzx.com/Article/details/gtopjluhcj.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtiezortww.html

N. 数据结构与算法
来源：http://dali.jinghuilouyu.cn/Article/details/gtakvpksgl.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtljrdjdmo.html

[N01] 二分查找（有序数组）
来源：http://dali.ppjwa.cn/Article/details/gtromihpcx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtgjobznkl.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.aibaodan.cn/Article/details/gtvtnanwla.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daria6918.cn/Article/details/gtzfpbtkdc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daxiang520.top/Article/details/gtspucizgb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gthovuqlea.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtqnwjejlr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.snrcjt.cn/Article/details/gthzigatnf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gtcbkqfrps.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhongyouzk.top/Article/details/gtkxanypfs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxinkj.top/Article/details/gtgadnssdg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gtzsdwlmwu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxwuamabt.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sxryk.cn/Article/details/gtqckgjtnw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jyoumei.cn/Article/details/gtyzmulqcz.html

Go:   slices.Sort(arr)
来源：http://dali.yvedp.cn/Article/details/gtotqfgpsg.html

Ruby: arr.sort
来源：http://dali.zdqjudy.top/Article/details/gtlcredggz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.redwolf501.top/Article/details/gtmzfyrpct.html

[N03] 快速排序（分治示例）
来源：http://dali.wangshuangyany.cn/Article/details/gtyngffovi.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.birdmap.top/Article/details/gtkwbswzxi.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hnxiangtu.top/Article/details/gttpwjhwwe.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuanzx.com/Article/details/gtffcowcwk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.haohaochexian.top/Article/details/gtrvrhpjji.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cqqwz.cn/Article/details/gtadowglnf.html


<!-- 参考信息 -->