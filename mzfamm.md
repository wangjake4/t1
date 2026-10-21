代发 wailian999

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tianlin.xyz/Article/details/gteiysghaj.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.nwbrower.top/Article/details/gtatkzvkib.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yangfankeji.com/Article/details/gtedkaabtz.html

TS:   d.toISOString()
来源：http://dali.yangfankeji.com/Article/details/gtzyhmdzit.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cucudq.cn/Article/details/gtvfpmdsah.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hywenlv.cn/Article/details/gtqdbtbuuo.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangtech.top/Article/details/gtyyokflfd.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sysykeji.top/Article/details/gtkjufkibb.html

[J03] 字符串解析为日期
来源：http://dali.yj20258888.top/Article/details/gtjvfjswnn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jianghu66.top/Article/details/gtxvebahxo.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj20258.top/Article/details/gtprxbhrtg.html

JS:   new Date("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gtuaylppuv.html

TS:   new Date("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtxtdctvjf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gttthlsovh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hammf.cn/Article/details/gtezddujzm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gthkatnuup.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.guowangkeji.top/Article/details/gtuguxhocp.html

[J04] 时间戳与日期互转
来源：http://dali.yonumen.top/Article/details/gtorjkxxdq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.tian-w.cn/Article/details/gtoszgptll.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.aibaodan.cn/Article/details/gtqzaqvnhi.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.dianchejie.cn/Article/details/gtlcamnnzh.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ydzc1.top/Article/details/gtjvkgnvth.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shangyingyoupin.top/Article/details/gtvwezsrvq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.dashuyun.cn/Article/details/gtoibisnxp.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yj202588.top/Article/details/gtgljbhflr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpcwujwgd.html

[J05] 时间加减（加 7 天）
来源：http://dali.sysykeji.top/Article/details/gtvuwpoptb.html

Py:   now + timedelta(days=7)
来源：http://dali.zhijiandao.cn/Article/details/gtflrurdzo.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jianghu66.top/Article/details/gtgocezhco.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ppjwa.cn/Article/details/gtqrkrqzeq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuanzx.com/Article/details/gtceatfkvd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.daxiang520.top/Article/details/gtfoldbmny.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ydzc1.top/Article/details/gtckooaxll.html

Ruby: Time.now + 7 * 86400
来源：http://dali.c1oappe.top/Article/details/gtbmeamzuc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zdqjudy.top/Article/details/gtginlsqte.html

[J06] 计算两时间之差
来源：http://dali.nwbrower.top/Article/details/gtaylbkcaj.html

Py:   (end - start).total_seconds()
来源：http://dali.316326.xyz/Article/details/gtxwbfmcou.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenzaomai.com/Article/details/gtanfvmoxe.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shuidangran.top/Article/details/gtsnqwjumb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xziqi.cn/Article/details/gtjlnjqnzu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yueranfly.top/Article/details/gtrhrtvbfi.html

Go:   end.Sub(start).Hours()
来源：http://dali.yueranfly.top/Article/details/gtonlzciyt.html

Ruby: end - start                 # 返回秒数
来源：http://dali.bjfxy.top/Article/details/gtfdnubcbh.html

C#:   (end - start).TotalSeconds
来源：http://dali.shangyingyoupin.top/Article/details/gtkwajjexb.html

[J07] 比较两个日期
来源：http://dali.hysaishi.cn/Article/details/gtwggzwixd.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yonumen.top/Article/details/gtxwrbqjrd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jlsjyb.cn/Article/details/gtktofibjc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.haohaochexian.top/Article/details/gtiotczagc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhongyouzk.top/Article/details/gtxyxrujmx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xuetiantiany.cn/Article/details/gtxhxpezqv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yuanzhike.top/Article/details/gtqdokykht.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yuxming.cn/Article/details/gtymtjaxak.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shangyingyoupin.top/Article/details/gtkeyzzfpe.html

[J08] 提取年月日与星期
来源：http://dali.snrcjt.cn/Article/details/gtvuomkbwh.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinqigufen.top/Article/details/gtlnpwrdgi.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.vqdsnc.cn/Article/details/gtxdbwerfe.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.aizwys.cn/Article/details/gtzwpunehv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yanxiufei.cn/Article/details/gtgucwyurf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinqigufen.top/Article/details/gtfxzootdk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hywenlv.cn/Article/details/gtkueyygyv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jyoumei.cn/Article/details/gttftaipfm.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xuanzx.com/Article/details/gtdkszropo.html

[J09] 时区处理
来源：http://dali.dashuyun.cn/Article/details/gtznkmeehc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hfpthk.cn/Article/details/gtxkklvwxq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.kuanghao11.cn/Article/details/gtsiobiywv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xziqi.cn/Article/details/gtyzoqaatw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.bjfxy.top/Article/details/gtcdexecvx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yongpay.top/Article/details/gtxloqnqbj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zdqjudy.top/Article/details/gtvcewqypz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.andypj.xyz/Article/details/gtglkaannv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yangfankeji.com/Article/details/gtnceartnt.html

[J10] 取今天 / 本月第一天
来源：http://dali.yanxiufei.cn/Article/details/gtyscsfpxn.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xuanzx.com/Article/details/gttnvfqsjc.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jqgfzy.top/Article/details/gtnqfeagzj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.9152youxi.cn/Article/details/gtjnvbjsnj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jyoumei.cn/Article/details/gthnlrknhj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yvedp.cn/Article/details/gtubfckhnf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.pengpengdd.cyou/Article/details/gtyzqbvnko.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xinyue.icu/Article/details/gtegblbzqc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtxahklkdv.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtnkqpuekv.html

K. JSON 与序列化
来源：http://dali.cucudq.cn/Article/details/gtosgdxfes.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtiqrdehca.html

[K01] 对象转 JSON 字符串
来源：http://dali.xuanzx.com/Article/details/gtniqqxnhg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jyoumei.cn/Article/details/gtdthdwhba.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zycfv.cn/Article/details/gtzmlxtnzd.html

JS:   JSON.stringify(obj)
来源：http://dali.zhoulong.xyz/Article/details/gthwvpvjyq.html

TS:   JSON.stringify(obj)
来源：http://dali.chenzaomai.com/Article/details/gtevxgrnlg.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cucudq.cn/Article/details/gtclfosfgz.html

Go:   json.Marshal(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtirzovjlu.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.tian-w.cn/Article/details/gtsacztmpc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.nanxinkj.top/Article/details/gtokgcpmxt.html

[K02] JSON 字符串转对象
来源：http://dali.yueranfly.top/Article/details/gtemtfngwt.html

Py:   json.loads(s)
来源：http://dali.andypj.xyz/Article/details/gthwvqmxrx.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xuanzx.com/Article/details/gtjoruqgcv.html

JS:   JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtauxikcow.html

TS:   JSON.parse(s)
来源：http://dali.sweek.top/Article/details/gtslqsqtei.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.redwolf501.top/Article/details/gtusbibier.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zycfv.cn/Article/details/gteiutmhno.html

Ruby: JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gtqrizsfft.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhoulong.xyz/Article/details/gtludjztal.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cqqwz.cn/Article/details/gtatgbqqsd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jyoumei.cn/Article/details/gtnljnucqh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cheryme.top/Article/details/gtxqgqvano.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtkxakdhvl.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shzxlz.cn/Article/details/gtfdxuogfc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gzhubu.top/Article/details/gtrgbblpjm.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jiagoushi.top/Article/details/gtirilmqlw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.daxiang520.top/Article/details/gttilmxdbp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cdnleiting.top/Article/details/gtbwydywlm.html

[K04] 读取 JSON 文件
来源：http://dali.zycfv.cn/Article/details/gtcqdjfmdx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhiwuduotai.top/Article/details/gtfutmasyt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtayiltfpo.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guannengcc.top/Article/details/gtoouujijt.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhengqikj.top/Article/details/gtfsuuzwiv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yj202588.top/Article/details/gtwqxfvnyy.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ivvv.top/Article/details/gtzfgcrrxa.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.mhx1999.top/Article/details/gtxqedskac.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjawnjxxc.html

[K05] 深拷贝对象
来源：http://dali.daxiang520.top/Article/details/gtkpzzblii.html

Py:   copy.deepcopy(obj)
来源：http://dali.sweek.top/Article/details/gtinstfady.html

PHP:  unserialize(serialize($obj));
来源：http://dali.guannengcc.top/Article/details/gtwkyxadus.html

JS:   structuredClone(obj)
来源：http://dali.sufxvd.cn/Article/details/gtcodwfnxg.html

TS:   structuredClone(obj)
来源：http://dali.0kj1m.cn/Article/details/gtcmskeump.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shanyushiyangtech.top/Article/details/gtyrbhybig.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.c1oappe.top/Article/details/gtzgnikoqr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.0kj1m.cn/Article/details/gthcxszyah.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shangyingyoupin.top/Article/details/gtaelccbid.html

[K06] 解析 URL 查询串
来源：http://dali.jqgufenzy.top/Article/details/gtgdsqgnxf.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hywenlv.cn/Article/details/gtozbecivn.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xziqi.cn/Article/details/gtnkpfiyzd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yueranfly.top/Article/details/gthuadnqnx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hysaishi.cn/Article/details/gtxxzfosbl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.316326.xyz/Article/details/gtdcewsial.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.aizwys.cn/Article/details/gtrcqvoxfg.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gtymddykhl.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwxwzbmtt.html

[K07] 进制转换
来源：http://dali.cdnleiting.top/Article/details/gtvyzbkpzz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gtypslrxtc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gtegjdeesh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gtpslmngpq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gtuaipgefx.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gtzpgxhrkx.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhongyouzk.top/Article/details/gtfcllvosv.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.haohaochexian.top/Article/details/gttpwdskng.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtttmtczyj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.nanxinkj.top/Article/details/gthkrprzyr.html

Py:   pickle.dumps(obj)
来源：http://dali.bjfxy.top/Article/details/gtchntertm.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nwbrower.top/Article/details/gtornlcgks.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cashguo.top/Article/details/gtjhmcoetm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangtech.top/Article/details/gtykvwnrja.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhaomingkeji.xyz/Article/details/gtofifmkxs.html

Go:   encoding/gob
来源：http://dali.andypj.xyz/Article/details/gtiuuynzzk.html

Ruby: Marshal.dump(obj)
来源：http://dali.andypj.xyz/Article/details/gtuuazjlws.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhongyouzk.top/Article/details/gtatwrdtqe.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtgwqevvuq.html

L. 网络请求
来源：http://dali.xuetiantiany.cn/Article/details/gtgxkbdokm.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gttdmxpvqf.html

[L01] 发送 GET 请求
来源：http://dali.svipenyu.cn/Article/details/gtkfxkaykk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.gaohongyu789.top/Article/details/gtyubirzwb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinyuanbaomall.cn/Article/details/gtempjkjlz.html

JS:   await fetch(url)
来源：http://dali.andypj.xyz/Article/details/gtgepxdius.html

TS:   await fetch(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvmrooewj.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.iojbl.cn/Article/details/gtqenpjekx.html

Go:   resp, err := http.Get(url)
来源：http://dali.jqgufenzy.top/Article/details/gtsezmfsaq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cheryme.top/Article/details/gtfrxydcpw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.iojbl.cn/Article/details/gtobbodizs.html

[L02] 发送 POST JSON
来源：http://dali.shanyushiyangkeji.top/Article/details/gterwiushh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.nwbrower.top/Article/details/gthusdbhnu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cashguo.top/Article/details/gtpucgzuwy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cheryme.top/Article/details/gtbhdfzuie.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ydzc1.top/Article/details/gtqxqbdtlx.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zycfv.cn/Article/details/gtsureglrq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.quarkkingdee.top/Article/details/gtzdmrgahk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jqgufenzy.top/Article/details/gtnpoejqix.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ydzc1.top/Article/details/gtjvpmxrvg.html

[L03] 设置自定义请求头
来源：http://dali.zycfv.cn/Article/details/gtmwdmyhtm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hammf.cn/Article/details/gtothcazax.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jyoumei.cn/Article/details/gtzonqkvmq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.quarkkingdee.top/Article/details/gttncsbsnj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigfzy.top/Article/details/gtefdgclhe.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbqymhkim.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gaohongyu789.top/Article/details/gtatrzbmds.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cucudq.cn/Article/details/gteiyskape.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ehwqpu.com/Article/details/gtqlzguexr.html

[L04] 设置超时
来源：http://dali.mhx1999.top/Article/details/gttmjyiyjj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.havefunace.top/Article/details/gtwbxvuivt.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shzxlz.cn/Article/details/gtmaxiyldo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cqqwz.cn/Article/details/gtspwyzdpt.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.9152youxi.cn/Article/details/gtbccoyuqf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cheryme.top/Article/details/gtzgfvdogr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gaohongyu789.top/Article/details/gtjdfluhpf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.9152youxi.cn/Article/details/gtzdegjnfr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhixingplan.top/Article/details/gthjrsvnrq.html

[L05] 上传文件（multipart）
来源：http://dali.hysaishi.cn/Article/details/gtawysluzj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yj20258.top/Article/details/gttfpovspx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yuanzhike.top/Article/details/gtqeuaapbh.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.c1oappe.top/Article/details/gtzxccbxaf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhoulong.xyz/Article/details/gtwmsbdfdr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.nanxuanxn.top/Article/details/gtegugorzd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cheryme.top/Article/details/gtuqpzzrpu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.dashuyun.cn/Article/details/gtkqoicihu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtcpznigmn.html

[L06] 解析响应为 JSON
来源：http://dali.sweek.top/Article/details/gtmuadnbmt.html

Py:   resp.json()
来源：http://dali.tian-w.cn/Article/details/gtstgmogao.html

PHP:  json_decode($body, true);
来源：http://dali.zhengqikj.top/Article/details/gthposozwj.html

JS:   await resp.json()
来源：http://dali.zhoulong.xyz/Article/details/gtvrqbloae.html

TS:   await resp.json()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfhuipuru.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhixingplan.top/Article/details/gtpbbckcdn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.quarkkingdee.top/Article/details/gtpwkpqlmk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj20258888.top/Article/details/gtrxbqncea.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yuanzhike.top/Article/details/gtzhfyyxli.html

[L07] 处理 HTTP 状态码
来源：http://dali.guannengcc.top/Article/details/gtptjzzmap.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ybcxt.top/Article/details/gtksxvayup.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.c1oappe.top/Article/details/gtrwzxrude.html

JS:   resp.ok;  resp.status
来源：http://dali.xziqi.cn/Article/details/gtlshdjgtq.html

TS:   resp.ok;  resp.status
来源：http://dali.aibaodan.cn/Article/details/gtqoiwtekr.html

Java: resp.statusCode()
来源：http://dali.jlsjyb.cn/Article/details/gtgvivabar.html

Go:   resp.StatusCode
来源：http://dali.xinyue.icu/Article/details/gtpzohovvw.html

Ruby: resp.code.to_i
来源：http://dali.cashguo.top/Article/details/gtvrgdrkbw.html

C#:   (int)resp.StatusCode
来源：http://dali.dianchejie.cn/Article/details/gtrsyccrpc.html

[L08] 并发请求多个地址
来源：http://dali.jinqigufen.top/Article/details/gtixorsylm.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hysaishi.cn/Article/details/gtgtuxmwna.html

PHP:  curl_multi_init() 系列
来源：http://dali.yueranfly.top/Article/details/gtnbroscpy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhoulong.xyz/Article/details/gtpzmcqevf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.haohaochexian.top/Article/details/gtvvgyblus.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yonumen.top/Article/details/gtfrvmrzxt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.0kj1m.cn/Article/details/gtygifjiqb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hnxiangtu.top/Article/details/gtcdeurero.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cucudq.cn/Article/details/gtgjgsnvgu.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtfrurhyke.html

M. 命令行 / 进程 / 环境
来源：http://dali.ydzc1.top/Article/details/gtrbotudfs.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtojxpkdtg.html

[M01] 读取命令行参数
来源：http://dali.quarkkingdee.top/Article/details/gtdcrticzq.html

Py:   sys.argv[1:]
来源：http://dali.hywenlv.cn/Article/details/gtxyqojxjg.html

PHP:  $argv;  $argc;
来源：http://dali.nanxinkj.top/Article/details/gtvngwakme.html

JS:   process.argv.slice(2)
来源：http://dali.chenlongwang.top/Article/details/gtvkwkfttw.html

TS:   process.argv.slice(2)
来源：http://dali.chenzaomai.com/Article/details/gtermnwcfc.html

Java: args 数组（main 方法参数）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkwupicca.html

Go:   os.Args[1:]
来源：http://dali.jianghu66.top/Article/details/gtgxqohgqy.html

Ruby: ARGV
来源：http://dali.chenzaomai.com/Article/details/gtxmmvxtew.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhoulong.xyz/Article/details/gtxglwbjpt.html

[M02] 读取环境变量
来源：http://dali.redwolf501.top/Article/details/gttujnfcaw.html

Py:   os.environ.get("HOME")
来源：http://dali.fengsongda.top/Article/details/gtnibvnuuv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinqigfzy.top/Article/details/gtjphkymar.html

JS:   process.env.HOME
来源：http://dali.ybcxt.top/Article/details/gtkslviadg.html

TS:   process.env.HOME
来源：http://dali.fzhhl.top/Article/details/gtaustcsds.html

Java: System.getenv("HOME")
来源：http://dali.yuxming.cn/Article/details/gtvgdvawrx.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.mhx1999.top/Article/details/gtdojleads.html

Ruby: ENV["HOME"]
来源：http://dali.yongpay.top/Article/details/gttwcfnlpl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xylfe.cn/Article/details/gtxxnapugw.html

[M03] 执行外部命令
来源：http://dali.shzxlz.cn/Article/details/gtpqdzudsc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.nanxuanxn.top/Article/details/gtxplhkdsz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hfpthk.cn/Article/details/gtdzkheumo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxktwxpiw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gtsptoiyjy.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.tian-w.cn/Article/details/gtacapvqeg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gaohongyu789.top/Article/details/gtjqiuzyoe.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.pycfn.com/Article/details/gtdyydmwqp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ybcxt.top/Article/details/gtgoltbzzf.html

[M04] 获取当前工作目录
来源：http://dali.hfpthk.cn/Article/details/gtzyicjpfw.html

Py:   os.getcwd()
来源：http://dali.tanke756.top/Article/details/gtxrzyveao.html

PHP:  getcwd();
来源：http://dali.hfpthk.cn/Article/details/gtwrwioqnu.html

JS:   process.cwd()
来源：http://dali.hysaishi.cn/Article/details/gtlgmzhdmo.html

TS:   process.cwd()
来源：http://dali.iojbl.cn/Article/details/gtqirzphay.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinqigfzy.top/Article/details/gtluewbbyc.html

Go:   os.Getwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnvzldzge.html

Ruby: Dir.pwd
来源：http://dali.zhoulong.xyz/Article/details/gtccfhekfd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nanxinkj.top/Article/details/gtpmijkftv.html

[M05] 设置退出码
来源：http://dali.hywenlv.cn/Article/details/gtfpjcxyou.html

Py:   sys.exit(1)
来源：http://dali.shuidangran.top/Article/details/gtnfxutpvy.html

PHP:  exit(1);
来源：http://dali.nwbrower.top/Article/details/gtdtrrmkkm.html

JS:   process.exit(1)
来源：http://dali.fengsongda.top/Article/details/gtuubfatjv.html

TS:   process.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gtltifefye.html

Java: System.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gticvhxytu.html

Go:   os.Exit(1)
来源：http://dali.aizwys.cn/Article/details/gtvtrhiqha.html

Ruby: exit 1
来源：http://dali.ppjwa.cn/Article/details/gtidjxmlit.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.snrcjt.cn/Article/details/gtgrtgkneg.html

[M06] 向标准错误输出
来源：http://dali.yongpay.top/Article/details/gtjcdezqhs.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlboiugmr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yuxming.cn/Article/details/gtiziehspz.html

JS:   console.error("err")
来源：http://dali.ivvv.top/Article/details/gtkaqdrtij.html

TS:   console.error("err")
来源：http://dali.haohaochexian.top/Article/details/gtupvevlfe.html

Java: System.err.println("err")
来源：http://dali.hongshengwenyu.top/Article/details/gtrnqzwbjb.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gotoacloud.top/Article/details/gtdyjnngcc.html

Ruby: warn "err"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzkjpnmlq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hnxiangtu.top/Article/details/gtiohzljnf.html

[M07] 判断是否为主入口
来源：http://dali.cucudq.cn/Article/details/gtiolyvcen.html

Py:   if __name__ == "__main__":
来源：http://dali.ppjwa.cn/Article/details/gtetofltws.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.vqdsnc.cn/Article/details/gtlogndnsc.html

JS:   require.main === module
来源：http://dali.xylfe.cn/Article/details/gtjmztjnco.html

TS:   require.main === module
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlmismnim.html

Java: public static void main(String[] args)
来源：http://dali.yj202588.top/Article/details/gtxveekhrb.html

Go:   func main()
来源：http://dali.iojbl.cn/Article/details/gtfnrwqanl.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.nwbrower.top/Article/details/gtbeagkpkj.html

C#:   static void Main(string[] args)
来源：http://dali.sweek.top/Article/details/gtfdmugapd.html

[M08] 获取系统与运行时信息
来源：http://dali.zycfv.cn/Article/details/gtofwmbxgy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ydzc1.top/Article/details/gtfjjynxbt.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zycfv.cn/Article/details/gtovhrgmel.html

JS:   process.platform;  process.version
来源：http://dali.hnxiangtu.top/Article/details/gttwebvhyc.html


<!-- 参考信息 -->