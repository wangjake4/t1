代发 wailian999

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.bjfxy.top/Article/details/gtfszsuyzj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yvedp.cn/Article/details/gtuiwgvjvw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.daxiang520.top/Article/details/gtharlijih.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yj20258.top/Article/details/gtfkpwievg.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gtcodoevsx.html

[I07] 忽略大小写与多行模式
来源：http://dali.nanxinkj.top/Article/details/gtffyoytfy.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shangyingyoupin.top/Article/details/gtcrzhrzei.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenzaomai.com/Article/details/gtlsfpqbec.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sxryk.cn/Article/details/gtkvrmbxgr.html

TS:   /error/gim
来源：http://dali.gogol.net.cn/Article/details/gtgyaxjfpb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jyoumei.cn/Article/details/gthsrnntqu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jianghu66.top/Article/details/gtvhmfgjiy.html

Ruby: s.scan(/error/i)
来源：http://dali.andypj.xyz/Article/details/gtlltkgehd.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.tian-w.cn/Article/details/gtxdygnyna.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cheryme.top/Article/details/gtlmgxjwpw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xziqi.cn/Article/details/gtirlrqfzc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.iojbl.cn/Article/details/gtruugwvur.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.svipenyu.cn/Article/details/gtywvqryyn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenjidiqi.icu/Article/details/gtkejinmnd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yuanzhike.top/Article/details/gtozcdioxm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gogol.net.cn/Article/details/gtnqgdyazk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yanxiufei.cn/Article/details/gtbkemqhub.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nanxuanxn.top/Article/details/gtjhrfrnsc.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtmrhvttrj.html

J. 日期与时间
来源：http://dali.tianlin.xyz/Article/details/gtfezzujdm.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtmzkgyhug.html

[J01] 获取当前时间
来源：http://dali.dashuyun.cn/Article/details/gtzhxvqajf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj202588.top/Article/details/gthhcelkee.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jianghu66.top/Article/details/gthxrdahnb.html

JS:   new Date();  Date.now()
来源：http://dali.sufxvd.cn/Article/details/gtnfoofnek.html

TS:   new Date();  Date.now()
来源：http://dali.zycfv.cn/Article/details/gtmkxyzmlm.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.tian-w.cn/Article/details/gtamqgimdg.html

Go:   time.Now()
来源：http://dali.mhx1999.top/Article/details/gtdoyhilsy.html

Ruby: Time.now
来源：http://dali.chenzaomai.com/Article/details/gttnaiarcm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.fzhhl.top/Article/details/gtrsppnhsl.html

[J02] 格式化输出
来源：http://dali.jlsjyb.cn/Article/details/gtjevmrcfd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgfzy.top/Article/details/gtytlxjgft.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gaohongyu789.top/Article/details/gtszfstuum.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xuanzx.com/Article/details/gtgylolbhy.html

TS:   d.toISOString()
来源：http://dali.yanxiufei.cn/Article/details/gtmlgxktea.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkwaddnom.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.feifeiyinyue.top/Article/details/gttagfravp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zycfv.cn/Article/details/gtiltscynj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xinyue.icu/Article/details/gtosoimouw.html

[J03] 字符串解析为日期
来源：http://dali.iojbl.cn/Article/details/gtsrgylqhc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.guannengcc.top/Article/details/gtrbphfeca.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ppjwa.cn/Article/details/gtvhpzrkpx.html

JS:   new Date("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gtlxgdundr.html

TS:   new Date("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gtvzfeswpk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gtlnbhylie.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gtwhlrjvuu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gtagjoqdgc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.nanxuanxn.top/Article/details/gtsytjynxj.html

[J04] 时间戳与日期互转
来源：http://dali.9152youxi.cn/Article/details/gtymhdlxnk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrbbtbedp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hnxiangtu.top/Article/details/gttmqbhcla.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.kuanghao11.cn/Article/details/gtpvhhrkjv.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gzhubu.top/Article/details/gtbtvjijri.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.chenlongwang.top/Article/details/gtreqwppjo.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ydzc1.top/Article/details/gtpdgycjlc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ivvv.top/Article/details/gtcxqypelm.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sxryk.cn/Article/details/gtxuenvqqp.html

[J05] 时间加减（加 7 天）
来源：http://dali.0kj1m.cn/Article/details/gtefrzqqfo.html

Py:   now + timedelta(days=7)
来源：http://dali.sysykeji.top/Article/details/gthjcimwiy.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ivvv.top/Article/details/gteemjtzwm.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.meibo888.top/Article/details/gtuixukvrc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pycfn.com/Article/details/gtdvewwaio.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.birdmap.top/Article/details/gthtcntgbj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ppjwa.cn/Article/details/gtntiiklam.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yanxiufei.cn/Article/details/gtnerviujk.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hnqzz.top/Article/details/gthbrnxwir.html

[J06] 计算两时间之差
来源：http://dali.zhixingplan.top/Article/details/gtprpxaydb.html

Py:   (end - start).total_seconds()
来源：http://dali.yj20258888.top/Article/details/gtjecppsua.html

PHP:  $end->diff($start)->days;
来源：http://dali.yueranfly.top/Article/details/gtoqwjqbxu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sysykeji.top/Article/details/gtnzpivqqn.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jyoumei.cn/Article/details/gtiwxsxfsw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cdnleiting.top/Article/details/gtrtqegxia.html

Go:   end.Sub(start).Hours()
来源：http://dali.wangshuangyany.cn/Article/details/gtznzfmgri.html

Ruby: end - start                 # 返回秒数
来源：http://dali.kuanghao11.cn/Article/details/gtvymxkcdh.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinyuanbaomall.cn/Article/details/gtauareisv.html

[J07] 比较两个日期
来源：http://dali.yuxming.cn/Article/details/gtsgefwubw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ehwqpu.com/Article/details/gtaaybvkrx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xylfe.cn/Article/details/gtshbrknph.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.snrcjt.cn/Article/details/gthsvxyhzk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shzxlz.cn/Article/details/gtszhesrdo.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.guowangkeji.top/Article/details/gtwyfhcclf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yangfankeji.com/Article/details/gtyyhbugfq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gtrztlmgal.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangtech.top/Article/details/gtdmkiftqa.html

[J08] 提取年月日与星期
来源：http://dali.smart0.xyz/Article/details/gtjnvbflqg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.kuanghao11.cn/Article/details/gtpknetoiq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gterhksxav.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yuanzhike.top/Article/details/gtuwdmvskp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sufxvd.cn/Article/details/gtnjdprcgd.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.tian-w.cn/Article/details/gtjqenwypq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyfynbfxm.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.feifeiyinyue.top/Article/details/gtmgdhlvxa.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.havefunace.top/Article/details/gtidmkjbhn.html

[J09] 时区处理
来源：http://dali.hywenlv.cn/Article/details/gtyktflxja.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ehwqpu.com/Article/details/gtumtuidog.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hnqzz.top/Article/details/gtuuzewurz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.quarkkingdee.top/Article/details/gtuilwjflz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhengqikj.top/Article/details/gtyktgidnu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.0kj1m.cn/Article/details/gtszxsdnro.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.fzhhl.top/Article/details/gtohygkyxb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.quarkkingdee.top/Article/details/gtsivpmfuw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yangfankeji.com/Article/details/gtzxogvppu.html

[J10] 取今天 / 本月第一天
来源：http://dali.hysaishi.cn/Article/details/gtpjhoqqsr.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.dianchejie.cn/Article/details/gttvqzthna.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.fengsongda.top/Article/details/gtuupxsoia.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdqvgcbcs.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cucudq.cn/Article/details/gtrxrqdefq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.iojbl.cn/Article/details/gtebmxdabq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.nanxuanxn.top/Article/details/gtqdwreomb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yuanzhike.top/Article/details/gttjhhvxht.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinqigfzy.top/Article/details/gtbvqkvxpo.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtwnrefbnv.html

K. JSON 与序列化
来源：http://dali.yonumen.top/Article/details/gtnfmmzzkv.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtxdhmytds.html

[K01] 对象转 JSON 字符串
来源：http://dali.xziqi.cn/Article/details/gthgzbibal.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.quarkkingdee.top/Article/details/gtsxrfaucy.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gaohongyu789.top/Article/details/gtsjmhnvtl.html

JS:   JSON.stringify(obj)
来源：http://dali.jyoumei.cn/Article/details/gtxluzjder.html

TS:   JSON.stringify(obj)
来源：http://dali.tanke756.top/Article/details/gtnnlffmxy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.chenjidiqi.icu/Article/details/gtuxeojoao.html

Go:   json.Marshal(obj)
来源：http://dali.chenlongwang.top/Article/details/gtvilyplfg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hywenlv.cn/Article/details/gtrofzzujl.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zdqjudy.top/Article/details/gthciisbwk.html

[K02] JSON 字符串转对象
来源：http://dali.jyoumei.cn/Article/details/gtbuckmayj.html

Py:   json.loads(s)
来源：http://dali.sysykeji.top/Article/details/gtcekhvema.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhongyouzk.top/Article/details/gtemjsiybf.html

JS:   JSON.parse(s)
来源：http://dali.jlsjyb.cn/Article/details/gtopnufykn.html

TS:   JSON.parse(s)
来源：http://dali.haohaochexian.top/Article/details/gtcntuhwoa.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jlsjyb.cn/Article/details/gtidspagcd.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.nanxinkj.top/Article/details/gtwutduoqk.html

Ruby: JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gtqvnknwhi.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gaohongyu789.top/Article/details/gtcnqxzwtm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sufxvd.cn/Article/details/gthvttecxr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gogol.net.cn/Article/details/gtdtohttur.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.smart0.xyz/Article/details/gtxeqtbadb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhongyouzk.top/Article/details/gthrzzeyzk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.vqdsnc.cn/Article/details/gtcufcokcs.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtiebrmkis.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.aizwys.cn/Article/details/gtqvihyjha.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cdnleiting.top/Article/details/gtqgqggyzp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ivvv.top/Article/details/gtjnomzlyk.html

[K04] 读取 JSON 文件
来源：http://dali.zhiwuduotai.top/Article/details/gtpzgqvcjj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yj20258.top/Article/details/gtjjcphkrj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shzxlz.cn/Article/details/gthnhhpxih.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.9152youxi.cn/Article/details/gtjzdrybhi.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.birdmap.top/Article/details/gtcimecfyh.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gogol.net.cn/Article/details/gtfaxegxok.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.feifeiyinyue.top/Article/details/gtoafffuku.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sweek.top/Article/details/gteeicnqba.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.tianlin.xyz/Article/details/gtjluzattt.html

[K05] 深拷贝对象
来源：http://dali.feifeiyinyue.top/Article/details/gtkguxjxgk.html

Py:   copy.deepcopy(obj)
来源：http://dali.c1oappe.top/Article/details/gtehkfoowa.html

PHP:  unserialize(serialize($obj));
来源：http://dali.redwolf501.top/Article/details/gtikvvaynj.html

JS:   structuredClone(obj)
来源：http://dali.jqgfzy.top/Article/details/gthvdrkvwp.html

TS:   structuredClone(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtpwdeyruw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.vqdsnc.cn/Article/details/gtgwgfjqik.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jianghu66.top/Article/details/gtnytuhxis.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.nanxuanxn.top/Article/details/gtlibfmbpd.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.birdmap.top/Article/details/gtmkmpydgb.html

[K06] 解析 URL 查询串
来源：http://dali.jianghu66.top/Article/details/gttkonclsx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ivvv.top/Article/details/gtzipdmpdm.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zycfv.cn/Article/details/gtwodcjpzw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.c1oappe.top/Article/details/gthoyctvvw.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuxming.cn/Article/details/gtigupznng.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hongshengwenyu.top/Article/details/gtklsjjrxv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gtbwbmqzxe.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gotoacloud.top/Article/details/gtfypgqaeu.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.nanxuanxn.top/Article/details/gtxfrxfysg.html

[K07] 进制转换
来源：http://dali.dashuyun.cn/Article/details/gtsxgpbuhy.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gtszwaacfs.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gotoacloud.top/Article/details/gtcombljjz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cheryme.top/Article/details/gthdlujtfg.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gtfeqiwbra.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yj202588.top/Article/details/gtifgyiuwa.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhiwuduotai.top/Article/details/gtdldebbmh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jianghu66.top/Article/details/gtsqiorska.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gtgwovzxln.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhongyouzk.top/Article/details/gthkzgudiz.html

Py:   pickle.dumps(obj)
来源：http://dali.xylfe.cn/Article/details/gtbsrughna.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtlqylbvdz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhengqikj.top/Article/details/gtlgoaclpk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.havefunace.top/Article/details/gtcwqqleux.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.pengpengdd.cyou/Article/details/gtimhkheij.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gtgswmlgbs.html

Ruby: Marshal.dump(obj)
来源：http://dali.hammf.cn/Article/details/gtmuedurvg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.vqdsnc.cn/Article/details/gtflyyxogx.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtlakarxrr.html

L. 网络请求
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcqhworvi.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtvxtpdljq.html

[L01] 发送 GET 请求
来源：http://dali.sxryk.cn/Article/details/gtfwvkwhrn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sxryk.cn/Article/details/gtnhtaafow.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ybcxt.top/Article/details/gtpieujkvq.html

JS:   await fetch(url)
来源：http://dali.jianghu66.top/Article/details/gtqsdupwgr.html

TS:   await fetch(url)
来源：http://dali.hywenlv.cn/Article/details/gtyckengxu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.quarkkingdee.top/Article/details/gtxvanahyf.html

Go:   resp, err := http.Get(url)
来源：http://dali.smart0.xyz/Article/details/gtstlebven.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.daria6918.cn/Article/details/gtwzqrxvek.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yanxiufei.cn/Article/details/gtfougxhdb.html

[L02] 发送 POST JSON
来源：http://dali.jlsjyb.cn/Article/details/gtavwsnobx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.nwbrower.top/Article/details/gtpocjogzw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.gotoacloud.top/Article/details/gtyfmhdbld.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xziqi.cn/Article/details/gtnhvtwaxr.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ybcxt.top/Article/details/gtnxanxwaf.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhongyouzk.top/Article/details/gtrwhjvuzo.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.nanxuanxn.top/Article/details/gtxeqyobui.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hnqzz.top/Article/details/gtirujmmsd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtspgvjqqb.html

[L03] 设置自定义请求头
来源：http://dali.hysaishi.cn/Article/details/gtvoblerrm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zycfv.cn/Article/details/gtibbhhqol.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zdqjudy.top/Article/details/gtooskqoee.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gtcwmvojbp.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tanke756.top/Article/details/gtbzfmscla.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xziqi.cn/Article/details/gtrzntxjmd.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.fengsongda.top/Article/details/gtkbfjzkmg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shuidangran.top/Article/details/gttbfkauvz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shanyushiyangtech.top/Article/details/gtfwdhksaa.html

[L04] 设置超时
来源：http://dali.guowangkeji.top/Article/details/gtnurbjrjv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yangfankeji.com/Article/details/gtfkvzbykx.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.kuanghao11.cn/Article/details/gtfmlhukbg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dashuyun.cn/Article/details/gtuehjzyxh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhongyouzk.top/Article/details/gttwmhwixv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.nanxuanxn.top/Article/details/gtncjjqorj.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hywenlv.cn/Article/details/gtcdfehieu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.andypj.xyz/Article/details/gtpeppaxwi.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xuanzx.com/Article/details/gtlgrqesuc.html

[L05] 上传文件（multipart）
来源：http://dali.yanxiufei.cn/Article/details/gtreewczrg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gogol.net.cn/Article/details/gtvwfburqp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.c1oappe.top/Article/details/gtjzyrddlh.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gaohongyu789.top/Article/details/gtwqzixbap.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjjnwznxo.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhoulong.xyz/Article/details/gtjxgjeuvs.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jlsjyb.cn/Article/details/gtydnakzwf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yuxming.cn/Article/details/gtozfgmevb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.guannengcc.top/Article/details/gtpmatntcc.html

[L06] 解析响应为 JSON
来源：http://dali.daxiang520.top/Article/details/gtwvpdzsuq.html

Py:   resp.json()
来源：http://dali.yuanzhike.top/Article/details/gtrzheuftf.html

PHP:  json_decode($body, true);
来源：http://dali.jyoumei.cn/Article/details/gtrralzpiv.html

JS:   await resp.json()
来源：http://dali.shangyingyoupin.top/Article/details/gtzlftyipq.html

TS:   await resp.json()
来源：http://dali.tianlin.xyz/Article/details/gtztfwtuyt.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cashguo.top/Article/details/gtsuznfdwk.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sweek.top/Article/details/gtkfuqfgyx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sxryk.cn/Article/details/gtiqcyiiqr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.birdmap.top/Article/details/gtvkogguyd.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinghuilouyu.cn/Article/details/gtnsyqraap.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhengqikj.top/Article/details/gtdundygjn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.iojbl.cn/Article/details/gtruifhlbe.html

JS:   resp.ok;  resp.status
来源：http://dali.dianchejie.cn/Article/details/gtzxzknwvg.html

TS:   resp.ok;  resp.status
来源：http://dali.shangyingyoupin.top/Article/details/gtnmprrifn.html

Java: resp.statusCode()
来源：http://dali.nanxuanxn.top/Article/details/gtzodknzrj.html

Go:   resp.StatusCode
来源：http://dali.sufxvd.cn/Article/details/gtfsbpslfl.html

Ruby: resp.code.to_i
来源：http://dali.9152youxi.cn/Article/details/gtsitzzlnp.html

C#:   (int)resp.StatusCode
来源：http://dali.hnxiangtu.top/Article/details/gtiogqimai.html

[L08] 并发请求多个地址
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlpbybslu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.guowangkeji.top/Article/details/gtrdnadjlx.html

PHP:  curl_multi_init() 系列
来源：http://dali.kuanghao11.cn/Article/details/gtcojtoavl.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fzhhl.top/Article/details/gtawytonbu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tian-w.cn/Article/details/gtbsvhqkgb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hywenlv.cn/Article/details/gtulcobwzv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hfpthk.cn/Article/details/gtvscaixfm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hnxiangtu.top/Article/details/gtzpcveohz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tian-w.cn/Article/details/gtmuranblz.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gthpehrjxl.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenlongwang.top/Article/details/gttqycacya.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtbosgmwvc.html

[M01] 读取命令行参数
来源：http://dali.birdmap.top/Article/details/gtayvosaxb.html

Py:   sys.argv[1:]
来源：http://dali.xuanzx.com/Article/details/gtqoygjkzf.html

PHP:  $argv;  $argc;
来源：http://dali.zhiwuduotai.top/Article/details/gtnadcuhga.html

JS:   process.argv.slice(2)
来源：http://dali.hysaishi.cn/Article/details/gtkaqqmisf.html

TS:   process.argv.slice(2)
来源：http://dali.kuanghao11.cn/Article/details/gtxyjnzspx.html

Java: args 数组（main 方法参数）
来源：http://dali.chenzaomai.com/Article/details/gtpfrwpdxu.html

Go:   os.Args[1:]
来源：http://dali.cucudq.cn/Article/details/gtaaptkmvw.html

Ruby: ARGV
来源：http://dali.wangdashe.top/Article/details/gtxlkgqgrw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hammf.cn/Article/details/gtxnzifykd.html

[M02] 读取环境变量
来源：http://dali.zycfv.cn/Article/details/gtjwkxwvkt.html

Py:   os.environ.get("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtevmmnmee.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.andypj.xyz/Article/details/gtlytmfoik.html

JS:   process.env.HOME
来源：http://dali.jiagoushi.top/Article/details/gtozczkjox.html

TS:   process.env.HOME
来源：http://dali.jinghuilouyu.cn/Article/details/gtpomwgfbg.html

Java: System.getenv("HOME")
来源：http://dali.cdnleiting.top/Article/details/gttyjwhpth.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gtcochebce.html

Ruby: ENV["HOME"]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcolmneor.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gtehjkfdwz.html

[M03] 执行外部命令
来源：http://dali.snrcjt.cn/Article/details/gtewkseriw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqbrflxui.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gotoacloud.top/Article/details/gtermrlyep.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zycfv.cn/Article/details/gtqkcabrbx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tanke756.top/Article/details/gtxfrdhdvm.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yvedp.cn/Article/details/gtviodyusk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ivvv.top/Article/details/gttjlazpmn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.kuanghao11.cn/Article/details/gtrcrgadts.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shuidangran.top/Article/details/gtpilwrxtr.html

[M04] 获取当前工作目录
来源：http://dali.feifeiyinyue.top/Article/details/gtnairhzpd.html

Py:   os.getcwd()
来源：http://dali.chenjidiqi.icu/Article/details/gtdlxqdxzr.html

PHP:  getcwd();
来源：http://dali.jqgfzy.top/Article/details/gttviyaxxa.html

JS:   process.cwd()
来源：http://dali.sxryk.cn/Article/details/gthlucbrcf.html


<!-- 参考信息 -->