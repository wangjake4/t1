代发 wailian999

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.snrcjt.cn/Article/details/gt2chdlmtov.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2feanyhjp.html

Ruby: s.match?(/\d+/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xigcegmf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.birdmap.top/Article/details/gt2bkuzwuzd.html

[I02] 提取所有匹配
来源：http://dali.cqqwz.cn/Article/details/gt2mgrpxnko.html

Py:   re.findall(r"\d+", s)
来源：http://dali.guannengcc.top/Article/details/gt2cfhjezsy.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.quarkkingdee.top/Article/details/gt2dyfhfvbn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhongyouzk.top/Article/details/gt2dhdrdwdc.html

TS:   s.match(/\d+/g)
来源：http://dali.shzxlz.cn/Article/details/gt2qyyttlgy.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lqxslysb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.mhx1999.top/Article/details/gt2piibeigm.html

Ruby: s.scan(/\d+/)
来源：http://dali.0kj1m.cn/Article/details/gt2awazuyvv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.snrcjt.cn/Article/details/gt2nojzvssz.html

[I03] 提取捕获分组
来源：http://dali.yvedp.cn/Article/details/gt2nfkeyyhr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.birdmap.top/Article/details/gt2lpaotjlx.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.iojbl.cn/Article/details/gt2vgqzukfh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cqqwz.cn/Article/details/gt2ntoqnuzn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.birdmap.top/Article/details/gt2upndgssl.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zadpwemq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.wangdashe.top/Article/details/gt2eiyqdlzu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hnxiangtu.top/Article/details/gt2boamwpib.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.pengpengdd.cyou/Article/details/gt2axoruvyk.html

[I04] 正则替换
来源：http://dali.dianchejie.cn/Article/details/gt2zeiqetty.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cucudq.cn/Article/details/gt2xmtkftmu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258888.top/Article/details/gt2cywxzoqw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigufen.top/Article/details/gt2dkggjbph.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgufenzy.top/Article/details/gt2mmmcpfyj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uwgzahyb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.quarkkingdee.top/Article/details/gt2xxmvgicl.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.haohaochexian.top/Article/details/gt2qedvmcop.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yuanzhike.top/Article/details/gt2cjcnfljn.html

[I05] 按正则拆分
来源：http://dali.mhx1999.top/Article/details/gt2akwzwxlm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cashguo.top/Article/details/gt2atygfrgy.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gt2oeikrslo.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mmwvxcky.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.dianchejie.cn/Article/details/gt2xutobggo.html

Java: s.split("\\s*,\\s*")
来源：http://dali.redwolf501.top/Article/details/gt2ewcchyxw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ppjwa.cn/Article/details/gt2fabnhxng.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zycfv.cn/Article/details/gt2kizramzp.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shuidangran.top/Article/details/gt2wdtukrdz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xylfe.cn/Article/details/gt2sziubohk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sysykeji.top/Article/details/gt2bnwxfciw.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gaohongyu789.top/Article/details/gt2xpdwhaxb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.iojbl.cn/Article/details/gt2zjgcvkyk.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jlsjyb.cn/Article/details/gt2kzpfukxt.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.c1oappe.top/Article/details/gt2peaeoapd.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.pengpengdd.cyou/Article/details/gt2duyhqvnd.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.chenlongwang.top/Article/details/gt2rzujnfho.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.iojbl.cn/Article/details/gt2urtufded.html

[I07] 忽略大小写与多行模式
来源：http://dali.yongpay.top/Article/details/gt2eetslfyq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2czeijrbc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.bjfxy.top/Article/details/gt2mcpkrssq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nuzqhpdp.html

TS:   /error/gim
来源：http://dali.jianghu66.top/Article/details/gt2yojhnarv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cqqwz.cn/Article/details/gt2bdhmwxvy.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.dashuyun.cn/Article/details/gt2epwhegjz.html

Ruby: s.scan(/error/i)
来源：http://dali.fengsongda.top/Article/details/gt2kpdakgla.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.kuanghao11.cn/Article/details/gt2afgeqgoy.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.aizwys.cn/Article/details/gt2mfcsiail.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.nanxinkj.top/Article/details/gt2gurytvoc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.dashuyun.cn/Article/details/gt2kpvsavvw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinqigufen.top/Article/details/gt2xanwrbff.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hywenlv.cn/Article/details/gt2vrbufcbi.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shuidangran.top/Article/details/gt2wdetiiyz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xuanzx.com/Article/details/gt2hubglpmp.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.wangdashe.top/Article/details/gt2dudbxkrm.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.meibo888.top/Article/details/gt2xijhqhld.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vfsrwjjm.html

J. 日期与时间
来源：http://dali.snrcjt.cn/Article/details/gt2prmrqxuk.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2drlzeclj.html

[J01] 获取当前时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ndewokrb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.guowangkeji.top/Article/details/gt2ginmevcy.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sufxvd.cn/Article/details/gt2ruatgrec.html

JS:   new Date();  Date.now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2usxdwmlq.html

TS:   new Date();  Date.now()
来源：http://dali.gzhubu.top/Article/details/gt2mugazamm.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nanxuanxn.top/Article/details/gt2gfnpvehb.html

Go:   time.Now()
来源：http://dali.daxiang520.top/Article/details/gt2ugrysfkb.html

Ruby: Time.now
来源：http://dali.zhijiandao.cn/Article/details/gt2xudbgegp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cdnleiting.top/Article/details/gt2jfaciwaz.html

[J02] 格式化输出
来源：http://dali.meibo888.top/Article/details/gt2mwazmruz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ppjwa.cn/Article/details/gt2hxxtdogf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.mhx1999.top/Article/details/gt2egsxpepu.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jyoumei.cn/Article/details/gt2hsnevyou.html

TS:   d.toISOString()
来源：http://dali.ydzc1.top/Article/details/gt2clwwlfif.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinqigfzy.top/Article/details/gt2honyexfb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oifgpypm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.c1oappe.top/Article/details/gt2bplahcjj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.316326.xyz/Article/details/gt2odlnyicz.html

[J03] 字符串解析为日期
来源：http://dali.yueranfly.top/Article/details/gt2iackrjbz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhiwuduotai.top/Article/details/gt2kzisjema.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yvedp.cn/Article/details/gt2orgtcmks.html

JS:   new Date("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gt2jtwtprvm.html

TS:   new Date("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gt2lrikcixr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gt2xwafvdhe.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gt2pnocbscc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gt2mjrgbmxa.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sysykeji.top/Article/details/gt2kqbgdygt.html

[J04] 时间戳与日期互转
来源：http://dali.daxiang520.top/Article/details/gt2qfolxhug.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhoulong.xyz/Article/details/gt2aimddqyy.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.pengpengdd.cyou/Article/details/gt2xadpjpag.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cheryme.top/Article/details/gt2zznflptr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.iojbl.cn/Article/details/gt2kwvzzqxm.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cqqwz.cn/Article/details/gt2kelljtij.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.birdmap.top/Article/details/gt2igasmria.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.gotoacloud.top/Article/details/gt2mmhmddjx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhixingplan.top/Article/details/gt2pqoimzxk.html

[J05] 时间加减（加 7 天）
来源：http://dali.c1oappe.top/Article/details/gt2hiiwgjje.html

Py:   now + timedelta(days=7)
来源：http://dali.xinyue.icu/Article/details/gt2arigwuhh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ehwqpu.com/Article/details/gt2gmcrgfdc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.316326.xyz/Article/details/gt2zpywswqp.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jiagoushi.top/Article/details/gt2uldffcsb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinqigfzy.top/Article/details/gt2dxtzaftq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ppjwa.cn/Article/details/gt2wovkewwd.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xuetiantiany.cn/Article/details/gt2ureassne.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shzxlz.cn/Article/details/gt2djdsbsyz.html

[J06] 计算两时间之差
来源：http://dali.fzhhl.top/Article/details/gt2vxvnavdw.html

Py:   (end - start).total_seconds()
来源：http://dali.yueranfly.top/Article/details/gt2jzwbofen.html

PHP:  $end->diff($start)->days;
来源：http://dali.gaohongyu789.top/Article/details/gt2ostxtvaw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.meibo888.top/Article/details/gt2rkgckfmd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2swahorul.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.pycfn.com/Article/details/gt2oqcchdzb.html

Go:   end.Sub(start).Hours()
来源：http://dali.cqqwz.cn/Article/details/gt2flxomfgf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhiwuduotai.top/Article/details/gt2jfaejpnq.html

C#:   (end - start).TotalSeconds
来源：http://dali.yuxming.cn/Article/details/gt2bxqgzamv.html

[J07] 比较两个日期
来源：http://dali.yj20258888.top/Article/details/gt2foymkqbf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gt2lwufnhvv.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hnxiangtu.top/Article/details/gt2axlzxbtj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gaohongyu789.top/Article/details/gt2jubqhhrn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhoulong.xyz/Article/details/gt2ketxxodn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nrwizcbv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.snrcjt.cn/Article/details/gt2tcyoorke.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yvedp.cn/Article/details/gt2ngurdyrn.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jianghu66.top/Article/details/gt2jlwrkfdr.html

[J08] 提取年月日与星期
来源：http://dali.nanxinkj.top/Article/details/gt2unyzuxlu.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.iojbl.cn/Article/details/gt2fdvhjure.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hfpthk.cn/Article/details/gt2gpbmfevd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jianghu66.top/Article/details/gt2ihbsxeqx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jlsjyb.cn/Article/details/gt2cvwpwrto.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.mhx1999.top/Article/details/gt2docfnglc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yuanzhike.top/Article/details/gt2zcpapmac.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.redwolf501.top/Article/details/gt2bgovpflk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.daxiang520.top/Article/details/gt2llgvzviv.html

[J09] 时区处理
来源：http://dali.jinqigufen.top/Article/details/gt2nnbacwwe.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.aibaodan.cn/Article/details/gt2nrdrayso.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.birdmap.top/Article/details/gt2isrebpfi.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guowangkeji.top/Article/details/gt2umxsegmf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rocprqio.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gotoacloud.top/Article/details/gt2ihdslzfj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yongpay.top/Article/details/gt2epyqdlll.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hammf.cn/Article/details/gt2xbpdksju.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.nanxuanxn.top/Article/details/gt2fzspxqfj.html

[J10] 取今天 / 本月第一天
来源：http://dali.xinyue.icu/Article/details/gt2avpbiren.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.pycfn.com/Article/details/gt2hxtcydlu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.fzhhl.top/Article/details/gt2eajmnodf.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.daxiang520.top/Article/details/gt2uwsnwdyt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ivvv.top/Article/details/gt2bcontrsu.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.c1oappe.top/Article/details/gt2kooxhlhk.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.c1oappe.top/Article/details/gt2glvyxrqf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xuetiantiany.cn/Article/details/gt2qulbegfh.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gzhubu.top/Article/details/gt2ovzqxzzf.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2etmaokds.html

K. JSON 与序列化
来源：http://dali.0kj1m.cn/Article/details/gt2dubqgpvj.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2qedzufti.html

[K01] 对象转 JSON 字符串
来源：http://dali.yangfankeji.com/Article/details/gt2trzhzngx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jpagcbeo.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.sweek.top/Article/details/gt2ozewielo.html

JS:   JSON.stringify(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2kmhfdvpw.html

TS:   JSON.stringify(obj)
来源：http://dali.fengsongda.top/Article/details/gt2cfcsjhxl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xziqi.cn/Article/details/gt2hsfwtmgy.html

Go:   json.Marshal(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wtfdpoho.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinqigfzy.top/Article/details/gt2cykmrnol.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.havefunace.top/Article/details/gt2amnstlpb.html

[K02] JSON 字符串转对象
来源：http://dali.jlsjyb.cn/Article/details/gt2zpaudsnj.html

Py:   json.loads(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2leexnmof.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hysaishi.cn/Article/details/gt2unnuufda.html

JS:   JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ofssrjet.html

TS:   JSON.parse(s)
来源：http://dali.bjfxy.top/Article/details/gt2ipdrjvho.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.nanxuanxn.top/Article/details/gt2qhlimimt.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.daria6918.cn/Article/details/gt2elotybqb.html

Ruby: JSON.parse(s)
来源：http://dali.jinqigufen.top/Article/details/gt2yqicvcka.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinqigufen.top/Article/details/gt2emrmfwcv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.kuanghao11.cn/Article/details/gt2eijwqgqc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sweek.top/Article/details/gt2eenjwhfm.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xziqi.cn/Article/details/gt2snzlfarn.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cheryme.top/Article/details/gt2csfqlxjh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cdnleiting.top/Article/details/gt2hitmyhae.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cheryme.top/Article/details/gt2gteryzdz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cashguo.top/Article/details/gt2xojdfndo.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2nvovwtdt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.snrcjt.cn/Article/details/gt2kgvagjvm.html

[K04] 读取 JSON 文件
来源：http://dali.sxryk.cn/Article/details/gt2nobtbiun.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xinyue.icu/Article/details/gt2oqzouvli.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.nwbrower.top/Article/details/gt2owchbfkf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yangfankeji.com/Article/details/gt2paimefgo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hywenlv.cn/Article/details/gt2hpaswapi.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sxryk.cn/Article/details/gt2qewnlmvp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhoulong.xyz/Article/details/gt2odqpjwts.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xxytpanc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fioslobf.html

[K05] 深拷贝对象
来源：http://dali.haohaochexian.top/Article/details/gt2zcnqzzkw.html

Py:   copy.deepcopy(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2lgdcgqzr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.tian-w.cn/Article/details/gt2xyhtlpxy.html

JS:   structuredClone(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2ieliddry.html

TS:   structuredClone(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2dqzmdign.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenjidiqi.icu/Article/details/gt2hlwypliu.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hysaishi.cn/Article/details/gt2lndhsraj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yanxiufei.cn/Article/details/gt2mmxdshoy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhiwuduotai.top/Article/details/gt2pqsmawuh.html

[K06] 解析 URL 查询串
来源：http://dali.xuanzx.com/Article/details/gt2yibezewp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hysaishi.cn/Article/details/gt2ocablctn.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yueranfly.top/Article/details/gt2syrmdqcn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgufenzy.top/Article/details/gt2wpnrtpcv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tianlin.xyz/Article/details/gt2glaqafsq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yanxiufei.cn/Article/details/gt2cjazfrki.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hywenlv.cn/Article/details/gt2qpruudhn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.havefunace.top/Article/details/gt2xifaaujo.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.mhx1999.top/Article/details/gt2yjjfxqjs.html

[K07] 进制转换
来源：http://dali.tianlin.xyz/Article/details/gt2zetzknwo.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gt2qefqsaup.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hongshengwenyu.top/Article/details/gt2fjnligyc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gt2hjfgfddx.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gt2cnlnbuof.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gt2dooccjdc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhoulong.xyz/Article/details/gt2zfngqqcc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yvedp.cn/Article/details/gt2wsrfyhef.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gt2oikxotjk.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yj202588.top/Article/details/gt2vankleww.html

Py:   pickle.dumps(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2mgyoozna.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ydzc1.top/Article/details/gt2rmmxoypu.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.bjfxy.top/Article/details/gt2itdjxvve.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.quarkkingdee.top/Article/details/gt2sprykavg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.vqdsnc.cn/Article/details/gt2mlzkqggc.html

Go:   encoding/gob
来源：http://dali.ppjwa.cn/Article/details/gt2hgvuwzxx.html

Ruby: Marshal.dump(obj)
来源：http://dali.tian-w.cn/Article/details/gt2mdvopamx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhiwuduotai.top/Article/details/gt2zkggfofj.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2avfhqrzo.html

L. 网络请求
来源：http://dali.cashguo.top/Article/details/gt2tvcfhiuu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bncjmppg.html

[L01] 发送 GET 请求
来源：http://dali.aizwys.cn/Article/details/gt2aamtyxux.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.tanke756.top/Article/details/gt2vphmtyzk.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yongpay.top/Article/details/gt2daiwrlqh.html

JS:   await fetch(url)
来源：http://dali.shzxlz.cn/Article/details/gt2zugyawyo.html

TS:   await fetch(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ufwgczmw.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yongpay.top/Article/details/gt2jxjvsnxv.html

Go:   resp, err := http.Get(url)
来源：http://dali.tanke756.top/Article/details/gt2fduwohir.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cheryme.top/Article/details/gt2kayfyswh.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sufxvd.cn/Article/details/gt2dbmxxngx.html

[L02] 发送 POST JSON
来源：http://dali.dashuyun.cn/Article/details/gt2gcdgnskr.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cashguo.top/Article/details/gt2ulspaqeh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhixingplan.top/Article/details/gt2nmgylypp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigfzy.top/Article/details/gt2rmekdslo.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xziqi.cn/Article/details/gt2dbkmnnqt.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gogol.net.cn/Article/details/gt2kxqelqgt.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fcafstcn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yuxming.cn/Article/details/gt2zxpoxrbv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ppjwa.cn/Article/details/gt2ggpvndjc.html

[L03] 设置自定义请求头
来源：http://dali.gotoacloud.top/Article/details/gt2fvojtttw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gotoacloud.top/Article/details/gt2sjuomzeb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.aizwys.cn/Article/details/gt2hiyuwpvt.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxuanxn.top/Article/details/gt2bvhloryd.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aizwys.cn/Article/details/gt2wqhueloo.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yj202588.top/Article/details/gt2oajpqkvn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.kuanghao11.cn/Article/details/gt2ornnxiyl.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zycfv.cn/Article/details/gt2ttdespql.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.wangdashe.top/Article/details/gt2uuvuoqsi.html

[L04] 设置超时
来源：http://dali.ydzc1.top/Article/details/gt2slzrcylf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pwzruucy.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhixingplan.top/Article/details/gt2pfuzuain.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnqzz.top/Article/details/gt2vbkzcckb.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yueranfly.top/Article/details/gt2oiaueeur.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yueranfly.top/Article/details/gt2dldbecqo.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zycfv.cn/Article/details/gt2mtbnrhqv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sxryk.cn/Article/details/gt2uaaxvalq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ppjwa.cn/Article/details/gt2hxkanwys.html

[L05] 上传文件（multipart）
来源：http://dali.nanxuanxn.top/Article/details/gt2bsgameps.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.snrcjt.cn/Article/details/gt2xccopfjo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xuetiantiany.cn/Article/details/gt2xxtwyjfu.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zmltcmtg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sxryk.cn/Article/details/gt2lpiapexr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kyiiyrje.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.tian-w.cn/Article/details/gt2ocrypwty.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.vqdsnc.cn/Article/details/gt2sbwtiffe.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2iwinndng.html

[L06] 解析响应为 JSON
来源：http://dali.pengpengdd.cyou/Article/details/gt2foqeyush.html

Py:   resp.json()
来源：http://dali.c1oappe.top/Article/details/gt2tsnajwwu.html

PHP:  json_decode($body, true);
来源：http://dali.cucudq.cn/Article/details/gt2ydxdvqcm.html

JS:   await resp.json()
来源：http://dali.shuidangran.top/Article/details/gt2zkljruhf.html

TS:   await resp.json()
来源：http://dali.xinyue.icu/Article/details/gt2qwrpmgkm.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.aibaodan.cn/Article/details/gt2xlrhujeu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.redwolf501.top/Article/details/gt2ceqeygfu.html

Ruby: JSON.parse(resp.body)
来源：http://dali.quarkkingdee.top/Article/details/gt2qdcxkxkm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhiwuduotai.top/Article/details/gt2sobswazj.html

[L07] 处理 HTTP 状态码
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kfyuubol.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tianlin.xyz/Article/details/gt2culzzflv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.redwolf501.top/Article/details/gt2aqqgazly.html

JS:   resp.ok;  resp.status
来源：http://dali.zhongyouzk.top/Article/details/gt2byiwhgaf.html

TS:   resp.ok;  resp.status
来源：http://dali.fengsongda.top/Article/details/gt2nlebwhpa.html

Java: resp.statusCode()
来源：http://dali.hywenlv.cn/Article/details/gt2trwmwlnf.html

Go:   resp.StatusCode
来源：http://dali.yonumen.top/Article/details/gt2oqeoxfjk.html

Ruby: resp.code.to_i
来源：http://dali.svipenyu.cn/Article/details/gt2pxxxaltk.html


<!-- 参考信息 -->