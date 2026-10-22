代发 wailian999

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yvedp.cn/Article/details/gt2ahfxtvig.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.snrcjt.cn/Article/details/gt2bwpnvzou.html

JS:   /\d+/.test(s)
来源：http://dali.xziqi.cn/Article/details/gt2vegbzxao.html

TS:   /\d+/.test(s)
来源：http://dali.birdmap.top/Article/details/gt2jiwumgog.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yj202588.top/Article/details/gt2akgmylws.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ivvv.top/Article/details/gt2iaivuuoy.html

Ruby: s.match?(/\d+/)
来源：http://dali.yuxming.cn/Article/details/gt2tlxdanub.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.feifeiyinyue.top/Article/details/gt2eojtbuar.html

[I02] 提取所有匹配
来源：http://dali.zhongyouzk.top/Article/details/gt2rlkgxkni.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinqigfzy.top/Article/details/gt2vatkaorj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yj202588.top/Article/details/gt2jwyguavn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xinyue.icu/Article/details/gt2nbljtxab.html

TS:   s.match(/\d+/g)
来源：http://dali.haohaochexian.top/Article/details/gt2lbdxvsme.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.svipenyu.cn/Article/details/gt2detrweef.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xuanzx.com/Article/details/gt2vgekkglg.html

Ruby: s.scan(/\d+/)
来源：http://dali.ydzc1.top/Article/details/gt2axszcrbp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2talcsuwa.html

[I03] 提取捕获分组
来源：http://dali.tian-w.cn/Article/details/gt2viitdncr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinqigufen.top/Article/details/gt2tfpxlipt.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.svipenyu.cn/Article/details/gt2ulqsrmdr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cdnleiting.top/Article/details/gt2wsrkwytb.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.nanxuanxn.top/Article/details/gt2pktwytkk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xuanzx.com/Article/details/gt2hhwplzed.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shangyingyoupin.top/Article/details/gt2wwljzlwp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ybcxt.top/Article/details/gt2zkgkihsh.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ezzlwndn.html

[I04] 正则替换
来源：http://dali.zhiwuduotai.top/Article/details/gt2psmrstba.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cqqwz.cn/Article/details/gt2fmahdtdn.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ivvv.top/Article/details/gt2ikovzhta.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.wangshuangyany.cn/Article/details/gt2dxtzhryu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.vqdsnc.cn/Article/details/gt2gwpcvkyd.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.svipenyu.cn/Article/details/gt2mfaxfvjs.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jlsjyb.cn/Article/details/gt2fgkagacv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gt2bqchuosx.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shzxlz.cn/Article/details/gt2nkwuvsxr.html

[I05] 按正则拆分
来源：http://dali.jinqigufen.top/Article/details/gt2txyddbvs.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gotoacloud.top/Article/details/gt2whqfngky.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gt2pzzvdfce.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.0kj1m.cn/Article/details/gt2vkyhdqsx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gt2zlzxstpm.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ybcxt.top/Article/details/gt2cpixicaa.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hysaishi.cn/Article/details/gt2qvfrmhos.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gaohongyu789.top/Article/details/gt2dzrbcklc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.wangdashe.top/Article/details/gt2nrycnkwt.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinqigfzy.top/Article/details/gt2qsfcxjuk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.smart0.xyz/Article/details/gt2rdtcemew.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fpwngmfh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258888.top/Article/details/gt2xnjuivwh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2yahxltft.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cashguo.top/Article/details/gt2aazgkgre.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hammf.cn/Article/details/gt2wbyjsthi.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yonumen.top/Article/details/gt2jmgepqlx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gt2fjokhelr.html

[I07] 忽略大小写与多行模式
来源：http://dali.jyoumei.cn/Article/details/gt2tapsqyzz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.nwbrower.top/Article/details/gt2pdnndgor.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinqigfzy.top/Article/details/gt2xcfcjuzo.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yuanzhike.top/Article/details/gt2ldtxjwqm.html

TS:   /error/gim
来源：http://dali.cqqwz.cn/Article/details/gt2tskyoley.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.tian-w.cn/Article/details/gt2jbpmsxqe.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fxnnvfek.html

Ruby: s.scan(/error/i)
来源：http://dali.chenjidiqi.icu/Article/details/gt2cympuazq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.0kj1m.cn/Article/details/gt2gnzsksbt.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jiagoushi.top/Article/details/gt2ampwygsu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shzxlz.cn/Article/details/gt2vmmexnhi.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cashguo.top/Article/details/gt2jvehdimn.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fengsongda.top/Article/details/gt2vgsivido.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yanxiufei.cn/Article/details/gt2oiuxzcph.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.nanxinkj.top/Article/details/gt2cyphplwa.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.feifeiyinyue.top/Article/details/gt2qsfeqbgp.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ydzc1.top/Article/details/gt2kzwevhxe.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinqigfzy.top/Article/details/gt2mqgzauqx.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2cmxjgajt.html

J. 日期与时间
来源：http://dali.zycfv.cn/Article/details/gt2hjrymhqv.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2txegrqeo.html

[J01] 获取当前时间
来源：http://dali.ybcxt.top/Article/details/gt2nfpuwrsv.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhoulong.xyz/Article/details/gt2yoykohpp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cashguo.top/Article/details/gt2eevkpssc.html

JS:   new Date();  Date.now()
来源：http://dali.fzhhl.top/Article/details/gt2baxyyuvx.html

TS:   new Date();  Date.now()
来源：http://dali.guowangkeji.top/Article/details/gt2agvjljjd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.feifeiyinyue.top/Article/details/gt2miexnrfh.html

Go:   time.Now()
来源：http://dali.birdmap.top/Article/details/gt2mcfmslbo.html

Ruby: Time.now
来源：http://dali.jlsjyb.cn/Article/details/gt2bddulreq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zthwmsof.html

[J02] 格式化输出
来源：http://dali.bjfxy.top/Article/details/gt2pypoigsq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yanxiufei.cn/Article/details/gt2gvgwzneh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yj20258888.top/Article/details/gt2jwzvhzae.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.fzhhl.top/Article/details/gt2smdojqsq.html

TS:   d.toISOString()
来源：http://dali.feifeiyinyue.top/Article/details/gt2corgojfm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wyxifiwc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yuxming.cn/Article/details/gt2unlvyyhy.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258888.top/Article/details/gt2gdshwdxa.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.316326.xyz/Article/details/gt2iczgedgr.html

[J03] 字符串解析为日期
来源：http://dali.hfpthk.cn/Article/details/gt2gpmxqzma.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.nanxinkj.top/Article/details/gt2zyzyjohk.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhijiandao.cn/Article/details/gt2xwrqsqsk.html

JS:   new Date("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gt2fqzrhqzj.html

TS:   new Date("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gt2zmdmkkpx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gt2rxgngcnk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gt2qvaydkvs.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gt2ktywqyka.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.aibaodan.cn/Article/details/gt2dqhmyiwm.html

[J04] 时间戳与日期互转
来源：http://dali.sxryk.cn/Article/details/gt2izhnozea.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cucudq.cn/Article/details/gt2dwyqdmsf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hkufderq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cucudq.cn/Article/details/gt2seguoljf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.birdmap.top/Article/details/gt2iweiwajc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cdnleiting.top/Article/details/gt2afrcqltc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.bjfxy.top/Article/details/gt2szhebaof.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hfpthk.cn/Article/details/gt2wnakhggi.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jyoumei.cn/Article/details/gt2atgfwrsx.html

[J05] 时间加减（加 7 天）
来源：http://dali.kuanghao11.cn/Article/details/gt2hwxavjht.html

Py:   now + timedelta(days=7)
来源：http://dali.yangfankeji.com/Article/details/gt2ceylpqvr.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.snrcjt.cn/Article/details/gt2ktdfbyio.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yueranfly.top/Article/details/gt2sbgcrxsh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.mhx1999.top/Article/details/gt2mpsfmqzp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.andypj.xyz/Article/details/gt2lzpsepkn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.svipenyu.cn/Article/details/gt2oibkvgvq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.nwbrower.top/Article/details/gt2vbkjgfjz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.redwolf501.top/Article/details/gt2arjyvbgu.html

[J06] 计算两时间之差
来源：http://dali.snrcjt.cn/Article/details/gt2ctntskat.html

Py:   (end - start).total_seconds()
来源：http://dali.zhoulong.xyz/Article/details/gt2cwqlrnmp.html

PHP:  $end->diff($start)->days;
来源：http://dali.yongpay.top/Article/details/gt2tkcnzipg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sweek.top/Article/details/gt2ojeapzng.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhongyouzk.top/Article/details/gt2cmkngpjs.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hysaishi.cn/Article/details/gt2zvafxjkm.html

Go:   end.Sub(start).Hours()
来源：http://dali.yj202588.top/Article/details/gt2ebxfmpsm.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cashguo.top/Article/details/gt2muxhysil.html

C#:   (end - start).TotalSeconds
来源：http://dali.hfpthk.cn/Article/details/gt2jmbwkdnm.html

[J07] 比较两个日期
来源：http://dali.daxiang520.top/Article/details/gt2agclipoz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinqigufen.top/Article/details/gt2hctpotgu.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.fengsongda.top/Article/details/gt2hhxrfkjs.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yuanzhike.top/Article/details/gt2eousaxbk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigufen.top/Article/details/gt2elbzsccw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinqigufen.top/Article/details/gt2iemhhkpz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhixingplan.top/Article/details/gt2mhjnqbsd.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2urrytefs.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gt2ogkievqp.html

[J08] 提取年月日与星期
来源：http://dali.hnqzz.top/Article/details/gt2nzfrfltu.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yj20258.top/Article/details/gt2nhkxoixr.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gogol.net.cn/Article/details/gt2jxgcanve.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cheryme.top/Article/details/gt2dsljextb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.fengsongda.top/Article/details/gt2lsgfbtpe.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.feifeiyinyue.top/Article/details/gt2dbhqqbba.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.pengpengdd.cyou/Article/details/gt2rivcsrxn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sweek.top/Article/details/gt2hulorqvo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.tianlin.xyz/Article/details/gt2oyfofpbh.html

[J09] 时区处理
来源：http://dali.yangfankeji.com/Article/details/gt2cjbrpfaq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jyoumei.cn/Article/details/gt2xrezfgts.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.kuanghao11.cn/Article/details/gt2kttupatb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yueranfly.top/Article/details/gt2ouucsjpj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tanke756.top/Article/details/gt2mfxlvszy.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2swdozepi.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sxryk.cn/Article/details/gt2kkkomiep.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.tianlin.xyz/Article/details/gt2toppowev.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ockoresm.html

[J10] 取今天 / 本月第一天
来源：http://dali.tanke756.top/Article/details/gt2qpdzarda.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.birdmap.top/Article/details/gt2eqsullii.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gzhubu.top/Article/details/gt2bffdbdxe.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jlsjyb.cn/Article/details/gt2cnmrofyq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2yfspcief.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.birdmap.top/Article/details/gt2jxiswykz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ivvv.top/Article/details/gt2tlqvvpcq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gzhubu.top/Article/details/gt2yiotsthr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.birdmap.top/Article/details/gt2cwrbxoxw.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2wlomrdoq.html

K. JSON 与序列化
来源：http://dali.ppjwa.cn/Article/details/gt2yhcgszuz.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2indhcjaf.html

[K01] 对象转 JSON 字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jfutjjdl.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mnsfoabm.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.pycfn.com/Article/details/gt2wbhzhbwd.html

JS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rxowfhwv.html

TS:   JSON.stringify(obj)
来源：http://dali.xinyue.icu/Article/details/gt2lopnhven.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.tanke756.top/Article/details/gt2zmzfbanm.html

Go:   json.Marshal(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2tptddtqt.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cdnleiting.top/Article/details/gt2sdifgeew.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2wkrywwto.html

[K02] JSON 字符串转对象
来源：http://dali.zycfv.cn/Article/details/gt2picudvsd.html

Py:   json.loads(s)
来源：http://dali.sysykeji.top/Article/details/gt2exknbhza.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.daxiang520.top/Article/details/gt2hcyruxkn.html

JS:   JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2fupvjhzf.html

TS:   JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gt2uysbewrb.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yuanzhike.top/Article/details/gt2xmxxussg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.tianlin.xyz/Article/details/gt2ennljktf.html

Ruby: JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gt2vntqbhxs.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.redwolf501.top/Article/details/gt2nqzttjyl.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.snrcjt.cn/Article/details/gt2sbywhmvc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ydzc1.top/Article/details/gt2moakclce.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2asyqddnd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2ziqhkmit.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2zbaligkt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zycfv.cn/Article/details/gt2qslubhkc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.dashuyun.cn/Article/details/gt2ehdwycgx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2kzyfxgnr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinqigfzy.top/Article/details/gt2wrduxvsv.html

[K04] 读取 JSON 文件
来源：http://dali.hysaishi.cn/Article/details/gt2xuydaoej.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sweek.top/Article/details/gt2kiwnwskc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.quarkkingdee.top/Article/details/gt2drogntyd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yueranfly.top/Article/details/gt2bzkrtuzg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sxryk.cn/Article/details/gt2cgcofpjv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.guannengcc.top/Article/details/gt2juxuyabl.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.pengpengdd.cyou/Article/details/gt2irmpjflx.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sufxvd.cn/Article/details/gt2wxbjxybq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.snrcjt.cn/Article/details/gt2rvpyxcsy.html

[K05] 深拷贝对象
来源：http://dali.yongpay.top/Article/details/gt2pwbhjynb.html

Py:   copy.deepcopy(obj)
来源：http://dali.guannengcc.top/Article/details/gt2lemeiofe.html

PHP:  unserialize(serialize($obj));
来源：http://dali.havefunace.top/Article/details/gt2lsfrfnyx.html

JS:   structuredClone(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2zcwgssdo.html

TS:   structuredClone(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2ulwtzjqb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xuanzx.com/Article/details/gt2fdwxpabd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.aibaodan.cn/Article/details/gt2dwfxlvgx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.0kj1m.cn/Article/details/gt2wmtrgbvy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gotoacloud.top/Article/details/gt2phscezfg.html

[K06] 解析 URL 查询串
来源：http://dali.mhx1999.top/Article/details/gt2iivjcgvq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shangyingyoupin.top/Article/details/gt2pqflcrue.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hfpthk.cn/Article/details/gt2witchlly.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cdnleiting.top/Article/details/gt2hyaqrpfp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangdashe.top/Article/details/gt2gsotpkdy.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gogol.net.cn/Article/details/gt2muniqvpp.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gt2ngmudyiw.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gt2sbhpcpwz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ivvv.top/Article/details/gt2vamoalrg.html

[K07] 进制转换
来源：http://dali.zhiwuduotai.top/Article/details/gt2egeqiweg.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gt2mhdfwcpg.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.meibo888.top/Article/details/gt2rjsglwmm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gt2hqsxnymb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gt2mnaukppp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ivvv.top/Article/details/gt2ogfjbllc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.havefunace.top/Article/details/gt2vocijfvy.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zycfv.cn/Article/details/gt2xpbnvrxe.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gt2nerulflh.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uqyprsgx.html

Py:   pickle.dumps(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rtkilhxe.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nwbrower.top/Article/details/gt2jsnnlbji.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.haohaochexian.top/Article/details/gt2tfruhndj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.snrcjt.cn/Article/details/gt2cdwdaawp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenlongwang.top/Article/details/gt2ktoelpto.html

Go:   encoding/gob
来源：http://dali.jiagoushi.top/Article/details/gt2lmcypyyy.html

Ruby: Marshal.dump(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2dcimumyj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.sufxvd.cn/Article/details/gt2mubmdqis.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2ltygmvsx.html

L. 网络请求
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2twgcyiaj.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ttzfiuwv.html

[L01] 发送 GET 请求
来源：http://dali.tanke756.top/Article/details/gt2ixqngiex.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ppjwa.cn/Article/details/gt2bywtprgy.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinghuilouyu.cn/Article/details/gt2heeqkjoe.html

JS:   await fetch(url)
来源：http://dali.gaohongyu789.top/Article/details/gt2heyetsmc.html

TS:   await fetch(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2akmadrol.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xinyue.icu/Article/details/gt2xswqfblg.html

Go:   resp, err := http.Get(url)
来源：http://dali.hammf.cn/Article/details/gt2grfexwte.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.dashuyun.cn/Article/details/gt2tojmzsbx.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinqigufen.top/Article/details/gt2ouwrkdlb.html

[L02] 发送 POST JSON
来源：http://dali.iojbl.cn/Article/details/gt2bvnuvfde.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yanxiufei.cn/Article/details/gt2ltbfkyqp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.bjfxy.top/Article/details/gt2jmenoiqr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lfwxzcuk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hnxiangtu.top/Article/details/gt2lsghroni.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hnxiangtu.top/Article/details/gt2baeutoyw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhoulong.xyz/Article/details/gt2beuizkev.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yuxming.cn/Article/details/gt2qksgddon.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.snrcjt.cn/Article/details/gt2qcohwdzg.html

[L03] 设置自定义请求头
来源：http://dali.wangdashe.top/Article/details/gt2cdnqaldm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ppjwa.cn/Article/details/gt2oijbljnn.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhixingplan.top/Article/details/gt2kpfalosb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258.top/Article/details/gt2ybtsolcg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ehwqpu.com/Article/details/gt2kifgvlda.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhixingplan.top/Article/details/gt2wimlosqt.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.andypj.xyz/Article/details/gt2bqoxivcq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jiagoushi.top/Article/details/gt2rubgidel.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yuanzhike.top/Article/details/gt2suncuswf.html

[L04] 设置超时
来源：http://dali.zycfv.cn/Article/details/gt2vczrxntp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.fzhhl.top/Article/details/gt2asvtskej.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.birdmap.top/Article/details/gt2fmnmljnf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hysaishi.cn/Article/details/gt2bofvgmhd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zdqjudy.top/Article/details/gt2cakgmrzo.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xylfe.cn/Article/details/gt2rhuripmk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ybcxt.top/Article/details/gt2wwqexaqw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gaohongyu789.top/Article/details/gt2xcqsleqh.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shangyingyoupin.top/Article/details/gt2rxdulayc.html

[L05] 上传文件（multipart）
来源：http://dali.yj20258.top/Article/details/gt2rvoazpdk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xylfe.cn/Article/details/gt2tqmslout.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.aizwys.cn/Article/details/gt2pglghgzt.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2blxixkwq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hywenlv.cn/Article/details/gt2qpgjgipo.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xylfe.cn/Article/details/gt2kuninqbq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.nanxinkj.top/Article/details/gt2pkslqbsr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ivvv.top/Article/details/gt2ugfsujba.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2fvzbentl.html

[L06] 解析响应为 JSON
来源：http://dali.zhengqikj.top/Article/details/gt2bjypkuld.html

Py:   resp.json()
来源：http://dali.tian-w.cn/Article/details/gt2rntrlxyn.html

PHP:  json_decode($body, true);
来源：http://dali.yj20258888.top/Article/details/gt2lmphykiw.html

JS:   await resp.json()
来源：http://dali.cqqwz.cn/Article/details/gt2uepazioh.html

TS:   await resp.json()
来源：http://dali.xuetiantiany.cn/Article/details/gt2fvvttzrp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.316326.xyz/Article/details/gt2ztgwdbee.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jlsjyb.cn/Article/details/gt2pftkwhnw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhiwuduotai.top/Article/details/gt2aksdjnjv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.smart0.xyz/Article/details/gt2yyijoyqp.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zulufjvd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.redwolf501.top/Article/details/gt2bkdcmoau.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cucudq.cn/Article/details/gt2wcqcubiu.html

JS:   resp.ok;  resp.status
来源：http://dali.shangyingyoupin.top/Article/details/gt2brxifzcn.html


<!-- 参考信息 -->