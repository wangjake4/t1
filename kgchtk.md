代发 wailian999

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.redwolf501.top/Article/details/gtdbigaqmv.html

JS:   new Date();  Date.now()
来源：http://dali.guowangkeji.top/Article/details/gtxgmapcit.html

TS:   new Date();  Date.now()
来源：http://dali.yongpay.top/Article/details/gtcxqxocpg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.0kj1m.cn/Article/details/gtevxwkmel.html

Go:   time.Now()
来源：http://dali.zhongyouzk.top/Article/details/gttvnwnrzz.html

Ruby: Time.now
来源：http://dali.guannengcc.top/Article/details/gtwmtgrdag.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhiwuduotai.top/Article/details/gtlmaadsde.html

[J02] 格式化输出
来源：http://dali.yongpay.top/Article/details/gtiwrcyxph.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yangfankeji.com/Article/details/gtnrxgdkyu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.chenjidiqi.icu/Article/details/gtvsppkird.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.316326.xyz/Article/details/gtalmzonde.html

TS:   d.toISOString()
来源：http://dali.nwbrower.top/Article/details/gtnichsdzn.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.svipenyu.cn/Article/details/gtlrnmdjft.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hfpthk.cn/Article/details/gtxtasrkvs.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gzhubu.top/Article/details/gtqqlwraqi.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gaohongyu789.top/Article/details/gtletvjoad.html

[J03] 字符串解析为日期
来源：http://dali.gzhubu.top/Article/details/gtqwxvrfsl.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sufxvd.cn/Article/details/gtrgkdzdar.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yuxming.cn/Article/details/gturlsnifc.html

JS:   new Date("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gtpaucjmja.html

TS:   new Date("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gthtpmwhbn.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlhebhsbk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvuvqybfi.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gtokobzylj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ehwqpu.com/Article/details/gtwyaluoes.html

[J04] 时间戳与日期互转
来源：http://dali.yanxiufei.cn/Article/details/gtjlxhaozv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jqgufenzy.top/Article/details/gtsawprnps.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.pycfn.com/Article/details/gtdjhkcbxm.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhixingplan.top/Article/details/gtebrcymav.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hongshengwenyu.top/Article/details/gtounczaop.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.havefunace.top/Article/details/gtdmlfhlhr.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jiagoushi.top/Article/details/gtuhqaslhv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xziqi.cn/Article/details/gtrovunbyq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yongpay.top/Article/details/gtdvovwpkb.html

[J05] 时间加减（加 7 天）
来源：http://dali.shzxlz.cn/Article/details/gtfmuikzqs.html

Py:   now + timedelta(days=7)
来源：http://dali.pengpengdd.cyou/Article/details/gtqqhpnrxk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.chenjidiqi.icu/Article/details/gtewcxacfw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.mhx1999.top/Article/details/gthmqoafnl.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.smart0.xyz/Article/details/gtkkkrfbzl.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gaohongyu789.top/Article/details/gtqmcrezvw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ydzc1.top/Article/details/gtxqbqwlka.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jqgufenzy.top/Article/details/gtspagamkx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yj20258.top/Article/details/gtudgvlgjr.html

[J06] 计算两时间之差
来源：http://dali.cdnleiting.top/Article/details/gtrjjkxioz.html

Py:   (end - start).total_seconds()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtexqhjynz.html

PHP:  $end->diff($start)->days;
来源：http://dali.yj20258.top/Article/details/gtnehiijqw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yvedp.cn/Article/details/gtficeiyaa.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jqgfzy.top/Article/details/gtbxpntnkk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ivvv.top/Article/details/gtptzfcgcm.html

Go:   end.Sub(start).Hours()
来源：http://dali.tianlin.xyz/Article/details/gtzbknsgvt.html

Ruby: end - start                 # 返回秒数
来源：http://dali.nanxinkj.top/Article/details/gtcreazxfb.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj20258.top/Article/details/gtpdfdwwkn.html

[J07] 比较两个日期
来源：http://dali.snrcjt.cn/Article/details/gtwnaeglkd.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ybcxt.top/Article/details/gtdsdutayx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xziqi.cn/Article/details/gtipchqmzs.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sxryk.cn/Article/details/gtmwfthzjw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenjidiqi.icu/Article/details/gthkeekwkq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ydzc1.top/Article/details/gtvmykxild.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.c1oappe.top/Article/details/gtyopyzvuk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xylfe.cn/Article/details/gteiqxqsfs.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtahuwookh.html

[J08] 提取年月日与星期
来源：http://dali.chenzaomai.com/Article/details/gtmzsncnqr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.c1oappe.top/Article/details/gtvsgmkrfi.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhiwuduotai.top/Article/details/gtfiotxwgf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.316326.xyz/Article/details/gtcnzosszc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ydzc1.top/Article/details/gtcvddoupt.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hywenlv.cn/Article/details/gtslcvgrdk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.guannengcc.top/Article/details/gtrtokycgr.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shangyingyoupin.top/Article/details/gteolgnkxc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ehwqpu.com/Article/details/gtdibbgoym.html

[J09] 时区处理
来源：http://dali.cdnleiting.top/Article/details/gtdqgdmrla.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.havefunace.top/Article/details/gtycrnicqt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinqigufen.top/Article/details/gtynxctlzs.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shangyingyoupin.top/Article/details/gtmkilhbmy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtldbvhrsw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinqigufen.top/Article/details/gtzksfysvo.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.c1oappe.top/Article/details/gtzcnzeyov.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrwtdfecj.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zycfv.cn/Article/details/gteqrjdqcq.html

[J10] 取今天 / 本月第一天
来源：http://dali.shanyushiyangkeji.top/Article/details/gttjmfqubo.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.c1oappe.top/Article/details/gtelrfgqgs.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinqigfzy.top/Article/details/gtukvndtiq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.fzhhl.top/Article/details/gtloyhklcm.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gogol.net.cn/Article/details/gtbzqvuqvv.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj202588.top/Article/details/gtaqafbyhx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hnqzz.top/Article/details/gtvzhzwkus.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xylfe.cn/Article/details/gttthwxfzm.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xuanzx.com/Article/details/gtaypeuary.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtswdmlvxu.html

K. JSON 与序列化
来源：http://dali.daxiang520.top/Article/details/gtazzjrovy.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtveryszem.html

[K01] 对象转 JSON 字符串
来源：http://dali.hammf.cn/Article/details/gtvypooaya.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.tianlin.xyz/Article/details/gtzlhwiret.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.0kj1m.cn/Article/details/gtfaojtajx.html

JS:   JSON.stringify(obj)
来源：http://dali.316326.xyz/Article/details/gtzcxykqwt.html

TS:   JSON.stringify(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtgyvivdal.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yonumen.top/Article/details/gtjuatvind.html

Go:   json.Marshal(obj)
来源：http://dali.guannengcc.top/Article/details/gtdivqwaxh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xylfe.cn/Article/details/gtrpvxlven.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tanke756.top/Article/details/gtputuqqet.html

[K02] JSON 字符串转对象
来源：http://dali.jinqigufen.top/Article/details/gtpkiywgau.html

Py:   json.loads(s)
来源：http://dali.ppjwa.cn/Article/details/gtipgceaaf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jiagoushi.top/Article/details/gtcwunxkfq.html

JS:   JSON.parse(s)
来源：http://dali.xylfe.cn/Article/details/gtgtayzymq.html

TS:   JSON.parse(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkwlxumkm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.meibo888.top/Article/details/gtdtyvrjwz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.wangdashe.top/Article/details/gtkhaospnx.html

Ruby: JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gteupvmszm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zdqjudy.top/Article/details/gtmdwmveit.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.guowangkeji.top/Article/details/gtyupusesb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.quarkkingdee.top/Article/details/gtoanpigyy.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhongyouzk.top/Article/details/gtrugwinuz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gotoacloud.top/Article/details/gtmrwylsfu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258.top/Article/details/gthgydwbpm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtfcssyxcj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.mhx1999.top/Article/details/gtehgqdlqj.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtstzdtwvy.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinqigfzy.top/Article/details/gtfmguelof.html

[K04] 读取 JSON 文件
来源：http://dali.hnxiangtu.top/Article/details/gttisifnev.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yuanzhike.top/Article/details/gtltaaevcd.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hfpthk.cn/Article/details/gtpjgzslfv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenlongwang.top/Article/details/gtanslsbtb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jianghu66.top/Article/details/gtiqlcgcdr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.chenzaomai.com/Article/details/gtrluqpdnt.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgoxutzvw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yj202588.top/Article/details/gthvbjwkzh.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.fzhhl.top/Article/details/gtltulqoti.html

[K05] 深拷贝对象
来源：http://dali.dashuyun.cn/Article/details/gtgydiwiys.html

Py:   copy.deepcopy(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtnywdnkjk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ydzc1.top/Article/details/gtrdqsjoik.html

JS:   structuredClone(obj)
来源：http://dali.xylfe.cn/Article/details/gthxdwsfhy.html

TS:   structuredClone(obj)
来源：http://dali.nwbrower.top/Article/details/gtbvthdtww.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.meibo888.top/Article/details/gtaiogqqti.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.meibo888.top/Article/details/gtsouwgknb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.chenjidiqi.icu/Article/details/gtaekaanvp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinqigfzy.top/Article/details/gtirjxswfs.html

[K06] 解析 URL 查询串
来源：http://dali.ehwqpu.com/Article/details/gtvzmiibob.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jqgufenzy.top/Article/details/gteksznzml.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.chenlongwang.top/Article/details/gtrdheiivq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.c1oappe.top/Article/details/gthqmhzjco.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daria6918.cn/Article/details/gtezmuljfr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ydzc1.top/Article/details/gtxcthjytf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.bjfxy.top/Article/details/gtlrbtnazs.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gtwkbuiqlk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinqigfzy.top/Article/details/gtyhzxafyu.html

[K07] 进制转换
来源：http://dali.zhongyouzk.top/Article/details/gtknjdjefs.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtfogpnnxg.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhixingplan.top/Article/details/gtlmqrczqp.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gtgxeebrsh.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gtkpeqzxng.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gtothrwedx.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hnxiangtu.top/Article/details/gtcukhnswv.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.guannengcc.top/Article/details/gtjfhkghmr.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gtmjzikvnf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.wangshuangyany.cn/Article/details/gttdqdvjmw.html

Py:   pickle.dumps(obj)
来源：http://dali.yj202588.top/Article/details/gtdfntkywl.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hammf.cn/Article/details/gtzddwibcx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj202588.top/Article/details/gtyhsgvcyd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.nanxinkj.top/Article/details/gtorutolkx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xinyue.icu/Article/details/gttwlyjtyg.html

Go:   encoding/gob
来源：http://dali.yj202588.top/Article/details/gtqkwysdhr.html

Ruby: Marshal.dump(obj)
来源：http://dali.wangdashe.top/Article/details/gtlbfxiwqc.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hysaishi.cn/Article/details/gtajonalhe.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtpcipdhvz.html

L. 网络请求
来源：http://dali.feifeiyinyue.top/Article/details/gtchfirklz.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtxdpwvfox.html

[L01] 发送 GET 请求
来源：http://dali.pengpengdd.cyou/Article/details/gtrcxgniqa.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.tianlin.xyz/Article/details/gtqlkhertl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwxggtlkb.html

JS:   await fetch(url)
来源：http://dali.zhengqikj.top/Article/details/gtsmdvibel.html

TS:   await fetch(url)
来源：http://dali.nwbrower.top/Article/details/gtpqoxfozp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ydzc1.top/Article/details/gtqsnullaq.html

Go:   resp, err := http.Get(url)
来源：http://dali.cdnleiting.top/Article/details/gtznsruwuz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.316326.xyz/Article/details/gtloxzffqy.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jlsjyb.cn/Article/details/gtxprpjwmf.html

[L02] 发送 POST JSON
来源：http://dali.zhengqikj.top/Article/details/gtesocftdj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hammf.cn/Article/details/gtspkhekia.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.fzhhl.top/Article/details/gtcmmhdpfq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhixingplan.top/Article/details/gtnngoxqrk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuxming.cn/Article/details/gtfopkfqri.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.vqdsnc.cn/Article/details/gtqulqghmy.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yvedp.cn/Article/details/gtacgtdnkc.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ppjwa.cn/Article/details/gtqjzkxhuu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.havefunace.top/Article/details/gtakqziizk.html

[L03] 设置自定义请求头
来源：http://dali.ivvv.top/Article/details/gtvrpmbnjc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.c1oappe.top/Article/details/gtnjygmweq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sufxvd.cn/Article/details/gtnarrrzps.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzynhzcfh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tianlin.xyz/Article/details/gtwqgxcshs.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.tian-w.cn/Article/details/gtsnaqkrqb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.c1oappe.top/Article/details/gtnxqvjbkl.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.nanxinkj.top/Article/details/gtvzzvztub.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.bjfxy.top/Article/details/gtaswmfoet.html

[L04] 设置超时
来源：http://dali.zhoulong.xyz/Article/details/gtszhxcnqg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcqevngnb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtewegdlle.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jiagoushi.top/Article/details/gtqcyxnstd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zdqjudy.top/Article/details/gtogahjygs.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.andypj.xyz/Article/details/gtqjtjmosr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvcffqkie.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ivvv.top/Article/details/gtcxbvmjog.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xziqi.cn/Article/details/gtalmjaqiq.html

[L05] 上传文件（multipart）
来源：http://dali.xinyue.icu/Article/details/gthsxnajcf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hywenlv.cn/Article/details/gtekdbpavc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gogol.net.cn/Article/details/gtydvjqkzy.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhengqikj.top/Article/details/gtskefmxit.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsnaxgxdh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xuetiantiany.cn/Article/details/gtrwzqhnna.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jianghu66.top/Article/details/gtjkqdwnpr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shangyingyoupin.top/Article/details/gtfnuftkqw.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtkgsunzwr.html

[L06] 解析响应为 JSON
来源：http://dali.yuanzhike.top/Article/details/gttpdqwcgy.html

Py:   resp.json()
来源：http://dali.chenlongwang.top/Article/details/gtwxudaugn.html

PHP:  json_decode($body, true);
来源：http://dali.316326.xyz/Article/details/gtyhpyiyce.html

JS:   await resp.json()
来源：http://dali.dianchejie.cn/Article/details/gttobzpdfx.html

TS:   await resp.json()
来源：http://dali.nanxinkj.top/Article/details/gtgxlxxdhl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.andypj.xyz/Article/details/gtlpfytnbu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jiagoushi.top/Article/details/gtezvjirnm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cucudq.cn/Article/details/gtgvikzmpu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtszmmpxof.html

[L07] 处理 HTTP 状态码
来源：http://dali.dianchejie.cn/Article/details/gtpydbtbtj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.haohaochexian.top/Article/details/gtxtkixhjn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.redwolf501.top/Article/details/gtyamxvyms.html

JS:   resp.ok;  resp.status
来源：http://dali.tanke756.top/Article/details/gtjoxqszik.html

TS:   resp.ok;  resp.status
来源：http://dali.sysykeji.top/Article/details/gtluqcvrxk.html

Java: resp.statusCode()
来源：http://dali.hfpthk.cn/Article/details/gtcpvmcvyg.html

Go:   resp.StatusCode
来源：http://dali.zhiwuduotai.top/Article/details/gtzfgkrlvw.html

Ruby: resp.code.to_i
来源：http://dali.zhoulong.xyz/Article/details/gtyvxlygef.html

C#:   (int)resp.StatusCode
来源：http://dali.chenzaomai.com/Article/details/gtdrhsxnsv.html

[L08] 并发请求多个地址
来源：http://dali.feifeiyinyue.top/Article/details/gthdrnidnf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.wangshuangyany.cn/Article/details/gtevjahbuu.html

PHP:  curl_multi_init() 系列
来源：http://dali.xinyue.icu/Article/details/gtmnszivnp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gtwrhnkflx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cdnleiting.top/Article/details/gtwritrfno.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.316326.xyz/Article/details/gtnfkbxfmt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ivvv.top/Article/details/gtvbqzdige.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.chenjidiqi.icu/Article/details/gtaablorut.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.birdmap.top/Article/details/gtawdldzgr.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlrgcvrgj.html

M. 命令行 / 进程 / 环境
来源：http://dali.sufxvd.cn/Article/details/gtsrutjnfw.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtkynbmocx.html

[M01] 读取命令行参数
来源：http://dali.dianchejie.cn/Article/details/gtnlaztxbr.html

Py:   sys.argv[1:]
来源：http://dali.tian-w.cn/Article/details/gthzrztenv.html

PHP:  $argv;  $argc;
来源：http://dali.xylfe.cn/Article/details/gthjpujmcs.html

JS:   process.argv.slice(2)
来源：http://dali.nwbrower.top/Article/details/gttvaqoifo.html

TS:   process.argv.slice(2)
来源：http://dali.jlsjyb.cn/Article/details/gtlhpxwxxv.html

Java: args 数组（main 方法参数）
来源：http://dali.sufxvd.cn/Article/details/gtzmerllcy.html

Go:   os.Args[1:]
来源：http://dali.jinqigfzy.top/Article/details/gtowgpswjz.html

Ruby: ARGV
来源：http://dali.birdmap.top/Article/details/gtqwtsxzfp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.c1oappe.top/Article/details/gtcsgttoek.html

[M02] 读取环境变量
来源：http://dali.fengsongda.top/Article/details/gtnwwfaanp.html

Py:   os.environ.get("HOME")
来源：http://dali.tianlin.xyz/Article/details/gtyjltlgjw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhixingplan.top/Article/details/gttopsgpof.html

JS:   process.env.HOME
来源：http://dali.yj202588.top/Article/details/gtuxaxofhb.html

TS:   process.env.HOME
来源：http://dali.haohaochexian.top/Article/details/gtzqujvvlv.html

Java: System.getenv("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gttieewhbk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sysykeji.top/Article/details/gtkazposfc.html

Ruby: ENV["HOME"]
来源：http://dali.pengpengdd.cyou/Article/details/gtzttbpksc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sysykeji.top/Article/details/gtypufuwag.html

[M03] 执行外部命令
来源：http://dali.shzxlz.cn/Article/details/gtwxddzmle.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.daria6918.cn/Article/details/gtpwgcuubh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sufxvd.cn/Article/details/gtajgkfmlo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinqigfzy.top/Article/details/gtctuwfoyj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ybcxt.top/Article/details/gtxtbzwmgb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shuidangran.top/Article/details/gtzgscabrn.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shanyushiyangtech.top/Article/details/gtwdxsggnv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yuxming.cn/Article/details/gthtvgvvmk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.redwolf501.top/Article/details/gtoqsumisj.html

[M04] 获取当前工作目录
来源：http://dali.xuanzx.com/Article/details/gtujsjsypz.html

Py:   os.getcwd()
来源：http://dali.zhengqikj.top/Article/details/gtzfsbjzbh.html

PHP:  getcwd();
来源：http://dali.jqgfzy.top/Article/details/gtszkjjdsk.html

JS:   process.cwd()
来源：http://dali.gogol.net.cn/Article/details/gtqltquavy.html

TS:   process.cwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gtfonfveth.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yj202588.top/Article/details/gtrjtdcdcs.html

Go:   os.Getwd()
来源：http://dali.bjfxy.top/Article/details/gtctsyygme.html

Ruby: Dir.pwd
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnvdirjli.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sysykeji.top/Article/details/gtfklfcdzp.html

[M05] 设置退出码
来源：http://dali.jqgfzy.top/Article/details/gtgjzwwdng.html

Py:   sys.exit(1)
来源：http://dali.fengsongda.top/Article/details/gtnestzdsl.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gtigxwtbik.html

JS:   process.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gtfgupqkpz.html

TS:   process.exit(1)
来源：http://dali.yueranfly.top/Article/details/gtyffpeamy.html

Java: System.exit(1)
来源：http://dali.nwbrower.top/Article/details/gtuetrcfiq.html

Go:   os.Exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gthdkcixox.html

Ruby: exit 1
来源：http://dali.aibaodan.cn/Article/details/gtolpvsnaw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xuetiantiany.cn/Article/details/gtyjbljiro.html

[M06] 向标准错误输出
来源：http://dali.sysykeji.top/Article/details/gtfvigpfqg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.chenlongwang.top/Article/details/gtznmlwnqk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinqigufen.top/Article/details/gtgrmlscjd.html

JS:   console.error("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlckicujb.html

TS:   console.error("err")
来源：http://dali.daxiang520.top/Article/details/gtvdpthsne.html

Java: System.err.println("err")
来源：http://dali.zhongyouzk.top/Article/details/gtjqnofaim.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.316326.xyz/Article/details/gtcnbalsgx.html

Ruby: warn "err"
来源：http://dali.yangfankeji.com/Article/details/gtvsgrgrad.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.dianchejie.cn/Article/details/gtwawhdfxs.html

[M07] 判断是否为主入口
来源：http://dali.fengsongda.top/Article/details/gtkfqrklms.html

Py:   if __name__ == "__main__":
来源：http://dali.yanxiufei.cn/Article/details/gtgeewcbal.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.bjfxy.top/Article/details/gtqnuwvcis.html

JS:   require.main === module
来源：http://dali.ppjwa.cn/Article/details/gtadsmqtbt.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gtwshzsmsl.html


<!-- 参考信息 -->