代发 wailian999

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.wangshuangyany.cn/Article/details/gtbflihfdx.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.wangdashe.top/Article/details/gtzldxbbqd.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigfzy.top/Article/details/gtshytzsch.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ppjwa.cn/Article/details/gtvwgtbotr.html

[J03] 字符串解析为日期
来源：http://dali.yj20258888.top/Article/details/gtfytxikqc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cheryme.top/Article/details/gtjlhxaugq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sxryk.cn/Article/details/gtinzbmknb.html

JS:   new Date("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gtkmfhdllf.html

TS:   new Date("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gtdckjkqcv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gtszeqfalh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sweek.top/Article/details/gtkqmulqcq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gtnbuuzlhh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.tanke756.top/Article/details/gteyphqrgb.html

[J04] 时间戳与日期互转
来源：http://dali.jianghu66.top/Article/details/gtzqpkgtah.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gzhubu.top/Article/details/gtdtvunkht.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.smart0.xyz/Article/details/gtxjwubutu.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.chenzaomai.com/Article/details/gtvzrvzyez.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.guannengcc.top/Article/details/gtowxluqfb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.chenzaomai.com/Article/details/gtzrraikcc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shzxlz.cn/Article/details/gttyzesldi.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.kuanghao11.cn/Article/details/gtnxxumuwd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.chenlongwang.top/Article/details/gtyumpyyki.html

[J05] 时间加减（加 7 天）
来源：http://dali.gotoacloud.top/Article/details/gthejlfkkp.html

Py:   now + timedelta(days=7)
来源：http://dali.zhixingplan.top/Article/details/gtsmcayfox.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfnuadqgz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yanxiufei.cn/Article/details/gtqfbmmlex.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.mhx1999.top/Article/details/gtbjzkthie.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hywenlv.cn/Article/details/gtprbtqgdh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jqgufenzy.top/Article/details/gtzepmxeii.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cucudq.cn/Article/details/gtumuwrlun.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.nwbrower.top/Article/details/gthxlkiiwn.html

[J06] 计算两时间之差
来源：http://dali.hnxiangtu.top/Article/details/gtaboqmvgf.html

Py:   (end - start).total_seconds()
来源：http://dali.redwolf501.top/Article/details/gtcftvdsjg.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhiwuduotai.top/Article/details/gtdybgyonc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.feifeiyinyue.top/Article/details/gtowdwltpe.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.aibaodan.cn/Article/details/gttgeipqam.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sweek.top/Article/details/gtijylmnyz.html

Go:   end.Sub(start).Hours()
来源：http://dali.pengpengdd.cyou/Article/details/gttbbchaoy.html

Ruby: end - start                 # 返回秒数
来源：http://dali.aibaodan.cn/Article/details/gtjbuppfwf.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinghuilouyu.cn/Article/details/gtleyufddv.html

[J07] 比较两个日期
来源：http://dali.ehwqpu.com/Article/details/gtzsvgybnl.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sxryk.cn/Article/details/gtoequlsey.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwzztdnpc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.tianlin.xyz/Article/details/gtkrjffnad.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yuxming.cn/Article/details/gtlvkgrovx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yj202588.top/Article/details/gtuyetwguf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hysaishi.cn/Article/details/gtyblwcojt.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jinghuilouyu.cn/Article/details/gtufoigmkr.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gtbmcihhij.html

[J08] 提取年月日与星期
来源：http://dali.9152youxi.cn/Article/details/gtyugumfgf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinqigufen.top/Article/details/gtqhwugobq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.snrcjt.cn/Article/details/gtpsalkmur.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhongyouzk.top/Article/details/gtmhulrwxk.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shuidangran.top/Article/details/gthkupcgef.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cashguo.top/Article/details/gtqpvuaygo.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jiagoushi.top/Article/details/gtaozzyaxa.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.birdmap.top/Article/details/gtkisilful.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.316326.xyz/Article/details/gtbtitutyo.html

[J09] 时区处理
来源：http://dali.vqdsnc.cn/Article/details/gtguycvbqg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.bjfxy.top/Article/details/gtfzhohlas.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ehwqpu.com/Article/details/gtigderhvs.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.kuanghao11.cn/Article/details/gthvtaamsj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aibaodan.cn/Article/details/gtqfzzshlp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xuetiantiany.cn/Article/details/gtfjynmilp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yuanzhike.top/Article/details/gtwelukgwj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hnxiangtu.top/Article/details/gtjnazmhhx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinqigufen.top/Article/details/gtuzpwbeuv.html

[J10] 取今天 / 本月第一天
来源：http://dali.316326.xyz/Article/details/gtrkaqrvqy.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xuetiantiany.cn/Article/details/gtvmzpwqqb.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.birdmap.top/Article/details/gtywcmecdr.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gotoacloud.top/Article/details/gtdlghcvto.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.chenzaomai.com/Article/details/gtzuranpxs.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hnqzz.top/Article/details/gtxbaijywq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.birdmap.top/Article/details/gtqsysyvev.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiuflgmhf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.smart0.xyz/Article/details/gtlijorcdo.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtetxxgmlr.html

K. JSON 与序列化
来源：http://dali.yj202588.top/Article/details/gthqclkkrk.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtdzbtbjhg.html

[K01] 对象转 JSON 字符串
来源：http://dali.pycfn.com/Article/details/gtshihtorm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ehwqpu.com/Article/details/gtpsgmkzks.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.fzhhl.top/Article/details/gtwaolebhc.html

JS:   JSON.stringify(obj)
来源：http://dali.cashguo.top/Article/details/gtfyhbkebr.html

TS:   JSON.stringify(obj)
来源：http://dali.redwolf501.top/Article/details/gtowpcqypc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xinyue.icu/Article/details/gtguxfvfbu.html

Go:   json.Marshal(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtwiqtuvtg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.aizwys.cn/Article/details/gtccreczvq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtlvpgsasb.html

[K02] JSON 字符串转对象
来源：http://dali.yongpay.top/Article/details/gttrunyxsa.html

Py:   json.loads(s)
来源：http://dali.yuanzhike.top/Article/details/gtpvrjxdbk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinqigfzy.top/Article/details/gtpcsfccat.html

JS:   JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gtudcwywky.html

TS:   JSON.parse(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsbnogwfw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yonumen.top/Article/details/gtvdpmnqaz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.meibo888.top/Article/details/gttzelfsvp.html

Ruby: JSON.parse(s)
来源：http://dali.sysykeji.top/Article/details/gtwoqhrtmn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hnqzz.top/Article/details/gtkyifaiic.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jlsjyb.cn/Article/details/gtoxcktwpn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jianghu66.top/Article/details/gtxxhfwbaq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.smart0.xyz/Article/details/gtlsxqzkyt.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgfzy.top/Article/details/gtzmjafwoj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.daxiang520.top/Article/details/gtsbdpqgah.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtcdnpeguy.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ydzc1.top/Article/details/gttbkjqcsi.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.c1oappe.top/Article/details/gtgvtwvlul.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.pycfn.com/Article/details/gtqgsasmtz.html

[K04] 读取 JSON 文件
来源：http://dali.yvedp.cn/Article/details/gthcjdwquq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gtkqpgqeye.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.feifeiyinyue.top/Article/details/gtjswpzriy.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.havefunace.top/Article/details/gtlyhtcrvq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ybcxt.top/Article/details/gtqegsudwr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.daria6918.cn/Article/details/gteowyzygi.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.mhx1999.top/Article/details/gtnfinjjql.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.aibaodan.cn/Article/details/gtilwrydaz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.snrcjt.cn/Article/details/gtqbchzgqy.html

[K05] 深拷贝对象
来源：http://dali.wangdashe.top/Article/details/gtltrinfpb.html

Py:   copy.deepcopy(obj)
来源：http://dali.daxiang520.top/Article/details/gtvfkielel.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xylfe.cn/Article/details/gtvupuqsvm.html

JS:   structuredClone(obj)
来源：http://dali.cdnleiting.top/Article/details/gtxqwkhfsv.html

TS:   structuredClone(obj)
来源：http://dali.svipenyu.cn/Article/details/gtbasnbbqd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.wangshuangyany.cn/Article/details/gtaeewlccq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jiagoushi.top/Article/details/gthezkojbi.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.aizwys.cn/Article/details/gtmrclzcaz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cashguo.top/Article/details/gttasgeera.html

[K06] 解析 URL 查询串
来源：http://dali.yuanzhike.top/Article/details/gtjoprxmer.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzwgzjxkn.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.redwolf501.top/Article/details/gteiggnoub.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tanke756.top/Article/details/gtdnwpafwh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.fengsongda.top/Article/details/gtfbvlcnal.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhoulong.xyz/Article/details/gtwispsqld.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jyoumei.cn/Article/details/gtdkclgzow.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.pengpengdd.cyou/Article/details/gtmtrwzztv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gtcmzmuujr.html

[K07] 进制转换
来源：http://dali.jinqigufen.top/Article/details/gtsgkdbrvp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gtubggrcuj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.dashuyun.cn/Article/details/gtjwnbeijy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcbtxzodq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gtptjdkanh.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gtkyqljwst.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hnqzz.top/Article/details/gtgibowzok.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.gotoacloud.top/Article/details/gtqzpxisrw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaovuhqkl.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.chenzaomai.com/Article/details/gtnzryzzxb.html

Py:   pickle.dumps(obj)
来源：http://dali.svipenyu.cn/Article/details/gtyjeutlpr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yj20258.top/Article/details/gtuauwxgqy.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.pengpengdd.cyou/Article/details/gtdliljnyg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.316326.xyz/Article/details/gtqyshisgb.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sxryk.cn/Article/details/gtxezxjlby.html

Go:   encoding/gob
来源：http://dali.jinqigfzy.top/Article/details/gtyobffeid.html

Ruby: Marshal.dump(obj)
来源：http://dali.ivvv.top/Article/details/gtihnezmcu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.iojbl.cn/Article/details/gtuwzkplmn.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtviopuwhu.html

L. 网络请求
来源：http://dali.cdnleiting.top/Article/details/gtbsucjqkx.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtknimplsg.html

[L01] 发送 GET 请求
来源：http://dali.pycfn.com/Article/details/gtjpeerqby.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xuanzx.com/Article/details/gtyjyzxoxj.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yongpay.top/Article/details/gtdlwgbglr.html

JS:   await fetch(url)
来源：http://dali.jiagoushi.top/Article/details/gtwoaeeuxn.html

TS:   await fetch(url)
来源：http://dali.bjfxy.top/Article/details/gtbkhkmbho.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hnqzz.top/Article/details/gteiqtetgr.html

Go:   resp, err := http.Get(url)
来源：http://dali.quarkkingdee.top/Article/details/gtcysjxcuz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.quarkkingdee.top/Article/details/gtwmcbyfge.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyzoosctu.html

[L02] 发送 POST JSON
来源：http://dali.hfpthk.cn/Article/details/gtanespham.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhongyouzk.top/Article/details/gtjbwvbspx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hysaishi.cn/Article/details/gtqsssznca.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sweek.top/Article/details/gthnqusduy.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gaohongyu789.top/Article/details/gtsrnicreb.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.nwbrower.top/Article/details/gtvipkqkyi.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.pengpengdd.cyou/Article/details/gtmlwuyghv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.kuanghao11.cn/Article/details/gtmqpubjqy.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyqxgylpn.html

[L03] 设置自定义请求头
来源：http://dali.dianchejie.cn/Article/details/gtlyarrzkn.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhoulong.xyz/Article/details/gtgwatbbsp.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yueranfly.top/Article/details/gtwvafehcd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuxming.cn/Article/details/gtgatzwdrf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fengsongda.top/Article/details/gtrtaxmxdg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.vqdsnc.cn/Article/details/gtamvyjjdw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hongshengwenyu.top/Article/details/gtriordamq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xuanzx.com/Article/details/gtorwqvakg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zycfv.cn/Article/details/gtpprwmsnl.html

[L04] 设置超时
来源：http://dali.aibaodan.cn/Article/details/gtcdzltugc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.svipenyu.cn/Article/details/gtcjahjejp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhixingplan.top/Article/details/gtdqdeppxa.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jyoumei.cn/Article/details/gtwvqizpso.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhoulong.xyz/Article/details/gtsehrpvuo.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinqigfzy.top/Article/details/gtmfvadjpy.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yanxiufei.cn/Article/details/gtlfaorafr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthpyhuqyj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yuanzhike.top/Article/details/gtffqcljkg.html

[L05] 上传文件（multipart）
来源：http://dali.hnqzz.top/Article/details/gtjgmlhafi.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gzhubu.top/Article/details/gthokiojtq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjryeyurg.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.redwolf501.top/Article/details/gtkyjlzdkp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.haohaochexian.top/Article/details/gtivmbxnox.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ywan-chungtsiang.top/Article/details/gtchvrnecx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hnqzz.top/Article/details/gtitzumcor.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yanxiufei.cn/Article/details/gtnoiqkovl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yvedp.cn/Article/details/gtpvkmdocc.html

[L06] 解析响应为 JSON
来源：http://dali.c1oappe.top/Article/details/gtmwexqevo.html

Py:   resp.json()
来源：http://dali.jyoumei.cn/Article/details/gtulbldxxd.html

PHP:  json_decode($body, true);
来源：http://dali.nwbrower.top/Article/details/gtjzmldkwq.html

JS:   await resp.json()
来源：http://dali.redwolf501.top/Article/details/gtbspywehc.html

TS:   await resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gtjpzllciy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yvedp.cn/Article/details/gtpiyppsjv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.redwolf501.top/Article/details/gtqqgjqdxl.html

Ruby: JSON.parse(resp.body)
来源：http://dali.chenjidiqi.icu/Article/details/gtrfxnfgln.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.316326.xyz/Article/details/gtsabeybec.html

[L07] 处理 HTTP 状态码
来源：http://dali.hysaishi.cn/Article/details/gtzfuuoqbk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj202588.top/Article/details/gtrfygnxro.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yj20258.top/Article/details/gtaihxlfnh.html

JS:   resp.ok;  resp.status
来源：http://dali.xuanzx.com/Article/details/gthtqrbehc.html

TS:   resp.ok;  resp.status
来源：http://dali.snrcjt.cn/Article/details/gtlxaybors.html

Java: resp.statusCode()
来源：http://dali.birdmap.top/Article/details/gtxgyzcgkf.html

Go:   resp.StatusCode
来源：http://dali.yueranfly.top/Article/details/gtuxtnivcm.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gtvyqosegu.html

C#:   (int)resp.StatusCode
来源：http://dali.quarkkingdee.top/Article/details/gtxyszfmoa.html

[L08] 并发请求多个地址
来源：http://dali.sufxvd.cn/Article/details/gthjrzomfl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yueranfly.top/Article/details/gtwbrqggzu.html

PHP:  curl_multi_init() 系列
来源：http://dali.guannengcc.top/Article/details/gtrvxhaapv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tian-w.cn/Article/details/gtyjganlxo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sufxvd.cn/Article/details/gtkcajplll.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.wangdashe.top/Article/details/gtaqtribxx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hfpthk.cn/Article/details/gttitcejwm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jqgfzy.top/Article/details/gtgfncbcdr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.havefunace.top/Article/details/gtgbwxihbt.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtigmiexro.html

M. 命令行 / 进程 / 环境
来源：http://dali.jianghu66.top/Article/details/gtpvopfyre.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtfsdksqwy.html

[M01] 读取命令行参数
来源：http://dali.xylfe.cn/Article/details/gtdiriyjbg.html

Py:   sys.argv[1:]
来源：http://dali.redwolf501.top/Article/details/gtcvqjvvws.html

PHP:  $argv;  $argc;
来源：http://dali.jinqigfzy.top/Article/details/gthmsjloaq.html

JS:   process.argv.slice(2)
来源：http://dali.pengpengdd.cyou/Article/details/gtmfgemnzs.html

TS:   process.argv.slice(2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtukbruvor.html

Java: args 数组（main 方法参数）
来源：http://dali.hywenlv.cn/Article/details/gtoymveqhb.html

Go:   os.Args[1:]
来源：http://dali.daria6918.cn/Article/details/gtfzkmyefe.html

Ruby: ARGV
来源：http://dali.jqgfzy.top/Article/details/gtfispcoqf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.aibaodan.cn/Article/details/gtucthnvdv.html

[M02] 读取环境变量
来源：http://dali.vqdsnc.cn/Article/details/gtrfprlgrw.html

Py:   os.environ.get("HOME")
来源：http://dali.cashguo.top/Article/details/gtyllgphrh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sufxvd.cn/Article/details/gtysvreitw.html

JS:   process.env.HOME
来源：http://dali.hnqzz.top/Article/details/gtyriyhmox.html

TS:   process.env.HOME
来源：http://dali.zhoulong.xyz/Article/details/gtoojzdbdu.html

Java: System.getenv("HOME")
来源：http://dali.havefunace.top/Article/details/gtxacikdpp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.aizwys.cn/Article/details/gtesxyfwpf.html

Ruby: ENV["HOME"]
来源：http://dali.nwbrower.top/Article/details/gtpqudvbul.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jyoumei.cn/Article/details/gtymxjmilf.html

[M03] 执行外部命令
来源：http://dali.gotoacloud.top/Article/details/gtymzzorjm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hysaishi.cn/Article/details/gtzqeptetu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.mhx1999.top/Article/details/gtovpsinwa.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.haohaochexian.top/Article/details/gtfwmcepcb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhixingplan.top/Article/details/gttmvzgfwq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hongshengwenyu.top/Article/details/gtvjfanhgn.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gtclxuvmku.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinghuilouyu.cn/Article/details/gtnkkobpqo.html

C#:   Process.Start("ls", "-l");
来源：http://dali.chenjidiqi.icu/Article/details/gttrnrludd.html

[M04] 获取当前工作目录
来源：http://dali.jqgufenzy.top/Article/details/gtvecrtyak.html

Py:   os.getcwd()
来源：http://dali.yongpay.top/Article/details/gttfqimiix.html

PHP:  getcwd();
来源：http://dali.xylfe.cn/Article/details/gthmrjlsfi.html

JS:   process.cwd()
来源：http://dali.feifeiyinyue.top/Article/details/gtaqotocgu.html

TS:   process.cwd()
来源：http://dali.hysaishi.cn/Article/details/gtayjiahky.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.316326.xyz/Article/details/gtyazkkbfu.html

Go:   os.Getwd()
来源：http://dali.zhiwuduotai.top/Article/details/gtoqnfiknm.html

Ruby: Dir.pwd
来源：http://dali.chenjidiqi.icu/Article/details/gtpmjmoams.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhixingplan.top/Article/details/gtgikcverl.html

[M05] 设置退出码
来源：http://dali.zdqjudy.top/Article/details/gttastoruu.html

Py:   sys.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gtpgenyvnn.html

PHP:  exit(1);
来源：http://dali.nwbrower.top/Article/details/gtqxtmpbzf.html

JS:   process.exit(1)
来源：http://dali.tian-w.cn/Article/details/gtrnvlloue.html

TS:   process.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbxpkyfch.html

Java: System.exit(1)
来源：http://dali.xinyue.icu/Article/details/gtuoxnksyb.html

Go:   os.Exit(1)
来源：http://dali.dashuyun.cn/Article/details/gtvrtwtndc.html

Ruby: exit 1
来源：http://dali.316326.xyz/Article/details/gtuklitrmw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.guowangkeji.top/Article/details/gtrtbnyxta.html

[M06] 向标准错误输出
来源：http://dali.wangdashe.top/Article/details/gtndxhejbd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.haohaochexian.top/Article/details/gtbgiecvgf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.birdmap.top/Article/details/gtscptdvzc.html

JS:   console.error("err")
来源：http://dali.xylfe.cn/Article/details/gtkklrtwui.html

TS:   console.error("err")
来源：http://dali.cqqwz.cn/Article/details/gtiaswbrmr.html

Java: System.err.println("err")
来源：http://dali.nwbrower.top/Article/details/gtlzbpbblf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.chenlongwang.top/Article/details/gtbedkglog.html

Ruby: warn "err"
来源：http://dali.xuetiantiany.cn/Article/details/gtfkgggdkv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.daria6918.cn/Article/details/gtkbbungpg.html

[M07] 判断是否为主入口
来源：http://dali.gogol.net.cn/Article/details/gtvokfbubg.html

Py:   if __name__ == "__main__":
来源：http://dali.zhengqikj.top/Article/details/gtybhlqeqk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.0kj1m.cn/Article/details/gtqpwvjqxh.html

JS:   require.main === module
来源：http://dali.yj20258888.top/Article/details/gtcuutjosr.html

TS:   require.main === module
来源：http://dali.birdmap.top/Article/details/gtirhukmyv.html

Java: public static void main(String[] args)
来源：http://dali.cdnleiting.top/Article/details/gtuyutmmze.html

Go:   func main()
来源：http://dali.dianchejie.cn/Article/details/gtrxgepyfw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.aizwys.cn/Article/details/gtjabljmrt.html

C#:   static void Main(string[] args)
来源：http://dali.nwbrower.top/Article/details/gtyjmfnwwc.html

[M08] 获取系统与运行时信息
来源：http://dali.gaohongyu789.top/Article/details/gtmsyzstvl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yj202588.top/Article/details/gtndszlhhx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.meibo888.top/Article/details/gtmysxdeku.html

JS:   process.platform;  process.version
来源：http://dali.shzxlz.cn/Article/details/gtqztswrin.html

TS:   process.platform;  process.version
来源：http://dali.nanxuanxn.top/Article/details/gtkdglxoox.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.nwbrower.top/Article/details/gtoeqatjlj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cucudq.cn/Article/details/gtwrnfmhqa.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.tian-w.cn/Article/details/gtlqrdilpo.html


<!-- 参考信息 -->