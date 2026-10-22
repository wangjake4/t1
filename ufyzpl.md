代发 wailian999

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhoulong.xyz/Article/details/gt2zuwuscjd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.redwolf501.top/Article/details/gt2xatgclle.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.nwbrower.top/Article/details/gt2nswowurh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.kuanghao11.cn/Article/details/gt2adgbvktf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gt2vgusmbhh.html

[J08] 提取年月日与星期
来源：http://dali.yuxming.cn/Article/details/gt2ucyahnfc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.nanxuanxn.top/Article/details/gt2kgcdfqef.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2epmtwukz.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.mhx1999.top/Article/details/gt2czkfqjtm.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.fzhhl.top/Article/details/gt2kahumqqf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.tianlin.xyz/Article/details/gt2hfrpwyrw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.haohaochexian.top/Article/details/gt2cvxsiqmy.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hammf.cn/Article/details/gt2eekpjglj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jianghu66.top/Article/details/gt2atokzrvn.html

[J09] 时区处理
来源：http://dali.ehwqpu.com/Article/details/gt2yqxgopwb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.c1oappe.top/Article/details/gt2viidpohz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hongshengwenyu.top/Article/details/gt2arsosmxb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangdashe.top/Article/details/gt2hotjfzqy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hongshengwenyu.top/Article/details/gt2mqwsnkdj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xziqi.cn/Article/details/gt2gvhjmoto.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ltghedwq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.kuanghao11.cn/Article/details/gt2neqrpick.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hnqzz.top/Article/details/gt2gywiojxf.html

[J10] 取今天 / 本月第一天
来源：http://dali.andypj.xyz/Article/details/gt2kllfacbo.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yj20258888.top/Article/details/gt2aglmjzlz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zdqjudy.top/Article/details/gt2ricukuep.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.pycfn.com/Article/details/gt2xmgnyosv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yangfankeji.com/Article/details/gt2tgjzprdw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.daria6918.cn/Article/details/gt2lgpvpmud.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.316326.xyz/Article/details/gt2siisopui.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.havefunace.top/Article/details/gt2xctnwizk.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yiykjwjf.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2wcqyumir.html

K. JSON 与序列化
来源：http://dali.0kj1m.cn/Article/details/gt2tixcrxmn.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2adxqwmvf.html

[K01] 对象转 JSON 字符串
来源：http://dali.daria6918.cn/Article/details/gt2szqzypsk.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jqgufenzy.top/Article/details/gt2zhroniqa.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.nwbrower.top/Article/details/gt2igxbqnvc.html

JS:   JSON.stringify(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2dmioreau.html

TS:   JSON.stringify(obj)
来源：http://dali.redwolf501.top/Article/details/gt2zbhsvscn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jiagoushi.top/Article/details/gt2cwxlrfqa.html

Go:   json.Marshal(obj)
来源：http://dali.yj202588.top/Article/details/gt2aaktajeg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.9152youxi.cn/Article/details/gt2myiumxqj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2bszwyesn.html

[K02] JSON 字符串转对象
来源：http://dali.snrcjt.cn/Article/details/gt2tvzrrnew.html

Py:   json.loads(s)
来源：http://dali.iojbl.cn/Article/details/gt2dajnroyv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.snrcjt.cn/Article/details/gt2wdemivoh.html

JS:   JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gt2buzpbmda.html

TS:   JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gt2zsjupzva.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.vqdsnc.cn/Article/details/gt2nacagqjc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yj20258.top/Article/details/gt2mopgojzv.html

Ruby: JSON.parse(s)
来源：http://dali.cucudq.cn/Article/details/gt2ubfjtjth.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cucudq.cn/Article/details/gt2daomnkrz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.iojbl.cn/Article/details/gt2idtvzfzo.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ehwqpu.com/Article/details/gt2btrxbpnh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xziqi.cn/Article/details/gt2aofkoqot.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2ypwrimjy.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.pycfn.com/Article/details/gt2fwnfntyl.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.fengsongda.top/Article/details/gt2xdbglkct.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xinyue.icu/Article/details/gt2fzybxttc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.bjfxy.top/Article/details/gt2jsscomwa.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ydzc1.top/Article/details/gt2xwajufsl.html

[K04] 读取 JSON 文件
来源：http://dali.havefunace.top/Article/details/gt2ytmsachd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yanxiufei.cn/Article/details/gt2tmkkvzyl.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.wangshuangyany.cn/Article/details/gt2eujilyjr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenlongwang.top/Article/details/gt2qgqwedrj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shuidangran.top/Article/details/gt2zobohsrz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xqgnjedf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.316326.xyz/Article/details/gt2uspgxtgw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gaohongyu789.top/Article/details/gt2oxxchkgo.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hnqzz.top/Article/details/gt2orniloxv.html

[K05] 深拷贝对象
来源：http://dali.yonumen.top/Article/details/gt2plophenn.html

Py:   copy.deepcopy(obj)
来源：http://dali.daxiang520.top/Article/details/gt2pbpicyva.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gotoacloud.top/Article/details/gt2idzmgicd.html

JS:   structuredClone(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2ablmeaku.html

TS:   structuredClone(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2cewptabb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.pycfn.com/Article/details/gt2jnfloeiv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.c1oappe.top/Article/details/gt2qwcbisvw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tnszjkba.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.9152youxi.cn/Article/details/gt2sfterzcw.html

[K06] 解析 URL 查询串
来源：http://dali.c1oappe.top/Article/details/gt2bhmubeml.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xinyue.icu/Article/details/gt2zbjvzljb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yueranfly.top/Article/details/gt2oaagxbvj.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yangfankeji.com/Article/details/gt2pmptbyvi.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258888.top/Article/details/gt2ldlherir.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sufxvd.cn/Article/details/gt2jrnxpddd.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.wangdashe.top/Article/details/gt2eahammcq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gt2lonabvgs.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jyoumei.cn/Article/details/gt2upsnukxv.html

[K07] 进制转换
来源：http://dali.snrcjt.cn/Article/details/gt2gvrjlnmx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gt2pdfqcjyh.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wadoshaf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gt2nqypwlic.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gt2ltmcwasn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gt2motwtrdf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hysaishi.cn/Article/details/gt2fitfylwi.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.andypj.xyz/Article/details/gt2xjbylrql.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gt2ipcoqtgw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shzxlz.cn/Article/details/gt2lxgkvlvh.html

Py:   pickle.dumps(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2eunccneb.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zycfv.cn/Article/details/gt2gpvuufct.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cdnleiting.top/Article/details/gt2kepzoyqt.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sxryk.cn/Article/details/gt2vgijswnw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.0kj1m.cn/Article/details/gt2rcxullvr.html

Go:   encoding/gob
来源：http://dali.svipenyu.cn/Article/details/gt2fhpviuhe.html

Ruby: Marshal.dump(obj)
来源：http://dali.xinyue.icu/Article/details/gt2ezrvoeot.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.kuanghao11.cn/Article/details/gt2qpkrhaah.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2prmxutbi.html

L. 网络请求
来源：http://dali.hywenlv.cn/Article/details/gt2kwqzmndb.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2xgkpeoxr.html

[L01] 发送 GET 请求
来源：http://dali.haohaochexian.top/Article/details/gt2luogatkj.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.c1oappe.top/Article/details/gt2bzyjwbxa.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gotoacloud.top/Article/details/gt2xtbbwmun.html

JS:   await fetch(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2knycbtmy.html

TS:   await fetch(url)
来源：http://dali.snrcjt.cn/Article/details/gt2cbpwkmhe.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sysykeji.top/Article/details/gt2xnnxvxbb.html

Go:   resp, err := http.Get(url)
来源：http://dali.sweek.top/Article/details/gt2wsebcdrw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.tianlin.xyz/Article/details/gt2fumjqrxy.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hywenlv.cn/Article/details/gt2irmjrghw.html

[L02] 发送 POST JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ayxgxeye.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hnxiangtu.top/Article/details/gt2xbhecbav.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yvedp.cn/Article/details/gt2gtjmqgtq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenzaomai.com/Article/details/gt2sikixqnr.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fengsongda.top/Article/details/gt2wvkkcnxk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.vqdsnc.cn/Article/details/gt2elkrthsm.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.smart0.xyz/Article/details/gt2ssusoznc.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.haohaochexian.top/Article/details/gt2grarvaxn.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhongyouzk.top/Article/details/gt2eqtlxosd.html

[L03] 设置自定义请求头
来源：http://dali.gotoacloud.top/Article/details/gt2lrhfmtib.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.vqdsnc.cn/Article/details/gt2flhvasfq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2morrlmwu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhongyouzk.top/Article/details/gt2kqzhhraa.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ybcxt.top/Article/details/gt2qhkasoqt.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.haohaochexian.top/Article/details/gt2cqfpajac.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhiwuduotai.top/Article/details/gt2cowvncct.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.kuanghao11.cn/Article/details/gt2zmcckrhd.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kddgkmil.html

[L04] 设置超时
来源：http://dali.xinyue.icu/Article/details/gt2vlmoeczr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.sxryk.cn/Article/details/gt2szdkdfxj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zycfv.cn/Article/details/gt2bucruvei.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xziqi.cn/Article/details/gt2lmdwrgvp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuetiantiany.cn/Article/details/gt2sgzrfpld.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hywenlv.cn/Article/details/gt2qjevizzs.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.aizwys.cn/Article/details/gt2enmtyydq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ehwqpu.com/Article/details/gt2ggnobrim.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.meibo888.top/Article/details/gt2lizmveld.html

[L05] 上传文件（multipart）
来源：http://dali.0kj1m.cn/Article/details/gt2wkkrddgm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sysykeji.top/Article/details/gt2zdqblszr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhongyouzk.top/Article/details/gt2yzhalepj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hfyvlgsh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hysaishi.cn/Article/details/gt2coocsaoh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jqgufenzy.top/Article/details/gt2hhmcqlar.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oqosoedy.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hammf.cn/Article/details/gt2rhhttiao.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gt2ludciqcq.html

[L06] 解析响应为 JSON
来源：http://dali.gogol.net.cn/Article/details/gt2aumboaag.html

Py:   resp.json()
来源：http://dali.zhoulong.xyz/Article/details/gt2dezkobjr.html

PHP:  json_decode($body, true);
来源：http://dali.hongshengwenyu.top/Article/details/gt2kcxhqdtq.html

JS:   await resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gt2wwtgiivt.html

TS:   await resp.json()
来源：http://dali.jqgufenzy.top/Article/details/gt2aonohnky.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cqqwz.cn/Article/details/gt2xnydcqgz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.dianchejie.cn/Article/details/gt2gdqapdyr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhongyouzk.top/Article/details/gt2lpqatcoi.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hywenlv.cn/Article/details/gt2qqhobdtv.html

[L07] 处理 HTTP 状态码
来源：http://dali.9152youxi.cn/Article/details/gt2xmtkrciz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.havefunace.top/Article/details/gt2lovnlvlp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jiagoushi.top/Article/details/gt2rrtokmpi.html

JS:   resp.ok;  resp.status
来源：http://dali.hywenlv.cn/Article/details/gt2didgjqir.html

TS:   resp.ok;  resp.status
来源：http://dali.chenzaomai.com/Article/details/gt2ypvnrwzo.html

Java: resp.statusCode()
来源：http://dali.0kj1m.cn/Article/details/gt2vodjqazb.html

Go:   resp.StatusCode
来源：http://dali.zhengqikj.top/Article/details/gt2porojvoz.html

Ruby: resp.code.to_i
来源：http://dali.pengpengdd.cyou/Article/details/gt2sjlwocee.html

C#:   (int)resp.StatusCode
来源：http://dali.jlsjyb.cn/Article/details/gt2vnmauriy.html

[L08] 并发请求多个地址
来源：http://dali.xziqi.cn/Article/details/gt2ahcydihs.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.snrcjt.cn/Article/details/gt2znpwunlt.html

PHP:  curl_multi_init() 系列
来源：http://dali.hnxiangtu.top/Article/details/gt2uibayemv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tianlin.xyz/Article/details/gt2jxaydfpx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jlsjyb.cn/Article/details/gt2qiijllyj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shuidangran.top/Article/details/gt2rtpydeqw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sysykeji.top/Article/details/gt2pncprcjg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shuidangran.top/Article/details/gt2vigefuqq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yonumen.top/Article/details/gt2mntvygds.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2bgwujeyn.html

M. 命令行 / 进程 / 环境
来源：http://dali.hysaishi.cn/Article/details/gt2smxjgnfs.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2vkydquln.html

[M01] 读取命令行参数
来源：http://dali.c1oappe.top/Article/details/gt2csyymmir.html

Py:   sys.argv[1:]
来源：http://dali.hongshengwenyu.top/Article/details/gt2rqrqufyp.html

PHP:  $argv;  $argc;
来源：http://dali.zdqjudy.top/Article/details/gt2vkwwjitm.html

JS:   process.argv.slice(2)
来源：http://dali.cucudq.cn/Article/details/gt2nsvkouvd.html

TS:   process.argv.slice(2)
来源：http://dali.hysaishi.cn/Article/details/gt2xidqnhat.html

Java: args 数组（main 方法参数）
来源：http://dali.birdmap.top/Article/details/gt2lgenagbx.html

Go:   os.Args[1:]
来源：http://dali.iojbl.cn/Article/details/gt2oaksthkj.html

Ruby: ARGV
来源：http://dali.hysaishi.cn/Article/details/gt2jgjgkniq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.feifeiyinyue.top/Article/details/gt2rwfxeyxf.html

[M02] 读取环境变量
来源：http://dali.iojbl.cn/Article/details/gt2dgwgdymw.html

Py:   os.environ.get("HOME")
来源：http://dali.cashguo.top/Article/details/gt2jbxllxzf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cucudq.cn/Article/details/gt2cscqmbzb.html

JS:   process.env.HOME
来源：http://dali.zhongyouzk.top/Article/details/gt2dzryqpsp.html

TS:   process.env.HOME
来源：http://dali.bjfxy.top/Article/details/gt2lnofrmfe.html

Java: System.getenv("HOME")
来源：http://dali.hywenlv.cn/Article/details/gt2jqincrnf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cashguo.top/Article/details/gt2eglzuvjq.html

Ruby: ENV["HOME"]
来源：http://dali.daxiang520.top/Article/details/gt2mmbrvovo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xinyue.icu/Article/details/gt2clhbjefg.html

[M03] 执行外部命令
来源：http://dali.gogol.net.cn/Article/details/gt2fjjibqff.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.wangdashe.top/Article/details/gt2thjqzdrm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zdqjudy.top/Article/details/gt2caymbetb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shzxlz.cn/Article/details/gt2uvblwcom.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.feifeiyinyue.top/Article/details/gt2baumfzrr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.pycfn.com/Article/details/gt2wdkzqhhm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yuxming.cn/Article/details/gt2dmkeangt.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2srioudvz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shangyingyoupin.top/Article/details/gt2vnxxmmhq.html

[M04] 获取当前工作目录
来源：http://dali.ivvv.top/Article/details/gt2qxnqrjqv.html

Py:   os.getcwd()
来源：http://dali.chenzaomai.com/Article/details/gt2ipnaxewl.html

PHP:  getcwd();
来源：http://dali.zhixingplan.top/Article/details/gt2bwhnasum.html

JS:   process.cwd()
来源：http://dali.hongshengwenyu.top/Article/details/gt2tszatvsx.html

TS:   process.cwd()
来源：http://dali.aizwys.cn/Article/details/gt2saiqynqz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xylfe.cn/Article/details/gt2jbfbegmy.html

Go:   os.Getwd()
来源：http://dali.haohaochexian.top/Article/details/gt2rnlbemgc.html

Ruby: Dir.pwd
来源：http://dali.gzhubu.top/Article/details/gt2efbqiikm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.aizwys.cn/Article/details/gt2kswgjkvn.html

[M05] 设置退出码
来源：http://dali.gzhubu.top/Article/details/gt2qevcasvb.html

Py:   sys.exit(1)
来源：http://dali.andypj.xyz/Article/details/gt2rrljlxxz.html

PHP:  exit(1);
来源：http://dali.chenlongwang.top/Article/details/gt2spjonclj.html

JS:   process.exit(1)
来源：http://dali.xziqi.cn/Article/details/gt2eqaozrrn.html

TS:   process.exit(1)
来源：http://dali.iojbl.cn/Article/details/gt2goybsbjx.html

Java: System.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2gazokysx.html

Go:   os.Exit(1)
来源：http://dali.zhixingplan.top/Article/details/gt2dwcdywou.html

Ruby: exit 1
来源：http://dali.sweek.top/Article/details/gt2qdfxexyu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jmuxwyhi.html

[M06] 向标准错误输出
来源：http://dali.mhx1999.top/Article/details/gt2zhbfbnvi.html

Py:   print("err", file=sys.stderr)
来源：http://dali.wangdashe.top/Article/details/gt2rvvkwnqo.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.dashuyun.cn/Article/details/gt2vrvfvlil.html

JS:   console.error("err")
来源：http://dali.jiagoushi.top/Article/details/gt2puguxzus.html

TS:   console.error("err")
来源：http://dali.ppjwa.cn/Article/details/gt2gnlelxnb.html

Java: System.err.println("err")
来源：http://dali.smart0.xyz/Article/details/gt2zsripvft.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2urfbnonv.html

Ruby: warn "err"
来源：http://dali.zhongyouzk.top/Article/details/gt2gxjirqjq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sysykeji.top/Article/details/gt2pbzyshwj.html

[M07] 判断是否为主入口
来源：http://dali.dianchejie.cn/Article/details/gt2prwneudv.html

Py:   if __name__ == "__main__":
来源：http://dali.zdqjudy.top/Article/details/gt2pqxfuilv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.havefunace.top/Article/details/gt2ecnvsuja.html

JS:   require.main === module
来源：http://dali.jiagoushi.top/Article/details/gt2cxdidtqv.html

TS:   require.main === module
来源：http://dali.nanxinkj.top/Article/details/gt2zzkqvbmx.html

Java: public static void main(String[] args)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ycnawxeu.html

Go:   func main()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lvqbzatc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hnxiangtu.top/Article/details/gt2oevlduko.html

C#:   static void Main(string[] args)
来源：http://dali.yonumen.top/Article/details/gt2uuyidisi.html

[M08] 获取系统与运行时信息
来源：http://dali.tianlin.xyz/Article/details/gt2tysmmpoa.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jiagoushi.top/Article/details/gt2cjhesjzz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xziqi.cn/Article/details/gt2noankzwg.html

JS:   process.platform;  process.version
来源：http://dali.yj20258888.top/Article/details/gt2oixizzym.html

TS:   process.platform;  process.version
来源：http://dali.shuidangran.top/Article/details/gt2lvchuwtf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yj202588.top/Article/details/gt2arcckpwa.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yangfankeji.com/Article/details/gt2amnkuzyj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sufxvd.cn/Article/details/gt2killjskk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cashguo.top/Article/details/gt2abyhdueo.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2hrrxkwrj.html

N. 数据结构与算法
来源：http://dali.yj20258.top/Article/details/gt2akgozimg.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2gmzeoqrn.html

[N01] 二分查找（有序数组）
来源：http://dali.bjfxy.top/Article/details/gt2bmncdcsn.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gt2xqnmkori.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.redwolf501.top/Article/details/gt2uteyvrlk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.svipenyu.cn/Article/details/gt2mijnysvl.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.kuanghao11.cn/Article/details/gt2mcjlztdl.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ydsgtugs.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gt2bffwdnhm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhoulong.xyz/Article/details/gt2hfdmauhg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lomktlvt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hongshengwenyu.top/Article/details/gt2bnmcgemf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gzhubu.top/Article/details/gt2vynwsmkg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yangfankeji.com/Article/details/gt2hkfrrrqe.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cdnleiting.top/Article/details/gt2srjgdcrc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.0kj1m.cn/Article/details/gt2gwxgtfqn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sweek.top/Article/details/gt2fgwoqncd.html

Go:   slices.Sort(arr)
来源：http://dali.yj202588.top/Article/details/gt2lmsxqurw.html

Ruby: arr.sort
来源：http://dali.zycfv.cn/Article/details/gt2webcuhjx.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.dianchejie.cn/Article/details/gt2lpxveuzl.html

[N03] 快速排序（分治示例）
来源：http://dali.fzhhl.top/Article/details/gt2wvmvfwnm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhiwuduotai.top/Article/details/gt2baizpegb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.c1oappe.top/Article/details/gt2dkkubdlt.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jlsjyb.cn/Article/details/gt2kizhybxe.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shzxlz.cn/Article/details/gt2pgpxrgoi.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.pycfn.com/Article/details/gt2mfvlplfi.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jqgfzy.top/Article/details/gt2uffcgrem.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.haohaochexian.top/Article/details/gt2dodkvuoe.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinqigufen.top/Article/details/gt2svvwumfc.html

[N04] 斐波那契数列
来源：http://dali.jiagoushi.top/Article/details/gt2jcnrfajo.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xziqi.cn/Article/details/gt2fzatkdco.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2uomymsgj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pengpengdd.cyou/Article/details/gt2wzguhqsh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangdashe.top/Article/details/gt2gvxtabdz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yj20258.top/Article/details/gt2vnspviqq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.9152youxi.cn/Article/details/gt2shpgcqkn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2gnrxkkoh.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cashguo.top/Article/details/gt2eqnkkzge.html

[N05] 最大公约数
来源：http://dali.sxryk.cn/Article/details/gt2vjthiziq.html

Py:   math.gcd(a, b)
来源：http://dali.sweek.top/Article/details/gt2gzeahbfd.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zycfv.cn/Article/details/gt2tkfrvygk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.iojbl.cn/Article/details/gt2xgooqljz.html


<!-- 参考信息 -->