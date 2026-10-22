代发 wailian999

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhixingplan.top/Article/details/gt2ypnkzcux.html

Go:   defer f.Close()
来源：http://dali.xuetiantiany.cn/Article/details/gt2ryagtezz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.gogol.net.cn/Article/details/gt2mayzoqmq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2fjxiepht.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2mkycynkz.html

I. 正则表达式
来源：http://dali.jiagoushi.top/Article/details/gt2gzspfptj.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2grnvfagv.html

[I01] 判断是否匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rgwfpbss.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.nanxuanxn.top/Article/details/gt2egsmtrbk.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.guowangkeji.top/Article/details/gt2twrygahn.html

JS:   /\d+/.test(s)
来源：http://dali.zdqjudy.top/Article/details/gt2ngkvalkr.html

TS:   /\d+/.test(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2xzqyyxnh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.nanxinkj.top/Article/details/gt2csbithvq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2osbgdjqi.html

Ruby: s.match?(/\d+/)
来源：http://dali.shangyingyoupin.top/Article/details/gt2nldfgrhi.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hhkxcnkp.html

[I02] 提取所有匹配
来源：http://dali.pycfn.com/Article/details/gt2svyrqapx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jqgufenzy.top/Article/details/gt2ekilnuzx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cashguo.top/Article/details/gt2ayzfhmdz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ivvv.top/Article/details/gt2jyngwhfy.html

TS:   s.match(/\d+/g)
来源：http://dali.hnxiangtu.top/Article/details/gt2lfgzjrlc.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2cvjkbyka.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zbcyeiaj.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhongyouzk.top/Article/details/gt2yqhkftry.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xuanzx.com/Article/details/gt2ueitmafh.html

[I03] 提取捕获分组
来源：http://dali.fzhhl.top/Article/details/gt2vkysaymc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2obdgvfxy.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.fzhhl.top/Article/details/gt2xhkjboto.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xinyue.icu/Article/details/gt2rcghxomz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.316326.xyz/Article/details/gt2trgnyorp.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xuetiantiany.cn/Article/details/gt2yozppnwz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yj20258888.top/Article/details/gt2mgvzkhsa.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.chenlongwang.top/Article/details/gt2wfdcbdgh.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xuanzx.com/Article/details/gt2ohamlisf.html

[I04] 正则替换
来源：http://dali.yuxming.cn/Article/details/gt2lxbnzmew.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.tian-w.cn/Article/details/gt2xdwosdgq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sxryk.cn/Article/details/gt2valxnbee.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.iojbl.cn/Article/details/gt2krsewtnf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2kehlqpui.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yongpay.top/Article/details/gt2phsddezu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.birdmap.top/Article/details/gt2slvvkjeo.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.fzhhl.top/Article/details/gt2jwvgmdty.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinqigufen.top/Article/details/gt2rejiirbt.html

[I05] 按正则拆分
来源：http://dali.gogol.net.cn/Article/details/gt2zafxwwlo.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zycfv.cn/Article/details/gt2gbxysxtf.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sysykeji.top/Article/details/gt2fqfbtsnb.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hammf.cn/Article/details/gt2ilhuussq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yangfankeji.com/Article/details/gt2rtfqfqym.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gogol.net.cn/Article/details/gt2epszldnf.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zdqjudy.top/Article/details/gt2yopdqnek.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xziqi.cn/Article/details/gt2kpsqixxc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.dashuyun.cn/Article/details/gt2hxuhjflc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhengqikj.top/Article/details/gt2pwbdozji.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhixingplan.top/Article/details/gt2zpxgncmu.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yioejhyx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jlsjyb.cn/Article/details/gt2ffieyrmh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xylfe.cn/Article/details/gt2bxyaajjg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.c1oappe.top/Article/details/gt2ooqsnabp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yanxiufei.cn/Article/details/gt2uvumnwlz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhengqikj.top/Article/details/gt2fjpjrhgm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.meibo888.top/Article/details/gt2ystpvvoc.html

[I07] 忽略大小写与多行模式
来源：http://dali.tanke756.top/Article/details/gt2cdifneon.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rzzrcmib.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gzhubu.top/Article/details/gt2acwxdvtl.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.quarkkingdee.top/Article/details/gt2jjpdkdfi.html

TS:   /error/gim
来源：http://dali.ybcxt.top/Article/details/gt2hcmexjey.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.dianchejie.cn/Article/details/gt2ocygette.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.redwolf501.top/Article/details/gt2vvgjfrop.html

Ruby: s.scan(/error/i)
来源：http://dali.cashguo.top/Article/details/gt2xepyuluj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yj202588.top/Article/details/gt2hzvoudrv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.quarkkingdee.top/Article/details/gt2kwkjqjih.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yj202588.top/Article/details/gt2hsomhtiy.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cashguo.top/Article/details/gt2tyvyynzc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hywenlv.cn/Article/details/gt2xmimwdkk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wkymepbl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hnxiangtu.top/Article/details/gt2prhzmpau.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xziqi.cn/Article/details/gt2nshwuwwd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shangyingyoupin.top/Article/details/gt2cbiiaoof.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xziqi.cn/Article/details/gt2ybatawne.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2kpnpjent.html

J. 日期与时间
来源：http://dali.haohaochexian.top/Article/details/gt2roxdamfy.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2brynldtr.html

[J01] 获取当前时间
来源：http://dali.wangdashe.top/Article/details/gt2cuyqvtxq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ydzc1.top/Article/details/gt2egwuziyo.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yonumen.top/Article/details/gt2wlmrjpab.html

JS:   new Date();  Date.now()
来源：http://dali.cucudq.cn/Article/details/gt2iedjhaig.html

TS:   new Date();  Date.now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gfukoecc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ivvv.top/Article/details/gt2kdozhbpr.html

Go:   time.Now()
来源：http://dali.jyoumei.cn/Article/details/gt2wmztgevd.html

Ruby: Time.now
来源：http://dali.fzhhl.top/Article/details/gt2oidpsxor.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xinyue.icu/Article/details/gt2tcpikjua.html

[J02] 格式化输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xyswaskg.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258888.top/Article/details/gt2mjgyzcmp.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lpdegxbe.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhengqikj.top/Article/details/gt2msolmfez.html

TS:   d.toISOString()
来源：http://dali.pycfn.com/Article/details/gt2zivlelph.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinqigfzy.top/Article/details/gt2crooamsj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cashguo.top/Article/details/gt2zlmpzpmu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guannengcc.top/Article/details/gt2yzcycimk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.dashuyun.cn/Article/details/gt2ljvxlwlo.html

[J03] 字符串解析为日期
来源：http://dali.ppjwa.cn/Article/details/gt2mueotyof.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.feifeiyinyue.top/Article/details/gt2hkxocosn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xuanzx.com/Article/details/gt2crueignn.html

JS:   new Date("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gt2reutafde.html

TS:   new Date("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gt2tsttzqmw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gt2uducdvje.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gt2stndbdql.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gt2qcqosral.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gaohongyu789.top/Article/details/gt2lqasevum.html

[J04] 时间戳与日期互转
来源：http://dali.yj20258888.top/Article/details/gt2ibzfrvgp.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.haohaochexian.top/Article/details/gt2sxxiekal.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhongyouzk.top/Article/details/gt2dmzfvukw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ehwqpu.com/Article/details/gt2apzrihya.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhongyouzk.top/Article/details/gt2jzoaexme.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hnxiangtu.top/Article/details/gt2ftoibojy.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jyoumei.cn/Article/details/gt2hpbsaiyr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xuanzx.com/Article/details/gt2mjoibmmc.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xylfe.cn/Article/details/gt2zruaglav.html

[J05] 时间加减（加 7 天）
来源：http://dali.dianchejie.cn/Article/details/gt2yztdgnhx.html

Py:   now + timedelta(days=7)
来源：http://dali.bjfxy.top/Article/details/gt2tdmuttcc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yueranfly.top/Article/details/gt2ojjauzmz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tian-w.cn/Article/details/gt2enfljeca.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.vqdsnc.cn/Article/details/gt2phqbxqod.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cucudq.cn/Article/details/gt2jnsuyale.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sysykeji.top/Article/details/gt2ftqonexq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.quarkkingdee.top/Article/details/gt2sfgujnpg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.wangshuangyany.cn/Article/details/gt2kukicspr.html

[J06] 计算两时间之差
来源：http://dali.chenzaomai.com/Article/details/gt2axvujrfk.html

Py:   (end - start).total_seconds()
来源：http://dali.chenlongwang.top/Article/details/gt2vnzoolie.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhengqikj.top/Article/details/gt2mdondmeg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhijiandao.cn/Article/details/gt2odoexkuk.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.chenlongwang.top/Article/details/gt2puvlarix.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yangfankeji.com/Article/details/gt2ymqvqzcg.html

Go:   end.Sub(start).Hours()
来源：http://dali.jqgfzy.top/Article/details/gt2hpegedeh.html

Ruby: end - start                 # 返回秒数
来源：http://dali.fzhhl.top/Article/details/gt2arkpcfma.html

C#:   (end - start).TotalSeconds
来源：http://dali.yanxiufei.cn/Article/details/gt2ndgaroux.html

[J07] 比较两个日期
来源：http://dali.quarkkingdee.top/Article/details/gt2rhrsfcnr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.mhx1999.top/Article/details/gt2bzeyzqnu.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.dianchejie.cn/Article/details/gt2axxbrkra.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenzaomai.com/Article/details/gt2ifaazrnh.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.vqdsnc.cn/Article/details/gt2wodpzgow.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.mhx1999.top/Article/details/gt2kwyhppjg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hfpthk.cn/Article/details/gt2wtqyidwi.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ydzc1.top/Article/details/gt2oorwjcam.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gt2samydpbx.html

[J08] 提取年月日与星期
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ljzaalxn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.chenlongwang.top/Article/details/gt2tvrvjgrb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2seoubeaw.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yueranfly.top/Article/details/gt2gnwtxgxc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xuetiantiany.cn/Article/details/gt2efmnataw.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.nwbrower.top/Article/details/gt2bkbpxubh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhengqikj.top/Article/details/gt2oyfbmnjn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.birdmap.top/Article/details/gt2fuerhplg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.wangdashe.top/Article/details/gt2gwikkncg.html

[J09] 时区处理
来源：http://dali.yonumen.top/Article/details/gt2gxsqivzl.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ppjwa.cn/Article/details/gt2jdtzpwvv.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.guowangkeji.top/Article/details/gt2kgrpvupw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pengpengdd.cyou/Article/details/gt2dlaoayly.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhiwuduotai.top/Article/details/gt2pbhvcjln.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.316326.xyz/Article/details/gt2fefxoueb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tanke756.top/Article/details/gt2tbsochrr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hammf.cn/Article/details/gt2soyfbsrc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xuetiantiany.cn/Article/details/gt2qzofcodv.html

[J10] 取今天 / 本月第一天
来源：http://dali.yvedp.cn/Article/details/gt2suxxtums.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.quarkkingdee.top/Article/details/gt2vtzvflfp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yueranfly.top/Article/details/gt2ofcacphx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.bjfxy.top/Article/details/gt2oshojohj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.pycfn.com/Article/details/gt2zhwobqlu.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2hhoagshf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.tian-w.cn/Article/details/gt2qrjfucmg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lvqnyegw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.vqdsnc.cn/Article/details/gt2hhdfsxmz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2agxfamfd.html

K. JSON 与序列化
来源：http://dali.yuxming.cn/Article/details/gt2njyemjmm.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2bunomcqn.html

[K01] 对象转 JSON 字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2qlgnrzwv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.nanxinkj.top/Article/details/gt2nludicuu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.snrcjt.cn/Article/details/gt2vdjnyqmw.html

JS:   JSON.stringify(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2ufpjtemd.html

TS:   JSON.stringify(obj)
来源：http://dali.yj20258888.top/Article/details/gt2mnvnclvk.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.haohaochexian.top/Article/details/gt2gcqjmcpj.html

Go:   json.Marshal(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2wkplokah.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.fengsongda.top/Article/details/gt2pgqnawko.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fysnhxeb.html

[K02] JSON 字符串转对象
来源：http://dali.zdqjudy.top/Article/details/gt2gayedolk.html

Py:   json.loads(s)
来源：http://dali.nwbrower.top/Article/details/gt2fkfiimjh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jlsbuwxx.html

JS:   JSON.parse(s)
来源：http://dali.andypj.xyz/Article/details/gt2deyphirk.html

TS:   JSON.parse(s)
来源：http://dali.birdmap.top/Article/details/gt2ttxhrbsx.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.fzhhl.top/Article/details/gt2ybwcunwa.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yanxiufei.cn/Article/details/gt2xchjpoco.html

Ruby: JSON.parse(s)
来源：http://dali.bjfxy.top/Article/details/gt2riqbppwl.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2dkoehedw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.nwbrower.top/Article/details/gt2umdzhkfp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gogol.net.cn/Article/details/gt2ynzycmes.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.316326.xyz/Article/details/gt2dwwslnht.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.kuanghao11.cn/Article/details/gt2zlsogxmd.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sxryk.cn/Article/details/gt2agjiabvy.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yj20258888.top/Article/details/gt2srnfcjti.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.tanke756.top/Article/details/gt2asbduvfg.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vyaqsdmv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ybcxt.top/Article/details/gt2ecatoshu.html

[K04] 读取 JSON 文件
来源：http://dali.kuanghao11.cn/Article/details/gt2crahmyhc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ydzc1.top/Article/details/gt2ysvivams.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.iojbl.cn/Article/details/gt2whlvvsdr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cucudq.cn/Article/details/gt2fzkacngh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gogol.net.cn/Article/details/gt2nzvaobon.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.c1oappe.top/Article/details/gt2kvfqbpny.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.havefunace.top/Article/details/gt2wpzgijpz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sysykeji.top/Article/details/gt2crlxkfeb.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinqigfzy.top/Article/details/gt2vkhjvhol.html

[K05] 深拷贝对象
来源：http://dali.hywenlv.cn/Article/details/gt2xykapbwt.html

Py:   copy.deepcopy(obj)
来源：http://dali.sysykeji.top/Article/details/gt2vowzkxso.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yj20258.top/Article/details/gt2npzuiaxm.html

JS:   structuredClone(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ypcyildz.html

TS:   structuredClone(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fucnipev.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.gzhubu.top/Article/details/gt2dyklfzyj.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sysykeji.top/Article/details/gt2rallxiao.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.c1oappe.top/Article/details/gt2hxzblepd.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sysykeji.top/Article/details/gt2pglyrdot.html

[K06] 解析 URL 查询串
来源：http://dali.tian-w.cn/Article/details/gt2gzywlqqk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.tian-w.cn/Article/details/gt2cagxzkaq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.aizwys.cn/Article/details/gt2sdhofjgw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangshuangyany.cn/Article/details/gt2orejvedl.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnqzz.top/Article/details/gt2wzlelsvt.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.feifeiyinyue.top/Article/details/gt2ayofiguq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.aizwys.cn/Article/details/gt2tppwieej.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yuanzhike.top/Article/details/gt2xlbdzpfz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.smart0.xyz/Article/details/gt2yvhceozk.html

[K07] 进制转换
来源：http://dali.hywenlv.cn/Article/details/gt2bwtstfzt.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gt2qydcxwri.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yanxiufei.cn/Article/details/gt2llmqvwdw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gt2mmbpnene.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wccfusej.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gt2yahtklff.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhoulong.xyz/Article/details/gt2rrfdhayy.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.gaohongyu789.top/Article/details/gt2fcueeays.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gt2vjvrvqna.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ybcxt.top/Article/details/gt2yifatfxv.html

Py:   pickle.dumps(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2fobkujcd.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhoulong.xyz/Article/details/gt2tzahsqpg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.wangshuangyany.cn/Article/details/gt2mqxowuji.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.nanxinkj.top/Article/details/gt2mphhhgxv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.fengsongda.top/Article/details/gt2atzrtwzl.html

Go:   encoding/gob
来源：http://dali.ehwqpu.com/Article/details/gt2byvmgzpn.html

Ruby: Marshal.dump(obj)
来源：http://dali.shuidangran.top/Article/details/gt2lrvfcooe.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.nwbrower.top/Article/details/gt2ffqlxnpj.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2bxlzqlof.html

L. 网络请求
来源：http://dali.jinqigfzy.top/Article/details/gt2kfbggybe.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2ilubaenz.html

[L01] 发送 GET 请求
来源：http://dali.jinqigufen.top/Article/details/gt2idpfrhzl.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cheryme.top/Article/details/gt2papbrkcw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.pengpengdd.cyou/Article/details/gt2hitjpshf.html

JS:   await fetch(url)
来源：http://dali.sweek.top/Article/details/gt2mqrzschj.html

TS:   await fetch(url)
来源：http://dali.cucudq.cn/Article/details/gt2eufixrxz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhixingplan.top/Article/details/gt2kewogmez.html

Go:   resp, err := http.Get(url)
来源：http://dali.chenlongwang.top/Article/details/gt2nefboroa.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinqigufen.top/Article/details/gt2oozquwxc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinqigfzy.top/Article/details/gt2wtxjulmm.html

[L02] 发送 POST JSON
来源：http://dali.yongpay.top/Article/details/gt2helwdksu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.pengpengdd.cyou/Article/details/gt2tngmmgrg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hongshengwenyu.top/Article/details/gt2cfxcdowq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tanke756.top/Article/details/gt2kwxkejhu.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hnxiangtu.top/Article/details/gt2gyanjtku.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.guannengcc.top/Article/details/gt2kombzyqc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yonumen.top/Article/details/gt2vnvyyztx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.fzhhl.top/Article/details/gt2cbywaclc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.havefunace.top/Article/details/gt2qbldzipv.html

[L03] 设置自定义请求头
来源：http://dali.andypj.xyz/Article/details/gt2whfafmxj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gzhubu.top/Article/details/gt2grfhrysp.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhiwuduotai.top/Article/details/gt2shmulwel.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxinkj.top/Article/details/gt2cdnmyfri.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ybcxt.top/Article/details/gt2vxtsmisj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.daria6918.cn/Article/details/gt2xcwpcjjq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhixingplan.top/Article/details/gt2vqfbfzng.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xinyue.icu/Article/details/gt2ksbvzcbb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xuanzx.com/Article/details/gt2ohgstwsd.html

[L04] 设置超时
来源：http://dali.hysaishi.cn/Article/details/gt2wfkprpxz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yj20258888.top/Article/details/gt2qbydfhqx.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.chenlongwang.top/Article/details/gt2hjvkujqv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vytemlmy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hysaishi.cn/Article/details/gt2quuggqio.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.chenzaomai.com/Article/details/gt2uidsqjst.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.snrcjt.cn/Article/details/gt2utipjvfq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldnrayqn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.meibo888.top/Article/details/gt2suadfegc.html

[L05] 上传文件（multipart）
来源：http://dali.ppjwa.cn/Article/details/gt2apkqinyz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhongyouzk.top/Article/details/gt2xwxxwppw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yangfankeji.com/Article/details/gt2teffqhmf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ynjirtxs.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.pycfn.com/Article/details/gt2qpksguif.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.chenlongwang.top/Article/details/gt2lmvkwfol.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yanxiufei.cn/Article/details/gt2fcdplpmo.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cqqwz.cn/Article/details/gt2jxnqvuni.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2fiqmyiqj.html

[L06] 解析响应为 JSON
来源：http://dali.hongshengwenyu.top/Article/details/gt2spftsyco.html

Py:   resp.json()
来源：http://dali.vqdsnc.cn/Article/details/gt2ickveadq.html

PHP:  json_decode($body, true);
来源：http://dali.zhiwuduotai.top/Article/details/gt2xqihoegd.html

JS:   await resp.json()
来源：http://dali.hywenlv.cn/Article/details/gt2rzunocmi.html

TS:   await resp.json()
来源：http://dali.nwbrower.top/Article/details/gt2sfhsfuxw.html


<!-- 参考信息 -->