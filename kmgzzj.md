代发 wailian999

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.wangdashe.top/Article/details/gtertvrbrq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xuanzx.com/Article/details/gtivqrmhua.html

Ruby: s.match?(/\d+/)
来源：http://dali.jqgfzy.top/Article/details/gtlkajcuzg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cdnleiting.top/Article/details/gtfhoikxke.html

[I02] 提取所有匹配
来源：http://dali.xuetiantiany.cn/Article/details/gthjzjoryp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hfpthk.cn/Article/details/gtdrlrrzbt.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.pengpengdd.cyou/Article/details/gtnwebfgam.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.smart0.xyz/Article/details/gthmpfowma.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gtpnigelie.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cucudq.cn/Article/details/gtmhdnprhl.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yj20258.top/Article/details/gtrvwvubsl.html

Ruby: s.scan(/\d+/)
来源：http://dali.hammf.cn/Article/details/gtgkqjicww.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.daria6918.cn/Article/details/gtscwswjof.html

[I03] 提取捕获分组
来源：http://dali.yonumen.top/Article/details/gtycrilevl.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nanxinkj.top/Article/details/gtlztqmddz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xziqi.cn/Article/details/gtceuyqrpi.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shzxlz.cn/Article/details/gtnuxwnuha.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.tian-w.cn/Article/details/gttcpfariv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.mhx1999.top/Article/details/gtqullwzpb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.feifeiyinyue.top/Article/details/gtdutlwlsj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.chenjidiqi.icu/Article/details/gtodmlwfmu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yonumen.top/Article/details/gthombljuv.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gtioghcadx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hnqzz.top/Article/details/gttysvjgqp.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.guannengcc.top/Article/details/gtyawszhkb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.daxiang520.top/Article/details/gtwxgqbewf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sysykeji.top/Article/details/gtfsdwyyen.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmuvkybcx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cucudq.cn/Article/details/gttdkwqths.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gtignqwvjc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zycfv.cn/Article/details/gtumvxacki.html

[I05] 按正则拆分
来源：http://dali.pycfn.com/Article/details/gtwlhlzbor.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cqqwz.cn/Article/details/gtrytuighd.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtkjwgqwuz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jqgufenzy.top/Article/details/gtbxbxxqge.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.316326.xyz/Article/details/gtslatxshd.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sufxvd.cn/Article/details/gtrysscvgt.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.dashuyun.cn/Article/details/gtcfkwhbks.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.tanke756.top/Article/details/gtkgrhhbcs.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.vqdsnc.cn/Article/details/gtukiidekh.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenzaomai.com/Article/details/gtdtcgkqoy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nwbrower.top/Article/details/gtuhfnrpkk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.guowangkeji.top/Article/details/gtzgqfyvzk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.snrcjt.cn/Article/details/gtljbaiyif.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ehwqpu.com/Article/details/gtxmdfvtxl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.svipenyu.cn/Article/details/gtnafnjptm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.mhx1999.top/Article/details/gtlkymihkq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jqgufenzy.top/Article/details/gtftswhqwa.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yj202588.top/Article/details/gteuvbfhfw.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtydvlmbfh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.nanxinkj.top/Article/details/gthjffybgy.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xylfe.cn/Article/details/gtudthnerf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.guowangkeji.top/Article/details/gtshtduvhn.html

TS:   /error/gim
来源：http://dali.fzhhl.top/Article/details/gtwdaclsgh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhengqikj.top/Article/details/gtslsbiblp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.pengpengdd.cyou/Article/details/gthdvnslyl.html

Ruby: s.scan(/error/i)
来源：http://dali.meibo888.top/Article/details/gtflckyqgl.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.chenjidiqi.icu/Article/details/gtmcnknscm.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.chenzaomai.com/Article/details/gtvzbaqpxj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hysaishi.cn/Article/details/gtmvxqjafy.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.fzhhl.top/Article/details/gtzockgcqt.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ydzc1.top/Article/details/gtlblezwpk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.haohaochexian.top/Article/details/gtyzeivinb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yj202588.top/Article/details/gtrgdxrghf.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.bjfxy.top/Article/details/gtragapwum.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhongyouzk.top/Article/details/gtnfzpbswt.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shangyingyoupin.top/Article/details/gtqsmexvmh.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtpagrpirg.html

J. 日期与时间
来源：http://dali.sxryk.cn/Article/details/gtsjyfjgwr.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtjlusdkbw.html

[J01] 获取当前时间
来源：http://dali.nanxinkj.top/Article/details/gtdrtrftjk.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hammf.cn/Article/details/gtssxjnwph.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shanyushiyangtech.top/Article/details/gtickvqlcm.html

JS:   new Date();  Date.now()
来源：http://dali.mhx1999.top/Article/details/gttrdnygox.html

TS:   new Date();  Date.now()
来源：http://dali.0kj1m.cn/Article/details/gtsjbpsesn.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.svipenyu.cn/Article/details/gtsybraccn.html

Go:   time.Now()
来源：http://dali.sxryk.cn/Article/details/gtgmkurzbq.html

Ruby: Time.now
来源：http://dali.0kj1m.cn/Article/details/gtcwhkmnah.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shanyushiyangtech.top/Article/details/gtpumkchjx.html

[J02] 格式化输出
来源：http://dali.jqgfzy.top/Article/details/gtzwebukdz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sysykeji.top/Article/details/gtholhrapm.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shuidangran.top/Article/details/gtvedsvlsa.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.haohaochexian.top/Article/details/gtwnazwpjk.html

TS:   d.toISOString()
来源：http://dali.yvedp.cn/Article/details/gtqwrxpfgq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jqgfzy.top/Article/details/gtqupjxuoh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.havefunace.top/Article/details/gtjaulaeuh.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zdqjudy.top/Article/details/gthxjnbnhr.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gogol.net.cn/Article/details/gtqyhvzvii.html

[J03] 字符串解析为日期
来源：http://dali.jyoumei.cn/Article/details/gthounsugo.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.aibaodan.cn/Article/details/gtqejnufbs.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.daria6918.cn/Article/details/gtwykupnkf.html

JS:   new Date("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gtoyyoguab.html

TS:   new Date("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtqqpofuiw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gtumxmfmjj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gtaujpszbk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gtnijpdwho.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.tian-w.cn/Article/details/gthgkwnqfl.html

[J04] 时间戳与日期互转
来源：http://dali.c1oappe.top/Article/details/gtyevqnmbu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ehwqpu.com/Article/details/gtucakvnzt.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.smart0.xyz/Article/details/gtisdgjwph.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cheryme.top/Article/details/gtmnvjlaue.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.havefunace.top/Article/details/gtkllteyuv.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmrfaoudb.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sxryk.cn/Article/details/gtjufclyoh.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shzxlz.cn/Article/details/gtdsnyuxgq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.feifeiyinyue.top/Article/details/gtljbykwka.html

[J05] 时间加减（加 7 天）
来源：http://dali.mhx1999.top/Article/details/gtptzgmuig.html

Py:   now + timedelta(days=7)
来源：http://dali.fengsongda.top/Article/details/gtnocjpgiy.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.c1oappe.top/Article/details/gtguqjlgju.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigfzy.top/Article/details/gtqkoldbcg.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuxming.cn/Article/details/gtrchddrup.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhoulong.xyz/Article/details/gtfkwlsmjw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hywenlv.cn/Article/details/gtfzfapgak.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhixingplan.top/Article/details/gtzphriqbg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.nwbrower.top/Article/details/gthdpvsino.html

[J06] 计算两时间之差
来源：http://dali.yuanzhike.top/Article/details/gtlobhheov.html

Py:   (end - start).total_seconds()
来源：http://dali.ehwqpu.com/Article/details/gttfpnjfma.html

PHP:  $end->diff($start)->days;
来源：http://dali.yj202588.top/Article/details/gtlnwkzgax.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yuxming.cn/Article/details/gtiabkefni.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.meibo888.top/Article/details/gtggannkfr.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.fzhhl.top/Article/details/gtjcarknrx.html

Go:   end.Sub(start).Hours()
来源：http://dali.xylfe.cn/Article/details/gtkkxyorqm.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hammf.cn/Article/details/gtcgvknqnp.html

C#:   (end - start).TotalSeconds
来源：http://dali.cdnleiting.top/Article/details/gtcshjlyna.html

[J07] 比较两个日期
来源：http://dali.yuxming.cn/Article/details/gtgzesnjeh.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinghuilouyu.cn/Article/details/gtztyttqwp.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ehwqpu.com/Article/details/gtfljxdcem.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sxryk.cn/Article/details/gtkiszequv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhengqikj.top/Article/details/gtubawogdx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xinyue.icu/Article/details/gtuuwpntir.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zdqjudy.top/Article/details/gtzhptzmqg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gtpzbkptof.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jyoumei.cn/Article/details/gtginxdayh.html

[J08] 提取年月日与星期
来源：http://dali.xylfe.cn/Article/details/gtodwtpesu.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zdqjudy.top/Article/details/gtibemzcqk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yanxiufei.cn/Article/details/gtsynouqry.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhoulong.xyz/Article/details/gthyghlzpv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sufxvd.cn/Article/details/gtlxpbclmf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.nanxinkj.top/Article/details/gtycclxrxl.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.chenjidiqi.icu/Article/details/gtccbmhlro.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yj202588.top/Article/details/gtebbvdlee.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.chenlongwang.top/Article/details/gtjmzwkgkz.html

[J09] 时区处理
来源：http://dali.cucudq.cn/Article/details/gtmfhsjztn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.wangshuangyany.cn/Article/details/gtyxtnsswq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yueranfly.top/Article/details/gtyobtyksf.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.snrcjt.cn/Article/details/gtxypxxtml.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fengsongda.top/Article/details/gtesfqtgzc.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.316326.xyz/Article/details/gtxzlytosl.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.guowangkeji.top/Article/details/gttkpellkh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nanxuanxn.top/Article/details/gtlyfftgzt.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.nanxuanxn.top/Article/details/gtlflbuzkt.html

[J10] 取今天 / 本月第一天
来源：http://dali.kuanghao11.cn/Article/details/gtpqurcyea.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sxryk.cn/Article/details/gtrzlikxdh.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cashguo.top/Article/details/gtdmpovvhl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yj202588.top/Article/details/gtxoppqjep.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj202588.top/Article/details/gtfrjgqqzu.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xuanzx.com/Article/details/gtrrpslxcl.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jqgufenzy.top/Article/details/gtjfkaynno.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tanke756.top/Article/details/gttlswudyy.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.quarkkingdee.top/Article/details/gtzcyomlve.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtnhzdewxn.html

K. JSON 与序列化
来源：http://dali.sysykeji.top/Article/details/gtmyigdvgh.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtbuepsvon.html

[K01] 对象转 JSON 字符串
来源：http://dali.ehwqpu.com/Article/details/gtptaxdnhr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhoulong.xyz/Article/details/gtvnrtelcv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.aizwys.cn/Article/details/gtkuxqsspu.html

JS:   JSON.stringify(obj)
来源：http://dali.birdmap.top/Article/details/gtzjrerekc.html

TS:   JSON.stringify(obj)
来源：http://dali.ehwqpu.com/Article/details/gtmcjeexie.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfyodqzzh.html

Go:   json.Marshal(obj)
来源：http://dali.chenlongwang.top/Article/details/gtqtxnwhur.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zycfv.cn/Article/details/gtojpexker.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.dashuyun.cn/Article/details/gttmsjgpqs.html

[K02] JSON 字符串转对象
来源：http://dali.yj202588.top/Article/details/gtnirgitvu.html

Py:   json.loads(s)
来源：http://dali.meibo888.top/Article/details/gtssnrrttw.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ehwqpu.com/Article/details/gtsgilondl.html

JS:   JSON.parse(s)
来源：http://dali.jyoumei.cn/Article/details/gtrbhzsqsy.html

TS:   JSON.parse(s)
来源：http://dali.zhengqikj.top/Article/details/gtlgjswhdt.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.meibo888.top/Article/details/gteflkyquf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.tianlin.xyz/Article/details/gtimymtrit.html

Ruby: JSON.parse(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtyigoydfq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yanxiufei.cn/Article/details/gtekyizcvv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ehwqpu.com/Article/details/gtfbyyszea.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gaohongyu789.top/Article/details/gtkdunibye.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.aibaodan.cn/Article/details/gtndubyfpm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.c1oappe.top/Article/details/gtydvcjooh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtdxtzredl.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtoalathts.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xuanzx.com/Article/details/gtujxjhmfs.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ydzc1.top/Article/details/gttbawlsbo.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.feifeiyinyue.top/Article/details/gtrnwdupvi.html

[K04] 读取 JSON 文件
来源：http://dali.yuanzhike.top/Article/details/gtsnejvynu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.316326.xyz/Article/details/gtpdlwtywm.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ivvv.top/Article/details/gtmdvmdvys.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aizwys.cn/Article/details/gtgwgacoqa.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cdnleiting.top/Article/details/gtpdgbwozm.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cdnleiting.top/Article/details/gtppwvxdlq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jyoumei.cn/Article/details/gtuydiyjlq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cqqwz.cn/Article/details/gtkovgwips.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.chenjidiqi.icu/Article/details/gtxihzohlv.html

[K05] 深拷贝对象
来源：http://dali.jyoumei.cn/Article/details/gtzwiltbdi.html

Py:   copy.deepcopy(obj)
来源：http://dali.tanke756.top/Article/details/gtgmeaddri.html

PHP:  unserialize(serialize($obj));
来源：http://dali.0kj1m.cn/Article/details/gtmjsbtwzv.html

JS:   structuredClone(obj)
来源：http://dali.dianchejie.cn/Article/details/gtotwjpubj.html

TS:   structuredClone(obj)
来源：http://dali.smart0.xyz/Article/details/gtuwadkqdl.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.dashuyun.cn/Article/details/gtfxqcggvd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.tian-w.cn/Article/details/gttocqiuai.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.chenzaomai.com/Article/details/gtqajdvqtm.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.pengpengdd.cyou/Article/details/gtufvlclsf.html

[K06] 解析 URL 查询串
来源：http://dali.sysykeji.top/Article/details/gtbxoqmzge.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.nanxuanxn.top/Article/details/gtcngqvdlr.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.wangshuangyany.cn/Article/details/gttuwxvnli.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hammf.cn/Article/details/gtwwnwwdpr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aizwys.cn/Article/details/gtlavtaibu.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.vqdsnc.cn/Article/details/gtvvqfjbqx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gtncpjyspo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xziqi.cn/Article/details/gtwqroksxh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhengqikj.top/Article/details/gtyiyousak.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gtjymsszsn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gtcunojrhb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.wangshuangyany.cn/Article/details/gtkctqfimd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gthswzyqpl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gtxkdpgolm.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gtjsixqpis.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.pycfn.com/Article/details/gtsbmvocjr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.guannengcc.top/Article/details/gtkvzjlzxv.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gttcfojrld.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.aibaodan.cn/Article/details/gtycootipb.html

Py:   pickle.dumps(obj)
来源：http://dali.svipenyu.cn/Article/details/gteyosvadm.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtefexqohi.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgtofflau.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yangfankeji.com/Article/details/gtlcarvine.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinghuilouyu.cn/Article/details/gtnmoprikk.html

Go:   encoding/gob
来源：http://dali.ppjwa.cn/Article/details/gtlvzorqaj.html

Ruby: Marshal.dump(obj)
来源：http://dali.sxryk.cn/Article/details/gtsupjtvbb.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.c1oappe.top/Article/details/gtnsqdjass.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtrrfgnwod.html

L. 网络请求
来源：http://dali.cashguo.top/Article/details/gtzkboqmxc.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtnmjilolm.html

[L01] 发送 GET 请求
来源：http://dali.yuanzhike.top/Article/details/gtxxozqkri.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xinyue.icu/Article/details/gtvhqayoqs.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ehwqpu.com/Article/details/gtpecsxzcb.html

JS:   await fetch(url)
来源：http://dali.aibaodan.cn/Article/details/gttzkdznyc.html

TS:   await fetch(url)
来源：http://dali.shzxlz.cn/Article/details/gtqmiepfis.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.daria6918.cn/Article/details/gttxeqqsqk.html

Go:   resp, err := http.Get(url)
来源：http://dali.xziqi.cn/Article/details/gtdbtmbfpo.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yvedp.cn/Article/details/gtkxwwjasn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.feifeiyinyue.top/Article/details/gtnaicywfx.html

[L02] 发送 POST JSON
来源：http://dali.yonumen.top/Article/details/gtitdcquzo.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxzzfwbzm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shanyushiyangtech.top/Article/details/gtbjckgfnu.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dashuyun.cn/Article/details/gtmfzcujtv.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenlongwang.top/Article/details/gtyuizktxn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.daria6918.cn/Article/details/gttmwcbhug.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.9152youxi.cn/Article/details/gtjlsnbynf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hfpthk.cn/Article/details/gtbdnthifc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.nwbrower.top/Article/details/gtcitxmxci.html

[L03] 设置自定义请求头
来源：http://dali.ivvv.top/Article/details/gtfotwldmp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.feifeiyinyue.top/Article/details/gtvkfrhizt.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.fzhhl.top/Article/details/gtofkwwcma.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hfpthk.cn/Article/details/gtlerigrwk.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenlongwang.top/Article/details/gtflhmufqm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.svipenyu.cn/Article/details/gtspoxphgg.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shanyushiyangtech.top/Article/details/gtlanxbbsb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.wangdashe.top/Article/details/gtqbqstjug.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinqigfzy.top/Article/details/gtqqkjbsof.html

[L04] 设置超时
来源：http://dali.wangdashe.top/Article/details/gtjjhlbpwt.html

Py:   requests.get(url, timeout=5)
来源：http://dali.mhx1999.top/Article/details/gtuilyoibq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shzxlz.cn/Article/details/gtjrsleshx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhongyouzk.top/Article/details/gtzqlzzfqj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dashuyun.cn/Article/details/gtvnscheot.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.guannengcc.top/Article/details/gtrreycych.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.fzhhl.top/Article/details/gtrdvfvjim.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shzxlz.cn/Article/details/gtlxmeotgd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yuanzhike.top/Article/details/gtdcvxrvhc.html

[L05] 上传文件（multipart）
来源：http://dali.xziqi.cn/Article/details/gtecgxraqp.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhongyouzk.top/Article/details/gtzzzkyzsn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.meibo888.top/Article/details/gtsyhxzjxk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenjidiqi.icu/Article/details/gttdxcjthp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cucudq.cn/Article/details/gticckvxwc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gogol.net.cn/Article/details/gtgopzypbw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.mhx1999.top/Article/details/gtkdyyocsa.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.fzhhl.top/Article/details/gtfbxihpjg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtfmjsovyv.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gteznoyinc.html

Py:   resp.json()
来源：http://dali.feifeiyinyue.top/Article/details/gthiuqakik.html

PHP:  json_decode($body, true);
来源：http://dali.iojbl.cn/Article/details/gtobobfclp.html

JS:   await resp.json()
来源：http://dali.sufxvd.cn/Article/details/gtgpbkxcjg.html

TS:   await resp.json()
来源：http://dali.yuxming.cn/Article/details/gtwayjsclg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jqgfzy.top/Article/details/gtqpakccoj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.aibaodan.cn/Article/details/gtrkyfojkb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sxryk.cn/Article/details/gtmuvgiklx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hywenlv.cn/Article/details/gtqogsslac.html

[L07] 处理 HTTP 状态码
来源：http://dali.guowangkeji.top/Article/details/gtpbmnqsfb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ehwqpu.com/Article/details/gtajhazipm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cqqwz.cn/Article/details/gtbyxfdwlu.html

JS:   resp.ok;  resp.status
来源：http://dali.xylfe.cn/Article/details/gtfbxeryvs.html

TS:   resp.ok;  resp.status
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyigixvzs.html

Java: resp.statusCode()
来源：http://dali.nanxuanxn.top/Article/details/gtppivmpeb.html

Go:   resp.StatusCode
来源：http://dali.xylfe.cn/Article/details/gtxgzkhjtn.html

Ruby: resp.code.to_i
来源：http://dali.hongshengwenyu.top/Article/details/gtvpexiylx.html


<!-- 参考信息 -->