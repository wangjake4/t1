代发 wailian999

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.redwolf501.top/Article/details/gtxrikpyli.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtzexmfoss.html

Ruby: s.match?(/\d+/)
来源：http://dali.sufxvd.cn/Article/details/gtnhwednmf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.iojbl.cn/Article/details/gtaclehqsu.html

[I02] 提取所有匹配
来源：http://dali.yj20258.top/Article/details/gtrvyrqkvf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cashguo.top/Article/details/gttjmivziz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xuanzx.com/Article/details/gtylczmlru.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj202588.top/Article/details/gtmkkphipp.html

TS:   s.match(/\d+/g)
来源：http://dali.hywenlv.cn/Article/details/gthbxdwkxt.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sxryk.cn/Article/details/gtvnefdlgq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yangfankeji.com/Article/details/gtfmpqnjtp.html

Ruby: s.scan(/\d+/)
来源：http://dali.aibaodan.cn/Article/details/gtwgfgrkqs.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yueranfly.top/Article/details/gtaekmhxcy.html

[I03] 提取捕获分组
来源：http://dali.zhoulong.xyz/Article/details/gtxugfppji.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cashguo.top/Article/details/gtggunzzbh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hnqzz.top/Article/details/gtkapqvcbr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.tian-w.cn/Article/details/gtynwigyql.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yj20258888.top/Article/details/gtxkmpsagg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ivvv.top/Article/details/gtifbzdveh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tian-w.cn/Article/details/gtckssbkod.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sweek.top/Article/details/gtpezmjjaw.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yj20258.top/Article/details/gtraeqlrbb.html

[I04] 正则替换
来源：http://dali.guannengcc.top/Article/details/gtqpllhpiy.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hongshengwenyu.top/Article/details/gthvdshahn.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ybcxt.top/Article/details/gtabvmrtth.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gogol.net.cn/Article/details/gtqjwogrqf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gzhubu.top/Article/details/gtxjzeaplz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.wangshuangyany.cn/Article/details/gtnsygluix.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.nanxuanxn.top/Article/details/gtapypejeq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.kuanghao11.cn/Article/details/gtdcjdjqrw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtttynbapz.html

[I05] 按正则拆分
来源：http://dali.cheryme.top/Article/details/gtnsuwdfqi.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhixingplan.top/Article/details/gtrjfeokru.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.dashuyun.cn/Article/details/gtavoowedx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.snrcjt.cn/Article/details/gtqgboxuwq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gtlfrcdhdh.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yanxiufei.cn/Article/details/gtyovmqvxr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmcqwsqad.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xuanzx.com/Article/details/gtqyyzjuyf.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yangfankeji.com/Article/details/gtsqulkddo.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.nanxinkj.top/Article/details/gtfaubbyiz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.chenjidiqi.icu/Article/details/gtoonwytfx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jqgufenzy.top/Article/details/gtpztixsyn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jiagoushi.top/Article/details/gtbjqsftyx.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ydzc1.top/Article/details/gtalsvsspi.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhiwuduotai.top/Article/details/gtvxahjzel.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinqigufen.top/Article/details/gtshxrlnpw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.iojbl.cn/Article/details/gtqxyhhmzn.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.tianlin.xyz/Article/details/gtyqczdsih.html

[I07] 忽略大小写与多行模式
来源：http://dali.xylfe.cn/Article/details/gtnvremfdh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfkuymaez.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsbxbxivr.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.meibo888.top/Article/details/gttvqyzcgi.html

TS:   /error/gim
来源：http://dali.ydzc1.top/Article/details/gtxakbwnjr.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yangfankeji.com/Article/details/gtdtsryejo.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtosgoycnx.html

Ruby: s.scan(/error/i)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbifbcbzd.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.nanxuanxn.top/Article/details/gtvhdwsbtt.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hysaishi.cn/Article/details/gthuqwgtge.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.redwolf501.top/Article/details/gtulbjajxf.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.tianlin.xyz/Article/details/gtujkahrlq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gotoacloud.top/Article/details/gtjpiljjwa.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.mhx1999.top/Article/details/gtkfavhhqp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jlsjyb.cn/Article/details/gtiqakeduy.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cdnleiting.top/Article/details/gtercivyno.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.pengpengdd.cyou/Article/details/gtupwfgdpy.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hnqzz.top/Article/details/gtxlxiuwzp.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtfebzebzs.html

J. 日期与时间
来源：http://dali.tanke756.top/Article/details/gtcvuhdbsq.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtyazefaje.html

[J01] 获取当前时间
来源：http://dali.aizwys.cn/Article/details/gtsjwlevdl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hywenlv.cn/Article/details/gtlyzswxre.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhiwuduotai.top/Article/details/gtuajtlpod.html

JS:   new Date();  Date.now()
来源：http://dali.kuanghao11.cn/Article/details/gtgsqxmvhj.html

TS:   new Date();  Date.now()
来源：http://dali.zdqjudy.top/Article/details/gttnsxinkh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.pengpengdd.cyou/Article/details/gtuehesfxy.html

Go:   time.Now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlfhgbbxp.html

Ruby: Time.now
来源：http://dali.hongshengwenyu.top/Article/details/gtskjbqmfh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.wangdashe.top/Article/details/gtdbmcffjn.html

[J02] 格式化输出
来源：http://dali.hysaishi.cn/Article/details/gttrrpqkqg.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.feifeiyinyue.top/Article/details/gtfjxqgpml.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.sxryk.cn/Article/details/gtuqhosiea.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.tianlin.xyz/Article/details/gthbkchxiq.html

TS:   d.toISOString()
来源：http://dali.bjfxy.top/Article/details/gtfdzgakdq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ivvv.top/Article/details/gthmdxijgk.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.haohaochexian.top/Article/details/gtyeojrnuc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangdashe.top/Article/details/gtujupeufk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jlsjyb.cn/Article/details/gtoncuvgzo.html

[J03] 字符串解析为日期
来源：http://dali.andypj.xyz/Article/details/gteqpkjxww.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shzxlz.cn/Article/details/gtajkhklys.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.chenjidiqi.icu/Article/details/gtvmscwfyk.html

JS:   new Date("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtzlcctaml.html

TS:   new Date("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gtzsrzjtps.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gtnzrvfnok.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtmthqwttu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gtleqosumk.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hammf.cn/Article/details/gtnjqhvtjn.html

[J04] 时间戳与日期互转
来源：http://dali.xuetiantiany.cn/Article/details/gtrhodngiw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.nanxuanxn.top/Article/details/gtmnmdzozs.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.pycfn.com/Article/details/gtbhgkxjbh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.havefunace.top/Article/details/gtspghimze.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.haohaochexian.top/Article/details/gtcnhnpuxx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlgpaztcv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.316326.xyz/Article/details/gtzrzixfiq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gttplfxmyc.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gtkhqhtppd.html

[J05] 时间加减（加 7 天）
来源：http://dali.tian-w.cn/Article/details/gtcdcqaqgp.html

Py:   now + timedelta(days=7)
来源：http://dali.zycfv.cn/Article/details/gtmfiwysrb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.andypj.xyz/Article/details/gtfrebucci.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guowangkeji.top/Article/details/gtkgzxobbv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aibaodan.cn/Article/details/gtwezjnrkw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hnqzz.top/Article/details/gtqwxvgcfk.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sxryk.cn/Article/details/gtkubxlsjh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.dianchejie.cn/Article/details/gtcnpghdyg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yueranfly.top/Article/details/gtveyhkzam.html

[J06] 计算两时间之差
来源：http://dali.hnqzz.top/Article/details/gtiobmbywv.html

Py:   (end - start).total_seconds()
来源：http://dali.xylfe.cn/Article/details/gtodidwerh.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhoulong.xyz/Article/details/gtewdrhotw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gogol.net.cn/Article/details/gtgdvqmzoj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.nanxinkj.top/Article/details/gtekgoadkp.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.guannengcc.top/Article/details/gtnldgvaxs.html

Go:   end.Sub(start).Hours()
来源：http://dali.hongshengwenyu.top/Article/details/gttvcmicxh.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yj20258.top/Article/details/gtrupkalyv.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenzaomai.com/Article/details/gtosvwwduu.html

[J07] 比较两个日期
来源：http://dali.hnxiangtu.top/Article/details/gthcizunvt.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shangyingyoupin.top/Article/details/gtferrsevi.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sweek.top/Article/details/gtxzkqzwxb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrpwtmlow.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.mhx1999.top/Article/details/gtojjenevv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.wangshuangyany.cn/Article/details/gtbktmpzrq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jiagoushi.top/Article/details/gtjcixtjni.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gtjrknpisx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gtrkqcotid.html

[J08] 提取年月日与星期
来源：http://dali.ybcxt.top/Article/details/gtpakixtba.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shanyushiyangtech.top/Article/details/gteedvoxge.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.fzhhl.top/Article/details/gtpycuhmfo.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xinyue.icu/Article/details/gtjaudevlh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.snrcjt.cn/Article/details/gtqolqssel.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hammf.cn/Article/details/gtitqyfzvq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinqigfzy.top/Article/details/gtxqljzbvk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.svipenyu.cn/Article/details/gtojytudrj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hywenlv.cn/Article/details/gtrvykdfgt.html

[J09] 时区处理
来源：http://dali.shangyingyoupin.top/Article/details/gtbpbwoeua.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ydzc1.top/Article/details/gtowldonsu.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.fengsongda.top/Article/details/gtluqbnsvs.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.iojbl.cn/Article/details/gtkdhxovcl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ivvv.top/Article/details/gtzeappkfy.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhijiandao.cn/Article/details/gttfdzfxho.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xuetiantiany.cn/Article/details/gtepjnpbnt.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.pycfn.com/Article/details/gtzygeracl.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jyoumei.cn/Article/details/gticqoifxu.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenjidiqi.icu/Article/details/gtchftdplv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.mhx1999.top/Article/details/gtvhdcoulo.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.haohaochexian.top/Article/details/gtcnsfypip.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shzxlz.cn/Article/details/gtkqvwuvic.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtlaegdmlu.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zycfv.cn/Article/details/gtcvdaxgql.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj20258.top/Article/details/gtqwxmohlv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hysaishi.cn/Article/details/gtkzwlozwl.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jlsjyb.cn/Article/details/gtqgavtdos.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtpnukqhyq.html

K. JSON 与序列化
来源：http://dali.svipenyu.cn/Article/details/gtuoepieud.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtmdzlmgbi.html

[K01] 对象转 JSON 字符串
来源：http://dali.jqgufenzy.top/Article/details/gtxdadmhfh.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jqgufenzy.top/Article/details/gtnsxzbqhn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.daria6918.cn/Article/details/gtmkvcsdwd.html

JS:   JSON.stringify(obj)
来源：http://dali.tianlin.xyz/Article/details/gtcjcfwsfa.html

TS:   JSON.stringify(obj)
来源：http://dali.tanke756.top/Article/details/gtkryriyzl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jyoumei.cn/Article/details/gtjvdwenlz.html

Go:   json.Marshal(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtdljwdczt.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.tianlin.xyz/Article/details/gtirkkyvbc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cheryme.top/Article/details/gtvjhfbunt.html

[K02] JSON 字符串转对象
来源：http://dali.yueranfly.top/Article/details/gtxstzkysh.html

Py:   json.loads(s)
来源：http://dali.zhongyouzk.top/Article/details/gtarrfkhip.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.9152youxi.cn/Article/details/gtvqzvonlz.html

JS:   JSON.parse(s)
来源：http://dali.nanxinkj.top/Article/details/gtownytjvb.html

TS:   JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gtladqycsm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsddtquqx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.daxiang520.top/Article/details/gtzdedoxje.html

Ruby: JSON.parse(s)
来源：http://dali.wangdashe.top/Article/details/gtrhcfbkhf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.9152youxi.cn/Article/details/gtdqauyzwe.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinghuilouyu.cn/Article/details/gtyvfmgijf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.fzhhl.top/Article/details/gtiwypxque.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sysykeji.top/Article/details/gtqsxslnbm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hammf.cn/Article/details/gtcciuqiqv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jiagoushi.top/Article/details/gtucwwgsrt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.sxryk.cn/Article/details/gtcwbmqanl.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sufxvd.cn/Article/details/gtqwqhxhym.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yangfankeji.com/Article/details/gtgjncwrja.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xinyue.icu/Article/details/gtmtppmtfq.html

[K04] 读取 JSON 文件
来源：http://dali.sxryk.cn/Article/details/gteiwtjmzb.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.andypj.xyz/Article/details/gtzvmofvkt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yuanzhike.top/Article/details/gtressosbc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gtgidgziue.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aizwys.cn/Article/details/gtgrrwdnzx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hnxiangtu.top/Article/details/gtpzcorcdp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.guowangkeji.top/Article/details/gtqhjwfddn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yongpay.top/Article/details/gtczxjtdpt.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.c1oappe.top/Article/details/gtspgodevs.html

[K05] 深拷贝对象
来源：http://dali.cucudq.cn/Article/details/gtlfvixrpw.html

Py:   copy.deepcopy(obj)
来源：http://dali.vqdsnc.cn/Article/details/gteztcgcmz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.tian-w.cn/Article/details/gthvzhgmqj.html

JS:   structuredClone(obj)
来源：http://dali.jlsjyb.cn/Article/details/gteoakcsoa.html

TS:   structuredClone(obj)
来源：http://dali.jianghu66.top/Article/details/gtchjxbgfe.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.tianlin.xyz/Article/details/gtjphsmjqv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.guannengcc.top/Article/details/gtombxcoao.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.haohaochexian.top/Article/details/gtzgvcxnfn.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hnqzz.top/Article/details/gtjucjobfr.html

[K06] 解析 URL 查询串
来源：http://dali.sxryk.cn/Article/details/gtavkawzxk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hnxiangtu.top/Article/details/gtkpgnpjap.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shuidangran.top/Article/details/gtoubqckkp.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxuanxn.top/Article/details/gtuzmibwpz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guannengcc.top/Article/details/gtwvitbjzx.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hongshengwenyu.top/Article/details/gtxchfooht.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.daxiang520.top/Article/details/gtscyeoxcc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sysykeji.top/Article/details/gtdwjeaxqo.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xuetiantiany.cn/Article/details/gtyvrmlrmc.html

[K07] 进制转换
来源：http://dali.nanxuanxn.top/Article/details/gtecgkxglb.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gtagkrzmfz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hywenlv.cn/Article/details/gtsglkqmnt.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtwqzjqnku.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yj20258.top/Article/details/gtlelgkpqw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gtlpijnizh.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.guannengcc.top/Article/details/gtujdagbxq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.chenlongwang.top/Article/details/gtvaqydydp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gtemvzikxw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sxryk.cn/Article/details/gttsurkyaa.html

Py:   pickle.dumps(obj)
来源：http://dali.cashguo.top/Article/details/gtxcnwladq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gtzsiavmnz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hongshengwenyu.top/Article/details/gtzdgbolgj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.dianchejie.cn/Article/details/gtpguyvjmt.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hnqzz.top/Article/details/gtgqiliaae.html

Go:   encoding/gob
来源：http://dali.feifeiyinyue.top/Article/details/gtbbgqcoke.html

Ruby: Marshal.dump(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtpevtmhbl.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.andypj.xyz/Article/details/gtohugyroa.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gttkujsbqe.html

L. 网络请求
来源：http://dali.shanyushiyangtech.top/Article/details/gtgtxsqizs.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtoenlulcy.html

[L01] 发送 GET 请求
来源：http://dali.quarkkingdee.top/Article/details/gtrytwbrow.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jlsjyb.cn/Article/details/gtnflhmbdh.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.quarkkingdee.top/Article/details/gtghuhlken.html

JS:   await fetch(url)
来源：http://dali.meibo888.top/Article/details/gtgdgyvpai.html

TS:   await fetch(url)
来源：http://dali.bjfxy.top/Article/details/gtqpvhhokq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.aibaodan.cn/Article/details/gtjftkkuvu.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhiwuduotai.top/Article/details/gtucnzxlau.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cqqwz.cn/Article/details/gtylspvwlz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhiwuduotai.top/Article/details/gthgbrzxey.html

[L02] 发送 POST JSON
来源：http://dali.yangfankeji.com/Article/details/gtfsprsjlo.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.0kj1m.cn/Article/details/gtmmkphkew.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.nanxinkj.top/Article/details/gtqqglbqfi.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuanzx.com/Article/details/gtrlbdlnqh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhongyouzk.top/Article/details/gtmeksxtid.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenlongwang.top/Article/details/gtgxrvhzqw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtazeajewa.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hnqzz.top/Article/details/gtoxdmwyfk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.iojbl.cn/Article/details/gtbpmickex.html

[L03] 设置自定义请求头
来源：http://dali.meibo888.top/Article/details/gttmlwotaj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ybcxt.top/Article/details/gtcholfzak.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.birdmap.top/Article/details/gtjfvgylyi.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cashguo.top/Article/details/gtqvyqbqev.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daria6918.cn/Article/details/gtnnrbreom.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.0kj1m.cn/Article/details/gtthdvxruf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gzhubu.top/Article/details/gtpfzlqqpw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.c1oappe.top/Article/details/gtqhixdkmo.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hongshengwenyu.top/Article/details/gtqaxhcipk.html

[L04] 设置超时
来源：http://dali.yuxming.cn/Article/details/gtlexxrxkp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yanxiufei.cn/Article/details/gtoyskctjo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hfpthk.cn/Article/details/gtbkoaocgx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shuidangran.top/Article/details/gtijvsrngh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gtmsguliya.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jianghu66.top/Article/details/gtjszmbpmn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkbqwjtbk.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.daria6918.cn/Article/details/gtpfmoahqi.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cqqwz.cn/Article/details/gtdjscuity.html

[L05] 上传文件（multipart）
来源：http://dali.ydzc1.top/Article/details/gtxknmjncu.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shangyingyoupin.top/Article/details/gtoxvgfshs.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.feifeiyinyue.top/Article/details/gttigxbvfp.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cucudq.cn/Article/details/gtxcvbirfz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.c1oappe.top/Article/details/gtpjvwbtaz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.316326.xyz/Article/details/gtrseqnido.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cheryme.top/Article/details/gtcjzzifbi.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.mhx1999.top/Article/details/gtezvboryq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.havefunace.top/Article/details/gtkqhhxsqu.html

[L06] 解析响应为 JSON
来源：http://dali.chenlongwang.top/Article/details/gttrjehaso.html

Py:   resp.json()
来源：http://dali.cucudq.cn/Article/details/gtoimudloj.html

PHP:  json_decode($body, true);
来源：http://dali.zycfv.cn/Article/details/gtjvopqyjl.html

JS:   await resp.json()
来源：http://dali.ehwqpu.com/Article/details/gtymhlirvr.html

TS:   await resp.json()
来源：http://dali.xziqi.cn/Article/details/gtgzbghwua.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gtliezfxbt.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhengqikj.top/Article/details/gtqxeoxqxq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zycfv.cn/Article/details/gtbwsavxlp.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yueranfly.top/Article/details/gtuwrqjevp.html

[L07] 处理 HTTP 状态码
来源：http://dali.gotoacloud.top/Article/details/gtpukhqjtt.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.chenlongwang.top/Article/details/gtvwoxiurv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cheryme.top/Article/details/gtfmsqngvt.html

JS:   resp.ok;  resp.status
来源：http://dali.cdnleiting.top/Article/details/gtnfhenliz.html

TS:   resp.ok;  resp.status
来源：http://dali.havefunace.top/Article/details/gtxezupwft.html

Java: resp.statusCode()
来源：http://dali.xylfe.cn/Article/details/gtvmnatkct.html

Go:   resp.StatusCode
来源：http://dali.zycfv.cn/Article/details/gtxluopjmn.html

Ruby: resp.code.to_i
来源：http://dali.zhiwuduotai.top/Article/details/gtjhqffytd.html


<!-- 参考信息 -->