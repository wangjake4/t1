代发 wailian999

J. 日期与时间
来源：http://dali.shangyingyoupin.top/Article/details/gtgumngfgw.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtnmyxqgix.html

[J01] 获取当前时间
来源：http://dali.chenjidiqi.icu/Article/details/gtmuoqviet.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.pycfn.com/Article/details/gtklnnlvne.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ivvv.top/Article/details/gtxemhuivi.html

JS:   new Date();  Date.now()
来源：http://dali.zhixingplan.top/Article/details/gtwsfjchab.html

TS:   new Date();  Date.now()
来源：http://dali.tian-w.cn/Article/details/gtpfulwbuw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shangyingyoupin.top/Article/details/gtvckvxbpb.html

Go:   time.Now()
来源：http://dali.havefunace.top/Article/details/gtqzmjrmns.html

Ruby: Time.now
来源：http://dali.iojbl.cn/Article/details/gtvlxqtwdh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.vqdsnc.cn/Article/details/gtyaooxcnx.html

[J02] 格式化输出
来源：http://dali.sweek.top/Article/details/gtcygifjmb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.0kj1m.cn/Article/details/gtqebypxhn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.nwbrower.top/Article/details/gtoteadtxa.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xziqi.cn/Article/details/gtkwjokqzd.html

TS:   d.toISOString()
来源：http://dali.meibo888.top/Article/details/gtgkwumpan.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sweek.top/Article/details/gtyyzaxwiw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqudknmro.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgufenzy.top/Article/details/gtdktxbbtg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daria6918.cn/Article/details/gtenxtjwqp.html

[J03] 字符串解析为日期
来源：http://dali.shanyushiyangtech.top/Article/details/gthnpwxter.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zdqjudy.top/Article/details/gteoshcuqh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cqqwz.cn/Article/details/gtjsjvgjdf.html

JS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdiqnccoq.html

TS:   new Date("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gthlymhwpo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gtyqpnpzzb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gtqmnabnqh.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gtyswufmkt.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.guannengcc.top/Article/details/gtskdmugia.html

[J04] 时间戳与日期互转
来源：http://dali.birdmap.top/Article/details/gturmzyxyx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.vqdsnc.cn/Article/details/gtgeieshmf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhiwuduotai.top/Article/details/gtidxqdxqa.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yangfankeji.com/Article/details/gtkkiavwbw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yuanzhike.top/Article/details/gttrmkmesk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jqgufenzy.top/Article/details/gtbdeumhog.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gotoacloud.top/Article/details/gtzojnkdvu.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.c1oappe.top/Article/details/gtnmsexwts.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gogol.net.cn/Article/details/gtfklvciug.html

[J05] 时间加减（加 7 天）
来源：http://dali.sysykeji.top/Article/details/gtibwtxhoj.html

Py:   now + timedelta(days=7)
来源：http://dali.jinqigufen.top/Article/details/gtyvkujmkh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cashguo.top/Article/details/gtzwowounn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hywenlv.cn/Article/details/gtodglkbuy.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nwbrower.top/Article/details/gtgfxwxjrm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsnljjhyf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.feifeiyinyue.top/Article/details/gtpdueqcpk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hfpthk.cn/Article/details/gtsfsgrygd.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xylfe.cn/Article/details/gtgmfekyon.html

[J06] 计算两时间之差
来源：http://dali.jinghuilouyu.cn/Article/details/gtkhayyltw.html

Py:   (end - start).total_seconds()
来源：http://dali.hnqzz.top/Article/details/gtjzwnoxow.html

PHP:  $end->diff($start)->days;
来源：http://dali.jqgufenzy.top/Article/details/gtbxlgqzil.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jlsjyb.cn/Article/details/gtegblccmy.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhijiandao.cn/Article/details/gtefvigtpk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.guannengcc.top/Article/details/gtotfywrwo.html

Go:   end.Sub(start).Hours()
来源：http://dali.quarkkingdee.top/Article/details/gtnyhlmazm.html

Ruby: end - start                 # 返回秒数
来源：http://dali.guannengcc.top/Article/details/gtxjlmzfpx.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenjidiqi.icu/Article/details/gtilujgzzr.html

[J07] 比较两个日期
来源：http://dali.gogol.net.cn/Article/details/gtohssburh.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sweek.top/Article/details/gthqioksjs.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cashguo.top/Article/details/gthwdcaujh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenzaomai.com/Article/details/gtvbylspgd.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hnxiangtu.top/Article/details/gtdglluvlr.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.vqdsnc.cn/Article/details/gtbkxfyala.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yangfankeji.com/Article/details/gtlixgqwot.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.9152youxi.cn/Article/details/gtniuopjkd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gttcviayfe.html

[J08] 提取年月日与星期
来源：http://dali.hammf.cn/Article/details/gtrpnxmfhv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.iojbl.cn/Article/details/gtybvpshnp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sweek.top/Article/details/gtttlnrmgs.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ydzc1.top/Article/details/gteqgjvimz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinghuilouyu.cn/Article/details/gtbbjykezy.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cheryme.top/Article/details/gttezwhyux.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shangyingyoupin.top/Article/details/gtjcjaplao.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.316326.xyz/Article/details/gtzpkothxw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.iojbl.cn/Article/details/gtqfqqgyzu.html

[J09] 时区处理
来源：http://dali.zhiwuduotai.top/Article/details/gtmuxabake.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwcnrylwv.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.tian-w.cn/Article/details/gthlxekzbh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gzhubu.top/Article/details/gtpsjuwcit.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxuanxn.top/Article/details/gtfumadrge.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.fzhhl.top/Article/details/gtrsrppxcc.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhiwuduotai.top/Article/details/gtmbcyrjvh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.bjfxy.top/Article/details/gtrcfstvft.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yvedp.cn/Article/details/gtqwjpcybc.html

[J10] 取今天 / 本月第一天
来源：http://dali.wangdashe.top/Article/details/gtqwwsgwzq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.wangdashe.top/Article/details/gtpgfsdjoy.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.guannengcc.top/Article/details/gttjipocdl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cdnleiting.top/Article/details/gtkmxxozch.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtibqrgrma.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.nwbrower.top/Article/details/gtlggfllpw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xylfe.cn/Article/details/gtmkwfqisu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gogol.net.cn/Article/details/gtjqjrvjpz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jlsjyb.cn/Article/details/gtsidizaqm.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtbogcyioa.html

K. JSON 与序列化
来源：http://dali.aizwys.cn/Article/details/gtpjvbyouy.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtryqhftov.html

[K01] 对象转 JSON 字符串
来源：http://dali.yj20258888.top/Article/details/gtgjjpwiaw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.wangshuangyany.cn/Article/details/gtgpqdpuzi.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhongyouzk.top/Article/details/gtyktfhmyf.html

JS:   JSON.stringify(obj)
来源：http://dali.0kj1m.cn/Article/details/gtqzlvroqy.html

TS:   JSON.stringify(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtpxmvhnle.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.chenlongwang.top/Article/details/gtrgwysawu.html

Go:   json.Marshal(obj)
来源：http://dali.hywenlv.cn/Article/details/gtspofcbkc.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.snrcjt.cn/Article/details/gtizoymeaw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtpruqcewl.html

[K02] JSON 字符串转对象
来源：http://dali.cheryme.top/Article/details/gtkbeccmik.html

Py:   json.loads(s)
来源：http://dali.vqdsnc.cn/Article/details/gtwngbzgbl.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jlsjyb.cn/Article/details/gtpcoqhxjq.html

JS:   JSON.parse(s)
来源：http://dali.ybcxt.top/Article/details/gtznryargk.html

TS:   JSON.parse(s)
来源：http://dali.hfpthk.cn/Article/details/gtcidiqure.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhongyouzk.top/Article/details/gtbqxcpilb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhoulong.xyz/Article/details/gtecoqsbmb.html

Ruby: JSON.parse(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbzmmvsyd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.nanxinkj.top/Article/details/gtcwocvrvh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yonumen.top/Article/details/gtfaiyiaqs.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hywenlv.cn/Article/details/gtvisxlxgf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.smart0.xyz/Article/details/gtsxouxfgg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxuanxn.top/Article/details/gtswzdjjln.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtdyigckzc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.mhx1999.top/Article/details/gtogsyzijw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cqqwz.cn/Article/details/gtczsgonxf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.tanke756.top/Article/details/gtgvvhviic.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.smart0.xyz/Article/details/gttyjgremf.html

[K04] 读取 JSON 文件
来源：http://dali.yuanzhike.top/Article/details/gtrozwdscp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gzhubu.top/Article/details/gtvloiauef.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cqqwz.cn/Article/details/gtxtqbqnpw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aibaodan.cn/Article/details/gtlpzftbyq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258888.top/Article/details/gtnqgtvrkp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jiagoushi.top/Article/details/gtheuezicy.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sxryk.cn/Article/details/gtdsiwymaf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtgdpmskkh.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ybcxt.top/Article/details/gtcdbcmpfo.html

[K05] 深拷贝对象
来源：http://dali.zhixingplan.top/Article/details/gttiiggwat.html

Py:   copy.deepcopy(obj)
来源：http://dali.nanxinkj.top/Article/details/gtoqcpyees.html

PHP:  unserialize(serialize($obj));
来源：http://dali.redwolf501.top/Article/details/gtxpolfnct.html

JS:   structuredClone(obj)
来源：http://dali.hywenlv.cn/Article/details/gtnyyfmalp.html

TS:   structuredClone(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtxdafajhz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jianghu66.top/Article/details/gtzfguztqa.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.meibo888.top/Article/details/gtmhumrnrc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.kuanghao11.cn/Article/details/gtefgvjmgw.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.fengsongda.top/Article/details/gtjqkzgttl.html

[K06] 解析 URL 查询串
来源：http://dali.hnqzz.top/Article/details/gtpkorsfwz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jqgfzy.top/Article/details/gtzpzrstsj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtirrxlbcv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhixingplan.top/Article/details/gtvuxelvhb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.c1oappe.top/Article/details/gtacivruyd.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jianghu66.top/Article/details/gtvcygxhpa.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hammf.cn/Article/details/gtjkcdcubn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhixingplan.top/Article/details/gtzunedxcq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.smart0.xyz/Article/details/gtbdquxmcw.html

[K07] 进制转换
来源：http://dali.yueranfly.top/Article/details/gtswteiael.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.havefunace.top/Article/details/gtfvufkcvw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ydzc1.top/Article/details/gtpvgzpdiq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gtzefgmume.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yongpay.top/Article/details/gtsjygmrux.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.meibo888.top/Article/details/gtslfayyxy.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ybcxt.top/Article/details/gtnladxbia.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zycfv.cn/Article/details/gtxsamilfu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtfbdebcwx.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.havefunace.top/Article/details/gtqhnuswri.html

Py:   pickle.dumps(obj)
来源：http://dali.9152youxi.cn/Article/details/gtpagjyvub.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jlsjyb.cn/Article/details/gthimlovuj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.dashuyun.cn/Article/details/gtalfbxory.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.daxiang520.top/Article/details/gtlifhkruy.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xuetiantiany.cn/Article/details/gtjhqkusyu.html

Go:   encoding/gob
来源：http://dali.yanxiufei.cn/Article/details/gtwlxnhlos.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtizfovbbz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ydzc1.top/Article/details/gtefqjlewp.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtvyerkebp.html

L. 网络请求
来源：http://dali.andypj.xyz/Article/details/gttjwkjwnk.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtgdxannau.html

[L01] 发送 GET 请求
来源：http://dali.wangshuangyany.cn/Article/details/gtvhktrepw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.gogol.net.cn/Article/details/gtcgcyjbpz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jianghu66.top/Article/details/gtxxoiupfc.html

JS:   await fetch(url)
来源：http://dali.ydzc1.top/Article/details/gtflozmfef.html

TS:   await fetch(url)
来源：http://dali.yanxiufei.cn/Article/details/gtvplamgvi.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.guannengcc.top/Article/details/gtmvlpcrer.html

Go:   resp, err := http.Get(url)
来源：http://dali.yuanzhike.top/Article/details/gtulnzbrwp.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinqigfzy.top/Article/details/gtoscrmfwr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xziqi.cn/Article/details/gtyombckca.html

[L02] 发送 POST JSON
来源：http://dali.zhiwuduotai.top/Article/details/gtalepmgkv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhiwuduotai.top/Article/details/gtlzlfdeya.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwiawvbyj.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.smart0.xyz/Article/details/gtufojjcdh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guannengcc.top/Article/details/gtixtxqewz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.iojbl.cn/Article/details/gtpbhwmdgi.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xuanzx.com/Article/details/gtvfxrfqff.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoqmsnyeu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hysaishi.cn/Article/details/gtvatlrbzz.html

[L03] 设置自定义请求头
来源：http://dali.yvedp.cn/Article/details/gtdmtgjdgl.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.316326.xyz/Article/details/gtmpwnmrkf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jiagoushi.top/Article/details/gtdurclkna.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gogol.net.cn/Article/details/gtszmunarc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tanke756.top/Article/details/gtridsiysy.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.daxiang520.top/Article/details/gtvcgxxqkl.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.chenlongwang.top/Article/details/gtvomxomgo.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.tian-w.cn/Article/details/gtejxzsfes.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hfpthk.cn/Article/details/gtujyiotlq.html

[L04] 设置超时
来源：http://dali.quarkkingdee.top/Article/details/gtcgspambe.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtevgdislw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.tanke756.top/Article/details/gtoliiqcck.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.kuanghao11.cn/Article/details/gtqevoimnr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.birdmap.top/Article/details/gtzmmbqnir.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinghuilouyu.cn/Article/details/gtbjemsyqc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhoulong.xyz/Article/details/gtahwvdxbh.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cashguo.top/Article/details/gtfniluzgj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zycfv.cn/Article/details/gtsmfozcdi.html

[L05] 上传文件（multipart）
来源：http://dali.birdmap.top/Article/details/gtpnzulocz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinqigfzy.top/Article/details/gtbpijeslq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cqqwz.cn/Article/details/gtnqqthoix.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhengqikj.top/Article/details/gtoqbdgvku.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sysykeji.top/Article/details/gtgrxnshol.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhongyouzk.top/Article/details/gtigandocj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gogol.net.cn/Article/details/gtzlvyznjv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sweek.top/Article/details/gtaolapyky.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtwnmctrdr.html

[L06] 解析响应为 JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuzfpnnpt.html

Py:   resp.json()
来源：http://dali.iojbl.cn/Article/details/gtklkjratn.html

PHP:  json_decode($body, true);
来源：http://dali.dashuyun.cn/Article/details/gtepcnyqex.html

JS:   await resp.json()
来源：http://dali.hammf.cn/Article/details/gtquvuhrln.html

TS:   await resp.json()
来源：http://dali.yongpay.top/Article/details/gtpitdkyoi.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.mhx1999.top/Article/details/gtjecubotl.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shuidangran.top/Article/details/gtnqvjodxj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhengqikj.top/Article/details/gtxkihkgov.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.birdmap.top/Article/details/gthpvxxeoy.html

[L07] 处理 HTTP 状态码
来源：http://dali.hongshengwenyu.top/Article/details/gtuxxkpksz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.chenzaomai.com/Article/details/gtnvebujvi.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ybcxt.top/Article/details/gtesrjqlsh.html

JS:   resp.ok;  resp.status
来源：http://dali.chenlongwang.top/Article/details/gtzvongydg.html

TS:   resp.ok;  resp.status
来源：http://dali.nwbrower.top/Article/details/gtdknfvsxa.html

Java: resp.statusCode()
来源：http://dali.havefunace.top/Article/details/gtvvbfenyq.html

Go:   resp.StatusCode
来源：http://dali.cdnleiting.top/Article/details/gtgyrhyats.html

Ruby: resp.code.to_i
来源：http://dali.cashguo.top/Article/details/gtohtwbybc.html

C#:   (int)resp.StatusCode
来源：http://dali.feifeiyinyue.top/Article/details/gtdcqpxyrm.html

[L08] 并发请求多个地址
来源：http://dali.yj20258888.top/Article/details/gtuntjxnoa.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shangyingyoupin.top/Article/details/gtygixugmc.html

PHP:  curl_multi_init() 系列
来源：http://dali.cheryme.top/Article/details/gtctxxpadr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhongyouzk.top/Article/details/gtfdtrzymg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yvedp.cn/Article/details/gtcrzvcwqq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.wangshuangyany.cn/Article/details/gtwabbtbii.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.vqdsnc.cn/Article/details/gtzzjzihbe.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.fzhhl.top/Article/details/gtcyhthnmd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tianlin.xyz/Article/details/gtymvplsaq.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtijoiihmc.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinqigfzy.top/Article/details/gtubtriqxp.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtnncrggar.html

[M01] 读取命令行参数
来源：http://dali.cdnleiting.top/Article/details/gthektprzk.html

Py:   sys.argv[1:]
来源：http://dali.guannengcc.top/Article/details/gtribxyxcj.html

PHP:  $argv;  $argc;
来源：http://dali.fzhhl.top/Article/details/gtnjtomosk.html

JS:   process.argv.slice(2)
来源：http://dali.hysaishi.cn/Article/details/gtqprhpvdh.html

TS:   process.argv.slice(2)
来源：http://dali.hammf.cn/Article/details/gtuiklbtae.html

Java: args 数组（main 方法参数）
来源：http://dali.guowangkeji.top/Article/details/gtumzsebmg.html

Go:   os.Args[1:]
来源：http://dali.xylfe.cn/Article/details/gtiqphozby.html

Ruby: ARGV
来源：http://dali.wangdashe.top/Article/details/gtphgwuvkx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.smart0.xyz/Article/details/gtatpyhthj.html

[M02] 读取环境变量
来源：http://dali.hysaishi.cn/Article/details/gtotxawabj.html

Py:   os.environ.get("HOME")
来源：http://dali.jianghu66.top/Article/details/gtxgpzlsod.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yangfankeji.com/Article/details/gtwthxdurh.html

JS:   process.env.HOME
来源：http://dali.redwolf501.top/Article/details/gtckrpotsj.html

TS:   process.env.HOME
来源：http://dali.hongshengwenyu.top/Article/details/gtkcwnnael.html

Java: System.getenv("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjqcqubck.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gtwehogyjw.html

Ruby: ENV["HOME"]
来源：http://dali.zhoulong.xyz/Article/details/gteqaqyagf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtegngugux.html

[M03] 执行外部命令
来源：http://dali.yj202588.top/Article/details/gtzqqiozyt.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yj202588.top/Article/details/gtmhmtjydr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.chenzaomai.com/Article/details/gtupyvbwjy.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.bjfxy.top/Article/details/gtmhezkqqu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258.top/Article/details/gtqehvchhq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwjmxtbox.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jyoumei.cn/Article/details/gtxvjepcdp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hysaishi.cn/Article/details/gtzdqzerxu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gaohongyu789.top/Article/details/gtuhhzgsto.html

[M04] 获取当前工作目录
来源：http://dali.wangdashe.top/Article/details/gtmwigktor.html

Py:   os.getcwd()
来源：http://dali.tianlin.xyz/Article/details/gtqwrybkfp.html

PHP:  getcwd();
来源：http://dali.svipenyu.cn/Article/details/gtlyrxxgvo.html

JS:   process.cwd()
来源：http://dali.hysaishi.cn/Article/details/gteueecrqk.html

TS:   process.cwd()
来源：http://dali.birdmap.top/Article/details/gtzlmvobfp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yongpay.top/Article/details/gtehnqxaca.html

Go:   os.Getwd()
来源：http://dali.yangfankeji.com/Article/details/gtrpxgpknj.html

Ruby: Dir.pwd
来源：http://dali.tanke756.top/Article/details/gthnlinmdp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nanxinkj.top/Article/details/gtvijmudks.html

[M05] 设置退出码
来源：http://dali.xziqi.cn/Article/details/gtcynhpeqa.html

Py:   sys.exit(1)
来源：http://dali.fzhhl.top/Article/details/gtsgylvaad.html

PHP:  exit(1);
来源：http://dali.vqdsnc.cn/Article/details/gtvxgdupvf.html

JS:   process.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gtzewyldrc.html

TS:   process.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gtiafbnpby.html

Java: System.exit(1)
来源：http://dali.chenlongwang.top/Article/details/gtpfjidcvz.html

Go:   os.Exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtbmceqvwx.html

Ruby: exit 1
来源：http://dali.ydzc1.top/Article/details/gtlwvunzae.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.andypj.xyz/Article/details/gtnswkxusg.html

[M06] 向标准错误输出
来源：http://dali.xylfe.cn/Article/details/gtbazmprtr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.haohaochexian.top/Article/details/gtaluyixpd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hfpthk.cn/Article/details/gtllgozpvc.html

JS:   console.error("err")
来源：http://dali.cqqwz.cn/Article/details/gtdqmxmfhr.html

TS:   console.error("err")
来源：http://dali.hongshengwenyu.top/Article/details/gtlzogjpeu.html

Java: System.err.println("err")
来源：http://dali.dashuyun.cn/Article/details/gtzuuulpiu.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtewttcfsv.html

Ruby: warn "err"
来源：http://dali.shuidangran.top/Article/details/gtbsundzmo.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.quarkkingdee.top/Article/details/gtkxwrkhqj.html

[M07] 判断是否为主入口
来源：http://dali.wangshuangyany.cn/Article/details/gtfkqxcxta.html


<!-- 参考信息 -->