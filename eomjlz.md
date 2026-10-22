代发 wailian999

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.vqdsnc.cn/Article/details/gt2mriwobcq.html

Go:   defer f.Close()
来源：http://dali.mhx1999.top/Article/details/gt2zptqnhtq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.wangshuangyany.cn/Article/details/gt2cqrvtxqe.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hnqzz.top/Article/details/gt2bvnhrlbo.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2ilwmwvqx.html

I. 正则表达式
来源：http://dali.guannengcc.top/Article/details/gt2pvurfwse.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2bzxgcvag.html

[I01] 判断是否匹配
来源：http://dali.jianghu66.top/Article/details/gt2darwvxgf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yuxming.cn/Article/details/gt2tvvtzpot.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ybcxt.top/Article/details/gt2uuujpext.html

JS:   /\d+/.test(s)
来源：http://dali.smart0.xyz/Article/details/gt2cshzaing.html

TS:   /\d+/.test(s)
来源：http://dali.guannengcc.top/Article/details/gt2kwgxhinz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.chenzaomai.com/Article/details/gt2dypoptnh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hnqzz.top/Article/details/gt2prbynxym.html

Ruby: s.match?(/\d+/)
来源：http://dali.yongpay.top/Article/details/gt2gydkyoep.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yvedp.cn/Article/details/gt2bdcdldyd.html

[I02] 提取所有匹配
来源：http://dali.jiagoushi.top/Article/details/gt2ymfrftwg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tian-w.cn/Article/details/gt2rocbajes.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2viamhcfw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zycfv.cn/Article/details/gt2zubxxoyk.html

TS:   s.match(/\d+/g)
来源：http://dali.hnqzz.top/Article/details/gt2qboovcax.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yuanzhike.top/Article/details/gt2efiemumu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.9152youxi.cn/Article/details/gt2fxxpgdbj.html

Ruby: s.scan(/\d+/)
来源：http://dali.sysykeji.top/Article/details/gt2franmeco.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wyfwiskh.html

[I03] 提取捕获分组
来源：http://dali.xziqi.cn/Article/details/gt2lwgroieb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yueranfly.top/Article/details/gt2krvzawgo.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.aizwys.cn/Article/details/gt2hsoorzwq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2zscgnvdk.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yuxming.cn/Article/details/gt2dqyncaei.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hfpthk.cn/Article/details/gt2qkjsgrri.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hfpthk.cn/Article/details/gt2cmvsrizg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.havefunace.top/Article/details/gt2tcygtwki.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhixingplan.top/Article/details/gt2sjshaxjq.html

[I04] 正则替换
来源：http://dali.xylfe.cn/Article/details/gt2zqfnrtsz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ehwqpu.com/Article/details/gt2djhyaksg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yueranfly.top/Article/details/gt2juzhwlgv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.quarkkingdee.top/Article/details/gt2zrkpwtaw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.tianlin.xyz/Article/details/gt2ncpyqpkx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhixingplan.top/Article/details/gt2gbfpsvfr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tanke756.top/Article/details/gt2yzmmknds.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qkttvonx.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.iojbl.cn/Article/details/gt2rqwkebud.html

[I05] 按正则拆分
来源：http://dali.yj20258.top/Article/details/gt2lzfumjyk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.fzhhl.top/Article/details/gt2aaamdtsi.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gt2hidqglly.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zycfv.cn/Article/details/gt2hfokwfxn.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tian-w.cn/Article/details/gt2loaxrmwj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.vqdsnc.cn/Article/details/gt2dxafrpel.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.chenlongwang.top/Article/details/gt2skigsvfd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhoulong.xyz/Article/details/gt2sdxqkjym.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.havefunace.top/Article/details/gt2fbbbjhxa.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2opzakcql.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gt2gzzvhsoe.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.aizwys.cn/Article/details/gt2nsonlmxk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenzaomai.com/Article/details/gt2rxizzvoz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yvedp.cn/Article/details/gt2pdjcfwfu.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gt2ktqzwwwa.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zycfv.cn/Article/details/gt2ufhnlfcd.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinghuilouyu.cn/Article/details/gt2imclyrbz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.birdmap.top/Article/details/gt2xvxlzuzu.html

[I07] 忽略大小写与多行模式
来源：http://dali.quarkkingdee.top/Article/details/gt2cayirvfy.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhengqikj.top/Article/details/gt2kzixxeie.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.daxiang520.top/Article/details/gt2rnkjabxw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.chenzaomai.com/Article/details/gt2ohbsbcgs.html

TS:   /error/gim
来源：http://dali.xuetiantiany.cn/Article/details/gt2gpyzhsyo.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.redwolf501.top/Article/details/gt2hbtjrgjb.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.kuanghao11.cn/Article/details/gt2apfjtahm.html

Ruby: s.scan(/error/i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbbqxew.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hnxiangtu.top/Article/details/gt2fwxmmdwr.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.chenlongwang.top/Article/details/gt2zojistln.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.haohaochexian.top/Article/details/gt2omnkhufc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wjpxqudj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sysykeji.top/Article/details/gt2usjlkone.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qlaizpll.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.aibaodan.cn/Article/details/gt2lxcujjpo.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhengqikj.top/Article/details/gt2utvyauos.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.meibo888.top/Article/details/gt2vehgvjfw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xziqi.cn/Article/details/gt2zkylcwyn.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2kzocrqsr.html

J. 日期与时间
来源：http://dali.meibo888.top/Article/details/gt2oihtoviq.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2aqhffotv.html

[J01] 获取当前时间
来源：http://dali.daria6918.cn/Article/details/gt2zsnazrtm.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hfpthk.cn/Article/details/gt2lhplwppx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yj20258.top/Article/details/gt2molqyxrp.html

JS:   new Date();  Date.now()
来源：http://dali.tian-w.cn/Article/details/gt2uhivondf.html

TS:   new Date();  Date.now()
来源：http://dali.zhengqikj.top/Article/details/gt2yofqdaho.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.meibo888.top/Article/details/gt2sdydurqr.html

Go:   time.Now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hdhkszyd.html

Ruby: Time.now
来源：http://dali.tanke756.top/Article/details/gt2emmpnvzd.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yongpay.top/Article/details/gt2ispkbazd.html

[J02] 格式化输出
来源：http://dali.guowangkeji.top/Article/details/gt2cyoctbpb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgfzy.top/Article/details/gt2vlzwndmf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.bjfxy.top/Article/details/gt2fustjtlk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinqigufen.top/Article/details/gt2cfjbehce.html

TS:   d.toISOString()
来源：http://dali.wangdashe.top/Article/details/gt2bjmdctna.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.0kj1m.cn/Article/details/gt2lxvtrvnx.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.daxiang520.top/Article/details/gt2afvshvna.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258.top/Article/details/gt2xjnznxtt.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sxryk.cn/Article/details/gt2nxdcxetg.html

[J03] 字符串解析为日期
来源：http://dali.fengsongda.top/Article/details/gt2fsdmbjnr.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.vqdsnc.cn/Article/details/gt2kkcfhfug.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.dianchejie.cn/Article/details/gt2tbdvckbb.html

JS:   new Date("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gt2dobytlhf.html

TS:   new Date("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gt2iiorhcvc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gt2lriijoqy.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gt2fksiyrfi.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gt2jxqftpyr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gaohongyu789.top/Article/details/gt2oaqetksc.html

[J04] 时间戳与日期互转
来源：http://dali.sxryk.cn/Article/details/gt2faqramrm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jqgufenzy.top/Article/details/gt2oapgmeen.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cqqwz.cn/Article/details/gt2onjvmsoa.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhoulong.xyz/Article/details/gt2dqbtkxjo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jyoumei.cn/Article/details/gt2pvdecrmq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tanke756.top/Article/details/gt2bzxynjgc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.wangdashe.top/Article/details/gt2efilcilo.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.redwolf501.top/Article/details/gt2ufmprrup.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xwrsfsbj.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj20258888.top/Article/details/gt2ssxtunzq.html

Py:   now + timedelta(days=7)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2drbmrwjq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.tanke756.top/Article/details/gt2oglzzvph.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnxiangtu.top/Article/details/gt2zlsjhgln.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ybcxt.top/Article/details/gt2hsygufuq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.0kj1m.cn/Article/details/gt2uysilvbm.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sweek.top/Article/details/gt2xzotikyx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yj20258.top/Article/details/gt2cdfplrss.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.daxiang520.top/Article/details/gt2aigjqlhq.html

[J06] 计算两时间之差
来源：http://dali.yuanzhike.top/Article/details/gt2ghnseryn.html

Py:   (end - start).total_seconds()
来源：http://dali.nanxuanxn.top/Article/details/gt2xrqettzq.html

PHP:  $end->diff($start)->days;
来源：http://dali.havefunace.top/Article/details/gt2giybuxde.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jyoumei.cn/Article/details/gt2vykfatdo.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.meibo888.top/Article/details/gt2mgskmnxk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sufxvd.cn/Article/details/gt2hlxoxexl.html

Go:   end.Sub(start).Hours()
来源：http://dali.hfpthk.cn/Article/details/gt2bwvmmqdv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.pengpengdd.cyou/Article/details/gt2rwyzhcsq.html

C#:   (end - start).TotalSeconds
来源：http://dali.ybcxt.top/Article/details/gt2wbrahmcb.html

[J07] 比较两个日期
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ejjyexpv.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yj202588.top/Article/details/gt2fwlayxld.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.birdmap.top/Article/details/gt2hethexef.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yonumen.top/Article/details/gt2kihlwbbw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cdnleiting.top/Article/details/gt2emfikyag.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yuxming.cn/Article/details/gt2zrltmqiy.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hysaishi.cn/Article/details/gt2mduwgykn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gt2srogsyze.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jyoumei.cn/Article/details/gt2kwxjojxx.html

[J08] 提取年月日与星期
来源：http://dali.jianghu66.top/Article/details/gt2lircuwee.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shuidangran.top/Article/details/gt2wvmqgxth.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinqigufen.top/Article/details/gt2weuovqli.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yuxming.cn/Article/details/gt2pvuiqsnh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.wangdashe.top/Article/details/gt2qfmvbicf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.svipenyu.cn/Article/details/gt2kkxjhjsx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.andypj.xyz/Article/details/gt2lkskonyc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shangyingyoupin.top/Article/details/gt2mmuwrsja.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ybcxt.top/Article/details/gt2bjdphcoh.html

[J09] 时区处理
来源：http://dali.jyoumei.cn/Article/details/gt2upzbctqy.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.meibo888.top/Article/details/gt2cgtzldza.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.0kj1m.cn/Article/details/gt2pxtxqwdx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aizwys.cn/Article/details/gt2ifxjghlv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dianchejie.cn/Article/details/gt2qyfrxflg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nanxinkj.top/Article/details/gt2qpblhcgq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ppjwa.cn/Article/details/gt2rcwxzsts.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.andypj.xyz/Article/details/gt2untetxex.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xinyue.icu/Article/details/gt2xddajhfc.html

[J10] 取今天 / 本月第一天
来源：http://dali.yanxiufei.cn/Article/details/gt2kkvdyxeh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2wucrhdln.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.316326.xyz/Article/details/gt2vbrbbmli.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhoulong.xyz/Article/details/gt2vmqegtus.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cdnleiting.top/Article/details/gt2ndyguxgm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ufulglre.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cqqwz.cn/Article/details/gt2etjqskjq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qtamdimr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhoulong.xyz/Article/details/gt2knayzurm.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2vyrxstqc.html

K. JSON 与序列化
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qzbimyrp.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2yeimtmxc.html

[K01] 对象转 JSON 字符串
来源：http://dali.yj202588.top/Article/details/gt2wzmnhcjn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yonumen.top/Article/details/gt2cyxyesuf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shuidangran.top/Article/details/gt2clygvuhc.html

JS:   JSON.stringify(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2tlmwlrxi.html

TS:   JSON.stringify(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2oeyalgbu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cdnleiting.top/Article/details/gt2jhgjbkze.html

Go:   json.Marshal(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2xjmncvcy.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.pycfn.com/Article/details/gt2bdlrztwm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tian-w.cn/Article/details/gt2kxwbjrpi.html

[K02] JSON 字符串转对象
来源：http://dali.vqdsnc.cn/Article/details/gt2qndtuuiv.html

Py:   json.loads(s)
来源：http://dali.jinqigufen.top/Article/details/gt2zittphtj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jqgfzy.top/Article/details/gt2lsljlavh.html

JS:   JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2dgiicmff.html

TS:   JSON.parse(s)
来源：http://dali.yvedp.cn/Article/details/gt2xsxmiswj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.mhx1999.top/Article/details/gt2fnqfmfgl.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.vqdsnc.cn/Article/details/gt2oqmzqfzh.html

Ruby: JSON.parse(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wyxizgzh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gzhubu.top/Article/details/gt2bgtgpnfm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.guannengcc.top/Article/details/gt2brzxdqzy.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yj202588.top/Article/details/gt2ymyvwavg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gzhubu.top/Article/details/gt2eugotgyn.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.andypj.xyz/Article/details/gt2bxldmiaq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhengqikj.top/Article/details/gt2gujbdktj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2dmjtlsoy.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yuxming.cn/Article/details/gt2youhkhvp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2zjpebhzv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.9152youxi.cn/Article/details/gt2gohfphxf.html

[K04] 读取 JSON 文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2tlrvwiid.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xziqi.cn/Article/details/gt2bfgzbpqj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.nanxinkj.top/Article/details/gt2mldygmjb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhoulong.xyz/Article/details/gt2jszqpcsl.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yongpay.top/Article/details/gt2maxheysm.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gt2sgflwroq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tqwkwjky.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yuxming.cn/Article/details/gt2izihxchn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinqigfzy.top/Article/details/gt2nnrziezh.html

[K05] 深拷贝对象
来源：http://dali.dianchejie.cn/Article/details/gt2wizcozex.html

Py:   copy.deepcopy(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2raldsfqq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.pengpengdd.cyou/Article/details/gt2ncwvnzvp.html

JS:   structuredClone(obj)
来源：http://dali.yvedp.cn/Article/details/gt2cdbyglud.html

TS:   structuredClone(obj)
来源：http://dali.sweek.top/Article/details/gt2zvgcavtl.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jlsjyb.cn/Article/details/gt2dkkiuofp.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.wangdashe.top/Article/details/gt2udqwakpg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.redwolf501.top/Article/details/gt2egpzurgl.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqpkjhw.html

[K06] 解析 URL 查询串
来源：http://dali.wangdashe.top/Article/details/gt2vslpsrgi.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yuanzhike.top/Article/details/gt2ingurucu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.fzhhl.top/Article/details/gt2murfsvps.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhoulong.xyz/Article/details/gt2vmslezvy.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shangyingyoupin.top/Article/details/gt2kcbxxhyd.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.tanke756.top/Article/details/gt2dvacztlj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nanxuanxn.top/Article/details/gt2ooyfflwb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gt2iladanqa.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yonumen.top/Article/details/gt2pouhjjko.html

[K07] 进制转换
来源：http://dali.fzhhl.top/Article/details/gt2fjyeuxad.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gt2ytodyfdb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xuanzx.com/Article/details/gt2zqqukwjx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gt2gdjhvzjo.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gt2sryicgea.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rspvdiys.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yueranfly.top/Article/details/gt2jgiooxdy.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yj20258.top/Article/details/gt2xsagkrvj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gt2dtixaefp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jqgfzy.top/Article/details/gt2oiofpljr.html

Py:   pickle.dumps(obj)
来源：http://dali.iojbl.cn/Article/details/gt2bdykixfg.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.meibo888.top/Article/details/gt2cflvdraa.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxrgytf.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fjdtirmi.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.snrcjt.cn/Article/details/gt2edrgiacp.html

Go:   encoding/gob
来源：http://dali.316326.xyz/Article/details/gt2fesexiir.html

Ruby: Marshal.dump(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2qbxompzf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jinqigufen.top/Article/details/gt2bxaddarz.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2ksinjcyl.html

L. 网络请求
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2clezqqdf.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2yjlhjvwe.html

[L01] 发送 GET 请求
来源：http://dali.zhiwuduotai.top/Article/details/gt2jfqyfqnr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.feifeiyinyue.top/Article/details/gt2sokapums.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhongyouzk.top/Article/details/gt2sjoibmjt.html

JS:   await fetch(url)
来源：http://dali.sxryk.cn/Article/details/gt2tayidxcl.html

TS:   await fetch(url)
来源：http://dali.zhoulong.xyz/Article/details/gt2cckvvqdt.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.nanxuanxn.top/Article/details/gt2izglfgql.html

Go:   resp, err := http.Get(url)
来源：http://dali.haohaochexian.top/Article/details/gt2yuntaaib.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yuxming.cn/Article/details/gt2amemdjag.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dhnaeqhu.html

[L02] 发送 POST JSON
来源：http://dali.wangshuangyany.cn/Article/details/gt2vqdhsprs.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.dashuyun.cn/Article/details/gt2qlbgjwbx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cheryme.top/Article/details/gt2iviouoxr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gotoacloud.top/Article/details/gt2cuzgbnqe.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yueranfly.top/Article/details/gt2nljeigvi.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkwlrvc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.bjfxy.top/Article/details/gt2gjwycosh.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhongyouzk.top/Article/details/gt2blbrtbvb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ppjwa.cn/Article/details/gt2vktbmkob.html

[L03] 设置自定义请求头
来源：http://dali.chenjidiqi.icu/Article/details/gt2zupeehle.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.316326.xyz/Article/details/gt2napcfurj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.guannengcc.top/Article/details/gt2aldnmszh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.mhx1999.top/Article/details/gt2immyufex.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuetiantiany.cn/Article/details/gt2lnixtssg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.svipenyu.cn/Article/details/gt2zjmbueym.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.chenjidiqi.icu/Article/details/gt2uxuntztk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gzhubu.top/Article/details/gt2iklwxoup.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gaohongyu789.top/Article/details/gt2ewwrgtxh.html

[L04] 设置超时
来源：http://dali.jlsjyb.cn/Article/details/gt2hrqvyekg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.smart0.xyz/Article/details/gt2myyirvce.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hysaishi.cn/Article/details/gt2vcaudnyf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jyoumei.cn/Article/details/gt2bjhzbvpf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pengpengdd.cyou/Article/details/gt2jcajvvtl.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sweek.top/Article/details/gt2akxonxhe.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.fengsongda.top/Article/details/gt2liofaugd.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.feifeiyinyue.top/Article/details/gt2tsssrwqz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.tian-w.cn/Article/details/gt2aqurvruo.html

[L05] 上传文件（multipart）
来源：http://dali.tanke756.top/Article/details/gt2wkmghuid.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cdnleiting.top/Article/details/gt2ysuzqctl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yonumen.top/Article/details/gt2auusplsj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.snrcjt.cn/Article/details/gt2ottnhpzm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fhcitgly.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhongyouzk.top/Article/details/gt2chmbmctx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2cctxcpre.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jiagoushi.top/Article/details/gt2lgkjmvoo.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ivvv.top/Article/details/gt2vsoqivfm.html

[L06] 解析响应为 JSON
来源：http://dali.yj202588.top/Article/details/gt2bagyvqzq.html

Py:   resp.json()
来源：http://dali.havefunace.top/Article/details/gt2rcuycqfo.html

PHP:  json_decode($body, true);
来源：http://dali.tianlin.xyz/Article/details/gt2hdqjdzcq.html

JS:   await resp.json()
来源：http://dali.hfpthk.cn/Article/details/gt2zuzgyskj.html

TS:   await resp.json()
来源：http://dali.yuanzhike.top/Article/details/gt2rjevmrok.html


<!-- 参考信息 -->