代发 wailian999

[J07] 比较两个日期
来源：http://dali.daxiang520.top/Article/details/gtjxgivhxm.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.iojbl.cn/Article/details/gtaifyxjnm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jqgfzy.top/Article/details/gtrawghrri.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.pengpengdd.cyou/Article/details/gtcjrjushe.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.bjfxy.top/Article/details/gtvlymiyyy.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhiwuduotai.top/Article/details/gteotirfzy.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.kuanghao11.cn/Article/details/gtwfykrpxz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gtldvkwkvh.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.nanxinkj.top/Article/details/gtbofolgbm.html

[J08] 提取年月日与星期
来源：http://dali.tian-w.cn/Article/details/gtcxxazocr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.9152youxi.cn/Article/details/gttvxhnsnd.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.dashuyun.cn/Article/details/gtxpzulsvo.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.wangdashe.top/Article/details/gtachfvoel.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.daxiang520.top/Article/details/gtqzucblzy.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cqqwz.cn/Article/details/gtnpsoouzr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yuxming.cn/Article/details/gtejhhoaim.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhijiandao.cn/Article/details/gtfakqabnu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.haohaochexian.top/Article/details/gtnjtptgyw.html

[J09] 时区处理
来源：http://dali.nwbrower.top/Article/details/gthcplnysr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yj202588.top/Article/details/gtmktnkuny.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.snrcjt.cn/Article/details/gtdnhoyusd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.haohaochexian.top/Article/details/gtyiiytaqu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ivvv.top/Article/details/gtooznwihu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cashguo.top/Article/details/gtuqupeclz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.guowangkeji.top/Article/details/gtpkttajhf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.dianchejie.cn/Article/details/gtzoafgwlg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.snrcjt.cn/Article/details/gtgdsbqrej.html

[J10] 取今天 / 本月第一天
来源：http://dali.ehwqpu.com/Article/details/gttzrgksyv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.kuanghao11.cn/Article/details/gtdawrezqy.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhengqikj.top/Article/details/gtocsflvtc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yuanzhike.top/Article/details/gtrrincqkj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.dashuyun.cn/Article/details/gtutvdhvsa.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.wangdashe.top/Article/details/gtyjhqiujk.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.nanxuanxn.top/Article/details/gteoncwkoj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.c1oappe.top/Article/details/gtfmnzaxwm.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinqigfzy.top/Article/details/gtgidnnyha.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtcghujjxy.html

K. JSON 与序列化
来源：http://dali.ybcxt.top/Article/details/gtgtiiekun.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtgfvwpzjd.html

[K01] 对象转 JSON 字符串
来源：http://dali.yuxming.cn/Article/details/gtpelpbqip.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.daria6918.cn/Article/details/gtjhdjosdg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.daria6918.cn/Article/details/gtetdbeakr.html

JS:   JSON.stringify(obj)
来源：http://dali.yj20258.top/Article/details/gtrwpqeeup.html

TS:   JSON.stringify(obj)
来源：http://dali.cashguo.top/Article/details/gtrsfyswyi.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cashguo.top/Article/details/gteamfqkzo.html

Go:   json.Marshal(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtieyjqvpv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.smart0.xyz/Article/details/gtmuxsosuw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtcsojzrii.html

[K02] JSON 字符串转对象
来源：http://dali.yuxming.cn/Article/details/gtyjdrhhuu.html

Py:   json.loads(s)
来源：http://dali.sufxvd.cn/Article/details/gtaqgmtaln.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ivvv.top/Article/details/gtojvhzzyk.html

JS:   JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gtebnpvwee.html

TS:   JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gtvwnndoze.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jlsjyb.cn/Article/details/gtzmxsmfkj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.nwbrower.top/Article/details/gthmqqxrbi.html

Ruby: JSON.parse(s)
来源：http://dali.havefunace.top/Article/details/gtaxotuxbl.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yj20258.top/Article/details/gtnbqrmpse.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.havefunace.top/Article/details/gtjgnludpq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.c1oappe.top/Article/details/gtqedjetdt.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gzhubu.top/Article/details/gtiumpclpv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjrhktuzy.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.guowangkeji.top/Article/details/gtzggjshyt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.haohaochexian.top/Article/details/gtfeolyrpt.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.aizwys.cn/Article/details/gtprwjwxzt.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hywenlv.cn/Article/details/gtmthhjvgu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhengqikj.top/Article/details/gtdbqbudhj.html

[K04] 读取 JSON 文件
来源：http://dali.andypj.xyz/Article/details/gtqxbolwrr.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ivvv.top/Article/details/gtbkyrjbxe.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jqgfzy.top/Article/details/gtpjhuijnd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuxming.cn/Article/details/gtaszjaaau.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangdashe.top/Article/details/gtvnsdruwf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gtrgpjgtbj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtddahvwyx.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.havefunace.top/Article/details/gtjmwnifen.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtdwdgycwe.html

[K05] 深拷贝对象
来源：http://dali.hnxiangtu.top/Article/details/gtwtcclunh.html

Py:   copy.deepcopy(obj)
来源：http://dali.gotoacloud.top/Article/details/gtypoaqsst.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoscpqoyr.html

JS:   structuredClone(obj)
来源：http://dali.hammf.cn/Article/details/gtaegcfyfx.html

TS:   structuredClone(obj)
来源：http://dali.316326.xyz/Article/details/gtcdoehlwv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhiwuduotai.top/Article/details/gtbzmoqqwx.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.mhx1999.top/Article/details/gtbrnownoe.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.daria6918.cn/Article/details/gthfhuswqf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbswondxx.html

[K06] 解析 URL 查询串
来源：http://dali.jianghu66.top/Article/details/gtwxzfntie.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xziqi.cn/Article/details/gtrpjbmthm.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.sxryk.cn/Article/details/gtggpbvelb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.smart0.xyz/Article/details/gtbswmviro.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guowangkeji.top/Article/details/gtgjtnpttg.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ivvv.top/Article/details/gtqhtrhtiq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gtdpuscyck.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.wangdashe.top/Article/details/gtctxfpadu.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtibttlxci.html

[K07] 进制转换
来源：http://dali.yj20258.top/Article/details/gthvtxbytq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gtbtksgoic.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yuxming.cn/Article/details/gtrwmjskwj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gtyfrxfrse.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gtfmxunwod.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gtjrflfgjt.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.vqdsnc.cn/Article/details/gtcehvbzvg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.wangshuangyany.cn/Article/details/gtxgsbpbzn.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gtvcpooiaa.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.nanxuanxn.top/Article/details/gtpgmtbhtr.html

Py:   pickle.dumps(obj)
来源：http://dali.dashuyun.cn/Article/details/gtbbykvgio.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.tian-w.cn/Article/details/gtsfordxuf.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xinyue.icu/Article/details/gtnzkkfjsc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cqqwz.cn/Article/details/gtcexlmsdu.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yonumen.top/Article/details/gtjwmdosbn.html

Go:   encoding/gob
来源：http://dali.hfpthk.cn/Article/details/gtjoxrwnrq.html

Ruby: Marshal.dump(obj)
来源：http://dali.pycfn.com/Article/details/gtsxgpuoam.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gtxxqhhxvp.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gttbtwjtyz.html

L. 网络请求
来源：http://dali.svipenyu.cn/Article/details/gtxhmzvonc.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtlllptxdk.html

[L01] 发送 GET 请求
来源：http://dali.jyoumei.cn/Article/details/gtfqjhjgfi.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hammf.cn/Article/details/gtpfcyohrt.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cqqwz.cn/Article/details/gtqwarulwg.html

JS:   await fetch(url)
来源：http://dali.cdnleiting.top/Article/details/gtmumfgncc.html

TS:   await fetch(url)
来源：http://dali.jlsjyb.cn/Article/details/gtybdqpcdq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.guannengcc.top/Article/details/gtfkftyfsk.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhengqikj.top/Article/details/gtpkctesyf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.wangshuangyany.cn/Article/details/gtahunvsrc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shzxlz.cn/Article/details/gtfzhnwmck.html

[L02] 发送 POST JSON
来源：http://dali.guowangkeji.top/Article/details/gtewnmyepl.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.andypj.xyz/Article/details/gtzgcqmdhh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.vqdsnc.cn/Article/details/gtboqmllhi.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yueranfly.top/Article/details/gtqzxfmrzm.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigufen.top/Article/details/gtwnoiuwyo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.kuanghao11.cn/Article/details/gthyadjafm.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.nwbrower.top/Article/details/gtntgysfyo.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.vqdsnc.cn/Article/details/gthwqxvrgl.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jiagoushi.top/Article/details/gtxxsozkjj.html

[L03] 设置自定义请求头
来源：http://dali.bjfxy.top/Article/details/gtoiyxizzf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sweek.top/Article/details/gtjetjptpp.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.snrcjt.cn/Article/details/gtaezveycp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangdashe.top/Article/details/gtjxqnhnpn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yangfankeji.com/Article/details/gtepwocwvw.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.iojbl.cn/Article/details/gtbnlekgmo.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoihqyyca.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhixingplan.top/Article/details/gtevqofavb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.nwbrower.top/Article/details/gtyjjcwntw.html

[L04] 设置超时
来源：http://dali.zhongyouzk.top/Article/details/gtqdlvaswq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xuanzx.com/Article/details/gtrxkfyxea.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.andypj.xyz/Article/details/gtpwmfwxdt.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tianlin.xyz/Article/details/gtrayxqvjf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sysykeji.top/Article/details/gtgzogyfxz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.svipenyu.cn/Article/details/gtqdywyxsn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hywenlv.cn/Article/details/gtbzjwnbcr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yj20258.top/Article/details/gtjzkhofgh.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yangfankeji.com/Article/details/gthtfjlzga.html

[L05] 上传文件（multipart）
来源：http://dali.wangdashe.top/Article/details/gtisyjbffs.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinqigufen.top/Article/details/gtmrmkcmlq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.redwolf501.top/Article/details/gtnmdqvutt.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.guowangkeji.top/Article/details/gtfmcvywnr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhongyouzk.top/Article/details/gtgkazglpo.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hfpthk.cn/Article/details/gtadokicnn.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hammf.cn/Article/details/gtiiihzvdu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjokywpoi.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtmbhpbflg.html

[L06] 解析响应为 JSON
来源：http://dali.ybcxt.top/Article/details/gtofsvjuov.html

Py:   resp.json()
来源：http://dali.316326.xyz/Article/details/gtcagdlhvy.html

PHP:  json_decode($body, true);
来源：http://dali.smart0.xyz/Article/details/gtgiimdejg.html

JS:   await resp.json()
来源：http://dali.sxryk.cn/Article/details/gtesejtlpn.html

TS:   await resp.json()
来源：http://dali.hfpthk.cn/Article/details/gtankrgcie.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnfcxqsms.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtktfuojil.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cheryme.top/Article/details/gtugofuoqq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gaohongyu789.top/Article/details/gtwfmvcaaf.html

[L07] 处理 HTTP 状态码
来源：http://dali.hnxiangtu.top/Article/details/gtnkuvszlb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tian-w.cn/Article/details/gtoymnpwio.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ivvv.top/Article/details/gtdnxloyet.html

JS:   resp.ok;  resp.status
来源：http://dali.jyoumei.cn/Article/details/gtptdboibw.html

TS:   resp.ok;  resp.status
来源：http://dali.fzhhl.top/Article/details/gtdreenceb.html

Java: resp.statusCode()
来源：http://dali.jiagoushi.top/Article/details/gtaffjvozp.html

Go:   resp.StatusCode
来源：http://dali.c1oappe.top/Article/details/gtpzailwjs.html

Ruby: resp.code.to_i
来源：http://dali.gotoacloud.top/Article/details/gtrbieptbs.html

C#:   (int)resp.StatusCode
来源：http://dali.sysykeji.top/Article/details/gtvomrqrsi.html

[L08] 并发请求多个地址
来源：http://dali.jlsjyb.cn/Article/details/gtbystejfj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gzhubu.top/Article/details/gtnklpuvfy.html

PHP:  curl_multi_init() 系列
来源：http://dali.yanxiufei.cn/Article/details/gtiyhybgjf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shuidangran.top/Article/details/gtxmzmskwj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxuanxn.top/Article/details/gtcyqrdkym.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.bjfxy.top/Article/details/gtbqjrqrrb.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cashguo.top/Article/details/gteajhmztg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sxryk.cn/Article/details/gtudfgtieb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ybcxt.top/Article/details/gtdyzpbrqf.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtlvkosszt.html

M. 命令行 / 进程 / 环境
来源：http://dali.ywan-chungtsiang.top/Article/details/gtehehuxbw.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtzknndqxy.html

[M01] 读取命令行参数
来源：http://dali.zycfv.cn/Article/details/gtsckwtpmb.html

Py:   sys.argv[1:]
来源：http://dali.gotoacloud.top/Article/details/gtntpcmmuw.html

PHP:  $argv;  $argc;
来源：http://dali.quarkkingdee.top/Article/details/gttzuekcyj.html

JS:   process.argv.slice(2)
来源：http://dali.redwolf501.top/Article/details/gtdqikcjuw.html

TS:   process.argv.slice(2)
来源：http://dali.sysykeji.top/Article/details/gtdcibhzhu.html

Java: args 数组（main 方法参数）
来源：http://dali.yongpay.top/Article/details/gtadjsoowz.html

Go:   os.Args[1:]
来源：http://dali.daria6918.cn/Article/details/gtstvwbepb.html

Ruby: ARGV
来源：http://dali.nanxinkj.top/Article/details/gtepjhesqh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhengqikj.top/Article/details/gtiitvtpeo.html

[M02] 读取环境变量
来源：http://dali.fzhhl.top/Article/details/gtilvteqgh.html

Py:   os.environ.get("HOME")
来源：http://dali.hfpthk.cn/Article/details/gtzyhzsblh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yvedp.cn/Article/details/gtgulxiprv.html

JS:   process.env.HOME
来源：http://dali.xylfe.cn/Article/details/gtoqufksct.html

TS:   process.env.HOME
来源：http://dali.zhiwuduotai.top/Article/details/gtmjzhqjrt.html

Java: System.getenv("HOME")
来源：http://dali.andypj.xyz/Article/details/gtmerccnex.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gtpgetglep.html

Ruby: ENV["HOME"]
来源：http://dali.xinyue.icu/Article/details/gtfvhvuzac.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gtsqvyhwoe.html

[M03] 执行外部命令
来源：http://dali.kuanghao11.cn/Article/details/gtjsjxleoc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yj202588.top/Article/details/gtjpztqdku.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ivvv.top/Article/details/gttussaguc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhongyouzk.top/Article/details/gticmhegpk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxuanxn.top/Article/details/gtxwrwnmim.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.9152youxi.cn/Article/details/gtyzlsfkhf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.snrcjt.cn/Article/details/gtzvsltmtr.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jqgufenzy.top/Article/details/gtbpvzlnbo.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hammf.cn/Article/details/gtvpzeqddz.html

[M04] 获取当前工作目录
来源：http://dali.daria6918.cn/Article/details/gtiuxbyfhl.html

Py:   os.getcwd()
来源：http://dali.ivvv.top/Article/details/gtwvhpsoag.html

PHP:  getcwd();
来源：http://dali.pengpengdd.cyou/Article/details/gtaossmfcd.html

JS:   process.cwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpokwxqlp.html

TS:   process.cwd()
来源：http://dali.jyoumei.cn/Article/details/gtupbgzgtu.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.fzhhl.top/Article/details/gtibhsusob.html

Go:   os.Getwd()
来源：http://dali.pycfn.com/Article/details/gtkjznkmnj.html

Ruby: Dir.pwd
来源：http://dali.fzhhl.top/Article/details/gteecltlvl.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhongyouzk.top/Article/details/gtwgmitxss.html

[M05] 设置退出码
来源：http://dali.aizwys.cn/Article/details/gtodufvdvt.html

Py:   sys.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gtiqotwusf.html

PHP:  exit(1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttpwsntct.html

JS:   process.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gthafzrgbw.html

TS:   process.exit(1)
来源：http://dali.xinyue.icu/Article/details/gtefebfljt.html

Java: System.exit(1)
来源：http://dali.xylfe.cn/Article/details/gtrvvitxoe.html

Go:   os.Exit(1)
来源：http://dali.yj20258888.top/Article/details/gtsdpbdkaw.html

Ruby: exit 1
来源：http://dali.gogol.net.cn/Article/details/gtpvtfxpmf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.wangdashe.top/Article/details/gtudxaorex.html

[M06] 向标准错误输出
来源：http://dali.yj20258.top/Article/details/gtkemlhuia.html

Py:   print("err", file=sys.stderr)
来源：http://dali.andypj.xyz/Article/details/gtyclgmxjt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yuanzhike.top/Article/details/gtqnxqadyf.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gtlzsujxtu.html

TS:   console.error("err")
来源：http://dali.zhongyouzk.top/Article/details/gtjehxmruy.html

Java: System.err.println("err")
来源：http://dali.jlsjyb.cn/Article/details/gtoiwgexkc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxzxneflk.html

Ruby: warn "err"
来源：http://dali.yangfankeji.com/Article/details/gtuxnlosew.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hnxiangtu.top/Article/details/gtwtadtzzz.html

[M07] 判断是否为主入口
来源：http://dali.cdnleiting.top/Article/details/gtxwhcphrz.html

Py:   if __name__ == "__main__":
来源：http://dali.meibo888.top/Article/details/gtgclkchts.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.pengpengdd.cyou/Article/details/gtpcymnxmw.html

JS:   require.main === module
来源：http://dali.jlsjyb.cn/Article/details/gtwphnylfa.html

TS:   require.main === module
来源：http://dali.sxryk.cn/Article/details/gtzyyxlxbx.html

Java: public static void main(String[] args)
来源：http://dali.jqgfzy.top/Article/details/gtxdkclqvv.html

Go:   func main()
来源：http://dali.tian-w.cn/Article/details/gtejpdunhn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.kuanghao11.cn/Article/details/gtwokpqjlg.html

C#:   static void Main(string[] args)
来源：http://dali.shangyingyoupin.top/Article/details/gtjrfxrhvn.html

[M08] 获取系统与运行时信息
来源：http://dali.sxryk.cn/Article/details/gturrbxtkw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtotgvshxc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.tian-w.cn/Article/details/gtzkthofcx.html

JS:   process.platform;  process.version
来源：http://dali.cucudq.cn/Article/details/gtykqnkpng.html

TS:   process.platform;  process.version
来源：http://dali.chenjidiqi.icu/Article/details/gtxqfqhizy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.tian-w.cn/Article/details/gtyychtinu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.quarkkingdee.top/Article/details/gtrnsomsvo.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.nanxinkj.top/Article/details/gtunovufzq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.birdmap.top/Article/details/gtxmastqil.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtdrptawux.html

N. 数据结构与算法
来源：http://dali.snrcjt.cn/Article/details/gtknzkydmp.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtqiuypqhh.html

[N01] 二分查找（有序数组）
来源：http://dali.zhixingplan.top/Article/details/gtzvbozbkj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.tanke756.top/Article/details/gtvmsegepz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sxryk.cn/Article/details/gtikeyyvid.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gtauoisjrz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ivvv.top/Article/details/gtwmefypxl.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.birdmap.top/Article/details/gtisfihaev.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtfqzoagdc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.quarkkingdee.top/Article/details/gtsnmdgren.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gzhubu.top/Article/details/gteflolgju.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxxrnatgh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cucudq.cn/Article/details/gtocjtbwmy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hammf.cn/Article/details/gtfgogmepa.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxfwyoglx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.0kj1m.cn/Article/details/gtyrwxkygj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cucudq.cn/Article/details/gtjmcqenma.html

Go:   slices.Sort(arr)
来源：http://dali.pycfn.com/Article/details/gtrsscoftd.html

Ruby: arr.sort
来源：http://dali.haohaochexian.top/Article/details/gtkrittspl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jqgufenzy.top/Article/details/gtaifepwqc.html

[N03] 快速排序（分治示例）
来源：http://dali.shuidangran.top/Article/details/gtdldmznmf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.meibo888.top/Article/details/gtdykcxtlk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.sweek.top/Article/details/gtcefjpqwz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangtech.top/Article/details/gtmiljihfd.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gotoacloud.top/Article/details/gtahkbvvoq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.wangdashe.top/Article/details/gtctcuhnju.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cheryme.top/Article/details/gtvfnlwxzg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.tianlin.xyz/Article/details/gtqtumihce.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.tanke756.top/Article/details/gtxhzaflcp.html

[N04] 斐波那契数列
来源：http://dali.jinqigufen.top/Article/details/gtebugoonn.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ybcxt.top/Article/details/gtonvfybov.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hysaishi.cn/Article/details/gtpfjfhadr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sweek.top/Article/details/gtjaqdnpcu.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dianchejie.cn/Article/details/gtaigeyhml.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ybcxt.top/Article/details/gtirgyniek.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.chenlongwang.top/Article/details/gtliqixybw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.birdmap.top/Article/details/gtvqmvxtwo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yongpay.top/Article/details/gtwxwffauv.html


<!-- 参考信息 -->