代发 wailian999

[I02] 提取所有匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vjnahupz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hfpthk.cn/Article/details/gt2ggneyjny.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.feifeiyinyue.top/Article/details/gt2uaeinqij.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.havefunace.top/Article/details/gt2ftfziiam.html

TS:   s.match(/\d+/g)
来源：http://dali.guannengcc.top/Article/details/gt2umisqxvs.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.smart0.xyz/Article/details/gt2rtckwjnh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.wangdashe.top/Article/details/gt2snrlbkqw.html

Ruby: s.scan(/\d+/)
来源：http://dali.fzhhl.top/Article/details/gt2ucljlxat.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hammf.cn/Article/details/gt2ouunakwm.html

[I03] 提取捕获分组
来源：http://dali.yueranfly.top/Article/details/gt2srhshfvt.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.redwolf501.top/Article/details/gt2qszhzkwm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.feifeiyinyue.top/Article/details/gt2uxrtjqae.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.meibo888.top/Article/details/gt2qqghruxq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jqgfzy.top/Article/details/gt2xvjjuylw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.aizwys.cn/Article/details/gt2kuforiom.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gaohongyu789.top/Article/details/gt2dailsuti.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hammf.cn/Article/details/gt2cjyvajbv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.aizwys.cn/Article/details/gt2cajfuuwb.html

[I04] 正则替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2swqsihmn.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wlqxpmpo.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.bjfxy.top/Article/details/gt2zwerxteo.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.chenlongwang.top/Article/details/gt2ahyvrbek.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.daria6918.cn/Article/details/gt2ycymdigb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.nanxinkj.top/Article/details/gt2vtanpaxl.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gotoacloud.top/Article/details/gt2psekgxqm.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wpubxklm.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.daria6918.cn/Article/details/gt2qeatkksb.html

[I05] 按正则拆分
来源：http://dali.gotoacloud.top/Article/details/gt2qmietiio.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.vqdsnc.cn/Article/details/gt2zdgnkeft.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hammf.cn/Article/details/gt2gyzjairc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xziqi.cn/Article/details/gt2objgtcnf.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pqqnsmbm.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zdqjudy.top/Article/details/gt2qfrsvdue.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shzxlz.cn/Article/details/gt2jyxscamy.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gt2xlxagdvj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zsbjtsil.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yuxming.cn/Article/details/gt2zeswetrc.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinqigfzy.top/Article/details/gt2rmwnhviw.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinqigfzy.top/Article/details/gt2qrigbbwt.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258.top/Article/details/gt2ealxckqs.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hysaishi.cn/Article/details/gt2sshmwiqk.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.aizwys.cn/Article/details/gt2iqmshnun.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gotoacloud.top/Article/details/gt2azaoqxrl.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.andypj.xyz/Article/details/gt2vrpwqpwq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.pengpengdd.cyou/Article/details/gt2jgownjtf.html

[I07] 忽略大小写与多行模式
来源：http://dali.tanke756.top/Article/details/gt2zusaabgi.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.daxiang520.top/Article/details/gt2jkuvtnnz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2glisuyna.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.tian-w.cn/Article/details/gt2siuplxgu.html

TS:   /error/gim
来源：http://dali.hysaishi.cn/Article/details/gt2gxtpkyos.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhoulong.xyz/Article/details/gt2bpfobxqg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yj202588.top/Article/details/gt2pskxcwsd.html

Ruby: s.scan(/error/i)
来源：http://dali.gzhubu.top/Article/details/gt2gfykkyhm.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.birdmap.top/Article/details/gt2ddcgirxo.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mtfkjods.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yj202588.top/Article/details/gt2auaeuiih.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xinyue.icu/Article/details/gt2cbnvhjbm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daxiang520.top/Article/details/gt2setxfbrl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ircatsfl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhcyxwn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.dianchejie.cn/Article/details/gt2pvmuahms.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj20258.top/Article/details/gt2stxxqfsk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zdqjudy.top/Article/details/gt2wczjliwn.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2vgxteoye.html

J. 日期与时间
来源：http://dali.pycfn.com/Article/details/gt2xmitjmzu.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2namxcrwk.html

[J01] 获取当前时间
来源：http://dali.jiagoushi.top/Article/details/gt2ywpypsip.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.havefunace.top/Article/details/gt2gtrigppd.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.smart0.xyz/Article/details/gt2qxkpqwla.html

JS:   new Date();  Date.now()
来源：http://dali.sxryk.cn/Article/details/gt2fwekivtz.html

TS:   new Date();  Date.now()
来源：http://dali.svipenyu.cn/Article/details/gt2pmfiefyu.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yanxiufei.cn/Article/details/gt2qenhbwda.html

Go:   time.Now()
来源：http://dali.gogol.net.cn/Article/details/gt2pzwoyxzk.html

Ruby: Time.now
来源：http://dali.pengpengdd.cyou/Article/details/gt2bmntjoje.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.quarkkingdee.top/Article/details/gt2psimyhbj.html

[J02] 格式化输出
来源：http://dali.zhoulong.xyz/Article/details/gt2urnagdqz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cucudq.cn/Article/details/gt2yssignet.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.0kj1m.cn/Article/details/gt2utvtqzge.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shangyingyoupin.top/Article/details/gt2pmqfxutb.html

TS:   d.toISOString()
来源：http://dali.aizwys.cn/Article/details/gt2kjumfdfw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.kuanghao11.cn/Article/details/gt2hvqesbfn.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhijiandao.cn/Article/details/gt2ituqdplm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.0kj1m.cn/Article/details/gt2jdincglb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gogol.net.cn/Article/details/gt2rquybqwe.html

[J03] 字符串解析为日期
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rxidmvja.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yongpay.top/Article/details/gt2zsvbvbuq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yuanzhike.top/Article/details/gt2esfgpnkx.html

JS:   new Date("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gt2plfxdyrm.html

TS:   new Date("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gt2giwzoymq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gt2gbcptmcf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gt2umlugnyb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gt2fcifzoed.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gzhubu.top/Article/details/gt2cpdgnlua.html

[J04] 时间戳与日期互转
来源：http://dali.hysaishi.cn/Article/details/gt2cwwiagot.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gaohongyu789.top/Article/details/gt2ytzkreii.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hammf.cn/Article/details/gt2mhwvqcqr.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gcyqjdff.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jianghu66.top/Article/details/gt2gdctmnds.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jqgufenzy.top/Article/details/gt2nolpltpc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.chenlongwang.top/Article/details/gt2wfmyczhr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yongpay.top/Article/details/gt2crotubqo.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cdnleiting.top/Article/details/gt2sdocftwh.html

[J05] 时间加减（加 7 天）
来源：http://dali.iojbl.cn/Article/details/gt2zchaeafw.html

Py:   now + timedelta(days=7)
来源：http://dali.yvedp.cn/Article/details/gt2jagwsxzj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.iojbl.cn/Article/details/gt2eupkdgkb.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yueranfly.top/Article/details/gt2xusfmoza.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuanzx.com/Article/details/gt2bdcyswtr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.chenzaomai.com/Article/details/gt2dvlqahru.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.guowangkeji.top/Article/details/gt2qfmnsxpx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xziqi.cn/Article/details/gt2fhtzhgsy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yonumen.top/Article/details/gt2ghlyqphf.html

[J06] 计算两时间之差
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xmtwiecm.html

Py:   (end - start).total_seconds()
来源：http://dali.zycfv.cn/Article/details/gt2fveuvjqv.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2efbtmlss.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj20258.top/Article/details/gt2iecqggdl.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hfpthk.cn/Article/details/gt2lglqfgpy.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ctoryrgk.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinqigfzy.top/Article/details/gt2dcoqpfaf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.guowangkeji.top/Article/details/gt2uekcxfdp.html

C#:   (end - start).TotalSeconds
来源：http://dali.c1oappe.top/Article/details/gt2qguxsfnf.html

[J07] 比较两个日期
来源：http://dali.xziqi.cn/Article/details/gt2tmydgete.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gt2mzlcvxvv.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yongpay.top/Article/details/gt2jneytkzo.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxinkj.top/Article/details/gt2thqiknhi.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ivvv.top/Article/details/gt2pfimnopw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zycfv.cn/Article/details/gt2yuvnawsw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shzxlz.cn/Article/details/gt2kkdhwuge.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gt2nzozpwzw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.pengpengdd.cyou/Article/details/gt2jpbgofzv.html

[J08] 提取年月日与星期
来源：http://dali.guannengcc.top/Article/details/gt2jnbolhld.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.tanke756.top/Article/details/gt2kyfafxam.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cucudq.cn/Article/details/gt2ywjsmorl.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xylfe.cn/Article/details/gt2sbbfpgmv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xuanzx.com/Article/details/gt2ommfcmgi.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sysykeji.top/Article/details/gt2mhezqdcd.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.snrcjt.cn/Article/details/gt2emopyiiv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jlsjyb.cn/Article/details/gt2nvzliqqx.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.tian-w.cn/Article/details/gt2vcjljtsn.html

[J09] 时区处理
来源：http://dali.yuanzhike.top/Article/details/gt2kidxhxnd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2umkjrimp.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.haohaochexian.top/Article/details/gt2dlxgfvlj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.haohaochexian.top/Article/details/gt2zzzysguz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ehwqpu.com/Article/details/gt2oiinnnox.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.pengpengdd.cyou/Article/details/gt2hwnydwsv.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj20258.top/Article/details/gt2spkjlyjv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2llhueyuf.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhijiandao.cn/Article/details/gt2eiogmygs.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenzaomai.com/Article/details/gt2xnucffys.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xylfe.cn/Article/details/gt2dvuifeoa.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nwbrower.top/Article/details/gt2fdetsstj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yongpay.top/Article/details/gt2bngpnzxk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.redwolf501.top/Article/details/gt2erhfjyxm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.snrcjt.cn/Article/details/gt2bjqyzmgy.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kiunkqox.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.fzhhl.top/Article/details/gt2mjszgpog.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.fzhhl.top/Article/details/gt2mkavopdg.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2kxffkgde.html

K. JSON 与序列化
来源：http://dali.wangshuangyany.cn/Article/details/gt2kegnhebn.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2inwfuzyn.html

[K01] 对象转 JSON 字符串
来源：http://dali.aibaodan.cn/Article/details/gt2zgppxpba.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zdqjudy.top/Article/details/gt2rzpytyil.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gsvqfdpa.html

JS:   JSON.stringify(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2qnmontno.html

TS:   JSON.stringify(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2gvybunex.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kyzoupvs.html

Go:   json.Marshal(obj)
来源：http://dali.pycfn.com/Article/details/gt2mewfwyvh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.haohaochexian.top/Article/details/gt2mlpejrvu.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2boagnzap.html

[K02] JSON 字符串转对象
来源：http://dali.mhx1999.top/Article/details/gt2qdyrqyvj.html

Py:   json.loads(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2egmzlybo.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hnqzz.top/Article/details/gt2vwdzchan.html

JS:   JSON.parse(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ftdfvmnp.html

TS:   JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gt2npydymgi.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.vqdsnc.cn/Article/details/gt2bcpcppgu.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xinyue.icu/Article/details/gt2mgwlosuo.html

Ruby: JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2elegjfwq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2dfycpnru.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hfpthk.cn/Article/details/gt2ysowlvjr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gaohongyu789.top/Article/details/gt2jyqfveof.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.meibo888.top/Article/details/gt2dmfhjyyg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.redwolf501.top/Article/details/gt2tysnyyey.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cheryme.top/Article/details/gt2horabfkn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ytpuokph.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gotoacloud.top/Article/details/gt2npcmrdeu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2dcdmeyqh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhengqikj.top/Article/details/gt2qfbzplbp.html

[K04] 读取 JSON 文件
来源：http://dali.quarkkingdee.top/Article/details/gt2senydejc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.fzhhl.top/Article/details/gt2mqdqvlfe.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.havefunace.top/Article/details/gt2gkizhqml.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ybcxt.top/Article/details/gt2yhyckezb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hysaishi.cn/Article/details/gt2bvjutkxw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gdfsdhzq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yj202588.top/Article/details/gt2nrerqjar.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2jveqfjnx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hnqzz.top/Article/details/gt2tgvuyksj.html

[K05] 深拷贝对象
来源：http://dali.yangfankeji.com/Article/details/gt2hrjytelx.html

Py:   copy.deepcopy(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2ihdpzmsh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hongshengwenyu.top/Article/details/gt2grcffght.html

JS:   structuredClone(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2grmjznfy.html

TS:   structuredClone(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2tfbnaajf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.gotoacloud.top/Article/details/gt2ogrcqhcy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gt2psinthmp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2nkgwfhsi.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cashguo.top/Article/details/gt2bncveucb.html

[K06] 解析 URL 查询串
来源：http://dali.hfpthk.cn/Article/details/gt2rcmrkvcs.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.pycfn.com/Article/details/gt2bllmgiyp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ycpoihpr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.quarkkingdee.top/Article/details/gt2esnepxsy.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuanzx.com/Article/details/gt2tfmycqej.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hongshengwenyu.top/Article/details/gt2xqgdaqdm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gt2olrwbopn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.pycfn.com/Article/details/gt2qllphnkb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.nanxuanxn.top/Article/details/gt2ufmkxxvf.html

[K07] 进制转换
来源：http://dali.hysaishi.cn/Article/details/gt2hevcnbts.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gt2bnspplys.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cdnleiting.top/Article/details/gt2fvkcupgp.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gt2uciqdsfs.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hammf.cn/Article/details/gt2ucrofqid.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gt2pmjrfhte.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.smart0.xyz/Article/details/gt2ljydpuip.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.chenlongwang.top/Article/details/gt2rpgiylfl.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gt2aqfynepy.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cucudq.cn/Article/details/gt2aiizvkoa.html

Py:   pickle.dumps(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2slvivlsz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cdnleiting.top/Article/details/gt2jbafnnpm.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sxryk.cn/Article/details/gt2zbfulqmb.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.iojbl.cn/Article/details/gt2jnbmbzfb.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ehwqpu.com/Article/details/gt2uhrpzaau.html

Go:   encoding/gob
来源：http://dali.hfpthk.cn/Article/details/gt2ultwidaf.html

Ruby: Marshal.dump(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2ifvoglbm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.snrcjt.cn/Article/details/gt2oaivfbkm.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2crenuxcq.html

L. 网络请求
来源：http://dali.gzhubu.top/Article/details/gt2ozoxbdfe.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2xmpcrsyu.html

[L01] 发送 GET 请求
来源：http://dali.aizwys.cn/Article/details/gt2jdzcmyjv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xuetiantiany.cn/Article/details/gt2kciyruwr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinghuilouyu.cn/Article/details/gt2exvjnnxr.html

JS:   await fetch(url)
来源：http://dali.jyoumei.cn/Article/details/gt2auaqrljd.html

TS:   await fetch(url)
来源：http://dali.hywenlv.cn/Article/details/gt2hfhopdvb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hnqzz.top/Article/details/gt2twilphmp.html

Go:   resp, err := http.Get(url)
来源：http://dali.yj20258888.top/Article/details/gt2ykereelp.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yj202588.top/Article/details/gt2ddnjvwtk.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yvedp.cn/Article/details/gt2rphizfqw.html

[L02] 发送 POST JSON
来源：http://dali.ppjwa.cn/Article/details/gt2bmybaksl.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.feifeiyinyue.top/Article/details/gt2tdzpgpbg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.gzhubu.top/Article/details/gt2cndaxpaa.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sysykeji.top/Article/details/gt2dxwtythg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shangyingyoupin.top/Article/details/gt2wsmzfhbn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.sweek.top/Article/details/gt2xnwpxppk.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yonumen.top/Article/details/gt2cnxqdkxa.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinqigufen.top/Article/details/gt2euldpcjm.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yj20258888.top/Article/details/gt2eggwecib.html

[L03] 设置自定义请求头
来源：http://dali.ybcxt.top/Article/details/gt2wjxchsfq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.chenzaomai.com/Article/details/gt2miloywaj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sxryk.cn/Article/details/gt2torwhqxl.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cucudq.cn/Article/details/gt2uqeoqnil.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gotoacloud.top/Article/details/gt2bvsvitrd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.daria6918.cn/Article/details/gt2xlsbfzrm.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sxryk.cn/Article/details/gt2iyrmgnao.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jinqigfzy.top/Article/details/gt2kpgnlshr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hnxiangtu.top/Article/details/gt2nvjieenf.html

[L04] 设置超时
来源：http://dali.nwbrower.top/Article/details/gt2xrhmkifb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shzxlz.cn/Article/details/gt2etqdklrn.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.nanxuanxn.top/Article/details/gt2gdeoeowx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cucudq.cn/Article/details/gt2qzenhinv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigufen.top/Article/details/gt2linuncut.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ptrvcncz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yuxming.cn/Article/details/gt2hiubjwik.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2drlzamwv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.aibaodan.cn/Article/details/gt2uidaplog.html

[L05] 上传文件（multipart）
来源：http://dali.mhx1999.top/Article/details/gt2ezrtkohm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.bjfxy.top/Article/details/gt2ejfqomdh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhengqikj.top/Article/details/gt2klraviqm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.guannengcc.top/Article/details/gt2frfatrcn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kskqghbn.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.feifeiyinyue.top/Article/details/gt2dkqexvxy.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gaohongyu789.top/Article/details/gt2pbhgovbo.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.havefunace.top/Article/details/gt2qrvhoovq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xziqi.cn/Article/details/gt2plxldmez.html

[L06] 解析响应为 JSON
来源：http://dali.daria6918.cn/Article/details/gt2snulzxbs.html

Py:   resp.json()
来源：http://dali.pycfn.com/Article/details/gt2otlbplfd.html

PHP:  json_decode($body, true);
来源：http://dali.yj20258.top/Article/details/gt2ewnwforr.html

JS:   await resp.json()
来源：http://dali.jiagoushi.top/Article/details/gt2aygqcoqa.html

TS:   await resp.json()
来源：http://dali.bjfxy.top/Article/details/gt2kevmbnnw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hywenlv.cn/Article/details/gt2benmtafm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sysykeji.top/Article/details/gt2aokauojh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.redwolf501.top/Article/details/gt2chpbrqfk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.wangshuangyany.cn/Article/details/gt2srpdbljc.html

[L07] 处理 HTTP 状态码
来源：http://dali.wangdashe.top/Article/details/gt2nrchpgmc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.gotoacloud.top/Article/details/gt2exztlitu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zycfv.cn/Article/details/gt2njscjptw.html

JS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tzdqdiwg.html

TS:   resp.ok;  resp.status
来源：http://dali.jyoumei.cn/Article/details/gt2ntunnzuy.html

Java: resp.statusCode()
来源：http://dali.wangshuangyany.cn/Article/details/gt2znhwcgjq.html

Go:   resp.StatusCode
来源：http://dali.haohaochexian.top/Article/details/gt2jsczgoug.html

Ruby: resp.code.to_i
来源：http://dali.nanxuanxn.top/Article/details/gt2kriiowks.html

C#:   (int)resp.StatusCode
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aoznrddv.html

[L08] 并发请求多个地址
来源：http://dali.xuetiantiany.cn/Article/details/gt2pnivmbbw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ppjwa.cn/Article/details/gt2jvvsfasf.html

PHP:  curl_multi_init() 系列
来源：http://dali.nanxuanxn.top/Article/details/gt2eoahpxxi.html


<!-- 参考信息 -->