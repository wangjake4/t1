代发 wailian999

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hongshengwenyu.top/Article/details/gtefqruuib.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.guannengcc.top/Article/details/gtjnzworji.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhiwuduotai.top/Article/details/gtllmlzzfg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xinyue.icu/Article/details/gtmhqjyyau.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.pycfn.com/Article/details/gtvhedxahu.html

[J08] 提取年月日与星期
来源：http://dali.yangfankeji.com/Article/details/gtwsplbshq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hnxiangtu.top/Article/details/gtrqrbdere.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jianghu66.top/Article/details/gtmphnabfx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinqigfzy.top/Article/details/gterfmofgy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhongyouzk.top/Article/details/gtjwnoqaoo.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.316326.xyz/Article/details/gtsbwqfdpn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.iojbl.cn/Article/details/gtcfgsfcaj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.mhx1999.top/Article/details/gtvemmyrwz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shzxlz.cn/Article/details/gtncumwxzm.html

[J09] 时区处理
来源：http://dali.sysykeji.top/Article/details/gtfnwyoiaf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzdwqghfm.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinqigufen.top/Article/details/gtrfvyjzao.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gtqgatnyuy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nwbrower.top/Article/details/gtpyuddrnj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xuetiantiany.cn/Article/details/gtrviycksi.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinqigufen.top/Article/details/gtdilflucr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqouwvzwf.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.fengsongda.top/Article/details/gtdpopywtj.html

[J10] 取今天 / 本月第一天
来源：http://dali.jqgfzy.top/Article/details/gtyujpesrg.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.c1oappe.top/Article/details/gtoeykvgvz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jiagoushi.top/Article/details/gtnixtoudb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gogol.net.cn/Article/details/gtvvanheiz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtqaoobsic.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ppjwa.cn/Article/details/gtkctvoyle.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cucudq.cn/Article/details/gtqbpaqxoo.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xziqi.cn/Article/details/gtkawbojsr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yuxming.cn/Article/details/gtpxepphyz.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtlvkmozxp.html

K. JSON 与序列化
来源：http://dali.nanxuanxn.top/Article/details/gtnxzllsmq.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtabqhlibq.html

[K01] 对象转 JSON 字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtohjtstsr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.c1oappe.top/Article/details/gtqpracjyl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ehwqpu.com/Article/details/gtmrhsiohh.html

JS:   JSON.stringify(obj)
来源：http://dali.sweek.top/Article/details/gtvroobtey.html

TS:   JSON.stringify(obj)
来源：http://dali.daria6918.cn/Article/details/gtdkbtiaqh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hfpthk.cn/Article/details/gtsytanaml.html

Go:   json.Marshal(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtapdtocow.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.guannengcc.top/Article/details/gtodxmhlvh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.chenzaomai.com/Article/details/gtyklfetjd.html

[K02] JSON 字符串转对象
来源：http://dali.nanxuanxn.top/Article/details/gtviuqffxx.html

Py:   json.loads(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtevpamycs.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yj202588.top/Article/details/gtaeyyfvkd.html

JS:   JSON.parse(s)
来源：http://dali.zhixingplan.top/Article/details/gtdcytfxlu.html

TS:   JSON.parse(s)
来源：http://dali.daxiang520.top/Article/details/gtyapmhtbd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zdqjudy.top/Article/details/gtgzmtitfo.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.meibo888.top/Article/details/gtrmlxfyer.html

Ruby: JSON.parse(s)
来源：http://dali.sweek.top/Article/details/gtthcaiymr.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtitohtrqj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jyoumei.cn/Article/details/gthlvpsoss.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenjidiqi.icu/Article/details/gtltopgapu.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.svipenyu.cn/Article/details/gthywwitii.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.andypj.xyz/Article/details/gthcrnvjjj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hywenlv.cn/Article/details/gtdrcvoteh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtutdtmzqo.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yanxiufei.cn/Article/details/gtyapnwiuz.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zdqjudy.top/Article/details/gtckbbdvox.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hysaishi.cn/Article/details/gthaanhksa.html

[K04] 读取 JSON 文件
来源：http://dali.gogol.net.cn/Article/details/gtdyibfnuo.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinqigfzy.top/Article/details/gtscodskuq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.mhx1999.top/Article/details/gtdsbajgvq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenlongwang.top/Article/details/gtoklefvap.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.birdmap.top/Article/details/gteplyvtqd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhoulong.xyz/Article/details/gtuvcnktre.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.aizwys.cn/Article/details/gtrbljhwtf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zdqjudy.top/Article/details/gtpncaxfwa.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsusydoee.html

[K05] 深拷贝对象
来源：http://dali.shuidangran.top/Article/details/gtyfpyucez.html

Py:   copy.deepcopy(obj)
来源：http://dali.tianlin.xyz/Article/details/gttfngofez.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xylfe.cn/Article/details/gttucekubi.html

JS:   structuredClone(obj)
来源：http://dali.snrcjt.cn/Article/details/gtbhndrazg.html

TS:   structuredClone(obj)
来源：http://dali.zhengqikj.top/Article/details/gtngiughji.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ivvv.top/Article/details/gtqajowkbx.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xinyue.icu/Article/details/gtmmgsivdl.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.sufxvd.cn/Article/details/gtwkcoqoub.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.daxiang520.top/Article/details/gteqdwjrvy.html

[K06] 解析 URL 查询串
来源：http://dali.sweek.top/Article/details/gtwswurqfm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gtkaswpgwe.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xinyue.icu/Article/details/gtbtemtczd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgfzy.top/Article/details/gtvesavuew.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shangyingyoupin.top/Article/details/gtwzlvrsaz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cheryme.top/Article/details/gtddxouizp.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gtnfuxcqup.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hywenlv.cn/Article/details/gtlhdvnpvu.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gthgpqohnt.html

[K07] 进制转换
来源：http://dali.xuetiantiany.cn/Article/details/gtxpnxwimn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yj20258.top/Article/details/gtdqgeigju.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xylfe.cn/Article/details/gtksllqmrg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gtftrflqew.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gtdjthhyez.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gtyzuawywq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.0kj1m.cn/Article/details/gtuolyytzd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yuxming.cn/Article/details/gtupwjthip.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.sweek.top/Article/details/gtehaywfds.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shanyushiyangtech.top/Article/details/gtxheosjnr.html

Py:   pickle.dumps(obj)
来源：http://dali.sxryk.cn/Article/details/gtuwjtnvlx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yj202588.top/Article/details/gtnuogqryh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhongyouzk.top/Article/details/gtqualvjuq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.c1oappe.top/Article/details/gturtpmiqb.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenlongwang.top/Article/details/gtcyrsgczb.html

Go:   encoding/gob
来源：http://dali.daxiang520.top/Article/details/gtlxlidthi.html

Ruby: Marshal.dump(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtfgjoryhs.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yj202588.top/Article/details/gtflpaczur.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtsjfxvznl.html

L. 网络请求
来源：http://dali.svipenyu.cn/Article/details/gtdygugdnk.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtxemcyhqj.html

[L01] 发送 GET 请求
来源：http://dali.yangfankeji.com/Article/details/gtjuzlrkyw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.kuanghao11.cn/Article/details/gtibxjuprb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.wangdashe.top/Article/details/gttnpofkno.html

JS:   await fetch(url)
来源：http://dali.iojbl.cn/Article/details/gtdwmfldre.html

TS:   await fetch(url)
来源：http://dali.daria6918.cn/Article/details/gtpxgwhkua.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.wangshuangyany.cn/Article/details/gtwfzubnpq.html

Go:   resp, err := http.Get(url)
来源：http://dali.hfpthk.cn/Article/details/gtwjbpoutn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jqgufenzy.top/Article/details/gtxoeqrrdn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xinyue.icu/Article/details/gtjcxuqsvk.html

[L02] 发送 POST JSON
来源：http://dali.cheryme.top/Article/details/gtilermvng.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.0kj1m.cn/Article/details/gtxzfzmema.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xziqi.cn/Article/details/gtmkedkqqw.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guowangkeji.top/Article/details/gttsrwoewx.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.c1oappe.top/Article/details/gtskdbaczh.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.nwbrower.top/Article/details/gtlmogkoyr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinqigfzy.top/Article/details/gtjhoyqhqy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfqyqoqfc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jqgfzy.top/Article/details/gtfrrphziz.html

[L03] 设置自定义请求头
来源：http://dali.zdqjudy.top/Article/details/gtvseljsdm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.guowangkeji.top/Article/details/gtqrqgrenn.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sysykeji.top/Article/details/gthorqwugh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhengqikj.top/Article/details/gtntqrwlhn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jyoumei.cn/Article/details/gtusmgncep.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sufxvd.cn/Article/details/gtiplprnrx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shzxlz.cn/Article/details/gtjkiolxot.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jiagoushi.top/Article/details/gtqcxdisjv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yj20258.top/Article/details/gtncwfsatx.html

[L04] 设置超时
来源：http://dali.guowangkeji.top/Article/details/gtqbokxsjo.html

Py:   requests.get(url, timeout=5)
来源：http://dali.smart0.xyz/Article/details/gtvgwacxip.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhongyouzk.top/Article/details/gtmrsgfubi.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258.top/Article/details/gtoaytcyiq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cashguo.top/Article/details/gtwjgtafgk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.chenjidiqi.icu/Article/details/gtlhlkpgpk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zycfv.cn/Article/details/gtidtfgwps.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hysaishi.cn/Article/details/gtwwpnysnm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xylfe.cn/Article/details/gthamnlkwv.html

[L05] 上传文件（multipart）
来源：http://dali.316326.xyz/Article/details/gtxeleilne.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.aibaodan.cn/Article/details/gtgepuvdok.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shangyingyoupin.top/Article/details/gtmaavyulb.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhongyouzk.top/Article/details/gtnbmrqgql.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.fzhhl.top/Article/details/gtwfqyixaz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yj202588.top/Article/details/gtcezfqwmx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtnrpmiiav.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.dashuyun.cn/Article/details/gtxopvjhmv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtijuqrnjs.html

[L06] 解析响应为 JSON
来源：http://dali.tianlin.xyz/Article/details/gtherwfubh.html

Py:   resp.json()
来源：http://dali.zhixingplan.top/Article/details/gtmfzudkrq.html

PHP:  json_decode($body, true);
来源：http://dali.nanxinkj.top/Article/details/gtocwvayri.html

JS:   await resp.json()
来源：http://dali.yj20258888.top/Article/details/gtmhahrlzk.html

TS:   await resp.json()
来源：http://dali.chenlongwang.top/Article/details/gtmuixuxvu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenzaomai.com/Article/details/gtqqfyvvez.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jqgufenzy.top/Article/details/gtvhbxqqxz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gaohongyu789.top/Article/details/gtdirjmniy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yvedp.cn/Article/details/gtausprrxl.html

[L07] 处理 HTTP 状态码
来源：http://dali.kuanghao11.cn/Article/details/gtisqkmzbe.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinqigufen.top/Article/details/gtosllerdp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.andypj.xyz/Article/details/gtkuourynq.html

JS:   resp.ok;  resp.status
来源：http://dali.yangfankeji.com/Article/details/gttuljkfuz.html

TS:   resp.ok;  resp.status
来源：http://dali.jinqigfzy.top/Article/details/gtdlutxgwn.html

Java: resp.statusCode()
来源：http://dali.cdnleiting.top/Article/details/gtqscfidll.html

Go:   resp.StatusCode
来源：http://dali.jianghu66.top/Article/details/gtnfeiogmb.html

Ruby: resp.code.to_i
来源：http://dali.snrcjt.cn/Article/details/gtrxukomrw.html

C#:   (int)resp.StatusCode
来源：http://dali.ppjwa.cn/Article/details/gthxkttfvt.html

[L08] 并发请求多个地址
来源：http://dali.chenlongwang.top/Article/details/gtsmacocdt.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yvedp.cn/Article/details/gtspxtahoe.html

PHP:  curl_multi_init() 系列
来源：http://dali.sysykeji.top/Article/details/gtecrzhqom.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dashuyun.cn/Article/details/gtqawzfxgw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aizwys.cn/Article/details/gtaqvegyoo.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhongyouzk.top/Article/details/gthcztqldx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xziqi.cn/Article/details/gtwjywbmfq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.chenlongwang.top/Article/details/gtffppemph.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gzhubu.top/Article/details/gtcdcligev.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtdynrbaeg.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinqigufen.top/Article/details/gtoevcpsgo.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtiectbwla.html

[M01] 读取命令行参数
来源：http://dali.bjfxy.top/Article/details/gtqmokknns.html

Py:   sys.argv[1:]
来源：http://dali.nwbrower.top/Article/details/gtxaubnhqi.html

PHP:  $argv;  $argc;
来源：http://dali.gzhubu.top/Article/details/gtybeovstd.html

JS:   process.argv.slice(2)
来源：http://dali.pengpengdd.cyou/Article/details/gtqgzhyywy.html

TS:   process.argv.slice(2)
来源：http://dali.jqgufenzy.top/Article/details/gtvxezcmyf.html

Java: args 数组（main 方法参数）
来源：http://dali.pengpengdd.cyou/Article/details/gteppwwthr.html

Go:   os.Args[1:]
来源：http://dali.xziqi.cn/Article/details/gtamjtcbsz.html

Ruby: ARGV
来源：http://dali.andypj.xyz/Article/details/gtdwpcyzah.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ydzc1.top/Article/details/gtfqdwvkdn.html

[M02] 读取环境变量
来源：http://dali.ehwqpu.com/Article/details/gtygdbtovf.html

Py:   os.environ.get("HOME")
来源：http://dali.fengsongda.top/Article/details/gtznkwdgcv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.kuanghao11.cn/Article/details/gtvgxqpxvo.html

JS:   process.env.HOME
来源：http://dali.sxryk.cn/Article/details/gtidusuekj.html

TS:   process.env.HOME
来源：http://dali.hammf.cn/Article/details/gtxjrmkpmg.html

Java: System.getenv("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gtnajqcehf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.tianlin.xyz/Article/details/gtcwrlyytt.html

Ruby: ENV["HOME"]
来源：http://dali.jiagoushi.top/Article/details/gtklqnmiob.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.meibo888.top/Article/details/gteegsgwdo.html

[M03] 执行外部命令
来源：http://dali.sweek.top/Article/details/gtirdrxfgy.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.9152youxi.cn/Article/details/gtqumsnoov.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.iojbl.cn/Article/details/gtaundkzwc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenzaomai.com/Article/details/gtpwfbeolw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.aizwys.cn/Article/details/gtzlfqbqrp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.haohaochexian.top/Article/details/gtjtyfgizl.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cashguo.top/Article/details/gtfnoozzur.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cheryme.top/Article/details/gtxyekpijv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yuanzhike.top/Article/details/gtcmtpzaam.html

[M04] 获取当前工作目录
来源：http://dali.tanke756.top/Article/details/gthwdowljy.html

Py:   os.getcwd()
来源：http://dali.0kj1m.cn/Article/details/gtvqhjwzuk.html

PHP:  getcwd();
来源：http://dali.xziqi.cn/Article/details/gtvllbxobn.html

JS:   process.cwd()
来源：http://dali.mhx1999.top/Article/details/gtgrqwfakt.html

TS:   process.cwd()
来源：http://dali.nanxuanxn.top/Article/details/gtycmycpmm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.daria6918.cn/Article/details/gtiaxohgpi.html

Go:   os.Getwd()
来源：http://dali.yangfankeji.com/Article/details/gtchlfvhjs.html

Ruby: Dir.pwd
来源：http://dali.ydzc1.top/Article/details/gtaoqzkequ.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ppjwa.cn/Article/details/gtsfbynhiw.html

[M05] 设置退出码
来源：http://dali.xylfe.cn/Article/details/gthykctmgn.html

Py:   sys.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gthmoqccrw.html

PHP:  exit(1);
来源：http://dali.jqgufenzy.top/Article/details/gtalqmzvwh.html

JS:   process.exit(1)
来源：http://dali.meibo888.top/Article/details/gtdwvyjtyb.html

TS:   process.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gtluvopuik.html

Java: System.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtfyggdshk.html

Go:   os.Exit(1)
来源：http://dali.0kj1m.cn/Article/details/gtbmhcrizb.html

Ruby: exit 1
来源：http://dali.cdnleiting.top/Article/details/gthxmhqhhm.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhoulong.xyz/Article/details/gtdpgjpaxo.html

[M06] 向标准错误输出
来源：http://dali.dashuyun.cn/Article/details/gthkhqdirp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xuetiantiany.cn/Article/details/gtninizosq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yonumen.top/Article/details/gtmmhiolxs.html

JS:   console.error("err")
来源：http://dali.zhoulong.xyz/Article/details/gtbvexyeel.html

TS:   console.error("err")
来源：http://dali.0kj1m.cn/Article/details/gtxhenszof.html

Java: System.err.println("err")
来源：http://dali.yueranfly.top/Article/details/gtpueeardp.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jqgfzy.top/Article/details/gtanubjjau.html

Ruby: warn "err"
来源：http://dali.sxryk.cn/Article/details/gtpuuvphnj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nwbrower.top/Article/details/gtudywbtvm.html

[M07] 判断是否为主入口
来源：http://dali.smart0.xyz/Article/details/gtnmgbwyry.html

Py:   if __name__ == "__main__":
来源：http://dali.hnqzz.top/Article/details/gtrwpaxqye.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cdnleiting.top/Article/details/gtykipqyyv.html

JS:   require.main === module
来源：http://dali.9152youxi.cn/Article/details/gtavyeevam.html

TS:   require.main === module
来源：http://dali.sufxvd.cn/Article/details/gtdchnruqg.html

Java: public static void main(String[] args)
来源：http://dali.yuxming.cn/Article/details/gtxevmomtw.html

Go:   func main()
来源：http://dali.gaohongyu789.top/Article/details/gtpeydfpeg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sxryk.cn/Article/details/gtitbefweo.html

C#:   static void Main(string[] args)
来源：http://dali.ybcxt.top/Article/details/gtccizidni.html

[M08] 获取系统与运行时信息
来源：http://dali.shanyushiyangtech.top/Article/details/gtgdmbrgjm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yvedp.cn/Article/details/gtcmyyrfrg.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.tanke756.top/Article/details/gtnlkwyrzd.html

JS:   process.platform;  process.version
来源：http://dali.ppjwa.cn/Article/details/gtfzyoysxg.html

TS:   process.platform;  process.version
来源：http://dali.0kj1m.cn/Article/details/gtcjwvkmpc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhongyouzk.top/Article/details/gtbbaiwvlo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hysaishi.cn/Article/details/gtouhyjsqk.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jyoumei.cn/Article/details/gtbbeamoqz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hnqzz.top/Article/details/gtvtfcdbxk.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtinmrdmka.html

N. 数据结构与算法
来源：http://dali.zhoulong.xyz/Article/details/gtpvnxgupu.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtosrfurib.html

[N01] 二分查找（有序数组）
来源：http://dali.316326.xyz/Article/details/gtydxxrgxg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtkyprgqyr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xuetiantiany.cn/Article/details/gtcvplorex.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtarnlulab.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tanke756.top/Article/details/gtfrinpyoe.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtklztnjnu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sweek.top/Article/details/gtbmnujnqu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zycfv.cn/Article/details/gtluuojmhi.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yj20258888.top/Article/details/gtyhzhoecx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.0kj1m.cn/Article/details/gtaptlweef.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dashuyun.cn/Article/details/gtxcqgzckw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.316326.xyz/Article/details/gtzsgbyxrm.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tanke756.top/Article/details/gtfmgxrtgo.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hongshengwenyu.top/Article/details/gthiuyhkpf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.daxiang520.top/Article/details/gtfibnjcsc.html

Go:   slices.Sort(arr)
来源：http://dali.cdnleiting.top/Article/details/gtndcsfhpu.html

Ruby: arr.sort
来源：http://dali.hfpthk.cn/Article/details/gtehzckxwe.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.haohaochexian.top/Article/details/gtnpvfrjyo.html

[N03] 快速排序（分治示例）
来源：http://dali.cdnleiting.top/Article/details/gtrzjgzsrl.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdyqpowgf.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jqgfzy.top/Article/details/gtwjlowwmk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hongshengwenyu.top/Article/details/gtycamkqns.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fengsongda.top/Article/details/gtzmlobwvu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.tianlin.xyz/Article/details/gtkjaypqju.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sufxvd.cn/Article/details/gtzftnoenc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cheryme.top/Article/details/gtfsddspfv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yueranfly.top/Article/details/gtwjlnzyua.html

[N04] 斐波那契数列
来源：http://dali.c1oappe.top/Article/details/gtoshehbld.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gzhubu.top/Article/details/gtdorovyzx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ehwqpu.com/Article/details/gtxkrifrwe.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gttzzhjbuk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shzxlz.cn/Article/details/gtkfemphai.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jqgufenzy.top/Article/details/gtaoenpvci.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.haohaochexian.top/Article/details/gtrvmtpuda.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtnsdqwtdv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.gogol.net.cn/Article/details/gtrrbvcook.html

[N05] 最大公约数
来源：http://dali.dianchejie.cn/Article/details/gtwtjqraxp.html

Py:   math.gcd(a, b)
来源：http://dali.chenjidiqi.icu/Article/details/gtitzljtpc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xuanzx.com/Article/details/gtcnzbqfnk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gaohongyu789.top/Article/details/gtmqgwljdj.html


<!-- 参考信息 -->