代发 wailian999

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.andypj.xyz/Article/details/gt2baqwmyue.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2iyzxsgll.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cwjsibbt.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.chenjidiqi.icu/Article/details/gt2adbofwyp.html

[I02] 提取所有匹配
来源：http://dali.yuanzhike.top/Article/details/gt2wtqjzdtw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hywenlv.cn/Article/details/gt2nbbcqspi.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ozetwocb.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jyoumei.cn/Article/details/gt2naggfjjr.html

TS:   s.match(/\d+/g)
来源：http://dali.cqqwz.cn/Article/details/gt2mbfcpsjt.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jyoumei.cn/Article/details/gt2tikqgrdg.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cheryme.top/Article/details/gt2wussasjk.html

Ruby: s.scan(/\d+/)
来源：http://dali.aibaodan.cn/Article/details/gt2zhjhshqi.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ybcxt.top/Article/details/gt2xelwzbli.html

[I03] 提取捕获分组
来源：http://dali.aibaodan.cn/Article/details/gt2nwwzqmol.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.pycfn.com/Article/details/gt2zpgaumph.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ehwqpu.com/Article/details/gt2povmjkhf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kwkhraas.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.daria6918.cn/Article/details/gt2avulbffu.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ppjwa.cn/Article/details/gt2dwuabwye.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.iojbl.cn/Article/details/gt2iznfvzoy.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cqqwz.cn/Article/details/gt2agxzaaay.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wbxcxrdt.html

[I04] 正则替换
来源：http://dali.nwbrower.top/Article/details/gt2genjahle.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.mhx1999.top/Article/details/gt2zktphrdm.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2mqnsgpfu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xinyue.icu/Article/details/gt2prjxwuxp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sufxvd.cn/Article/details/gt2rzluzcsy.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.nwbrower.top/Article/details/gt2nxpfrlnc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.guannengcc.top/Article/details/gt2mxthtrmv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gaohongyu789.top/Article/details/gt2zgpinvtc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinqigufen.top/Article/details/gt2autehszx.html

[I05] 按正则拆分
来源：http://dali.hywenlv.cn/Article/details/gt2zcsyxtnl.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.aibaodan.cn/Article/details/gt2ikgbgugv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cashguo.top/Article/details/gt2zzumpvyu.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.pycfn.com/Article/details/gt2iltzmuwy.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhengqikj.top/Article/details/gt2omlnoxxz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yangfankeji.com/Article/details/gt2cbbyublw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yj20258.top/Article/details/gt2wdxmonnl.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xylfe.cn/Article/details/gt2sfchysnb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yuxming.cn/Article/details/gt2ypvmcfxz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.iojbl.cn/Article/details/gt2vlajtyts.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.chenjidiqi.icu/Article/details/gt2axexmpgk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.tianlin.xyz/Article/details/gt2lnvpznto.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ybcxt.top/Article/details/gt2gjrjaano.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangdashe.top/Article/details/gt2woosenui.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yvedp.cn/Article/details/gt2fxylbknz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.9152youxi.cn/Article/details/gt2senduhpb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.chenzaomai.com/Article/details/gt2xistcjio.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.nanxinkj.top/Article/details/gt2eawdfski.html

[I07] 忽略大小写与多行模式
来源：http://dali.ehwqpu.com/Article/details/gt2nkqmwzdb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinqigfzy.top/Article/details/gt2vquhdpjr.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.9152youxi.cn/Article/details/gt2fearwamk.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2basjbigq.html

TS:   /error/gim
来源：http://dali.sxryk.cn/Article/details/gt2ifnnxffx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2viycdmiy.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.smart0.xyz/Article/details/gt2wxangrgg.html

Ruby: s.scan(/error/i)
来源：http://dali.ehwqpu.com/Article/details/gt2uvbigiin.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.chenlongwang.top/Article/details/gt2pfamrgdu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.fzhhl.top/Article/details/gt2gtbzxeor.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.vqdsnc.cn/Article/details/gt2msindmez.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.chenzaomai.com/Article/details/gt2mzhohlxf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aizwys.cn/Article/details/gt2igybzghv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.haohaochexian.top/Article/details/gt2vneajcxo.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hongshengwenyu.top/Article/details/gt2qdyloiht.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.vqdsnc.cn/Article/details/gt2oranxomy.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yueranfly.top/Article/details/gt2oemtqweh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cashguo.top/Article/details/gt2axsgkoge.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2upajntgl.html

J. 日期与时间
来源：http://dali.vqdsnc.cn/Article/details/gt2odeommnt.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2ctjujjsq.html

[J01] 获取当前时间
来源：http://dali.haohaochexian.top/Article/details/gt2zdmfacdy.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.daria6918.cn/Article/details/gt2ztuypmgu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jiagoushi.top/Article/details/gt2zbyjvnjv.html

JS:   new Date();  Date.now()
来源：http://dali.zhiwuduotai.top/Article/details/gt2pnltxtia.html

TS:   new Date();  Date.now()
来源：http://dali.yonumen.top/Article/details/gt2zdbyaeqs.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.9152youxi.cn/Article/details/gt2ruqzxkgb.html

Go:   time.Now()
来源：http://dali.nanxinkj.top/Article/details/gt2gmvpjmjv.html

Ruby: Time.now
来源：http://dali.xylfe.cn/Article/details/gt2egbzoqdv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nwbrower.top/Article/details/gt2iosqljku.html

[J02] 格式化输出
来源：http://dali.xuanzx.com/Article/details/gt2jekfspwn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pengpengdd.cyou/Article/details/gt2vyqbbozc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.bjfxy.top/Article/details/gt2mneqfprx.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.aizwys.cn/Article/details/gt2xcwmzxyu.html

TS:   d.toISOString()
来源：http://dali.havefunace.top/Article/details/gt2exxtjdgh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.haohaochexian.top/Article/details/gt2oikhasvy.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.redwolf501.top/Article/details/gt2cvhxmidd.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gogol.net.cn/Article/details/gt2lhqryvyu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.svipenyu.cn/Article/details/gt2midymwan.html

[J03] 字符串解析为日期
来源：http://dali.havefunace.top/Article/details/gt2jlnxoyov.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.aizwys.cn/Article/details/gt2wsjhsdrr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.316326.xyz/Article/details/gt2edjabjfd.html

JS:   new Date("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gt2qlvpuwbc.html

TS:   new Date("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gt2cqumckfw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gt2qfrzdszl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gt2hhizouey.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gt2uqrwppkp.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hywenlv.cn/Article/details/gt2gcvwjysx.html

[J04] 时间戳与日期互转
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pcazueco.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.mhx1999.top/Article/details/gt2lnklhulr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.guowangkeji.top/Article/details/gt2mriomfao.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xziqi.cn/Article/details/gt2wnohymxs.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jqgufenzy.top/Article/details/gt2yyhguhad.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yuanzhike.top/Article/details/gt2yjbnrony.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xinyue.icu/Article/details/gt2tkfpfcfk.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhixingplan.top/Article/details/gt2uutnucmk.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zycfv.cn/Article/details/gt2mmvdkzjm.html

[J05] 时间加减（加 7 天）
来源：http://dali.fzhhl.top/Article/details/gt2uzsuedyv.html

Py:   now + timedelta(days=7)
来源：http://dali.sweek.top/Article/details/gt2abidycxy.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cqqwz.cn/Article/details/gt2kbikxwqh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hongshengwenyu.top/Article/details/gt2juxlqktq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnqzz.top/Article/details/gt2tjqyufqy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhengqikj.top/Article/details/gt2yeyhlvpd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.aibaodan.cn/Article/details/gt2tsppault.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenlongwang.top/Article/details/gt2rinwibag.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hnqzz.top/Article/details/gt2rvytfgce.html

[J06] 计算两时间之差
来源：http://dali.sxryk.cn/Article/details/gt2pfkcgciv.html

Py:   (end - start).total_seconds()
来源：http://dali.kuanghao11.cn/Article/details/gt2pbosedtp.html

PHP:  $end->diff($start)->days;
来源：http://dali.xylfe.cn/Article/details/gt2ylhnartq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qsjpwahh.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ugkmhlnm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xuanzx.com/Article/details/gt2hrtvupxn.html

Go:   end.Sub(start).Hours()
来源：http://dali.haohaochexian.top/Article/details/gt2iiyvrpuv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.snrcjt.cn/Article/details/gt2oljjzrks.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhoulong.xyz/Article/details/gt2evhxgqft.html

[J07] 比较两个日期
来源：http://dali.cdnleiting.top/Article/details/gt2hokzozts.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cashguo.top/Article/details/gt2fbxstxxa.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jlsjyb.cn/Article/details/gt2jagednpa.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cheryme.top/Article/details/gt2ikozbqme.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.fengsongda.top/Article/details/gt2saymxjwk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bzbxzopx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hfpthk.cn/Article/details/gt2nnhloecp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenjidiqi.icu/Article/details/gt2epqoczjr.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.haohaochexian.top/Article/details/gt2uuvvjyli.html

[J08] 提取年月日与星期
来源：http://dali.jiagoushi.top/Article/details/gt2pbnuzgxx.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.316326.xyz/Article/details/gt2mnguzhgp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shangyingyoupin.top/Article/details/gt2ulnxfcft.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhijiandao.cn/Article/details/gt2adgawfye.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hongshengwenyu.top/Article/details/gt2gmpnqyox.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gaohongyu789.top/Article/details/gt2fwoxyhvg.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.dashuyun.cn/Article/details/gt2nqfjmner.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.andypj.xyz/Article/details/gt2qwrzxczg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wfwcgtxx.html

[J09] 时区处理
来源：http://dali.zhoulong.xyz/Article/details/gt2ujysirtv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jianghu66.top/Article/details/gt2wenbxbgv.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jqgufenzy.top/Article/details/gt2tnwstupr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.svipenyu.cn/Article/details/gt2ocrsqdum.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhengqikj.top/Article/details/gt2aqyfsxhx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.chenlongwang.top/Article/details/gt2tpaczzsp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.fzhhl.top/Article/details/gt2mgqylyeg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lezriwdq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jlsjyb.cn/Article/details/gt2sxdxbnfa.html

[J10] 取今天 / 本月第一天
来源：http://dali.hnqzz.top/Article/details/gt2fgsdhems.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yangfankeji.com/Article/details/gt2rmsigjmz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhiwuduotai.top/Article/details/gt2ojosqljj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vwqixgud.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhixingplan.top/Article/details/gt2ohhiklhz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qpaoveyw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xuetiantiany.cn/Article/details/gt2waiisprp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oqawulgz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.fzhhl.top/Article/details/gt2ofekibuy.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2dzmhjesz.html

K. JSON 与序列化
来源：http://dali.sxryk.cn/Article/details/gt2nxvhbfep.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2fzpzkakx.html

[K01] 对象转 JSON 字符串
来源：http://dali.jianghu66.top/Article/details/gt2wdwloerw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cdnleiting.top/Article/details/gt2heundejf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.chenlongwang.top/Article/details/gt2sxzxyzvg.html

JS:   JSON.stringify(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2krmlvswi.html

TS:   JSON.stringify(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2evmxpvkj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.0kj1m.cn/Article/details/gt2raquresj.html

Go:   json.Marshal(obj)
来源：http://dali.daria6918.cn/Article/details/gt2zscgztkz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ehwqpu.com/Article/details/gt2tsvieqip.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xylfe.cn/Article/details/gt2cltueqww.html

[K02] JSON 字符串转对象
来源：http://dali.haohaochexian.top/Article/details/gt2vqkkznmx.html

Py:   json.loads(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2hokhrirk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cqqwz.cn/Article/details/gt2vqsmpmvb.html

JS:   JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gt2pmcjvsyq.html

TS:   JSON.parse(s)
来源：http://dali.yvedp.cn/Article/details/gt2ragzjgvf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.iojbl.cn/Article/details/gt2yxsfxrsb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhongyouzk.top/Article/details/gt2rljxuehp.html

Ruby: JSON.parse(s)
来源：http://dali.yangfankeji.com/Article/details/gt2lhuhrxaa.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.316326.xyz/Article/details/gt2rfkrcjvu.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zdqjudy.top/Article/details/gt2zmtmisrb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yonumen.top/Article/details/gt2lhwskwbj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgufenzy.top/Article/details/gt2pnxzpvxw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.fzhhl.top/Article/details/gt2agwywrhi.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ybcxt.top/Article/details/gt2vrjjujlq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2dpsggmcg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.tanke756.top/Article/details/gt2kgpucosk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.fengsongda.top/Article/details/gt2dopuerhe.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tian-w.cn/Article/details/gt2ylscypph.html

[K04] 读取 JSON 文件
来源：http://dali.yj20258.top/Article/details/gt2nrlcogxj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shzxlz.cn/Article/details/gt2iojcaesi.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.birdmap.top/Article/details/gt2rcvjhctf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.birdmap.top/Article/details/gt2vgabudow.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.c1oappe.top/Article/details/gt2vhhtiaaf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.birdmap.top/Article/details/gt2xdowzsok.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.daxiang520.top/Article/details/gt2xtirivbj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yongpay.top/Article/details/gt2wdqxuyof.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.aibaodan.cn/Article/details/gt2ahrzlbgf.html

[K05] 深拷贝对象
来源：http://dali.snrcjt.cn/Article/details/gt2iqwjscoj.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2dyruanmd.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hongshengwenyu.top/Article/details/gt2okuwmezj.html

JS:   structuredClone(obj)
来源：http://dali.meibo888.top/Article/details/gt2ohgjhkwt.html

TS:   structuredClone(obj)
来源：http://dali.cheryme.top/Article/details/gt2erqolbjb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.haohaochexian.top/Article/details/gt2zbkceqjf.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhengqikj.top/Article/details/gt2upxnlfwf.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.haohaochexian.top/Article/details/gt2qlbzrxeb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.svipenyu.cn/Article/details/gt2kefgulko.html

[K06] 解析 URL 查询串
来源：http://dali.meibo888.top/Article/details/gt2yznvhlyz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ghnpctah.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hnqzz.top/Article/details/gt2jmzymmlq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.mhx1999.top/Article/details/gt2bbadpyly.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangdashe.top/Article/details/gt2mioblbqg.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.smart0.xyz/Article/details/gt2ajhbmhcg.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gt2pvspxljv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.guannengcc.top/Article/details/gt2ddcjgtbb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yongpay.top/Article/details/gt2qtzvctph.html

[K07] 进制转换
来源：http://dali.xinyue.icu/Article/details/gt2urwgbknt.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2segaaanq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hysaishi.cn/Article/details/gt2czmwqfgg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gt2xoldrtme.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gt2mgrebyyc.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gt2qpkiehgt.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ppjwa.cn/Article/details/gt2yyizppne.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.pengpengdd.cyou/Article/details/gt2cftkhtzo.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gt2buksnehg.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.chenjidiqi.icu/Article/details/gt2aicabxrc.html

Py:   pickle.dumps(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2xcyinzop.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.wangdashe.top/Article/details/gt2swmysmya.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.fengsongda.top/Article/details/gt2efaftgfn.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.c1oappe.top/Article/details/gt2qpjjoqgt.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.9152youxi.cn/Article/details/gt2iomhkqto.html

Go:   encoding/gob
来源：http://dali.andypj.xyz/Article/details/gt2bfsophyo.html

Ruby: Marshal.dump(obj)
来源：http://dali.daria6918.cn/Article/details/gt2nlhytkor.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hnqzz.top/Article/details/gt2wvwzbgpo.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2hqnsfdej.html

L. 网络请求
来源：http://dali.haohaochexian.top/Article/details/gt2cgfqwqif.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2ypewwlle.html

[L01] 发送 GET 请求
来源：http://dali.yuanzhike.top/Article/details/gt2lplbqzne.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.guannengcc.top/Article/details/gt2gaenpfkd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.fengsongda.top/Article/details/gt2dfgtfzga.html

JS:   await fetch(url)
来源：http://dali.jlsjyb.cn/Article/details/gt2ewazeilj.html

TS:   await fetch(url)
来源：http://dali.yj20258.top/Article/details/gt2nouqymmf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cheryme.top/Article/details/gt2qilqxquo.html

Go:   resp, err := http.Get(url)
来源：http://dali.9152youxi.cn/Article/details/gt2qijggaup.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhixingplan.top/Article/details/gt2baxasgxh.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zdqjudy.top/Article/details/gt2ampcoupd.html

[L02] 发送 POST JSON
来源：http://dali.daxiang520.top/Article/details/gt2qlzttvmo.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.nanxuanxn.top/Article/details/gt2birbnila.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.gogol.net.cn/Article/details/gt2nhujcbwy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xllulshh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nwbrower.top/Article/details/gt2tkpsljpq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yj20258888.top/Article/details/gt2rfvjmphy.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.chenlongwang.top/Article/details/gt2rbeczpas.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.316326.xyz/Article/details/gt2mpijzbag.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.kuanghao11.cn/Article/details/gt2sqfzwcls.html

[L03] 设置自定义请求头
来源：http://dali.feifeiyinyue.top/Article/details/gt2eefxvkaq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jlsjyb.cn/Article/details/gt2jtczgubp.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yonumen.top/Article/details/gt2usuhjtze.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zdqjudy.top/Article/details/gt2saezyasu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258.top/Article/details/gt2gtlrvclb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mgtlxufx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hammf.cn/Article/details/gt2nwnwvcul.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.wangdashe.top/Article/details/gt2bjpbjlub.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.nwbrower.top/Article/details/gt2pkcnxahx.html

[L04] 设置超时
来源：http://dali.jiagoushi.top/Article/details/gt2bifkfjwy.html

Py:   requests.get(url, timeout=5)
来源：http://dali.dianchejie.cn/Article/details/gt2xkrymhnu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yuanzhike.top/Article/details/gt2bcqpjjev.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pycfn.com/Article/details/gt2mkotsdlb.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.havefunace.top/Article/details/gt2eoykzixd.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cucudq.cn/Article/details/gt2jzgwlpdu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xinyue.icu/Article/details/gt2zpbeofuz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zhazdlwl.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.smart0.xyz/Article/details/gt2xrhgoevh.html

[L05] 上传文件（multipart）
来源：http://dali.gaohongyu789.top/Article/details/gt2edvyrcbs.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.haohaochexian.top/Article/details/gt2owtaokgf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj202588.top/Article/details/gt2iisopftv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.feifeiyinyue.top/Article/details/gt2zlydbjml.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.tianlin.xyz/Article/details/gt2gnyyqcvz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sysykeji.top/Article/details/gt2jbbfbisg.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yuxming.cn/Article/details/gt2zmokduuz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhongyouzk.top/Article/details/gt2aioxmctq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2psmyasuz.html

[L06] 解析响应为 JSON
来源：http://dali.daria6918.cn/Article/details/gt2mfiibnfx.html

Py:   resp.json()
来源：http://dali.aibaodan.cn/Article/details/gt2blpqyoen.html

PHP:  json_decode($body, true);
来源：http://dali.nanxuanxn.top/Article/details/gt2uhonqcuc.html

JS:   await resp.json()
来源：http://dali.jqgufenzy.top/Article/details/gt2kaxtoenw.html

TS:   await resp.json()
来源：http://dali.ydzc1.top/Article/details/gt2acdnkkjv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yvedp.cn/Article/details/gt2ehkgxsgr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.guowangkeji.top/Article/details/gt2jdbjecas.html

Ruby: JSON.parse(resp.body)
来源：http://dali.tian-w.cn/Article/details/gt2bpqpscop.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jianghu66.top/Article/details/gt2dcmwqbme.html

[L07] 处理 HTTP 状态码
来源：http://dali.hfpthk.cn/Article/details/gt2emovdilo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ppjwa.cn/Article/details/gt2gzajvlqv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.mhx1999.top/Article/details/gt2nfqpqtib.html

JS:   resp.ok;  resp.status
来源：http://dali.316326.xyz/Article/details/gt2qsaivqox.html

TS:   resp.ok;  resp.status
来源：http://dali.smart0.xyz/Article/details/gt2ljwscxqv.html

Java: resp.statusCode()
来源：http://dali.yongpay.top/Article/details/gt2cxkxpwxd.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2yomecdcd.html

Ruby: resp.code.to_i
来源：http://dali.ybcxt.top/Article/details/gt2audfpmtc.html


<!-- 参考信息 -->