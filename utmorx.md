代发 wailian999

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ybcxt.top/Article/details/gtudguzdfy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ehwqpu.com/Article/details/gtevatbqzy.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.chenzaomai.com/Article/details/gtmyffovno.html

[I05] 按正则拆分
来源：http://dali.yj20258.top/Article/details/gtezoktphr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cqqwz.cn/Article/details/gtczjgxwqz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yueranfly.top/Article/details/gthxwrvkfa.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ivvv.top/Article/details/gtzscgsvcs.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.andypj.xyz/Article/details/gtpsvzjsel.html

Java: s.split("\\s*,\\s*")
来源：http://dali.iojbl.cn/Article/details/gtemnmljgb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.guowangkeji.top/Article/details/gtvlzidnwp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gtwlamqtiu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.iojbl.cn/Article/details/gtvoyxmkum.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.pengpengdd.cyou/Article/details/gtbsfmynma.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.0kj1m.cn/Article/details/gtheresetp.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.kuanghao11.cn/Article/details/gtgddqfudm.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnxiangtu.top/Article/details/gtbvpxjyjf.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.316326.xyz/Article/details/gturiahnhd.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.chenjidiqi.icu/Article/details/gtodblyfoi.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gzhubu.top/Article/details/gtngfpnczo.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hywenlv.cn/Article/details/gtpyeqbjsw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtssazfrjt.html

[I07] 忽略大小写与多行模式
来源：http://dali.hysaishi.cn/Article/details/gtyjjtrbio.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.0kj1m.cn/Article/details/gtwqmayipo.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jiagoushi.top/Article/details/gtrczsnoqi.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvboufewm.html

TS:   /error/gim
来源：http://dali.sweek.top/Article/details/gtbvxzalmt.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.fengsongda.top/Article/details/gtmscdgqpv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shuidangran.top/Article/details/gtmrjdwsyk.html

Ruby: s.scan(/error/i)
来源：http://dali.jianghu66.top/Article/details/gtbuziswjf.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvewdfjxl.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhongyouzk.top/Article/details/gtchexrcml.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.chenlongwang.top/Article/details/gtxaokebwu.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinghuilouyu.cn/Article/details/gthtmaqixz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.smart0.xyz/Article/details/gtwhfuzlif.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.snrcjt.cn/Article/details/gtswoluufb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hammf.cn/Article/details/gtrfssolyn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.tianlin.xyz/Article/details/gtzxonpxes.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.kuanghao11.cn/Article/details/gtfszzxibu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jqgfzy.top/Article/details/gtemlbnrgv.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtnhzmvfsp.html

J. 日期与时间
来源：http://dali.pengpengdd.cyou/Article/details/gtqqsgzppl.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtnrlhplby.html

[J01] 获取当前时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gtntgmanht.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hammf.cn/Article/details/gtnyxvjody.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shanyushiyangkeji.top/Article/details/gthwvplyqs.html

JS:   new Date();  Date.now()
来源：http://dali.jlsjyb.cn/Article/details/gthpgnjnyj.html

TS:   new Date();  Date.now()
来源：http://dali.wangshuangyany.cn/Article/details/gtcizcmuhs.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.snrcjt.cn/Article/details/gttgresfwc.html

Go:   time.Now()
来源：http://dali.cucudq.cn/Article/details/gtyhgteqda.html

Ruby: Time.now
来源：http://dali.ehwqpu.com/Article/details/gthnwtkbfo.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtinhwjbbs.html

[J02] 格式化输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gthwohabnq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.meibo888.top/Article/details/gtowwliija.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.0kj1m.cn/Article/details/gtjcsmsbtc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.tanke756.top/Article/details/gtuxcogpde.html

TS:   d.toISOString()
来源：http://dali.sweek.top/Article/details/gtfbcwgkcq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ehwqpu.com/Article/details/gtyxrylewh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.svipenyu.cn/Article/details/gtiucomhad.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jlsjyb.cn/Article/details/gtqfkmisrg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shanyushiyangtech.top/Article/details/gtamdfguap.html

[J03] 字符串解析为日期
来源：http://dali.ydzc1.top/Article/details/gtwwyzakne.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gotoacloud.top/Article/details/gtaqmtmmbx.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.fengsongda.top/Article/details/gtcfiwqcue.html

JS:   new Date("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtsjztvipb.html

TS:   new Date("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gtjdfuaeet.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtofirkwrn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hammf.cn/Article/details/gtjlvyabyc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gtckzikrup.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yanxiufei.cn/Article/details/gtaqqrkvww.html

[J04] 时间戳与日期互转
来源：http://dali.hnqzz.top/Article/details/gtdnleqgwh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hywenlv.cn/Article/details/gthsqejbqv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cdnleiting.top/Article/details/gtvmxlpyvc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yj20258.top/Article/details/gtzoeugiuz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.chenlongwang.top/Article/details/gtcflurcun.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gthjfwyuhu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jyoumei.cn/Article/details/gthemyaqco.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yanxiufei.cn/Article/details/gtmgehgtrp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.dashuyun.cn/Article/details/gtzaausovv.html

[J05] 时间加减（加 7 天）
来源：http://dali.tianlin.xyz/Article/details/gtgjrnnuuz.html

Py:   now + timedelta(days=7)
来源：http://dali.feifeiyinyue.top/Article/details/gtuobifard.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.iojbl.cn/Article/details/gtcrenqevw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangtech.top/Article/details/gtaxxcjciw.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.0kj1m.cn/Article/details/gtjlqwclpx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jiagoushi.top/Article/details/gtjfynkqqi.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.bjfxy.top/Article/details/gtpryuuurh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shangyingyoupin.top/Article/details/gtekelqgpa.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jyoumei.cn/Article/details/gtfrmkkmlf.html

[J06] 计算两时间之差
来源：http://dali.fengsongda.top/Article/details/gtuifuhsad.html

Py:   (end - start).total_seconds()
来源：http://dali.jyoumei.cn/Article/details/gtkhewdqui.html

PHP:  $end->diff($start)->days;
来源：http://dali.yanxiufei.cn/Article/details/gtlycbyxkk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.redwolf501.top/Article/details/gtefmogeng.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xziqi.cn/Article/details/gtztzujazz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.pengpengdd.cyou/Article/details/gtpmbpxhpt.html

Go:   end.Sub(start).Hours()
来源：http://dali.daxiang520.top/Article/details/gtywpjlale.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcyrrelzw.html

C#:   (end - start).TotalSeconds
来源：http://dali.jyoumei.cn/Article/details/gtmbtdmtgp.html

[J07] 比较两个日期
来源：http://dali.jqgfzy.top/Article/details/gtwlepnhjb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tian-w.cn/Article/details/gtvkdyuyad.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtamwgfrwt.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ivvv.top/Article/details/gtnqfduvby.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.wangdashe.top/Article/details/gtjevjyqbx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.dianchejie.cn/Article/details/gtkibdqzeg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hysaishi.cn/Article/details/gtluyvpcna.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.aizwys.cn/Article/details/gtvrmjgyof.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yongpay.top/Article/details/gtiqnafnhi.html

[J08] 提取年月日与星期
来源：http://dali.birdmap.top/Article/details/gtenjqamdc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.iojbl.cn/Article/details/gtodktxjkp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shangyingyoupin.top/Article/details/gticnkqywy.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.iojbl.cn/Article/details/gtokdlxjvh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcwgtdlue.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.pengpengdd.cyou/Article/details/gtkfbjsqzo.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhongyouzk.top/Article/details/gtzngyqrgr.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shzxlz.cn/Article/details/gtjlfkjuvu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hywenlv.cn/Article/details/gtkudtawzw.html

[J09] 时区处理
来源：http://dali.vqdsnc.cn/Article/details/gtulmrvhgs.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sxryk.cn/Article/details/gtzlbnxygg.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sweek.top/Article/details/gtdiqskvsn.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sxryk.cn/Article/details/gtrokzjodx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gzhubu.top/Article/details/gtetyngbyn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jianghu66.top/Article/details/gtngqoaimr.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhijiandao.cn/Article/details/gtydhrbatr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.chenzaomai.com/Article/details/gtufnijztk.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinqigfzy.top/Article/details/gtdzbzsdqt.html

[J10] 取今天 / 本月第一天
来源：http://dali.sxryk.cn/Article/details/gtbshwfepx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.wangshuangyany.cn/Article/details/gtoctfjxmp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yanxiufei.cn/Article/details/gtiqnsxqdx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqdnllucf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hnqzz.top/Article/details/gtyzaltcjr.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ydzc1.top/Article/details/gtriiyyqvb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cucudq.cn/Article/details/gtkqiqkfmx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.daria6918.cn/Article/details/gtuzmwzlua.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jianghu66.top/Article/details/gtqtlrzmgt.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtykpaqxsy.html

K. JSON 与序列化
来源：http://dali.birdmap.top/Article/details/gtwqowzpxu.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzoyucoue.html

[K01] 对象转 JSON 字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjdufmyvw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.nanxinkj.top/Article/details/gtvfpngzfo.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jlsjyb.cn/Article/details/gtvpuuyfbz.html

JS:   JSON.stringify(obj)
来源：http://dali.hfpthk.cn/Article/details/gttcttjbso.html

TS:   JSON.stringify(obj)
来源：http://dali.guannengcc.top/Article/details/gtwqajbngq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.9152youxi.cn/Article/details/gtxmhyxlgn.html

Go:   json.Marshal(obj)
来源：http://dali.andypj.xyz/Article/details/gteaqzdvmz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gogol.net.cn/Article/details/gtwezxnbow.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cheryme.top/Article/details/gtfzqzgkax.html

[K02] JSON 字符串转对象
来源：http://dali.xinyue.icu/Article/details/gtratmuwsm.html

Py:   json.loads(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvljqtluy.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yonumen.top/Article/details/gthhqcifgv.html

JS:   JSON.parse(s)
来源：http://dali.daria6918.cn/Article/details/gtdhebnhrn.html

TS:   JSON.parse(s)
来源：http://dali.jyoumei.cn/Article/details/gtdnczwnda.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yuanzhike.top/Article/details/gtdordhdbn.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sysykeji.top/Article/details/gtubjbmjsb.html

Ruby: JSON.parse(s)
来源：http://dali.yuanzhike.top/Article/details/gtsdvevuvd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtngalrmgm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.pengpengdd.cyou/Article/details/gtrcicspsk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jqgufenzy.top/Article/details/gtlduuygds.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.iojbl.cn/Article/details/gttoivepde.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cheryme.top/Article/details/gtmsbydrxv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhoulong.xyz/Article/details/gtkcxkrqcu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.wangdashe.top/Article/details/gtuavezssw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jiagoushi.top/Article/details/gtutevxcml.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvnltfpto.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jianghu66.top/Article/details/gtztxrqzyl.html

[K04] 读取 JSON 文件
来源：http://dali.zycfv.cn/Article/details/gtbubgtuaa.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sweek.top/Article/details/gtwmmxshun.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.chenlongwang.top/Article/details/gthlbudury.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cucudq.cn/Article/details/gthlvxufty.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cucudq.cn/Article/details/gtyhhzvhzn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yanxiufei.cn/Article/details/gtcdvaalsr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xuetiantiany.cn/Article/details/gttrtniqkq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gthcjuxcel.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sufxvd.cn/Article/details/gtqobovljo.html

[K05] 深拷贝对象
来源：http://dali.fengsongda.top/Article/details/gttqrrcrxq.html

Py:   copy.deepcopy(obj)
来源：http://dali.yvedp.cn/Article/details/gtepgcnqxk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.aibaodan.cn/Article/details/gtbokfazmm.html

JS:   structuredClone(obj)
来源：http://dali.ppjwa.cn/Article/details/gtbjgfafxm.html

TS:   structuredClone(obj)
来源：http://dali.jyoumei.cn/Article/details/gtbspjohzq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cashguo.top/Article/details/gtcnjoubmg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yvedp.cn/Article/details/gtxpsqhtdb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.316326.xyz/Article/details/gtkpzhdbwp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cashguo.top/Article/details/gtpwrfwjne.html

[K06] 解析 URL 查询串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpwpdevkz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.tanke756.top/Article/details/gtzuvifhlw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yuanzhike.top/Article/details/gthgaktgce.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.svipenyu.cn/Article/details/gtozqbkbpg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258.top/Article/details/gtumthwydy.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.kuanghao11.cn/Article/details/gtmkojulcm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gtbuldrasc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinghuilouyu.cn/Article/details/gtqqlgzsda.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.fzhhl.top/Article/details/gtyowlipwu.html

[K07] 进制转换
来源：http://dali.svipenyu.cn/Article/details/gtxodbmeil.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gtajwukjvf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhengqikj.top/Article/details/gtcqmqtohv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gtoesqhmax.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gtbhygrozk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gtyzqpucot.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.birdmap.top/Article/details/gtxbngmmqz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.mhx1999.top/Article/details/gtxrglzxke.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gtrkxxfqff.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gaohongyu789.top/Article/details/gtxzjqstze.html

Py:   pickle.dumps(obj)
来源：http://dali.pycfn.com/Article/details/gtrvwmxejb.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yuxming.cn/Article/details/gtamcuyvho.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.tianlin.xyz/Article/details/gtkjddkixp.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.bjfxy.top/Article/details/gtjckdaqgl.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.kuanghao11.cn/Article/details/gtqnqnwxno.html

Go:   encoding/gob
来源：http://dali.yonumen.top/Article/details/gtscdfplro.html

Ruby: Marshal.dump(obj)
来源：http://dali.cqqwz.cn/Article/details/gtevotqfzc.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zycfv.cn/Article/details/gtxxmdgbmk.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtbieqktau.html

L. 网络请求
来源：http://dali.jinqigufen.top/Article/details/gtrkigtsdp.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtsmubgvcu.html

[L01] 发送 GET 请求
来源：http://dali.xuanzx.com/Article/details/gtyxjtrnzx.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.fengsongda.top/Article/details/gtjpitpdol.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxmjmgjrp.html

JS:   await fetch(url)
来源：http://dali.jyoumei.cn/Article/details/gtaxzqagiw.html

TS:   await fetch(url)
来源：http://dali.jianghu66.top/Article/details/gtwuimnbbt.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzbxhttyq.html

Go:   resp, err := http.Get(url)
来源：http://dali.yj20258888.top/Article/details/gtndorlpll.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.pycfn.com/Article/details/gtoojezybt.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.chenjidiqi.icu/Article/details/gtqtvmvgeb.html

[L02] 发送 POST JSON
来源：http://dali.xziqi.cn/Article/details/gtqcufcxtj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yuanzhike.top/Article/details/gterythatg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yangfankeji.com/Article/details/gtxijcbdfn.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigfzy.top/Article/details/gtsxtowsfo.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nwbrower.top/Article/details/gttgzyvfno.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cqqwz.cn/Article/details/gteecnvvau.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhongyouzk.top/Article/details/gtnymzreru.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hongshengwenyu.top/Article/details/gtfbimkdjj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xuanzx.com/Article/details/gtaydmqzlw.html

[L03] 设置自定义请求头
来源：http://dali.jinghuilouyu.cn/Article/details/gtugejmlzo.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.havefunace.top/Article/details/gtanpsnzgt.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhiwuduotai.top/Article/details/gtmzzgsxcy.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jqgfzy.top/Article/details/gtfwbmdgmi.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.meibo888.top/Article/details/gtgotleqzq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.tianlin.xyz/Article/details/gtoecczxba.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.dashuyun.cn/Article/details/gtcpajstba.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xziqi.cn/Article/details/gtqudnnmmw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jianghu66.top/Article/details/gtrzkhfybu.html

[L04] 设置超时
来源：http://dali.zycfv.cn/Article/details/gtdnmlqxwq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zdqjudy.top/Article/details/gtovlymchd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhiwuduotai.top/Article/details/gtlwunquor.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuetiantiany.cn/Article/details/gthlqxsrmz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.guowangkeji.top/Article/details/gttzjhbcpy.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.aibaodan.cn/Article/details/gtfsoeewwg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gzhubu.top/Article/details/gtaojulwsi.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtodpiyjxs.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hywenlv.cn/Article/details/gtxuoeknmq.html

[L05] 上传文件（multipart）
来源：http://dali.gotoacloud.top/Article/details/gtsnwsbpgn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinqigfzy.top/Article/details/gtrgryrtxk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yuxming.cn/Article/details/gtbeppuqku.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhoulong.xyz/Article/details/gtpviouupw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.dianchejie.cn/Article/details/gtjeskrkud.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.pycfn.com/Article/details/gtczbrzakv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.haohaochexian.top/Article/details/gtxkiljoqr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.quarkkingdee.top/Article/details/gtgclzrele.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvghryity.html

[L06] 解析响应为 JSON
来源：http://dali.pengpengdd.cyou/Article/details/gtmxgnmxrz.html

Py:   resp.json()
来源：http://dali.yuanzhike.top/Article/details/gtzceplvic.html

PHP:  json_decode($body, true);
来源：http://dali.hywenlv.cn/Article/details/gtfnvxexnj.html

JS:   await resp.json()
来源：http://dali.smart0.xyz/Article/details/gtsersfqlx.html

TS:   await resp.json()
来源：http://dali.yanxiufei.cn/Article/details/gtyvgtdwmw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hnqzz.top/Article/details/gtqgrxeoas.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sxryk.cn/Article/details/gtrsckzdsr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.fengsongda.top/Article/details/gtfhetewdd.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cqqwz.cn/Article/details/gtsnqhlmfq.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhoulong.xyz/Article/details/gtysanprrb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj20258888.top/Article/details/gtqnxihxkx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yj20258888.top/Article/details/gtzrjjwurr.html

JS:   resp.ok;  resp.status
来源：http://dali.hnqzz.top/Article/details/gtzuklmzrw.html

TS:   resp.ok;  resp.status
来源：http://dali.yonumen.top/Article/details/gthahqbcgy.html

Java: resp.statusCode()
来源：http://dali.fengsongda.top/Article/details/gtiffpykvt.html

Go:   resp.StatusCode
来源：http://dali.daxiang520.top/Article/details/gtbunqdrrq.html

Ruby: resp.code.to_i
来源：http://dali.hnxiangtu.top/Article/details/gtjtwisijb.html

C#:   (int)resp.StatusCode
来源：http://dali.mhx1999.top/Article/details/gtpdbsvaot.html

[L08] 并发请求多个地址
来源：http://dali.sweek.top/Article/details/gttkicaqow.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.nanxuanxn.top/Article/details/gtrexmnicz.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhoulong.xyz/Article/details/gthyzuvutl.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcllvihfb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.kuanghao11.cn/Article/details/gtornfilpb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.tian-w.cn/Article/details/gtnsyjtktg.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.bjfxy.top/Article/details/gtyfmhbecy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ppjwa.cn/Article/details/gttucwybwf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gotoacloud.top/Article/details/gtsnalixqs.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtsjxwjdek.html

M. 命令行 / 进程 / 环境
来源：http://dali.jqgfzy.top/Article/details/gtabxubzeo.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtkczqdtdz.html

[M01] 读取命令行参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqfqqqxow.html

Py:   sys.argv[1:]
来源：http://dali.bjfxy.top/Article/details/gtskuolyav.html

PHP:  $argv;  $argc;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrxfpibgs.html

JS:   process.argv.slice(2)
来源：http://dali.gaohongyu789.top/Article/details/gtcvmzieiw.html

TS:   process.argv.slice(2)
来源：http://dali.hysaishi.cn/Article/details/gtbbkcjvhl.html

Java: args 数组（main 方法参数）
来源：http://dali.yuanzhike.top/Article/details/gtzqauokid.html

Go:   os.Args[1:]
来源：http://dali.aibaodan.cn/Article/details/gtlnoycdmv.html

Ruby: ARGV
来源：http://dali.shuidangran.top/Article/details/gteeqvwnjf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shanyushiyangtech.top/Article/details/gtvufdyhji.html

[M02] 读取环境变量
来源：http://dali.mhx1999.top/Article/details/gtasbxmfre.html

Py:   os.environ.get("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gtldgceasd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zycfv.cn/Article/details/gtiwqjckte.html

JS:   process.env.HOME
来源：http://dali.9152youxi.cn/Article/details/gtlkxczhze.html

TS:   process.env.HOME
来源：http://dali.andypj.xyz/Article/details/gtnmwixuim.html

Java: System.getenv("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gtkxsmosgn.html


<!-- 参考信息 -->