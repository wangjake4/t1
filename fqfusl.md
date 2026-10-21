代发 wailian999

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtfdadnuwg.html

I. 正则表达式
来源：http://dali.xinyue.icu/Article/details/gtaxxfflam.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtdfeyptgi.html

[I01] 判断是否匹配
来源：http://dali.fzhhl.top/Article/details/gtkzkgukzo.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shuidangran.top/Article/details/gtbvuwpiao.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gogol.net.cn/Article/details/gtcvcrfyde.html

JS:   /\d+/.test(s)
来源：http://dali.zhoulong.xyz/Article/details/gtsyfixjvk.html

TS:   /\d+/.test(s)
来源：http://dali.tianlin.xyz/Article/details/gtdqpdkkzq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.iojbl.cn/Article/details/gthwzkclci.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtiylpibyt.html

Ruby: s.match?(/\d+/)
来源：http://dali.cheryme.top/Article/details/gtitbepvvf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cdnleiting.top/Article/details/gtuahlsohl.html

[I02] 提取所有匹配
来源：http://dali.iojbl.cn/Article/details/gtjasmrhao.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hywenlv.cn/Article/details/gtrkvnllkz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yuxming.cn/Article/details/gtukeryyhl.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsqtfncar.html

TS:   s.match(/\d+/g)
来源：http://dali.quarkkingdee.top/Article/details/gteffovhdo.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.meibo888.top/Article/details/gtfufxgrrh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.kuanghao11.cn/Article/details/gtgwhznqap.html

Ruby: s.scan(/\d+/)
来源：http://dali.jianghu66.top/Article/details/gtlhigmpua.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtonlmgtst.html

[I03] 提取捕获分组
来源：http://dali.yj20258.top/Article/details/gtdqbszths.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.tanke756.top/Article/details/gtydwescgj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.daxiang520.top/Article/details/gttrwnxrzb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.316326.xyz/Article/details/gtjolqdidg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.nanxuanxn.top/Article/details/gtkivgadmo.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cdnleiting.top/Article/details/gtbnyhnlgt.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenjidiqi.icu/Article/details/gtxzzeixop.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.birdmap.top/Article/details/gtvgvgpqdl.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.chenlongwang.top/Article/details/gtycsgohfd.html

[I04] 正则替换
来源：http://dali.hnxiangtu.top/Article/details/gtvuxcuxbf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shzxlz.cn/Article/details/gtxbrlaxkl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hysaishi.cn/Article/details/gtogjeqfoq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhiwuduotai.top/Article/details/gtpxpdbgdm.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxuanxn.top/Article/details/gtuqltrrdq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.fengsongda.top/Article/details/gtbstyrgrq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.andypj.xyz/Article/details/gtpwceiaoe.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hammf.cn/Article/details/gtpjdxrosg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.smart0.xyz/Article/details/gtsgeqqtwy.html

[I05] 按正则拆分
来源：http://dali.snrcjt.cn/Article/details/gtuwkbmnaz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gotoacloud.top/Article/details/gtjznrcyqn.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhixingplan.top/Article/details/gtabrifdhp.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.316326.xyz/Article/details/gtgxkzafbc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sxryk.cn/Article/details/gtompaqzzn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tanke756.top/Article/details/gtkkvgnopy.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gaohongyu789.top/Article/details/gtovbrecyz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gaohongyu789.top/Article/details/gthgycptkr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.birdmap.top/Article/details/gtljvmqefn.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinqigufen.top/Article/details/gtbfkrvzjs.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yuanzhike.top/Article/details/gthqewfwgf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sxryk.cn/Article/details/gtkeehrsci.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.iojbl.cn/Article/details/gtcqqksovf.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuanzx.com/Article/details/gtvrkagapz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shuidangran.top/Article/details/gtqigqkbsr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jyoumei.cn/Article/details/gtjocwvzdb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yj20258.top/Article/details/gtukvpfoyn.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gticngtxms.html

[I07] 忽略大小写与多行模式
来源：http://dali.fzhhl.top/Article/details/gtbymufezy.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.svipenyu.cn/Article/details/gtuqhyqtul.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.smart0.xyz/Article/details/gtqouenzaq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.kuanghao11.cn/Article/details/gtgvtertzb.html

TS:   /error/gim
来源：http://dali.zhixingplan.top/Article/details/gtzbjjwggg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.aibaodan.cn/Article/details/gtzolgtmkc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hammf.cn/Article/details/gtgvgizuxj.html

Ruby: s.scan(/error/i)
来源：http://dali.cqqwz.cn/Article/details/gthfsdvytr.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sufxvd.cn/Article/details/gtkzaiopat.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cheryme.top/Article/details/gtczqvzpuw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shangyingyoupin.top/Article/details/gtxshjnnho.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.tanke756.top/Article/details/gtlxucqnfe.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yangfankeji.com/Article/details/gtcognbvsb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnqzz.top/Article/details/gtjojjztuo.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.wangshuangyany.cn/Article/details/gtmnwxnxvs.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.snrcjt.cn/Article/details/gtiaesbjtz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xuetiantiany.cn/Article/details/gtwhejrwyg.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shangyingyoupin.top/Article/details/gtqfqivpge.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxxhjhylx.html

J. 日期与时间
来源：http://dali.tianlin.xyz/Article/details/gtvpzeruhp.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtxncidofs.html

[J01] 获取当前时间
来源：http://dali.hammf.cn/Article/details/gtizvnhnmv.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.snrcjt.cn/Article/details/gtdkyjhoql.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jlsjyb.cn/Article/details/gtwanxqxqd.html

JS:   new Date();  Date.now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrzvbdnsb.html

TS:   new Date();  Date.now()
来源：http://dali.mhx1999.top/Article/details/gtnoulcpvu.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hnxiangtu.top/Article/details/gtucrdwmhq.html

Go:   time.Now()
来源：http://dali.andypj.xyz/Article/details/gtrxmcbsfq.html

Ruby: Time.now
来源：http://dali.gogol.net.cn/Article/details/gtcjmseono.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yuanzhike.top/Article/details/gtfwglmeqj.html

[J02] 格式化输出
来源：http://dali.yangfankeji.com/Article/details/gtigntwvgi.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.0kj1m.cn/Article/details/gtcsikkszx.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yueranfly.top/Article/details/gtencuypyp.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.guannengcc.top/Article/details/gtoeaihdzo.html

TS:   d.toISOString()
来源：http://dali.nanxuanxn.top/Article/details/gtfcaldbuf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.dashuyun.cn/Article/details/gtozyyshtz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sufxvd.cn/Article/details/gtfzhonvbj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hongshengwenyu.top/Article/details/gtivlkfxka.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hywenlv.cn/Article/details/gtbekfycoz.html

[J03] 字符串解析为日期
来源：http://dali.shangyingyoupin.top/Article/details/gtdjubvcjm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hysaishi.cn/Article/details/gtzaloyuyh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yuanzhike.top/Article/details/gtfxfckbgn.html

JS:   new Date("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gtaliywhae.html

TS:   new Date("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gthidliygs.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtfjdiyubh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gtxomguhym.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gtazsrwswz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.wangshuangyany.cn/Article/details/gtwrlmmsng.html

[J04] 时间戳与日期互转
来源：http://dali.guowangkeji.top/Article/details/gtexjruyfq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hysaishi.cn/Article/details/gtknoiqdvj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.fzhhl.top/Article/details/gtozlqobnk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zdqjudy.top/Article/details/gtjflkqchj.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.havefunace.top/Article/details/gtgszsvayc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.nanxinkj.top/Article/details/gtxwpiujpq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.snrcjt.cn/Article/details/gtbrubkobv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yonumen.top/Article/details/gtfpphhybb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nanxuanxn.top/Article/details/gtfaagjokb.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj20258.top/Article/details/gthljtnelf.html

Py:   now + timedelta(days=7)
来源：http://dali.hongshengwenyu.top/Article/details/gtkmdgarey.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gaohongyu789.top/Article/details/gtqpfdbiop.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.birdmap.top/Article/details/gtcfdwdpij.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jiagoushi.top/Article/details/gtnsvlrrht.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.0kj1m.cn/Article/details/gtaxtfqnpx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.iojbl.cn/Article/details/gtxkmslsgt.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yvedp.cn/Article/details/gtftrqyome.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.svipenyu.cn/Article/details/gtwdfswagc.html

[J06] 计算两时间之差
来源：http://dali.316326.xyz/Article/details/gtauyxsjem.html

Py:   (end - start).total_seconds()
来源：http://dali.wangshuangyany.cn/Article/details/gtupmomkvz.html

PHP:  $end->diff($start)->days;
来源：http://dali.0kj1m.cn/Article/details/gtzjefwhug.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj20258.top/Article/details/gtnmgltoma.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yanxiufei.cn/Article/details/gtntkfrtoe.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.svipenyu.cn/Article/details/gtumrofiyl.html

Go:   end.Sub(start).Hours()
来源：http://dali.jiagoushi.top/Article/details/gtitkipehb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.chenjidiqi.icu/Article/details/gtkkummxex.html

C#:   (end - start).TotalSeconds
来源：http://dali.tianlin.xyz/Article/details/gtiggvybja.html

[J07] 比较两个日期
来源：http://dali.316326.xyz/Article/details/gtcpgesbuu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.kuanghao11.cn/Article/details/gtfonmjlvz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hongshengwenyu.top/Article/details/gtcvfnmphd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shangyingyoupin.top/Article/details/gtjqtidozd.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.mhx1999.top/Article/details/gtncupzoez.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhijiandao.cn/Article/details/gtpipiroei.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xinyue.icu/Article/details/gtxiqrgaja.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gtofrqdftg.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hfpthk.cn/Article/details/gtfgnmzfji.html

[J08] 提取年月日与星期
来源：http://dali.vqdsnc.cn/Article/details/gtjyfxfyds.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.havefunace.top/Article/details/gtnhinxwwy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shzxlz.cn/Article/details/gtdscbyopr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zdqjudy.top/Article/details/gtlmdvzdzs.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhiwuduotai.top/Article/details/gtloqoqkai.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.wangshuangyany.cn/Article/details/gthtptpjdm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.meibo888.top/Article/details/gtucqvgvnl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.snrcjt.cn/Article/details/gttskeqztq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yj202588.top/Article/details/gtbzxzhzwt.html

[J09] 时区处理
来源：http://dali.yanxiufei.cn/Article/details/gtldfmybfs.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nanxuanxn.top/Article/details/gtpduaujyw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvvbrjorg.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.c1oappe.top/Article/details/gteimaxutk.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.birdmap.top/Article/details/gtxsfawzns.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.chenlongwang.top/Article/details/gtaktrvseu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj20258888.top/Article/details/gtgmmtluax.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbijayyhd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenzaomai.com/Article/details/gtqudqtdro.html

[J10] 取今天 / 本月第一天
来源：http://dali.wangshuangyany.cn/Article/details/gtyllftrtg.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gzhubu.top/Article/details/gtpwisgaxo.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.quarkkingdee.top/Article/details/gtjtdhcpcc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhoulong.xyz/Article/details/gtvnyfijlg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhengqikj.top/Article/details/gtujqjiaee.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hywenlv.cn/Article/details/gtqqpnkezd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinyuanbaomall.cn/Article/details/gteehqcanh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shuidangran.top/Article/details/gtaqybbrtr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtksuxsiqx.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtljzjhetn.html

K. JSON 与序列化
来源：http://dali.jinqigufen.top/Article/details/gtvceccwjm.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjmcjwhvg.html

[K01] 对象转 JSON 字符串
来源：http://dali.havefunace.top/Article/details/gtfymaxrkp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yueranfly.top/Article/details/gtbyefznbo.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yueranfly.top/Article/details/gtkjudfjaz.html

JS:   JSON.stringify(obj)
来源：http://dali.smart0.xyz/Article/details/gtiwdilmxf.html

TS:   JSON.stringify(obj)
来源：http://dali.daxiang520.top/Article/details/gtsansuvce.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yongpay.top/Article/details/gtdytatckw.html

Go:   json.Marshal(obj)
来源：http://dali.guowangkeji.top/Article/details/gtpbliqprb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sufxvd.cn/Article/details/gtqndxlrlq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.snrcjt.cn/Article/details/gtbtdbngns.html

[K02] JSON 字符串转对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdxvidxcb.html

Py:   json.loads(s)
来源：http://dali.yangfankeji.com/Article/details/gtbmjewxdq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.nanxuanxn.top/Article/details/gtajrdnbhp.html

JS:   JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtpwpqlnep.html

TS:   JSON.parse(s)
来源：http://dali.dashuyun.cn/Article/details/gtkbsbizft.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xylfe.cn/Article/details/gtlzwbvzqf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.vqdsnc.cn/Article/details/gtoovpnocw.html

Ruby: JSON.parse(s)
来源：http://dali.ybcxt.top/Article/details/gttkdbpgbz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gotoacloud.top/Article/details/gtmrqwixvl.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhoulong.xyz/Article/details/gttqhmgtcn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yongpay.top/Article/details/gtjdpeurab.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jiagoushi.top/Article/details/gtoxioomxt.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.nwbrower.top/Article/details/gtzguqwfmz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sysykeji.top/Article/details/gtlzibuuot.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.fengsongda.top/Article/details/gtkwnjquay.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinqigfzy.top/Article/details/gthffgkyqh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtncplcchj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hnxiangtu.top/Article/details/gtomddqwkt.html

[K04] 读取 JSON 文件
来源：http://dali.chenzaomai.com/Article/details/gtgfbnperk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jlsjyb.cn/Article/details/gtwiaxbhbo.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gzhubu.top/Article/details/gtahiqhjsp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yueranfly.top/Article/details/gtvyzyktft.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gogol.net.cn/Article/details/gtknfbwlqp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ivvv.top/Article/details/gtrdkfxlij.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hywenlv.cn/Article/details/gtiequedxm.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yj20258888.top/Article/details/gttcsbzafe.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinghuilouyu.cn/Article/details/gttxzirpnw.html

[K05] 深拷贝对象
来源：http://dali.yuxming.cn/Article/details/gtrciycqjm.html

Py:   copy.deepcopy(obj)
来源：http://dali.ehwqpu.com/Article/details/gtqjevcssn.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yangfankeji.com/Article/details/gtbzrqcpvg.html

JS:   structuredClone(obj)
来源：http://dali.yueranfly.top/Article/details/gthyuhnzoe.html

TS:   structuredClone(obj)
来源：http://dali.tian-w.cn/Article/details/gtsybidvxr.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ydzc1.top/Article/details/gtayirbuov.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ydzc1.top/Article/details/gtjblswpak.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.vqdsnc.cn/Article/details/gtzobbyxhu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hongshengwenyu.top/Article/details/gtepchvuso.html

[K06] 解析 URL 查询串
来源：http://dali.guowangkeji.top/Article/details/gtcyrcqjao.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.guowangkeji.top/Article/details/gtlggpblnt.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.bjfxy.top/Article/details/gtsbygxuvo.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfnzfumaj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sufxvd.cn/Article/details/gtueqfhmwg.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinqigufen.top/Article/details/gtaiwtxufs.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gteigksrwp.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.havefunace.top/Article/details/gttjkylxsk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xuanzx.com/Article/details/gtmvvbifib.html

[K07] 进制转换
来源：http://dali.9152youxi.cn/Article/details/gtmjvehesz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gtuslvoeic.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinqigfzy.top/Article/details/gtgygreefd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gtwjvsiybe.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gtodcxhwfy.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gtivfmeuxa.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jqgfzy.top/Article/details/gtqbucmgbb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ehwqpu.com/Article/details/gtdljstghz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gtwfnudavk.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yj20258.top/Article/details/gtffrzqjhd.html

Py:   pickle.dumps(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtbdldyurd.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gogol.net.cn/Article/details/gtebougsgp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.dianchejie.cn/Article/details/gtliaolnox.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhengqikj.top/Article/details/gtcwylcbaj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sweek.top/Article/details/gtfincymon.html

Go:   encoding/gob
来源：http://dali.sweek.top/Article/details/gtyfzaiarg.html

Ruby: Marshal.dump(obj)
来源：http://dali.xylfe.cn/Article/details/gtslpwmzmd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.nanxuanxn.top/Article/details/gtvjmbhnhm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtybheuvlr.html

L. 网络请求
来源：http://dali.yanxiufei.cn/Article/details/gtfvebsoxg.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtxapsjriv.html

[L01] 发送 GET 请求
来源：http://dali.nanxuanxn.top/Article/details/gtbggqmefr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xuetiantiany.cn/Article/details/gtvdkphbqo.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ydzc1.top/Article/details/gtifbvbvcf.html

JS:   await fetch(url)
来源：http://dali.hnqzz.top/Article/details/gtzzfkoijp.html

TS:   await fetch(url)
来源：http://dali.hfpthk.cn/Article/details/gtugffwcyo.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.chenlongwang.top/Article/details/gtpzgoqqih.html

Go:   resp, err := http.Get(url)
来源：http://dali.yj20258.top/Article/details/gtroeyvthn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sysykeji.top/Article/details/gtsbnbzels.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hnxiangtu.top/Article/details/gtcfdlvtka.html

[L02] 发送 POST JSON
来源：http://dali.sysykeji.top/Article/details/gtdlitqtpa.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shzxlz.cn/Article/details/gtvbssnjmp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zdqjudy.top/Article/details/gtigbawtwo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.redwolf501.top/Article/details/gtvijeugpg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtevurpsov.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.quarkkingdee.top/Article/details/gtpltjxlit.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jqgfzy.top/Article/details/gtymnmosfv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnlunxovf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.tianlin.xyz/Article/details/gtdrnfkwmj.html

[L03] 设置自定义请求头
来源：http://dali.tian-w.cn/Article/details/gtkxlpmpho.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cqqwz.cn/Article/details/gtnwawviek.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zdqjudy.top/Article/details/gtpxgboxrl.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fzhhl.top/Article/details/gtkunzeavm.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yvedp.cn/Article/details/gtardeushz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cdnleiting.top/Article/details/gtksfonvtj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jinqigufen.top/Article/details/gtihlnkoif.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hongshengwenyu.top/Article/details/gtnukfiajn.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.havefunace.top/Article/details/gtoovmqati.html

[L04] 设置超时
来源：http://dali.cdnleiting.top/Article/details/gtopmrzilc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.wangshuangyany.cn/Article/details/gtjbbxmtzi.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.tanke756.top/Article/details/gtuhidivmt.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxinkj.top/Article/details/gtzmfuhzpz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtakhuuabj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jiagoushi.top/Article/details/gtwsnsdglg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlefisegt.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cqqwz.cn/Article/details/gtstkxgcwt.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenjidiqi.icu/Article/details/gtxteslpva.html

[L05] 上传文件（multipart）
来源：http://dali.jyoumei.cn/Article/details/gtzhpeftlh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.tanke756.top/Article/details/gttnvoybjp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.smart0.xyz/Article/details/gtrzurwbrc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.aizwys.cn/Article/details/gtcnxecnnh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgufenzy.top/Article/details/gtugtautui.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.haohaochexian.top/Article/details/gtmwhmzfwq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sweek.top/Article/details/gtjtkvzajl.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xuetiantiany.cn/Article/details/gtuiscqbaf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtmwrnlckb.html

[L06] 解析响应为 JSON
来源：http://dali.hongshengwenyu.top/Article/details/gtrpwmxjjj.html

Py:   resp.json()
来源：http://dali.shangyingyoupin.top/Article/details/gtdxmxofmk.html

PHP:  json_decode($body, true);
来源：http://dali.kuanghao11.cn/Article/details/gtmebnusor.html

JS:   await resp.json()
来源：http://dali.xinyue.icu/Article/details/gthziastkp.html

TS:   await resp.json()
来源：http://dali.yongpay.top/Article/details/gthfusigip.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hywenlv.cn/Article/details/gtwixhldrf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.birdmap.top/Article/details/gtmjykbtlj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sysykeji.top/Article/details/gtrzyrflzu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwkwfknwy.html


<!-- 参考信息 -->