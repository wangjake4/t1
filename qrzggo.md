代发 wailian999

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ywan-chungtsiang.top/Article/details/gteegnjqkj.html

Go:   defer f.Close()
来源：http://dali.guowangkeji.top/Article/details/gtkfiomqhs.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhengqikj.top/Article/details/gtrmlernmy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtydmulyvg.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtoxssfmlt.html

I. 正则表达式
来源：http://dali.quarkkingdee.top/Article/details/gtyltvwzcx.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtrtwomzwn.html

[I01] 判断是否匹配
来源：http://dali.yueranfly.top/Article/details/gtwtrogbkn.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tanke756.top/Article/details/gtvpzkmjul.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yj20258.top/Article/details/gtbqpycmty.html

JS:   /\d+/.test(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtwrmxgxpq.html

TS:   /\d+/.test(s)
来源：http://dali.yueranfly.top/Article/details/gtjwojkhvr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhixingplan.top/Article/details/gtqapffxgx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shzxlz.cn/Article/details/gtephzhwjk.html

Ruby: s.match?(/\d+/)
来源：http://dali.yj20258888.top/Article/details/gtolkeuizy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.svipenyu.cn/Article/details/gtkrdlmipu.html

[I02] 提取所有匹配
来源：http://dali.svipenyu.cn/Article/details/gthgnilffc.html

Py:   re.findall(r"\d+", s)
来源：http://dali.nanxinkj.top/Article/details/gtolbhqfct.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yuanzhike.top/Article/details/gtpyfbqlkv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shuidangran.top/Article/details/gtaufitlzu.html

TS:   s.match(/\d+/g)
来源：http://dali.aizwys.cn/Article/details/gthmkqatqy.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.tanke756.top/Article/details/gtfnszivwb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.fzhhl.top/Article/details/gtxkykczgi.html

Ruby: s.scan(/\d+/)
来源：http://dali.gaohongyu789.top/Article/details/gtxjhehwbg.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gtrstkxgxi.html

[I03] 提取捕获分组
来源：http://dali.andypj.xyz/Article/details/gtavhvqwms.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.daxiang520.top/Article/details/gtoonltypc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.dashuyun.cn/Article/details/gtduhzgmuv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cdnleiting.top/Article/details/gttrcenkcw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ydzc1.top/Article/details/gtpfltoeno.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.iojbl.cn/Article/details/gthtchfcmr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhoulong.xyz/Article/details/gtkhzolsdi.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.316326.xyz/Article/details/gtsjdogjmu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gaohongyu789.top/Article/details/gtifcsvgfd.html

[I04] 正则替换
来源：http://dali.yueranfly.top/Article/details/gtvuciftpt.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtydtulhag.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtlxgxisel.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258888.top/Article/details/gtsibewqnz.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yonumen.top/Article/details/gtvvhleguj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.c1oappe.top/Article/details/gtzghhbunm.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.wangshuangyany.cn/Article/details/gtacgwcavw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yuxming.cn/Article/details/gtzfzfxmro.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.daria6918.cn/Article/details/gtvscizkjt.html

[I05] 按正则拆分
来源：http://dali.tanke756.top/Article/details/gtdjqhevjr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.tanke756.top/Article/details/gtealowgxi.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtsfikisal.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtucckjzhr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.smart0.xyz/Article/details/gtxmjbhycu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinghuilouyu.cn/Article/details/gtqevcqmmm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yj202588.top/Article/details/gtvqssbezl.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cheryme.top/Article/details/gtemwvhbzn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.fzhhl.top/Article/details/gtcnjllgoa.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hongshengwenyu.top/Article/details/gtxzigcjso.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.snrcjt.cn/Article/details/gtdmtzfgei.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shuidangran.top/Article/details/gtlmmqqfea.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xinyue.icu/Article/details/gtitoyztyg.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuanzx.com/Article/details/gthqzwlqne.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zycfv.cn/Article/details/gtihbwbrnc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.dianchejie.cn/Article/details/gttyojmbgc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yj20258888.top/Article/details/gtgdnmvhge.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.dianchejie.cn/Article/details/gtvnoxdysk.html

[I07] 忽略大小写与多行模式
来源：http://dali.chenlongwang.top/Article/details/gtjeklpqmn.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.fengsongda.top/Article/details/gtzwdxsqlw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.316326.xyz/Article/details/gtrylwmbgc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hnqzz.top/Article/details/gtndgqzirm.html

TS:   /error/gim
来源：http://dali.guannengcc.top/Article/details/gtjpbvmvoh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.kuanghao11.cn/Article/details/gtvodaysus.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.chenlongwang.top/Article/details/gtyrglepxr.html

Ruby: s.scan(/error/i)
来源：http://dali.sysykeji.top/Article/details/gthzxnlcvi.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.nanxinkj.top/Article/details/gturcbyxim.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.daxiang520.top/Article/details/gtijaxuqhk.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xylfe.cn/Article/details/gtvcezliwe.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.chenjidiqi.icu/Article/details/gtchtaahvz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.c1oappe.top/Article/details/gtvxfjxoob.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.9152youxi.cn/Article/details/gtoycsshfu.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cqqwz.cn/Article/details/gtfdgrpubb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jyoumei.cn/Article/details/gtzptxsfxj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.guannengcc.top/Article/details/gtqttpgzim.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nanxuanxn.top/Article/details/gtnzgonlii.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtsrvkqsif.html

J. 日期与时间
来源：http://dali.yueranfly.top/Article/details/gtlcexokxq.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtknjfuxmd.html

[J01] 获取当前时间
来源：http://dali.shuidangran.top/Article/details/gtdintycdk.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gaohongyu789.top/Article/details/gtfjcyztxt.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrsnwycrp.html

JS:   new Date();  Date.now()
来源：http://dali.yj20258.top/Article/details/gtvmndiemc.html

TS:   new Date();  Date.now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcrxqkcnn.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nwbrower.top/Article/details/gtnszsjtrk.html

Go:   time.Now()
来源：http://dali.cqqwz.cn/Article/details/gtqlpwbwgp.html

Ruby: Time.now
来源：http://dali.fengsongda.top/Article/details/gtegepzjwb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hywenlv.cn/Article/details/gtktdpqmjm.html

[J02] 格式化输出
来源：http://dali.yvedp.cn/Article/details/gtonbbbhzc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgufenzy.top/Article/details/gtcpkkfozd.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.0kj1m.cn/Article/details/gtthchbxwq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.daria6918.cn/Article/details/gtwvkcnenn.html

TS:   d.toISOString()
来源：http://dali.cdnleiting.top/Article/details/gtmmbdlydi.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.bjfxy.top/Article/details/gttgssqqac.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.nanxuanxn.top/Article/details/gtcpspvxfb.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tanke756.top/Article/details/gthlwklthu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yonumen.top/Article/details/gthcavohiw.html

[J03] 字符串解析为日期
来源：http://dali.tanke756.top/Article/details/gtovteepec.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.vqdsnc.cn/Article/details/gtardnvrpq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.daria6918.cn/Article/details/gtnhbhtprf.html

JS:   new Date("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gtubfloapb.html

TS:   new Date("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gtonyuvwxz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gthztawgdw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gtpmzvwidl.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gtparifqzg.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.guowangkeji.top/Article/details/gtcxrpuzsx.html

[J04] 时间戳与日期互转
来源：http://dali.yj20258.top/Article/details/gtbsiwacno.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.tanke756.top/Article/details/gtvtidphme.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzdhsimlu.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.pycfn.com/Article/details/gtxpoxttbz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xylfe.cn/Article/details/gtldwdkpve.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ybcxt.top/Article/details/gttjzrtzkg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.bjfxy.top/Article/details/gtjejayokx.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cqqwz.cn/Article/details/gtxqdmpcxg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gzhubu.top/Article/details/gtfgbweqmh.html

[J05] 时间加减（加 7 天）
来源：http://dali.hongshengwenyu.top/Article/details/gtyypgdrqg.html

Py:   now + timedelta(days=7)
来源：http://dali.feifeiyinyue.top/Article/details/gtvsvggvwz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.feifeiyinyue.top/Article/details/gtoaqcqytj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.feifeiyinyue.top/Article/details/gttlpdgumb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gogol.net.cn/Article/details/gtbcabykts.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xuanzx.com/Article/details/gtfubkvcsl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.c1oappe.top/Article/details/gtrdlsvnbp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hnqzz.top/Article/details/gtrutcadbs.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sweek.top/Article/details/gtmdztukzd.html

[J06] 计算两时间之差
来源：http://dali.xuanzx.com/Article/details/gtuludqzfg.html

Py:   (end - start).total_seconds()
来源：http://dali.cucudq.cn/Article/details/gtsgskdnsx.html

PHP:  $end->diff($start)->days;
来源：http://dali.jianghu66.top/Article/details/gtpinxvtyl.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj20258.top/Article/details/gtrntkhlfa.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.tian-w.cn/Article/details/gtemikedhz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.chenlongwang.top/Article/details/gtkuiycmns.html

Go:   end.Sub(start).Hours()
来源：http://dali.daxiang520.top/Article/details/gtqwermytv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shuidangran.top/Article/details/gtzrjpjrmh.html

C#:   (end - start).TotalSeconds
来源：http://dali.sufxvd.cn/Article/details/gtntwvnmal.html

[J07] 比较两个日期
来源：http://dali.yuxming.cn/Article/details/gtjblkfhii.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.meibo888.top/Article/details/gtiywgnbke.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gogol.net.cn/Article/details/gtzmfujhwk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jyoumei.cn/Article/details/gtxgdrroyg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ybcxt.top/Article/details/gtodhepjlc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hnqzz.top/Article/details/gttabbxkwj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sufxvd.cn/Article/details/gtezmlrvpx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.daxiang520.top/Article/details/gtjutoohen.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gtgxzeagxc.html

[J08] 提取年月日与星期
来源：http://dali.daxiang520.top/Article/details/gtmunnlimj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shanyushiyangtech.top/Article/details/gtzatjfxky.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cqqwz.cn/Article/details/gtnbchqspv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.c1oappe.top/Article/details/gtnxxijvmx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.fengsongda.top/Article/details/gthymyhxov.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.0kj1m.cn/Article/details/gtleftsnba.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gaohongyu789.top/Article/details/gtqsshvelj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yuanzhike.top/Article/details/gtljehhhxq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cqqwz.cn/Article/details/gtiqayrrah.html

[J09] 时区处理
来源：http://dali.mhx1999.top/Article/details/gtwwvqfpif.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zdqjudy.top/Article/details/gtcxaejsbh.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.svipenyu.cn/Article/details/gtgtzwcnsv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuetiantiany.cn/Article/details/gtgokllxcy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.0kj1m.cn/Article/details/gtajjpsilj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.havefunace.top/Article/details/gtpiufbzim.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.dianchejie.cn/Article/details/gtryowhoyg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhiwuduotai.top/Article/details/gtysyviuch.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.pycfn.com/Article/details/gttgliaops.html

[J10] 取今天 / 本月第一天
来源：http://dali.nanxinkj.top/Article/details/gtlozhixqo.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhixingplan.top/Article/details/gtzqvxkcgg.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhengqikj.top/Article/details/gtomeuebem.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yj20258.top/Article/details/gtnlcgndxy.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtldilvwth.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.c1oappe.top/Article/details/gtaxytggvb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ybcxt.top/Article/details/gtjqeusauh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ivvv.top/Article/details/gthzthlxad.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yueranfly.top/Article/details/gtzmxmzjwa.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtligllgxe.html

K. JSON 与序列化
来源：http://dali.yueranfly.top/Article/details/gtwumvrykv.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtgemmohtg.html

[K01] 对象转 JSON 字符串
来源：http://dali.ivvv.top/Article/details/gtmxjqhzkg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yvedp.cn/Article/details/gtxjdjwkgw.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ivvv.top/Article/details/gthycqpzrq.html

JS:   JSON.stringify(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtlkbqtvyz.html

TS:   JSON.stringify(obj)
来源：http://dali.wangdashe.top/Article/details/gtzasuusno.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shanyushiyangtech.top/Article/details/gtsmurngsn.html

Go:   json.Marshal(obj)
来源：http://dali.nwbrower.top/Article/details/gtpsmsrbmz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hfpthk.cn/Article/details/gtbxmddrbw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gzhubu.top/Article/details/gtdqkrtxky.html

[K02] JSON 字符串转对象
来源：http://dali.redwolf501.top/Article/details/gtxbuawlvf.html

Py:   json.loads(s)
来源：http://dali.hammf.cn/Article/details/gtziefjwhf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.vqdsnc.cn/Article/details/gtsfzxwhna.html

JS:   JSON.parse(s)
来源：http://dali.bjfxy.top/Article/details/gtzrieejpx.html

TS:   JSON.parse(s)
来源：http://dali.cqqwz.cn/Article/details/gtmxrvguvr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hywenlv.cn/Article/details/gtgfuizcaj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.havefunace.top/Article/details/gtugtfhaio.html

Ruby: JSON.parse(s)
来源：http://dali.cheryme.top/Article/details/gtfbjpfqaj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.meibo888.top/Article/details/gtrfkbvgmo.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.andypj.xyz/Article/details/gtnylabtpi.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hywenlv.cn/Article/details/gtcybkfhai.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cashguo.top/Article/details/gtnonuqhsu.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.316326.xyz/Article/details/gtgiukoubr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthglsyacv.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtvedjordv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xziqi.cn/Article/details/gtcqkphoex.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hammf.cn/Article/details/gtqxtkbdyr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tian-w.cn/Article/details/gtdypexqlt.html

[K04] 读取 JSON 文件
来源：http://dali.yueranfly.top/Article/details/gtrdtbsxbm.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhengqikj.top/Article/details/gtgptstxci.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jyoumei.cn/Article/details/gthgemywpm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhengqikj.top/Article/details/gtxxvevbvj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jiagoushi.top/Article/details/gtkpblyyrp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnbtqqfbn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.chenzaomai.com/Article/details/gttsnonfuu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yj20258888.top/Article/details/gtisehtzvm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyspvgeky.html

[K05] 深拷贝对象
来源：http://dali.jyoumei.cn/Article/details/gtnzebcqhb.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrunpptlk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.daxiang520.top/Article/details/gtujcqotyq.html

JS:   structuredClone(obj)
来源：http://dali.sufxvd.cn/Article/details/gtrvjrveyg.html

TS:   structuredClone(obj)
来源：http://dali.shzxlz.cn/Article/details/gtlylqncat.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hysaishi.cn/Article/details/gtcoozscua.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shanyushiyangtech.top/Article/details/gtuelsyhry.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gogol.net.cn/Article/details/gtxvdbqpxa.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jyoumei.cn/Article/details/gtthqzdzwj.html

[K06] 解析 URL 查询串
来源：http://dali.zhoulong.xyz/Article/details/gtzevmcvkt.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.kuanghao11.cn/Article/details/gtqboyasln.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.316326.xyz/Article/details/gtcfmtkdbi.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gotoacloud.top/Article/details/gtcbkvviwo.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pycfn.com/Article/details/gtjtosoazf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.feifeiyinyue.top/Article/details/gtplhtbxlx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nanxinkj.top/Article/details/gtxrgetbfe.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xinyue.icu/Article/details/gtnarlcatv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.guannengcc.top/Article/details/gtbgcxmkni.html

[K07] 进制转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtywytpwsh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gtjgkgxwoe.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ydzc1.top/Article/details/gtanwawjrl.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gtcslmtlhd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gtwqejotdy.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gtxxmvlaif.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cashguo.top/Article/details/gtknflmezs.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.haohaochexian.top/Article/details/gtxkuodqow.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gtzizzucmb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinghuilouyu.cn/Article/details/gtdkcnpsii.html

Py:   pickle.dumps(obj)
来源：http://dali.yueranfly.top/Article/details/gtszheyjrc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.pycfn.com/Article/details/gtvmyuofqy.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.svipenyu.cn/Article/details/gtlzotyzps.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gzhubu.top/Article/details/gtbvpqjzxe.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yongpay.top/Article/details/gtjuwgzpec.html

Go:   encoding/gob
来源：http://dali.jinqigfzy.top/Article/details/gtbrhqlopi.html

Ruby: Marshal.dump(obj)
来源：http://dali.9152youxi.cn/Article/details/gtexozckes.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.daria6918.cn/Article/details/gtkdxsvefa.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtwvybbmml.html

L. 网络请求
来源：http://dali.jinqigfzy.top/Article/details/gtwraqitqf.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtxfrkdzoq.html

[L01] 发送 GET 请求
来源：http://dali.vqdsnc.cn/Article/details/gtbzxsppwz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.haohaochexian.top/Article/details/gttigntrxd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nanxuanxn.top/Article/details/gtfidqbbpj.html

JS:   await fetch(url)
来源：http://dali.dianchejie.cn/Article/details/gtlqekxygo.html

TS:   await fetch(url)
来源：http://dali.chenlongwang.top/Article/details/gtayphyesn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xziqi.cn/Article/details/gtnkoaoefy.html

Go:   resp, err := http.Get(url)
来源：http://dali.jyoumei.cn/Article/details/gtxtcckpvh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.haohaochexian.top/Article/details/gtstodtqbu.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jianghu66.top/Article/details/gtmhdevffq.html

[L02] 发送 POST JSON
来源：http://dali.birdmap.top/Article/details/gtmtgiomit.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.0kj1m.cn/Article/details/gtqjizvpcd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.iojbl.cn/Article/details/gttvsngumq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sysykeji.top/Article/details/gtcoszkiiu.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jyoumei.cn/Article/details/gtpmffgwlo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cucudq.cn/Article/details/gtfmrhaqoa.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.tanke756.top/Article/details/gtggtbdpsv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.redwolf501.top/Article/details/gtfkxnmpwt.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gaohongyu789.top/Article/details/gtpkhnokix.html

[L03] 设置自定义请求头
来源：http://dali.sysykeji.top/Article/details/gtgdqvlcke.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yj20258888.top/Article/details/gtyqkjpqau.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sysykeji.top/Article/details/gttuayhmla.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnxiangtu.top/Article/details/gtiemjxryt.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shzxlz.cn/Article/details/gtplfxlztw.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.nwbrower.top/Article/details/gtmlalidhp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.dashuyun.cn/Article/details/gtkktlroju.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hywenlv.cn/Article/details/gtpxpnxwuq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gogol.net.cn/Article/details/gtndxzrhzz.html

[L04] 设置超时
来源：http://dali.aibaodan.cn/Article/details/gthltbjdtg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yuanzhike.top/Article/details/gtdsmygiqa.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sweek.top/Article/details/gtbhnwsaye.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhoulong.xyz/Article/details/gtkpixwlwl.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangtech.top/Article/details/gtnidviatu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shanyushiyangtech.top/Article/details/gtjogrkjwf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.mhx1999.top/Article/details/gtdocnrhhx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hnqzz.top/Article/details/gthglycbig.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xziqi.cn/Article/details/gtrckbtekh.html

[L05] 上传文件（multipart）
来源：http://dali.hammf.cn/Article/details/gtyxoxohsy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ppjwa.cn/Article/details/gtbajomwgs.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sysykeji.top/Article/details/gtxvyujsva.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgufenzy.top/Article/details/gtgektuihi.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenzaomai.com/Article/details/gtqlmyoare.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yongpay.top/Article/details/gtzcszadvw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.tianlin.xyz/Article/details/gtbpvmrawt.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhengqikj.top/Article/details/gteuiibgid.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjqbrsjxw.html

[L06] 解析响应为 JSON
来源：http://dali.tianlin.xyz/Article/details/gtckuezslt.html

Py:   resp.json()
来源：http://dali.wangdashe.top/Article/details/gtmpqpdlxn.html

PHP:  json_decode($body, true);
来源：http://dali.hywenlv.cn/Article/details/gttzaijzdr.html

JS:   await resp.json()
来源：http://dali.daxiang520.top/Article/details/gtvfnodojl.html

TS:   await resp.json()
来源：http://dali.ywan-chungtsiang.top/Article/details/gttmpilkht.html


<!-- 参考信息 -->