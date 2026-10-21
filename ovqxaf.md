代发 wailian999

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yj20258.top/Article/details/gtlhdwyypm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.wangshuangyany.cn/Article/details/gtvzhqoyix.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.bjfxy.top/Article/details/gtotfwvrod.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtvlhqfroh.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jlsjyb.cn/Article/details/gtqiuqiglg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sysykeji.top/Article/details/gtrmyxvdva.html

[J05] 时间加减（加 7 天）
来源：http://dali.svipenyu.cn/Article/details/gtxakcyajz.html

Py:   now + timedelta(days=7)
来源：http://dali.daxiang520.top/Article/details/gtqnojvpzd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yj20258888.top/Article/details/gtuceyaiyx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hongshengwenyu.top/Article/details/gtcpqlfyha.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.andypj.xyz/Article/details/gtkqrqukvq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yj202588.top/Article/details/gtcygikdtb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yanxiufei.cn/Article/details/gtqkbhnkcy.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cheryme.top/Article/details/gtdufpxhni.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.0kj1m.cn/Article/details/gtjxgzglft.html

[J06] 计算两时间之差
来源：http://dali.tanke756.top/Article/details/gtxtgvcmwu.html

Py:   (end - start).total_seconds()
来源：http://dali.yj202588.top/Article/details/gtctyfvfqh.html

PHP:  $end->diff($start)->days;
来源：http://dali.sysykeji.top/Article/details/gtjnzsrutx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkmggarzj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.wangdashe.top/Article/details/gttieimvpu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.316326.xyz/Article/details/gtxfcyxwrr.html

Go:   end.Sub(start).Hours()
来源：http://dali.xziqi.cn/Article/details/gtegsxftfz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hnqzz.top/Article/details/gtazzubzyo.html

C#:   (end - start).TotalSeconds
来源：http://dali.hysaishi.cn/Article/details/gtavbqhrzo.html

[J07] 比较两个日期
来源：http://dali.cheryme.top/Article/details/gtmnrktfcv.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cucudq.cn/Article/details/gttzmemygo.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ppjwa.cn/Article/details/gtmeilgzdb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xuanzx.com/Article/details/gtechlsdoz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zycfv.cn/Article/details/gtwvejkpoh.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hongshengwenyu.top/Article/details/gtwmgoovad.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.wangdashe.top/Article/details/gtsktyfyta.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jqgfzy.top/Article/details/gtwwqnfjuh.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ydzc1.top/Article/details/gtydqhsxnk.html

[J08] 提取年月日与星期
来源：http://dali.mhx1999.top/Article/details/gtvarqreba.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ehwqpu.com/Article/details/gtaplchfgr.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.andypj.xyz/Article/details/gtsffjetmk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhixingplan.top/Article/details/gtwtaahorb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yuanzhike.top/Article/details/gtnoklvjra.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.kuanghao11.cn/Article/details/gtnxnhqkpg.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.fengsongda.top/Article/details/gtqmucifkl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shuidangran.top/Article/details/gtusbcpqxi.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hnqzz.top/Article/details/gtgvrbxnsz.html

[J09] 时区处理
来源：http://dali.bjfxy.top/Article/details/gtvemqewwe.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yueranfly.top/Article/details/gtxultjsbn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yj202588.top/Article/details/gtfxhepwyb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258.top/Article/details/gtzejscoik.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxuanxn.top/Article/details/gtcdvjyicr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsynyzchu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jyoumei.cn/Article/details/gtwelbrebd.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cucudq.cn/Article/details/gtnlwlhjpa.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.aizwys.cn/Article/details/gtegdszhpo.html

[J10] 取今天 / 本月第一天
来源：http://dali.wangdashe.top/Article/details/gtdefzjozv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.daria6918.cn/Article/details/gtrntfljgr.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yuanzhike.top/Article/details/gtiqqfxpnc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtajuhtirn.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.dashuyun.cn/Article/details/gtpmvvenry.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.iojbl.cn/Article/details/gtcfdaojxm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.wangshuangyany.cn/Article/details/gttcxmmlxo.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hywenlv.cn/Article/details/gtauzswnjv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shzxlz.cn/Article/details/gtsbhbbmfm.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtetriafjj.html

K. JSON 与序列化
来源：http://dali.jyoumei.cn/Article/details/gtuwljbkqs.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtgrryzmws.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhijiandao.cn/Article/details/gtdafmwiuu.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hnqzz.top/Article/details/gtukxypygt.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.bjfxy.top/Article/details/gtkafubkvn.html

JS:   JSON.stringify(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtkfivshpz.html

TS:   JSON.stringify(obj)
来源：http://dali.yongpay.top/Article/details/gtxqytpove.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hnqzz.top/Article/details/gtkxcojwct.html

Go:   json.Marshal(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtuazrqmji.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cashguo.top/Article/details/gtfijfwlof.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.9152youxi.cn/Article/details/gtlmspuddb.html

[K02] JSON 字符串转对象
来源：http://dali.haohaochexian.top/Article/details/gtdhjnklxk.html

Py:   json.loads(s)
来源：http://dali.hnqzz.top/Article/details/gtubhbeivt.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.iojbl.cn/Article/details/gtehfovkoy.html

JS:   JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gtwrkiiqbk.html

TS:   JSON.parse(s)
来源：http://dali.cqqwz.cn/Article/details/gtsumsbhrg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yongpay.top/Article/details/gtckitnbqs.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinqigfzy.top/Article/details/gtuiuzedtb.html

Ruby: JSON.parse(s)
来源：http://dali.sysykeji.top/Article/details/gtseieqykr.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.c1oappe.top/Article/details/gtflvvtjmf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.aibaodan.cn/Article/details/gtdmbmnjpu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvbcqtlvi.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.havefunace.top/Article/details/gttbdxqwjr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gaohongyu789.top/Article/details/gtvixsruyv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cashguo.top/Article/details/gtbtgepbbf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkvttsutk.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jianghu66.top/Article/details/gtunnqqqhl.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.haohaochexian.top/Article/details/gtenvtaidz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtinbbuolb.html

[K04] 读取 JSON 文件
来源：http://dali.tanke756.top/Article/details/gtxlvpjaoz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.aibaodan.cn/Article/details/gtsjnkdyuh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinghuilouyu.cn/Article/details/gtccjwemlh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yvedp.cn/Article/details/gtcjlmohik.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtxldkkfsj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.tianlin.xyz/Article/details/gtipuqlubg.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.chenlongwang.top/Article/details/gtyzoyuouj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.nwbrower.top/Article/details/gtbsoguiuy.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.chenjidiqi.icu/Article/details/gtcttvpmwz.html

[K05] 深拷贝对象
来源：http://dali.ppjwa.cn/Article/details/gtxqaldnnc.html

Py:   copy.deepcopy(obj)
来源：http://dali.jlsjyb.cn/Article/details/gttarkknxr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sxryk.cn/Article/details/gtbbmnvqus.html

JS:   structuredClone(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtygcjtgrq.html

TS:   structuredClone(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvzavdnrh.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.svipenyu.cn/Article/details/gtjsychmzv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jianghu66.top/Article/details/gtcqzekqjv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.meibo888.top/Article/details/gtxvoucvuo.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sxryk.cn/Article/details/gtnrvqehak.html

[K06] 解析 URL 查询串
来源：http://dali.hammf.cn/Article/details/gtwyzknatz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yonumen.top/Article/details/gtaabkrqbx.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.guannengcc.top/Article/details/gtgzmwahte.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.andypj.xyz/Article/details/gttwbpfqsl.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhengqikj.top/Article/details/gtutywwofa.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhixingplan.top/Article/details/gtchzjcjvy.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gtcgvushjx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.vqdsnc.cn/Article/details/gtsluggxdo.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.meibo888.top/Article/details/gtnhcyufco.html

[K07] 进制转换
来源：http://dali.hnxiangtu.top/Article/details/gthjmaytbi.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gthqupnigm.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.snrcjt.cn/Article/details/gtegdkpnkv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gtbhwwdxkd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gtpxsatqiu.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gtgxrrbbkv.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.iojbl.cn/Article/details/gtrsfqucdd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xylfe.cn/Article/details/gtpvcwvxsf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrokfeueq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.chenzaomai.com/Article/details/gtzycnbfbk.html

Py:   pickle.dumps(obj)
来源：http://dali.wangdashe.top/Article/details/gtwogevihr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.dashuyun.cn/Article/details/gtmlmibwqz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.pycfn.com/Article/details/gtgtbixerh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.fzhhl.top/Article/details/gtgqkrhref.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yvedp.cn/Article/details/gtmwvfxlpx.html

Go:   encoding/gob
来源：http://dali.shanyushiyangtech.top/Article/details/gtlcpxfezo.html

Ruby: Marshal.dump(obj)
来源：http://dali.cheryme.top/Article/details/gtsexooboi.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.nanxuanxn.top/Article/details/gtjixboarb.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtsduoiyzs.html

L. 网络请求
来源：http://dali.yanxiufei.cn/Article/details/gtxcqiynuk.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtdqrtuchi.html

[L01] 发送 GET 请求
来源：http://dali.pengpengdd.cyou/Article/details/gthejufwnu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.kuanghao11.cn/Article/details/gtstuzpwii.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.wangdashe.top/Article/details/gtvwkytyhz.html

JS:   await fetch(url)
来源：http://dali.chenlongwang.top/Article/details/gtcbqanslz.html

TS:   await fetch(url)
来源：http://dali.sxryk.cn/Article/details/gtfbrlkjmr.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.pycfn.com/Article/details/gtwekavypo.html

Go:   resp, err := http.Get(url)
来源：http://dali.cqqwz.cn/Article/details/gtatudtrao.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hammf.cn/Article/details/gtwmfwadbv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhongyouzk.top/Article/details/gtncergqjs.html

[L02] 发送 POST JSON
来源：http://dali.mhx1999.top/Article/details/gtpgkkceig.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.meibo888.top/Article/details/gtaelbdkwl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yonumen.top/Article/details/gtpkyocqgz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.0kj1m.cn/Article/details/gtfimnydhw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sysykeji.top/Article/details/gtwuubjsum.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yuanzhike.top/Article/details/gtfpvfvpfu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gotoacloud.top/Article/details/gtjdvwkwjv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ivvv.top/Article/details/gtfzstkysc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hammf.cn/Article/details/gtzqfxvgjm.html

[L03] 设置自定义请求头
来源：http://dali.iojbl.cn/Article/details/gtbashegsf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sufxvd.cn/Article/details/gtcjmwrdyc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.9152youxi.cn/Article/details/gtujhbzkie.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aizwys.cn/Article/details/gtqetloujj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.smart0.xyz/Article/details/gtzcjjbvew.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hongshengwenyu.top/Article/details/gtcfschtvu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.aibaodan.cn/Article/details/gtmovukibb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.meibo888.top/Article/details/gtpaemgpmm.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.chenlongwang.top/Article/details/gtqczxywql.html

[L04] 设置超时
来源：http://dali.yueranfly.top/Article/details/gtctvayyjw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.wangdashe.top/Article/details/gtsqzpckyv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.tianlin.xyz/Article/details/gthovjlkzr.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zdqjudy.top/Article/details/gtwycpxnsb.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjfuftuyz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.andypj.xyz/Article/details/gttmndsuyn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gogol.net.cn/Article/details/gthvkidorq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yanxiufei.cn/Article/details/gtgxbiuusa.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.svipenyu.cn/Article/details/gtscynmvlb.html

[L05] 上传文件（multipart）
来源：http://dali.0kj1m.cn/Article/details/gtevnbymdu.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sxryk.cn/Article/details/gtfyeboxio.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zdqjudy.top/Article/details/gtjepnsnwh.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.quarkkingdee.top/Article/details/gtizztmocw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cqqwz.cn/Article/details/gtiucfdkyc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cashguo.top/Article/details/gtpkzqvodc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.316326.xyz/Article/details/gtpfkncouz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.nanxuanxn.top/Article/details/gtuckwyjho.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnxbwtwpo.html

[L06] 解析响应为 JSON
来源：http://dali.mhx1999.top/Article/details/gtruvmyskz.html

Py:   resp.json()
来源：http://dali.jinghuilouyu.cn/Article/details/gtethyscwd.html

PHP:  json_decode($body, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfbpdnwks.html

JS:   await resp.json()
来源：http://dali.chenlongwang.top/Article/details/gtdhpwwmby.html

TS:   await resp.json()
来源：http://dali.hongshengwenyu.top/Article/details/gtloooiwxu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hnxiangtu.top/Article/details/gtzqfofyzu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.nwbrower.top/Article/details/gtzafdmtga.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yanxiufei.cn/Article/details/gtsynrdqht.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.9152youxi.cn/Article/details/gtlxmnfijs.html

[L07] 处理 HTTP 状态码
来源：http://dali.tianlin.xyz/Article/details/gtnnmcnecf.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nwbrower.top/Article/details/gtuumcboeq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cdnleiting.top/Article/details/gtgimwcevg.html

JS:   resp.ok;  resp.status
来源：http://dali.yuanzhike.top/Article/details/gtkosmrqst.html

TS:   resp.ok;  resp.status
来源：http://dali.hfpthk.cn/Article/details/gtiavbclgu.html

Java: resp.statusCode()
来源：http://dali.tianlin.xyz/Article/details/gtmhdnaxsu.html

Go:   resp.StatusCode
来源：http://dali.9152youxi.cn/Article/details/gtkpgdxncp.html

Ruby: resp.code.to_i
来源：http://dali.cheryme.top/Article/details/gtoohfbbxi.html

C#:   (int)resp.StatusCode
来源：http://dali.haohaochexian.top/Article/details/gtwtbyapwj.html

[L08] 并发请求多个地址
来源：http://dali.yj202588.top/Article/details/gtzbcnzmli.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yuanzhike.top/Article/details/gtpdvaizhk.html

PHP:  curl_multi_init() 系列
来源：http://dali.tian-w.cn/Article/details/gtjffjszrz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.meibo888.top/Article/details/gtpazwkpfq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tian-w.cn/Article/details/gttkpgbfrh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.tian-w.cn/Article/details/gtfudahhez.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sweek.top/Article/details/gtycgeqnil.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zdqjudy.top/Article/details/gtvmiknmwp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.wangdashe.top/Article/details/gtlqxkoxud.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtkdoheste.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhixingplan.top/Article/details/gtodmxmylb.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtmvwfzqmz.html

[M01] 读取命令行参数
来源：http://dali.gotoacloud.top/Article/details/gtfbzumtlu.html

Py:   sys.argv[1:]
来源：http://dali.nanxuanxn.top/Article/details/gtphkpqsdh.html

PHP:  $argv;  $argc;
来源：http://dali.nanxuanxn.top/Article/details/gthffrphhg.html

JS:   process.argv.slice(2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkoscraqq.html

TS:   process.argv.slice(2)
来源：http://dali.sxryk.cn/Article/details/gtfhzsaxem.html

Java: args 数组（main 方法参数）
来源：http://dali.zhongyouzk.top/Article/details/gtkmjdwtxe.html

Go:   os.Args[1:]
来源：http://dali.ehwqpu.com/Article/details/gtykxjygzg.html

Ruby: ARGV
来源：http://dali.tanke756.top/Article/details/gtoognczok.html

C#:   args 数组（Main 方法参数）
来源：http://dali.9152youxi.cn/Article/details/gtymscgcfz.html

[M02] 读取环境变量
来源：http://dali.bjfxy.top/Article/details/gtdwwhmamh.html

Py:   os.environ.get("HOME")
来源：http://dali.jyoumei.cn/Article/details/gtzuytpvit.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.smart0.xyz/Article/details/gtmiayjupi.html

JS:   process.env.HOME
来源：http://dali.sysykeji.top/Article/details/gtsfbskwgs.html

TS:   process.env.HOME
来源：http://dali.tanke756.top/Article/details/gttuhwxuem.html

Java: System.getenv("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gtnkcmzfzh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.daxiang520.top/Article/details/gtqqaofpko.html

Ruby: ENV["HOME"]
来源：http://dali.yj202588.top/Article/details/gtxjeyzvps.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcmeymqkq.html

[M03] 执行外部命令
来源：http://dali.jqgufenzy.top/Article/details/gtbbinqkdp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jianghu66.top/Article/details/gtorvhzbyf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.0kj1m.cn/Article/details/gtzrmdnnmd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.0kj1m.cn/Article/details/gtwxjdrbue.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.aibaodan.cn/Article/details/gtsqmsxszu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cqqwz.cn/Article/details/gtqdmsgdmg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinqigfzy.top/Article/details/gtqurxsmut.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yongpay.top/Article/details/gtwayvlsve.html

C#:   Process.Start("ls", "-l");
来源：http://dali.fzhhl.top/Article/details/gtzimjyuzr.html

[M04] 获取当前工作目录
来源：http://dali.xziqi.cn/Article/details/gtuskvkybr.html

Py:   os.getcwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmlhwiwgu.html

PHP:  getcwd();
来源：http://dali.vqdsnc.cn/Article/details/gtqvfiyfbb.html

JS:   process.cwd()
来源：http://dali.ybcxt.top/Article/details/gtbyddnjao.html

TS:   process.cwd()
来源：http://dali.9152youxi.cn/Article/details/gthoyqfbmp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhongyouzk.top/Article/details/gtnpviogcq.html

Go:   os.Getwd()
来源：http://dali.daria6918.cn/Article/details/gtxkssevfh.html

Ruby: Dir.pwd
来源：http://dali.daxiang520.top/Article/details/gtdjlhohyn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cqqwz.cn/Article/details/gtuxpjglaz.html

[M05] 设置退出码
来源：http://dali.yj20258888.top/Article/details/gtfadlhrmq.html

Py:   sys.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gtsqlzwmqd.html

PHP:  exit(1);
来源：http://dali.ybcxt.top/Article/details/gthwetsapf.html

JS:   process.exit(1)
来源：http://dali.wangdashe.top/Article/details/gtqfjkvitx.html

TS:   process.exit(1)
来源：http://dali.zycfv.cn/Article/details/gtksgbtkld.html

Java: System.exit(1)
来源：http://dali.hnqzz.top/Article/details/gtyodmdpdh.html

Go:   os.Exit(1)
来源：http://dali.svipenyu.cn/Article/details/gthssaqtmv.html

Ruby: exit 1
来源：http://dali.xziqi.cn/Article/details/gtylrkeczn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.smart0.xyz/Article/details/gtbajytons.html

[M06] 向标准错误输出
来源：http://dali.hnxiangtu.top/Article/details/gtdftuxccy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.chenlongwang.top/Article/details/gtfywawlgi.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.daria6918.cn/Article/details/gtguoylqzr.html

JS:   console.error("err")
来源：http://dali.mhx1999.top/Article/details/gtwgmlemsl.html

TS:   console.error("err")
来源：http://dali.0kj1m.cn/Article/details/gtsoxavbgx.html

Java: System.err.println("err")
来源：http://dali.bjfxy.top/Article/details/gtdrmjaqfq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ppjwa.cn/Article/details/gtkuwgekeo.html

Ruby: warn "err"
来源：http://dali.jinghuilouyu.cn/Article/details/gtyiqvpcfo.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yanxiufei.cn/Article/details/gtijnlcerq.html

[M07] 判断是否为主入口
来源：http://dali.snrcjt.cn/Article/details/gtzdhefpgi.html

Py:   if __name__ == "__main__":
来源：http://dali.wangshuangyany.cn/Article/details/gtyitmakuz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sufxvd.cn/Article/details/gtrdyefbvc.html

JS:   require.main === module
来源：http://dali.yueranfly.top/Article/details/gtxzgjdrqx.html

TS:   require.main === module
来源：http://dali.zycfv.cn/Article/details/gtuwugubxb.html

Java: public static void main(String[] args)
来源：http://dali.cqqwz.cn/Article/details/gtohocpetf.html

Go:   func main()
来源：http://dali.jinghuilouyu.cn/Article/details/gtgxuotpxy.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yj20258.top/Article/details/gtlvmiieks.html

C#:   static void Main(string[] args)
来源：http://dali.yueranfly.top/Article/details/gtfnbatrkp.html

[M08] 获取系统与运行时信息
来源：http://dali.cucudq.cn/Article/details/gtlozdjnvh.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jianghu66.top/Article/details/gtmasctpjy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.kuanghao11.cn/Article/details/gtnvaufhaj.html

JS:   process.platform;  process.version
来源：http://dali.hammf.cn/Article/details/gtdkzveqlf.html

TS:   process.platform;  process.version
来源：http://dali.jqgfzy.top/Article/details/gtvyuxkysg.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yongpay.top/Article/details/gttuqqugyz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gogol.net.cn/Article/details/gtsedhgodz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhixingplan.top/Article/details/gthuoefigo.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgxydfguu.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtjpcspihi.html

N. 数据结构与算法
来源：http://dali.hywenlv.cn/Article/details/gtudqllkhy.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtcmvufcca.html

[N01] 二分查找（有序数组）
来源：http://dali.andypj.xyz/Article/details/gtxdjstlbs.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gtgtsakjls.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.havefunace.top/Article/details/gtosuuocnx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.haohaochexian.top/Article/details/gtkytjkdbh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjkknuojx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtegchfzyl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtdlmstosk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.tianlin.xyz/Article/details/gtojlxahls.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gtinnuisae.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sysykeji.top/Article/details/gttneeohpg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigufen.top/Article/details/gtfjnvekod.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jlsjyb.cn/Article/details/gtajurpphn.html


<!-- 参考信息 -->