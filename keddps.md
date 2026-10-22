代发 wailian999

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.vqdsnc.cn/Article/details/gtriyuhogx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yanxiufei.cn/Article/details/gtrazpakeb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yj202588.top/Article/details/gtmcdhdzsz.html

[J06] 计算两时间之差
来源：http://dali.ybcxt.top/Article/details/gtanbevhvf.html

Py:   (end - start).total_seconds()
来源：http://dali.dashuyun.cn/Article/details/gtbtxpjjpv.html

PHP:  $end->diff($start)->days;
来源：http://dali.wangshuangyany.cn/Article/details/gtqtlnwvcm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.pycfn.com/Article/details/gtndajqexu.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.chenlongwang.top/Article/details/gtvfgdojhr.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yanxiufei.cn/Article/details/gteasqofnt.html

Go:   end.Sub(start).Hours()
来源：http://dali.daxiang520.top/Article/details/gtoxtbnwoa.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ivvv.top/Article/details/gtoauohjtp.html

C#:   (end - start).TotalSeconds
来源：http://dali.jyoumei.cn/Article/details/gtdoyfnmqi.html

[J07] 比较两个日期
来源：http://dali.yvedp.cn/Article/details/gtuwfdwfai.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yuxming.cn/Article/details/gtddfrtjbg.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ehwqpu.com/Article/details/gtimqhwnbi.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gzhubu.top/Article/details/gtryspsmsr.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ivvv.top/Article/details/gtwxfigtve.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jyoumei.cn/Article/details/gtjzfdvsfe.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.smart0.xyz/Article/details/gtgcyrsrty.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.aibaodan.cn/Article/details/gtqdhbrxpf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.sysykeji.top/Article/details/gtamcreqxk.html

[J08] 提取年月日与星期
来源：http://dali.shuidangran.top/Article/details/gtsjmoeser.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.aizwys.cn/Article/details/gtvbutqxfn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hysaishi.cn/Article/details/gtkbzxowxp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hysaishi.cn/Article/details/gtryxghrsh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.pycfn.com/Article/details/gtwqosegtl.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shuidangran.top/Article/details/gtgctvpeyc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwxofanje.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.snrcjt.cn/Article/details/gthmojvohb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hongshengwenyu.top/Article/details/gtrerqsqir.html

[J09] 时区处理
来源：http://dali.yanxiufei.cn/Article/details/gtlvlrvdjk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtefdyzqof.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.dashuyun.cn/Article/details/gttjlhwvrm.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jiagoushi.top/Article/details/gttwvqnava.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuanzx.com/Article/details/gtcanmntsq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xuetiantiany.cn/Article/details/gtookectul.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zycfv.cn/Article/details/gtuliuinsr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xuanzx.com/Article/details/gtjtsnonjq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.smart0.xyz/Article/details/gtbizakrat.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj20258.top/Article/details/gtyzbidksf.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sweek.top/Article/details/gtbymknkmd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xuanzx.com/Article/details/gtojqzogqn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yonumen.top/Article/details/gtncbupjzr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.havefunace.top/Article/details/gtzjfyowvy.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.andypj.xyz/Article/details/gtckbuytle.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jqgufenzy.top/Article/details/gtcdcoqmjg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gogol.net.cn/Article/details/gtyxwgrdka.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jiagoushi.top/Article/details/gtkbwzxxfg.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtgjubntsa.html

K. JSON 与序列化
来源：http://dali.bjfxy.top/Article/details/gtshmpykhv.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtfxcjmxjl.html

[K01] 对象转 JSON 字符串
来源：http://dali.iojbl.cn/Article/details/gtgzbrdycc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.aibaodan.cn/Article/details/gtikclqyxh.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.kuanghao11.cn/Article/details/gtvhpxitpp.html

JS:   JSON.stringify(obj)
来源：http://dali.zhengqikj.top/Article/details/gtnryljhfz.html

TS:   JSON.stringify(obj)
来源：http://dali.yueranfly.top/Article/details/gtjtcteeay.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cucudq.cn/Article/details/gtxutggrzj.html

Go:   json.Marshal(obj)
来源：http://dali.jiagoushi.top/Article/details/gtffbclmfr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.guannengcc.top/Article/details/gtguensxvs.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tanke756.top/Article/details/gtuxxcxkvq.html

[K02] JSON 字符串转对象
来源：http://dali.sufxvd.cn/Article/details/gtjtigggwd.html

Py:   json.loads(s)
来源：http://dali.gogol.net.cn/Article/details/gtcocmlkdf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.wangdashe.top/Article/details/gtufsiozqq.html

JS:   JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gtbehnuhtt.html

TS:   JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gtoibwecnv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.mhx1999.top/Article/details/gtgmcumzbv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.guowangkeji.top/Article/details/gtglzovbmr.html

Ruby: JSON.parse(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtiwenzeyi.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtwpirsvlr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.nanxuanxn.top/Article/details/gtfjydaqsi.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jiagoushi.top/Article/details/gtuuxbhuix.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxinkj.top/Article/details/gtwgdqbfpe.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ehwqpu.com/Article/details/gtsojsoams.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.andypj.xyz/Article/details/gtwfovxztw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hysaishi.cn/Article/details/gtveivzsgs.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hfpthk.cn/Article/details/gtmyipntnj.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtljodzfti.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj20258888.top/Article/details/gtxdhwodbn.html

[K04] 读取 JSON 文件
来源：http://dali.chenzaomai.com/Article/details/gthcvjzdpj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shuidangran.top/Article/details/gtfdvdzbda.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yueranfly.top/Article/details/gtaujimaxt.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tanke756.top/Article/details/gtcmcxmqpf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sweek.top/Article/details/gtaqybtemv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.svipenyu.cn/Article/details/gtkhbfbtds.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cucudq.cn/Article/details/gtqnywawtd.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zycfv.cn/Article/details/gthgtmgfzo.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.svipenyu.cn/Article/details/gtepbqmnpg.html

[K05] 深拷贝对象
来源：http://dali.gogol.net.cn/Article/details/gtewtffahb.html

Py:   copy.deepcopy(obj)
来源：http://dali.ydzc1.top/Article/details/gtmrbhsxsy.html

PHP:  unserialize(serialize($obj));
来源：http://dali.svipenyu.cn/Article/details/gtnqxblisn.html

JS:   structuredClone(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtmbmwhycc.html

TS:   structuredClone(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtiecarvft.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yuanzhike.top/Article/details/gtqrywpmsg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shuidangran.top/Article/details/gtvwdqppyb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ppjwa.cn/Article/details/gtinrbyfmb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.svipenyu.cn/Article/details/gtagzgjhta.html

[K06] 解析 URL 查询串
来源：http://dali.hysaishi.cn/Article/details/gtpmclmpwl.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gaohongyu789.top/Article/details/gthfxcraja.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.andypj.xyz/Article/details/gtmjuvavkw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnxiangtu.top/Article/details/gtjjhtubod.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hongshengwenyu.top/Article/details/gtuphpfcef.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ppjwa.cn/Article/details/gtrmhetinl.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yvedp.cn/Article/details/gtivnjsbfa.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ehwqpu.com/Article/details/gthxfsnmib.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gtqvsivyyn.html

[K07] 进制转换
来源：http://dali.tianlin.xyz/Article/details/gtxxwjlaqv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tanke756.top/Article/details/gtavmhhuam.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.quarkkingdee.top/Article/details/gtyxpfloos.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gtntijktcb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gtssjkjnfu.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yonumen.top/Article/details/gtrjwynwhr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpffzgyco.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.vqdsnc.cn/Article/details/gtzhaytfbg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gtdranowxf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cheryme.top/Article/details/gtvzucprup.html

Py:   pickle.dumps(obj)
来源：http://dali.aizwys.cn/Article/details/gtpyfxadwy.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gogol.net.cn/Article/details/gttocakmim.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hnqzz.top/Article/details/gtpyqtlhxi.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtclqlvelx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj20258.top/Article/details/gtuuwtlzhe.html

Go:   encoding/gob
来源：http://dali.zhongyouzk.top/Article/details/gtjiigrjww.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuikqelbe.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jinghuilouyu.cn/Article/details/gtdxgtucdr.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gthxikbvsn.html

L. 网络请求
来源：http://dali.snrcjt.cn/Article/details/gtsytjnqbn.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtzlcadnlk.html

[L01] 发送 GET 请求
来源：http://dali.gotoacloud.top/Article/details/gtdmqmrckg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.gaohongyu789.top/Article/details/gtsyziojvu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nanxuanxn.top/Article/details/gtcbxkzksa.html

JS:   await fetch(url)
来源：http://dali.zhengqikj.top/Article/details/gtxjrnzggn.html

TS:   await fetch(url)
来源：http://dali.vqdsnc.cn/Article/details/gtbsedjxcy.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhixingplan.top/Article/details/gtqurjwaku.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhixingplan.top/Article/details/gtkrxpogch.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.dashuyun.cn/Article/details/gtysavfiwi.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sweek.top/Article/details/gtyrdffwyv.html

[L02] 发送 POST JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlmuievqp.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cheryme.top/Article/details/gtechhgkoz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.0kj1m.cn/Article/details/gtkocmhzsc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yueranfly.top/Article/details/gtsbyyhhyk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dashuyun.cn/Article/details/gtxqkjpuzf.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cdnleiting.top/Article/details/gtjhigacqq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.guannengcc.top/Article/details/gthiwihxob.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmsgwwhyw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cdnleiting.top/Article/details/gtylxofcdi.html

[L03] 设置自定义请求头
来源：http://dali.fzhhl.top/Article/details/gtlbyivuda.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yueranfly.top/Article/details/gtzhbjwyzl.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.meibo888.top/Article/details/gtqrupvqtx.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sysykeji.top/Article/details/gtumhhnpxj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sweek.top/Article/details/gtwnamiros.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yj20258.top/Article/details/gtxrmyweyt.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnmsjktbp.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.daria6918.cn/Article/details/gtrdpamqeu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cucudq.cn/Article/details/gtakdjaksz.html

[L04] 设置超时
来源：http://dali.bjfxy.top/Article/details/gtfholjens.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xylfe.cn/Article/details/gtdytyzqpr.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.vqdsnc.cn/Article/details/gtxgukjilt.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhixingplan.top/Article/details/gtbavqicjr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sufxvd.cn/Article/details/gtxvxoaaei.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhongyouzk.top/Article/details/gtgfywbgzq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.aibaodan.cn/Article/details/gtdcgbrwuk.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jlsjyb.cn/Article/details/gtncwkvkea.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yangfankeji.com/Article/details/gtkrislttd.html

[L05] 上传文件（multipart）
来源：http://dali.chenjidiqi.icu/Article/details/gtbwvfjjzk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hysaishi.cn/Article/details/gtuelcyarv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.316326.xyz/Article/details/gtqmiouajr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yonumen.top/Article/details/gtfquusqsw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinghuilouyu.cn/Article/details/gtvijbtwpr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shangyingyoupin.top/Article/details/gtixzahocs.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yj202588.top/Article/details/gtsullaihy.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.nwbrower.top/Article/details/gtahxczgov.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtdyqtjqvh.html

[L06] 解析响应为 JSON
来源：http://dali.gogol.net.cn/Article/details/gthntlcbff.html

Py:   resp.json()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkidvkjkx.html

PHP:  json_decode($body, true);
来源：http://dali.iojbl.cn/Article/details/gtzeeilcox.html

JS:   await resp.json()
来源：http://dali.chenlongwang.top/Article/details/gtlkveukro.html

TS:   await resp.json()
来源：http://dali.birdmap.top/Article/details/gtixcziicq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shzxlz.cn/Article/details/gtjggphnrs.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ydzc1.top/Article/details/gtyukyqnwq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.feifeiyinyue.top/Article/details/gtuqvcowos.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ehwqpu.com/Article/details/gtcblnpqcb.html

[L07] 处理 HTTP 状态码
来源：http://dali.kuanghao11.cn/Article/details/gtmjykopdm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.chenzaomai.com/Article/details/gtmdsefeez.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.mhx1999.top/Article/details/gtwphzuqtc.html

JS:   resp.ok;  resp.status
来源：http://dali.aibaodan.cn/Article/details/gtthxgkdca.html

TS:   resp.ok;  resp.status
来源：http://dali.yj202588.top/Article/details/gtzxqkzjhj.html

Java: resp.statusCode()
来源：http://dali.yj20258888.top/Article/details/gtugihkksj.html

Go:   resp.StatusCode
来源：http://dali.hysaishi.cn/Article/details/gtkfksonhg.html

Ruby: resp.code.to_i
来源：http://dali.zycfv.cn/Article/details/gtrcyhvaaz.html

C#:   (int)resp.StatusCode
来源：http://dali.cdnleiting.top/Article/details/gtcagkgyqk.html

[L08] 并发请求多个地址
来源：http://dali.yj202588.top/Article/details/gtsnksbwme.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jianghu66.top/Article/details/gtuvgbwtqf.html

PHP:  curl_multi_init() 系列
来源：http://dali.chenzaomai.com/Article/details/gtlynvcmhj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gtrdqbhnye.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.havefunace.top/Article/details/gtcijbexzl.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.tian-w.cn/Article/details/gtovpjwbzu.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jqgfzy.top/Article/details/gtpmfrhezc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.pycfn.com/Article/details/gtizldmlpx.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.meibo888.top/Article/details/gtwtvnfuhj.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtpbcqptrb.html

M. 命令行 / 进程 / 环境
来源：http://dali.birdmap.top/Article/details/gtgavbwgra.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtegqwndlj.html

[M01] 读取命令行参数
来源：http://dali.cashguo.top/Article/details/gtpwgdnrqa.html

Py:   sys.argv[1:]
来源：http://dali.hnqzz.top/Article/details/gtlupeulgq.html

PHP:  $argv;  $argc;
来源：http://dali.nwbrower.top/Article/details/gttjgewubn.html

JS:   process.argv.slice(2)
来源：http://dali.fzhhl.top/Article/details/gtmssdvwwn.html

TS:   process.argv.slice(2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfqzcnibb.html

Java: args 数组（main 方法参数）
来源：http://dali.zycfv.cn/Article/details/gtwlxkrbej.html

Go:   os.Args[1:]
来源：http://dali.daria6918.cn/Article/details/gtwezhnzuz.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gtqcmazyht.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwtjputt.html

[M02] 读取环境变量
来源：http://dali.9152youxi.cn/Article/details/gtjbmgmhhm.html

Py:   os.environ.get("HOME")
来源：http://dali.shuidangran.top/Article/details/gtqvnbvieu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.haohaochexian.top/Article/details/gtbovvidrt.html

JS:   process.env.HOME
来源：http://dali.jqgfzy.top/Article/details/gtznrpkokc.html

TS:   process.env.HOME
来源：http://dali.hywenlv.cn/Article/details/gtutqnmryz.html

Java: System.getenv("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gtvohilqly.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gtmibyjyqg.html

Ruby: ENV["HOME"]
来源：http://dali.shangyingyoupin.top/Article/details/gtjzocvrnl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.guannengcc.top/Article/details/gtqvvdmtut.html

[M03] 执行外部命令
来源：http://dali.cucudq.cn/Article/details/gtrguykdee.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.pengpengdd.cyou/Article/details/gthtzceovu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdkezjgah.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnqzz.top/Article/details/gtuvtmfvgv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnqzz.top/Article/details/gtyamvzyuk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.c1oappe.top/Article/details/gtwqqgfoqj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlzxbearw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.tian-w.cn/Article/details/gtanqfsfqr.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhiwuduotai.top/Article/details/gtwetrzfde.html

[M04] 获取当前工作目录
来源：http://dali.9152youxi.cn/Article/details/gtynbikwdj.html

Py:   os.getcwd()
来源：http://dali.shuidangran.top/Article/details/gtpcdjdalp.html

PHP:  getcwd();
来源：http://dali.yongpay.top/Article/details/gthydvfmxh.html

JS:   process.cwd()
来源：http://dali.cucudq.cn/Article/details/gtpylctchb.html

TS:   process.cwd()
来源：http://dali.cdnleiting.top/Article/details/gtydebvmjj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cqqwz.cn/Article/details/gtwsqxkdpy.html

Go:   os.Getwd()
来源：http://dali.vqdsnc.cn/Article/details/gtlhortece.html

Ruby: Dir.pwd
来源：http://dali.andypj.xyz/Article/details/gtlkazpkuv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.daxiang520.top/Article/details/gtpodtfwni.html

[M05] 设置退出码
来源：http://dali.jiagoushi.top/Article/details/gtsuimahrr.html

Py:   sys.exit(1)
来源：http://dali.birdmap.top/Article/details/gtwlvkacli.html

PHP:  exit(1);
来源：http://dali.316326.xyz/Article/details/gtzlycikye.html

JS:   process.exit(1)
来源：http://dali.jianghu66.top/Article/details/gtxhotknlg.html

TS:   process.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gtprccdovg.html

Java: System.exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtznibtvbo.html

Go:   os.Exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgtvwnwpe.html

Ruby: exit 1
来源：http://dali.svipenyu.cn/Article/details/gtvdpbdsiy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xuanzx.com/Article/details/gtbkihxzhb.html

[M06] 向标准错误输出
来源：http://dali.jiagoushi.top/Article/details/gtdoqwjxod.html

Py:   print("err", file=sys.stderr)
来源：http://dali.guannengcc.top/Article/details/gtjyeszuhu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.gaohongyu789.top/Article/details/gtgcxfguan.html

JS:   console.error("err")
来源：http://dali.feifeiyinyue.top/Article/details/gttrzhmlxi.html

TS:   console.error("err")
来源：http://dali.cqqwz.cn/Article/details/gtygsukahz.html

Java: System.err.println("err")
来源：http://dali.guowangkeji.top/Article/details/gtufoqvirv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.chenlongwang.top/Article/details/gtlomxbyqb.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gtbynmczcm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gtgszhtkxm.html

[M07] 判断是否为主入口
来源：http://dali.cucudq.cn/Article/details/gtyhkjoict.html

Py:   if __name__ == "__main__":
来源：http://dali.nanxinkj.top/Article/details/gtjqdvsfsl.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cqqwz.cn/Article/details/gtcbekegqh.html

JS:   require.main === module
来源：http://dali.xinyue.icu/Article/details/gtpqhjjzsz.html

TS:   require.main === module
来源：http://dali.hammf.cn/Article/details/gtmwdqixtn.html

Java: public static void main(String[] args)
来源：http://dali.yueranfly.top/Article/details/gtosqzxtqs.html

Go:   func main()
来源：http://dali.vqdsnc.cn/Article/details/gtirpxddzr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gaohongyu789.top/Article/details/gtmcdrrafe.html

C#:   static void Main(string[] args)
来源：http://dali.gogol.net.cn/Article/details/gtsfwvluns.html

[M08] 获取系统与运行时信息
来源：http://dali.wangshuangyany.cn/Article/details/gtpebhypme.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yj20258.top/Article/details/gtfdkixldf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ydzc1.top/Article/details/gtcdxctpfg.html

JS:   process.platform;  process.version
来源：http://dali.redwolf501.top/Article/details/gtebobeiyx.html

TS:   process.platform;  process.version
来源：http://dali.ppjwa.cn/Article/details/gtzuggcfud.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yongpay.top/Article/details/gtzjeqgifl.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.guowangkeji.top/Article/details/gttavzvojj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cheryme.top/Article/details/gtgzsafawq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.aizwys.cn/Article/details/gtgwrexvps.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtaxawzhct.html

N. 数据结构与算法
来源：http://dali.xuanzx.com/Article/details/gttqigfkku.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtnopotwaf.html

[N01] 二分查找（有序数组）
来源：http://dali.nanxinkj.top/Article/details/gtguogxwhg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtnontgokz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.daxiang520.top/Article/details/gtqoxhivto.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuxming.cn/Article/details/gtuthtsohu.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.birdmap.top/Article/details/gtdruakpzp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtkshhmisi.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ivvv.top/Article/details/gtljnszjtu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.aizwys.cn/Article/details/gtfovokqrm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtefgpsmmi.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.svipenyu.cn/Article/details/gtlrugnwhq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daria6918.cn/Article/details/gthyhucjvx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xylfe.cn/Article/details/gtekurevtc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guowangkeji.top/Article/details/gtkttygnpy.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hammf.cn/Article/details/gtdcfcwaui.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jqgufenzy.top/Article/details/gtlwecwphi.html

Go:   slices.Sort(arr)
来源：http://dali.gotoacloud.top/Article/details/gtofytnnwp.html

Ruby: arr.sort
来源：http://dali.daxiang520.top/Article/details/gtqobuzzac.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yj20258888.top/Article/details/gtbjmdxtjm.html

[N03] 快速排序（分治示例）
来源：http://dali.jyoumei.cn/Article/details/gtmgbolmmr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.smart0.xyz/Article/details/gtvnwtwdol.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yuxming.cn/Article/details/gtaptuxxjm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pycfn.com/Article/details/gtdbzizfpp.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258.top/Article/details/gtxxhemgjo.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxauhtrfq.html


<!-- 参考信息 -->