代发 wailian999

Py:   (end - start).total_seconds()
来源：http://dali.zhiwuduotai.top/Article/details/gtaffhjzlt.html

PHP:  $end->diff($start)->days;
来源：http://dali.vqdsnc.cn/Article/details/gtxgdjdwct.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xylfe.cn/Article/details/gtnulkujsg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.dashuyun.cn/Article/details/gtszozsbft.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.tianlin.xyz/Article/details/gtvvscplew.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinqigfzy.top/Article/details/gtmpypedro.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shangyingyoupin.top/Article/details/gtxjakwsaa.html

C#:   (end - start).TotalSeconds
来源：http://dali.shangyingyoupin.top/Article/details/gtlxxvnkhp.html

[J07] 比较两个日期
来源：http://dali.jyoumei.cn/Article/details/gtzcztpmnq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ybcxt.top/Article/details/gtlxpbiuhi.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yonumen.top/Article/details/gtpbylhash.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yj202588.top/Article/details/gtbvbhpupm.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpsxwkcpo.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.0kj1m.cn/Article/details/gtkixrulnw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttgzeagzf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkjuzczmw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.iojbl.cn/Article/details/gthxzkibur.html

[J08] 提取年月日与星期
来源：http://dali.fengsongda.top/Article/details/gtvmpwzhbt.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.snrcjt.cn/Article/details/gtkavwnqru.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xuanzx.com/Article/details/gtxuqwsjto.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.quarkkingdee.top/Article/details/gtrqrmqyra.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtevlblfwy.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.guannengcc.top/Article/details/gtsvgectsg.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xuetiantiany.cn/Article/details/gtisutvmwn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yj202588.top/Article/details/gtkzrbwvkd.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.bjfxy.top/Article/details/gtqihajbyh.html

[J09] 时区处理
来源：http://dali.jqgufenzy.top/Article/details/gtxtyttkus.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hysaishi.cn/Article/details/gtamjawweo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sysykeji.top/Article/details/gtodzzgjnz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.316326.xyz/Article/details/gtgzcfpxip.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sxryk.cn/Article/details/gtxwklpdms.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jqgufenzy.top/Article/details/gtjrtvnnji.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.wangdashe.top/Article/details/gtjnkxrmjv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.feifeiyinyue.top/Article/details/gtwtqsdfed.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shuidangran.top/Article/details/gtkductqtp.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhengqikj.top/Article/details/gtvtorozsv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.kuanghao11.cn/Article/details/gtezdlrwyf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ehwqpu.com/Article/details/gtjdlnxynj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.havefunace.top/Article/details/gtbisvergh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.iojbl.cn/Article/details/gtexhzuqmx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yueranfly.top/Article/details/gtlljlerhx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.vqdsnc.cn/Article/details/gtgpmvzoaj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuygrottc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.tian-w.cn/Article/details/gtavqiucjy.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtnlnqlzur.html

K. JSON 与序列化
来源：http://dali.zycfv.cn/Article/details/gtsxzvaryw.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gthvtmqbfm.html

[K01] 对象转 JSON 字符串
来源：http://dali.haohaochexian.top/Article/details/gtnsdzjtoo.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.nanxuanxn.top/Article/details/gtocacfjqk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdntqyrsf.html

JS:   JSON.stringify(obj)
来源：http://dali.gotoacloud.top/Article/details/gtvwkykdbt.html

TS:   JSON.stringify(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtluwqsnjc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xinyue.icu/Article/details/gtbesnbvbf.html

Go:   json.Marshal(obj)
来源：http://dali.zhixingplan.top/Article/details/gtvpdlabzl.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.nwbrower.top/Article/details/gtoeqzrzee.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.aizwys.cn/Article/details/gttiockdzi.html

[K02] JSON 字符串转对象
来源：http://dali.tianlin.xyz/Article/details/gtyjkojdum.html

Py:   json.loads(s)
来源：http://dali.ydzc1.top/Article/details/gtnnaalpkc.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ehwqpu.com/Article/details/gtrbuynscy.html

JS:   JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gtvvpwwtzj.html

TS:   JSON.parse(s)
来源：http://dali.ydzc1.top/Article/details/gtomwbaiqm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.pycfn.com/Article/details/gtmiuhziyp.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cdnleiting.top/Article/details/gtcxnskbzd.html

Ruby: JSON.parse(s)
来源：http://dali.nanxuanxn.top/Article/details/gtciricftn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.chenzaomai.com/Article/details/gttybkqkqd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yangfankeji.com/Article/details/gtyqdzmrvu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shuidangran.top/Article/details/gtnzcvyrni.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhixingplan.top/Article/details/gtwxrwpcxx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.fzhhl.top/Article/details/gtgtsriryy.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sweek.top/Article/details/gtljebprqd.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.daxiang520.top/Article/details/gtptwjcaay.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jianghu66.top/Article/details/gtacvclhpx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.dashuyun.cn/Article/details/gttdzutlep.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cheryme.top/Article/details/gtjytmtlve.html

[K04] 读取 JSON 文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvdbfplto.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yonumen.top/Article/details/gtavvuykmc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.0kj1m.cn/Article/details/gtcqdqegsd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cqqwz.cn/Article/details/gtrakmjqqa.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuxuasemk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.dianchejie.cn/Article/details/gtrpmjvobo.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinqigufen.top/Article/details/gtezsdwddt.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shzxlz.cn/Article/details/gtflxghuvz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xylfe.cn/Article/details/gtagbrnmvu.html

[K05] 深拷贝对象
来源：http://dali.feifeiyinyue.top/Article/details/gtbirhonyq.html

Py:   copy.deepcopy(obj)
来源：http://dali.0kj1m.cn/Article/details/gtzmrujeez.html

PHP:  unserialize(serialize($obj));
来源：http://dali.iojbl.cn/Article/details/gtlhwmuchn.html

JS:   structuredClone(obj)
来源：http://dali.dianchejie.cn/Article/details/gtgrzteetf.html

TS:   structuredClone(obj)
来源：http://dali.jiagoushi.top/Article/details/gtcsmooddp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xziqi.cn/Article/details/gtysdmsflh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ehwqpu.com/Article/details/gtzqeiivre.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.tianlin.xyz/Article/details/gtvbwnsinr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sufxvd.cn/Article/details/gtnjkxontx.html

[K06] 解析 URL 查询串
来源：http://dali.ybcxt.top/Article/details/gtulrfwafw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.wangdashe.top/Article/details/gtoxcyclfx.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yongpay.top/Article/details/gtfnzavqkt.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.havefunace.top/Article/details/gtclkehsjg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258888.top/Article/details/gtbotgwaou.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xylfe.cn/Article/details/gtaloprnkz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cheryme.top/Article/details/gtaeqdyofn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.pycfn.com/Article/details/gtoeojgzmc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gttbfbvmpl.html

[K07] 进制转换
来源：http://dali.havefunace.top/Article/details/gtlxbvkbha.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.birdmap.top/Article/details/gtwvjumgju.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.fengsongda.top/Article/details/gtiuwzdaoo.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtjrhcyvsq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gthpkmrqnj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gtnicwuuju.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sysykeji.top/Article/details/gtipbpelkx.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yj202588.top/Article/details/gtjrzuhnzm.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj202588.top/Article/details/gtmydqyred.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jqgufenzy.top/Article/details/gtawshdelc.html

Py:   pickle.dumps(obj)
来源：http://dali.svipenyu.cn/Article/details/gtetycyrdx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cucudq.cn/Article/details/gtvqbirfmz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258.top/Article/details/gtvscbymgo.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jqgfzy.top/Article/details/gtpsmryxwi.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj202588.top/Article/details/gtwklewpys.html

Go:   encoding/gob
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqhiwjben.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtlfgkqvhy.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jiagoushi.top/Article/details/gtuiwmiyjy.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtaywujpgb.html

L. 网络请求
来源：http://dali.dianchejie.cn/Article/details/gtnwxfvsbp.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtaxgvzlcp.html

[L01] 发送 GET 请求
来源：http://dali.hywenlv.cn/Article/details/gtkipzmfoh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinghuilouyu.cn/Article/details/gtxrpdqryz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yuanzhike.top/Article/details/gtqwykflto.html

JS:   await fetch(url)
来源：http://dali.wangshuangyany.cn/Article/details/gtmfsrrovc.html

TS:   await fetch(url)
来源：http://dali.jinqigfzy.top/Article/details/gtvxblntve.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.mhx1999.top/Article/details/gthcpzrmmo.html

Go:   resp, err := http.Get(url)
来源：http://dali.xuanzx.com/Article/details/gtjxugaswl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gogol.net.cn/Article/details/gtdskbjtls.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yueranfly.top/Article/details/gtjdzzrvfl.html

[L02] 发送 POST JSON
来源：http://dali.mhx1999.top/Article/details/gtflhbgrze.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hfpthk.cn/Article/details/gtxitvgppk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.fzhhl.top/Article/details/gtvplftgwv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jlsjyb.cn/Article/details/gtppfgaqko.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.haohaochexian.top/Article/details/gtghgyhlzp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jqgfzy.top/Article/details/gtyqevhyot.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.daria6918.cn/Article/details/gtxbawdajs.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.kuanghao11.cn/Article/details/gtcilanflz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yvedp.cn/Article/details/gtczystxdp.html

[L03] 设置自定义请求头
来源：http://dali.nwbrower.top/Article/details/gtoctmpwpb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gzhubu.top/Article/details/gtmgbwgkvl.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.pycfn.com/Article/details/gtlljsybch.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhoulong.xyz/Article/details/gtqweqatgt.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtardljuah.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sxryk.cn/Article/details/gtouskoqup.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shangyingyoupin.top/Article/details/gtkkfwrdcu.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.redwolf501.top/Article/details/gtqhuxuxdz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.meibo888.top/Article/details/gtayebqyrd.html

[L04] 设置超时
来源：http://dali.hnxiangtu.top/Article/details/gthrigarev.html

Py:   requests.get(url, timeout=5)
来源：http://dali.meibo888.top/Article/details/gtrtigxfzn.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.0kj1m.cn/Article/details/gtqlmjarxn.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xziqi.cn/Article/details/gtwqnsjowy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigufen.top/Article/details/gtowtixksu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cdnleiting.top/Article/details/gtpvriktyd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.guannengcc.top/Article/details/gtwlotqbum.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yj20258888.top/Article/details/gtquovoyhq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yuxming.cn/Article/details/gtytzfuqhi.html

[L05] 上传文件（multipart）
来源：http://dali.vqdsnc.cn/Article/details/gtajbexwjo.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jqgufenzy.top/Article/details/gtjjtczbva.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.nwbrower.top/Article/details/gtttlkmwte.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gaohongyu789.top/Article/details/gtpeoyscmg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cucudq.cn/Article/details/gtqekwtsir.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jiagoushi.top/Article/details/gtiflihkjv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jiagoushi.top/Article/details/gtydiybvob.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.tanke756.top/Article/details/gtzdoeavjf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ehwqpu.com/Article/details/gthwdmzpoz.html

[L06] 解析响应为 JSON
来源：http://dali.havefunace.top/Article/details/gtpjtrqlub.html

Py:   resp.json()
来源：http://dali.jiagoushi.top/Article/details/gtbfnszuzn.html

PHP:  json_decode($body, true);
来源：http://dali.mhx1999.top/Article/details/gtkhlcucpr.html

JS:   await resp.json()
来源：http://dali.c1oappe.top/Article/details/gtwdpowexw.html

TS:   await resp.json()
来源：http://dali.hnxiangtu.top/Article/details/gtlhxyalrq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gzhubu.top/Article/details/gtfkgamrvb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xuetiantiany.cn/Article/details/gthlvlsvxo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yueranfly.top/Article/details/gtcikpktnh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xuanzx.com/Article/details/gtluirqgef.html

[L07] 处理 HTTP 状态码
来源：http://dali.gaohongyu789.top/Article/details/gtowixffif.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yueranfly.top/Article/details/gtsobhckko.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jqgufenzy.top/Article/details/gtprltdnew.html

JS:   resp.ok;  resp.status
来源：http://dali.xuanzx.com/Article/details/gtxrzxvbqd.html

TS:   resp.ok;  resp.status
来源：http://dali.haohaochexian.top/Article/details/gtvyldhaqe.html

Java: resp.statusCode()
来源：http://dali.zycfv.cn/Article/details/gtuvqrdijr.html

Go:   resp.StatusCode
来源：http://dali.iojbl.cn/Article/details/gtaodtipne.html

Ruby: resp.code.to_i
来源：http://dali.xuetiantiany.cn/Article/details/gtydumaeop.html

C#:   (int)resp.StatusCode
来源：http://dali.hongshengwenyu.top/Article/details/gtnxihmiia.html

[L08] 并发请求多个地址
来源：http://dali.hywenlv.cn/Article/details/gtziraiylj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yangfankeji.com/Article/details/gtvnnwybpb.html

PHP:  curl_multi_init() 系列
来源：http://dali.gaohongyu789.top/Article/details/gtnvapvuaz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cucudq.cn/Article/details/gtcbmtenom.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258.top/Article/details/gtrxomhuks.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinqigufen.top/Article/details/gtaykpbogl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.dashuyun.cn/Article/details/gtmuuuvhur.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhengqikj.top/Article/details/gtzswzpule.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xziqi.cn/Article/details/gtevgkxyzq.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtfuqbnpoe.html

M. 命令行 / 进程 / 环境
来源：http://dali.yonumen.top/Article/details/gtddphpjvx.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtgystnyln.html

[M01] 读取命令行参数
来源：http://dali.zycfv.cn/Article/details/gtqxhwrhdg.html

Py:   sys.argv[1:]
来源：http://dali.aibaodan.cn/Article/details/gtmgkpqujg.html

PHP:  $argv;  $argc;
来源：http://dali.mhx1999.top/Article/details/gtgdqbkvas.html

JS:   process.argv.slice(2)
来源：http://dali.sufxvd.cn/Article/details/gtgdztahqt.html

TS:   process.argv.slice(2)
来源：http://dali.zhengqikj.top/Article/details/gtlgrefdtm.html

Java: args 数组（main 方法参数）
来源：http://dali.jinqigufen.top/Article/details/gtdwsmuilw.html

Go:   os.Args[1:]
来源：http://dali.hammf.cn/Article/details/gtnpgdbfst.html

Ruby: ARGV
来源：http://dali.tianlin.xyz/Article/details/gtbdhbwsaw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gogol.net.cn/Article/details/gtissfkqkh.html

[M02] 读取环境变量
来源：http://dali.yvedp.cn/Article/details/gtlamsqiry.html

Py:   os.environ.get("HOME")
来源：http://dali.yuxming.cn/Article/details/gtziwjmuwo.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinghuilouyu.cn/Article/details/gtbjrznoqo.html

JS:   process.env.HOME
来源：http://dali.cqqwz.cn/Article/details/gtebbcrchk.html

TS:   process.env.HOME
来源：http://dali.jqgfzy.top/Article/details/gtjczlvjhw.html

Java: System.getenv("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwnkqtxyj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jqgfzy.top/Article/details/gtolbuzgdk.html

Ruby: ENV["HOME"]
来源：http://dali.smart0.xyz/Article/details/gtjbxakwpp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhengqikj.top/Article/details/gtwlhptflr.html

[M03] 执行外部命令
来源：http://dali.9152youxi.cn/Article/details/gthjqgtvdd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.redwolf501.top/Article/details/gtewxpkazz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj20258.top/Article/details/gtgpaorhui.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.quarkkingdee.top/Article/details/gtdicflbgk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jyoumei.cn/Article/details/gtmjylezvi.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yonumen.top/Article/details/gtoqbifdrb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sysykeji.top/Article/details/gtsbkpmhtz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.guannengcc.top/Article/details/gtiqwcbxoj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinqigfzy.top/Article/details/gtzppbblws.html

[M04] 获取当前工作目录
来源：http://dali.smart0.xyz/Article/details/gttmdmhvhz.html

Py:   os.getcwd()
来源：http://dali.gaohongyu789.top/Article/details/gtsyyuzabi.html

PHP:  getcwd();
来源：http://dali.gogol.net.cn/Article/details/gtuvswrace.html

JS:   process.cwd()
来源：http://dali.9152youxi.cn/Article/details/gtucytatvd.html

TS:   process.cwd()
来源：http://dali.nanxinkj.top/Article/details/gtmtfmkfwz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yonumen.top/Article/details/gtagdchhqh.html

Go:   os.Getwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtopdzgmst.html

Ruby: Dir.pwd
来源：http://dali.zhixingplan.top/Article/details/gtsswzcymw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xziqi.cn/Article/details/gtgakqllxv.html

[M05] 设置退出码
来源：http://dali.tian-w.cn/Article/details/gtsjmnxocl.html

Py:   sys.exit(1)
来源：http://dali.yonumen.top/Article/details/gtetlbifel.html

PHP:  exit(1);
来源：http://dali.sxryk.cn/Article/details/gthiblxdzv.html

JS:   process.exit(1)
来源：http://dali.meibo888.top/Article/details/gtqsbegzii.html

TS:   process.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gtvqjvvdwi.html

Java: System.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gtspserkfa.html

Go:   os.Exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtaaycushx.html

Ruby: exit 1
来源：http://dali.jiagoushi.top/Article/details/gtdsehgwsq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xziqi.cn/Article/details/gtdqybutbp.html

[M06] 向标准错误输出
来源：http://dali.quarkkingdee.top/Article/details/gtjxrnmhtm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shzxlz.cn/Article/details/gtrkcxithh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.0kj1m.cn/Article/details/gtssgoidui.html

JS:   console.error("err")
来源：http://dali.gaohongyu789.top/Article/details/gtxovsylko.html

TS:   console.error("err")
来源：http://dali.shzxlz.cn/Article/details/gtpyfrkpic.html

Java: System.err.println("err")
来源：http://dali.xinyue.icu/Article/details/gtorlvvyla.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hysaishi.cn/Article/details/gtexwittkx.html

Ruby: warn "err"
来源：http://dali.hysaishi.cn/Article/details/gtvvblcqkm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhengqikj.top/Article/details/gtxjjhystb.html

[M07] 判断是否为主入口
来源：http://dali.fengsongda.top/Article/details/gtscajbksy.html

Py:   if __name__ == "__main__":
来源：http://dali.jqgfzy.top/Article/details/gtxbgcoljs.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gogol.net.cn/Article/details/gttkcvnpzz.html

JS:   require.main === module
来源：http://dali.hywenlv.cn/Article/details/gtsspdshhx.html

TS:   require.main === module
来源：http://dali.jinghuilouyu.cn/Article/details/gttntkjdgq.html

Java: public static void main(String[] args)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlrnwhzkr.html

Go:   func main()
来源：http://dali.chenjidiqi.icu/Article/details/gtavzdafat.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.dianchejie.cn/Article/details/gtbarzldiy.html

C#:   static void Main(string[] args)
来源：http://dali.dianchejie.cn/Article/details/gtqrpeqhyb.html

[M08] 获取系统与运行时信息
来源：http://dali.jinqigufen.top/Article/details/gtkixqjdln.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ehwqpu.com/Article/details/gtpdlbuwzh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.tanke756.top/Article/details/gtphawvkgj.html

JS:   process.platform;  process.version
来源：http://dali.tianlin.xyz/Article/details/gtithyoorc.html

TS:   process.platform;  process.version
来源：http://dali.jinyuanbaomall.cn/Article/details/gtigbbudxa.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yueranfly.top/Article/details/gtstxnixkt.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.tianlin.xyz/Article/details/gtaiqidxie.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xinyue.icu/Article/details/gtytyyqsgq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jlsjyb.cn/Article/details/gtbpwkxxfr.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtkevuzdne.html

N. 数据结构与算法
来源：http://dali.xziqi.cn/Article/details/gtiftdiflv.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtgysxctus.html

[N01] 二分查找（有序数组）
来源：http://dali.tanke756.top/Article/details/gtnqfoaxdk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtbabrcaut.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.daxiang520.top/Article/details/gtqnkfrgxb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cqqwz.cn/Article/details/gtfrnnyxmj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.meibo888.top/Article/details/gtdlkgsvdo.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gtfbznipox.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtaeppkbyy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yueranfly.top/Article/details/gtnhuestmb.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtiopvwexj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.snrcjt.cn/Article/details/gtmdvyplnc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxuanxn.top/Article/details/gtkjiexqmu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.feifeiyinyue.top/Article/details/gtjjzofesg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jiagoushi.top/Article/details/gtmuiyuweu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangdashe.top/Article/details/gtihuvdulr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jiagoushi.top/Article/details/gtgpfbladf.html

Go:   slices.Sort(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtafsxnebz.html

Ruby: arr.sort
来源：http://dali.yanxiufei.cn/Article/details/gtzuubayfw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpsdprlwn.html

[N03] 快速排序（分治示例）
来源：http://dali.guowangkeji.top/Article/details/gtsovoocik.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.meibo888.top/Article/details/gtozupewjm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.sweek.top/Article/details/gtfcsglmsi.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenjidiqi.icu/Article/details/gtuhtcigxk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigfzy.top/Article/details/gtwjmhbdub.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sweek.top/Article/details/gtrtmwstbf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cdnleiting.top/Article/details/gtxhuyjbum.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.0kj1m.cn/Article/details/gtpnefbjmi.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.aibaodan.cn/Article/details/gtdkchdacb.html

[N04] 斐波那契数列
来源：http://dali.fzhhl.top/Article/details/gtobbejyln.html


<!-- 参考信息 -->