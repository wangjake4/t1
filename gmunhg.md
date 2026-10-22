代发 wailian999

Py:   (end - start).total_seconds()
来源：http://dali.0kj1m.cn/Article/details/gtrsmwwaoi.html

PHP:  $end->diff($start)->days;
来源：http://dali.316326.xyz/Article/details/gtuvfbddry.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cqqwz.cn/Article/details/gtpmharvgj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hongshengwenyu.top/Article/details/gtvvnukmmv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zycfv.cn/Article/details/gtlrpbjska.html

Go:   end.Sub(start).Hours()
来源：http://dali.zdqjudy.top/Article/details/gtsxqmhcnu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.aizwys.cn/Article/details/gtctarjmjz.html

C#:   (end - start).TotalSeconds
来源：http://dali.cheryme.top/Article/details/gtbzagsgeh.html

[J07] 比较两个日期
来源：http://dali.haohaochexian.top/Article/details/gtegzzuonz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tian-w.cn/Article/details/gtnidkiqrl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xuetiantiany.cn/Article/details/gtnhnkoqta.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqhdwnucc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.guowangkeji.top/Article/details/gtvrnmstmq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sweek.top/Article/details/gtncwrfdcv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yonumen.top/Article/details/gtyhkctnrc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jinqigufen.top/Article/details/gtgmiasjsp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.aizwys.cn/Article/details/gtafsgckvg.html

[J08] 提取年月日与星期
来源：http://dali.jqgfzy.top/Article/details/gtoescasmb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gaohongyu789.top/Article/details/gtutgzamgw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhijiandao.cn/Article/details/gtoxbbxzee.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yangfankeji.com/Article/details/gtyvekdiec.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinqigfzy.top/Article/details/gtojsagblv.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.fengsongda.top/Article/details/gttzkawjrb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.vqdsnc.cn/Article/details/gtcvyeekqz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.aibaodan.cn/Article/details/gtbxhikdew.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.fengsongda.top/Article/details/gtpxanzzaz.html

[J09] 时区处理
来源：http://dali.cheryme.top/Article/details/gtntxanipc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.fengsongda.top/Article/details/gtcvrvfoyo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.dashuyun.cn/Article/details/gtxpyrdjfd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.smart0.xyz/Article/details/gtahknilgu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuetiantiany.cn/Article/details/gtibocmrjj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nanxuanxn.top/Article/details/gttqiwftrp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.nwbrower.top/Article/details/gtiwoljaov.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.mhx1999.top/Article/details/gtjnrrprla.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrfrpruro.html

[J10] 取今天 / 本月第一天
来源：http://dali.gotoacloud.top/Article/details/gtfuuqbeoj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.iojbl.cn/Article/details/gtmtrqncrv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.daxiang520.top/Article/details/gtdyaqhvtz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shuidangran.top/Article/details/gtxnfwurin.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhengqikj.top/Article/details/gtwfhtskgz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.c1oappe.top/Article/details/gtluumiwug.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ydzc1.top/Article/details/gtihoggvcj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shuidangran.top/Article/details/gtbudfzwhz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xuanzx.com/Article/details/gtwqduypks.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtbwkptmel.html

K. JSON 与序列化
来源：http://dali.nanxuanxn.top/Article/details/gtqtvilmbu.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtxdtkvtkq.html

[K01] 对象转 JSON 字符串
来源：http://dali.yueranfly.top/Article/details/gtskfoggtl.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsgkkftnd.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.wangshuangyany.cn/Article/details/gtkeyczges.html

JS:   JSON.stringify(obj)
来源：http://dali.daxiang520.top/Article/details/gthjgwbxge.html

TS:   JSON.stringify(obj)
来源：http://dali.redwolf501.top/Article/details/gtpnyygduv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shangyingyoupin.top/Article/details/gtxiwotdgp.html

Go:   json.Marshal(obj)
来源：http://dali.jqgfzy.top/Article/details/gtlqvzxeiw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.vqdsnc.cn/Article/details/gttpsanuby.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.haohaochexian.top/Article/details/gtfadrjabo.html

[K02] JSON 字符串转对象
来源：http://dali.daxiang520.top/Article/details/gtazfixiyk.html

Py:   json.loads(s)
来源：http://dali.snrcjt.cn/Article/details/gtufczcsxk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hnqzz.top/Article/details/gtygkmqefk.html

JS:   JSON.parse(s)
来源：http://dali.zdqjudy.top/Article/details/gtmuhagdrx.html

TS:   JSON.parse(s)
来源：http://dali.xuanzx.com/Article/details/gtjtvukjtd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gttiiuzbdy.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jiagoushi.top/Article/details/gtzsxwxvre.html

Ruby: JSON.parse(s)
来源：http://dali.yj202588.top/Article/details/gtwoiappsw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjmpqvktu.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shangyingyoupin.top/Article/details/gtyzrgrmnj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.vqdsnc.cn/Article/details/gtleltffxq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shuidangran.top/Article/details/gtxkjvxoxq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzetnicbh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.birdmap.top/Article/details/gtgqufwosw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jianghu66.top/Article/details/gtanyihpps.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yuxming.cn/Article/details/gtwvrifcrb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gotoacloud.top/Article/details/gtitvzxrhr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jqgfzy.top/Article/details/gtqxemvxmf.html

[K04] 读取 JSON 文件
来源：http://dali.xinyue.icu/Article/details/gtaqmezwzg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hongshengwenyu.top/Article/details/gtmkfescnz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xziqi.cn/Article/details/gtdetrfghm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hywenlv.cn/Article/details/gtxdvzyvia.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xinyue.icu/Article/details/gtiyslpjbq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.guowangkeji.top/Article/details/gtxzkmeibi.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.wangshuangyany.cn/Article/details/gtlumevpfb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.daria6918.cn/Article/details/gtxzfmouxh.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.birdmap.top/Article/details/gtqnxxwoqz.html

[K05] 深拷贝对象
来源：http://dali.zhongyouzk.top/Article/details/gthihtpkvj.html

Py:   copy.deepcopy(obj)
来源：http://dali.cheryme.top/Article/details/gtwpxegxws.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hfpthk.cn/Article/details/gtzbyeevos.html

JS:   structuredClone(obj)
来源：http://dali.yangfankeji.com/Article/details/gtqpjwwdwb.html

TS:   structuredClone(obj)
来源：http://dali.9152youxi.cn/Article/details/gtsrytaosv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hfpthk.cn/Article/details/gtuzwnrwtq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.snrcjt.cn/Article/details/gteivsfnxq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cdnleiting.top/Article/details/gttgfzcqqq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.pycfn.com/Article/details/gtxmwbgljw.html

[K06] 解析 URL 查询串
来源：http://dali.c1oappe.top/Article/details/gtpdiakkwv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhoulong.xyz/Article/details/gtquqgyzkf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.wangdashe.top/Article/details/gtgpaxjhhi.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.meibo888.top/Article/details/gtqniaymlb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuanzx.com/Article/details/gthjtgslyj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.pycfn.com/Article/details/gthytyuwxi.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenjidiqi.icu/Article/details/gtebidrqfi.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gttapuejyn.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shangyingyoupin.top/Article/details/gtxohecwsz.html

[K07] 进制转换
来源：http://dali.ehwqpu.com/Article/details/gtiaspcagi.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gtehqwbdgd.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.0kj1m.cn/Article/details/gtfwguhkjg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlyaveoji.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ivvv.top/Article/details/gtfookfabu.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gtnjqwbppw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cashguo.top/Article/details/gtflubrdro.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.guowangkeji.top/Article/details/gtisxcpttx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gtexhlcbyu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sysykeji.top/Article/details/gthgbvzfqr.html

Py:   pickle.dumps(obj)
来源：http://dali.zhixingplan.top/Article/details/gtqwgtpyca.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.bjfxy.top/Article/details/gtieubrrwn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xylfe.cn/Article/details/gtxmcnqmag.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xuanzx.com/Article/details/gtgevjfwez.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.dashuyun.cn/Article/details/gtrqrgngdu.html

Go:   encoding/gob
来源：http://dali.birdmap.top/Article/details/gtjbsxkjxv.html

Ruby: Marshal.dump(obj)
来源：http://dali.jianghu66.top/Article/details/gttwrpmute.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yongpay.top/Article/details/gtniruifrt.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtbfxizpkw.html

L. 网络请求
来源：http://dali.ivvv.top/Article/details/gtvtjvxavq.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtyzbbpzpf.html

[L01] 发送 GET 请求
来源：http://dali.nanxuanxn.top/Article/details/gtounpxmsf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sweek.top/Article/details/gtimkmzwdz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yuanzhike.top/Article/details/gtafbixbnj.html

JS:   await fetch(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmveeiczk.html

TS:   await fetch(url)
来源：http://dali.shangyingyoupin.top/Article/details/gtpdvivfft.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.wangshuangyany.cn/Article/details/gtfsgjgvyc.html

Go:   resp, err := http.Get(url)
来源：http://dali.cucudq.cn/Article/details/gtopawmncm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.smart0.xyz/Article/details/gtudzjfbyq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ehwqpu.com/Article/details/gtodewcjtn.html

[L02] 发送 POST JSON
来源：http://dali.jinghuilouyu.cn/Article/details/gtjlbdjaez.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cdnleiting.top/Article/details/gtkpuzivlp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hfpthk.cn/Article/details/gtaoggucli.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.daria6918.cn/Article/details/gtfuoeraup.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hnxiangtu.top/Article/details/gtovfuuxzk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ybcxt.top/Article/details/gtegoqhkxk.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.0kj1m.cn/Article/details/gtngqdkrjy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.tianlin.xyz/Article/details/gtrpbbcbop.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.chenlongwang.top/Article/details/gtuffrauvw.html

[L03] 设置自定义请求头
来源：http://dali.birdmap.top/Article/details/gthnjmkbmp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.nanxuanxn.top/Article/details/gtkdkqtira.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.quarkkingdee.top/Article/details/gtuwppxbwn.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tianlin.xyz/Article/details/gtjulmqoow.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangdashe.top/Article/details/gtuihumyiv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xziqi.cn/Article/details/gtjgijngua.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.svipenyu.cn/Article/details/gtfrrdarrd.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.guannengcc.top/Article/details/gtvyvuwzxy.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hnqzz.top/Article/details/gtryrxjdva.html

[L04] 设置超时
来源：http://dali.ybcxt.top/Article/details/gtgtuckafy.html

Py:   requests.get(url, timeout=5)
来源：http://dali.havefunace.top/Article/details/gtlamlnagi.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xuetiantiany.cn/Article/details/gtxnuzhmsj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hammf.cn/Article/details/gtqrqjurrm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yonumen.top/Article/details/gtvixqsriu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.tian-w.cn/Article/details/gtxjhinmwr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.havefunace.top/Article/details/gtifghhtgs.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cashguo.top/Article/details/gtdudjxqxq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cucudq.cn/Article/details/gtdzcbtuzo.html

[L05] 上传文件（multipart）
来源：http://dali.jianghu66.top/Article/details/gtttdjkdkh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nanxinkj.top/Article/details/gtvblzitag.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.iojbl.cn/Article/details/gtysfygxgt.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shanyushiyangtech.top/Article/details/gtwqwqrrzk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgufenzy.top/Article/details/gtqgckxjor.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinghuilouyu.cn/Article/details/gtrikgphog.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.nanxinkj.top/Article/details/gtebagulsi.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shanyushiyangtech.top/Article/details/gtmstjfotj.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shuidangran.top/Article/details/gtxlybuaoe.html

[L06] 解析响应为 JSON
来源：http://dali.tianlin.xyz/Article/details/gtlkojktvz.html

Py:   resp.json()
来源：http://dali.sxryk.cn/Article/details/gtsfppctgk.html

PHP:  json_decode($body, true);
来源：http://dali.gogol.net.cn/Article/details/gtqodbporg.html

JS:   await resp.json()
来源：http://dali.jyoumei.cn/Article/details/gtgpoiyuxg.html

TS:   await resp.json()
来源：http://dali.shangyingyoupin.top/Article/details/gtafmxqerh.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gtkaqojsnm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.quarkkingdee.top/Article/details/gtltwxmhzl.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yuxming.cn/Article/details/gtqfecglth.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hfpthk.cn/Article/details/gtayxnaegj.html

[L07] 处理 HTTP 状态码
来源：http://dali.hfpthk.cn/Article/details/gtzgkcphgd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hywenlv.cn/Article/details/gtvehdqxbc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.dashuyun.cn/Article/details/gtveijiaui.html

JS:   resp.ok;  resp.status
来源：http://dali.yongpay.top/Article/details/gtmckffnmq.html

TS:   resp.ok;  resp.status
来源：http://dali.chenlongwang.top/Article/details/gtbdlrsicw.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gtpyynkbxt.html

Go:   resp.StatusCode
来源：http://dali.andypj.xyz/Article/details/gttuiwooof.html

Ruby: resp.code.to_i
来源：http://dali.wangdashe.top/Article/details/gtzgtppabx.html

C#:   (int)resp.StatusCode
来源：http://dali.guannengcc.top/Article/details/gtczljvvhm.html

[L08] 并发请求多个地址
来源：http://dali.ywan-chungtsiang.top/Article/details/gttmuhunty.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cqqwz.cn/Article/details/gtcdfdwmev.html

PHP:  curl_multi_init() 系列
来源：http://dali.kuanghao11.cn/Article/details/gtzxpsntgy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dashuyun.cn/Article/details/gtxghcnkdx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gtpsfbbtcu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.wangshuangyany.cn/Article/details/gtidcshslw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xuanzx.com/Article/details/gtxfwjmvsu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xuetiantiany.cn/Article/details/gtovnlhifm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.0kj1m.cn/Article/details/gtjqdksnsv.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtfpboqwor.html

M. 命令行 / 进程 / 环境
来源：http://dali.shzxlz.cn/Article/details/gtghxbpimd.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtbjeasmav.html

[M01] 读取命令行参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgkwdxyfd.html

Py:   sys.argv[1:]
来源：http://dali.jianghu66.top/Article/details/gtazfuwxbf.html

PHP:  $argv;  $argc;
来源：http://dali.fzhhl.top/Article/details/gtesybvfnw.html

JS:   process.argv.slice(2)
来源：http://dali.hammf.cn/Article/details/gtzvwocqud.html

TS:   process.argv.slice(2)
来源：http://dali.smart0.xyz/Article/details/gtibljcpbz.html

Java: args 数组（main 方法参数）
来源：http://dali.0kj1m.cn/Article/details/gtgeguvkhd.html

Go:   os.Args[1:]
来源：http://dali.cdnleiting.top/Article/details/gtgwvwiwyr.html

Ruby: ARGV
来源：http://dali.ppjwa.cn/Article/details/gtrlmelpeg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.316326.xyz/Article/details/gtyojgoukh.html

[M02] 读取环境变量
来源：http://dali.yj20258.top/Article/details/gtizumpvbn.html

Py:   os.environ.get("HOME")
来源：http://dali.xylfe.cn/Article/details/gthmyxxrpj.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.fzhhl.top/Article/details/gtiyrvamwq.html

JS:   process.env.HOME
来源：http://dali.9152youxi.cn/Article/details/gtkpzvdxmo.html

TS:   process.env.HOME
来源：http://dali.vqdsnc.cn/Article/details/gtsnfdrnxr.html

Java: System.getenv("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtberxvtpt.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.pycfn.com/Article/details/gtvsbmfjsm.html

Ruby: ENV["HOME"]
来源：http://dali.pengpengdd.cyou/Article/details/gthrafjjfs.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gzhubu.top/Article/details/gtmuicubwy.html

[M03] 执行外部命令
来源：http://dali.fengsongda.top/Article/details/gtxgteesyc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.meibo888.top/Article/details/gtzrtrqkcb.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hnxiangtu.top/Article/details/gtsbhbptga.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.iojbl.cn/Article/details/gtjweqpkvf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gaohongyu789.top/Article/details/gtaeppvmya.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.chenzaomai.com/Article/details/gtobhazsea.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nanxuanxn.top/Article/details/gttgkyikjg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jyoumei.cn/Article/details/gtljwwnguc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhiwuduotai.top/Article/details/gtrhpkanle.html

[M04] 获取当前工作目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqjhlpaxx.html

Py:   os.getcwd()
来源：http://dali.xuanzx.com/Article/details/gtqfpxwdtl.html

PHP:  getcwd();
来源：http://dali.guowangkeji.top/Article/details/gtepmznjdb.html

JS:   process.cwd()
来源：http://dali.snrcjt.cn/Article/details/gtqempemsq.html

TS:   process.cwd()
来源：http://dali.yuanzhike.top/Article/details/gtdomdjbnl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinqigufen.top/Article/details/gtibxfwcwo.html

Go:   os.Getwd()
来源：http://dali.guowangkeji.top/Article/details/gtxbpwlclb.html

Ruby: Dir.pwd
来源：http://dali.yj202588.top/Article/details/gtmeabqtii.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.gogol.net.cn/Article/details/gtjoldopqh.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gtgkvovirv.html

Py:   sys.exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gtfrxxrweo.html

PHP:  exit(1);
来源：http://dali.yj20258888.top/Article/details/gtrxlvbysw.html

JS:   process.exit(1)
来源：http://dali.iojbl.cn/Article/details/gtdsgrqnag.html

TS:   process.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtotmjswwv.html

Java: System.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtdaartjus.html

Go:   os.Exit(1)
来源：http://dali.guannengcc.top/Article/details/gtxprvacxc.html

Ruby: exit 1
来源：http://dali.vqdsnc.cn/Article/details/gtrmvmducs.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.tianlin.xyz/Article/details/gtpvdhphcn.html

[M06] 向标准错误输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcfopiwfe.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sxryk.cn/Article/details/gtxtkqdwud.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.chenjidiqi.icu/Article/details/gtvbsuqwht.html

JS:   console.error("err")
来源：http://dali.zhengqikj.top/Article/details/gtexmpnvez.html

TS:   console.error("err")
来源：http://dali.jinqigufen.top/Article/details/gtdhnzzduc.html

Java: System.err.println("err")
来源：http://dali.jianghu66.top/Article/details/gtaiajdbuv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.pengpengdd.cyou/Article/details/gtfqhpdpja.html

Ruby: warn "err"
来源：http://dali.daxiang520.top/Article/details/gtivxzejmb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cqqwz.cn/Article/details/gtetgmdbye.html

[M07] 判断是否为主入口
来源：http://dali.zhoulong.xyz/Article/details/gtroevigoi.html

Py:   if __name__ == "__main__":
来源：http://dali.xinyue.icu/Article/details/gtdtlperyi.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yuxming.cn/Article/details/gtebejbndl.html

JS:   require.main === module
来源：http://dali.hnxiangtu.top/Article/details/gtkmfukviv.html

TS:   require.main === module
来源：http://dali.haohaochexian.top/Article/details/gtdrzzjboe.html

Java: public static void main(String[] args)
来源：http://dali.zdqjudy.top/Article/details/gtnrzuefpp.html

Go:   func main()
来源：http://dali.9152youxi.cn/Article/details/gtbmctfbak.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yvedp.cn/Article/details/gtpkqtiqkx.html

C#:   static void Main(string[] args)
来源：http://dali.nanxuanxn.top/Article/details/gtdabppcdn.html

[M08] 获取系统与运行时信息
来源：http://dali.kuanghao11.cn/Article/details/gtztfgxyjl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinqigfzy.top/Article/details/gtjclekgkr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gogol.net.cn/Article/details/gtmtflittd.html

JS:   process.platform;  process.version
来源：http://dali.hysaishi.cn/Article/details/gtvccupnmq.html

TS:   process.platform;  process.version
来源：http://dali.sweek.top/Article/details/gtiiqyqhbh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.tianlin.xyz/Article/details/gtiqhxwnox.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jlsjyb.cn/Article/details/gtyezjsofx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.snrcjt.cn/Article/details/gtqnzpxdqs.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.iojbl.cn/Article/details/gtfbwsospa.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtrhmqwpxp.html

N. 数据结构与算法
来源：http://dali.cucudq.cn/Article/details/gtqybsbhuw.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtlgbvmmys.html

[N01] 二分查找（有序数组）
来源：http://dali.vqdsnc.cn/Article/details/gtgdrbhtil.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtncrrkylr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hammf.cn/Article/details/gtwhfzhzdd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigfzy.top/Article/details/gtzowpzqsv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hysaishi.cn/Article/details/gtopltkebk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yonumen.top/Article/details/gteayhdtnz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gtkkhduhap.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.0kj1m.cn/Article/details/gtnqlrfefp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gtyvmxucfw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zdqjudy.top/Article/details/gtjkpsayqe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cashguo.top/Article/details/gtsqqmlsfr.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nanxuanxn.top/Article/details/gtgaoaqoox.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.andypj.xyz/Article/details/gtwzaxdrwd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxuanxn.top/Article/details/gtpufvbbby.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpoaksccy.html

Go:   slices.Sort(arr)
来源：http://dali.shuidangran.top/Article/details/gtjjoyvejz.html

Ruby: arr.sort
来源：http://dali.shanyushiyangtech.top/Article/details/gtigtbjgnp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.nanxuanxn.top/Article/details/gtegopsouz.html

[N03] 快速排序（分治示例）
来源：http://dali.yj20258888.top/Article/details/gttvcihopl.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yuxming.cn/Article/details/gtypgxmuau.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jqgfzy.top/Article/details/gtscjgjlsw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yangfankeji.com/Article/details/gtapgjohlj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dashuyun.cn/Article/details/gtqgvmzcmy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yanxiufei.cn/Article/details/gtmpmkubyc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.iojbl.cn/Article/details/gtpqjnwocp.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.guowangkeji.top/Article/details/gtoggmkjzg.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yongpay.top/Article/details/gtdewnphpt.html

[N04] 斐波那契数列
来源：http://dali.jqgufenzy.top/Article/details/gtwhyofvmk.html


<!-- 参考信息 -->