代发 wailian999

================================================================================
来源：http://dali.havefunace.top/Article/details/gtjbhfjypg.html

I. 正则表达式
来源：http://dali.fengsongda.top/Article/details/gtmafftjpm.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtihsqtqdy.html

[I01] 判断是否匹配
来源：http://dali.nanxuanxn.top/Article/details/gtebsblmwj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gteddknpxt.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtyycjacoi.html

JS:   /\d+/.test(s)
来源：http://dali.chenlongwang.top/Article/details/gtozfjrued.html

TS:   /\d+/.test(s)
来源：http://dali.316326.xyz/Article/details/gtjjnvacrq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hongshengwenyu.top/Article/details/gtuxcfekjl.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.tanke756.top/Article/details/gtwxikenzy.html

Ruby: s.match?(/\d+/)
来源：http://dali.shzxlz.cn/Article/details/gthhindfoc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yongpay.top/Article/details/gtwtgydamk.html

[I02] 提取所有匹配
来源：http://dali.xinyue.icu/Article/details/gthojxxjoq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hywenlv.cn/Article/details/gtqoinkxqe.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.quarkkingdee.top/Article/details/gtmfbajzfk.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.smart0.xyz/Article/details/gtolnwfscx.html

TS:   s.match(/\d+/g)
来源：http://dali.gotoacloud.top/Article/details/gtunyrzfpr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.meibo888.top/Article/details/gtuuradbpq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cucudq.cn/Article/details/gtllacevrb.html

Ruby: s.scan(/\d+/)
来源：http://dali.fengsongda.top/Article/details/gtwkcuzohn.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtohymwgiz.html

[I03] 提取捕获分组
来源：http://dali.yj20258.top/Article/details/gtnynnmtkq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yonumen.top/Article/details/gtqyyqklxt.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.andypj.xyz/Article/details/gtcnbgofem.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shangyingyoupin.top/Article/details/gtlagzyusq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.redwolf501.top/Article/details/gtmoeurqbh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yongpay.top/Article/details/gtbjrcwamf.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sysykeji.top/Article/details/gtatjovbod.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jiagoushi.top/Article/details/gtrziwtzkr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.guowangkeji.top/Article/details/gtjkgondgg.html

[I04] 正则替换
来源：http://dali.wangdashe.top/Article/details/gteixegslw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzzqvcuft.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hysaishi.cn/Article/details/gtbzvdofrm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxjckhaud.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.0kj1m.cn/Article/details/gtmlvaeudr.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbglpglne.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.havefunace.top/Article/details/gtdkcxnlzz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkkdlpmxt.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gaohongyu789.top/Article/details/gttkbgdadk.html

[I05] 按正则拆分
来源：http://dali.svipenyu.cn/Article/details/gtgtyxqxzm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.iojbl.cn/Article/details/gtjxlynbdm.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.wangdashe.top/Article/details/gtwcwbamjs.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ivvv.top/Article/details/gtwysmimic.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ppjwa.cn/Article/details/gtwlnfxlqx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jianghu66.top/Article/details/gtjgmbrdxx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.daxiang520.top/Article/details/gtxvbwoyam.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.tian-w.cn/Article/details/gtyraeykym.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.316326.xyz/Article/details/gtfpforgao.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cashguo.top/Article/details/gtsevkmzkb.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gtsfqgyand.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.kuanghao11.cn/Article/details/gtxnfburce.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpmimdstg.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenjidiqi.icu/Article/details/gtlkzzhyhj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.pycfn.com/Article/details/gttsmiclya.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.haohaochexian.top/Article/details/gtmkcclcvm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sxryk.cn/Article/details/gtauorckcy.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gtfyfpibyd.html

[I07] 忽略大小写与多行模式
来源：http://dali.cucudq.cn/Article/details/gtgvggiekc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hnxiangtu.top/Article/details/gtlblyehfs.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xylfe.cn/Article/details/gticmmeqac.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sufxvd.cn/Article/details/gteujttszx.html

TS:   /error/gim
来源：http://dali.xuanzx.com/Article/details/gtflzffgrb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinqigufen.top/Article/details/gtewsfxtpu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yvedp.cn/Article/details/gtcnjgzpuf.html

Ruby: s.scan(/error/i)
来源：http://dali.zycfv.cn/Article/details/gtrncmwgrr.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sysykeji.top/Article/details/gthkvjsjzp.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.meibo888.top/Article/details/gtnugxcbiu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.0kj1m.cn/Article/details/gtjuveljew.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shzxlz.cn/Article/details/gteocrgybj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.bjfxy.top/Article/details/gtbuzzxjge.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnxiangtu.top/Article/details/gtvcutsqwy.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.feifeiyinyue.top/Article/details/gtbvkctgoi.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jqgfzy.top/Article/details/gtfrozyhdy.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hfpthk.cn/Article/details/gtgdndmpzb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yueranfly.top/Article/details/gtpdwkzbak.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtpxcespzh.html

J. 日期与时间
来源：http://dali.ydzc1.top/Article/details/gtplhxrjbk.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtxnbykyjt.html

[J01] 获取当前时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqmjarnss.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.daria6918.cn/Article/details/gtaegylkzl.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gotoacloud.top/Article/details/gticalwsug.html

JS:   new Date();  Date.now()
来源：http://dali.vqdsnc.cn/Article/details/gtxdoyieds.html

TS:   new Date();  Date.now()
来源：http://dali.iojbl.cn/Article/details/gtunxtnidx.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.guowangkeji.top/Article/details/gtcairibso.html

Go:   time.Now()
来源：http://dali.yj20258888.top/Article/details/gtuguiznyh.html

Ruby: Time.now
来源：http://dali.jyoumei.cn/Article/details/gtijiecvtp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.smart0.xyz/Article/details/gtntarlzol.html

[J02] 格式化输出
来源：http://dali.c1oappe.top/Article/details/gtvgswigay.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nanxuanxn.top/Article/details/gtqsicsopv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhiwuduotai.top/Article/details/gthsodctdp.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.tanke756.top/Article/details/gtmngqfikg.html

TS:   d.toISOString()
来源：http://dali.snrcjt.cn/Article/details/gthblgaagq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.meibo888.top/Article/details/gtzibcgiva.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.tian-w.cn/Article/details/gtzeakkklc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.haohaochexian.top/Article/details/gtuhrqihqi.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzzbretph.html

[J03] 字符串解析为日期
来源：http://dali.cdnleiting.top/Article/details/gtpvkeegno.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.tanke756.top/Article/details/gtdcmkttfq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shuidangran.top/Article/details/gteoftnitm.html

JS:   new Date("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtzddwfrxo.html

TS:   new Date("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtylfgfchs.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gttsaqslfb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtorsreunf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gtkhfxzjzl.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcojaymnt.html

[J04] 时间戳与日期互转
来源：http://dali.tianlin.xyz/Article/details/gtxtcenhqv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jlsjyb.cn/Article/details/gtlztqggfr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.wangshuangyany.cn/Article/details/gtxeymkgpu.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.aizwys.cn/Article/details/gtofctoypr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.bjfxy.top/Article/details/gtuazvyhez.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhoulong.xyz/Article/details/gtqugnfdhk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cashguo.top/Article/details/gtmqctiwhr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sysykeji.top/Article/details/gtwwhijled.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcvtnzhfg.html

[J05] 时间加减（加 7 天）
来源：http://dali.ivvv.top/Article/details/gtvtifqliw.html

Py:   now + timedelta(days=7)
来源：http://dali.jianghu66.top/Article/details/gtanniuzix.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cqqwz.cn/Article/details/gtksjnhkww.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sxryk.cn/Article/details/gtfodopnqu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jyoumei.cn/Article/details/gtcjnopcso.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hnqzz.top/Article/details/gtogtyrvuw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xylfe.cn/Article/details/gthsdmgmbf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.andypj.xyz/Article/details/gtodbzzsyt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xuetiantiany.cn/Article/details/gtvyhvdijh.html

[J06] 计算两时间之差
来源：http://dali.shzxlz.cn/Article/details/gtlvymmdpz.html

Py:   (end - start).total_seconds()
来源：http://dali.9152youxi.cn/Article/details/gtpoipsagk.html

PHP:  $end->diff($start)->days;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpeqbvqmr.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.pengpengdd.cyou/Article/details/gtacynlykm.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.quarkkingdee.top/Article/details/gtcjfytjow.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xinyue.icu/Article/details/gtrwxdcjwg.html

Go:   end.Sub(start).Hours()
来源：http://dali.yanxiufei.cn/Article/details/gtugdkdidd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shuidangran.top/Article/details/gthccxpvzb.html

C#:   (end - start).TotalSeconds
来源：http://dali.snrcjt.cn/Article/details/gtvwujkbbt.html

[J07] 比较两个日期
来源：http://dali.tian-w.cn/Article/details/gtonjcwdsv.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jlsjyb.cn/Article/details/gtrukbxlsi.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.fengsongda.top/Article/details/gtuxeyfsve.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yj202588.top/Article/details/gtyikkouic.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hfpthk.cn/Article/details/gtsyvamzxh.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shuidangran.top/Article/details/gtnxmzhrrx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.kuanghao11.cn/Article/details/gtdkvlmlot.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.daxiang520.top/Article/details/gtkkrmuigv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.0kj1m.cn/Article/details/gtduaffjkr.html

[J08] 提取年月日与星期
来源：http://dali.bjfxy.top/Article/details/gtcyqivplt.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xylfe.cn/Article/details/gtshtiijom.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ehwqpu.com/Article/details/gtaomlmiuw.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.mhx1999.top/Article/details/gtmxqhtfnl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ehwqpu.com/Article/details/gtgnyitxrf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlaqomgys.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.fengsongda.top/Article/details/gtqtukbghw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cqqwz.cn/Article/details/gtouswjzgw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yuanzhike.top/Article/details/gtoxhnpszv.html

[J09] 时区处理
来源：http://dali.gotoacloud.top/Article/details/gtobzaqlfd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zdqjudy.top/Article/details/gtkpkaxxkn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sxryk.cn/Article/details/gtwnvyatqf.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nwbrower.top/Article/details/gtcupsldbp.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.redwolf501.top/Article/details/gtpyqtietg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zdqjudy.top/Article/details/gtvgykklhy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhiwuduotai.top/Article/details/gtlwyppoiv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.kuanghao11.cn/Article/details/gtdahqeliv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxsjkwwrd.html

[J10] 取今天 / 本月第一天
来源：http://dali.tian-w.cn/Article/details/gtatetvpop.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.aibaodan.cn/Article/details/gtrtaqcyom.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhongyouzk.top/Article/details/gtwldkwqvg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.c1oappe.top/Article/details/gtirpdcppu.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.daria6918.cn/Article/details/gtrrwwwnbv.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.bjfxy.top/Article/details/gtxoxncbds.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj202588.top/Article/details/gtbymoamwn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.iojbl.cn/Article/details/gtmydextlk.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.vqdsnc.cn/Article/details/gtgipuaflz.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gterhzjbam.html

K. JSON 与序列化
来源：http://dali.ehwqpu.com/Article/details/gtexedeqow.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtfhplojgz.html

[K01] 对象转 JSON 字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtufsrlkwj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gogol.net.cn/Article/details/gtbwecowzd.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.dianchejie.cn/Article/details/gthqplxpqt.html

JS:   JSON.stringify(obj)
来源：http://dali.iojbl.cn/Article/details/gtfyvzxujk.html

TS:   JSON.stringify(obj)
来源：http://dali.guannengcc.top/Article/details/gtkhkszsgi.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.fzhhl.top/Article/details/gtlxzkaqeg.html

Go:   json.Marshal(obj)
来源：http://dali.ybcxt.top/Article/details/gtwzslfkpy.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jiagoushi.top/Article/details/gtcbrqockk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtzxanjmoo.html

[K02] JSON 字符串转对象
来源：http://dali.hnqzz.top/Article/details/gtfyhnwngn.html

Py:   json.loads(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzplgctmm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yueranfly.top/Article/details/gtphsgqzij.html

JS:   JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gtmbizohlf.html

TS:   JSON.parse(s)
来源：http://dali.hnxiangtu.top/Article/details/gtingdiait.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ppjwa.cn/Article/details/gtxhgyclfw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.daxiang520.top/Article/details/gtallspadd.html

Ruby: JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gthhjnvtzj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cashguo.top/Article/details/gtgnuogxls.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.snrcjt.cn/Article/details/gtuwkhzeiu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.0kj1m.cn/Article/details/gtirjxylpi.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.0kj1m.cn/Article/details/gthjozxaye.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.fengsongda.top/Article/details/gtvkwdlqfx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnxiangtu.top/Article/details/gtmqhwubgs.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jiagoushi.top/Article/details/gtymrjqtwq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jiagoushi.top/Article/details/gtizgseumt.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhengqikj.top/Article/details/gtwrbzgdfu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xziqi.cn/Article/details/gtzdgdpwfh.html

[K04] 读取 JSON 文件
来源：http://dali.tian-w.cn/Article/details/gtxitzfgjv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.0kj1m.cn/Article/details/gtoirqnmad.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.9152youxi.cn/Article/details/gtrehcweft.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenlongwang.top/Article/details/gtphmjmwcm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.dianchejie.cn/Article/details/gtdxfzxnos.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yueranfly.top/Article/details/gtagallxnc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.chenzaomai.com/Article/details/gtokcrfqhl.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.tian-w.cn/Article/details/gtagyeknnj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.fengsongda.top/Article/details/gthknzqnpw.html

[K05] 深拷贝对象
来源：http://dali.yanxiufei.cn/Article/details/gtqqyqneod.html

Py:   copy.deepcopy(obj)
来源：http://dali.aibaodan.cn/Article/details/gtvbnnazzw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cucudq.cn/Article/details/gtruwrupqu.html

JS:   structuredClone(obj)
来源：http://dali.yj20258.top/Article/details/gtdekynkwa.html

TS:   structuredClone(obj)
来源：http://dali.yvedp.cn/Article/details/gtznmvdcoa.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.pycfn.com/Article/details/gtrhaltkel.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.fengsongda.top/Article/details/gtnpjsqkzl.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.sysykeji.top/Article/details/gtvriebprs.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.iojbl.cn/Article/details/gtuoplmpqy.html

[K06] 解析 URL 查询串
来源：http://dali.xziqi.cn/Article/details/gtvyysdclc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gaohongyu789.top/Article/details/gtmforlauf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.daria6918.cn/Article/details/gtqocvhjqt.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xinyue.icu/Article/details/gtuglitvfw.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xinyue.icu/Article/details/gtlfzgqylv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.dianchejie.cn/Article/details/gtbknlrqfn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.meibo888.top/Article/details/gtddpiiiok.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.redwolf501.top/Article/details/gtrltfcvsv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhoulong.xyz/Article/details/gtouzogemr.html

[K07] 进制转换
来源：http://dali.redwolf501.top/Article/details/gtlcfcshpz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gtnrhnssrj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jianghu66.top/Article/details/gtpaoxtmdf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gtkypwkhwm.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gtmnwuixta.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gtdblvwyvr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xinyue.icu/Article/details/gtvafjymjx.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.chenzaomai.com/Article/details/gtgxlcsgff.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gtikdfqqpo.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cashguo.top/Article/details/gtyogdqndv.html

Py:   pickle.dumps(obj)
来源：http://dali.fzhhl.top/Article/details/gtjmavoicc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhixingplan.top/Article/details/gtmszpuouu.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zdqjudy.top/Article/details/gtutenbqkk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.nwbrower.top/Article/details/gtkfnzzezk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.daria6918.cn/Article/details/gtolstxksf.html

Go:   encoding/gob
来源：http://dali.ehwqpu.com/Article/details/gtwnaaiomi.html

Ruby: Marshal.dump(obj)
来源：http://dali.aizwys.cn/Article/details/gtlqubdtnz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.birdmap.top/Article/details/gtoctxijsg.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtlrwfmctx.html

L. 网络请求
来源：http://dali.zdqjudy.top/Article/details/gtinebecvd.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtfcmsqpui.html

[L01] 发送 GET 请求
来源：http://dali.jqgfzy.top/Article/details/gtpddrkvgh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cqqwz.cn/Article/details/gtzeyrqxqd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yongpay.top/Article/details/gthnnsomsq.html

JS:   await fetch(url)
来源：http://dali.316326.xyz/Article/details/gtwkrfovct.html

TS:   await fetch(url)
来源：http://dali.zhongyouzk.top/Article/details/gtuyviygip.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhixingplan.top/Article/details/gtosiyctuk.html

Go:   resp, err := http.Get(url)
来源：http://dali.guannengcc.top/Article/details/gtbeqcpvpj.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.birdmap.top/Article/details/gtjhnmwuwo.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ivvv.top/Article/details/gtkmqxnawy.html

[L02] 发送 POST JSON
来源：http://dali.cqqwz.cn/Article/details/gtekrodnww.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jianghu66.top/Article/details/gtdcuqzgpu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.birdmap.top/Article/details/gtwdgyohel.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangtech.top/Article/details/gtzgwdezvq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.snrcjt.cn/Article/details/gtgrhivknk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.daria6918.cn/Article/details/gtusgwgjvx.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.dianchejie.cn/Article/details/gtbgxinabl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.nanxuanxn.top/Article/details/gtowzamveu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.redwolf501.top/Article/details/gttagyhcae.html

[L03] 设置自定义请求头
来源：http://dali.316326.xyz/Article/details/gtwttnwmfo.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cqqwz.cn/Article/details/gtenqpildw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ybcxt.top/Article/details/gtpuxrcrey.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfckarcif.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.9152youxi.cn/Article/details/gtpnvowigw.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.tianlin.xyz/Article/details/gteahjrcyo.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xinyue.icu/Article/details/gtapevdmjh.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xuetiantiany.cn/Article/details/gttxegnchj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.tianlin.xyz/Article/details/gtoizopafc.html

[L04] 设置超时
来源：http://dali.redwolf501.top/Article/details/gtwabxbtqp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.fengsongda.top/Article/details/gtwmybybdz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhoulong.xyz/Article/details/gtcrggwatn.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sufxvd.cn/Article/details/gtjaacjazh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yangfankeji.com/Article/details/gtvlirledm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yj20258.top/Article/details/gtbokjbbgn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hnxiangtu.top/Article/details/gtgjrpgxol.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jiagoushi.top/Article/details/gtqoezmitw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.wangshuangyany.cn/Article/details/gtuqpigziv.html

[L05] 上传文件（multipart）
来源：http://dali.jinqigufen.top/Article/details/gtlqvfikwh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yj20258888.top/Article/details/gtcgackwgu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.chenzaomai.com/Article/details/gtxbrbmluh.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ydzc1.top/Article/details/gtgrzpffty.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgacbxyig.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ybcxt.top/Article/details/gtwpnvgpnz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jqgfzy.top/Article/details/gtzgdcyucx.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xuetiantiany.cn/Article/details/gtupwoenmh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtnmzvouqc.html

[L06] 解析响应为 JSON
来源：http://dali.birdmap.top/Article/details/gttfysizma.html

Py:   resp.json()
来源：http://dali.nanxuanxn.top/Article/details/gtqpybwfnk.html

PHP:  json_decode($body, true);
来源：http://dali.yangfankeji.com/Article/details/gtnbtozdml.html

JS:   await resp.json()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtthmzdkgm.html

TS:   await resp.json()
来源：http://dali.gotoacloud.top/Article/details/gtxmfpridv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgbqnyrla.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xuetiantiany.cn/Article/details/gtuimrpgdh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.iojbl.cn/Article/details/gtvktmarje.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gotoacloud.top/Article/details/gtjqhgxwof.html


<!-- 参考信息 -->