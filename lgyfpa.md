代发 wailian999

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yongpay.top/Article/details/gtnbwjksrc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj20258888.top/Article/details/gtbmssnshh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ydzc1.top/Article/details/gtihkmzkmf.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sweek.top/Article/details/gthqdhrubl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shzxlz.cn/Article/details/gtgyneeflr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtstcsfzdj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xylfe.cn/Article/details/gtmtwzaihn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.aizwys.cn/Article/details/gtlaqmpmpg.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jyoumei.cn/Article/details/gthmycucfn.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ehwqpu.com/Article/details/gtioobetye.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.redwolf501.top/Article/details/gtqehzqocz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenjidiqi.icu/Article/details/gtrzuhjgqy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.meibo888.top/Article/details/gtnuxbuhas.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.dianchejie.cn/Article/details/gtjqopndjv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yanxiufei.cn/Article/details/gtvzmizxww.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yj202588.top/Article/details/gtdxnhzxvd.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ivvv.top/Article/details/gtjvtublhy.html

[I07] 忽略大小写与多行模式
来源：http://dali.yueranfly.top/Article/details/gtmmoqvctp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jyoumei.cn/Article/details/gtinxlcoqh.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yonumen.top/Article/details/gtqqafijfv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sysykeji.top/Article/details/gtlufnbhqe.html

TS:   /error/gim
来源：http://dali.sxryk.cn/Article/details/gtvqfwnlyz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shangyingyoupin.top/Article/details/gtfenphgvn.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jyoumei.cn/Article/details/gtcuzgvyqf.html

Ruby: s.scan(/error/i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttpmkdisq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhoulong.xyz/Article/details/gtvukfdzen.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.wangdashe.top/Article/details/gtgrexfaht.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.aizwys.cn/Article/details/gteyiptgph.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yonumen.top/Article/details/gtecygvcwo.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgufenzy.top/Article/details/gtepgvmius.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.redwolf501.top/Article/details/gtoyhubqqe.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ehwqpu.com/Article/details/gthsbmmzvf.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.daria6918.cn/Article/details/gtloxzzehe.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.316326.xyz/Article/details/gtosofedsa.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.birdmap.top/Article/details/gtgcaedswe.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtplugloup.html

J. 日期与时间
来源：http://dali.c1oappe.top/Article/details/gtkqwxtpql.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtueqbpixy.html

[J01] 获取当前时间
来源：http://dali.nwbrower.top/Article/details/gtoxfkuflw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sweek.top/Article/details/gtvqlebavu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yj20258888.top/Article/details/gtgwlmodhn.html

JS:   new Date();  Date.now()
来源：http://dali.jqgfzy.top/Article/details/gtugkoiytn.html

TS:   new Date();  Date.now()
来源：http://dali.hnqzz.top/Article/details/gtfqolpbqh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yvedp.cn/Article/details/gtzyazgrrg.html

Go:   time.Now()
来源：http://dali.hfpthk.cn/Article/details/gttfmiredt.html

Ruby: Time.now
来源：http://dali.kuanghao11.cn/Article/details/gtvzsnxoee.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinqigfzy.top/Article/details/gthyuyymyu.html

[J02] 格式化输出
来源：http://dali.gaohongyu789.top/Article/details/gtjorhvtyu.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dianchejie.cn/Article/details/gtwygrxsys.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yvedp.cn/Article/details/gtyaimcxkw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shuidangran.top/Article/details/gtharkvkiy.html

TS:   d.toISOString()
来源：http://dali.jinqigufen.top/Article/details/gtrmsxplri.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ydzc1.top/Article/details/gtgawtvahk.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yongpay.top/Article/details/gtayypfuuf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwulfnhmy.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jiagoushi.top/Article/details/gtblamlmou.html

[J03] 字符串解析为日期
来源：http://dali.xinyue.icu/Article/details/gtojpwfkhm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.0kj1m.cn/Article/details/gtqwcvvall.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtttsmhtjb.html

JS:   new Date("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gtgkomoaxw.html

TS:   new Date("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtgqlotlaq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gtegivkzny.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gtjbqtqwjs.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gtrbdypptz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.pycfn.com/Article/details/gtzioidhub.html

[J04] 时间戳与日期互转
来源：http://dali.guowangkeji.top/Article/details/gtijdardcu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jianghu66.top/Article/details/gtpaxlnayi.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yanxiufei.cn/Article/details/gtbjsbpqxm.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jlsjyb.cn/Article/details/gtvwcurdia.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yanxiufei.cn/Article/details/gtmqjqappy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jlsjyb.cn/Article/details/gtzvttiyfd.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gotoacloud.top/Article/details/gtjoxpykln.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cheryme.top/Article/details/gtfpsepxur.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gtyuqngzqt.html

[J05] 时间加减（加 7 天）
来源：http://dali.shzxlz.cn/Article/details/gtnfqfkhyp.html

Py:   now + timedelta(days=7)
来源：http://dali.mhx1999.top/Article/details/gttpjlaowz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.andypj.xyz/Article/details/gtjnauhbby.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhoulong.xyz/Article/details/gtszyjfhee.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hongshengwenyu.top/Article/details/gtadmqcwyg.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.wangdashe.top/Article/details/gtagzhrdfp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.nwbrower.top/Article/details/gtykmqyxvt.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xinyue.icu/Article/details/gtcfmmneje.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoxrhytmw.html

[J06] 计算两时间之差
来源：http://dali.dashuyun.cn/Article/details/gtkkxwrebo.html

Py:   (end - start).total_seconds()
来源：http://dali.aizwys.cn/Article/details/gtskydhgtz.html

PHP:  $end->diff($start)->days;
来源：http://dali.yj202588.top/Article/details/gtzliqgxci.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yonumen.top/Article/details/gtcbdrizau.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cashguo.top/Article/details/gtaggglnbo.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.snrcjt.cn/Article/details/gtyjxdzyox.html

Go:   end.Sub(start).Hours()
来源：http://dali.shuidangran.top/Article/details/gtsbownqaj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jiagoushi.top/Article/details/gtvrhyydln.html

C#:   (end - start).TotalSeconds
来源：http://dali.nanxinkj.top/Article/details/gtxynflgmf.html

[J07] 比较两个日期
来源：http://dali.zhiwuduotai.top/Article/details/gtsafsnmvc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.0kj1m.cn/Article/details/gtvpefucie.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.havefunace.top/Article/details/gtvdjkzgoy.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.wangshuangyany.cn/Article/details/gtinldeynq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.fzhhl.top/Article/details/gttfvdoexl.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ydzc1.top/Article/details/gtpbfrgzpk.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sxryk.cn/Article/details/gtwraymqbh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shzxlz.cn/Article/details/gtdisvajzp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.pengpengdd.cyou/Article/details/gtcsubmury.html

[J08] 提取年月日与星期
来源：http://dali.birdmap.top/Article/details/gtvuklrbgt.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhoulong.xyz/Article/details/gtnhsrtxtk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yueranfly.top/Article/details/gtvaldopgz.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.tian-w.cn/Article/details/gthqvzgzfl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.haohaochexian.top/Article/details/gtwzgpsato.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shanyushiyangkeji.top/Article/details/gttswtyugy.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfdptqrkh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.wangshuangyany.cn/Article/details/gtzcccyfdp.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.vqdsnc.cn/Article/details/gtzfuqmomf.html

[J09] 时区处理
来源：http://dali.xuetiantiany.cn/Article/details/gteiqlaspq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.aibaodan.cn/Article/details/gtjhvqtljc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sysykeji.top/Article/details/gttkmzuknh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tian-w.cn/Article/details/gtkmlvjkak.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hongshengwenyu.top/Article/details/gtoarybnpb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nanxuanxn.top/Article/details/gtdiijwvei.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfzmwkagf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yongpay.top/Article/details/gthxvgcpwd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnkiibqbh.html

[J10] 取今天 / 本月第一天
来源：http://dali.svipenyu.cn/Article/details/gtyzcntcvf.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shuidangran.top/Article/details/gtucucthwr.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ybcxt.top/Article/details/gtfkkovbwb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.wangdashe.top/Article/details/gtfkzxhinb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.bjfxy.top/Article/details/gtsprsmtlb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.nanxinkj.top/Article/details/gtgfxlidyv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jlsjyb.cn/Article/details/gtuhaqoqpe.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ivvv.top/Article/details/gtynalvspo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinqigfzy.top/Article/details/gtfyskbygi.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlmoxcteg.html

K. JSON 与序列化
来源：http://dali.mhx1999.top/Article/details/gtkqbbbfdo.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtkgtcpcuw.html

[K01] 对象转 JSON 字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtuebxexlj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.chenlongwang.top/Article/details/gtepdzntka.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigfzy.top/Article/details/gtasxdjyps.html

JS:   JSON.stringify(obj)
来源：http://dali.ppjwa.cn/Article/details/gtnllgkrfy.html

TS:   JSON.stringify(obj)
来源：http://dali.shuidangran.top/Article/details/gtunnflyig.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.meibo888.top/Article/details/gtarjonqpr.html

Go:   json.Marshal(obj)
来源：http://dali.havefunace.top/Article/details/gthjmbpqjd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.9152youxi.cn/Article/details/gtybqjdxps.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtczcnpwal.html

[K02] JSON 字符串转对象
来源：http://dali.feifeiyinyue.top/Article/details/gtjoeuvkrh.html

Py:   json.loads(s)
来源：http://dali.xylfe.cn/Article/details/gtvhywkgbi.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sysykeji.top/Article/details/gtovbamgkt.html

JS:   JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gtbzrxdxxa.html

TS:   JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gtkfpleqmv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.9152youxi.cn/Article/details/gtvyomklfj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.tian-w.cn/Article/details/gtbicsmqau.html

Ruby: JSON.parse(s)
来源：http://dali.quarkkingdee.top/Article/details/gtwmrzogmk.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cdnleiting.top/Article/details/gtezflstmt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cucudq.cn/Article/details/gthunzuxiu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.tian-w.cn/Article/details/gtyymuamks.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jyoumei.cn/Article/details/gtansbsohj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gogol.net.cn/Article/details/gtflbtgvdd.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gtmokzwxpe.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnzfyenul.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.chenlongwang.top/Article/details/gturcnhclq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcmciwycc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gthrdcdszx.html

[K04] 读取 JSON 文件
来源：http://dali.tianlin.xyz/Article/details/gtrzoghzbk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.wangshuangyany.cn/Article/details/gtdctworrj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hysaishi.cn/Article/details/gthiwyhonw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.andypj.xyz/Article/details/gtboeravze.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.dashuyun.cn/Article/details/gteabqkvdz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.c1oappe.top/Article/details/gtfycgjeii.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.smart0.xyz/Article/details/gtrfajaetw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xinyue.icu/Article/details/gtkabtrlmt.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfrpwwrhr.html

[K05] 深拷贝对象
来源：http://dali.snrcjt.cn/Article/details/gtglqmmhow.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtywjlvqlx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gotoacloud.top/Article/details/gtndywxrna.html

JS:   structuredClone(obj)
来源：http://dali.yj20258888.top/Article/details/gtrojxxrdn.html

TS:   structuredClone(obj)
来源：http://dali.shuidangran.top/Article/details/gtyqjfiyrv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xinyue.icu/Article/details/gtlcoohrsz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.wangdashe.top/Article/details/gtzhejydlz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.shzxlz.cn/Article/details/gtshjmdoll.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinghuilouyu.cn/Article/details/gtsakbvvsj.html

[K06] 解析 URL 查询串
来源：http://dali.jinqigfzy.top/Article/details/gtfvxjclnp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shzxlz.cn/Article/details/gtundymupz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfrmtkbhh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gtijsptats.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jiagoushi.top/Article/details/gtsdjbblio.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.nanxinkj.top/Article/details/gttorfvxft.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shangyingyoupin.top/Article/details/gteejadszx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhiwuduotai.top/Article/details/gtmtwtppwl.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj20258.top/Article/details/gticgehvzv.html

[K07] 进制转换
来源：http://dali.yonumen.top/Article/details/gtyvhuawcx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gthmwufgso.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaoknpibt.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gtbmynqrhg.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yj20258.top/Article/details/gtdxuwqilr.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gtyyanpagv.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hnxiangtu.top/Article/details/gtojddqddk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cashguo.top/Article/details/gtiitawwut.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtvvpeviyc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jyoumei.cn/Article/details/gtvvsmzjeg.html

Py:   pickle.dumps(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfsnycrhg.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hnqzz.top/Article/details/gtmwvqstek.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cheryme.top/Article/details/gtkouxntvr.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gzhubu.top/Article/details/gtpyheuwub.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yuxming.cn/Article/details/gtdactnoms.html

Go:   encoding/gob
来源：http://dali.fengsongda.top/Article/details/gtqimgqqvv.html

Ruby: Marshal.dump(obj)
来源：http://dali.ppjwa.cn/Article/details/gttpnkspqu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.c1oappe.top/Article/details/gtbenaatoj.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtqsahxxse.html

L. 网络请求
来源：http://dali.ppjwa.cn/Article/details/gtalhozwev.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gteiqmwhow.html

[L01] 发送 GET 请求
来源：http://dali.iojbl.cn/Article/details/gtqxjaojba.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.quarkkingdee.top/Article/details/gtuednvbjc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhiwuduotai.top/Article/details/gtofjqqucl.html

JS:   await fetch(url)
来源：http://dali.sufxvd.cn/Article/details/gthrymxrho.html

TS:   await fetch(url)
来源：http://dali.aizwys.cn/Article/details/gtnpqparhw.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhengqikj.top/Article/details/gthntbwefd.html

Go:   resp, err := http.Get(url)
来源：http://dali.shzxlz.cn/Article/details/gtkgbodqmm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zycfv.cn/Article/details/gtnxeleitb.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.birdmap.top/Article/details/gtlpmrbhoo.html

[L02] 发送 POST JSON
来源：http://dali.xylfe.cn/Article/details/gtaubbigaa.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yangfankeji.com/Article/details/gtelvukeug.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.svipenyu.cn/Article/details/gtungcrpjy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gogol.net.cn/Article/details/gtnngeojof.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.andypj.xyz/Article/details/gtyfvbcamz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.andypj.xyz/Article/details/gtybwnhtvx.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.chenjidiqi.icu/Article/details/gtvyfsflzc.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.nwbrower.top/Article/details/gtwyxribjv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.fzhhl.top/Article/details/gtyslnhoqc.html

[L03] 设置自定义请求头
来源：http://dali.zycfv.cn/Article/details/gtixsulpws.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hnxiangtu.top/Article/details/gtwrtkoqjf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cashguo.top/Article/details/gtbemdtwxv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xziqi.cn/Article/details/gtducgpelt.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtettaloqj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.dashuyun.cn/Article/details/gttscfqhyu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gotoacloud.top/Article/details/gtmuwaiufp.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.pengpengdd.cyou/Article/details/gtaofpzpci.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.316326.xyz/Article/details/gtcvwdmiet.html

[L04] 设置超时
来源：http://dali.hywenlv.cn/Article/details/gtezubdgrr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gotoacloud.top/Article/details/gtfrjkclkg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.smart0.xyz/Article/details/gtpeggvacf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.bjfxy.top/Article/details/gtuuacpvkr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shzxlz.cn/Article/details/gttxfmwwft.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.chenzaomai.com/Article/details/gtwbsazfug.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.0kj1m.cn/Article/details/gtdotgcrdd.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yanxiufei.cn/Article/details/gtrqpbwtgg.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.fzhhl.top/Article/details/gtceabdrof.html

[L05] 上传文件（multipart）
来源：http://dali.wangshuangyany.cn/Article/details/gtuleuzdga.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shzxlz.cn/Article/details/gtisdkjjay.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoxavjobf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.nwbrower.top/Article/details/gtfsslbtcl.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.kuanghao11.cn/Article/details/gtupvbfxtl.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hnqzz.top/Article/details/gtqivatwph.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gzhubu.top/Article/details/gtsfkkzexb.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.quarkkingdee.top/Article/details/gtgkipcwnf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtcvvmeyfl.html

[L06] 解析响应为 JSON
来源：http://dali.nwbrower.top/Article/details/gtskragtzf.html

Py:   resp.json()
来源：http://dali.0kj1m.cn/Article/details/gtqtxuvspf.html

PHP:  json_decode($body, true);
来源：http://dali.cdnleiting.top/Article/details/gtwvcwpqvy.html

JS:   await resp.json()
来源：http://dali.kuanghao11.cn/Article/details/gtukskbqlr.html

TS:   await resp.json()
来源：http://dali.guannengcc.top/Article/details/gtwgfplsnp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ehwqpu.com/Article/details/gtwawsavbb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yonumen.top/Article/details/gtipcyivuz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.iojbl.cn/Article/details/gttzutburf.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xuanzx.com/Article/details/gtgjogytna.html

[L07] 处理 HTTP 状态码
来源：http://dali.jqgfzy.top/Article/details/gtjtsbdntd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jiagoushi.top/Article/details/gtuixmapjq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jiagoushi.top/Article/details/gttqvrumov.html

JS:   resp.ok;  resp.status
来源：http://dali.nwbrower.top/Article/details/gtevdvcnka.html

TS:   resp.ok;  resp.status
来源：http://dali.kuanghao11.cn/Article/details/gtwlboautu.html

Java: resp.statusCode()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrmhhfqkt.html

Go:   resp.StatusCode
来源：http://dali.kuanghao11.cn/Article/details/gtqggyijsd.html

Ruby: resp.code.to_i
来源：http://dali.kuanghao11.cn/Article/details/gtifmuiolp.html

C#:   (int)resp.StatusCode
来源：http://dali.daxiang520.top/Article/details/gtmhgqejrg.html

[L08] 并发请求多个地址
来源：http://dali.guowangkeji.top/Article/details/gtcvytcflt.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zycfv.cn/Article/details/gtejfkbqpk.html

PHP:  curl_multi_init() 系列
来源：http://dali.xinyue.icu/Article/details/gtpxoryuqf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ivvv.top/Article/details/gtsegstxvs.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.feifeiyinyue.top/Article/details/gtaiucjbxe.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhixingplan.top/Article/details/gtnukdzdni.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.c1oappe.top/Article/details/gtpjxeedqs.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cheryme.top/Article/details/gtluakrryg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.c1oappe.top/Article/details/gtlznxbsir.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtsdtnsueu.html

M. 命令行 / 进程 / 环境
来源：http://dali.gzhubu.top/Article/details/gtuckwxegg.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtjkvgqubl.html

[M01] 读取命令行参数
来源：http://dali.gaohongyu789.top/Article/details/gtyxbnxivz.html

Py:   sys.argv[1:]
来源：http://dali.xuetiantiany.cn/Article/details/gtzmszpcuc.html

PHP:  $argv;  $argc;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtngjknpdk.html

JS:   process.argv.slice(2)
来源：http://dali.iojbl.cn/Article/details/gtlweriqbc.html

TS:   process.argv.slice(2)
来源：http://dali.yueranfly.top/Article/details/gtcdtgzdht.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gtoqvdnmry.html

Go:   os.Args[1:]
来源：http://dali.sxryk.cn/Article/details/gtauaxdqtm.html

Ruby: ARGV
来源：http://dali.jinqigfzy.top/Article/details/gtpldyoteq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.kuanghao11.cn/Article/details/gtfmejmpeo.html

[M02] 读取环境变量
来源：http://dali.nanxinkj.top/Article/details/gtqaxcrywh.html

Py:   os.environ.get("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gteuhmjcdf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.316326.xyz/Article/details/gtvmalhgih.html

JS:   process.env.HOME
来源：http://dali.0kj1m.cn/Article/details/gttemghzfp.html

TS:   process.env.HOME
来源：http://dali.chenlongwang.top/Article/details/gtjlongxid.html

Java: System.getenv("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gtdzadmrwr.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sufxvd.cn/Article/details/gtkvgkdmcy.html

Ruby: ENV["HOME"]
来源：http://dali.vqdsnc.cn/Article/details/gtmgumtkem.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.havefunace.top/Article/details/gtxzqoshkg.html

[M03] 执行外部命令
来源：http://dali.quarkkingdee.top/Article/details/gtangwatox.html


<!-- 参考信息 -->