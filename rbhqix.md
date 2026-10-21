代发 wailian999

[J03] 字符串解析为日期
来源：http://dali.tian-w.cn/Article/details/gtrtvsflpw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.chenjidiqi.icu/Article/details/gtlulkmywv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtimobvtjf.html

JS:   new Date("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gtwffvzeyy.html

TS:   new Date("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gtwhwsrdpv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtcpoucwov.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gtvkycixlk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gtfilopmhc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinqigufen.top/Article/details/gtzhzvesdh.html

[J04] 时间戳与日期互转
来源：http://dali.hnxiangtu.top/Article/details/gtpjiicdds.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shzxlz.cn/Article/details/gtylyulaoe.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.havefunace.top/Article/details/gtfxzpjpbd.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yonumen.top/Article/details/gtvlyahgqg.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.bjfxy.top/Article/details/gticiadzor.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sxryk.cn/Article/details/gtkiyulqrr.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yvedp.cn/Article/details/gtoqvbsurf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.snrcjt.cn/Article/details/gtqaonzewt.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.meibo888.top/Article/details/gtmcfdzmjn.html

[J05] 时间加减（加 7 天）
来源：http://dali.tanke756.top/Article/details/gtztckczss.html

Py:   now + timedelta(days=7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtylfplecy.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhongyouzk.top/Article/details/gteentboxw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhengqikj.top/Article/details/gtzlvgqwok.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jianghu66.top/Article/details/gtonklvgon.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xuanzx.com/Article/details/gtowbxknay.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jyoumei.cn/Article/details/gtojpbdazn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ybcxt.top/Article/details/gtcagxpmkp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sxryk.cn/Article/details/gtypigiqtr.html

[J06] 计算两时间之差
来源：http://dali.hnxiangtu.top/Article/details/gtmeidmxye.html

Py:   (end - start).total_seconds()
来源：http://dali.yueranfly.top/Article/details/gtjtjatjcx.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhixingplan.top/Article/details/gtkzabhoxs.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj202588.top/Article/details/gtynwpdnlp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ppjwa.cn/Article/details/gtltztkyqb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gaohongyu789.top/Article/details/gtvdjreffp.html

Go:   end.Sub(start).Hours()
来源：http://dali.yj20258.top/Article/details/gthxjnfggx.html

Ruby: end - start                 # 返回秒数
来源：http://dali.tanke756.top/Article/details/gtwdomezeg.html

C#:   (end - start).TotalSeconds
来源：http://dali.zdqjudy.top/Article/details/gtfzuceztl.html

[J07] 比较两个日期
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxbsyxnha.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ydzc1.top/Article/details/gtawpnthby.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.fengsongda.top/Article/details/gtwatataju.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinghuilouyu.cn/Article/details/gtofftxyrz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hywenlv.cn/Article/details/gtnebhqmlc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ydzc1.top/Article/details/gtiulejffl.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.bjfxy.top/Article/details/gtzvxhplty.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.daria6918.cn/Article/details/gtbobomzam.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.daria6918.cn/Article/details/gtmihhiacr.html

[J08] 提取年月日与星期
来源：http://dali.aizwys.cn/Article/details/gtuaaahzdj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.fengsongda.top/Article/details/gtsedtjaya.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.dashuyun.cn/Article/details/gtllwnhtnv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwsrrpzct.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthrjrnrnh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.havefunace.top/Article/details/gtgjidgiwc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.meibo888.top/Article/details/gtkbtdjzjj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gaohongyu789.top/Article/details/gtefescsjc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hongshengwenyu.top/Article/details/gtifnbncer.html

[J09] 时区处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtspgjtxga.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yj20258888.top/Article/details/gtqegkqqld.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.guannengcc.top/Article/details/gtglkmyizk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xylfe.cn/Article/details/gtowvadntm.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sufxvd.cn/Article/details/gtcmepcikj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gotoacloud.top/Article/details/gtytoibulr.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jqgfzy.top/Article/details/gtxgnbmpzy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.0kj1m.cn/Article/details/gtakdrpvhv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ehwqpu.com/Article/details/gtabpjture.html

[J10] 取今天 / 本月第一天
来源：http://dali.jianghu66.top/Article/details/gtexkpfxfr.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yuanzhike.top/Article/details/gtongoctda.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hywenlv.cn/Article/details/gtxggrnniy.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ybcxt.top/Article/details/gtxrsbokxf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ydzc1.top/Article/details/gtntvcvftq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.316326.xyz/Article/details/gtfpmpxtht.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ehwqpu.com/Article/details/gtpitykise.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shanyushiyangtech.top/Article/details/gtjsrghjuc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zycfv.cn/Article/details/gttsisbtba.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtqokrcwdi.html

K. JSON 与序列化
来源：http://dali.xuetiantiany.cn/Article/details/gtkpzkwrca.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtlxjmmntb.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtnoqpdxxi.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinqigfzy.top/Article/details/gtkbrddpuh.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yangfankeji.com/Article/details/gttvymtxeh.html

JS:   JSON.stringify(obj)
来源：http://dali.shuidangran.top/Article/details/gtiwbecnkm.html

TS:   JSON.stringify(obj)
来源：http://dali.cashguo.top/Article/details/gtnnxqwxku.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.aizwys.cn/Article/details/gtmmezowdj.html

Go:   json.Marshal(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gttxrnptym.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xylfe.cn/Article/details/gtwmtzclhj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shzxlz.cn/Article/details/gtgotreyle.html

[K02] JSON 字符串转对象
来源：http://dali.jinghuilouyu.cn/Article/details/gtczukriwn.html

Py:   json.loads(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdfeevgck.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hnxiangtu.top/Article/details/gtnficfqco.html

JS:   JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gtryboxiot.html

TS:   JSON.parse(s)
来源：http://dali.dashuyun.cn/Article/details/gteglgdwxa.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yuxming.cn/Article/details/gtxsbykkns.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.iojbl.cn/Article/details/gtewcefpsu.html

Ruby: JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gtcrqydzoi.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtkizecymd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.guowangkeji.top/Article/details/gtlwdqfewu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhoulong.xyz/Article/details/gtmhfozfxp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.dashuyun.cn/Article/details/gtmpmguzkt.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinqigufen.top/Article/details/gtrficqynq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxaoehthy.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtimlmxtyg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.smart0.xyz/Article/details/gtfsdftsuk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yonumen.top/Article/details/gtxcvosfeq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.daria6918.cn/Article/details/gtelvepbkg.html

[K04] 读取 JSON 文件
来源：http://dali.zdqjudy.top/Article/details/gtishqdoqp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.aibaodan.cn/Article/details/gtgyeetbwi.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.aibaodan.cn/Article/details/gtoyceqivk.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtorllgfwo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aizwys.cn/Article/details/gtrstjgmmf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yanxiufei.cn/Article/details/gtiobkijix.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jqgufenzy.top/Article/details/gtnvyalsny.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jyoumei.cn/Article/details/gtxwhiegqm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.iojbl.cn/Article/details/gtxtwmcsio.html

[K05] 深拷贝对象
来源：http://dali.meibo888.top/Article/details/gtkctwsbnq.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhengqikj.top/Article/details/gtnutsupdw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhoulong.xyz/Article/details/gtqggcvxul.html

JS:   structuredClone(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgrmmtkzd.html

TS:   structuredClone(obj)
来源：http://dali.yj202588.top/Article/details/gtstaiikqo.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.fengsongda.top/Article/details/gtmrmeyzqu.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yj202588.top/Article/details/gtketxjlmq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.sweek.top/Article/details/gtmppfeeyt.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ybcxt.top/Article/details/gtnehwllhm.html

[K06] 解析 URL 查询串
来源：http://dali.yanxiufei.cn/Article/details/gtvvqawwcf.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkwiezsfw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.bjfxy.top/Article/details/gtajktavmt.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.dashuyun.cn/Article/details/gtgxpzumgl.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cqqwz.cn/Article/details/gtglwrrihj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xziqi.cn/Article/details/gtdxofqqtd.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvvuqirhs.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.0kj1m.cn/Article/details/gtawyzubox.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.guannengcc.top/Article/details/gtqjujozfr.html

[K07] 进制转换
来源：http://dali.meibo888.top/Article/details/gtcuruhyil.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gtfhqdchhm.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.daxiang520.top/Article/details/gtocjtdfkd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtpeddyuts.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gtllfikjzj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtlfzamphq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.daxiang520.top/Article/details/gtgabfgtnf.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.gogol.net.cn/Article/details/gtvzdaoaob.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gtnvstdmky.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.andypj.xyz/Article/details/gtfzuxjonq.html

Py:   pickle.dumps(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtqsnwvkcn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.aibaodan.cn/Article/details/gtattplqyk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.daxiang520.top/Article/details/gtxcitqcmk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hywenlv.cn/Article/details/gtzkwrlkji.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.guowangkeji.top/Article/details/gtpvpwaiaa.html

Go:   encoding/gob
来源：http://dali.cqqwz.cn/Article/details/gtffhwdlqz.html

Ruby: Marshal.dump(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiwdegzuf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.sxryk.cn/Article/details/gtfjayhbki.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtrggisbvf.html

L. 网络请求
来源：http://dali.shanyushiyangtech.top/Article/details/gtnmtgtnnv.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtfigncbvz.html

[L01] 发送 GET 请求
来源：http://dali.zhiwuduotai.top/Article/details/gtiwmryeff.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.chenlongwang.top/Article/details/gtsghohevk.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.snrcjt.cn/Article/details/gtkgkbwwsj.html

JS:   await fetch(url)
来源：http://dali.sufxvd.cn/Article/details/gtxofveore.html

TS:   await fetch(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwrnabidu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.nwbrower.top/Article/details/gtxudapqye.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhiwuduotai.top/Article/details/gtspbofjvg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cdnleiting.top/Article/details/gtekudugxz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinqigfzy.top/Article/details/gtenyejddl.html

[L02] 发送 POST JSON
来源：http://dali.yongpay.top/Article/details/gtzmqfclyf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.kuanghao11.cn/Article/details/gtntgwljcs.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.dashuyun.cn/Article/details/gtvsjuazzn.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.kuanghao11.cn/Article/details/gthsusvkck.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nanxuanxn.top/Article/details/gtcajcbexc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hfpthk.cn/Article/details/gtjilicfpu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jianghu66.top/Article/details/gtthcvtdcz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ybcxt.top/Article/details/gtrlrdxcpy.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.tian-w.cn/Article/details/gtoeqorwci.html

[L03] 设置自定义请求头
来源：http://dali.cashguo.top/Article/details/gtyezmifsa.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.kuanghao11.cn/Article/details/gtwytdulfv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yj20258888.top/Article/details/gtxpywvlcy.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhengqikj.top/Article/details/gtviylgysf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.dianchejie.cn/Article/details/gtykygtfjj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hysaishi.cn/Article/details/gtzfmgrlzc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sufxvd.cn/Article/details/gtfxefcndv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hnqzz.top/Article/details/gtjzjnwxxb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinqigufen.top/Article/details/gtwxveqyri.html

[L04] 设置超时
来源：http://dali.dashuyun.cn/Article/details/gthnpccgzy.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tian-w.cn/Article/details/gtgvgkpcal.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cqqwz.cn/Article/details/gtauacsfuz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yanxiufei.cn/Article/details/gtycvqlusc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yvedp.cn/Article/details/gtfgmsdpij.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yongpay.top/Article/details/gtchkgczcs.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ppjwa.cn/Article/details/gtlowywapq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jqgufenzy.top/Article/details/gtoufsqzri.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenlongwang.top/Article/details/gtbohrcnii.html

[L05] 上传文件（multipart）
来源：http://dali.cucudq.cn/Article/details/gtdhreumjq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gogol.net.cn/Article/details/gtfhfqrrdh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.316326.xyz/Article/details/gttxwhudgb.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.guowangkeji.top/Article/details/gtogjcwrya.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yangfankeji.com/Article/details/gtgdkuyuwb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.fengsongda.top/Article/details/gtghrucoxh.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.andypj.xyz/Article/details/gtxodypaim.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.meibo888.top/Article/details/gttavektor.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmilxdmgk.html

[L06] 解析响应为 JSON
来源：http://dali.pengpengdd.cyou/Article/details/gtwzflgytw.html

Py:   resp.json()
来源：http://dali.0kj1m.cn/Article/details/gtzttgkojw.html

PHP:  json_decode($body, true);
来源：http://dali.yj20258.top/Article/details/gtgaolkzag.html

JS:   await resp.json()
来源：http://dali.chenjidiqi.icu/Article/details/gtbjbxyrbh.html

TS:   await resp.json()
来源：http://dali.daxiang520.top/Article/details/gtjpnxiomb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenjidiqi.icu/Article/details/gtswrxjlpu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hammf.cn/Article/details/gtcmewewjv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shanyushiyangtech.top/Article/details/gtevugedjp.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.andypj.xyz/Article/details/gtfbdaqryv.html

[L07] 处理 HTTP 状态码
来源：http://dali.yonumen.top/Article/details/gtwwrjegtl.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj20258888.top/Article/details/gtruhyybrw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jianghu66.top/Article/details/gtkjvtncjk.html

JS:   resp.ok;  resp.status
来源：http://dali.ehwqpu.com/Article/details/gtjmkfbszq.html

TS:   resp.ok;  resp.status
来源：http://dali.gotoacloud.top/Article/details/gtipmmqlgr.html

Java: resp.statusCode()
来源：http://dali.ivvv.top/Article/details/gtagbjdwaz.html

Go:   resp.StatusCode
来源：http://dali.ydzc1.top/Article/details/gtmgpfitpq.html

Ruby: resp.code.to_i
来源：http://dali.chenlongwang.top/Article/details/gtmmqywcvf.html

C#:   (int)resp.StatusCode
来源：http://dali.daria6918.cn/Article/details/gtszoxacyr.html

[L08] 并发请求多个地址
来源：http://dali.gaohongyu789.top/Article/details/gtlnpsmqbc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.bjfxy.top/Article/details/gtuqyaascf.html

PHP:  curl_multi_init() 系列
来源：http://dali.ivvv.top/Article/details/gtaovtscou.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cqqwz.cn/Article/details/gtknsxblkm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gtunulcigs.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.c1oappe.top/Article/details/gtktolqier.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ydzc1.top/Article/details/gtqpquwrlx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.havefunace.top/Article/details/gtdwqpeuxg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jyoumei.cn/Article/details/gtufwlhyvr.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtnkzblued.html

M. 命令行 / 进程 / 环境
来源：http://dali.shuidangran.top/Article/details/gtxysywfwr.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtikmvoxjh.html

[M01] 读取命令行参数
来源：http://dali.dianchejie.cn/Article/details/gtspmmqhxk.html

Py:   sys.argv[1:]
来源：http://dali.kuanghao11.cn/Article/details/gtaumkjvtv.html

PHP:  $argv;  $argc;
来源：http://dali.daxiang520.top/Article/details/gtvgohgupm.html

JS:   process.argv.slice(2)
来源：http://dali.gzhubu.top/Article/details/gtwovtovld.html

TS:   process.argv.slice(2)
来源：http://dali.dianchejie.cn/Article/details/gtjvtiswfk.html

Java: args 数组（main 方法参数）
来源：http://dali.shangyingyoupin.top/Article/details/gtqbbqnglt.html

Go:   os.Args[1:]
来源：http://dali.hnxiangtu.top/Article/details/gtxxkurhhk.html

Ruby: ARGV
来源：http://dali.cheryme.top/Article/details/gthglqjmwd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpchpiykm.html

[M02] 读取环境变量
来源：http://dali.xylfe.cn/Article/details/gtjbzpiaua.html

Py:   os.environ.get("HOME")
来源：http://dali.cdnleiting.top/Article/details/gtxcbtlwxm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrlcgvaah.html

JS:   process.env.HOME
来源：http://dali.cucudq.cn/Article/details/gtfkzghbtp.html

TS:   process.env.HOME
来源：http://dali.pengpengdd.cyou/Article/details/gtkoglfawl.html

Java: System.getenv("HOME")
来源：http://dali.tian-w.cn/Article/details/gtajvugkml.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.wangdashe.top/Article/details/gtyioqcqku.html

Ruby: ENV["HOME"]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxylxucce.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gtouapvoav.html

[M03] 执行外部命令
来源：http://dali.yangfankeji.com/Article/details/gtkhstyawc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.svipenyu.cn/Article/details/gtpjbdqrgr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj202588.top/Article/details/gtquvnihun.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jianghu66.top/Article/details/gtttasevdc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwcujeisp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhongyouzk.top/Article/details/gttyeiqxtl.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqhorfiqt.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cheryme.top/Article/details/gttbiriwqa.html

C#:   Process.Start("ls", "-l");
来源：http://dali.birdmap.top/Article/details/gtfsdjyygc.html

[M04] 获取当前工作目录
来源：http://dali.cashguo.top/Article/details/gtqwwuykbk.html

Py:   os.getcwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxbpexcjx.html

PHP:  getcwd();
来源：http://dali.yuxming.cn/Article/details/gtgrugaixi.html

JS:   process.cwd()
来源：http://dali.xylfe.cn/Article/details/gtttxmuwsc.html

TS:   process.cwd()
来源：http://dali.yj202588.top/Article/details/gtzgmxjdwi.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.wangdashe.top/Article/details/gtehyilecm.html

Go:   os.Getwd()
来源：http://dali.cheryme.top/Article/details/gtqtpwijja.html

Ruby: Dir.pwd
来源：http://dali.andypj.xyz/Article/details/gtyhkguxrl.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cdnleiting.top/Article/details/gtdsbrtfoc.html

[M05] 设置退出码
来源：http://dali.yueranfly.top/Article/details/gtjxjibbet.html

Py:   sys.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gtlktvfzem.html

PHP:  exit(1);
来源：http://dali.yvedp.cn/Article/details/gtvvsdxdzi.html

JS:   process.exit(1)
来源：http://dali.yueranfly.top/Article/details/gtphajuydy.html

TS:   process.exit(1)
来源：http://dali.cheryme.top/Article/details/gthyslrhdc.html

Java: System.exit(1)
来源：http://dali.cheryme.top/Article/details/gtdijcjjew.html

Go:   os.Exit(1)
来源：http://dali.birdmap.top/Article/details/gthmcwlkcm.html

Ruby: exit 1
来源：http://dali.andypj.xyz/Article/details/gthikptgmj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.gogol.net.cn/Article/details/gtapgxmszv.html

[M06] 向标准错误输出
来源：http://dali.dashuyun.cn/Article/details/gtkttbqkuv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.svipenyu.cn/Article/details/gtesualopa.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ydzc1.top/Article/details/gtzsdctwbf.html

JS:   console.error("err")
来源：http://dali.hongshengwenyu.top/Article/details/gtiwbggkmi.html

TS:   console.error("err")
来源：http://dali.shzxlz.cn/Article/details/gtnqhbfofk.html

Java: System.err.println("err")
来源：http://dali.vqdsnc.cn/Article/details/gtneppvaie.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hfpthk.cn/Article/details/gtjtcgsqph.html

Ruby: warn "err"
来源：http://dali.yj202588.top/Article/details/gtbsqijxpd.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.daria6918.cn/Article/details/gtwfksieuq.html

[M07] 判断是否为主入口
来源：http://dali.wangshuangyany.cn/Article/details/gtdyfzmtyl.html

Py:   if __name__ == "__main__":
来源：http://dali.dashuyun.cn/Article/details/gtrlpjgmze.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.mhx1999.top/Article/details/gtektxdybf.html

JS:   require.main === module
来源：http://dali.0kj1m.cn/Article/details/gtvamsebpx.html

TS:   require.main === module
来源：http://dali.xziqi.cn/Article/details/gtjnhsntsc.html

Java: public static void main(String[] args)
来源：http://dali.dashuyun.cn/Article/details/gtambwcfmp.html

Go:   func main()
来源：http://dali.fzhhl.top/Article/details/gtslecvvnb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.iojbl.cn/Article/details/gtjfrsmupl.html

C#:   static void Main(string[] args)
来源：http://dali.nwbrower.top/Article/details/gtwgkzxgcn.html

[M08] 获取系统与运行时信息
来源：http://dali.havefunace.top/Article/details/gtxpxbvozx.html

Py:   platform.system();  platform.python_version()
来源：http://dali.haohaochexian.top/Article/details/gtvvmjwbgy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinghuilouyu.cn/Article/details/gtailantpx.html

JS:   process.platform;  process.version
来源：http://dali.yj20258.top/Article/details/gtislllmio.html

TS:   process.platform;  process.version
来源：http://dali.bjfxy.top/Article/details/gtpptzmrqy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cucudq.cn/Article/details/gtsgwbksdx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cheryme.top/Article/details/gtqavdqaem.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gzhubu.top/Article/details/gtoemhugmq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hammf.cn/Article/details/gthzooclhs.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtiuaguegf.html

N. 数据结构与算法
来源：http://dali.wangshuangyany.cn/Article/details/gtiyuxwowb.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gthywjvlie.html


<!-- 参考信息 -->