代发 wailian999

[I02] 提取所有匹配
来源：http://dali.yj202588.top/Article/details/gtikrcilny.html

Py:   re.findall(r"\d+", s)
来源：http://dali.316326.xyz/Article/details/gtqncilpfl.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yj20258888.top/Article/details/gtsmhpwmxm.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ybcxt.top/Article/details/gtelxuznsf.html

TS:   s.match(/\d+/g)
来源：http://dali.hysaishi.cn/Article/details/gtaugxkgmg.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.0kj1m.cn/Article/details/gtjsvjtjuk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.tian-w.cn/Article/details/gtsbzuiofr.html

Ruby: s.scan(/\d+/)
来源：http://dali.haohaochexian.top/Article/details/gtjzicmony.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.c1oappe.top/Article/details/gtcmuwkjmb.html

[I03] 提取捕获分组
来源：http://dali.zdqjudy.top/Article/details/gtifwcitqu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hnqzz.top/Article/details/gtmckozzgs.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xuetiantiany.cn/Article/details/gtlbaxofzd.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shangyingyoupin.top/Article/details/gtgcbxqetj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sweek.top/Article/details/gtoyojmpih.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cashguo.top/Article/details/gtdxcsbsqc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jiagoushi.top/Article/details/gtxcqqpajx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.dianchejie.cn/Article/details/gtwspvilnt.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yonumen.top/Article/details/gtwnusmolc.html

[I04] 正则替换
来源：http://dali.hnqzz.top/Article/details/gtdtvckboe.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ybcxt.top/Article/details/gtbgfrojrg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ybcxt.top/Article/details/gtaudpfqbe.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sxryk.cn/Article/details/gtnbqzdgcj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yuxming.cn/Article/details/gtswrlgukt.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yuanzhike.top/Article/details/gtgqhzewmn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yj20258.top/Article/details/gtbfqqjzse.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xinyue.icu/Article/details/gtkjhfmbow.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.tian-w.cn/Article/details/gtleigvjwy.html

[I05] 按正则拆分
来源：http://dali.shuidangran.top/Article/details/gtolpqdyeq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yj20258.top/Article/details/gtdlynduoj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jqgfzy.top/Article/details/gtgjhjdwif.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.fengsongda.top/Article/details/gtnaxfeqml.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.quarkkingdee.top/Article/details/gtgpggdobs.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yonumen.top/Article/details/gtxbwwipir.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hongshengwenyu.top/Article/details/gtoxhtpscn.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jianghu66.top/Article/details/gtbmxqwtlf.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.vqdsnc.cn/Article/details/gtsntsivrw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhongyouzk.top/Article/details/gthqvjagod.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xinyue.icu/Article/details/gtikpqwgzx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jiagoushi.top/Article/details/gtanwgdhfv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuanzx.com/Article/details/gtjdstevje.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ivvv.top/Article/details/gtxliurmno.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj20258.top/Article/details/gtwdwvuswb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yongpay.top/Article/details/gtqdoqunwx.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cashguo.top/Article/details/gtudhgfhaq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.andypj.xyz/Article/details/gtjgsldggv.html

[I07] 忽略大小写与多行模式
来源：http://dali.daxiang520.top/Article/details/gtcaxdsjzq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.chenlongwang.top/Article/details/gtwdnwwhow.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ybcxt.top/Article/details/gtdzigekpn.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hywenlv.cn/Article/details/gtfcvlvdrq.html

TS:   /error/gim
来源：http://dali.yj20258.top/Article/details/gtfuajqwwi.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.daria6918.cn/Article/details/gtqhkuuyjr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.chenzaomai.com/Article/details/gtpbpqokti.html

Ruby: s.scan(/error/i)
来源：http://dali.redwolf501.top/Article/details/gthaohxhuv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.dashuyun.cn/Article/details/gtyklmabko.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.snrcjt.cn/Article/details/gtkbabphun.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.haohaochexian.top/Article/details/gtnsvewsmd.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ehwqpu.com/Article/details/gtiqltsxwp.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pengpengdd.cyou/Article/details/gtwualbpnd.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zycfv.cn/Article/details/gtpkokqoob.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shuidangran.top/Article/details/gtjbuohfeq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.birdmap.top/Article/details/gtcdrhgclo.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.snrcjt.cn/Article/details/gtqlpefxpr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cheryme.top/Article/details/gtvgnqvsgr.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtdtimhkec.html

J. 日期与时间
来源：http://dali.jinghuilouyu.cn/Article/details/gtaynkbmnb.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtripcbhqf.html

[J01] 获取当前时间
来源：http://dali.quarkkingdee.top/Article/details/gtpuhzgphz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ehwqpu.com/Article/details/gtsilwvuos.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hfpthk.cn/Article/details/gtgljtksac.html

JS:   new Date();  Date.now()
来源：http://dali.fzhhl.top/Article/details/gtzmfnxnnx.html

TS:   new Date();  Date.now()
来源：http://dali.fzhhl.top/Article/details/gtmiljmrho.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.feifeiyinyue.top/Article/details/gtynepzyoz.html

Go:   time.Now()
来源：http://dali.yanxiufei.cn/Article/details/gtshscvsto.html

Ruby: Time.now
来源：http://dali.daxiang520.top/Article/details/gtllszwevo.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhoulong.xyz/Article/details/gtenefgjim.html

[J02] 格式化输出
来源：http://dali.dashuyun.cn/Article/details/gtzslqmhmw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.meibo888.top/Article/details/gtsackzjtj.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.redwolf501.top/Article/details/gtkuycfvci.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.tianlin.xyz/Article/details/gtxfzznatc.html

TS:   d.toISOString()
来源：http://dali.fengsongda.top/Article/details/gtvommitbm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nanxuanxn.top/Article/details/gtburwsmdz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtniacqjne.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhengqikj.top/Article/details/gtfzrqbjug.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shzxlz.cn/Article/details/gtkkbvkeik.html

[J03] 字符串解析为日期
来源：http://dali.hammf.cn/Article/details/gtyaqgvovs.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gzhubu.top/Article/details/gtisausntm.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jianghu66.top/Article/details/gtllntlsdu.html

JS:   new Date("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtonxixnun.html

TS:   new Date("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gthpaxhvfi.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gtmisztsmb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gtbacvcbad.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtptygpiln.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xinyue.icu/Article/details/gtaruzonem.html

[J04] 时间戳与日期互转
来源：http://dali.shzxlz.cn/Article/details/gtevtuspzk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.316326.xyz/Article/details/gtunaqmiia.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xuetiantiany.cn/Article/details/gtezhpwwrc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.316326.xyz/Article/details/gtprlfkgee.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ppjwa.cn/Article/details/gttxnczvbg.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhongyouzk.top/Article/details/gtfdklqsos.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.mhx1999.top/Article/details/gtxpklufhp.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shuidangran.top/Article/details/gtbkcxqpzi.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xuanzx.com/Article/details/gtdwrfwfct.html

[J05] 时间加减（加 7 天）
来源：http://dali.gaohongyu789.top/Article/details/gtriqmtntz.html

Py:   now + timedelta(days=7)
来源：http://dali.guowangkeji.top/Article/details/gtcfpasuca.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.nanxuanxn.top/Article/details/gtpbdhtgky.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gogol.net.cn/Article/details/gtyefbixxw.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shzxlz.cn/Article/details/gtxlrcidkx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xziqi.cn/Article/details/gtlzxhazxw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.haohaochexian.top/Article/details/gtisuiawtu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.tanke756.top/Article/details/gtnjhwxrzy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hysaishi.cn/Article/details/gtjhetbsgl.html

[J06] 计算两时间之差
来源：http://dali.wangshuangyany.cn/Article/details/gtvksqvkjr.html

Py:   (end - start).total_seconds()
来源：http://dali.aibaodan.cn/Article/details/gttultqaiy.html

PHP:  $end->diff($start)->days;
来源：http://dali.yj20258.top/Article/details/gtbkivzion.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhixingplan.top/Article/details/gtxkpsncls.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zdqjudy.top/Article/details/gtwatdhfob.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cqqwz.cn/Article/details/gtryteaqfx.html

Go:   end.Sub(start).Hours()
来源：http://dali.sufxvd.cn/Article/details/gtilejovyx.html

Ruby: end - start                 # 返回秒数
来源：http://dali.iojbl.cn/Article/details/gtrygytjmg.html

C#:   (end - start).TotalSeconds
来源：http://dali.jiagoushi.top/Article/details/gtkiythsyt.html

[J07] 比较两个日期
来源：http://dali.zhoulong.xyz/Article/details/gtxfgcrfox.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xziqi.cn/Article/details/gtdmcyzvrn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cucudq.cn/Article/details/gtmdllivaw.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhoulong.xyz/Article/details/gtwqwcwtjy.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yj202588.top/Article/details/gtyhvqtyyi.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gotoacloud.top/Article/details/gtrxbsrcii.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjohxzlxc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ybcxt.top/Article/details/gtfreaubgv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.pengpengdd.cyou/Article/details/gtjpffatcp.html

[J08] 提取年月日与星期
来源：http://dali.havefunace.top/Article/details/gtzymzztis.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.birdmap.top/Article/details/gtcowniaun.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zdqjudy.top/Article/details/gtcyznlxvy.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenjidiqi.icu/Article/details/gtuiqkbvbb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tanke756.top/Article/details/gthvocuejt.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zdqjudy.top/Article/details/gtknrnmuen.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.wangshuangyany.cn/Article/details/gtptkuirbl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hywenlv.cn/Article/details/gtsozifevs.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqpphocms.html

[J09] 时区处理
来源：http://dali.hammf.cn/Article/details/gttktcuwwi.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.chenzaomai.com/Article/details/gtjemnboyo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cdnleiting.top/Article/details/gtrqkxadoa.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cdnleiting.top/Article/details/gtggenmram.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cqqwz.cn/Article/details/gtsybgyqku.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gogol.net.cn/Article/details/gtvtrwtmlm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhijiandao.cn/Article/details/gtsrfabhgq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.kuanghao11.cn/Article/details/gtoyaeorzu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenjidiqi.icu/Article/details/gtefrqgsvs.html

[J10] 取今天 / 本月第一天
来源：http://dali.pycfn.com/Article/details/gtmrkdwdmg.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjwpzsysi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xziqi.cn/Article/details/gtekocoqun.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.c1oappe.top/Article/details/gtyvymlogk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hammf.cn/Article/details/gtgnbbrpti.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.daxiang520.top/Article/details/gtgimxxses.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cqqwz.cn/Article/details/gtrosiqqti.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhongyouzk.top/Article/details/gtlxyjycag.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrjqssvti.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtcxloptuo.html

K. JSON 与序列化
来源：http://dali.aizwys.cn/Article/details/gtowetknyk.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtiynxzupm.html

[K01] 对象转 JSON 字符串
来源：http://dali.redwolf501.top/Article/details/gtkpqohgtu.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.iojbl.cn/Article/details/gtvyubrkep.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.sysykeji.top/Article/details/gtnrnangal.html

JS:   JSON.stringify(obj)
来源：http://dali.dianchejie.cn/Article/details/gtxtbcgrbs.html

TS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsjzprqxj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xinyue.icu/Article/details/gtlqnjpzjf.html

Go:   json.Marshal(obj)
来源：http://dali.shuidangran.top/Article/details/gtpmlygnmp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.redwolf501.top/Article/details/gtgxslbioh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.daria6918.cn/Article/details/gtiieutgos.html

[K02] JSON 字符串转对象
来源：http://dali.guannengcc.top/Article/details/gtobeklrpu.html

Py:   json.loads(s)
来源：http://dali.havefunace.top/Article/details/gtgtyrsnyq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jianghu66.top/Article/details/gtajbvxict.html

JS:   JSON.parse(s)
来源：http://dali.dashuyun.cn/Article/details/gtcgrtoxog.html

TS:   JSON.parse(s)
来源：http://dali.tanke756.top/Article/details/gterxogiqc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbzcycich.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.nanxinkj.top/Article/details/gtvixygtif.html

Ruby: JSON.parse(s)
来源：http://dali.zhoulong.xyz/Article/details/gtquflmsfr.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jqgufenzy.top/Article/details/gtzzrjpzzf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hnxiangtu.top/Article/details/gtrzutzenb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gaohongyu789.top/Article/details/gtguonkvvl.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.quarkkingdee.top/Article/details/gtudywfqkc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhengqikj.top/Article/details/gtdqnrkdoe.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinqigufen.top/Article/details/gtfixutqrl.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.c1oappe.top/Article/details/gtgeydzmlu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.wangdashe.top/Article/details/gtsqtvlvhq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtccykmtkq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.guowangkeji.top/Article/details/gtijsxepkg.html

[K04] 读取 JSON 文件
来源：http://dali.hnqzz.top/Article/details/gtfcgcxqcg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hfpthk.cn/Article/details/gtkeieeois.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yongpay.top/Article/details/gtjrzsgzxl.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.316326.xyz/Article/details/gticnytbhj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jlsjyb.cn/Article/details/gtvaifbcbm.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.chenzaomai.com/Article/details/gtuvacdhtr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yanxiufei.cn/Article/details/gtourwwdfa.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtglfimifq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhongyouzk.top/Article/details/gtbaworwyl.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gtrmihiaeo.html

Py:   copy.deepcopy(obj)
来源：http://dali.cucudq.cn/Article/details/gtamjdqxyt.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cucudq.cn/Article/details/gtkgalmzkt.html

JS:   structuredClone(obj)
来源：http://dali.tian-w.cn/Article/details/gtamiiblqq.html

TS:   structuredClone(obj)
来源：http://dali.xylfe.cn/Article/details/gtbbilqtse.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ivvv.top/Article/details/gtsrrmtwcg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.chenjidiqi.icu/Article/details/gtyvwrtqts.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yj20258.top/Article/details/gtaqlzsopd.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinghuilouyu.cn/Article/details/gtzwdatfkm.html

[K06] 解析 URL 查询串
来源：http://dali.shanyushiyangtech.top/Article/details/gtpiupemcu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ehwqpu.com/Article/details/gtqdqnltym.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.mhx1999.top/Article/details/gtmfszepsr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shangyingyoupin.top/Article/details/gtnepgawzj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuetiantiany.cn/Article/details/gttrulffkb.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gogol.net.cn/Article/details/gtsxdsovah.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yj202588.top/Article/details/gtnumxidmf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yangfankeji.com/Article/details/gthfhgwrpl.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gtefmrqgbu.html

[K07] 进制转换
来源：http://dali.jqgufenzy.top/Article/details/gtbhlapagk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gtzoiwwadk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.aizwys.cn/Article/details/gtbhpzxtdx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gthevkcmfl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yonumen.top/Article/details/gtguxyzdei.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gtyopovlmg.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cdnleiting.top/Article/details/gtmkehqgjp.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.dashuyun.cn/Article/details/gtjoxhxlwk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gtufouuqeu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yongpay.top/Article/details/gtnxrsrzpl.html

Py:   pickle.dumps(obj)
来源：http://dali.c1oappe.top/Article/details/gtvmatftoj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jlsjyb.cn/Article/details/gtetqevglm.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.316326.xyz/Article/details/gtiumqsnnd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yongpay.top/Article/details/gtbzztgbsx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.mhx1999.top/Article/details/gtblhykkcn.html

Go:   encoding/gob
来源：http://dali.jlsjyb.cn/Article/details/gtyliacvkn.html

Ruby: Marshal.dump(obj)
来源：http://dali.tian-w.cn/Article/details/gtptrkabmy.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yanxiufei.cn/Article/details/gtcaivluxh.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtydsveogm.html

L. 网络请求
来源：http://dali.zhoulong.xyz/Article/details/gtynfbmnjy.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtoexcebuf.html

[L01] 发送 GET 请求
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpfuywpqv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.9152youxi.cn/Article/details/gttbuplevr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hongshengwenyu.top/Article/details/gtmismhiin.html

JS:   await fetch(url)
来源：http://dali.fzhhl.top/Article/details/gtleruhsxx.html

TS:   await fetch(url)
来源：http://dali.redwolf501.top/Article/details/gtujjdpodu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.wangshuangyany.cn/Article/details/gtfdgryluj.html

Go:   resp, err := http.Get(url)
来源：http://dali.jyoumei.cn/Article/details/gtcrdxliww.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.chenzaomai.com/Article/details/gtgjmptibu.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gotoacloud.top/Article/details/gtvraxbdne.html

[L02] 发送 POST JSON
来源：http://dali.yj20258888.top/Article/details/gtxrwqlxqp.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.vqdsnc.cn/Article/details/gtbgbyzbsd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cucudq.cn/Article/details/gtefqzmdwe.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj202588.top/Article/details/gtcuzyzmuw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sxryk.cn/Article/details/gtbttvbjxd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cqqwz.cn/Article/details/gtaanpwxpv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.nanxuanxn.top/Article/details/gteyzgotxw.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.wangdashe.top/Article/details/gtpyxvsmaa.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.aizwys.cn/Article/details/gttbukifwm.html

[L03] 设置自定义请求头
来源：http://dali.xziqi.cn/Article/details/gtqgvhlbep.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.haohaochexian.top/Article/details/gttmyqgwnj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.bjfxy.top/Article/details/gtciwriihe.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yanxiufei.cn/Article/details/gtuyjddjoz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.quarkkingdee.top/Article/details/gthllnaqhv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.316326.xyz/Article/details/gtlnytfyoc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jqgufenzy.top/Article/details/gtcptxfjdt.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yanxiufei.cn/Article/details/gtxzoveeen.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jyoumei.cn/Article/details/gttbtywkvo.html

[L04] 设置超时
来源：http://dali.aizwys.cn/Article/details/gtbhdnpmrh.html

Py:   requests.get(url, timeout=5)
来源：http://dali.nwbrower.top/Article/details/gtpfxitksq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.feifeiyinyue.top/Article/details/gthizevkjl.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuanzhike.top/Article/details/gtzabograv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fengsongda.top/Article/details/gtcbqgvvaz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jqgufenzy.top/Article/details/gtivzcshkl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ehwqpu.com/Article/details/gtccflyeye.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yj20258888.top/Article/details/gtqocctzby.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ppjwa.cn/Article/details/gtiohbjmmx.html

[L05] 上传文件（multipart）
来源：http://dali.meibo888.top/Article/details/gtgymwgnom.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.fzhhl.top/Article/details/gtyptgbkgo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jqgufenzy.top/Article/details/gtfntckgoc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhoulong.xyz/Article/details/gtwuldbcgn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.guannengcc.top/Article/details/gthqptdykd.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.dashuyun.cn/Article/details/gtuuvvmszf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zycfv.cn/Article/details/gtrhmtprfe.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.tian-w.cn/Article/details/gtxeglfbaq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gthfsmwptn.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gtvxfjrnng.html

Py:   resp.json()
来源：http://dali.yvedp.cn/Article/details/gtdgtpviut.html

PHP:  json_decode($body, true);
来源：http://dali.chenlongwang.top/Article/details/gttaubllsv.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gtzisppxoj.html

TS:   await resp.json()
来源：http://dali.zhengqikj.top/Article/details/gtgxrozcqb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhongyouzk.top/Article/details/gtzddmuawt.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cdnleiting.top/Article/details/gtjcrphekq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hfpthk.cn/Article/details/gtwyecmzve.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.aizwys.cn/Article/details/gtpzsxzurl.html

[L07] 处理 HTTP 状态码
来源：http://dali.smart0.xyz/Article/details/gtmezaqizv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yongpay.top/Article/details/gtjxbwznhu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhixingplan.top/Article/details/gtkzqcqspz.html

JS:   resp.ok;  resp.status
来源：http://dali.nanxuanxn.top/Article/details/gtvetbyycu.html

TS:   resp.ok;  resp.status
来源：http://dali.cheryme.top/Article/details/gtvpqaorgt.html

Java: resp.statusCode()
来源：http://dali.ybcxt.top/Article/details/gtshikanlb.html

Go:   resp.StatusCode
来源：http://dali.andypj.xyz/Article/details/gtcmfxhvdh.html

Ruby: resp.code.to_i
来源：http://dali.shuidangran.top/Article/details/gtgwawuhzu.html

C#:   (int)resp.StatusCode
来源：http://dali.tian-w.cn/Article/details/gtuputwbml.html

[L08] 并发请求多个地址
来源：http://dali.yonumen.top/Article/details/gthgmsfglk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yonumen.top/Article/details/gtkozydzfa.html

PHP:  curl_multi_init() 系列
来源：http://dali.shuidangran.top/Article/details/gtygtjmcxc.html


<!-- 参考信息 -->