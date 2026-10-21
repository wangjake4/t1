代发 wailian999

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sysykeji.top/Article/details/gthpwqgaua.html

Go:   defer f.Close()
来源：http://dali.sufxvd.cn/Article/details/gtcywncecs.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfjzcsejy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.meibo888.top/Article/details/gtgvvcvacx.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtcnxgbqri.html

I. 正则表达式
来源：http://dali.wangshuangyany.cn/Article/details/gtcqfzwpkb.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gttmlqqofy.html

[I01] 判断是否匹配
来源：http://dali.c1oappe.top/Article/details/gtadscjgxr.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shuidangran.top/Article/details/gtayuyivhl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.nwbrower.top/Article/details/gtddjhvnmc.html

JS:   /\d+/.test(s)
来源：http://dali.tian-w.cn/Article/details/gtneqxwhbh.html

TS:   /\d+/.test(s)
来源：http://dali.jianghu66.top/Article/details/gtqpmtzcxk.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuvsdnjtw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.tanke756.top/Article/details/gtxdfpyooc.html

Ruby: s.match?(/\d+/)
来源：http://dali.smart0.xyz/Article/details/gtheljkhsv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jiagoushi.top/Article/details/gtngplgikn.html

[I02] 提取所有匹配
来源：http://dali.chenjidiqi.icu/Article/details/gtvtmrsurw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shangyingyoupin.top/Article/details/gtmaqebaxa.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.chenlongwang.top/Article/details/gtjglccbus.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.svipenyu.cn/Article/details/gtjfuopeju.html

TS:   s.match(/\d+/g)
来源：http://dali.zycfv.cn/Article/details/gtwfxaaxkj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jqgufenzy.top/Article/details/gtolmhywux.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gotoacloud.top/Article/details/gttisroera.html

Ruby: s.scan(/\d+/)
来源：http://dali.nanxinkj.top/Article/details/gtylpiincw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbkcjmjrt.html

[I03] 提取捕获分组
来源：http://dali.pengpengdd.cyou/Article/details/gtzczuexjr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.tanke756.top/Article/details/gtzosydigx.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.tian-w.cn/Article/details/gtljwxzbuj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.chenzaomai.com/Article/details/gtfaidyslo.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhiwuduotai.top/Article/details/gtvfyuwmes.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.guannengcc.top/Article/details/gtvlbckfic.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cashguo.top/Article/details/gtjbcpvflr.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.snrcjt.cn/Article/details/gtobymqxrc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yj20258888.top/Article/details/gtnmpqoowe.html

[I04] 正则替换
来源：http://dali.9152youxi.cn/Article/details/gtmqfclcak.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jiagoushi.top/Article/details/gtsiwdwivo.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.haohaochexian.top/Article/details/gtganotzyk.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zycfv.cn/Article/details/gtrrgfpcbe.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xuanzx.com/Article/details/gtqfbekymv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.smart0.xyz/Article/details/gtncftnwel.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sweek.top/Article/details/gtdopzxqkn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sysykeji.top/Article/details/gtkdevlobe.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.birdmap.top/Article/details/gtybinsida.html

[I05] 按正则拆分
来源：http://dali.hfpthk.cn/Article/details/gtklolrwuw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhongyouzk.top/Article/details/gtypcuqlbc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.fengsongda.top/Article/details/gtrplfdkyh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hammf.cn/Article/details/gtdnncbewq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hnqzz.top/Article/details/gtclpnzoxk.html

Java: s.split("\\s*,\\s*")
来源：http://dali.redwolf501.top/Article/details/gtwldkblnl.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jianghu66.top/Article/details/gtkklerypw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cheryme.top/Article/details/gtllqbmgix.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yuanzhike.top/Article/details/gtmeywvkam.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.wangshuangyany.cn/Article/details/gtuxgaetqw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.svipenyu.cn/Article/details/gtaokhexfz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.guowangkeji.top/Article/details/gtjtosibdz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shzxlz.cn/Article/details/gtiesmqumw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.smart0.xyz/Article/details/gtagahtyck.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xuetiantiany.cn/Article/details/gteotebjcf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gtzwxtxrky.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvwpiddhc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.vqdsnc.cn/Article/details/gtdtptvtqe.html

[I07] 忽略大小写与多行模式
来源：http://dali.yonumen.top/Article/details/gtfwsbptxz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hongshengwenyu.top/Article/details/gtevaqteiv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yuxming.cn/Article/details/gtclzyuxsz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xuetiantiany.cn/Article/details/gtafbkwbca.html

TS:   /error/gim
来源：http://dali.gzhubu.top/Article/details/gtslibnbgy.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yuxming.cn/Article/details/gtxcleviex.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ehwqpu.com/Article/details/gtglpzdwsg.html

Ruby: s.scan(/error/i)
来源：http://dali.nanxinkj.top/Article/details/gtfsjzqwda.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.aizwys.cn/Article/details/gtavgzsxsm.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yongpay.top/Article/details/gtrgoqrerw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sxryk.cn/Article/details/gttaqxixfa.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.aibaodan.cn/Article/details/gtjuflrmuo.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xinyue.icu/Article/details/gtmlasuwjb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daxiang520.top/Article/details/gtfwklxeuq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gtuzqvjnhv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.dashuyun.cn/Article/details/gtqmxymsao.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hywenlv.cn/Article/details/gtwiojqfhs.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaikvepys.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtliomsvsn.html

J. 日期与时间
来源：http://dali.c1oappe.top/Article/details/gtbamntcgu.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtckuyarbt.html

[J01] 获取当前时间
来源：http://dali.xuetiantiany.cn/Article/details/gtwykjsbjy.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj202588.top/Article/details/gtqbspiplc.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yonumen.top/Article/details/gtatbmnnbc.html

JS:   new Date();  Date.now()
来源：http://dali.nanxuanxn.top/Article/details/gtfeaqelvl.html

TS:   new Date();  Date.now()
来源：http://dali.yanxiufei.cn/Article/details/gtnfwbwodh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hnxiangtu.top/Article/details/gtszgvumrz.html

Go:   time.Now()
来源：http://dali.yuxming.cn/Article/details/gtpmxmygjk.html

Ruby: Time.now
来源：http://dali.gogol.net.cn/Article/details/gtjkvpfpbv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenjidiqi.icu/Article/details/gtctnezcrp.html

[J02] 格式化输出
来源：http://dali.jqgfzy.top/Article/details/gtlgjzdixl.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhoulong.xyz/Article/details/gtfktxflma.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.pycfn.com/Article/details/gtjrvyqxmo.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.bjfxy.top/Article/details/gtfziyedew.html

TS:   d.toISOString()
来源：http://dali.gzhubu.top/Article/details/gtpcylhaon.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.316326.xyz/Article/details/gtymzbbfiy.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hnxiangtu.top/Article/details/gtpwdswxdu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jlsjyb.cn/Article/details/gtkbmhewat.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.havefunace.top/Article/details/gtzahkcoho.html

[J03] 字符串解析为日期
来源：http://dali.316326.xyz/Article/details/gtdtknozle.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xuanzx.com/Article/details/gtvfsydkua.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.guowangkeji.top/Article/details/gtywiqjmaf.html

JS:   new Date("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gtkbsqgulq.html

TS:   new Date("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gtxzyssznz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjibtsifj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gtaveolzlj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gtqtjttrbe.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.feifeiyinyue.top/Article/details/gtkdakcjih.html

[J04] 时间戳与日期互转
来源：http://dali.hnqzz.top/Article/details/gtdczadhgn.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.chenzaomai.com/Article/details/gtkukdkaea.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.tian-w.cn/Article/details/gtnijwwybl.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.svipenyu.cn/Article/details/gttezlgmgu.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.nwbrower.top/Article/details/gtnamlrbgx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yuanzhike.top/Article/details/gtxgdwueki.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cucudq.cn/Article/details/gtbbaggick.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xziqi.cn/Article/details/gtekhkwxaw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yuanzhike.top/Article/details/gtxcuqchue.html

[J05] 时间加减（加 7 天）
来源：http://dali.cheryme.top/Article/details/gtivyctafc.html

Py:   now + timedelta(days=7)
来源：http://dali.yonumen.top/Article/details/gtnovqxdsd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hywenlv.cn/Article/details/gtcyjahyls.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hywenlv.cn/Article/details/gtatoinxyu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangdashe.top/Article/details/gthebutzvd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.0kj1m.cn/Article/details/gtvfpxiyaf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwxtkqlbs.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtffsnernq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinghuilouyu.cn/Article/details/gttyzhfzem.html

[J06] 计算两时间之差
来源：http://dali.tanke756.top/Article/details/gtrfeiubtq.html

Py:   (end - start).total_seconds()
来源：http://dali.nwbrower.top/Article/details/gtihbykjak.html

PHP:  $end->diff($start)->days;
来源：http://dali.nwbrower.top/Article/details/gtsolobcuk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shzxlz.cn/Article/details/gtuwcjkkmk.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.fengsongda.top/Article/details/gtaeyjnlkp.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.havefunace.top/Article/details/gtxsmcpnvz.html

Go:   end.Sub(start).Hours()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrkeuvgan.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwlhgfxil.html

C#:   (end - start).TotalSeconds
来源：http://dali.snrcjt.cn/Article/details/gtcakehkfc.html

[J07] 比较两个日期
来源：http://dali.hysaishi.cn/Article/details/gtknlhttjx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yanxiufei.cn/Article/details/gtqyknpzch.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shanyushiyangtech.top/Article/details/gthjqpbqqx.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.fzhhl.top/Article/details/gtoflmsthz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.tian-w.cn/Article/details/gtwsfukzch.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.kuanghao11.cn/Article/details/gtgqghcioe.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.guannengcc.top/Article/details/gtcqhearkf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdsqubqhi.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaaazftwu.html

[J08] 提取年月日与星期
来源：http://dali.yvedp.cn/Article/details/gthlgpjwni.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hnxiangtu.top/Article/details/gtxdgasshh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shuidangran.top/Article/details/gtidjyfzrz.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.fzhhl.top/Article/details/gtylsaqwbi.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.chenjidiqi.icu/Article/details/gthrskofig.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.pycfn.com/Article/details/gtcdvitzmk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhengqikj.top/Article/details/gttdipvvuu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinqigufen.top/Article/details/gtzlcdivqh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.fengsongda.top/Article/details/gtxagkmnet.html

[J09] 时区处理
来源：http://dali.yueranfly.top/Article/details/gtwhzlrjxo.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yvedp.cn/Article/details/gtgbjaqtob.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ybcxt.top/Article/details/gtmluonxop.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shangyingyoupin.top/Article/details/gtcfcrwsgx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yueranfly.top/Article/details/gtumklkmnk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.9152youxi.cn/Article/details/gtddpklpxp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.0kj1m.cn/Article/details/gtsgafqkqi.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shuidangran.top/Article/details/gtjnnnqqnx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.tianlin.xyz/Article/details/gtvsqxqnkg.html

[J10] 取今天 / 本月第一天
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyjtkqfnc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.aibaodan.cn/Article/details/gtonredfnu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jyoumei.cn/Article/details/gtdzxiluux.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xylfe.cn/Article/details/gtzdhnvhen.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbhogtrwv.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yanxiufei.cn/Article/details/gtvesaqjpf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.pengpengdd.cyou/Article/details/gtqxiohdzv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xziqi.cn/Article/details/gtglvixlri.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jiagoushi.top/Article/details/gtziikecby.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtfmrpzxql.html

K. JSON 与序列化
来源：http://dali.hnqzz.top/Article/details/gtlxggnaab.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtpvueufvw.html

[K01] 对象转 JSON 字符串
来源：http://dali.xuanzx.com/Article/details/gtpxpkrqzl.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ybcxt.top/Article/details/gtewmvvnxs.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xuanzx.com/Article/details/gtppayaxvr.html

JS:   JSON.stringify(obj)
来源：http://dali.dianchejie.cn/Article/details/gtlectyife.html

TS:   JSON.stringify(obj)
来源：http://dali.hysaishi.cn/Article/details/gtqwsnsxdh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sysykeji.top/Article/details/gtvpniflmh.html

Go:   json.Marshal(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gthdkotehd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sufxvd.cn/Article/details/gtzyvajsaw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaugcbnvi.html

[K02] JSON 字符串转对象
来源：http://dali.snrcjt.cn/Article/details/gtbquctepn.html

Py:   json.loads(s)
来源：http://dali.wangdashe.top/Article/details/gttseqyoxy.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.aizwys.cn/Article/details/gtocbioacz.html

JS:   JSON.parse(s)
来源：http://dali.shuidangran.top/Article/details/gthqfgmccg.html

TS:   JSON.parse(s)
来源：http://dali.ehwqpu.com/Article/details/gtizlqnhvj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yangfankeji.com/Article/details/gtuwafsxir.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sufxvd.cn/Article/details/gtvcypzgrf.html

Ruby: JSON.parse(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtkizkhkhd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xziqi.cn/Article/details/gtzpirjtcf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hammf.cn/Article/details/gtpzqrgqpb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yonumen.top/Article/details/gttpjivrkk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxuanxn.top/Article/details/gtjzjofknt.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tian-w.cn/Article/details/gtcbaknnoc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.mhx1999.top/Article/details/gtdikbbaew.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.snrcjt.cn/Article/details/gtnccuoghv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jlsjyb.cn/Article/details/gtxcwdmggp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xziqi.cn/Article/details/gtumdpfaso.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.svipenyu.cn/Article/details/gtsgukdpqo.html

[K04] 读取 JSON 文件
来源：http://dali.yj20258888.top/Article/details/gtzrppgzln.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.mhx1999.top/Article/details/gtnqhisxnj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hywenlv.cn/Article/details/gtqtfivbrg.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhongyouzk.top/Article/details/gtstfvcowt.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbomkqndn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.daxiang520.top/Article/details/gttnhneqza.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.mhx1999.top/Article/details/gtnycithba.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.316326.xyz/Article/details/gtlotmllco.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shangyingyoupin.top/Article/details/gtagcgxsks.html

[K05] 深拷贝对象
来源：http://dali.pycfn.com/Article/details/gtalftthcc.html

Py:   copy.deepcopy(obj)
来源：http://dali.mhx1999.top/Article/details/gthodmtrav.html

PHP:  unserialize(serialize($obj));
来源：http://dali.pengpengdd.cyou/Article/details/gtwuwopzfb.html

JS:   structuredClone(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzromwnwg.html

TS:   structuredClone(obj)
来源：http://dali.xziqi.cn/Article/details/gtrrudtage.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.fzhhl.top/Article/details/gtkqyerjft.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.daria6918.cn/Article/details/gtisqtfldm.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.haohaochexian.top/Article/details/gtfrllbfas.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfwgeyobg.html

[K06] 解析 URL 查询串
来源：http://dali.jiagoushi.top/Article/details/gtvtkaqarp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cucudq.cn/Article/details/gtlreblejp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.fzhhl.top/Article/details/gtcnftuaxf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ppjwa.cn/Article/details/gtcpfiyemi.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxuanxn.top/Article/details/gtqvitgukh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cdnleiting.top/Article/details/gtyvbhaasn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinqigufen.top/Article/details/gtbphdpdym.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hywenlv.cn/Article/details/gtyxbqvtpj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinghuilouyu.cn/Article/details/gtyzokqxqk.html

[K07] 进制转换
来源：http://dali.xuanzx.com/Article/details/gtmzegtvpz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gtrvgqkbdl.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hnxiangtu.top/Article/details/gtytahdgfb.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmjradqqt.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtsvzdcaar.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gtpainofsd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.haohaochexian.top/Article/details/gtqefrsete.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gtyjswpeho.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gtjenhmlwz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.pycfn.com/Article/details/gtjukidbwr.html

Py:   pickle.dumps(obj)
来源：http://dali.zdqjudy.top/Article/details/gtcnckrlbw.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xinyue.icu/Article/details/gtxmygqsph.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.daria6918.cn/Article/details/gtpsxgamnn.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.quarkkingdee.top/Article/details/gtfubhpjst.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xinyue.icu/Article/details/gttoryktch.html

Go:   encoding/gob
来源：http://dali.kuanghao11.cn/Article/details/gttxvtucot.html

Ruby: Marshal.dump(obj)
来源：http://dali.tanke756.top/Article/details/gtmjqqquiz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.fzhhl.top/Article/details/gtywyywskm.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtjyuywrvs.html

L. 网络请求
来源：http://dali.xziqi.cn/Article/details/gtacxbdkim.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtlkbdvhns.html

[L01] 发送 GET 请求
来源：http://dali.316326.xyz/Article/details/gtwaepleqr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.aibaodan.cn/Article/details/gtwuwvgbzt.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hnxiangtu.top/Article/details/gtudobktis.html

JS:   await fetch(url)
来源：http://dali.sysykeji.top/Article/details/gtqsrvqvhl.html

TS:   await fetch(url)
来源：http://dali.svipenyu.cn/Article/details/gtucjgpuyp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sweek.top/Article/details/gtzbqzlmnm.html

Go:   resp, err := http.Get(url)
来源：http://dali.cashguo.top/Article/details/gtxrmnixpv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.guannengcc.top/Article/details/gtvngnsreh.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.dianchejie.cn/Article/details/gtfaxwlfsx.html

[L02] 发送 POST JSON
来源：http://dali.tian-w.cn/Article/details/gttpwactnc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.fzhhl.top/Article/details/gtgqvmxekc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.pycfn.com/Article/details/gtmspzbmvo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhongyouzk.top/Article/details/gtnkebvooz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sysykeji.top/Article/details/gtfgdvzvsr.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zycfv.cn/Article/details/gtvmctbjkw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.tanke756.top/Article/details/gtrnzbmpup.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.chenzaomai.com/Article/details/gthesmwhei.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hnqzz.top/Article/details/gthxpmlgno.html

[L03] 设置自定义请求头
来源：http://dali.yonumen.top/Article/details/gtlxefukhe.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hnqzz.top/Article/details/gtcxvdrtow.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yvedp.cn/Article/details/gtnklxsifm.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.andypj.xyz/Article/details/gtumxofxda.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fzhhl.top/Article/details/gttcxrtnig.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhengqikj.top/Article/details/gtiwxsckbn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.tianlin.xyz/Article/details/gtalxwygxz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cqqwz.cn/Article/details/gtdirtnunw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.nanxuanxn.top/Article/details/gtlblnxpov.html

[L04] 设置超时
来源：http://dali.zhongyouzk.top/Article/details/gtaiihvyyi.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jyoumei.cn/Article/details/gtlslxahpg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.meibo888.top/Article/details/gtuikdcqdp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jiagoushi.top/Article/details/gtmmvqwlfy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.smart0.xyz/Article/details/gtsvrpronk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hfpthk.cn/Article/details/gtfhnbnewl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zycfv.cn/Article/details/gtyvzjxefr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gttjaqpyoc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.svipenyu.cn/Article/details/gtezvwgjnj.html

[L05] 上传文件（multipart）
来源：http://dali.sufxvd.cn/Article/details/gtosbikahu.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.aizwys.cn/Article/details/gtiyqrjbnv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xylfe.cn/Article/details/gtvanmtsph.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.9152youxi.cn/Article/details/gtzqxtbpav.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ehwqpu.com/Article/details/gtzgpqsins.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.andypj.xyz/Article/details/gtssndmjol.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zycfv.cn/Article/details/gtletpdqni.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jianghu66.top/Article/details/gthinsoglo.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.pycfn.com/Article/details/gtlbxotqfd.html

[L06] 解析响应为 JSON
来源：http://dali.svipenyu.cn/Article/details/gtqnvwlsft.html

Py:   resp.json()
来源：http://dali.feifeiyinyue.top/Article/details/gtacbsfcea.html

PHP:  json_decode($body, true);
来源：http://dali.wangdashe.top/Article/details/gtggwuocjs.html

JS:   await resp.json()
来源：http://dali.nanxuanxn.top/Article/details/gtfydqnaov.html

TS:   await resp.json()
来源：http://dali.gotoacloud.top/Article/details/gtpdqravyk.html


<!-- 参考信息 -->