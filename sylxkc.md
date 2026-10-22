代发 wailian999

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.wangdashe.top/Article/details/gtkmfchmze.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzydxqooq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.feifeiyinyue.top/Article/details/gtkqfdcgzz.html

[I05] 按正则拆分
来源：http://dali.guannengcc.top/Article/details/gtfxfgwads.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhoulong.xyz/Article/details/gtgqxgvqoh.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gtcapovpcf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.nwbrower.top/Article/details/gtdqrfflfj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtejltkjiq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.pengpengdd.cyou/Article/details/gtlyzxlusk.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.guowangkeji.top/Article/details/gtzdbesxrt.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yangfankeji.com/Article/details/gtpykbqupf.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yanxiufei.cn/Article/details/gtgsiibtye.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yj20258.top/Article/details/gtiqpkgxtk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sysykeji.top/Article/details/gttlpssxis.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.aibaodan.cn/Article/details/gthbqesclk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangdashe.top/Article/details/gtntqebaog.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xylfe.cn/Article/details/gtucacxxtq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gtlfqgjaus.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hfpthk.cn/Article/details/gtdsoywtbq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jqgufenzy.top/Article/details/gtjhyjlvdy.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xuetiantiany.cn/Article/details/gtkhzqzogd.html

[I07] 忽略大小写与多行模式
来源：http://dali.sxryk.cn/Article/details/gtocvkdecr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.wangdashe.top/Article/details/gtvwiqevle.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.nwbrower.top/Article/details/gtyagxgato.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cqqwz.cn/Article/details/gtvffbehpq.html

TS:   /error/gim
来源：http://dali.c1oappe.top/Article/details/gtrzwzunei.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.pycfn.com/Article/details/gtxunrljkt.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhengqikj.top/Article/details/gtikduniah.html

Ruby: s.scan(/error/i)
来源：http://dali.ybcxt.top/Article/details/gtzsbjovwf.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hywenlv.cn/Article/details/gtiyokklir.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jiagoushi.top/Article/details/gtiupqxpfe.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shanyushiyangkeji.top/Article/details/gtioiqpdri.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.redwolf501.top/Article/details/gtsiamhrtl.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fengsongda.top/Article/details/gtaqwsirdg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shuidangran.top/Article/details/gtkhfgozqt.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gogol.net.cn/Article/details/gtlfpxhdhp.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.nanxuanxn.top/Article/details/gtyxwklrei.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sweek.top/Article/details/gtzsxhkmnj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.fzhhl.top/Article/details/gtmkcristx.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtphlozvwo.html

J. 日期与时间
来源：http://dali.zdqjudy.top/Article/details/gtmbiwkujr.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtdrthdqjh.html

[J01] 获取当前时间
来源：http://dali.zhongyouzk.top/Article/details/gttunyoqjf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj20258.top/Article/details/gtvimvaowz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xuetiantiany.cn/Article/details/gtwwwfgjwh.html

JS:   new Date();  Date.now()
来源：http://dali.chenlongwang.top/Article/details/gtminxryef.html

TS:   new Date();  Date.now()
来源：http://dali.zdqjudy.top/Article/details/gtppwmrmyp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ehwqpu.com/Article/details/gtqnuohusx.html

Go:   time.Now()
来源：http://dali.tian-w.cn/Article/details/gtwnsjjwot.html

Ruby: Time.now
来源：http://dali.cashguo.top/Article/details/gtugdkjver.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.kuanghao11.cn/Article/details/gtpxguznde.html

[J02] 格式化输出
来源：http://dali.jqgfzy.top/Article/details/gtqgjiwnnv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuxming.cn/Article/details/gtffjevftm.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhengqikj.top/Article/details/gtxouwsrvw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.dianchejie.cn/Article/details/gtxsaoobcn.html

TS:   d.toISOString()
来源：http://dali.hnxiangtu.top/Article/details/gtxqsbgvyf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.0kj1m.cn/Article/details/gtfsmouiyp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.iojbl.cn/Article/details/gthrdhmhzo.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.feifeiyinyue.top/Article/details/gtqdccpiyr.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.dashuyun.cn/Article/details/gtnglplfkb.html

[J03] 字符串解析为日期
来源：http://dali.gzhubu.top/Article/details/gtxucpvrei.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.dashuyun.cn/Article/details/gtuhmkhgpq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.feifeiyinyue.top/Article/details/gtahnbcemb.html

JS:   new Date("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gtlzfrgubs.html

TS:   new Date("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gteqromqgw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtspybnhlr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtvnvgfiya.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gtagtfosxi.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaqiamqjq.html

[J04] 时间戳与日期互转
来源：http://dali.xuetiantiany.cn/Article/details/gtdawnipxn.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.chenzaomai.com/Article/details/gtfqayhmhu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jiagoushi.top/Article/details/gtdqmdnbjw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yanxiufei.cn/Article/details/gtdgbifbfo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shzxlz.cn/Article/details/gtdpmpcdxp.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yanxiufei.cn/Article/details/gtfmrjrgdq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtkktvrsol.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cashguo.top/Article/details/gtroskzjbc.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ehwqpu.com/Article/details/gtecogsxji.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinqigufen.top/Article/details/gtoptazzkj.html

Py:   now + timedelta(days=7)
来源：http://dali.xylfe.cn/Article/details/gtavanwdnd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hammf.cn/Article/details/gtsovkttsu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfopdvrad.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pengpengdd.cyou/Article/details/gtoilrpyuv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinqigfzy.top/Article/details/gtyjjcopmy.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.kuanghao11.cn/Article/details/gtrdsfvxqx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hfpthk.cn/Article/details/gtgtxoequl.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hywenlv.cn/Article/details/gteffhxzaj.html

[J06] 计算两时间之差
来源：http://dali.yuanzhike.top/Article/details/gtnyrqursu.html

Py:   (end - start).total_seconds()
来源：http://dali.haohaochexian.top/Article/details/gtgibdgfku.html

PHP:  $end->diff($start)->days;
来源：http://dali.shuidangran.top/Article/details/gttzlbkmjj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.c1oappe.top/Article/details/gtgocwtejg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.smart0.xyz/Article/details/gtikrfqrdz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xinyue.icu/Article/details/gtzenxsjbj.html

Go:   end.Sub(start).Hours()
来源：http://dali.iojbl.cn/Article/details/gtsbrmbnnt.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinghuilouyu.cn/Article/details/gtpjxuceqm.html

C#:   (end - start).TotalSeconds
来源：http://dali.gotoacloud.top/Article/details/gtnkqtodbr.html

[J07] 比较两个日期
来源：http://dali.hywenlv.cn/Article/details/gtkoeqakmb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhoulong.xyz/Article/details/gtzwaguygh.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinghuilouyu.cn/Article/details/gtkkcrcweh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zdqjudy.top/Article/details/gtxdpkkonu.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shzxlz.cn/Article/details/gttguarpbg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhijiandao.cn/Article/details/gtstwyptgt.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinqigfzy.top/Article/details/gtxyjseysn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xinyue.icu/Article/details/gtefeeulsf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqzeeatcn.html

[J08] 提取年月日与星期
来源：http://dali.aizwys.cn/Article/details/gtfsioselw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.fzhhl.top/Article/details/gtowwbzihu.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.guowangkeji.top/Article/details/gtgwhhqvfp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.feifeiyinyue.top/Article/details/gtnbmckevf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.smart0.xyz/Article/details/gtqfztaija.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jqgufenzy.top/Article/details/gtxavagebi.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhongyouzk.top/Article/details/gtytnisrvc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yj202588.top/Article/details/gtxaxsqcll.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zycfv.cn/Article/details/gtipxyojtw.html

[J09] 时区处理
来源：http://dali.xuetiantiany.cn/Article/details/gteptrzdie.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.fengsongda.top/Article/details/gtvjrbsfgc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.svipenyu.cn/Article/details/gtcvmgrksc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhengqikj.top/Article/details/gtfeibknci.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gtjzukqkfd.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yangfankeji.com/Article/details/gtfsubiokz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.nwbrower.top/Article/details/gtesmcaepv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hnxiangtu.top/Article/details/gtchwgicke.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gaohongyu789.top/Article/details/gtlmtzfcnu.html

[J10] 取今天 / 本月第一天
来源：http://dali.nwbrower.top/Article/details/gthzplnrfs.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.iojbl.cn/Article/details/gtybrqdyme.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.fzhhl.top/Article/details/gttuvftbrh.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yonumen.top/Article/details/gtjijlnicf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ivvv.top/Article/details/gtphapsoyo.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gaohongyu789.top/Article/details/gtgknskbhm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhongyouzk.top/Article/details/gtsamazruz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.guowangkeji.top/Article/details/gtsjekmpev.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhongyouzk.top/Article/details/gtbablvenj.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtjwnirdfj.html

K. JSON 与序列化
来源：http://dali.cashguo.top/Article/details/gtzawhziua.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtahaogjof.html

[K01] 对象转 JSON 字符串
来源：http://dali.mhx1999.top/Article/details/gtuzikcslg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhixingplan.top/Article/details/gtmhqvsjnb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.daria6918.cn/Article/details/gtqdlfauxf.html

JS:   JSON.stringify(obj)
来源：http://dali.tanke756.top/Article/details/gthqgzoytz.html

TS:   JSON.stringify(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtdlinxsqe.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.chenlongwang.top/Article/details/gtnjnimevs.html

Go:   json.Marshal(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxylyqqnk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.wangshuangyany.cn/Article/details/gtoscrepcq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtiupfgywy.html

[K02] JSON 字符串转对象
来源：http://dali.yj20258.top/Article/details/gtdaebuilq.html

Py:   json.loads(s)
来源：http://dali.aibaodan.cn/Article/details/gtzxafvpbd.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xziqi.cn/Article/details/gtymzwocco.html

JS:   JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gtlwhtnqiy.html

TS:   JSON.parse(s)
来源：http://dali.nanxuanxn.top/Article/details/gtcydeybug.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gzhubu.top/Article/details/gtfpbevnur.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zdqjudy.top/Article/details/gtdeycqkqd.html

Ruby: JSON.parse(s)
来源：http://dali.fzhhl.top/Article/details/gtvkhggmml.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hammf.cn/Article/details/gthldxrckb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuhwabunq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtanirqszq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sysykeji.top/Article/details/gtogsetfbi.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sysykeji.top/Article/details/gtvbqzakpk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangdashe.top/Article/details/gtlbrjeqmg.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xziqi.cn/Article/details/gtqkmooaxn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sxryk.cn/Article/details/gtdosqanzp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jyoumei.cn/Article/details/gtrieizajn.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinqigfzy.top/Article/details/gtrqczxotp.html

[K04] 读取 JSON 文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtqiqomnkb.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.chenzaomai.com/Article/details/gtrboetkxv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jqgufenzy.top/Article/details/gtbbmdguyf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fzhhl.top/Article/details/gtamofnstf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pengpengdd.cyou/Article/details/gtwwdwwnzp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtazuptzbn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.redwolf501.top/Article/details/gtdqzbctfn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.dashuyun.cn/Article/details/gtlbosoglh.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shzxlz.cn/Article/details/gtbcypbulq.html

[K05] 深拷贝对象
来源：http://dali.jinqigufen.top/Article/details/gtoefxettm.html

Py:   copy.deepcopy(obj)
来源：http://dali.xinyue.icu/Article/details/gtqzbpjqpd.html

PHP:  unserialize(serialize($obj));
来源：http://dali.andypj.xyz/Article/details/gtqpatpamd.html

JS:   structuredClone(obj)
来源：http://dali.sweek.top/Article/details/gtzyyrayso.html

TS:   structuredClone(obj)
来源：http://dali.yuxming.cn/Article/details/gtblnyuibb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ppjwa.cn/Article/details/gtwktwlvqb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sysykeji.top/Article/details/gtovfvcnra.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhixingplan.top/Article/details/gtljbcifrh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ywan-chungtsiang.top/Article/details/gtykgojlxl.html

[K06] 解析 URL 查询串
来源：http://dali.vqdsnc.cn/Article/details/gtfogjoidg.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinqigufen.top/Article/details/gtfbgvyqnm.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ydzc1.top/Article/details/gthvovmxkz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ehwqpu.com/Article/details/gtyriimwby.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.feifeiyinyue.top/Article/details/gtevdgmxne.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinqigfzy.top/Article/details/gtdyxijvdp.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.dashuyun.cn/Article/details/gtpaunvsbx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhixingplan.top/Article/details/gtuobgjlpf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.feifeiyinyue.top/Article/details/gtgpcreixu.html

[K07] 进制转换
来源：http://dali.haohaochexian.top/Article/details/gtmyxtehbm.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtmdzhyqur.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yj20258.top/Article/details/gtadqybelq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gtjfkjwaut.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gtsyrsncgn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gtmpzembpe.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.0kj1m.cn/Article/details/gtqxugnxlj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jqgufenzy.top/Article/details/gtnoamqpbp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtomyydldg.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hnqzz.top/Article/details/gtbwcftdgr.html

Py:   pickle.dumps(obj)
来源：http://dali.yj202588.top/Article/details/gtrmsjaqmv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hywenlv.cn/Article/details/gtcpyjihbb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.c1oappe.top/Article/details/gtgxlulfhx.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.redwolf501.top/Article/details/gtbggttbzc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.wangshuangyany.cn/Article/details/gtquzjqliu.html

Go:   encoding/gob
来源：http://dali.havefunace.top/Article/details/gtbswmaobj.html

Ruby: Marshal.dump(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtywinsoty.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.smart0.xyz/Article/details/gtkompzjim.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtesmwhsuj.html

L. 网络请求
来源：http://dali.yuxming.cn/Article/details/gtsgxzwdgf.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtlzpwsvmm.html

[L01] 发送 GET 请求
来源：http://dali.9152youxi.cn/Article/details/gtvtrpqwyn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.fzhhl.top/Article/details/gtvbvettfn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiyykxabk.html

JS:   await fetch(url)
来源：http://dali.fzhhl.top/Article/details/gtlnqovkmy.html

TS:   await fetch(url)
来源：http://dali.yongpay.top/Article/details/gtbxfgplat.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hnqzz.top/Article/details/gtjailbihy.html

Go:   resp, err := http.Get(url)
来源：http://dali.ydzc1.top/Article/details/gtgawxwraf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.dashuyun.cn/Article/details/gtbyabamlt.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.nwbrower.top/Article/details/gtytkunnnj.html

[L02] 发送 POST JSON
来源：http://dali.aizwys.cn/Article/details/gttbywiekw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ppjwa.cn/Article/details/gtisnxyxwg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hnqzz.top/Article/details/gtrvfoudre.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gotoacloud.top/Article/details/gtenxettgo.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhixingplan.top/Article/details/gtufnaxeob.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.c1oappe.top/Article/details/gtlbzcwawa.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.snrcjt.cn/Article/details/gtsqhfvisc.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hywenlv.cn/Article/details/gtqbfawwkg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.wangdashe.top/Article/details/gtsiwunxkw.html

[L03] 设置自定义请求头
来源：http://dali.c1oappe.top/Article/details/gtfaqethff.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jyoumei.cn/Article/details/gtyvaaapwt.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hammf.cn/Article/details/gtmyebbrwj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zdqjudy.top/Article/details/gtdhpmhmbx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuxming.cn/Article/details/gtoelcknol.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.quarkkingdee.top/Article/details/gtfxqovgir.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.pengpengdd.cyou/Article/details/gtvjnueuoa.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hnqzz.top/Article/details/gtjghkjycv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hfpthk.cn/Article/details/gtawyljzzq.html

[L04] 设置超时
来源：http://dali.xuanzx.com/Article/details/gtktbqrsdf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jqgfzy.top/Article/details/gtorcnagol.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sysykeji.top/Article/details/gtpmddpmud.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nwbrower.top/Article/details/gtdzkikzlc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tian-w.cn/Article/details/gtxwlzllsc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yuanzhike.top/Article/details/gtyqivvuwe.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhoulong.xyz/Article/details/gtcwarisbo.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.9152youxi.cn/Article/details/gthtccdkbh.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hywenlv.cn/Article/details/gtcuedtcfd.html

[L05] 上传文件（multipart）
来源：http://dali.hywenlv.cn/Article/details/gtbcmpgpoq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.mhx1999.top/Article/details/gtlexjvjpj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.9152youxi.cn/Article/details/gtblwlkkrz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenlongwang.top/Article/details/gtvbpfuufa.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.9152youxi.cn/Article/details/gtifwtvias.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.316326.xyz/Article/details/gtkhybjigk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.0kj1m.cn/Article/details/gtcumduwcf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.chenzaomai.com/Article/details/gtbcrrjqzx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.smart0.xyz/Article/details/gtuxpnmkeq.html

[L06] 解析响应为 JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gtqyoaefsx.html

Py:   resp.json()
来源：http://dali.316326.xyz/Article/details/gtpnxnqflz.html

PHP:  json_decode($body, true);
来源：http://dali.ydzc1.top/Article/details/gtmlowedpl.html

JS:   await resp.json()
来源：http://dali.guowangkeji.top/Article/details/gtdkvfvrpw.html

TS:   await resp.json()
来源：http://dali.fengsongda.top/Article/details/gtbfmnpytm.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xziqi.cn/Article/details/gtxfgfycmr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.meibo888.top/Article/details/gtrbskbabf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nanxinkj.top/Article/details/gtzbqmwcul.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gzhubu.top/Article/details/gtmmuyzvxv.html

[L07] 处理 HTTP 状态码
来源：http://dali.shzxlz.cn/Article/details/gtuarrkldf.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jqgufenzy.top/Article/details/gtbgdcfiab.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yangfankeji.com/Article/details/gtzvlnpkxt.html

JS:   resp.ok;  resp.status
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhrdqyhw.html

TS:   resp.ok;  resp.status
来源：http://dali.dianchejie.cn/Article/details/gtvspigiyc.html

Java: resp.statusCode()
来源：http://dali.jqgfzy.top/Article/details/gtpjdzbxej.html

Go:   resp.StatusCode
来源：http://dali.jlsjyb.cn/Article/details/gtklywoxgp.html

Ruby: resp.code.to_i
来源：http://dali.fzhhl.top/Article/details/gtvummbvuv.html

C#:   (int)resp.StatusCode
来源：http://dali.xuanzx.com/Article/details/gtaxmtxpnv.html

[L08] 并发请求多个地址
来源：http://dali.sufxvd.cn/Article/details/gtrekeijkn.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.quarkkingdee.top/Article/details/gtqbednllr.html

PHP:  curl_multi_init() 系列
来源：http://dali.yanxiufei.cn/Article/details/gtmcdjbjck.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhongyouzk.top/Article/details/gtuiketins.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tianlin.xyz/Article/details/gtggbcgyuj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhoulong.xyz/Article/details/gtzvjycaxs.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.dashuyun.cn/Article/details/gtkrcfsydz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xuanzx.com/Article/details/gtvvzqhwgf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjjtzooaz.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtkrwnkxgn.html

M. 命令行 / 进程 / 环境
来源：http://dali.xziqi.cn/Article/details/gtvwldtqbc.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtzfzqajxu.html

[M01] 读取命令行参数
来源：http://dali.yj20258888.top/Article/details/gteerndmmp.html

Py:   sys.argv[1:]
来源：http://dali.yueranfly.top/Article/details/gtgcuzfsyu.html

PHP:  $argv;  $argc;
来源：http://dali.chenjidiqi.icu/Article/details/gthmcdnjew.html

JS:   process.argv.slice(2)
来源：http://dali.vqdsnc.cn/Article/details/gtvddwakvj.html

TS:   process.argv.slice(2)
来源：http://dali.xuanzx.com/Article/details/gtdyyzjvjm.html

Java: args 数组（main 方法参数）
来源：http://dali.shangyingyoupin.top/Article/details/gthmmfwcjl.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gtgnfecqxm.html

Ruby: ARGV
来源：http://dali.quarkkingdee.top/Article/details/gtzesizooz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xziqi.cn/Article/details/gtulftepsx.html

[M02] 读取环境变量
来源：http://dali.redwolf501.top/Article/details/gtwdyogeqy.html

Py:   os.environ.get("HOME")
来源：http://dali.cashguo.top/Article/details/gtjmnjtgis.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.mhx1999.top/Article/details/gtuvxhaopb.html

JS:   process.env.HOME
来源：http://dali.andypj.xyz/Article/details/gtwmmebkto.html

TS:   process.env.HOME
来源：http://dali.xziqi.cn/Article/details/gtqvsxdpxt.html

Java: System.getenv("HOME")
来源：http://dali.redwolf501.top/Article/details/gtdieqsnrk.html


<!-- 参考信息 -->