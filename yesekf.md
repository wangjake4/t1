代发 wailian999

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdyeomwll.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yvedp.cn/Article/details/gtguvilodq.html

JS:   /\d+/.test(s)
来源：http://dali.sweek.top/Article/details/gtacbrtvjb.html

TS:   /\d+/.test(s)
来源：http://dali.sxryk.cn/Article/details/gtehpxxwuj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.fzhhl.top/Article/details/gtxeorncht.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinqigfzy.top/Article/details/gtrjtlixjv.html

Ruby: s.match?(/\d+/)
来源：http://dali.yonumen.top/Article/details/gtdairydkt.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yj20258.top/Article/details/gtxxsbnoxj.html

[I02] 提取所有匹配
来源：http://dali.hywenlv.cn/Article/details/gtgxzrzebp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.haohaochexian.top/Article/details/gtwfmzoblf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jianghu66.top/Article/details/gtjfobymdv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sweek.top/Article/details/gttfvzfqgx.html

TS:   s.match(/\d+/g)
来源：http://dali.gotoacloud.top/Article/details/gtgwcxkwmo.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.andypj.xyz/Article/details/gteplinmxa.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gtziqwptrb.html

Ruby: s.scan(/\d+/)
来源：http://dali.hnxiangtu.top/Article/details/gtjhbiiiew.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtzhjdjfjj.html

[I03] 提取捕获分组
来源：http://dali.zdqjudy.top/Article/details/gtwbvnqzhf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.dianchejie.cn/Article/details/gtzqnndfbv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.fengsongda.top/Article/details/gttggkanqw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yvedp.cn/Article/details/gteggxpulj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.nanxuanxn.top/Article/details/gtzydsfxfl.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.aibaodan.cn/Article/details/gtwizziidt.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.9152youxi.cn/Article/details/gtrjrikwie.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xuanzx.com/Article/details/gtbakavakt.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shangyingyoupin.top/Article/details/gtfpvhiysb.html

[I04] 正则替换
来源：http://dali.guannengcc.top/Article/details/gtdvefxorm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shangyingyoupin.top/Article/details/gtvyuyfxkw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.9152youxi.cn/Article/details/gtbuzouvdq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxinkj.top/Article/details/gtrcjtteix.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.tian-w.cn/Article/details/gtrewlcaig.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.daria6918.cn/Article/details/gtnnxxwhno.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtgnjtsscu.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtukeazpzd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.daria6918.cn/Article/details/gtdabrylic.html

[I05] 按正则拆分
来源：http://dali.hongshengwenyu.top/Article/details/gtdfptsbez.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yanxiufei.cn/Article/details/gtntibjpos.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.svipenyu.cn/Article/details/gtidtxvqvf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjzkkalec.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.wangdashe.top/Article/details/gtoqlkbrge.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sysykeji.top/Article/details/gtmlhfcipr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.guannengcc.top/Article/details/gtdtbeegya.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.chenjidiqi.icu/Article/details/gtffbfexxk.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.chenzaomai.com/Article/details/gtepayegko.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhixingplan.top/Article/details/gtajimkbkr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ivvv.top/Article/details/gtmykunccw.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenjidiqi.icu/Article/details/gtffqzsifn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gaohongyu789.top/Article/details/gtvupennez.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daxiang520.top/Article/details/gthtghefsm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gzhubu.top/Article/details/gtturcmvyr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xziqi.cn/Article/details/gticgcaltm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.tianlin.xyz/Article/details/gtagqwosqt.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gtkzjeuakm.html

[I07] 忽略大小写与多行模式
来源：http://dali.yuxming.cn/Article/details/gtdiylucvs.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xylfe.cn/Article/details/gtpgjgkajb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.aibaodan.cn/Article/details/gtpqaevnzs.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xylfe.cn/Article/details/gtzthanjvj.html

TS:   /error/gim
来源：http://dali.shuidangran.top/Article/details/gtlqusuitd.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.birdmap.top/Article/details/gtefsvxaim.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.tianlin.xyz/Article/details/gtsqcwdtvx.html

Ruby: s.scan(/error/i)
来源：http://dali.daria6918.cn/Article/details/gtheqhatjj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yueranfly.top/Article/details/gtzwiaydwv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.bjfxy.top/Article/details/gtnwnqkyed.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.snrcjt.cn/Article/details/gtbjiiknkq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinqigfzy.top/Article/details/gtwbfmfqik.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yangfankeji.com/Article/details/gtkmthceje.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.snrcjt.cn/Article/details/gtacwqwbva.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tanke756.top/Article/details/gtlnlwmrwe.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xuetiantiany.cn/Article/details/gtvulqbopt.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jlsjyb.cn/Article/details/gtetnxfywz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.daria6918.cn/Article/details/gtakrxggdi.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtpgiyeebh.html

J. 日期与时间
来源：http://dali.yj202588.top/Article/details/gteabksfyv.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtqpwwruzj.html

[J01] 获取当前时间
来源：http://dali.hywenlv.cn/Article/details/gtcajmmvxu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hywenlv.cn/Article/details/gtafcvgosh.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yuanzhike.top/Article/details/gtiejphyem.html

JS:   new Date();  Date.now()
来源：http://dali.yj202588.top/Article/details/gtdrlurzev.html

TS:   new Date();  Date.now()
来源：http://dali.snrcjt.cn/Article/details/gtanwtylqr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhiwuduotai.top/Article/details/gtbiieabdl.html

Go:   time.Now()
来源：http://dali.sysykeji.top/Article/details/gtbbjgrsxw.html

Ruby: Time.now
来源：http://dali.sufxvd.cn/Article/details/gteftzyzmw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.wangdashe.top/Article/details/gtjyyqnfka.html

[J02] 格式化输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gtejeuqgdd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.quarkkingdee.top/Article/details/gtdnxtealr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shanyushiyangtech.top/Article/details/gtttdvknkk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hammf.cn/Article/details/gtfwdvkexf.html

TS:   d.toISOString()
来源：http://dali.gogol.net.cn/Article/details/gtmxbdbdqd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.pengpengdd.cyou/Article/details/gtkbfiryzy.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.smart0.xyz/Article/details/gtpuntweiz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shangyingyoupin.top/Article/details/gttvgizmwb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.dianchejie.cn/Article/details/gtaovzydvu.html

[J03] 字符串解析为日期
来源：http://dali.guannengcc.top/Article/details/gtctnmcxao.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.pengpengdd.cyou/Article/details/gttvpcykcj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yuxming.cn/Article/details/gtepdggsfp.html

JS:   new Date("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtwtpmrewc.html

TS:   new Date("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gtroygjmzv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gtobesindn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gtmddbiydv.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gthefwnlbx.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhijiandao.cn/Article/details/gtalmfwcqj.html

[J04] 时间戳与日期互转
来源：http://dali.nwbrower.top/Article/details/gtjzenvdww.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.316326.xyz/Article/details/gtnwufjbjf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhengqikj.top/Article/details/gttjibpmml.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.chenjidiqi.icu/Article/details/gtsribljyn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.redwolf501.top/Article/details/gtvmqldpmx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xziqi.cn/Article/details/gtasjzuhle.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ybcxt.top/Article/details/gtbxsujohv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.iojbl.cn/Article/details/gtqkzhwrep.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yonumen.top/Article/details/gtiqvsxvdn.html

[J05] 时间加减（加 7 天）
来源：http://dali.ppjwa.cn/Article/details/gtsbzguzkc.html

Py:   now + timedelta(days=7)
来源：http://dali.cucudq.cn/Article/details/gttwtunlhk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.chenlongwang.top/Article/details/gtdmrsagtf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuanzx.com/Article/details/gttrqawtiu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cashguo.top/Article/details/gtlwmwuwmw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cqqwz.cn/Article/details/gtsnyrcyfu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xuanzx.com/Article/details/gtmdcwwquv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cqqwz.cn/Article/details/gtykckhkar.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.pengpengdd.cyou/Article/details/gtqwczxegn.html

[J06] 计算两时间之差
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmswgixra.html

Py:   (end - start).total_seconds()
来源：http://dali.hysaishi.cn/Article/details/gtzlhbzprz.html

PHP:  $end->diff($start)->days;
来源：http://dali.yuxming.cn/Article/details/gtghnknrjq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jqgufenzy.top/Article/details/gtskrnljws.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.vqdsnc.cn/Article/details/gtndbemaaa.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zycfv.cn/Article/details/gtnypliddn.html

Go:   end.Sub(start).Hours()
来源：http://dali.ybcxt.top/Article/details/gtewgikzmh.html

Ruby: end - start                 # 返回秒数
来源：http://dali.mhx1999.top/Article/details/gtlvyjbhto.html

C#:   (end - start).TotalSeconds
来源：http://dali.yonumen.top/Article/details/gtaotidwwt.html

[J07] 比较两个日期
来源：http://dali.chenjidiqi.icu/Article/details/gtnmjtifrz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jqgfzy.top/Article/details/gtcjrwicna.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jyoumei.cn/Article/details/gtxcibytdu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sxryk.cn/Article/details/gtvktxszys.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sysykeji.top/Article/details/gtpgpzaygs.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cqqwz.cn/Article/details/gtnrafktrg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.daria6918.cn/Article/details/gtckcewhho.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gtsytvhyow.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.daxiang520.top/Article/details/gtsxerbygk.html

[J08] 提取年月日与星期
来源：http://dali.daria6918.cn/Article/details/gtawdrhven.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuieasorc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.c1oappe.top/Article/details/gtfggkplbj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yuanzhike.top/Article/details/gtvgkovmzl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.svipenyu.cn/Article/details/gtcifdejgy.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhongyouzk.top/Article/details/gtqfwzhzwu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.havefunace.top/Article/details/gttmotyynx.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.iojbl.cn/Article/details/gtumcykciq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.bjfxy.top/Article/details/gtikideklz.html

[J09] 时区处理
来源：http://dali.pengpengdd.cyou/Article/details/gtymdoyevu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yj20258888.top/Article/details/gtiycqueed.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.meibo888.top/Article/details/gtbuommlnk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.feifeiyinyue.top/Article/details/gtosxsrjwz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sweek.top/Article/details/gtvgcapfaz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.chenzaomai.com/Article/details/gtkwurtxma.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.0kj1m.cn/Article/details/gtitenamfr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinghuilouyu.cn/Article/details/gttrvwkmzr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.nanxinkj.top/Article/details/gtlmwadufk.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhixingplan.top/Article/details/gtgjbgpzdw.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xylfe.cn/Article/details/gtrxiuvrgk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cheryme.top/Article/details/gtifbxonki.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.c1oappe.top/Article/details/gtqnxsdyyp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.snrcjt.cn/Article/details/gtwixzdsbb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shzxlz.cn/Article/details/gtevpfvbuw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.dianchejie.cn/Article/details/gtrkakhxzk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ehwqpu.com/Article/details/gtfsogvrbr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.andypj.xyz/Article/details/gtkfmmdngz.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gttwvwbeph.html

K. JSON 与序列化
来源：http://dali.c1oappe.top/Article/details/gtrqkthvtv.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gttbrwclot.html

[K01] 对象转 JSON 字符串
来源：http://dali.dashuyun.cn/Article/details/gtcvimyzdy.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhongyouzk.top/Article/details/gtljwtlugv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yuxming.cn/Article/details/gtzkajxhwc.html

JS:   JSON.stringify(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtplsoeura.html

TS:   JSON.stringify(obj)
来源：http://dali.gzhubu.top/Article/details/gtulgvwurv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yanxiufei.cn/Article/details/gtayxesywq.html

Go:   json.Marshal(obj)
来源：http://dali.quarkkingdee.top/Article/details/gttxjvsrqt.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yonumen.top/Article/details/gtbhlqlfrw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sxryk.cn/Article/details/gtvcqzkhbe.html

[K02] JSON 字符串转对象
来源：http://dali.xinyue.icu/Article/details/gtantxvtnk.html

Py:   json.loads(s)
来源：http://dali.daxiang520.top/Article/details/gtgvxuwzfx.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.mhx1999.top/Article/details/gtxhbpbhtx.html

JS:   JSON.parse(s)
来源：http://dali.cheryme.top/Article/details/gtimaxuosy.html

TS:   JSON.parse(s)
来源：http://dali.zhengqikj.top/Article/details/gtidhpykyt.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yangfankeji.com/Article/details/gtikixqhhd.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jiagoushi.top/Article/details/gtkguggixu.html

Ruby: JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gtxaaqdeeh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.snrcjt.cn/Article/details/gtswnwhtpm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yanxiufei.cn/Article/details/gtjkbkvxat.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhongyouzk.top/Article/details/gticpkdqmb.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.wangshuangyany.cn/Article/details/gtdjjaeuwb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.svipenyu.cn/Article/details/gtidrwkghm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gaohongyu789.top/Article/details/gtzajijycg.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinqigufen.top/Article/details/gtfpvoyoiq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.havefunace.top/Article/details/gtrgnpshwk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cheryme.top/Article/details/gtswvtwouc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shanyushiyangtech.top/Article/details/gtswkfifdq.html

[K04] 读取 JSON 文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtynoptcwj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhongyouzk.top/Article/details/gtnnktmped.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jqgfzy.top/Article/details/gtwlxtcxhr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.andypj.xyz/Article/details/gtregaxzhl.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuanzhike.top/Article/details/gtydrrbddy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.pengpengdd.cyou/Article/details/gtukszozpu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangtech.top/Article/details/gtennhvcel.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hfpthk.cn/Article/details/gtqsrllyci.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtnmxtxyga.html

[K05] 深拷贝对象
来源：http://dali.shangyingyoupin.top/Article/details/gtwzlhfsvv.html

Py:   copy.deepcopy(obj)
来源：http://dali.svipenyu.cn/Article/details/gtwghlkgvx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhoulong.xyz/Article/details/gtmevheims.html

JS:   structuredClone(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtfhomibyi.html

TS:   structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gtlijeaigu.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.daria6918.cn/Article/details/gtsejxfrhz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hongshengwenyu.top/Article/details/gtvaloywfv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.dianchejie.cn/Article/details/gtkfdjbgdy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sweek.top/Article/details/gtwlcwdfvz.html

[K06] 解析 URL 查询串
来源：http://dali.jiagoushi.top/Article/details/gthmeyqhww.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.guowangkeji.top/Article/details/gtgbgqwepq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.snrcjt.cn/Article/details/gtznqxkrik.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jlsjyb.cn/Article/details/gtmysyxiej.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hywenlv.cn/Article/details/gtmoonlskb.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhiwuduotai.top/Article/details/gtfwimijzw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yonumen.top/Article/details/gtnjvwbjxe.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.kuanghao11.cn/Article/details/gtqdjkarnz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.havefunace.top/Article/details/gtkrcuaxso.html

[K07] 进制转换
来源：http://dali.hammf.cn/Article/details/gtebkxfwbb.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gtwbpokayf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.wangdashe.top/Article/details/gtzertturc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gtdqjypqjv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtllzsrqzd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gtsktyjuby.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cdnleiting.top/Article/details/gtcdzzzrha.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jianghu66.top/Article/details/gtikbznqna.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gtplciiehq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sufxvd.cn/Article/details/gturkjrumz.html

Py:   pickle.dumps(obj)
来源：http://dali.cqqwz.cn/Article/details/gtsfytqonb.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.birdmap.top/Article/details/gtdyvergbl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yongpay.top/Article/details/gtddcfawnz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yonumen.top/Article/details/gtcizbfgww.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jyoumei.cn/Article/details/gtejovddxm.html

Go:   encoding/gob
来源：http://dali.feifeiyinyue.top/Article/details/gtlklvqido.html

Ruby: Marshal.dump(obj)
来源：http://dali.bjfxy.top/Article/details/gthuwjzgir.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.9152youxi.cn/Article/details/gtqarymyom.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtavvabfze.html

L. 网络请求
来源：http://dali.pycfn.com/Article/details/gtbbppatby.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gterwlcper.html

[L01] 发送 GET 请求
来源：http://dali.wangshuangyany.cn/Article/details/gtpdamlizf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ydzc1.top/Article/details/gtgnttoacb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinqigfzy.top/Article/details/gtrgwrjgox.html

JS:   await fetch(url)
来源：http://dali.vqdsnc.cn/Article/details/gtypzhggdu.html

TS:   await fetch(url)
来源：http://dali.zhongyouzk.top/Article/details/gtruzaoclr.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.dashuyun.cn/Article/details/gturfljtcx.html

Go:   resp, err := http.Get(url)
来源：http://dali.nanxinkj.top/Article/details/gtwgfkokoq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.dashuyun.cn/Article/details/gtdlmvobic.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sxryk.cn/Article/details/gtlltyyggm.html

[L02] 发送 POST JSON
来源：http://dali.yangfankeji.com/Article/details/gtflnsbrwz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.tanke756.top/Article/details/gtzmaohwoq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jyoumei.cn/Article/details/gtoricrqgb.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuetiantiany.cn/Article/details/gtqwaadshk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fengsongda.top/Article/details/gtdxofewgd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ehwqpu.com/Article/details/gtjeotelvk.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.9152youxi.cn/Article/details/gtqosclydx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hnxiangtu.top/Article/details/gtrwitgxzn.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.svipenyu.cn/Article/details/gtddqmvizg.html

[L03] 设置自定义请求头
来源：http://dali.nanxuanxn.top/Article/details/gtjlvztoyx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yuxming.cn/Article/details/gtbhchfxcp.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.svipenyu.cn/Article/details/gtdvetcysr.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.birdmap.top/Article/details/gtmmvwdbiu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yongpay.top/Article/details/gtnqsuktna.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.aibaodan.cn/Article/details/gtstglmicp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jinqigufen.top/Article/details/gtbpaqrcjr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xuanzx.com/Article/details/gtrppsrqdg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hongshengwenyu.top/Article/details/gtrvqvjmou.html

[L04] 设置超时
来源：http://dali.aibaodan.cn/Article/details/gtpebyrrle.html

Py:   requests.get(url, timeout=5)
来源：http://dali.birdmap.top/Article/details/gthsyaltvl.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sxryk.cn/Article/details/gtiyrofyup.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shzxlz.cn/Article/details/gtpxjxbtaj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258.top/Article/details/gtredxozrf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ydzc1.top/Article/details/gtpnqipcur.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.wangshuangyany.cn/Article/details/gtwnidxvmf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.feifeiyinyue.top/Article/details/gtvgqhjumd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jqgfzy.top/Article/details/gtznbwpgcv.html

[L05] 上传文件（multipart）
来源：http://dali.xziqi.cn/Article/details/gtuuqrsalr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.wangdashe.top/Article/details/gtvwvnhaxc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yuanzhike.top/Article/details/gtjwolizoy.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhoulong.xyz/Article/details/gtlkedvbew.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hfpthk.cn/Article/details/gtxolxctsd.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yangfankeji.com/Article/details/gttyuitpuo.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.chenzaomai.com/Article/details/gtzgbwbsrb.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.dianchejie.cn/Article/details/gtdnlbehli.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gttfmpqlib.html

[L06] 解析响应为 JSON
来源：http://dali.dashuyun.cn/Article/details/gtfgtwtmnl.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gtgyocclfk.html

PHP:  json_decode($body, true);
来源：http://dali.feifeiyinyue.top/Article/details/gttgzzhlja.html

JS:   await resp.json()
来源：http://dali.cheryme.top/Article/details/gtvpwfwkbc.html

TS:   await resp.json()
来源：http://dali.sweek.top/Article/details/gtgufrzmpa.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yuanzhike.top/Article/details/gteehxeuzm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.chenzaomai.com/Article/details/gtjqrvudzt.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shzxlz.cn/Article/details/gtjcwmwihg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.daxiang520.top/Article/details/gtxgshwuad.html

[L07] 处理 HTTP 状态码
来源：http://dali.shangyingyoupin.top/Article/details/gtxpsmoowa.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nwbrower.top/Article/details/gtknfexvee.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sufxvd.cn/Article/details/gtjhprnbbx.html

JS:   resp.ok;  resp.status
来源：http://dali.bjfxy.top/Article/details/gtozhtkuos.html


<!-- 参考信息 -->