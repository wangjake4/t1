代发 wailian999

J. 日期与时间
来源：http://dali.hysaishi.cn/Article/details/gtfuaqfctt.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gthevfskgn.html

[J01] 获取当前时间
来源：http://dali.hnqzz.top/Article/details/gtiuszeauw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gaohongyu789.top/Article/details/gtbarqpdfo.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.aibaodan.cn/Article/details/gthaexeoia.html

JS:   new Date();  Date.now()
来源：http://dali.tianlin.xyz/Article/details/gtarctnvxm.html

TS:   new Date();  Date.now()
来源：http://dali.zhengqikj.top/Article/details/gtnainaccn.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hnxiangtu.top/Article/details/gtsacrfujf.html

Go:   time.Now()
来源：http://dali.hysaishi.cn/Article/details/gtfegroruh.html

Ruby: Time.now
来源：http://dali.gaohongyu789.top/Article/details/gtrkkjbyob.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.svipenyu.cn/Article/details/gtnafiwgee.html

[J02] 格式化输出
来源：http://dali.jqgfzy.top/Article/details/gtttltjual.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj202588.top/Article/details/gtzvflwyii.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.havefunace.top/Article/details/gtlooafmuj.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.aizwys.cn/Article/details/gtuwgnltew.html

TS:   d.toISOString()
来源：http://dali.yuanzhike.top/Article/details/gtfxvnwvab.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.c1oappe.top/Article/details/gtoxtqxuzo.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.svipenyu.cn/Article/details/gtnkrfijpl.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtesuynyih.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gzhubu.top/Article/details/gtypoiknmi.html

[J03] 字符串解析为日期
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnavlhrqm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shangyingyoupin.top/Article/details/gtuvtfwtlm.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj20258.top/Article/details/gtkxhmkmbf.html

JS:   new Date("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gtysovwmlo.html

TS:   new Date("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gttzqjshbc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gtzbgjahhu.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gteyumzmfz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtejseqwpr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.guowangkeji.top/Article/details/gtlfovabyn.html

[J04] 时间戳与日期互转
来源：http://dali.xziqi.cn/Article/details/gtfwyommno.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.aizwys.cn/Article/details/gtuqpdufqm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.birdmap.top/Article/details/gtklkjjlev.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ppjwa.cn/Article/details/gtbjyasuzl.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hywenlv.cn/Article/details/gtelhopzkt.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.redwolf501.top/Article/details/gtspvkvlsw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.iojbl.cn/Article/details/gtwmdeuxzr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yvedp.cn/Article/details/gtactrwyph.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gttdccrksp.html

[J05] 时间加减（加 7 天）
来源：http://dali.birdmap.top/Article/details/gtpjmircvb.html

Py:   now + timedelta(days=7)
来源：http://dali.guowangkeji.top/Article/details/gtumzcwrwf.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xuetiantiany.cn/Article/details/gtcjkqyjrq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gzhubu.top/Article/details/gtcbqybxaw.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cdnleiting.top/Article/details/gtaxjgcizt.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yangfankeji.com/Article/details/gtmwhkodma.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xinyue.icu/Article/details/gttqenlotd.html

Ruby: Time.now + 7 * 86400
来源：http://dali.havefunace.top/Article/details/gttqzclfnl.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.9152youxi.cn/Article/details/gtvrupsjib.html

[J06] 计算两时间之差
来源：http://dali.zhiwuduotai.top/Article/details/gturmeluxi.html

Py:   (end - start).total_seconds()
来源：http://dali.jinghuilouyu.cn/Article/details/gtezgwapxe.html

PHP:  $end->diff($start)->days;
来源：http://dali.shuidangran.top/Article/details/gtndgorriz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hammf.cn/Article/details/gtbsnhmvmt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sxryk.cn/Article/details/gtvsbdwkqe.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.pengpengdd.cyou/Article/details/gthviiadxb.html

Go:   end.Sub(start).Hours()
来源：http://dali.havefunace.top/Article/details/gtqiqjeded.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shuidangran.top/Article/details/gtoaqcdwyo.html

C#:   (end - start).TotalSeconds
来源：http://dali.xziqi.cn/Article/details/gtbeajqrhz.html

[J07] 比较两个日期
来源：http://dali.yangfankeji.com/Article/details/gtdqkejsmy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gtfbipwpbv.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yj20258.top/Article/details/gtjftavxxq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.snrcjt.cn/Article/details/gtdxvbunez.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yuxming.cn/Article/details/gthanpffoa.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlidsupcx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ehwqpu.com/Article/details/gtfizvuumu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.snrcjt.cn/Article/details/gtsudhiako.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gtelkemfhy.html

[J08] 提取年月日与星期
来源：http://dali.sufxvd.cn/Article/details/gtxjsvltir.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cqqwz.cn/Article/details/gtkfplssbl.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yj20258888.top/Article/details/gtapvurleq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.haohaochexian.top/Article/details/gtxgnnpsxp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.iojbl.cn/Article/details/gtkehibkth.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jqgfzy.top/Article/details/gtefhsyunr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jqgfzy.top/Article/details/gteozugwhd.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenjidiqi.icu/Article/details/gtbdriyzwu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yongpay.top/Article/details/gtoybrqsyc.html

[J09] 时区处理
来源：http://dali.jinqigfzy.top/Article/details/gtpjvsnuly.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.bjfxy.top/Article/details/gtqgplrwqg.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yj202588.top/Article/details/gtqvuoewcv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pengpengdd.cyou/Article/details/gtuiouscyw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.svipenyu.cn/Article/details/gtqbzavyxa.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.chenjidiqi.icu/Article/details/gtneqvfamo.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.aizwys.cn/Article/details/gttkurwned.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.c1oappe.top/Article/details/gtnmwfdozl.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yvedp.cn/Article/details/gthrthajwe.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinqigufen.top/Article/details/gtqizyfeee.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfubitqii.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtelikhlwu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.fengsongda.top/Article/details/gtdtrhfcoj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.pycfn.com/Article/details/gtcepnrfii.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xziqi.cn/Article/details/gtcfmivfom.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ybcxt.top/Article/details/gtbhyzqril.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.bjfxy.top/Article/details/gtdqbnoztp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.nwbrower.top/Article/details/gtgurnromr.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtmfcktxst.html

K. JSON 与序列化
来源：http://dali.svipenyu.cn/Article/details/gtrbanutzg.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtdjqlprdm.html

[K01] 对象转 JSON 字符串
来源：http://dali.iojbl.cn/Article/details/gtkepstuqv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.daria6918.cn/Article/details/gtumhbzehz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cdnleiting.top/Article/details/gtsinuclhc.html

JS:   JSON.stringify(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtpqgnvxlj.html

TS:   JSON.stringify(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtitkiothk.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.dashuyun.cn/Article/details/gtwtrelqet.html

Go:   json.Marshal(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtujccmstj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yj202588.top/Article/details/gtxstuqdnz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtwgjxbhdj.html

[K02] JSON 字符串转对象
来源：http://dali.tianlin.xyz/Article/details/gtvirkitid.html

Py:   json.loads(s)
来源：http://dali.mhx1999.top/Article/details/gtuxwpdpti.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hammf.cn/Article/details/gtpsqlizvh.html

JS:   JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gtwfcadzlj.html

TS:   JSON.parse(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcryxfzip.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cdnleiting.top/Article/details/gtypjpthpk.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hfpthk.cn/Article/details/gtdemnrkdl.html

Ruby: JSON.parse(s)
来源：http://dali.hfpthk.cn/Article/details/gtvvsdalyv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gaohongyu789.top/Article/details/gtjpovgmeq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cqqwz.cn/Article/details/gtcpnruzgc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpswxazso.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yvedp.cn/Article/details/gtqsgwsokt.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jlsjyb.cn/Article/details/gtveotequm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnxiangtu.top/Article/details/gtukjbtklk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tianlin.xyz/Article/details/gtpfvqgalt.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtooxbxiwf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jqgfzy.top/Article/details/gtcwslgemk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jiagoushi.top/Article/details/gtrrbjieig.html

[K04] 读取 JSON 文件
来源：http://dali.daxiang520.top/Article/details/gtztsqebwx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yangfankeji.com/Article/details/gtvrxceroz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yangfankeji.com/Article/details/gtwrhaiatm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yvedp.cn/Article/details/gtuavdbegp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sysykeji.top/Article/details/gttdytzemp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpvlppfhk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.pengpengdd.cyou/Article/details/gtquauphdr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.wangdashe.top/Article/details/gtwfooglee.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yj20258888.top/Article/details/gtrdqzcipc.html

[K05] 深拷贝对象
来源：http://dali.chenjidiqi.icu/Article/details/gtreanvbbk.html

Py:   copy.deepcopy(obj)
来源：http://dali.9152youxi.cn/Article/details/gtyvgfknqo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.redwolf501.top/Article/details/gtmtigcnhl.html

JS:   structuredClone(obj)
来源：http://dali.cheryme.top/Article/details/gtcfjxcdpo.html

TS:   structuredClone(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjzjfvhdp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.kuanghao11.cn/Article/details/gtehdncmpi.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jqgufenzy.top/Article/details/gtsvlvnifp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hammf.cn/Article/details/gtzcopffas.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.nwbrower.top/Article/details/gtrmrshwek.html

[K06] 解析 URL 查询串
来源：http://dali.yj20258.top/Article/details/gtkhxchxoe.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sysykeji.top/Article/details/gttotouvgn.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.sxryk.cn/Article/details/gtfvfscnmg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yonumen.top/Article/details/gtsjjsgmtn.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cashguo.top/Article/details/gtuyazamvy.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gotoacloud.top/Article/details/gtmdybjgxq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gtomxexoho.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.daria6918.cn/Article/details/gtzxhalkkr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.0kj1m.cn/Article/details/gtprfprzui.html

[K07] 进制转换
来源：http://dali.yangfankeji.com/Article/details/gtndczlvzp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gtypnqttjw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxakrbsrz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gtrgyhypni.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gtoisgdhol.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gtxsppbvfg.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jiagoushi.top/Article/details/gtbbapkoli.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.redwolf501.top/Article/details/gtjksjfvqb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gtcydcqdpf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cucudq.cn/Article/details/gtmtolqacn.html

Py:   pickle.dumps(obj)
来源：http://dali.havefunace.top/Article/details/gtltrgnmbt.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zycfv.cn/Article/details/gtiwkhzmug.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.daxiang520.top/Article/details/gtmibcqqts.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdkcotqqn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhiwuduotai.top/Article/details/gtasepoepi.html

Go:   encoding/gob
来源：http://dali.tanke756.top/Article/details/gtgzazxulo.html

Ruby: Marshal.dump(obj)
来源：http://dali.yonumen.top/Article/details/gtxclsaeqj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gaohongyu789.top/Article/details/gtxqaqzztn.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtledxzzat.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gtipkksodf.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gthqzqaksn.html

[L01] 发送 GET 请求
来源：http://dali.daria6918.cn/Article/details/gtrtclyyjg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.gzhubu.top/Article/details/gtcvcdoznz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.9152youxi.cn/Article/details/gteujjqris.html

JS:   await fetch(url)
来源：http://dali.tian-w.cn/Article/details/gtuyccjude.html

TS:   await fetch(url)
来源：http://dali.vqdsnc.cn/Article/details/gtkwiodizh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.meibo888.top/Article/details/gtkjzjxrju.html

Go:   resp, err := http.Get(url)
来源：http://dali.pengpengdd.cyou/Article/details/gtzujglhop.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xziqi.cn/Article/details/gtutktytjl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.pengpengdd.cyou/Article/details/gttemyypij.html

[L02] 发送 POST JSON
来源：http://dali.haohaochexian.top/Article/details/gtkbdeeqhs.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.bjfxy.top/Article/details/gthvtdjvzs.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jianghu66.top/Article/details/gtbiwwnjfc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gotoacloud.top/Article/details/gtmtdnmuxu.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jiagoushi.top/Article/details/gtezsmjudr.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jqgufenzy.top/Article/details/gtxrygctft.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ybcxt.top/Article/details/gtzdzusrob.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.pycfn.com/Article/details/gtkzmmwhiy.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.feifeiyinyue.top/Article/details/gtznuksqgy.html

[L03] 设置自定义请求头
来源：http://dali.zhongyouzk.top/Article/details/gtodcgtwei.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ydzc1.top/Article/details/gtadckpxba.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xinyue.icu/Article/details/gtothptbox.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yueranfly.top/Article/details/gtshgwcgye.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgtaltdjl.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yueranfly.top/Article/details/gtddwodkrx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yuxming.cn/Article/details/gtrrklonis.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgshcspty.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yj20258.top/Article/details/gtlhltxshb.html

[L04] 设置超时
来源：http://dali.xylfe.cn/Article/details/gttmofhgqq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthcnkejcd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.haohaochexian.top/Article/details/gtsnryciiw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ivvv.top/Article/details/gtmxomamed.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.mhx1999.top/Article/details/gtdvddvnxo.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cucudq.cn/Article/details/gtnpnecmsi.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jqgfzy.top/Article/details/gtqftfwtoh.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jiagoushi.top/Article/details/gtnblgykzg.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jqgufenzy.top/Article/details/gtamduqpcv.html

[L05] 上传文件（multipart）
来源：http://dali.sysykeji.top/Article/details/gtuxkwlmzd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xuetiantiany.cn/Article/details/gtlfrivsiu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj20258.top/Article/details/gtdamfyins.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.dianchejie.cn/Article/details/gtxjtndwlz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigufen.top/Article/details/gtpajhtcjd.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zdqjudy.top/Article/details/gtztpaupcm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ydzc1.top/Article/details/gteeesedja.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhixingplan.top/Article/details/gtwtfsdmzw.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtiicdulxm.html

[L06] 解析响应为 JSON
来源：http://dali.ehwqpu.com/Article/details/gtbqabzeaw.html

Py:   resp.json()
来源：http://dali.ybcxt.top/Article/details/gttonnmyaj.html

PHP:  json_decode($body, true);
来源：http://dali.cdnleiting.top/Article/details/gtqzxabpio.html

JS:   await resp.json()
来源：http://dali.cucudq.cn/Article/details/gtiynanhtl.html

TS:   await resp.json()
来源：http://dali.zhixingplan.top/Article/details/gtfcamooho.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hnxiangtu.top/Article/details/gtgqcuwowb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hnxiangtu.top/Article/details/gtsxxudvpg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.havefunace.top/Article/details/gtbdbkzvmw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhongyouzk.top/Article/details/gttsfqjxyb.html

[L07] 处理 HTTP 状态码
来源：http://dali.316326.xyz/Article/details/gttqzrsfhv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhixingplan.top/Article/details/gtkwkdiirj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.tianlin.xyz/Article/details/gtomlqxsey.html

JS:   resp.ok;  resp.status
来源：http://dali.xinyue.icu/Article/details/gtzlkgexma.html

TS:   resp.ok;  resp.status
来源：http://dali.c1oappe.top/Article/details/gthmukwcer.html

Java: resp.statusCode()
来源：http://dali.gogol.net.cn/Article/details/gtnglksvcn.html

Go:   resp.StatusCode
来源：http://dali.hnqzz.top/Article/details/gtoshwwpnu.html

Ruby: resp.code.to_i
来源：http://dali.jlsjyb.cn/Article/details/gtcldvpieh.html

C#:   (int)resp.StatusCode
来源：http://dali.xylfe.cn/Article/details/gtfljcbnlo.html

[L08] 并发请求多个地址
来源：http://dali.aizwys.cn/Article/details/gtdfnfithv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhixingplan.top/Article/details/gtphrncifc.html

PHP:  curl_multi_init() 系列
来源：http://dali.cheryme.top/Article/details/gtxoygpeod.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jlsjyb.cn/Article/details/gtwmzvbmip.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jyoumei.cn/Article/details/gtfvbwcakf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yuanzhike.top/Article/details/gtoirgkwut.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ivvv.top/Article/details/gtylxsbcfj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.gotoacloud.top/Article/details/gtepjjhrls.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xuetiantiany.cn/Article/details/gtqormmqcw.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqiiukwhg.html

M. 命令行 / 进程 / 环境
来源：http://dali.yanxiufei.cn/Article/details/gtajyzllvb.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtujbswkgq.html

[M01] 读取命令行参数
来源：http://dali.guannengcc.top/Article/details/gtixurnvit.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gttnievczo.html

PHP:  $argv;  $argc;
来源：http://dali.ivvv.top/Article/details/gtisuqawsp.html

JS:   process.argv.slice(2)
来源：http://dali.cqqwz.cn/Article/details/gtxnvtbgoa.html

TS:   process.argv.slice(2)
来源：http://dali.cucudq.cn/Article/details/gtqfzciffp.html

Java: args 数组（main 方法参数）
来源：http://dali.redwolf501.top/Article/details/gtqpuemrmx.html

Go:   os.Args[1:]
来源：http://dali.chenzaomai.com/Article/details/gtaxuuekzd.html

Ruby: ARGV
来源：http://dali.xylfe.cn/Article/details/gtytlupvmo.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gzhubu.top/Article/details/gtopefflgq.html

[M02] 读取环境变量
来源：http://dali.svipenyu.cn/Article/details/gtxnnsywey.html

Py:   os.environ.get("HOME")
来源：http://dali.shuidangran.top/Article/details/gtsywensyi.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xylfe.cn/Article/details/gtfgeuzdhx.html

JS:   process.env.HOME
来源：http://dali.daria6918.cn/Article/details/gttjkupkei.html

TS:   process.env.HOME
来源：http://dali.shangyingyoupin.top/Article/details/gtkbplxgtt.html

Java: System.getenv("HOME")
来源：http://dali.yangfankeji.com/Article/details/gtnwjnmbgf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gtjvyoomdu.html

Ruby: ENV["HOME"]
来源：http://dali.jlsjyb.cn/Article/details/gtleqzfvwj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtupwglozq.html

[M03] 执行外部命令
来源：http://dali.jyoumei.cn/Article/details/gtkjvfvudr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yvedp.cn/Article/details/gtchzgzekj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cdnleiting.top/Article/details/gtwseszigh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zdqjudy.top/Article/details/gtnyhuehlh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.aizwys.cn/Article/details/gtpkasiliw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ppjwa.cn/Article/details/gtymlbttgu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.dianchejie.cn/Article/details/gtthjvfecq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.0kj1m.cn/Article/details/gtdqjcvacx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinghuilouyu.cn/Article/details/gtslcoyjyv.html

[M04] 获取当前工作目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gthlbuhfyd.html

Py:   os.getcwd()
来源：http://dali.mhx1999.top/Article/details/gtoxtimony.html

PHP:  getcwd();
来源：http://dali.hnxiangtu.top/Article/details/gtshonheip.html

JS:   process.cwd()
来源：http://dali.yj20258.top/Article/details/gtmdpexlsf.html

TS:   process.cwd()
来源：http://dali.zycfv.cn/Article/details/gtfckceqjj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhaomingkeji.xyz/Article/details/gthnmtabba.html

Go:   os.Getwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzwdehymy.html

Ruby: Dir.pwd
来源：http://dali.zdqjudy.top/Article/details/gtjzbfkrwk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yuanzhike.top/Article/details/gtbugdyqpr.html

[M05] 设置退出码
来源：http://dali.andypj.xyz/Article/details/gttwfekgxe.html

Py:   sys.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmvgydwqf.html

PHP:  exit(1);
来源：http://dali.fengsongda.top/Article/details/gtqiupndxl.html

JS:   process.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gtvpgufpai.html

TS:   process.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtojzypphv.html

Java: System.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtrcettiyc.html

Go:   os.Exit(1)
来源：http://dali.dianchejie.cn/Article/details/gtnsiyonqg.html

Ruby: exit 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqlwmqquw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shuidangran.top/Article/details/gtfucsaniy.html

[M06] 向标准错误输出
来源：http://dali.zhixingplan.top/Article/details/gtifnlbeft.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gotoacloud.top/Article/details/gthenrozrn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.havefunace.top/Article/details/gtantvcuut.html

JS:   console.error("err")
来源：http://dali.guowangkeji.top/Article/details/gtjsqpmjrd.html

TS:   console.error("err")
来源：http://dali.daria6918.cn/Article/details/gtyfiouxgq.html

Java: System.err.println("err")
来源：http://dali.jianghu66.top/Article/details/gtyutpmqef.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.fzhhl.top/Article/details/gtpyibyhdf.html

Ruby: warn "err"
来源：http://dali.guannengcc.top/Article/details/gtreuchmyo.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nwbrower.top/Article/details/gtowhpmdib.html

[M07] 判断是否为主入口
来源：http://dali.andypj.xyz/Article/details/gtiexxtfhz.html


<!-- 参考信息 -->