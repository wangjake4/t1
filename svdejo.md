代发 wailian999

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.316326.xyz/Article/details/gtdfnptuux.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.nanxinkj.top/Article/details/gtenktivtc.html

Ruby: s.match?(/\d+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjckqhjhu.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.0kj1m.cn/Article/details/gtrglwypuv.html

[I02] 提取所有匹配
来源：http://dali.9152youxi.cn/Article/details/gtokubauwq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.smart0.xyz/Article/details/gtsecjzyjx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.guannengcc.top/Article/details/gttvesplqo.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jqgfzy.top/Article/details/gtdygebfpp.html

TS:   s.match(/\d+/g)
来源：http://dali.dianchejie.cn/Article/details/gtyecgozyl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hnxiangtu.top/Article/details/gtojkbkule.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthgrjeljg.html

Ruby: s.scan(/\d+/)
来源：http://dali.nanxuanxn.top/Article/details/gthllryfoc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ppjwa.cn/Article/details/gtvotocmsn.html

[I03] 提取捕获分组
来源：http://dali.gaohongyu789.top/Article/details/gtpytssoza.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sysykeji.top/Article/details/gtcmlgxnix.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yanxiufei.cn/Article/details/gtubvbnany.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfwcgvfmh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgqllhngp.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.bjfxy.top/Article/details/gtszjdvwau.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.haohaochexian.top/Article/details/gtviiqfmcg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cucudq.cn/Article/details/gtmnpeaqxk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinghuilouyu.cn/Article/details/gtizayeeoa.html

[I04] 正则替换
来源：http://dali.tianlin.xyz/Article/details/gtcjzgmlox.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.wangdashe.top/Article/details/gttllmpbdp.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zdqjudy.top/Article/details/gtueacrdpl.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.daxiang520.top/Article/details/gtcqalndll.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhoulong.xyz/Article/details/gtryjrvvou.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jqgufenzy.top/Article/details/gtczlcjlpp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xylfe.cn/Article/details/gtsbvtxwuj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.mhx1999.top/Article/details/gtdcigegax.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cucudq.cn/Article/details/gtjtbydbgv.html

[I05] 按正则拆分
来源：http://dali.ivvv.top/Article/details/gtaqcfjbcu.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cqqwz.cn/Article/details/gtivksxdvu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gthjjzgfmd.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shangyingyoupin.top/Article/details/gtrsyvkozf.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttimxznkh.html

Java: s.split("\\s*,\\s*")
来源：http://dali.daxiang520.top/Article/details/gtvjjvagbr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yongpay.top/Article/details/gtybncudhs.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.quarkkingdee.top/Article/details/gtifhtypjw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yanxiufei.cn/Article/details/gtufviflwj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ydzc1.top/Article/details/gtoeqcbcbe.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.iojbl.cn/Article/details/gtwtxcvqqo.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cdnleiting.top/Article/details/gtmyxkytiy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shuidangran.top/Article/details/gtovampror.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ybcxt.top/Article/details/gtnwqsqffx.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinghuilouyu.cn/Article/details/gtvzgsetld.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.fengsongda.top/Article/details/gtoptshanz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.tanke756.top/Article/details/gtnjziqfts.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.c1oappe.top/Article/details/gtafpqwgsx.html

[I07] 忽略大小写与多行模式
来源：http://dali.nanxinkj.top/Article/details/gtcymgznpo.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hongshengwenyu.top/Article/details/gtvchjsdlk.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.dashuyun.cn/Article/details/gtsfdxythl.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xylfe.cn/Article/details/gtmzyykxwc.html

TS:   /error/gim
来源：http://dali.zhixingplan.top/Article/details/gtdrhzbqsd.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.quarkkingdee.top/Article/details/gtlobxxmvt.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ybcxt.top/Article/details/gtyxesvxfm.html

Ruby: s.scan(/error/i)
来源：http://dali.hnqzz.top/Article/details/gthewlzghm.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.snrcjt.cn/Article/details/gtlzodgxdo.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.aibaodan.cn/Article/details/gtelszommr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.wangshuangyany.cn/Article/details/gtgqqmytyk.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yanxiufei.cn/Article/details/gtmpgnjuud.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.316326.xyz/Article/details/gtraddcovk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258.top/Article/details/gtcgcdklus.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yonumen.top/Article/details/gtqynyshkj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zdqjudy.top/Article/details/gtakqvhgfz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.bjfxy.top/Article/details/gtyxvpumbx.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hnqzz.top/Article/details/gtujqvaptk.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtoowsrlxr.html

J. 日期与时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyqlcvwza.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtzwthwgzr.html

[J01] 获取当前时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdfbsokk.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.dianchejie.cn/Article/details/gtsorlpzok.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.iojbl.cn/Article/details/gtzyggqofl.html

JS:   new Date();  Date.now()
来源：http://dali.gogol.net.cn/Article/details/gtshrioujk.html

TS:   new Date();  Date.now()
来源：http://dali.316326.xyz/Article/details/gtdeibiduj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sxryk.cn/Article/details/gtftusatvo.html

Go:   time.Now()
来源：http://dali.iojbl.cn/Article/details/gtasyhffti.html

Ruby: Time.now
来源：http://dali.birdmap.top/Article/details/gtzbznpitd.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hnxiangtu.top/Article/details/gtdrufiwle.html

[J02] 格式化输出
来源：http://dali.birdmap.top/Article/details/gtaeenrrca.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hammf.cn/Article/details/gtncrbzjot.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xuanzx.com/Article/details/gtrjunypki.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.0kj1m.cn/Article/details/gtprjplytv.html

TS:   d.toISOString()
来源：http://dali.kuanghao11.cn/Article/details/gttopwnxws.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jlsjyb.cn/Article/details/gtoqouzxzy.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.pengpengdd.cyou/Article/details/gtchhvzcpa.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cqqwz.cn/Article/details/gtfmlccfxa.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.chenjidiqi.icu/Article/details/gtbithcppo.html

[J03] 字符串解析为日期
来源：http://dali.mhx1999.top/Article/details/gtcuuewlhh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shuidangran.top/Article/details/gtzexnpxsr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ydzc1.top/Article/details/gttezkdpbh.html

JS:   new Date("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gtawubbtzh.html

TS:   new Date("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gtwskhypiw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gthdclcytw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gtjikdowpr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gtkjjcbkls.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gaohongyu789.top/Article/details/gtmpqavoja.html

[J04] 时间戳与日期互转
来源：http://dali.dianchejie.cn/Article/details/gtsypdtpaf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sufxvd.cn/Article/details/gtbfgwajxi.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shzxlz.cn/Article/details/gtqjoigtky.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ehwqpu.com/Article/details/gtdhcmyupk.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xylfe.cn/Article/details/gtgpndikdx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zycfv.cn/Article/details/gtrasekbhv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yangfankeji.com/Article/details/gtwluzlsei.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gtoxjyuczv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hfpthk.cn/Article/details/gtiyykenie.html

[J05] 时间加减（加 7 天）
来源：http://dali.sxryk.cn/Article/details/gtvjzipubw.html

Py:   now + timedelta(days=7)
来源：http://dali.nanxinkj.top/Article/details/gtmnvqtvsk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cdnleiting.top/Article/details/gtyifiapnl.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhengqikj.top/Article/details/gtjqyxhawk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangdashe.top/Article/details/gtlhviadzs.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cashguo.top/Article/details/gtpqeqdcog.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xinyue.icu/Article/details/gtjmzbispi.html

Ruby: Time.now + 7 * 86400
来源：http://dali.birdmap.top/Article/details/gtnanbigvz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shuidangran.top/Article/details/gtyfldgssa.html

[J06] 计算两时间之差
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjmgfqvec.html

Py:   (end - start).total_seconds()
来源：http://dali.hongshengwenyu.top/Article/details/gtmrsptbld.html

PHP:  $end->diff($start)->days;
来源：http://dali.gogol.net.cn/Article/details/gtzfdfnyfx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gzhubu.top/Article/details/gtzmlbvzeq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jlsjyb.cn/Article/details/gtmmfsxvhz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.guowangkeji.top/Article/details/gtgopezeve.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinqigfzy.top/Article/details/gtulwpfbih.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnwhiymes.html

C#:   (end - start).TotalSeconds
来源：http://dali.hfpthk.cn/Article/details/gtgiwvkhmr.html

[J07] 比较两个日期
来源：http://dali.haohaochexian.top/Article/details/gtriqhonnf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gtoctbzzlm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.c1oappe.top/Article/details/gtezuntzhj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hfpthk.cn/Article/details/gtqbbbbvlk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.9152youxi.cn/Article/details/gthipgaduw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.pycfn.com/Article/details/gtcfmijrne.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jqgfzy.top/Article/details/gtwhryshnf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ehwqpu.com/Article/details/gtigxnownr.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gtruxzxjzd.html

[J08] 提取年月日与星期
来源：http://dali.mhx1999.top/Article/details/gtobbmbmgp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.wangdashe.top/Article/details/gtbfopofrn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jqgufenzy.top/Article/details/gtipgkbvee.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.iojbl.cn/Article/details/gtiigtifyj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhixingplan.top/Article/details/gtrvbxjkpg.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhongyouzk.top/Article/details/gtlwsocmcn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jyoumei.cn/Article/details/gthskoammg.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinqigfzy.top/Article/details/gtdiydrtfc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yueranfly.top/Article/details/gtzixabhky.html

[J09] 时区处理
来源：http://dali.guannengcc.top/Article/details/gtqadmbuyh.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.316326.xyz/Article/details/gtpymtkhva.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.nanxinkj.top/Article/details/gttuzhlnkf.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jianghu66.top/Article/details/gtdarrtpix.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sweek.top/Article/details/gthfiguxgh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cqqwz.cn/Article/details/gtdnrbdcrb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gzhubu.top/Article/details/gtjmgheppw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.aibaodan.cn/Article/details/gtaljneqqf.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.tian-w.cn/Article/details/gtdvaubrhh.html

[J10] 取今天 / 本月第一天
来源：http://dali.ivvv.top/Article/details/gtfubrmtrw.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.guannengcc.top/Article/details/gtamvrefxx.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yuanzhike.top/Article/details/gtjeizszxk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.bjfxy.top/Article/details/gtglmcenpg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sysykeji.top/Article/details/gtcaxyqxsq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yvedp.cn/Article/details/gtrvtbmvux.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.haohaochexian.top/Article/details/gtpffudeap.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tianlin.xyz/Article/details/gtmkmodnsx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hnqzz.top/Article/details/gtkqofabsj.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtuyabveya.html

K. JSON 与序列化
来源：http://dali.yonumen.top/Article/details/gtzfuwpjjl.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtxxirpezd.html

[K01] 对象转 JSON 字符串
来源：http://dali.nanxinkj.top/Article/details/gtvecsdtsl.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xuetiantiany.cn/Article/details/gtdwezqoaz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxuanxn.top/Article/details/gtfyfuegdf.html

JS:   JSON.stringify(obj)
来源：http://dali.gzhubu.top/Article/details/gtblguqqvw.html

TS:   JSON.stringify(obj)
来源：http://dali.iojbl.cn/Article/details/gtvwaowioh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinqigfzy.top/Article/details/gtksptwrex.html

Go:   json.Marshal(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkevmrgar.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jianghu66.top/Article/details/gtmbthwjzq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yongpay.top/Article/details/gtktyvsirj.html

[K02] JSON 字符串转对象
来源：http://dali.yueranfly.top/Article/details/gtrowgkpgm.html

Py:   json.loads(s)
来源：http://dali.tianlin.xyz/Article/details/gtvruwyiyr.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yj20258.top/Article/details/gtfozultsm.html

JS:   JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gthldodwjn.html

TS:   JSON.parse(s)
来源：http://dali.snrcjt.cn/Article/details/gtbjwkrirg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gotoacloud.top/Article/details/gtacvfrgjq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.redwolf501.top/Article/details/gtujzabgcf.html

Ruby: JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gtgqovafdk.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.chenzaomai.com/Article/details/gtrupgxkhp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hysaishi.cn/Article/details/gteigodmdw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.feifeiyinyue.top/Article/details/gtfydpsidy.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsovpfspp.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ehwqpu.com/Article/details/gtvpkjqqqd.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shzxlz.cn/Article/details/gtbybesxcy.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtmwzvmhfe.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.pycfn.com/Article/details/gtvehhgpcb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xylfe.cn/Article/details/gteujuceqb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ppjwa.cn/Article/details/gtnblfflev.html

[K04] 读取 JSON 文件
来源：http://dali.9152youxi.cn/Article/details/gtchqvqkwl.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.quarkkingdee.top/Article/details/gttegnwcpb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cheryme.top/Article/details/gtqophdekh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ivvv.top/Article/details/gtgicwzikr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guannengcc.top/Article/details/gtpdrlvnzt.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shangyingyoupin.top/Article/details/gtordruhrp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hammf.cn/Article/details/gteicmgduh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.pycfn.com/Article/details/gtrfmsxery.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sysykeji.top/Article/details/gtoizmwrme.html

[K05] 深拷贝对象
来源：http://dali.zhiwuduotai.top/Article/details/gtqlvujbpd.html

Py:   copy.deepcopy(obj)
来源：http://dali.tian-w.cn/Article/details/gtlticpgof.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shzxlz.cn/Article/details/gtnzgvgexx.html

JS:   structuredClone(obj)
来源：http://dali.cucudq.cn/Article/details/gtdetrvfpi.html

TS:   structuredClone(obj)
来源：http://dali.zdqjudy.top/Article/details/gtgpnbphxy.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.andypj.xyz/Article/details/gtvlzivpmy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yj20258888.top/Article/details/gtnfoxkstq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xuetiantiany.cn/Article/details/gtnqijuzdr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yj20258888.top/Article/details/gtwdqnqjgi.html

[K06] 解析 URL 查询串
来源：http://dali.pycfn.com/Article/details/gtysojyyff.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.bjfxy.top/Article/details/gthtoljlhq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.sxryk.cn/Article/details/gtyhdkfapd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.snrcjt.cn/Article/details/gtsnsqvlqd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.vqdsnc.cn/Article/details/gtxxyueiri.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xylfe.cn/Article/details/gtjqtlelwo.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gtfzefhyah.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.nwbrower.top/Article/details/gtnwautxnt.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.wangdashe.top/Article/details/gtstzuvmsh.html

[K07] 进制转换
来源：http://dali.tanke756.top/Article/details/gtxalamcuh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtpsjykkmx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.snrcjt.cn/Article/details/gtrkdmgeuc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gteyvradyw.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gtaierqnut.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gtdvreqtzp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gogol.net.cn/Article/details/gtqbcjxaqd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jiagoushi.top/Article/details/gtsxdkpwsu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ivvv.top/Article/details/gtyzbtbjyv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.pengpengdd.cyou/Article/details/gtbyefkzwg.html

Py:   pickle.dumps(obj)
来源：http://dali.pycfn.com/Article/details/gtiabupzii.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zdqjudy.top/Article/details/gtiswzoqhn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdrivsrtx.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.guowangkeji.top/Article/details/gtmayuqtwa.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.daxiang520.top/Article/details/gtuvjkpphb.html

Go:   encoding/gob
来源：http://dali.hywenlv.cn/Article/details/gtcoqezvcu.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtbvoeldbw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shanyushiyangtech.top/Article/details/gtgsasiidy.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtxyxfzxgi.html

L. 网络请求
来源：http://dali.dashuyun.cn/Article/details/gtsycjivdh.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtotujwnim.html

[L01] 发送 GET 请求
来源：http://dali.birdmap.top/Article/details/gtasaqymhn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xylfe.cn/Article/details/gtxcekturp.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.c1oappe.top/Article/details/gtxeeksilx.html

JS:   await fetch(url)
来源：http://dali.ivvv.top/Article/details/gtghrcjyiu.html

TS:   await fetch(url)
来源：http://dali.hywenlv.cn/Article/details/gtttqnrcnv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.dashuyun.cn/Article/details/gtulqrehea.html

Go:   resp, err := http.Get(url)
来源：http://dali.cheryme.top/Article/details/gtpovatlgj.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yongpay.top/Article/details/gtbvesxtpq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhixingplan.top/Article/details/gtdslmkqcd.html

[L02] 发送 POST JSON
来源：http://dali.zhiwuduotai.top/Article/details/gtzdwvnwye.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhiwuduotai.top/Article/details/gtuxowiimb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shzxlz.cn/Article/details/gtauxqdhul.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigfzy.top/Article/details/gtlhivjogs.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sweek.top/Article/details/gtqatmfmrh.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zdqjudy.top/Article/details/gtlaaeplrg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xuanzx.com/Article/details/gtoncnuwex.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hysaishi.cn/Article/details/gtrnnribwh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.meibo888.top/Article/details/gteyjsknky.html

[L03] 设置自定义请求头
来源：http://dali.xylfe.cn/Article/details/gtsxtxczlx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.andypj.xyz/Article/details/gtzhcogeyu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yangfankeji.com/Article/details/gtcfzawyee.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cashguo.top/Article/details/gtdhdeyxca.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aibaodan.cn/Article/details/gtqwaahuet.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sysykeji.top/Article/details/gtbuuorpcw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.daria6918.cn/Article/details/gtdpbxcvcg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yj20258.top/Article/details/gtbqwsjqef.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.aibaodan.cn/Article/details/gtvfklinfp.html

[L04] 设置超时
来源：http://dali.mhx1999.top/Article/details/gtntnoxqby.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shangyingyoupin.top/Article/details/gttzgjbxpq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.quarkkingdee.top/Article/details/gtotjtyktp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fengsongda.top/Article/details/gtehmrdnsl.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daria6918.cn/Article/details/gtswcybici.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jlsjyb.cn/Article/details/gthsvxztfb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jyoumei.cn/Article/details/gtnclnpgjm.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xinyue.icu/Article/details/gtihwjhfcv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shzxlz.cn/Article/details/gtkulwpsyk.html

[L05] 上传文件（multipart）
来源：http://dali.nanxuanxn.top/Article/details/gtuwcslgpx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.fengsongda.top/Article/details/gtagiuznqu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.quarkkingdee.top/Article/details/gthoriczyv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ppjwa.cn/Article/details/gtubcwkynw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shangyingyoupin.top/Article/details/gtxrxxfxgj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.kuanghao11.cn/Article/details/gtsfdblacp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ehwqpu.com/Article/details/gtkgiioqfk.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yonumen.top/Article/details/gtkztwktrx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xziqi.cn/Article/details/gttmodryvz.html

[L06] 解析响应为 JSON
来源：http://dali.zhengqikj.top/Article/details/gtrozxatam.html

Py:   resp.json()
来源：http://dali.gotoacloud.top/Article/details/gtdolewgyl.html

PHP:  json_decode($body, true);
来源：http://dali.sysykeji.top/Article/details/gttbusfdpk.html

JS:   await resp.json()
来源：http://dali.nanxinkj.top/Article/details/gtpqpdznef.html

TS:   await resp.json()
来源：http://dali.chenlongwang.top/Article/details/gtuxzdppux.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gtvwwratiw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhengqikj.top/Article/details/gtkezpdrip.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yongpay.top/Article/details/gtrsooitum.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.dashuyun.cn/Article/details/gtpmnwofff.html

[L07] 处理 HTTP 状态码
来源：http://dali.hywenlv.cn/Article/details/gtzqlqvsnc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zdqjudy.top/Article/details/gtlnsbaidh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cdnleiting.top/Article/details/gtpnajrlwm.html

JS:   resp.ok;  resp.status
来源：http://dali.havefunace.top/Article/details/gtwuzmypef.html

TS:   resp.ok;  resp.status
来源：http://dali.quarkkingdee.top/Article/details/gtxrcjujig.html

Java: resp.statusCode()
来源：http://dali.chenjidiqi.icu/Article/details/gtejheeptv.html

Go:   resp.StatusCode
来源：http://dali.yueranfly.top/Article/details/gtlodksmid.html

Ruby: resp.code.to_i
来源：http://dali.hnqzz.top/Article/details/gtpppgrznm.html


<!-- 参考信息 -->