代发 wailian999

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hongshengwenyu.top/Article/details/gt2sgwlkrfp.html

Go:   defer f.Close()
来源：http://dali.c1oappe.top/Article/details/gt2pfloqfst.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.pycfn.com/Article/details/gt2mbpwhool.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2jndvccuq.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2tbalbnlf.html

I. 正则表达式
来源：http://dali.gzhubu.top/Article/details/gt2aixfqqal.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2awknappi.html

[I01] 判断是否匹配
来源：http://dali.hfpthk.cn/Article/details/gt2hwwntaph.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ybcxt.top/Article/details/gt2fkftludv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.aizwys.cn/Article/details/gt2tenuahby.html

JS:   /\d+/.test(s)
来源：http://dali.fzhhl.top/Article/details/gt2jdtyojbm.html

TS:   /\d+/.test(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2fvvaaius.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.guannengcc.top/Article/details/gt2yxtqbvwq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2oislpwqs.html

Ruby: s.match?(/\d+/)
来源：http://dali.fengsongda.top/Article/details/gt2sbxzzfhr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ivvv.top/Article/details/gt2uzoyquce.html

[I02] 提取所有匹配
来源：http://dali.kuanghao11.cn/Article/details/gt2uiygxeyu.html

Py:   re.findall(r"\d+", s)
来源：http://dali.chenzaomai.com/Article/details/gt2ldtfnhjf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.daxiang520.top/Article/details/gt2qdkirngv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wwyqhcei.html

TS:   s.match(/\d+/g)
来源：http://dali.zhoulong.xyz/Article/details/gt2gmbtqoby.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sufxvd.cn/Article/details/gt2xghoczye.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.nanxinkj.top/Article/details/gt2mpebxmug.html

Ruby: s.scan(/\d+/)
来源：http://dali.svipenyu.cn/Article/details/gt2glnsdixp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.andypj.xyz/Article/details/gt2xxdkfbhb.html

[I03] 提取捕获分组
来源：http://dali.feifeiyinyue.top/Article/details/gt2tozxwrmk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gzhubu.top/Article/details/gt2hqruufmf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zycfv.cn/Article/details/gt2hpmcopdc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.316326.xyz/Article/details/gt2izbrsguz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.chenzaomai.com/Article/details/gt2ermrmwcf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sweek.top/Article/details/gt2soxrondr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinqigufen.top/Article/details/gt2ndxjkoyt.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhiwuduotai.top/Article/details/gt2jsvwkzfp.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yueranfly.top/Article/details/gt2gcguoped.html

[I04] 正则替换
来源：http://dali.dashuyun.cn/Article/details/gt2qcohyufm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinqigufen.top/Article/details/gt2qdqvwrvj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.quarkkingdee.top/Article/details/gt2xbhgctfl.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgufenzy.top/Article/details/gt2fpgdnczn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.bjfxy.top/Article/details/gt2rpfuvari.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hfpthk.cn/Article/details/gt2puvpmesz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.chenzaomai.com/Article/details/gt2oitvxtlm.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ppjwa.cn/Article/details/gt2justudpb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yongpay.top/Article/details/gt2ottpmquq.html

[I05] 按正则拆分
来源：http://dali.yj202588.top/Article/details/gt2sdaxqspr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jlsjyb.cn/Article/details/gt2xuioiwcp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cdnleiting.top/Article/details/gt2fhgbzgrk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gt2ifyrplhe.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gt2jwjamygd.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cucudq.cn/Article/details/gt2xyaxegdc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.nwbrower.top/Article/details/gt2rnctuclq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.meibo888.top/Article/details/gt2uflstcdi.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cheryme.top/Article/details/gt2iojskuuz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xqdjvkpt.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sufxvd.cn/Article/details/gt2vrifvfgu.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenzaomai.com/Article/details/gt2qsegjodb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pengpengdd.cyou/Article/details/gt2yqijhdzw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xziqi.cn/Article/details/gt2llorvsxx.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhiwuduotai.top/Article/details/gt2gynzivdz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xylfe.cn/Article/details/gt2cduhwiut.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.quarkkingdee.top/Article/details/gt2pgpravec.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yvedp.cn/Article/details/gt2mbawvbym.html

[I07] 忽略大小写与多行模式
来源：http://dali.yuanzhike.top/Article/details/gt2tkwsvvjk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fcbblplg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.guannengcc.top/Article/details/gt2oeniswwo.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj20258.top/Article/details/gt2vmvbrkup.html

TS:   /error/gim
来源：http://dali.gaohongyu789.top/Article/details/gt2obiqsxiw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sctwvwra.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zycfv.cn/Article/details/gt2jsadbodm.html

Ruby: s.scan(/error/i)
来源：http://dali.quarkkingdee.top/Article/details/gt2ojvyjszy.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shangyingyoupin.top/Article/details/gt2sbbjctew.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hysaishi.cn/Article/details/gt2psfnivsn.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jiagoushi.top/Article/details/gt2qgahdppa.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yangfankeji.com/Article/details/gt2qkiddvol.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgufenzy.top/Article/details/gt2ydyidupi.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cashguo.top/Article/details/gt2wlxwbypz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tianlin.xyz/Article/details/gt2vrkifasw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.birdmap.top/Article/details/gt2ptditrks.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.andypj.xyz/Article/details/gt2smrpgzxw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.pycfn.com/Article/details/gt2xjfichiz.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2jwdfqzhd.html

J. 日期与时间
来源：http://dali.tianlin.xyz/Article/details/gt2cglidkpf.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2wfokdeni.html

[J01] 获取当前时间
来源：http://dali.wangdashe.top/Article/details/gt2ljnhrdpt.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gogol.net.cn/Article/details/gt2bgipybil.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2twmtdmkk.html

JS:   new Date();  Date.now()
来源：http://dali.vqdsnc.cn/Article/details/gt2lrnueimj.html

TS:   new Date();  Date.now()
来源：http://dali.tian-w.cn/Article/details/gt2vpfllbvi.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yj202588.top/Article/details/gt2uqndhlib.html

Go:   time.Now()
来源：http://dali.yvedp.cn/Article/details/gt2cesjmjpi.html

Ruby: Time.now
来源：http://dali.shuidangran.top/Article/details/gt2itytsazm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.0kj1m.cn/Article/details/gt2agcbyckg.html

[J02] 格式化输出
来源：http://dali.guannengcc.top/Article/details/gt2sljnpkkb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ybcxt.top/Article/details/gt2zxhdkjqe.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.fengsongda.top/Article/details/gt2lpgkpcec.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ydzc1.top/Article/details/gt2ojqsuftn.html

TS:   d.toISOString()
来源：http://dali.0kj1m.cn/Article/details/gt2ndavcipl.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenzaomai.com/Article/details/gt2eqezksvk.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yj20258888.top/Article/details/gt2bczmrtxl.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aizwys.cn/Article/details/gt2fliaobji.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.9152youxi.cn/Article/details/gt2ttfpfkef.html

[J03] 字符串解析为日期
来源：http://dali.xylfe.cn/Article/details/gt2hmnpstci.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cashguo.top/Article/details/gt2gixagwkz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jlsjyb.cn/Article/details/gt2hvxbfsmf.html

JS:   new Date("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gt2ntdstwfh.html

TS:   new Date("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gt2cdtogncs.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gt2wbdumyir.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gt2cxtqsjnq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gt2upnafstm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinqigufen.top/Article/details/gt2aogkoaii.html

[J04] 时间戳与日期互转
来源：http://dali.cheryme.top/Article/details/gt2dponklhm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.redwolf501.top/Article/details/gt2mlqgrnfj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hnqzz.top/Article/details/gt2ecivmgtk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hfpthk.cn/Article/details/gt2qmkstjyr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jyoumei.cn/Article/details/gt2lfkuhrye.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.mhx1999.top/Article/details/gt2yghcybws.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ybcxt.top/Article/details/gt2tdjdtqxr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ydzc1.top/Article/details/gt2tpqcgkme.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yongpay.top/Article/details/gt2sfxmjlke.html

[J05] 时间加减（加 7 天）
来源：http://dali.daria6918.cn/Article/details/gt2egqfycvx.html

Py:   now + timedelta(days=7)
来源：http://dali.fengsongda.top/Article/details/gt2nrvlfkpy.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.316326.xyz/Article/details/gt2xsdgbcsy.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dianchejie.cn/Article/details/gt2fxcvlhuz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ydzc1.top/Article/details/gt2vhydpgar.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jqgufenzy.top/Article/details/gt2qirstycn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yj20258.top/Article/details/gt2xkcdjigq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zycfv.cn/Article/details/gt2uebsyzfs.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.gogol.net.cn/Article/details/gt2kqacedjl.html

[J06] 计算两时间之差
来源：http://dali.zhengqikj.top/Article/details/gt2whhjljbx.html

Py:   (end - start).total_seconds()
来源：http://dali.shuidangran.top/Article/details/gt2byomnsyt.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhongyouzk.top/Article/details/gt2ogoeitps.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhijiandao.cn/Article/details/gt2tqlyzxrm.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.chenzaomai.com/Article/details/gt2geepjvvs.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.aibaodan.cn/Article/details/gt2zgncyyzr.html

Go:   end.Sub(start).Hours()
来源：http://dali.birdmap.top/Article/details/gt2wminzkcl.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gogol.net.cn/Article/details/gt2wmwpjcmh.html

C#:   (end - start).TotalSeconds
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mefzimyf.html

[J07] 比较两个日期
来源：http://dali.hnxiangtu.top/Article/details/gt2odqcqtdb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gt2iyvysiap.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhoulong.xyz/Article/details/gt2gqvedwzs.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhoulong.xyz/Article/details/gt2mojlnibg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.pycfn.com/Article/details/gt2mvsdvvsx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yueranfly.top/Article/details/gt2bekbxhwq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hdtnumhy.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hysaishi.cn/Article/details/gt2pxftvcqk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shzxlz.cn/Article/details/gt2kjlknfnw.html

[J08] 提取年月日与星期
来源：http://dali.fengsongda.top/Article/details/gt2tayqqixh.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yj20258.top/Article/details/gt2syocjbgf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.kuanghao11.cn/Article/details/gt2npfkzpud.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.daxiang520.top/Article/details/gt2syxsvqzx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yuxming.cn/Article/details/gt2cfouqobm.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.mhx1999.top/Article/details/gt2vttgtrlv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhongyouzk.top/Article/details/gt2ijqlqqnm.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.nanxinkj.top/Article/details/gt2atsqjkqy.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.guowangkeji.top/Article/details/gt2itdulqxg.html

[J09] 时区处理
来源：http://dali.nanxinkj.top/Article/details/gt2ccjexzlb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yanxiufei.cn/Article/details/gt2jywpiclr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jyoumei.cn/Article/details/gt2tvgqheps.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dashuyun.cn/Article/details/gt2baunefvi.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangdashe.top/Article/details/gt2tvutjvvg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.svipenyu.cn/Article/details/gt2luffkpdw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ydzc1.top/Article/details/gt2pzoeoppp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xqdthopz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jyoumei.cn/Article/details/gt2xidyrlwa.html

[J10] 取今天 / 本月第一天
来源：http://dali.nwbrower.top/Article/details/gt2fqdlxukf.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xinyue.icu/Article/details/gt2daspeepf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tian-w.cn/Article/details/gt2rnuygkoo.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2drptfmql.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shzxlz.cn/Article/details/gt2jzorgzry.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cashguo.top/Article/details/gt2blovpcwr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hbwdfjzj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.fzhhl.top/Article/details/gt2lbdfkmxv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yangfankeji.com/Article/details/gt2exqkhqpj.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2rmwzakra.html

K. JSON 与序列化
来源：http://dali.yueranfly.top/Article/details/gt2rhambrpg.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2ytcnzdwf.html

[K01] 对象转 JSON 字符串
来源：http://dali.tanke756.top/Article/details/gt2gjnzqazw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zycfv.cn/Article/details/gt2obpdvcng.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2manmlyrb.html

JS:   JSON.stringify(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2snceccqi.html

TS:   JSON.stringify(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2xfktwwng.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.chenlongwang.top/Article/details/gt2vqroyedi.html

Go:   json.Marshal(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2zmbegzgg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gzhubu.top/Article/details/gt2tufnbzgl.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2szpasyuv.html

[K02] JSON 字符串转对象
来源：http://dali.gotoacloud.top/Article/details/gt2wricnikh.html

Py:   json.loads(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2optbzyhv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cucudq.cn/Article/details/gt2bbnvvekh.html

JS:   JSON.parse(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xlsunbql.html

TS:   JSON.parse(s)
来源：http://dali.tian-w.cn/Article/details/gt2nuswefnt.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gzhubu.top/Article/details/gt2ajtgvqsz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xinyue.icu/Article/details/gt2zcnwdyjh.html

Ruby: JSON.parse(s)
来源：http://dali.hywenlv.cn/Article/details/gt2fuvayonj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xuanzx.com/Article/details/gt2hzayhatm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhixingplan.top/Article/details/gt2lycrgnyx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.redwolf501.top/Article/details/gt2jlfbzkkj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhixingplan.top/Article/details/gt2dducagwp.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cqqwz.cn/Article/details/gt2zncpbmku.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2dpmxbevy.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.redwolf501.top/Article/details/gt2eqdskavc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gzhubu.top/Article/details/gt2euxrbiax.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2ehztczbo.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.pycfn.com/Article/details/gt2srdnuqnk.html

[K04] 读取 JSON 文件
来源：http://dali.jlsjyb.cn/Article/details/gt2zfjbqvnm.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yj20258.top/Article/details/gt2gednxqpj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.fzhhl.top/Article/details/gt2sczxuunj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yangfankeji.com/Article/details/gt2zywrfndb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258.top/Article/details/gt2bxgbxpnd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.9152youxi.cn/Article/details/gt2xulvrzdn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cheryme.top/Article/details/gt2hsodkyaa.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sweek.top/Article/details/gt2rseooqyo.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yonumen.top/Article/details/gt2olxwilgj.html

[K05] 深拷贝对象
来源：http://dali.chenzaomai.com/Article/details/gt2okocjbrq.html

Py:   copy.deepcopy(obj)
来源：http://dali.yonumen.top/Article/details/gt2qgacjblz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sufxvd.cn/Article/details/gt2ncklpoov.html

JS:   structuredClone(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2enzbtphr.html

TS:   structuredClone(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2hjkjkthg.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yuxming.cn/Article/details/gt2gynfipvm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sufxvd.cn/Article/details/gt2fsllxidu.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dpfriugf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ehwqpu.com/Article/details/gt2ovbzjrbj.html

[K06] 解析 URL 查询串
来源：http://dali.chenlongwang.top/Article/details/gt2mpfvqrwu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.c1oappe.top/Article/details/gt2aibaoxcb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cucudq.cn/Article/details/gt2njyspxpm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ppjwa.cn/Article/details/gt2xkqxqltr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xinyue.icu/Article/details/gt2pgifjkew.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fzvtroqc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hfpthk.cn/Article/details/gt2rfpdepdf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yueranfly.top/Article/details/gt2engzajpw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hnxiangtu.top/Article/details/gt2lctkzljo.html

[K07] 进制转换
来源：http://dali.jianghu66.top/Article/details/gt2xejqsdwh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gt2neqtfxrm.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yuxming.cn/Article/details/gt2emsnrlwx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2llenjfiv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gt2ztbbeopm.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gt2xjcnixfj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.smart0.xyz/Article/details/gt2mxbwxmwr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ybcxt.top/Article/details/gt2nazjybtt.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gt2jwhgmmij.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.chenjidiqi.icu/Article/details/gt2gercnjap.html

Py:   pickle.dumps(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ithcmolg.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jianghu66.top/Article/details/gt2sbcznygs.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sufxvd.cn/Article/details/gt2pozzluag.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xacivaxb.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhixingplan.top/Article/details/gt2isjvhmpd.html

Go:   encoding/gob
来源：http://dali.fzhhl.top/Article/details/gt2zpnxtttw.html

Ruby: Marshal.dump(obj)
来源：http://dali.sweek.top/Article/details/gt2gwycgqai.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ctkakzoq.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2fniwdhxj.html

L. 网络请求
来源：http://dali.0kj1m.cn/Article/details/gt2zjijwarq.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2artjcqex.html

[L01] 发送 GET 请求
来源：http://dali.snrcjt.cn/Article/details/gt2vgxiqust.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.snrcjt.cn/Article/details/gt2pgfuvaed.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nanxinkj.top/Article/details/gt2hyuviujc.html

JS:   await fetch(url)
来源：http://dali.iojbl.cn/Article/details/gt2uiyhyrau.html

TS:   await fetch(url)
来源：http://dali.hfpthk.cn/Article/details/gt2moztxlrn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gogol.net.cn/Article/details/gt2fxxqlgfj.html

Go:   resp, err := http.Get(url)
来源：http://dali.yuanzhike.top/Article/details/gt2jdokikok.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jlsjyb.cn/Article/details/gt2gybmmslg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.smart0.xyz/Article/details/gt2azobqrwy.html

[L02] 发送 POST JSON
来源：http://dali.ybcxt.top/Article/details/gt2roaxdtyd.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.haohaochexian.top/Article/details/gt2kruykdkq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhiwuduotai.top/Article/details/gt2kgjxiwlf.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hywenlv.cn/Article/details/gt2fefyfjsk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenzaomai.com/Article/details/gt2lxklsmxb.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cucudq.cn/Article/details/gt2vudpxbwq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhoulong.xyz/Article/details/gt2jgpzzvcp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhiwuduotai.top/Article/details/gt2yjeoclhe.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.smart0.xyz/Article/details/gt2ssbpwvdc.html

[L03] 设置自定义请求头
来源：http://dali.hnxiangtu.top/Article/details/gt2ubbkcrmw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cashguo.top/Article/details/gt2mhxvirdq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.bjfxy.top/Article/details/gt2pmujmbxo.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sufxvd.cn/Article/details/gt2ebkqyvvn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.redwolf501.top/Article/details/gt2zeflemxd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cxnypite.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jinqigufen.top/Article/details/gt2nptgxajy.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shuidangran.top/Article/details/gt2sxxxdgpq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.daria6918.cn/Article/details/gt2bgmbzwdn.html

[L04] 设置超时
来源：http://dali.xuanzx.com/Article/details/gt2xdsbgqvn.html

Py:   requests.get(url, timeout=5)
来源：http://dali.meibo888.top/Article/details/gt2xwbukipm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ydzc1.top/Article/details/gt2rrnrelfm.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2omrqfopp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.0kj1m.cn/Article/details/gt2owydqxqs.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jyoumei.cn/Article/details/gt2bhaoaykq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gotoacloud.top/Article/details/gt2jwyjcekc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cqqwz.cn/Article/details/gt2jugunrcj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.pengpengdd.cyou/Article/details/gt2pvbzlqnz.html

[L05] 上传文件（multipart）
来源：http://dali.xziqi.cn/Article/details/gt2qdsyysyd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.chenlongwang.top/Article/details/gt2sfkocwpc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.tianlin.xyz/Article/details/gt2kxjvkbnb.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.havefunace.top/Article/details/gt2ucfwdoic.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cucudq.cn/Article/details/gt2omeylgbz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.wangdashe.top/Article/details/gt2kjirsjhk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ybcxt.top/Article/details/gt2nvhrwcmq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.guannengcc.top/Article/details/gt2vzfypwum.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hnqzz.top/Article/details/gt2xjrgxoqk.html

[L06] 解析响应为 JSON
来源：http://dali.daxiang520.top/Article/details/gt2ghvqlyob.html

Py:   resp.json()
来源：http://dali.fengsongda.top/Article/details/gt2xrsqrdgg.html

PHP:  json_decode($body, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yoorahjx.html

JS:   await resp.json()
来源：http://dali.mhx1999.top/Article/details/gt2kcupehue.html

TS:   await resp.json()
来源：http://dali.chenlongwang.top/Article/details/gt2braqxylt.html


<!-- 参考信息 -->