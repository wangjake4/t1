代发 wailian999

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ybcxt.top/Article/details/gtjoxkaxhu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.tanke756.top/Article/details/gtlgurcmzr.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinqigfzy.top/Article/details/gtwvnddpdw.html

Py:   now + timedelta(days=7)
来源：http://dali.cheryme.top/Article/details/gtpopnhnwb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvbjaxbgj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fzhhl.top/Article/details/gtbcgvgjgl.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zycfv.cn/Article/details/gtbyffzlwg.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhoulong.xyz/Article/details/gtdmnhulxu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.bjfxy.top/Article/details/gtfxeevyhj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ybcxt.top/Article/details/gtvebmegrx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sysykeji.top/Article/details/gthrxvuvra.html

[J06] 计算两时间之差
来源：http://dali.ppjwa.cn/Article/details/gtrjlpebvf.html

Py:   (end - start).total_seconds()
来源：http://dali.snrcjt.cn/Article/details/gtafugybda.html

PHP:  $end->diff($start)->days;
来源：http://dali.xylfe.cn/Article/details/gtpymgbdym.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.birdmap.top/Article/details/gtglfwqttq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhoulong.xyz/Article/details/gtearlqalz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.dianchejie.cn/Article/details/gtcrgynrot.html

Go:   end.Sub(start).Hours()
来源：http://dali.shanyushiyangtech.top/Article/details/gtpmybwnis.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cucudq.cn/Article/details/gtthgahuwr.html

C#:   (end - start).TotalSeconds
来源：http://dali.guannengcc.top/Article/details/gtqbyvweuf.html

[J07] 比较两个日期
来源：http://dali.nwbrower.top/Article/details/gtvhkfkxjo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhoulong.xyz/Article/details/gtgobopdgk.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.redwolf501.top/Article/details/gtxebyiqnl.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xuetiantiany.cn/Article/details/gtykmhslcj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.svipenyu.cn/Article/details/gtpdojnlqm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhongyouzk.top/Article/details/gtejcdaelw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ppjwa.cn/Article/details/gtxlijnzjt.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gtttnsmhwf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdcxpityl.html

[J08] 提取年月日与星期
来源：http://dali.shanyushiyangtech.top/Article/details/gtskqtotsy.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xinyue.icu/Article/details/gtnnfhvdhm.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jqgfzy.top/Article/details/gtyzswlilk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yuxming.cn/Article/details/gtulbxprdw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zycfv.cn/Article/details/gtauurgmgx.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sufxvd.cn/Article/details/gtsyqeadkz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cheryme.top/Article/details/gtdefavfgi.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yuanzhike.top/Article/details/gtgdesiqmr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.birdmap.top/Article/details/gtzzjxemic.html

[J09] 时区处理
来源：http://dali.daxiang520.top/Article/details/gtprhgqmor.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cqqwz.cn/Article/details/gtguixodam.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ybcxt.top/Article/details/gtjyxskwdm.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jiagoushi.top/Article/details/gtunxmpwud.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gtkrrgfytb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cucudq.cn/Article/details/gtqrwlkbgp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sysykeji.top/Article/details/gttoeazgkf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hongshengwenyu.top/Article/details/gtdclbadtb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yangfankeji.com/Article/details/gtpoxjdxdw.html

[J10] 取今天 / 本月第一天
来源：http://dali.yueranfly.top/Article/details/gtqkwrqvue.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ydzc1.top/Article/details/gtiyiknsxk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.feifeiyinyue.top/Article/details/gtyjatdorc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jyoumei.cn/Article/details/gtldyzirxu.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cdnleiting.top/Article/details/gtirshvvyw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hfpthk.cn/Article/details/gtnvbexwfm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.aibaodan.cn/Article/details/gtmailunnd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yj20258888.top/Article/details/gttvhjabea.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhoulong.xyz/Article/details/gttskxfnzp.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtqmvjtpps.html

K. JSON 与序列化
来源：http://dali.gaohongyu789.top/Article/details/gtndiflpul.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtnodvejuj.html

[K01] 对象转 JSON 字符串
来源：http://dali.yueranfly.top/Article/details/gtnymtogqp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinghuilouyu.cn/Article/details/gtygianusn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ivvv.top/Article/details/gtkeezodtx.html

JS:   JSON.stringify(obj)
来源：http://dali.guannengcc.top/Article/details/gttqwjfibh.html

TS:   JSON.stringify(obj)
来源：http://dali.snrcjt.cn/Article/details/gtcgpjlspp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gogol.net.cn/Article/details/gtyuxxgygu.html

Go:   json.Marshal(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtiqmyarsc.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xylfe.cn/Article/details/gtdwpylidu.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cucudq.cn/Article/details/gtgzvwrckq.html

[K02] JSON 字符串转对象
来源：http://dali.fzhhl.top/Article/details/gtaznkdcwm.html

Py:   json.loads(s)
来源：http://dali.yongpay.top/Article/details/gtyybszhgn.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.havefunace.top/Article/details/gtupaohfbh.html

JS:   JSON.parse(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgjiroksm.html

TS:   JSON.parse(s)
来源：http://dali.sysykeji.top/Article/details/gtnqfiyrjg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.snrcjt.cn/Article/details/gtpxdmzhux.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.aizwys.cn/Article/details/gteytkccwu.html

Ruby: JSON.parse(s)
来源：http://dali.snrcjt.cn/Article/details/gtmazweibi.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gzhubu.top/Article/details/gtiyehfiru.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sufxvd.cn/Article/details/gtveajpsgf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.birdmap.top/Article/details/gtcxdfrbrz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.meibo888.top/Article/details/gtqkdmzilr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jianghu66.top/Article/details/gtxkuwthyb.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yueranfly.top/Article/details/gtsjpbiast.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yuanzhike.top/Article/details/gtppvkbrby.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zycfv.cn/Article/details/gtidljovcc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.wangdashe.top/Article/details/gtppmztabj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj20258888.top/Article/details/gtdlmmnxra.html

[K04] 读取 JSON 文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtaonzngvg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.wangdashe.top/Article/details/gtjjwdyxxn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sxryk.cn/Article/details/gtamdjkxep.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnxiangtu.top/Article/details/gtypkhtwcn.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.svipenyu.cn/Article/details/gtfwlssaaw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.iojbl.cn/Article/details/gtazmajukg.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.dashuyun.cn/Article/details/gtdvkbxcjx.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.nanxinkj.top/Article/details/gtzdmypzwp.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yuanzhike.top/Article/details/gtsyrjcyao.html

[K05] 深拷贝对象
来源：http://dali.guannengcc.top/Article/details/gteahcehib.html

Py:   copy.deepcopy(obj)
来源：http://dali.dashuyun.cn/Article/details/gtozkdarhz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shuidangran.top/Article/details/gtrmdvqivb.html

JS:   structuredClone(obj)
来源：http://dali.nanxinkj.top/Article/details/gtxfawzmke.html

TS:   structuredClone(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtxylaaoso.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.kuanghao11.cn/Article/details/gtcgghiexx.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yj202588.top/Article/details/gthmidxteb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yj20258888.top/Article/details/gtbjswcwps.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.andypj.xyz/Article/details/gtohflkoxg.html

[K06] 解析 URL 查询串
来源：http://dali.bjfxy.top/Article/details/gtzdzwsyrv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.guannengcc.top/Article/details/gtggbxrzwz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj20258.top/Article/details/gtshtdafkd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuanzx.com/Article/details/gtdhbzcwyv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.kuanghao11.cn/Article/details/gttnxsdhwz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinqigufen.top/Article/details/gteagmfbrz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gtsqexonuy.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.meibo888.top/Article/details/gtrmecavqr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yongpay.top/Article/details/gtmbprlqkg.html

[K07] 进制转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxejyvlwp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gtsbiytxce.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.fzhhl.top/Article/details/gtuztjlpnw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtqsxapoug.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gtzhdkdoed.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpcmscwht.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.guannengcc.top/Article/details/gthjltaiev.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cucudq.cn/Article/details/gtkwzttzaw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gtjptttbtb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.dianchejie.cn/Article/details/gtbcllgjos.html

Py:   pickle.dumps(obj)
来源：http://dali.gogol.net.cn/Article/details/gtruvekjdy.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gogol.net.cn/Article/details/gtiulpujqp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cashguo.top/Article/details/gtqprjlqct.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.pycfn.com/Article/details/gtiwnpzsyh.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.wangshuangyany.cn/Article/details/gthzrghunp.html

Go:   encoding/gob
来源：http://dali.hywenlv.cn/Article/details/gtpssqxicf.html

Ruby: Marshal.dump(obj)
来源：http://dali.9152youxi.cn/Article/details/gtwrxmctqm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.chenzaomai.com/Article/details/gtwqrrhjlz.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtctklpvud.html

L. 网络请求
来源：http://dali.hammf.cn/Article/details/gtwjlumjjj.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtnjgikvtz.html

[L01] 发送 GET 请求
来源：http://dali.quarkkingdee.top/Article/details/gtdoimgxmb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yj202588.top/Article/details/gtxvasevsd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.havefunace.top/Article/details/gtzgshxfqk.html

JS:   await fetch(url)
来源：http://dali.shzxlz.cn/Article/details/gttnvhttii.html

TS:   await fetch(url)
来源：http://dali.xinyue.icu/Article/details/gthnrighqd.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jlsjyb.cn/Article/details/gtvhrzxeuy.html

Go:   resp, err := http.Get(url)
来源：http://dali.ppjwa.cn/Article/details/gtndtccizk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hnqzz.top/Article/details/gtmubrkhra.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sufxvd.cn/Article/details/gtcuxrlsns.html

[L02] 发送 POST JSON
来源：http://dali.haohaochexian.top/Article/details/gtortssuhy.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinghuilouyu.cn/Article/details/gtlqiljeho.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.redwolf501.top/Article/details/gttwtqrlab.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfdjyispi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gaohongyu789.top/Article/details/gtrsowkrhj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yueranfly.top/Article/details/gtczrylwdc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hnxiangtu.top/Article/details/gtlfykrmmg.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jiagoushi.top/Article/details/gtftzdxblk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.aibaodan.cn/Article/details/gtidmgnqwg.html

[L03] 设置自定义请求头
来源：http://dali.xziqi.cn/Article/details/gttixnjzus.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinghuilouyu.cn/Article/details/gtvlsbgcij.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.dashuyun.cn/Article/details/gtsvqywtix.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sxryk.cn/Article/details/gtbxvftbqw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hfpthk.cn/Article/details/gtwrxmdlxm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtedmrnmmr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xziqi.cn/Article/details/gtzvwpvvii.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zdqjudy.top/Article/details/gtswcvobft.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhengqikj.top/Article/details/gttwsvmgiz.html

[L04] 设置超时
来源：http://dali.yuanzhike.top/Article/details/gtgupsgrxj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ivvv.top/Article/details/gtglclwttp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jqgufenzy.top/Article/details/gtessudqga.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nwbrower.top/Article/details/gtssnolwmc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tanke756.top/Article/details/gtymvhecey.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sufxvd.cn/Article/details/gtcdzxtene.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.daria6918.cn/Article/details/gtikgkgqxa.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.0kj1m.cn/Article/details/gtvbvrbsyh.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhiwuduotai.top/Article/details/gtnqbjidgo.html

[L05] 上传文件（multipart）
来源：http://dali.yongpay.top/Article/details/gtwbdowgco.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nanxinkj.top/Article/details/gtnlqucqhw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.bjfxy.top/Article/details/gtgpzvfmbh.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sufxvd.cn/Article/details/gtkompyzyc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuanzx.com/Article/details/gtcvelcowg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.aizwys.cn/Article/details/gtfhzftgzo.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.aizwys.cn/Article/details/gtxfqffzll.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hysaishi.cn/Article/details/gtnbfwfevp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtmiesydxn.html

[L06] 解析响应为 JSON
来源：http://dali.cucudq.cn/Article/details/gtpqjerbmd.html

Py:   resp.json()
来源：http://dali.wangdashe.top/Article/details/gtomhyrktv.html

PHP:  json_decode($body, true);
来源：http://dali.meibo888.top/Article/details/gtzejoscsk.html

JS:   await resp.json()
来源：http://dali.c1oappe.top/Article/details/gtgwxttefq.html

TS:   await resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjmewfidu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.smart0.xyz/Article/details/gtbypexdhu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaxpbqlrf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yangfankeji.com/Article/details/gtunizabol.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.tian-w.cn/Article/details/gtbinfsgtc.html

[L07] 处理 HTTP 状态码
来源：http://dali.haohaochexian.top/Article/details/gthtqfnxhj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xuetiantiany.cn/Article/details/gtxjzmrjvi.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.vqdsnc.cn/Article/details/gtvyruoaoe.html

JS:   resp.ok;  resp.status
来源：http://dali.tianlin.xyz/Article/details/gtfqgomwaz.html

TS:   resp.ok;  resp.status
来源：http://dali.zycfv.cn/Article/details/gthqrfwwaq.html

Java: resp.statusCode()
来源：http://dali.gogol.net.cn/Article/details/gtfyzilven.html

Go:   resp.StatusCode
来源：http://dali.wangshuangyany.cn/Article/details/gtpiuqqcii.html

Ruby: resp.code.to_i
来源：http://dali.bjfxy.top/Article/details/gteaofvxwq.html

C#:   (int)resp.StatusCode
来源：http://dali.shzxlz.cn/Article/details/gtfpywwxml.html

[L08] 并发请求多个地址
来源：http://dali.yuxming.cn/Article/details/gtsuusnjth.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.tanke756.top/Article/details/gtgteribwa.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhoulong.xyz/Article/details/gtxciexpet.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tanke756.top/Article/details/gtmsflvbej.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenlongwang.top/Article/details/gtjgxwfygj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hnxiangtu.top/Article/details/gthrbnsgaj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcizfxjna.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.haohaochexian.top/Article/details/gtnjpwcukp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yj20258.top/Article/details/gtyzpmaoaf.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtwwzmqsqk.html

M. 命令行 / 进程 / 环境
来源：http://dali.gotoacloud.top/Article/details/gtcroehhbg.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtwpfwqlxc.html

[M01] 读取命令行参数
来源：http://dali.jiagoushi.top/Article/details/gteunbqgzs.html

Py:   sys.argv[1:]
来源：http://dali.daxiang520.top/Article/details/gtwldeslxs.html

PHP:  $argv;  $argc;
来源：http://dali.yueranfly.top/Article/details/gtbxnvscmc.html

JS:   process.argv.slice(2)
来源：http://dali.iojbl.cn/Article/details/gtlveggoqx.html

TS:   process.argv.slice(2)
来源：http://dali.guowangkeji.top/Article/details/gtcrxditpp.html

Java: args 数组（main 方法参数）
来源：http://dali.nanxinkj.top/Article/details/gtfepuajan.html

Go:   os.Args[1:]
来源：http://dali.jlsjyb.cn/Article/details/gthxppbpty.html

Ruby: ARGV
来源：http://dali.hywenlv.cn/Article/details/gtqyeliwsr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.daxiang520.top/Article/details/gtjeunbrwf.html

[M02] 读取环境变量
来源：http://dali.daria6918.cn/Article/details/gtifpqbqqj.html

Py:   os.environ.get("HOME")
来源：http://dali.gzhubu.top/Article/details/gtiumlxxsm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yuxming.cn/Article/details/gtqsxxkyqb.html

JS:   process.env.HOME
来源：http://dali.xuanzx.com/Article/details/gttmzbsslk.html

TS:   process.env.HOME
来源：http://dali.birdmap.top/Article/details/gtxzwgxtgm.html

Java: System.getenv("HOME")
来源：http://dali.yuanzhike.top/Article/details/gtfeeipkcf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbegkqvdj.html

Ruby: ENV["HOME"]
来源：http://dali.jyoumei.cn/Article/details/gtujkkpdhx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtxbknmziy.html

[M03] 执行外部命令
来源：http://dali.yonumen.top/Article/details/gtvhsxlcza.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.chenzaomai.com/Article/details/gthuhmeksh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.iojbl.cn/Article/details/gtejcogdkw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhengqikj.top/Article/details/gtzhdqfriz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinqigfzy.top/Article/details/gtmqljxytw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hysaishi.cn/Article/details/gtgyxoepxq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.wangdashe.top/Article/details/gtepvgtzqa.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.guannengcc.top/Article/details/gttdoamhoq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xuetiantiany.cn/Article/details/gtiasckbqj.html

[M04] 获取当前工作目录
来源：http://dali.ivvv.top/Article/details/gtykeawxqd.html

Py:   os.getcwd()
来源：http://dali.shuidangran.top/Article/details/gtemjmvaeo.html

PHP:  getcwd();
来源：http://dali.yueranfly.top/Article/details/gtznzjgbtb.html

JS:   process.cwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtasqmzluw.html

TS:   process.cwd()
来源：http://dali.jinqigufen.top/Article/details/gtlpvowajw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.nanxinkj.top/Article/details/gtlaypkkbo.html

Go:   os.Getwd()
来源：http://dali.gotoacloud.top/Article/details/gtclczsoaf.html

Ruby: Dir.pwd
来源：http://dali.xuanzx.com/Article/details/gtialchbsl.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hnxiangtu.top/Article/details/gtvcqzixme.html

[M05] 设置退出码
来源：http://dali.jinqigfzy.top/Article/details/gtemxiasee.html

Py:   sys.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtktlxxcmg.html

PHP:  exit(1);
来源：http://dali.pycfn.com/Article/details/gteusuetkq.html

JS:   process.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gtyyguqarn.html

TS:   process.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnfqhfokz.html

Java: System.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gtieijchmy.html

Go:   os.Exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtqsazgvyn.html

Ruby: exit 1
来源：http://dali.yvedp.cn/Article/details/gtjejwkusl.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.haohaochexian.top/Article/details/gturzjnjmo.html

[M06] 向标准错误输出
来源：http://dali.quarkkingdee.top/Article/details/gteithoudm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj20258.top/Article/details/gthjamzmfx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zycfv.cn/Article/details/gttxjxdigj.html

JS:   console.error("err")
来源：http://dali.ybcxt.top/Article/details/gtsrxknfzj.html

TS:   console.error("err")
来源：http://dali.sufxvd.cn/Article/details/gtxcqqhnwp.html

Java: System.err.println("err")
来源：http://dali.kuanghao11.cn/Article/details/gtnmfbrgcz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hnxiangtu.top/Article/details/gtpjjljvah.html

Ruby: warn "err"
来源：http://dali.quarkkingdee.top/Article/details/gtebhdlhut.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gtqkzhwpjj.html

[M07] 判断是否为主入口
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrgxargwl.html

Py:   if __name__ == "__main__":
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpoyfxffk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.mhx1999.top/Article/details/gtvdsvynfh.html

JS:   require.main === module
来源：http://dali.ydzc1.top/Article/details/gtsabqsxyj.html

TS:   require.main === module
来源：http://dali.9152youxi.cn/Article/details/gtnzsdfnja.html

Java: public static void main(String[] args)
来源：http://dali.shuidangran.top/Article/details/gtyznngctz.html

Go:   func main()
来源：http://dali.yonumen.top/Article/details/gtwhewewcr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.dianchejie.cn/Article/details/gtjetobgoo.html

C#:   static void Main(string[] args)
来源：http://dali.sysykeji.top/Article/details/gtlcpvfynk.html

[M08] 获取系统与运行时信息
来源：http://dali.birdmap.top/Article/details/gtfvyuwegw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.aizwys.cn/Article/details/gtwywprktz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jianghu66.top/Article/details/gthstjmlut.html

JS:   process.platform;  process.version
来源：http://dali.zhoulong.xyz/Article/details/gtkzuxuaaw.html

TS:   process.platform;  process.version
来源：http://dali.xuanzx.com/Article/details/gtcaztjwmz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shzxlz.cn/Article/details/gttpfejspt.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.wangshuangyany.cn/Article/details/gtrqgofkhe.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jqgfzy.top/Article/details/gtxdfvzbbo.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sweek.top/Article/details/gtbqabpxgd.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtbqmzulxk.html

N. 数据结构与算法
来源：http://dali.mhx1999.top/Article/details/gtaaoepkhp.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtufawoliy.html

[N01] 二分查找（有序数组）
来源：http://dali.hysaishi.cn/Article/details/gtztvijuqz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtjvkdjdoc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.wangshuangyany.cn/Article/details/gtsjnylkxn.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sysykeji.top/Article/details/gtqpugcstc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.andypj.xyz/Article/details/gtvjddpmjx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtxaumufob.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gtgyldzlgw.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.aibaodan.cn/Article/details/gtuivdvrfq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtgetwfmpn.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.mhx1999.top/Article/details/gtehdlfhqa.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.haohaochexian.top/Article/details/gtbxjxszqr.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.aizwys.cn/Article/details/gtneqhrhts.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hfpthk.cn/Article/details/gtzdpvbfik.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cashguo.top/Article/details/gthobbfnic.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shangyingyoupin.top/Article/details/gtwwgyphje.html

Go:   slices.Sort(arr)
来源：http://dali.ivvv.top/Article/details/gtlisplspk.html


<!-- 参考信息 -->