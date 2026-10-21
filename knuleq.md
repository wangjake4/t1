代发 wailian999

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.redwolf501.top/Article/details/gttubctkmg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sysykeji.top/Article/details/gtluzmacps.html

JS:   /\d+/.test(s)
来源：http://dali.jianghu66.top/Article/details/gtjmhxpxro.html

TS:   /\d+/.test(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjcjwylka.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cashguo.top/Article/details/gtgocczate.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jqgfzy.top/Article/details/gttmfmuaux.html

Ruby: s.match?(/\d+/)
来源：http://dali.shuidangran.top/Article/details/gtufksstcg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhoulong.xyz/Article/details/gtoypmpiyu.html

[I02] 提取所有匹配
来源：http://dali.yuanzhike.top/Article/details/gtwmignavh.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shangyingyoupin.top/Article/details/gtdrwphboe.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.dianchejie.cn/Article/details/gtijvrzhsa.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hnxiangtu.top/Article/details/gtnousicqo.html

TS:   s.match(/\d+/g)
来源：http://dali.fzhhl.top/Article/details/gtkyhbuvjx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj20258.top/Article/details/gtojdbgbta.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yangfankeji.com/Article/details/gtwqmyhokv.html

Ruby: s.scan(/\d+/)
来源：http://dali.aizwys.cn/Article/details/gtgtxwhtwc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xinyue.icu/Article/details/gtcdupwmqu.html

[I03] 提取捕获分组
来源：http://dali.yvedp.cn/Article/details/gtfjakafjs.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtegxubdkw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shzxlz.cn/Article/details/gtviiykxrs.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.iojbl.cn/Article/details/gtlyxppmdj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ivvv.top/Article/details/gtupocpdku.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gogol.net.cn/Article/details/gtpytfglzx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cheryme.top/Article/details/gtosiubgvu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jqgfzy.top/Article/details/gtbiinbzdn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.tianlin.xyz/Article/details/gtzrcjybkw.html

[I04] 正则替换
来源：http://dali.xylfe.cn/Article/details/gtdtcigsab.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gaohongyu789.top/Article/details/gtiahrcpjx.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258888.top/Article/details/gthcsgkoli.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.aizwys.cn/Article/details/gtvvhffgma.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sweek.top/Article/details/gtgkpkmwiq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gogol.net.cn/Article/details/gtfreigpvg.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jianghu66.top/Article/details/gtuoruuofk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gotoacloud.top/Article/details/gtrbtqxbhq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shuidangran.top/Article/details/gtpeuvnlin.html

[I05] 按正则拆分
来源：http://dali.chenjidiqi.icu/Article/details/gtsxaaogcl.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmyrzkzua.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtsauhypur.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.pengpengdd.cyou/Article/details/gtzdhqieiz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrbtbdhgk.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yuxming.cn/Article/details/gtvuuqpfbd.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmpaqdqgc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yongpay.top/Article/details/gtmhqsmocy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.chenzaomai.com/Article/details/gtuflwmzuw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jianghu66.top/Article/details/gtpsspiqgv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xziqi.cn/Article/details/gtdugeblox.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ivvv.top/Article/details/gtnelkzzva.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.mhx1999.top/Article/details/gtepujynqe.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhoulong.xyz/Article/details/gtpefirpsl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.iojbl.cn/Article/details/gtzzzkxnfr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jiagoushi.top/Article/details/gtrjglzamc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.tanke756.top/Article/details/gtmcljzqys.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shangyingyoupin.top/Article/details/gtsuwgvusu.html

[I07] 忽略大小写与多行模式
来源：http://dali.tianlin.xyz/Article/details/gtznggrdzp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sxryk.cn/Article/details/gtyfgynijg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbyynpghb.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cheryme.top/Article/details/gtnwtbpcys.html

TS:   /error/gim
来源：http://dali.gaohongyu789.top/Article/details/gtycvunumj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.quarkkingdee.top/Article/details/gtnefiacay.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shuidangran.top/Article/details/gtfpgawbrl.html

Ruby: s.scan(/error/i)
来源：http://dali.snrcjt.cn/Article/details/gtxjnlgbho.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhongyouzk.top/Article/details/gtevvdbudg.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtistbxqsd.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ppjwa.cn/Article/details/gtcjhkkgoe.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.tian-w.cn/Article/details/gthvrbychl.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdvlznyfx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.birdmap.top/Article/details/gteauclyux.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zycfv.cn/Article/details/gthbylyahv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.c1oappe.top/Article/details/gtrmnjgtzx.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.svipenyu.cn/Article/details/gtpvsiyzqy.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.dianchejie.cn/Article/details/gtzrdlslut.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtkmcxcgcj.html

J. 日期与时间
来源：http://dali.hysaishi.cn/Article/details/gtmjfjkdmm.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtekefakiu.html

[J01] 获取当前时间
来源：http://dali.yongpay.top/Article/details/gtnenotqqi.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yonumen.top/Article/details/gtxzalpdtp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.316326.xyz/Article/details/gtwtwoxbzp.html

JS:   new Date();  Date.now()
来源：http://dali.pengpengdd.cyou/Article/details/gtfbqlrwyp.html

TS:   new Date();  Date.now()
来源：http://dali.hysaishi.cn/Article/details/gtpdpzrqtb.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.c1oappe.top/Article/details/gtgplkxxur.html

Go:   time.Now()
来源：http://dali.9152youxi.cn/Article/details/gtjhjsiixk.html

Ruby: Time.now
来源：http://dali.hfpthk.cn/Article/details/gtnarlwfcm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.guannengcc.top/Article/details/gtalnaiwxt.html

[J02] 格式化输出
来源：http://dali.xuetiantiany.cn/Article/details/gtxxkamkgo.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gotoacloud.top/Article/details/gtuylaxieb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yonumen.top/Article/details/gtfnpkgqsx.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gogol.net.cn/Article/details/gttikvmpqy.html

TS:   d.toISOString()
来源：http://dali.nanxinkj.top/Article/details/gtbdxoxroj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.daxiang520.top/Article/details/gtkymzduou.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ehwqpu.com/Article/details/gtjxrygpvx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hysaishi.cn/Article/details/gtvtqzbgcv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.chenzaomai.com/Article/details/gtgaverpig.html

[J03] 字符串解析为日期
来源：http://dali.iojbl.cn/Article/details/gtcmahooln.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.daxiang520.top/Article/details/gtyjoykbrl.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj20258888.top/Article/details/gtqnepmxxn.html

JS:   new Date("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gtmjzjsrhe.html

TS:   new Date("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gtdrnqwoks.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gtlohxwtrk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gttboqhfiw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gtnmcoxcwg.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sxryk.cn/Article/details/gtqkqojtcq.html

[J04] 时间戳与日期互转
来源：http://dali.xuetiantiany.cn/Article/details/gtcufomyih.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ybcxt.top/Article/details/gttjgrgurk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhongyouzk.top/Article/details/gtlouuwrze.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gogol.net.cn/Article/details/gtxgxupigl.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ydzc1.top/Article/details/gtgluuymqd.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.quarkkingdee.top/Article/details/gtntxubgfz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.fzhhl.top/Article/details/gtpytybvqc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yj20258.top/Article/details/gtkobzoyym.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.0kj1m.cn/Article/details/gtifyixjsb.html

[J05] 时间加减（加 7 天）
来源：http://dali.iojbl.cn/Article/details/gtkgnogfzo.html

Py:   now + timedelta(days=7)
来源：http://dali.birdmap.top/Article/details/gtoiavrmvx.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ivvv.top/Article/details/gtzqdkpbhz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.c1oappe.top/Article/details/gtlfplmhwj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hysaishi.cn/Article/details/gtiqquzsiu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.0kj1m.cn/Article/details/gtkpbuagew.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cheryme.top/Article/details/gtgyvbueyr.html

Ruby: Time.now + 7 * 86400
来源：http://dali.dianchejie.cn/Article/details/gtyrpgijrh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shzxlz.cn/Article/details/gtulgholcj.html

[J06] 计算两时间之差
来源：http://dali.cqqwz.cn/Article/details/gtkjadbwvj.html

Py:   (end - start).total_seconds()
来源：http://dali.xuanzx.com/Article/details/gtimlpyilp.html

PHP:  $end->diff($start)->days;
来源：http://dali.ivvv.top/Article/details/gttkyggkjl.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinqigufen.top/Article/details/gtevgdjowh.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.kuanghao11.cn/Article/details/gtbdyodocr.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jyoumei.cn/Article/details/gtcneeutwc.html

Go:   end.Sub(start).Hours()
来源：http://dali.chenjidiqi.icu/Article/details/gteloytvmy.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpaucfczk.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhengqikj.top/Article/details/gtnnxsardn.html

[J07] 比较两个日期
来源：http://dali.sweek.top/Article/details/gtyofbewiy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tian-w.cn/Article/details/gtgrdkeyur.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhengqikj.top/Article/details/gtzbowhyef.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.pengpengdd.cyou/Article/details/gtfvcqtvye.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hywenlv.cn/Article/details/gtqdgorypw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.nwbrower.top/Article/details/gtafvqckgv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.fengsongda.top/Article/details/gtjvtebhhe.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhoulong.xyz/Article/details/gtoklsjxez.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jyoumei.cn/Article/details/gtftykycbe.html

[J08] 提取年月日与星期
来源：http://dali.sysykeji.top/Article/details/gtaargzdax.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.daria6918.cn/Article/details/gtlcklfmcy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinghuilouyu.cn/Article/details/gtskrgcmno.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yuxming.cn/Article/details/gtfjhjxkpk.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xinyue.icu/Article/details/gtqzzqbjma.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cqqwz.cn/Article/details/gtjyaimdix.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.9152youxi.cn/Article/details/gtoywcqidl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjexwrrrv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhengqikj.top/Article/details/gtipmoknql.html

[J09] 时区处理
来源：http://dali.chenjidiqi.icu/Article/details/gtlyjnqcgj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.mhx1999.top/Article/details/gtorgvbnty.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.smart0.xyz/Article/details/gtxhfoubmf.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fzhhl.top/Article/details/gtrvdwpxkj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuetiantiany.cn/Article/details/gtncqdkixt.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xinyue.icu/Article/details/gtmyoaowzg.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.mhx1999.top/Article/details/gtluuccowh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ppjwa.cn/Article/details/gtskstoqnh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhoulong.xyz/Article/details/gtfunqtfhe.html

[J10] 取今天 / 本月第一天
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlkauwgof.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zycfv.cn/Article/details/gteehmbrdk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.chenlongwang.top/Article/details/gtaptswtud.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yj20258.top/Article/details/gtyuiutywa.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.chenzaomai.com/Article/details/gtlzquuxgm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.pycfn.com/Article/details/gtjwrxsvjs.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.redwolf501.top/Article/details/gtxzvuidyn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yongpay.top/Article/details/gtdoytoopq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.feifeiyinyue.top/Article/details/gttflbyiqm.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtdfuqrmue.html

K. JSON 与序列化
来源：http://dali.xinyue.icu/Article/details/gthmeznjkc.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtmigjcvkf.html

[K01] 对象转 JSON 字符串
来源：http://dali.hfpthk.cn/Article/details/gtvaizlttk.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.daria6918.cn/Article/details/gtxnudkvol.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvtsypbdb.html

JS:   JSON.stringify(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtntmiysti.html

TS:   JSON.stringify(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtivhsguig.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ydzc1.top/Article/details/gtlgwkoxll.html

Go:   json.Marshal(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gttzzqgzne.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gaohongyu789.top/Article/details/gtlsehymsq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.iojbl.cn/Article/details/gtqsekpynd.html

[K02] JSON 字符串转对象
来源：http://dali.feifeiyinyue.top/Article/details/gtvpfabwlu.html

Py:   json.loads(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtjxbprbkr.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.quarkkingdee.top/Article/details/gtyksaunmz.html

JS:   JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gtbdjaknzn.html

TS:   JSON.parse(s)
来源：http://dali.bjfxy.top/Article/details/gtqnlmmflq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sufxvd.cn/Article/details/gtpqvibpic.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cqqwz.cn/Article/details/gtuzrlosjy.html

Ruby: JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gtlpddlgpv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yuanzhike.top/Article/details/gtvmxlipfs.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhoulong.xyz/Article/details/gtqkgdrihh.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.0kj1m.cn/Article/details/gtmxtthhal.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.wangshuangyany.cn/Article/details/gtmhfrthnf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhengqikj.top/Article/details/gtxvtwbxtp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ivvv.top/Article/details/gtcgmdhbly.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtpqcdjole.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.chenjidiqi.icu/Article/details/gtayvqdvmo.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.chenlongwang.top/Article/details/gtzdnaimab.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.chenzaomai.com/Article/details/gtiknugftu.html

[K04] 读取 JSON 文件
来源：http://dali.zhongyouzk.top/Article/details/gtxdptcvsg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shangyingyoupin.top/Article/details/gtxyupnzfr.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gaohongyu789.top/Article/details/gtijozptxj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.andypj.xyz/Article/details/gtzwkikffx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jiagoushi.top/Article/details/gtyahfwmsn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.dashuyun.cn/Article/details/gtmsznajjc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hammf.cn/Article/details/gtmpvkprds.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zycfv.cn/Article/details/gtdvzydkmv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.c1oappe.top/Article/details/gtmbumrvrw.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gticnznxez.html

Py:   copy.deepcopy(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtuxrkudkw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.wangdashe.top/Article/details/gthxmrwffd.html

JS:   structuredClone(obj)
来源：http://dali.tianlin.xyz/Article/details/gtyazhijvf.html

TS:   structuredClone(obj)
来源：http://dali.pycfn.com/Article/details/gtfskpunqz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.0kj1m.cn/Article/details/gtfkbbigvq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shuidangran.top/Article/details/gtfvjlhtrm.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jyoumei.cn/Article/details/gtdedrvxgc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnzvcdvzo.html

[K06] 解析 URL 查询串
来源：http://dali.guowangkeji.top/Article/details/gtxmaibfji.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtolndkkln.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.dianchejie.cn/Article/details/gtbmkrqdtd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenlongwang.top/Article/details/gttlxvttnk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangshuangyany.cn/Article/details/gtbsrcmzjq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.fzhhl.top/Article/details/gtszlitcdw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yvedp.cn/Article/details/gtkkmdpwzr.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.iojbl.cn/Article/details/gtcpobuvix.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdweeuivo.html

[K07] 进制转换
来源：http://dali.shuidangran.top/Article/details/gtgfmqplqz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gtrgnqffho.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sufxvd.cn/Article/details/gtmmszkuzy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gtswcwmxoi.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gtypsobahy.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gtqrtfmuns.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zycfv.cn/Article/details/gtiqoyjjpm.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.0kj1m.cn/Article/details/gthsmvbtpk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gtnrbwgfgs.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cdnleiting.top/Article/details/gtosayuimd.html

Py:   pickle.dumps(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtkclveksy.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gzhubu.top/Article/details/gtmthikgwz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.tianlin.xyz/Article/details/gtjiefmpxa.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gtwjiewigb.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yanxiufei.cn/Article/details/gtvjvaenil.html

Go:   encoding/gob
来源：http://dali.jyoumei.cn/Article/details/gtsfyljrrx.html

Ruby: Marshal.dump(obj)
来源：http://dali.meibo888.top/Article/details/gthvdycacv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhongyouzk.top/Article/details/gtnbbanico.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtcminqnci.html

L. 网络请求
来源：http://dali.tian-w.cn/Article/details/gtkcqrdpcb.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtuqxuxvgg.html

[L01] 发送 GET 请求
来源：http://dali.guowangkeji.top/Article/details/gthqdxrmad.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.nanxinkj.top/Article/details/gtslhnfukb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shuidangran.top/Article/details/gtfjzscewz.html

JS:   await fetch(url)
来源：http://dali.guowangkeji.top/Article/details/gteyphzcwa.html

TS:   await fetch(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzcsuqyud.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.svipenyu.cn/Article/details/gtcpaflzsb.html

Go:   resp, err := http.Get(url)
来源：http://dali.bjfxy.top/Article/details/gtkanvikoz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.dianchejie.cn/Article/details/gtqohdzchn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinqigfzy.top/Article/details/gtgzcpwcvy.html

[L02] 发送 POST JSON
来源：http://dali.xylfe.cn/Article/details/gtuasvfixp.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.birdmap.top/Article/details/gtpsiiefhy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sysykeji.top/Article/details/gtgvjbolsa.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jiagoushi.top/Article/details/gtazpbowgr.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fengsongda.top/Article/details/gtgpyutpxw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.c1oappe.top/Article/details/gtmbriyuhp.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sysykeji.top/Article/details/gtaycdrnjz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.tianlin.xyz/Article/details/gtrcxaoeos.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.chenlongwang.top/Article/details/gttihqzlnx.html

[L03] 设置自定义请求头
来源：http://dali.havefunace.top/Article/details/gtqjkdavzk.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ivvv.top/Article/details/gtseycjuge.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ybcxt.top/Article/details/gtiqqqncwu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gtorostond.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yanxiufei.cn/Article/details/gtfgflrfss.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinqigfzy.top/Article/details/gtgjbmdzhb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sxryk.cn/Article/details/gtpokmresl.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.fengsongda.top/Article/details/gtyqagissu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sysykeji.top/Article/details/gtmqjkffxc.html

[L04] 设置超时
来源：http://dali.redwolf501.top/Article/details/gtrkucrgcg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.nwbrower.top/Article/details/gtusxwxeup.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sxryk.cn/Article/details/gtniseovqp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sxryk.cn/Article/details/gtnyomrdfv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shuidangran.top/Article/details/gtorpidnqh.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yonumen.top/Article/details/gtukouincm.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.kuanghao11.cn/Article/details/gtzwokbcsa.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.nwbrower.top/Article/details/gtsnrckxkr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.feifeiyinyue.top/Article/details/gtsqgzixyv.html

[L05] 上传文件（multipart）
来源：http://dali.pengpengdd.cyou/Article/details/gthdrcrexf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cqqwz.cn/Article/details/gtftjxopxl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.mhx1999.top/Article/details/gtlvrxgyvw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.pengpengdd.cyou/Article/details/gtsytsdnaj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnxiangtu.top/Article/details/gtmtviedyw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xziqi.cn/Article/details/gtuqutbvko.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhiwuduotai.top/Article/details/gtkuffjmdl.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.pengpengdd.cyou/Article/details/gthvfcmxdb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjrsqmqpi.html

[L06] 解析响应为 JSON
来源：http://dali.yueranfly.top/Article/details/gtofqtwxlk.html

Py:   resp.json()
来源：http://dali.ybcxt.top/Article/details/gtpiyexxkx.html

PHP:  json_decode($body, true);
来源：http://dali.zdqjudy.top/Article/details/gteluvvkeu.html

JS:   await resp.json()
来源：http://dali.gotoacloud.top/Article/details/gtbbgjcmgu.html

TS:   await resp.json()
来源：http://dali.yvedp.cn/Article/details/gtsvfpilxl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hammf.cn/Article/details/gtxioirsvq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlaxypqbo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhiwuduotai.top/Article/details/gtzmzxinuw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yueranfly.top/Article/details/gtfrdzskur.html

[L07] 处理 HTTP 状态码
来源：http://dali.cashguo.top/Article/details/gtapeyqkfu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tian-w.cn/Article/details/gtveswfkse.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cdnleiting.top/Article/details/gttlenagng.html

JS:   resp.ok;  resp.status
来源：http://dali.wangdashe.top/Article/details/gtsjqqoqqj.html


<!-- 参考信息 -->