代发 wailian999

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yongpay.top/Article/details/gtevaabwwn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.dashuyun.cn/Article/details/gtrrqfydzw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cucudq.cn/Article/details/gtmuoitznp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gtymkhatsg.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gtoqixyusv.html

[J08] 提取年月日与星期
来源：http://dali.hammf.cn/Article/details/gtyuesfkqx.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shuidangran.top/Article/details/gtamijegwi.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.dashuyun.cn/Article/details/gtelyvmpce.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.daria6918.cn/Article/details/gteefbixhd.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.chenzaomai.com/Article/details/gtcizjoloh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwmmxmrzq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.9152youxi.cn/Article/details/gtlsbvrwxl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zycfv.cn/Article/details/gtlfafhzaw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shzxlz.cn/Article/details/gthuwomxnw.html

[J09] 时区处理
来源：http://dali.yueranfly.top/Article/details/gtgezayjch.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gzhubu.top/Article/details/gtkuivirkb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.vqdsnc.cn/Article/details/gtlvzluzhx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.smart0.xyz/Article/details/gtvcfhvkhj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhoulong.xyz/Article/details/gtcfxjijpp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yuanzhike.top/Article/details/gthxwpcoge.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.9152youxi.cn/Article/details/gtopdtfjal.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gotoacloud.top/Article/details/gtznipjfad.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ybcxt.top/Article/details/gtrxxjyjpw.html

[J10] 取今天 / 本月第一天
来源：http://dali.daria6918.cn/Article/details/gtjptxktva.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yj20258.top/Article/details/gtwloxlser.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tian-w.cn/Article/details/gtonslymma.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.guowangkeji.top/Article/details/gttzfqyktg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yangfankeji.com/Article/details/gtjxxnorzf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj20258.top/Article/details/gtlfafchdf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj20258.top/Article/details/gtgegdbbxk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ydzc1.top/Article/details/gtfipucrut.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhongyouzk.top/Article/details/gtlyqviqrm.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gthrodgnru.html

K. JSON 与序列化
来源：http://dali.nwbrower.top/Article/details/gtzmgakfvb.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtwyznbinc.html

[K01] 对象转 JSON 字符串
来源：http://dali.havefunace.top/Article/details/gtklizandw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sxryk.cn/Article/details/gtrywovhet.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xylfe.cn/Article/details/gttoowopek.html

JS:   JSON.stringify(obj)
来源：http://dali.zdqjudy.top/Article/details/gtmhedkvar.html

TS:   JSON.stringify(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtkwharmnn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.fzhhl.top/Article/details/gtnjxjrptn.html

Go:   json.Marshal(obj)
来源：http://dali.nanxinkj.top/Article/details/gtbvcandbr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ybcxt.top/Article/details/gtqohblkqv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.snrcjt.cn/Article/details/gtztcxjyyl.html

[K02] JSON 字符串转对象
来源：http://dali.ivvv.top/Article/details/gtpksuahez.html

Py:   json.loads(s)
来源：http://dali.pycfn.com/Article/details/gtntwjwela.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.bjfxy.top/Article/details/gtctfrxqbl.html

JS:   JSON.parse(s)
来源：http://dali.haohaochexian.top/Article/details/gttuvsklrp.html

TS:   JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gtcqtenezl.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hongshengwenyu.top/Article/details/gtyemjjgwi.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.0kj1m.cn/Article/details/gtaswxwovw.html

Ruby: JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gtrrtmlkbe.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jiagoushi.top/Article/details/gtcmhkislv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.svipenyu.cn/Article/details/gthhzfadmn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zycfv.cn/Article/details/gtcivdqwnp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigfzy.top/Article/details/gtphlsxjtl.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnqzz.top/Article/details/gtbqeuuedl.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhongyouzk.top/Article/details/gtttyawnub.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.andypj.xyz/Article/details/gtpwwwxfla.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.fengsongda.top/Article/details/gtwihmhsfd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.316326.xyz/Article/details/gtqzddkudm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.pycfn.com/Article/details/gthejvgusa.html

[K04] 读取 JSON 文件
来源：http://dali.yonumen.top/Article/details/gtwdwitapr.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.0kj1m.cn/Article/details/gtifaztsmb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.guannengcc.top/Article/details/gtzrbomlge.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.iojbl.cn/Article/details/gtrzadxyzg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gtcktszbvm.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yongpay.top/Article/details/gttsyieefh.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.chenlongwang.top/Article/details/gtingxibyn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ydzc1.top/Article/details/gtplgkvivi.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hfpthk.cn/Article/details/gtkntqpouz.html

[K05] 深拷贝对象
来源：http://dali.hnqzz.top/Article/details/gtbrwgzgtv.html

Py:   copy.deepcopy(obj)
来源：http://dali.ehwqpu.com/Article/details/gtybdosqvf.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ydzc1.top/Article/details/gthgchdmnn.html

JS:   structuredClone(obj)
来源：http://dali.havefunace.top/Article/details/gtskrjmepi.html

TS:   structuredClone(obj)
来源：http://dali.xinyue.icu/Article/details/gtyqqevrsq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ppjwa.cn/Article/details/gtjtcprnys.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.birdmap.top/Article/details/gtcbrbqyli.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhengqikj.top/Article/details/gtnwjrsuab.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yongpay.top/Article/details/gthfpktwda.html

[K06] 解析 URL 查询串
来源：http://dali.jinqigfzy.top/Article/details/gtmvlxwvff.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.9152youxi.cn/Article/details/gtyabnetsf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj20258888.top/Article/details/gtrdpqkwiw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.9152youxi.cn/Article/details/gtkanaupcn.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.quarkkingdee.top/Article/details/gthvonvnho.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.meibo888.top/Article/details/gtwbaxpyhh.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xziqi.cn/Article/details/gtxjgffdej.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.svipenyu.cn/Article/details/gtjrmkysxu.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jqgfzy.top/Article/details/gtqudhpnqh.html

[K07] 进制转换
来源：http://dali.hnqzz.top/Article/details/gtnqwniwkn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtugwihdjb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.fengsongda.top/Article/details/gtwhczubbn.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gtsiztwlvn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gtnfsknuul.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gtfvunyhyw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhiwuduotai.top/Article/details/gtinbuuxrz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.pycfn.com/Article/details/gtnrxalcnb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gttshsqbyx.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.c1oappe.top/Article/details/gtngkvhhau.html

Py:   pickle.dumps(obj)
来源：http://dali.hnqzz.top/Article/details/gtaomtwkqc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cheryme.top/Article/details/gthwiaebel.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangtech.top/Article/details/gtuzihqsaf.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jlsjyb.cn/Article/details/gtumfojvds.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.aizwys.cn/Article/details/gtyfwhnqjb.html

Go:   encoding/gob
来源：http://dali.shangyingyoupin.top/Article/details/gtrqeespxe.html

Ruby: Marshal.dump(obj)
来源：http://dali.fengsongda.top/Article/details/gtmwueqnwd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.snrcjt.cn/Article/details/gtqczahcsf.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gttggvjjfu.html

L. 网络请求
来源：http://dali.jyoumei.cn/Article/details/gtnzopgcef.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtupctzoiv.html

[L01] 发送 GET 请求
来源：http://dali.nwbrower.top/Article/details/gthegjmiag.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.wangdashe.top/Article/details/gtsiggbyzw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.pengpengdd.cyou/Article/details/gtyplwhlsq.html

JS:   await fetch(url)
来源：http://dali.andypj.xyz/Article/details/gthbueripk.html

TS:   await fetch(url)
来源：http://dali.redwolf501.top/Article/details/gtomhcynkq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhoulong.xyz/Article/details/gttxbklhcd.html

Go:   resp, err := http.Get(url)
来源：http://dali.smart0.xyz/Article/details/gtsujbjojn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ydzc1.top/Article/details/gtqgykrvkf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zycfv.cn/Article/details/gtbniddnvn.html

[L02] 发送 POST JSON
来源：http://dali.tian-w.cn/Article/details/gtpmhwtaku.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ydzc1.top/Article/details/gtkkbkmaxh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.meibo888.top/Article/details/gtuahjceid.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sxryk.cn/Article/details/gtpeonubvf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dashuyun.cn/Article/details/gthitihxqw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ybcxt.top/Article/details/gtbsjzcvib.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jyoumei.cn/Article/details/gtppbpreaj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hysaishi.cn/Article/details/gtuetjyubd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sxryk.cn/Article/details/gtclleqmul.html

[L03] 设置自定义请求头
来源：http://dali.jlsjyb.cn/Article/details/gthrknwrvs.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.iojbl.cn/Article/details/gtscisqaah.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yonumen.top/Article/details/gthjwuacmn.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zdqjudy.top/Article/details/gtjorfrvgf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.mhx1999.top/Article/details/gtmwiucvjk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xuetiantiany.cn/Article/details/gteobhhxrg.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sysykeji.top/Article/details/gtlqiivref.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shzxlz.cn/Article/details/gtwryunkqi.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhoulong.xyz/Article/details/gtfviswgeg.html

[L04] 设置超时
来源：http://dali.iojbl.cn/Article/details/gtzuxxgaat.html

Py:   requests.get(url, timeout=5)
来源：http://dali.birdmap.top/Article/details/gtwelaspgn.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yvedp.cn/Article/details/gtknlpihqh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tian-w.cn/Article/details/gtwhdzpkrg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jiagoushi.top/Article/details/gtwuhazhcx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinghuilouyu.cn/Article/details/gtsnjhdyqm.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cheryme.top/Article/details/gthqnsukvi.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.pengpengdd.cyou/Article/details/gtnwltitwu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.dashuyun.cn/Article/details/gtttakkglx.html

[L05] 上传文件（multipart）
来源：http://dali.c1oappe.top/Article/details/gtxulgnwui.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwyhepwcq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cheryme.top/Article/details/gtieuugrqp.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.iojbl.cn/Article/details/gtuprostsi.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenzaomai.com/Article/details/gtruzrbdms.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.kuanghao11.cn/Article/details/gtahbarmzh.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hongshengwenyu.top/Article/details/gtsqfktynm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.redwolf501.top/Article/details/gtgosxareh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xylfe.cn/Article/details/gtygydogms.html

[L06] 解析响应为 JSON
来源：http://dali.sweek.top/Article/details/gtqhvndzny.html

Py:   resp.json()
来源：http://dali.yuxming.cn/Article/details/gtnlgdaxnk.html

PHP:  json_decode($body, true);
来源：http://dali.yj20258888.top/Article/details/gtihtpotva.html

JS:   await resp.json()
来源：http://dali.jqgufenzy.top/Article/details/gtxuhkdshg.html

TS:   await resp.json()
来源：http://dali.xuanzx.com/Article/details/gtrqqpnrqx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cashguo.top/Article/details/gtupjnelef.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yongpay.top/Article/details/gtdvyifsdt.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jiagoushi.top/Article/details/gtwofhppkx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cdnleiting.top/Article/details/gtevamphhn.html

[L07] 处理 HTTP 状态码
来源：http://dali.yongpay.top/Article/details/gtcnavovtm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.guowangkeji.top/Article/details/gtjhdwjlhf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.aibaodan.cn/Article/details/gtapakactf.html

JS:   resp.ok;  resp.status
来源：http://dali.hongshengwenyu.top/Article/details/gtmscmjmen.html

TS:   resp.ok;  resp.status
来源：http://dali.chenlongwang.top/Article/details/gtowguspds.html

Java: resp.statusCode()
来源：http://dali.wangdashe.top/Article/details/gtalbhkpuo.html

Go:   resp.StatusCode
来源：http://dali.xziqi.cn/Article/details/gtoxtjgruy.html

Ruby: resp.code.to_i
来源：http://dali.zdqjudy.top/Article/details/gtkmwiczjp.html

C#:   (int)resp.StatusCode
来源：http://dali.yuxming.cn/Article/details/gtgryuftmj.html

[L08] 并发请求多个地址
来源：http://dali.meibo888.top/Article/details/gtmastznsz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.pycfn.com/Article/details/gtmoyhckei.html

PHP:  curl_multi_init() 系列
来源：http://dali.0kj1m.cn/Article/details/gtveoefehn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.havefunace.top/Article/details/gtlnygqsbf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cashguo.top/Article/details/gttyrvuxmt.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.fzhhl.top/Article/details/gtfjdlorvw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yuanzhike.top/Article/details/gtxbltmfie.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hongshengwenyu.top/Article/details/gtucsejtyp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhengqikj.top/Article/details/gtisdwhhej.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtisuzcmsp.html

M. 命令行 / 进程 / 环境
来源：http://dali.hongshengwenyu.top/Article/details/gtmoqemblo.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtgjrpwzko.html

[M01] 读取命令行参数
来源：http://dali.sufxvd.cn/Article/details/gthlzscwds.html

Py:   sys.argv[1:]
来源：http://dali.yonumen.top/Article/details/gtpfnbojzy.html

PHP:  $argv;  $argc;
来源：http://dali.ywan-chungtsiang.top/Article/details/gteelsiimf.html

JS:   process.argv.slice(2)
来源：http://dali.zhoulong.xyz/Article/details/gtszduvxjn.html

TS:   process.argv.slice(2)
来源：http://dali.chenzaomai.com/Article/details/gttwxbmulb.html

Java: args 数组（main 方法参数）
来源：http://dali.hnxiangtu.top/Article/details/gtuunttdso.html

Go:   os.Args[1:]
来源：http://dali.guannengcc.top/Article/details/gtwgmihuib.html

Ruby: ARGV
来源：http://dali.jlsjyb.cn/Article/details/gtmehceezb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.wangshuangyany.cn/Article/details/gtyylykero.html

[M02] 读取环境变量
来源：http://dali.ppjwa.cn/Article/details/gtgayhkgcz.html

Py:   os.environ.get("HOME")
来源：http://dali.daria6918.cn/Article/details/gtjhccqxzt.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ydzc1.top/Article/details/gtakmsbgxo.html

JS:   process.env.HOME
来源：http://dali.jqgufenzy.top/Article/details/gtliwhfwnq.html

TS:   process.env.HOME
来源：http://dali.bjfxy.top/Article/details/gtjgbwrcaz.html

Java: System.getenv("HOME")
来源：http://dali.sufxvd.cn/Article/details/gtmhzrwdgq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.tanke756.top/Article/details/gtbvdltlbi.html

Ruby: ENV["HOME"]
来源：http://dali.zhoulong.xyz/Article/details/gtkfyaixrm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xylfe.cn/Article/details/gtgzsnfjza.html

[M03] 执行外部命令
来源：http://dali.9152youxi.cn/Article/details/gtmqblkjjc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hnqzz.top/Article/details/gtemypnjwz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.chenzaomai.com/Article/details/gtxylrlcbj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jlsjyb.cn/Article/details/gthifggkis.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgrbvvjbh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gzhubu.top/Article/details/gtvpbxxqzz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jiagoushi.top/Article/details/gtviwagrip.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jianghu66.top/Article/details/gtgqftjmee.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sysykeji.top/Article/details/gtlmoyctch.html

[M04] 获取当前工作目录
来源：http://dali.mhx1999.top/Article/details/gtnklzdhfr.html

Py:   os.getcwd()
来源：http://dali.cqqwz.cn/Article/details/gtnpwhyhmv.html

PHP:  getcwd();
来源：http://dali.yj20258.top/Article/details/gtgvtflkyf.html

JS:   process.cwd()
来源：http://dali.hfpthk.cn/Article/details/gtflxuddik.html

TS:   process.cwd()
来源：http://dali.ydzc1.top/Article/details/gtdnonsfzz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jyoumei.cn/Article/details/gtngglzeem.html

Go:   os.Getwd()
来源：http://dali.hammf.cn/Article/details/gtmadhbjnt.html

Ruby: Dir.pwd
来源：http://dali.gogol.net.cn/Article/details/gtxoalsbfj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yuxming.cn/Article/details/gtkpekopmb.html

[M05] 设置退出码
来源：http://dali.daria6918.cn/Article/details/gtteakpiug.html

Py:   sys.exit(1)
来源：http://dali.yj20258.top/Article/details/gtqjkqiwdv.html

PHP:  exit(1);
来源：http://dali.0kj1m.cn/Article/details/gtgtkmhioq.html

JS:   process.exit(1)
来源：http://dali.jianghu66.top/Article/details/gtmdblqkyn.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtofripjno.html

Java: System.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gtgtswnytd.html

Go:   os.Exit(1)
来源：http://dali.dashuyun.cn/Article/details/gtkuokaklt.html

Ruby: exit 1
来源：http://dali.ivvv.top/Article/details/gtdewjiovw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sysykeji.top/Article/details/gtfkznsruw.html

[M06] 向标准错误输出
来源：http://dali.guowangkeji.top/Article/details/gtwqfzfxsp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yuanzhike.top/Article/details/gttzukrbse.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shanyushiyangtech.top/Article/details/gtvyzmogri.html

JS:   console.error("err")
来源：http://dali.yj20258.top/Article/details/gtceotgqfo.html

TS:   console.error("err")
来源：http://dali.zhengqikj.top/Article/details/gtuqcttkfa.html

Java: System.err.println("err")
来源：http://dali.wangshuangyany.cn/Article/details/gtzsruysru.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj20258.top/Article/details/gtgofzexqm.html

Ruby: warn "err"
来源：http://dali.yj20258.top/Article/details/gtbsmskara.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.pengpengdd.cyou/Article/details/gtmtxpbvgf.html

[M07] 判断是否为主入口
来源：http://dali.hammf.cn/Article/details/gtdhxemxhr.html

Py:   if __name__ == "__main__":
来源：http://dali.zycfv.cn/Article/details/gtxhpzzpyb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.0kj1m.cn/Article/details/gtdxnhjsjy.html

JS:   require.main === module
来源：http://dali.zhixingplan.top/Article/details/gtigywfbhd.html

TS:   require.main === module
来源：http://dali.havefunace.top/Article/details/gtzsqrqubx.html

Java: public static void main(String[] args)
来源：http://dali.xinyue.icu/Article/details/gtwxgxjraa.html

Go:   func main()
来源：http://dali.hnxiangtu.top/Article/details/gtwizjtnuj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.fengsongda.top/Article/details/gtqkynbjgj.html

C#:   static void Main(string[] args)
来源：http://dali.sxryk.cn/Article/details/gtmofbhrep.html

[M08] 获取系统与运行时信息
来源：http://dali.svipenyu.cn/Article/details/gtkzuyjnig.html

Py:   platform.system();  platform.python_version()
来源：http://dali.pycfn.com/Article/details/gtbpghlrtf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jqgfzy.top/Article/details/gtouzgkkic.html

JS:   process.platform;  process.version
来源：http://dali.birdmap.top/Article/details/gtlcqqumug.html

TS:   process.platform;  process.version
来源：http://dali.quarkkingdee.top/Article/details/gtsekhkzef.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.quarkkingdee.top/Article/details/gtgsmehsyc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.havefunace.top/Article/details/gtpagwmuss.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.mhx1999.top/Article/details/gtcbzoclsa.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cdnleiting.top/Article/details/gtpepeverh.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtkmjzpfqm.html

N. 数据结构与算法
来源：http://dali.smart0.xyz/Article/details/gtfiobyhjh.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtswnuypto.html

[N01] 二分查找（有序数组）
来源：http://dali.vqdsnc.cn/Article/details/gtxsjddfzp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hammf.cn/Article/details/gtinfsrvjw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yj202588.top/Article/details/gtyytixvvc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zdqjudy.top/Article/details/gtihaxcfag.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuxming.cn/Article/details/gtggshnkeu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtebaztlae.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtejhxjnaj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cucudq.cn/Article/details/gtxmflktwk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtpzzmvqkl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.chenlongwang.top/Article/details/gtkluscxbl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yonumen.top/Article/details/gtjpwpmbtp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.snrcjt.cn/Article/details/gtksfpfcoc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigfzy.top/Article/details/gtolzwngbt.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.c1oappe.top/Article/details/gtawxdajor.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sxryk.cn/Article/details/gtppfjxiqa.html

Go:   slices.Sort(arr)
来源：http://dali.nanxinkj.top/Article/details/gtexvxhwyu.html

Ruby: arr.sort
来源：http://dali.nanxinkj.top/Article/details/gtderehnqk.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.smart0.xyz/Article/details/gtyedjhctz.html

[N03] 快速排序（分治示例）
来源：http://dali.ivvv.top/Article/details/gtixabyfhk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sxryk.cn/Article/details/gtkkygrqab.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gotoacloud.top/Article/details/gtwrejndhs.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgfzy.top/Article/details/gtgraohbyp.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hysaishi.cn/Article/details/gtxhooxltt.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.0kj1m.cn/Article/details/gtimxnzvgj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.dianchejie.cn/Article/details/gtziyrbhga.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtytofogvn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.aizwys.cn/Article/details/gteysytrja.html

[N04] 斐波那契数列
来源：http://dali.yongpay.top/Article/details/gtbkcrjdyc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hfpthk.cn/Article/details/gtftdeuahe.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ybcxt.top/Article/details/gtovtvprjh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj20258888.top/Article/details/gtkfiendju.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hfpthk.cn/Article/details/gtomoekbia.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jianghu66.top/Article/details/gtkituiphk.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.0kj1m.cn/Article/details/gtyvwockqm.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xinyue.icu/Article/details/gtkjdxvebt.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cheryme.top/Article/details/gtdrbwtpqh.html

[N05] 最大公约数
来源：http://dali.wangdashe.top/Article/details/gtndrlkths.html

Py:   math.gcd(a, b)
来源：http://dali.ivvv.top/Article/details/gtemhqwepp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cashguo.top/Article/details/gtotyuhivt.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnxiangtu.top/Article/details/gthcznabdi.html


<!-- 参考信息 -->