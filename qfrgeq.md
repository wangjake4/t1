代发 wailian999

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jyoumei.cn/Article/details/gt2dwhnmwyc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.meibo888.top/Article/details/gt2nogqinpd.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2plzbdxdc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.316326.xyz/Article/details/gt2glpfwaca.html

[I02] 提取所有匹配
来源：http://dali.jianghu66.top/Article/details/gt2csolfceb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cheryme.top/Article/details/gt2vjovzism.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cqqwz.cn/Article/details/gt2bvmqqgnp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vcdqsxco.html

TS:   s.match(/\d+/g)
来源：http://dali.yueranfly.top/Article/details/gt2cfudyrdr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cdnleiting.top/Article/details/gt2wttnvqwo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.guowangkeji.top/Article/details/gt2lzxjwcmx.html

Ruby: s.scan(/\d+/)
来源：http://dali.cqqwz.cn/Article/details/gt2xlpigwnn.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sufxvd.cn/Article/details/gt2lhbawqjy.html

[I03] 提取捕获分组
来源：http://dali.xziqi.cn/Article/details/gt2cjjhigxz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.havefunace.top/Article/details/gt2wzvhildb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.chenjidiqi.icu/Article/details/gt2rbpdrhvy.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hfpthk.cn/Article/details/gt2hocpypqa.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zdqjudy.top/Article/details/gt2bbbxwxtm.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.mhx1999.top/Article/details/gt2ajqgfkbq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yanxiufei.cn/Article/details/gt2eaykrdlw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qhiuezyk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vbxifbql.html

[I04] 正则替换
来源：http://dali.aizwys.cn/Article/details/gt2qniztvrs.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yj202588.top/Article/details/gt2ctgtfmha.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cucudq.cn/Article/details/gt2nmwjmlue.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.wangshuangyany.cn/Article/details/gt2hbvgnkkk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ybcxt.top/Article/details/gt2rkzocikl.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.fzhhl.top/Article/details/gt2vwajkfci.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.birdmap.top/Article/details/gt2kqzvjref.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.haohaochexian.top/Article/details/gt2ctrpgzin.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hnqzz.top/Article/details/gt2whppnebs.html

[I05] 按正则拆分
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yogucbqm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cdnleiting.top/Article/details/gt2obscvqpq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.daxiang520.top/Article/details/gt2ktztqbyx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jqgfzy.top/Article/details/gt2dfielpvi.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wvjkwhtw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jianghu66.top/Article/details/gt2nrfrviwn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cdnleiting.top/Article/details/gt2yonktvld.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gogol.net.cn/Article/details/gt2vgjopohb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yongpay.top/Article/details/gt2lcaihyjp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.nanxinkj.top/Article/details/gt2gorplygd.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gt2erwrlcwe.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.tian-w.cn/Article/details/gt2ylbkmxes.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shangyingyoupin.top/Article/details/gt2xtoklwag.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cashguo.top/Article/details/gt2zawiwcxj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.iojbl.cn/Article/details/gt2yizfzqfc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pcrjujiz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhiwuduotai.top/Article/details/gt2mtxbhteu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.fengsongda.top/Article/details/gt2rqgwmblh.html

[I07] 忽略大小写与多行模式
来源：http://dali.kuanghao11.cn/Article/details/gt2imnxtkal.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.fzhhl.top/Article/details/gt2mznucjly.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sweek.top/Article/details/gt2xeftgvwh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.kuanghao11.cn/Article/details/gt2uyqzprbm.html

TS:   /error/gim
来源：http://dali.feifeiyinyue.top/Article/details/gt2hwzyjvba.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yueranfly.top/Article/details/gt2ojhfbamo.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.316326.xyz/Article/details/gt2sjnyndai.html

Ruby: s.scan(/error/i)
来源：http://dali.chenzaomai.com/Article/details/gt2gxhvgbac.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.0kj1m.cn/Article/details/gt2plksalfn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bhtplcfk.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yongpay.top/Article/details/gt2kmzghkrv.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.smart0.xyz/Article/details/gt2vdkikyby.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.svipenyu.cn/Article/details/gt2izbgtvpt.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258888.top/Article/details/gt2fxidtzjo.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jiagoushi.top/Article/details/gt2pwkpfsla.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.bjfxy.top/Article/details/gt2hmsgerfb.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xylfe.cn/Article/details/gt2cwkpwxfe.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hywenlv.cn/Article/details/gt2gxxqgrrj.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2vxppiegb.html

J. 日期与时间
来源：http://dali.quarkkingdee.top/Article/details/gt2gubvpilc.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2zmvjlfui.html

[J01] 获取当前时间
来源：http://dali.tian-w.cn/Article/details/gt2mawrgsre.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shangyingyoupin.top/Article/details/gt2djtsnuqf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.nwbrower.top/Article/details/gt2gnqinpmc.html

JS:   new Date();  Date.now()
来源：http://dali.wangdashe.top/Article/details/gt2lsqeuonk.html

TS:   new Date();  Date.now()
来源：http://dali.tianlin.xyz/Article/details/gt2pggdivka.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hnxiangtu.top/Article/details/gt2gkefjalb.html

Go:   time.Now()
来源：http://dali.chenlongwang.top/Article/details/gt2diivekaq.html

Ruby: Time.now
来源：http://dali.nwbrower.top/Article/details/gt2tlxuctiv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.smart0.xyz/Article/details/gt2dvsozzrj.html

[J02] 格式化输出
来源：http://dali.smart0.xyz/Article/details/gt2guksnyit.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shangyingyoupin.top/Article/details/gt2gizshbvo.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhoulong.xyz/Article/details/gt2gscuyvhs.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.tanke756.top/Article/details/gt2wtpzmqpo.html

TS:   d.toISOString()
来源：http://dali.quarkkingdee.top/Article/details/gt2aagpygvx.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cashguo.top/Article/details/gt2zmejiysm.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.guannengcc.top/Article/details/gt2ltdplfbi.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.iojbl.cn/Article/details/gt2vfikorkv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.kuanghao11.cn/Article/details/gt2kvkwvdpu.html

[J03] 字符串解析为日期
来源：http://dali.gzhubu.top/Article/details/gt2hbngzkzf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xylfe.cn/Article/details/gt2uqseaozx.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhoulong.xyz/Article/details/gt2dyjdprdp.html

JS:   new Date("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gt2bysgyyps.html

TS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2cudkuplz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gt2rtlksimp.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gt2zmglddlq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gt2hicrlpmj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mkyxyzzy.html

[J04] 时间戳与日期互转
来源：http://dali.zhijiandao.cn/Article/details/gt2dlnzsxaq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.fzhhl.top/Article/details/gt2wpzbninc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sweek.top/Article/details/gt2bndumyhn.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xuanzx.com/Article/details/gt2ueldsjzm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sysykeji.top/Article/details/gt2jdqyhlyz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gogol.net.cn/Article/details/gt2bvkjebrf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cdnleiting.top/Article/details/gt2azwpgkes.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.daxiang520.top/Article/details/gt2qsktvcpe.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yuxming.cn/Article/details/gt2kexhryfl.html

[J05] 时间加减（加 7 天）
来源：http://dali.wangshuangyany.cn/Article/details/gt2gmybucxj.html

Py:   now + timedelta(days=7)
来源：http://dali.tianlin.xyz/Article/details/gt2gtiicsan.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wypgyijo.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hywenlv.cn/Article/details/gt2dwihgaop.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shzxlz.cn/Article/details/gt2xslejeqr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2emeyrjpj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yueranfly.top/Article/details/gt2doyqmtxe.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhongyouzk.top/Article/details/gt2hdtlntfl.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kqiyoenx.html

[J06] 计算两时间之差
来源：http://dali.gogol.net.cn/Article/details/gt2delsunvz.html

Py:   (end - start).total_seconds()
来源：http://dali.birdmap.top/Article/details/gt2eaaslywq.html

PHP:  $end->diff($start)->days;
来源：http://dali.ppjwa.cn/Article/details/gt2ferxhdjs.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yuanzhike.top/Article/details/gt2mwdwfgfd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.andypj.xyz/Article/details/gt2cqbbmztj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhengqikj.top/Article/details/gt2znasooad.html

Go:   end.Sub(start).Hours()
来源：http://dali.shangyingyoupin.top/Article/details/gt2knltfoko.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yuanzhike.top/Article/details/gt2airoohkl.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nxfegzus.html

[J07] 比较两个日期
来源：http://dali.chenjidiqi.icu/Article/details/gt2gkdltjqz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sysykeji.top/Article/details/gt2jhgqsuff.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinqigfzy.top/Article/details/gt2cwrmnbtu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yangfankeji.com/Article/details/gt2jezxmubb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.snrcjt.cn/Article/details/gt2tuujeylw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jlsjyb.cn/Article/details/gt2ymfyumad.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.fzhhl.top/Article/details/gt2wttwvzob.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jyoumei.cn/Article/details/gt2mnkpntbl.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gt2cufhsfii.html

[J08] 提取年月日与星期
来源：http://dali.jinqigufen.top/Article/details/gt2tvnldhus.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.nanxuanxn.top/Article/details/gt2nzcbenpa.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zycfv.cn/Article/details/gt2fmklyath.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.fengsongda.top/Article/details/gt2amiatyks.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yvedp.cn/Article/details/gt2iyoqleqk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zycfv.cn/Article/details/gt2phjqmalr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.chenjidiqi.icu/Article/details/gt2yqhgihsj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shuidangran.top/Article/details/gt2wbwszyaq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oahiokrl.html

[J09] 时区处理
来源：http://dali.andypj.xyz/Article/details/gt2pjrmicvs.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xuetiantiany.cn/Article/details/gt2vcltcjga.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.wangdashe.top/Article/details/gt2ixhwyasr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tian-w.cn/Article/details/gt2nrskurpb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.feifeiyinyue.top/Article/details/gt2eievpnph.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.mhx1999.top/Article/details/gt2mubjpunh.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.pengpengdd.cyou/Article/details/gt2cbziydch.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nanxinkj.top/Article/details/gt2nyrpmqfp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shzxlz.cn/Article/details/gt2veptziqi.html

[J10] 取今天 / 本月第一天
来源：http://dali.iojbl.cn/Article/details/gt2forvjxtp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tian-w.cn/Article/details/gt2bbjepwtt.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gotoacloud.top/Article/details/gt2gxeotvuz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yueranfly.top/Article/details/gt2phgyjtsb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gt2fkumqspe.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yongpay.top/Article/details/gt2yzwfylsu.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.tanke756.top/Article/details/gt2oiopmgfo.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shangyingyoupin.top/Article/details/gt2bhetqymj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hysaishi.cn/Article/details/gt2acgrjbjr.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2yazakqdu.html

K. JSON 与序列化
来源：http://dali.c1oappe.top/Article/details/gt2fouvllbz.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2cyxrwhvj.html

[K01] 对象转 JSON 字符串
来源：http://dali.daxiang520.top/Article/details/gt2qvmfpvmc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2meoxxyzl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.tian-w.cn/Article/details/gt2slgfmdzy.html

JS:   JSON.stringify(obj)
来源：http://dali.ydzc1.top/Article/details/gt2qckwtdif.html

TS:   JSON.stringify(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2zbmbudax.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.aizwys.cn/Article/details/gt2olokjrso.html

Go:   json.Marshal(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2empobywj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.svipenyu.cn/Article/details/gt2pmnxocfc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2vzrqxuhy.html

[K02] JSON 字符串转对象
来源：http://dali.hongshengwenyu.top/Article/details/gt2gqkeootx.html

Py:   json.loads(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2knlimfdg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenjidiqi.icu/Article/details/gt2wbvlhxxc.html

JS:   JSON.parse(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2kywyyhcp.html

TS:   JSON.parse(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oudopapn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hywenlv.cn/Article/details/gt2ylnvsnko.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xinyue.icu/Article/details/gt2fxmowrqp.html

Ruby: JSON.parse(s)
来源：http://dali.9152youxi.cn/Article/details/gt2cvmrmqby.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gbbhkvgu.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sweek.top/Article/details/gt2qqehfsfa.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.andypj.xyz/Article/details/gt2fwadvsxn.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.andypj.xyz/Article/details/gt2hrlrioir.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ljwuibmm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.dashuyun.cn/Article/details/gt2wgmqpnca.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sqfpmdss.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.snrcjt.cn/Article/details/gt2rbtajiqf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shuidangran.top/Article/details/gt2kxolnuqm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.9152youxi.cn/Article/details/gt2blygjxge.html

[K04] 读取 JSON 文件
来源：http://dali.jlsjyb.cn/Article/details/gt2ffxvrezl.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cqqwz.cn/Article/details/gt2mqjfwumq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hongshengwenyu.top/Article/details/gt2hyiuqewt.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zycfv.cn/Article/details/gt2igozfvdh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sysykeji.top/Article/details/gt2nvpcndbb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.birdmap.top/Article/details/gt2weniqwcp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gotoacloud.top/Article/details/gt2ojpyilob.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jiagoushi.top/Article/details/gt2uzgmzggv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nanxinkj.top/Article/details/gt2fqnwqidi.html

[K05] 深拷贝对象
来源：http://dali.hongshengwenyu.top/Article/details/gt2cldbjhah.html

Py:   copy.deepcopy(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2mxyncuup.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sweek.top/Article/details/gt2mwoijgih.html

JS:   structuredClone(obj)
来源：http://dali.316326.xyz/Article/details/gt2ywywcyli.html

TS:   structuredClone(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2fnnutyti.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.svipenyu.cn/Article/details/gt2rquhhhio.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hysaishi.cn/Article/details/gt2ptgjnvqd.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xinyue.icu/Article/details/gt2qypvzdvb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.chenzaomai.com/Article/details/gt2vrhlmkif.html

[K06] 解析 URL 查询串
来源：http://dali.shzxlz.cn/Article/details/gt2weoiprxu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hammf.cn/Article/details/gt2izaqsblq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jqgfzy.top/Article/details/gt2zjxaqtgx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenjidiqi.icu/Article/details/gt2swiclsku.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ppjwa.cn/Article/details/gt2dbaletoy.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhoulong.xyz/Article/details/gt2hlcqofoc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hnxiangtu.top/Article/details/gt2bekrzlmy.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wvvryqzl.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.guannengcc.top/Article/details/gt2magcqmsy.html

[K07] 进制转换
来源：http://dali.ppjwa.cn/Article/details/gt2svrpqkpl.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gt2kxhbxbbt.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cheryme.top/Article/details/gt2jdtzunsi.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gt2mnulvvgf.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tgbtocrj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gt2bhyoftrp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ppjwa.cn/Article/details/gt2kmslqguo.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.svipenyu.cn/Article/details/gt2oltkqolw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.birdmap.top/Article/details/gt2wpxhgqqj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cqqwz.cn/Article/details/gt2ablxphwj.html

Py:   pickle.dumps(obj)
来源：http://dali.andypj.xyz/Article/details/gt2udmvivej.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.fengsongda.top/Article/details/gt2ajyaywrw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yangfankeji.com/Article/details/gt2qygriiue.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.guannengcc.top/Article/details/gt2lhwwomfk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jianghu66.top/Article/details/gt2sghtrbsc.html

Go:   encoding/gob
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hzkfuifn.html

Ruby: Marshal.dump(obj)
来源：http://dali.316326.xyz/Article/details/gt2bgkpdduj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jqgfzy.top/Article/details/gt2nacllgct.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2ngluhzoa.html

L. 网络请求
来源：http://dali.9152youxi.cn/Article/details/gt2cjkgidrb.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2wephpctd.html

[L01] 发送 GET 请求
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2trcigxyy.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cdnleiting.top/Article/details/gt2fvxnirlj.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yueranfly.top/Article/details/gt2aoklfsyu.html

JS:   await fetch(url)
来源：http://dali.sweek.top/Article/details/gt2jplewabg.html

TS:   await fetch(url)
来源：http://dali.ybcxt.top/Article/details/gt2oxfgdfdr.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yvedp.cn/Article/details/gt2huglrmgw.html

Go:   resp, err := http.Get(url)
来源：http://dali.nanxinkj.top/Article/details/gt2ddwxkvwg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.dianchejie.cn/Article/details/gt2atdqchis.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hnqzz.top/Article/details/gt2ybqfzxpl.html

[L02] 发送 POST JSON
来源：http://dali.haohaochexian.top/Article/details/gt2dqkdgviv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.sxryk.cn/Article/details/gt2ozgdozum.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.gotoacloud.top/Article/details/gt2obolsbtz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenlongwang.top/Article/details/gt2zjcxbstv.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.birdmap.top/Article/details/gt2clohqofn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.9152youxi.cn/Article/details/gt2glnsjrjr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.nanxuanxn.top/Article/details/gt2yqwvctqh.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.gzhubu.top/Article/details/gt2anjrmzhb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hywenlv.cn/Article/details/gt2kskpayvy.html

[L03] 设置自定义请求头
来源：http://dali.zdqjudy.top/Article/details/gt2hgmgsecb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hnxiangtu.top/Article/details/gt2egwgpyrd.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jianghu66.top/Article/details/gt2qsmgxkwi.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kjmwmbuj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pljwqgqq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sweek.top/Article/details/gt2ofqghmrg.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gzhubu.top/Article/details/gt2isbrfkyd.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ybcxt.top/Article/details/gt2uchsuxir.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.kuanghao11.cn/Article/details/gt2gnjvtuwa.html

[L04] 设置超时
来源：http://dali.kuanghao11.cn/Article/details/gt2izedzseu.html

Py:   requests.get(url, timeout=5)
来源：http://dali.sysykeji.top/Article/details/gt2mgymgpkd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sufxvd.cn/Article/details/gt2mlwvsoru.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hammf.cn/Article/details/gt2malrxezv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xziqi.cn/Article/details/gt2zuapkftn.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gzhubu.top/Article/details/gt2wntlihyf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gogol.net.cn/Article/details/gt2zjppayof.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hnxiangtu.top/Article/details/gt2nomviqzb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenjidiqi.icu/Article/details/gt2wprlbbuc.html

[L05] 上传文件（multipart）
来源：http://dali.jlsjyb.cn/Article/details/gt2dbahrums.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qfafatww.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zycfv.cn/Article/details/gt2nujlufpf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuetiantiany.cn/Article/details/gt2ymyevpea.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shuidangran.top/Article/details/gt2bvjruicd.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xinyue.icu/Article/details/gt2qyfanwlc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.pycfn.com/Article/details/gt2difaqqcz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.chenlongwang.top/Article/details/gt2mlvlmbhn.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mcibnyqv.html

[L06] 解析响应为 JSON
来源：http://dali.sysykeji.top/Article/details/gt2nsuurfjj.html

Py:   resp.json()
来源：http://dali.daxiang520.top/Article/details/gt2uryeubco.html

PHP:  json_decode($body, true);
来源：http://dali.9152youxi.cn/Article/details/gt2lefxzzfi.html

JS:   await resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gt2biauiqds.html

TS:   await resp.json()
来源：http://dali.aizwys.cn/Article/details/gt2mcbutjrx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.vqdsnc.cn/Article/details/gt2navxkizc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shuidangran.top/Article/details/gt2mtarykpa.html

Ruby: JSON.parse(resp.body)
来源：http://dali.dashuyun.cn/Article/details/gt2ttzpunym.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yj20258.top/Article/details/gt2jjmopwdw.html

[L07] 处理 HTTP 状态码
来源：http://dali.sweek.top/Article/details/gt2hihplsyp.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.aibaodan.cn/Article/details/gt2ituejajg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jyoumei.cn/Article/details/gt2cwozcuat.html

JS:   resp.ok;  resp.status
来源：http://dali.snrcjt.cn/Article/details/gt2weqgnhou.html

TS:   resp.ok;  resp.status
来源：http://dali.hongshengwenyu.top/Article/details/gt2lgitoeeu.html

Java: resp.statusCode()
来源：http://dali.svipenyu.cn/Article/details/gt2zibmonnf.html

Go:   resp.StatusCode
来源：http://dali.jianghu66.top/Article/details/gt2jglayoxa.html

Ruby: resp.code.to_i
来源：http://dali.yuanzhike.top/Article/details/gt2ifjchlun.html


<!-- 参考信息 -->