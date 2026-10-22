代发 wailian999

J. 日期与时间
来源：http://dali.smart0.xyz/Article/details/gtcrtgmuil.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtehpgwucx.html

[J01] 获取当前时间
来源：http://dali.xziqi.cn/Article/details/gtiiiemfkr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.chenzaomai.com/Article/details/gtvgklvixg.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yj202588.top/Article/details/gtlmvppbow.html

JS:   new Date();  Date.now()
来源：http://dali.zhongyouzk.top/Article/details/gtztquvuvm.html

TS:   new Date();  Date.now()
来源：http://dali.zdqjudy.top/Article/details/gtjyguftjc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nanxuanxn.top/Article/details/gtplywjjrc.html

Go:   time.Now()
来源：http://dali.nwbrower.top/Article/details/gtuotiubod.html

Ruby: Time.now
来源：http://dali.0kj1m.cn/Article/details/gtqcmnvaij.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.0kj1m.cn/Article/details/gtzqgsjgch.html

[J02] 格式化输出
来源：http://dali.shzxlz.cn/Article/details/gtmsctdtyu.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenzaomai.com/Article/details/gtvotsirfg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.chenlongwang.top/Article/details/gtklfzblhe.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.aizwys.cn/Article/details/gtmoxxfmem.html

TS:   d.toISOString()
来源：http://dali.shzxlz.cn/Article/details/gtwbqjhyfq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yuxming.cn/Article/details/gterqdizts.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.c1oappe.top/Article/details/gtgxjeobez.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zycfv.cn/Article/details/gthvcetaok.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zycfv.cn/Article/details/gtnnufiqko.html

[J03] 字符串解析为日期
来源：http://dali.c1oappe.top/Article/details/gtthuukcwm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shangyingyoupin.top/Article/details/gtexehijif.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrlnbeoiy.html

JS:   new Date("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gtjzkbyjbu.html

TS:   new Date("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gtnekxsewv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtabwjbdjh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gtrppzkehg.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gtlssvavir.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xuanzx.com/Article/details/gtcnyadgkm.html

[J04] 时间戳与日期互转
来源：http://dali.dashuyun.cn/Article/details/gtndeseqsh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxcnpwwqc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhijiandao.cn/Article/details/gtiqhceubr.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jianghu66.top/Article/details/gtirncqccr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.tianlin.xyz/Article/details/gtzwllyxms.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmqulkuio.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gogol.net.cn/Article/details/gtleossfsl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xuanzx.com/Article/details/gtoiwzpupq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.pycfn.com/Article/details/gtwsvyjrir.html

[J05] 时间加减（加 7 天）
来源：http://dali.jlsjyb.cn/Article/details/gtjbqtrjff.html

Py:   now + timedelta(days=7)
来源：http://dali.zhixingplan.top/Article/details/gttmjpeqqw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jqgfzy.top/Article/details/gtiuyqssug.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoctfuumv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgfzy.top/Article/details/gthjxtspvf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xuanzx.com/Article/details/gtqlbjhobd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.fengsongda.top/Article/details/gtgypunilt.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hnqzz.top/Article/details/gtwbstwrfz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.snrcjt.cn/Article/details/gtxiehuiut.html

[J06] 计算两时间之差
来源：http://dali.0kj1m.cn/Article/details/gtirapxclp.html

Py:   (end - start).total_seconds()
来源：http://dali.haohaochexian.top/Article/details/gtohqhgxgp.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhaomingkeji.xyz/Article/details/gttrermfui.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gogol.net.cn/Article/details/gtytdcnfcx.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yueranfly.top/Article/details/gtprmkslcn.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hnqzz.top/Article/details/gthkoknxqq.html

Go:   end.Sub(start).Hours()
来源：http://dali.yj20258888.top/Article/details/gtdvcwkuye.html

Ruby: end - start                 # 返回秒数
来源：http://dali.aibaodan.cn/Article/details/gtplnkgtld.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinyuanbaomall.cn/Article/details/gtovsoyucm.html

[J07] 比较两个日期
来源：http://dali.sysykeji.top/Article/details/gtnsbmpzdx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.bjfxy.top/Article/details/gtmyxcgnea.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cashguo.top/Article/details/gtlsjabbnj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.iojbl.cn/Article/details/gtvbqmadaj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.fengsongda.top/Article/details/gtenxczdbw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.wangshuangyany.cn/Article/details/gtiszkduas.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sweek.top/Article/details/gtvgnhkerr.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhengqikj.top/Article/details/gtkzmyvxwv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gtqchszlyh.html

[J08] 提取年月日与星期
来源：http://dali.daria6918.cn/Article/details/gtlxpegeof.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shanyushiyangtech.top/Article/details/gtzrkprsee.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yongpay.top/Article/details/gtzhncptfb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.nwbrower.top/Article/details/gtjzxzwfpy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ivvv.top/Article/details/gtbkxsssmw.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.tian-w.cn/Article/details/gtiqstbcfn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shzxlz.cn/Article/details/gtxrdbuvqi.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shanyushiyangtech.top/Article/details/gthvwfiibh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sxryk.cn/Article/details/gtapammfdc.html

[J09] 时区处理
来源：http://dali.aizwys.cn/Article/details/gtuocamwqi.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hywenlv.cn/Article/details/gthqgxwobf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.316326.xyz/Article/details/gtrvyxnjnk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xylfe.cn/Article/details/gteukisotv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daxiang520.top/Article/details/gtxpgvkdfr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ppjwa.cn/Article/details/gtwiiatzol.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.kuanghao11.cn/Article/details/gtgzeczgfb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cqqwz.cn/Article/details/gtqcebewpb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sysykeji.top/Article/details/gtklkflimo.html

[J10] 取今天 / 本月第一天
来源：http://dali.yuxming.cn/Article/details/gtsumrkmud.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.guannengcc.top/Article/details/gthhgakxhd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jqgufenzy.top/Article/details/gtbpqessbv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.nanxuanxn.top/Article/details/gtmvuwpzzc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zycfv.cn/Article/details/gtdstjhswv.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.bjfxy.top/Article/details/gtxoejamzh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zdqjudy.top/Article/details/gtxxhtgazf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cucudq.cn/Article/details/gtwjqkqrdr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenlongwang.top/Article/details/gttynswcmm.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gthpveffws.html

K. JSON 与序列化
来源：http://dali.yuxming.cn/Article/details/gtceqdognn.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtywnhkjne.html

[K01] 对象转 JSON 字符串
来源：http://dali.c1oappe.top/Article/details/gttyybnijl.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.guannengcc.top/Article/details/gtweiuudes.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gaohongyu789.top/Article/details/gtqapkdfnb.html

JS:   JSON.stringify(obj)
来源：http://dali.aizwys.cn/Article/details/gtwlqhiigp.html

TS:   JSON.stringify(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtajipibec.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhoulong.xyz/Article/details/gtmgjonuca.html

Go:   json.Marshal(obj)
来源：http://dali.jianghu66.top/Article/details/gtmdymsagd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gogol.net.cn/Article/details/gtjezygtcb.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.snrcjt.cn/Article/details/gtkdvyemsy.html

[K02] JSON 字符串转对象
来源：http://dali.yvedp.cn/Article/details/gtsyztuznq.html

Py:   json.loads(s)
来源：http://dali.c1oappe.top/Article/details/gtbxxvdrxd.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tanke756.top/Article/details/gtxxevbegb.html

JS:   JSON.parse(s)
来源：http://dali.tanke756.top/Article/details/gtpwkkychd.html

TS:   JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gtrfhncrbp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjcwhenqg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yongpay.top/Article/details/gtcjwtidky.html

Ruby: JSON.parse(s)
来源：http://dali.zhoulong.xyz/Article/details/gtxaqchrbt.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sxryk.cn/Article/details/gtssxxqgpm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gtlbemvmzb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhiwuduotai.top/Article/details/gtwhqhthby.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ppjwa.cn/Article/details/gtqracmgmz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jyoumei.cn/Article/details/gtdqhjjzjv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgufenzy.top/Article/details/gtjwowlswr.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgxeoaonz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gotoacloud.top/Article/details/gtboyftiiv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.snrcjt.cn/Article/details/gtptlzuzrj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yuxming.cn/Article/details/gtnpiyjoqj.html

[K04] 读取 JSON 文件
来源：http://dali.yanxiufei.cn/Article/details/gthozwbxyu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sxryk.cn/Article/details/gtcgthsync.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.haohaochexian.top/Article/details/gtkalgkptv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xylfe.cn/Article/details/gtoruvwpjr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ppjwa.cn/Article/details/gtadcgysmr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhiwuduotai.top/Article/details/gtwquwmumk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hnqzz.top/Article/details/gthqshqgkz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yj202588.top/Article/details/gtbppmgevq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yonumen.top/Article/details/gtnaeoelvi.html

[K05] 深拷贝对象
来源：http://dali.daria6918.cn/Article/details/gtytjsffmx.html

Py:   copy.deepcopy(obj)
来源：http://dali.nanxinkj.top/Article/details/gtdwwrrecu.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yueranfly.top/Article/details/gtoaywaczf.html

JS:   structuredClone(obj)
来源：http://dali.yvedp.cn/Article/details/gtrmzdaqxw.html

TS:   structuredClone(obj)
来源：http://dali.zdqjudy.top/Article/details/gtpibmrdef.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.guowangkeji.top/Article/details/gtlkfudkho.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinghuilouyu.cn/Article/details/gtjtumzojx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.snrcjt.cn/Article/details/gtdodjlhxn.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.chenlongwang.top/Article/details/gttukqhzui.html

[K06] 解析 URL 查询串
来源：http://dali.9152youxi.cn/Article/details/gtadcofman.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.nanxuanxn.top/Article/details/gtbkwelrwq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hammf.cn/Article/details/gtjvmjghjb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.feifeiyinyue.top/Article/details/gthusukfaz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.birdmap.top/Article/details/gtjoepfmsw.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.vqdsnc.cn/Article/details/gtcdmklbds.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhiwuduotai.top/Article/details/gtnasemzkh.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gtzebysgwz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjpcotqip.html

[K07] 进制转换
来源：http://dali.gotoacloud.top/Article/details/gtrjryjxor.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gtmrfkuutu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jiagoushi.top/Article/details/gtuhcakkuc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gtgreantkd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gttrpkexpb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gtjljhrtmi.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hywenlv.cn/Article/details/gtmpkstwqh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ivvv.top/Article/details/gtltiwugyw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.pycfn.com/Article/details/gtirjbfazc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yj20258.top/Article/details/gtvxfapzhd.html

Py:   pickle.dumps(obj)
来源：http://dali.cashguo.top/Article/details/gtqeokorge.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yuanzhike.top/Article/details/gtjyoebzqi.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cdnleiting.top/Article/details/gtrpaemldd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.316326.xyz/Article/details/gtiyynxakt.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.mhx1999.top/Article/details/gtklcewfvl.html

Go:   encoding/gob
来源：http://dali.jinghuilouyu.cn/Article/details/gtadthplut.html

Ruby: Marshal.dump(obj)
来源：http://dali.yuanzhike.top/Article/details/gtzwlirbvi.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.guannengcc.top/Article/details/gtjmqlqyhj.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtmostffga.html

L. 网络请求
来源：http://dali.jinghuilouyu.cn/Article/details/gtgzzeugjh.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtesmlypqp.html

[L01] 发送 GET 请求
来源：http://dali.shuidangran.top/Article/details/gtbpzlrzay.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yj20258888.top/Article/details/gtgmudvkgo.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.fengsongda.top/Article/details/gtcmofwzbz.html

JS:   await fetch(url)
来源：http://dali.ybcxt.top/Article/details/gtijzxadev.html

TS:   await fetch(url)
来源：http://dali.feifeiyinyue.top/Article/details/gtqehflcbb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hammf.cn/Article/details/gtrgumfovq.html

Go:   resp, err := http.Get(url)
来源：http://dali.pycfn.com/Article/details/gtnzwujrzp.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinqigfzy.top/Article/details/gtkynwgsyd.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cdnleiting.top/Article/details/gttfjuqtdi.html

[L02] 发送 POST JSON
来源：http://dali.yueranfly.top/Article/details/gtgoqixfut.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yj20258888.top/Article/details/gtjkwvqjry.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jlsjyb.cn/Article/details/gtranknvjf.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhoulong.xyz/Article/details/gtlcnpcbkt.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sxryk.cn/Article/details/gtzcszvltv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jyoumei.cn/Article/details/gtvuksmfml.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yonumen.top/Article/details/gtigkepkzi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.birdmap.top/Article/details/gtutmbiidp.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ehwqpu.com/Article/details/gtpgxcuuqh.html

[L03] 设置自定义请求头
来源：http://dali.yuxming.cn/Article/details/gtxwkowfkq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xziqi.cn/Article/details/gtnqphyjpr.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gzhubu.top/Article/details/gtxodttvls.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinghuilouyu.cn/Article/details/gtaonszdst.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gaohongyu789.top/Article/details/gtoeaiymvj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.0kj1m.cn/Article/details/gtqfhdhtgh.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.redwolf501.top/Article/details/gtgqnqstuv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yanxiufei.cn/Article/details/gtclvhmdwc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.nanxinkj.top/Article/details/gtyxtpxbdt.html

[L04] 设置超时
来源：http://dali.chenjidiqi.icu/Article/details/gteurpsodm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yj202588.top/Article/details/gtxfkmkwzy.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sufxvd.cn/Article/details/gtguviffkq.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gzhubu.top/Article/details/gtfseezhkf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fzhhl.top/Article/details/gtgwshpnhh.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yj20258888.top/Article/details/gtgozzxpls.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shuidangran.top/Article/details/gtobmgywlw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.chenlongwang.top/Article/details/gtsfoccxee.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.wangshuangyany.cn/Article/details/gthvkpeuwj.html

[L05] 上传文件（multipart）
来源：http://dali.jyoumei.cn/Article/details/gteiywalpe.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yongpay.top/Article/details/gtjywgfydb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjerkwhen.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.pycfn.com/Article/details/gtefrfrhbn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ehwqpu.com/Article/details/gtziybvjdy.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.nwbrower.top/Article/details/gtleebvmkp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shangyingyoupin.top/Article/details/gttvxgqafh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.redwolf501.top/Article/details/gtdzusqzzz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cashguo.top/Article/details/gtvclegfnl.html

[L06] 解析响应为 JSON
来源：http://dali.yueranfly.top/Article/details/gtbegiwuku.html

Py:   resp.json()
来源：http://dali.daxiang520.top/Article/details/gtqvddzdtb.html

PHP:  json_decode($body, true);
来源：http://dali.smart0.xyz/Article/details/gtpzxbfxaa.html

JS:   await resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gtqpejnziw.html

TS:   await resp.json()
来源：http://dali.yuxming.cn/Article/details/gtdazfkurh.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gtdepcsdwh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.tianlin.xyz/Article/details/gtzqmdulja.html

Ruby: JSON.parse(resp.body)
来源：http://dali.wangshuangyany.cn/Article/details/gtiqokmgjn.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hfpthk.cn/Article/details/gtyvddcvuc.html

[L07] 处理 HTTP 状态码
来源：http://dali.pengpengdd.cyou/Article/details/gtmdwiunmq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.chenlongwang.top/Article/details/gtyfickduh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yuxming.cn/Article/details/gthsdexdif.html

JS:   resp.ok;  resp.status
来源：http://dali.jinqigfzy.top/Article/details/gtjfqcwhbs.html

TS:   resp.ok;  resp.status
来源：http://dali.zycfv.cn/Article/details/gtfsxqyqok.html

Java: resp.statusCode()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtytixhsio.html

Go:   resp.StatusCode
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjivstvfg.html

Ruby: resp.code.to_i
来源：http://dali.havefunace.top/Article/details/gtchsqyvdd.html

C#:   (int)resp.StatusCode
来源：http://dali.jinqigfzy.top/Article/details/gtwafruhcq.html

[L08] 并发请求多个地址
来源：http://dali.hfpthk.cn/Article/details/gtnffagqgd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cashguo.top/Article/details/gtgbgiryiu.html

PHP:  curl_multi_init() 系列
来源：http://dali.jqgfzy.top/Article/details/gtvbznitth.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnxiangtu.top/Article/details/gtvjfttmii.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hammf.cn/Article/details/gtbnodyshd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hnxiangtu.top/Article/details/gtdmjqsbhy.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hysaishi.cn/Article/details/gtmqhqeqbt.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.haohaochexian.top/Article/details/gtubvibwfn.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.chenlongwang.top/Article/details/gtslibemdm.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtjrtithcs.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhongyouzk.top/Article/details/gtpnmbbfrp.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gttnrovkpq.html

[M01] 读取命令行参数
来源：http://dali.jinqigfzy.top/Article/details/gtlcedoqvm.html

Py:   sys.argv[1:]
来源：http://dali.zhoulong.xyz/Article/details/gtwejswtna.html

PHP:  $argv;  $argc;
来源：http://dali.havefunace.top/Article/details/gtgonwdozv.html

JS:   process.argv.slice(2)
来源：http://dali.zhoulong.xyz/Article/details/gtrltbprcg.html

TS:   process.argv.slice(2)
来源：http://dali.guannengcc.top/Article/details/gtdqiypyzc.html

Java: args 数组（main 方法参数）
来源：http://dali.bjfxy.top/Article/details/gtjsjiiooz.html

Go:   os.Args[1:]
来源：http://dali.yj202588.top/Article/details/gtvvlqujvd.html

Ruby: ARGV
来源：http://dali.ivvv.top/Article/details/gtqmrcvvkd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.aizwys.cn/Article/details/gtctrbeemg.html

[M02] 读取环境变量
来源：http://dali.iojbl.cn/Article/details/gtdwzmtdng.html

Py:   os.environ.get("HOME")
来源：http://dali.sxryk.cn/Article/details/gttybofriz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.dashuyun.cn/Article/details/gtpvtmwdox.html

JS:   process.env.HOME
来源：http://dali.gogol.net.cn/Article/details/gtgkiwqgmb.html

TS:   process.env.HOME
来源：http://dali.yonumen.top/Article/details/gthumkeiuf.html

Java: System.getenv("HOME")
来源：http://dali.smart0.xyz/Article/details/gtaxokdmri.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gtptrrlunr.html

Ruby: ENV["HOME"]
来源：http://dali.gzhubu.top/Article/details/gtxnbbsuwb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hnqzz.top/Article/details/gtratmfbrt.html

[M03] 执行外部命令
来源：http://dali.xinyue.icu/Article/details/gtvluoelok.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.fzhhl.top/Article/details/gtagoimmqe.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gzhubu.top/Article/details/gteijobdpy.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cdnleiting.top/Article/details/gtbwuvlnvt.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.aizwys.cn/Article/details/gtrptgoupv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqcjprnkx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtivbksyyl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cheryme.top/Article/details/gtqrhruriv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shuidangran.top/Article/details/gtsoshpqfx.html

[M04] 获取当前工作目录
来源：http://dali.gogol.net.cn/Article/details/gtjdypslhe.html

Py:   os.getcwd()
来源：http://dali.bjfxy.top/Article/details/gtndwdrpir.html

PHP:  getcwd();
来源：http://dali.dashuyun.cn/Article/details/gtwwolnmbx.html

JS:   process.cwd()
来源：http://dali.jinqigfzy.top/Article/details/gtuoptwlmf.html

TS:   process.cwd()
来源：http://dali.hnqzz.top/Article/details/gtmsssykyn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.aibaodan.cn/Article/details/gtwbwwlvka.html

Go:   os.Getwd()
来源：http://dali.ivvv.top/Article/details/gtgqmamsng.html

Ruby: Dir.pwd
来源：http://dali.tianlin.xyz/Article/details/gtfolwastf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hysaishi.cn/Article/details/gtulzbzlwh.html

[M05] 设置退出码
来源：http://dali.sysykeji.top/Article/details/gttwdwzojr.html

Py:   sys.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gthswcrpzw.html

PHP:  exit(1);
来源：http://dali.jinqigfzy.top/Article/details/gtriputksc.html

JS:   process.exit(1)
来源：http://dali.yj20258888.top/Article/details/gtojphklaa.html

TS:   process.exit(1)
来源：http://dali.sysykeji.top/Article/details/gtkmralxjv.html

Java: System.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gtwihodgak.html

Go:   os.Exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtqvyybuka.html

Ruby: exit 1
来源：http://dali.cashguo.top/Article/details/gtvxrauabs.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj202588.top/Article/details/gthqjbqwsl.html

[M06] 向标准错误输出
来源：http://dali.zhoulong.xyz/Article/details/gttltkmvog.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhiwuduotai.top/Article/details/gtbsigxywr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfbzrljmz.html

JS:   console.error("err")
来源：http://dali.andypj.xyz/Article/details/gtkxxlsqff.html

TS:   console.error("err")
来源：http://dali.zycfv.cn/Article/details/gtyuzvfbuf.html

Java: System.err.println("err")
来源：http://dali.yj20258.top/Article/details/gtnldliouk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sxryk.cn/Article/details/gtgfzyhlrp.html

Ruby: warn "err"
来源：http://dali.guannengcc.top/Article/details/gtkvmuacab.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinqigfzy.top/Article/details/gtumjczqdu.html

[M07] 判断是否为主入口
来源：http://dali.hnxiangtu.top/Article/details/gtyarehdzk.html


<!-- 参考信息 -->