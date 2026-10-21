代发 wailian999

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yuxming.cn/Article/details/gtaaqpwtzm.html

JS:   new Date();  Date.now()
来源：http://dali.tian-w.cn/Article/details/gtiahueduy.html

TS:   new Date();  Date.now()
来源：http://dali.chenzaomai.com/Article/details/gtzqacmamk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.9152youxi.cn/Article/details/gtnlpocluj.html

Go:   time.Now()
来源：http://dali.sysykeji.top/Article/details/gthwkqxkrx.html

Ruby: Time.now
来源：http://dali.yvedp.cn/Article/details/gtoyjbpykh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ppjwa.cn/Article/details/gtjaizdxkb.html

[J02] 格式化输出
来源：http://dali.cqqwz.cn/Article/details/gthwvejmmw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daria6918.cn/Article/details/gtjzvwrakk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjgtuzfzm.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cdnleiting.top/Article/details/gtaccxydgp.html

TS:   d.toISOString()
来源：http://dali.shanyushiyangtech.top/Article/details/gteurpwbup.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinqigufen.top/Article/details/gtseeyargb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yj20258888.top/Article/details/gtneiuenua.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daria6918.cn/Article/details/gtwnnfegpb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.wangdashe.top/Article/details/gthabeqhth.html

[J03] 字符串解析为日期
来源：http://dali.zhengqikj.top/Article/details/gtmeyrjhnu.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yuxming.cn/Article/details/gtpjpezgnw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.aizwys.cn/Article/details/gtgyvysben.html

JS:   new Date("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gtepjdrdho.html

TS:   new Date("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnmzlfvfg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gtmrhfmgsk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtzqcwfnyh.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gtgobkcmtc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.mhx1999.top/Article/details/gtlyoqpncd.html

[J04] 时间戳与日期互转
来源：http://dali.zhengqikj.top/Article/details/gtawyrtilu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhoulong.xyz/Article/details/gtoeqretem.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hammf.cn/Article/details/gtdhehfkrx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sweek.top/Article/details/gtdzhiydtl.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yangfankeji.com/Article/details/gtzqihsjgc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yj20258.top/Article/details/gtmcpccnnx.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtjmzedegr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhijiandao.cn/Article/details/gtsbemxymw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.daxiang520.top/Article/details/gtrkcxjdza.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhoulong.xyz/Article/details/gtzlxkiepi.html

Py:   now + timedelta(days=7)
来源：http://dali.zhongyouzk.top/Article/details/gtyliwxvzp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.fzhhl.top/Article/details/gtptydlsrd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.redwolf501.top/Article/details/gtbfhepfsm.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shzxlz.cn/Article/details/gtbedwbskr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhongyouzk.top/Article/details/gtsltrayjf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.andypj.xyz/Article/details/gtvtjwhuif.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhengqikj.top/Article/details/gtookzodky.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yueranfly.top/Article/details/gtrlgtpdle.html

[J06] 计算两时间之差
来源：http://dali.meibo888.top/Article/details/gtriaaqrbi.html

Py:   (end - start).total_seconds()
来源：http://dali.gaohongyu789.top/Article/details/gtzrtryjbj.html

PHP:  $end->diff($start)->days;
来源：http://dali.ybcxt.top/Article/details/gtbinwvaib.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.meibo888.top/Article/details/gtiijbdxjw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.aibaodan.cn/Article/details/gtwfqtnbub.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.daxiang520.top/Article/details/gtaedvbfyv.html

Go:   end.Sub(start).Hours()
来源：http://dali.haohaochexian.top/Article/details/gtablxxvty.html

Ruby: end - start                 # 返回秒数
来源：http://dali.bjfxy.top/Article/details/gtttedujpx.html

C#:   (end - start).TotalSeconds
来源：http://dali.jlsjyb.cn/Article/details/gtuvdvrgwc.html

[J07] 比较两个日期
来源：http://dali.ybcxt.top/Article/details/gtnmlkiquh.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sufxvd.cn/Article/details/gtbcxlowrq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hfpthk.cn/Article/details/gtjkixgpqw.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigfzy.top/Article/details/gtimzxfpdx.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hywenlv.cn/Article/details/gtvauzcboi.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cdnleiting.top/Article/details/gtyiyxyzms.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cashguo.top/Article/details/gtaeymeoci.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gzhubu.top/Article/details/gtxgjqoppw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gtjqvtpanf.html

[J08] 提取年月日与星期
来源：http://dali.zhixingplan.top/Article/details/gtljeajapx.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.daxiang520.top/Article/details/gtvqmmujzi.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkrcumabs.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.haohaochexian.top/Article/details/gtpyokmsfw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.chenlongwang.top/Article/details/gtqqkwhmek.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.aibaodan.cn/Article/details/gtahvqywof.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.nwbrower.top/Article/details/gtqxzbetfp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shangyingyoupin.top/Article/details/gttuvidpsn.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.pengpengdd.cyou/Article/details/gtzoprlfoq.html

[J09] 时区处理
来源：http://dali.redwolf501.top/Article/details/gtyoffghxa.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.tianlin.xyz/Article/details/gtqppqefav.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yuanzhike.top/Article/details/gtrnltoyeh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigfzy.top/Article/details/gtjzfcqhty.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tanke756.top/Article/details/gtknspczdz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfqekdeik.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hywenlv.cn/Article/details/gtvgyroffb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.chenlongwang.top/Article/details/gtehnmujud.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yanxiufei.cn/Article/details/gtybdghvqn.html

[J10] 取今天 / 本月第一天
来源：http://dali.smart0.xyz/Article/details/gtrqgqtrdf.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.0kj1m.cn/Article/details/gtsjpdxmld.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.pycfn.com/Article/details/gtypwkwrmb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhixingplan.top/Article/details/gtjqikeidi.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hfpthk.cn/Article/details/gtgkhkbxix.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.nanxinkj.top/Article/details/gtrvmxnbzy.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jqgfzy.top/Article/details/gtxildccla.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hysaishi.cn/Article/details/gtvgduoycx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hysaishi.cn/Article/details/gtojyfmuyy.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gttrvpjeri.html

K. JSON 与序列化
来源：http://dali.zhijiandao.cn/Article/details/gtxwrjefrq.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtnknowyyp.html

[K01] 对象转 JSON 字符串
来源：http://dali.fzhhl.top/Article/details/gtfrnlhmwn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jiagoushi.top/Article/details/gtksytbfum.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhongyouzk.top/Article/details/gtauilased.html

JS:   JSON.stringify(obj)
来源：http://dali.zycfv.cn/Article/details/gtubapzoqg.html

TS:   JSON.stringify(obj)
来源：http://dali.haohaochexian.top/Article/details/gtxfqvdmvk.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinqigfzy.top/Article/details/gtjhborsts.html

Go:   json.Marshal(obj)
来源：http://dali.iojbl.cn/Article/details/gtcelnwlbd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhixingplan.top/Article/details/gtbyvxffwb.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hfpthk.cn/Article/details/gtvhhmoaay.html

[K02] JSON 字符串转对象
来源：http://dali.gotoacloud.top/Article/details/gtxvqbtmvy.html

Py:   json.loads(s)
来源：http://dali.shzxlz.cn/Article/details/gthkjvdeep.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.dashuyun.cn/Article/details/gtduegqyvn.html

JS:   JSON.parse(s)
来源：http://dali.wangdashe.top/Article/details/gtjripvkxb.html

TS:   JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gtjuqnvbbn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gtirjfvohm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.aizwys.cn/Article/details/gtplzsnlnj.html

Ruby: JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gtizetmbla.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.guannengcc.top/Article/details/gtvexmulio.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ppjwa.cn/Article/details/gtjiqikojs.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.tianlin.xyz/Article/details/gtimnncbrp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jiagoushi.top/Article/details/gtpcsmcuoy.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gtwgoazvhg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.snrcjt.cn/Article/details/gtfjcyebld.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtaknhiafq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.tianlin.xyz/Article/details/gtpocheinw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.redwolf501.top/Article/details/gtznvkowhn.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nanxuanxn.top/Article/details/gtkzhdtxqp.html

[K04] 读取 JSON 文件
来源：http://dali.ppjwa.cn/Article/details/gtorsueomt.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.aibaodan.cn/Article/details/gtcprjiqpk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yangfankeji.com/Article/details/gtiawjecdl.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gtsqeqaaqy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shzxlz.cn/Article/details/gtuwbnylmq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.aizwys.cn/Article/details/gtlcuvfdzq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhongyouzk.top/Article/details/gtdqvlkzyn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.fzhhl.top/Article/details/gtqefbgwnb.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.mhx1999.top/Article/details/gtvndrlzfh.html

[K05] 深拷贝对象
来源：http://dali.feifeiyinyue.top/Article/details/gtxhfcoylf.html

Py:   copy.deepcopy(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtjjodskuj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.aizwys.cn/Article/details/gtnzdtdjrr.html

JS:   structuredClone(obj)
来源：http://dali.gzhubu.top/Article/details/gtsaxuljld.html

TS:   structuredClone(obj)
来源：http://dali.jiagoushi.top/Article/details/gtgyrkjtal.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hnxiangtu.top/Article/details/gtdmolwplh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.chenjidiqi.icu/Article/details/gtvinwcios.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.iojbl.cn/Article/details/gtliuddmdj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jyoumei.cn/Article/details/gttkhorlhk.html

[K06] 解析 URL 查询串
来源：http://dali.c1oappe.top/Article/details/gtmklpjkia.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.aizwys.cn/Article/details/gtafeosemp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhongyouzk.top/Article/details/gtqrfwkihw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jyoumei.cn/Article/details/gtlscmnfni.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangshuangyany.cn/Article/details/gtlrhlcryq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yanxiufei.cn/Article/details/gtqrrmipil.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jqgufenzy.top/Article/details/gtogsszpzx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yuanzhike.top/Article/details/gtigmdkker.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gtpcdeqbtj.html

[K07] 进制转换
来源：http://dali.snrcjt.cn/Article/details/gtyaoakfwt.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtvozsbaan.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shanyushiyangtech.top/Article/details/gtjyxtfpbd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gtubqleqhq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gtwssqwlfp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gtuzrgwydu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ppjwa.cn/Article/details/gtyllxmkkz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hfpthk.cn/Article/details/gthtsjkybx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gtfurrqoti.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sxryk.cn/Article/details/gttkbvnhwg.html

Py:   pickle.dumps(obj)
来源：http://dali.ydzc1.top/Article/details/gtaltefehm.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ivvv.top/Article/details/gtiozougtz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.redwolf501.top/Article/details/gtcwerzawc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.daria6918.cn/Article/details/gtnxisnamr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.nanxinkj.top/Article/details/gtghjwivrx.html

Go:   encoding/gob
来源：http://dali.gotoacloud.top/Article/details/gtujgpehjk.html

Ruby: Marshal.dump(obj)
来源：http://dali.ehwqpu.com/Article/details/gtnqdlbojm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.bjfxy.top/Article/details/gtqeytbbkr.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtqmdfmrmo.html

L. 网络请求
来源：http://dali.tanke756.top/Article/details/gtzhyminwx.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtcedddosh.html

[L01] 发送 GET 请求
来源：http://dali.daria6918.cn/Article/details/gterddriwu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gtcanyxjtw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.smart0.xyz/Article/details/gtscrrqvnl.html

JS:   await fetch(url)
来源：http://dali.havefunace.top/Article/details/gtaclwdzna.html

TS:   await fetch(url)
来源：http://dali.feifeiyinyue.top/Article/details/gtcmdcrxtb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.mhx1999.top/Article/details/gtmuzkgacb.html

Go:   resp, err := http.Get(url)
来源：http://dali.cqqwz.cn/Article/details/gtepjwoizv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cheryme.top/Article/details/gtvsarmphu.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhiwuduotai.top/Article/details/gtvltlzjae.html

[L02] 发送 POST JSON
来源：http://dali.hnxiangtu.top/Article/details/gtiaoaycwc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.haohaochexian.top/Article/details/gtuiepiumx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jiagoushi.top/Article/details/gttqatorme.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.smart0.xyz/Article/details/gtkxsoywuz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sweek.top/Article/details/gtndkodulg.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xinyue.icu/Article/details/gtxxwfuyfc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hnxiangtu.top/Article/details/gtovpunnyv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.feifeiyinyue.top/Article/details/gtkroawith.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.fzhhl.top/Article/details/gtnydkanff.html

[L03] 设置自定义请求头
来源：http://dali.c1oappe.top/Article/details/gtobcdzjeq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.feifeiyinyue.top/Article/details/gtgcmffezx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.redwolf501.top/Article/details/gttlrlszzt.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cheryme.top/Article/details/gteozjpevw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fengsongda.top/Article/details/gtudpetqzm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.daxiang520.top/Article/details/gtmptupyhy.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.vqdsnc.cn/Article/details/gtqjvkfkov.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnzbweffr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xinyue.icu/Article/details/gtlqnbxjdt.html

[L04] 设置超时
来源：http://dali.jinqigufen.top/Article/details/gtdeujjsma.html

Py:   requests.get(url, timeout=5)
来源：http://dali.svipenyu.cn/Article/details/gtiombwetm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hywenlv.cn/Article/details/gtjpirfbac.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nwbrower.top/Article/details/gteqvjtzje.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigfzy.top/Article/details/gtcvecdckt.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jiagoushi.top/Article/details/gtpwtppxiu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gaohongyu789.top/Article/details/gtxprxgfgg.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.birdmap.top/Article/details/gtozgnytfm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hnxiangtu.top/Article/details/gtmqizbunq.html

[L05] 上传文件（multipart）
来源：http://dali.c1oappe.top/Article/details/gtzedhxsuk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.wangdashe.top/Article/details/gtskkfceqp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jianghu66.top/Article/details/gtdeanjlao.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.fengsongda.top/Article/details/gtkmszkwhq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hongshengwenyu.top/Article/details/gtjnfruqnr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gaohongyu789.top/Article/details/gtzttajawl.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.fzhhl.top/Article/details/gtrxxkyfng.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hammf.cn/Article/details/gtflxjacvv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtfbeltowv.html

[L06] 解析响应为 JSON
来源：http://dali.fengsongda.top/Article/details/gttsozfwey.html

Py:   resp.json()
来源：http://dali.chenlongwang.top/Article/details/gtscqumtqo.html

PHP:  json_decode($body, true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdqohoutt.html

JS:   await resp.json()
来源：http://dali.yvedp.cn/Article/details/gtqyvhlduc.html

TS:   await resp.json()
来源：http://dali.meibo888.top/Article/details/gtcpwpacbj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hysaishi.cn/Article/details/gtzccejbkp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zycfv.cn/Article/details/gtsfzhupws.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj202588.top/Article/details/gtowvufkdr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ppjwa.cn/Article/details/gtrqmulbqn.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gtphngfcbv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xinyue.icu/Article/details/gttbobfniq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gogol.net.cn/Article/details/gtthtoulfd.html

JS:   resp.ok;  resp.status
来源：http://dali.zhixingplan.top/Article/details/gtceulwcfc.html

TS:   resp.ok;  resp.status
来源：http://dali.sxryk.cn/Article/details/gtdldhibch.html

Java: resp.statusCode()
来源：http://dali.gaohongyu789.top/Article/details/gtmxqqmmxc.html

Go:   resp.StatusCode
来源：http://dali.jyoumei.cn/Article/details/gtrtrejtls.html

Ruby: resp.code.to_i
来源：http://dali.chenzaomai.com/Article/details/gtwbvipwgw.html

C#:   (int)resp.StatusCode
来源：http://dali.kuanghao11.cn/Article/details/gtcfycmasd.html

[L08] 并发请求多个地址
来源：http://dali.jinghuilouyu.cn/Article/details/gtiirjrmky.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hysaishi.cn/Article/details/gtyhbznuor.html

PHP:  curl_multi_init() 系列
来源：http://dali.yvedp.cn/Article/details/gtcuktdudy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtedvrnbht.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aizwys.cn/Article/details/gtsyccdrzc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinqigfzy.top/Article/details/gttmczpwhd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xylfe.cn/Article/details/gtbhszmftq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cashguo.top/Article/details/gtaouxnmlx.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hnxiangtu.top/Article/details/gtegyyitzc.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtqzvhkqgk.html

M. 命令行 / 进程 / 环境
来源：http://dali.tanke756.top/Article/details/gtoukzjdxo.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtlowbjxjl.html

[M01] 读取命令行参数
来源：http://dali.tian-w.cn/Article/details/gtqcroikii.html

Py:   sys.argv[1:]
来源：http://dali.aizwys.cn/Article/details/gtgxkncwnb.html

PHP:  $argv;  $argc;
来源：http://dali.yueranfly.top/Article/details/gtbkcedvav.html

JS:   process.argv.slice(2)
来源：http://dali.daria6918.cn/Article/details/gtvmrflyap.html

TS:   process.argv.slice(2)
来源：http://dali.kuanghao11.cn/Article/details/gtqzvhzhjt.html

Java: args 数组（main 方法参数）
来源：http://dali.shangyingyoupin.top/Article/details/gtfgbzigfw.html

Go:   os.Args[1:]
来源：http://dali.kuanghao11.cn/Article/details/gtatuqmzci.html

Ruby: ARGV
来源：http://dali.svipenyu.cn/Article/details/gtacdnogdy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yonumen.top/Article/details/gtpjpptxrk.html

[M02] 读取环境变量
来源：http://dali.pycfn.com/Article/details/gtgborhmds.html

Py:   os.environ.get("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlmhypqxp.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.guannengcc.top/Article/details/gttepetixl.html

JS:   process.env.HOME
来源：http://dali.ydzc1.top/Article/details/gtwynhbpln.html

TS:   process.env.HOME
来源：http://dali.wangdashe.top/Article/details/gtssvhdzkh.html

Java: System.getenv("HOME")
来源：http://dali.9152youxi.cn/Article/details/gthqkzxwrk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sxryk.cn/Article/details/gtrwobwvhk.html

Ruby: ENV["HOME"]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtphfnxgze.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnejllbvp.html

[M03] 执行外部命令
来源：http://dali.redwolf501.top/Article/details/gtytxjpmke.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.guannengcc.top/Article/details/gttgfmrruu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sweek.top/Article/details/gtadnjzlxi.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hongshengwenyu.top/Article/details/gtjiwlribn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.aizwys.cn/Article/details/gtndplxaco.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.redwolf501.top/Article/details/gtsqhwzoca.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ppjwa.cn/Article/details/gthuntzrtf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gzhubu.top/Article/details/gtejppwcxu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yonumen.top/Article/details/gtnbcgyhjg.html

[M04] 获取当前工作目录
来源：http://dali.hnqzz.top/Article/details/gtytqznlto.html

Py:   os.getcwd()
来源：http://dali.havefunace.top/Article/details/gtrfwebgcq.html

PHP:  getcwd();
来源：http://dali.feifeiyinyue.top/Article/details/gtuxwwawmg.html

JS:   process.cwd()
来源：http://dali.zhixingplan.top/Article/details/gtgzznzcvk.html

TS:   process.cwd()
来源：http://dali.pengpengdd.cyou/Article/details/gtxufltssx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shangyingyoupin.top/Article/details/gtooekywbd.html

Go:   os.Getwd()
来源：http://dali.kuanghao11.cn/Article/details/gtcwoxphti.html

Ruby: Dir.pwd
来源：http://dali.gotoacloud.top/Article/details/gtxgtlxbne.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shangyingyoupin.top/Article/details/gtfdbitntc.html

[M05] 设置退出码
来源：http://dali.tanke756.top/Article/details/gtggtmwyxt.html

Py:   sys.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gtjlblajgb.html

PHP:  exit(1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcitrmrgg.html

JS:   process.exit(1)
来源：http://dali.tanke756.top/Article/details/gtsrjlculu.html

TS:   process.exit(1)
来源：http://dali.smart0.xyz/Article/details/gtzzjbffrc.html

Java: System.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtochwbbwx.html

Go:   os.Exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtpbcyjrph.html

Ruby: exit 1
来源：http://dali.9152youxi.cn/Article/details/gthisqswpp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.tianlin.xyz/Article/details/gtduswrebf.html

[M06] 向标准错误输出
来源：http://dali.xinyue.icu/Article/details/gtbgqvpkkq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.chenzaomai.com/Article/details/gtaqodjmpt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhiwuduotai.top/Article/details/gtepcoupps.html

JS:   console.error("err")
来源：http://dali.zhengqikj.top/Article/details/gtvjhgvkmq.html

TS:   console.error("err")
来源：http://dali.quarkkingdee.top/Article/details/gtdcwmeifj.html

Java: System.err.println("err")
来源：http://dali.bjfxy.top/Article/details/gtrubsldwe.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hnxiangtu.top/Article/details/gtgvrzlhkb.html

Ruby: warn "err"
来源：http://dali.hywenlv.cn/Article/details/gttfuvaiqr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nanxuanxn.top/Article/details/gtmjawywsa.html

[M07] 判断是否为主入口
来源：http://dali.dashuyun.cn/Article/details/gtzgsdauad.html

Py:   if __name__ == "__main__":
来源：http://dali.fzhhl.top/Article/details/gtzoxbrawi.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hysaishi.cn/Article/details/gtkozunzrg.html

JS:   require.main === module
来源：http://dali.cucudq.cn/Article/details/gtrngngduw.html

TS:   require.main === module
来源：http://dali.zhixingplan.top/Article/details/gtornlakjo.html


<!-- 参考信息 -->