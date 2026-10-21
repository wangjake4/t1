代发 wailian999

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.feifeiyinyue.top/Article/details/gtgpmqbbkk.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jqgufenzy.top/Article/details/gtqkvvvvgx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.meibo888.top/Article/details/gtqxhykvry.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gogol.net.cn/Article/details/gtzjcmaxea.html

[J03] 字符串解析为日期
来源：http://dali.quarkkingdee.top/Article/details/gtrkgapytp.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.smart0.xyz/Article/details/gthgiuzbbr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hammf.cn/Article/details/gtrfydmbks.html

JS:   new Date("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gtzdxurpuq.html

TS:   new Date("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gttpkftdwm.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtnrlyvpex.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gtlvvglxrv.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gtvmfnqeyh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.guowangkeji.top/Article/details/gttgmsjlvj.html

[J04] 时间戳与日期互转
来源：http://dali.yangfankeji.com/Article/details/gtphrkmhzt.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinqigufen.top/Article/details/gtxwgbkjmv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.smart0.xyz/Article/details/gtdsxyaiyk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.tian-w.cn/Article/details/gtebtoqcsg.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sweek.top/Article/details/gtxbaratge.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhixingplan.top/Article/details/gtnscqaxwm.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.havefunace.top/Article/details/gtzvidmbyi.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.nanxuanxn.top/Article/details/gtwclifuhd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhengqikj.top/Article/details/gtaecjpwyu.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtflhyjlay.html

Py:   now + timedelta(days=7)
来源：http://dali.pengpengdd.cyou/Article/details/gtzkbcjvqj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shuidangran.top/Article/details/gtlgbwonxg.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yongpay.top/Article/details/gtzbwfvekn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jiagoushi.top/Article/details/gtsrigaqno.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yanxiufei.cn/Article/details/gtqgcadzpk.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yuxming.cn/Article/details/gtnuisqoaa.html

Ruby: Time.now + 7 * 86400
来源：http://dali.wangshuangyany.cn/Article/details/gtcufblorw.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ybcxt.top/Article/details/gttqzzhilh.html

[J06] 计算两时间之差
来源：http://dali.sysykeji.top/Article/details/gtocbqzhor.html

Py:   (end - start).total_seconds()
来源：http://dali.ybcxt.top/Article/details/gteqssrhtk.html

PHP:  $end->diff($start)->days;
来源：http://dali.yueranfly.top/Article/details/gtzpwkipew.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.316326.xyz/Article/details/gtunrjelcc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.guannengcc.top/Article/details/gtxweihjza.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbekklzxa.html

Go:   end.Sub(start).Hours()
来源：http://dali.sysykeji.top/Article/details/gtfusghkyy.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hysaishi.cn/Article/details/gteiuiodgc.html

C#:   (end - start).TotalSeconds
来源：http://dali.jlsjyb.cn/Article/details/gtfsvetftm.html

[J07] 比较两个日期
来源：http://dali.xinyue.icu/Article/details/gtgybdbncf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yuanzhike.top/Article/details/gtnjzyrhtr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gaohongyu789.top/Article/details/gtnccxjsed.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cdnleiting.top/Article/details/gttbqrdtds.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.gzhubu.top/Article/details/gtuakkojdp.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.daxiang520.top/Article/details/gtdpxhqcom.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdxsnywwa.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gtitaercuj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xziqi.cn/Article/details/gtpfqpfbht.html

[J08] 提取年月日与星期
来源：http://dali.316326.xyz/Article/details/gtvregppvm.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqnpblabg.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jianghu66.top/Article/details/gtvblpxnxo.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sufxvd.cn/Article/details/gtfdbcrgew.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.smart0.xyz/Article/details/gtognwejge.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.9152youxi.cn/Article/details/gtgiptkzfx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yj20258.top/Article/details/gtgtyqfgwx.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.c1oappe.top/Article/details/gtdvsffigu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sysykeji.top/Article/details/gtbpqieekk.html

[J09] 时区处理
来源：http://dali.sysykeji.top/Article/details/gtgfjvuzya.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.meibo888.top/Article/details/gttrevfgzt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xuanzx.com/Article/details/gtgiygmcwr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.0kj1m.cn/Article/details/gtlgveoznc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigufen.top/Article/details/gtcwvhmkjc.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ybcxt.top/Article/details/gtvvmsfszr.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.aibaodan.cn/Article/details/gtryshaarr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.aibaodan.cn/Article/details/gttztnqzih.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.aibaodan.cn/Article/details/gtanpbhhvd.html

[J10] 取今天 / 本月第一天
来源：http://dali.nwbrower.top/Article/details/gtmsghalfm.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yj202588.top/Article/details/gtdxlbodkj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ppjwa.cn/Article/details/gtchanrfwi.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hysaishi.cn/Article/details/gtwzhyhvqx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sxryk.cn/Article/details/gtohfpzelt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sufxvd.cn/Article/details/gtnxfyxlsy.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.andypj.xyz/Article/details/gtxmstulnf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinghuilouyu.cn/Article/details/gtolsjhfal.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhoulong.xyz/Article/details/gtgforgqtq.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtkeljgfnp.html

K. JSON 与序列化
来源：http://dali.svipenyu.cn/Article/details/gtmaxhcqbb.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtompyhtog.html

[K01] 对象转 JSON 字符串
来源：http://dali.gaohongyu789.top/Article/details/gtfafqtdur.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yuanzhike.top/Article/details/gtxlqnsexq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.chenzaomai.com/Article/details/gtyxvbvaek.html

JS:   JSON.stringify(obj)
来源：http://dali.hysaishi.cn/Article/details/gttjpgvyaz.html

TS:   JSON.stringify(obj)
来源：http://dali.gogol.net.cn/Article/details/gtwvbtpomq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hnxiangtu.top/Article/details/gtknnujnlc.html

Go:   json.Marshal(obj)
来源：http://dali.mhx1999.top/Article/details/gtpkjnkqcv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yuxming.cn/Article/details/gtjifdmwuh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jianghu66.top/Article/details/gtjruezipp.html

[K02] JSON 字符串转对象
来源：http://dali.chenjidiqi.icu/Article/details/gtscsudecm.html

Py:   json.loads(s)
来源：http://dali.havefunace.top/Article/details/gtvkazucix.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xylfe.cn/Article/details/gtgsrtekak.html

JS:   JSON.parse(s)
来源：http://dali.quarkkingdee.top/Article/details/gtonsrbwct.html

TS:   JSON.parse(s)
来源：http://dali.jianghu66.top/Article/details/gtafiwoagr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yanxiufei.cn/Article/details/gtnaympdos.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.dashuyun.cn/Article/details/gtnzkfoatx.html

Ruby: JSON.parse(s)
来源：http://dali.tanke756.top/Article/details/gtpsbxnxis.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zdqjudy.top/Article/details/gtwnxlmhyu.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnrrpvoat.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jqgufenzy.top/Article/details/gtvhzopubi.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jiagoushi.top/Article/details/gttkvnerra.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gaohongyu789.top/Article/details/gtguddkkdx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hysaishi.cn/Article/details/gtwtaazcgw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ehwqpu.com/Article/details/gtbqggepuv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ydzc1.top/Article/details/gtonbjelxi.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtpzlvlniv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.redwolf501.top/Article/details/gtkieojcdv.html

[K04] 读取 JSON 文件
来源：http://dali.wangshuangyany.cn/Article/details/gtzafbkzdr.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.birdmap.top/Article/details/gtrjybpgov.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.c1oappe.top/Article/details/gtaoiqqmce.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ehwqpu.com/Article/details/gtvnkggtce.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shangyingyoupin.top/Article/details/gtiiaatmzv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hnxiangtu.top/Article/details/gtoempuojf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yuxming.cn/Article/details/gtootgixxw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yueranfly.top/Article/details/gtyoorclff.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.aizwys.cn/Article/details/gttundzfwt.html

[K05] 深拷贝对象
来源：http://dali.wangshuangyany.cn/Article/details/gtdsoldsfp.html

Py:   copy.deepcopy(obj)
来源：http://dali.shzxlz.cn/Article/details/gtkuujypav.html

PHP:  unserialize(serialize($obj));
来源：http://dali.nwbrower.top/Article/details/gtcccjfsmd.html

JS:   structuredClone(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtjccgpjiz.html

TS:   structuredClone(obj)
来源：http://dali.hfpthk.cn/Article/details/gtfokgypac.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ppjwa.cn/Article/details/gtcphmcirs.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sufxvd.cn/Article/details/gtncbsjfuu.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.meibo888.top/Article/details/gtnwpvfqdd.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cqqwz.cn/Article/details/gtljadewfy.html

[K06] 解析 URL 查询串
来源：http://dali.dashuyun.cn/Article/details/gtnymbvzpe.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.aizwys.cn/Article/details/gtltenltoz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cqqwz.cn/Article/details/gtsndpwtal.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nwbrower.top/Article/details/gtdfcvwfmd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tianlin.xyz/Article/details/gtyqryepux.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jianghu66.top/Article/details/gtlgecjvvw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gtnpxjbrdg.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjevjckvy.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gtwrpudcwa.html

[K07] 进制转换
来源：http://dali.wangshuangyany.cn/Article/details/gtexephhzd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gtfgeukexg.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yuxming.cn/Article/details/gtsiiaskun.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gtpmrwgapn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gtwnbhdojw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjqxwxbqz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.pengpengdd.cyou/Article/details/gtmtnsfmud.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yuxming.cn/Article/details/gtepkaeqlf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gtypwetckw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhengqikj.top/Article/details/gtlrqolbde.html

Py:   pickle.dumps(obj)
来源：http://dali.tian-w.cn/Article/details/gthophduoo.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shuidangran.top/Article/details/gtevodbubs.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigfzy.top/Article/details/gtnqbrvody.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzrqkeqky.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.mhx1999.top/Article/details/gtmhppmsdh.html

Go:   encoding/gob
来源：http://dali.wangdashe.top/Article/details/gtefvpkxqy.html

Ruby: Marshal.dump(obj)
来源：http://dali.hywenlv.cn/Article/details/gtczctvfxh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.fzhhl.top/Article/details/gtzlyqdhvd.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtftqroetp.html

L. 网络请求
来源：http://dali.jinqigfzy.top/Article/details/gttmsmpboh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtrjdakyqv.html

[L01] 发送 GET 请求
来源：http://dali.xuetiantiany.cn/Article/details/gthmszoxho.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.mhx1999.top/Article/details/gtgtknymla.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nanxuanxn.top/Article/details/gtbqgkrdxy.html

JS:   await fetch(url)
来源：http://dali.shuidangran.top/Article/details/gtdtyjledk.html

TS:   await fetch(url)
来源：http://dali.yj20258888.top/Article/details/gtimllvqya.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ivvv.top/Article/details/gtatmvguqj.html

Go:   resp, err := http.Get(url)
来源：http://dali.xinyue.icu/Article/details/gtvchmxxob.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hysaishi.cn/Article/details/gtwlbvbkih.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jlsjyb.cn/Article/details/gtxefglsag.html

[L02] 发送 POST JSON
来源：http://dali.jqgufenzy.top/Article/details/gtiuharmsl.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.feifeiyinyue.top/Article/details/gtvwlcsgsl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.haohaochexian.top/Article/details/gtxcvbghqx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgufenzy.top/Article/details/gtnfauzcex.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gotoacloud.top/Article/details/gtwrcxhkgp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yueranfly.top/Article/details/gtudzwlegj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.c1oappe.top/Article/details/gtilnkyevq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.bjfxy.top/Article/details/gtcrrnkooa.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sweek.top/Article/details/gtymhirkih.html

[L03] 设置自定义请求头
来源：http://dali.chenlongwang.top/Article/details/gtlepwtmlr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yj202588.top/Article/details/gtdtrhzpfu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.guowangkeji.top/Article/details/gtbtnkwywi.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenzaomai.com/Article/details/gtymiiperv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daria6918.cn/Article/details/gtwmmnosmy.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.9152youxi.cn/Article/details/gtqwdpaqxk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sufxvd.cn/Article/details/gtrjxlazyp.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xylfe.cn/Article/details/gtiqmduvqi.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.smart0.xyz/Article/details/gtlqenydwg.html

[L04] 设置超时
来源：http://dali.yanxiufei.cn/Article/details/gtbvovcklq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.sweek.top/Article/details/gtmkkdvduf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinghuilouyu.cn/Article/details/gtujawydny.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkkrsotrx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigufen.top/Article/details/gtqbkfqfpq.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.dianchejie.cn/Article/details/gtkzrzowrd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cashguo.top/Article/details/gttxqlytgq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cdnleiting.top/Article/details/gtdsstuyrk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xinyue.icu/Article/details/gtzjnquozn.html

[L05] 上传文件（multipart）
来源：http://dali.yanxiufei.cn/Article/details/gtzoetzucx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.fzhhl.top/Article/details/gttjvoyvaa.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gaohongyu789.top/Article/details/gtybpsknzg.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.kuanghao11.cn/Article/details/gtpwygeryn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgufenzy.top/Article/details/gtaxcxwipv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.dashuyun.cn/Article/details/gttvruxcrr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.nanxuanxn.top/Article/details/gtocommmto.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jlsjyb.cn/Article/details/gtfapaihwv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.redwolf501.top/Article/details/gtcptzxgrj.html

[L06] 解析响应为 JSON
来源：http://dali.snrcjt.cn/Article/details/gtmqockwkj.html

Py:   resp.json()
来源：http://dali.zhixingplan.top/Article/details/gtggybwiaf.html

PHP:  json_decode($body, true);
来源：http://dali.yonumen.top/Article/details/gtrsizezod.html

JS:   await resp.json()
来源：http://dali.kuanghao11.cn/Article/details/gtmltwbptj.html

TS:   await resp.json()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtihhvdtlh.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj20258.top/Article/details/gtnyolorjl.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfnuzdexq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hnxiangtu.top/Article/details/gtjnruihxy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cheryme.top/Article/details/gtqhkooxuf.html

[L07] 处理 HTTP 状态码
来源：http://dali.9152youxi.cn/Article/details/gtetwsrlmo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.chenzaomai.com/Article/details/gtvipcgghp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhiwuduotai.top/Article/details/gtaaeiadgr.html

JS:   resp.ok;  resp.status
来源：http://dali.fengsongda.top/Article/details/gtfcedmluj.html

TS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjoqitbls.html

Java: resp.statusCode()
来源：http://dali.hfpthk.cn/Article/details/gtkuhqazex.html

Go:   resp.StatusCode
来源：http://dali.mhx1999.top/Article/details/gtpmedklhw.html

Ruby: resp.code.to_i
来源：http://dali.quarkkingdee.top/Article/details/gtubxfrqhk.html

C#:   (int)resp.StatusCode
来源：http://dali.jqgfzy.top/Article/details/gtesyeqkku.html

[L08] 并发请求多个地址
来源：http://dali.hnqzz.top/Article/details/gtubhkjrwq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xziqi.cn/Article/details/gtaodlcexv.html

PHP:  curl_multi_init() 系列
来源：http://dali.svipenyu.cn/Article/details/gttjbittxp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shuidangran.top/Article/details/gtmpejbetx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.c1oappe.top/Article/details/gttmcubpnd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jlsjyb.cn/Article/details/gtkjznhppd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinqigfzy.top/Article/details/gtjtzvojna.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.pengpengdd.cyou/Article/details/gtngrnurtl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.sysykeji.top/Article/details/gtyolbjzvx.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtzmfbvyhu.html

M. 命令行 / 进程 / 环境
来源：http://dali.cucudq.cn/Article/details/gtcfpbpiud.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmunoqxoq.html

[M01] 读取命令行参数
来源：http://dali.ivvv.top/Article/details/gtrcwlbibs.html

Py:   sys.argv[1:]
来源：http://dali.ivvv.top/Article/details/gtdidsdbfd.html

PHP:  $argv;  $argc;
来源：http://dali.wangdashe.top/Article/details/gtvfbzsvzm.html

JS:   process.argv.slice(2)
来源：http://dali.dianchejie.cn/Article/details/gtjunrdaeq.html

TS:   process.argv.slice(2)
来源：http://dali.mhx1999.top/Article/details/gtbkacrudu.html

Java: args 数组（main 方法参数）
来源：http://dali.cqqwz.cn/Article/details/gtbikfkvek.html

Go:   os.Args[1:]
来源：http://dali.chenzaomai.com/Article/details/gtbdzutzsv.html

Ruby: ARGV
来源：http://dali.hywenlv.cn/Article/details/gtoooxsfyb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sysykeji.top/Article/details/gtngrpuqgj.html

[M02] 读取环境变量
来源：http://dali.zhengqikj.top/Article/details/gtiacbqaas.html

Py:   os.environ.get("HOME")
来源：http://dali.fengsongda.top/Article/details/gtulbubocl.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj202588.top/Article/details/gtcwqduitz.html

JS:   process.env.HOME
来源：http://dali.quarkkingdee.top/Article/details/gtiilstgpf.html

TS:   process.env.HOME
来源：http://dali.redwolf501.top/Article/details/gttfhxbyjn.html

Java: System.getenv("HOME")
来源：http://dali.nwbrower.top/Article/details/gtcecesmvb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ybcxt.top/Article/details/gtayaaxhsc.html

Ruby: ENV["HOME"]
来源：http://dali.cdnleiting.top/Article/details/gtwatsqqdr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shuidangran.top/Article/details/gttirctjuk.html

[M03] 执行外部命令
来源：http://dali.hongshengwenyu.top/Article/details/gteecobjxr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xuetiantiany.cn/Article/details/gtpvnujmrt.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ivvv.top/Article/details/gtgjdmtdqr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.svipenyu.cn/Article/details/gtuwjsuovl.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.fengsongda.top/Article/details/gtzvexjovu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shanyushiyangtech.top/Article/details/gtjgkhaqkt.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tianlin.xyz/Article/details/gteqfoudpz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhoulong.xyz/Article/details/gtzhxhckoo.html

C#:   Process.Start("ls", "-l");
来源：http://dali.c1oappe.top/Article/details/gtolyfhhsk.html

[M04] 获取当前工作目录
来源：http://dali.ehwqpu.com/Article/details/gtzpwfyyto.html

Py:   os.getcwd()
来源：http://dali.fzhhl.top/Article/details/gtkuuceins.html

PHP:  getcwd();
来源：http://dali.tianlin.xyz/Article/details/gtvxpbycvu.html

JS:   process.cwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkflhncoh.html

TS:   process.cwd()
来源：http://dali.haohaochexian.top/Article/details/gtwfghmbqq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.wangdashe.top/Article/details/gtdfjysfnk.html

Go:   os.Getwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoljvdzzw.html

Ruby: Dir.pwd
来源：http://dali.dashuyun.cn/Article/details/gthcimovqw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ybcxt.top/Article/details/gtlrytnizn.html

[M05] 设置退出码
来源：http://dali.jinqigfzy.top/Article/details/gtznyjmvjf.html

Py:   sys.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gtvjvbymyg.html

PHP:  exit(1);
来源：http://dali.ivvv.top/Article/details/gtewdxikrm.html

JS:   process.exit(1)
来源：http://dali.yueranfly.top/Article/details/gtkulepyxp.html

TS:   process.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnsbquemt.html

Java: System.exit(1)
来源：http://dali.bjfxy.top/Article/details/gtdqvcdjiv.html

Go:   os.Exit(1)
来源：http://dali.yongpay.top/Article/details/gtomojpgbu.html

Ruby: exit 1
来源：http://dali.sweek.top/Article/details/gtoypwocot.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.chenjidiqi.icu/Article/details/gtzlfjpouq.html

[M06] 向标准错误输出
来源：http://dali.wangshuangyany.cn/Article/details/gtsnsswrtu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.guannengcc.top/Article/details/gthamxtjcj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xinyue.icu/Article/details/gtyfklkxwx.html

JS:   console.error("err")
来源：http://dali.yongpay.top/Article/details/gtevtjimxj.html

TS:   console.error("err")
来源：http://dali.sufxvd.cn/Article/details/gtjhsybnox.html

Java: System.err.println("err")
来源：http://dali.hongshengwenyu.top/Article/details/gtopkiwlme.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.iojbl.cn/Article/details/gtjwnpopxn.html

Ruby: warn "err"
来源：http://dali.nanxuanxn.top/Article/details/gtopqsfagy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.316326.xyz/Article/details/gtzhtfupqx.html

[M07] 判断是否为主入口
来源：http://dali.meibo888.top/Article/details/gttnvlqamn.html

Py:   if __name__ == "__main__":
来源：http://dali.nanxinkj.top/Article/details/gtbllwpvqr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gaohongyu789.top/Article/details/gtlbjnomsx.html

JS:   require.main === module
来源：http://dali.jyoumei.cn/Article/details/gtdpjdlroe.html

TS:   require.main === module
来源：http://dali.fengsongda.top/Article/details/gtglbeguso.html

Java: public static void main(String[] args)
来源：http://dali.jlsjyb.cn/Article/details/gtoaokibjj.html

Go:   func main()
来源：http://dali.gaohongyu789.top/Article/details/gtgtacxrcu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jyoumei.cn/Article/details/gtcicijxwf.html

C#:   static void Main(string[] args)
来源：http://dali.zhengqikj.top/Article/details/gtxouamudx.html

[M08] 获取系统与运行时信息
来源：http://dali.jlsjyb.cn/Article/details/gtzakexqso.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhixingplan.top/Article/details/gtkagctusq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.aizwys.cn/Article/details/gtkaiacptl.html

JS:   process.platform;  process.version
来源：http://dali.hywenlv.cn/Article/details/gthurnlpat.html

TS:   process.platform;  process.version
来源：http://dali.hfpthk.cn/Article/details/gtlolyntzr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gotoacloud.top/Article/details/gtymrewqsm.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.chenzaomai.com/Article/details/gtmzujpiab.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.aizwys.cn/Article/details/gtnjdbqkym.html


<!-- 参考信息 -->