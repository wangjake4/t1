代发 wailian999

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.nwbrower.top/Article/details/gt2vfpxkjrf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sysykeji.top/Article/details/gt2fxnbhxtj.html

Ruby: s.match?(/\d+/)
来源：http://dali.0kj1m.cn/Article/details/gt2umwborfz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ayddltne.html

[I02] 提取所有匹配
来源：http://dali.jinqigfzy.top/Article/details/gt2hrwjezmh.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tian-w.cn/Article/details/gt2vjsmksuy.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.tianlin.xyz/Article/details/gt2kctbkwnp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.havefunace.top/Article/details/gt2ygnkylwp.html

TS:   s.match(/\d+/g)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zeealkcc.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.0kj1m.cn/Article/details/gt2yocsdmin.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hrbwrdxx.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhengqikj.top/Article/details/gt2jrzkxpkx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.bjfxy.top/Article/details/gt2afcxlzrm.html

[I03] 提取捕获分组
来源：http://dali.zycfv.cn/Article/details/gt2itwhiuok.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.bjfxy.top/Article/details/gt2glunwdkm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yj20258888.top/Article/details/gt2hynotknd.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.snrcjt.cn/Article/details/gt2pwbleavi.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hnxiangtu.top/Article/details/gt2ycyfkatj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cqqwz.cn/Article/details/gt2tgtwneui.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gogol.net.cn/Article/details/gt2dzwppefs.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gzhubu.top/Article/details/gt2mkemawoa.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zycfv.cn/Article/details/gt2punngfxc.html

[I04] 正则替换
来源：http://dali.9152youxi.cn/Article/details/gt2uzbdspnp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.vqdsnc.cn/Article/details/gt2nlptondx.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2lkoayoez.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ydzc1.top/Article/details/gt2coejmigl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhixingplan.top/Article/details/gt2evzurdes.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shuidangran.top/Article/details/gt2kznuoplt.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gt2vauvvsce.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xinyue.icu/Article/details/gt2qmmkcmkd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gogol.net.cn/Article/details/gt2ccbusifg.html

[I05] 按正则拆分
来源：http://dali.aibaodan.cn/Article/details/gt2fdhxxjfx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.chenlongwang.top/Article/details/gt2tskmdobx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.svipenyu.cn/Article/details/gt2prxnnhwr.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kggebvvn.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.havefunace.top/Article/details/gt2qasseemb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhengqikj.top/Article/details/gt2hpwkldhi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ivvv.top/Article/details/gt2pqlaoxgf.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.quarkkingdee.top/Article/details/gt2nxdkdjyq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.wangshuangyany.cn/Article/details/gt2izlgptwm.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.c1oappe.top/Article/details/gt2pddoyeyu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gt2dxclzyqe.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ehwqpu.com/Article/details/gt2mmubfnjy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sufxvd.cn/Article/details/gt2sjhitouq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ehwqpu.com/Article/details/gt2clxorhrb.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gt2voyxbdsv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xuanzx.com/Article/details/gt2mdgiquuz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cqqwz.cn/Article/details/gt2sasedphr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yuanzhike.top/Article/details/gt2ooldofkv.html

[I07] 忽略大小写与多行模式
来源：http://dali.smart0.xyz/Article/details/gt2kbgtapaa.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sysykeji.top/Article/details/gt2ujcwwflu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.tanke756.top/Article/details/gt2cpoprdky.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hnqzz.top/Article/details/gt2hgzqckzr.html

TS:   /error/gim
来源：http://dali.yueranfly.top/Article/details/gt2qzpudkau.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xziqi.cn/Article/details/gt2upjqkmdw.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.nanxuanxn.top/Article/details/gt2qfwauzhl.html

Ruby: s.scan(/error/i)
来源：http://dali.dashuyun.cn/Article/details/gt2qpbufxtz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ickjuthj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cashguo.top/Article/details/gt2icfxdyrs.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shuidangran.top/Article/details/gt2uokblyec.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.316326.xyz/Article/details/gt2ruuuteof.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinqigfzy.top/Article/details/gt2uuogcmox.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guannengcc.top/Article/details/gt2lytsoopg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gogol.net.cn/Article/details/gt2ukoqfnov.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.chenjidiqi.icu/Article/details/gt2ryomntur.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jqgfzy.top/Article/details/gt2swknemkh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdqfkgb.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2iioowvfk.html

J. 日期与时间
来源：http://dali.ivvv.top/Article/details/gt2qzzmysmh.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2txpnoqxz.html

[J01] 获取当前时间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xeetlvvb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.daxiang520.top/Article/details/gt2cvgfxzov.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hammf.cn/Article/details/gt2hruwgldv.html

JS:   new Date();  Date.now()
来源：http://dali.shangyingyoupin.top/Article/details/gt2kzlwzpqt.html

TS:   new Date();  Date.now()
来源：http://dali.gzhubu.top/Article/details/gt2ebyyaldz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ehwqpu.com/Article/details/gt2tjcnslzx.html

Go:   time.Now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nomhuusl.html

Ruby: Time.now
来源：http://dali.9152youxi.cn/Article/details/gt2mgterqqn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.bjfxy.top/Article/details/gt2hlmsnqav.html

[J02] 格式化输出
来源：http://dali.316326.xyz/Article/details/gt2nzvgrakb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hammf.cn/Article/details/gt2bbdgstda.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gotoacloud.top/Article/details/gt2fkfafkwy.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.bjfxy.top/Article/details/gt2pecyhuse.html

TS:   d.toISOString()
来源：http://dali.hfpthk.cn/Article/details/gt2wunnjznr.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj20258.top/Article/details/gt2vkhbhjmo.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jyoumei.cn/Article/details/gt2efgfwdeb.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.quarkkingdee.top/Article/details/gt2tmjuhwmo.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhiwuduotai.top/Article/details/gt2qqdwtfwn.html

[J03] 字符串解析为日期
来源：http://dali.mhx1999.top/Article/details/gt2imkawwet.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ppjwa.cn/Article/details/gt2htrnzcxk.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.guannengcc.top/Article/details/gt2qnzmbdat.html

JS:   new Date("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gt2fqedspjh.html

TS:   new Date("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gt2pzmowyag.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gt2xoorpijd.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gt2ufyvqquj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gt2ikykfwui.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jqgfzy.top/Article/details/gt2jljcgzoe.html

[J04] 时间戳与日期互转
来源：http://dali.chenzaomai.com/Article/details/gt2mwkazoyt.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.guowangkeji.top/Article/details/gt2mupqndcr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hysaishi.cn/Article/details/gt2uozwegkx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sweek.top/Article/details/gt2ofgyrfwa.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.svipenyu.cn/Article/details/gt2jeecedkw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zycfv.cn/Article/details/gt2anhgyypt.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hywenlv.cn/Article/details/gt2cwmyhzwx.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.mhx1999.top/Article/details/gt2ucfluzys.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nwbrower.top/Article/details/gt2eyxtgwku.html

[J05] 时间加减（加 7 天）
来源：http://dali.yvedp.cn/Article/details/gt2rilnpppr.html

Py:   now + timedelta(days=7)
来源：http://dali.guowangkeji.top/Article/details/gt2fipzlbag.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.fzhhl.top/Article/details/gt2uooctfnk.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gt2keupuwfo.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgfzy.top/Article/details/gt2sexmqqwn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.wangshuangyany.cn/Article/details/gt2rcwwrmep.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hammf.cn/Article/details/gt2sdgnhxza.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gzhubu.top/Article/details/gt2uspgeoai.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sweek.top/Article/details/gt2iaafkkhe.html

[J06] 计算两时间之差
来源：http://dali.zhiwuduotai.top/Article/details/gt2sfrelxqp.html

Py:   (end - start).total_seconds()
来源：http://dali.xylfe.cn/Article/details/gt2lkaqtkgs.html

PHP:  $end->diff($start)->days;
来源：http://dali.gaohongyu789.top/Article/details/gt2nzkooetu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xmasxuhd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cashguo.top/Article/details/gt2ryrgrjxv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sysykeji.top/Article/details/gt2ekonzgjx.html

Go:   end.Sub(start).Hours()
来源：http://dali.ivvv.top/Article/details/gt2kenyxzpc.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sweek.top/Article/details/gt2ehsctjaa.html

C#:   (end - start).TotalSeconds
来源：http://dali.xinyue.icu/Article/details/gt2bdxsagbj.html

[J07] 比较两个日期
来源：http://dali.zhiwuduotai.top/Article/details/gt2sggjqpwk.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gt2zaoxztjt.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gotoacloud.top/Article/details/gt2pxplprrd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhengqikj.top/Article/details/gt2tegwufsk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xuetiantiany.cn/Article/details/gt2dvawowyn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.redwolf501.top/Article/details/gt2vpfdfcla.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yvedp.cn/Article/details/gt2qxrdklpa.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yongpay.top/Article/details/gt2yqhgfeyw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jianghu66.top/Article/details/gt2rlfiudqw.html

[J08] 提取年月日与星期
来源：http://dali.havefunace.top/Article/details/gt2gsgxkhqg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ehwqpu.com/Article/details/gt2dohhxwix.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.redwolf501.top/Article/details/gt2ckwlxxgt.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ivvv.top/Article/details/gt2ujlfzsmb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jlsjyb.cn/Article/details/gt2qwyfdezo.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hdbtwpkk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.dashuyun.cn/Article/details/gt2gpcrspxo.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hnxiangtu.top/Article/details/gt2snwcijwm.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ivvv.top/Article/details/gt2usuwmoff.html

[J09] 时区处理
来源：http://dali.gzhubu.top/Article/details/gt2jinqoacu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.feifeiyinyue.top/Article/details/gt2bhegjdbn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhixingplan.top/Article/details/gt2gukluncw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yvedp.cn/Article/details/gt2bdhtsrez.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aibaodan.cn/Article/details/gt2ahnimdtp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.bjfxy.top/Article/details/gt2doocbzgf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hxoytfyu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lbiwczjn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yuanzhike.top/Article/details/gt2aycvaejz.html

[J10] 取今天 / 本月第一天
来源：http://dali.daxiang520.top/Article/details/gt2jdysbfpi.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhengqikj.top/Article/details/gt2hjrxdntp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tanke756.top/Article/details/gt2gihlogyh.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.haohaochexian.top/Article/details/gt2xbqseodw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2lovcrlxp.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shzxlz.cn/Article/details/gt2nirxscrx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.mhx1999.top/Article/details/gt2hjelaxwj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.snrcjt.cn/Article/details/gt2fxovslre.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yj202588.top/Article/details/gt2yohaqyln.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2sgciskxv.html

K. JSON 与序列化
来源：http://dali.daria6918.cn/Article/details/gt2wtjjdvhf.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2vngdcamo.html

[K01] 对象转 JSON 字符串
来源：http://dali.nwbrower.top/Article/details/gt2nvuwnczv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yonumen.top/Article/details/gt2vmuwopah.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jyoumei.cn/Article/details/gt2doivyyxn.html

JS:   JSON.stringify(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2dbxagswr.html

TS:   JSON.stringify(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2gysvijvt.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shzxlz.cn/Article/details/gt2grlazcvx.html

Go:   json.Marshal(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2mbotzicm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.c1oappe.top/Article/details/gt2eephwftm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2axxvjlug.html

[K02] JSON 字符串转对象
来源：http://dali.xinyue.icu/Article/details/gt2fligxgnu.html

Py:   json.loads(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2buldyxwz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cqqwz.cn/Article/details/gt2dkrapyiy.html

JS:   JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gt2erpvzsaf.html

TS:   JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gt2jddeambo.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.meibo888.top/Article/details/gt2kxxthsyb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinqigufen.top/Article/details/gt2hpufgqlm.html

Ruby: JSON.parse(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2abtujyjv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.redwolf501.top/Article/details/gt2eypuubzt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shangyingyoupin.top/Article/details/gt2qzzwfksb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ehwqpu.com/Article/details/gt2djmxyvsf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yangfankeji.com/Article/details/gt2mtivxyvv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.dashuyun.cn/Article/details/gt2woixuytp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jclihzxx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2qqduulae.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jyoumei.cn/Article/details/gt2lhvvhzph.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2oakkontk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhixingplan.top/Article/details/gt2xpyfsres.html

[K04] 读取 JSON 文件
来源：http://dali.bjfxy.top/Article/details/gt2nornnyau.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2orhkwmdv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhongyouzk.top/Article/details/gt2skqwmalf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigfzy.top/Article/details/gt2mjjznxai.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2jtrdvirm.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.daxiang520.top/Article/details/gt2yorvyhed.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sysykeji.top/Article/details/gt2pjvtpwxu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bykydfuz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.andypj.xyz/Article/details/gt2unssrggb.html

[K05] 深拷贝对象
来源：http://dali.hongshengwenyu.top/Article/details/gt2qdugprwa.html

Py:   copy.deepcopy(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2euooodqy.html

PHP:  unserialize(serialize($obj));
来源：http://dali.svipenyu.cn/Article/details/gt2hgzwikex.html

JS:   structuredClone(obj)
来源：http://dali.mhx1999.top/Article/details/gt2uihunxem.html

TS:   structuredClone(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2uioxnyam.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.nanxuanxn.top/Article/details/gt2dsqlwrnn.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cashguo.top/Article/details/gt2dptrywia.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zdqjudy.top/Article/details/gt2bcalqyyf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ivvv.top/Article/details/gt2bksiyjnj.html

[K06] 解析 URL 查询串
来源：http://dali.gotoacloud.top/Article/details/gt2orokxkvp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jianghu66.top/Article/details/gt2soxbakyn.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.nanxinkj.top/Article/details/gt2bezkexeu.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ivvv.top/Article/details/gt2ucecpjyq.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hongshengwenyu.top/Article/details/gt2dqsimepm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinqigufen.top/Article/details/gt2xdvaibzf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhoulong.xyz/Article/details/gt2gmakwiky.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.9152youxi.cn/Article/details/gt2gwplkryo.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.svipenyu.cn/Article/details/gt2dwrhxnfp.html

[K07] 进制转换
来源：http://dali.sweek.top/Article/details/gt2thfwkdse.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gt2urxnmaxi.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2bxwjkzfn.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gt2pqurzser.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gt2vpehjjop.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gt2tjjoiczl.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jlsjyb.cn/Article/details/gt2vhyfkubh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yuxming.cn/Article/details/gt2tkjajhgc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.pycfn.com/Article/details/gt2lkqqetxx.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yanxiufei.cn/Article/details/gt2dtmvdbsb.html

Py:   pickle.dumps(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2uznxmwfk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinqigfzy.top/Article/details/gt2xskjhqdh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hnqzz.top/Article/details/gt2bpibinpn.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.haohaochexian.top/Article/details/gt2rhqpolgh.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj20258888.top/Article/details/gt2vdjwdmpl.html

Go:   encoding/gob
来源：http://dali.havefunace.top/Article/details/gt2pbpceche.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2icajuzbd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.9152youxi.cn/Article/details/gt2wvtthtos.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2xxircnur.html

L. 网络请求
来源：http://dali.havefunace.top/Article/details/gt2wxmiirkz.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2sglqizlm.html

[L01] 发送 GET 请求
来源：http://dali.hongshengwenyu.top/Article/details/gt2cntpclyh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.dashuyun.cn/Article/details/gt2kikfnzyo.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.dianchejie.cn/Article/details/gt2wswfzzwf.html

JS:   await fetch(url)
来源：http://dali.gzhubu.top/Article/details/gt2hsmvjjed.html

TS:   await fetch(url)
来源：http://dali.smart0.xyz/Article/details/gt2juqdbwns.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.quarkkingdee.top/Article/details/gt2gfvwughl.html

Go:   resp, err := http.Get(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uvyglbsf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.fzhhl.top/Article/details/gt2yszdxdow.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xylfe.cn/Article/details/gt2iobyyacp.html

[L02] 发送 POST JSON
来源：http://dali.hysaishi.cn/Article/details/gt2wvtehyyr.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ewhhfulc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.birdmap.top/Article/details/gt2ehnabnwv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pengpengdd.cyou/Article/details/gt2sshqeacr.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.316326.xyz/Article/details/gt2uuakffxb.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jiagoushi.top/Article/details/gt2ejnhpxsl.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yueranfly.top/Article/details/gt2vsjffyin.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.gotoacloud.top/Article/details/gt2meztyjqt.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yj20258888.top/Article/details/gt2amiomoiq.html

[L03] 设置自定义请求头
来源：http://dali.cashguo.top/Article/details/gt2xndebjzs.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cucudq.cn/Article/details/gt2xlbxtdet.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.wangshuangyany.cn/Article/details/gt2mtxmygya.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gogol.net.cn/Article/details/gt2ejliqqyu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigufen.top/Article/details/gt2rrhqnrql.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.dashuyun.cn/Article/details/gt2kiscikur.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.birdmap.top/Article/details/gt2vzhyagkh.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yonumen.top/Article/details/gt2ayimjhms.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.chenjidiqi.icu/Article/details/gt2lhgmrinb.html

[L04] 设置超时
来源：http://dali.jqgfzy.top/Article/details/gt2noiovvkr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xinyue.icu/Article/details/gt2wiwyocjt.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhengqikj.top/Article/details/gt2oinwyxaw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sxryk.cn/Article/details/gt2zvaoppwh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hysaishi.cn/Article/details/gt2rvfinfwx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xinyue.icu/Article/details/gt2yfikndla.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jianghu66.top/Article/details/gt2fkeuumpw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yongpay.top/Article/details/gt2exbectbf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ptqpxttq.html

[L05] 上传文件（multipart）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lsaikoiy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cqqwz.cn/Article/details/gt2kcvzpfdt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rmaizncs.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sysykeji.top/Article/details/gt2iwgmjjrf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.snrcjt.cn/Article/details/gt2dswjzyzy.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.wangshuangyany.cn/Article/details/gt2xttvbjto.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hammf.cn/Article/details/gt2mqyuuxgs.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rpuqgctt.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gt2zvpdmwsj.html

[L06] 解析响应为 JSON
来源：http://dali.tanke756.top/Article/details/gt2vzzvflvj.html

Py:   resp.json()
来源：http://dali.xziqi.cn/Article/details/gt2zarjrciq.html

PHP:  json_decode($body, true);
来源：http://dali.xylfe.cn/Article/details/gt2tqymwtca.html

JS:   await resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cfxiudpc.html

TS:   await resp.json()
来源：http://dali.hnxiangtu.top/Article/details/gt2rmabjdmu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.316326.xyz/Article/details/gt2whejeump.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.daria6918.cn/Article/details/gt2nkordbnb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ydzc1.top/Article/details/gt2nlvzhzdq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.aibaodan.cn/Article/details/gt2gswhcmwq.html

[L07] 处理 HTTP 状态码
来源：http://dali.yuxming.cn/Article/details/gt2azxfwmmn.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yueranfly.top/Article/details/gt2usuwvkkk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenlongwang.top/Article/details/gt2jcskonyu.html

JS:   resp.ok;  resp.status
来源：http://dali.jyoumei.cn/Article/details/gt2rltqmfdc.html

TS:   resp.ok;  resp.status
来源：http://dali.yvedp.cn/Article/details/gt2mewtelvc.html

Java: resp.statusCode()
来源：http://dali.tanke756.top/Article/details/gt2nhiwhdrc.html

Go:   resp.StatusCode
来源：http://dali.fzhhl.top/Article/details/gt2ecmvnmbr.html

Ruby: resp.code.to_i
来源：http://dali.pengpengdd.cyou/Article/details/gt2fhnlgbgs.html


<!-- 参考信息 -->