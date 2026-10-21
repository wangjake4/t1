代发 wailian999

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xinyue.icu/Article/details/gtvgiairfp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yuanzhike.top/Article/details/gtktdmnrmo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nwbrower.top/Article/details/gtivpovyri.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jyoumei.cn/Article/details/gtqdgpqqgm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinqigufen.top/Article/details/gtgbsubszj.html

Go:   defer f.Close()
来源：http://dali.xuanzx.com/Article/details/gttuillkzw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hammf.cn/Article/details/gthbfqbkyq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtdjsqkzmv.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtllpzghoj.html

I. 正则表达式
来源：http://dali.zhixingplan.top/Article/details/gtbrhxyefj.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtxpuzguvw.html

[I01] 判断是否匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtisuvbert.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jqgfzy.top/Article/details/gtlomucvbt.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinqigufen.top/Article/details/gtaxdytvsn.html

JS:   /\d+/.test(s)
来源：http://dali.svipenyu.cn/Article/details/gtdgssiisg.html

TS:   /\d+/.test(s)
来源：http://dali.9152youxi.cn/Article/details/gtgyfebyvq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ivvv.top/Article/details/gtokdbtjur.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.tianlin.xyz/Article/details/gtgwajojed.html

Ruby: s.match?(/\d+/)
来源：http://dali.xylfe.cn/Article/details/gthfhtbniq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.chenjidiqi.icu/Article/details/gtrafibtig.html

[I02] 提取所有匹配
来源：http://dali.daria6918.cn/Article/details/gttqqinpqp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gotoacloud.top/Article/details/gtilybrgdk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.9152youxi.cn/Article/details/gtiagvftel.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.guannengcc.top/Article/details/gtejdriyqz.html

TS:   s.match(/\d+/g)
来源：http://dali.yangfankeji.com/Article/details/gthcqbdhai.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.quarkkingdee.top/Article/details/gtcitirxmd.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.nanxuanxn.top/Article/details/gtfdvllfle.html

Ruby: s.scan(/\d+/)
来源：http://dali.daxiang520.top/Article/details/gtokpuqbny.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gthnouibyy.html

[I03] 提取捕获分组
来源：http://dali.yuanzhike.top/Article/details/gtcfuaesfr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpninctxs.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.feifeiyinyue.top/Article/details/gtshqyffkx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yuxming.cn/Article/details/gtuhabason.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvcstlfiq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yueranfly.top/Article/details/gtlvszjute.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shanyushiyangtech.top/Article/details/gtldgzopne.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gogol.net.cn/Article/details/gtmsjfifsx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.c1oappe.top/Article/details/gtkixzeqcs.html

[I04] 正则替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfssmbcwf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.redwolf501.top/Article/details/gtcbqabuie.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtjfpzwsou.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ydzc1.top/Article/details/gtghqcabzi.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hfpthk.cn/Article/details/gtudavrocf.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.quarkkingdee.top/Article/details/gtcuwgkufl.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cqqwz.cn/Article/details/gtbcqdbuod.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.iojbl.cn/Article/details/gtsccogbat.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yuanzhike.top/Article/details/gtsjyxdibx.html

[I05] 按正则拆分
来源：http://dali.shanyushiyangtech.top/Article/details/gtufprfuav.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.sysykeji.top/Article/details/gtcksqcwrn.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.birdmap.top/Article/details/gtvtipwaqu.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.chenzaomai.com/Article/details/gtprbvzfvd.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.vqdsnc.cn/Article/details/gtnwmzxsvc.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yongpay.top/Article/details/gtnuefyixt.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yonumen.top/Article/details/gtvkcauczj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gtgrscmghm.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sweek.top/Article/details/gtnrqywlrt.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xziqi.cn/Article/details/gtayiwyser.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthixzurqo.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sweek.top/Article/details/gtulkcxknt.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shuidangran.top/Article/details/gtbrqnngdt.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlwllplxw.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gtccbpbiwy.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.svipenyu.cn/Article/details/gtwpgjvyrv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jyoumei.cn/Article/details/gtdpgrkliu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ydzc1.top/Article/details/gtcagpyvne.html

[I07] 忽略大小写与多行模式
来源：http://dali.gogol.net.cn/Article/details/gtarhghwll.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.kuanghao11.cn/Article/details/gtpumogqtu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlphyofde.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jqgfzy.top/Article/details/gtigqohcwd.html

TS:   /error/gim
来源：http://dali.sweek.top/Article/details/gtujywicly.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.wangshuangyany.cn/Article/details/gtkzqoufik.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gteoxinnym.html

Ruby: s.scan(/error/i)
来源：http://dali.gaohongyu789.top/Article/details/gtrtbmlath.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gzhubu.top/Article/details/gtgfxqdlgn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ehwqpu.com/Article/details/gtnzawafuq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.chenjidiqi.icu/Article/details/gtzfxpqikx.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.daxiang520.top/Article/details/gtcrosmggb.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zdqjudy.top/Article/details/gtgqckqmss.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhongyouzk.top/Article/details/gtgfriulgy.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpxrjvnpa.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cashguo.top/Article/details/gtyzmgbhyu.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvmdllbst.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.kuanghao11.cn/Article/details/gteswnxmsq.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gthhrwqqsp.html

J. 日期与时间
来源：http://dali.iojbl.cn/Article/details/gtgmqwolmd.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtajcigxeh.html

[J01] 获取当前时间
来源：http://dali.sweek.top/Article/details/gtohkyarre.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cqqwz.cn/Article/details/gtqppqmgwf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xziqi.cn/Article/details/gtsdgqwimg.html

JS:   new Date();  Date.now()
来源：http://dali.yanxiufei.cn/Article/details/gtowdrmdpp.html

TS:   new Date();  Date.now()
来源：http://dali.jinqigfzy.top/Article/details/gtudgbzhbl.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hfpthk.cn/Article/details/gtuplmurrc.html

Go:   time.Now()
来源：http://dali.0kj1m.cn/Article/details/gtpewkzykb.html

Ruby: Time.now
来源：http://dali.daria6918.cn/Article/details/gtznzxqmvv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hnqzz.top/Article/details/gthwrocxlc.html

[J02] 格式化输出
来源：http://dali.sysykeji.top/Article/details/gtclyexnhv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hongshengwenyu.top/Article/details/gtucrmsspn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jqgufenzy.top/Article/details/gtmzbnrrhc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xinyue.icu/Article/details/gtpavveukj.html

TS:   d.toISOString()
来源：http://dali.meibo888.top/Article/details/gtprahhgdm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.wangdashe.top/Article/details/gtlpucbudd.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.quarkkingdee.top/Article/details/gtsqbfutbn.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jiagoushi.top/Article/details/gttldbuner.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.fengsongda.top/Article/details/gtqajhhzmh.html

[J03] 字符串解析为日期
来源：http://dali.nanxuanxn.top/Article/details/gtnaeoaojc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.tanke756.top/Article/details/gtofiapqhr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sufxvd.cn/Article/details/gtwwnfayqb.html

JS:   new Date("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwxexcbyz.html

TS:   new Date("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gtzhhedwac.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnadgzhly.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sweek.top/Article/details/gtygwbbvbo.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gtsnmzresm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shuidangran.top/Article/details/gtzeevxxqs.html

[J04] 时间戳与日期互转
来源：http://dali.jinqigfzy.top/Article/details/gtsudisolg.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.chenjidiqi.icu/Article/details/gtcioshbwf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gogol.net.cn/Article/details/gtuyeysqkc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zdqjudy.top/Article/details/gtcdjucoyb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.svipenyu.cn/Article/details/gtawkypsyx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shzxlz.cn/Article/details/gtoltrvcgd.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ydzc1.top/Article/details/gtvnytakfs.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sysykeji.top/Article/details/gtjdndusmh.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.bjfxy.top/Article/details/gticbqfnod.html

[J05] 时间加减（加 7 天）
来源：http://dali.jlsjyb.cn/Article/details/gtbmvvqvoo.html

Py:   now + timedelta(days=7)
来源：http://dali.yvedp.cn/Article/details/gtkhqbeorq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hongshengwenyu.top/Article/details/gtribimsqq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtolldnwlq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuetiantiany.cn/Article/details/gtejvhdjqi.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhiwuduotai.top/Article/details/gtnmejrxyj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.vqdsnc.cn/Article/details/gtqxlezatj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.0kj1m.cn/Article/details/gtjukeqlop.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.tanke756.top/Article/details/gtxwkktouc.html

[J06] 计算两时间之差
来源：http://dali.hnxiangtu.top/Article/details/gtktserbdb.html

Py:   (end - start).total_seconds()
来源：http://dali.jiagoushi.top/Article/details/gthabtggal.html

PHP:  $end->diff($start)->days;
来源：http://dali.yj20258.top/Article/details/gtvctqqonc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yongpay.top/Article/details/gtaripwjur.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shuidangran.top/Article/details/gtaiyykwub.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sweek.top/Article/details/gtvsombdqm.html

Go:   end.Sub(start).Hours()
来源：http://dali.aizwys.cn/Article/details/gtnggngzgh.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinqigufen.top/Article/details/gtbooqlzdt.html

C#:   (end - start).TotalSeconds
来源：http://dali.ivvv.top/Article/details/gtrhgcyabd.html

[J07] 比较两个日期
来源：http://dali.pycfn.com/Article/details/gtehzuzptn.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gtjjpclaht.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sysykeji.top/Article/details/gtshncktev.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.pengpengdd.cyou/Article/details/gtcccnnich.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yuxming.cn/Article/details/gtwytuzhtx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.feifeiyinyue.top/Article/details/gtstlqvdsw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hysaishi.cn/Article/details/gtvhvkupvg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xinyue.icu/Article/details/gtlphbmoro.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yonumen.top/Article/details/gtqryivmev.html

[J08] 提取年月日与星期
来源：http://dali.nanxuanxn.top/Article/details/gtulsheomr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhoulong.xyz/Article/details/gtipppgdpx.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hfpthk.cn/Article/details/gtmpigjdcy.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sysykeji.top/Article/details/gtsjkvdexk.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xylfe.cn/Article/details/gttffssyhp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sxryk.cn/Article/details/gtfrjiaoji.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.snrcjt.cn/Article/details/gtuylxfhel.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhixingplan.top/Article/details/gtekijelre.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvinnohfs.html

[J09] 时区处理
来源：http://dali.snrcjt.cn/Article/details/gtmmlhrogn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.daxiang520.top/Article/details/gttijcpsnc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jlsjyb.cn/Article/details/gtrctlarxa.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hfpthk.cn/Article/details/gtnjmwjxjv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258.top/Article/details/gtftcejuqh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yonumen.top/Article/details/gtznchmhcp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.0kj1m.cn/Article/details/gtmktasnln.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpeipqkzz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yj20258.top/Article/details/gtgnvnwhxo.html

[J10] 取今天 / 本月第一天
来源：http://dali.jyoumei.cn/Article/details/gtdatngvms.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cqqwz.cn/Article/details/gtwtkgkmaq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.guowangkeji.top/Article/details/gtqtnmssug.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtycyzzjnb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ivvv.top/Article/details/gtgvnqfvji.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.c1oappe.top/Article/details/gthltjxvky.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsncomwjv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yongpay.top/Article/details/gtijjkicmc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.nanxinkj.top/Article/details/gtovvnzbvy.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpnxstkap.html

K. JSON 与序列化
来源：http://dali.zhixingplan.top/Article/details/gtimdzcfkx.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gteqtebwyl.html

[K01] 对象转 JSON 字符串
来源：http://dali.cqqwz.cn/Article/details/gtdkwbzxog.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xuetiantiany.cn/Article/details/gtdoclegye.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgufenzy.top/Article/details/gthfftzjcq.html

JS:   JSON.stringify(obj)
来源：http://dali.jyoumei.cn/Article/details/gtvjkaqkju.html

TS:   JSON.stringify(obj)
来源：http://dali.sufxvd.cn/Article/details/gtrlzzbbzq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hfpthk.cn/Article/details/gtnshcceds.html

Go:   json.Marshal(obj)
来源：http://dali.gotoacloud.top/Article/details/gtdeqsnmsz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sysykeji.top/Article/details/gtvhuhogih.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.dashuyun.cn/Article/details/gtpoyddgng.html

[K02] JSON 字符串转对象
来源：http://dali.redwolf501.top/Article/details/gtgychdbtu.html

Py:   json.loads(s)
来源：http://dali.jqgfzy.top/Article/details/gtkztryvdh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.svipenyu.cn/Article/details/gtbygbztsz.html

JS:   JSON.parse(s)
来源：http://dali.xziqi.cn/Article/details/gtchvuaotq.html

TS:   JSON.parse(s)
来源：http://dali.jinqigfzy.top/Article/details/gtiilbhchf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sxryk.cn/Article/details/gthaqdbpfi.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.9152youxi.cn/Article/details/gtyfiyzkdv.html

Ruby: JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gtttoslggq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.daxiang520.top/Article/details/gtqywfwjue.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yj20258.top/Article/details/gthnebcujs.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hammf.cn/Article/details/gthwfzthes.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmotuhojo.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hywenlv.cn/Article/details/gtytojvtzj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhoulong.xyz/Article/details/gtqwwlgexy.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdwfzhdwc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmfextyaq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yuanzhike.top/Article/details/gtpjwhvand.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqcktimly.html

[K04] 读取 JSON 文件
来源：http://dali.nwbrower.top/Article/details/gtbusnayrm.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.smart0.xyz/Article/details/gtrukwglln.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.0kj1m.cn/Article/details/gtassqnamb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jlsjyb.cn/Article/details/gtnbahnbzt.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yongpay.top/Article/details/gtamrmahop.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.bjfxy.top/Article/details/gtqzqllrck.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.feifeiyinyue.top/Article/details/gtqjtwwrfq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpdnfnjqz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hongshengwenyu.top/Article/details/gtknqhifdk.html

[K05] 深拷贝对象
来源：http://dali.dashuyun.cn/Article/details/gtrkzqlryd.html

Py:   copy.deepcopy(obj)
来源：http://dali.shzxlz.cn/Article/details/gtcchgarse.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gzhubu.top/Article/details/gtcanmxels.html

JS:   structuredClone(obj)
来源：http://dali.xziqi.cn/Article/details/gtffetxgdp.html

TS:   structuredClone(obj)
来源：http://dali.wangdashe.top/Article/details/gtuwqcsgjl.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yj202588.top/Article/details/gticixfmpw.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yvedp.cn/Article/details/gtajxpawsm.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jinqigfzy.top/Article/details/gtumclvebq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.smart0.xyz/Article/details/gtuikgjazr.html

[K06] 解析 URL 查询串
来源：http://dali.shuidangran.top/Article/details/gtrpqfcvfv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkmelrhbv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.daxiang520.top/Article/details/gtbqfqiqda.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxinkj.top/Article/details/gtcasppljn.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenlongwang.top/Article/details/gtoemwtxwa.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ppjwa.cn/Article/details/gtbqkaisdr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yonumen.top/Article/details/gtptzocmte.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gaohongyu789.top/Article/details/gtjyhrvriu.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.0kj1m.cn/Article/details/gtrcfizhke.html

[K07] 进制转换
来源：http://dali.daria6918.cn/Article/details/gtjbcjqmgb.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gtidmwjnvp.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmldgfnfs.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gtjuguyppc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gtojmpbavh.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtwdqoczam.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gzhubu.top/Article/details/gtycbbwmud.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzdtvfwyv.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gtdlaaivvz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfikvobxb.html

Py:   pickle.dumps(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtunsbzyvw.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.vqdsnc.cn/Article/details/gtvcmxvsfp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.iojbl.cn/Article/details/gtkumfikim.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sufxvd.cn/Article/details/gtbjwdyabk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.tianlin.xyz/Article/details/gtreuooivj.html

Go:   encoding/gob
来源：http://dali.ppjwa.cn/Article/details/gtuzqcdrdm.html

Ruby: Marshal.dump(obj)
来源：http://dali.xziqi.cn/Article/details/gtgbkqymxs.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.guowangkeji.top/Article/details/gtddpeizzd.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtcralppxx.html

L. 网络请求
来源：http://dali.quarkkingdee.top/Article/details/gtwmnhpiza.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtklsxjswu.html

[L01] 发送 GET 请求
来源：http://dali.redwolf501.top/Article/details/gtailblwtw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.smart0.xyz/Article/details/gtrbzlziqg.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.wangshuangyany.cn/Article/details/gtzojiqoeo.html

JS:   await fetch(url)
来源：http://dali.shuidangran.top/Article/details/gtsjtqkzdz.html

TS:   await fetch(url)
来源：http://dali.gogol.net.cn/Article/details/gtfkpkloem.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xylfe.cn/Article/details/gtxkxyorsi.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfhwkvjqf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ppjwa.cn/Article/details/gtoviuovrg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.redwolf501.top/Article/details/gtwradonyq.html

[L02] 发送 POST JSON
来源：http://dali.chenjidiqi.icu/Article/details/gtdzirpcvh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.haohaochexian.top/Article/details/gtlbivhiwx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cashguo.top/Article/details/gtopstkchc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgufenzy.top/Article/details/gtmffarxhg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.0kj1m.cn/Article/details/gtvvmaddqv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xuanzx.com/Article/details/gtngmulzmd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zycfv.cn/Article/details/gtefpwoxnh.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.chenjidiqi.icu/Article/details/gtnbvjnpog.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ydzc1.top/Article/details/gtkzuxtodz.html

[L03] 设置自定义请求头
来源：http://dali.fengsongda.top/Article/details/gtycudendi.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hnxiangtu.top/Article/details/gtojoboouk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xuetiantiany.cn/Article/details/gtikyovpsp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuetiantiany.cn/Article/details/gtgjbfcmsd.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daxiang520.top/Article/details/gtmtybaaxj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.haohaochexian.top/Article/details/gtwofeuhrw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yj202588.top/Article/details/gtbthrimqt.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xziqi.cn/Article/details/gtjnttosre.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhongyouzk.top/Article/details/gtvptwnxzn.html

[L04] 设置超时
来源：http://dali.jianghu66.top/Article/details/gtyiccsabb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkulbbwsd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cdnleiting.top/Article/details/gtmixzdoje.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daxiang520.top/Article/details/gtykrlcden.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hongshengwenyu.top/Article/details/gthwneqdzz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yuxming.cn/Article/details/gtrqqeusim.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jlsjyb.cn/Article/details/gtzyeflcll.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.meibo888.top/Article/details/gtqgrdneix.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jianghu66.top/Article/details/gtgqvuoxgd.html

[L05] 上传文件（multipart）
来源：http://dali.hysaishi.cn/Article/details/gtxboeiypk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nanxinkj.top/Article/details/gtdkecbvjr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hnqzz.top/Article/details/gtihpisqna.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.meibo888.top/Article/details/gtbvxwgamb.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.pengpengdd.cyou/Article/details/gtcmmnxynx.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.wangdashe.top/Article/details/gtzwxwwgwa.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cashguo.top/Article/details/gtwkfbdabl.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ybcxt.top/Article/details/gtsbcbtkrk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yongpay.top/Article/details/gtlikgbhtt.html

[L06] 解析响应为 JSON
来源：http://dali.iojbl.cn/Article/details/gthqpbtapv.html


<!-- 参考信息 -->