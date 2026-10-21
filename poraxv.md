代发 wailian999

[J03] 字符串解析为日期
来源：http://dali.hnqzz.top/Article/details/gtgqvoemxs.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shzxlz.cn/Article/details/gtaxfurdfl.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcjvoilss.html

JS:   new Date("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gtunwtlsem.html

TS:   new Date("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gtlcrdofet.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gtnfyoihrr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gtqqparofj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gtlgayfkux.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cheryme.top/Article/details/gthpohmran.html

[J04] 时间戳与日期互转
来源：http://dali.gogol.net.cn/Article/details/gtsaejmptg.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.birdmap.top/Article/details/gtllpybwhu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yueranfly.top/Article/details/gtjkbvlaat.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.andypj.xyz/Article/details/gtnlpxaeuc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.pycfn.com/Article/details/gtuvucrkco.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ppjwa.cn/Article/details/gtpsfixbbu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.chenlongwang.top/Article/details/gtdjqcfhpm.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jinqigufen.top/Article/details/gtfqlxcbkq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.redwolf501.top/Article/details/gttpurywlr.html

[J05] 时间加减（加 7 天）
来源：http://dali.hnqzz.top/Article/details/gtgznjkdnp.html

Py:   now + timedelta(days=7)
来源：http://dali.ppjwa.cn/Article/details/gtrkxnclad.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.tianlin.xyz/Article/details/gtfcfxyemi.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cqqwz.cn/Article/details/gtuvczvroc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cdnleiting.top/Article/details/gthcsazlyu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.fzhhl.top/Article/details/gtohxfmcaq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.birdmap.top/Article/details/gtkydzhnmk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hywenlv.cn/Article/details/gthvhgapca.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xziqi.cn/Article/details/gtckvizlva.html

[J06] 计算两时间之差
来源：http://dali.hongshengwenyu.top/Article/details/gtgnvfagwb.html

Py:   (end - start).total_seconds()
来源：http://dali.cdnleiting.top/Article/details/gteochkskn.html

PHP:  $end->diff($start)->days;
来源：http://dali.316326.xyz/Article/details/gtelrktimx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gzhubu.top/Article/details/gtlqaotxmy.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.316326.xyz/Article/details/gtwfsakivt.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhengqikj.top/Article/details/gtxuufnwdj.html

Go:   end.Sub(start).Hours()
来源：http://dali.gogol.net.cn/Article/details/gtlhezyvhy.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cqqwz.cn/Article/details/gtwvjrofkt.html

C#:   (end - start).TotalSeconds
来源：http://dali.cucudq.cn/Article/details/gtiyrjpbca.html

[J07] 比较两个日期
来源：http://dali.fengsongda.top/Article/details/gtsufqsnmq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yj20258888.top/Article/details/gttavcdsku.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.aibaodan.cn/Article/details/gtsiqmunga.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.wangdashe.top/Article/details/gtwnbzwcyi.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhengqikj.top/Article/details/gtpcanllqj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.daxiang520.top/Article/details/gtqpqeynrf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cashguo.top/Article/details/gtfmtclhty.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtveiavziy.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gtasrpbdrs.html

[J08] 提取年月日与星期
来源：http://dali.jinqigfzy.top/Article/details/gtyoikiidd.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.c1oappe.top/Article/details/gtajcqbjro.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shuidangran.top/Article/details/gthtvwnnds.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jyoumei.cn/Article/details/gtwzrysamv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.dianchejie.cn/Article/details/gtuqpeqwyb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gzhubu.top/Article/details/gthmdrgfqf.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.nanxuanxn.top/Article/details/gtxlwxrqmp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jyoumei.cn/Article/details/gtvjkvbrsf.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yj202588.top/Article/details/gtiteojijf.html

[J09] 时区处理
来源：http://dali.gzhubu.top/Article/details/gtyxafbzgt.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.redwolf501.top/Article/details/gthlglihud.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.guowangkeji.top/Article/details/gtbbksllts.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.snrcjt.cn/Article/details/gtqmqbwesg.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenjidiqi.icu/Article/details/gtrdlttpsh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.andypj.xyz/Article/details/gttdrizhqs.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.svipenyu.cn/Article/details/gtbjhzcvgr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.wangdashe.top/Article/details/gtkxlodgfh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hfpthk.cn/Article/details/gtpznkljby.html

[J10] 取今天 / 本月第一天
来源：http://dali.aizwys.cn/Article/details/gtisxkttaa.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.c1oappe.top/Article/details/gtojtatcel.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.pycfn.com/Article/details/gtwdulqjiv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.svipenyu.cn/Article/details/gtuzxwasaa.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sweek.top/Article/details/gtrxzzzrxx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zycfv.cn/Article/details/gtiduwabiv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhiwuduotai.top/Article/details/gtfnuspkwu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.dashuyun.cn/Article/details/gtggmlagay.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cqqwz.cn/Article/details/gtttjcchcj.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtirrcpmlf.html

K. JSON 与序列化
来源：http://dali.aizwys.cn/Article/details/gtnpbwjujj.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtnvnleoft.html

[K01] 对象转 JSON 字符串
来源：http://dali.jlsjyb.cn/Article/details/gtaujatqya.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtackzvknm.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.c1oappe.top/Article/details/gtgktrfudq.html

JS:   JSON.stringify(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtqjbdsado.html

TS:   JSON.stringify(obj)
来源：http://dali.xziqi.cn/Article/details/gtkosnmdjl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shzxlz.cn/Article/details/gtshhpyiui.html

Go:   json.Marshal(obj)
来源：http://dali.dianchejie.cn/Article/details/gtzibufpbz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yuanzhike.top/Article/details/gtdspczpjj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xuanzx.com/Article/details/gtpvdaypqd.html

[K02] JSON 字符串转对象
来源：http://dali.daxiang520.top/Article/details/gtagrzrzgx.html

Py:   json.loads(s)
来源：http://dali.haohaochexian.top/Article/details/gtnczugjmv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tianlin.xyz/Article/details/gttmmlycpp.html

JS:   JSON.parse(s)
来源：http://dali.wangdashe.top/Article/details/gtvstcjyww.html

TS:   JSON.parse(s)
来源：http://dali.xinyue.icu/Article/details/gtzchsivup.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.fengsongda.top/Article/details/gtqyxyytyo.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.bjfxy.top/Article/details/gtkltbblbi.html

Ruby: JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gtwzuvenlx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtdmieusnj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gaohongyu789.top/Article/details/gtwmnfdpgf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.aizwys.cn/Article/details/gtxwhlyvxb.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.chenzaomai.com/Article/details/gtpuxhltle.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cqqwz.cn/Article/details/gtdfgqbuho.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.redwolf501.top/Article/details/gtwprqezca.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwybjctvz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.guannengcc.top/Article/details/gtdbyfaxum.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shuidangran.top/Article/details/gtkcmhxpen.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhoulong.xyz/Article/details/gtronzpmur.html

[K04] 读取 JSON 文件
来源：http://dali.xuetiantiany.cn/Article/details/gtqznrrccu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xinyue.icu/Article/details/gtoonnbplf.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shangyingyoupin.top/Article/details/gtmqiligcb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hammf.cn/Article/details/gtfjyvvgeo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xziqi.cn/Article/details/gtlgtampsa.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.fzhhl.top/Article/details/gtuuighhyw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.svipenyu.cn/Article/details/gtltuwunjq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yj20258888.top/Article/details/gtzcfvtome.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hnxiangtu.top/Article/details/gtkiouiybl.html

[K05] 深拷贝对象
来源：http://dali.yueranfly.top/Article/details/gtzlaphfhg.html

Py:   copy.deepcopy(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtdxaiutgq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xylfe.cn/Article/details/gtwphwktro.html

JS:   structuredClone(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmpxnesau.html

TS:   structuredClone(obj)
来源：http://dali.xziqi.cn/Article/details/gtkyyahchp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinghuilouyu.cn/Article/details/gthklkhfyx.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.dianchejie.cn/Article/details/gtdrxwbair.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.svipenyu.cn/Article/details/gtwywwnxcv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hnqzz.top/Article/details/gtjegumbdj.html

[K06] 解析 URL 查询串
来源：http://dali.nanxuanxn.top/Article/details/gtkppdausy.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cheryme.top/Article/details/gtdmewiaqw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.andypj.xyz/Article/details/gtjvebkrbq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnihfxyge.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daria6918.cn/Article/details/gtxdodlyzk.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jqgufenzy.top/Article/details/gtwjdedtwx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gtrokdpypj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinqigufen.top/Article/details/gtpiekohgc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yangfankeji.com/Article/details/gtxqngimjs.html

[K07] 进制转换
来源：http://dali.zhixingplan.top/Article/details/gtqzouxmuu.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gtgsnvjupt.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yj202588.top/Article/details/gtiqwnfkik.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gtefyzpnsu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gtkouvftuf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.sweek.top/Article/details/gtjlnqwibm.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yuanzhike.top/Article/details/gtpiolaqis.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.andypj.xyz/Article/details/gtjqupcxbq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gtskospnti.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.daria6918.cn/Article/details/gthcaobsnu.html

Py:   pickle.dumps(obj)
来源：http://dali.dashuyun.cn/Article/details/gtakgurdxn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yonumen.top/Article/details/gtxnuuoclv.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zycfv.cn/Article/details/gtrmuuejwa.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdyviaaal.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.dianchejie.cn/Article/details/gtvjfjporc.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gtxnkhvtnd.html

Ruby: Marshal.dump(obj)
来源：http://dali.daxiang520.top/Article/details/gtrhtrayxh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hysaishi.cn/Article/details/gtqpxpqynl.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtcqqbpdtf.html

L. 网络请求
来源：http://dali.hongshengwenyu.top/Article/details/gtvhfetjia.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtxlhjtwrm.html

[L01] 发送 GET 请求
来源：http://dali.ywan-chungtsiang.top/Article/details/gthbnzejdt.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.snrcjt.cn/Article/details/gtxabmtcub.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhengqikj.top/Article/details/gtevunntfh.html

JS:   await fetch(url)
来源：http://dali.gogol.net.cn/Article/details/gtucubibfx.html

TS:   await fetch(url)
来源：http://dali.nwbrower.top/Article/details/gtshtjpukk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hysaishi.cn/Article/details/gtslakdnkg.html

Go:   resp, err := http.Get(url)
来源：http://dali.hysaishi.cn/Article/details/gtenbkcbcc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shzxlz.cn/Article/details/gtmbsmotgp.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.chenlongwang.top/Article/details/gtboyckoef.html

[L02] 发送 POST JSON
来源：http://dali.cashguo.top/Article/details/gticcnlfvh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhengqikj.top/Article/details/gtplibauwr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.redwolf501.top/Article/details/gtypmjcapa.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.quarkkingdee.top/Article/details/gtezschwtz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.aizwys.cn/Article/details/gtkoyqdniz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shanyushiyangtech.top/Article/details/gtrnbqxizy.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xziqi.cn/Article/details/gteeatexdc.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gtkwjhigyb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jqgufenzy.top/Article/details/gtalfuyenu.html

[L03] 设置自定义请求头
来源：http://dali.xziqi.cn/Article/details/gtbhvzcgbh.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.316326.xyz/Article/details/gttbepulzv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cucudq.cn/Article/details/gtzqkzkanv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnqzz.top/Article/details/gtpvkrzhad.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.kuanghao11.cn/Article/details/gtwjmlagjw.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jqgfzy.top/Article/details/gtzxeqmzmu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ppjwa.cn/Article/details/gtbsuhpldg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shuidangran.top/Article/details/gtokxfxvrl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.svipenyu.cn/Article/details/gthvmcforq.html

[L04] 设置超时
来源：http://dali.quarkkingdee.top/Article/details/gtcljlsgnt.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yj20258888.top/Article/details/gtkesyomvi.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.feifeiyinyue.top/Article/details/gtjyuhxjkh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.andypj.xyz/Article/details/gtffdiezxn.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jyoumei.cn/Article/details/gtsobfzfln.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhengqikj.top/Article/details/gtsbzttzwe.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.aibaodan.cn/Article/details/gtsguizecs.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbrbxpvfe.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jqgfzy.top/Article/details/gtexvsjowi.html

[L05] 上传文件（multipart）
来源：http://dali.shzxlz.cn/Article/details/gtdktafmvp.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.dashuyun.cn/Article/details/gtealewiir.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jyoumei.cn/Article/details/gtajrnoyvk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.9152youxi.cn/Article/details/gtstxuvbxc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcgmaufkv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hnxiangtu.top/Article/details/gtxmcfahxd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.fengsongda.top/Article/details/gtgquhotrf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.pengpengdd.cyou/Article/details/gtttiaqhms.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.c1oappe.top/Article/details/gtobpczszn.html

[L06] 解析响应为 JSON
来源：http://dali.redwolf501.top/Article/details/gtvvcnuexn.html

Py:   resp.json()
来源：http://dali.tanke756.top/Article/details/gtgyaldohi.html

PHP:  json_decode($body, true);
来源：http://dali.zhongyouzk.top/Article/details/gtatzkdefo.html

JS:   await resp.json()
来源：http://dali.hnqzz.top/Article/details/gtjsrkievp.html

TS:   await resp.json()
来源：http://dali.dashuyun.cn/Article/details/gtbcalpypy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shanyushiyangkeji.top/Article/details/gteegzylub.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xziqi.cn/Article/details/gtkvxgmnpj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbbaysdxg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jqgufenzy.top/Article/details/gtcuzadrbu.html

[L07] 处理 HTTP 状态码
来源：http://dali.zycfv.cn/Article/details/gthikvhcxn.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ppjwa.cn/Article/details/gtmjinlhil.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yj20258888.top/Article/details/gtvrbejbat.html

JS:   resp.ok;  resp.status
来源：http://dali.ybcxt.top/Article/details/gtampkeiao.html

TS:   resp.ok;  resp.status
来源：http://dali.cheryme.top/Article/details/gtpuzeynjx.html

Java: resp.statusCode()
来源：http://dali.sufxvd.cn/Article/details/gtckopaylc.html

Go:   resp.StatusCode
来源：http://dali.xuetiantiany.cn/Article/details/gtjubxdiyr.html

Ruby: resp.code.to_i
来源：http://dali.jlsjyb.cn/Article/details/gtiermkqdi.html

C#:   (int)resp.StatusCode
来源：http://dali.tian-w.cn/Article/details/gtyfcrkplw.html

[L08] 并发请求多个地址
来源：http://dali.zhongyouzk.top/Article/details/gtdpxgmrbg.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.iojbl.cn/Article/details/gtkwfzthmb.html

PHP:  curl_multi_init() 系列
来源：http://dali.dianchejie.cn/Article/details/gteysyiwln.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenzaomai.com/Article/details/gtcksxbqrv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhengqikj.top/Article/details/gtcvwrwjpw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.tian-w.cn/Article/details/gtwufjgvby.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ehwqpu.com/Article/details/gtfszswacx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.mhx1999.top/Article/details/gtfitekuhy.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.c1oappe.top/Article/details/gtoavfwvmn.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtcgmizyct.html

M. 命令行 / 进程 / 环境
来源：http://dali.cheryme.top/Article/details/gtdjimnldd.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtonpfxcov.html

[M01] 读取命令行参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsprasdaq.html

Py:   sys.argv[1:]
来源：http://dali.pycfn.com/Article/details/gtuxrtrznq.html

PHP:  $argv;  $argc;
来源：http://dali.xinyue.icu/Article/details/gtpgmtadck.html

JS:   process.argv.slice(2)
来源：http://dali.hysaishi.cn/Article/details/gtifmzxmzy.html

TS:   process.argv.slice(2)
来源：http://dali.0kj1m.cn/Article/details/gtqnjsradz.html

Java: args 数组（main 方法参数）
来源：http://dali.yanxiufei.cn/Article/details/gtjqxasqka.html

Go:   os.Args[1:]
来源：http://dali.guannengcc.top/Article/details/gtahbpngvn.html

Ruby: ARGV
来源：http://dali.andypj.xyz/Article/details/gthtjodhfr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhixingplan.top/Article/details/gtzdpfvwjb.html

[M02] 读取环境变量
来源：http://dali.hammf.cn/Article/details/gtqaphrskr.html

Py:   os.environ.get("HOME")
来源：http://dali.shzxlz.cn/Article/details/gtlzyschwq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhoulong.xyz/Article/details/gtlaggszjv.html

JS:   process.env.HOME
来源：http://dali.cashguo.top/Article/details/gtgigmubhi.html

TS:   process.env.HOME
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzkezhwjm.html

Java: System.getenv("HOME")
来源：http://dali.xuanzx.com/Article/details/gtoeihyglz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.mhx1999.top/Article/details/gtrbfxanyf.html

Ruby: ENV["HOME"]
来源：http://dali.jyoumei.cn/Article/details/gtslzzhesq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.mhx1999.top/Article/details/gtoqcosguw.html

[M03] 执行外部命令
来源：http://dali.jyoumei.cn/Article/details/gtgkdsiywx.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.quarkkingdee.top/Article/details/gtebfacioc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinqigufen.top/Article/details/gtwzeguohk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.316326.xyz/Article/details/gtzviqrcyx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.nwbrower.top/Article/details/gtwaixzgie.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yongpay.top/Article/details/gtohjpwovz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gaohongyu789.top/Article/details/gthyulnwbx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.haohaochexian.top/Article/details/gtoxakqypl.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yongpay.top/Article/details/gtimnvtgta.html

[M04] 获取当前工作目录
来源：http://dali.yangfankeji.com/Article/details/gtqebzjjsb.html

Py:   os.getcwd()
来源：http://dali.yueranfly.top/Article/details/gttakgzbsy.html

PHP:  getcwd();
来源：http://dali.sysykeji.top/Article/details/gtpaoadilv.html

JS:   process.cwd()
来源：http://dali.sweek.top/Article/details/gtrvzuydke.html

TS:   process.cwd()
来源：http://dali.zhengqikj.top/Article/details/gtkgbrtdvf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.snrcjt.cn/Article/details/gtbblncfbv.html

Go:   os.Getwd()
来源：http://dali.ybcxt.top/Article/details/gtjwepdayp.html

Ruby: Dir.pwd
来源：http://dali.hywenlv.cn/Article/details/gtxrjimabn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sxryk.cn/Article/details/gtbdjncbdf.html

[M05] 设置退出码
来源：http://dali.jlsjyb.cn/Article/details/gtgeyespzv.html

Py:   sys.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtysmulwxm.html

PHP:  exit(1);
来源：http://dali.xylfe.cn/Article/details/gtjlepimjs.html

JS:   process.exit(1)
来源：http://dali.wangdashe.top/Article/details/gtuydadghg.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtoswuhrvh.html

Java: System.exit(1)
来源：http://dali.zycfv.cn/Article/details/gtoqhkssxb.html

Go:   os.Exit(1)
来源：http://dali.tian-w.cn/Article/details/gtgqmwtglv.html

Ruby: exit 1
来源：http://dali.pycfn.com/Article/details/gttvlenohr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.birdmap.top/Article/details/gtuzqkjjuo.html

[M06] 向标准错误输出
来源：http://dali.wangshuangyany.cn/Article/details/gtbeqzsvkb.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtafhdvgsa.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shuidangran.top/Article/details/gthdhdggri.html

JS:   console.error("err")
来源：http://dali.tianlin.xyz/Article/details/gtxwwmwdab.html

TS:   console.error("err")
来源：http://dali.wangdashe.top/Article/details/gttokeixne.html

Java: System.err.println("err")
来源：http://dali.zhengqikj.top/Article/details/gtayibazle.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xuetiantiany.cn/Article/details/gtcijenfvx.html

Ruby: warn "err"
来源：http://dali.jyoumei.cn/Article/details/gtfysrcowg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.316326.xyz/Article/details/gtemuoczkk.html

[M07] 判断是否为主入口
来源：http://dali.nwbrower.top/Article/details/gtpnducwzi.html

Py:   if __name__ == "__main__":
来源：http://dali.xylfe.cn/Article/details/gtzurejnig.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ehwqpu.com/Article/details/gttmsbrnbj.html

JS:   require.main === module
来源：http://dali.guannengcc.top/Article/details/gtrhfaitep.html

TS:   require.main === module
来源：http://dali.bjfxy.top/Article/details/gtodzxdyhs.html

Java: public static void main(String[] args)
来源：http://dali.cdnleiting.top/Article/details/gtdsppcdaa.html

Go:   func main()
来源：http://dali.yonumen.top/Article/details/gtmenlhivd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhongyouzk.top/Article/details/gtsohimecn.html

C#:   static void Main(string[] args)
来源：http://dali.nanxinkj.top/Article/details/gtajtrsncv.html

[M08] 获取系统与运行时信息
来源：http://dali.hnxiangtu.top/Article/details/gtgbcznhvl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hnqzz.top/Article/details/gtdcvcjpar.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jqgfzy.top/Article/details/gtbcjlcaxk.html

JS:   process.platform;  process.version
来源：http://dali.iojbl.cn/Article/details/gtpbjjrqdu.html

TS:   process.platform;  process.version
来源：http://dali.feifeiyinyue.top/Article/details/gtbsutuswo.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ppjwa.cn/Article/details/gtticskcyb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hnxiangtu.top/Article/details/gttourghpu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.c1oappe.top/Article/details/gtluaxsqac.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.feifeiyinyue.top/Article/details/gtxnsnvzer.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtbibxnuyr.html

N. 数据结构与算法
来源：http://dali.fengsongda.top/Article/details/gtqxsyxotb.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtukscfkxs.html


<!-- 参考信息 -->