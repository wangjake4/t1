代发 wailian999

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.nanxinkj.top/Article/details/gt2inchgjzo.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.tian-w.cn/Article/details/gt2qsxnblzi.html

Ruby: s.match?(/\d+/)
来源：http://dali.yueranfly.top/Article/details/gt2riahrhbx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.aibaodan.cn/Article/details/gt2lbrrdtuc.html

[I02] 提取所有匹配
来源：http://dali.xylfe.cn/Article/details/gt2fukblrvj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.guannengcc.top/Article/details/gt2vqcchfim.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sysykeji.top/Article/details/gt2rkjfydjn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.feifeiyinyue.top/Article/details/gt2gzcgmirb.html

TS:   s.match(/\d+/g)
来源：http://dali.xinyue.icu/Article/details/gt2bjtabfjw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.nanxuanxn.top/Article/details/gt2ldikcpag.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.dashuyun.cn/Article/details/gt2afzfigcj.html

Ruby: s.scan(/\d+/)
来源：http://dali.daxiang520.top/Article/details/gt2rorwkwtj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pszstcub.html

[I03] 提取捕获分组
来源：http://dali.c1oappe.top/Article/details/gt2bhzgqifq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zeeexujx.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hnxiangtu.top/Article/details/gt2okmgbpjc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2cpohjxhc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.vqdsnc.cn/Article/details/gt2kffrxdos.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sysykeji.top/Article/details/gt2phypcynl.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.redwolf501.top/Article/details/gt2vpzbylxt.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shangyingyoupin.top/Article/details/gt2dxlketin.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.smart0.xyz/Article/details/gt2kygidkim.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qqcmehuj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.daxiang520.top/Article/details/gt2nbkkfpvg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.fzhhl.top/Article/details/gt2uhysymst.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hammf.cn/Article/details/gt2hswemjru.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.daria6918.cn/Article/details/gt2cbayutwf.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sysykeji.top/Article/details/gt2xoqjcapx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hywenlv.cn/Article/details/gt2zopykhmk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.bjfxy.top/Article/details/gt2vvqwihzl.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nghnjmjs.html

[I05] 按正则拆分
来源：http://dali.haohaochexian.top/Article/details/gt2kunfwiuq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.fengsongda.top/Article/details/gt2cshygdxf.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.guannengcc.top/Article/details/gt2axekxqlj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gt2kqskqqrx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.guowangkeji.top/Article/details/gt2ujdiaihq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.smart0.xyz/Article/details/gt2bnbnzudw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hywenlv.cn/Article/details/gt2hbtfjxdh.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhoulong.xyz/Article/details/gt2oiptntzw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yanxiufei.cn/Article/details/gt2ecqsvilp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.redwolf501.top/Article/details/gt2rtirbgdt.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cashguo.top/Article/details/gt2uqcnjenj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.c1oappe.top/Article/details/gt2jyynpibd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ivvv.top/Article/details/gt2zrrcuqjk.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxinkj.top/Article/details/gt2vpmsofhp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shangyingyoupin.top/Article/details/gt2gxwggzkm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.tianlin.xyz/Article/details/gt2wfbwqprw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xylfe.cn/Article/details/gt2wortlzyj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.aizwys.cn/Article/details/gt2uclzhbev.html

[I07] 忽略大小写与多行模式
来源：http://dali.iojbl.cn/Article/details/gt2oxbmisnw.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yongpay.top/Article/details/gt2oezgbvdb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhengqikj.top/Article/details/gt2hvakoiap.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yonumen.top/Article/details/gt2blhfzqre.html

TS:   /error/gim
来源：http://dali.yuxming.cn/Article/details/gt2mvqvobxu.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jlsjyb.cn/Article/details/gt2suidnyre.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.316326.xyz/Article/details/gt2qngmrten.html

Ruby: s.scan(/error/i)
来源：http://dali.gotoacloud.top/Article/details/gt2gngyvrww.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.mhx1999.top/Article/details/gt2jjpdbghu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hammf.cn/Article/details/gt2gkdnfpwr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gt2cyolrnqr.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hnxiangtu.top/Article/details/gt2jdbupclh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mnlfopte.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gotoacloud.top/Article/details/gt2gjuvymxb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.snrcjt.cn/Article/details/gt2fdpdjjmo.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gzhubu.top/Article/details/gt2lemfpzqe.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xinyue.icu/Article/details/gt2dyodaeam.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.wangshuangyany.cn/Article/details/gt2oezzipvp.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2cdiyyrjs.html

J. 日期与时间
来源：http://dali.gaohongyu789.top/Article/details/gt2uryzqqef.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2fxfdpehh.html

[J01] 获取当前时间
来源：http://dali.cheryme.top/Article/details/gt2nmeqgmht.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.guowangkeji.top/Article/details/gt2zyhafjaf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.9152youxi.cn/Article/details/gt2irhjmvao.html

JS:   new Date();  Date.now()
来源：http://dali.ivvv.top/Article/details/gt2orqrdyjk.html

TS:   new Date();  Date.now()
来源：http://dali.ybcxt.top/Article/details/gt2xhmmqeaq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhixingplan.top/Article/details/gt2ouwlkflc.html

Go:   time.Now()
来源：http://dali.dianchejie.cn/Article/details/gt2uiwgzwox.html

Ruby: Time.now
来源：http://dali.wangshuangyany.cn/Article/details/gt2wypitufh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zycfv.cn/Article/details/gt2uhbjpcso.html

[J02] 格式化输出
来源：http://dali.xuetiantiany.cn/Article/details/gt2cyimgped.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhiwuduotai.top/Article/details/gt2vmxwrrkr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.redwolf501.top/Article/details/gt2kcdvzcrw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yonumen.top/Article/details/gt2llewfbrz.html

TS:   d.toISOString()
来源：http://dali.ivvv.top/Article/details/gt2tciffqyj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zycfv.cn/Article/details/gt2xwdypbex.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.bjfxy.top/Article/details/gt2dwsxqvcn.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.meibo888.top/Article/details/gt2balryifi.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jyoumei.cn/Article/details/gt2dchazlpr.html

[J03] 字符串解析为日期
来源：http://dali.svipenyu.cn/Article/details/gt2vbbtabdw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhiwuduotai.top/Article/details/gt2pdmrqdev.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.fengsongda.top/Article/details/gt2rgjzyvvo.html

JS:   new Date("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ijvjpklz.html

TS:   new Date("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gt2bkbaukss.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gt2juiaqtda.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gt2wlmulmoh.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gt2npymtvjs.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.tanke756.top/Article/details/gt2qdnsninu.html

[J04] 时间戳与日期互转
来源：http://dali.zhiwuduotai.top/Article/details/gt2cssgsjiw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qlmnhdgb.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.dashuyun.cn/Article/details/gt2aymfkmvl.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zycfv.cn/Article/details/gt2cfgjmgbw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ehwqpu.com/Article/details/gt2xplvkctz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yongpay.top/Article/details/gt2rckgcrpx.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xfpcblzu.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.pycfn.com/Article/details/gt2shzvvccf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shuidangran.top/Article/details/gt2grvhgzrl.html

[J05] 时间加减（加 7 天）
来源：http://dali.cashguo.top/Article/details/gt2cehmgpap.html

Py:   now + timedelta(days=7)
来源：http://dali.chenjidiqi.icu/Article/details/gt2fkeyfkgu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hnqzz.top/Article/details/gt2kspieluz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.mhx1999.top/Article/details/gt2ogyvvulq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daxiang520.top/Article/details/gt2ugnmcsid.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shuidangran.top/Article/details/gt2qfbndwow.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.andypj.xyz/Article/details/gt2qwanxpnu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gogol.net.cn/Article/details/gt2mxlnhszv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.fengsongda.top/Article/details/gt2pfsdxdpz.html

[J06] 计算两时间之差
来源：http://dali.jinqigufen.top/Article/details/gt2ndehlnmp.html

Py:   (end - start).total_seconds()
来源：http://dali.zhixingplan.top/Article/details/gt2tafgsxpw.html

PHP:  $end->diff($start)->days;
来源：http://dali.nanxuanxn.top/Article/details/gt2cpkbgklu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zycfv.cn/Article/details/gt2dlqhpaik.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sweek.top/Article/details/gt2pkjqikfc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj20258888.top/Article/details/gt2wzfkysko.html

Go:   end.Sub(start).Hours()
来源：http://dali.feifeiyinyue.top/Article/details/gt2nhkiweib.html

Ruby: end - start                 # 返回秒数
来源：http://dali.quarkkingdee.top/Article/details/gt2tneltoks.html

C#:   (end - start).TotalSeconds
来源：http://dali.xinyue.icu/Article/details/gt2xydloyvk.html

[J07] 比较两个日期
来源：http://dali.yj20258888.top/Article/details/gt2idqoyzko.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yonumen.top/Article/details/gt2ymwprojl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinqigufen.top/Article/details/gt2wcpwcztj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ztohevea.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.nwbrower.top/Article/details/gt2xzhjzrff.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fdwftrtf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2sgwaapog.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gt2cjtqwxap.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xziqi.cn/Article/details/gt2mmgkpahw.html

[J08] 提取年月日与星期
来源：http://dali.jqgufenzy.top/Article/details/gt2suqwejns.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yvedp.cn/Article/details/gt2xgsschos.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.dianchejie.cn/Article/details/gt2ywsrarnc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.haohaochexian.top/Article/details/gt2jwpjckgm.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.aibaodan.cn/Article/details/gt2ouqyrbil.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.pengpengdd.cyou/Article/details/gt2wpxyrctv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hefakvki.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tanke756.top/Article/details/gt2yapjufpp.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.feifeiyinyue.top/Article/details/gt2fnevxait.html

[J09] 时区处理
来源：http://dali.aibaodan.cn/Article/details/gt2frtscgqk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.wangdashe.top/Article/details/gt2lubnxaef.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.guannengcc.top/Article/details/gt2tobrlohi.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.andypj.xyz/Article/details/gt2vgrwwifg.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shangyingyoupin.top/Article/details/gt2tdewgulc.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ehwqpu.com/Article/details/gt2kecledxc.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cashguo.top/Article/details/gt2dgehfiho.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.chenjidiqi.icu/Article/details/gt2mtwfkqdz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.wangdashe.top/Article/details/gt2zavwmjzn.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenjidiqi.icu/Article/details/gt2pvkvxeif.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hysaishi.cn/Article/details/gt2xqqpcbol.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gotoacloud.top/Article/details/gt2yzwrhzbx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2dyaubjhp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.daria6918.cn/Article/details/gt2lplsretv.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.daxiang520.top/Article/details/gt2nywsdolh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.tanke756.top/Article/details/gt2qjrvwgjl.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.dashuyun.cn/Article/details/gt2eobcgmus.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yonumen.top/Article/details/gt2weakqhbu.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rthislkc.html

K. JSON 与序列化
来源：http://dali.hywenlv.cn/Article/details/gt2dbeceiuq.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vnizxedb.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2ercyjmcd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.guowangkeji.top/Article/details/gt2duaktoax.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cdnleiting.top/Article/details/gt2tprshnon.html

JS:   JSON.stringify(obj)
来源：http://dali.sysykeji.top/Article/details/gt2onifezad.html

TS:   JSON.stringify(obj)
来源：http://dali.bjfxy.top/Article/details/gt2xolekjmz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jiagoushi.top/Article/details/gt2fdzcmzsr.html

Go:   json.Marshal(obj)
来源：http://dali.cheryme.top/Article/details/gt2ehodfhfi.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.nanxinkj.top/Article/details/gt2yjiacwks.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2qarbcnxc.html

[K02] JSON 字符串转对象
来源：http://dali.316326.xyz/Article/details/gt2romvbbto.html

Py:   json.loads(s)
来源：http://dali.c1oappe.top/Article/details/gt2cvibgsos.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhongyouzk.top/Article/details/gt2okjosrhv.html

JS:   JSON.parse(s)
来源：http://dali.fzhhl.top/Article/details/gt2ptcgiulh.html

TS:   JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2arlvasjz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2muvurlrs.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yangfankeji.com/Article/details/gt2dohqfhnd.html

Ruby: JSON.parse(s)
来源：http://dali.ppjwa.cn/Article/details/gt2hxtctdlo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xuanzx.com/Article/details/gt2pneipzgz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cheryme.top/Article/details/gt2qllxupqf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xylfe.cn/Article/details/gt2tcaxaqko.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shzxlz.cn/Article/details/gt2aqbmedry.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yongpay.top/Article/details/gt2hxnxdbme.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2wwdauikv.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.birdmap.top/Article/details/gt2zrtmniyj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhongyouzk.top/Article/details/gt2rmzdvoem.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xswbjquh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.smart0.xyz/Article/details/gt2nvkgthcc.html

[K04] 读取 JSON 文件
来源：http://dali.mhx1999.top/Article/details/gt2vpebdinw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xinyue.icu/Article/details/gt2ofnerzey.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wtbznwfw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yanxiufei.cn/Article/details/gt2kujswfnl.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ltdlarbb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2abagcbhl.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ehwqpu.com/Article/details/gt2iqntwsdv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yueranfly.top/Article/details/gt2wmyskacz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shzxlz.cn/Article/details/gt2mzlphajw.html

[K05] 深拷贝对象
来源：http://dali.jqgfzy.top/Article/details/gt2qxrcrjfh.html

Py:   copy.deepcopy(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2fqqfsfhh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.tanke756.top/Article/details/gt2vbkqrrdl.html

JS:   structuredClone(obj)
来源：http://dali.ivvv.top/Article/details/gt2tqrabiqs.html

TS:   structuredClone(obj)
来源：http://dali.zycfv.cn/Article/details/gt2crolccij.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shuidangran.top/Article/details/gt2mrqvesei.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shuidangran.top/Article/details/gt2gioxsgvu.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.nanxuanxn.top/Article/details/gt2bgjbuegg.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gaohongyu789.top/Article/details/gt2kgxvxqwc.html

[K06] 解析 URL 查询串
来源：http://dali.aibaodan.cn/Article/details/gt2kvnhsxtp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.svipenyu.cn/Article/details/gt2ujgnzcsi.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.feifeiyinyue.top/Article/details/gt2znchcutx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj202588.top/Article/details/gt2nbbszuce.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.redwolf501.top/Article/details/gt2jjkoyinp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yj20258.top/Article/details/gt2udeokjls.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gotoacloud.top/Article/details/gt2ajfdwiks.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shangyingyoupin.top/Article/details/gt2qiinadrk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yueranfly.top/Article/details/gt2wjbqbdmi.html

[K07] 进制转换
来源：http://dali.yuanzhike.top/Article/details/gt2axddxhrb.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gt2baxylgea.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hysaishi.cn/Article/details/gt2qydyhzhp.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gt2frsohuje.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gt2mntbieyz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gt2rdrdoqdx.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.daria6918.cn/Article/details/gt2zgyuyfeo.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hnqzz.top/Article/details/gt2wvxlfgoy.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gt2wyupopev.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.quarkkingdee.top/Article/details/gt2liecnlvr.html

Py:   pickle.dumps(obj)
来源：http://dali.c1oappe.top/Article/details/gt2ckumfezb.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhoulong.xyz/Article/details/gt2nerqnznb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xylfe.cn/Article/details/gt2kmhjiyos.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jqgufenzy.top/Article/details/gt2domnwniq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yvedp.cn/Article/details/gt2fdcnyipr.html

Go:   encoding/gob
来源：http://dali.9152youxi.cn/Article/details/gt2aaglbtfl.html

Ruby: Marshal.dump(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2jwmlrybx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.svipenyu.cn/Article/details/gt2exmqinmf.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2gfbhvasc.html

L. 网络请求
来源：http://dali.zhoulong.xyz/Article/details/gt2xbkafdef.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2qeamzbic.html

[L01] 发送 GET 请求
来源：http://dali.haohaochexian.top/Article/details/gt2orqmrpfn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jqgfzy.top/Article/details/gt2biegenve.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lxweoxmm.html

JS:   await fetch(url)
来源：http://dali.birdmap.top/Article/details/gt2ijlnieja.html

TS:   await fetch(url)
来源：http://dali.quarkkingdee.top/Article/details/gt2oidnmwjm.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.daria6918.cn/Article/details/gt2koirueai.html

Go:   resp, err := http.Get(url)
来源：http://dali.quarkkingdee.top/Article/details/gt2nxesooar.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yangfankeji.com/Article/details/gt2coflkcvn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jiagoushi.top/Article/details/gt2xqxejpoo.html

[L02] 发送 POST JSON
来源：http://dali.gzhubu.top/Article/details/gt2xpunczat.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yvedp.cn/Article/details/gt2dzusamli.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.9152youxi.cn/Article/details/gt2dugeevdc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sufxvd.cn/Article/details/gt2ctsbobqb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zycfv.cn/Article/details/gt2rsvioaxj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenzaomai.com/Article/details/gt2ezunjrjr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.nwbrower.top/Article/details/gt2qesjkewy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinqigufen.top/Article/details/gt2tpnjqonn.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hywenlv.cn/Article/details/gt2ofocbpbe.html

[L03] 设置自定义请求头
来源：http://dali.cashguo.top/Article/details/gt2xonibpua.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jiagoushi.top/Article/details/gt2ksosqkvh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cashguo.top/Article/details/gt2xjsavxsk.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbgedry.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhongyouzk.top/Article/details/gt2npqntccp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.0kj1m.cn/Article/details/gt2hujbktxa.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.iojbl.cn/Article/details/gt2sftsxplb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.daria6918.cn/Article/details/gt2lefsbnhb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.pengpengdd.cyou/Article/details/gt2zcctmjlt.html

[L04] 设置超时
来源：http://dali.jqgfzy.top/Article/details/gt2oyjdgbzm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.mhx1999.top/Article/details/gt2juntzdck.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.tian-w.cn/Article/details/gt2uvfsyelm.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xylfe.cn/Article/details/gt2bekvkjjt.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cashguo.top/Article/details/gt2urugywti.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.wangshuangyany.cn/Article/details/gt2qsgrkqcq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.aibaodan.cn/Article/details/gt2clqabhbt.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinqigufen.top/Article/details/gt2djvgfltz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqekcfpx.html

[L05] 上传文件（multipart）
来源：http://dali.hnxiangtu.top/Article/details/gt2jsjpvmoa.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sweek.top/Article/details/gt2upfngeee.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.aizwys.cn/Article/details/gt2tirfxdpt.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.nwbrower.top/Article/details/gt2aopweokl.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuanzx.com/Article/details/gt2nahwuqzy.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.smart0.xyz/Article/details/gt2krofuetx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.chenlongwang.top/Article/details/gt2whlfavnf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gzhubu.top/Article/details/gt2tgrthwkf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2qmrycxix.html

[L06] 解析响应为 JSON
来源：http://dali.zhengqikj.top/Article/details/gt2jognxfty.html

Py:   resp.json()
来源：http://dali.cheryme.top/Article/details/gt2qguuiwjr.html

PHP:  json_decode($body, true);
来源：http://dali.dianchejie.cn/Article/details/gt2ftyiwmfr.html

JS:   await resp.json()
来源：http://dali.birdmap.top/Article/details/gt2dsiqtnur.html

TS:   await resp.json()
来源：http://dali.chenzaomai.com/Article/details/gt2xozholbt.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cszahwnw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2khtuxigf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sysykeji.top/Article/details/gt2zmdwcval.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.sufxvd.cn/Article/details/gt2mnudzmjd.html

[L07] 处理 HTTP 状态码
来源：http://dali.guowangkeji.top/Article/details/gt2zxklkgyl.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.mhx1999.top/Article/details/gt2amxwpbak.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.havefunace.top/Article/details/gt2jkcchicn.html

JS:   resp.ok;  resp.status
来源：http://dali.wangshuangyany.cn/Article/details/gt2ribnuzpg.html

TS:   resp.ok;  resp.status
来源：http://dali.gaohongyu789.top/Article/details/gt2ylzzngci.html

Java: resp.statusCode()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hnisixsx.html

Go:   resp.StatusCode
来源：http://dali.daxiang520.top/Article/details/gt2xvgmgqxv.html

Ruby: resp.code.to_i
来源：http://dali.jiagoushi.top/Article/details/gt2rqgdniwm.html


<!-- 参考信息 -->