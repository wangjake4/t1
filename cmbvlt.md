代发 wailian999

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yvedp.cn/Article/details/gtqvfhgewg.html

Go:   defer f.Close()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmvajxkco.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jlsjyb.cn/Article/details/gtrnqoqbfq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtftinbmfr.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtvegysrvm.html

I. 正则表达式
来源：http://dali.birdmap.top/Article/details/gtipilkcgy.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtfwjgxhwk.html

[I01] 判断是否匹配
来源：http://dali.cqqwz.cn/Article/details/gtspwghcoo.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yuxming.cn/Article/details/gtwsnazaiu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.haohaochexian.top/Article/details/gtityjcnqs.html

JS:   /\d+/.test(s)
来源：http://dali.andypj.xyz/Article/details/gtzztvfdds.html

TS:   /\d+/.test(s)
来源：http://dali.yuxming.cn/Article/details/gtyluhzmql.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ehwqpu.com/Article/details/gtoqxszlmk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.guowangkeji.top/Article/details/gthdhrbkra.html

Ruby: s.match?(/\d+/)
来源：http://dali.daxiang520.top/Article/details/gtlduosafl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.chenlongwang.top/Article/details/gtwbewlpbt.html

[I02] 提取所有匹配
来源：http://dali.0kj1m.cn/Article/details/gtxogximks.html

Py:   re.findall(r"\d+", s)
来源：http://dali.kuanghao11.cn/Article/details/gtytwkjgrh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.andypj.xyz/Article/details/gtctkhfkic.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yanxiufei.cn/Article/details/gturhctjpq.html

TS:   s.match(/\d+/g)
来源：http://dali.meibo888.top/Article/details/gtdfsyirlm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.guowangkeji.top/Article/details/gtippvhjex.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yuxming.cn/Article/details/gttsxbyltl.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gtxcqufbom.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ybcxt.top/Article/details/gtujjqtzyr.html

[I03] 提取捕获分组
来源：http://dali.bjfxy.top/Article/details/gtdtvfhpwu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yongpay.top/Article/details/gtknuhqkop.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yueranfly.top/Article/details/gtddghrkns.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xziqi.cn/Article/details/gtiptvfcrh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sxryk.cn/Article/details/gtsrelmwbg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.snrcjt.cn/Article/details/gtlqieogun.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.0kj1m.cn/Article/details/gtykqbpurz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ybcxt.top/Article/details/gtbyjntddv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xziqi.cn/Article/details/gtigimhqcf.html

[I04] 正则替换
来源：http://dali.dashuyun.cn/Article/details/gtiggeokuy.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gaohongyu789.top/Article/details/gtnivlyjuo.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zycfv.cn/Article/details/gtygcxgpaf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xylfe.cn/Article/details/gtavecdyjw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxinkj.top/Article/details/gtdskrqktz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yuxming.cn/Article/details/gtmxyqgpti.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hywenlv.cn/Article/details/gtklitdyzq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.daxiang520.top/Article/details/gtxzglfpbn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.tian-w.cn/Article/details/gtufecworw.html

[I05] 按正则拆分
来源：http://dali.cashguo.top/Article/details/gtgyjatdlp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cheryme.top/Article/details/gtfygakgfu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.snrcjt.cn/Article/details/gtcwwqjfkr.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gtexrebhmp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gthmtnxkbt.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yangfankeji.com/Article/details/gtdfolowjx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xinyue.icu/Article/details/gtuktltsnl.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gtraaocchu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.316326.xyz/Article/details/gtmbbtehmh.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmgrzxija.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yj20258.top/Article/details/gthfbpptur.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.wangshuangyany.cn/Article/details/gtatzgohok.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.haohaochexian.top/Article/details/gtwisaulpi.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangdashe.top/Article/details/gtsdifrkot.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.daria6918.cn/Article/details/gtqjicovth.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xuanzx.com/Article/details/gtnrhjvoya.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jiagoushi.top/Article/details/gtbeaggzlm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhoulong.xyz/Article/details/gtvkyhimjl.html

[I07] 忽略大小写与多行模式
来源：http://dali.gzhubu.top/Article/details/gtcombpqui.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jianghu66.top/Article/details/gtfzqmvdkq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.pycfn.com/Article/details/gtfecxolwe.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sxryk.cn/Article/details/gtfguycvce.html

TS:   /error/gim
来源：http://dali.gaohongyu789.top/Article/details/gtoducokpm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.9152youxi.cn/Article/details/gtuozthahe.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jqgfzy.top/Article/details/gtdewcuuil.html

Ruby: s.scan(/error/i)
来源：http://dali.zycfv.cn/Article/details/gtxyqzfppt.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jqgufenzy.top/Article/details/gtrprxeqpv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.bjfxy.top/Article/details/gtmuhjoprd.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.vqdsnc.cn/Article/details/gtbhojhohb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hywenlv.cn/Article/details/gtcjmbwwxx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cdnleiting.top/Article/details/gtoiwzkwva.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ybcxt.top/Article/details/gttquqyngt.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hammf.cn/Article/details/gtvzyvjwwe.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinqigfzy.top/Article/details/gtnvdtfpix.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shzxlz.cn/Article/details/gtyppfartw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenlongwang.top/Article/details/gttbiynskd.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtxwbphjhy.html

J. 日期与时间
来源：http://dali.xuanzx.com/Article/details/gtcfvzlaen.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtlermbprn.html

[J01] 获取当前时间
来源：http://dali.shangyingyoupin.top/Article/details/gtzmvzizge.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj20258888.top/Article/details/gtgffxuqyi.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yonumen.top/Article/details/gtecmvwhze.html

JS:   new Date();  Date.now()
来源：http://dali.chenzaomai.com/Article/details/gtpqeitbbe.html

TS:   new Date();  Date.now()
来源：http://dali.bjfxy.top/Article/details/gtfsczrqpk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hongshengwenyu.top/Article/details/gtbpdfbsar.html

Go:   time.Now()
来源：http://dali.kuanghao11.cn/Article/details/gtmcdklydr.html

Ruby: Time.now
来源：http://dali.havefunace.top/Article/details/gtnkrduvtx.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.guowangkeji.top/Article/details/gtbgapyfsp.html

[J02] 格式化输出
来源：http://dali.gzhubu.top/Article/details/gtknejhpji.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenjidiqi.icu/Article/details/gtqqplkhzm.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcsyirdjy.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zdqjudy.top/Article/details/gtrommzwnp.html

TS:   d.toISOString()
来源：http://dali.yj202588.top/Article/details/gtddpflftw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hnqzz.top/Article/details/gtklevlvez.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.wangdashe.top/Article/details/gtfxymvcwh.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ehwqpu.com/Article/details/gttesfvkfe.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cdnleiting.top/Article/details/gtlhanwbjm.html

[J03] 字符串解析为日期
来源：http://dali.ehwqpu.com/Article/details/gteorvxygr.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinghuilouyu.cn/Article/details/gttdnjypzx.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hongshengwenyu.top/Article/details/gtqgfnnklp.html

JS:   new Date("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gtlgcscfru.html

TS:   new Date("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gtarzfosuq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gthpzkijta.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sweek.top/Article/details/gtxcfvxacl.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gtjzcspmio.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jqgufenzy.top/Article/details/gtitdslsad.html

[J04] 时间戳与日期互转
来源：http://dali.daxiang520.top/Article/details/gtvhqohmjd.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xinyue.icu/Article/details/gtftwebmch.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.smart0.xyz/Article/details/gtdtvzmulu.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.havefunace.top/Article/details/gtunzrlxbv.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gogol.net.cn/Article/details/gtzhpgsgag.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.dashuyun.cn/Article/details/gtnnwqcuif.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yongpay.top/Article/details/gthxabcsnn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.nanxinkj.top/Article/details/gtwrziuzjm.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.chenzaomai.com/Article/details/gtombvevuu.html

[J05] 时间加减（加 7 天）
来源：http://dali.meibo888.top/Article/details/gtsukirbhe.html

Py:   now + timedelta(days=7)
来源：http://dali.gaohongyu789.top/Article/details/gtxailogla.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ydzc1.top/Article/details/gtvaffsjdl.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhengqikj.top/Article/details/gtjgudzicg.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yangfankeji.com/Article/details/gtsnsxjvbs.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqyzhbohu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.fzhhl.top/Article/details/gtanisooth.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yongpay.top/Article/details/gtuvwwqcvp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jyoumei.cn/Article/details/gtwpqfvhyh.html

[J06] 计算两时间之差
来源：http://dali.xylfe.cn/Article/details/gthsevxzgt.html

Py:   (end - start).total_seconds()
来源：http://dali.zycfv.cn/Article/details/gtoeaxtnpa.html

PHP:  $end->diff($start)->days;
来源：http://dali.ybcxt.top/Article/details/gtxlosdued.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xuetiantiany.cn/Article/details/gtqrrbatam.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhijiandao.cn/Article/details/gtdbpdzecm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.birdmap.top/Article/details/gtltwwugbu.html

Go:   end.Sub(start).Hours()
来源：http://dali.sweek.top/Article/details/gtfusjtspt.html

Ruby: end - start                 # 返回秒数
来源：http://dali.aizwys.cn/Article/details/gtngseuedw.html

C#:   (end - start).TotalSeconds
来源：http://dali.hnxiangtu.top/Article/details/gtquczbwqj.html

[J07] 比较两个日期
来源：http://dali.redwolf501.top/Article/details/gtqqbvhqdd.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.bjfxy.top/Article/details/gtsaxmhhdk.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtinnnrphe.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hnqzz.top/Article/details/gtuhpunrgb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jinghuilouyu.cn/Article/details/gtpksoovum.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.tian-w.cn/Article/details/gttlseatfk.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jianghu66.top/Article/details/gtmaaiupem.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gtzfwfkduk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gtrsjtahpa.html

[J08] 提取年月日与星期
来源：http://dali.jiagoushi.top/Article/details/gtjnuddick.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yueranfly.top/Article/details/gtezycaqos.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.havefunace.top/Article/details/gtoejiyigb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cheryme.top/Article/details/gteosesdpd.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gogol.net.cn/Article/details/gtwyiynkjm.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jiagoushi.top/Article/details/gtenyacqyx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jqgfzy.top/Article/details/gtrycgdtzy.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gzhubu.top/Article/details/gtlubvvfdf.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sweek.top/Article/details/gtchdorbns.html

[J09] 时区处理
来源：http://dali.aibaodan.cn/Article/details/gtibixopqj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.dianchejie.cn/Article/details/gtipibdcmq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.nwbrower.top/Article/details/gtycjkwkcf.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangshuangyany.cn/Article/details/gtnakhmphd.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dianchejie.cn/Article/details/gtsetqkdxu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yongpay.top/Article/details/gtkbxskolm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hammf.cn/Article/details/gtcalgtdxr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ivvv.top/Article/details/gtiqcupuao.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.vqdsnc.cn/Article/details/gttwxcwvwi.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinqigufen.top/Article/details/gtpvmmjkdo.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinqigfzy.top/Article/details/gtkwhrekvn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nwbrower.top/Article/details/gtkjduxzio.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.meibo888.top/Article/details/gtmtumbihe.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.redwolf501.top/Article/details/gtvzqqmnpw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.meibo888.top/Article/details/gtuenydphj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.316326.xyz/Article/details/gtknnbqawq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cucudq.cn/Article/details/gtqamwpxzp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yj202588.top/Article/details/gtrwvsbead.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtawivobvo.html

K. JSON 与序列化
来源：http://dali.gogol.net.cn/Article/details/gtbmjvmchr.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtwsopnsdb.html

[K01] 对象转 JSON 字符串
来源：http://dali.andypj.xyz/Article/details/gtypqkwdrs.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.quarkkingdee.top/Article/details/gtfdyfktfe.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.snrcjt.cn/Article/details/gtftffpxjd.html

JS:   JSON.stringify(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtyosnzpcl.html

TS:   JSON.stringify(obj)
来源：http://dali.yvedp.cn/Article/details/gtwsqhvrzr.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.tanke756.top/Article/details/gttwoyjsrk.html

Go:   json.Marshal(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtofjzawrg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.nwbrower.top/Article/details/gthgugrxnz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xinyue.icu/Article/details/gtfkvcutap.html

[K02] JSON 字符串转对象
来源：http://dali.yonumen.top/Article/details/gtcrmwubkc.html

Py:   json.loads(s)
来源：http://dali.daria6918.cn/Article/details/gtcipdunfy.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tian-w.cn/Article/details/gtbtpqyffd.html

JS:   JSON.parse(s)
来源：http://dali.yanxiufei.cn/Article/details/gtrfciiyju.html

TS:   JSON.parse(s)
来源：http://dali.bjfxy.top/Article/details/gtyawqsjag.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.redwolf501.top/Article/details/gtaqunpncr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jianghu66.top/Article/details/gtixvdwxli.html

Ruby: JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gtrjypazuy.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shzxlz.cn/Article/details/gtmsbbrymu.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yangfankeji.com/Article/details/gtlsonhgmv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cdnleiting.top/Article/details/gtknyvlitd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsdxiryup.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuxming.cn/Article/details/gtkaznhcqi.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgufenzy.top/Article/details/gtarcnlprf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xuanzx.com/Article/details/gtrmhvicdv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ppjwa.cn/Article/details/gtscpgfvpo.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.dashuyun.cn/Article/details/gtpwfcdthn.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tian-w.cn/Article/details/gtkgeboupb.html

[K04] 读取 JSON 文件
来源：http://dali.jinqigufen.top/Article/details/gtrisfroug.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcxmzggnb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.redwolf501.top/Article/details/gthbvvrhhb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tianlin.xyz/Article/details/gtvrwjudtn.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guannengcc.top/Article/details/gtuqckhakv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yueranfly.top/Article/details/gttkoaxhvs.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinqigufen.top/Article/details/gtzusfpxiw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yueranfly.top/Article/details/gtlwujebbj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hammf.cn/Article/details/gtkkxexreb.html

[K05] 深拷贝对象
来源：http://dali.ybcxt.top/Article/details/gtzszoqfkv.html

Py:   copy.deepcopy(obj)
来源：http://dali.andypj.xyz/Article/details/gtnsifcuuo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.wangdashe.top/Article/details/gtanwnodyo.html

JS:   structuredClone(obj)
来源：http://dali.yj202588.top/Article/details/gtwpbyydxd.html

TS:   structuredClone(obj)
来源：http://dali.yj202588.top/Article/details/gtmhrbysih.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xinyue.icu/Article/details/gtwermschx.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yongpay.top/Article/details/gtkwxcnwpc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yongpay.top/Article/details/gtldjpmnfu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.nanxinkj.top/Article/details/gtubopvdru.html

[K06] 解析 URL 查询串
来源：http://dali.yonumen.top/Article/details/gtbcwrkdzh.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shzxlz.cn/Article/details/gtjoyxgxra.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.sxryk.cn/Article/details/gtbpclklnf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shuidangran.top/Article/details/gtutrvqkdh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pycfn.com/Article/details/gtwxyqtnoh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hongshengwenyu.top/Article/details/gtwoenmjit.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gtthcffdrb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.tanke756.top/Article/details/gtdeflkjmy.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.vqdsnc.cn/Article/details/gtenzvmtlc.html

[K07] 进制转换
来源：http://dali.hnxiangtu.top/Article/details/gtpoyqntfg.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gtkjmiduxd.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cdnleiting.top/Article/details/gtjbtdeqfw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtprlnwnsx.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gtrjivzvgq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gtkspaouip.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gaohongyu789.top/Article/details/gtyfeqeprc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yonumen.top/Article/details/gtbneknvcs.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gteltvjmcb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ybcxt.top/Article/details/gtilixusji.html

Py:   pickle.dumps(obj)
来源：http://dali.hywenlv.cn/Article/details/gtfalaajmx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.guannengcc.top/Article/details/gtqwhzzeur.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ydzc1.top/Article/details/gtvdasuxnv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yongpay.top/Article/details/gtcasnijaf.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cheryme.top/Article/details/gtmfwzgrjp.html

Go:   encoding/gob
来源：http://dali.jinqigufen.top/Article/details/gtbecaekxf.html

Ruby: Marshal.dump(obj)
来源：http://dali.fzhhl.top/Article/details/gthhzvpqwe.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jinqigfzy.top/Article/details/gtrxtjhmds.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtphiufhhs.html

L. 网络请求
来源：http://dali.hfpthk.cn/Article/details/gtifulqjrj.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtrkzjolrn.html

[L01] 发送 GET 请求
来源：http://dali.yongpay.top/Article/details/gtpyshaasr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hammf.cn/Article/details/gtfxshwpbf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.bjfxy.top/Article/details/gtztgkwfuc.html

JS:   await fetch(url)
来源：http://dali.meibo888.top/Article/details/gtuslsnfnh.html

TS:   await fetch(url)
来源：http://dali.havefunace.top/Article/details/gtqmiehfwg.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.vqdsnc.cn/Article/details/gtapbwzivn.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gtidwxawad.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.fzhhl.top/Article/details/gtiztremai.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cashguo.top/Article/details/gtdfqfnodu.html

[L02] 发送 POST JSON
来源：http://dali.feifeiyinyue.top/Article/details/gtaplcgvxu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hywenlv.cn/Article/details/gtofrnptbm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.mhx1999.top/Article/details/gtjbhcaatk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yanxiufei.cn/Article/details/gttczdjlcq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.andypj.xyz/Article/details/gtmyjaeiqu.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhixingplan.top/Article/details/gtdbnqjtpu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ppjwa.cn/Article/details/gtzmalvvsh.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.chenjidiqi.icu/Article/details/gtgwtjskrj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yueranfly.top/Article/details/gthlntzlfc.html

[L03] 设置自定义请求头
来源：http://dali.aizwys.cn/Article/details/gtrxdfdbly.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.chenzaomai.com/Article/details/gtkjjyzmiq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.dianchejie.cn/Article/details/gtgawzefmx.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.bjfxy.top/Article/details/gtqxdusrxl.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuxming.cn/Article/details/gtjqirrpyi.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xylfe.cn/Article/details/gtzvilwnzd.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yuxming.cn/Article/details/gteqeftawc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shzxlz.cn/Article/details/gtkhksyztx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsjqkdqpo.html

[L04] 设置超时
来源：http://dali.meibo888.top/Article/details/gtdvutbbhs.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tian-w.cn/Article/details/gtvgnqyiio.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.0kj1m.cn/Article/details/gtpalvjtid.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yongpay.top/Article/details/gtqthrkelx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhongyouzk.top/Article/details/gtkkdjwbqt.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhiwuduotai.top/Article/details/gtddygveuz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.dashuyun.cn/Article/details/gtcgfaelan.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xuanzx.com/Article/details/gtxwredlxg.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cqqwz.cn/Article/details/gtbfrydsxx.html

[L05] 上传文件（multipart）
来源：http://dali.cqqwz.cn/Article/details/gtvabyfjug.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cucudq.cn/Article/details/gtrkkyhknx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sweek.top/Article/details/gtqdhnrfjn.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.pycfn.com/Article/details/gtcvsnwhlb.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgufenzy.top/Article/details/gttfiawpbr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ehwqpu.com/Article/details/gtwblaidpt.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.kuanghao11.cn/Article/details/gtsauoeosw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.smart0.xyz/Article/details/gtltxsydfr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hnqzz.top/Article/details/gtcyphaymj.html

[L06] 解析响应为 JSON
来源：http://dali.hongshengwenyu.top/Article/details/gtnbgdrngv.html

Py:   resp.json()
来源：http://dali.hfpthk.cn/Article/details/gtwwfbkxcz.html

PHP:  json_decode($body, true);
来源：http://dali.guowangkeji.top/Article/details/gtzrvobpcx.html

JS:   await resp.json()
来源：http://dali.ybcxt.top/Article/details/gtautonkry.html

TS:   await resp.json()
来源：http://dali.wangdashe.top/Article/details/gtugpppcde.html


<!-- 参考信息 -->