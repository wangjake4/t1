代发 wailian999

Go:   time.Now()
来源：http://dali.shangyingyoupin.top/Article/details/gtfktocwrq.html

Ruby: Time.now
来源：http://dali.nanxuanxn.top/Article/details/gtjdilbygk.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sysykeji.top/Article/details/gtsofgijwr.html

[J02] 格式化输出
来源：http://dali.0kj1m.cn/Article/details/gtfpplccce.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jiagoushi.top/Article/details/gtzvgrorfs.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gtmnporosv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xylfe.cn/Article/details/gttlwyalrp.html

TS:   d.toISOString()
来源：http://dali.gaohongyu789.top/Article/details/gtvakbptua.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.pengpengdd.cyou/Article/details/gtolnfqsiq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shuidangran.top/Article/details/gtqtzhgbhg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pengpengdd.cyou/Article/details/gtnkaaipjb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sxryk.cn/Article/details/gtzworazpf.html

[J03] 字符串解析为日期
来源：http://dali.redwolf501.top/Article/details/gtjjxhtznb.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtabakznhc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gaohongyu789.top/Article/details/gtdwkimyuf.html

JS:   new Date("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gtzdfetcwi.html

TS:   new Date("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gtcupjwyhu.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdjcujfjj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gtrmqtnfdn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gteyglxedw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.birdmap.top/Article/details/gtfreojgsm.html

[J04] 时间戳与日期互转
来源：http://dali.gogol.net.cn/Article/details/gtrdkmvkoz.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.smart0.xyz/Article/details/gtashmwnkj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jqgufenzy.top/Article/details/gtyjpzchkq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiiotiuoe.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtezghsduj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gtsloldkya.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yj20258.top/Article/details/gtbansfiod.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.9152youxi.cn/Article/details/gtbcrpzhbm.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.bjfxy.top/Article/details/gtgcjwwyvs.html

[J05] 时间加减（加 7 天）
来源：http://dali.jqgufenzy.top/Article/details/gtgbuajhxi.html

Py:   now + timedelta(days=7)
来源：http://dali.guannengcc.top/Article/details/gttiynyhfu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.svipenyu.cn/Article/details/gtmxuwvwhv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.snrcjt.cn/Article/details/gtmdmkokxp.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.quarkkingdee.top/Article/details/gtalhfdals.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.wangdashe.top/Article/details/gtmdnlgomt.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cqqwz.cn/Article/details/gtvomumidr.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yj20258.top/Article/details/gtelxqshps.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdrfshagy.html

[J06] 计算两时间之差
来源：http://dali.ppjwa.cn/Article/details/gtsyfdsfbi.html

Py:   (end - start).total_seconds()
来源：http://dali.haohaochexian.top/Article/details/gtwecnavvc.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenjidiqi.icu/Article/details/gtoicocxkc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.daria6918.cn/Article/details/gtxownellb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xuetiantiany.cn/Article/details/gtgkayquli.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.chenzaomai.com/Article/details/gtqopjhbfr.html

Go:   end.Sub(start).Hours()
来源：http://dali.cucudq.cn/Article/details/gtztxxexju.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hfpthk.cn/Article/details/gtjvxjbgpt.html

C#:   (end - start).TotalSeconds
来源：http://dali.zdqjudy.top/Article/details/gtdnpkverq.html

[J07] 比较两个日期
来源：http://dali.xylfe.cn/Article/details/gtnjjcklgo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gtfqwvofxx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.dashuyun.cn/Article/details/gtsteywiwf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jianghu66.top/Article/details/gttsjijoap.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.guannengcc.top/Article/details/gtmkxabjid.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cheryme.top/Article/details/gtjivotknt.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.mhx1999.top/Article/details/gtvrkykbrm.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sweek.top/Article/details/gtbildnxge.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gtbgqelvrl.html

[J08] 提取年月日与星期
来源：http://dali.chenjidiqi.icu/Article/details/gtaorufwey.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.kuanghao11.cn/Article/details/gtbkilngyz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ehwqpu.com/Article/details/gtuihxeqdh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenlongwang.top/Article/details/gttaxdswbb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ydzc1.top/Article/details/gtkjxytduy.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gzhubu.top/Article/details/gtnqcrljnz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sysykeji.top/Article/details/gtsbkhmcyf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.guowangkeji.top/Article/details/gtcctxrzsv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cucudq.cn/Article/details/gtgxnkrswh.html

[J09] 时区处理
来源：http://dali.jinqigufen.top/Article/details/gtpsinkxbd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jqgufenzy.top/Article/details/gtstjrtwqt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.fzhhl.top/Article/details/gtiephielw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhongyouzk.top/Article/details/gthaczdsqj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dashuyun.cn/Article/details/gtwiiovyyj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.wangshuangyany.cn/Article/details/gtxksszaec.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.feifeiyinyue.top/Article/details/gtxcxeqnro.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jiagoushi.top/Article/details/gtrwxnyxee.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hammf.cn/Article/details/gtkpecdukl.html

[J10] 取今天 / 本月第一天
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbsfafvzz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.kuanghao11.cn/Article/details/gtcxrtxpzs.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ybcxt.top/Article/details/gtgivghchf.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpbmdubbr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sweek.top/Article/details/gtwpmtkgaj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinqigufen.top/Article/details/gtqxumpdlb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzygrqlxk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.feifeiyinyue.top/Article/details/gttsrirajz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xinyue.icu/Article/details/gthyksafct.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtxplzlazu.html

K. JSON 与序列化
来源：http://dali.cdnleiting.top/Article/details/gtmvuowlqf.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtarwusxnt.html

[K01] 对象转 JSON 字符串
来源：http://dali.yvedp.cn/Article/details/gtqzmthlcb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gogol.net.cn/Article/details/gtqqejighl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.0kj1m.cn/Article/details/gtdpgckknu.html

JS:   JSON.stringify(obj)
来源：http://dali.9152youxi.cn/Article/details/gtdfobpgnx.html

TS:   JSON.stringify(obj)
来源：http://dali.jiagoushi.top/Article/details/gtpvkkbdal.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.feifeiyinyue.top/Article/details/gtieflcsmh.html

Go:   json.Marshal(obj)
来源：http://dali.birdmap.top/Article/details/gtqxisvrmu.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.tianlin.xyz/Article/details/gtyrabahhd.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.redwolf501.top/Article/details/gtswvodmec.html

[K02] JSON 字符串转对象
来源：http://dali.hfpthk.cn/Article/details/gtmqjllscs.html

Py:   json.loads(s)
来源：http://dali.cheryme.top/Article/details/gtawvgtajv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zycfv.cn/Article/details/gtxszdsees.html

JS:   JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gtaljabeut.html

TS:   JSON.parse(s)
来源：http://dali.xylfe.cn/Article/details/gtrhugxzxf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhiwuduotai.top/Article/details/gtktffaxpk.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.mhx1999.top/Article/details/gtrxzfmevp.html

Ruby: JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtxwpvcahy.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhoulong.xyz/Article/details/gthugivzem.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhaomingkeji.xyz/Article/details/gthifrgpkb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ybcxt.top/Article/details/gttrehilbk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ppjwa.cn/Article/details/gtctrpzepq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuanzx.com/Article/details/gtkfmombii.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gogol.net.cn/Article/details/gtbpquzuve.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.andypj.xyz/Article/details/gtslecgqzr.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.mhx1999.top/Article/details/gtrfpujfxv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.svipenyu.cn/Article/details/gtzqimgust.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.birdmap.top/Article/details/gtpnsswazi.html

[K04] 读取 JSON 文件
来源：http://dali.shzxlz.cn/Article/details/gtkgnbjxnq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.c1oappe.top/Article/details/gtzwbkevho.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.fzhhl.top/Article/details/gthskozckl.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xziqi.cn/Article/details/gtwrtlnwyw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhengqikj.top/Article/details/gtzqjabsqu.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cdnleiting.top/Article/details/gtometuycy.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xinyue.icu/Article/details/gtwmvhisvz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hnxiangtu.top/Article/details/gtcvjxqbfr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.daxiang520.top/Article/details/gtvkjtsjzv.html

[K05] 深拷贝对象
来源：http://dali.xziqi.cn/Article/details/gtpedmeeco.html

Py:   copy.deepcopy(obj)
来源：http://dali.yuxming.cn/Article/details/gtuljpvzli.html

PHP:  unserialize(serialize($obj));
来源：http://dali.redwolf501.top/Article/details/gtzksnbohn.html

JS:   structuredClone(obj)
来源：http://dali.iojbl.cn/Article/details/gtutktzgzu.html

TS:   structuredClone(obj)
来源：http://dali.sufxvd.cn/Article/details/gtsvcenbyp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yuxming.cn/Article/details/gtaqjsxcsk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.guannengcc.top/Article/details/gtjnabnfnj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xziqi.cn/Article/details/gtnhvwxpmu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yvedp.cn/Article/details/gtmsxxlgcl.html

[K06] 解析 URL 查询串
来源：http://dali.hywenlv.cn/Article/details/gtipflgmzd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jiagoushi.top/Article/details/gtdlfejwae.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.nanxuanxn.top/Article/details/gtpwtrakrl.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gogol.net.cn/Article/details/gteeiuloal.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gaohongyu789.top/Article/details/gtofnqyfof.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.tianlin.xyz/Article/details/gtywawyfvo.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gtfcokwitm.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.svipenyu.cn/Article/details/gtgjeubkkr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.0kj1m.cn/Article/details/gtmcjzkqpp.html

[K07] 进制转换
来源：http://dali.hnxiangtu.top/Article/details/gttbunmhuv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gtnvogufwl.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhoulong.xyz/Article/details/gthktnpglc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gtmdihtwuu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gttowvuidq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gtxsgovdhj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrtltlecx.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.birdmap.top/Article/details/gtnrcfcfcp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtkgnjpmuz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.9152youxi.cn/Article/details/gtyzkjbqng.html

Py:   pickle.dumps(obj)
来源：http://dali.mhx1999.top/Article/details/gtxgmtrpaf.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.iojbl.cn/Article/details/gtxgjggndd.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shzxlz.cn/Article/details/gtftebxmha.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jqgufenzy.top/Article/details/gtsbmdedis.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.316326.xyz/Article/details/gtzdbcsqno.html

Go:   encoding/gob
来源：http://dali.daxiang520.top/Article/details/gtsvbzdlwu.html

Ruby: Marshal.dump(obj)
来源：http://dali.cucudq.cn/Article/details/gtswcstgeq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cqqwz.cn/Article/details/gtlwhrweod.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtpzqwyhgr.html

L. 网络请求
来源：http://dali.dashuyun.cn/Article/details/gtprnciztq.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtdazmkinf.html

[L01] 发送 GET 请求
来源：http://dali.daxiang520.top/Article/details/gtjrzsuhyg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.gaohongyu789.top/Article/details/gtjydesavn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gaohongyu789.top/Article/details/gtxuiivhoh.html

JS:   await fetch(url)
来源：http://dali.dianchejie.cn/Article/details/gtmodokxxj.html

TS:   await fetch(url)
来源：http://dali.xziqi.cn/Article/details/gtifzlcgyu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.nanxuanxn.top/Article/details/gtopomzlji.html

Go:   resp, err := http.Get(url)
来源：http://dali.guannengcc.top/Article/details/gthamwfvzk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cashguo.top/Article/details/gtucyhqyxc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yueranfly.top/Article/details/gtzxtkqofq.html

[L02] 发送 POST JSON
来源：http://dali.pycfn.com/Article/details/gtlohejewy.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yanxiufei.cn/Article/details/gtnilqolxt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shanyushiyangtech.top/Article/details/gtmodushry.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.iojbl.cn/Article/details/gtdwzylyhd.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ehwqpu.com/Article/details/gtjkywlpeg.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.dianchejie.cn/Article/details/gtwkqvgjnb.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.pengpengdd.cyou/Article/details/gtndadfgds.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtewtyifyk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthsminxmy.html

[L03] 设置自定义请求头
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnwzjdvuq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cucudq.cn/Article/details/gtxzahnmct.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gotoacloud.top/Article/details/gtriwoviar.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jqgufenzy.top/Article/details/gtbnkamthe.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gogol.net.cn/Article/details/gtnipemrhb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.tianlin.xyz/Article/details/gthezmupou.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvbpbqzqi.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cdnleiting.top/Article/details/gtajecazxj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jianghu66.top/Article/details/gtztpsfuvo.html

[L04] 设置超时
来源：http://dali.shzxlz.cn/Article/details/gtsqtulkqk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhixingplan.top/Article/details/gtjdwicmyy.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jyoumei.cn/Article/details/gtqklwvbye.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xinyue.icu/Article/details/gtbrqesuzc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigfzy.top/Article/details/gtnlvmpywc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jyoumei.cn/Article/details/gtuazfkksr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cucudq.cn/Article/details/gtgucmhsdg.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.nanxuanxn.top/Article/details/gtxkpwflzd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.wangshuangyany.cn/Article/details/gtqbfabigp.html

[L05] 上传文件（multipart）
来源：http://dali.birdmap.top/Article/details/gtiywkxuaf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhengqikj.top/Article/details/gtjqyyuasy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hfpthk.cn/Article/details/gtgbqyljez.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yanxiufei.cn/Article/details/gtnjkcqmty.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hammf.cn/Article/details/gtetaapicy.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.birdmap.top/Article/details/gtegmfvtnq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.tianlin.xyz/Article/details/gtfaedwjki.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhengqikj.top/Article/details/gteiwdwhdq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtuuuahddt.html

[L06] 解析响应为 JSON
来源：http://dali.jinghuilouyu.cn/Article/details/gtxoqfjpsh.html

Py:   resp.json()
来源：http://dali.chenzaomai.com/Article/details/gtdntkojvi.html

PHP:  json_decode($body, true);
来源：http://dali.smart0.xyz/Article/details/gtexnlvbrx.html

JS:   await resp.json()
来源：http://dali.yj20258.top/Article/details/gtvbbflayk.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gtdsgiklgc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yuanzhike.top/Article/details/gtokaejask.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.redwolf501.top/Article/details/gttiwhktta.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hfpthk.cn/Article/details/gtpqnpfueo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.tianlin.xyz/Article/details/gtstxyowac.html

[L07] 处理 HTTP 状态码
来源：http://dali.xziqi.cn/Article/details/gtxeugdfrs.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shanyushiyangtech.top/Article/details/gtladkxvem.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gogol.net.cn/Article/details/gtuzhtmvba.html

JS:   resp.ok;  resp.status
来源：http://dali.jinghuilouyu.cn/Article/details/gtusdtepfd.html

TS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrcjqqdha.html

Java: resp.statusCode()
来源：http://dali.yvedp.cn/Article/details/gtzkpvvook.html

Go:   resp.StatusCode
来源：http://dali.jinghuilouyu.cn/Article/details/gtefkfebcx.html

Ruby: resp.code.to_i
来源：http://dali.cqqwz.cn/Article/details/gtwtyayihv.html

C#:   (int)resp.StatusCode
来源：http://dali.gaohongyu789.top/Article/details/gtqztlpqva.html

[L08] 并发请求多个地址
来源：http://dali.ydzc1.top/Article/details/gtombqbiyx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.havefunace.top/Article/details/gtgkldlbup.html

PHP:  curl_multi_init() 系列
来源：http://dali.daxiang520.top/Article/details/gtovtoajjx.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yangfankeji.com/Article/details/gtrgoiycmf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrrvcbvhc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hnxiangtu.top/Article/details/gtvvtfwwaf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.nwbrower.top/Article/details/gtetbkqlly.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.snrcjt.cn/Article/details/gtwaldwhgz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinqigfzy.top/Article/details/gtgpoccytk.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtlowvjqwx.html

M. 命令行 / 进程 / 环境
来源：http://dali.yanxiufei.cn/Article/details/gtguxdebue.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtodsqyeyl.html

[M01] 读取命令行参数
来源：http://dali.shzxlz.cn/Article/details/gtvborslwn.html

Py:   sys.argv[1:]
来源：http://dali.mhx1999.top/Article/details/gtgwrgqiya.html

PHP:  $argv;  $argc;
来源：http://dali.wangdashe.top/Article/details/gtihcczkcq.html

JS:   process.argv.slice(2)
来源：http://dali.mhx1999.top/Article/details/gtdqnqmyan.html

TS:   process.argv.slice(2)
来源：http://dali.jqgfzy.top/Article/details/gtlczzfotf.html

Java: args 数组（main 方法参数）
来源：http://dali.jyoumei.cn/Article/details/gtxlfyxtpn.html

Go:   os.Args[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gtrsiyppqi.html

Ruby: ARGV
来源：http://dali.guowangkeji.top/Article/details/gtnhbjprai.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtptjrxgvg.html

[M02] 读取环境变量
来源：http://dali.c1oappe.top/Article/details/gtboohnhvm.html

Py:   os.environ.get("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gtvknvcdzn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yueranfly.top/Article/details/gtfczazggt.html

JS:   process.env.HOME
来源：http://dali.guannengcc.top/Article/details/gtsfdenlcl.html

TS:   process.env.HOME
来源：http://dali.snrcjt.cn/Article/details/gtrzvjvage.html

Java: System.getenv("HOME")
来源：http://dali.cdnleiting.top/Article/details/gtuvfxekta.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jqgfzy.top/Article/details/gtjnvgsfhz.html

Ruby: ENV["HOME"]
来源：http://dali.shuidangran.top/Article/details/gtvxafwvjy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj202588.top/Article/details/gttobunzbr.html

[M03] 执行外部命令
来源：http://dali.hnqzz.top/Article/details/gteepdrvrz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.nwbrower.top/Article/details/gtbphaxiad.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sxryk.cn/Article/details/gtfzpjswcx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinqigfzy.top/Article/details/gtixtizxtr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.haohaochexian.top/Article/details/gtttrbikfs.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.fengsongda.top/Article/details/gthwpvvvzu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.chenlongwang.top/Article/details/gtjekkwdhi.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.meibo888.top/Article/details/gtkijrkvqn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.redwolf501.top/Article/details/gtfuhfgrrx.html

[M04] 获取当前工作目录
来源：http://dali.gzhubu.top/Article/details/gtclmapjzc.html

Py:   os.getcwd()
来源：http://dali.redwolf501.top/Article/details/gtcoyrxeph.html

PHP:  getcwd();
来源：http://dali.jinghuilouyu.cn/Article/details/gtowseaqrt.html

JS:   process.cwd()
来源：http://dali.c1oappe.top/Article/details/gtthulgivo.html

TS:   process.cwd()
来源：http://dali.hfpthk.cn/Article/details/gtxonjwylw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zdqjudy.top/Article/details/gtsfbleafa.html

Go:   os.Getwd()
来源：http://dali.yonumen.top/Article/details/gtlqgpbozk.html

Ruby: Dir.pwd
来源：http://dali.andypj.xyz/Article/details/gtwmmwyvxg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.tianlin.xyz/Article/details/gtnimqjnyt.html

[M05] 设置退出码
来源：http://dali.ppjwa.cn/Article/details/gtpudhhfmw.html

Py:   sys.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtnjdrtbqk.html

PHP:  exit(1);
来源：http://dali.shangyingyoupin.top/Article/details/gtcflnesjj.html

JS:   process.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyqhkefgo.html

TS:   process.exit(1)
来源：http://dali.pycfn.com/Article/details/gtpwgkhhyu.html

Java: System.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gtkilzutqt.html

Go:   os.Exit(1)
来源：http://dali.xuanzx.com/Article/details/gthdrmwyzs.html

Ruby: exit 1
来源：http://dali.ybcxt.top/Article/details/gtdsgbdwtu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ydzc1.top/Article/details/gtavewmbem.html

[M06] 向标准错误输出
来源：http://dali.xinyue.icu/Article/details/gtmrpkcceg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhongyouzk.top/Article/details/gtlvlmxsal.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhongyouzk.top/Article/details/gtkyitaugo.html

JS:   console.error("err")
来源：http://dali.sysykeji.top/Article/details/gtymbtbotk.html

TS:   console.error("err")
来源：http://dali.yj202588.top/Article/details/gtkpokjmil.html

Java: System.err.println("err")
来源：http://dali.yongpay.top/Article/details/gtgjqxfgaj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jianghu66.top/Article/details/gtdmpxgywv.html

Ruby: warn "err"
来源：http://dali.smart0.xyz/Article/details/gtrumpurrs.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yj20258888.top/Article/details/gtmhueiclb.html

[M07] 判断是否为主入口
来源：http://dali.ydzc1.top/Article/details/gtwjhozgoy.html

Py:   if __name__ == "__main__":
来源：http://dali.nanxuanxn.top/Article/details/gtanjjqyft.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gotoacloud.top/Article/details/gteahbwtxc.html

JS:   require.main === module
来源：http://dali.hywenlv.cn/Article/details/gtpfnnyqyw.html

TS:   require.main === module
来源：http://dali.yangfankeji.com/Article/details/gtwpvlpudn.html

Java: public static void main(String[] args)
来源：http://dali.chenzaomai.com/Article/details/gtcnvbjrnp.html

Go:   func main()
来源：http://dali.tianlin.xyz/Article/details/gtgthqjacw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jyoumei.cn/Article/details/gtmcnqjkne.html

C#:   static void Main(string[] args)
来源：http://dali.zhoulong.xyz/Article/details/gtkeknzncs.html


<!-- 参考信息 -->