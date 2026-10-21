代发 wailian999

================================================================================
来源：http://dali.316326.xyz/Article/details/gtpgqylucw.html

I. 正则表达式
来源：http://dali.yj20258.top/Article/details/gtwfpjksdy.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtrqvweeld.html

[I01] 判断是否匹配
来源：http://dali.andypj.xyz/Article/details/gtcupevxjj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.pengpengdd.cyou/Article/details/gtmaeogkay.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwpgzkmtw.html

JS:   /\d+/.test(s)
来源：http://dali.nanxinkj.top/Article/details/gtvzhmusio.html

TS:   /\d+/.test(s)
来源：http://dali.yonumen.top/Article/details/gtmgavhosb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sysykeji.top/Article/details/gtzteplcop.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.svipenyu.cn/Article/details/gtwxypxfvc.html

Ruby: s.match?(/\d+/)
来源：http://dali.ppjwa.cn/Article/details/gtzjkoposm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgdpsnyda.html

[I02] 提取所有匹配
来源：http://dali.ppjwa.cn/Article/details/gtwvihcene.html

Py:   re.findall(r"\d+", s)
来源：http://dali.chenlongwang.top/Article/details/gtpnzipogg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.aizwys.cn/Article/details/gtfwpgpijp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.andypj.xyz/Article/details/gtxdobehgg.html

TS:   s.match(/\d+/g)
来源：http://dali.daxiang520.top/Article/details/gthasedgzx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinqigfzy.top/Article/details/gtejufhekt.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.bjfxy.top/Article/details/gtzbqylfqs.html

Ruby: s.scan(/\d+/)
来源：http://dali.quarkkingdee.top/Article/details/gtcgndzvyq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.andypj.xyz/Article/details/gtsxehrhvh.html

[I03] 提取捕获分组
来源：http://dali.chenzaomai.com/Article/details/gtemmqurmd.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jqgfzy.top/Article/details/gtzakxonmi.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gthzeheusy.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.sxryk.cn/Article/details/gtavygelgz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shuidangran.top/Article/details/gtdfgiknok.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.wangshuangyany.cn/Article/details/gtdvoztvrt.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.guannengcc.top/Article/details/gtcdvzctkg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sweek.top/Article/details/gtewnxjjhe.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.svipenyu.cn/Article/details/gtkrchtapb.html

[I04] 正则替换
来源：http://dali.xziqi.cn/Article/details/gtmidkozea.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhongyouzk.top/Article/details/gtafjzfocw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtlqyqqmon.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgfzy.top/Article/details/gtukdxbphe.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gaohongyu789.top/Article/details/gtketxwegu.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.bjfxy.top/Article/details/gtrqlxdbcy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtrwgxoijb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.pycfn.com/Article/details/gteoteltoa.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.bjfxy.top/Article/details/gtppkqmbav.html

[I05] 按正则拆分
来源：http://dali.xziqi.cn/Article/details/gtgncsbjvq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ehwqpu.com/Article/details/gtpcefxgnv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xinyue.icu/Article/details/gtybtrwvvp.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gtffzqupez.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yuanzhike.top/Article/details/gtldfelczh.html

Java: s.split("\\s*,\\s*")
来源：http://dali.kuanghao11.cn/Article/details/gtavbrdpld.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cqqwz.cn/Article/details/gthqlrjqhk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.wangdashe.top/Article/details/gtwnhvggvw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.birdmap.top/Article/details/gtmdxuuzvd.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdqetxjpf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gtnxtpyetu.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ybcxt.top/Article/details/gtahkvtxoo.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gtzefvvhxs.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nwbrower.top/Article/details/gtnevqznlw.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hongshengwenyu.top/Article/details/gtblhvssjl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sufxvd.cn/Article/details/gtikdaktqc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.quarkkingdee.top/Article/details/gtfbpptoxb.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.chenjidiqi.icu/Article/details/gtfkwzbtrg.html

[I07] 忽略大小写与多行模式
来源：http://dali.quarkkingdee.top/Article/details/gtdgejleor.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hywenlv.cn/Article/details/gtmqhusadx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwrlzvfhc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.fengsongda.top/Article/details/gtgtkwxjro.html

TS:   /error/gim
来源：http://dali.nanxuanxn.top/Article/details/gtosfiotjj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.mhx1999.top/Article/details/gtrapsysob.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.nanxinkj.top/Article/details/gtdjsdprwv.html

Ruby: s.scan(/error/i)
来源：http://dali.gotoacloud.top/Article/details/gtdmhyifdb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.quarkkingdee.top/Article/details/gtqvsgthbj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hywenlv.cn/Article/details/gtdkeknret.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.nanxinkj.top/Article/details/gtmfmumkhk.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.vqdsnc.cn/Article/details/gtzooocuex.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guowangkeji.top/Article/details/gtxgrlxvhi.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shangyingyoupin.top/Article/details/gtnjhdmzfd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xinyue.icu/Article/details/gtelpyuyvo.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.316326.xyz/Article/details/gtvzyugcha.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xuanzx.com/Article/details/gtplsfcidw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gogol.net.cn/Article/details/gtamqaclhk.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtjpkarwbj.html

J. 日期与时间
来源：http://dali.meibo888.top/Article/details/gtkzvzsrgr.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtpihindlg.html

[J01] 获取当前时间
来源：http://dali.hywenlv.cn/Article/details/gtwhocygrv.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zdqjudy.top/Article/details/gtokfcckhs.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xziqi.cn/Article/details/gtzxcjgkrk.html

JS:   new Date();  Date.now()
来源：http://dali.xylfe.cn/Article/details/gtgrjcehzx.html

TS:   new Date();  Date.now()
来源：http://dali.cheryme.top/Article/details/gtyvcjqgej.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.guannengcc.top/Article/details/gttzkakbtw.html

Go:   time.Now()
来源：http://dali.ydzc1.top/Article/details/gtzomleyen.html

Ruby: Time.now
来源：http://dali.pengpengdd.cyou/Article/details/gtduosirsr.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.guowangkeji.top/Article/details/gtatjgtvby.html

[J02] 格式化输出
来源：http://dali.cqqwz.cn/Article/details/gtlynhrllh.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daria6918.cn/Article/details/gtyonzahkk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.feifeiyinyue.top/Article/details/gtqalqtiha.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.andypj.xyz/Article/details/gtntmnzqsv.html

TS:   d.toISOString()
来源：http://dali.dashuyun.cn/Article/details/gtuzhdojsk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xinyue.icu/Article/details/gtjsvhhivp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.wangshuangyany.cn/Article/details/gtzmpfhgun.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hfpthk.cn/Article/details/gtzepgiute.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jqgfzy.top/Article/details/gtizaojyir.html

[J03] 字符串解析为日期
来源：http://dali.wangshuangyany.cn/Article/details/gtsocgpunf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.fengsongda.top/Article/details/gtwkmrxgoh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hysaishi.cn/Article/details/gtupapthhj.html

JS:   new Date("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtybngydve.html

TS:   new Date("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gtdkwgodjo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtjmygwjbb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuizivmvd.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gtufvpzjng.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yvedp.cn/Article/details/gtskzvbsio.html

[J04] 时间戳与日期互转
来源：http://dali.fengsongda.top/Article/details/gtppsxythp.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cashguo.top/Article/details/gtzapjhpiq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhengqikj.top/Article/details/gtnapkhenf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtftvwrzie.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.redwolf501.top/Article/details/gtbptgejqj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yangfankeji.com/Article/details/gtnzpofayp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbrfxaxzf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhoulong.xyz/Article/details/gtzjorjbqv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yonumen.top/Article/details/gtknayotsf.html

[J05] 时间加减（加 7 天）
来源：http://dali.yangfankeji.com/Article/details/gtzrkbmiqa.html

Py:   now + timedelta(days=7)
来源：http://dali.hywenlv.cn/Article/details/gtlpogzpon.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.kuanghao11.cn/Article/details/gtzdbqhsjo.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhixingplan.top/Article/details/gtrckieheh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ppjwa.cn/Article/details/gtmxlvjolz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.tianlin.xyz/Article/details/gtrnwecugq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.316326.xyz/Article/details/gtmnsvpine.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yj202588.top/Article/details/gtoutncxht.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yonumen.top/Article/details/gtyyhaueak.html

[J06] 计算两时间之差
来源：http://dali.chenjidiqi.icu/Article/details/gtjnvluzle.html

Py:   (end - start).total_seconds()
来源：http://dali.jinqigfzy.top/Article/details/gtopjzqeyg.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhongyouzk.top/Article/details/gtuwxugteh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ydzc1.top/Article/details/gtvkaasbna.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhoulong.xyz/Article/details/gtuqtmhurd.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.guannengcc.top/Article/details/gtoawatfxl.html

Go:   end.Sub(start).Hours()
来源：http://dali.cheryme.top/Article/details/gtcdxwvslc.html

Ruby: end - start                 # 返回秒数
来源：http://dali.dianchejie.cn/Article/details/gtstlemovp.html

C#:   (end - start).TotalSeconds
来源：http://dali.tanke756.top/Article/details/gtzixmlcjf.html

[J07] 比较两个日期
来源：http://dali.9152youxi.cn/Article/details/gtbmslcemy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gtywrciddj.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuanzmtzo.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.fengsongda.top/Article/details/gtmncpdbhv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.haohaochexian.top/Article/details/gtjcodbtwd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sufxvd.cn/Article/details/gtyrbnfijq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hammf.cn/Article/details/gtusqqjeyi.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.wangdashe.top/Article/details/gtqndczvwx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gzhubu.top/Article/details/gttrmsbdaz.html

[J08] 提取年月日与星期
来源：http://dali.hongshengwenyu.top/Article/details/gtlujrkido.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.nanxuanxn.top/Article/details/gtlwkjwtvw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhongyouzk.top/Article/details/gtrybjphlo.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.vqdsnc.cn/Article/details/gtmpdjsmah.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ywan-chungtsiang.top/Article/details/gttjvscucw.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzcphzhyy.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.bjfxy.top/Article/details/gteyqxzlmx.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xuetiantiany.cn/Article/details/gtydpdrjrv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yvedp.cn/Article/details/gtbhnbdwpz.html

[J09] 时区处理
来源：http://dali.yongpay.top/Article/details/gtqntlhyep.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.guowangkeji.top/Article/details/gtsvykyulx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhijiandao.cn/Article/details/gtjyeiuhtk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cashguo.top/Article/details/gtltzqyfxj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yongpay.top/Article/details/gtalbwylgm.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gzhubu.top/Article/details/gtpxbecczp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.kuanghao11.cn/Article/details/gtdcbieikk.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.316326.xyz/Article/details/gtriyrdgvx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.mhx1999.top/Article/details/gtealaqfvk.html

[J10] 取今天 / 本月第一天
来源：http://dali.guannengcc.top/Article/details/gtnngxcnsc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtswzrguom.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jqgfzy.top/Article/details/gtamfymncs.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.tanke756.top/Article/details/gtukeraqfi.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhengqikj.top/Article/details/gtgvjrwefq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shzxlz.cn/Article/details/gtwgmkamfe.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.pycfn.com/Article/details/gtwrgzmdyh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ivvv.top/Article/details/gtplzuprnl.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtwxqdfnvu.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtgrnjluhg.html

K. JSON 与序列化
来源：http://dali.yangfankeji.com/Article/details/gtopnjnejd.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtgushpmiq.html

[K01] 对象转 JSON 字符串
来源：http://dali.hammf.cn/Article/details/gtamjlkvet.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtomxdsdao.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.snrcjt.cn/Article/details/gtrtlqjtfd.html

JS:   JSON.stringify(obj)
来源：http://dali.yj20258.top/Article/details/gtbgbjgtlj.html

TS:   JSON.stringify(obj)
来源：http://dali.yvedp.cn/Article/details/gtoatqgnvo.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jqgufenzy.top/Article/details/gtsenaryxl.html

Go:   json.Marshal(obj)
来源：http://dali.jqgufenzy.top/Article/details/gttryhptmv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hongshengwenyu.top/Article/details/gtgmtjvphv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtypzwctlx.html

[K02] JSON 字符串转对象
来源：http://dali.snrcjt.cn/Article/details/gtewhwshch.html

Py:   json.loads(s)
来源：http://dali.xziqi.cn/Article/details/gttminpkrh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cqqwz.cn/Article/details/gthtxtxgds.html

JS:   JSON.parse(s)
来源：http://dali.fengsongda.top/Article/details/gtqewnwyok.html

TS:   JSON.parse(s)
来源：http://dali.sweek.top/Article/details/gtxukuqnou.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.daxiang520.top/Article/details/gtbvvvxljh.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cashguo.top/Article/details/gtkiquezba.html

Ruby: JSON.parse(s)
来源：http://dali.ppjwa.cn/Article/details/gtscweyyew.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yvedp.cn/Article/details/gtgpqcblkb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zycfv.cn/Article/details/gtvofibmqx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.andypj.xyz/Article/details/gtswvpcday.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.wangdashe.top/Article/details/gtonfgpehx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.mhx1999.top/Article/details/gtnnmjzknb.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gtskcecbsz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cheryme.top/Article/details/gtxrerlmea.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmehzporv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.aizwys.cn/Article/details/gtjnxsxjkg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sweek.top/Article/details/gtmepsbyyl.html

[K04] 读取 JSON 文件
来源：http://dali.shuidangran.top/Article/details/gttzaqjexl.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.havefunace.top/Article/details/gtxulaemum.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.316326.xyz/Article/details/gtyqfviksa.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenzaomai.com/Article/details/gtgoqwbswf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xylfe.cn/Article/details/gtvrbunbob.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.pycfn.com/Article/details/gtmypnhpiy.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.chenjidiqi.icu/Article/details/gtkobtkorp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.tanke756.top/Article/details/gttruxnqlr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nwbrower.top/Article/details/gtpubcctxz.html

[K05] 深拷贝对象
来源：http://dali.yj20258.top/Article/details/gtvluekbnk.html

Py:   copy.deepcopy(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtqufkcxso.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hnqzz.top/Article/details/gtneqgkeju.html

JS:   structuredClone(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtitglgzjw.html

TS:   structuredClone(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqloomtgg.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.dashuyun.cn/Article/details/gtzjjpynvc.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.tian-w.cn/Article/details/gtjnjztssv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hongshengwenyu.top/Article/details/gtaienbtzt.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.tian-w.cn/Article/details/gtdpxhsjxa.html

[K06] 解析 URL 查询串
来源：http://dali.zhoulong.xyz/Article/details/gtfgturtmj.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.tianlin.xyz/Article/details/gttyvpnnkp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cdnleiting.top/Article/details/gtapszsgjl.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnqzz.top/Article/details/gtaenzfnws.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tianlin.xyz/Article/details/gtbzvwqueh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jiagoushi.top/Article/details/gtvcqtgsuy.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinqigfzy.top/Article/details/gtzgjrjjoa.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hongshengwenyu.top/Article/details/gtxwcduaua.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gtgtmlphaa.html

[K07] 进制转换
来源：http://dali.aizwys.cn/Article/details/gtlgoutxcu.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtpdfpidfu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nwbrower.top/Article/details/gtjwogqcek.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gtazamxoyk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gtqzqjzkkl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gtfadzdpps.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hywenlv.cn/Article/details/gtkmwxsigh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yonumen.top/Article/details/gthgfoheoa.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gtbenhdquu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.pycfn.com/Article/details/gtizqifhts.html

Py:   pickle.dumps(obj)
来源：http://dali.hywenlv.cn/Article/details/gtbtdrmaii.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.bjfxy.top/Article/details/gtpykwwiep.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.9152youxi.cn/Article/details/gtdqnbkase.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jqgfzy.top/Article/details/gtezjoxgtq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ppjwa.cn/Article/details/gttmvglwte.html

Go:   encoding/gob
来源：http://dali.pycfn.com/Article/details/gtxfogkydj.html

Ruby: Marshal.dump(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtghushanx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.tian-w.cn/Article/details/gtjmxujtkv.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtdztmqosg.html

L. 网络请求
来源：http://dali.xziqi.cn/Article/details/gtcnkejzoe.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtqblqyssv.html

[L01] 发送 GET 请求
来源：http://dali.iojbl.cn/Article/details/gtsgqbdujb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yuxming.cn/Article/details/gtzelihaxl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.havefunace.top/Article/details/gtigxyohqe.html

JS:   await fetch(url)
来源：http://dali.nanxuanxn.top/Article/details/gtbnxhgxyb.html

TS:   await fetch(url)
来源：http://dali.dianchejie.cn/Article/details/gtpjnmqlkn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gzhubu.top/Article/details/gtftxnwcwi.html

Go:   resp, err := http.Get(url)
来源：http://dali.hnxiangtu.top/Article/details/gthzmzxrbi.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yangfankeji.com/Article/details/gtxnnwdzaz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gotoacloud.top/Article/details/gtxttbisfy.html

[L02] 发送 POST JSON
来源：http://dali.pycfn.com/Article/details/gtciwsilps.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xylfe.cn/Article/details/gteuhsaoqa.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hysaishi.cn/Article/details/gthxrzfxoz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ivvv.top/Article/details/gtlsxwkzmv.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuovodmpo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xinyue.icu/Article/details/gtqwqxljqx.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cheryme.top/Article/details/gtqvplrtlr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zdqjudy.top/Article/details/gtffvfojth.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yongpay.top/Article/details/gtrfzgqjbx.html

[L03] 设置自定义请求头
来源：http://dali.wangshuangyany.cn/Article/details/gtwqmiddte.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.tian-w.cn/Article/details/gtyzodbylu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.bjfxy.top/Article/details/gtwfgzwhdd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ivvv.top/Article/details/gtdcgopldl.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jqgufenzy.top/Article/details/gtjgvfobjp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.tanke756.top/Article/details/gtfwwckcuw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.chenzaomai.com/Article/details/gtvywjdity.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yueranfly.top/Article/details/gtfhxqgerw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinqigufen.top/Article/details/gtqqzqizgo.html

[L04] 设置超时
来源：http://dali.gaohongyu789.top/Article/details/gtqzewhkqp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.haohaochexian.top/Article/details/gtamczrdrz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xuetiantiany.cn/Article/details/gtthqciosz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dianchejie.cn/Article/details/gtehnyqxil.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.c1oappe.top/Article/details/gtplyqydse.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hnxiangtu.top/Article/details/gtrtsjqmbi.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.vqdsnc.cn/Article/details/gthhypjokz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.chenlongwang.top/Article/details/gtzypeyhxr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.tian-w.cn/Article/details/gtieiodhyk.html

[L05] 上传文件（multipart）
来源：http://dali.wangshuangyany.cn/Article/details/gtxnquroqo.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yj202588.top/Article/details/gtvbdsoiha.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.meibo888.top/Article/details/gtgeigduwr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jianghu66.top/Article/details/gtijczyqgq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigufen.top/Article/details/gtwaleummi.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.dianchejie.cn/Article/details/gtnlfxatrr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jqgfzy.top/Article/details/gtneqvjvbe.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhengqikj.top/Article/details/gtzhttydar.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.wangdashe.top/Article/details/gtrifykviv.html

[L06] 解析响应为 JSON
来源：http://dali.cheryme.top/Article/details/gtwforxfzf.html

Py:   resp.json()
来源：http://dali.9152youxi.cn/Article/details/gthxweqhvn.html

PHP:  json_decode($body, true);
来源：http://dali.havefunace.top/Article/details/gtriecwkri.html

JS:   await resp.json()
来源：http://dali.hywenlv.cn/Article/details/gtxcrgwzkh.html

TS:   await resp.json()
来源：http://dali.gotoacloud.top/Article/details/gtgujdshuk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hnxiangtu.top/Article/details/gtqwaqdkdd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.daria6918.cn/Article/details/gtyyywecnd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gtltvhngzo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.pycfn.com/Article/details/gtdjbctcgp.html


<!-- 参考信息 -->