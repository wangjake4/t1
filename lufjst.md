代发 wailian999

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gtfuvkefrs.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yj20258888.top/Article/details/gtzgkhrcbm.html

[J05] 时间加减（加 7 天）
来源：http://dali.jianghu66.top/Article/details/gtflhthtwj.html

Py:   now + timedelta(days=7)
来源：http://dali.fengsongda.top/Article/details/gtmaydxctu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.kuanghao11.cn/Article/details/gtlcykzhzr.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhiwuduotai.top/Article/details/gtvajclkvh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nanxuanxn.top/Article/details/gtlmrhgfes.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.kuanghao11.cn/Article/details/gtgsaeexxw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.snrcjt.cn/Article/details/gttxretwip.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hfpthk.cn/Article/details/gtckdkgdwv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.0kj1m.cn/Article/details/gtdmmljtld.html

[J06] 计算两时间之差
来源：http://dali.jiagoushi.top/Article/details/gtwhdihcqx.html

Py:   (end - start).total_seconds()
来源：http://dali.yj20258888.top/Article/details/gtrbdhtvcs.html

PHP:  $end->diff($start)->days;
来源：http://dali.feifeiyinyue.top/Article/details/gtrweijdms.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hysaishi.cn/Article/details/gttbyvyrci.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.guowangkeji.top/Article/details/gteelvzwny.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cheryme.top/Article/details/gtvooqzxnm.html

Go:   end.Sub(start).Hours()
来源：http://dali.gotoacloud.top/Article/details/gtmqlevgnn.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yuanzhike.top/Article/details/gtqodzwmjz.html

C#:   (end - start).TotalSeconds
来源：http://dali.yonumen.top/Article/details/gtklxrmkzw.html

[J07] 比较两个日期
来源：http://dali.yj20258.top/Article/details/gtphplsndi.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hongshengwenyu.top/Article/details/gtgvbqcwga.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yongpay.top/Article/details/gtmdtjaapz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hnxiangtu.top/Article/details/gtczoficcx.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtphrmgfih.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yvedp.cn/Article/details/gtunthytom.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.tanke756.top/Article/details/gtzshdkwlp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenlongwang.top/Article/details/gtuugbyavd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gtwwtajtti.html

[J08] 提取年月日与星期
来源：http://dali.birdmap.top/Article/details/gtefwgccnw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.tian-w.cn/Article/details/gtvyoalmlv.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.nanxuanxn.top/Article/details/gtegfcbdez.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yuanzhike.top/Article/details/gtwrzhsjdt.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.iojbl.cn/Article/details/gtetxforfl.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sxryk.cn/Article/details/gtyydlrrut.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhongyouzk.top/Article/details/gtbaeqevmm.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hnxiangtu.top/Article/details/gtjwprgieu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cqqwz.cn/Article/details/gtratfkhjp.html

[J09] 时区处理
来源：http://dali.sysykeji.top/Article/details/gtzcodxiep.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhiwuduotai.top/Article/details/gtxvdvxzgn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sweek.top/Article/details/gttxhhunjd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuanzhike.top/Article/details/gtxeudmazv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.c1oappe.top/Article/details/gtkczibuap.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdweqymcg.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.meibo888.top/Article/details/gtjfejaxjp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nanxinkj.top/Article/details/gtadbrpqzw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.kuanghao11.cn/Article/details/gtovjugjzu.html

[J10] 取今天 / 本月第一天
来源：http://dali.wangshuangyany.cn/Article/details/gtpxzfagdi.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.birdmap.top/Article/details/gtaguewlul.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.fengsongda.top/Article/details/gtzuhgvtoi.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.dianchejie.cn/Article/details/gtznogdjnn.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.meibo888.top/Article/details/gtmileyetm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.quarkkingdee.top/Article/details/gtbtcmxrhh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.316326.xyz/Article/details/gttldfohqa.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.iojbl.cn/Article/details/gtjhxrezyx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmhthfdld.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtizqinjkm.html

K. JSON 与序列化
来源：http://dali.ppjwa.cn/Article/details/gtnppepdsx.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtzcgcrleo.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhoulong.xyz/Article/details/gtwerzbecm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.birdmap.top/Article/details/gtytgxzqup.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqqegoefp.html

JS:   JSON.stringify(obj)
来源：http://dali.sweek.top/Article/details/gtfaifsxsx.html

TS:   JSON.stringify(obj)
来源：http://dali.sufxvd.cn/Article/details/gtcgdltxew.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yonumen.top/Article/details/gtfltvbihp.html

Go:   json.Marshal(obj)
来源：http://dali.andypj.xyz/Article/details/gtusngunpl.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zdqjudy.top/Article/details/gtviknixkq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yvedp.cn/Article/details/gtmdwpowpz.html

[K02] JSON 字符串转对象
来源：http://dali.xuanzx.com/Article/details/gtzaqrvoeg.html

Py:   json.loads(s)
来源：http://dali.gzhubu.top/Article/details/gtpmwthukj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhengqikj.top/Article/details/gtptadhpfy.html

JS:   JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gtlmykmjvm.html

TS:   JSON.parse(s)
来源：http://dali.tian-w.cn/Article/details/gtrfteqktw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.smart0.xyz/Article/details/gtbhbesgxc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.guowangkeji.top/Article/details/gtozwttdgw.html

Ruby: JSON.parse(s)
来源：http://dali.aizwys.cn/Article/details/gtuefwwteu.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.0kj1m.cn/Article/details/gthzcddapb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ehwqpu.com/Article/details/gtklfhyzps.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaiidgbkq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhongyouzk.top/Article/details/gtehxxgobz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xinyue.icu/Article/details/gtfvnbvbuo.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yonumen.top/Article/details/gtmcmybntp.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yuxming.cn/Article/details/gtjcocjarq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xuanzx.com/Article/details/gttuqfvmiu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gotoacloud.top/Article/details/gtzwuzelft.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinqigfzy.top/Article/details/gtmqfwxvxj.html

[K04] 读取 JSON 文件
来源：http://dali.yuxming.cn/Article/details/gtoyibqqwx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.0kj1m.cn/Article/details/gtmacrhkbh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xinyue.icu/Article/details/gtlohglhyz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj202588.top/Article/details/gttqubjgvx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ydzc1.top/Article/details/gtkmbvxjdd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.aizwys.cn/Article/details/gtskxdfqls.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jlsjyb.cn/Article/details/gttgpjwgen.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yj20258.top/Article/details/gtiflrqruu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtvyjquyzq.html

[K05] 深拷贝对象
来源：http://dali.xuanzx.com/Article/details/gttqwmsmqx.html

Py:   copy.deepcopy(obj)
来源：http://dali.yj202588.top/Article/details/gteiyvnnxp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sufxvd.cn/Article/details/gtwdflnwik.html

JS:   structuredClone(obj)
来源：http://dali.yvedp.cn/Article/details/gtikervmrm.html

TS:   structuredClone(obj)
来源：http://dali.zhengqikj.top/Article/details/gtyaktnvzq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jianghu66.top/Article/details/gtmdapslud.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.bjfxy.top/Article/details/gtlxwfolqc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jyoumei.cn/Article/details/gtndkjjkhx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ehwqpu.com/Article/details/gtzzcfcxnj.html

[K06] 解析 URL 查询串
来源：http://dali.zycfv.cn/Article/details/gtrydymzjn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.bjfxy.top/Article/details/gtwebrcnef.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hnxiangtu.top/Article/details/gtuuadwoea.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yvedp.cn/Article/details/gtdxnujfar.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwcowzyjj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yj202588.top/Article/details/gtrjzeeqtm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yj20258888.top/Article/details/gtgjcpphjb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.wangshuangyany.cn/Article/details/gttigkamjr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yueranfly.top/Article/details/gtmolbelrj.html

[K07] 进制转换
来源：http://dali.sysykeji.top/Article/details/gtwycjdoei.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gtjlzklatl.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jiagoushi.top/Article/details/gthsfglwdq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gtbkaozuro.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gtdgprddka.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtazazryph.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhoulong.xyz/Article/details/gtjcjsoqhf.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbmtnwfas.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gtxwrbmkkx.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.dianchejie.cn/Article/details/gtiqbshbjr.html

Py:   pickle.dumps(obj)
来源：http://dali.zhixingplan.top/Article/details/gtrkaoxaad.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtvhuihjcr.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hongshengwenyu.top/Article/details/gtmrphqshx.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.daxiang520.top/Article/details/gtybyxltsp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cqqwz.cn/Article/details/gtkuyocyem.html

Go:   encoding/gob
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtehtncodb.html

Ruby: Marshal.dump(obj)
来源：http://dali.mhx1999.top/Article/details/gtuuskvffa.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ehwqpu.com/Article/details/gtnpwrdrqj.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtidptbtxw.html

L. 网络请求
来源：http://dali.wangshuangyany.cn/Article/details/gtjpzvmtgo.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtvsbcgmkm.html

[L01] 发送 GET 请求
来源：http://dali.yvedp.cn/Article/details/gtjyfijywa.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.smart0.xyz/Article/details/gtajixjeql.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.tianlin.xyz/Article/details/gtmekhfckg.html

JS:   await fetch(url)
来源：http://dali.9152youxi.cn/Article/details/gtmuqabczm.html

TS:   await fetch(url)
来源：http://dali.smart0.xyz/Article/details/gtvywgxrfx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jqgufenzy.top/Article/details/gtvnxraxmd.html

Go:   resp, err := http.Get(url)
来源：http://dali.ydzc1.top/Article/details/gtpwdpplkr.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.316326.xyz/Article/details/gtfliaupks.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.kuanghao11.cn/Article/details/gtvgkoqbvx.html

[L02] 发送 POST JSON
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsrjmvzxm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhengqikj.top/Article/details/gtpnetvlal.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.aizwys.cn/Article/details/gtjmkgzumo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yongpay.top/Article/details/gtlnwfgbkc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.meibo888.top/Article/details/gtvygwzili.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.iojbl.cn/Article/details/gttlsetpyt.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.fzhhl.top/Article/details/gtcmeyebhi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cucudq.cn/Article/details/gtmenetxxw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cdnleiting.top/Article/details/gtzhtnjhte.html

[L03] 设置自定义请求头
来源：http://dali.aizwys.cn/Article/details/gtfgtygsvx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shuidangran.top/Article/details/gtcopmyhax.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.tanke756.top/Article/details/gtydcmxodo.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.9152youxi.cn/Article/details/gtrnoxhvdl.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ydzc1.top/Article/details/gtuxubgjiz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.smart0.xyz/Article/details/gtkbpxopwj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yongpay.top/Article/details/gttcoahbiy.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.tanke756.top/Article/details/gtlmdgmbpj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.316326.xyz/Article/details/gtfjrfsoax.html

[L04] 设置超时
来源：http://dali.dianchejie.cn/Article/details/gtzqqpkvkd.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcgtvuyun.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.guowangkeji.top/Article/details/gtysrzphwx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuanzx.com/Article/details/gtxfnucinm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cashguo.top/Article/details/gtlcakiahl.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.andypj.xyz/Article/details/gtlpvubdxi.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ybcxt.top/Article/details/gtcbbuxjbc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gzhubu.top/Article/details/gtehwtuuom.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.snrcjt.cn/Article/details/gtarxfsvyy.html

[L05] 上传文件（multipart）
来源：http://dali.jinqigufen.top/Article/details/gtquduvlpf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtokqibaxn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj202588.top/Article/details/gtqsgxydte.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xziqi.cn/Article/details/gtaygkkeju.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhixingplan.top/Article/details/gtyghyskcm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.tian-w.cn/Article/details/gtobtrfoxu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinqigufen.top/Article/details/gthlblgfsg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.snrcjt.cn/Article/details/gtgcrykmlc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtamjphwkm.html

[L06] 解析响应为 JSON
来源：http://dali.bjfxy.top/Article/details/gtabdbcjtr.html

Py:   resp.json()
来源：http://dali.0kj1m.cn/Article/details/gtyotcbnog.html

PHP:  json_decode($body, true);
来源：http://dali.sxryk.cn/Article/details/gtmyiqzjmv.html

JS:   await resp.json()
来源：http://dali.redwolf501.top/Article/details/gtvkpgsnvq.html

TS:   await resp.json()
来源：http://dali.yuxming.cn/Article/details/gtgthquvdn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jqgfzy.top/Article/details/gtkfyavyzz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.smart0.xyz/Article/details/gtjmyjbsli.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hnqzz.top/Article/details/gtvphprani.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zdqjudy.top/Article/details/gtdszoxsbl.html

[L07] 处理 HTTP 状态码
来源：http://dali.sweek.top/Article/details/gtfbsjnrrl.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinqigfzy.top/Article/details/gtlwgsbjhk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhongyouzk.top/Article/details/gtcuzxdmkh.html

JS:   resp.ok;  resp.status
来源：http://dali.mhx1999.top/Article/details/gtbilzoyow.html

TS:   resp.ok;  resp.status
来源：http://dali.yangfankeji.com/Article/details/gttrvvwwpf.html

Java: resp.statusCode()
来源：http://dali.fzhhl.top/Article/details/gtgeouuame.html

Go:   resp.StatusCode
来源：http://dali.mhx1999.top/Article/details/gtaizwtxhu.html

Ruby: resp.code.to_i
来源：http://dali.yvedp.cn/Article/details/gtkwwkrafq.html

C#:   (int)resp.StatusCode
来源：http://dali.chenjidiqi.icu/Article/details/gtzyqzxsuk.html

[L08] 并发请求多个地址
来源：http://dali.cdnleiting.top/Article/details/gtpbaxcmtr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhiwuduotai.top/Article/details/gtwqdlcwku.html

PHP:  curl_multi_init() 系列
来源：http://dali.dianchejie.cn/Article/details/gtpxxcemca.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yvedp.cn/Article/details/gtxqyslcrg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.iojbl.cn/Article/details/gthtlqhrrc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jianghu66.top/Article/details/gtxatewxiq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.wangshuangyany.cn/Article/details/gtldthpyft.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.kuanghao11.cn/Article/details/gtviexrtrv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jiagoushi.top/Article/details/gtnudsklgr.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtkwwipsoa.html

M. 命令行 / 进程 / 环境
来源：http://dali.guannengcc.top/Article/details/gtaazrfvzo.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtqhrijtcx.html

[M01] 读取命令行参数
来源：http://dali.zhixingplan.top/Article/details/gtnyejbnyg.html

Py:   sys.argv[1:]
来源：http://dali.pycfn.com/Article/details/gtatpkwhst.html

PHP:  $argv;  $argc;
来源：http://dali.cucudq.cn/Article/details/gtxtnfvlfz.html

JS:   process.argv.slice(2)
来源：http://dali.sysykeji.top/Article/details/gtbiybskjx.html

TS:   process.argv.slice(2)
来源：http://dali.meibo888.top/Article/details/gtfxwptgpu.html

Java: args 数组（main 方法参数）
来源：http://dali.yvedp.cn/Article/details/gtkdwltxqr.html

Go:   os.Args[1:]
来源：http://dali.jqgufenzy.top/Article/details/gtopdnujwh.html

Ruby: ARGV
来源：http://dali.yanxiufei.cn/Article/details/gtgzrrcvmd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gzhubu.top/Article/details/gtxxrzwabc.html

[M02] 读取环境变量
来源：http://dali.cashguo.top/Article/details/gtmqsvreio.html

Py:   os.environ.get("HOME")
来源：http://dali.sxryk.cn/Article/details/gtkvfrlfmi.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jyoumei.cn/Article/details/gtjflnfxba.html

JS:   process.env.HOME
来源：http://dali.hnxiangtu.top/Article/details/gtnryuiivl.html

TS:   process.env.HOME
来源：http://dali.tian-w.cn/Article/details/gtdfbtssmi.html

Java: System.getenv("HOME")
来源：http://dali.aizwys.cn/Article/details/gtgshpdlkv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sweek.top/Article/details/gtzftovfgq.html

Ruby: ENV["HOME"]
来源：http://dali.meibo888.top/Article/details/gtfhgeknwy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.mhx1999.top/Article/details/gtbsbqsmzc.html

[M03] 执行外部命令
来源：http://dali.gogol.net.cn/Article/details/gtzgqwzasa.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jianghu66.top/Article/details/gtzjlqzvxl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.meibo888.top/Article/details/gtfekmyxpu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.pengpengdd.cyou/Article/details/gtwzqyjlrd.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhixingplan.top/Article/details/gtsvixkprz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinghuilouyu.cn/Article/details/gtghbnireq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.daria6918.cn/Article/details/gtqiwplzuq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.chenzaomai.com/Article/details/gtleqqwjdf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sweek.top/Article/details/gtfinrezqs.html

[M04] 获取当前工作目录
来源：http://dali.yanxiufei.cn/Article/details/gtqkoadobb.html

Py:   os.getcwd()
来源：http://dali.gzhubu.top/Article/details/gtyriyfnmc.html

PHP:  getcwd();
来源：http://dali.iojbl.cn/Article/details/gtbwezsghp.html

JS:   process.cwd()
来源：http://dali.yuxming.cn/Article/details/gthtbwsdrk.html

TS:   process.cwd()
来源：http://dali.jinqigufen.top/Article/details/gtexjyedok.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gaohongyu789.top/Article/details/gtlkctkcod.html

Go:   os.Getwd()
来源：http://dali.zhixingplan.top/Article/details/gthsjskqcm.html

Ruby: Dir.pwd
来源：http://dali.guannengcc.top/Article/details/gtaxxziadg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.wangdashe.top/Article/details/gtfhqjjudy.html

[M05] 设置退出码
来源：http://dali.hysaishi.cn/Article/details/gttxuvgzje.html

Py:   sys.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtzxojfenk.html

PHP:  exit(1);
来源：http://dali.ppjwa.cn/Article/details/gtonpucwop.html

JS:   process.exit(1)
来源：http://dali.yueranfly.top/Article/details/gtgblvfbai.html

TS:   process.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gttumykyav.html

Java: System.exit(1)
来源：http://dali.cucudq.cn/Article/details/gtkatacglt.html

Go:   os.Exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtitpabekg.html

Ruby: exit 1
来源：http://dali.chenjidiqi.icu/Article/details/gtbcsrxyqj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cqqwz.cn/Article/details/gteiqbbqnt.html

[M06] 向标准错误输出
来源：http://dali.gogol.net.cn/Article/details/gtdohcfjvu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xinyue.icu/Article/details/gtnqepzosf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.c1oappe.top/Article/details/gtjjscfzda.html

JS:   console.error("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gtiivracyk.html

TS:   console.error("err")
来源：http://dali.guowangkeji.top/Article/details/gtbghhcvng.html

Java: System.err.println("err")
来源：http://dali.iojbl.cn/Article/details/gthxkjoggn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhixingplan.top/Article/details/gtoiresegs.html

Ruby: warn "err"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuzbkgzwu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yueranfly.top/Article/details/gtxfanqglp.html

[M07] 判断是否为主入口
来源：http://dali.tianlin.xyz/Article/details/gtfnlxkxwt.html

Py:   if __name__ == "__main__":
来源：http://dali.xuetiantiany.cn/Article/details/gttcqhpctb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cdnleiting.top/Article/details/gtylskaobs.html

JS:   require.main === module
来源：http://dali.chenzaomai.com/Article/details/gtsueoztdd.html

TS:   require.main === module
来源：http://dali.wangshuangyany.cn/Article/details/gtxxfnesos.html

Java: public static void main(String[] args)
来源：http://dali.zhongyouzk.top/Article/details/gtlejwumnk.html

Go:   func main()
来源：http://dali.jinqigfzy.top/Article/details/gtkigzxaso.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.aizwys.cn/Article/details/gtionpucfx.html

C#:   static void Main(string[] args)
来源：http://dali.jyoumei.cn/Article/details/gttqaterkb.html

[M08] 获取系统与运行时信息
来源：http://dali.yanxiufei.cn/Article/details/gtunvmtgjz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhongyouzk.top/Article/details/gtnlsolhkx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.daxiang520.top/Article/details/gtwikgfjsj.html

JS:   process.platform;  process.version
来源：http://dali.aizwys.cn/Article/details/gtisljsino.html

TS:   process.platform;  process.version
来源：http://dali.aibaodan.cn/Article/details/gtynbofjbq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xuanzx.com/Article/details/gtbkvgtbua.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.svipenyu.cn/Article/details/gtgsdkzibj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.kuanghao11.cn/Article/details/gtvzbcftya.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yangfankeji.com/Article/details/gtqylliwav.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtgahztdfe.html

N. 数据结构与算法
来源：http://dali.xziqi.cn/Article/details/gtnftplvyh.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtgrjffmcy.html

[N01] 二分查找（有序数组）
来源：http://dali.yj20258.top/Article/details/gtvunclvvq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.gzhubu.top/Article/details/gtuaefjcma.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.gotoacloud.top/Article/details/gtiocolejz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnxiangtu.top/Article/details/gtwbywcxwf.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xinyue.icu/Article/details/gtqwynfxxk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyuzghwdu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gtucggqeob.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.tanke756.top/Article/details/gterbnbkiv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtcrnyapvw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xuetiantiany.cn/Article/details/gtrfvzrsnd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.bjfxy.top/Article/details/gtsylojipn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.meibo888.top/Article/details/gtlkxxzhtl.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.kuanghao11.cn/Article/details/gtmcgqotim.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.iojbl.cn/Article/details/gtpqaobcdq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cashguo.top/Article/details/gtcwrmhejf.html

Go:   slices.Sort(arr)
来源：http://dali.yuxming.cn/Article/details/gtgojoczxx.html


<!-- 参考信息 -->