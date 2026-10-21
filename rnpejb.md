代发 wailian999

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yanxiufei.cn/Article/details/gtjiznixpi.html

Go:   end.Sub(start).Hours()
来源：http://dali.feifeiyinyue.top/Article/details/gtqzebtgsa.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cashguo.top/Article/details/gtpnvmqxaj.html

C#:   (end - start).TotalSeconds
来源：http://dali.wangshuangyany.cn/Article/details/gtdtmubhcx.html

[J07] 比较两个日期
来源：http://dali.chenlongwang.top/Article/details/gtxzbwyavu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gtsfaoezsb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.wangdashe.top/Article/details/gtdkqafevx.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ivvv.top/Article/details/gtvpkaotnw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangtech.top/Article/details/gtdcuzofqi.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yongpay.top/Article/details/gtpgvbdzeq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.guowangkeji.top/Article/details/gtiiviouab.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.wangshuangyany.cn/Article/details/gtpsvsyhnx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.nanxinkj.top/Article/details/gttvzmfbzx.html

[J08] 提取年月日与星期
来源：http://dali.316326.xyz/Article/details/gtnchmfgli.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.pycfn.com/Article/details/gtyucmvwvy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gzhubu.top/Article/details/gtqqcamjbj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.tianlin.xyz/Article/details/gtnlmoqmbh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinqigufen.top/Article/details/gtitesumfe.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtghjgcahx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hysaishi.cn/Article/details/gtheacesea.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ppjwa.cn/Article/details/gtbjwlndkr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gaohongyu789.top/Article/details/gtbctamunq.html

[J09] 时区处理
来源：http://dali.jqgfzy.top/Article/details/gtjzkeiwqk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yangfankeji.com/Article/details/gtnncubujo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.nwbrower.top/Article/details/gtjvakqdhl.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.quarkkingdee.top/Article/details/gtnbbvdinq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.9152youxi.cn/Article/details/gtprbtgmzh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.bjfxy.top/Article/details/gtnxvdiked.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj202588.top/Article/details/gtxkhzqdcg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.wangdashe.top/Article/details/gtvpwcjjyn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yuanzhike.top/Article/details/gtmndfzvnk.html

[J10] 取今天 / 本月第一天
来源：http://dali.feifeiyinyue.top/Article/details/gtyhduojoy.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.c1oappe.top/Article/details/gthqobzicc.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hnxiangtu.top/Article/details/gtuzqpdojr.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwidrqzxm.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zycfv.cn/Article/details/gtcaggjaag.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlxvqwegx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xuetiantiany.cn/Article/details/gtuxhflgfu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.fengsongda.top/Article/details/gtwyfojzrk.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sweek.top/Article/details/gtsjuesgrr.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtwywhezwg.html

K. JSON 与序列化
来源：http://dali.yueranfly.top/Article/details/gttixjfcrd.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtuiaaivyc.html

[K01] 对象转 JSON 字符串
来源：http://dali.shzxlz.cn/Article/details/gtfurupsdl.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.guowangkeji.top/Article/details/gtnlljuibm.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gzhubu.top/Article/details/gtszghxayx.html

JS:   JSON.stringify(obj)
来源：http://dali.iojbl.cn/Article/details/gtjjchemnd.html

TS:   JSON.stringify(obj)
来源：http://dali.yongpay.top/Article/details/gtequleaxv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jianghu66.top/Article/details/gtauxnqirz.html

Go:   json.Marshal(obj)
来源：http://dali.xuanzx.com/Article/details/gtcbyadhhd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shzxlz.cn/Article/details/gtkeiundwn.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xinyue.icu/Article/details/gtnvdguirx.html

[K02] JSON 字符串转对象
来源：http://dali.zhijiandao.cn/Article/details/gtjlmuuebx.html

Py:   json.loads(s)
来源：http://dali.jqgfzy.top/Article/details/gtzyucfcvn.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tanke756.top/Article/details/gtxbipweqt.html

JS:   JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gtqglpfirn.html

TS:   JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gtagnsqcru.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.wangshuangyany.cn/Article/details/gtqudgmxgr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sufxvd.cn/Article/details/gtjzircvnu.html

Ruby: JSON.parse(s)
来源：http://dali.mhx1999.top/Article/details/gtoyvrgidl.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cheryme.top/Article/details/gtweoiqzwt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cheryme.top/Article/details/gtxnxjrkcm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhongyouzk.top/Article/details/gtdnijmytv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hysaishi.cn/Article/details/gtdubacqwm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnqzz.top/Article/details/gtugbvwmum.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gtbidtokkw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yangfankeji.com/Article/details/gtfianehzx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.vqdsnc.cn/Article/details/gthtrhgqmu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cashguo.top/Article/details/gtfeemzqci.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.redwolf501.top/Article/details/gtbasidwwd.html

[K04] 读取 JSON 文件
来源：http://dali.jiagoushi.top/Article/details/gtitxfmfds.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.guowangkeji.top/Article/details/gtzdacarss.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sxryk.cn/Article/details/gtcrwwbkzx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ivvv.top/Article/details/gtyqmuhrmb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.316326.xyz/Article/details/gtoaxdofrc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.c1oappe.top/Article/details/gtkunnpvie.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.316326.xyz/Article/details/gtkmwvexzo.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xinyue.icu/Article/details/gtcuikorqm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.316326.xyz/Article/details/gtpzkqlnom.html

[K05] 深拷贝对象
来源：http://dali.hfpthk.cn/Article/details/gtooxentyo.html

Py:   copy.deepcopy(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtrntivxvr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.birdmap.top/Article/details/gttnjjbpqu.html

JS:   structuredClone(obj)
来源：http://dali.daxiang520.top/Article/details/gtpgohferu.html

TS:   structuredClone(obj)
来源：http://dali.gotoacloud.top/Article/details/gtnbwpbila.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.pengpengdd.cyou/Article/details/gtunekwmgy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.9152youxi.cn/Article/details/gtcygqylfd.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hammf.cn/Article/details/gtgzrhtegy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.feifeiyinyue.top/Article/details/gtfqrrzxks.html

[K06] 解析 URL 查询串
来源：http://dali.zhongyouzk.top/Article/details/gtlotxdkgu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hnxiangtu.top/Article/details/gtiragkzxe.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.wangdashe.top/Article/details/gtosxlskji.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ydzc1.top/Article/details/gtcswamlmd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.fzhhl.top/Article/details/gtkejowwwq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gaohongyu789.top/Article/details/gtthpnqrum.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gtyoflvsfi.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gtqwgzjpjf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gtrhskrtoh.html

[K07] 进制转换
来源：http://dali.zdqjudy.top/Article/details/gtronzuxby.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gtsnamivxs.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xinyue.icu/Article/details/gtslqeczmr.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmbftvwno.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gtlokygsbh.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gtqrrzzapz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zycfv.cn/Article/details/gtolynokit.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.aizwys.cn/Article/details/gtsoehpwfq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.birdmap.top/Article/details/gtjqlgqpph.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.quarkkingdee.top/Article/details/gtmhqmrsck.html

Py:   pickle.dumps(obj)
来源：http://dali.guannengcc.top/Article/details/gtbdueovjb.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhongyouzk.top/Article/details/gtvjzxnyks.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yonumen.top/Article/details/gtjbwjbyrl.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.chenzaomai.com/Article/details/gtfvklactx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hysaishi.cn/Article/details/gtftnfgrnc.html

Go:   encoding/gob
来源：http://dali.hywenlv.cn/Article/details/gtvmsfxpdd.html

Ruby: Marshal.dump(obj)
来源：http://dali.aizwys.cn/Article/details/gtxztblcie.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.pengpengdd.cyou/Article/details/gtirfvpfal.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtcdzthbqn.html

L. 网络请求
来源：http://dali.meibo888.top/Article/details/gtiidmzvzc.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtzjyjclrn.html

[L01] 发送 GET 请求
来源：http://dali.ehwqpu.com/Article/details/gtyiruntdy.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yangfankeji.com/Article/details/gtmhxdiisb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hongshengwenyu.top/Article/details/gtwkruasbc.html

JS:   await fetch(url)
来源：http://dali.hysaishi.cn/Article/details/gtpyehurzk.html

TS:   await fetch(url)
来源：http://dali.yj20258888.top/Article/details/gtyqcpymux.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yj202588.top/Article/details/gtvyshgbjs.html

Go:   resp, err := http.Get(url)
来源：http://dali.cashguo.top/Article/details/gtrrpprbki.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zdqjudy.top/Article/details/gtezndswxs.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.wangshuangyany.cn/Article/details/gtpwjzomwb.html

[L02] 发送 POST JSON
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgewexkqq.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.haohaochexian.top/Article/details/gtlynlkjad.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.nanxinkj.top/Article/details/gtbfnvokcn.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjwbmzhyl.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgfzy.top/Article/details/gtxaekvucu.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.0kj1m.cn/Article/details/gtvpzhzpvu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.kuanghao11.cn/Article/details/gtkpxjjpnc.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.chenzaomai.com/Article/details/gtbskzbmvr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yanxiufei.cn/Article/details/gtbanqjaze.html

[L03] 设置自定义请求头
来源：http://dali.jqgufenzy.top/Article/details/gthwkoxkwh.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xziqi.cn/Article/details/gtarqtuuat.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtezevgizq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aizwys.cn/Article/details/gtolczumnj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hysaishi.cn/Article/details/gtwttkkrkj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.316326.xyz/Article/details/gtstmynuip.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbmggbmhh.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jianghu66.top/Article/details/gtpwgrohrl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.pengpengdd.cyou/Article/details/gtakyitjsu.html

[L04] 设置超时
来源：http://dali.zhoulong.xyz/Article/details/gtnxgsepbx.html

Py:   requests.get(url, timeout=5)
来源：http://dali.feifeiyinyue.top/Article/details/gtzwywuhuf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.kuanghao11.cn/Article/details/gtyakgbkvk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daxiang520.top/Article/details/gtkokmljkg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.smart0.xyz/Article/details/gtukkycnpy.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.havefunace.top/Article/details/gtjolfaeqf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hywenlv.cn/Article/details/gtmabuyjoo.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.tanke756.top/Article/details/gttyijzjxr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.316326.xyz/Article/details/gtlukybwcq.html

[L05] 上传文件（multipart）
来源：http://dali.hysaishi.cn/Article/details/gtzfmwhctj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hysaishi.cn/Article/details/gttqdompng.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.mhx1999.top/Article/details/gtjueqyiki.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmuduuxsa.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.guannengcc.top/Article/details/gtauljwttv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.0kj1m.cn/Article/details/gtboesxxgo.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gzhubu.top/Article/details/gtpmaanzgn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hnqzz.top/Article/details/gtjnbcrxvv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtbhlobcmy.html

[L06] 解析响应为 JSON
来源：http://dali.iojbl.cn/Article/details/gtjjftdfiq.html

Py:   resp.json()
来源：http://dali.tianlin.xyz/Article/details/gtvtscyumn.html

PHP:  json_decode($body, true);
来源：http://dali.aibaodan.cn/Article/details/gtlfnzwncq.html

JS:   await resp.json()
来源：http://dali.zhiwuduotai.top/Article/details/gthzktmuxf.html

TS:   await resp.json()
来源：http://dali.sysykeji.top/Article/details/gtbrrravih.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cashguo.top/Article/details/gtjqlkvona.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hongshengwenyu.top/Article/details/gtfqlkbkds.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sxryk.cn/Article/details/gtfpbhfreq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.bjfxy.top/Article/details/gtedhhpqzr.html

[L07] 处理 HTTP 状态码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjucdnpqx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gtpmhbxlmo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gtbjxuhkgc.html

JS:   resp.ok;  resp.status
来源：http://dali.gogol.net.cn/Article/details/gtiwyczvij.html

TS:   resp.ok;  resp.status
来源：http://dali.yangfankeji.com/Article/details/gtrojxxhth.html

Java: resp.statusCode()
来源：http://dali.zhixingplan.top/Article/details/gtdtubaqzu.html

Go:   resp.StatusCode
来源：http://dali.c1oappe.top/Article/details/gtxogudymq.html

Ruby: resp.code.to_i
来源：http://dali.shanyushiyangtech.top/Article/details/gtykmbwhrb.html

C#:   (int)resp.StatusCode
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnbhpoolw.html

[L08] 并发请求多个地址
来源：http://dali.yongpay.top/Article/details/gtmhoromky.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.nanxuanxn.top/Article/details/gtfalvuqum.html

PHP:  curl_multi_init() 系列
来源：http://dali.tian-w.cn/Article/details/gtbhqsymhq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xinyue.icu/Article/details/gtgnpthbgy.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuxming.cn/Article/details/gtsrbytglj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.dashuyun.cn/Article/details/gtbjutlriv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.aibaodan.cn/Article/details/gtdgwwzurg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhengqikj.top/Article/details/gtaeztdcum.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yj202588.top/Article/details/gtbzcgxtbt.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtmgetgjlj.html

M. 命令行 / 进程 / 环境
来源：http://dali.guowangkeji.top/Article/details/gtpkqwasjx.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtspprsdrc.html

[M01] 读取命令行参数
来源：http://dali.hnxiangtu.top/Article/details/gtzxghzqcu.html

Py:   sys.argv[1:]
来源：http://dali.gaohongyu789.top/Article/details/gthpkddvyt.html

PHP:  $argv;  $argc;
来源：http://dali.yongpay.top/Article/details/gtoldhqlki.html

JS:   process.argv.slice(2)
来源：http://dali.0kj1m.cn/Article/details/gtbrggkgaz.html

TS:   process.argv.slice(2)
来源：http://dali.9152youxi.cn/Article/details/gtapbrroqu.html

Java: args 数组（main 方法参数）
来源：http://dali.dashuyun.cn/Article/details/gtadmjehxl.html

Go:   os.Args[1:]
来源：http://dali.havefunace.top/Article/details/gtarqunewh.html

Ruby: ARGV
来源：http://dali.pycfn.com/Article/details/gtpbreharl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shanyushiyangtech.top/Article/details/gtzxcrmcbb.html

[M02] 读取环境变量
来源：http://dali.pycfn.com/Article/details/gtavtsjuzd.html

Py:   os.environ.get("HOME")
来源：http://dali.guannengcc.top/Article/details/gtmwzkkhuk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sxryk.cn/Article/details/gtqdxxouin.html

JS:   process.env.HOME
来源：http://dali.316326.xyz/Article/details/gtnflvajoa.html

TS:   process.env.HOME
来源：http://dali.shanyushiyangtech.top/Article/details/gtmvewixdh.html

Java: System.getenv("HOME")
来源：http://dali.zycfv.cn/Article/details/gtzouymmpu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hnqzz.top/Article/details/gtaxrxbyul.html

Ruby: ENV["HOME"]
来源：http://dali.sysykeji.top/Article/details/gtugzkrtdy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gtczlknoij.html

[M03] 执行外部命令
来源：http://dali.c1oappe.top/Article/details/gtnuskhapw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.meibo888.top/Article/details/gtabbowpox.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shanyushiyangtech.top/Article/details/gtesoiwans.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jlsjyb.cn/Article/details/gtbbgviqbv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shuidangran.top/Article/details/gtgglrpduf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shzxlz.cn/Article/details/gtrdqbogod.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.c1oappe.top/Article/details/gtdwyvoght.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yanxiufei.cn/Article/details/gthyfkrjoy.html

C#:   Process.Start("ls", "-l");
来源：http://dali.snrcjt.cn/Article/details/gtwqfpeuth.html

[M04] 获取当前工作目录
来源：http://dali.aibaodan.cn/Article/details/gtpgofzxmg.html

Py:   os.getcwd()
来源：http://dali.ehwqpu.com/Article/details/gthebxacwx.html

PHP:  getcwd();
来源：http://dali.hysaishi.cn/Article/details/gtqdwpzzyw.html

JS:   process.cwd()
来源：http://dali.316326.xyz/Article/details/gtdbnbqpih.html

TS:   process.cwd()
来源：http://dali.cheryme.top/Article/details/gtgqgkupdk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhengqikj.top/Article/details/gtwkcepwhy.html

Go:   os.Getwd()
来源：http://dali.xuanzx.com/Article/details/gtiyyexalv.html

Ruby: Dir.pwd
来源：http://dali.shuidangran.top/Article/details/gtcpjyorzk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hongshengwenyu.top/Article/details/gtgslsfvls.html

[M05] 设置退出码
来源：http://dali.vqdsnc.cn/Article/details/gtimbozwcp.html

Py:   sys.exit(1)
来源：http://dali.wangdashe.top/Article/details/gtfkehuvcb.html

PHP:  exit(1);
来源：http://dali.aibaodan.cn/Article/details/gtsrmlenla.html

JS:   process.exit(1)
来源：http://dali.yj20258.top/Article/details/gtbhyxglfp.html

TS:   process.exit(1)
来源：http://dali.daxiang520.top/Article/details/gtjiazkgtm.html

Java: System.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gtmopnrdjg.html

Go:   os.Exit(1)
来源：http://dali.hfpthk.cn/Article/details/gtlhbxtmue.html

Ruby: exit 1
来源：http://dali.fzhhl.top/Article/details/gtzavxviel.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.nanxinkj.top/Article/details/gtnrvhrqol.html

[M06] 向标准错误输出
来源：http://dali.yueranfly.top/Article/details/gtnkdgiiav.html

Py:   print("err", file=sys.stderr)
来源：http://dali.redwolf501.top/Article/details/gtlcpgwrrb.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtepxohqkc.html

JS:   console.error("err")
来源：http://dali.nanxuanxn.top/Article/details/gtqzqjzchg.html

TS:   console.error("err")
来源：http://dali.yueranfly.top/Article/details/gtsxqmoqlf.html

Java: System.err.println("err")
来源：http://dali.yj20258888.top/Article/details/gtsopegycz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.c1oappe.top/Article/details/gturcwllqa.html

Ruby: warn "err"
来源：http://dali.hysaishi.cn/Article/details/gtbxntabdb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.feifeiyinyue.top/Article/details/gtovxkejma.html

[M07] 判断是否为主入口
来源：http://dali.cucudq.cn/Article/details/gtpnowwcit.html

Py:   if __name__ == "__main__":
来源：http://dali.shuidangran.top/Article/details/gtxsupspsk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.redwolf501.top/Article/details/gtplthaksz.html

JS:   require.main === module
来源：http://dali.cashguo.top/Article/details/gtlzshbymd.html

TS:   require.main === module
来源：http://dali.tianlin.xyz/Article/details/gtkrsmigxl.html

Java: public static void main(String[] args)
来源：http://dali.shuidangran.top/Article/details/gtgpusfmwz.html

Go:   func main()
来源：http://dali.redwolf501.top/Article/details/gtgosayzdd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cqqwz.cn/Article/details/gtzslkkopj.html

C#:   static void Main(string[] args)
来源：http://dali.birdmap.top/Article/details/gtvkpykzcn.html

[M08] 获取系统与运行时信息
来源：http://dali.xuanzx.com/Article/details/gtojvwrwmt.html

Py:   platform.system();  platform.python_version()
来源：http://dali.nanxuanxn.top/Article/details/gtspgaaojb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hnqzz.top/Article/details/gtmtkklttw.html

JS:   process.platform;  process.version
来源：http://dali.cqqwz.cn/Article/details/gtehousbhx.html

TS:   process.platform;  process.version
来源：http://dali.jinghuilouyu.cn/Article/details/gtqlxznrsw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cheryme.top/Article/details/gtdpmxjrsj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtamvhdxkd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbgktnowd.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ehwqpu.com/Article/details/gtnjhjuhco.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtnxyjmkuq.html

N. 数据结构与算法
来源：http://dali.meibo888.top/Article/details/gtuyyrcnab.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtawehhryw.html

[N01] 二分查找（有序数组）
来源：http://dali.pycfn.com/Article/details/gtmoktxkrb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gtsgmpghzj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ppjwa.cn/Article/details/gtxjvvvify.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xylfe.cn/Article/details/gthpzjhjfx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.9152youxi.cn/Article/details/gtzqlioexr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtufuruhwc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gtslvglpoc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.dianchejie.cn/Article/details/gtmkozfmho.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtqbwregzo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.wangdashe.top/Article/details/gtfrvqrtvd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnqzz.top/Article/details/gtibnfjsiy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cqqwz.cn/Article/details/gtqwbheypy.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jiagoushi.top/Article/details/gtmnyahigi.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yongpay.top/Article/details/gtvxvmefsg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jqgfzy.top/Article/details/gtbobohqbd.html

Go:   slices.Sort(arr)
来源：http://dali.ivvv.top/Article/details/gtjxtkrxen.html

Ruby: arr.sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gteivazcbg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.havefunace.top/Article/details/gttefotwwe.html

[N03] 快速排序（分治示例）
来源：http://dali.yuxming.cn/Article/details/gtnhingyqk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.wangshuangyany.cn/Article/details/gtfpajwiip.html

PHP:  // 递归实现，或用 usort
来源：http://dali.wangdashe.top/Article/details/gtdgosbmdi.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sysykeji.top/Article/details/gtsjltnzkk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258888.top/Article/details/gttwedtrmo.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yueranfly.top/Article/details/gtqqpsfisp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj20258.top/Article/details/gthglfntsa.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.haohaochexian.top/Article/details/gtvxwnmivr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.smart0.xyz/Article/details/gttpdaalsk.html

[N04] 斐波那契数列
来源：http://dali.cashguo.top/Article/details/gtovsobuiu.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jyoumei.cn/Article/details/gtctstadtu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yj202588.top/Article/details/gtvqurvuth.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pycfn.com/Article/details/gtmmhdjkyo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yvedp.cn/Article/details/gtzgcpuqrw.html


<!-- 参考信息 -->