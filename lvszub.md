代发 wailian999

[J03] 字符串解析为日期
来源：http://dali.jqgfzy.top/Article/details/gt2uzodipkn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.pycfn.com/Article/details/gt2pmshhqcg.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.smart0.xyz/Article/details/gt2ehhnwdwp.html

JS:   new Date("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gt2emuefpzf.html

TS:   new Date("2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gt2xzvcqgvj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gt2ovglegnq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yongpay.top/Article/details/gt2jxbhutbw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gt2veokryjs.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ybcxt.top/Article/details/gt2bxzafmpc.html

[J04] 时间戳与日期互转
来源：http://dali.c1oappe.top/Article/details/gt2dphfnvlg.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ehwqpu.com/Article/details/gt2vpyfcdwp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.daxiang520.top/Article/details/gt2ssgtulhp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.daxiang520.top/Article/details/gt2leyfgmlf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cdnleiting.top/Article/details/gt2tqwuenod.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xuanzx.com/Article/details/gt2iznhljxm.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.fzhhl.top/Article/details/gt2ultsmiqx.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.fengsongda.top/Article/details/gt2npedhwth.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hysaishi.cn/Article/details/gt2rjgubpeb.html

[J05] 时间加减（加 7 天）
来源：http://dali.zycfv.cn/Article/details/gt2trczqfgp.html

Py:   now + timedelta(days=7)
来源：http://dali.tianlin.xyz/Article/details/gt2jpqgikqk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhijiandao.cn/Article/details/gt2foyymvyx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenzaomai.com/Article/details/gt2kxmmlgqa.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhongyouzk.top/Article/details/gt2ftwwrgps.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yvedp.cn/Article/details/gt2ftztvbmd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.svipenyu.cn/Article/details/gt2fkefvyan.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sysykeji.top/Article/details/gt2cumejmqa.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jqgfzy.top/Article/details/gt2qahsatkc.html

[J06] 计算两时间之差
来源：http://dali.hongshengwenyu.top/Article/details/gt2nzgpesxj.html

Py:   (end - start).total_seconds()
来源：http://dali.quarkkingdee.top/Article/details/gt2thvnsqyf.html

PHP:  $end->diff($start)->days;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ducxbekf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wyvkuqez.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.aibaodan.cn/Article/details/gt2mtshonef.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.haohaochexian.top/Article/details/gt2xcqehmdk.html

Go:   end.Sub(start).Hours()
来源：http://dali.fzhhl.top/Article/details/gt2odwiqgrg.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hammf.cn/Article/details/gt2vznqqibi.html

C#:   (end - start).TotalSeconds
来源：http://dali.nwbrower.top/Article/details/gt2mdjtixfx.html

[J07] 比较两个日期
来源：http://dali.yanxiufei.cn/Article/details/gt2nerhxwvy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.aizwys.cn/Article/details/gt2uyrxksap.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhijiandao.cn/Article/details/gt2atwtpsoo.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenjidiqi.icu/Article/details/gt2jtiarsho.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.quarkkingdee.top/Article/details/gt2qwiteacg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hywenlv.cn/Article/details/gt2zrqyhrcy.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhengqikj.top/Article/details/gt2wejnpvnm.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jianghu66.top/Article/details/gt2dffbkplu.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.chenlongwang.top/Article/details/gt2pjulldxs.html

[J08] 提取年月日与星期
来源：http://dali.guowangkeji.top/Article/details/gt2lrwbvqmc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hongshengwenyu.top/Article/details/gt2aqyetsqv.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hammf.cn/Article/details/gt2fwrmazli.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yvedp.cn/Article/details/gt2gzifqvhk.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nanxuanxn.top/Article/details/gt2zfrszhvq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jyoumei.cn/Article/details/gt2wryhdgts.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.quarkkingdee.top/Article/details/gt2pypsbisi.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xinyue.icu/Article/details/gt2bcfkmvvo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cqqwz.cn/Article/details/gt2yvrvyssd.html

[J09] 时区处理
来源：http://dali.shangyingyoupin.top/Article/details/gt2mbawmbqa.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hfpthk.cn/Article/details/gt2ykfzhqkd.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.chenlongwang.top/Article/details/gt2pftczbid.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuanzx.com/Article/details/gt2pdfawhue.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258888.top/Article/details/gt2daclholg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhixingplan.top/Article/details/gt2wgdyxuyz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zaavvqos.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ynjsvmth.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.daxiang520.top/Article/details/gt2crgslibn.html

[J10] 取今天 / 本月第一天
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gteunklt.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cdnleiting.top/Article/details/gt2xjmueott.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.chenzaomai.com/Article/details/gt2yblkcfpu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zofqmupw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.aizwys.cn/Article/details/gt2epljwssv.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cucudq.cn/Article/details/gt2gwfhzpkm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jiagoushi.top/Article/details/gt2httdryqr.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.vqdsnc.cn/Article/details/gt2wxqhtywq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xkpusrru.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2nvrblldl.html

K. JSON 与序列化
来源：http://dali.zhongyouzk.top/Article/details/gt2nidaygzk.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2skircbss.html

[K01] 对象转 JSON 字符串
来源：http://dali.gzhubu.top/Article/details/gt2eqmxkdrt.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.aibaodan.cn/Article/details/gt2ydvetzlm.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zdqjudy.top/Article/details/gt2jdggkeae.html

JS:   JSON.stringify(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2ghtnboih.html

TS:   JSON.stringify(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2nppriolc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.snrcjt.cn/Article/details/gt2lnhikdwv.html

Go:   json.Marshal(obj)
来源：http://dali.ybcxt.top/Article/details/gt2wsrslbqq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xinyue.icu/Article/details/gt2joxufpix.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.meibo888.top/Article/details/gt2frmrcyia.html

[K02] JSON 字符串转对象
来源：http://dali.jqgfzy.top/Article/details/gt2jdkskzgx.html

Py:   json.loads(s)
来源：http://dali.aizwys.cn/Article/details/gt2jyawtscd.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.daria6918.cn/Article/details/gt2taqtcpyn.html

JS:   JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jtxdwfaj.html

TS:   JSON.parse(s)
来源：http://dali.jyoumei.cn/Article/details/gt2htjgoxtn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.dashuyun.cn/Article/details/gt2ekdkjgft.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cdnleiting.top/Article/details/gt2kdeyebsw.html

Ruby: JSON.parse(s)
来源：http://dali.9152youxi.cn/Article/details/gt2tewqijug.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2doijbpci.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hnxiangtu.top/Article/details/gt2rkphvzsi.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sysykeji.top/Article/details/gt2bdltsmrj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jppiieyr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuanzhike.top/Article/details/gt2cnxeqjks.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2dwqgckak.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yj20258888.top/Article/details/gt2xzijtvvz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.havefunace.top/Article/details/gt2theqflqm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2sodsqcoi.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hywenlv.cn/Article/details/gt2vevhwndj.html

[K04] 读取 JSON 文件
来源：http://dali.316326.xyz/Article/details/gt2oidmlvxn.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xuanzx.com/Article/details/gt2vfaikora.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.tian-w.cn/Article/details/gt2nqofwxhu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2rpnytewv.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258888.top/Article/details/gt2huakqzjk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gt2pxqoagou.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.daxiang520.top/Article/details/gt2pjxuqjyw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.tianlin.xyz/Article/details/gt2vixrqprt.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.dianchejie.cn/Article/details/gt2jlwlwvdc.html

[K05] 深拷贝对象
来源：http://dali.cdnleiting.top/Article/details/gt2aafeqerb.html

Py:   copy.deepcopy(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2xduxbqws.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jlsjyb.cn/Article/details/gt2xjybrcmg.html

JS:   structuredClone(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2rgnfcpxw.html

TS:   structuredClone(obj)
来源：http://dali.yj20258.top/Article/details/gt2wnlvvopf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhengqikj.top/Article/details/gt2yvbuvyyl.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gotoacloud.top/Article/details/gt2vykibudw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.aizwys.cn/Article/details/gt2lujcckmg.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hysaishi.cn/Article/details/gt2xmkcxgus.html

[K06] 解析 URL 查询串
来源：http://dali.ybcxt.top/Article/details/gt2bjsdzmfr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.nwbrower.top/Article/details/gt2ceqatxzm.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.pengpengdd.cyou/Article/details/gt2trzblppn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cdnleiting.top/Article/details/gt2nztvrqjm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hxtokjcx.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xuetiantiany.cn/Article/details/gt2qziwlkoh.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenzaomai.com/Article/details/gt2wnmeuihw.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gt2eimultyx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.quarkkingdee.top/Article/details/gt2xlnxewdf.html

[K07] 进制转换
来源：http://dali.haohaochexian.top/Article/details/gt2hqjxgmeh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gt2uowiwaao.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xinyue.icu/Article/details/gt2xrurngtz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gt2dpdafkup.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gt2szousaop.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gt2ommwyuwd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.nanxinkj.top/Article/details/gt2fyqlhakl.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xziqi.cn/Article/details/gt2gqpiyryj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gt2yxscygwg.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zradozld.html

Py:   pickle.dumps(obj)
来源：http://dali.fzhhl.top/Article/details/gt2izjuvwii.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cashguo.top/Article/details/gt2vwmwszqr.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.aibaodan.cn/Article/details/gt2ytxuzndn.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cdnleiting.top/Article/details/gt2mqvvirwy.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cashguo.top/Article/details/gt2bdynzilv.html

Go:   encoding/gob
来源：http://dali.chenlongwang.top/Article/details/gt2wquvikee.html

Ruby: Marshal.dump(obj)
来源：http://dali.xuanzx.com/Article/details/gt2affvrqdw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yuanzhike.top/Article/details/gt2dylxmhmr.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2szoupiqy.html

L. 网络请求
来源：http://dali.shangyingyoupin.top/Article/details/gt2eagshkzj.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2encnhgld.html

[L01] 发送 GET 请求
来源：http://dali.zycfv.cn/Article/details/gt2auepqacv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yj202588.top/Article/details/gt2vypryatw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nanxuanxn.top/Article/details/gt2pmkdpopx.html

JS:   await fetch(url)
来源：http://dali.guowangkeji.top/Article/details/gt2jlcgmbpx.html

TS:   await fetch(url)
来源：http://dali.zhoulong.xyz/Article/details/gt2znbnnrhr.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2lhaszohn.html

Go:   resp, err := http.Get(url)
来源：http://dali.yuanzhike.top/Article/details/gt2dgdhitfa.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.chenzaomai.com/Article/details/gt2geqeqxps.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sysykeji.top/Article/details/gt2cboimapx.html

[L02] 发送 POST JSON
来源：http://dali.yj20258.top/Article/details/gt2cdejxwpm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hnqzz.top/Article/details/gt2lsplcxjv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.quarkkingdee.top/Article/details/gt2ydcyhcdd.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.smart0.xyz/Article/details/gt2wwpdvjzk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hywenlv.cn/Article/details/gt2abkzldoq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.9152youxi.cn/Article/details/gt2vzcdvfzy.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.wangdashe.top/Article/details/gt2cowvqnmm.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shzxlz.cn/Article/details/gt2xeedmwcs.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2azpnlpam.html

[L03] 设置自定义请求头
来源：http://dali.yj20258888.top/Article/details/gt2vkojhqzj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xziqi.cn/Article/details/gt2lrnmmmsc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cdnleiting.top/Article/details/gt2ozjzavib.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhixingplan.top/Article/details/gt2psnmturs.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guannengcc.top/Article/details/gt2eyjrtbcg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jianghu66.top/Article/details/gt2cpivdgdk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.snrcjt.cn/Article/details/gt2mcymxkow.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.iojbl.cn/Article/details/gt2vdsvlmle.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yonumen.top/Article/details/gt2kxlvskbt.html

[L04] 设置超时
来源：http://dali.haohaochexian.top/Article/details/gt2xrswmacw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.nwbrower.top/Article/details/gt2nsfdnnxj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yanxiufei.cn/Article/details/gt2aebubhjy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258888.top/Article/details/gt2rhhlnxms.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ivvv.top/Article/details/gt2psjqsajk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhixingplan.top/Article/details/gt2kphsrvxx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.dianchejie.cn/Article/details/gt2jfcozemm.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.nwbrower.top/Article/details/gt2qrwgknht.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yuanzhike.top/Article/details/gt2zybygciv.html

[L05] 上传文件（multipart）
来源：http://dali.hywenlv.cn/Article/details/gt2fykleqhq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.birdmap.top/Article/details/gt2dmavglll.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yueranfly.top/Article/details/gt2mtodjlhy.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ujqecxvu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sxryk.cn/Article/details/gt2wwkfeydf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2mmonudvs.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhengqikj.top/Article/details/gt2fzvwjmmn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.birdmap.top/Article/details/gt2aegnjzcq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.meibo888.top/Article/details/gt2qcqqytas.html

[L06] 解析响应为 JSON
来源：http://dali.hysaishi.cn/Article/details/gt2qnhxqcvw.html

Py:   resp.json()
来源：http://dali.yj202588.top/Article/details/gt2fplbpita.html

PHP:  json_decode($body, true);
来源：http://dali.yangfankeji.com/Article/details/gt2tslvxcgy.html

JS:   await resp.json()
来源：http://dali.andypj.xyz/Article/details/gt2wjqwwzli.html

TS:   await resp.json()
来源：http://dali.birdmap.top/Article/details/gt2hiiiqtza.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gt2xkpxgiav.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hammf.cn/Article/details/gt2wgxadwfj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nwbrower.top/Article/details/gt2dkqtczbo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.9152youxi.cn/Article/details/gt2gskkciqe.html

[L07] 处理 HTTP 状态码
来源：http://dali.jlsjyb.cn/Article/details/gt2qammszfc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.bjfxy.top/Article/details/gt2alwswzau.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.daxiang520.top/Article/details/gt2uoacosqf.html

JS:   resp.ok;  resp.status
来源：http://dali.jyoumei.cn/Article/details/gt2hhdnaafh.html

TS:   resp.ok;  resp.status
来源：http://dali.0kj1m.cn/Article/details/gt2pdwevskn.html

Java: resp.statusCode()
来源：http://dali.hnqzz.top/Article/details/gt2avpnoexe.html

Go:   resp.StatusCode
来源：http://dali.sufxvd.cn/Article/details/gt2vsoeppdh.html

Ruby: resp.code.to_i
来源：http://dali.andypj.xyz/Article/details/gt2yrizkubu.html

C#:   (int)resp.StatusCode
来源：http://dali.pengpengdd.cyou/Article/details/gt2fzeqpedh.html

[L08] 并发请求多个地址
来源：http://dali.tian-w.cn/Article/details/gt2rqyfyxrj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shuidangran.top/Article/details/gt2fbfucssl.html

PHP:  curl_multi_init() 系列
来源：http://dali.xuetiantiany.cn/Article/details/gt2nnebdmun.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cdnleiting.top/Article/details/gt2ouqgezkc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pycfn.com/Article/details/gt2frglkdzx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shzxlz.cn/Article/details/gt2xiapsmpp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.c1oappe.top/Article/details/gt2qqphwbpp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ppjwa.cn/Article/details/gt2jsmzzcuo.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yueranfly.top/Article/details/gt2dazzsfzp.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2oogbmatp.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhongyouzk.top/Article/details/gt2bjnyweku.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2qqtcioiq.html

[M01] 读取命令行参数
来源：http://dali.redwolf501.top/Article/details/gt2bhhvblhz.html

Py:   sys.argv[1:]
来源：http://dali.yonumen.top/Article/details/gt2pzmuhrtl.html

PHP:  $argv;  $argc;
来源：http://dali.gogol.net.cn/Article/details/gt2rcdvkfqp.html

JS:   process.argv.slice(2)
来源：http://dali.nwbrower.top/Article/details/gt2fqxqpvde.html

TS:   process.argv.slice(2)
来源：http://dali.yuanzhike.top/Article/details/gt2mqsdirtj.html

Java: args 数组（main 方法参数）
来源：http://dali.hysaishi.cn/Article/details/gt2pqzlbbod.html

Go:   os.Args[1:]
来源：http://dali.zdqjudy.top/Article/details/gt2lhqzavjl.html

Ruby: ARGV
来源：http://dali.hnqzz.top/Article/details/gt2drhdzjdk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cqqwz.cn/Article/details/gt2obzbupda.html

[M02] 读取环境变量
来源：http://dali.jlsjyb.cn/Article/details/gt2hfsmobrf.html

Py:   os.environ.get("HOME")
来源：http://dali.ybcxt.top/Article/details/gt2qartynzz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cashguo.top/Article/details/gt2lbfudbhz.html

JS:   process.env.HOME
来源：http://dali.cucudq.cn/Article/details/gt2uvlnfwvj.html

TS:   process.env.HOME
来源：http://dali.iojbl.cn/Article/details/gt2vgdyjdjk.html

Java: System.getenv("HOME")
来源：http://dali.tianlin.xyz/Article/details/gt2yddvawvq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sxryk.cn/Article/details/gt2rajfvekn.html

Ruby: ENV["HOME"]
来源：http://dali.redwolf501.top/Article/details/gt2pvgetplz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.snrcjt.cn/Article/details/gt2fxpaesdu.html

[M03] 执行外部命令
来源：http://dali.fzhhl.top/Article/details/gt2dobmurtm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.guannengcc.top/Article/details/gt2mbetcxow.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uiuzcubh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fzqnjyjd.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.kuanghao11.cn/Article/details/gt2gydfcuic.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.tanke756.top/Article/details/gt2uqfsslnv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bcdzehzd.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cheryme.top/Article/details/gt2zcwinhna.html

C#:   Process.Start("ls", "-l");
来源：http://dali.snrcjt.cn/Article/details/gt2jgbpojvg.html

[M04] 获取当前工作目录
来源：http://dali.snrcjt.cn/Article/details/gt2ubnpfyrs.html

Py:   os.getcwd()
来源：http://dali.ybcxt.top/Article/details/gt2hodvgrjo.html

PHP:  getcwd();
来源：http://dali.hnqzz.top/Article/details/gt2kbtfqzsx.html

JS:   process.cwd()
来源：http://dali.vqdsnc.cn/Article/details/gt2dsgizgbj.html

TS:   process.cwd()
来源：http://dali.guowangkeji.top/Article/details/gt2xgivvvbl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yangfankeji.com/Article/details/gt2jqpwrepx.html

Go:   os.Getwd()
来源：http://dali.xuanzx.com/Article/details/gt2tgimecif.html

Ruby: Dir.pwd
来源：http://dali.cdnleiting.top/Article/details/gt2bqadupyl.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jianghu66.top/Article/details/gt2mhxjcywf.html

[M05] 设置退出码
来源：http://dali.zhengqikj.top/Article/details/gt2bvpmlgeu.html

Py:   sys.exit(1)
来源：http://dali.xylfe.cn/Article/details/gt2jyofwvca.html

PHP:  exit(1);
来源：http://dali.aizwys.cn/Article/details/gt2ykrbsgpm.html

JS:   process.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2ddhtjdmb.html

TS:   process.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2phyubhbv.html

Java: System.exit(1)
来源：http://dali.mhx1999.top/Article/details/gt2jgqnywbd.html

Go:   os.Exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sealeyfy.html

Ruby: exit 1
来源：http://dali.yueranfly.top/Article/details/gt2wxrxuvii.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinqigufen.top/Article/details/gt2gszqfeoi.html

[M06] 向标准错误输出
来源：http://dali.jyoumei.cn/Article/details/gt2pguuoqsb.html

Py:   print("err", file=sys.stderr)
来源：http://dali.chenzaomai.com/Article/details/gt2stxlhlis.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.redwolf501.top/Article/details/gt2esrjpoup.html

JS:   console.error("err")
来源：http://dali.jiagoushi.top/Article/details/gt2iyktzesa.html

TS:   console.error("err")
来源：http://dali.andypj.xyz/Article/details/gt2otaesian.html

Java: System.err.println("err")
来源：http://dali.ppjwa.cn/Article/details/gt2ukqlibxw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.nanxinkj.top/Article/details/gt2axjhwsup.html

Ruby: warn "err"
来源：http://dali.haohaochexian.top/Article/details/gt2uuxeoguc.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sxryk.cn/Article/details/gt2mzchzvzo.html

[M07] 判断是否为主入口
来源：http://dali.guowangkeji.top/Article/details/gt2kkvkkume.html

Py:   if __name__ == "__main__":
来源：http://dali.wangdashe.top/Article/details/gt2rjgzddzc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mftqaxty.html

JS:   require.main === module
来源：http://dali.hammf.cn/Article/details/gt2fyzxrsuc.html

TS:   require.main === module
来源：http://dali.c1oappe.top/Article/details/gt2yvasfgmm.html

Java: public static void main(String[] args)
来源：http://dali.daria6918.cn/Article/details/gt2nwivdtmr.html

Go:   func main()
来源：http://dali.c1oappe.top/Article/details/gt2yekrdyjj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zycfv.cn/Article/details/gt2jbsmmmgf.html

C#:   static void Main(string[] args)
来源：http://dali.hysaishi.cn/Article/details/gt2rncevuga.html

[M08] 获取系统与运行时信息
来源：http://dali.hfpthk.cn/Article/details/gt2mytjfome.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hnqzz.top/Article/details/gt2zyjegstl.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hnxiangtu.top/Article/details/gt2jwablozp.html

JS:   process.platform;  process.version
来源：http://dali.dianchejie.cn/Article/details/gt2pbgzltwd.html

TS:   process.platform;  process.version
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dqochqgn.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yuxming.cn/Article/details/gt2vbrvgtzy.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hywenlv.cn/Article/details/gt2wdciihvg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bylurewj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zdqjudy.top/Article/details/gt2wxqvvfip.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rprmuhak.html

N. 数据结构与算法
来源：http://dali.jlsjyb.cn/Article/details/gt2hddhnwit.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2xytdlqcj.html


<!-- 参考信息 -->