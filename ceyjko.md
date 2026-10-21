代发 wailian999

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ivvv.top/Article/details/gtukxeudsi.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.dashuyun.cn/Article/details/gtukyvvlac.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yuanzhike.top/Article/details/gtrpbgiyhd.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.iojbl.cn/Article/details/gttscyicnz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.daxiang520.top/Article/details/gteqbwwofh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hfpthk.cn/Article/details/gtysjwsefs.html

[J09] 时区处理
来源：http://dali.zhongyouzk.top/Article/details/gtlzgfnxig.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gzhubu.top/Article/details/gttnnejpdo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jqgfzy.top/Article/details/gtzktndfwr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhoulong.xyz/Article/details/gtpbiqwvgu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgufenzy.top/Article/details/gtkgvybwvz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.kuanghao11.cn/Article/details/gtrkrptvxc.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.guannengcc.top/Article/details/gtyrplnkdg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.chenjidiqi.icu/Article/details/gtbxvmijgh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.daria6918.cn/Article/details/gtfgsbobjz.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinghuilouyu.cn/Article/details/gtcigpiorv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.svipenyu.cn/Article/details/gtijcltfbk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinqigufen.top/Article/details/gtzbunxegb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jqgfzy.top/Article/details/gttugiyydo.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ehwqpu.com/Article/details/gtzlaymbsc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhoulong.xyz/Article/details/gtmbbcqiwf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sufxvd.cn/Article/details/gtajflzhxk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhixingplan.top/Article/details/gtabgtpksj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yj20258888.top/Article/details/gthlvbslyo.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtxguzfrgf.html

K. JSON 与序列化
来源：http://dali.cheryme.top/Article/details/gtbctaoqoj.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtqmhneslp.html

[K01] 对象转 JSON 字符串
来源：http://dali.wangdashe.top/Article/details/gtrgbfcblg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gzhubu.top/Article/details/gtevpesval.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.9152youxi.cn/Article/details/gtiulxcoup.html

JS:   JSON.stringify(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiiobhxvv.html

TS:   JSON.stringify(obj)
来源：http://dali.ppjwa.cn/Article/details/gtrsxxdyly.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.fzhhl.top/Article/details/gtvqjwnsqy.html

Go:   json.Marshal(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkggjwafx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinqigufen.top/Article/details/gteiplbxom.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shzxlz.cn/Article/details/gtwzscwrha.html

[K02] JSON 字符串转对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gtycjsgwwm.html

Py:   json.loads(s)
来源：http://dali.xylfe.cn/Article/details/gtltnjgayk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shzxlz.cn/Article/details/gtbywmxeby.html

JS:   JSON.parse(s)
来源：http://dali.bjfxy.top/Article/details/gtnbodlyun.html

TS:   JSON.parse(s)
来源：http://dali.fengsongda.top/Article/details/gtvfrdhobr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.aibaodan.cn/Article/details/gtvyxbaoff.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.9152youxi.cn/Article/details/gtbwkhjust.html

Ruby: JSON.parse(s)
来源：http://dali.yonumen.top/Article/details/gtqlkisoii.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ivvv.top/Article/details/gtiowtyhzd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sysykeji.top/Article/details/gtgrbcouon.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xinyue.icu/Article/details/gtmuzwpbsp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yonumen.top/Article/details/gtbxqolopf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.c1oappe.top/Article/details/gttmmvtegi.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hysaishi.cn/Article/details/gtjlwjvpra.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gticbstwvz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yonumen.top/Article/details/gtpbrzpsiv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yueranfly.top/Article/details/gtbmhcqdoo.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tanke756.top/Article/details/gtxrdheibc.html

[K04] 读取 JSON 文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtynacehtw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.nanxuanxn.top/Article/details/gtilzeheze.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhoulong.xyz/Article/details/gtumhgkwbc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhixingplan.top/Article/details/gtizssmpmi.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtmmmfxbtx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xylfe.cn/Article/details/gtpcvptewi.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.bjfxy.top/Article/details/gteowgjfxy.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hnqzz.top/Article/details/gtvqcrttoc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinghuilouyu.cn/Article/details/gteuhdtawo.html

[K05] 深拷贝对象
来源：http://dali.daria6918.cn/Article/details/gtljytzugc.html

Py:   copy.deepcopy(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwyksdvei.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shangyingyoupin.top/Article/details/gtenxoftyc.html

JS:   structuredClone(obj)
来源：http://dali.xziqi.cn/Article/details/gtcjahtbdm.html

TS:   structuredClone(obj)
来源：http://dali.jianghu66.top/Article/details/gthrygmuyu.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.guowangkeji.top/Article/details/gtwiauxfqn.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yuanzhike.top/Article/details/gtvonxzzps.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hnqzz.top/Article/details/gtmlehfvjf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkkcgraig.html

[K06] 解析 URL 查询串
来源：http://dali.jinghuilouyu.cn/Article/details/gtxniqhwqk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yonumen.top/Article/details/gtljxqvyzs.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cheryme.top/Article/details/gtvnkrouer.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhengqikj.top/Article/details/gthdpqxzil.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hywenlv.cn/Article/details/gtlusgyofw.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zycfv.cn/Article/details/gtwujfuxtt.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhixingplan.top/Article/details/gtsauekouu.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gaohongyu789.top/Article/details/gtwrsvzchr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhixingplan.top/Article/details/gthyvvowiv.html

[K07] 进制转换
来源：http://dali.0kj1m.cn/Article/details/gtjwnilxmi.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gtepybxegz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jyoumei.cn/Article/details/gtrhsxkxks.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gtxqevfefd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gtelwhruax.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtuzvngdkj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.nwbrower.top/Article/details/gtgvpzghtw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xuetiantiany.cn/Article/details/gtvzgzyatx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gtgzynxisz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.chenjidiqi.icu/Article/details/gthwoyycbe.html

Py:   pickle.dumps(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtaszfoiem.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nanxuanxn.top/Article/details/gtsfvbtkem.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigufen.top/Article/details/gtytvwwsjr.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.316326.xyz/Article/details/gtzokdamgp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zdqjudy.top/Article/details/gtilydmphp.html

Go:   encoding/gob
来源：http://dali.jinqigfzy.top/Article/details/gtgndtgbqx.html

Ruby: Marshal.dump(obj)
来源：http://dali.hnqzz.top/Article/details/gthbobateh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xinyue.icu/Article/details/gtihxwwmml.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtbveaqrms.html

L. 网络请求
来源：http://dali.yuanzhike.top/Article/details/gtuunipbwx.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtvfdmgybl.html

[L01] 发送 GET 请求
来源：http://dali.ybcxt.top/Article/details/gtfqlrdjdr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shzxlz.cn/Article/details/gtagaktmpe.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhixingplan.top/Article/details/gtxluarpxk.html

JS:   await fetch(url)
来源：http://dali.redwolf501.top/Article/details/gtusnmrmzi.html

TS:   await fetch(url)
来源：http://dali.hysaishi.cn/Article/details/gtkyhuarfg.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ydzc1.top/Article/details/gtxlvxxezd.html

Go:   resp, err := http.Get(url)
来源：http://dali.chenzaomai.com/Article/details/gtfsqpchvf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.pengpengdd.cyou/Article/details/gtwlvvcbzy.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sweek.top/Article/details/gtwrvafqnq.html

[L02] 发送 POST JSON
来源：http://dali.aibaodan.cn/Article/details/gtrvbalofw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkpftrndb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.havefunace.top/Article/details/gtjagilgwt.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.aizwys.cn/Article/details/gtafyrcwhc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.vqdsnc.cn/Article/details/gtthpxndja.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jqgufenzy.top/Article/details/gtpjxbdehw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.nanxuanxn.top/Article/details/gtzteasyqu.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.mhx1999.top/Article/details/gtpzhgtztl.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.andypj.xyz/Article/details/gttyvosxuy.html

[L03] 设置自定义请求头
来源：http://dali.ehwqpu.com/Article/details/gtvegjgmfv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yj20258.top/Article/details/gtqqrcgxbf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yuxming.cn/Article/details/gtpqoxlxvf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangdashe.top/Article/details/gtnjimeczj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.svipenyu.cn/Article/details/gtfvtlfkie.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zdqjudy.top/Article/details/gtlfisocvk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.guowangkeji.top/Article/details/gttmadehnj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zycfv.cn/Article/details/gtqbqvexgl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.0kj1m.cn/Article/details/gtneaixkbg.html

[L04] 设置超时
来源：http://dali.cqqwz.cn/Article/details/gtrprjxzwj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxokwcbxf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.dianchejie.cn/Article/details/gtrtmeyvih.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yongpay.top/Article/details/gtylouvxsd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xinyue.icu/Article/details/gtgozpdyre.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yj20258.top/Article/details/gtlhzenhtg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gogol.net.cn/Article/details/gtujoosejv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.bjfxy.top/Article/details/gtebhpguco.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ehwqpu.com/Article/details/gtiruicaac.html

[L05] 上传文件（multipart）
来源：http://dali.fengsongda.top/Article/details/gtnpqufjuy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.daria6918.cn/Article/details/gtxxvijanq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jianghu66.top/Article/details/gtjolkyuia.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.svipenyu.cn/Article/details/gtcqujricr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnqzz.top/Article/details/gttasffguz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ivvv.top/Article/details/gtpcbhtcbb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hongshengwenyu.top/Article/details/gtbstnsihx.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.guowangkeji.top/Article/details/gtxtkmehxs.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yj202588.top/Article/details/gtdrjqhyei.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gtiskqoyua.html

Py:   resp.json()
来源：http://dali.yj20258888.top/Article/details/gtonaqfuyl.html

PHP:  json_decode($body, true);
来源：http://dali.meibo888.top/Article/details/gtesbpmfuq.html

JS:   await resp.json()
来源：http://dali.zhoulong.xyz/Article/details/gtwvfixtit.html

TS:   await resp.json()
来源：http://dali.tanke756.top/Article/details/gtsjnpdflm.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.wangdashe.top/Article/details/gtghlcysrz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cucudq.cn/Article/details/gthkjlwkmh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcmjmivcb.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.pycfn.com/Article/details/gtyezouetu.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtelibbaag.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.birdmap.top/Article/details/gtratyrkbf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jinqigufen.top/Article/details/gtkamhvruy.html

JS:   resp.ok;  resp.status
来源：http://dali.ppjwa.cn/Article/details/gtksxjlkdm.html

TS:   resp.ok;  resp.status
来源：http://dali.aibaodan.cn/Article/details/gtqmybjuzh.html

Java: resp.statusCode()
来源：http://dali.wangdashe.top/Article/details/gthhwopytc.html

Go:   resp.StatusCode
来源：http://dali.shanyushiyangkeji.top/Article/details/gtghmpyclb.html

Ruby: resp.code.to_i
来源：http://dali.gaohongyu789.top/Article/details/gtvdgirags.html

C#:   (int)resp.StatusCode
来源：http://dali.bjfxy.top/Article/details/gtplhakwlj.html

[L08] 并发请求多个地址
来源：http://dali.yueranfly.top/Article/details/gtamtfcdwv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.smart0.xyz/Article/details/gtsufrfafr.html

PHP:  curl_multi_init() 系列
来源：http://dali.guowangkeji.top/Article/details/gtdcmzblnl.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gogol.net.cn/Article/details/gtgqjvyrqv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guannengcc.top/Article/details/gtvndbxnfx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.guannengcc.top/Article/details/gtspuvbqwe.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gzhubu.top/Article/details/gtzrxifonk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yueranfly.top/Article/details/gtiljvmlba.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zycfv.cn/Article/details/gtzlxydjym.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtkuacehvd.html

M. 命令行 / 进程 / 环境
来源：http://dali.316326.xyz/Article/details/gtcspejzur.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtqismgpat.html

[M01] 读取命令行参数
来源：http://dali.daria6918.cn/Article/details/gtllcyzdvo.html

Py:   sys.argv[1:]
来源：http://dali.chenzaomai.com/Article/details/gtcevobtat.html

PHP:  $argv;  $argc;
来源：http://dali.ehwqpu.com/Article/details/gtdlagcnri.html

JS:   process.argv.slice(2)
来源：http://dali.chenjidiqi.icu/Article/details/gtfqjakxxb.html

TS:   process.argv.slice(2)
来源：http://dali.zhiwuduotai.top/Article/details/gttftdhirc.html

Java: args 数组（main 方法参数）
来源：http://dali.chenzaomai.com/Article/details/gtotacpcll.html

Go:   os.Args[1:]
来源：http://dali.shuidangran.top/Article/details/gtblmgxdyt.html

Ruby: ARGV
来源：http://dali.dianchejie.cn/Article/details/gtvqxrxwbx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.birdmap.top/Article/details/gtgistplym.html

[M02] 读取环境变量
来源：http://dali.jyoumei.cn/Article/details/gtcgttskoj.html

Py:   os.environ.get("HOME")
来源：http://dali.pycfn.com/Article/details/gtgcscvmno.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hongshengwenyu.top/Article/details/gtgzndssjs.html

JS:   process.env.HOME
来源：http://dali.xziqi.cn/Article/details/gtfuafemnk.html

TS:   process.env.HOME
来源：http://dali.pycfn.com/Article/details/gtatykxsix.html

Java: System.getenv("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtxdgnfomq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gtfmcbifkz.html

Ruby: ENV["HOME"]
来源：http://dali.jinqigufen.top/Article/details/gtnlcrkxfc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cdnleiting.top/Article/details/gtfsbmesjx.html

[M03] 执行外部命令
来源：http://dali.tian-w.cn/Article/details/gthrobhooq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yj202588.top/Article/details/gtslrnsfkp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.snrcjt.cn/Article/details/gtsipbltmj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoecsbnih.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.havefunace.top/Article/details/gtycecrrnv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zycfv.cn/Article/details/gtkpnboebc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhiwuduotai.top/Article/details/gtdqdfinpy.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yueranfly.top/Article/details/gtdrqjmudm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.wangdashe.top/Article/details/gtueowcudv.html

[M04] 获取当前工作目录
来源：http://dali.vqdsnc.cn/Article/details/gtikhmjnyp.html

Py:   os.getcwd()
来源：http://dali.pycfn.com/Article/details/gtleivmcgb.html

PHP:  getcwd();
来源：http://dali.sxryk.cn/Article/details/gtchcueaix.html

JS:   process.cwd()
来源：http://dali.jinqigfzy.top/Article/details/gtwhwhoozu.html

TS:   process.cwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsuayjlla.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xuanzx.com/Article/details/gtfrlbcnoq.html

Go:   os.Getwd()
来源：http://dali.shzxlz.cn/Article/details/gtsazujdfd.html

Ruby: Dir.pwd
来源：http://dali.haohaochexian.top/Article/details/gtcgfdgyol.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhiwuduotai.top/Article/details/gtqezdviyr.html

[M05] 设置退出码
来源：http://dali.jqgfzy.top/Article/details/gtxrvfhddo.html

Py:   sys.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gtjrtwpgso.html

PHP:  exit(1);
来源：http://dali.ppjwa.cn/Article/details/gtbwqdgois.html

JS:   process.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gtqagwiqpm.html

TS:   process.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gthuawbweg.html

Java: System.exit(1)
来源：http://dali.yvedp.cn/Article/details/gtuigcyryt.html

Go:   os.Exit(1)
来源：http://dali.shuidangran.top/Article/details/gtuefjaqsb.html

Ruby: exit 1
来源：http://dali.birdmap.top/Article/details/gtxvcoucxb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.smart0.xyz/Article/details/gtvcrdekzw.html

[M06] 向标准错误输出
来源：http://dali.cheryme.top/Article/details/gtzoouaqgm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinqigufen.top/Article/details/gtutgruhgn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.redwolf501.top/Article/details/gtehxvcgqs.html

JS:   console.error("err")
来源：http://dali.jqgufenzy.top/Article/details/gtcagiaknm.html

TS:   console.error("err")
来源：http://dali.yvedp.cn/Article/details/gthdzkwbpj.html

Java: System.err.println("err")
来源：http://dali.tanke756.top/Article/details/gtimsdqlpy.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.pengpengdd.cyou/Article/details/gtkbrqegol.html

Ruby: warn "err"
来源：http://dali.snrcjt.cn/Article/details/gttqajgjth.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhoulong.xyz/Article/details/gttodkjldc.html

[M07] 判断是否为主入口
来源：http://dali.jiagoushi.top/Article/details/gtnyxwtxcu.html

Py:   if __name__ == "__main__":
来源：http://dali.yj202588.top/Article/details/gtmsnthipk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hnxiangtu.top/Article/details/gtexecqymn.html

JS:   require.main === module
来源：http://dali.wangshuangyany.cn/Article/details/gtzjwwnxgv.html

TS:   require.main === module
来源：http://dali.aizwys.cn/Article/details/gtojbpoepq.html

Java: public static void main(String[] args)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgrtdkztl.html

Go:   func main()
来源：http://dali.xinyue.icu/Article/details/gtvojpvgvb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.dashuyun.cn/Article/details/gtxoeyunes.html

C#:   static void Main(string[] args)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtessgljvm.html

[M08] 获取系统与运行时信息
来源：http://dali.kuanghao11.cn/Article/details/gtnpfzfuil.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ydzc1.top/Article/details/gtcibmmymr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yueranfly.top/Article/details/gtmjxlvdml.html

JS:   process.platform;  process.version
来源：http://dali.yj202588.top/Article/details/gtnndarclg.html

TS:   process.platform;  process.version
来源：http://dali.hywenlv.cn/Article/details/gtyfsiayim.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cucudq.cn/Article/details/gtjndhqiij.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ybcxt.top/Article/details/gtqwdnptbe.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yongpay.top/Article/details/gtmjvgrjyv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zdqjudy.top/Article/details/gtnjuncmly.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gthbrktyuz.html

N. 数据结构与算法
来源：http://dali.xuetiantiany.cn/Article/details/gtztzdyvsu.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtulrevcmf.html

[N01] 二分查找（有序数组）
来源：http://dali.tian-w.cn/Article/details/gttwxhobvy.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtabvocxpg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zycfv.cn/Article/details/gtldaazgcc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guannengcc.top/Article/details/gtwoxfjplw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ybcxt.top/Article/details/gtcbavqmop.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.bjfxy.top/Article/details/gteexrsmnq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtafgjnzdy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.birdmap.top/Article/details/gtiasvtsab.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gtetjcdayg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.nwbrower.top/Article/details/gtmetqlxug.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gaohongyu789.top/Article/details/gtvqoajebr.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.smart0.xyz/Article/details/gtpcaictbd.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cucudq.cn/Article/details/gtnpnmfijr.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hywenlv.cn/Article/details/gtvgryqvot.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhiwuduotai.top/Article/details/gtmibdekpi.html

Go:   slices.Sort(arr)
来源：http://dali.havefunace.top/Article/details/gtcwawapik.html

Ruby: arr.sort
来源：http://dali.xinyue.icu/Article/details/gtxkjonlcp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.sysykeji.top/Article/details/gtfmscipmk.html

[N03] 快速排序（分治示例）
来源：http://dali.wangshuangyany.cn/Article/details/gtzjwxxukk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.fengsongda.top/Article/details/gthddmzyac.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gzhubu.top/Article/details/gtocrzwqyh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zdqjudy.top/Article/details/gtlzzvxnkh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fzhhl.top/Article/details/gtirrnlahs.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.havefunace.top/Article/details/gtrtvayhfs.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xylfe.cn/Article/details/gtolnktiuy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.nanxinkj.top/Article/details/gthpywurhi.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xinyue.icu/Article/details/gtjiwhkayl.html

[N04] 斐波那契数列
来源：http://dali.sweek.top/Article/details/gthcwefbau.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.0kj1m.cn/Article/details/gtsmcnlvle.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.aibaodan.cn/Article/details/gtnutcqrdz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.316326.xyz/Article/details/gtdqyuwuec.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenjidiqi.icu/Article/details/gthmhwyyna.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.9152youxi.cn/Article/details/gtkgdmiqkk.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yuanzhike.top/Article/details/gtdkgknskw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cqqwz.cn/Article/details/gthfkvbnor.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.pycfn.com/Article/details/gtougvpqdd.html

[N05] 最大公约数
来源：http://dali.hnqzz.top/Article/details/gtoldompfg.html

Py:   math.gcd(a, b)
来源：http://dali.chenlongwang.top/Article/details/gtzjaabome.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtsjtzjzlz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shangyingyoupin.top/Article/details/gtwbwvohlu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yangfankeji.com/Article/details/gtcopshftf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yj20258888.top/Article/details/gtvededrhb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinqigufen.top/Article/details/gtblkchsxx.html

Ruby: a.gcd(b)
来源：http://dali.dianchejie.cn/Article/details/gtuzluzbzb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gaohongyu789.top/Article/details/gtlvninvuz.html

[N06] 判断回文字符串
来源：http://dali.jqgfzy.top/Article/details/gtjsabswtb.html

Py:   s == s[::-1]
来源：http://dali.yj20258888.top/Article/details/gtvclksjra.html

PHP:  $s === strrev($s);
来源：http://dali.zhongyouzk.top/Article/details/gtpjgkhbpl.html


<!-- 参考信息 -->