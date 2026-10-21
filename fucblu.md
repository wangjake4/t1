代发 wailian999

[J07] 比较两个日期
来源：http://dali.cucudq.cn/Article/details/gtamxosgem.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.nanxinkj.top/Article/details/gtfuwwxkxn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.guannengcc.top/Article/details/gtwbilafmy.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yongpay.top/Article/details/gteryxsrsu.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jyoumei.cn/Article/details/gtyehbmypx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xuetiantiany.cn/Article/details/gtwhoucgrc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jqgufenzy.top/Article/details/gteulnkomc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hysaishi.cn/Article/details/gtmngrjpsp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.nwbrower.top/Article/details/gtjvfywpan.html

[J08] 提取年月日与星期
来源：http://dali.hywenlv.cn/Article/details/gtbfbkjryr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.fengsongda.top/Article/details/gtdaxvblwl.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ivvv.top/Article/details/gtjhlbxefv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.316326.xyz/Article/details/gtwpmnqbgr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nwbrower.top/Article/details/gtjtbboren.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jiagoushi.top/Article/details/gtujhdkfrh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.mhx1999.top/Article/details/gtkrqlwyeh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cashguo.top/Article/details/gtomwjytkh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.pengpengdd.cyou/Article/details/gtybjwthve.html

[J09] 时区处理
来源：http://dali.nwbrower.top/Article/details/gtkwtroauv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.pycfn.com/Article/details/gtbpqwyzub.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.nanxuanxn.top/Article/details/gtuooqbkpy.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jyoumei.cn/Article/details/gtiqlpzowq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhixingplan.top/Article/details/gteecciwdd.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zycfv.cn/Article/details/gthvvciwvj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xziqi.cn/Article/details/gtsjptuwwt.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hnxiangtu.top/Article/details/gtuysbkyry.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cucudq.cn/Article/details/gtdmzmrxyy.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhiwuduotai.top/Article/details/gtppclkbne.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxpnhqexl.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tanke756.top/Article/details/gtroephhds.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.9152youxi.cn/Article/details/gtwwjxghuo.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.dashuyun.cn/Article/details/gtopjdapvc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj20258888.top/Article/details/gtidmygtik.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinghuilouyu.cn/Article/details/gtrwsmvbxh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jiagoushi.top/Article/details/gtuqpwdrjk.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cdnleiting.top/Article/details/gtvepjhxog.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtxouajnhk.html

K. JSON 与序列化
来源：http://dali.shuidangran.top/Article/details/gtfxmnalce.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtsduzhopp.html

[K01] 对象转 JSON 字符串
来源：http://dali.guowangkeji.top/Article/details/gttnztguyc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zdqjudy.top/Article/details/gtnavwjloh.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gaohongyu789.top/Article/details/gtawtydalw.html

JS:   JSON.stringify(obj)
来源：http://dali.smart0.xyz/Article/details/gtqobkdyiu.html

TS:   JSON.stringify(obj)
来源：http://dali.ybcxt.top/Article/details/gtmzltwggf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.fzhhl.top/Article/details/gtoebqioml.html

Go:   json.Marshal(obj)
来源：http://dali.andypj.xyz/Article/details/gtkdgwlpbw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.dianchejie.cn/Article/details/gtncpogpoa.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.redwolf501.top/Article/details/gttjxtbdea.html

[K02] JSON 字符串转对象
来源：http://dali.xuanzx.com/Article/details/gthqcponua.html

Py:   json.loads(s)
来源：http://dali.xylfe.cn/Article/details/gtsdjpqsof.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jqgfzy.top/Article/details/gtnlvyjbbp.html

JS:   JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtfcicrauq.html

TS:   JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gtngplmged.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shuidangran.top/Article/details/gtbjytlchb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.quarkkingdee.top/Article/details/gtaaukzloc.html

Ruby: JSON.parse(s)
来源：http://dali.tanke756.top/Article/details/gtlreotjll.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.havefunace.top/Article/details/gtdlxsfifq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.chenzaomai.com/Article/details/gthvxazolb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jianghu66.top/Article/details/gtivegizoa.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cashguo.top/Article/details/gtugpnexdj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gtjyjislst.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zdqjudy.top/Article/details/gtelerazmb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gogol.net.cn/Article/details/gtoweyccpt.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.guannengcc.top/Article/details/gtpimohdkh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtxnisnyrt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shanyushiyangtech.top/Article/details/gtkgcgtqqp.html

[K04] 读取 JSON 文件
来源：http://dali.shzxlz.cn/Article/details/gtzmeemorq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.mhx1999.top/Article/details/gtseqaodwe.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yuanzhike.top/Article/details/gtzigwydnh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yueranfly.top/Article/details/gtmrmbjuhy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhongyouzk.top/Article/details/gttlamwskb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sxryk.cn/Article/details/gtlqybwyyr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcbtkfhsc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xinyue.icu/Article/details/gtdwskpjej.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.pycfn.com/Article/details/gthnpvcwxg.html

[K05] 深拷贝对象
来源：http://dali.jlsjyb.cn/Article/details/gtjlbllbfb.html

Py:   copy.deepcopy(obj)
来源：http://dali.ppjwa.cn/Article/details/gtjkwlbvxr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhoulong.xyz/Article/details/gtnqhtshmp.html

JS:   structuredClone(obj)
来源：http://dali.aibaodan.cn/Article/details/gtfzsxfqmr.html

TS:   structuredClone(obj)
来源：http://dali.guannengcc.top/Article/details/gtcgthyiow.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jyoumei.cn/Article/details/gtgoqiyooe.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.fengsongda.top/Article/details/gtduoqmjdi.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.aizwys.cn/Article/details/gtfwbghjqz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yj20258888.top/Article/details/gtepvvjeoh.html

[K06] 解析 URL 查询串
来源：http://dali.shangyingyoupin.top/Article/details/gtkcxqoxvs.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shzxlz.cn/Article/details/gtkfarwwbb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gogol.net.cn/Article/details/gtfylfpxuc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenlongwang.top/Article/details/gtpglfjdjf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.redwolf501.top/Article/details/gtjhafuthf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ydzc1.top/Article/details/gtgmwlgkyx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqaxnkzem.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hfpthk.cn/Article/details/gtjaaqvqqb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yueranfly.top/Article/details/gtiynhypgl.html

[K07] 进制转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvugcocws.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtanuivnhz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xuanzx.com/Article/details/gtcvernthg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gtekmizwgy.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gtgijgshyt.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gtlflgljgi.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.0kj1m.cn/Article/details/gtjgmkqzbl.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhoulong.xyz/Article/details/gtpgpvzkfp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gtlpyczgoi.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhiwuduotai.top/Article/details/gtahxsipze.html

Py:   pickle.dumps(obj)
来源：http://dali.daria6918.cn/Article/details/gtyywnarcp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtuwitpcro.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hfpthk.cn/Article/details/gtktmezmhn.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xylfe.cn/Article/details/gtmyxmkwqx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.daria6918.cn/Article/details/gtjbmtsrpr.html

Go:   encoding/gob
来源：http://dali.shangyingyoupin.top/Article/details/gtyqjjvzkn.html

Ruby: Marshal.dump(obj)
来源：http://dali.ybcxt.top/Article/details/gtctdpvcnm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlipjkefb.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gttcxjdxqu.html

L. 网络请求
来源：http://dali.nwbrower.top/Article/details/gtegyoneep.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtgsledxhk.html

[L01] 发送 GET 请求
来源：http://dali.jinqigfzy.top/Article/details/gttleufjmi.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cdnleiting.top/Article/details/gtfbellmty.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gotoacloud.top/Article/details/gtbpedzjpy.html

JS:   await fetch(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcunfoijs.html

TS:   await fetch(url)
来源：http://dali.chenlongwang.top/Article/details/gtobbsvxjl.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ydzc1.top/Article/details/gttdgeglwq.html

Go:   resp, err := http.Get(url)
来源：http://dali.nanxuanxn.top/Article/details/gtzugskqdz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yuxming.cn/Article/details/gtjjzudjoo.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xuanzx.com/Article/details/gttuljvdxl.html

[L02] 发送 POST JSON
来源：http://dali.hnqzz.top/Article/details/gtyuydqllj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gogol.net.cn/Article/details/gttgsesqtn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.quarkkingdee.top/Article/details/gtltxkfend.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cdnleiting.top/Article/details/gtdheifqgh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.quarkkingdee.top/Article/details/gtznnawfir.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hnqzz.top/Article/details/gtfsdrrldu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cqqwz.cn/Article/details/gtrvqgbpmk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.quarkkingdee.top/Article/details/gttnwiqvom.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xylfe.cn/Article/details/gtsvkoirtm.html

[L03] 设置自定义请求头
来源：http://dali.xuetiantiany.cn/Article/details/gtkhnllrnk.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.haohaochexian.top/Article/details/gtmcfojjhy.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zycfv.cn/Article/details/gtpodpkoap.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aibaodan.cn/Article/details/gtjyuqtwka.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangdashe.top/Article/details/gteeygmdxl.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zycfv.cn/Article/details/gteldbngbo.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gtxjelkuld.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ehwqpu.com/Article/details/gthwkulkfm.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sweek.top/Article/details/gtpxdmjnrb.html

[L04] 设置超时
来源：http://dali.hammf.cn/Article/details/gtqguilhtg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.haohaochexian.top/Article/details/gtnvkrpwwn.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jyoumei.cn/Article/details/gttnjhrvam.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuanzhike.top/Article/details/gtsqadtnoj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gotoacloud.top/Article/details/gtdopmlfbj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sufxvd.cn/Article/details/gtupucegod.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.bjfxy.top/Article/details/gtbhsqtbbz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinqigfzy.top/Article/details/gtonsjdshn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenzaomai.com/Article/details/gtdwjwlena.html

[L05] 上传文件（multipart）
来源：http://dali.chenzaomai.com/Article/details/gtzojhnwjl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sweek.top/Article/details/gtkxgiqcze.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.aizwys.cn/Article/details/gtmbqgqift.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.quarkkingdee.top/Article/details/gtcpckxtlb.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sxryk.cn/Article/details/gtxwkmpmxx.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.daria6918.cn/Article/details/gtstwdnovn.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.fzhhl.top/Article/details/gtphwcyayk.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jqgfzy.top/Article/details/gtjtcyijfg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinqigufen.top/Article/details/gttfkufsae.html

[L06] 解析响应为 JSON
来源：http://dali.yuxming.cn/Article/details/gthjdlwrze.html

Py:   resp.json()
来源：http://dali.vqdsnc.cn/Article/details/gtdxvqmxdj.html

PHP:  json_decode($body, true);
来源：http://dali.9152youxi.cn/Article/details/gtsqytfvgg.html

JS:   await resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gtoyycoocl.html

TS:   await resp.json()
来源：http://dali.cdnleiting.top/Article/details/gtunfhjfwn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.haohaochexian.top/Article/details/gtgtwzywmr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.dashuyun.cn/Article/details/gtwqhrccnr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhixingplan.top/Article/details/gtisfsvhxi.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ppjwa.cn/Article/details/gtrmynlhec.html

[L07] 处理 HTTP 状态码
来源：http://dali.nwbrower.top/Article/details/gtvbybzmwc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtliowewgu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yueranfly.top/Article/details/gtigiditcq.html

JS:   resp.ok;  resp.status
来源：http://dali.bjfxy.top/Article/details/gtfmnkxpsw.html

TS:   resp.ok;  resp.status
来源：http://dali.xylfe.cn/Article/details/gtifbqkygk.html

Java: resp.statusCode()
来源：http://dali.yj202588.top/Article/details/gtutxxaoct.html

Go:   resp.StatusCode
来源：http://dali.tian-w.cn/Article/details/gtzgsmqcrd.html

Ruby: resp.code.to_i
来源：http://dali.shzxlz.cn/Article/details/gthnqrnfrf.html

C#:   (int)resp.StatusCode
来源：http://dali.yangfankeji.com/Article/details/gtekvjgxeq.html

[L08] 并发请求多个地址
来源：http://dali.tian-w.cn/Article/details/gthognfvdz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.redwolf501.top/Article/details/gtwpzhuuvf.html

PHP:  curl_multi_init() 系列
来源：http://dali.svipenyu.cn/Article/details/gtvcsbyddr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pycfn.com/Article/details/gtpusbvyyy.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jiagoushi.top/Article/details/gtfgnmlrct.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.snrcjt.cn/Article/details/gtaimqlzyd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yj202588.top/Article/details/gtptbfzohx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gtrzfckjfc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.chenzaomai.com/Article/details/gtvvuvrjuy.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtjkzjwxnj.html

M. 命令行 / 进程 / 环境
来源：http://dali.ydzc1.top/Article/details/gtanvggfwz.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtwahszckm.html

[M01] 读取命令行参数
来源：http://dali.xuetiantiany.cn/Article/details/gtljaoahjp.html

Py:   sys.argv[1:]
来源：http://dali.hysaishi.cn/Article/details/gtzqmknhzt.html

PHP:  $argv;  $argc;
来源：http://dali.fengsongda.top/Article/details/gtwkvtyszn.html

JS:   process.argv.slice(2)
来源：http://dali.xuetiantiany.cn/Article/details/gtaxkpafqe.html

TS:   process.argv.slice(2)
来源：http://dali.meibo888.top/Article/details/gtsoyzqhrc.html

Java: args 数组（main 方法参数）
来源：http://dali.jlsjyb.cn/Article/details/gtzlquwsys.html

Go:   os.Args[1:]
来源：http://dali.sysykeji.top/Article/details/gtoazpdegl.html

Ruby: ARGV
来源：http://dali.pengpengdd.cyou/Article/details/gtomxrnffs.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hnqzz.top/Article/details/gtnehwajae.html

[M02] 读取环境变量
来源：http://dali.jiagoushi.top/Article/details/gtjpofeogy.html

Py:   os.environ.get("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gtkvetpdqv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hammf.cn/Article/details/gtuzrvtezy.html

JS:   process.env.HOME
来源：http://dali.ppjwa.cn/Article/details/gtjumbctjr.html

TS:   process.env.HOME
来源：http://dali.snrcjt.cn/Article/details/gtzwwxsgxg.html

Java: System.getenv("HOME")
来源：http://dali.wangdashe.top/Article/details/gtrtmzwmkw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gtzeujgplb.html

Ruby: ENV["HOME"]
来源：http://dali.dianchejie.cn/Article/details/gtacqgauaf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gtyvbhgwqs.html

[M03] 执行外部命令
来源：http://dali.redwolf501.top/Article/details/gteizdvdpd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhoulong.xyz/Article/details/gtxsxvyajf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ybcxt.top/Article/details/gtkptwbsan.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yueranfly.top/Article/details/gtbexklrth.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkfwtbhvp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jlsjyb.cn/Article/details/gtzifyneuh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xinyue.icu/Article/details/gtlxdozluu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.pycfn.com/Article/details/gtwyrdrklu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.feifeiyinyue.top/Article/details/gtufminyut.html

[M04] 获取当前工作目录
来源：http://dali.chenzaomai.com/Article/details/gtzhtjqjov.html

Py:   os.getcwd()
来源：http://dali.havefunace.top/Article/details/gtwwxlvqgs.html

PHP:  getcwd();
来源：http://dali.cucudq.cn/Article/details/gtcztpjcax.html

JS:   process.cwd()
来源：http://dali.sysykeji.top/Article/details/gttpzqdnet.html

TS:   process.cwd()
来源：http://dali.sweek.top/Article/details/gtbzepbkhh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jiagoushi.top/Article/details/gtggafjrfg.html

Go:   os.Getwd()
来源：http://dali.yonumen.top/Article/details/gtqajtnmes.html

Ruby: Dir.pwd
来源：http://dali.zhixingplan.top/Article/details/gtidsozcpg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shangyingyoupin.top/Article/details/gthoehqikt.html

[M05] 设置退出码
来源：http://dali.ehwqpu.com/Article/details/gtlyajrdgv.html

Py:   sys.exit(1)
来源：http://dali.xinyue.icu/Article/details/gtibnhlhaa.html

PHP:  exit(1);
来源：http://dali.aibaodan.cn/Article/details/gtsfogbrrx.html

JS:   process.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gthmeugpyp.html

TS:   process.exit(1)
来源：http://dali.ivvv.top/Article/details/gtduxqqnys.html

Java: System.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtscvtrcii.html

Go:   os.Exit(1)
来源：http://dali.zhengqikj.top/Article/details/gtmsjljllx.html

Ruby: exit 1
来源：http://dali.dashuyun.cn/Article/details/gtjsqouofx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhiwuduotai.top/Article/details/gtxnilwcwa.html

[M06] 向标准错误输出
来源：http://dali.sxryk.cn/Article/details/gtmsqbvtwq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jyoumei.cn/Article/details/gtaeawckvk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jyoumei.cn/Article/details/gtueolvsgr.html

JS:   console.error("err")
来源：http://dali.ppjwa.cn/Article/details/gtleduuoga.html

TS:   console.error("err")
来源：http://dali.jianghu66.top/Article/details/gtxusaadsh.html

Java: System.err.println("err")
来源：http://dali.chenzaomai.com/Article/details/gtwbqoksho.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gzhubu.top/Article/details/gtvtkzmgqk.html

Ruby: warn "err"
来源：http://dali.yj20258888.top/Article/details/gtcpbytfvn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xziqi.cn/Article/details/gthzaracdt.html

[M07] 判断是否为主入口
来源：http://dali.zdqjudy.top/Article/details/gtvhtiqpnm.html

Py:   if __name__ == "__main__":
来源：http://dali.yj20258888.top/Article/details/gtjxtcejok.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xuanzx.com/Article/details/gthqktyfmu.html

JS:   require.main === module
来源：http://dali.shanyushiyangtech.top/Article/details/gtykqcmbeq.html

TS:   require.main === module
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwwbspgud.html

Java: public static void main(String[] args)
来源：http://dali.ydzc1.top/Article/details/gtynnlsjwd.html

Go:   func main()
来源：http://dali.wangshuangyany.cn/Article/details/gtdqbacmyq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.daria6918.cn/Article/details/gtaregiahr.html

C#:   static void Main(string[] args)
来源：http://dali.smart0.xyz/Article/details/gtuzcwypsm.html

[M08] 获取系统与运行时信息
来源：http://dali.zhongyouzk.top/Article/details/gtbzeztssz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sysykeji.top/Article/details/gttdisvfnj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gzhubu.top/Article/details/gtodjypbfd.html

JS:   process.platform;  process.version
来源：http://dali.jinqigufen.top/Article/details/gteqvojqji.html

TS:   process.platform;  process.version
来源：http://dali.kuanghao11.cn/Article/details/gttfblvolh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.haohaochexian.top/Article/details/gthgwtqlna.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yongpay.top/Article/details/gtcziupgxm.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jyoumei.cn/Article/details/gtssrdmtfg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.0kj1m.cn/Article/details/gtyeymfykp.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtgdfiuxyo.html

N. 数据结构与算法
来源：http://dali.smart0.xyz/Article/details/gtqvuznzhq.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtvtpmunos.html

[N01] 二分查找（有序数组）
来源：http://dali.wangshuangyany.cn/Article/details/gtmoacifyd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtdponvnkf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.316326.xyz/Article/details/gtjtrqnrad.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jianghu66.top/Article/details/gtwwcsdoze.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guowangkeji.top/Article/details/gtuclvuplr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtieayxkin.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.meibo888.top/Article/details/gttmytpihj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.chenzaomai.com/Article/details/gtcwvonauo.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtzwvawcdm.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hysaishi.cn/Article/details/gtnwkalqzh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jyoumei.cn/Article/details/gtqhgnmtof.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.tian-w.cn/Article/details/gtjcznjzsk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.quarkkingdee.top/Article/details/gtmyqowvmz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gotoacloud.top/Article/details/gtzxwlwrbj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zycfv.cn/Article/details/gtwjtlncdy.html

Go:   slices.Sort(arr)
来源：http://dali.cdnleiting.top/Article/details/gttqdilmbu.html

Ruby: arr.sort
来源：http://dali.hywenlv.cn/Article/details/gtmyblreuo.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cucudq.cn/Article/details/gtfiviamrj.html

[N03] 快速排序（分治示例）
来源：http://dali.0kj1m.cn/Article/details/gthatnjxcr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xziqi.cn/Article/details/gthfqofssv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hongshengwenyu.top/Article/details/gttqlkiwnx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daria6918.cn/Article/details/gtcdzdnost.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yueranfly.top/Article/details/gtpmnqmfdl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yuanzhike.top/Article/details/gtzgtjyuka.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.feifeiyinyue.top/Article/details/gtpmfgnaii.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xylfe.cn/Article/details/gtcbwvkkub.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ppjwa.cn/Article/details/gtmsxfngwv.html

[N04] 斐波那契数列
来源：http://dali.mhx1999.top/Article/details/gtfbtulavg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cucudq.cn/Article/details/gtwldmrrcg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.snrcjt.cn/Article/details/gtrxtpbnzv.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pycfn.com/Article/details/gtzfiqbiwk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtjqacinfh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shuidangran.top/Article/details/gtgvoolvlf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.nanxuanxn.top/Article/details/gtozkokxcx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.chenzaomai.com/Article/details/gtynjvpljt.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtcholdjim.html


<!-- 参考信息 -->