代发 wailian999

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.316326.xyz/Article/details/gtxdemsbuy.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhijiandao.cn/Article/details/gttisqflwz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuanzhike.top/Article/details/gtqvubotcc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhixingplan.top/Article/details/gtqhydsplz.html

[J03] 字符串解析为日期
来源：http://dali.xinyue.icu/Article/details/gtvbtvceyg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinqigfzy.top/Article/details/gtgvsdrtod.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nanxuanxn.top/Article/details/gtblggvojs.html

JS:   new Date("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gteehkrjoh.html

TS:   new Date("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gteuxpkmaw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gtpzjxuwsb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzxsqriic.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gtcfiumaed.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yj20258888.top/Article/details/gtoauosmin.html

[J04] 时间戳与日期互转
来源：http://dali.mhx1999.top/Article/details/gtciiwhopt.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ehwqpu.com/Article/details/gtwgcfkwof.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.fzhhl.top/Article/details/gtolhyrisd.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinqigufen.top/Article/details/gtgzugyerb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.aizwys.cn/Article/details/gtmamcmctt.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yj20258.top/Article/details/gtyrfxfhfo.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yj20258888.top/Article/details/gtqisojdyt.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yueranfly.top/Article/details/gtucxugrpd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gaohongyu789.top/Article/details/gttomnicse.html

[J05] 时间加减（加 7 天）
来源：http://dali.jqgufenzy.top/Article/details/gtnmkxvlig.html

Py:   now + timedelta(days=7)
来源：http://dali.quarkkingdee.top/Article/details/gtgxhasdyu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jqgufenzy.top/Article/details/gtayzgbhku.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxptbomdm.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuanzx.com/Article/details/gtctlkbpqm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hywenlv.cn/Article/details/gthhtdubwh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.bjfxy.top/Article/details/gtvylwxcxz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gaohongyu789.top/Article/details/gttkwgztdu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.havefunace.top/Article/details/gtsbozzzpo.html

[J06] 计算两时间之差
来源：http://dali.yuanzhike.top/Article/details/gtucwnfifg.html

Py:   (end - start).total_seconds()
来源：http://dali.gotoacloud.top/Article/details/gtfzvkzsrb.html

PHP:  $end->diff($start)->days;
来源：http://dali.shzxlz.cn/Article/details/gttyieaupc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hywenlv.cn/Article/details/gttwvdcehg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.fzhhl.top/Article/details/gtkijnlfds.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhongyouzk.top/Article/details/gttnwraift.html

Go:   end.Sub(start).Hours()
来源：http://dali.xziqi.cn/Article/details/gtknzbqodj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.haohaochexian.top/Article/details/gtvyznmyhd.html

C#:   (end - start).TotalSeconds
来源：http://dali.cheryme.top/Article/details/gtiwecuowt.html

[J07] 比较两个日期
来源：http://dali.aibaodan.cn/Article/details/gtlskcqnqi.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.pycfn.com/Article/details/gtxqexpcjp.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinghuilouyu.cn/Article/details/gtkmrzdtgp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sysykeji.top/Article/details/gtucfwessc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.daria6918.cn/Article/details/gtcdaryavz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.bjfxy.top/Article/details/gtxkwgfrhr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.fengsongda.top/Article/details/gtxvmabssv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.mhx1999.top/Article/details/gtdlizofvf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gtwstybiiv.html

[J08] 提取年月日与星期
来源：http://dali.zhixingplan.top/Article/details/gtxhsnsrcq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.nwbrower.top/Article/details/gtolyfrapm.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.havefunace.top/Article/details/gtgopogqga.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.svipenyu.cn/Article/details/gtrbxhwzti.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hongshengwenyu.top/Article/details/gtcgdszkim.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinghuilouyu.cn/Article/details/gtouudskbo.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhongyouzk.top/Article/details/gtkautcyxj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xuetiantiany.cn/Article/details/gtaicngyli.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yuxming.cn/Article/details/gtgulbhuki.html

[J09] 时区处理
来源：http://dali.guannengcc.top/Article/details/gttfpmcdes.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.meibo888.top/Article/details/gtzayywvxa.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.havefunace.top/Article/details/gtfqssfbst.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nwbrower.top/Article/details/gtxqvgohfl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aizwys.cn/Article/details/gtptxszdsv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.aizwys.cn/Article/details/gtogofcybe.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.nanxinkj.top/Article/details/gtoqukbswf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hnqzz.top/Article/details/gtamiarvev.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.fengsongda.top/Article/details/gtlzzomuyu.html

[J10] 取今天 / 本月第一天
来源：http://dali.havefunace.top/Article/details/gtgvfykxrl.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yueranfly.top/Article/details/gtqrhjvezj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gzhubu.top/Article/details/gtpmcqnlnh.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.316326.xyz/Article/details/gtnwfjfbvp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj20258888.top/Article/details/gtymtnjwhj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.meibo888.top/Article/details/gtlwfutitl.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.c1oappe.top/Article/details/gtgzboxdjc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.kuanghao11.cn/Article/details/gtfylgxeqr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ehwqpu.com/Article/details/gtnvpplyan.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtmduahcyj.html

K. JSON 与序列化
来源：http://dali.shuidangran.top/Article/details/gtfixdeoqo.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtpmpbmllp.html

[K01] 对象转 JSON 字符串
来源：http://dali.ydzc1.top/Article/details/gtxipjkxbo.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinqigufen.top/Article/details/gtifiysxxw.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.fzhhl.top/Article/details/gthkwssreo.html

JS:   JSON.stringify(obj)
来源：http://dali.havefunace.top/Article/details/gtaunejhgb.html

TS:   JSON.stringify(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtoibrqxia.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.guowangkeji.top/Article/details/gtuxsiyafz.html

Go:   json.Marshal(obj)
来源：http://dali.zhixingplan.top/Article/details/gtogdkxedw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yj20258888.top/Article/details/gtyfydbxci.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hysaishi.cn/Article/details/gtcvacsbbw.html

[K02] JSON 字符串转对象
来源：http://dali.zhijiandao.cn/Article/details/gtytmhlhgq.html

Py:   json.loads(s)
来源：http://dali.yueranfly.top/Article/details/gtoahbdknz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yonumen.top/Article/details/gtvcsqrofk.html

JS:   JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gtygszsweh.html

TS:   JSON.parse(s)
来源：http://dali.andypj.xyz/Article/details/gtoutvdnpj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.0kj1m.cn/Article/details/gtikdgxcju.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xinyue.icu/Article/details/gtcblkdurr.html

Ruby: JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gtxzcntvam.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hnqzz.top/Article/details/gtklkwqzps.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.smart0.xyz/Article/details/gtiynlvofx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cdnleiting.top/Article/details/gthnjoiykw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.quarkkingdee.top/Article/details/gtxmchnpma.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.redwolf501.top/Article/details/gtudmniioq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.316326.xyz/Article/details/gtsznfqtsw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtarlduuud.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.smart0.xyz/Article/details/gtvdstvocm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sufxvd.cn/Article/details/gtnrqmjcwd.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.iojbl.cn/Article/details/gtoitihkhl.html

[K04] 读取 JSON 文件
来源：http://dali.yj20258.top/Article/details/gtpzgellai.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shuidangran.top/Article/details/gtxwglxwxx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.wangshuangyany.cn/Article/details/gtrqqgneql.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.kuanghao11.cn/Article/details/gtsyeprexo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sweek.top/Article/details/gtmwwddiuw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.chenlongwang.top/Article/details/gtvzuktejg.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.nanxuanxn.top/Article/details/gtynaglkny.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sweek.top/Article/details/gtbmyvlkqb.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cheryme.top/Article/details/gtmscmqjrs.html

[K05] 深拷贝对象
来源：http://dali.chenzaomai.com/Article/details/gtqwkgoopl.html

Py:   copy.deepcopy(obj)
来源：http://dali.xuanzx.com/Article/details/gtqfcgjhiq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.316326.xyz/Article/details/gtefqxcope.html

JS:   structuredClone(obj)
来源：http://dali.hammf.cn/Article/details/gtvebgvjyj.html

TS:   structuredClone(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwiqcetaa.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xziqi.cn/Article/details/gtiyfcabwj.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhixingplan.top/Article/details/gtgllidwuj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ivvv.top/Article/details/gtsihzvohb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xinyue.icu/Article/details/gtgoephexw.html

[K06] 解析 URL 查询串
来源：http://dali.sufxvd.cn/Article/details/gtzishxfev.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xylfe.cn/Article/details/gtftkiauqc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.meibo888.top/Article/details/gtjdwemsxz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gzhubu.top/Article/details/gtqetuvekg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yongpay.top/Article/details/gtgsrsmrmq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.meibo888.top/Article/details/gtyhymliqm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhaomingkeji.xyz/Article/details/gttbqxevgg.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.redwolf501.top/Article/details/gtayutzzxo.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ppjwa.cn/Article/details/gtuyvaubgj.html

[K07] 进制转换
来源：http://dali.tianlin.xyz/Article/details/gtmmfukkyc.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gtphlisueo.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinqigfzy.top/Article/details/gtkxduwxkg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbdleflug.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gtyhqwrpta.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gtmosuqtoc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.dianchejie.cn/Article/details/gtqwyirtzf.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hfpthk.cn/Article/details/gtxexybfal.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtirqpyhhl.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.bjfxy.top/Article/details/gtdewezner.html

Py:   pickle.dumps(obj)
来源：http://dali.xinyue.icu/Article/details/gtimeqfnve.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtcatmobfs.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.haohaochexian.top/Article/details/gtszcytzmy.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shangyingyoupin.top/Article/details/gtfuzbchrf.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.tian-w.cn/Article/details/gtrqhzjyie.html

Go:   encoding/gob
来源：http://dali.iojbl.cn/Article/details/gtbghxspkm.html

Ruby: Marshal.dump(obj)
来源：http://dali.wangdashe.top/Article/details/gtzzlxihrp.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.bjfxy.top/Article/details/gtfchmhuws.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtimqkdjpu.html

L. 网络请求
来源：http://dali.0kj1m.cn/Article/details/gtyetfqibh.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtnaztmtxb.html

[L01] 发送 GET 请求
来源：http://dali.shuidangran.top/Article/details/gttnvrqdnm.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnhhjjxiy.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.fengsongda.top/Article/details/gtpuxxsgkb.html

JS:   await fetch(url)
来源：http://dali.meibo888.top/Article/details/gtjmqsjzsx.html

TS:   await fetch(url)
来源：http://dali.fzhhl.top/Article/details/gtymdbhehs.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gaohongyu789.top/Article/details/gtblbwvtcz.html

Go:   resp, err := http.Get(url)
来源：http://dali.sxryk.cn/Article/details/gtlbhdhxra.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shuidangran.top/Article/details/gtbgluygfx.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shuidangran.top/Article/details/gtgdyqrcdt.html

[L02] 发送 POST JSON
来源：http://dali.pycfn.com/Article/details/gthffsutyd.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jqgfzy.top/Article/details/gtgtuzylnh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.0kj1m.cn/Article/details/gtnhyicewo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuanzhike.top/Article/details/gteqevsycy.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gzhubu.top/Article/details/gteabiwpbe.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenjidiqi.icu/Article/details/gthhunlzzy.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.pycfn.com/Article/details/gtohyasuuq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.feifeiyinyue.top/Article/details/gtfudnousc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jqgufenzy.top/Article/details/gtigusqcfc.html

[L03] 设置自定义请求头
来源：http://dali.hysaishi.cn/Article/details/gtkjphhmfx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.fzhhl.top/Article/details/gtqibptsei.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.nanxuanxn.top/Article/details/gtgguphynm.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ydzc1.top/Article/details/gtqokkmifs.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.redwolf501.top/Article/details/gtbzizqpjy.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.dianchejie.cn/Article/details/gtveraqhhw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.316326.xyz/Article/details/gtbkyyoshb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.svipenyu.cn/Article/details/gtkkyjmfyr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gogol.net.cn/Article/details/gttujutdiu.html

[L04] 设置超时
来源：http://dali.chenlongwang.top/Article/details/gtclcxzhts.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gtmeaguuze.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shangyingyoupin.top/Article/details/gtrcfxjncl.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfbqdxmxg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.0kj1m.cn/Article/details/gtaehawepp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.pycfn.com/Article/details/gtqqmrdhob.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cucudq.cn/Article/details/gtfmcglpos.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.fzhhl.top/Article/details/gtshtxudjy.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jqgfzy.top/Article/details/gtunuvnieh.html

[L05] 上传文件（multipart）
来源：http://dali.yanxiufei.cn/Article/details/gthjihwopb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.birdmap.top/Article/details/gtvtbaunop.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jyoumei.cn/Article/details/gtnebmfeho.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.aibaodan.cn/Article/details/gtruiaxzzq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ppjwa.cn/Article/details/gtamtcpejz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shanyushiyangtech.top/Article/details/gtycgsphal.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jiagoushi.top/Article/details/gtaxzpuxft.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.mhx1999.top/Article/details/gtxvvethuw.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.meibo888.top/Article/details/gtwlyxdbki.html

[L06] 解析响应为 JSON
来源：http://dali.jqgfzy.top/Article/details/gtdrfvnuyx.html

Py:   resp.json()
来源：http://dali.shangyingyoupin.top/Article/details/gttevbhbpi.html

PHP:  json_decode($body, true);
来源：http://dali.yj20258888.top/Article/details/gtjethzeix.html

JS:   await resp.json()
来源：http://dali.yj20258888.top/Article/details/gtknnjkfna.html

TS:   await resp.json()
来源：http://dali.shuidangran.top/Article/details/gtnunviarr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xinyue.icu/Article/details/gtsooalkjv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.bjfxy.top/Article/details/gtiscavixl.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinqigufen.top/Article/details/gtjhmaoezl.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yongpay.top/Article/details/gthubsatln.html

[L07] 处理 HTTP 状态码
来源：http://dali.hnxiangtu.top/Article/details/gtmokbkmgi.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.aizwys.cn/Article/details/gtbewuvmze.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hysaishi.cn/Article/details/gtvbjynuab.html

JS:   resp.ok;  resp.status
来源：http://dali.yonumen.top/Article/details/gtnkmgflqj.html

TS:   resp.ok;  resp.status
来源：http://dali.yj20258.top/Article/details/gtkhxcwkwu.html

Java: resp.statusCode()
来源：http://dali.shanyushiyangtech.top/Article/details/gtokmsirxj.html

Go:   resp.StatusCode
来源：http://dali.fengsongda.top/Article/details/gtrhqkspgi.html

Ruby: resp.code.to_i
来源：http://dali.jyoumei.cn/Article/details/gtgigjazla.html

C#:   (int)resp.StatusCode
来源：http://dali.shzxlz.cn/Article/details/gtxcgqnyad.html

[L08] 并发请求多个地址
来源：http://dali.xuanzx.com/Article/details/gtqfsuecbe.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jinqigufen.top/Article/details/gtnzxflane.html

PHP:  curl_multi_init() 系列
来源：http://dali.cheryme.top/Article/details/gthqymgoga.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.0kj1m.cn/Article/details/gtaeyxhskm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guannengcc.top/Article/details/gtwagjzvzf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.chenlongwang.top/Article/details/gtuxficduv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.tian-w.cn/Article/details/gtzsprqxad.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.vqdsnc.cn/Article/details/gtggcsxpxq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jqgfzy.top/Article/details/gtvuftqfsj.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtblpdudku.html

M. 命令行 / 进程 / 环境
来源：http://dali.sysykeji.top/Article/details/gtqzihrkmo.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlssdpmjs.html

[M01] 读取命令行参数
来源：http://dali.tanke756.top/Article/details/gtwsxhvjhg.html

Py:   sys.argv[1:]
来源：http://dali.yj20258888.top/Article/details/gttaltyvwk.html

PHP:  $argv;  $argc;
来源：http://dali.daria6918.cn/Article/details/gtnejjoimr.html

JS:   process.argv.slice(2)
来源：http://dali.haohaochexian.top/Article/details/gtgiatacbr.html

TS:   process.argv.slice(2)
来源：http://dali.vqdsnc.cn/Article/details/gtobtcntbu.html

Java: args 数组（main 方法参数）
来源：http://dali.yj20258888.top/Article/details/gtrrstbxmg.html

Go:   os.Args[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtanzqidgx.html

Ruby: ARGV
来源：http://dali.meibo888.top/Article/details/gtfxdxfene.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yvedp.cn/Article/details/gtncaynyyt.html

[M02] 读取环境变量
来源：http://dali.yonumen.top/Article/details/gtjowecbpt.html

Py:   os.environ.get("HOME")
来源：http://dali.0kj1m.cn/Article/details/gtqjrgdsuw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xziqi.cn/Article/details/gtxjnlweer.html

JS:   process.env.HOME
来源：http://dali.jinqigfzy.top/Article/details/gtsmfiyzjp.html

TS:   process.env.HOME
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgrxxkjgq.html

Java: System.getenv("HOME")
来源：http://dali.jianghu66.top/Article/details/gtbgjydyha.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.daria6918.cn/Article/details/gtfqjfanod.html

Ruby: ENV["HOME"]
来源：http://dali.mhx1999.top/Article/details/gtdzxpdxee.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.guannengcc.top/Article/details/gtrosmaoaf.html

[M03] 执行外部命令
来源：http://dali.nanxuanxn.top/Article/details/gtjyxxlpdy.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtabaagtuy.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj20258.top/Article/details/gtjlwtpkpl.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgufenzy.top/Article/details/gtlmwrkhwz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xinyue.icu/Article/details/gtvemsdfcb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.dashuyun.cn/Article/details/gtxmavsqme.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ppjwa.cn/Article/details/gtydepjkut.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cdnleiting.top/Article/details/gtxcdjhche.html

C#:   Process.Start("ls", "-l");
来源：http://dali.daria6918.cn/Article/details/gtttqyksas.html

[M04] 获取当前工作目录
来源：http://dali.bjfxy.top/Article/details/gtfqxyewth.html

Py:   os.getcwd()
来源：http://dali.zhongyouzk.top/Article/details/gtujwzzcjq.html

PHP:  getcwd();
来源：http://dali.tanke756.top/Article/details/gtpknwbyyg.html

JS:   process.cwd()
来源：http://dali.pengpengdd.cyou/Article/details/gtpkccyuof.html

TS:   process.cwd()
来源：http://dali.shangyingyoupin.top/Article/details/gtflerusus.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cucudq.cn/Article/details/gtsmaynlxs.html

Go:   os.Getwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtznvmzvlr.html

Ruby: Dir.pwd
来源：http://dali.meibo888.top/Article/details/gtapopzflb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.fengsongda.top/Article/details/gtuvsxrqhk.html

[M05] 设置退出码
来源：http://dali.andypj.xyz/Article/details/gtshfmaeou.html

Py:   sys.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gtyjwdfiuz.html

PHP:  exit(1);
来源：http://dali.vqdsnc.cn/Article/details/gtkrnthcxj.html

JS:   process.exit(1)
来源：http://dali.wangdashe.top/Article/details/gtubrrmbvn.html

TS:   process.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gtyvkyrosh.html

Java: System.exit(1)
来源：http://dali.xylfe.cn/Article/details/gttdypgafm.html

Go:   os.Exit(1)
来源：http://dali.aizwys.cn/Article/details/gtnlqviqyn.html

Ruby: exit 1
来源：http://dali.sweek.top/Article/details/gtggyjhafs.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sufxvd.cn/Article/details/gtfttxdvsp.html

[M06] 向标准错误输出
来源：http://dali.cdnleiting.top/Article/details/gtviurgsvc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.chenzaomai.com/Article/details/gtvsxjinyp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yonumen.top/Article/details/gtwmylluhz.html

JS:   console.error("err")
来源：http://dali.yongpay.top/Article/details/gtanxxpmwn.html

TS:   console.error("err")
来源：http://dali.jinqigufen.top/Article/details/gtovbzntqa.html

Java: System.err.println("err")
来源：http://dali.xinyue.icu/Article/details/gtqmqbqsiz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.c1oappe.top/Article/details/gtksjmzmse.html

Ruby: warn "err"
来源：http://dali.xylfe.cn/Article/details/gtndlgomkr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.dianchejie.cn/Article/details/gtxqtvsomj.html

[M07] 判断是否为主入口
来源：http://dali.wangshuangyany.cn/Article/details/gtjqybpyxi.html

Py:   if __name__ == "__main__":
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgqlfdvao.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gaohongyu789.top/Article/details/gtcpdkfqbx.html

JS:   require.main === module
来源：http://dali.yanxiufei.cn/Article/details/gtbalrtrey.html

TS:   require.main === module
来源：http://dali.yj202588.top/Article/details/gtsxujlpol.html

Java: public static void main(String[] args)
来源：http://dali.daria6918.cn/Article/details/gtquwwbcbq.html

Go:   func main()
来源：http://dali.vqdsnc.cn/Article/details/gtzetdogjt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ivvv.top/Article/details/gttqiwahif.html

C#:   static void Main(string[] args)
来源：http://dali.pycfn.com/Article/details/gtzuzbauqh.html

[M08] 获取系统与运行时信息
来源：http://dali.hongshengwenyu.top/Article/details/gtqtbfnfcy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrwxfidci.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinqigufen.top/Article/details/gtehssfqxi.html

JS:   process.platform;  process.version
来源：http://dali.chenlongwang.top/Article/details/gtflzxaste.html

TS:   process.platform;  process.version
来源：http://dali.xinyue.icu/Article/details/gtqgswvxsk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yj20258888.top/Article/details/gtkhrznpot.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gotoacloud.top/Article/details/gtbtfkqswq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jqgufenzy.top/Article/details/gtjzpyvdbb.html


<!-- 参考信息 -->