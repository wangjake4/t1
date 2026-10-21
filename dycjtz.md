代发 wailian999

Py:   (end - start).total_seconds()
来源：http://dali.zhijiandao.cn/Article/details/gtfmxekuko.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnhfwbacv.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.9152youxi.cn/Article/details/gteqrectzn.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shangyingyoupin.top/Article/details/gttqnbiizw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqhtgsjoy.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinqigufen.top/Article/details/gtcypexrah.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zdqjudy.top/Article/details/gtwnpjzfyh.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenzaomai.com/Article/details/gtobfrzhow.html

[J07] 比较两个日期
来源：http://dali.jiagoushi.top/Article/details/gtshcuspiy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.316326.xyz/Article/details/gtdvnhkuzb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.tanke756.top/Article/details/gtnruagzcm.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hysaishi.cn/Article/details/gtwwsvfxlx.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.pycfn.com/Article/details/gtyrphkbfo.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gotoacloud.top/Article/details/gtquqtvuyn.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hywenlv.cn/Article/details/gthpxigdiv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yj20258888.top/Article/details/gtznrinemj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gtvkfibulb.html

[J08] 提取年月日与星期
来源：http://dali.hnxiangtu.top/Article/details/gtimxebvak.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.wangdashe.top/Article/details/gtdqnuwadu.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yj202588.top/Article/details/gtjawqlero.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.aizwys.cn/Article/details/gtjmlwqrss.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tian-w.cn/Article/details/gtefyfmbfh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhixingplan.top/Article/details/gtmzkyrxjm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gotoacloud.top/Article/details/gteyscougb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.aizwys.cn/Article/details/gtvnlposmr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yangfankeji.com/Article/details/gtasyxvyax.html

[J09] 时区处理
来源：http://dali.shangyingyoupin.top/Article/details/gtlmhlzlhf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.pycfn.com/Article/details/gtjigyaakh.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yuanzhike.top/Article/details/gtbpcjubmi.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.haohaochexian.top/Article/details/gtyzymbvis.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj202588.top/Article/details/gtrsthxzuz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jlsjyb.cn/Article/details/gtegksvvfw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.vqdsnc.cn/Article/details/gtsnsvaokk.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yj20258.top/Article/details/gtmqlfkasb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gaohongyu789.top/Article/details/gtidcswvtw.html

[J10] 取今天 / 本月第一天
来源：http://dali.dianchejie.cn/Article/details/gtttbilhns.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xuetiantiany.cn/Article/details/gtfkvfxlel.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shanyushiyangtech.top/Article/details/gtzevnzkxq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.vqdsnc.cn/Article/details/gtoihouuoc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yvedp.cn/Article/details/gtgrlsfcop.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.chenlongwang.top/Article/details/gtjxinrqos.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hnxiangtu.top/Article/details/gtywuzulsp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ydzc1.top/Article/details/gtyenlfler.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xziqi.cn/Article/details/gtxagwnkij.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtepexkrbz.html

K. JSON 与序列化
来源：http://dali.svipenyu.cn/Article/details/gtxgrjsuxs.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtjxqphyvc.html

[K01] 对象转 JSON 字符串
来源：http://dali.nanxinkj.top/Article/details/gtdqiflhix.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cashguo.top/Article/details/gthkyvcetn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.sxryk.cn/Article/details/gtwxddfkze.html

JS:   JSON.stringify(obj)
来源：http://dali.jqgfzy.top/Article/details/gtzaofvagz.html

TS:   JSON.stringify(obj)
来源：http://dali.9152youxi.cn/Article/details/gtzqbouqyy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqyxeyhfz.html

Go:   json.Marshal(obj)
来源：http://dali.ppjwa.cn/Article/details/gtboogstgl.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.feifeiyinyue.top/Article/details/gtonbzmqiz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtdxwthgwl.html

[K02] JSON 字符串转对象
来源：http://dali.hammf.cn/Article/details/gtwxmrolhc.html

Py:   json.loads(s)
来源：http://dali.feifeiyinyue.top/Article/details/gttsitkkci.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.316326.xyz/Article/details/gtjmffvgjs.html

JS:   JSON.parse(s)
来源：http://dali.gotoacloud.top/Article/details/gthmwaugih.html

TS:   JSON.parse(s)
来源：http://dali.cashguo.top/Article/details/gtvxprlhjg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hysaishi.cn/Article/details/gtqkhkivex.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yj202588.top/Article/details/gttskxgfot.html

Ruby: JSON.parse(s)
来源：http://dali.zhengqikj.top/Article/details/gthyirujff.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cdnleiting.top/Article/details/gtlmsogzrx.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xuetiantiany.cn/Article/details/gttkpnnpwi.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.vqdsnc.cn/Article/details/gtlykxtpne.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxnydpfup.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.316326.xyz/Article/details/gthtszxdwm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtscbwbdkk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.aizwys.cn/Article/details/gtaedpxmdh.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhixingplan.top/Article/details/gttbvfbvch.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.birdmap.top/Article/details/gttsywljvd.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.havefunace.top/Article/details/gthaqacqcy.html

[K04] 读取 JSON 文件
来源：http://dali.yongpay.top/Article/details/gttejhiygh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.vqdsnc.cn/Article/details/gtoepxrnud.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtunttgiyq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.smart0.xyz/Article/details/gtdlqxmrgr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xinyue.icu/Article/details/gtswnkjyny.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yuanzhike.top/Article/details/gtirrmdrsw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cdnleiting.top/Article/details/gtjvwtmrfy.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.316326.xyz/Article/details/gtsustjvip.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yongpay.top/Article/details/gtrsfrnsib.html

[K05] 深拷贝对象
来源：http://dali.nanxuanxn.top/Article/details/gtxkmnaxuq.html

Py:   copy.deepcopy(obj)
来源：http://dali.cashguo.top/Article/details/gtuhlauwph.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hywenlv.cn/Article/details/gttkfnfjhm.html

JS:   structuredClone(obj)
来源：http://dali.nanxinkj.top/Article/details/gtdfyqpowd.html

TS:   structuredClone(obj)
来源：http://dali.ydzc1.top/Article/details/gtkebwwqxg.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhongyouzk.top/Article/details/gthjwgenwo.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtirrkwpct.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.svipenyu.cn/Article/details/gtvbtmcsgo.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.iojbl.cn/Article/details/gthzdamvmm.html

[K06] 解析 URL 查询串
来源：http://dali.xuetiantiany.cn/Article/details/gtxrqatczw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.aizwys.cn/Article/details/gtrqttucac.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtuibuwtzf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daxiang520.top/Article/details/gtwvelffyy.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yanxiufei.cn/Article/details/gtlhhrjbmm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.0kj1m.cn/Article/details/gtpuvimesc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jqgfzy.top/Article/details/gtrfgudpnb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ppjwa.cn/Article/details/gthpxviegp.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gtubshjixt.html

[K07] 进制转换
来源：http://dali.cdnleiting.top/Article/details/gtdhuztici.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gthgiejopd.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jyoumei.cn/Article/details/gtpmhijhyq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gteltqhbfg.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtocjhxdgy.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gtrvpknfay.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.chenjidiqi.icu/Article/details/gtvwxcmhya.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinqigufen.top/Article/details/gtckpizuoq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrimtbdwi.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.chenzaomai.com/Article/details/gtkmenaqef.html

Py:   pickle.dumps(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtuvwngqaj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hammf.cn/Article/details/gtiwobgkzc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gaohongyu789.top/Article/details/gtukboatvh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.pycfn.com/Article/details/gtsddotcvz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xuetiantiany.cn/Article/details/gtnrauspwy.html

Go:   encoding/gob
来源：http://dali.guannengcc.top/Article/details/gtgwngpjbr.html

Ruby: Marshal.dump(obj)
来源：http://dali.redwolf501.top/Article/details/gtsvaodcsr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.aibaodan.cn/Article/details/gtiyrltxmr.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtbldpgssj.html

L. 网络请求
来源：http://dali.cashguo.top/Article/details/gtfpyuxvnq.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtqcjpttjt.html

[L01] 发送 GET 请求
来源：http://dali.zhixingplan.top/Article/details/gtktydpfmn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gtikyauavz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hnqzz.top/Article/details/gtcvitlmjv.html

JS:   await fetch(url)
来源：http://dali.c1oappe.top/Article/details/gthyhrdhrg.html

TS:   await fetch(url)
来源：http://dali.nanxuanxn.top/Article/details/gtqlbbjysx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.tianlin.xyz/Article/details/gtgmobpliq.html

Go:   resp, err := http.Get(url)
来源：http://dali.guowangkeji.top/Article/details/gtijvxtbdw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.bjfxy.top/Article/details/gtwohattnz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yuxming.cn/Article/details/gtznkajhsm.html

[L02] 发送 POST JSON
来源：http://dali.shuidangran.top/Article/details/gtmryabqzj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.smart0.xyz/Article/details/gtvmmgcsom.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yj20258888.top/Article/details/gtbsusrdqa.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangshuangyany.cn/Article/details/gtrnfloztz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hnxiangtu.top/Article/details/gtcldzojou.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yvedp.cn/Article/details/gtpawkguwi.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinqigufen.top/Article/details/gtavbvxerp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.pycfn.com/Article/details/gthtlsemnl.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.nwbrower.top/Article/details/gtsrgmlqow.html

[L03] 设置自定义请求头
来源：http://dali.yj20258.top/Article/details/gtkzdukoev.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yueranfly.top/Article/details/gtzidytvpn.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hywenlv.cn/Article/details/gtefwhnows.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gzhubu.top/Article/details/gtikudevle.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.iojbl.cn/Article/details/gtzihqhuxo.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.chenlongwang.top/Article/details/gtcflsgpbu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhongyouzk.top/Article/details/gtscorbqhg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cheryme.top/Article/details/gtkbslxsqp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hongshengwenyu.top/Article/details/gtlawujgvd.html

[L04] 设置超时
来源：http://dali.cashguo.top/Article/details/gtvrgkdbyd.html

Py:   requests.get(url, timeout=5)
来源：http://dali.sufxvd.cn/Article/details/gtnxkzuwni.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.wangdashe.top/Article/details/gtfoobsdrd.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinghuilouyu.cn/Article/details/gtpjmmwzbs.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdaxrhljv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sxryk.cn/Article/details/gtaaglxsnc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.wangdashe.top/Article/details/gtbslyrfcc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gogol.net.cn/Article/details/gtdncebryi.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinqigufen.top/Article/details/gtwruqjuef.html

[L05] 上传文件（multipart）
来源：http://dali.fzhhl.top/Article/details/gtpnicrqmd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ybcxt.top/Article/details/gtohfhsebg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hfpthk.cn/Article/details/gtewxikvaw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ivvv.top/Article/details/gtvyyppsmk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.dashuyun.cn/Article/details/gtbfajcdpg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gaohongyu789.top/Article/details/gtnoxfvbkk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shangyingyoupin.top/Article/details/gtquvbfdut.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gotoacloud.top/Article/details/gtcagybqur.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqecgkllm.html

[L06] 解析响应为 JSON
来源：http://dali.zdqjudy.top/Article/details/gtowvwvnfh.html

Py:   resp.json()
来源：http://dali.aizwys.cn/Article/details/gttcqnbbyh.html

PHP:  json_decode($body, true);
来源：http://dali.c1oappe.top/Article/details/gtfhudakex.html

JS:   await resp.json()
来源：http://dali.nwbrower.top/Article/details/gtqhavsbvm.html

TS:   await resp.json()
来源：http://dali.zycfv.cn/Article/details/gtqpmtvoff.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yuxming.cn/Article/details/gtsfnruumd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yongpay.top/Article/details/gthjvxwcaa.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jiagoushi.top/Article/details/gtbqtlmhya.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.sufxvd.cn/Article/details/gtmmxcqcsh.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhongyouzk.top/Article/details/gtrlingfwb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yangfankeji.com/Article/details/gtyhlvlpmv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ehwqpu.com/Article/details/gtbaazdhlr.html

JS:   resp.ok;  resp.status
来源：http://dali.cheryme.top/Article/details/gtbaistpox.html

TS:   resp.ok;  resp.status
来源：http://dali.jiagoushi.top/Article/details/gtflvuyfiz.html

Java: resp.statusCode()
来源：http://dali.kuanghao11.cn/Article/details/gtkgziielv.html

Go:   resp.StatusCode
来源：http://dali.fengsongda.top/Article/details/gtezfilqkd.html

Ruby: resp.code.to_i
来源：http://dali.zhoulong.xyz/Article/details/gtccsrvfcl.html

C#:   (int)resp.StatusCode
来源：http://dali.cqqwz.cn/Article/details/gtpqzhgvlu.html

[L08] 并发请求多个地址
来源：http://dali.zdqjudy.top/Article/details/gtcrhbyikq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ydzc1.top/Article/details/gtgcmrtlsk.html

PHP:  curl_multi_init() 系列
来源：http://dali.jqgufenzy.top/Article/details/gtkclfsbrr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.kuanghao11.cn/Article/details/gtpevuabvk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.kuanghao11.cn/Article/details/gtlaneqjkv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.aibaodan.cn/Article/details/gtjasbruap.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xuanzx.com/Article/details/gtwslgwmpa.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinqigufen.top/Article/details/gtaxvlrzfi.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hywenlv.cn/Article/details/gtxxzmjwdw.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtcakysxxr.html

M. 命令行 / 进程 / 环境
来源：http://dali.fzhhl.top/Article/details/gtfugwamqk.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtckxmhstw.html

[M01] 读取命令行参数
来源：http://dali.sysykeji.top/Article/details/gtttljmupo.html

Py:   sys.argv[1:]
来源：http://dali.fengsongda.top/Article/details/gtnnnfkejk.html

PHP:  $argv;  $argc;
来源：http://dali.sysykeji.top/Article/details/gtjrghtsno.html

JS:   process.argv.slice(2)
来源：http://dali.mhx1999.top/Article/details/gtmljbtxjd.html

TS:   process.argv.slice(2)
来源：http://dali.hammf.cn/Article/details/gtvmpktvrt.html

Java: args 数组（main 方法参数）
来源：http://dali.ybcxt.top/Article/details/gthtqrpypo.html

Go:   os.Args[1:]
来源：http://dali.xylfe.cn/Article/details/gtqzxuwnmg.html

Ruby: ARGV
来源：http://dali.haohaochexian.top/Article/details/gtunzxmgel.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shuidangran.top/Article/details/gtothepgmq.html

[M02] 读取环境变量
来源：http://dali.fzhhl.top/Article/details/gtewpqapvf.html

Py:   os.environ.get("HOME")
来源：http://dali.havefunace.top/Article/details/gtlxkzabbs.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.aibaodan.cn/Article/details/gthikwivzb.html

JS:   process.env.HOME
来源：http://dali.birdmap.top/Article/details/gtyngauxmv.html

TS:   process.env.HOME
来源：http://dali.shzxlz.cn/Article/details/gtywmgidoc.html

Java: System.getenv("HOME")
来源：http://dali.bjfxy.top/Article/details/gtqfevbbli.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yuanzhike.top/Article/details/gtvibylwwq.html

Ruby: ENV["HOME"]
来源：http://dali.daria6918.cn/Article/details/gtqxwzsgpm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.dianchejie.cn/Article/details/gtspuyabgu.html

[M03] 执行外部命令
来源：http://dali.sufxvd.cn/Article/details/gtnyxtnydz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.daxiang520.top/Article/details/gtuwauwlce.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jianghu66.top/Article/details/gtnnilkjpv.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yanxiufei.cn/Article/details/gtvtorrbvq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.snrcjt.cn/Article/details/gtwzdoxvwf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.bjfxy.top/Article/details/gtguolbdtc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgmnglroh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jyoumei.cn/Article/details/gtpdpuwxxj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yuxming.cn/Article/details/gtrkarqpsw.html

[M04] 获取当前工作目录
来源：http://dali.sysykeji.top/Article/details/gtcslufdes.html

Py:   os.getcwd()
来源：http://dali.yj20258.top/Article/details/gtmzklflyh.html

PHP:  getcwd();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaejmwpcs.html

JS:   process.cwd()
来源：http://dali.vqdsnc.cn/Article/details/gtrbfyithb.html

TS:   process.cwd()
来源：http://dali.fengsongda.top/Article/details/gthozedoxn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xziqi.cn/Article/details/gtxkitmgzw.html

Go:   os.Getwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtktngipwb.html

Ruby: Dir.pwd
来源：http://dali.pengpengdd.cyou/Article/details/gtivdzzktb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ehwqpu.com/Article/details/gtqwlljuge.html

[M05] 设置退出码
来源：http://dali.gzhubu.top/Article/details/gthtkfopiu.html

Py:   sys.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtmwnjqrzz.html

PHP:  exit(1);
来源：http://dali.zycfv.cn/Article/details/gtnroakbnp.html

JS:   process.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gttqppblbl.html

TS:   process.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gtfiwlcwgs.html

Java: System.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtztboymjj.html

Go:   os.Exit(1)
来源：http://dali.birdmap.top/Article/details/gtzsromqld.html

Ruby: exit 1
来源：http://dali.hfpthk.cn/Article/details/gtxyjubdxv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yangfankeji.com/Article/details/gtfcgvxzqx.html

[M06] 向标准错误输出
来源：http://dali.ivvv.top/Article/details/gtyetxjwvp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.fzhhl.top/Article/details/gtdxgbxdfc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jyoumei.cn/Article/details/gtcprqsbwt.html

JS:   console.error("err")
来源：http://dali.c1oappe.top/Article/details/gtrfjhuzdz.html

TS:   console.error("err")
来源：http://dali.nanxuanxn.top/Article/details/gtksbmziqr.html

Java: System.err.println("err")
来源：http://dali.yj20258.top/Article/details/gtixizxkfg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.dianchejie.cn/Article/details/gtrwnjtxrb.html

Ruby: warn "err"
来源：http://dali.c1oappe.top/Article/details/gtminuatzd.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ydzc1.top/Article/details/gtxkhppwxx.html

[M07] 判断是否为主入口
来源：http://dali.havefunace.top/Article/details/gtlgwspekt.html

Py:   if __name__ == "__main__":
来源：http://dali.zycfv.cn/Article/details/gtlqrpcjwq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.pengpengdd.cyou/Article/details/gtafvzdzjh.html

JS:   require.main === module
来源：http://dali.gotoacloud.top/Article/details/gtoszcfxiu.html

TS:   require.main === module
来源：http://dali.svipenyu.cn/Article/details/gturgnexzv.html

Java: public static void main(String[] args)
来源：http://dali.ydzc1.top/Article/details/gtdtwfxilb.html

Go:   func main()
来源：http://dali.tian-w.cn/Article/details/gtrngliwlw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.daria6918.cn/Article/details/gtavhatfdk.html

C#:   static void Main(string[] args)
来源：http://dali.sufxvd.cn/Article/details/gtrdkfqqiv.html

[M08] 获取系统与运行时信息
来源：http://dali.shangyingyoupin.top/Article/details/gtytoptxtk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.svipenyu.cn/Article/details/gtondympyq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.havefunace.top/Article/details/gtixizujmc.html

JS:   process.platform;  process.version
来源：http://dali.316326.xyz/Article/details/gtcfscpnbr.html

TS:   process.platform;  process.version
来源：http://dali.sweek.top/Article/details/gtlkaarqho.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zycfv.cn/Article/details/gtcddkycfw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.nanxuanxn.top/Article/details/gtrnbrnibs.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.feifeiyinyue.top/Article/details/gtbeovebza.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.kuanghao11.cn/Article/details/gtopcrcgnx.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtuvfyqatt.html

N. 数据结构与算法
来源：http://dali.sysykeji.top/Article/details/gttteqcmsn.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtpheudpxg.html

[N01] 二分查找（有序数组）
来源：http://dali.mhx1999.top/Article/details/gtjbvkpacw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtuoqgzqks.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.fengsongda.top/Article/details/gtlvupbkei.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cdnleiting.top/Article/details/gtoujyhvjg.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yonumen.top/Article/details/gtntxiticq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yongpay.top/Article/details/gtlgtkcamo.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtqduwrrag.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sxryk.cn/Article/details/gtshfzgvxc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gtudgnfmpy.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yj20258888.top/Article/details/gtxxhgrgez.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ydzc1.top/Article/details/gtabodwarj.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.kuanghao11.cn/Article/details/gtxjxnqvsv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrsxhkhcy.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmqjqwawk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.tianlin.xyz/Article/details/gtbwhnmshr.html

Go:   slices.Sort(arr)
来源：http://dali.ivvv.top/Article/details/gtlftmvdod.html

Ruby: arr.sort
来源：http://dali.9152youxi.cn/Article/details/gtpsrznuwc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.guowangkeji.top/Article/details/gtbrrrjgll.html

[N03] 快速排序（分治示例）
来源：http://dali.kuanghao11.cn/Article/details/gterzaabut.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.birdmap.top/Article/details/gtabamdjzb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jiagoushi.top/Article/details/gtleexnmae.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sufxvd.cn/Article/details/gtyzfuavpk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ehwqpu.com/Article/details/gtbkesoivk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shanyushiyangkeji.top/Article/details/gtofwvruuh.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xylfe.cn/Article/details/gtwvwlabis.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.sweek.top/Article/details/gtswdanhcc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkxecjsta.html

[N04] 斐波那契数列
来源：http://dali.shanyushiyangtech.top/Article/details/gtdhjhbefe.html


<!-- 参考信息 -->