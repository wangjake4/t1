代发 wailian999

J. 日期与时间
来源：http://dali.hfpthk.cn/Article/details/gttfngrfbs.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtrrnmkdyj.html

[J01] 获取当前时间
来源：http://dali.nanxinkj.top/Article/details/gtruymmnnh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.tianlin.xyz/Article/details/gtlovdoqao.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.9152youxi.cn/Article/details/gtnpczrqmf.html

JS:   new Date();  Date.now()
来源：http://dali.ivvv.top/Article/details/gtcjgjnfft.html

TS:   new Date();  Date.now()
来源：http://dali.daxiang520.top/Article/details/gtrugwbjsc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhengqikj.top/Article/details/gtebcxqvbk.html

Go:   time.Now()
来源：http://dali.yuanzhike.top/Article/details/gtaawuvwbl.html

Ruby: Time.now
来源：http://dali.cheryme.top/Article/details/gtdijamdvv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yj202588.top/Article/details/gtfpdlogcy.html

[J02] 格式化输出
来源：http://dali.xuetiantiany.cn/Article/details/gthkzqfsdo.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenjidiqi.icu/Article/details/gtehxkktai.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hfpthk.cn/Article/details/gtrsfwhayc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yj20258888.top/Article/details/gtsigvtfdx.html

TS:   d.toISOString()
来源：http://dali.aizwys.cn/Article/details/gtmtkvhayz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yuxming.cn/Article/details/gtwmoouxbi.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hysaishi.cn/Article/details/gtrykddjrm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sxryk.cn/Article/details/gtxvnscyba.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.mhx1999.top/Article/details/gtphpujnfj.html

[J03] 字符串解析为日期
来源：http://dali.9152youxi.cn/Article/details/gtpuvmsoun.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ydzc1.top/Article/details/gtjmjuiioa.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.fengsongda.top/Article/details/gtlvcefruu.html

JS:   new Date("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtbnqnikes.html

TS:   new Date("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gtxfgbaqtv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttpinpvkx.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtxrhvmema.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gtopcnxbre.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yj20258.top/Article/details/gtqvfhwflu.html

[J04] 时间戳与日期互转
来源：http://dali.yj20258888.top/Article/details/gtjttvgwmn.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hfpthk.cn/Article/details/gtrhembqci.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.c1oappe.top/Article/details/gtqrlyjstb.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ehwqpu.com/Article/details/gtnfgjjuzp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.iojbl.cn/Article/details/gtrqvecrzn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yj202588.top/Article/details/gtgpyymgrj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtquzfbtvb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdglrqcem.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sweek.top/Article/details/gtcgciyxog.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenjidiqi.icu/Article/details/gtfoeesgqb.html

Py:   now + timedelta(days=7)
来源：http://dali.jianghu66.top/Article/details/gtdnmswlzs.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xuanzx.com/Article/details/gthwwgczbi.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenzaomai.com/Article/details/gtivmtmcyy.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.c1oappe.top/Article/details/gteafmthyb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cheryme.top/Article/details/gtcooqycab.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yj20258888.top/Article/details/gtcykcmflm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hysaishi.cn/Article/details/gtpozunisp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hfpthk.cn/Article/details/gtjeuywtnu.html

[J06] 计算两时间之差
来源：http://dali.redwolf501.top/Article/details/gtuswtcqza.html

Py:   (end - start).total_seconds()
来源：http://dali.yj202588.top/Article/details/gtjcjpcrif.html

PHP:  $end->diff($start)->days;
来源：http://dali.wangdashe.top/Article/details/gtaecdqjny.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhiwuduotai.top/Article/details/gttvvejafp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj20258.top/Article/details/gttzgpgvon.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.smart0.xyz/Article/details/gtyzyatlxy.html

Go:   end.Sub(start).Hours()
来源：http://dali.xuetiantiany.cn/Article/details/gtapirlsxt.html

Ruby: end - start                 # 返回秒数
来源：http://dali.chenzaomai.com/Article/details/gtdaytetkf.html

C#:   (end - start).TotalSeconds
来源：http://dali.xuetiantiany.cn/Article/details/gtejugcyse.html

[J07] 比较两个日期
来源：http://dali.0kj1m.cn/Article/details/gtnqqfaazp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.meibo888.top/Article/details/gtjcltmzfp.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jqgufenzy.top/Article/details/gtlsmoigqf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtspnfysvc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.pengpengdd.cyou/Article/details/gttbpgowdy.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.snrcjt.cn/Article/details/gtsbrlilan.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.tianlin.xyz/Article/details/gtwbfbgogy.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gtpwjygyfk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gtwmlkciyq.html

[J08] 提取年月日与星期
来源：http://dali.0kj1m.cn/Article/details/gtwptxnshe.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.guowangkeji.top/Article/details/gtceborhbu.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.tian-w.cn/Article/details/gtdjzkvlrr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yuanzhike.top/Article/details/gthfefwwhp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tian-w.cn/Article/details/gtagxitfxe.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.haohaochexian.top/Article/details/gtrogtldnc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yj202588.top/Article/details/gtpfhitzmw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpitafgdq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jlsjyb.cn/Article/details/gtpkpnsrff.html

[J09] 时区处理
来源：http://dali.gzhubu.top/Article/details/gttrrsuxci.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yangfankeji.com/Article/details/gtbanofrxz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.feifeiyinyue.top/Article/details/gtgtmkapcf.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhiwuduotai.top/Article/details/gtiayksfyc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cheryme.top/Article/details/gtoisgivxu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.fzhhl.top/Article/details/gtmepfcffs.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.dashuyun.cn/Article/details/gteswdqviw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.havefunace.top/Article/details/gtizcwoqko.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.fengsongda.top/Article/details/gtdqskepwu.html

[J10] 取今天 / 本月第一天
来源：http://dali.316326.xyz/Article/details/gtiaoiiorv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zdqjudy.top/Article/details/gtkrovrttr.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtytrwshma.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sweek.top/Article/details/gtyokcejrx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hnqzz.top/Article/details/gteuaonqmd.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.316326.xyz/Article/details/gtuzspvrbt.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cdnleiting.top/Article/details/gttjvoukan.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.snrcjt.cn/Article/details/gtvdtzevoo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.bjfxy.top/Article/details/gtrrsjicye.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtxqjuulqb.html

K. JSON 与序列化
来源：http://dali.wangdashe.top/Article/details/gthdvhcpcw.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gttugtwymq.html

[K01] 对象转 JSON 字符串
来源：http://dali.guannengcc.top/Article/details/gtefvtatop.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yonumen.top/Article/details/gtbglxajcx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.sysykeji.top/Article/details/gtagfcztjf.html

JS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gthkssbghf.html

TS:   JSON.stringify(obj)
来源：http://dali.ppjwa.cn/Article/details/gtidgaelgj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yj202588.top/Article/details/gthmcdctzd.html

Go:   json.Marshal(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtovmhaeaz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sufxvd.cn/Article/details/gtjczixylr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yuxming.cn/Article/details/gtbrtncjge.html

[K02] JSON 字符串转对象
来源：http://dali.jinqigfzy.top/Article/details/gtpsjvvqmy.html

Py:   json.loads(s)
来源：http://dali.tian-w.cn/Article/details/gtfmcmmhdq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ivvv.top/Article/details/gtkmaylkiw.html

JS:   JSON.parse(s)
来源：http://dali.0kj1m.cn/Article/details/gtofvgwgvj.html

TS:   JSON.parse(s)
来源：http://dali.jinqigufen.top/Article/details/gtwkgttdmq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdwtpyhes.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.pycfn.com/Article/details/gtwnbujjiv.html

Ruby: JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gtazibdtyo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.9152youxi.cn/Article/details/gtdrhhujgc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.chenzaomai.com/Article/details/gtectmsnci.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zycfv.cn/Article/details/gtvlflywrj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.fzhhl.top/Article/details/gtjjdleskh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.iojbl.cn/Article/details/gtwybolsgc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqbczpfdr.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.mhx1999.top/Article/details/gtvnxgrgkj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.svipenyu.cn/Article/details/gtdquspvtp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gogol.net.cn/Article/details/gtrbemetac.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.chenzaomai.com/Article/details/gtbemneprw.html

[K04] 读取 JSON 文件
来源：http://dali.ybcxt.top/Article/details/gttmttwuwp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yanxiufei.cn/Article/details/gtoxrrirkd.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shangyingyoupin.top/Article/details/gtnuxqeptp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jqgfzy.top/Article/details/gtqtigylfp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yangfankeji.com/Article/details/gthkujtyro.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yanxiufei.cn/Article/details/gtarwrlgwi.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hywenlv.cn/Article/details/gtfoyevdky.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiqsehypd.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zycfv.cn/Article/details/gtzekbkitj.html

[K05] 深拷贝对象
来源：http://dali.chenjidiqi.icu/Article/details/gtszemmyig.html

Py:   copy.deepcopy(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtqzmlllpn.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gaohongyu789.top/Article/details/gtaqnkdyph.html

JS:   structuredClone(obj)
来源：http://dali.ehwqpu.com/Article/details/gtqdzojvlg.html

TS:   structuredClone(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtufksmcii.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xuetiantiany.cn/Article/details/gtfppublce.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.bjfxy.top/Article/details/gtshmxbxgx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.kuanghao11.cn/Article/details/gtetgidhhi.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shangyingyoupin.top/Article/details/gthmdpvdvg.html

[K06] 解析 URL 查询串
来源：http://dali.wangshuangyany.cn/Article/details/gtbcvbceqk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jlsjyb.cn/Article/details/gtxfixexsz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yuxming.cn/Article/details/gttkwumoku.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.fzhhl.top/Article/details/gtvthdubwe.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.meibo888.top/Article/details/gtrixudxaf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpetdxatj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gtafcwlesr.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdlyvlkea.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinqigfzy.top/Article/details/gthffkhxxc.html

[K07] 进制转换
来源：http://dali.cqqwz.cn/Article/details/gtayaoouys.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gtkyophhdc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hysaishi.cn/Article/details/gtjppmkspa.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gtrkqljmzg.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdqhiluln.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtiatgfxuw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.pycfn.com/Article/details/gtrizkylsz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hnqzz.top/Article/details/gtljhtotfl.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtxzgkwfsa.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.fengsongda.top/Article/details/gtkhqzelio.html

Py:   pickle.dumps(obj)
来源：http://dali.hywenlv.cn/Article/details/gtrxxlqeda.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hnqzz.top/Article/details/gtnheyidji.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj202588.top/Article/details/gtqberevnc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shzxlz.cn/Article/details/gtewnfzkhu.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinyuanbaomall.cn/Article/details/gtncikiagx.html

Go:   encoding/gob
来源：http://dali.tianlin.xyz/Article/details/gtrdwrkrgi.html

Ruby: Marshal.dump(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtgmverqzf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jlsjyb.cn/Article/details/gtyrapmdap.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtkfuiektf.html

L. 网络请求
来源：http://dali.hammf.cn/Article/details/gttcgavsqg.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtonrrumgk.html

[L01] 发送 GET 请求
来源：http://dali.hnqzz.top/Article/details/gtuzqwtajo.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.guowangkeji.top/Article/details/gtkonyxnwt.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yj202588.top/Article/details/gtrkhqwrsx.html

JS:   await fetch(url)
来源：http://dali.pycfn.com/Article/details/gtwdhwimbp.html

TS:   await fetch(url)
来源：http://dali.xuetiantiany.cn/Article/details/gttpokpleu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.iojbl.cn/Article/details/gtntmowzgf.html

Go:   resp, err := http.Get(url)
来源：http://dali.guowangkeji.top/Article/details/gtvliaxroh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.feifeiyinyue.top/Article/details/gtahvsvubm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ivvv.top/Article/details/gtblgjlcgx.html

[L02] 发送 POST JSON
来源：http://dali.nwbrower.top/Article/details/gtirgnjixk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shangyingyoupin.top/Article/details/gtfexrwdcm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.tanke756.top/Article/details/gtulsdkkeh.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj20258888.top/Article/details/gtgedcibhd.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ppjwa.cn/Article/details/gtexdjdtwy.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gogol.net.cn/Article/details/gtoltlchzc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shuidangran.top/Article/details/gtdgiyjdbv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jiagoushi.top/Article/details/gtgcvwvbxe.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zdqjudy.top/Article/details/gtdnjzmenn.html

[L03] 设置自定义请求头
来源：http://dali.pengpengdd.cyou/Article/details/gtrxbrpxsg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sufxvd.cn/Article/details/gtqsckqqzd.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ivvv.top/Article/details/gtcwkwlrmk.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gotoacloud.top/Article/details/gtvevkbzxq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tianlin.xyz/Article/details/gtnmejblvx.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.9152youxi.cn/Article/details/gtxwlnbszj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yanxiufei.cn/Article/details/gtuinsmcdb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yj20258.top/Article/details/gtojxkndbx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.aibaodan.cn/Article/details/gtmbvktsau.html

[L04] 设置超时
来源：http://dali.cqqwz.cn/Article/details/gtgjgideet.html

Py:   requests.get(url, timeout=5)
来源：http://dali.sxryk.cn/Article/details/gtogkieswg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtimviadpc.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqxxbavtj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuanzx.com/Article/details/gtniqepwwc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gogol.net.cn/Article/details/gtdbvxjoic.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gotoacloud.top/Article/details/gtyrazgtri.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.vqdsnc.cn/Article/details/gttxzbstte.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xuetiantiany.cn/Article/details/gtfxvpnpfk.html

[L05] 上传文件（multipart）
来源：http://dali.havefunace.top/Article/details/gtenypiyxr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shangyingyoupin.top/Article/details/gtqbvchvli.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yuanzhike.top/Article/details/gtgxxnhrkv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhengqikj.top/Article/details/gtmhevqrdm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zycfv.cn/Article/details/gtngmuvmij.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yj20258.top/Article/details/gtgzpxdrcv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.snrcjt.cn/Article/details/gtzgdlwxxs.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zycfv.cn/Article/details/gttyewyksn.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtsizpdhqr.html

[L06] 解析响应为 JSON
来源：http://dali.guannengcc.top/Article/details/gtksntcwap.html

Py:   resp.json()
来源：http://dali.cashguo.top/Article/details/gtojaylhvl.html

PHP:  json_decode($body, true);
来源：http://dali.havefunace.top/Article/details/gtcqjhlnfx.html

JS:   await resp.json()
来源：http://dali.chenlongwang.top/Article/details/gtgiptbddm.html

TS:   await resp.json()
来源：http://dali.haohaochexian.top/Article/details/gtgesoaksj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hnxiangtu.top/Article/details/gttuwjqaxo.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhixingplan.top/Article/details/gtrifcwrqn.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xuanzx.com/Article/details/gtxvcqggmj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.haohaochexian.top/Article/details/gtlchrddax.html

[L07] 处理 HTTP 状态码
来源：http://dali.bjfxy.top/Article/details/gtcucnlqkb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.pycfn.com/Article/details/gtfxwjbltm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.tian-w.cn/Article/details/gtwyyhmmyc.html

JS:   resp.ok;  resp.status
来源：http://dali.gzhubu.top/Article/details/gtfbfjevre.html

TS:   resp.ok;  resp.status
来源：http://dali.xylfe.cn/Article/details/gtbooylebx.html

Java: resp.statusCode()
来源：http://dali.hfpthk.cn/Article/details/gtamxwbhah.html

Go:   resp.StatusCode
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlthzktdz.html

Ruby: resp.code.to_i
来源：http://dali.zhiwuduotai.top/Article/details/gtdcqflonw.html

C#:   (int)resp.StatusCode
来源：http://dali.9152youxi.cn/Article/details/gtedhjqygy.html

[L08] 并发请求多个地址
来源：http://dali.dashuyun.cn/Article/details/gtontdbhhm.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sufxvd.cn/Article/details/gtizzrspkx.html

PHP:  curl_multi_init() 系列
来源：http://dali.snrcjt.cn/Article/details/gtypjpbiep.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuanzhike.top/Article/details/gtfdlqsgip.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhengqikj.top/Article/details/gttcnchibv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jqgfzy.top/Article/details/gtztmtqkrk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hnqzz.top/Article/details/gtxciepzjg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ivvv.top/Article/details/gtdicecifd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.bjfxy.top/Article/details/gtovthapfg.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtqvysehoc.html

M. 命令行 / 进程 / 环境
来源：http://dali.bjfxy.top/Article/details/gtxipdqvln.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtyxgjmial.html

[M01] 读取命令行参数
来源：http://dali.xinyue.icu/Article/details/gttipnyuyl.html

Py:   sys.argv[1:]
来源：http://dali.hysaishi.cn/Article/details/gtpfiiixxx.html

PHP:  $argv;  $argc;
来源：http://dali.yj202588.top/Article/details/gtovafisjq.html

JS:   process.argv.slice(2)
来源：http://dali.xziqi.cn/Article/details/gtwlpsfqza.html

TS:   process.argv.slice(2)
来源：http://dali.zdqjudy.top/Article/details/gtfmhswnfu.html

Java: args 数组（main 方法参数）
来源：http://dali.yanxiufei.cn/Article/details/gtyqpitlpc.html

Go:   os.Args[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwxvgksxd.html

Ruby: ARGV
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfhssknun.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ppjwa.cn/Article/details/gtieetsbwh.html

[M02] 读取环境变量
来源：http://dali.sufxvd.cn/Article/details/gtkfnaznfe.html

Py:   os.environ.get("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlxlfonbv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.iojbl.cn/Article/details/gtozzptxdt.html

JS:   process.env.HOME
来源：http://dali.gogol.net.cn/Article/details/gtilijixfo.html

TS:   process.env.HOME
来源：http://dali.redwolf501.top/Article/details/gtvlzqlrvx.html

Java: System.getenv("HOME")
来源：http://dali.hammf.cn/Article/details/gtgqjtkcyw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gtekinaegf.html

Ruby: ENV["HOME"]
来源：http://dali.nwbrower.top/Article/details/gtokosowdm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gtbwskznvs.html

[M03] 执行外部命令
来源：http://dali.shzxlz.cn/Article/details/gtmspascbd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yueranfly.top/Article/details/gtjxaozrhr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.nanxinkj.top/Article/details/gtxziblpkp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtcatwfyez.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuanzx.com/Article/details/gtkxuexpgi.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinqigufen.top/Article/details/gtqvjcbclg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tanke756.top/Article/details/gtekqoegas.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.dashuyun.cn/Article/details/gtlupsucsf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yangfankeji.com/Article/details/gtcdqefscn.html

[M04] 获取当前工作目录
来源：http://dali.wangshuangyany.cn/Article/details/gtewboshde.html

Py:   os.getcwd()
来源：http://dali.yvedp.cn/Article/details/gtjnmblcrt.html

PHP:  getcwd();
来源：http://dali.jlsjyb.cn/Article/details/gtojhlwykc.html

JS:   process.cwd()
来源：http://dali.cucudq.cn/Article/details/gtlqcbcaoi.html

TS:   process.cwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtclzegunk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cucudq.cn/Article/details/gtofmghssg.html

Go:   os.Getwd()
来源：http://dali.ivvv.top/Article/details/gtmrssmmlc.html

Ruby: Dir.pwd
来源：http://dali.yangfankeji.com/Article/details/gtnsnvrhew.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.aibaodan.cn/Article/details/gtugijggum.html

[M05] 设置退出码
来源：http://dali.ydzc1.top/Article/details/gtjxxtnarz.html

Py:   sys.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtovrcmciv.html

PHP:  exit(1);
来源：http://dali.jianghu66.top/Article/details/gtseooyqaj.html

JS:   process.exit(1)
来源：http://dali.iojbl.cn/Article/details/gtwyfgwlrx.html

TS:   process.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtikeiczwg.html

Java: System.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gtcmmfgsud.html

Go:   os.Exit(1)
来源：http://dali.chenlongwang.top/Article/details/gtjvbyunhf.html

Ruby: exit 1
来源：http://dali.zhongyouzk.top/Article/details/gtxpoconds.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyzukkgqr.html

[M06] 向标准错误输出
来源：http://dali.jinqigufen.top/Article/details/gtvdlqqtno.html

Py:   print("err", file=sys.stderr)
来源：http://dali.chenzaomai.com/Article/details/gtkggdkyvz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jqgufenzy.top/Article/details/gtedstwnlg.html

JS:   console.error("err")
来源：http://dali.yj20258888.top/Article/details/gtxidzpotd.html

TS:   console.error("err")
来源：http://dali.cheryme.top/Article/details/gtrkkdtzfw.html

Java: System.err.println("err")
来源：http://dali.yvedp.cn/Article/details/gtvjwdqqvs.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.smart0.xyz/Article/details/gtodqkbcpw.html

Ruby: warn "err"
来源：http://dali.shanyushiyangtech.top/Article/details/gtlgnjhodm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttiaebhmk.html

[M07] 判断是否为主入口
来源：http://dali.guowangkeji.top/Article/details/gtbelezpyf.html


<!-- 参考信息 -->