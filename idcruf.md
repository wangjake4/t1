代发 wailian999

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zdqjudy.top/Article/details/gtfjqxmuyv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yuanzhike.top/Article/details/gtkkddslbn.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.aibaodan.cn/Article/details/gtiynunoyo.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sxryk.cn/Article/details/gtyphezoxg.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.nwbrower.top/Article/details/gtaligeocv.html

[J08] 提取年月日与星期
来源：http://dali.nanxinkj.top/Article/details/gtjqpegwno.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cashguo.top/Article/details/gtvgliflex.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shzxlz.cn/Article/details/gtndbkmhyn.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhoulong.xyz/Article/details/gtilyvwvfq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.iojbl.cn/Article/details/gtkqezkxbu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinqigfzy.top/Article/details/gtknimlorj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.iojbl.cn/Article/details/gtijopxili.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.aibaodan.cn/Article/details/gtqqozpvom.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sufxvd.cn/Article/details/gtbbifbgzp.html

[J09] 时区处理
来源：http://dali.iojbl.cn/Article/details/gtlrilrkle.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xuanzx.com/Article/details/gtjckxevjl.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.daria6918.cn/Article/details/gtvmwnktfu.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shuidangran.top/Article/details/gthxfqwyyz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.0kj1m.cn/Article/details/gtuounepyk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.birdmap.top/Article/details/gtiabntsbv.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.mhx1999.top/Article/details/gtvnkuxwvj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gaohongyu789.top/Article/details/gtbrhkcfkl.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.daria6918.cn/Article/details/gtyasdbauy.html

[J10] 取今天 / 本月第一天
来源：http://dali.9152youxi.cn/Article/details/gtjtghepnc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.snrcjt.cn/Article/details/gtxmffqapa.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yj20258.top/Article/details/gtjtzzxnkp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.redwolf501.top/Article/details/gtigtbcjba.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinqigufen.top/Article/details/gtkdjzhwsk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xziqi.cn/Article/details/gtcypexfes.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.tian-w.cn/Article/details/gtgsjsvjoy.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hnqzz.top/Article/details/gtknnllgrd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sysykeji.top/Article/details/gtcyheqlao.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtajsmpdhj.html

K. JSON 与序列化
来源：http://dali.jqgufenzy.top/Article/details/gtfwkmyqwk.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtmfwsrzgx.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhixingplan.top/Article/details/gtxfqdieis.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sweek.top/Article/details/gtszmkuywd.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jianghu66.top/Article/details/gtnlihbkts.html

JS:   JSON.stringify(obj)
来源：http://dali.tanke756.top/Article/details/gtzgdwvehg.html

TS:   JSON.stringify(obj)
来源：http://dali.sysykeji.top/Article/details/gtzybecubc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jiagoushi.top/Article/details/gtedczrans.html

Go:   json.Marshal(obj)
来源：http://dali.aibaodan.cn/Article/details/gtsropdjog.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.meibo888.top/Article/details/gtlklenvlb.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yj20258888.top/Article/details/gtyrjwfdel.html

[K02] JSON 字符串转对象
来源：http://dali.zhijiandao.cn/Article/details/gtykteokqg.html

Py:   json.loads(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtigyhqfvp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.redwolf501.top/Article/details/gtkoihmnod.html

JS:   JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtqbzzyzfo.html

TS:   JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gtpbsocrwb.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.tanke756.top/Article/details/gttotokohr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.smart0.xyz/Article/details/gtcvzmaiaa.html

Ruby: JSON.parse(s)
来源：http://dali.sxryk.cn/Article/details/gtdjdhhsgv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtygxhgbwy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.birdmap.top/Article/details/gtjqpbioba.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gzhubu.top/Article/details/gtisjgyumi.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.c1oappe.top/Article/details/gtxscsmqpb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gtrekatvua.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xinyue.icu/Article/details/gtrbheyrdj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gogol.net.cn/Article/details/gtkhpxasgu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yangfankeji.com/Article/details/gtppnofhee.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhengqikj.top/Article/details/gtorzhlcun.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.guannengcc.top/Article/details/gtrwwzanol.html

[K04] 读取 JSON 文件
来源：http://dali.redwolf501.top/Article/details/gtviansvnv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jyoumei.cn/Article/details/gtylugbmbg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jiagoushi.top/Article/details/gtdbreskwe.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.bjfxy.top/Article/details/gtqyhtznjk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aizwys.cn/Article/details/gtotefbfca.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shangyingyoupin.top/Article/details/gtmeatvozo.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gtlyjtkmwf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.aibaodan.cn/Article/details/gtqadbripo.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sysykeji.top/Article/details/gttsqvudip.html

[K05] 深拷贝对象
来源：http://dali.yanxiufei.cn/Article/details/gthromaxnt.html

Py:   copy.deepcopy(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtnbhgxwjq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yongpay.top/Article/details/gtrpgsbkee.html

JS:   structuredClone(obj)
来源：http://dali.gzhubu.top/Article/details/gtnczcqljr.html

TS:   structuredClone(obj)
来源：http://dali.guowangkeji.top/Article/details/gtgcuoxkcn.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinghuilouyu.cn/Article/details/gttnohohen.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtevqxhget.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.tian-w.cn/Article/details/gtffnyhqli.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yanxiufei.cn/Article/details/gtpyzbrkot.html

[K06] 解析 URL 查询串
来源：http://dali.cashguo.top/Article/details/gtvgidjpmj.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.0kj1m.cn/Article/details/gtdwqpjicw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ppjwa.cn/Article/details/gtwpprvbzk.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shzxlz.cn/Article/details/gtbovqmctf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shangyingyoupin.top/Article/details/gtygcgyqdo.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.nanxinkj.top/Article/details/gtzxvojnhi.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhoulong.xyz/Article/details/gtxyhpafbc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.pycfn.com/Article/details/gtpvphowrk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.redwolf501.top/Article/details/gtujhzfiaq.html

[K07] 进制转换
来源：http://dali.havefunace.top/Article/details/gtfgxniboq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gtlrscmmel.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yvedp.cn/Article/details/gtecpnycxj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yongpay.top/Article/details/gthqbctfhn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gtguhvhnlb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gtjqkofwjj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.aibaodan.cn/Article/details/gthxmohgea.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cheryme.top/Article/details/gtjldlcius.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gtcyrztbah.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.chenjidiqi.icu/Article/details/gtwgoyaaxv.html

Py:   pickle.dumps(obj)
来源：http://dali.sweek.top/Article/details/gtefvmsgyt.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.chenjidiqi.icu/Article/details/gthbnmgbhp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jqgfzy.top/Article/details/gtlinjrvyi.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.chenjidiqi.icu/Article/details/gtyfwbupvo.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhoulong.xyz/Article/details/gtzyroqgxo.html

Go:   encoding/gob
来源：http://dali.smart0.xyz/Article/details/gtopvsdmqv.html

Ruby: Marshal.dump(obj)
来源：http://dali.mhx1999.top/Article/details/gtxqlqbkih.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.sxryk.cn/Article/details/gttosnuffv.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtubtdsszk.html

L. 网络请求
来源：http://dali.gotoacloud.top/Article/details/gtzbcfmpux.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtrbobmbth.html

[L01] 发送 GET 请求
来源：http://dali.mhx1999.top/Article/details/gtvfcdbzzd.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hnxiangtu.top/Article/details/gtyzfrkmbg.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.kuanghao11.cn/Article/details/gtwrelbffp.html

JS:   await fetch(url)
来源：http://dali.fzhhl.top/Article/details/gtpojponor.html

TS:   await fetch(url)
来源：http://dali.jiagoushi.top/Article/details/gtthkcnmce.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmcijhtwk.html

Go:   resp, err := http.Get(url)
来源：http://dali.bjfxy.top/Article/details/gtiwnoruyf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhongyouzk.top/Article/details/gtbgntjtst.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.havefunace.top/Article/details/gtqoprgssn.html

[L02] 发送 POST JSON
来源：http://dali.tian-w.cn/Article/details/gthdifbqyr.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jianghu66.top/Article/details/gtzsxtfwlt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xinyue.icu/Article/details/gtzwfynjsy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhongyouzk.top/Article/details/gtfducqahg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.316326.xyz/Article/details/gtzvsdcyys.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yuxming.cn/Article/details/gttpedeozl.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cashguo.top/Article/details/gtdqascmvb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.andypj.xyz/Article/details/gtzvpzohld.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sweek.top/Article/details/gtppvixluo.html

[L03] 设置自定义请求头
来源：http://dali.c1oappe.top/Article/details/gtvsmhauha.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinqigfzy.top/Article/details/gtelqzkffl.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yvedp.cn/Article/details/gtyfrycnuf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daxiang520.top/Article/details/gtjxmishai.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shuidangran.top/Article/details/gteggpallg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkifdlllf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.daria6918.cn/Article/details/gtjexekgir.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ppjwa.cn/Article/details/gtqluzhhny.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sysykeji.top/Article/details/gtvdkqdpsy.html

[L04] 设置超时
来源：http://dali.shanyushiyangtech.top/Article/details/gtviedmnnv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.aizwys.cn/Article/details/gtobtpvtdd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtykszerlh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ehwqpu.com/Article/details/gtpwceozvj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.mhx1999.top/Article/details/gtdbpxojos.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ivvv.top/Article/details/gtcwhleefo.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cucudq.cn/Article/details/gthdcacqtk.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sysykeji.top/Article/details/gttbhjhwbm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gzhubu.top/Article/details/gtowjbyfcp.html

[L05] 上传文件（multipart）
来源：http://dali.smart0.xyz/Article/details/gtmkjheewz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yueranfly.top/Article/details/gtytfnqfgl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.svipenyu.cn/Article/details/gtnktjmhur.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.vqdsnc.cn/Article/details/gtrbnvhpxq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnxiangtu.top/Article/details/gtcryknxjt.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.dashuyun.cn/Article/details/gtsjzwagij.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cqqwz.cn/Article/details/gtvctqfkfq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zdqjudy.top/Article/details/gtsgftkyva.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtesidtgdx.html

[L06] 解析响应为 JSON
来源：http://dali.yonumen.top/Article/details/gtkttngflm.html

Py:   resp.json()
来源：http://dali.9152youxi.cn/Article/details/gtcupkuxea.html

PHP:  json_decode($body, true);
来源：http://dali.cdnleiting.top/Article/details/gtmnoxfgjc.html

JS:   await resp.json()
来源：http://dali.hammf.cn/Article/details/gtxkgtgphh.html

TS:   await resp.json()
来源：http://dali.sxryk.cn/Article/details/gtpfokwoae.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.snrcjt.cn/Article/details/gtwqhspzxn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.svipenyu.cn/Article/details/gtzgszoaon.html

Ruby: JSON.parse(resp.body)
来源：http://dali.daria6918.cn/Article/details/gtlpqgcmlg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.mhx1999.top/Article/details/gtbufmejbv.html

[L07] 处理 HTTP 状态码
来源：http://dali.guowangkeji.top/Article/details/gtluilivul.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cheryme.top/Article/details/gtqgkvuxug.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhixingplan.top/Article/details/gtpqsgiaim.html

JS:   resp.ok;  resp.status
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjhozjjbx.html

TS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangkeji.top/Article/details/gtttbwvtmv.html

Java: resp.statusCode()
来源：http://dali.bjfxy.top/Article/details/gtserkotjr.html

Go:   resp.StatusCode
来源：http://dali.jinghuilouyu.cn/Article/details/gtczceqlpj.html

Ruby: resp.code.to_i
来源：http://dali.yj20258888.top/Article/details/gtzyhtnloj.html

C#:   (int)resp.StatusCode
来源：http://dali.nanxinkj.top/Article/details/gttahzzmrk.html

[L08] 并发请求多个地址
来源：http://dali.zhixingplan.top/Article/details/gtfcjeqqxd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jianghu66.top/Article/details/gthtzywgbb.html

PHP:  curl_multi_init() 系列
来源：http://dali.jiagoushi.top/Article/details/gtmzoszyfm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gtstluppnu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yueranfly.top/Article/details/gtwkpnvbib.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.fzhhl.top/Article/details/gthxzhchss.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gotoacloud.top/Article/details/gtncqnvrna.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xylfe.cn/Article/details/gtslammvfe.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtljpowxug.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtrmmjqgmp.html

M. 命令行 / 进程 / 环境
来源：http://dali.316326.xyz/Article/details/gttpuxwsuo.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtudztseev.html

[M01] 读取命令行参数
来源：http://dali.cashguo.top/Article/details/gtqkrkmqug.html

Py:   sys.argv[1:]
来源：http://dali.yuxming.cn/Article/details/gtcspiizsd.html

PHP:  $argv;  $argc;
来源：http://dali.dianchejie.cn/Article/details/gthjbdkgen.html

JS:   process.argv.slice(2)
来源：http://dali.nanxinkj.top/Article/details/gttgzeqlhp.html

TS:   process.argv.slice(2)
来源：http://dali.zhengqikj.top/Article/details/gtgkxeteeb.html

Java: args 数组（main 方法参数）
来源：http://dali.shangyingyoupin.top/Article/details/gteavtqijs.html

Go:   os.Args[1:]
来源：http://dali.yanxiufei.cn/Article/details/gtcjbtdfwe.html

Ruby: ARGV
来源：http://dali.zhiwuduotai.top/Article/details/gtbacnhyra.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xziqi.cn/Article/details/gtmkrwgbox.html

[M02] 读取环境变量
来源：http://dali.vqdsnc.cn/Article/details/gtbqufqbzl.html

Py:   os.environ.get("HOME")
来源：http://dali.jqgfzy.top/Article/details/gtauygvmwh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.chenjidiqi.icu/Article/details/gthtuqafhn.html

JS:   process.env.HOME
来源：http://dali.hysaishi.cn/Article/details/gtuntcztkg.html

TS:   process.env.HOME
来源：http://dali.yongpay.top/Article/details/gtbcejpzbg.html

Java: System.getenv("HOME")
来源：http://dali.yuxming.cn/Article/details/gtijolxwqt.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhixingplan.top/Article/details/gtsjmmknmm.html

Ruby: ENV["HOME"]
来源：http://dali.zhongyouzk.top/Article/details/gteiygxlzm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yuanzhike.top/Article/details/gtlahvomgg.html

[M03] 执行外部命令
来源：http://dali.pengpengdd.cyou/Article/details/gttsreigww.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.smart0.xyz/Article/details/gtxhoywlpy.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinghuilouyu.cn/Article/details/gthbmgmrkv.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.mhx1999.top/Article/details/gtymmknyih.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yonumen.top/Article/details/gterzelcss.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yj202588.top/Article/details/gtphijvehz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinqigfzy.top/Article/details/gthhsnvpda.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.kuanghao11.cn/Article/details/gtkjqwhvqf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyojrszhl.html

[M04] 获取当前工作目录
来源：http://dali.sufxvd.cn/Article/details/gtjhejgkwx.html

Py:   os.getcwd()
来源：http://dali.gzhubu.top/Article/details/gtaiqzeryv.html

PHP:  getcwd();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvjyiavzc.html

JS:   process.cwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gthcxnhtxv.html

TS:   process.cwd()
来源：http://dali.daxiang520.top/Article/details/gtpqmrqrcd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.mhx1999.top/Article/details/gtfoujudcb.html

Go:   os.Getwd()
来源：http://dali.guowangkeji.top/Article/details/gtwjomovtm.html

Ruby: Dir.pwd
来源：http://dali.feifeiyinyue.top/Article/details/gtqxrqchxy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.pengpengdd.cyou/Article/details/gtqxjapfbw.html

[M05] 设置退出码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnlctajaf.html

Py:   sys.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gtfqanomcm.html

PHP:  exit(1);
来源：http://dali.chenjidiqi.icu/Article/details/gtizuadogk.html

JS:   process.exit(1)
来源：http://dali.cheryme.top/Article/details/gtcdduulcw.html

TS:   process.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtskozuylv.html

Java: System.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpbwtjglj.html

Go:   os.Exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gtiljtrbfa.html

Ruby: exit 1
来源：http://dali.sysykeji.top/Article/details/gtpcnzldot.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinqigufen.top/Article/details/gtgbmqewig.html

[M06] 向标准错误输出
来源：http://dali.gotoacloud.top/Article/details/gtkegsccfu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yueranfly.top/Article/details/gtuqtgiysx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinqigufen.top/Article/details/gtglcnqhrn.html

JS:   console.error("err")
来源：http://dali.ivvv.top/Article/details/gtnijjeves.html

TS:   console.error("err")
来源：http://dali.yuanzhike.top/Article/details/gtzfuxmece.html

Java: System.err.println("err")
来源：http://dali.daxiang520.top/Article/details/gtqqpdbnwm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jqgfzy.top/Article/details/gttldvernt.html

Ruby: warn "err"
来源：http://dali.chenjidiqi.icu/Article/details/gtxgfuwttn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.snrcjt.cn/Article/details/gtkzfrfioo.html

[M07] 判断是否为主入口
来源：http://dali.zhiwuduotai.top/Article/details/gtliwqknwx.html

Py:   if __name__ == "__main__":
来源：http://dali.jinqigfzy.top/Article/details/gtgxkoirvd.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xuanzx.com/Article/details/gtzhrwknbk.html

JS:   require.main === module
来源：http://dali.yj202588.top/Article/details/gthimevcpd.html

TS:   require.main === module
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyrbuwxtp.html

Java: public static void main(String[] args)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcugddjas.html

Go:   func main()
来源：http://dali.kuanghao11.cn/Article/details/gtlpyrkrnx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yuxming.cn/Article/details/gtkdgyjxud.html

C#:   static void Main(string[] args)
来源：http://dali.guannengcc.top/Article/details/gtqyhdfcqb.html

[M08] 获取系统与运行时信息
来源：http://dali.haohaochexian.top/Article/details/gtpuivkvvr.html

Py:   platform.system();  platform.python_version()
来源：http://dali.tianlin.xyz/Article/details/gtywckndww.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yj20258888.top/Article/details/gtewjagyxg.html

JS:   process.platform;  process.version
来源：http://dali.quarkkingdee.top/Article/details/gtxikagtoy.html

TS:   process.platform;  process.version
来源：http://dali.ehwqpu.com/Article/details/gtjrnljyan.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hnqzz.top/Article/details/gtkrkddwpe.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sysykeji.top/Article/details/gtznnupoqe.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.vqdsnc.cn/Article/details/gtjekkjtni.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.daria6918.cn/Article/details/gtdwqjjkgm.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtleggsevi.html

N. 数据结构与算法
来源：http://dali.svipenyu.cn/Article/details/gtzwwlvawz.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtxagllxde.html

[N01] 二分查找（有序数组）
来源：http://dali.bjfxy.top/Article/details/gtbdkhazvr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.fzhhl.top/Article/details/gtbftufscs.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.316326.xyz/Article/details/gthsdadggp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.meibo888.top/Article/details/gttwrzwmqf.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuxming.cn/Article/details/gtdyfkozpe.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ivvv.top/Article/details/gtzisfyauc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.iojbl.cn/Article/details/gthropwbes.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hnxiangtu.top/Article/details/gtezgyluws.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gttmzbnkib.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.0kj1m.cn/Article/details/gtgwzuqpja.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgfzy.top/Article/details/gtunuhbufc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yj202588.top/Article/details/gtcqwkzqjw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jqgfzy.top/Article/details/gtetxvnpdr.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwwhwprce.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zycfv.cn/Article/details/gtfbutckdh.html

Go:   slices.Sort(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtfnktkwwp.html

Ruby: arr.sort
来源：http://dali.nanxuanxn.top/Article/details/gtidcmwyxz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.iojbl.cn/Article/details/gtvddhtmjj.html

[N03] 快速排序（分治示例）
来源：http://dali.zhoulong.xyz/Article/details/gthblfnlqq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yangfankeji.com/Article/details/gtrgobaqmi.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ivvv.top/Article/details/gtbbyvmkwe.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dianchejie.cn/Article/details/gtuofesydp.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenzaomai.com/Article/details/gtynedindo.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jqgfzy.top/Article/details/gtuvnbpbwj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cucudq.cn/Article/details/gtbliinumn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ydzc1.top/Article/details/gtefzdltvm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yj202588.top/Article/details/gtgrnthlkf.html

[N04] 斐波那契数列
来源：http://dali.yvedp.cn/Article/details/gtwitiyopw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yangfankeji.com/Article/details/gtwtunjonw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhongyouzk.top/Article/details/gtlvbfccgg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hysaishi.cn/Article/details/gtlzgrhlqw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aibaodan.cn/Article/details/gtpgfjksyn.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yongpay.top/Article/details/gtahcmyumh.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.sweek.top/Article/details/gtldldobuj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hywenlv.cn/Article/details/gtxtkkqbkc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ybcxt.top/Article/details/gtgpquombx.html

[N05] 最大公约数
来源：http://dali.xuetiantiany.cn/Article/details/gtfuqdendb.html

Py:   math.gcd(a, b)
来源：http://dali.sxryk.cn/Article/details/gtlfoevral.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yuxming.cn/Article/details/gtpmwdbyab.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fengsongda.top/Article/details/gtomlqtzwm.html


<!-- 参考信息 -->