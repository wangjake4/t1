代发 wailian999

================================================================================
来源：http://dali.sweek.top/Article/details/gt2xywurgtm.html

I. 正则表达式
来源：http://dali.fzhhl.top/Article/details/gt2ypchdwos.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2iczuevqo.html

[I01] 判断是否匹配
来源：http://dali.chenjidiqi.icu/Article/details/gt2ecehxeww.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.fzhhl.top/Article/details/gt2kptgbfic.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gotoacloud.top/Article/details/gt2xstjyufa.html

JS:   /\d+/.test(s)
来源：http://dali.xylfe.cn/Article/details/gt2luyupped.html

TS:   /\d+/.test(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2bclzzmes.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yuanzhike.top/Article/details/gt2okhnufeh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lfmsvzun.html

Ruby: s.match?(/\d+/)
来源：http://dali.nanxuanxn.top/Article/details/gt2nwowppfy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.birdmap.top/Article/details/gt2qzlnorcm.html

[I02] 提取所有匹配
来源：http://dali.iojbl.cn/Article/details/gt2xnoxaxqh.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tanke756.top/Article/details/gt2vunsxkkg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uoqrswms.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj20258.top/Article/details/gt2cqixcbzr.html

TS:   s.match(/\d+/g)
来源：http://dali.cqqwz.cn/Article/details/gt2hjhnjpwq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yonumen.top/Article/details/gt2uzwfgebz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.c1oappe.top/Article/details/gt2levazvrj.html

Ruby: s.scan(/\d+/)
来源：http://dali.daria6918.cn/Article/details/gt2hsacvjol.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.meibo888.top/Article/details/gt2ejyzjqdp.html

[I03] 提取捕获分组
来源：http://dali.dianchejie.cn/Article/details/gt2ijnglxtz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.dashuyun.cn/Article/details/gt2ovdnqcfz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ppjwa.cn/Article/details/gt2wptdjzrt.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2itnlkxpd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ehwqpu.com/Article/details/gt2awojewab.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.tanke756.top/Article/details/gt2ovavqvrn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.haohaochexian.top/Article/details/gt2zgjfvted.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.0kj1m.cn/Article/details/gt2skbkklim.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cdnleiting.top/Article/details/gt2gyfeuugc.html

[I04] 正则替换
来源：http://dali.cucudq.cn/Article/details/gt2ilklfrpf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hammf.cn/Article/details/gt2effblzre.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sweek.top/Article/details/gt2iaevtfnd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tvcblfds.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.tian-w.cn/Article/details/gt2qmudahxj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2pgtdvnxd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cashguo.top/Article/details/gt2lmrxjdph.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jqgfzy.top/Article/details/gt2jriumlfj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sweek.top/Article/details/gt2zlnvbhcf.html

[I05] 按正则拆分
来源：http://dali.dashuyun.cn/Article/details/gt2swnppjwc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.sufxvd.cn/Article/details/gt2qypjrbrs.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zdqjudy.top/Article/details/gt2rgqnmzsq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.snrcjt.cn/Article/details/gt2pvvpvjlv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.chenzaomai.com/Article/details/gt2gyoqwslk.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhiwuduotai.top/Article/details/gt2qwubjvoh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.nanxinkj.top/Article/details/gt2cmccotbz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.daria6918.cn/Article/details/gt2kimrliid.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hywenlv.cn/Article/details/gt2ldejporp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sysykeji.top/Article/details/gt2fibsyaia.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shangyingyoupin.top/Article/details/gt2sdudhdvq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cashguo.top/Article/details/gt2egfahpbu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mhycvyfp.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shzxlz.cn/Article/details/gt2zupxtnpb.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xuetiantiany.cn/Article/details/gt2nnzbpxbe.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.dashuyun.cn/Article/details/gt2ssfrlutn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shuidangran.top/Article/details/gt2obwtjxwx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2deawmkik.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinqigfzy.top/Article/details/gt2vdixegrl.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ehwqpu.com/Article/details/gt2optnbksd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fqjipasu.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.wangdashe.top/Article/details/gt2wzdoommx.html

TS:   /error/gim
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2whwngjxw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xinyue.icu/Article/details/gt2ixmyoneq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.kuanghao11.cn/Article/details/gt2tqctiiat.html

Ruby: s.scan(/error/i)
来源：http://dali.xuetiantiany.cn/Article/details/gt2rgxnkrtx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.wangshuangyany.cn/Article/details/gt2dpljlzkj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhoulong.xyz/Article/details/gt2rerjient.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.gogol.net.cn/Article/details/gt2sskxkqzj.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gzhubu.top/Article/details/gt2hhdbcszr.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fvgsmjpc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dianchejie.cn/Article/details/gt2xxlpeaka.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hnxiangtu.top/Article/details/gt2iqztdbif.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.0kj1m.cn/Article/details/gt2pforvzyj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jianghu66.top/Article/details/gt2aopjctlc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.0kj1m.cn/Article/details/gt2vmynnfhu.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2lghneivs.html

J. 日期与时间
来源：http://dali.xziqi.cn/Article/details/gt2awdcpomr.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2qukcnbpx.html

[J01] 获取当前时间
来源：http://dali.vqdsnc.cn/Article/details/gt2zkcauxwk.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinqigfzy.top/Article/details/gt2riqxurfx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.andypj.xyz/Article/details/gt2rujaaslo.html

JS:   new Date();  Date.now()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cwyxrbqu.html

TS:   new Date();  Date.now()
来源：http://dali.gogol.net.cn/Article/details/gt2omcrccln.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.kuanghao11.cn/Article/details/gt2lfdoeacj.html

Go:   time.Now()
来源：http://dali.ppjwa.cn/Article/details/gt2yrjgovjk.html

Ruby: Time.now
来源：http://dali.zhongyouzk.top/Article/details/gt2snretzzx.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zdqjudy.top/Article/details/gt2wbtqnmpp.html

[J02] 格式化输出
来源：http://dali.aibaodan.cn/Article/details/gt2hdhdnwlr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.birdmap.top/Article/details/gt2npqkyfvl.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cashguo.top/Article/details/gt2ticfnecu.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.sysykeji.top/Article/details/gt2oltovobu.html

TS:   d.toISOString()
来源：http://dali.guowangkeji.top/Article/details/gt2pturxbns.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dtqpplcg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.wangshuangyany.cn/Article/details/gt2fwpxntdo.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenzaomai.com/Article/details/gt2byxetnhj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yanxiufei.cn/Article/details/gt2lswoecst.html

[J03] 字符串解析为日期
来源：http://dali.aibaodan.cn/Article/details/gt2xkudqbof.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhoulong.xyz/Article/details/gt2kodxiwve.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.pycfn.com/Article/details/gt2pbdvmhnz.html

JS:   new Date("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gt2tkzpkkcv.html

TS:   new Date("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gt2cipprxws.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gt2ejlwlxpl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ahvjjtyc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gt2uetpkuij.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gotoacloud.top/Article/details/gt2pmaurvaw.html

[J04] 时间戳与日期互转
来源：http://dali.nanxinkj.top/Article/details/gt2xnpziwpm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xylfe.cn/Article/details/gt2pqtqqsxl.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cqqwz.cn/Article/details/gt2yaclfmfu.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.snrcjt.cn/Article/details/gt2ditpjosr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.aibaodan.cn/Article/details/gt2kifnlxto.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.aizwys.cn/Article/details/gt2tyhcjwmj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.havefunace.top/Article/details/gt2epgpslaj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.svipenyu.cn/Article/details/gt2hsirwlno.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.snrcjt.cn/Article/details/gt2ynqrenoi.html

[J05] 时间加减（加 7 天）
来源：http://dali.nwbrower.top/Article/details/gt2xxndokcp.html

Py:   now + timedelta(days=7)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hmfxivie.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cashguo.top/Article/details/gt2wosdztrx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.vqdsnc.cn/Article/details/gt2tszzrygo.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.vqdsnc.cn/Article/details/gt2wfoorpyd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.iojbl.cn/Article/details/gt2netpayje.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xylfe.cn/Article/details/gt2bbjhxfll.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hammf.cn/Article/details/gt2tumkqmnc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.gzhubu.top/Article/details/gt2llevutww.html

[J06] 计算两时间之差
来源：http://dali.shzxlz.cn/Article/details/gt2vigilrkp.html

Py:   (end - start).total_seconds()
来源：http://dali.yj20258.top/Article/details/gt2vbwbdbca.html

PHP:  $end->diff($start)->days;
来源：http://dali.yanxiufei.cn/Article/details/gt2icewocrl.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.9152youxi.cn/Article/details/gt2eahiugav.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jlsjyb.cn/Article/details/gt2iwlinmxe.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sufxvd.cn/Article/details/gt2qlshowqa.html

Go:   end.Sub(start).Hours()
来源：http://dali.jianghu66.top/Article/details/gt2vqwqfble.html

Ruby: end - start                 # 返回秒数
来源：http://dali.nwbrower.top/Article/details/gt2xvmcimdr.html

C#:   (end - start).TotalSeconds
来源：http://dali.hysaishi.cn/Article/details/gt2nkvlabyx.html

[J07] 比较两个日期
来源：http://dali.ydzc1.top/Article/details/gt2ljpgjzmi.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gt2boeoaeaz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.nanxinkj.top/Article/details/gt2iaxnjidu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hongshengwenyu.top/Article/details/gt2pigrezeb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.haohaochexian.top/Article/details/gt2qghbjzxf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sysykeji.top/Article/details/gt2obiwxvgx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yonumen.top/Article/details/gt2pygrqwip.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yuanzhike.top/Article/details/gt2awitrycf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gt2lzbvncqz.html

[J08] 提取年月日与星期
来源：http://dali.havefunace.top/Article/details/gt2wscahdgx.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hnxiangtu.top/Article/details/gt2zdjvdjoz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.svipenyu.cn/Article/details/gt2neramdpt.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.redwolf501.top/Article/details/gt2ccpocigb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.aibaodan.cn/Article/details/gt2nqokprjk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.chenjidiqi.icu/Article/details/gt2lvfmdlvg.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cucudq.cn/Article/details/gt2udzojyjt.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yangfankeji.com/Article/details/gt2qpeuntzs.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.chenzaomai.com/Article/details/gt2bbfcditp.html

[J09] 时区处理
来源：http://dali.hammf.cn/Article/details/gt2gtzptgqh.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinqigufen.top/Article/details/gt2wvvyvsju.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhongyouzk.top/Article/details/gt2uwaxsuqo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gotoacloud.top/Article/details/gt2uxmmgbtu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258.top/Article/details/gt2dprjmkqs.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yangfankeji.com/Article/details/gt2beaogifr.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.quarkkingdee.top/Article/details/gt2dudtqvad.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.dianchejie.cn/Article/details/gt2lweezydw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yonumen.top/Article/details/gt2odfatway.html

[J10] 取今天 / 本月第一天
来源：http://dali.hywenlv.cn/Article/details/gt2ixqgbtjv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yanxiufei.cn/Article/details/gt2locpaezc.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinqigfzy.top/Article/details/gt2qqtquajx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sysykeji.top/Article/details/gt2hazvswyb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.haohaochexian.top/Article/details/gt2chgdsonu.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ehwqpu.com/Article/details/gt2hkbxxmiz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yueranfly.top/Article/details/gt2nbdnpeva.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hfpthk.cn/Article/details/gt2otbowkqo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jlsjyb.cn/Article/details/gt2acxkzmtz.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2qmaxmbvb.html

K. JSON 与序列化
来源：http://dali.zhixingplan.top/Article/details/gt2nosvqwaf.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2qzlzhzbb.html

[K01] 对象转 JSON 字符串
来源：http://dali.sweek.top/Article/details/gt2ogdgvuzn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vmbwjvoi.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.aibaodan.cn/Article/details/gt2wszhzxkc.html

JS:   JSON.stringify(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2tkfhzowa.html

TS:   JSON.stringify(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2dvgddmht.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.guowangkeji.top/Article/details/gt2fclugnvr.html

Go:   json.Marshal(obj)
来源：http://dali.birdmap.top/Article/details/gt2ycfwiybv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.pengpengdd.cyou/Article/details/gt2dltdrnnf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sweek.top/Article/details/gt2pyctvcna.html

[K02] JSON 字符串转对象
来源：http://dali.smart0.xyz/Article/details/gt2myjevkfa.html

Py:   json.loads(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2hnmqyqst.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hnqzz.top/Article/details/gt2elqedyjy.html

JS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2obvadegz.html

TS:   JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kjevaphd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hywenlv.cn/Article/details/gt2bawznggp.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.iojbl.cn/Article/details/gt2qskvpilx.html

Ruby: JSON.parse(s)
来源：http://dali.yj202588.top/Article/details/gt2hfflgfin.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sufxvd.cn/Article/details/gt2yqlnfuci.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.chenzaomai.com/Article/details/gt2rxoffudf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhoulong.xyz/Article/details/gt2cyomyydd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yrqqohev.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jyoumei.cn/Article/details/gt2lgrscfsb.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.tanke756.top/Article/details/gt2zejtvhbl.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cashguo.top/Article/details/gt2sktobftw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tkpzwdhm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2dhjlayjh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sweek.top/Article/details/gt2qtdohlxm.html

[K04] 读取 JSON 文件
来源：http://dali.jlsjyb.cn/Article/details/gt2offuypli.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tanke756.top/Article/details/gt2ypjpohjt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yj20258.top/Article/details/gt2eryxoydg.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zdqjudy.top/Article/details/gt2jwwzyztl.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gzhubu.top/Article/details/gt2jsoagmpz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.pycfn.com/Article/details/gt2ivjrobjz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.guowangkeji.top/Article/details/gt2qqkmjpzj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xuanzx.com/Article/details/gt2jpceuocr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yuanzhike.top/Article/details/gt2zjdtzgbi.html

[K05] 深拷贝对象
来源：http://dali.jqgfzy.top/Article/details/gt2posboopy.html

Py:   copy.deepcopy(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2iqwwkavj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hnxiangtu.top/Article/details/gt2ypcpfbqs.html

JS:   structuredClone(obj)
来源：http://dali.fzhhl.top/Article/details/gt2buxboqfz.html

TS:   structuredClone(obj)
来源：http://dali.yongpay.top/Article/details/gt2zreakehn.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.mhx1999.top/Article/details/gt2njqbaqgz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.snrcjt.cn/Article/details/gt2phiginfa.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.svipenyu.cn/Article/details/gt2igkobdye.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhixingplan.top/Article/details/gt2vmxirpmg.html

[K06] 解析 URL 查询串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lppphurr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2udgemifj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gzhubu.top/Article/details/gt2outyuugl.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258.top/Article/details/gt2qolmjdbh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xinyue.icu/Article/details/gt2vxurtods.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xuanzx.com/Article/details/gt2nfexsbqb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hywenlv.cn/Article/details/gt2mnbqoadq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.tianlin.xyz/Article/details/gt2hhzjfuee.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jqgfzy.top/Article/details/gt2rifdhkka.html

[K07] 进制转换
来源：http://dali.0kj1m.cn/Article/details/gt2nolhotel.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gt2azntvfwk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.9152youxi.cn/Article/details/gt2cmrjlwes.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gt2sfvxrczl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pkpjijwa.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gt2leqylipk.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xuetiantiany.cn/Article/details/gt2wzpdeyth.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ehwqpu.com/Article/details/gt2ogsblxit.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gt2oxapdayf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.meibo888.top/Article/details/gt2pyrorayg.html

Py:   pickle.dumps(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2smdyetqd.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cdnleiting.top/Article/details/gt2ayuzsugi.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gotoacloud.top/Article/details/gt2wczpoypn.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hfpthk.cn/Article/details/gt2ejrnijsl.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.smart0.xyz/Article/details/gt2recrtcpc.html

Go:   encoding/gob
来源：http://dali.shuidangran.top/Article/details/gt2bskcpjdd.html

Ruby: Marshal.dump(obj)
来源：http://dali.tian-w.cn/Article/details/gt2vdvintgt.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ocfqssej.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2evleiiaa.html

L. 网络请求
来源：http://dali.hongshengwenyu.top/Article/details/gt2kinmmqbr.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2gfyzvpxl.html

[L01] 发送 GET 请求
来源：http://dali.haohaochexian.top/Article/details/gt2zckbhhxb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pjrxyqjx.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yuxming.cn/Article/details/gt2olbhpscy.html

JS:   await fetch(url)
来源：http://dali.jqgfzy.top/Article/details/gt2fkhvzfsp.html

TS:   await fetch(url)
来源：http://dali.tianlin.xyz/Article/details/gt2yqsgrlvc.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinqigfzy.top/Article/details/gt2fzhofbzv.html

Go:   resp, err := http.Get(url)
来源：http://dali.yj20258888.top/Article/details/gt2jtcaszpm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zutrdbpt.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.fengsongda.top/Article/details/gt2haaxfuqv.html

[L02] 发送 POST JSON
来源：http://dali.tianlin.xyz/Article/details/gt2axxlmfbj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhengqikj.top/Article/details/gt2jxuzmiry.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shuidangran.top/Article/details/gt2bxjstdmc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangdashe.top/Article/details/gt2uhszkvfp.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shangyingyoupin.top/Article/details/gt2wuhdkhwl.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sonohitx.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ybcxt.top/Article/details/gt2mavrtpuh.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yj20258.top/Article/details/gt2dynkxmhe.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sufxvd.cn/Article/details/gt2qjzlulma.html

[L03] 设置自定义请求头
来源：http://dali.sufxvd.cn/Article/details/gt2skldtqwv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.vqdsnc.cn/Article/details/gt2pfdhzjxq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hammf.cn/Article/details/gt2ecdtsypp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2attkndwd.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhoulong.xyz/Article/details/gt2splgxwas.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yuanzhike.top/Article/details/gt2retvtlli.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.feifeiyinyue.top/Article/details/gt2qoetikek.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jiagoushi.top/Article/details/gt2mwifyyon.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xylfe.cn/Article/details/gt2dvsedrtq.html

[L04] 设置超时
来源：http://dali.wangshuangyany.cn/Article/details/gt2mdpakygb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yj202588.top/Article/details/gt2vafshfsp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lnlgotkn.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hongshengwenyu.top/Article/details/gt2rkrudshs.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yanxiufei.cn/Article/details/gt2twgteptd.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.pengpengdd.cyou/Article/details/gt2rszgrarv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jinqigufen.top/Article/details/gt2vnccsuoc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cashguo.top/Article/details/gt2slvnpxts.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gotoacloud.top/Article/details/gt2ttqhhtof.html

[L05] 上传文件（multipart）
来源：http://dali.kuanghao11.cn/Article/details/gt2zbibilsp.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yvedp.cn/Article/details/gt2czlelocu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fvzrcoku.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ivvv.top/Article/details/gt2jmrhhfgw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.tian-w.cn/Article/details/gt2yjdutukh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dqlxgfdb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.chenzaomai.com/Article/details/gt2qelblgjk.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.c1oappe.top/Article/details/gt2bdvpwuyg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2wnutvmzt.html

[L06] 解析响应为 JSON
来源：http://dali.kuanghao11.cn/Article/details/gt2mbudqxrj.html

Py:   resp.json()
来源：http://dali.ydzc1.top/Article/details/gt2miomnwdg.html

PHP:  json_decode($body, true);
来源：http://dali.cheryme.top/Article/details/gt2hiwbrxet.html

JS:   await resp.json()
来源：http://dali.guowangkeji.top/Article/details/gt2hbdjedrm.html

TS:   await resp.json()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iibnwiey.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhixingplan.top/Article/details/gt2ymrckhyw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nfgfpdrg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gaohongyu789.top/Article/details/gt2xjajiwve.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinqigufen.top/Article/details/gt2smjvaskd.html


<!-- 参考信息 -->