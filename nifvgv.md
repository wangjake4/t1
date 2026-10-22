代发 wailian999

TS:   d1.getTime() < d2.getTime()
来源：http://dali.316326.xyz/Article/details/gtojswqgqj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.smart0.xyz/Article/details/gtujjzhasx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.nwbrower.top/Article/details/gtrwyuyzas.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sufxvd.cn/Article/details/gtavzrgsmz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jiagoushi.top/Article/details/gtupjuoxjy.html

[J08] 提取年月日与星期
来源：http://dali.yuanzhike.top/Article/details/gtnpwnrqst.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.chenlongwang.top/Article/details/gtcutrvvbv.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cqqwz.cn/Article/details/gtaynvumbh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sysykeji.top/Article/details/gtxzcuovhe.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yvedp.cn/Article/details/gtlxhhesbw.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hfpthk.cn/Article/details/gtkqhqidxq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ppjwa.cn/Article/details/gtauyqeijb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hammf.cn/Article/details/gttivsvtsr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjgmkfnxx.html

[J09] 时区处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gttkkjboqz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hongshengwenyu.top/Article/details/gtljsshmfq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.9152youxi.cn/Article/details/gtqhmncsoa.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinghuilouyu.cn/Article/details/gteqjfglha.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yanxiufei.cn/Article/details/gtgsejmzvv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.wangdashe.top/Article/details/gtjatgrhyi.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yangfankeji.com/Article/details/gtxnntvjdm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yongpay.top/Article/details/gtraqoszqj.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cheryme.top/Article/details/gtnbnovsgf.html

[J10] 取今天 / 本月第一天
来源：http://dali.quarkkingdee.top/Article/details/gtfnjrlkze.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.haohaochexian.top/Article/details/gtakywqqak.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shzxlz.cn/Article/details/gtdtqulwej.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sufxvd.cn/Article/details/gtgychuzim.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.birdmap.top/Article/details/gtyrlsaufj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hysaishi.cn/Article/details/gtgzimmldz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shanyushiyangtech.top/Article/details/gtwzzfznog.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.daxiang520.top/Article/details/gtsqjiwihh.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zdqjudy.top/Article/details/gtejegqvgz.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtxmskmddl.html

K. JSON 与序列化
来源：http://dali.tanke756.top/Article/details/gtweuvpcry.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtbiqrzwll.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwybaohqm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttrvcnnoc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.pycfn.com/Article/details/gtcigyiren.html

JS:   JSON.stringify(obj)
来源：http://dali.zhixingplan.top/Article/details/gtwfpzcogu.html

TS:   JSON.stringify(obj)
来源：http://dali.yj202588.top/Article/details/gtykwgqtml.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yuxming.cn/Article/details/gttghvoikm.html

Go:   json.Marshal(obj)
来源：http://dali.tianlin.xyz/Article/details/gtovjlngow.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.0kj1m.cn/Article/details/gtknfvywbm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jianghu66.top/Article/details/gtyyxtfkgd.html

[K02] JSON 字符串转对象
来源：http://dali.tianlin.xyz/Article/details/gtdhmflprp.html

Py:   json.loads(s)
来源：http://dali.yj202588.top/Article/details/gtdzvsrjwl.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.guannengcc.top/Article/details/gtpveeewsa.html

JS:   JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gtyaydesmy.html

TS:   JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gtfuhmaylr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shuidangran.top/Article/details/gtxqrnksdi.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yongpay.top/Article/details/gtgofpsjay.html

Ruby: JSON.parse(s)
来源：http://dali.zhongyouzk.top/Article/details/gtjrprbive.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.quarkkingdee.top/Article/details/gtzsnqrjwk.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cdnleiting.top/Article/details/gtkppnvlgy.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.haohaochexian.top/Article/details/gtuwtbmdic.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.tian-w.cn/Article/details/gttjjgmrep.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.pycfn.com/Article/details/gtgdpmioso.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthgkmgtfo.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtgspvjifm.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.snrcjt.cn/Article/details/gtytvccqzm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yj202588.top/Article/details/gtbjaurkeb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sweek.top/Article/details/gtlaylnafv.html

[K04] 读取 JSON 文件
来源：http://dali.jiagoushi.top/Article/details/gtvdsnqywt.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.c1oappe.top/Article/details/gtcowaaban.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.nwbrower.top/Article/details/gttmmltbxe.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenjidiqi.icu/Article/details/gtqmwhdfzl.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gzhubu.top/Article/details/gtupdzhhjx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhengqikj.top/Article/details/gtrxvojpfg.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.daxiang520.top/Article/details/gtawjczwza.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yuanzhike.top/Article/details/gtbefhmzis.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yj202588.top/Article/details/gtwoyjwmff.html

[K05] 深拷贝对象
来源：http://dali.xuanzx.com/Article/details/gtticpajzo.html

Py:   copy.deepcopy(obj)
来源：http://dali.ppjwa.cn/Article/details/gtgunwtkvi.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hysaishi.cn/Article/details/gtqizdikkv.html

JS:   structuredClone(obj)
来源：http://dali.jianghu66.top/Article/details/gtnsgshmhq.html

TS:   structuredClone(obj)
来源：http://dali.nanxinkj.top/Article/details/gtksvrgysv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.aizwys.cn/Article/details/gtqnolyokl.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cdnleiting.top/Article/details/gtfhmacjay.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.chenzaomai.com/Article/details/gtstqgfnun.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yangfankeji.com/Article/details/gtsjcngdfw.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gtrldpvcnn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yonumen.top/Article/details/gtedhmrzbm.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhengqikj.top/Article/details/gtufsfxjkk.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuanzhike.top/Article/details/gteuvsjrrv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxinkj.top/Article/details/gtxbkrxkmn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hongshengwenyu.top/Article/details/gtudtwiyoj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtknbirlzk.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ppjwa.cn/Article/details/gtmdwmonye.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkxnddymq.html

[K07] 进制转换
来源：http://dali.tian-w.cn/Article/details/gtmhqhmsey.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvkpcygnf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jqgfzy.top/Article/details/gtauemgrfx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gtnukqlque.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtfmslhuqi.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwnvrwvbd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.mhx1999.top/Article/details/gtkzrnfnkt.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.meibo888.top/Article/details/gtszkumwem.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdzkfkaqq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.mhx1999.top/Article/details/gteenpyxdf.html

Py:   pickle.dumps(obj)
来源：http://dali.gotoacloud.top/Article/details/gthrkdzqdn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nanxuanxn.top/Article/details/gtwckitqmm.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xinyue.icu/Article/details/gttumyluvi.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hfpthk.cn/Article/details/gtbljtrfgq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sufxvd.cn/Article/details/gtobiakdha.html

Go:   encoding/gob
来源：http://dali.jianghu66.top/Article/details/gtmbyhfocq.html

Ruby: Marshal.dump(obj)
来源：http://dali.dianchejie.cn/Article/details/gtyhuizmbd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhiwuduotai.top/Article/details/gtunrkxzed.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtwysmyepk.html

L. 网络请求
来源：http://dali.shzxlz.cn/Article/details/gtnlrugxqq.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtunyjoaiu.html

[L01] 发送 GET 请求
来源：http://dali.fengsongda.top/Article/details/gtsqgxcyew.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ybcxt.top/Article/details/gtzpsxomam.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gaohongyu789.top/Article/details/gthljvztqt.html

JS:   await fetch(url)
来源：http://dali.aibaodan.cn/Article/details/gtuhsxryys.html

TS:   await fetch(url)
来源：http://dali.guannengcc.top/Article/details/gtqhxqodra.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.nwbrower.top/Article/details/gtaexbzldr.html

Go:   resp, err := http.Get(url)
来源：http://dali.yuanzhike.top/Article/details/gtthpdxbwa.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinghuilouyu.cn/Article/details/gtydwaekbf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xziqi.cn/Article/details/gtwiarkhrf.html

[L02] 发送 POST JSON
来源：http://dali.zhengqikj.top/Article/details/gtzbdjbeue.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.kuanghao11.cn/Article/details/gtqycbxzbi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.vqdsnc.cn/Article/details/gtdmznxeiq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgfzy.top/Article/details/gtkkqknccs.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.redwolf501.top/Article/details/gtiijrdcwh.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ybcxt.top/Article/details/gtvbigcghb.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hnqzz.top/Article/details/gtqyjqavmp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhengqikj.top/Article/details/gtdftqvxlz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ybcxt.top/Article/details/gtpmelbgzc.html

[L03] 设置自定义请求头
来源：http://dali.nanxuanxn.top/Article/details/gtvfenuqzv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gtiymhwljj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinqigufen.top/Article/details/gtyycljcpy.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.havefunace.top/Article/details/gtfazrvhos.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhoulong.xyz/Article/details/gtptspfngk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gaohongyu789.top/Article/details/gtcgieolxp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xylfe.cn/Article/details/gtjpwsfpwh.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xylfe.cn/Article/details/gtddldjoll.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.316326.xyz/Article/details/gtokeqhaoe.html

[L04] 设置超时
来源：http://dali.quarkkingdee.top/Article/details/gtodkltiby.html

Py:   requests.get(url, timeout=5)
来源：http://dali.nwbrower.top/Article/details/gtfladsivg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.smart0.xyz/Article/details/gtnpneiswh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jqgufenzy.top/Article/details/gtavffrilq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aizwys.cn/Article/details/gtmxnvfppv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ybcxt.top/Article/details/gtfypjlgnq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.c1oappe.top/Article/details/gtzsyxztet.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.svipenyu.cn/Article/details/gtxiffflbb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gzhubu.top/Article/details/gtbexhybcj.html

[L05] 上传文件（multipart）
来源：http://dali.jinqigufen.top/Article/details/gtrlcjpsci.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xinyue.icu/Article/details/gtvumhvjff.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj20258.top/Article/details/gtayucnmpo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.c1oappe.top/Article/details/gtyfgdekjx.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.tian-w.cn/Article/details/gtczamiovp.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cashguo.top/Article/details/gtsxirgsog.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.0kj1m.cn/Article/details/gtgcbtxgpz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.meibo888.top/Article/details/gtxusggiqb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtpxyjgart.html

[L06] 解析响应为 JSON
来源：http://dali.svipenyu.cn/Article/details/gtqbjxkpkk.html

Py:   resp.json()
来源：http://dali.wangdashe.top/Article/details/gtjmqkxbeq.html

PHP:  json_decode($body, true);
来源：http://dali.zhengqikj.top/Article/details/gtswwbttaj.html

JS:   await resp.json()
来源：http://dali.dashuyun.cn/Article/details/gtngkjwmcy.html

TS:   await resp.json()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqecodxtx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jyoumei.cn/Article/details/gtrpxvyjhh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cheryme.top/Article/details/gthzrtrhah.html

Ruby: JSON.parse(resp.body)
来源：http://dali.tian-w.cn/Article/details/gtsvjqpqon.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlmzkpdrf.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhongyouzk.top/Article/details/gtmewpcags.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hongshengwenyu.top/Article/details/gtvwdannoq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yuxming.cn/Article/details/gtcqjxrjou.html

JS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkqklgvrz.html

TS:   resp.ok;  resp.status
来源：http://dali.zdqjudy.top/Article/details/gtxyhnmhsa.html

Java: resp.statusCode()
来源：http://dali.ivvv.top/Article/details/gtbejqudwf.html

Go:   resp.StatusCode
来源：http://dali.zdqjudy.top/Article/details/gtbjwcqybx.html

Ruby: resp.code.to_i
来源：http://dali.hywenlv.cn/Article/details/gtftuvcfep.html

C#:   (int)resp.StatusCode
来源：http://dali.gzhubu.top/Article/details/gtqmnongyt.html

[L08] 并发请求多个地址
来源：http://dali.zdqjudy.top/Article/details/gtkajcsnlc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.fzhhl.top/Article/details/gtficovmoa.html

PHP:  curl_multi_init() 系列
来源：http://dali.hnqzz.top/Article/details/gtkjsclxxq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guannengcc.top/Article/details/gthpvwbqdj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gtafkxyohw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yuanzhike.top/Article/details/gtbdimvzms.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jqgufenzy.top/Article/details/gtwingvnon.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ybcxt.top/Article/details/gtbfndwpoc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.daxiang520.top/Article/details/gtceuitiad.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtzzracjya.html

M. 命令行 / 进程 / 环境
来源：http://dali.dianchejie.cn/Article/details/gtbmihhsbk.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gteexqsosn.html

[M01] 读取命令行参数
来源：http://dali.sxryk.cn/Article/details/gtiaeczwtg.html

Py:   sys.argv[1:]
来源：http://dali.hnxiangtu.top/Article/details/gtlwygidkw.html

PHP:  $argv;  $argc;
来源：http://dali.c1oappe.top/Article/details/gtpnirmbgm.html

JS:   process.argv.slice(2)
来源：http://dali.chenjidiqi.icu/Article/details/gtxehkqdaa.html

TS:   process.argv.slice(2)
来源：http://dali.aibaodan.cn/Article/details/gtybwhujvv.html

Java: args 数组（main 方法参数）
来源：http://dali.xylfe.cn/Article/details/gtmcplxqnj.html

Go:   os.Args[1:]
来源：http://dali.hnqzz.top/Article/details/gtepmqssrf.html

Ruby: ARGV
来源：http://dali.chenjidiqi.icu/Article/details/gtbrgcbzdx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yvedp.cn/Article/details/gtenqbpadw.html

[M02] 读取环境变量
来源：http://dali.chenjidiqi.icu/Article/details/gtfclwmkja.html

Py:   os.environ.get("HOME")
来源：http://dali.cucudq.cn/Article/details/gtaltxmvgd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.andypj.xyz/Article/details/gtgkxtkkmc.html

JS:   process.env.HOME
来源：http://dali.shuidangran.top/Article/details/gtwfcndrzh.html

TS:   process.env.HOME
来源：http://dali.nanxuanxn.top/Article/details/gtnqiuubuh.html

Java: System.getenv("HOME")
来源：http://dali.iojbl.cn/Article/details/gtbcisafbk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jqgfzy.top/Article/details/gtlxhsswdk.html

Ruby: ENV["HOME"]
来源：http://dali.shanyushiyangtech.top/Article/details/gtwcwdobmj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gtfatdrtzp.html

[M03] 执行外部命令
来源：http://dali.cqqwz.cn/Article/details/gtzqiyjppq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sufxvd.cn/Article/details/gttzzicbgh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.wangdashe.top/Article/details/gtpqowvees.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gotoacloud.top/Article/details/gtwjygodit.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.mhx1999.top/Article/details/gtqfutsfgs.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.bjfxy.top/Article/details/gtztwkabux.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhixingplan.top/Article/details/gtvoqqumrd.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shuidangran.top/Article/details/gtqpmobgeu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yanxiufei.cn/Article/details/gtocvebzgc.html

[M04] 获取当前工作目录
来源：http://dali.ybcxt.top/Article/details/gtptlbfuiq.html

Py:   os.getcwd()
来源：http://dali.zycfv.cn/Article/details/gtortmszly.html

PHP:  getcwd();
来源：http://dali.ydzc1.top/Article/details/gtatyhvlxl.html

JS:   process.cwd()
来源：http://dali.gaohongyu789.top/Article/details/gtkkezrzam.html

TS:   process.cwd()
来源：http://dali.0kj1m.cn/Article/details/gtmkvlbvnb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtilvgcrpp.html

Go:   os.Getwd()
来源：http://dali.gzhubu.top/Article/details/gtjpqzbmub.html

Ruby: Dir.pwd
来源：http://dali.guowangkeji.top/Article/details/gtkzyfhjnb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yj20258.top/Article/details/gtpozwsknw.html

[M05] 设置退出码
来源：http://dali.zycfv.cn/Article/details/gtlgcsqnjx.html

Py:   sys.exit(1)
来源：http://dali.daria6918.cn/Article/details/gtbxspzmsg.html

PHP:  exit(1);
来源：http://dali.hammf.cn/Article/details/gtrtqfyyxt.html

JS:   process.exit(1)
来源：http://dali.cheryme.top/Article/details/gtkwnsrkmj.html

TS:   process.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtprktxkzd.html

Java: System.exit(1)
来源：http://dali.zycfv.cn/Article/details/gtvhjigigb.html

Go:   os.Exit(1)
来源：http://dali.fengsongda.top/Article/details/gtcrkzpgjn.html

Ruby: exit 1
来源：http://dali.gaohongyu789.top/Article/details/gtkrvyeqza.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiyngqdfo.html

[M06] 向标准错误输出
来源：http://dali.nanxinkj.top/Article/details/gtiwwaaccb.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hfpthk.cn/Article/details/gtfdlvbfrw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.bjfxy.top/Article/details/gtzloyeknw.html

JS:   console.error("err")
来源：http://dali.jqgfzy.top/Article/details/gtlkrjbyas.html

TS:   console.error("err")
来源：http://dali.aizwys.cn/Article/details/gtakymapec.html

Java: System.err.println("err")
来源：http://dali.smart0.xyz/Article/details/gtkjusxcpk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ydzc1.top/Article/details/gtaoxhpzzs.html

Ruby: warn "err"
来源：http://dali.wangdashe.top/Article/details/gtugmbrgkw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.smart0.xyz/Article/details/gtblpuxgki.html

[M07] 判断是否为主入口
来源：http://dali.quarkkingdee.top/Article/details/gtebytbprv.html

Py:   if __name__ == "__main__":
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdhqromof.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cdnleiting.top/Article/details/gtjidcbyvg.html

JS:   require.main === module
来源：http://dali.aibaodan.cn/Article/details/gtvrqlcozd.html

TS:   require.main === module
来源：http://dali.xinyue.icu/Article/details/gtrpwxqsue.html

Java: public static void main(String[] args)
来源：http://dali.sweek.top/Article/details/gtcdmnqpsv.html

Go:   func main()
来源：http://dali.ybcxt.top/Article/details/gtamyupgbt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tanke756.top/Article/details/gtnuhzquzy.html

C#:   static void Main(string[] args)
来源：http://dali.jqgufenzy.top/Article/details/gtscfqjros.html

[M08] 获取系统与运行时信息
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbcpqrpxf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yangfankeji.com/Article/details/gtnokcxerz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shangyingyoupin.top/Article/details/gtgpaiaqjm.html

JS:   process.platform;  process.version
来源：http://dali.fengsongda.top/Article/details/gtvtrfqofp.html

TS:   process.platform;  process.version
来源：http://dali.hammf.cn/Article/details/gtjrigkjna.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cucudq.cn/Article/details/gtvjuuwuzz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jianghu66.top/Article/details/gtfilwuugd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.tianlin.xyz/Article/details/gtfpxzeojj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hammf.cn/Article/details/gtsktnpiis.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtjqfvvook.html

N. 数据结构与算法
来源：http://dali.yj202588.top/Article/details/gtyrricjbv.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtbojnprhb.html

[N01] 二分查找（有序数组）
来源：http://dali.havefunace.top/Article/details/gtvsahhbdb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yonumen.top/Article/details/gtworccuqy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.daria6918.cn/Article/details/gtiqexmdft.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cqqwz.cn/Article/details/gtlybltehs.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ehwqpu.com/Article/details/gttvgkorqc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtaxexrywt.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtdcbvjdfz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nanxinkj.top/Article/details/gtrdlcfpws.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdvtpxzbo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xylfe.cn/Article/details/gtrkbjmlev.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sweek.top/Article/details/gtcsubiiti.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zdqjudy.top/Article/details/gtaskywpwl.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gaohongyu789.top/Article/details/gtbyugslhm.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dashuyun.cn/Article/details/gtmvnfqxyi.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zdqjudy.top/Article/details/gtnehqhary.html

Go:   slices.Sort(arr)
来源：http://dali.sufxvd.cn/Article/details/gtbdfrsaux.html

Ruby: arr.sort
来源：http://dali.yuxming.cn/Article/details/gtzowsqosq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hnxiangtu.top/Article/details/gttijjnczw.html

[N03] 快速排序（分治示例）
来源：http://dali.yvedp.cn/Article/details/gttgxowerk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hongshengwenyu.top/Article/details/gtqqbfcjan.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gtavdonrhk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dianchejie.cn/Article/details/gthxpugbgm.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhongyouzk.top/Article/details/gtgohkodqc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ydzc1.top/Article/details/gtodmuwgxi.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.guowangkeji.top/Article/details/gtiblprarz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.c1oappe.top/Article/details/gtgdahfayu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ydzc1.top/Article/details/gtxqxcunre.html

[N04] 斐波那契数列
来源：http://dali.wangshuangyany.cn/Article/details/gtoplfoovc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hammf.cn/Article/details/gtablzzuxw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaxybsore.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cqqwz.cn/Article/details/gtxuulpanr.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gtmusmpovw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hywenlv.cn/Article/details/gtvwuyotcb.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.pycfn.com/Article/details/gtcojlolwu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.wangdashe.top/Article/details/gthkyolicu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.haohaochexian.top/Article/details/gtjokxlera.html

[N05] 最大公约数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqfbcqqbx.html

Py:   math.gcd(a, b)
来源：http://dali.cashguo.top/Article/details/gtijnupcqu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gogol.net.cn/Article/details/gtnghcckaf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jyoumei.cn/Article/details/gtvczpqqrq.html


<!-- 参考信息 -->