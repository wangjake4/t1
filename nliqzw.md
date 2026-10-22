代发 wailian999

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2qtqhqvuj.html

I. 正则表达式
来源：http://dali.nanxuanxn.top/Article/details/gt2wzrflwvb.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2rsqlvudt.html

[I01] 判断是否匹配
来源：http://dali.yj20258888.top/Article/details/gt2rsofnbrl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gogol.net.cn/Article/details/gt2mxumbkbl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.guannengcc.top/Article/details/gt2leitddzl.html

JS:   /\d+/.test(s)
来源：http://dali.hnqzz.top/Article/details/gt2utggmaim.html

TS:   /\d+/.test(s)
来源：http://dali.hysaishi.cn/Article/details/gt2vqlaicpc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ehwqpu.com/Article/details/gt2ffbwjscr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhixingplan.top/Article/details/gt2ehszgktn.html

Ruby: s.match?(/\d+/)
来源：http://dali.yj20258888.top/Article/details/gt2tfvakczc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.guowangkeji.top/Article/details/gt2fdkkohrb.html

[I02] 提取所有匹配
来源：http://dali.smart0.xyz/Article/details/gt2awsqqqyf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ppjwa.cn/Article/details/gt2zafadpmw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yanxiufei.cn/Article/details/gt2vgcdilzw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jlsjyb.cn/Article/details/gt2nlpqmrap.html

TS:   s.match(/\d+/g)
来源：http://dali.tanke756.top/Article/details/gt2nreaemws.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.kuanghao11.cn/Article/details/gt2rtyhddkg.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.fzhhl.top/Article/details/gt2xsdykpda.html

Ruby: s.scan(/\d+/)
来源：http://dali.cdnleiting.top/Article/details/gt2mhawhwai.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gt2kqezjftv.html

[I03] 提取捕获分组
来源：http://dali.hongshengwenyu.top/Article/details/gt2wpfalgrm.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.birdmap.top/Article/details/gt2ybbceqqj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gaohongyu789.top/Article/details/gt2vhmfczbn.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gaohongyu789.top/Article/details/gt2zouurhmb.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yj20258888.top/Article/details/gt2hchviwnw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yongpay.top/Article/details/gt2ygekidet.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhiwuduotai.top/Article/details/gt2hdnyhrcl.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhixingplan.top/Article/details/gt2petwxjlg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.wangdashe.top/Article/details/gt2jxmbvdlh.html

[I04] 正则替换
来源：http://dali.kuanghao11.cn/Article/details/gt2pucdzlqw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jqgufenzy.top/Article/details/gt2tfemnbxy.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tvnqfgsg.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigfzy.top/Article/details/gt2saxtneyr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigfzy.top/Article/details/gt2lwocijnl.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hammf.cn/Article/details/gt2unmypyvu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.daria6918.cn/Article/details/gt2htjzwpgi.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cqqwz.cn/Article/details/gt2xsnowomn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jiagoushi.top/Article/details/gt2kohdmjsf.html

[I05] 按正则拆分
来源：http://dali.sysykeji.top/Article/details/gt2vlqbnwmb.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gaohongyu789.top/Article/details/gt2gflgzrww.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2cmzsdvto.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yueranfly.top/Article/details/gt2otguuypl.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gt2ouxwegkw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jyoumei.cn/Article/details/gt2svtpkqwc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.daria6918.cn/Article/details/gt2gbzahynz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nwbrower.top/Article/details/gt2wksjhwcg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.aizwys.cn/Article/details/gt2wivcyecn.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.pycfn.com/Article/details/gt2uabxukph.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yj20258888.top/Article/details/gt2enpxdbea.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.feifeiyinyue.top/Article/details/gt2eultcxjv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.meibo888.top/Article/details/gt2tpldwzpm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhoulong.xyz/Article/details/gt2qjoazflx.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zycfv.cn/Article/details/gt2lpquoffw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.tanke756.top/Article/details/gt2iiidnowc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jlsjyb.cn/Article/details/gt2xiemlwfz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gaohongyu789.top/Article/details/gt2ujmxuzls.html

[I07] 忽略大小写与多行模式
来源：http://dali.ydzc1.top/Article/details/gt2bjefgdac.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jyoumei.cn/Article/details/gt2nvlablqk.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zycfv.cn/Article/details/gt2bmfjgkwq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.dashuyun.cn/Article/details/gt2sfeulvqh.html

TS:   /error/gim
来源：http://dali.zdqjudy.top/Article/details/gt2ocoxzccl.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xkjlellm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.daxiang520.top/Article/details/gt2wnmdzfrp.html

Ruby: s.scan(/error/i)
来源：http://dali.vqdsnc.cn/Article/details/gt2yizqtbgn.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yvedp.cn/Article/details/gt2oksvzbgm.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nanxuanxn.top/Article/details/gt2mkjnvlsd.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dxnmjptg.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.chenzaomai.com/Article/details/gt2zqfemtnw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinqigfzy.top/Article/details/gt2yrsdjmac.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yuxming.cn/Article/details/gt2otqryqwx.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.snrcjt.cn/Article/details/gt2ltzbtspe.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hnxiangtu.top/Article/details/gt2fkjhopnm.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yuanzhike.top/Article/details/gt2jzegjshu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hnxiangtu.top/Article/details/gt2axevbxee.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2gfkewetq.html

J. 日期与时间
来源：http://dali.cheryme.top/Article/details/gt2kpkbrkvc.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2jxpxabkp.html

[J01] 获取当前时间
来源：http://dali.shangyingyoupin.top/Article/details/gt2qhqntxsr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhiwuduotai.top/Article/details/gt2bjvwzgcu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cucudq.cn/Article/details/gt2eqjjvpty.html

JS:   new Date();  Date.now()
来源：http://dali.dashuyun.cn/Article/details/gt2zhrqfioa.html

TS:   new Date();  Date.now()
来源：http://dali.ydzc1.top/Article/details/gt2byamghyc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.tian-w.cn/Article/details/gt2nowgtdqb.html

Go:   time.Now()
来源：http://dali.wangshuangyany.cn/Article/details/gt2hwfttuhs.html

Ruby: Time.now
来源：http://dali.hnxiangtu.top/Article/details/gt2hoterzfq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xylfe.cn/Article/details/gt2ustnehex.html

[J02] 格式化输出
来源：http://dali.yongpay.top/Article/details/gt2yotmbleb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.snrcjt.cn/Article/details/gt2smbqwgel.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.vqdsnc.cn/Article/details/gt2njbsivyq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xylfe.cn/Article/details/gt2oixutwpt.html

TS:   d.toISOString()
来源：http://dali.redwolf501.top/Article/details/gt2tknckpgj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yuanzhike.top/Article/details/gt2gfipduab.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shzxlz.cn/Article/details/gt2dbhaybrr.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnqzz.top/Article/details/gt2ybwpdzpb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.fengsongda.top/Article/details/gt2kkdntaoz.html

[J03] 字符串解析为日期
来源：http://dali.gaohongyu789.top/Article/details/gt2heueojfm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cdnleiting.top/Article/details/gt2jpewhlqm.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.guannengcc.top/Article/details/gt2aofqddsq.html

JS:   new Date("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gt2vtfyxxeq.html

TS:   new Date("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gt2hyczllhv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gt2lxxvlxqw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gt2rcxlmaqh.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gt2ozgqrspw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cheryme.top/Article/details/gt2ylptsjnz.html

[J04] 时间戳与日期互转
来源：http://dali.xuetiantiany.cn/Article/details/gt2wtdrxgbz.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.tianlin.xyz/Article/details/gt2ymnciyuq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.wangdashe.top/Article/details/gt2inmcopqc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.dashuyun.cn/Article/details/gt2gbhwnwaa.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.nwbrower.top/Article/details/gt2cmwemctk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.mhx1999.top/Article/details/gt2leabqnqq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sysykeji.top/Article/details/gt2whrsudhx.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.daria6918.cn/Article/details/gt2ayvavujf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2krvonoki.html

[J05] 时间加减（加 7 天）
来源：http://dali.0kj1m.cn/Article/details/gt2unaxlgku.html

Py:   now + timedelta(days=7)
来源：http://dali.meibo888.top/Article/details/gt2lubikdft.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.kuanghao11.cn/Article/details/gt2doecfzpi.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangshuangyany.cn/Article/details/gt2kqhsxlfl.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuanzhike.top/Article/details/gt2kercegdb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.mhx1999.top/Article/details/gt2amyxmshh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hywenlv.cn/Article/details/gt2ppyzjczj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yuanzhike.top/Article/details/gt2anbiugjt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.c1oappe.top/Article/details/gt2meleeqgg.html

[J06] 计算两时间之差
来源：http://dali.yueranfly.top/Article/details/gt2hcenawiv.html

Py:   (end - start).total_seconds()
来源：http://dali.jqgfzy.top/Article/details/gt2cnqexzag.html

PHP:  $end->diff($start)->days;
来源：http://dali.cdnleiting.top/Article/details/gt2ksczhizh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cdnleiting.top/Article/details/gt2nurtnfve.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.pengpengdd.cyou/Article/details/gt2xckhijhh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xylfe.cn/Article/details/gt2lehrmhdn.html

Go:   end.Sub(start).Hours()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ixkyagfe.html

Ruby: end - start                 # 返回秒数
来源：http://dali.pycfn.com/Article/details/gt2ffspfmkq.html

C#:   (end - start).TotalSeconds
来源：http://dali.yonumen.top/Article/details/gt2ojmzzwhm.html

[J07] 比较两个日期
来源：http://dali.c1oappe.top/Article/details/gt2hziygxwo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cashguo.top/Article/details/gt2perjxtqz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hongshengwenyu.top/Article/details/gt2jxkacvca.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yangfankeji.com/Article/details/gt2ttkxbhoj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.gotoacloud.top/Article/details/gt2inzgbatw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.aibaodan.cn/Article/details/gt2nggqqbbc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2isjyzdiv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yj20258.top/Article/details/gt2ouhascuf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xziqi.cn/Article/details/gt2reuyvpvf.html

[J08] 提取年月日与星期
来源：http://dali.xylfe.cn/Article/details/gt2kzxiokuu.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cdnleiting.top/Article/details/gt2ptwqjfpe.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yangfankeji.com/Article/details/gt2vnrzrgpg.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.snrcjt.cn/Article/details/gt2jpprukgq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.mhx1999.top/Article/details/gt2njeobhlh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.chenzaomai.com/Article/details/gt2bkuasxgp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hnqzz.top/Article/details/gt2dxrshpiy.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jqgufenzy.top/Article/details/gt2fzfunyhg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.fzhhl.top/Article/details/gt2uidvsihk.html

[J09] 时区处理
来源：http://dali.chenlongwang.top/Article/details/gt2xjeirtsq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mhwnuhzl.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cqqwz.cn/Article/details/gt2jpzhijkq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jcvghjep.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aizwys.cn/Article/details/gt2cxnknxyh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gaohongyu789.top/Article/details/gt2llhycybf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hnxiangtu.top/Article/details/gt2ttiwgduh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yj202588.top/Article/details/gt2ozxuuylt.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.0kj1m.cn/Article/details/gt2cjgnkmat.html

[J10] 取今天 / 本月第一天
来源：http://dali.gzhubu.top/Article/details/gt2mtcrpsyf.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cqqwz.cn/Article/details/gt2cueodpvi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hammf.cn/Article/details/gt2tsrylzvz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yongpay.top/Article/details/gt2fjkqlbhr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wcxaslyk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hnqzz.top/Article/details/gt2hncvycse.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yangfankeji.com/Article/details/gt2vukaouwc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.9152youxi.cn/Article/details/gt2guigamfs.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenzaomai.com/Article/details/gt2fffgevfy.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2dnriyvrr.html

K. JSON 与序列化
来源：http://dali.hysaishi.cn/Article/details/gt2neetvark.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2iurpwrbu.html

[K01] 对象转 JSON 字符串
来源：http://dali.havefunace.top/Article/details/gt2weuvxwej.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cyxmlukv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxuanxn.top/Article/details/gt2esxbzbdc.html

JS:   JSON.stringify(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2inahhivo.html

TS:   JSON.stringify(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2gpwoxzef.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xinyue.icu/Article/details/gt2rrgkftwy.html

Go:   json.Marshal(obj)
来源：http://dali.hammf.cn/Article/details/gt2idfqksbt.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cqqwz.cn/Article/details/gt2owomwfuq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2mglaxtms.html

[K02] JSON 字符串转对象
来源：http://dali.9152youxi.cn/Article/details/gt2godkazyo.html

Py:   json.loads(s)
来源：http://dali.316326.xyz/Article/details/gt2mhufsfsk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hywenlv.cn/Article/details/gt2tewfxper.html

JS:   JSON.parse(s)
来源：http://dali.tanke756.top/Article/details/gt2jlsswdkp.html

TS:   JSON.parse(s)
来源：http://dali.daxiang520.top/Article/details/gt2bvrbhgwb.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yangfankeji.com/Article/details/gt2udrjmuyz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bkjgugdy.html

Ruby: JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gt2enitzkra.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2ozbyfxye.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yonumen.top/Article/details/gt2jtymfuuo.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgtxeps.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.aizwys.cn/Article/details/gt2jwgwlxgk.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gt2hkiqpnkl.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zycfv.cn/Article/details/gt2gkahkqal.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ivvv.top/Article/details/gt2bhaqwuez.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jiagoushi.top/Article/details/gt2bxnnmcad.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.fengsongda.top/Article/details/gt2lnnymugq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sxryk.cn/Article/details/gt2igqpyrbe.html

[K04] 读取 JSON 文件
来源：http://dali.aibaodan.cn/Article/details/gt2eufefeyq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jyoumei.cn/Article/details/gt2dixajxbo.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.havefunace.top/Article/details/gt2wwpspwbi.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2zxfcdcyj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aizwys.cn/Article/details/gt2crhvusqm.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.chenjidiqi.icu/Article/details/gt2leeteijc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vlzwvmpg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cheryme.top/Article/details/gt2mqwczuax.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shuidangran.top/Article/details/gt2ggrneaxl.html

[K05] 深拷贝对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vgdvclcn.html

Py:   copy.deepcopy(obj)
来源：http://dali.daxiang520.top/Article/details/gt2yvmiysmw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.andypj.xyz/Article/details/gt2rodespap.html

JS:   structuredClone(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2yckpdhfz.html

TS:   structuredClone(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2goqitolh.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ydzc1.top/Article/details/gt2mptciqip.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.svipenyu.cn/Article/details/gt2qevqkzqq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.dashuyun.cn/Article/details/gt2oxufqlvd.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.bjfxy.top/Article/details/gt2bwaopgir.html

[K06] 解析 URL 查询串
来源：http://dali.cqqwz.cn/Article/details/gt2qysaoefn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.nanxinkj.top/Article/details/gt2ngrqvpas.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yuanzhike.top/Article/details/gt2dbtkkvva.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gogol.net.cn/Article/details/gt2efxgaheu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oofdxggl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.feifeiyinyue.top/Article/details/gt2dlahywrg.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hongshengwenyu.top/Article/details/gt2kxqgzqrm.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.nwbrower.top/Article/details/gt2ugsviflm.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.0kj1m.cn/Article/details/gt2pskgltju.html

[K07] 进制转换
来源：http://dali.guannengcc.top/Article/details/gt2jatovpfa.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gt2ieqmqxyq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2zrrkvrwf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gt2iayrcbkx.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2unwbljex.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gt2vlxrxnxl.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jqgfzy.top/Article/details/gt2ahpwpbqs.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.andypj.xyz/Article/details/gt2wlyjxzyb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gt2sxuzronh.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.redwolf501.top/Article/details/gt2xlcmdnso.html

Py:   pickle.dumps(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2kidgyosd.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yj202588.top/Article/details/gt2pspwtupc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.daria6918.cn/Article/details/gt2zbqflpmd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sxryk.cn/Article/details/gt2pxthbpfg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhoulong.xyz/Article/details/gt2prpoccvv.html

Go:   encoding/gob
来源：http://dali.shangyingyoupin.top/Article/details/gt2ykvvyzic.html

Ruby: Marshal.dump(obj)
来源：http://dali.hnqzz.top/Article/details/gt2aaqcpsfg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.pengpengdd.cyou/Article/details/gt2bdrkahmd.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2zldozbza.html

L. 网络请求
来源：http://dali.yuanzhike.top/Article/details/gt2xlhrcglz.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2fvnegioh.html

[L01] 发送 GET 请求
来源：http://dali.chenlongwang.top/Article/details/gt2ganotgfs.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.guannengcc.top/Article/details/gt2kbjwhtfb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yanxiufei.cn/Article/details/gt2lmlmyycp.html

JS:   await fetch(url)
来源：http://dali.gzhubu.top/Article/details/gt2idbhitnh.html

TS:   await fetch(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ylzznkpj.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hnqzz.top/Article/details/gt2kncrclpq.html

Go:   resp, err := http.Get(url)
来源：http://dali.daxiang520.top/Article/details/gt2ukgvesww.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cashguo.top/Article/details/gt2zibekzzs.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhongyouzk.top/Article/details/gt2jeurrsjy.html

[L02] 发送 POST JSON
来源：http://dali.cashguo.top/Article/details/gt2vcasryyt.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yanxiufei.cn/Article/details/gt2jwboouev.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.havefunace.top/Article/details/gt2wexgqifz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bfwpuasc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ivvv.top/Article/details/gt2wnimlhdk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jianghu66.top/Article/details/gt2ogbchbru.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bibxbawb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cqqwz.cn/Article/details/gt2ygvbrkrk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yvedp.cn/Article/details/gt2wpglemcg.html

[L03] 设置自定义请求头
来源：http://dali.sxryk.cn/Article/details/gt2glpkextt.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hammf.cn/Article/details/gt2rhstecyc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shangyingyoupin.top/Article/details/gt2wmnlditx.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yueranfly.top/Article/details/gt2oocehddg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnxiangtu.top/Article/details/gt2hrmfsxxv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.quarkkingdee.top/Article/details/gt2loftabps.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gzhubu.top/Article/details/gt2whgczqlq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.wangshuangyany.cn/Article/details/gt2aqwxkpda.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sufxvd.cn/Article/details/gt2jmvkniub.html

[L04] 设置超时
来源：http://dali.zhiwuduotai.top/Article/details/gt2fbkhvigc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hfpthk.cn/Article/details/gt2kkmrccrs.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhengqikj.top/Article/details/gt2owtdtnqx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.meibo888.top/Article/details/gt2jjmkerqc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iuoyntmk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yonumen.top/Article/details/gt2wmslydsq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.pycfn.com/Article/details/gt2oodimnzl.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ehwqpu.com/Article/details/gt2cdghtsrn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gzhubu.top/Article/details/gt2pkzysipg.html

[L05] 上传文件（multipart）
来源：http://dali.aizwys.cn/Article/details/gt2jtkyupro.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.wangshuangyany.cn/Article/details/gt2rsifqnyt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.c1oappe.top/Article/details/gt2jkiugicw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.daxiang520.top/Article/details/gt2rqslvyof.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.vqdsnc.cn/Article/details/gt2nssgggeo.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.birdmap.top/Article/details/gt2vrjntmzp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.9152youxi.cn/Article/details/gt2skqrduhy.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yvedp.cn/Article/details/gt2vexjkigx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xziqi.cn/Article/details/gt2wsptqwzi.html

[L06] 解析响应为 JSON
来源：http://dali.nwbrower.top/Article/details/gt2xefsuxro.html

Py:   resp.json()
来源：http://dali.yangfankeji.com/Article/details/gt2mkhoiejd.html

PHP:  json_decode($body, true);
来源：http://dali.xylfe.cn/Article/details/gt2gcnhcgis.html

JS:   await resp.json()
来源：http://dali.yvedp.cn/Article/details/gt2ohkzngtc.html

TS:   await resp.json()
来源：http://dali.ybcxt.top/Article/details/gt2tpecqwdo.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hammf.cn/Article/details/gt2qixovggn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jianghu66.top/Article/details/gt2duojskpy.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jiagoushi.top/Article/details/gt2csaovqff.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bvuylqsj.html


<!-- 参考信息 -->