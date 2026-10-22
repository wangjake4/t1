代发 wailian999

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jlsjyb.cn/Article/details/gt2ornzyesf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenzaomai.com/Article/details/gt2jetnmeox.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj202588.top/Article/details/gt2dzequpxx.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.birdmap.top/Article/details/gt2zzowumfy.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gogol.net.cn/Article/details/gt2tnuupcjz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.c1oappe.top/Article/details/gt2uccpbqpu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.birdmap.top/Article/details/gt2fufjkamw.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2usmghrme.html

J. 日期与时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2azhsmdxi.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2ajdwgqid.html

[J01] 获取当前时间
来源：http://dali.ehwqpu.com/Article/details/gt2qtkdegaf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nwbrower.top/Article/details/gt2wkmmhgjr.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fxolvzrk.html

JS:   new Date();  Date.now()
来源：http://dali.guowangkeji.top/Article/details/gt2gonhprgr.html

TS:   new Date();  Date.now()
来源：http://dali.jlsjyb.cn/Article/details/gt2ynkijuiy.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yj20258888.top/Article/details/gt2uuycwvdg.html

Go:   time.Now()
来源：http://dali.bjfxy.top/Article/details/gt2uwutqrap.html

Ruby: Time.now
来源：http://dali.jlsjyb.cn/Article/details/gt2vzljtuxy.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nwbrower.top/Article/details/gt2gnvsjamy.html

[J02] 格式化输出
来源：http://dali.0kj1m.cn/Article/details/gt2hhaqcvdu.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yvedp.cn/Article/details/gt2aerhtdqk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jyoumei.cn/Article/details/gt2tvytetxb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xuanzx.com/Article/details/gt2jtvmkjja.html

TS:   d.toISOString()
来源：http://dali.yj20258.top/Article/details/gt2xzqoedox.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.guowangkeji.top/Article/details/gt2ebrdnrwe.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.svipenyu.cn/Article/details/gt2enaijrcw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shzxlz.cn/Article/details/gt2cepsomyn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sweek.top/Article/details/gt2mnwutgky.html

[J03] 字符串解析为日期
来源：http://dali.ppjwa.cn/Article/details/gt2zlvoytqb.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yonumen.top/Article/details/gt2fkadrqch.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.havefunace.top/Article/details/gt2jyhujdog.html

JS:   new Date("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gt2wcbchwpd.html

TS:   new Date("2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gt2rgempvek.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gt2dexoaxyx.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bedfrgjt.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gt2mmwnbznw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhengqikj.top/Article/details/gt2sgkrdgbn.html

[J04] 时间戳与日期互转
来源：http://dali.c1oappe.top/Article/details/gt2aydzutkf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shzxlz.cn/Article/details/gt2qspznisi.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yueranfly.top/Article/details/gt2sjxgifpa.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sufxvd.cn/Article/details/gt2bhczojfk.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sufxvd.cn/Article/details/gt2ladbxhjs.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.aibaodan.cn/Article/details/gt2vwwycnkn.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.quarkkingdee.top/Article/details/gt2uxbasmab.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.wangdashe.top/Article/details/gt2djkgzcad.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gaohongyu789.top/Article/details/gt2aavztain.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhijiandao.cn/Article/details/gt2fcqqdmdu.html

Py:   now + timedelta(days=7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hykvwpwj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gaohongyu789.top/Article/details/gt2knlifrts.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hammf.cn/Article/details/gt2fnotuajt.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.meibo888.top/Article/details/gt2pclrrrba.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yj20258888.top/Article/details/gt2kvsbevhn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.feifeiyinyue.top/Article/details/gt2epdmrqic.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sxryk.cn/Article/details/gt2dlwcobik.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.aibaodan.cn/Article/details/gt2itnfhcnb.html

[J06] 计算两时间之差
来源：http://dali.kuanghao11.cn/Article/details/gt2ryhufzgq.html

Py:   (end - start).total_seconds()
来源：http://dali.pycfn.com/Article/details/gt2fidibzkw.html

PHP:  $end->diff($start)->days;
来源：http://dali.aibaodan.cn/Article/details/gt2xhgzjhny.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jiagoushi.top/Article/details/gt2edcdkusc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.0kj1m.cn/Article/details/gt2uubcdvqb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj20258888.top/Article/details/gt2ddzediof.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nliyisyo.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sweek.top/Article/details/gt2zlytobtj.html

C#:   (end - start).TotalSeconds
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sgzvayif.html

[J07] 比较两个日期
来源：http://dali.xylfe.cn/Article/details/gt2xxuocqkx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.daria6918.cn/Article/details/gt2krihesnm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.chenzaomai.com/Article/details/gt2culbahnm.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenjidiqi.icu/Article/details/gt2tcrokxlp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ovsouxwo.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2sdjwmenm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hysaishi.cn/Article/details/gt2gajnhiwu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zatbayla.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gt2vrideppx.html

[J08] 提取年月日与星期
来源：http://dali.yj20258888.top/Article/details/gt2kuiqzbec.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sufxvd.cn/Article/details/gt2qxqwbgay.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jqgfzy.top/Article/details/gt2sexywkba.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sweek.top/Article/details/gt2pbfgvbyr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinqigfzy.top/Article/details/gt2wstmuvwv.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rggigaka.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.chenlongwang.top/Article/details/gt2shjdwuku.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jqgfzy.top/Article/details/gt2fqdgellb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xuanzx.com/Article/details/gt2idusesll.html

[J09] 时区处理
来源：http://dali.havefunace.top/Article/details/gt2bphdsdjo.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nanxinkj.top/Article/details/gt2romajqnv.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.nwbrower.top/Article/details/gt2zkrbvkok.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuanzx.com/Article/details/gt2psddhopt.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hammf.cn/Article/details/gt2jfcalabe.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hywenlv.cn/Article/details/gt2nhxexpvt.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cheryme.top/Article/details/gt2uvcngfxh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xylfe.cn/Article/details/gt2tdkbdrgl.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zdqjudy.top/Article/details/gt2xyllkocl.html

[J10] 取今天 / 本月第一天
来源：http://dali.c1oappe.top/Article/details/gt2iodnfdkp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.svipenyu.cn/Article/details/gt2jdpmlram.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.birdmap.top/Article/details/gt2zjoxihbp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hfpthk.cn/Article/details/gt2ditupuiy.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.aibaodan.cn/Article/details/gt2smipqvue.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj20258888.top/Article/details/gt2hlzkgvfe.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.havefunace.top/Article/details/gt2smrmylbm.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shzxlz.cn/Article/details/gt2eehmdjfx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wftiopcg.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2inpzsvfh.html

K. JSON 与序列化
来源：http://dali.shuidangran.top/Article/details/gt2tgmsqawx.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2zepdxfhi.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2svxtcbmq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gaohongyu789.top/Article/details/gt2zxfywwoy.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.meibo888.top/Article/details/gt2scxfhxzy.html

JS:   JSON.stringify(obj)
来源：http://dali.xylfe.cn/Article/details/gt2ebfricvh.html

TS:   JSON.stringify(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2muwevwdt.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hammf.cn/Article/details/gt2rueoccjn.html

Go:   json.Marshal(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2ghifcrvw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sxryk.cn/Article/details/gt2ppgjswma.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2fcmunmiy.html

[K02] JSON 字符串转对象
来源：http://dali.sysykeji.top/Article/details/gt2udtpgezk.html

Py:   json.loads(s)
来源：http://dali.chenzaomai.com/Article/details/gt2ytjoajco.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mfflxqmb.html

JS:   JSON.parse(s)
来源：http://dali.havefunace.top/Article/details/gt2ckrisgpu.html

TS:   JSON.parse(s)
来源：http://dali.aibaodan.cn/Article/details/gt2mcmeawcr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gogol.net.cn/Article/details/gt2gzcpgpfl.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gzhubu.top/Article/details/gt2fqixeyxx.html

Ruby: JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gt2fxdkciir.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.fzhhl.top/Article/details/gt2owvuwkqm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.aibaodan.cn/Article/details/gt2ocdjcfoz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xuanzx.com/Article/details/gt2eplyphqm.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jlsjyb.cn/Article/details/gt2bgjzukku.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.andypj.xyz/Article/details/gt2bfmcsydm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jyoumei.cn/Article/details/gt2drzgtngx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2deoxlymm.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yueranfly.top/Article/details/gt2giyasqqj.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.mhx1999.top/Article/details/gt2fgvxbctn.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.bjfxy.top/Article/details/gt2xmogfaui.html

[K04] 读取 JSON 文件
来源：http://dali.redwolf501.top/Article/details/gt2qedxvkfr.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xuanzx.com/Article/details/gt2woswscpe.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xuetiantiany.cn/Article/details/gt2cdinxgfo.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hysaishi.cn/Article/details/gt2umbolfcv.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxinkj.top/Article/details/gt2dfprqsaj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.tian-w.cn/Article/details/gt2dfofvwmb.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vphxqqfo.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.pycfn.com/Article/details/gt2kgvsqnmj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sufxvd.cn/Article/details/gt2bodfpbcs.html

[K05] 深拷贝对象
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uihgnisx.html

Py:   copy.deepcopy(obj)
来源：http://dali.xziqi.cn/Article/details/gt2butcdipt.html

PHP:  unserialize(serialize($obj));
来源：http://dali.chenjidiqi.icu/Article/details/gt2fssycqyr.html

JS:   structuredClone(obj)
来源：http://dali.hammf.cn/Article/details/gt2ttdlzkop.html

TS:   structuredClone(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2tqkjskxm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jlsjyb.cn/Article/details/gt2mhessfkm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.0kj1m.cn/Article/details/gt2ereeeumu.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.iojbl.cn/Article/details/gt2psamyssq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tdlpkqns.html

[K06] 解析 URL 查询串
来源：http://dali.tian-w.cn/Article/details/gt2udykyast.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sysykeji.top/Article/details/gt2ostxoarh.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.chenjidiqi.icu/Article/details/gt2hbbvpzgr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.fengsongda.top/Article/details/gt2nlvsrjck.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jianghu66.top/Article/details/gt2djwjpxzh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.guannengcc.top/Article/details/gt2ojjcrwgp.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cheryme.top/Article/details/gt2uzlolpsw.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yvedp.cn/Article/details/gt2lqpvvbnc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.kuanghao11.cn/Article/details/gt2cdeqptti.html

[K07] 进制转换
来源：http://dali.yangfankeji.com/Article/details/gt2lnsqjjxc.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gt2gcbkfrmk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jqgufenzy.top/Article/details/gt2azkwjfjw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sjwzlkuc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gt2ugkfdtcv.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hammf.cn/Article/details/gt2ydjushyf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hnxiangtu.top/Article/details/gt2ebllstru.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hysaishi.cn/Article/details/gt2dmpjefqj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xrcbkipv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gaohongyu789.top/Article/details/gt2dikngbiu.html

Py:   pickle.dumps(obj)
来源：http://dali.fengsongda.top/Article/details/gt2gpxfpyjj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cdnleiting.top/Article/details/gt2vwqxslqc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.haohaochexian.top/Article/details/gt2nvyzzabv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.fengsongda.top/Article/details/gt2sqyohunm.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ybcxt.top/Article/details/gt2ksxhhoce.html

Go:   encoding/gob
来源：http://dali.dashuyun.cn/Article/details/gt2tbmgtovm.html

Ruby: Marshal.dump(obj)
来源：http://dali.birdmap.top/Article/details/gt2lcyglrai.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zycfv.cn/Article/details/gt2qdkrcmyf.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2sodwaydf.html

L. 网络请求
来源：http://dali.nwbrower.top/Article/details/gt2gpfrygem.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zermfozd.html

[L01] 发送 GET 请求
来源：http://dali.yanxiufei.cn/Article/details/gt2jbeaxpbq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ybcxt.top/Article/details/gt2tbxoggok.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yj20258.top/Article/details/gt2ohgjkldw.html

JS:   await fetch(url)
来源：http://dali.hysaishi.cn/Article/details/gt2drrtaqli.html

TS:   await fetch(url)
来源：http://dali.aibaodan.cn/Article/details/gt2cbsnjcyl.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.fengsongda.top/Article/details/gt2snqeokwp.html

Go:   resp, err := http.Get(url)
来源：http://dali.nanxinkj.top/Article/details/gt2czlwpvxe.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yj20258.top/Article/details/gt2agxnfalh.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uzbrocen.html

[L02] 发送 POST JSON
来源：http://dali.snrcjt.cn/Article/details/gt2jvtuklff.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gaohongyu789.top/Article/details/gt2ptdgwngf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yj20258888.top/Article/details/gt2qfoowjiz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shuidangran.top/Article/details/gt2loxrjqtu.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jiagoushi.top/Article/details/gt2oplohjse.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.guowangkeji.top/Article/details/gt2dnwgwibc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhengqikj.top/Article/details/gt2crdmeqdd.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cucudq.cn/Article/details/gt2fsfgomnk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pznjfxas.html

[L03] 设置自定义请求头
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ofukqwjj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cheryme.top/Article/details/gt2fgwbdxgt.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yuanzhike.top/Article/details/gt2bkvfsvua.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cdnleiting.top/Article/details/gt2hnoawkbc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.9152youxi.cn/Article/details/gt2woujibin.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.daxiang520.top/Article/details/gt2cmelcrhe.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.pycfn.com/Article/details/gt2sgtkdvll.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jyoumei.cn/Article/details/gt2osxtwsxs.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ivvv.top/Article/details/gt2phktudka.html

[L04] 设置超时
来源：http://dali.nwbrower.top/Article/details/gt2rpcajvut.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ybcxt.top/Article/details/gt2tnnjroiu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.0kj1m.cn/Article/details/gt2hphvbuxy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gaohongyu789.top/Article/details/gt2ndeowoas.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gaohongyu789.top/Article/details/gt2jdhxuqnj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhengqikj.top/Article/details/gt2tkzqihac.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.chenzaomai.com/Article/details/gt2iyiowauw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shangyingyoupin.top/Article/details/gt2uktgohgi.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.vqdsnc.cn/Article/details/gt2rscrpmca.html

[L05] 上传文件（multipart）
来源：http://dali.jlsjyb.cn/Article/details/gt2qajfxtvf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cdnleiting.top/Article/details/gt2fzogmckj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hnqzz.top/Article/details/gt2ksnawfgz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yonumen.top/Article/details/gt2uwfardnn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.0kj1m.cn/Article/details/gt2qnvevqtf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qaiziblo.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sysykeji.top/Article/details/gt2wlooocmr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zycfv.cn/Article/details/gt2efegxtev.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2prddijee.html

[L06] 解析响应为 JSON
来源：http://dali.nwbrower.top/Article/details/gt2ubssxybb.html

Py:   resp.json()
来源：http://dali.hnqzz.top/Article/details/gt2bupanxku.html

PHP:  json_decode($body, true);
来源：http://dali.cdnleiting.top/Article/details/gt2xylckhnz.html

JS:   await resp.json()
来源：http://dali.yj20258.top/Article/details/gt2ngobkpdt.html

TS:   await resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gt2mvqugtsp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.nanxinkj.top/Article/details/gt2udayqrbj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.iojbl.cn/Article/details/gt2xmnpdvxf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.9152youxi.cn/Article/details/gt2zcnahdwr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.redwolf501.top/Article/details/gt2nulercix.html

[L07] 处理 HTTP 状态码
来源：http://dali.chenjidiqi.icu/Article/details/gt2ecmhtwpm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.snrcjt.cn/Article/details/gt2pmgihftj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gotoacloud.top/Article/details/gt2osohjnpf.html

JS:   resp.ok;  resp.status
来源：http://dali.redwolf501.top/Article/details/gt2rabrudlr.html

TS:   resp.ok;  resp.status
来源：http://dali.wangshuangyany.cn/Article/details/gt2ctulfaud.html

Java: resp.statusCode()
来源：http://dali.shzxlz.cn/Article/details/gt2nnoduyww.html

Go:   resp.StatusCode
来源：http://dali.ppjwa.cn/Article/details/gt2ttnldhhn.html

Ruby: resp.code.to_i
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gpxklojt.html

C#:   (int)resp.StatusCode
来源：http://dali.sxryk.cn/Article/details/gt2ekzgsyca.html

[L08] 并发请求多个地址
来源：http://dali.yvedp.cn/Article/details/gt2lylvmppe.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yonumen.top/Article/details/gt2ungexbew.html

PHP:  curl_multi_init() 系列
来源：http://dali.daria6918.cn/Article/details/gt2moziipdi.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxinkj.top/Article/details/gt2dllrvkko.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tanke756.top/Article/details/gt2aoxtlwsf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.daria6918.cn/Article/details/gt2fznknwas.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhengqikj.top/Article/details/gt2lrkarabo.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.vqdsnc.cn/Article/details/gt2jdrgezhc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.haohaochexian.top/Article/details/gt2mnfbdbjz.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2imgduhui.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhoulong.xyz/Article/details/gt2uhvshdpl.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2jjybisju.html

[M01] 读取命令行参数
来源：http://dali.snrcjt.cn/Article/details/gt2vsorltgd.html

Py:   sys.argv[1:]
来源：http://dali.yangfankeji.com/Article/details/gt2hsohinmt.html

PHP:  $argv;  $argc;
来源：http://dali.zycfv.cn/Article/details/gt2dxltrose.html

JS:   process.argv.slice(2)
来源：http://dali.sxryk.cn/Article/details/gt2gihlevmo.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqfqsqh.html

Java: args 数组（main 方法参数）
来源：http://dali.yueranfly.top/Article/details/gt2ksavyflx.html

Go:   os.Args[1:]
来源：http://dali.aizwys.cn/Article/details/gt2xzaebycm.html

Ruby: ARGV
来源：http://dali.xuanzx.com/Article/details/gt2vkxzayme.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jianghu66.top/Article/details/gt2rrcotpqj.html

[M02] 读取环境变量
来源：http://dali.hnxiangtu.top/Article/details/gt2wtzqapbc.html

Py:   os.environ.get("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gt2uwiqtqsw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shzxlz.cn/Article/details/gt2vuvlsifg.html

JS:   process.env.HOME
来源：http://dali.gaohongyu789.top/Article/details/gt2qdcvmtvg.html

TS:   process.env.HOME
来源：http://dali.aizwys.cn/Article/details/gt2nxvkinrr.html

Java: System.getenv("HOME")
来源：http://dali.ydzc1.top/Article/details/gt2mowmwcdq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cdnleiting.top/Article/details/gt2adxgpfwo.html

Ruby: ENV["HOME"]
来源：http://dali.0kj1m.cn/Article/details/gt2nixxyfom.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cqqwz.cn/Article/details/gt2pbkhsmtb.html

[M03] 执行外部命令
来源：http://dali.sweek.top/Article/details/gt2wilauhhj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yanxiufei.cn/Article/details/gt2koirhiug.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.redwolf501.top/Article/details/gt2gbipjepf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuetiantiany.cn/Article/details/gt2ppwxwsxg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yongpay.top/Article/details/gt2wnfyfxac.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhengqikj.top/Article/details/gt2tyexcmqq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nanxuanxn.top/Article/details/gt2fpylpudd.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ydzc1.top/Article/details/gt2lsuptpme.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sxryk.cn/Article/details/gt2utotdbul.html

[M04] 获取当前工作目录
来源：http://dali.meibo888.top/Article/details/gt2brgiyyyq.html

Py:   os.getcwd()
来源：http://dali.andypj.xyz/Article/details/gt2nyvyjylb.html

PHP:  getcwd();
来源：http://dali.zhixingplan.top/Article/details/gt2xulyjrpj.html

JS:   process.cwd()
来源：http://dali.ydzc1.top/Article/details/gt2ypfapzcx.html

TS:   process.cwd()
来源：http://dali.yanxiufei.cn/Article/details/gt2gxisgskg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.smart0.xyz/Article/details/gt2wfdrdhno.html

Go:   os.Getwd()
来源：http://dali.tanke756.top/Article/details/gt2lqliygdd.html

Ruby: Dir.pwd
来源：http://dali.zycfv.cn/Article/details/gt2kswolgif.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zycfv.cn/Article/details/gt2lwllpgol.html

[M05] 设置退出码
来源：http://dali.yj202588.top/Article/details/gt2uodqcvfk.html

Py:   sys.exit(1)
来源：http://dali.hnqzz.top/Article/details/gt2mdkkvkwi.html

PHP:  exit(1);
来源：http://dali.yanxiufei.cn/Article/details/gt2mprnhwkx.html

JS:   process.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gt2kwtqjyjb.html

TS:   process.exit(1)
来源：http://dali.xuanzx.com/Article/details/gt2vduijots.html

Java: System.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gt2oucyvwfu.html

Go:   os.Exit(1)
来源：http://dali.daxiang520.top/Article/details/gt2eyabcmzn.html

Ruby: exit 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2saznmtqv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ppjwa.cn/Article/details/gt2bqdjxytt.html

[M06] 向标准错误输出
来源：http://dali.daria6918.cn/Article/details/gt2bmudvsmq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zyzwnsil.html


<!-- 参考信息 -->