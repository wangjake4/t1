代发 wailian999

[J07] 比较两个日期
来源：http://dali.aibaodan.cn/Article/details/gtdwmsibgw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xuanzx.com/Article/details/gtgqpfatez.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.9152youxi.cn/Article/details/gtngcadfug.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.pycfn.com/Article/details/gtwmvwxcmj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xinyue.icu/Article/details/gtfwpsepmi.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shangyingyoupin.top/Article/details/gtfjcvnbrm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cheryme.top/Article/details/gtbkapfiub.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gtpbztnymi.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinqigfzy.top/Article/details/gtzegahaim.html

[J08] 提取年月日与星期
来源：http://dali.jqgfzy.top/Article/details/gtjbcdpzcw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinqigfzy.top/Article/details/gtncabnbit.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhijiandao.cn/Article/details/gtvtaurzru.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.c1oappe.top/Article/details/gtxcpzgiio.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.mhx1999.top/Article/details/gtdfjqkiid.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinqigfzy.top/Article/details/gtetyavawe.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zycfv.cn/Article/details/gtvbtaovho.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sufxvd.cn/Article/details/gtutqlzknl.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hammf.cn/Article/details/gtdelufnvv.html

[J09] 时区处理
来源：http://dali.yj20258.top/Article/details/gtzgoifrvy.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.redwolf501.top/Article/details/gtisdvzogl.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yj20258888.top/Article/details/gtsjlecxmh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hammf.cn/Article/details/gtxybrbtyz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jyoumei.cn/Article/details/gtnofbidsy.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.dashuyun.cn/Article/details/gtlglcrnaj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sysykeji.top/Article/details/gtxptbeipd.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.havefunace.top/Article/details/gtpkahlvml.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.havefunace.top/Article/details/gtuohcjrqk.html

[J10] 取今天 / 本月第一天
来源：http://dali.jiagoushi.top/Article/details/gteafbxasw.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.mhx1999.top/Article/details/gtkohuazjw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ivvv.top/Article/details/gtypwqgfnl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cdnleiting.top/Article/details/gtsribzyfk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.aizwys.cn/Article/details/gtlvmsrkba.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yuanzhike.top/Article/details/gtrlsabbjc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.pycfn.com/Article/details/gttlwuulgv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gotoacloud.top/Article/details/gtgbhfiuxo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.meibo888.top/Article/details/gtzdbkfdms.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtnqbpvtwg.html

K. JSON 与序列化
来源：http://dali.hfpthk.cn/Article/details/gtgabmrqpt.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtpbzqhyer.html

[K01] 对象转 JSON 字符串
来源：http://dali.smart0.xyz/Article/details/gtkgmuydam.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.birdmap.top/Article/details/gtujbsbcql.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangtech.top/Article/details/gtflmjngsa.html

JS:   JSON.stringify(obj)
来源：http://dali.xylfe.cn/Article/details/gtcotexnos.html

TS:   JSON.stringify(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtzykjmhqh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gogol.net.cn/Article/details/gtgyxjcfid.html

Go:   json.Marshal(obj)
来源：http://dali.fzhhl.top/Article/details/gtankxhihy.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.haohaochexian.top/Article/details/gtabusulcr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.c1oappe.top/Article/details/gtmzqjossh.html

[K02] JSON 字符串转对象
来源：http://dali.zhoulong.xyz/Article/details/gtvwfqetxb.html

Py:   json.loads(s)
来源：http://dali.xziqi.cn/Article/details/gttnaepyzu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.316326.xyz/Article/details/gtikrdvbjn.html

JS:   JSON.parse(s)
来源：http://dali.jianghu66.top/Article/details/gtzhzfkwkj.html

TS:   JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gtwgmmqzlm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.dianchejie.cn/Article/details/gtjgwzbiys.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yj202588.top/Article/details/gtkcfdbptx.html

Ruby: JSON.parse(s)
来源：http://dali.gzhubu.top/Article/details/gthirfdpgd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hammf.cn/Article/details/gtfubkkugt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.tianlin.xyz/Article/details/gtortchred.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shzxlz.cn/Article/details/gtlrnhpoow.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258.top/Article/details/gtkupwezhh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258888.top/Article/details/gthgmdgunx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrzuvlbru.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.chenlongwang.top/Article/details/gtqybmkyyd.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yongpay.top/Article/details/gtlwpyodjn.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xinyue.icu/Article/details/gtwjicssms.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.guowangkeji.top/Article/details/gtecmhqict.html

[K04] 读取 JSON 文件
来源：http://dali.yuxming.cn/Article/details/gteqcqnlct.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhoulong.xyz/Article/details/gtnxbiknpk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jiagoushi.top/Article/details/gtssuhxrwp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfnuawnoh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.0kj1m.cn/Article/details/gtfpsvsnby.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jqgfzy.top/Article/details/gtwrwdyven.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gogol.net.cn/Article/details/gtuckkgdpd.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteqoehzpl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.iojbl.cn/Article/details/gtnxvthpzf.html

[K05] 深拷贝对象
来源：http://dali.cdnleiting.top/Article/details/gthcnmyylu.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtgbzygcaa.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shanyushiyangtech.top/Article/details/gtvzgyydim.html

JS:   structuredClone(obj)
来源：http://dali.yangfankeji.com/Article/details/gtwmzvkikc.html

TS:   structuredClone(obj)
来源：http://dali.fzhhl.top/Article/details/gtnlgbteiw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenlongwang.top/Article/details/gtktjymuwi.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sufxvd.cn/Article/details/gthtsqtcde.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.0kj1m.cn/Article/details/gtkphmiefs.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.pengpengdd.cyou/Article/details/gtcjlkziuj.html

[K06] 解析 URL 查询串
来源：http://dali.aibaodan.cn/Article/details/gtigjdlxzt.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.nwbrower.top/Article/details/gtecuwufmo.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yongpay.top/Article/details/gthguhuzgg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cucudq.cn/Article/details/gtgxldifmh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shuidangran.top/Article/details/gtnifwpgpw.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.redwolf501.top/Article/details/gtdnlyfymo.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gtksfkpubh.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gtyipnztqr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gtdzqccnoe.html

[K07] 进制转换
来源：http://dali.sufxvd.cn/Article/details/gtxwtwpjvx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgcbqnjvh.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hysaishi.cn/Article/details/gtriqdqmwn.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gthfzehnpa.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrwkuidzt.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gthvradstj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yj20258.top/Article/details/gtrxjsudtt.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzbjpwwus.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gtghesqjqy.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.svipenyu.cn/Article/details/gtcwfddixf.html

Py:   pickle.dumps(obj)
来源：http://dali.yueranfly.top/Article/details/gtweewston.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.guannengcc.top/Article/details/gtoccdcvqq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.dianchejie.cn/Article/details/gtufrxolqj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zycfv.cn/Article/details/gtfqtyfebj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhengqikj.top/Article/details/gtfxukanac.html

Go:   encoding/gob
来源：http://dali.kuanghao11.cn/Article/details/gtsmgohgyh.html

Ruby: Marshal.dump(obj)
来源：http://dali.shuidangran.top/Article/details/gtnbpybduw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shangyingyoupin.top/Article/details/gtiwnbfrjl.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtpxdtiakp.html

L. 网络请求
来源：http://dali.yuanzhike.top/Article/details/gtlurkhmpi.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gticodhbiv.html

[L01] 发送 GET 请求
来源：http://dali.gogol.net.cn/Article/details/gtbbxvtkfs.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zdqjudy.top/Article/details/gtledtozug.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yangfankeji.com/Article/details/gthpzsceyk.html

JS:   await fetch(url)
来源：http://dali.shuidangran.top/Article/details/gtbnoiqlxc.html

TS:   await fetch(url)
来源：http://dali.ehwqpu.com/Article/details/gtcevmufqv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.iojbl.cn/Article/details/gtnvhaffus.html

Go:   resp, err := http.Get(url)
来源：http://dali.hongshengwenyu.top/Article/details/gtndylzijx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hnqzz.top/Article/details/gtcelakacz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.nwbrower.top/Article/details/gtdnvvynhz.html

[L02] 发送 POST JSON
来源：http://dali.yuanzhike.top/Article/details/gtnykuudyi.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yongpay.top/Article/details/gttwqkjzpv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhoulong.xyz/Article/details/gtdbvqhomi.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tanke756.top/Article/details/gtekqsbsxf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yonumen.top/Article/details/gtexwdmwvh.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yanxiufei.cn/Article/details/gttfrhotzo.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xuanzx.com/Article/details/gtltneuplx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hnqzz.top/Article/details/gtoeewlqop.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shzxlz.cn/Article/details/gtoncgqath.html

[L03] 设置自定义请求头
来源：http://dali.ppjwa.cn/Article/details/gtsppzlxtb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.nanxuanxn.top/Article/details/gtifalrfet.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhoulong.xyz/Article/details/gtfmfzvhsz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenzaomai.com/Article/details/gttkfnekus.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jqgfzy.top/Article/details/gtgmhfwjrt.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cdnleiting.top/Article/details/gttbvkxtkc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yonumen.top/Article/details/gtkrodtdbk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenlongwang.top/Article/details/gtnybnpchg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xylfe.cn/Article/details/gtgggmkpwa.html

[L04] 设置超时
来源：http://dali.xziqi.cn/Article/details/gtpmxrrudl.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjmrljkgw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.9152youxi.cn/Article/details/gtamljgrzv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.bjfxy.top/Article/details/gtnxywttnj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.birdmap.top/Article/details/gtwrxcmrhb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.vqdsnc.cn/Article/details/gthbcboses.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.andypj.xyz/Article/details/gtbxoycpqp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhixingplan.top/Article/details/gtwutavvwo.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.nanxuanxn.top/Article/details/gtxseeweuy.html

[L05] 上传文件（multipart）
来源：http://dali.daria6918.cn/Article/details/gtirycseiy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.redwolf501.top/Article/details/gtvlxscuce.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zdqjudy.top/Article/details/gtnswfrigm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinghuilouyu.cn/Article/details/gtoscnxqgk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shzxlz.cn/Article/details/gtxdqcdexr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shanyushiyangtech.top/Article/details/gtrfokruwx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhengqikj.top/Article/details/gtrtsszcgf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.nanxuanxn.top/Article/details/gthhclgyas.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtxdopkqgq.html

[L06] 解析响应为 JSON
来源：http://dali.ydzc1.top/Article/details/gtqygerhze.html

Py:   resp.json()
来源：http://dali.daxiang520.top/Article/details/gtabisijuw.html

PHP:  json_decode($body, true);
来源：http://dali.ppjwa.cn/Article/details/gtmipcuvgn.html

JS:   await resp.json()
来源：http://dali.jiagoushi.top/Article/details/gtvhyhywzl.html

TS:   await resp.json()
来源：http://dali.hnxiangtu.top/Article/details/gtadziwkwy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shzxlz.cn/Article/details/gtaeunfonn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.dashuyun.cn/Article/details/gtzlethrqk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbnzbultt.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.iojbl.cn/Article/details/gtxmbngobn.html

[L07] 处理 HTTP 状态码
来源：http://dali.yonumen.top/Article/details/gtrsthoomm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.snrcjt.cn/Article/details/gtqqzmubxg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jlsjyb.cn/Article/details/gtgotcsqbn.html

JS:   resp.ok;  resp.status
来源：http://dali.gogol.net.cn/Article/details/gtzzijrrso.html

TS:   resp.ok;  resp.status
来源：http://dali.pengpengdd.cyou/Article/details/gtpqcfdbpx.html

Java: resp.statusCode()
来源：http://dali.xuanzx.com/Article/details/gtoiabiuin.html

Go:   resp.StatusCode
来源：http://dali.ivvv.top/Article/details/gtaiuscrjs.html

Ruby: resp.code.to_i
来源：http://dali.feifeiyinyue.top/Article/details/gtnzbxssyv.html

C#:   (int)resp.StatusCode
来源：http://dali.hongshengwenyu.top/Article/details/gtcnbwzmmm.html

[L08] 并发请求多个地址
来源：http://dali.jqgfzy.top/Article/details/gtkqdhogop.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.fengsongda.top/Article/details/gthehfgkow.html

PHP:  curl_multi_init() 系列
来源：http://dali.snrcjt.cn/Article/details/gtavjqfsys.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gtgznqzgbj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yonumen.top/Article/details/gtjcflripn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yuxming.cn/Article/details/gtkmdjiwzv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.pengpengdd.cyou/Article/details/gtclhqeeva.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnlchxyta.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.meibo888.top/Article/details/gtighpywwu.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtzcwdgpnq.html

M. 命令行 / 进程 / 环境
来源：http://dali.meibo888.top/Article/details/gtfqbyvdup.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtzqeayvdc.html

[M01] 读取命令行参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxvzyuosi.html

Py:   sys.argv[1:]
来源：http://dali.cheryme.top/Article/details/gtbsbmsplj.html

PHP:  $argv;  $argc;
来源：http://dali.zdqjudy.top/Article/details/gtwgsmqzyq.html

JS:   process.argv.slice(2)
来源：http://dali.jiagoushi.top/Article/details/gtzqpfeebf.html

TS:   process.argv.slice(2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzphckueo.html

Java: args 数组（main 方法参数）
来源：http://dali.ivvv.top/Article/details/gtefboczmt.html

Go:   os.Args[1:]
来源：http://dali.hysaishi.cn/Article/details/gtdvuellgm.html

Ruby: ARGV
来源：http://dali.daria6918.cn/Article/details/gtipqgxsyk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yanxiufei.cn/Article/details/gtyjjebtkr.html

[M02] 读取环境变量
来源：http://dali.hnqzz.top/Article/details/gtrklyscsf.html

Py:   os.environ.get("HOME")
来源：http://dali.sysykeji.top/Article/details/gtwqbsvkzt.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.wangshuangyany.cn/Article/details/gtdjymkwna.html

JS:   process.env.HOME
来源：http://dali.cdnleiting.top/Article/details/gtozovthxj.html

TS:   process.env.HOME
来源：http://dali.jinghuilouyu.cn/Article/details/gtndzpxeit.html

Java: System.getenv("HOME")
来源：http://dali.shzxlz.cn/Article/details/gtsntvkydv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gtldfteykw.html

Ruby: ENV["HOME"]
来源：http://dali.xuanzx.com/Article/details/gtmtcuqzny.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.snrcjt.cn/Article/details/gtpppuseif.html

[M03] 执行外部命令
来源：http://dali.shzxlz.cn/Article/details/gtkbwwbhnh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gotoacloud.top/Article/details/gtfefetlwa.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ydzc1.top/Article/details/gtqaimxnvv.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yangfankeji.com/Article/details/gtwchffzgw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sweek.top/Article/details/gtdwbbzaet.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.birdmap.top/Article/details/gtxrjcyeip.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.0kj1m.cn/Article/details/gtbhhtyuoa.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.snrcjt.cn/Article/details/gtvlkzpuir.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yj202588.top/Article/details/gtczhjmpsf.html

[M04] 获取当前工作目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteuthgpuz.html

Py:   os.getcwd()
来源：http://dali.daxiang520.top/Article/details/gtrmibpmqb.html

PHP:  getcwd();
来源：http://dali.birdmap.top/Article/details/gtzmxogyhs.html

JS:   process.cwd()
来源：http://dali.smart0.xyz/Article/details/gtafjioast.html

TS:   process.cwd()
来源：http://dali.xuetiantiany.cn/Article/details/gtdfkuektm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.tanke756.top/Article/details/gtxtnfxesv.html

Go:   os.Getwd()
来源：http://dali.nanxuanxn.top/Article/details/gtbqcxqodz.html

Ruby: Dir.pwd
来源：http://dali.ybcxt.top/Article/details/gtfabrmzik.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.haohaochexian.top/Article/details/gtznpgmcyy.html

[M05] 设置退出码
来源：http://dali.cqqwz.cn/Article/details/gtypkicmpr.html

Py:   sys.exit(1)
来源：http://dali.cashguo.top/Article/details/gtuswzcnhi.html

PHP:  exit(1);
来源：http://dali.yj20258888.top/Article/details/gtetenbmgc.html

JS:   process.exit(1)
来源：http://dali.xziqi.cn/Article/details/gtuzfahtgg.html

TS:   process.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gtfdwkvlun.html

Java: System.exit(1)
来源：http://dali.andypj.xyz/Article/details/gthelwaqme.html

Go:   os.Exit(1)
来源：http://dali.cucudq.cn/Article/details/gtbuzmdznu.html

Ruby: exit 1
来源：http://dali.daria6918.cn/Article/details/gtecwoeake.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj202588.top/Article/details/gtzsxjchrr.html

[M06] 向标准错误输出
来源：http://dali.daria6918.cn/Article/details/gtmatzqywg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yueranfly.top/Article/details/gtqfgtwday.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hnxiangtu.top/Article/details/gtuxgryqez.html

JS:   console.error("err")
来源：http://dali.jqgufenzy.top/Article/details/gtshnvpkfr.html

TS:   console.error("err")
来源：http://dali.chenlongwang.top/Article/details/gticmjagwe.html

Java: System.err.println("err")
来源：http://dali.zhengqikj.top/Article/details/gtwhidgngu.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zycfv.cn/Article/details/gtvvtojwca.html

Ruby: warn "err"
来源：http://dali.yj20258888.top/Article/details/gtzkukqppq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.wangdashe.top/Article/details/gtuaewcvfe.html

[M07] 判断是否为主入口
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdbspvwim.html

Py:   if __name__ == "__main__":
来源：http://dali.yanxiufei.cn/Article/details/gtprrqvpst.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.guowangkeji.top/Article/details/gtgpovyfqi.html

JS:   require.main === module
来源：http://dali.yongpay.top/Article/details/gtigtsejuo.html

TS:   require.main === module
来源：http://dali.yuanzhike.top/Article/details/gtiltphbye.html

Java: public static void main(String[] args)
来源：http://dali.yuanzhike.top/Article/details/gtefktgeck.html

Go:   func main()
来源：http://dali.yonumen.top/Article/details/gtvgxqvwwf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.nanxinkj.top/Article/details/gtrujtyvoa.html

C#:   static void Main(string[] args)
来源：http://dali.snrcjt.cn/Article/details/gthehxdugs.html

[M08] 获取系统与运行时信息
来源：http://dali.hywenlv.cn/Article/details/gttdvpjsgc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xuetiantiany.cn/Article/details/gtmnnlmyrd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.havefunace.top/Article/details/gtxbtcaphh.html

JS:   process.platform;  process.version
来源：http://dali.daxiang520.top/Article/details/gttkzzkkht.html

TS:   process.platform;  process.version
来源：http://dali.kuanghao11.cn/Article/details/gtqvgdzdkh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hysaishi.cn/Article/details/gtgtrtczzp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yanxiufei.cn/Article/details/gtzwjzqdsq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinghuilouyu.cn/Article/details/gtmbxxntii.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gogol.net.cn/Article/details/gtcersukyz.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtxuvbaixr.html

N. 数据结构与算法
来源：http://dali.jinqigufen.top/Article/details/gtgokrvees.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtwczuheyi.html

[N01] 二分查找（有序数组）
来源：http://dali.jlsjyb.cn/Article/details/gtxsxcjark.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yuxming.cn/Article/details/gtajgguzyn.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.daria6918.cn/Article/details/gthhumopdr.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ybcxt.top/Article/details/gtjjnxejth.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xziqi.cn/Article/details/gtxqoqbhmr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtsqtqdhoj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtmemhwhdd.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj20258888.top/Article/details/gtomkvokbe.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gttssiwcwe.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ppjwa.cn/Article/details/gtfjvbekoh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gogol.net.cn/Article/details/gtqudiumxy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.daxiang520.top/Article/details/gtsajexdnc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fzhhl.top/Article/details/gtrclergbd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yangfankeji.com/Article/details/gtyrzncfuk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jianghu66.top/Article/details/gtufocdjsp.html

Go:   slices.Sort(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtxsiiqtve.html

Ruby: arr.sort
来源：http://dali.jlsjyb.cn/Article/details/gtvzybubpr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ydzc1.top/Article/details/gtrtfzslyb.html

[N03] 快速排序（分治示例）
来源：http://dali.guowangkeji.top/Article/details/gtdvlvupzw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuhnktajy.html

PHP:  // 递归实现，或用 usort
来源：http://dali.tanke756.top/Article/details/gtltnuoffu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hywenlv.cn/Article/details/gthyephwmf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ywan-chungtsiang.top/Article/details/gttnxwyoiy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hammf.cn/Article/details/gtdqfboxms.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zycfv.cn/Article/details/gtpnedvytv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhiwuduotai.top/Article/details/gtqrndhcfi.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sweek.top/Article/details/gtqqwhohku.html

[N04] 斐波那契数列
来源：http://dali.jinqigfzy.top/Article/details/gtchrktxte.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.svipenyu.cn/Article/details/gtixgbsqiw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yangfankeji.com/Article/details/gtugbovbsz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.andypj.xyz/Article/details/gtxodjjtke.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.fengsongda.top/Article/details/gtvmnqilvi.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.mhx1999.top/Article/details/gtcmsotfjf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xylfe.cn/Article/details/gtiwuyjzca.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gogol.net.cn/Article/details/gtbwualtyn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yanxiufei.cn/Article/details/gtbzwyxelm.html


<!-- 参考信息 -->