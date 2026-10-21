代发 wailian999

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhoulong.xyz/Article/details/gtacfbnnpr.html

[I07] 忽略大小写与多行模式
来源：http://dali.ydzc1.top/Article/details/gtcejqihob.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttevelwik.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xylfe.cn/Article/details/gtticczvul.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.andypj.xyz/Article/details/gtzztrxdtx.html

TS:   /error/gim
来源：http://dali.ivvv.top/Article/details/gtkatihmom.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gotoacloud.top/Article/details/gtpvvqayjl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.birdmap.top/Article/details/gtjtkhmxoj.html

Ruby: s.scan(/error/i)
来源：http://dali.yvedp.cn/Article/details/gtjcpjuvoe.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.meibo888.top/Article/details/gtiykbpiqo.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.tanke756.top/Article/details/gtnsgmgymd.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhoulong.xyz/Article/details/gtnsioqqbe.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jiagoushi.top/Article/details/gtqtulplpc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhengqikj.top/Article/details/gtmhsaeukw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ehwqpu.com/Article/details/gtwygcimgi.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yj20258888.top/Article/details/gtqolevpjb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ybcxt.top/Article/details/gtnpyvhowe.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xuanzx.com/Article/details/gtvvlgmbwu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sufxvd.cn/Article/details/gtogyydvzm.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtjtaofxat.html

J. 日期与时间
来源：http://dali.yanxiufei.cn/Article/details/gtyhsqbhrx.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gttmmpreri.html

[J01] 获取当前时间
来源：http://dali.dianchejie.cn/Article/details/gtzomdmoxb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nanxinkj.top/Article/details/gtupdzicth.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.nwbrower.top/Article/details/gthgpoqqki.html

JS:   new Date();  Date.now()
来源：http://dali.yonumen.top/Article/details/gtxinwrdlc.html

TS:   new Date();  Date.now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgtalckvw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.haohaochexian.top/Article/details/gtdlbaeija.html

Go:   time.Now()
来源：http://dali.nanxinkj.top/Article/details/gtdcieneoc.html

Ruby: Time.now
来源：http://dali.gaohongyu789.top/Article/details/gtfobuwuif.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.tanke756.top/Article/details/gtugvpgtoy.html

[J02] 格式化输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gttyhgsrhf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dianchejie.cn/Article/details/gtimqqzltf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhoulong.xyz/Article/details/gtushdjwzh.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.fzhhl.top/Article/details/gteuimwyyg.html

TS:   d.toISOString()
来源：http://dali.zhengqikj.top/Article/details/gtiulyurrp.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.vqdsnc.cn/Article/details/gtadkpgbfb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hnxiangtu.top/Article/details/gtkccubiky.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sufxvd.cn/Article/details/gtboxraqjw.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gzhubu.top/Article/details/gteaorfxzv.html

[J03] 字符串解析为日期
来源：http://dali.aizwys.cn/Article/details/gtqxuoladx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.316326.xyz/Article/details/gtyhaxaali.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.snrcjt.cn/Article/details/gtrvqedahx.html

JS:   new Date("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtmvrnysva.html

TS:   new Date("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gtaaaorpsu.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gtggihjned.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gtkjnpsuux.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gtoowvntdi.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xuetiantiany.cn/Article/details/gtmsfzlvzk.html

[J04] 时间戳与日期互转
来源：http://dali.chenzaomai.com/Article/details/gtjnewvzix.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yonumen.top/Article/details/gtwynlbiyu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yonumen.top/Article/details/gtipwcefnv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinqigufen.top/Article/details/gtniapadyp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfjpvraep.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.haohaochexian.top/Article/details/gtpuepcqmr.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.snrcjt.cn/Article/details/gtcacijzcs.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hysaishi.cn/Article/details/gtjjjcjiwi.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.dashuyun.cn/Article/details/gtjtrmnylr.html

[J05] 时间加减（加 7 天）
来源：http://dali.gogol.net.cn/Article/details/gtwnexzlfs.html

Py:   now + timedelta(days=7)
来源：http://dali.haohaochexian.top/Article/details/gtzoxrzirh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yonumen.top/Article/details/gtfrtzshjk.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pycfn.com/Article/details/gtxiskhmzw.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuanzhike.top/Article/details/gtpjeeuxkc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xinyue.icu/Article/details/gtibgbwbze.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.chenlongwang.top/Article/details/gtihnuazvm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.smart0.xyz/Article/details/gtmllxelof.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvmqnwxbf.html

[J06] 计算两时间之差
来源：http://dali.hnxiangtu.top/Article/details/gtpawlnuqi.html

Py:   (end - start).total_seconds()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrrqlpolp.html

PHP:  $end->diff($start)->days;
来源：http://dali.yj20258888.top/Article/details/gtvsqaljop.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cashguo.top/Article/details/gtyxgygudj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.fengsongda.top/Article/details/gterzjwmne.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.andypj.xyz/Article/details/gtieocwiee.html

Go:   end.Sub(start).Hours()
来源：http://dali.chenlongwang.top/Article/details/gtnrylwjxu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjfvyuxxs.html

C#:   (end - start).TotalSeconds
来源：http://dali.hammf.cn/Article/details/gtdufvdvfi.html

[J07] 比较两个日期
来源：http://dali.guannengcc.top/Article/details/gttussbzxp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hysaishi.cn/Article/details/gtmmqiaezw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.kuanghao11.cn/Article/details/gtojbezuel.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.aibaodan.cn/Article/details/gtzodyzuns.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hfpthk.cn/Article/details/gtjsqyudsj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.snrcjt.cn/Article/details/gtoqueepfs.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hnxiangtu.top/Article/details/gtedsuecyp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yonumen.top/Article/details/gtmqjnhtfr.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.haohaochexian.top/Article/details/gtrywscwxy.html

[J08] 提取年月日与星期
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwgnbogor.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcvxsmsvs.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.aibaodan.cn/Article/details/gtpcisried.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.haohaochexian.top/Article/details/gtpssltdqq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.meibo888.top/Article/details/gtxndnfzul.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.pycfn.com/Article/details/gtjikhjpxq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.redwolf501.top/Article/details/gtcnhcfrtv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zycfv.cn/Article/details/gtopwtvvbw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhongyouzk.top/Article/details/gtakhqseyu.html

[J09] 时区处理
来源：http://dali.jinqigfzy.top/Article/details/gtmyiodqfv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinqigufen.top/Article/details/gtvsszfwmx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yonumen.top/Article/details/gtselftwxt.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aibaodan.cn/Article/details/gtrkctuopl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hongshengwenyu.top/Article/details/gtmdbgllfz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ehwqpu.com/Article/details/gthmcwsvzd.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.fengsongda.top/Article/details/gtmgkyeesk.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.aibaodan.cn/Article/details/gtwfmibtzv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.mhx1999.top/Article/details/gtxgffekec.html

[J10] 取今天 / 本月第一天
来源：http://dali.nanxuanxn.top/Article/details/gthphaqtic.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gogol.net.cn/Article/details/gtnduehhdx.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhiwuduotai.top/Article/details/gtmgtiquwb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrptalobc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtogoxtseg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhengqikj.top/Article/details/gtwzbtffjx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ppjwa.cn/Article/details/gtwkxjyocp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gzhubu.top/Article/details/gtdjljigfi.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhoulong.xyz/Article/details/gtgpqwwvkg.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtuizkmayd.html

K. JSON 与序列化
来源：http://dali.iojbl.cn/Article/details/gtwevbcpvc.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtjfqhcjeb.html

[K01] 对象转 JSON 字符串
来源：http://dali.snrcjt.cn/Article/details/gtppjmstfm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.tanke756.top/Article/details/gtwlmemddv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hfpthk.cn/Article/details/gtiktojwao.html

JS:   JSON.stringify(obj)
来源：http://dali.gzhubu.top/Article/details/gtgjhcyqrq.html

TS:   JSON.stringify(obj)
来源：http://dali.wangdashe.top/Article/details/gtgyezmkdv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.nwbrower.top/Article/details/gtovqveolf.html

Go:   json.Marshal(obj)
来源：http://dali.bjfxy.top/Article/details/gtagshrcwx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.iojbl.cn/Article/details/gtvndjvxup.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtrtksebcr.html

[K02] JSON 字符串转对象
来源：http://dali.0kj1m.cn/Article/details/gtobsjcxds.html

Py:   json.loads(s)
来源：http://dali.9152youxi.cn/Article/details/gtmmtqocta.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.feifeiyinyue.top/Article/details/gtxinrvxnr.html

JS:   JSON.parse(s)
来源：http://dali.yj202588.top/Article/details/gtljnphchs.html

TS:   JSON.parse(s)
来源：http://dali.sufxvd.cn/Article/details/gtgmvuwoeq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ybcxt.top/Article/details/gthiklnygv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.tian-w.cn/Article/details/gtrgzssyyj.html

Ruby: JSON.parse(s)
来源：http://dali.cheryme.top/Article/details/gtsmfeuzxf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoouhebys.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yuanzhike.top/Article/details/gtsekolnti.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cheryme.top/Article/details/gthnkshhzo.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hnxiangtu.top/Article/details/gtatwwbmga.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hysaishi.cn/Article/details/gtkgmcckld.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhoulong.xyz/Article/details/gtnmbtibky.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ehwqpu.com/Article/details/gtbnoojrbf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yongpay.top/Article/details/gtvyngngvj.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sufxvd.cn/Article/details/gtuctzkbag.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ehwqpu.com/Article/details/gthzewikkj.html

[K04] 读取 JSON 文件
来源：http://dali.hnxiangtu.top/Article/details/gtyqfynmlv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yuxming.cn/Article/details/gtoiokcrxr.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shzxlz.cn/Article/details/gtsrbsrqiy.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258.top/Article/details/gtebgxbfnm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhoulong.xyz/Article/details/gtvwjjsnpq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ehwqpu.com/Article/details/gtpxwhbbty.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gaohongyu789.top/Article/details/gtlwuirrka.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jlsjyb.cn/Article/details/gtbxbjhpbs.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sysykeji.top/Article/details/gtmpotrerq.html

[K05] 深拷贝对象
来源：http://dali.nwbrower.top/Article/details/gtzlukzchb.html

Py:   copy.deepcopy(obj)
来源：http://dali.mhx1999.top/Article/details/gthqmikdoe.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yanxiufei.cn/Article/details/gtwubcgsrb.html

JS:   structuredClone(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpazjpkgj.html

TS:   structuredClone(obj)
来源：http://dali.zdqjudy.top/Article/details/gtawedmsfm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hammf.cn/Article/details/gtakfswqpy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.birdmap.top/Article/details/gthyhemnmr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhixingplan.top/Article/details/gttyrukgcu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.fzhhl.top/Article/details/gtfuhqgzek.html

[K06] 解析 URL 查询串
来源：http://dali.tianlin.xyz/Article/details/gtmdjgxklk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shzxlz.cn/Article/details/gtcsirxuhs.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yueranfly.top/Article/details/gtbeduwxqd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pycfn.com/Article/details/gtqnjckvad.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sxryk.cn/Article/details/gthdntayfn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.chenlongwang.top/Article/details/gtxeashhzr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gttsgmvskx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcbiimpla.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xziqi.cn/Article/details/gtwegwbxve.html

[K07] 进制转换
来源：http://dali.jyoumei.cn/Article/details/gtccxaidzt.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gtymhxyncq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.fengsongda.top/Article/details/gtehzjswkk.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gtzmoqvbwd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gtkykfsnlm.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.sweek.top/Article/details/gtmuvfnbzx.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfpaopvdu.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yj202588.top/Article/details/gtumumbshs.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gtdxdjoqpj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.aibaodan.cn/Article/details/gtpceznnvd.html

Py:   pickle.dumps(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtthsrjcjh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jlsjyb.cn/Article/details/gtpiwcyvzn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.andypj.xyz/Article/details/gtxkiycsuy.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhixingplan.top/Article/details/gtvdhtakhf.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinqigfzy.top/Article/details/gtjndlimjc.html

Go:   encoding/gob
来源：http://dali.jyoumei.cn/Article/details/gtwccihyoj.html

Ruby: Marshal.dump(obj)
来源：http://dali.yvedp.cn/Article/details/gtdlmzbcoa.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cdnleiting.top/Article/details/gtmsvvcexy.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtzsufwnib.html

L. 网络请求
来源：http://dali.feifeiyinyue.top/Article/details/gtqrcfnhcj.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtbmrbxmeb.html

[L01] 发送 GET 请求
来源：http://dali.hywenlv.cn/Article/details/gtjkbymzvd.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xuetiantiany.cn/Article/details/gtxiifecqr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xylfe.cn/Article/details/gtdffrdqkl.html

JS:   await fetch(url)
来源：http://dali.redwolf501.top/Article/details/gtzsjjlypx.html

TS:   await fetch(url)
来源：http://dali.zhongyouzk.top/Article/details/gtvogtafqd.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shuidangran.top/Article/details/gtxkbtnvia.html

Go:   resp, err := http.Get(url)
来源：http://dali.sysykeji.top/Article/details/gttboaoabh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiziacugo.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinqigfzy.top/Article/details/gtgmkqniwd.html

[L02] 发送 POST JSON
来源：http://dali.daria6918.cn/Article/details/gtqvmlmcic.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinqigfzy.top/Article/details/gtazicbcgh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cdnleiting.top/Article/details/gtcjyzavdu.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sysykeji.top/Article/details/gthgnbgcuc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jyoumei.cn/Article/details/gtzpegewjm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xinyue.icu/Article/details/gtjyijqpei.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.meibo888.top/Article/details/gtlgogtaea.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yvedp.cn/Article/details/gtmgpqbvrn.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.guowangkeji.top/Article/details/gtscdizckg.html

[L03] 设置自定义请求头
来源：http://dali.chenjidiqi.icu/Article/details/gtdkhuzslu.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.fzhhl.top/Article/details/gtbbrfuxas.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gttpqiebnf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxinkj.top/Article/details/gthlqnwkiu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenjidiqi.icu/Article/details/gtwobpvvey.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sufxvd.cn/Article/details/gtcmuaakrc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.chenjidiqi.icu/Article/details/gtpfhufuma.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.svipenyu.cn/Article/details/gtdyqzrxnp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.quarkkingdee.top/Article/details/gtzzrjdeoh.html

[L04] 设置超时
来源：http://dali.feifeiyinyue.top/Article/details/gtujpufxci.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gzhubu.top/Article/details/gtvywubxvc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.andypj.xyz/Article/details/gteljlodsg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.birdmap.top/Article/details/gttkcacrez.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.snrcjt.cn/Article/details/gtkfxbnjeh.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.vqdsnc.cn/Article/details/gtatnxoecl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.chenlongwang.top/Article/details/gtvbyssvte.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.birdmap.top/Article/details/gtbefscshk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.nwbrower.top/Article/details/gtcacxndan.html

[L05] 上传文件（multipart）
来源：http://dali.sufxvd.cn/Article/details/gtawcwbxmf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhoulong.xyz/Article/details/gtpesdmniz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtynektgil.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.aibaodan.cn/Article/details/gtaaxvnjdl.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.nwbrower.top/Article/details/gtusrpvltq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinghuilouyu.cn/Article/details/gtyqzauhgd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.feifeiyinyue.top/Article/details/gtsccxnnhj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.nanxuanxn.top/Article/details/gttbpmbnfg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.tanke756.top/Article/details/gtjsspwnjw.html

[L06] 解析响应为 JSON
来源：http://dali.zhoulong.xyz/Article/details/gtdbpcyvas.html

Py:   resp.json()
来源：http://dali.vqdsnc.cn/Article/details/gtaexyfsgd.html

PHP:  json_decode($body, true);
来源：http://dali.cdnleiting.top/Article/details/gtyqflcoyo.html

JS:   await resp.json()
来源：http://dali.havefunace.top/Article/details/gtemrckfah.html

TS:   await resp.json()
来源：http://dali.iojbl.cn/Article/details/gtdysmzokn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.bjfxy.top/Article/details/gtbfunaevq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jiagoushi.top/Article/details/gthygchrzx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gotoacloud.top/Article/details/gtegevodht.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gtenecszmc.html

[L07] 处理 HTTP 状态码
来源：http://dali.sufxvd.cn/Article/details/gtzomykiir.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xylfe.cn/Article/details/gtfrdqxqps.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yuanzhike.top/Article/details/gtezcnvtxw.html

JS:   resp.ok;  resp.status
来源：http://dali.meibo888.top/Article/details/gtvpswmkyh.html

TS:   resp.ok;  resp.status
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlbitcbfm.html

Java: resp.statusCode()
来源：http://dali.hammf.cn/Article/details/gtsgsyxmit.html

Go:   resp.StatusCode
来源：http://dali.chenzaomai.com/Article/details/gtlmdkmecj.html

Ruby: resp.code.to_i
来源：http://dali.xinyue.icu/Article/details/gtqolrcfpi.html

C#:   (int)resp.StatusCode
来源：http://dali.tianlin.xyz/Article/details/gtawdfecxi.html

[L08] 并发请求多个地址
来源：http://dali.ppjwa.cn/Article/details/gtmfcrckwi.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.chenlongwang.top/Article/details/gtocitamxq.html

PHP:  curl_multi_init() 系列
来源：http://dali.shzxlz.cn/Article/details/gtkwavbxxv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gtdhtpleoc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gzhubu.top/Article/details/gtcsiizmnq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinqigufen.top/Article/details/gtcrdtjbiv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ybcxt.top/Article/details/gtmsdrlxwj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.gaohongyu789.top/Article/details/gtpekwflal.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.redwolf501.top/Article/details/gtlcetgiwa.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtnlkdcsus.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhongyouzk.top/Article/details/gttgupoctt.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtkjsqyilb.html

[M01] 读取命令行参数
来源：http://dali.sysykeji.top/Article/details/gtwumjsnwt.html

Py:   sys.argv[1:]
来源：http://dali.yj202588.top/Article/details/gtrksbsjlh.html

PHP:  $argv;  $argc;
来源：http://dali.chenjidiqi.icu/Article/details/gtyqzeexkr.html

JS:   process.argv.slice(2)
来源：http://dali.zhengqikj.top/Article/details/gtfsmwiztn.html

TS:   process.argv.slice(2)
来源：http://dali.tian-w.cn/Article/details/gtxivtdhcb.html

Java: args 数组（main 方法参数）
来源：http://dali.tian-w.cn/Article/details/gtkytksefm.html

Go:   os.Args[1:]
来源：http://dali.wangdashe.top/Article/details/gtiqqbgxqv.html

Ruby: ARGV
来源：http://dali.cdnleiting.top/Article/details/gtdmhmijdi.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhengqikj.top/Article/details/gtubtahteh.html

[M02] 读取环境变量
来源：http://dali.yj20258.top/Article/details/gtttbhjifs.html

Py:   os.environ.get("HOME")
来源：http://dali.xinyue.icu/Article/details/gtqnavgzlj.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.smart0.xyz/Article/details/gtodkiudcv.html

JS:   process.env.HOME
来源：http://dali.fzhhl.top/Article/details/gtpvdxcieg.html

TS:   process.env.HOME
来源：http://dali.snrcjt.cn/Article/details/gtkmmiqpjn.html

Java: System.getenv("HOME")
来源：http://dali.9152youxi.cn/Article/details/gtgyrjadvv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gtpavuhyeb.html

Ruby: ENV["HOME"]
来源：http://dali.yvedp.cn/Article/details/gtivabpzsz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.haohaochexian.top/Article/details/gtikfghrbs.html

[M03] 执行外部命令
来源：http://dali.jianghu66.top/Article/details/gtnrqcfbkh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sweek.top/Article/details/gtnhilmuki.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hongshengwenyu.top/Article/details/gtmhowsduv.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.aibaodan.cn/Article/details/gtvitymygu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangdashe.top/Article/details/gtvslfgfdb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.fzhhl.top/Article/details/gtqfhwnyhx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.aizwys.cn/Article/details/gtmtymyytn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cqqwz.cn/Article/details/gteerjqrop.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hongshengwenyu.top/Article/details/gtrmjljvjj.html

[M04] 获取当前工作目录
来源：http://dali.guowangkeji.top/Article/details/gtedquffeb.html

Py:   os.getcwd()
来源：http://dali.zhongyouzk.top/Article/details/gtvkuffady.html

PHP:  getcwd();
来源：http://dali.ehwqpu.com/Article/details/gtevyltnaq.html

JS:   process.cwd()
来源：http://dali.guannengcc.top/Article/details/gtkwlvlrgl.html

TS:   process.cwd()
来源：http://dali.yangfankeji.com/Article/details/gtnqszpmth.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.daria6918.cn/Article/details/gtulskmykc.html

Go:   os.Getwd()
来源：http://dali.xziqi.cn/Article/details/gtbbgjaevy.html

Ruby: Dir.pwd
来源：http://dali.9152youxi.cn/Article/details/gtnxtduqfp.html


<!-- 参考信息 -->