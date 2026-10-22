代发 wailian999

[J07] 比较两个日期
来源：http://dali.aibaodan.cn/Article/details/gtdlolpnsc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gogol.net.cn/Article/details/gtclqduvck.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ybcxt.top/Article/details/gtnvjuvjye.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.daxiang520.top/Article/details/gtwhobxpju.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yongpay.top/Article/details/gtoibhuopc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkpjzxxzb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hywenlv.cn/Article/details/gtulwrkzoj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.pengpengdd.cyou/Article/details/gtkxvtjenp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yj20258.top/Article/details/gtondbcyeg.html

[J08] 提取年月日与星期
来源：http://dali.hammf.cn/Article/details/gtxzytkaea.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zdqjudy.top/Article/details/gtrgztijma.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xinyue.icu/Article/details/gtydkhnmwq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcwcgykou.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hywenlv.cn/Article/details/gtrysdlcjk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.redwolf501.top/Article/details/gtpikbjywk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.nwbrower.top/Article/details/gtsvdlfkrc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.andypj.xyz/Article/details/gtbobysanh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jqgfzy.top/Article/details/gtypioclgz.html

[J09] 时区处理
来源：http://dali.vqdsnc.cn/Article/details/gtxlueuggg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.kuanghao11.cn/Article/details/gtezltzagv.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yuanzhike.top/Article/details/gthybcwcqh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigufen.top/Article/details/gtudjtvcin.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gzhubu.top/Article/details/gteqmmondl.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gotoacloud.top/Article/details/gttbfiruim.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cheryme.top/Article/details/gtbynpekti.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hnqzz.top/Article/details/gttqvijbtc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shzxlz.cn/Article/details/gtfnaizkwk.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj20258888.top/Article/details/gtkbgknoqx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hammf.cn/Article/details/gtjevmpcwk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yueranfly.top/Article/details/gtttnbgtxb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.nanxuanxn.top/Article/details/gttonrilxq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hfpthk.cn/Article/details/gtiyhkojpj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.dianchejie.cn/Article/details/gthmrilllg.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yvedp.cn/Article/details/gtsigdvzcg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sysykeji.top/Article/details/gteeklmrys.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhoulong.xyz/Article/details/gtcbzdndze.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtvuhavfmc.html

K. JSON 与序列化
来源：http://dali.yj20258.top/Article/details/gtofccjjci.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtccwhfdeq.html

[K01] 对象转 JSON 字符串
来源：http://dali.dianchejie.cn/Article/details/gtuvwtvjcm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.0kj1m.cn/Article/details/gtginfiznk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxuanxn.top/Article/details/gtxhqtefxd.html

JS:   JSON.stringify(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtbnusqlal.html

TS:   JSON.stringify(obj)
来源：http://dali.chenzaomai.com/Article/details/gtvpbyvppg.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cdnleiting.top/Article/details/gtqqohjnxi.html

Go:   json.Marshal(obj)
来源：http://dali.xinyue.icu/Article/details/gtshhgixxx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.nwbrower.top/Article/details/gtvubxqhev.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.snrcjt.cn/Article/details/gtjbsdojhi.html

[K02] JSON 字符串转对象
来源：http://dali.cucudq.cn/Article/details/gtdmghhiax.html

Py:   json.loads(s)
来源：http://dali.yongpay.top/Article/details/gtpxnybtmk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xuanzx.com/Article/details/gttisvqyjb.html

JS:   JSON.parse(s)
来源：http://dali.hnqzz.top/Article/details/gtohqchqpz.html

TS:   JSON.parse(s)
来源：http://dali.yueranfly.top/Article/details/gtljvyedqh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhengqikj.top/Article/details/gtwdzxmtxz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaevqyqlk.html

Ruby: JSON.parse(s)
来源：http://dali.jqgfzy.top/Article/details/gtpxjdrrxz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.dashuyun.cn/Article/details/gtjrpjhhsf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.dianchejie.cn/Article/details/gtihlomikm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gzhubu.top/Article/details/gtpljceczy.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.bjfxy.top/Article/details/gtoenquxoe.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shuidangran.top/Article/details/gtzuciwlew.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yanxiufei.cn/Article/details/gtlhlqbukt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.havefunace.top/Article/details/gtupgianer.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjujifvkq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.nanxinkj.top/Article/details/gtguxkbaoz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.kuanghao11.cn/Article/details/gtsggyoown.html

[K04] 读取 JSON 文件
来源：http://dali.meibo888.top/Article/details/gtjbpsvzdh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxuctrmbz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shuidangran.top/Article/details/gthwyvanyz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nwbrower.top/Article/details/gtwfoqgjax.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jqgfzy.top/Article/details/gtudhvlpuv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nwbrower.top/Article/details/gttpbxfgaz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shzxlz.cn/Article/details/gtohfnmizw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shuidangran.top/Article/details/gtwcavoxcx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yvedp.cn/Article/details/gtnwzrgovn.html

[K05] 深拷贝对象
来源：http://dali.sysykeji.top/Article/details/gtwujbvnoo.html

Py:   copy.deepcopy(obj)
来源：http://dali.smart0.xyz/Article/details/gtaeulkvtz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cdnleiting.top/Article/details/gtrxickvnw.html

JS:   structuredClone(obj)
来源：http://dali.hfpthk.cn/Article/details/gtscvsiptz.html

TS:   structuredClone(obj)
来源：http://dali.tanke756.top/Article/details/gtbfxjeycj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.iojbl.cn/Article/details/gtepbzwzrs.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.mhx1999.top/Article/details/gtizxnycuz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ybcxt.top/Article/details/gtxzcwjcam.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gtprtoxhab.html

[K06] 解析 URL 查询串
来源：http://dali.svipenyu.cn/Article/details/gtmywwqrze.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hywenlv.cn/Article/details/gthhvwdwbk.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shuidangran.top/Article/details/gtrqqwwyjb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangshuangyany.cn/Article/details/gtgubfybhl.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cashguo.top/Article/details/gtelkumbsf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.aizwys.cn/Article/details/gtxzdwonwx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.feifeiyinyue.top/Article/details/gtzzqpgejs.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.nwbrower.top/Article/details/gtsfdstmha.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.nanxinkj.top/Article/details/gtlcvpwtsl.html

[K07] 进制转换
来源：http://dali.nanxinkj.top/Article/details/gtolayokpx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gtrtieqsvl.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtguwqyozi.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gtvxxrxhtc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gtmecpxkar.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gtqurwpvji.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xuanzx.com/Article/details/gtxbfvzliq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cheryme.top/Article/details/gtwgzjuikf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.havefunace.top/Article/details/gtsvbdjdju.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gtegswjigh.html

Py:   pickle.dumps(obj)
来源：http://dali.yongpay.top/Article/details/gtcjtpegda.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.316326.xyz/Article/details/gtdxikyxhw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.guowangkeji.top/Article/details/gthcgnooco.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hammf.cn/Article/details/gtcrgubduy.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.nanxuanxn.top/Article/details/gtntbnkcno.html

Go:   encoding/gob
来源：http://dali.yonumen.top/Article/details/gtwbehwuft.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtezzhjcuq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yanxiufei.cn/Article/details/gtflocsfuw.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtwgdenqwz.html

L. 网络请求
来源：http://dali.tanke756.top/Article/details/gtfyhrnlge.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtzwbkuqyi.html

[L01] 发送 GET 请求
来源：http://dali.chenzaomai.com/Article/details/gtldiztopy.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.pengpengdd.cyou/Article/details/gtohmdoumd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hnxiangtu.top/Article/details/gtufhtcurg.html

JS:   await fetch(url)
来源：http://dali.yangfankeji.com/Article/details/gtcxvccocz.html

TS:   await fetch(url)
来源：http://dali.feifeiyinyue.top/Article/details/gtmcjzoioo.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gzhubu.top/Article/details/gtowtggcjb.html

Go:   resp, err := http.Get(url)
来源：http://dali.cqqwz.cn/Article/details/gtyfphoiom.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hfpthk.cn/Article/details/gtfgaklpky.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.birdmap.top/Article/details/gtysllynkv.html

[L02] 发送 POST JSON
来源：http://dali.redwolf501.top/Article/details/gtoctksdfo.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xuetiantiany.cn/Article/details/gtcxqacswl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jlsjyb.cn/Article/details/gtjfkbhkam.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj202588.top/Article/details/gtxkckfttz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guannengcc.top/Article/details/gtppcbsbfa.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gaohongyu789.top/Article/details/gtssvjyhnc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.bjfxy.top/Article/details/gtikgujwnz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.dashuyun.cn/Article/details/gtupnatskf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhiwuduotai.top/Article/details/gtajxoeykl.html

[L03] 设置自定义请求头
来源：http://dali.9152youxi.cn/Article/details/gtyztzaftx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yuxming.cn/Article/details/gtelfpgomu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.svipenyu.cn/Article/details/gtfjenzfwz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yvedp.cn/Article/details/gtbqvpluxg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nwbrower.top/Article/details/gtcolctdjz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.9152youxi.cn/Article/details/gttfoklncd.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpfdxecni.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shuidangran.top/Article/details/gtitqnlnoh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shanyushiyangtech.top/Article/details/gtucbyczdj.html

[L04] 设置超时
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxliextsk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hnqzz.top/Article/details/gtcsgwkpjp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shzxlz.cn/Article/details/gtcwljkpny.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangdashe.top/Article/details/gtirvuccae.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jianghu66.top/Article/details/gtwzsjnwwf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.guowangkeji.top/Article/details/gtrbkxfujx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.redwolf501.top/Article/details/gtjruxstvy.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sweek.top/Article/details/gtiyvbeeat.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gaohongyu789.top/Article/details/gtryvsquxh.html

[L05] 上传文件（multipart）
来源：http://dali.yonumen.top/Article/details/gtfdgkgzem.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.aibaodan.cn/Article/details/gtmuihmvlt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sysykeji.top/Article/details/gtcbhxzgpj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuetiantiany.cn/Article/details/gtcbxjfpbt.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenzaomai.com/Article/details/gtirnahweq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqppnkptp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yongpay.top/Article/details/gtxhegqgdm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.dashuyun.cn/Article/details/gtolbouvaz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtjgnonata.html

[L06] 解析响应为 JSON
来源：http://dali.316326.xyz/Article/details/gtxotlbfrq.html

Py:   resp.json()
来源：http://dali.dashuyun.cn/Article/details/gtmpmiznwl.html

PHP:  json_decode($body, true);
来源：http://dali.xuanzx.com/Article/details/gtihiyqefp.html

JS:   await resp.json()
来源：http://dali.dianchejie.cn/Article/details/gtcdqumdnv.html

TS:   await resp.json()
来源：http://dali.chenlongwang.top/Article/details/gtxacllqzf.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.bjfxy.top/Article/details/gttkmcivqn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cashguo.top/Article/details/gtnxdrxjch.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sufxvd.cn/Article/details/gtnodjlegc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinyuanbaomall.cn/Article/details/gteqgxrtcd.html

[L07] 处理 HTTP 状态码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqydftxhy.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.guannengcc.top/Article/details/gtrowtdzgd.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nanxuanxn.top/Article/details/gtbtbnlljl.html

JS:   resp.ok;  resp.status
来源：http://dali.svipenyu.cn/Article/details/gtmcfsrjup.html

TS:   resp.ok;  resp.status
来源：http://dali.svipenyu.cn/Article/details/gtifiauuxv.html

Java: resp.statusCode()
来源：http://dali.nanxuanxn.top/Article/details/gtenpmslrx.html

Go:   resp.StatusCode
来源：http://dali.wangdashe.top/Article/details/gtadktlhzh.html

Ruby: resp.code.to_i
来源：http://dali.hywenlv.cn/Article/details/gtqxnwdhqa.html

C#:   (int)resp.StatusCode
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjplaztjv.html

[L08] 并发请求多个地址
来源：http://dali.feifeiyinyue.top/Article/details/gtytpleffx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yuxming.cn/Article/details/gtajmobotu.html

PHP:  curl_multi_init() 系列
来源：http://dali.hysaishi.cn/Article/details/gtjbpgpyca.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gtnvlzsbez.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.vqdsnc.cn/Article/details/gtlkdcsdqc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cdnleiting.top/Article/details/gtctvhyjhi.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.andypj.xyz/Article/details/gtsimqzemc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwfzkvgbc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.quarkkingdee.top/Article/details/gtrurffolp.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtstynmgsl.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinqigufen.top/Article/details/gtwultlccx.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtwoausice.html

[M01] 读取命令行参数
来源：http://dali.gotoacloud.top/Article/details/gtqpburefy.html

Py:   sys.argv[1:]
来源：http://dali.zdqjudy.top/Article/details/gtxurmkbab.html

PHP:  $argv;  $argc;
来源：http://dali.yj20258888.top/Article/details/gtazuaslod.html

JS:   process.argv.slice(2)
来源：http://dali.jinqigufen.top/Article/details/gtslrhuqry.html

TS:   process.argv.slice(2)
来源：http://dali.sweek.top/Article/details/gtrncebrnp.html

Java: args 数组（main 方法参数）
来源：http://dali.gotoacloud.top/Article/details/gttmuunbxu.html

Go:   os.Args[1:]
来源：http://dali.xinyue.icu/Article/details/gtqnaeirot.html

Ruby: ARGV
来源：http://dali.feifeiyinyue.top/Article/details/gtwpifvhvu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.fengsongda.top/Article/details/gtwnwlwcmw.html

[M02] 读取环境变量
来源：http://dali.yj202588.top/Article/details/gtadfshhsh.html

Py:   os.environ.get("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gtlzgfjlvv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.chenlongwang.top/Article/details/gtzhcwwwuh.html

JS:   process.env.HOME
来源：http://dali.fengsongda.top/Article/details/gtowynfyrb.html

TS:   process.env.HOME
来源：http://dali.hongshengwenyu.top/Article/details/gtyzrcgjju.html

Java: System.getenv("HOME")
来源：http://dali.ivvv.top/Article/details/gtrpygquvt.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yuanzhike.top/Article/details/gtadlpityy.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gtvfrvgoxh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.andypj.xyz/Article/details/gtuijafujs.html

[M03] 执行外部命令
来源：http://dali.mhx1999.top/Article/details/gtjsietxmz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.0kj1m.cn/Article/details/gtgfqkamvp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.dianchejie.cn/Article/details/gthdbxiphh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.tanke756.top/Article/details/gtrglzekpa.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenjidiqi.icu/Article/details/gtciimcpnj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ybcxt.top/Article/details/gtzkgknbqk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhengqikj.top/Article/details/gtxkxwmgsx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.c1oappe.top/Article/details/gtouenqqmd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cucudq.cn/Article/details/gtdzkygddp.html

[M04] 获取当前工作目录
来源：http://dali.c1oappe.top/Article/details/gtkthjcntl.html

Py:   os.getcwd()
来源：http://dali.zycfv.cn/Article/details/gtxhpaxxly.html

PHP:  getcwd();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzhiwazqz.html

JS:   process.cwd()
来源：http://dali.zycfv.cn/Article/details/gtpljnphks.html

TS:   process.cwd()
来源：http://dali.cqqwz.cn/Article/details/gtaenxwsxo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ppjwa.cn/Article/details/gtwyhhtayf.html

Go:   os.Getwd()
来源：http://dali.shangyingyoupin.top/Article/details/gtnegtdejc.html

Ruby: Dir.pwd
来源：http://dali.chenjidiqi.icu/Article/details/gtffqctqxz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cdnleiting.top/Article/details/gthuaoqtio.html

[M05] 设置退出码
来源：http://dali.hysaishi.cn/Article/details/gtuaxgnedd.html

Py:   sys.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtnzkgeoqq.html

PHP:  exit(1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpmhthwph.html

JS:   process.exit(1)
来源：http://dali.yj202588.top/Article/details/gtqyimxhpu.html

TS:   process.exit(1)
来源：http://dali.havefunace.top/Article/details/gtiwijecqe.html

Java: System.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gtnjumeaco.html

Go:   os.Exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gtskvavdbz.html

Ruby: exit 1
来源：http://dali.kuanghao11.cn/Article/details/gtizodrkdh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.wangdashe.top/Article/details/gtuzvudhvz.html

[M06] 向标准错误输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqaycgajn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sysykeji.top/Article/details/gttxdgqhxj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.haohaochexian.top/Article/details/gtuhaxxuvu.html

JS:   console.error("err")
来源：http://dali.xziqi.cn/Article/details/gtqjifbhik.html

TS:   console.error("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtyikowiid.html

Java: System.err.println("err")
来源：http://dali.birdmap.top/Article/details/gtyzjnrmrr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhixingplan.top/Article/details/gthqizgtbw.html

Ruby: warn "err"
来源：http://dali.hnxiangtu.top/Article/details/gtqrsorkuu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jlsjyb.cn/Article/details/gtwyiauluw.html

[M07] 判断是否为主入口
来源：http://dali.yongpay.top/Article/details/gtyrjudiaw.html

Py:   if __name__ == "__main__":
来源：http://dali.zdqjudy.top/Article/details/gtdlpjdtwr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ehwqpu.com/Article/details/gtrvxikqnr.html

JS:   require.main === module
来源：http://dali.9152youxi.cn/Article/details/gtydbjwtzq.html

TS:   require.main === module
来源：http://dali.zhongyouzk.top/Article/details/gtzghchqkh.html

Java: public static void main(String[] args)
来源：http://dali.ydzc1.top/Article/details/gtozbitrev.html

Go:   func main()
来源：http://dali.redwolf501.top/Article/details/gtvwixuxki.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.birdmap.top/Article/details/gtdcnjcghm.html

C#:   static void Main(string[] args)
来源：http://dali.iojbl.cn/Article/details/gtgeelkggo.html

[M08] 获取系统与运行时信息
来源：http://dali.sweek.top/Article/details/gtgxqpofof.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinqigfzy.top/Article/details/gtlcycgsxk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinghuilouyu.cn/Article/details/gtmpejqslw.html

JS:   process.platform;  process.version
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzhbryzrz.html

TS:   process.platform;  process.version
来源：http://dali.shzxlz.cn/Article/details/gtpuykzsrr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhixingplan.top/Article/details/gtgmwihczu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.quarkkingdee.top/Article/details/gtwtwybxwy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gaohongyu789.top/Article/details/gtyulpmgzb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shangyingyoupin.top/Article/details/gtrfppybit.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtearshkbm.html

N. 数据结构与算法
来源：http://dali.zycfv.cn/Article/details/gtoiuvcssd.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtflwbdlvd.html

[N01] 二分查找（有序数组）
来源：http://dali.316326.xyz/Article/details/gtczrgmlxt.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.fengsongda.top/Article/details/gtcfxkhsvg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.pycfn.com/Article/details/gtuhjxdlyz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tianlin.xyz/Article/details/gtlephslak.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fzhhl.top/Article/details/gtvyfxlkdm.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbesaqtpz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yueranfly.top/Article/details/gtfsksyvlu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jqgufenzy.top/Article/details/gtjyepveqp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.meibo888.top/Article/details/gtnfwphcxh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sufxvd.cn/Article/details/gtwskdoylm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtugcwdxgy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfhwdeign.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gaohongyu789.top/Article/details/gtbencnyuf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuanzx.com/Article/details/gtnqwsqdnm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinqigfzy.top/Article/details/gtbrimjana.html

Go:   slices.Sort(arr)
来源：http://dali.sysykeji.top/Article/details/gtilldudwf.html

Ruby: arr.sort
来源：http://dali.ehwqpu.com/Article/details/gtdvuwcwdu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.guannengcc.top/Article/details/gtmprpucow.html

[N03] 快速排序（分治示例）
来源：http://dali.yongpay.top/Article/details/gtuilhwgji.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.andypj.xyz/Article/details/gtnffvgsju.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yj20258.top/Article/details/gteyrwinpn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hnqzz.top/Article/details/gtiurzswki.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daria6918.cn/Article/details/gtmmpcphaf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.bjfxy.top/Article/details/gtkcujjkwb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ppjwa.cn/Article/details/gtlmwqvibd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.tanke756.top/Article/details/gtzvuufsdl.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xinyue.icu/Article/details/gttgbroadp.html

[N04] 斐波那契数列
来源：http://dali.nanxuanxn.top/Article/details/gtinhgpjjo.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yanxiufei.cn/Article/details/gtyjlbiwdd.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfjwwkkix.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenjidiqi.icu/Article/details/gtibrkughy.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhixingplan.top/Article/details/gtklatdxik.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jiagoushi.top/Article/details/gtsjmphufv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yueranfly.top/Article/details/gtvqdauexb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.kuanghao11.cn/Article/details/gtzbjfcsnw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cdnleiting.top/Article/details/gthuxismlt.html


<!-- 参考信息 -->