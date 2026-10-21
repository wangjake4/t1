代发 wailian999

J. 日期与时间
来源：http://dali.9152youxi.cn/Article/details/gtzpnniyrp.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtgslajdtn.html

[J01] 获取当前时间
来源：http://dali.andypj.xyz/Article/details/gtgvgbzipr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zycfv.cn/Article/details/gtjlaxqwvh.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.svipenyu.cn/Article/details/gtsiimewog.html

JS:   new Date();  Date.now()
来源：http://dali.9152youxi.cn/Article/details/gtgxucvtuj.html

TS:   new Date();  Date.now()
来源：http://dali.chenzaomai.com/Article/details/gtpjpqxtqj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ppjwa.cn/Article/details/gtivnkibba.html

Go:   time.Now()
来源：http://dali.redwolf501.top/Article/details/gtdmpuxzxn.html

Ruby: Time.now
来源：http://dali.jqgufenzy.top/Article/details/gtwfugjvwr.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hammf.cn/Article/details/gtgvytbbsv.html

[J02] 格式化输出
来源：http://dali.zhiwuduotai.top/Article/details/gtyxfkjktl.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ppjwa.cn/Article/details/gtmnuecduh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zdqjudy.top/Article/details/gtxollpekz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.9152youxi.cn/Article/details/gtdokudrwn.html

TS:   d.toISOString()
来源：http://dali.hammf.cn/Article/details/gtjejofxsw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.tanke756.top/Article/details/gtddlnchlf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shangyingyoupin.top/Article/details/gtkvfsqjuu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258.top/Article/details/gtveqyljle.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zycfv.cn/Article/details/gtqzjyinjt.html

[J03] 字符串解析为日期
来源：http://dali.svipenyu.cn/Article/details/gtdfjwuqon.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gotoacloud.top/Article/details/gtzhnmdejq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jianghu66.top/Article/details/gtaasytxuh.html

JS:   new Date("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtiexqsthu.html

TS:   new Date("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtsuvoamlt.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gtlbrtluio.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gtqjhrlhtx.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gtofemgiet.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jqgufenzy.top/Article/details/gtbdupqnud.html

[J04] 时间戳与日期互转
来源：http://dali.tanke756.top/Article/details/gtykdwvglh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jianghu66.top/Article/details/gtigonbrhb.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.nwbrower.top/Article/details/gtigisbtsf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.pengpengdd.cyou/Article/details/gtabqzcaxa.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.guowangkeji.top/Article/details/gtnwyqshrc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sufxvd.cn/Article/details/gthfrsgjke.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.daria6918.cn/Article/details/gtxzsiktgl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zdqjudy.top/Article/details/gtfawhdvly.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sxryk.cn/Article/details/gtzcozylgy.html

[J05] 时间加减（加 7 天）
来源：http://dali.bjfxy.top/Article/details/gtabteyvth.html

Py:   now + timedelta(days=7)
来源：http://dali.zhoulong.xyz/Article/details/gteszvfolh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cdnleiting.top/Article/details/gtvyutuqzp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgfzy.top/Article/details/gtbgrkurap.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhongyouzk.top/Article/details/gtpbakblfm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtekwyprjj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.tian-w.cn/Article/details/gtpflddbip.html

Ruby: Time.now + 7 * 86400
来源：http://dali.vqdsnc.cn/Article/details/gtwcwsndgb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shangyingyoupin.top/Article/details/gthahvnpjq.html

[J06] 计算两时间之差
来源：http://dali.nwbrower.top/Article/details/gttxyfylbm.html

Py:   (end - start).total_seconds()
来源：http://dali.yuxming.cn/Article/details/gtsutcbxmd.html

PHP:  $end->diff($start)->days;
来源：http://dali.wangdashe.top/Article/details/gtipnpkegu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.smart0.xyz/Article/details/gteovpvdnw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shanyushiyangtech.top/Article/details/gtawuukmuv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jqgfzy.top/Article/details/gtkbuvzyay.html

Go:   end.Sub(start).Hours()
来源：http://dali.xziqi.cn/Article/details/gtmbgdbmaf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.pycfn.com/Article/details/gthyfldfam.html

C#:   (end - start).TotalSeconds
来源：http://dali.feifeiyinyue.top/Article/details/gtvczrykqc.html

[J07] 比较两个日期
来源：http://dali.zhoulong.xyz/Article/details/gtamkkwtov.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangkeji.top/Article/details/gttbfebicy.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.dashuyun.cn/Article/details/gtlcwcojsa.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.aibaodan.cn/Article/details/gtfdtbhirg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxuanxn.top/Article/details/gtauubqcoj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.9152youxi.cn/Article/details/gtmbtgtaxt.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yvedp.cn/Article/details/gtekmllfcm.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cheryme.top/Article/details/gtpvzdjnne.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgajzldkb.html

[J08] 提取年月日与星期
来源：http://dali.cdnleiting.top/Article/details/gtddfcbrcy.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yongpay.top/Article/details/gtslpcbwjf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yj20258888.top/Article/details/gtkphexgyo.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.aizwys.cn/Article/details/gtmcqjmqbj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.iojbl.cn/Article/details/gtfgnniite.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.aizwys.cn/Article/details/gtaycnhgdv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.fzhhl.top/Article/details/gtaalkrrbd.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ydzc1.top/Article/details/gtjxeljtfx.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.tianlin.xyz/Article/details/gtgmrqtukq.html

[J09] 时区处理
来源：http://dali.hnxiangtu.top/Article/details/gtamjqtzpa.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yvedp.cn/Article/details/gteqfegunw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.dashuyun.cn/Article/details/gtpjbdnygy.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shzxlz.cn/Article/details/gtzxyxwvaf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hongshengwenyu.top/Article/details/gthtkhcwcp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.chenlongwang.top/Article/details/gtztssqylm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.nanxuanxn.top/Article/details/gtvcijzhjo.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.guowangkeji.top/Article/details/gtlnmhdrly.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shangyingyoupin.top/Article/details/gtvqlqrxgq.html

[J10] 取今天 / 本月第一天
来源：http://dali.jyoumei.cn/Article/details/gtnssrfaps.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.9152youxi.cn/Article/details/gtxypnqwjl.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.chenlongwang.top/Article/details/gtzjjvfyzy.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.mhx1999.top/Article/details/gtfzjnffvv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtffsuvzhq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jiagoushi.top/Article/details/gtlcanfrfm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cdnleiting.top/Article/details/gtyvobaebl.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.316326.xyz/Article/details/gtwsuysltk.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhijiandao.cn/Article/details/gtjtxpavam.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtfzgbjcry.html

K. JSON 与序列化
来源：http://dali.chenzaomai.com/Article/details/gtfgakpjzr.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtzyiwdgxh.html

[K01] 对象转 JSON 字符串
来源：http://dali.kuanghao11.cn/Article/details/gtekumzbvp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.redwolf501.top/Article/details/gtzmkpmefn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yueranfly.top/Article/details/gtkliusvka.html

JS:   JSON.stringify(obj)
来源：http://dali.xinyue.icu/Article/details/gtmdfgtdzq.html

TS:   JSON.stringify(obj)
来源：http://dali.yj20258.top/Article/details/gtifrhvxqm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jyoumei.cn/Article/details/gtbxpketaf.html

Go:   json.Marshal(obj)
来源：http://dali.sufxvd.cn/Article/details/gtkxumffll.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuyrjbrzq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtmwqdjuvv.html

[K02] JSON 字符串转对象
来源：http://dali.yuanzhike.top/Article/details/gtjgapdkkm.html

Py:   json.loads(s)
来源：http://dali.chenzaomai.com/Article/details/gtrpqnskde.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhoulong.xyz/Article/details/gtbdenswim.html

JS:   JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gtmihleavw.html

TS:   JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gtpatxwqaw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.nanxuanxn.top/Article/details/gtsnfjaala.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yj20258888.top/Article/details/gtmgfjzssh.html

Ruby: JSON.parse(s)
来源：http://dali.gogol.net.cn/Article/details/gtvjapbmtd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jianghu66.top/Article/details/gtrgqsvyul.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.nwbrower.top/Article/details/gtrtbwmatg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhongyouzk.top/Article/details/gtbtryctdv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xuetiantiany.cn/Article/details/gtjaootdml.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrndgdmpu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinqigufen.top/Article/details/gtsnuondit.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gzhubu.top/Article/details/gtnskcipta.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhixingplan.top/Article/details/gtvhhdtokz.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hfpthk.cn/Article/details/gtjrqwybvb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tian-w.cn/Article/details/gtooxlhybd.html

[K04] 读取 JSON 文件
来源：http://dali.cdnleiting.top/Article/details/gtylrsyucc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gzhubu.top/Article/details/gtuutsimpn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sysykeji.top/Article/details/gtoiuoztpb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenzaomai.com/Article/details/gtwqqvejmh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aibaodan.cn/Article/details/gtdcblrwyq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cdnleiting.top/Article/details/gtimkhybfa.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.nanxuanxn.top/Article/details/gtmkhwbrwt.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.iojbl.cn/Article/details/gtoaxrnzxq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hnxiangtu.top/Article/details/gtpmbsrimy.html

[K05] 深拷贝对象
来源：http://dali.cqqwz.cn/Article/details/gtwxjwmqje.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtrhjejciz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gaohongyu789.top/Article/details/gtbhtjnmlg.html

JS:   structuredClone(obj)
来源：http://dali.cheryme.top/Article/details/gtikpblycc.html

TS:   structuredClone(obj)
来源：http://dali.yj20258.top/Article/details/gtabqdmduc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.daria6918.cn/Article/details/gtrkmlmrtf.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xylfe.cn/Article/details/gtelvburuy.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttnntgdba.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.guowangkeji.top/Article/details/gtahfcnqdi.html

[K06] 解析 URL 查询串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtniohaphh.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.smart0.xyz/Article/details/gtobipkcul.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yangfankeji.com/Article/details/gtbcknbkrz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gzhubu.top/Article/details/gtwemdjepr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daxiang520.top/Article/details/gtfbznkahl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hywenlv.cn/Article/details/gturysqnmb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhengqikj.top/Article/details/gtmzrrcqvb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.svipenyu.cn/Article/details/gtlplsvcav.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jlsjyb.cn/Article/details/gtuhpzvupy.html

[K07] 进制转换
来源：http://dali.zhiwuduotai.top/Article/details/gtqtfukiwk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gtsyhfcfoe.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cdnleiting.top/Article/details/gtdoanmgmp.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gtwruiukge.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yj202588.top/Article/details/gtlgtkrdgl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gtgvrkfvqs.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cdnleiting.top/Article/details/gtzrhvanks.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.dianchejie.cn/Article/details/gtejdobqum.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gtwignwrdd.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.smart0.xyz/Article/details/gtrxreohpf.html

Py:   pickle.dumps(obj)
来源：http://dali.aibaodan.cn/Article/details/gtncayeoqj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.9152youxi.cn/Article/details/gtfzqyaphs.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hongshengwenyu.top/Article/details/gtzftgnets.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.svipenyu.cn/Article/details/gtlxoeknrq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ivvv.top/Article/details/gtzqypjeai.html

Go:   encoding/gob
来源：http://dali.gaohongyu789.top/Article/details/gtfizsixeg.html

Ruby: Marshal.dump(obj)
来源：http://dali.birdmap.top/Article/details/gtfhwcevej.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ybcxt.top/Article/details/gtdrlwzylt.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtbcrivgjy.html

L. 网络请求
来源：http://dali.aibaodan.cn/Article/details/gtfbuqyapc.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtceigviiq.html

[L01] 发送 GET 请求
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyezitkpp.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yonumen.top/Article/details/gtmhoshypl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.tanke756.top/Article/details/gtotoxqilh.html

JS:   await fetch(url)
来源：http://dali.316326.xyz/Article/details/gtgmyazyng.html

TS:   await fetch(url)
来源：http://dali.jiagoushi.top/Article/details/gthqrxdvkn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.chenjidiqi.icu/Article/details/gtgeejvlcx.html

Go:   resp, err := http.Get(url)
来源：http://dali.xinyue.icu/Article/details/gtozzjabah.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cheryme.top/Article/details/gtnvxjptig.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.nanxuanxn.top/Article/details/gtldfhmizr.html

[L02] 发送 POST JSON
来源：http://dali.c1oappe.top/Article/details/gtudxtkjkr.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.snrcjt.cn/Article/details/gtzdkxsqad.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yongpay.top/Article/details/gtotfmiksq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hammf.cn/Article/details/gtzrrogeto.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xziqi.cn/Article/details/gtarcqfzym.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.guannengcc.top/Article/details/gtyzfmsido.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cqqwz.cn/Article/details/gtxfmecmnt.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.nanxinkj.top/Article/details/gtrreiztqi.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cashguo.top/Article/details/gtzrhwaslc.html

[L03] 设置自定义请求头
来源：http://dali.mhx1999.top/Article/details/gtuiueeqgc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hfpthk.cn/Article/details/gtqxqqcpxn.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xylfe.cn/Article/details/gtytrmcjtf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxuanxn.top/Article/details/gtrjtrkerq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sxryk.cn/Article/details/gtgcsdxbva.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yongpay.top/Article/details/gtgovfsltr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cqqwz.cn/Article/details/gtyvhvtplg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yuxming.cn/Article/details/gtebnqpicl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jqgufenzy.top/Article/details/gtieqxnqvv.html

[L04] 设置超时
来源：http://dali.xuanzx.com/Article/details/gtlgfsqciv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinqigfzy.top/Article/details/gtetgewfwq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.9152youxi.cn/Article/details/gthtjbkflk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.9152youxi.cn/Article/details/gtevxvetdk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yonumen.top/Article/details/gtvlxfxazu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sysykeji.top/Article/details/gtdqsswdyl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.mhx1999.top/Article/details/gtbtonjlyu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ybcxt.top/Article/details/gtjxcohjai.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.tian-w.cn/Article/details/gtzfrprpkw.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gtajymzzlh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shuidangran.top/Article/details/gtrpvumrhh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yueranfly.top/Article/details/gtxlnhahfv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sweek.top/Article/details/gtowipztrq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.snrcjt.cn/Article/details/gtczubqbcb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinqigfzy.top/Article/details/gtrbjwgtpx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.wangdashe.top/Article/details/gtezrljnww.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yonumen.top/Article/details/gtoesyvqmq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtezrcqhmj.html

[L06] 解析响应为 JSON
来源：http://dali.cdnleiting.top/Article/details/gtjwmnfdgi.html

Py:   resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gtmfmgcxun.html

PHP:  json_decode($body, true);
来源：http://dali.yuxming.cn/Article/details/gtxbxbttzs.html

JS:   await resp.json()
来源：http://dali.hnqzz.top/Article/details/gtqrszgxsy.html

TS:   await resp.json()
来源：http://dali.vqdsnc.cn/Article/details/gtkoyzcmqh.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj20258.top/Article/details/gtbxbivxxz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.chenjidiqi.icu/Article/details/gtqhjilnxl.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nanxuanxn.top/Article/details/gtxzhfbcpq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.tian-w.cn/Article/details/gtcuqawuxu.html

[L07] 处理 HTTP 状态码
来源：http://dali.svipenyu.cn/Article/details/gtabsftckm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tanke756.top/Article/details/gtxhgxaali.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.dashuyun.cn/Article/details/gtljfbluql.html

JS:   resp.ok;  resp.status
来源：http://dali.daria6918.cn/Article/details/gtxzwcklze.html

TS:   resp.ok;  resp.status
来源：http://dali.zycfv.cn/Article/details/gtlkegowib.html

Java: resp.statusCode()
来源：http://dali.pengpengdd.cyou/Article/details/gtleixxakr.html

Go:   resp.StatusCode
来源：http://dali.snrcjt.cn/Article/details/gtyaofbomy.html

Ruby: resp.code.to_i
来源：http://dali.9152youxi.cn/Article/details/gtzwudjunb.html

C#:   (int)resp.StatusCode
来源：http://dali.shanyushiyangtech.top/Article/details/gtqingtqad.html

[L08] 并发请求多个地址
来源：http://dali.svipenyu.cn/Article/details/gtnqhejmqp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cucudq.cn/Article/details/gteubauows.html

PHP:  curl_multi_init() 系列
来源：http://dali.cucudq.cn/Article/details/gtcgwvthfz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigufen.top/Article/details/gtyutezari.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxinkj.top/Article/details/gtjyvswsfa.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmfuckiqp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinqigfzy.top/Article/details/gtpdzvplsq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.9152youxi.cn/Article/details/gtfwagohvb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhoulong.xyz/Article/details/gtcxhpegkh.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtqiuwzavj.html

M. 命令行 / 进程 / 环境
来源：http://dali.shangyingyoupin.top/Article/details/gtgjpoyreb.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtacuuihbz.html

[M01] 读取命令行参数
来源：http://dali.gzhubu.top/Article/details/gturvledjk.html

Py:   sys.argv[1:]
来源：http://dali.dianchejie.cn/Article/details/gtwaptrfpg.html

PHP:  $argv;  $argc;
来源：http://dali.andypj.xyz/Article/details/gtbbrwzcta.html

JS:   process.argv.slice(2)
来源：http://dali.chenzaomai.com/Article/details/gtbulenpnn.html

TS:   process.argv.slice(2)
来源：http://dali.xylfe.cn/Article/details/gtekmfrxvz.html

Java: args 数组（main 方法参数）
来源：http://dali.wangshuangyany.cn/Article/details/gtbhpmjiya.html

Go:   os.Args[1:]
来源：http://dali.hysaishi.cn/Article/details/gtpboatgij.html

Ruby: ARGV
来源：http://dali.snrcjt.cn/Article/details/gtroldxepr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yuxming.cn/Article/details/gtptkxinfb.html

[M02] 读取环境变量
来源：http://dali.9152youxi.cn/Article/details/gtbhhcffbx.html

Py:   os.environ.get("HOME")
来源：http://dali.sxryk.cn/Article/details/gtsqjqzmbm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.dashuyun.cn/Article/details/gtvkceqdow.html

JS:   process.env.HOME
来源：http://dali.ydzc1.top/Article/details/gtvonhewsi.html

TS:   process.env.HOME
来源：http://dali.jqgfzy.top/Article/details/gtujfwxzjc.html

Java: System.getenv("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gtstchelkx.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ppjwa.cn/Article/details/gtnbctkqsq.html

Ruby: ENV["HOME"]
来源：http://dali.svipenyu.cn/Article/details/gtarhhxtkh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.316326.xyz/Article/details/gtqnxlqxby.html

[M03] 执行外部命令
来源：http://dali.jinqigfzy.top/Article/details/gteneeeqxz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gaohongyu789.top/Article/details/gthdhsvthg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cashguo.top/Article/details/gtwsgznucy.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.pycfn.com/Article/details/gtvyxjtujk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.316326.xyz/Article/details/gtjynadgrb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.wangshuangyany.cn/Article/details/gtbffukuel.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqzvcnbrj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.andypj.xyz/Article/details/gtrucbmucr.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhoulong.xyz/Article/details/gtfitkfwsl.html

[M04] 获取当前工作目录
来源：http://dali.tanke756.top/Article/details/gtwexirzsl.html

Py:   os.getcwd()
来源：http://dali.nwbrower.top/Article/details/gtzdbifsrz.html

PHP:  getcwd();
来源：http://dali.jqgfzy.top/Article/details/gtrbnsxixy.html

JS:   process.cwd()
来源：http://dali.yj20258.top/Article/details/gttocndaid.html

TS:   process.cwd()
来源：http://dali.hysaishi.cn/Article/details/gtmqwjxggk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cucudq.cn/Article/details/gtjlukfnaj.html

Go:   os.Getwd()
来源：http://dali.jinqigfzy.top/Article/details/gtohkndmcm.html

Ruby: Dir.pwd
来源：http://dali.ivvv.top/Article/details/gtyrzbpnls.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.aizwys.cn/Article/details/gtxjxalhbj.html

[M05] 设置退出码
来源：http://dali.hammf.cn/Article/details/gtfxhchdmm.html

Py:   sys.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtagwimqou.html

PHP:  exit(1);
来源：http://dali.yonumen.top/Article/details/gtqzssrpyi.html

JS:   process.exit(1)
来源：http://dali.hnqzz.top/Article/details/gtiyivrlsz.html

TS:   process.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gtrieycpsn.html

Java: System.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gtwsdepscj.html

Go:   os.Exit(1)
来源：http://dali.dashuyun.cn/Article/details/gtlcaacbgz.html

Ruby: exit 1
来源：http://dali.ivvv.top/Article/details/gtyrepkqvc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.316326.xyz/Article/details/gtlqfowkfe.html

[M06] 向标准错误输出
来源：http://dali.shangyingyoupin.top/Article/details/gtzahpztnm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yueranfly.top/Article/details/gttnmnhswi.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xuetiantiany.cn/Article/details/gtszdejaeb.html

JS:   console.error("err")
来源：http://dali.zhengqikj.top/Article/details/gtgindzupe.html

TS:   console.error("err")
来源：http://dali.mhx1999.top/Article/details/gtmybcqawh.html

Java: System.err.println("err")
来源：http://dali.yvedp.cn/Article/details/gtekxmnhoa.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.smart0.xyz/Article/details/gthijvwldz.html

Ruby: warn "err"
来源：http://dali.jqgfzy.top/Article/details/gtgbivfzxs.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.havefunace.top/Article/details/gtbwdhghlb.html

[M07] 判断是否为主入口
来源：http://dali.quarkkingdee.top/Article/details/gthokqzfra.html


<!-- 参考信息 -->