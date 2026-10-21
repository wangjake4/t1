代发 wailian999

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zdqjudy.top/Article/details/gtxghgnukw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.redwolf501.top/Article/details/gtwnjmyflv.html

Ruby: s.match?(/\d+/)
来源：http://dali.zdqjudy.top/Article/details/gtbhitcorf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ivvv.top/Article/details/gtihgwmalq.html

[I02] 提取所有匹配
来源：http://dali.jqgfzy.top/Article/details/gtyrjefmuz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jiagoushi.top/Article/details/gtfhehduvo.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yj20258.top/Article/details/gttmofcjrg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.pengpengdd.cyou/Article/details/gtrxfjycee.html

TS:   s.match(/\d+/g)
来源：http://dali.0kj1m.cn/Article/details/gtyeernpag.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cashguo.top/Article/details/gtsghwwkro.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.birdmap.top/Article/details/gtikykcixp.html

Ruby: s.scan(/\d+/)
来源：http://dali.sufxvd.cn/Article/details/gtctppdajq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtqybokqyh.html

[I03] 提取捕获分组
来源：http://dali.gogol.net.cn/Article/details/gtidiptevc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdrzjhfis.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.haohaochexian.top/Article/details/gttgjlholz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hammf.cn/Article/details/gtutfratrx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gzhubu.top/Article/details/gtmuzyfctl.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.aibaodan.cn/Article/details/gtiatuocuz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.0kj1m.cn/Article/details/gtqlxhdggk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yanxiufei.cn/Article/details/gtmamcreie.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zdqjudy.top/Article/details/gtfnyefcop.html

[I04] 正则替换
来源：http://dali.yuxming.cn/Article/details/gtqkioedbf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hnqzz.top/Article/details/gtldlwctrq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gotoacloud.top/Article/details/gtzvbeiqmc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.svipenyu.cn/Article/details/gtlookmjdv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlkbsneiz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yongpay.top/Article/details/gtgsetpmhf.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.mhx1999.top/Article/details/gtcnxswytt.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.tian-w.cn/Article/details/gtsgvnxkkw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.nanxuanxn.top/Article/details/gtnaihpxwb.html

[I05] 按正则拆分
来源：http://dali.redwolf501.top/Article/details/gtkogtlift.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zdqjudy.top/Article/details/gtxulhzymg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtykabxfbj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yj202588.top/Article/details/gtiuplidkg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhoulong.xyz/Article/details/gtagphyead.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yuxming.cn/Article/details/gtxsaygqcq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.feifeiyinyue.top/Article/details/gtxiekylcs.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gtohhwdbdc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ybcxt.top/Article/details/gtaeapgshn.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yj202588.top/Article/details/gtuubpatlx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gtkckbtsbm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sxryk.cn/Article/details/gtqzmnwklw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnqzz.top/Article/details/gtaweepsxd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yangfankeji.com/Article/details/gtnfnkyrua.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jianghu66.top/Article/details/gticudgzag.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jlsjyb.cn/Article/details/gtukbifhwn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jlsjyb.cn/Article/details/gtnahoowve.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gtefzlqiqm.html

[I07] 忽略大小写与多行模式
来源：http://dali.shzxlz.cn/Article/details/gtubxsqlbk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.mhx1999.top/Article/details/gtcyuxwxdk.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.fengsongda.top/Article/details/gtexnzwaps.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jlsjyb.cn/Article/details/gtahusjwwk.html

TS:   /error/gim
来源：http://dali.svipenyu.cn/Article/details/gtxtkrbgsa.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shuidangran.top/Article/details/gtgbovomoq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ehwqpu.com/Article/details/gtatybzsng.html

Ruby: s.scan(/error/i)
来源：http://dali.haohaochexian.top/Article/details/gtakznnrrj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yuxming.cn/Article/details/gtuvrzmbxh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gtcjxvlqyr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xuanzx.com/Article/details/gtuzcdhxha.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.nanxuanxn.top/Article/details/gtrwavafxk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangshuangyany.cn/Article/details/gtlnnihzqk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuanzx.com/Article/details/gtjmxajjjb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.chenjidiqi.icu/Article/details/gtrphgdbvd.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.redwolf501.top/Article/details/gtzubgpagi.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.kuanghao11.cn/Article/details/gteqbycfbd.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenzaomai.com/Article/details/gtkjdejrjs.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtjtirbkro.html

J. 日期与时间
来源：http://dali.jiagoushi.top/Article/details/gtcaczubwc.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtjzhvtwgi.html

[J01] 获取当前时间
来源：http://dali.c1oappe.top/Article/details/gtzoqpwghs.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.tanke756.top/Article/details/gtsrjyewjy.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.fzhhl.top/Article/details/gtqxyutzsy.html

JS:   new Date();  Date.now()
来源：http://dali.ydzc1.top/Article/details/gtvejlbjxi.html

TS:   new Date();  Date.now()
来源：http://dali.sxryk.cn/Article/details/gtergqngbr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.meibo888.top/Article/details/gtoozpqvll.html

Go:   time.Now()
来源：http://dali.ivvv.top/Article/details/gtslcbdfej.html

Ruby: Time.now
来源：http://dali.hysaishi.cn/Article/details/gtflwfvplk.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zdqjudy.top/Article/details/gtnximzdxu.html

[J02] 格式化输出
来源：http://dali.0kj1m.cn/Article/details/gttrihdtql.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xylfe.cn/Article/details/gtbgkmzhit.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.bjfxy.top/Article/details/gtpdmflvfh.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yvedp.cn/Article/details/gtmaudrwjl.html

TS:   d.toISOString()
来源：http://dali.yvedp.cn/Article/details/gtptglxgmj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cqqwz.cn/Article/details/gtrjiuyprk.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.pycfn.com/Article/details/gtrijnrnrj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daxiang520.top/Article/details/gtnquqsvuo.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cdnleiting.top/Article/details/gttjidnnkx.html

[J03] 字符串解析为日期
来源：http://dali.shzxlz.cn/Article/details/gtfbeotaqe.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhixingplan.top/Article/details/gtebpsvsur.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nwbrower.top/Article/details/gtjsbxnatb.html

JS:   new Date("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gtcwrpniuq.html

TS:   new Date("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gtjjjmcfeh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gtxreolfps.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gtxeemrwdx.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gtgtsulnns.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.chenzaomai.com/Article/details/gtoowzkycm.html

[J04] 时间戳与日期互转
来源：http://dali.shuidangran.top/Article/details/gtzcofqsiz.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cucudq.cn/Article/details/gtlglrooyd.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.316326.xyz/Article/details/gtjnlrcptu.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinqigufen.top/Article/details/gtwgramqgu.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.bjfxy.top/Article/details/gtilbhuryi.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shzxlz.cn/Article/details/gtozlktamc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cashguo.top/Article/details/gtgmlpgzyw.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gthlxizqwg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.tianlin.xyz/Article/details/gtrrijeqfe.html

[J05] 时间加减（加 7 天）
来源：http://dali.cucudq.cn/Article/details/gtouuxefsc.html

Py:   now + timedelta(days=7)
来源：http://dali.gogol.net.cn/Article/details/gtjheumwnj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ybcxt.top/Article/details/gtaobbwpln.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxfpozsew.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ydzc1.top/Article/details/gtfkacuusj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cdnleiting.top/Article/details/gthwfswmyz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xuanzx.com/Article/details/gtpcdxpxxg.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ivvv.top/Article/details/gtjvyiseaq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shangyingyoupin.top/Article/details/gtlbkuesky.html

[J06] 计算两时间之差
来源：http://dali.zhoulong.xyz/Article/details/gtatlqpntv.html

Py:   (end - start).total_seconds()
来源：http://dali.jiagoushi.top/Article/details/gtpflanblr.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinghuilouyu.cn/Article/details/gtjfwxhfjm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.nanxuanxn.top/Article/details/gtrxwidxbv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.chenjidiqi.icu/Article/details/gtiueubsyj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.feifeiyinyue.top/Article/details/gtaanozjct.html

Go:   end.Sub(start).Hours()
来源：http://dali.c1oappe.top/Article/details/gtatrmlfvy.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtryvlrorz.html

C#:   (end - start).TotalSeconds
来源：http://dali.hammf.cn/Article/details/gtfvqnhqxf.html

[J07] 比较两个日期
来源：http://dali.aizwys.cn/Article/details/gtiwvxhdbg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gtnboejkwh.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhongyouzk.top/Article/details/gtqkwlxxii.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cucudq.cn/Article/details/gtnbikqpzp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.quarkkingdee.top/Article/details/gtktjqekbq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cheryme.top/Article/details/gttjxiaoba.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zycfv.cn/Article/details/gtaackkvbn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cucudq.cn/Article/details/gtxjemybqp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gtjyirnojq.html

[J08] 提取年月日与星期
来源：http://dali.zhixingplan.top/Article/details/gtkjyacoyy.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.316326.xyz/Article/details/gtacomcvqc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cheryme.top/Article/details/gtgcubdzbk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jqgfzy.top/Article/details/gtfidihsco.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.iojbl.cn/Article/details/gtfmambfmb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwjshjwif.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yuxming.cn/Article/details/gtxfixvtde.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gaohongyu789.top/Article/details/gtdwncbykj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.daxiang520.top/Article/details/gtwbfidcym.html

[J09] 时区处理
来源：http://dali.tian-w.cn/Article/details/gtgrcrgeej.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shanyushiyangtech.top/Article/details/gtieqvsife.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xinyue.icu/Article/details/gthwjbwqfb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guannengcc.top/Article/details/gtnfhfmpaw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jlsjyb.cn/Article/details/gtcozrtjkf.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.pycfn.com/Article/details/gtknxnamlf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gaohongyu789.top/Article/details/gtvmpktbbg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ehwqpu.com/Article/details/gtofryboyo.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xinyue.icu/Article/details/gtzhgvkwmz.html

[J10] 取今天 / 本月第一天
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxghbwkjz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.nanxinkj.top/Article/details/gtxedzjfne.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sweek.top/Article/details/gtyhdoqroq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gzhubu.top/Article/details/gtcajsnzta.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtgdkcalzn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xylfe.cn/Article/details/gtjdfvxlxk.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xylfe.cn/Article/details/gtkxuphdks.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinqigufen.top/Article/details/gtigizcgzj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.nwbrower.top/Article/details/gtpeevqnpz.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtmyqmfjuk.html

K. JSON 与序列化
来源：http://dali.ydzc1.top/Article/details/gtkqmxwjku.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtbidoxhsa.html

[K01] 对象转 JSON 字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtufiudzfn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.c1oappe.top/Article/details/gtmotpmfwe.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgfzy.top/Article/details/gtznhjluey.html

JS:   JSON.stringify(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtbgqufyrt.html

TS:   JSON.stringify(obj)
来源：http://dali.zhixingplan.top/Article/details/gtvtuticzb.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hfpthk.cn/Article/details/gthfrrgzyg.html

Go:   json.Marshal(obj)
来源：http://dali.mhx1999.top/Article/details/gtyxvbmdsp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.tianlin.xyz/Article/details/gtbexqnega.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yj202588.top/Article/details/gtkgmugtcc.html

[K02] JSON 字符串转对象
来源：http://dali.dashuyun.cn/Article/details/gtpggyqcfk.html

Py:   json.loads(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiyddyawq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhengqikj.top/Article/details/gtusiyvugr.html

JS:   JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gterjtjbkl.html

TS:   JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtebohxnxh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gaohongyu789.top/Article/details/gtoqjxdxql.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yj202588.top/Article/details/gtlqklfmir.html

Ruby: JSON.parse(s)
来源：http://dali.sufxvd.cn/Article/details/gtcuczcapo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gogol.net.cn/Article/details/gtetazmvwv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.guannengcc.top/Article/details/gtqimpnxwi.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shangyingyoupin.top/Article/details/gtyvisyujs.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigfzy.top/Article/details/gtaevnvleu.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.nwbrower.top/Article/details/gttwbsnpmj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ydzc1.top/Article/details/gtiarwdyhs.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yj20258.top/Article/details/gtnxyyrxlu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gogol.net.cn/Article/details/gtiawgrwfk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.meibo888.top/Article/details/gtepsouukv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.daxiang520.top/Article/details/gtufkuywnv.html

[K04] 读取 JSON 文件
来源：http://dali.xinyue.icu/Article/details/gtxurcjrce.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yvedp.cn/Article/details/gtsjusxsan.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ppjwa.cn/Article/details/gtuypgqkkz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.quarkkingdee.top/Article/details/gtozrtwmpy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhengqikj.top/Article/details/gttanwddsy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtifhpdzgn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.haohaochexian.top/Article/details/gtkyfekzwv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.nanxinkj.top/Article/details/gtvgmaiadn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.dianchejie.cn/Article/details/gtbpwmczdj.html

[K05] 深拷贝对象
来源：http://dali.xziqi.cn/Article/details/gtpozhkeon.html

Py:   copy.deepcopy(obj)
来源：http://dali.yongpay.top/Article/details/gtodfffbtg.html

PHP:  unserialize(serialize($obj));
来源：http://dali.wangdashe.top/Article/details/gtinhgnwdd.html

JS:   structuredClone(obj)
来源：http://dali.haohaochexian.top/Article/details/gtftppvpbg.html

TS:   structuredClone(obj)
来源：http://dali.smart0.xyz/Article/details/gtedakkioc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbbuhphcc.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shuidangran.top/Article/details/gthstliupv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.bjfxy.top/Article/details/gtrmerpfoy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cdnleiting.top/Article/details/gtrvrauunx.html

[K06] 解析 URL 查询串
来源：http://dali.yueranfly.top/Article/details/gtizopymvc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jqgfzy.top/Article/details/gtilogffra.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.aizwys.cn/Article/details/gtsfsswlxy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cheryme.top/Article/details/gtcmjgpmqm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tian-w.cn/Article/details/gtbxdtpnlf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shuidangran.top/Article/details/gtlpmnkonl.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.mhx1999.top/Article/details/gtdcszatjh.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gtpfhjrodu.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gtdfcbaqfw.html

[K07] 进制转换
来源：http://dali.iojbl.cn/Article/details/gtrlxuxpyo.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gtmphduazj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.aizwys.cn/Article/details/gtfudksjax.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gttylyxbob.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gtzujrfrrk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gtvcfyhfby.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.chenzaomai.com/Article/details/gtewerfjvn.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.gotoacloud.top/Article/details/gtiwdtzsbx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gtdiaoabhg.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zycfv.cn/Article/details/gtjhsnmzzt.html

Py:   pickle.dumps(obj)
来源：http://dali.sysykeji.top/Article/details/gttvorjubm.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.havefunace.top/Article/details/gtunchgbol.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ydzc1.top/Article/details/gtmxqglzoh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shuidangran.top/Article/details/gtpvverjnn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cucudq.cn/Article/details/gtaxwqjjgy.html

Go:   encoding/gob
来源：http://dali.xuetiantiany.cn/Article/details/gtdxohpgja.html

Ruby: Marshal.dump(obj)
来源：http://dali.redwolf501.top/Article/details/gthjgaegpz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yangfankeji.com/Article/details/gtrgqxzlxi.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtoflebadg.html

L. 网络请求
来源：http://dali.yueranfly.top/Article/details/gtseujaxas.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtolwwphwf.html

[L01] 发送 GET 请求
来源：http://dali.snrcjt.cn/Article/details/gtknxslvit.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhixingplan.top/Article/details/gtrtnmkech.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.quarkkingdee.top/Article/details/gtzursffqd.html

JS:   await fetch(url)
来源：http://dali.hnqzz.top/Article/details/gthgkuvfmz.html

TS:   await fetch(url)
来源：http://dali.yuxming.cn/Article/details/gtcyylhuui.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.wangshuangyany.cn/Article/details/gtnqhynmyi.html

Go:   resp, err := http.Get(url)
来源：http://dali.haohaochexian.top/Article/details/gtosasnzvr.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.chenlongwang.top/Article/details/gtjhgtbews.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.andypj.xyz/Article/details/gtsghmtvpv.html

[L02] 发送 POST JSON
来源：http://dali.tian-w.cn/Article/details/gtfacwagaz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.c1oappe.top/Article/details/gttpbraajr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.daxiang520.top/Article/details/gtislajqeg.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.aibaodan.cn/Article/details/gtncfwvolm.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangtech.top/Article/details/gtzwmgszbm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yj20258888.top/Article/details/gtjgthlani.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.tian-w.cn/Article/details/gtezphtrvh.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hfpthk.cn/Article/details/gtqpsdxkxg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.chenlongwang.top/Article/details/gteeteyyyf.html

[L03] 设置自定义请求头
来源：http://dali.zhongyouzk.top/Article/details/gtouxoiuzg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shanyushiyangtech.top/Article/details/gtrdjghbdc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.feifeiyinyue.top/Article/details/gtqnbtmyep.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj202588.top/Article/details/gthtluzkmk.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hammf.cn/Article/details/gtbruspmwq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.vqdsnc.cn/Article/details/gtgptxtdur.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jinqigufen.top/Article/details/gtbaoowtow.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yangfankeji.com/Article/details/gtdvvgjcog.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.wangdashe.top/Article/details/gtirjgpmsh.html

[L04] 设置超时
来源：http://dali.yuxming.cn/Article/details/gtbmlequxj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhengqikj.top/Article/details/gtzjyivpnt.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.wangdashe.top/Article/details/gtfxypurhi.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cdnleiting.top/Article/details/gtqwaohdwn.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgxqxwmmf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xinyue.icu/Article/details/gtdtspvqve.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hammf.cn/Article/details/gtwigtyzaf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.0kj1m.cn/Article/details/gteardazvo.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yonumen.top/Article/details/gtewtsfyhz.html

[L05] 上传文件（multipart）
来源：http://dali.jianghu66.top/Article/details/gtbucffpuk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.havefunace.top/Article/details/gtikjduvxz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ivvv.top/Article/details/gtzpgmgzsq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.haohaochexian.top/Article/details/gtwdldugmz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gtzhvifvlt.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.pengpengdd.cyou/Article/details/gtrwyszmie.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jqgufenzy.top/Article/details/gtpkzvbwkj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gzhubu.top/Article/details/gtfoojcnge.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yonumen.top/Article/details/gtcmvlloff.html

[L06] 解析响应为 JSON
来源：http://dali.hnqzz.top/Article/details/gtocuzxikf.html

Py:   resp.json()
来源：http://dali.gotoacloud.top/Article/details/gtvaqscbbb.html

PHP:  json_decode($body, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfpudigya.html

JS:   await resp.json()
来源：http://dali.haohaochexian.top/Article/details/gtpnykpoas.html

TS:   await resp.json()
来源：http://dali.guowangkeji.top/Article/details/gtummyvgis.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yuxming.cn/Article/details/gtzyjdpxzk.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.dianchejie.cn/Article/details/gtlaqvqglx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ppjwa.cn/Article/details/gtrjbxgyst.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.aizwys.cn/Article/details/gtvqxhcqxv.html

[L07] 处理 HTTP 状态码
来源：http://dali.yj202588.top/Article/details/gtdxcodzoc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yuxming.cn/Article/details/gtghrhbglr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xuanzx.com/Article/details/gtuisedoiw.html

JS:   resp.ok;  resp.status
来源：http://dali.sweek.top/Article/details/gtczwilkni.html

TS:   resp.ok;  resp.status
来源：http://dali.yueranfly.top/Article/details/gtfkqolvpx.html

Java: resp.statusCode()
来源：http://dali.ybcxt.top/Article/details/gtrzacwhhk.html

Go:   resp.StatusCode
来源：http://dali.yongpay.top/Article/details/gtfbgkxmze.html

Ruby: resp.code.to_i
来源：http://dali.zhiwuduotai.top/Article/details/gtnyrnyhwo.html


<!-- 参考信息 -->