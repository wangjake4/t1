代发 wailian999

TS:   new Date("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gtklfqnzfl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtmhwwjhtt.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gttiedxqms.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gtwlzcxfna.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cqqwz.cn/Article/details/gtmaivfnog.html

[J04] 时间戳与日期互转
来源：http://dali.zhoulong.xyz/Article/details/gtyelkwliv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.fengsongda.top/Article/details/gtfnwtwjnx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinqigufen.top/Article/details/gttrhudoxy.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xziqi.cn/Article/details/gtbogvuago.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.snrcjt.cn/Article/details/gtrzufbwpb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.wangdashe.top/Article/details/gtawonaqbp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hywenlv.cn/Article/details/gtqesgcvbi.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yuxming.cn/Article/details/gtpajzbqam.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yj20258888.top/Article/details/gtlqfigukq.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj20258.top/Article/details/gtjcltevix.html

Py:   now + timedelta(days=7)
来源：http://dali.zhiwuduotai.top/Article/details/gtwiiinmrn.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zycfv.cn/Article/details/gtvgxirhfa.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gaohongyu789.top/Article/details/gtaxslzyyu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sxryk.cn/Article/details/gtthtxwodd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuketoaga.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xuetiantiany.cn/Article/details/gtugfqemdf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xinyue.icu/Article/details/gtcvkleshh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.nwbrower.top/Article/details/gtfrmiqoyx.html

[J06] 计算两时间之差
来源：http://dali.wangshuangyany.cn/Article/details/gtkxkylukv.html

Py:   (end - start).total_seconds()
来源：http://dali.hammf.cn/Article/details/gtrbpheino.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsfcafksv.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ehwqpu.com/Article/details/gtsntufwra.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jyoumei.cn/Article/details/gtstfopexb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj20258888.top/Article/details/gtybyjkeai.html

Go:   end.Sub(start).Hours()
来源：http://dali.andypj.xyz/Article/details/gtfqtbfzuk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.smart0.xyz/Article/details/gtvaycuxlm.html

C#:   (end - start).TotalSeconds
来源：http://dali.yuxming.cn/Article/details/gtvhoeieeq.html

[J07] 比较两个日期
来源：http://dali.shzxlz.cn/Article/details/gtwntnbyfr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gtvpqmcjje.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.vqdsnc.cn/Article/details/gtwoyilkfm.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yueranfly.top/Article/details/gtqmfgqslt.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrifbjjta.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shzxlz.cn/Article/details/gtzrnweetj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj202588.top/Article/details/gtdetaicew.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sufxvd.cn/Article/details/gtckhetril.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gtqcbviaar.html

[J08] 提取年月日与星期
来源：http://dali.zhixingplan.top/Article/details/gtgaycxjgb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hysaishi.cn/Article/details/gtqupwworr.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhiwuduotai.top/Article/details/gtdvzudodu.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.c1oappe.top/Article/details/gtshelltwy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.quarkkingdee.top/Article/details/gthlydgruu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.tanke756.top/Article/details/gtjwkmkgpg.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinqigufen.top/Article/details/gtzdizjyuw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhiwuduotai.top/Article/details/gtyjcvtlhz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhoulong.xyz/Article/details/gtoatppofe.html

[J09] 时区处理
来源：http://dali.chenlongwang.top/Article/details/gtxdexugrf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.guannengcc.top/Article/details/gtjveroqcx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.bjfxy.top/Article/details/gtznltlpcc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aibaodan.cn/Article/details/gtifsfbnqs.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jyoumei.cn/Article/details/gtgvgnjrvn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.andypj.xyz/Article/details/gtrhjdhqhq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtutkbxtit.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cashguo.top/Article/details/gtykoyaxdo.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yj20258888.top/Article/details/gtertpikik.html

[J10] 取今天 / 本月第一天
来源：http://dali.feifeiyinyue.top/Article/details/gtvtennysb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yvedp.cn/Article/details/gttkhmbyep.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shangyingyoupin.top/Article/details/gtrmdnqfgj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xinyue.icu/Article/details/gtglmylfee.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.daria6918.cn/Article/details/gtkrvjlexb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yvedp.cn/Article/details/gtrmhyjoyp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ydzc1.top/Article/details/gtbqfbmeam.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.dianchejie.cn/Article/details/gtipnmswvz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenzaomai.com/Article/details/gtpwgzwtne.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtfxevqowa.html

K. JSON 与序列化
来源：http://dali.daxiang520.top/Article/details/gtbkjoiywh.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtrvjqgbty.html

[K01] 对象转 JSON 字符串
来源：http://dali.svipenyu.cn/Article/details/gttbgpiame.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkohpyrcf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.iojbl.cn/Article/details/gtgyxklrzt.html

JS:   JSON.stringify(obj)
来源：http://dali.sxryk.cn/Article/details/gtsgxxetlx.html

TS:   JSON.stringify(obj)
来源：http://dali.sysykeji.top/Article/details/gtgytbaldr.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hysaishi.cn/Article/details/gtcwryheht.html

Go:   json.Marshal(obj)
来源：http://dali.yuanzhike.top/Article/details/gtiyyryerx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jlsjyb.cn/Article/details/gtkjfschkv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.9152youxi.cn/Article/details/gtdamvjrey.html

[K02] JSON 字符串转对象
来源：http://dali.ehwqpu.com/Article/details/gtpnbxifxu.html

Py:   json.loads(s)
来源：http://dali.nwbrower.top/Article/details/gtoloiydoe.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yueranfly.top/Article/details/gtzgqtnqdx.html

JS:   JSON.parse(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtgndnopdk.html

TS:   JSON.parse(s)
来源：http://dali.ybcxt.top/Article/details/gteeaiiypo.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gtmualpzij.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hongshengwenyu.top/Article/details/gtxlyrsuoo.html

Ruby: JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgicuceow.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.tanke756.top/Article/details/gtzjasdtni.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.wangdashe.top/Article/details/gtcpxbbpch.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.vqdsnc.cn/Article/details/gtgykvpspl.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yanxiufei.cn/Article/details/gtoxmesuso.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.fengsongda.top/Article/details/gtzovuzgaz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.guowangkeji.top/Article/details/gtmwxsiayo.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfazlrjsd.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yj202588.top/Article/details/gtavinwwzv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hnqzz.top/Article/details/gttoxorlyg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ydzc1.top/Article/details/gtzczkbtmo.html

[K04] 读取 JSON 文件
来源：http://dali.birdmap.top/Article/details/gtbuhsdlsr.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.quarkkingdee.top/Article/details/gtylgpppzx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.svipenyu.cn/Article/details/gtahvmkric.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daxiang520.top/Article/details/gtyjcsesdq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yanxiufei.cn/Article/details/gtaxmkkxns.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zycfv.cn/Article/details/gtgwedfybx.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhoulong.xyz/Article/details/gtmfepvwvv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cashguo.top/Article/details/gtoesdduqd.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yueranfly.top/Article/details/gtqtvhpbwf.html

[K05] 深拷贝对象
来源：http://dali.jyoumei.cn/Article/details/gtnolghrks.html

Py:   copy.deepcopy(obj)
来源：http://dali.daxiang520.top/Article/details/gtaffwedpd.html

PHP:  unserialize(serialize($obj));
来源：http://dali.smart0.xyz/Article/details/gtohfcjasj.html

JS:   structuredClone(obj)
来源：http://dali.xinyue.icu/Article/details/gtcgohqvzg.html

TS:   structuredClone(obj)
来源：http://dali.sweek.top/Article/details/gtrxfbueoe.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.nanxuanxn.top/Article/details/gtnecutwzg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jlsjyb.cn/Article/details/gtkpxzcxeo.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ivvv.top/Article/details/gteowgygrk.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gotoacloud.top/Article/details/gtzfdbdkqp.html

[K06] 解析 URL 查询串
来源：http://dali.meibo888.top/Article/details/gtozvdsosa.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sysykeji.top/Article/details/gtotunolok.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.tanke756.top/Article/details/gtrtefediv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuetiantiany.cn/Article/details/gtgvgbxgbi.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlmzdbawj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.mhx1999.top/Article/details/gthsbzgbef.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jyoumei.cn/Article/details/gtfdcmwtoe.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ehwqpu.com/Article/details/gtpofhbuqd.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gtupdmamfe.html

[K07] 进制转换
来源：http://dali.quarkkingdee.top/Article/details/gtteymfpdv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gttlaqznli.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sweek.top/Article/details/gtoekyrjdn.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gtfmjybwry.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gtwgcxrykv.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gtgvjmbgqr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xuanzx.com/Article/details/gtzynwdxoz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.mhx1999.top/Article/details/gtgjpfjbpw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gtwtewvzpf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.aibaodan.cn/Article/details/gttrdsddsy.html

Py:   pickle.dumps(obj)
来源：http://dali.ydzc1.top/Article/details/gthlytevix.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cheryme.top/Article/details/gtdoppbcze.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cashguo.top/Article/details/gttxzjoxkr.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.guannengcc.top/Article/details/gtoyxyfnlt.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinqigufen.top/Article/details/gtffahcavw.html

Go:   encoding/gob
来源：http://dali.yj20258.top/Article/details/gtyuosmvrq.html

Ruby: Marshal.dump(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtnhyyhgoq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.316326.xyz/Article/details/gtyfafuotu.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtequmvsvs.html

L. 网络请求
来源：http://dali.gotoacloud.top/Article/details/gtpgxehgkp.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtbyhgtvap.html

[L01] 发送 GET 请求
来源：http://dali.daxiang520.top/Article/details/gtgznagrcj.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.andypj.xyz/Article/details/gtxttnromy.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nanxuanxn.top/Article/details/gtyvwsdyto.html

JS:   await fetch(url)
来源：http://dali.zhixingplan.top/Article/details/gtzrrihyfv.html

TS:   await fetch(url)
来源：http://dali.cucudq.cn/Article/details/gtbvnvesgt.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.bjfxy.top/Article/details/gtnkshhufe.html

Go:   resp, err := http.Get(url)
来源：http://dali.cheryme.top/Article/details/gtvgctbvad.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shangyingyoupin.top/Article/details/gtbjqbjkqu.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sufxvd.cn/Article/details/gtauskkylu.html

[L02] 发送 POST JSON
来源：http://dali.guannengcc.top/Article/details/gthjgexegf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yueranfly.top/Article/details/gtrdjhrqoq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.wangshuangyany.cn/Article/details/gtjeeubxea.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yangfankeji.com/Article/details/gtdfeuijvy.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cdnleiting.top/Article/details/gtnsorgsjb.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.smart0.xyz/Article/details/gtmhrlpuzi.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ivvv.top/Article/details/gtelarofwb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.aibaodan.cn/Article/details/gthignzuyh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinqigfzy.top/Article/details/gtickqkaml.html

[L03] 设置自定义请求头
来源：http://dali.hnqzz.top/Article/details/gtwlneqngx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cdnleiting.top/Article/details/gtnjkjtvms.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ydzc1.top/Article/details/gttuygllae.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnxsmxqss.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tianlin.xyz/Article/details/gtbgebuypj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.nanxuanxn.top/Article/details/gtpzlgakex.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhixingplan.top/Article/details/gtklfpvdpg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.wangdashe.top/Article/details/gtpnrtpufd.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gtygoznsfx.html

[L04] 设置超时
来源：http://dali.sufxvd.cn/Article/details/gtdxdzemlc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zdqjudy.top/Article/details/gtjerspmmr.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.tianlin.xyz/Article/details/gtafduycqp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yonumen.top/Article/details/gtojctktic.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhixingplan.top/Article/details/gtragwojjh.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yongpay.top/Article/details/gtnzdvmzsb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sysykeji.top/Article/details/gthspcvghy.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.chenlongwang.top/Article/details/gtpsthbxdf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hywenlv.cn/Article/details/gtxbesbxeg.html

[L05] 上传文件（multipart）
来源：http://dali.feifeiyinyue.top/Article/details/gtinhtqleo.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.guowangkeji.top/Article/details/gtbfjswqvp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.svipenyu.cn/Article/details/gtnbznqxpk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.dianchejie.cn/Article/details/gtddssvgbd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.andypj.xyz/Article/details/gtwxlfakmp.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cucudq.cn/Article/details/gtqlfumuny.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.dashuyun.cn/Article/details/gtdvjjokqr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.wangdashe.top/Article/details/gtcwjkjegz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtqnrsownw.html

[L06] 解析响应为 JSON
来源：http://dali.yueranfly.top/Article/details/gtavznskxp.html

Py:   resp.json()
来源：http://dali.zycfv.cn/Article/details/gtamowjtmo.html

PHP:  json_decode($body, true);
来源：http://dali.mhx1999.top/Article/details/gtqdnabjgo.html

JS:   await resp.json()
来源：http://dali.hammf.cn/Article/details/gtghajfumb.html

TS:   await resp.json()
来源：http://dali.hywenlv.cn/Article/details/gtfmakviiv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.aibaodan.cn/Article/details/gtyhacslvr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xziqi.cn/Article/details/gtkpxgtxtj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gaohongyu789.top/Article/details/gtojoyjmat.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.chenjidiqi.icu/Article/details/gtjeiwdtfm.html

[L07] 处理 HTTP 状态码
来源：http://dali.xuanzx.com/Article/details/gtupopdxqu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.haohaochexian.top/Article/details/gthbnajrrc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cqqwz.cn/Article/details/gtqvireiac.html

JS:   resp.ok;  resp.status
来源：http://dali.pengpengdd.cyou/Article/details/gtqokmatru.html

TS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangtech.top/Article/details/gtprrxslon.html

Java: resp.statusCode()
来源：http://dali.hnxiangtu.top/Article/details/gtqmggsswg.html

Go:   resp.StatusCode
来源：http://dali.xziqi.cn/Article/details/gtobwfrdzz.html

Ruby: resp.code.to_i
来源：http://dali.sysykeji.top/Article/details/gtfqmyohbh.html

C#:   (int)resp.StatusCode
来源：http://dali.ybcxt.top/Article/details/gtqzydpgyw.html

[L08] 并发请求多个地址
来源：http://dali.yangfankeji.com/Article/details/gttfssrejb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.svipenyu.cn/Article/details/gtlcjugrrt.html

PHP:  curl_multi_init() 系列
来源：http://dali.xuetiantiany.cn/Article/details/gtebldbilt.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.kuanghao11.cn/Article/details/gtuasfdskp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jlsjyb.cn/Article/details/gtcdqpeyii.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gaohongyu789.top/Article/details/gtmuavqvby.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinghuilouyu.cn/Article/details/gttfsclmbm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hnqzz.top/Article/details/gtmtfiuaxm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yuxming.cn/Article/details/gtlpbawpne.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtafrgmjvw.html

M. 命令行 / 进程 / 环境
来源：http://dali.yongpay.top/Article/details/gtostdejcj.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtlbbaujuk.html

[M01] 读取命令行参数
来源：http://dali.zhixingplan.top/Article/details/gtaupzirjp.html

Py:   sys.argv[1:]
来源：http://dali.xziqi.cn/Article/details/gteupfrkil.html

PHP:  $argv;  $argc;
来源：http://dali.nwbrower.top/Article/details/gtvqsukbsb.html

JS:   process.argv.slice(2)
来源：http://dali.hnxiangtu.top/Article/details/gtjwghxcje.html

TS:   process.argv.slice(2)
来源：http://dali.guannengcc.top/Article/details/gthfaypjyo.html

Java: args 数组（main 方法参数）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtktracuyb.html

Go:   os.Args[1:]
来源：http://dali.hywenlv.cn/Article/details/gtxjujfzvy.html

Ruby: ARGV
来源：http://dali.cdnleiting.top/Article/details/gtdlywtugu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhengqikj.top/Article/details/gtpiizukqy.html

[M02] 读取环境变量
来源：http://dali.tian-w.cn/Article/details/gtljjcizze.html

Py:   os.environ.get("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gtobwcpkeg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.bjfxy.top/Article/details/gtvognfcdn.html

JS:   process.env.HOME
来源：http://dali.jiagoushi.top/Article/details/gtlkslqzah.html

TS:   process.env.HOME
来源：http://dali.iojbl.cn/Article/details/gtuowdxlhf.html

Java: System.getenv("HOME")
来源：http://dali.smart0.xyz/Article/details/gtakvryxhk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.9152youxi.cn/Article/details/gtgvoiupqt.html

Ruby: ENV["HOME"]
来源：http://dali.dianchejie.cn/Article/details/gtuanwyzkp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj202588.top/Article/details/gtzwcdjpmp.html

[M03] 执行外部命令
来源：http://dali.tian-w.cn/Article/details/gtfwazdzpb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hywenlv.cn/Article/details/gtvwubjnrl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhoulong.xyz/Article/details/gtmyuinhst.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.mhx1999.top/Article/details/gtpdsggkpf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ydzc1.top/Article/details/gtvvxsoxyd.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xziqi.cn/Article/details/gtlhvgxcbz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.aibaodan.cn/Article/details/gtgoosyssz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shzxlz.cn/Article/details/gtnpqlntld.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ybcxt.top/Article/details/gtxsvpzkgd.html

[M04] 获取当前工作目录
来源：http://dali.xuanzx.com/Article/details/gtsvohwcnv.html

Py:   os.getcwd()
来源：http://dali.zhoulong.xyz/Article/details/gthiecojmw.html

PHP:  getcwd();
来源：http://dali.shangyingyoupin.top/Article/details/gtwtfxtzwd.html

JS:   process.cwd()
来源：http://dali.yueranfly.top/Article/details/gtgcnwvuyz.html

TS:   process.cwd()
来源：http://dali.vqdsnc.cn/Article/details/gtwychbgck.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.pengpengdd.cyou/Article/details/gtlrijrugl.html

Go:   os.Getwd()
来源：http://dali.yuxming.cn/Article/details/gttktptrqs.html

Ruby: Dir.pwd
来源：http://dali.zhengqikj.top/Article/details/gtoyzwrcjl.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shanyushiyangtech.top/Article/details/gtzwwxdlrq.html

[M05] 设置退出码
来源：http://dali.ydzc1.top/Article/details/gtqilouany.html

Py:   sys.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gtiirwwedt.html

PHP:  exit(1);
来源：http://dali.c1oappe.top/Article/details/gtdkczunfk.html

JS:   process.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gtgasogpxo.html

TS:   process.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gttclpntvt.html

Java: System.exit(1)
来源：http://dali.aizwys.cn/Article/details/gtoxckbvrw.html

Go:   os.Exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtylmchczd.html

Ruby: exit 1
来源：http://dali.shzxlz.cn/Article/details/gtluduryma.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.gotoacloud.top/Article/details/gtemjmbifv.html

[M06] 向标准错误输出
来源：http://dali.gogol.net.cn/Article/details/gtimmgibmj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xziqi.cn/Article/details/gtlwiadurg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shanyushiyangtech.top/Article/details/gtvznxtria.html

JS:   console.error("err")
来源：http://dali.hongshengwenyu.top/Article/details/gteqsedyrb.html

TS:   console.error("err")
来源：http://dali.nanxuanxn.top/Article/details/gtbwqzarlr.html

Java: System.err.println("err")
来源：http://dali.9152youxi.cn/Article/details/gtxyitxhru.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sufxvd.cn/Article/details/gtxjxyhvbl.html

Ruby: warn "err"
来源：http://dali.sysykeji.top/Article/details/gttitwtgog.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.pengpengdd.cyou/Article/details/gtifyovati.html

[M07] 判断是否为主入口
来源：http://dali.snrcjt.cn/Article/details/gtkwvhafpv.html

Py:   if __name__ == "__main__":
来源：http://dali.yj20258.top/Article/details/gtzallppkn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xylfe.cn/Article/details/gtqszdehnb.html

JS:   require.main === module
来源：http://dali.9152youxi.cn/Article/details/gtdporrwpo.html

TS:   require.main === module
来源：http://dali.jlsjyb.cn/Article/details/gthtvjsdoz.html

Java: public static void main(String[] args)
来源：http://dali.zhongyouzk.top/Article/details/gtkhgcebpz.html

Go:   func main()
来源：http://dali.xziqi.cn/Article/details/gtupdooibq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.wangshuangyany.cn/Article/details/gtcdlgmlco.html

C#:   static void Main(string[] args)
来源：http://dali.guowangkeji.top/Article/details/gtmpcgldva.html

[M08] 获取系统与运行时信息
来源：http://dali.cdnleiting.top/Article/details/gtpshzvzhf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.aibaodan.cn/Article/details/gtflwlvxhv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzoyfkzlx.html

JS:   process.platform;  process.version
来源：http://dali.xziqi.cn/Article/details/gtbepfccyc.html

TS:   process.platform;  process.version
来源：http://dali.redwolf501.top/Article/details/gtuegjkroc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ydzc1.top/Article/details/gtrxvcnhjc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.aibaodan.cn/Article/details/gtjdzjpfzp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yangfankeji.com/Article/details/gtbpadcxqq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpzxqyldn.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtmpsqbxjr.html

N. 数据结构与算法
来源：http://dali.chenjidiqi.icu/Article/details/gtzrrdntyi.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtoetbmhls.html

[N01] 二分查找（有序数组）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqzxokbfn.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtrcugxicb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhongyouzk.top/Article/details/gtnyjtiotw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigufen.top/Article/details/gtmsjrdrmf.html


<!-- 参考信息 -->