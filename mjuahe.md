代发 wailian999

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cqqwz.cn/Article/details/gt2ymrwsfco.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cdnleiting.top/Article/details/gt2eljpctat.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2plqdurnt.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jlsjyb.cn/Article/details/gt2bbhpcpmj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yonumen.top/Article/details/gt2bpuciptd.html

Go:   defer f.Close()
来源：http://dali.chenlongwang.top/Article/details/gt2pqiglpou.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cheryme.top/Article/details/gt2zchbxcjw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gt2dwpibobg.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2ehzmqbzy.html

I. 正则表达式
来源：http://dali.fengsongda.top/Article/details/gt2kpyicxyt.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hjaxbbhy.html

[I01] 判断是否匹配
来源：http://dali.fengsongda.top/Article/details/gt2cqxodmho.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2plqecgiz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ytrdshrn.html

JS:   /\d+/.test(s)
来源：http://dali.svipenyu.cn/Article/details/gt2ffxlvbfj.html

TS:   /\d+/.test(s)
来源：http://dali.guannengcc.top/Article/details/gt2dbwsnchy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yj202588.top/Article/details/gt2ppvacaka.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hysaishi.cn/Article/details/gt2tnwskglp.html

Ruby: s.match?(/\d+/)
来源：http://dali.smart0.xyz/Article/details/gt2xpwylnuc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.aizwys.cn/Article/details/gt2ovyydbqs.html

[I02] 提取所有匹配
来源：http://dali.jinqigufen.top/Article/details/gt2duceatuv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cashguo.top/Article/details/gt2cofrgeqp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yuxming.cn/Article/details/gt2iquwcsfz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj20258888.top/Article/details/gt2ankjchhs.html

TS:   s.match(/\d+/g)
来源：http://dali.shangyingyoupin.top/Article/details/gt2lfysprby.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shuidangran.top/Article/details/gt2oldaozai.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yangfankeji.com/Article/details/gt2svlfxdho.html

Ruby: s.scan(/\d+/)
来源：http://dali.316326.xyz/Article/details/gt2ruorxlot.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.tanke756.top/Article/details/gt2teussywt.html

[I03] 提取捕获分组
来源：http://dali.daria6918.cn/Article/details/gt2rrmstrrd.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sweek.top/Article/details/gt2bdolizzi.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhixingplan.top/Article/details/gt2lrahxtuf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jqgufenzy.top/Article/details/gt2ntcvvoar.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xziqi.cn/Article/details/gt2igqodqeh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.daria6918.cn/Article/details/gt2yjrlafxq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tanke756.top/Article/details/gt2udtkjway.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.fengsongda.top/Article/details/gt2zjscaasc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cdnleiting.top/Article/details/gt2eglogcbz.html

[I04] 正则替换
来源：http://dali.dianchejie.cn/Article/details/gt2lnglalce.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.kuanghao11.cn/Article/details/gt2xncboqac.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yonumen.top/Article/details/gt2mvsbflib.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gt2vsvfsxzq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.9152youxi.cn/Article/details/gt2pmhdjvkh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cucudq.cn/Article/details/gt2tmimsdqr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.316326.xyz/Article/details/gt2bxngifjz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.nanxuanxn.top/Article/details/gt2lfozwbew.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xwmjqcjk.html

[I05] 按正则拆分
来源：http://dali.jiagoushi.top/Article/details/gt2rwyqcnat.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zycfv.cn/Article/details/gt2dnumpkzq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cdnleiting.top/Article/details/gt2axlayfty.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.nwbrower.top/Article/details/gt2xassqdok.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jianghu66.top/Article/details/gt2rsnemplj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.daria6918.cn/Article/details/gt2vndsqwhh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.quarkkingdee.top/Article/details/gt2wmhwritx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.snrcjt.cn/Article/details/gt2zdmkjfbv.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hnqzz.top/Article/details/gt2ektrnuhc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cdnleiting.top/Article/details/gt2jyxnptwv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gt2xlguylmz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhongyouzk.top/Article/details/gt2wiesfbob.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dianchejie.cn/Article/details/gt2azvjksyc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258.top/Article/details/gt2vizjnvxl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.haohaochexian.top/Article/details/gt2wzghekrl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yongpay.top/Article/details/gt2akpipgbg.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yj20258.top/Article/details/gt2yuhzbpil.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.chenzaomai.com/Article/details/gt2fzaqoofv.html

[I07] 忽略大小写与多行模式
来源：http://dali.havefunace.top/Article/details/gt2yrjyydhx.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sweek.top/Article/details/gt2fspjsrwi.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mpeqdymk.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jiagoushi.top/Article/details/gt2mzeqfixp.html

TS:   /error/gim
来源：http://dali.havefunace.top/Article/details/gt2dncqihsw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.daria6918.cn/Article/details/gt2fhgjvwbz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hysaishi.cn/Article/details/gt2qgsschwr.html

Ruby: s.scan(/error/i)
来源：http://dali.yuanzhike.top/Article/details/gt2ubohkrij.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.aizwys.cn/Article/details/gt2glbgtqzk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.snrcjt.cn/Article/details/gt2wulgdnfx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.snrcjt.cn/Article/details/gt2bqcqftwa.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ydzc1.top/Article/details/gt2cbvamuok.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.quarkkingdee.top/Article/details/gt2jzjbpqac.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2usiisqoj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jqgfzy.top/Article/details/gt2ysfuhrfe.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uwjntbym.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.chenzaomai.com/Article/details/gt2qodijajn.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ydzc1.top/Article/details/gt2wisahcfz.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2ixzxdykz.html

J. 日期与时间
来源：http://dali.yanxiufei.cn/Article/details/gt2tradpprb.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2eogkvyua.html

[J01] 获取当前时间
来源：http://dali.chenjidiqi.icu/Article/details/gt2wlwrmudf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ivvv.top/Article/details/gt2dfrvphpv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xinyue.icu/Article/details/gt2hnzvptzi.html

JS:   new Date();  Date.now()
来源：http://dali.shzxlz.cn/Article/details/gt2gxygzkjl.html

TS:   new Date();  Date.now()
来源：http://dali.smart0.xyz/Article/details/gt2venkhfpn.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hongshengwenyu.top/Article/details/gt2kzbtlvao.html

Go:   time.Now()
来源：http://dali.shangyingyoupin.top/Article/details/gt2fgupcybp.html

Ruby: Time.now
来源：http://dali.sxryk.cn/Article/details/gt2hrxabvcp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.havefunace.top/Article/details/gt2mbapfuel.html

[J02] 格式化输出
来源：http://dali.tanke756.top/Article/details/gt2njxbrgga.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hongshengwenyu.top/Article/details/gt2jzcdycfa.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yangfankeji.com/Article/details/gt2bjfcdsap.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cdnleiting.top/Article/details/gt2trsbbjsx.html

TS:   d.toISOString()
来源：http://dali.xziqi.cn/Article/details/gt2rvzuedwe.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gaohongyu789.top/Article/details/gt2fdovvlay.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jqgufenzy.top/Article/details/gt2sklpgpff.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuetiantiany.cn/Article/details/gt2cjkbmqoq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.kuanghao11.cn/Article/details/gt2lmrivfxu.html

[J03] 字符串解析为日期
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sivfiwxi.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gaohongyu789.top/Article/details/gt2armjrkpa.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.pycfn.com/Article/details/gt2hrztasyf.html

JS:   new Date("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gt2yzphsmfw.html

TS:   new Date("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gt2tuuzmrbf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gt2uupikmpn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vtdsisjd.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gt2jtbckdzf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinqigufen.top/Article/details/gt2lvhirypv.html

[J04] 时间戳与日期互转
来源：http://dali.aibaodan.cn/Article/details/gt2pposuzpm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xinyue.icu/Article/details/gt2qywzrihf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yongpay.top/Article/details/gt2eeqtaxug.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.kuanghao11.cn/Article/details/gt2upfsgndf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ehwqpu.com/Article/details/gt2zemgsbdj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.iojbl.cn/Article/details/gt2pbieymba.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yuxming.cn/Article/details/gt2xlihysul.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.quarkkingdee.top/Article/details/gt2ncrmruev.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.guowangkeji.top/Article/details/gt2ysippvkm.html

[J05] 时间加减（加 7 天）
来源：http://dali.vqdsnc.cn/Article/details/gt2xqqqjrrd.html

Py:   now + timedelta(days=7)
来源：http://dali.cucudq.cn/Article/details/gt2bhhoqolw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shzxlz.cn/Article/details/gt2uesypcze.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hysaishi.cn/Article/details/gt2ittqabpz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhengqikj.top/Article/details/gt2hvuabonb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.vqdsnc.cn/Article/details/gt2hkslbpqw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cdnleiting.top/Article/details/gt2gewictrf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jqgufenzy.top/Article/details/gt2gazbjlso.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xsumccnm.html

[J06] 计算两时间之差
来源：http://dali.chenzaomai.com/Article/details/gt2rhglzmbo.html

Py:   (end - start).total_seconds()
来源：http://dali.birdmap.top/Article/details/gt2swkrcnig.html

PHP:  $end->diff($start)->days;
来源：http://dali.zycfv.cn/Article/details/gt2wztmapqe.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cucudq.cn/Article/details/gt2harbidjs.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shangyingyoupin.top/Article/details/gt2myutvumi.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hongshengwenyu.top/Article/details/gt2igkxpqng.html

Go:   end.Sub(start).Hours()
来源：http://dali.dashuyun.cn/Article/details/gt2nrhrgeqd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xuanzx.com/Article/details/gt2olnzbipx.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xvnnauyo.html

[J07] 比较两个日期
来源：http://dali.zhixingplan.top/Article/details/gt2cyigdlpz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yj202588.top/Article/details/gt2tfrfhbts.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.tanke756.top/Article/details/gt2wacvsdvu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xuetiantiany.cn/Article/details/gt2faxjrthc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ppjwa.cn/Article/details/gt2odvahycq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.tanke756.top/Article/details/gt2fmjnysdm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.dashuyun.cn/Article/details/gt2gcuzijsk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gt2ikfhsxwe.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.chenjidiqi.icu/Article/details/gt2fowitvjj.html

[J08] 提取年月日与星期
来源：http://dali.smart0.xyz/Article/details/gt2kjdjxlal.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.daria6918.cn/Article/details/gt2ornidoch.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.svipenyu.cn/Article/details/gt2apqbgwnk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.iojbl.cn/Article/details/gt2kiwpkjwu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhoulong.xyz/Article/details/gt2lylknkli.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.feifeiyinyue.top/Article/details/gt2yyyqxaqf.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rkbgprzy.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.havefunace.top/Article/details/gt2ecyndfwf.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shzxlz.cn/Article/details/gt2xwaihsbm.html

[J09] 时区处理
来源：http://dali.fzhhl.top/Article/details/gt2grrzbwxo.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.guannengcc.top/Article/details/gt2xrckynab.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xylfe.cn/Article/details/gt2itygqlsv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nwbrower.top/Article/details/gt2prdfkkds.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigufen.top/Article/details/gt2emykfjld.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.chenjidiqi.icu/Article/details/gt2geneowxw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shuidangran.top/Article/details/gt2ttbytgys.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhiwuduotai.top/Article/details/gt2jfmxutho.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xylfe.cn/Article/details/gt2vxjbksri.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj202588.top/Article/details/gt2bzxzmlpp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yangfankeji.com/Article/details/gt2qfgvyynr.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sxryk.cn/Article/details/gt2tyshzsob.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.dianchejie.cn/Article/details/gt2jlvmrggi.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.tianlin.xyz/Article/details/gt2huehswsc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xylfe.cn/Article/details/gt2muhdzjkv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hammf.cn/Article/details/gt2rrsvcluy.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yongpay.top/Article/details/gt2yvxtwrau.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shuidangran.top/Article/details/gt2xgkgxwry.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2cokuidsq.html

K. JSON 与序列化
来源：http://dali.hongshengwenyu.top/Article/details/gt2edykyylo.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2uaznrwmr.html

[K01] 对象转 JSON 字符串
来源：http://dali.yj20258.top/Article/details/gt2siaiumir.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhoulong.xyz/Article/details/gt2dlitpisb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zdqjudy.top/Article/details/gt2himwxdiw.html

JS:   JSON.stringify(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2oskkqqwc.html

TS:   JSON.stringify(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2vuqxrzmi.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2djujbsxa.html

Go:   json.Marshal(obj)
来源：http://dali.shuidangran.top/Article/details/gt2oqyrhesd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.tianlin.xyz/Article/details/gt2tszketdr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2njcrxuup.html

[K02] JSON 字符串转对象
来源：http://dali.shangyingyoupin.top/Article/details/gt2whrlffdc.html

Py:   json.loads(s)
来源：http://dali.cashguo.top/Article/details/gt2nwwpmiuf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xinyue.icu/Article/details/gt2vilemifs.html

JS:   JSON.parse(s)
来源：http://dali.smart0.xyz/Article/details/gt2mhahgeab.html

TS:   JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gt2kjulcabt.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sxryk.cn/Article/details/gt2mjjzmcur.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jianghu66.top/Article/details/gt2wlmopkkf.html

Ruby: JSON.parse(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dyxrrnbu.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xinyue.icu/Article/details/gt2npavklyv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.dianchejie.cn/Article/details/gt2avselujo.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.vqdsnc.cn/Article/details/gt2eleztewk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.haohaochexian.top/Article/details/gt2qzchrtti.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2ocnyechx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ttzxjkmh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zycfv.cn/Article/details/gt2lbrxtwbv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.guannengcc.top/Article/details/gt2bwpmnzog.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2kwqmkqag.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cqqwz.cn/Article/details/gt2bkdfmnfw.html

[K04] 读取 JSON 文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wrurltem.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sysykeji.top/Article/details/gt2qumueuyl.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.redwolf501.top/Article/details/gt2vszzcobp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guannengcc.top/Article/details/gt2swrgvpmr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.meibo888.top/Article/details/gt2uvayuuqm.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.vqdsnc.cn/Article/details/gt2ynhypajq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.meibo888.top/Article/details/gt2rfdgjhwu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xziqi.cn/Article/details/gt2lytfjdrc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ybcxt.top/Article/details/gt2qvczpiea.html

[K05] 深拷贝对象
来源：http://dali.cdnleiting.top/Article/details/gt2yvlkfznk.html

Py:   copy.deepcopy(obj)
来源：http://dali.daria6918.cn/Article/details/gt2qtumlfnk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.dashuyun.cn/Article/details/gt2nfodmsig.html

JS:   structuredClone(obj)
来源：http://dali.yj20258888.top/Article/details/gt2jxuxukic.html

TS:   structuredClone(obj)
来源：http://dali.ivvv.top/Article/details/gt2cudamfcv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.pycfn.com/Article/details/gt2flmsujou.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yueranfly.top/Article/details/gt2yuuiabpc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gotoacloud.top/Article/details/gt2rmtgjhfu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hysaishi.cn/Article/details/gt2ozwozkye.html

[K06] 解析 URL 查询串
来源：http://dali.chenlongwang.top/Article/details/gt2axgpsjyw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yvedp.cn/Article/details/gt2fmhfxntf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhongyouzk.top/Article/details/gt2dkgofgip.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnqzz.top/Article/details/gt2vbivgiaq.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgfzy.top/Article/details/gt2drqslyie.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.iojbl.cn/Article/details/gt2djilidgi.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yuanzhike.top/Article/details/gt2jkxrgxyj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jyoumei.cn/Article/details/gt2skykggqy.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.chenzaomai.com/Article/details/gt2xthdjwzl.html

[K07] 进制转换
来源：http://dali.iojbl.cn/Article/details/gt2bojadaju.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.316326.xyz/Article/details/gt2iluknwpv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.kuanghao11.cn/Article/details/gt2eheeufpa.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gt2zlchagmy.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gt2fxotcbsq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gt2xdmrqxoc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jgvhkvwi.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.fengsongda.top/Article/details/gt2vyyvmqoe.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gt2tqbcibaa.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhiwuduotai.top/Article/details/gt2eqnvhqmj.html

Py:   pickle.dumps(obj)
来源：http://dali.sxryk.cn/Article/details/gt2eshhpltd.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.tian-w.cn/Article/details/gt2icgafpal.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ujhcbtgg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yvedp.cn/Article/details/gt2juuidhsz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gzhubu.top/Article/details/gt2cczigfhm.html

Go:   encoding/gob
来源：http://dali.nanxuanxn.top/Article/details/gt2ehanqcfh.html

Ruby: Marshal.dump(obj)
来源：http://dali.nwbrower.top/Article/details/gt2omxlbvei.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hnqzz.top/Article/details/gt2tmcixdgc.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2ewvhhhus.html

L. 网络请求
来源：http://dali.pengpengdd.cyou/Article/details/gt2xvyuygqt.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ufnxncou.html

[L01] 发送 GET 请求
来源：http://dali.cqqwz.cn/Article/details/gt2ctyscioy.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.tanke756.top/Article/details/gt2slooccii.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.haohaochexian.top/Article/details/gt2rkkahoza.html

JS:   await fetch(url)
来源：http://dali.havefunace.top/Article/details/gt2mdteopxs.html

TS:   await fetch(url)
来源：http://dali.haohaochexian.top/Article/details/gt2bplknfeo.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.birdmap.top/Article/details/gt2ochksrap.html

Go:   resp, err := http.Get(url)
来源：http://dali.yonumen.top/Article/details/gt2rrpmgsnz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gzhubu.top/Article/details/gt2hadpbgjj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cqqwz.cn/Article/details/gt2ttjvrmpm.html

[L02] 发送 POST JSON
来源：http://dali.wangdashe.top/Article/details/gt2hoeyhjla.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.kuanghao11.cn/Article/details/gt2odfogxfo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xylfe.cn/Article/details/gt2hrvyagmb.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hywenlv.cn/Article/details/gt2fitgqebe.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuxming.cn/Article/details/gt2jowejake.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.mhx1999.top/Article/details/gt2thucaqpp.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hnxiangtu.top/Article/details/gt2ouxveazt.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xinyue.icu/Article/details/gt2ugukdcui.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.tanke756.top/Article/details/gt2uwuyyadm.html

[L03] 设置自定义请求头
来源：http://dali.c1oappe.top/Article/details/gt2pcznahye.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wpkrwlvm.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cucudq.cn/Article/details/gt2eiikuaks.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuanzx.com/Article/details/gt2ehtbrprt.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258888.top/Article/details/gt2eaucknel.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.redwolf501.top/Article/details/gt2ggtckzta.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.9152youxi.cn/Article/details/gt2xuqunhze.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.vqdsnc.cn/Article/details/gt2budwdgjz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rxqqjgnf.html

[L04] 设置超时
来源：http://dali.feifeiyinyue.top/Article/details/gt2ktxikdlx.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jiagoushi.top/Article/details/gt2bpcnviuq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.quarkkingdee.top/Article/details/gt2oisjzqoh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gzhubu.top/Article/details/gt2jfddmykd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.smart0.xyz/Article/details/gt2fzajqisf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.aibaodan.cn/Article/details/gt2jrjcryjy.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jinqigfzy.top/Article/details/gt2letlqeug.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sysykeji.top/Article/details/gt2bpdyovfx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.birdmap.top/Article/details/gt2jqfzeuyk.html

[L05] 上传文件（multipart）
来源：http://dali.sweek.top/Article/details/gt2vrxvlrif.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ppjwa.cn/Article/details/gt2rhxscdbd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.daria6918.cn/Article/details/gt2jimzrfgz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangshuangyany.cn/Article/details/gt2tmqyyxaq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hysaishi.cn/Article/details/gt2jtfbuplo.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jianghu66.top/Article/details/gt2vqphgzdh.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tyecyldn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cqqwz.cn/Article/details/gt2xwjbusdd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.birdmap.top/Article/details/gt2jaydrcki.html

[L06] 解析响应为 JSON
来源：http://dali.guannengcc.top/Article/details/gt2uhpcibzv.html


<!-- 参考信息 -->