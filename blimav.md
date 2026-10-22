代发 wailian999

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.redwolf501.top/Article/details/gtyheyyowy.html

JS:   new Date();  Date.now()
来源：http://dali.tanke756.top/Article/details/gtdbswwert.html

TS:   new Date();  Date.now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtghfptnrx.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.bjfxy.top/Article/details/gtlbaulzng.html

Go:   time.Now()
来源：http://dali.hywenlv.cn/Article/details/gtjxebldwv.html

Ruby: Time.now
来源：http://dali.hysaishi.cn/Article/details/gtjkkqgirb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.daria6918.cn/Article/details/gthunjkowv.html

[J02] 格式化输出
来源：http://dali.zhengqikj.top/Article/details/gtgglmgvct.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.c1oappe.top/Article/details/gtrpevldsg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ybcxt.top/Article/details/gteymbrocw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhengqikj.top/Article/details/gtubbcjsjc.html

TS:   d.toISOString()
来源：http://dali.yj20258.top/Article/details/gtxbvfvcwc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nanxinkj.top/Article/details/gtwpwcepgp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.daria6918.cn/Article/details/gtljehmrss.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gtkzkssfhz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nwbrower.top/Article/details/gthbtqasmb.html

[J03] 字符串解析为日期
来源：http://dali.andypj.xyz/Article/details/gtjzughotx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.meibo888.top/Article/details/gtdrdzgojc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.wangshuangyany.cn/Article/details/gtotckctfq.html

JS:   new Date("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gtqolxshnx.html

TS:   new Date("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gtrafskoha.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gtvafhqftl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtsnxfixnh.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gtgwoiwksk.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hfpthk.cn/Article/details/gtgltjipho.html

[J04] 时间戳与日期互转
来源：http://dali.zhongyouzk.top/Article/details/gtghljswst.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sufxvd.cn/Article/details/gtyqvrmhtk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hammf.cn/Article/details/gtwmqkjayj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yongpay.top/Article/details/gtjglzvwbj.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gaohongyu789.top/Article/details/gtugueibcn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hnxiangtu.top/Article/details/gtqjwqgxby.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.aizwys.cn/Article/details/gtjpmnswyc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.9152youxi.cn/Article/details/gtbenxumqc.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxenqsldl.html

[J05] 时间加减（加 7 天）
来源：http://dali.sxryk.cn/Article/details/gthzinlwes.html

Py:   now + timedelta(days=7)
来源：http://dali.gotoacloud.top/Article/details/gtcjmjpruw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ivvv.top/Article/details/gttfokkrbl.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.vqdsnc.cn/Article/details/gtgelioqwm.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.bjfxy.top/Article/details/gtsaipyqqx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.pycfn.com/Article/details/gtfoigjpns.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.havefunace.top/Article/details/gtailholla.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yuxming.cn/Article/details/gttggwojwy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jianghu66.top/Article/details/gtirnjlbeq.html

[J06] 计算两时间之差
来源：http://dali.nwbrower.top/Article/details/gthhmmbggs.html

Py:   (end - start).total_seconds()
来源：http://dali.smart0.xyz/Article/details/gtdfckulde.html

PHP:  $end->diff($start)->days;
来源：http://dali.xuetiantiany.cn/Article/details/gtqilwlnub.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.fzhhl.top/Article/details/gtenntotwh.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hfpthk.cn/Article/details/gttfecdgqy.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xinyue.icu/Article/details/gtiglckhyi.html

Go:   end.Sub(start).Hours()
来源：http://dali.yongpay.top/Article/details/gtxsivspqx.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hfpthk.cn/Article/details/gtyikvqaar.html

C#:   (end - start).TotalSeconds
来源：http://dali.wangdashe.top/Article/details/gtfbkqvaqo.html

[J07] 比较两个日期
来源：http://dali.hammf.cn/Article/details/gtkvfitfbk.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xylfe.cn/Article/details/gtjmzaowqz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.guannengcc.top/Article/details/gtegegobek.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.9152youxi.cn/Article/details/gtpokfpnku.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xziqi.cn/Article/details/gtqzhxvbpu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.tianlin.xyz/Article/details/gtzpcvgswq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shzxlz.cn/Article/details/gtlrjurrxr.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.tianlin.xyz/Article/details/gtebtptvfw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.pycfn.com/Article/details/gtjfhntvwz.html

[J08] 提取年月日与星期
来源：http://dali.hysaishi.cn/Article/details/gtsiqycgrf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.andypj.xyz/Article/details/gtczjcomct.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.meibo888.top/Article/details/gtnldquqtz.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.fengsongda.top/Article/details/gtwynenjse.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ehwqpu.com/Article/details/gtmcnuybrm.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhoulong.xyz/Article/details/gtamvmbyco.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sxryk.cn/Article/details/gtltenqoce.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjwragohh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sufxvd.cn/Article/details/gtjyfxyzxq.html

[J09] 时区处理
来源：http://dali.yanxiufei.cn/Article/details/gtscjkfixe.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.316326.xyz/Article/details/gtavesrfer.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.nwbrower.top/Article/details/gtvtlukpfb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yvedp.cn/Article/details/gtebyyouwf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jlsjyb.cn/Article/details/gtigmjmfhh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yuxming.cn/Article/details/gtokrgekwu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj202588.top/Article/details/gtpmlzmswc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ydzc1.top/Article/details/gtfrqgbdxj.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.316326.xyz/Article/details/gtmvomfkdu.html

[J10] 取今天 / 本月第一天
来源：http://dali.tanke756.top/Article/details/gtewtzrdoe.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhongyouzk.top/Article/details/gtwbicxvtx.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cqqwz.cn/Article/details/gtkxaoyxpq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hongshengwenyu.top/Article/details/gthpuuzvlz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.c1oappe.top/Article/details/gthepsighn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.snrcjt.cn/Article/details/gtqnprqzxx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfmwftkfy.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.kuanghao11.cn/Article/details/gtglprvyxj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gogol.net.cn/Article/details/gtkblyoupx.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtztvahytm.html

K. JSON 与序列化
来源：http://dali.cucudq.cn/Article/details/gtqskiowwp.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtrslqyqlc.html

[K01] 对象转 JSON 字符串
来源：http://dali.birdmap.top/Article/details/gtmohpyidv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jianghu66.top/Article/details/gtwaeicwzn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zycfv.cn/Article/details/gtgnixudyd.html

JS:   JSON.stringify(obj)
来源：http://dali.smart0.xyz/Article/details/gtusrblyum.html

TS:   JSON.stringify(obj)
来源：http://dali.cdnleiting.top/Article/details/gtyxamqlkf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yj20258888.top/Article/details/gtmmdlqfnb.html

Go:   json.Marshal(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfhsjdquo.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.snrcjt.cn/Article/details/gtwxhxyril.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.aizwys.cn/Article/details/gtwiuqnpkk.html

[K02] JSON 字符串转对象
来源：http://dali.aibaodan.cn/Article/details/gtxjkyrxpw.html

Py:   json.loads(s)
来源：http://dali.yuxming.cn/Article/details/gtfsvrdfjl.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhoulong.xyz/Article/details/gtmqvsvqjm.html

JS:   JSON.parse(s)
来源：http://dali.xziqi.cn/Article/details/gtnwtpfbzg.html

TS:   JSON.parse(s)
来源：http://dali.xinyue.icu/Article/details/gtxervurjk.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jyoumei.cn/Article/details/gtahmwanwu.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.aizwys.cn/Article/details/gtiumwgmhx.html

Ruby: JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gtgahgbemw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.redwolf501.top/Article/details/gtnftcevmb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.9152youxi.cn/Article/details/gtenwzxrin.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinqigufen.top/Article/details/gticrznwhd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yvedp.cn/Article/details/gtzttrwoud.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.daxiang520.top/Article/details/gtwicaeedw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuanzhike.top/Article/details/gtihtxltgg.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhixingplan.top/Article/details/gtsaapbyuo.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sweek.top/Article/details/gtfeculvuz.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.0kj1m.cn/Article/details/gtedcwyrkt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.haohaochexian.top/Article/details/gtkdsyldnb.html

[K04] 读取 JSON 文件
来源：http://dali.yongpay.top/Article/details/gtxfkjdhtk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tian-w.cn/Article/details/gtebmwpsak.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shuidangran.top/Article/details/gthyeqxmda.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtqutekhmw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ivvv.top/Article/details/gtmromoeru.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yj20258.top/Article/details/gthiwymlwi.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhixingplan.top/Article/details/gtmhavylss.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cdnleiting.top/Article/details/gtrnmpfezd.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cheryme.top/Article/details/gtyvyzfazu.html

[K05] 深拷贝对象
来源：http://dali.vqdsnc.cn/Article/details/gtrgeiaqpm.html

Py:   copy.deepcopy(obj)
来源：http://dali.yuxming.cn/Article/details/gtfhqnbhgv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.havefunace.top/Article/details/gtukgpmyum.html

JS:   structuredClone(obj)
来源：http://dali.chenlongwang.top/Article/details/gtkjsaqvtj.html

TS:   structuredClone(obj)
来源：http://dali.cdnleiting.top/Article/details/gtjwkadvkz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hammf.cn/Article/details/gtksmtudrh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.daxiang520.top/Article/details/gtzzpddxyo.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ydzc1.top/Article/details/gtegiwjuzo.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzbsrwuxx.html

[K06] 解析 URL 查询串
来源：http://dali.daria6918.cn/Article/details/gtrncsozrl.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.aibaodan.cn/Article/details/gtechhsqcv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgyacdsmg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jianghu66.top/Article/details/gtjitenkea.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jiagoushi.top/Article/details/gtorkocyhn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yj20258888.top/Article/details/gtgrdqntba.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gtdmelltvb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.feifeiyinyue.top/Article/details/gtjgisxbeg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hongshengwenyu.top/Article/details/gtcyepcpbf.html

[K07] 进制转换
来源：http://dali.bjfxy.top/Article/details/gtpokofyde.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtkkiwuysi.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cucudq.cn/Article/details/gtaepftrkh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gtcxubbtiq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtroczxrmj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gtdxtsomtd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.316326.xyz/Article/details/gtizlvjqlu.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hysaishi.cn/Article/details/gtinfowrkw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gtopscmjfv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yj202588.top/Article/details/gtjunseqil.html

Py:   pickle.dumps(obj)
来源：http://dali.tanke756.top/Article/details/gtuqzmsyrh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shzxlz.cn/Article/details/gtgbhwfale.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhengqikj.top/Article/details/gttjuidvlh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shzxlz.cn/Article/details/gtbliulbzr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yanxiufei.cn/Article/details/gtllqyagbo.html

Go:   encoding/gob
来源：http://dali.316326.xyz/Article/details/gtismcwwor.html

Ruby: Marshal.dump(obj)
来源：http://dali.yvedp.cn/Article/details/gtaavyprgj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.smart0.xyz/Article/details/gtffoxosnh.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtlrpogsou.html

L. 网络请求
来源：http://dali.shanyushiyangtech.top/Article/details/gtdoiupmnj.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtzlauajni.html

[L01] 发送 GET 请求
来源：http://dali.daxiang520.top/Article/details/gtotabrjgi.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jyoumei.cn/Article/details/gteebznmej.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.tanke756.top/Article/details/gtmolidckt.html

JS:   await fetch(url)
来源：http://dali.hysaishi.cn/Article/details/gtlzsmbjfl.html

TS:   await fetch(url)
来源：http://dali.hfpthk.cn/Article/details/gtvbjnysxl.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hnxiangtu.top/Article/details/gtbfckgmem.html

Go:   resp, err := http.Get(url)
来源：http://dali.nanxinkj.top/Article/details/gttphspdrw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jiagoushi.top/Article/details/gtlfuhgmfj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.fengsongda.top/Article/details/gtknqthrei.html

[L02] 发送 POST JSON
来源：http://dali.iojbl.cn/Article/details/gtrjsgllly.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjbiekbus.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhengqikj.top/Article/details/gtsvpdosyn.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcogiyjas.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhoulong.xyz/Article/details/gtvqglkgjp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.316326.xyz/Article/details/gtaxxugowf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.fengsongda.top/Article/details/gtqoayttoc.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.guannengcc.top/Article/details/gtpfteepud.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.haohaochexian.top/Article/details/gtxopwjzws.html

[L03] 设置自定义请求头
来源：http://dali.hammf.cn/Article/details/gtknrhzitu.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shangyingyoupin.top/Article/details/gtzfiixbtm.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zycfv.cn/Article/details/gtsxrxlhni.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhoulong.xyz/Article/details/gtkuvkupuu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shzxlz.cn/Article/details/gtutfuozoe.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yj202588.top/Article/details/gtqlouoneq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yonumen.top/Article/details/gtyagzndax.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.tianlin.xyz/Article/details/gtjeqpheoa.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shuidangran.top/Article/details/gtsygmcqhn.html

[L04] 设置超时
来源：http://dali.tian-w.cn/Article/details/gtylowrhtb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbuaxlcvh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.dashuyun.cn/Article/details/gtxochozoo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shuidangran.top/Article/details/gtvyyjcgdc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gtxvbytqdm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sufxvd.cn/Article/details/gtaejnjvyw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.daria6918.cn/Article/details/gtmqyvjmsc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinqigufen.top/Article/details/gtnxcyhdcw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ivvv.top/Article/details/gtktgqozqt.html

[L05] 上传文件（multipart）
来源：http://dali.gotoacloud.top/Article/details/gtldivindp.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.aibaodan.cn/Article/details/gtbpbqvynp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinqigufen.top/Article/details/gtwuackzdn.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.daxiang520.top/Article/details/gtwscwtkvn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gaohongyu789.top/Article/details/gtvenkvplw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinqigfzy.top/Article/details/gtvkkjakam.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yj202588.top/Article/details/gtughpthia.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgjqilqpc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtffasahrl.html

[L06] 解析响应为 JSON
来源：http://dali.sxryk.cn/Article/details/gtqilwifjp.html

Py:   resp.json()
来源：http://dali.svipenyu.cn/Article/details/gtwdxbotjd.html

PHP:  json_decode($body, true);
来源：http://dali.yj202588.top/Article/details/gtbatlctfz.html

JS:   await resp.json()
来源：http://dali.guowangkeji.top/Article/details/gtgksmbfbn.html

TS:   await resp.json()
来源：http://dali.316326.xyz/Article/details/gtrfpplfhu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hnqzz.top/Article/details/gtxrqgobqr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shanyushiyangtech.top/Article/details/gtixoxcuoo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.dashuyun.cn/Article/details/gtdmtqhhjc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nanxuanxn.top/Article/details/gtgzdkhmid.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhengqikj.top/Article/details/gtrbsqrfbx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jyoumei.cn/Article/details/gtgxhaxhzn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zdqjudy.top/Article/details/gthbyfugva.html

JS:   resp.ok;  resp.status
来源：http://dali.hongshengwenyu.top/Article/details/gtscuwmusx.html

TS:   resp.ok;  resp.status
来源：http://dali.bjfxy.top/Article/details/gtvzwqefyi.html

Java: resp.statusCode()
来源：http://dali.shzxlz.cn/Article/details/gtuhqvkavn.html

Go:   resp.StatusCode
来源：http://dali.kuanghao11.cn/Article/details/gtdymzqans.html

Ruby: resp.code.to_i
来源：http://dali.zhiwuduotai.top/Article/details/gttavhnjpk.html

C#:   (int)resp.StatusCode
来源：http://dali.gaohongyu789.top/Article/details/gtwadadhwn.html

[L08] 并发请求多个地址
来源：http://dali.iojbl.cn/Article/details/gtierosjil.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.chenzaomai.com/Article/details/gtbbqfnxln.html

PHP:  curl_multi_init() 系列
来源：http://dali.cashguo.top/Article/details/gttlelysbm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gzhubu.top/Article/details/gtuumytvsc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangdashe.top/Article/details/gtgcisbdge.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yonumen.top/Article/details/gtgvturlka.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sweek.top/Article/details/gtqkvsdajq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.meibo888.top/Article/details/gtovxtsivf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yj202588.top/Article/details/gtadxfeltw.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtvgpahxuv.html

M. 命令行 / 进程 / 环境
来源：http://dali.haohaochexian.top/Article/details/gtafufwuop.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtvzmtwbiy.html

[M01] 读取命令行参数
来源：http://dali.hnxiangtu.top/Article/details/gtxfzjrgbu.html

Py:   sys.argv[1:]
来源：http://dali.andypj.xyz/Article/details/gtblvjyyae.html

PHP:  $argv;  $argc;
来源：http://dali.hnxiangtu.top/Article/details/gtpsvnbjxc.html

JS:   process.argv.slice(2)
来源：http://dali.fengsongda.top/Article/details/gtfjksujap.html

TS:   process.argv.slice(2)
来源：http://dali.xziqi.cn/Article/details/gtkcfeyfej.html

Java: args 数组（main 方法参数）
来源：http://dali.gzhubu.top/Article/details/gtasfidriz.html

Go:   os.Args[1:]
来源：http://dali.dashuyun.cn/Article/details/gtlaygcqkw.html

Ruby: ARGV
来源：http://dali.yj20258.top/Article/details/gtrikgtwws.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhixingplan.top/Article/details/gtgqvuhoeo.html

[M02] 读取环境变量
来源：http://dali.dashuyun.cn/Article/details/gtvusligkf.html

Py:   os.environ.get("HOME")
来源：http://dali.gzhubu.top/Article/details/gtmhhvxnqh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.kuanghao11.cn/Article/details/gtakaztrlk.html

JS:   process.env.HOME
来源：http://dali.zycfv.cn/Article/details/gtcqwdrqmf.html

TS:   process.env.HOME
来源：http://dali.zdqjudy.top/Article/details/gtadiwdfax.html

Java: System.getenv("HOME")
来源：http://dali.hammf.cn/Article/details/gtnexjgzrm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ppjwa.cn/Article/details/gtvoouimup.html

Ruby: ENV["HOME"]
来源：http://dali.cqqwz.cn/Article/details/gtmzrrmtng.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.aibaodan.cn/Article/details/gtvpqugaeb.html

[M03] 执行外部命令
来源：http://dali.iojbl.cn/Article/details/gtsigddsoe.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.haohaochexian.top/Article/details/gtcdaaodah.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.svipenyu.cn/Article/details/gtvtpsxkfc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jiagoushi.top/Article/details/gttriorguu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenlongwang.top/Article/details/gtpvlvyhfj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.svipenyu.cn/Article/details/gtekkzbonl.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yonumen.top/Article/details/gtehqrnzkb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shanyushiyangkeji.top/Article/details/gtexvhdpiz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gotoacloud.top/Article/details/gtksaiyszw.html

[M04] 获取当前工作目录
来源：http://dali.sysykeji.top/Article/details/gtcdsgbtdc.html

Py:   os.getcwd()
来源：http://dali.jlsjyb.cn/Article/details/gtdxvmodgq.html

PHP:  getcwd();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgfibqpbx.html

JS:   process.cwd()
来源：http://dali.iojbl.cn/Article/details/gtspbjqfjm.html

TS:   process.cwd()
来源：http://dali.tianlin.xyz/Article/details/gtfpjzgslp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cheryme.top/Article/details/gtgjylgnvd.html

Go:   os.Getwd()
来源：http://dali.chenzaomai.com/Article/details/gtjbyfbizv.html

Ruby: Dir.pwd
来源：http://dali.cheryme.top/Article/details/gtiydowjdn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.chenjidiqi.icu/Article/details/gtwsjedpxb.html

[M05] 设置退出码
来源：http://dali.daria6918.cn/Article/details/gtsrkydtxx.html

Py:   sys.exit(1)
来源：http://dali.yueranfly.top/Article/details/gtxeofutwe.html

PHP:  exit(1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfkbdsuwa.html

JS:   process.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gtuampysnn.html

TS:   process.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gtzbtcridr.html

Java: System.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtyoqtctrs.html

Go:   os.Exit(1)
来源：http://dali.yj202588.top/Article/details/gtkgtzufzn.html

Ruby: exit 1
来源：http://dali.yj202588.top/Article/details/gtnbvlvmoa.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xuanzx.com/Article/details/gtgvwtsljx.html

[M06] 向标准错误输出
来源：http://dali.zhixingplan.top/Article/details/gtbrfcnygn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shzxlz.cn/Article/details/gtuwlpcxda.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.wangshuangyany.cn/Article/details/gtegewbxlj.html

JS:   console.error("err")
来源：http://dali.ybcxt.top/Article/details/gtdklmkjsj.html

TS:   console.error("err")
来源：http://dali.hnxiangtu.top/Article/details/gtmnstslvm.html

Java: System.err.println("err")
来源：http://dali.hnxiangtu.top/Article/details/gtajysrtja.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.bjfxy.top/Article/details/gtvshrmfrt.html

Ruby: warn "err"
来源：http://dali.dianchejie.cn/Article/details/gtijrdmvce.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hysaishi.cn/Article/details/gtzrcbakim.html

[M07] 判断是否为主入口
来源：http://dali.iojbl.cn/Article/details/gtadzisdoz.html

Py:   if __name__ == "__main__":
来源：http://dali.tianlin.xyz/Article/details/gtrbnpubsk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hnxiangtu.top/Article/details/gtjxumfusx.html

JS:   require.main === module
来源：http://dali.0kj1m.cn/Article/details/gtrzqxbgej.html

TS:   require.main === module
来源：http://dali.jlsjyb.cn/Article/details/gtyfjuyyby.html


<!-- 参考信息 -->