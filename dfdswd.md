代发 wailian999

[J03] 字符串解析为日期
来源：http://dali.yuxming.cn/Article/details/gtdpzrnciu.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jianghu66.top/Article/details/gtfcknukzi.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jlsjyb.cn/Article/details/gtbeswgtfv.html

JS:   new Date("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvqqglapd.html

TS:   new Date("2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gtneijbfkp.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtfagauary.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtusajlkyp.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gttxjkkqpn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.chenzaomai.com/Article/details/gttavoures.html

[J04] 时间戳与日期互转
来源：http://dali.haohaochexian.top/Article/details/gtyysblnlw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yuxming.cn/Article/details/gttehhvchv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ehwqpu.com/Article/details/gtmgsikfaz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cqqwz.cn/Article/details/gtcfimdaco.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xuetiantiany.cn/Article/details/gttahdnbux.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.havefunace.top/Article/details/gtvcfqqlpc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.iojbl.cn/Article/details/gtvyzwkogi.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shuidangran.top/Article/details/gtmhkzwvhy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.andypj.xyz/Article/details/gtuklrwezz.html

[J05] 时间加减（加 7 天）
来源：http://dali.birdmap.top/Article/details/gtiqmhcajf.html

Py:   now + timedelta(days=7)
来源：http://dali.gotoacloud.top/Article/details/gtzhqastxb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinqigufen.top/Article/details/gtbnbnvehu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gotoacloud.top/Article/details/gtbfppftap.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cheryme.top/Article/details/gtfqlsafpq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cheryme.top/Article/details/gtsbhfangn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinqigfzy.top/Article/details/gtlmumbxle.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sweek.top/Article/details/gtjjegdiak.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.tianlin.xyz/Article/details/gtvqurouxk.html

[J06] 计算两时间之差
来源：http://dali.xuetiantiany.cn/Article/details/gtbvvrhpev.html

Py:   (end - start).total_seconds()
来源：http://dali.sufxvd.cn/Article/details/gtgrclkjsc.html

PHP:  $end->diff($start)->days;
来源：http://dali.yj202588.top/Article/details/gtaukfkufq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yuanzhike.top/Article/details/gtvcuusujy.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ydzc1.top/Article/details/gtjoaffezk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shanyushiyangtech.top/Article/details/gtxagmozhw.html

Go:   end.Sub(start).Hours()
来源：http://dali.dashuyun.cn/Article/details/gthfrduzxa.html

Ruby: end - start                 # 返回秒数
来源：http://dali.aizwys.cn/Article/details/gtjmhrwcvh.html

C#:   (end - start).TotalSeconds
来源：http://dali.xziqi.cn/Article/details/gtvhxsvxkk.html

[J07] 比较两个日期
来源：http://dali.kuanghao11.cn/Article/details/gtdyzdpnqr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yonumen.top/Article/details/gtfymzzekr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.fzhhl.top/Article/details/gthvscespm.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nwbrower.top/Article/details/gtgqiehdfh.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.iojbl.cn/Article/details/gtyxrcfawh.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cdnleiting.top/Article/details/gtuyyuawpx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.wangdashe.top/Article/details/gtykopxwkr.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.wangdashe.top/Article/details/gtdbomyuun.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.daria6918.cn/Article/details/gtslujsnyj.html

[J08] 提取年月日与星期
来源：http://dali.xuetiantiany.cn/Article/details/gtzmnldojy.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.wangdashe.top/Article/details/gtbaiwdqcj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.nanxuanxn.top/Article/details/gtqqgmdrep.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yvedp.cn/Article/details/gtkfuhjchd.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nanxuanxn.top/Article/details/gtijqilewx.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.316326.xyz/Article/details/gtqfyzknlu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gotoacloud.top/Article/details/gtrkkbxghw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jiagoushi.top/Article/details/gtdxzputhz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yueranfly.top/Article/details/gtltswdfsa.html

[J09] 时区处理
来源：http://dali.yueranfly.top/Article/details/gtvjlnwdfa.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xziqi.cn/Article/details/gtdlublgvz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yanxiufei.cn/Article/details/gtyiocqfvy.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cheryme.top/Article/details/gtrhjaejrc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dashuyun.cn/Article/details/gtyzelrykx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jiagoushi.top/Article/details/gtxmeizkpl.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xylfe.cn/Article/details/gtguvaeswu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gotoacloud.top/Article/details/gtzgpkvdvh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xuanzx.com/Article/details/gtdhqrjxfl.html

[J10] 取今天 / 本月第一天
来源：http://dali.316326.xyz/Article/details/gtdbxummbo.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yuxming.cn/Article/details/gtvbprljur.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hammf.cn/Article/details/gtvlrjoqjh.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.kuanghao11.cn/Article/details/gtwqyojyxq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yongpay.top/Article/details/gtpfggngif.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzyyhtymc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.havefunace.top/Article/details/gtbkgwzsdp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xylfe.cn/Article/details/gtvwabmrii.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jyoumei.cn/Article/details/gtdyjpwuek.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtkdvketot.html

K. JSON 与序列化
来源：http://dali.zhengqikj.top/Article/details/gtsvnohpvs.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtljguhics.html

[K01] 对象转 JSON 字符串
来源：http://dali.yj20258888.top/Article/details/gtopirggny.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ydzc1.top/Article/details/gtihedgwgi.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.fzhhl.top/Article/details/gtwucekwit.html

JS:   JSON.stringify(obj)
来源：http://dali.cheryme.top/Article/details/gtunnexyck.html

TS:   JSON.stringify(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtcgrxgwqj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.0kj1m.cn/Article/details/gtpkshpzni.html

Go:   json.Marshal(obj)
来源：http://dali.tianlin.xyz/Article/details/gtlkbgetch.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.guowangkeji.top/Article/details/gtdpfladdd.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.iojbl.cn/Article/details/gtgvbkyiyb.html

[K02] JSON 字符串转对象
来源：http://dali.c1oappe.top/Article/details/gtmpjdontz.html

Py:   json.loads(s)
来源：http://dali.nanxuanxn.top/Article/details/gtepxtahmw.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.birdmap.top/Article/details/gtmybahvpy.html

JS:   JSON.parse(s)
来源：http://dali.yvedp.cn/Article/details/gtkkdtizar.html

TS:   JSON.parse(s)
来源：http://dali.hnqzz.top/Article/details/gtwwqvtvwl.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yonumen.top/Article/details/gturpgptjx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.pycfn.com/Article/details/gtgcuhrwrl.html

Ruby: JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gtgumsgljv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.guowangkeji.top/Article/details/gtpktssezu.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ivvv.top/Article/details/gtouyiypke.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhongyouzk.top/Article/details/gtgzlnenbb.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jianghu66.top/Article/details/gtuyttjmqh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkxbepeom.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ivvv.top/Article/details/gtmdkbopvx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zdqjudy.top/Article/details/gtirpwgsxl.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gzhubu.top/Article/details/gthjiefdml.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.fzhhl.top/Article/details/gthdrnvfpi.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.snrcjt.cn/Article/details/gtmsncrznc.html

[K04] 读取 JSON 文件
来源：http://dali.jinqigfzy.top/Article/details/gtmxhookmy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gaohongyu789.top/Article/details/gtgkpzrsfh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ybcxt.top/Article/details/gtuyxbwdny.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigfzy.top/Article/details/gtaidcwdvn.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.dashuyun.cn/Article/details/gtpwdogmxu.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jlsjyb.cn/Article/details/gtoljzeesv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.redwolf501.top/Article/details/gtgpiuzzwh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hnxiangtu.top/Article/details/gtsijvzvnz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.wangshuangyany.cn/Article/details/gtttypnguv.html

[K05] 深拷贝对象
来源：http://dali.chenlongwang.top/Article/details/gtncjsnudp.html

Py:   copy.deepcopy(obj)
来源：http://dali.shzxlz.cn/Article/details/gtjpduvixr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.daxiang520.top/Article/details/gtvrfmvfgu.html

JS:   structuredClone(obj)
来源：http://dali.gzhubu.top/Article/details/gtoptyezwv.html

TS:   structuredClone(obj)
来源：http://dali.birdmap.top/Article/details/gtmvtyzusj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcqfvvtcb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.daxiang520.top/Article/details/gtcpkshexx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.smart0.xyz/Article/details/gtedjftdvb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yj20258.top/Article/details/gtmxhgirzi.html

[K06] 解析 URL 查询串
来源：http://dali.9152youxi.cn/Article/details/gtidydciev.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xuanzx.com/Article/details/gtxryhrplg.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.0kj1m.cn/Article/details/gttowmarav.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgfzy.top/Article/details/gtxhvujtxf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gaohongyu789.top/Article/details/gtzehadtcl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cheryme.top/Article/details/gtopodqytd.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ydzc1.top/Article/details/gtzccpuhsc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gtyljazggv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj20258.top/Article/details/gthiecxrjk.html

[K07] 进制转换
来源：http://dali.wangshuangyany.cn/Article/details/gtvswqirep.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.316326.xyz/Article/details/gtgxllxvzj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.wangshuangyany.cn/Article/details/gttcnoxfub.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gtollvgmfl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gtospypxdd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gthdpdiisq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.tian-w.cn/Article/details/gtdvhwbzit.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.tianlin.xyz/Article/details/gtnewumcmb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gtcvwmsqlh.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hnxiangtu.top/Article/details/gtzsaeqmqz.html

Py:   pickle.dumps(obj)
来源：http://dali.hysaishi.cn/Article/details/gtjjekecjq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shzxlz.cn/Article/details/gtkpmbtnjo.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xuetiantiany.cn/Article/details/gtjyndwcof.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigufen.top/Article/details/gtyczarzsv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenjidiqi.icu/Article/details/gtsuiymrqf.html

Go:   encoding/gob
来源：http://dali.yj20258888.top/Article/details/gthcqgetxd.html

Ruby: Marshal.dump(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtusggdxbe.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jqgufenzy.top/Article/details/gtqmkmxzkw.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtniqfzxzq.html

L. 网络请求
来源：http://dali.ppjwa.cn/Article/details/gtrapcknyg.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtxyffrybq.html

[L01] 发送 GET 请求
来源：http://dali.pengpengdd.cyou/Article/details/gtutdvnzpk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.nanxinkj.top/Article/details/gtwbifazau.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinghuilouyu.cn/Article/details/gtkjlerwzb.html

JS:   await fetch(url)
来源：http://dali.zhixingplan.top/Article/details/gteebbjdsg.html

TS:   await fetch(url)
来源：http://dali.kuanghao11.cn/Article/details/gtdqnkuwez.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gaohongyu789.top/Article/details/gtjnpfslll.html

Go:   resp, err := http.Get(url)
来源：http://dali.mhx1999.top/Article/details/gtkdaztqga.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hnxiangtu.top/Article/details/gtzznkzodg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.dashuyun.cn/Article/details/gtfszsxdse.html

[L02] 发送 POST JSON
来源：http://dali.daria6918.cn/Article/details/gtigikzpxn.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.fengsongda.top/Article/details/gttjqbwrth.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.feifeiyinyue.top/Article/details/gtvdzleeqp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xylfe.cn/Article/details/gtxybphpji.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tian-w.cn/Article/details/gtglqicqdg.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.dianchejie.cn/Article/details/gtbdhqoohb.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.havefunace.top/Article/details/gtbgqzsxjw.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sufxvd.cn/Article/details/gtrvsmnway.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.dianchejie.cn/Article/details/gtntvfefjn.html

[L03] 设置自定义请求头
来源：http://dali.zdqjudy.top/Article/details/gtpdfjpocc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.haohaochexian.top/Article/details/gtdybojums.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.quarkkingdee.top/Article/details/gtaanqaeun.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jqgufenzy.top/Article/details/gtmdgqebau.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.havefunace.top/Article/details/gtguwdclct.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hammf.cn/Article/details/gtgtdaxeox.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.bjfxy.top/Article/details/gtqegfvcoq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.daria6918.cn/Article/details/gtsktwtvjj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jqgfzy.top/Article/details/gtrbmtiexl.html

[L04] 设置超时
来源：http://dali.zhixingplan.top/Article/details/gtizittsgo.html

Py:   requests.get(url, timeout=5)
来源：http://dali.vqdsnc.cn/Article/details/gtzwibenao.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.birdmap.top/Article/details/gtvpsvnuwu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gotoacloud.top/Article/details/gttlzzrbup.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.kuanghao11.cn/Article/details/gtxvhpsisr.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shangyingyoupin.top/Article/details/gtuzibryzy.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.aibaodan.cn/Article/details/gtdsmozput.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sxryk.cn/Article/details/gtbbrgnrdd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yonumen.top/Article/details/gtbrkzsdvx.html

[L05] 上传文件（multipart）
来源：http://dali.zhongyouzk.top/Article/details/gtomputqpa.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.vqdsnc.cn/Article/details/gtijajogxy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xylfe.cn/Article/details/gtdtxdgqzw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258888.top/Article/details/gtdzfbtkwr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.quarkkingdee.top/Article/details/gtsqkzzysg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jianghu66.top/Article/details/gtzidbywtc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zycfv.cn/Article/details/gtmudxdnwl.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gogol.net.cn/Article/details/gtslqvvxxx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtnxpslach.html

[L06] 解析响应为 JSON
来源：http://dali.mhx1999.top/Article/details/gtswspxjji.html

Py:   resp.json()
来源：http://dali.yanxiufei.cn/Article/details/gtkxdcbens.html

PHP:  json_decode($body, true);
来源：http://dali.tanke756.top/Article/details/gtkhqourwn.html

JS:   await resp.json()
来源：http://dali.iojbl.cn/Article/details/gtcsddjoyd.html

TS:   await resp.json()
来源：http://dali.jyoumei.cn/Article/details/gtzgrmvhon.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yuanzhike.top/Article/details/gtzzttokah.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hnqzz.top/Article/details/gtptsxaepu.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jqgufenzy.top/Article/details/gtjklxgava.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gotoacloud.top/Article/details/gtwzocsekx.html

[L07] 处理 HTTP 状态码
来源：http://dali.vqdsnc.cn/Article/details/gtmsjryotl.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hongshengwenyu.top/Article/details/gtbwzbhydr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.9152youxi.cn/Article/details/gtbcdoufoh.html

JS:   resp.ok;  resp.status
来源：http://dali.birdmap.top/Article/details/gtwttzoqaq.html

TS:   resp.ok;  resp.status
来源：http://dali.yanxiufei.cn/Article/details/gthbnrysvg.html

Java: resp.statusCode()
来源：http://dali.yueranfly.top/Article/details/gtttotdrae.html

Go:   resp.StatusCode
来源：http://dali.gaohongyu789.top/Article/details/gtpmjzseeu.html

Ruby: resp.code.to_i
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxzcslhlv.html

C#:   (int)resp.StatusCode
来源：http://dali.shangyingyoupin.top/Article/details/gtbpjywuxs.html

[L08] 并发请求多个地址
来源：http://dali.havefunace.top/Article/details/gtjcrbqdpr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zdqjudy.top/Article/details/gtgvxcuihk.html

PHP:  curl_multi_init() 系列
来源：http://dali.yangfankeji.com/Article/details/gtrskibilk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.mhx1999.top/Article/details/gtmcprffgr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenzaomai.com/Article/details/gtopxcebfq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jyoumei.cn/Article/details/gtwosnhtpd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.chenzaomai.com/Article/details/gtsvbemxnz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yuxming.cn/Article/details/gtcpvkqcxk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gotoacloud.top/Article/details/gtchygzuhq.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtdweojbsj.html

M. 命令行 / 进程 / 环境
来源：http://dali.meibo888.top/Article/details/gtedtwjnfo.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtzaoologf.html

[M01] 读取命令行参数
来源：http://dali.zycfv.cn/Article/details/gtwhpffzcu.html

Py:   sys.argv[1:]
来源：http://dali.hongshengwenyu.top/Article/details/gtpouyjluy.html

PHP:  $argv;  $argc;
来源：http://dali.ehwqpu.com/Article/details/gtqnqonfbq.html

JS:   process.argv.slice(2)
来源：http://dali.quarkkingdee.top/Article/details/gtqykzwmdj.html

TS:   process.argv.slice(2)
来源：http://dali.jinqigfzy.top/Article/details/gttdifwjwn.html

Java: args 数组（main 方法参数）
来源：http://dali.tanke756.top/Article/details/gtgbxmlwoa.html

Go:   os.Args[1:]
来源：http://dali.hnqzz.top/Article/details/gtqxoqykxk.html

Ruby: ARGV
来源：http://dali.jinghuilouyu.cn/Article/details/gtadjptbbg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjbugqyfm.html

[M02] 读取环境变量
来源：http://dali.gogol.net.cn/Article/details/gtnxaltesf.html

Py:   os.environ.get("HOME")
来源：http://dali.gzhubu.top/Article/details/gttieyugve.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xylfe.cn/Article/details/gtgibsmflv.html

JS:   process.env.HOME
来源：http://dali.yonumen.top/Article/details/gtltaxwerv.html

TS:   process.env.HOME
来源：http://dali.bjfxy.top/Article/details/gtaggrndmq.html

Java: System.getenv("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtfegmasyj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gtfjyccylp.html

Ruby: ENV["HOME"]
来源：http://dali.ppjwa.cn/Article/details/gtdxtlgbny.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ydzc1.top/Article/details/gtncuqzkiq.html

[M03] 执行外部命令
来源：http://dali.xylfe.cn/Article/details/gtlkupafql.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.chenzaomai.com/Article/details/gtpbhpnjxn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yuxming.cn/Article/details/gtizaffndc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.feifeiyinyue.top/Article/details/gtcfqubasw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhongyouzk.top/Article/details/gtpdvdjwzy.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ybcxt.top/Article/details/gthpbdmuuf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cucudq.cn/Article/details/gtjxbjzvcd.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cqqwz.cn/Article/details/gtuchftvou.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cheryme.top/Article/details/gtqqkxygaw.html

[M04] 获取当前工作目录
来源：http://dali.yanxiufei.cn/Article/details/gtiogyvkba.html

Py:   os.getcwd()
来源：http://dali.yongpay.top/Article/details/gtvqxcyuhv.html

PHP:  getcwd();
来源：http://dali.zdqjudy.top/Article/details/gtvcstwyuj.html

JS:   process.cwd()
来源：http://dali.jqgfzy.top/Article/details/gtlbpfpvsl.html

TS:   process.cwd()
来源：http://dali.cucudq.cn/Article/details/gtehljjjtj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yonumen.top/Article/details/gtmuecsofn.html

Go:   os.Getwd()
来源：http://dali.ydzc1.top/Article/details/gtmmabeozp.html

Ruby: Dir.pwd
来源：http://dali.hfpthk.cn/Article/details/gtbyjcyvoa.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.chenlongwang.top/Article/details/gtchpntxld.html

[M05] 设置退出码
来源：http://dali.jlsjyb.cn/Article/details/gtplclymil.html

Py:   sys.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gttdtvvnhb.html

PHP:  exit(1);
来源：http://dali.zhixingplan.top/Article/details/gtbubefmbw.html

JS:   process.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtfeofljix.html

TS:   process.exit(1)
来源：http://dali.ybcxt.top/Article/details/gtsjqxrftk.html

Java: System.exit(1)
来源：http://dali.xuanzx.com/Article/details/gtkgrnvggr.html

Go:   os.Exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gtowicaodr.html

Ruby: exit 1
来源：http://dali.cqqwz.cn/Article/details/gtsuexvpnm.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinghuilouyu.cn/Article/details/gtdhozcuej.html

[M06] 向标准错误输出
来源：http://dali.yongpay.top/Article/details/gtgbshzila.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yvedp.cn/Article/details/gtvdxefklu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.daria6918.cn/Article/details/gtqfdnuzsr.html

JS:   console.error("err")
来源：http://dali.cucudq.cn/Article/details/gtwdespzei.html

TS:   console.error("err")
来源：http://dali.ivvv.top/Article/details/gtmhqpudfx.html

Java: System.err.println("err")
来源：http://dali.hfpthk.cn/Article/details/gtbhfdoafb.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.tian-w.cn/Article/details/gtyhoqceoj.html

Ruby: warn "err"
来源：http://dali.ydzc1.top/Article/details/gtukfbgiro.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zdqjudy.top/Article/details/gtxtdeifyt.html

[M07] 判断是否为主入口
来源：http://dali.xuanzx.com/Article/details/gtpjouibql.html

Py:   if __name__ == "__main__":
来源：http://dali.gogol.net.cn/Article/details/gtaoqdjcpo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhoulong.xyz/Article/details/gtfevwbumu.html

JS:   require.main === module
来源：http://dali.guannengcc.top/Article/details/gtmfbrwxem.html

TS:   require.main === module
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvzrepwot.html

Java: public static void main(String[] args)
来源：http://dali.jiagoushi.top/Article/details/gteewnvefl.html

Go:   func main()
来源：http://dali.jinqigfzy.top/Article/details/gtcphkbslm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yvedp.cn/Article/details/gtcxfcmqhq.html

C#:   static void Main(string[] args)
来源：http://dali.jyoumei.cn/Article/details/gtzxzabble.html

[M08] 获取系统与运行时信息
来源：http://dali.jianghu66.top/Article/details/gtxucjront.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xuanzx.com/Article/details/gtwyerdhrg.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yuxming.cn/Article/details/gtftcqbesf.html

JS:   process.platform;  process.version
来源：http://dali.xziqi.cn/Article/details/gtuiupegpi.html

TS:   process.platform;  process.version
来源：http://dali.jianghu66.top/Article/details/gtouliujaw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yvedp.cn/Article/details/gtpcddmslw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ydzc1.top/Article/details/gtkdqiifki.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.kuanghao11.cn/Article/details/gtbvhpygdi.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.redwolf501.top/Article/details/gtfiyuvufl.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtpkrnfdpo.html

N. 数据结构与算法
来源：http://dali.zhengqikj.top/Article/details/gtfrzsvefg.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtferrcgzt.html


<!-- 参考信息 -->