代发 wailian999

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtgsaugnli.html

I. 正则表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcivxapbc.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtbhsdkkxv.html

[I01] 判断是否匹配
来源：http://dali.xinyue.icu/Article/details/gtvxgkxcqa.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sysykeji.top/Article/details/gtynbnmqar.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtfflpjmey.html

JS:   /\d+/.test(s)
来源：http://dali.nanxuanxn.top/Article/details/gtfvwmfeha.html

TS:   /\d+/.test(s)
来源：http://dali.haohaochexian.top/Article/details/gtvrfddzdh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.redwolf501.top/Article/details/gtpftukznh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sxryk.cn/Article/details/gtmvwoqwlv.html

Ruby: s.match?(/\d+/)
来源：http://dali.zycfv.cn/Article/details/gtdqdtfvdc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.bjfxy.top/Article/details/gtjbguncws.html

[I02] 提取所有匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtqccazcaw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmzpwesqc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.tian-w.cn/Article/details/gtbrrzfgnd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.dashuyun.cn/Article/details/gtbetlxdoe.html

TS:   s.match(/\d+/g)
来源：http://dali.0kj1m.cn/Article/details/gtruezjqhn.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yuxming.cn/Article/details/gtkgzhojbo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zdqjudy.top/Article/details/gtexqgxktm.html

Ruby: s.scan(/\d+/)
来源：http://dali.redwolf501.top/Article/details/gtnpikstel.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yongpay.top/Article/details/gtrufvbiau.html

[I03] 提取捕获分组
来源：http://dali.kuanghao11.cn/Article/details/gtagnsscns.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.tian-w.cn/Article/details/gthskxcsfx.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xuetiantiany.cn/Article/details/gtbengbmdx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.quarkkingdee.top/Article/details/gtypmudpqw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yonumen.top/Article/details/gtrjjbvkit.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.mhx1999.top/Article/details/gtovnjxnam.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cheryme.top/Article/details/gtifnofaxo.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hammf.cn/Article/details/gtyiwgdfga.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shangyingyoupin.top/Article/details/gtnwdwgwlb.html

[I04] 正则替换
来源：http://dali.jinqigfzy.top/Article/details/gtnhifdnvm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdxtoyvkv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.tian-w.cn/Article/details/gtllozqqyh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cucudq.cn/Article/details/gthhrurcnv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gtsunyspmw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cdnleiting.top/Article/details/gthaadfggi.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hfpthk.cn/Article/details/gtnabqcakt.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.daria6918.cn/Article/details/gtimbdorct.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.iojbl.cn/Article/details/gtxnqfcfab.html

[I05] 按正则拆分
来源：http://dali.shanyushiyangtech.top/Article/details/gtqytdmzhv.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.tianlin.xyz/Article/details/gtmqfxcrsk.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.aibaodan.cn/Article/details/gtigevbrup.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.daria6918.cn/Article/details/gtkjgujvam.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hysaishi.cn/Article/details/gtfkrapcro.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hongshengwenyu.top/Article/details/gtajevvxtq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.nwbrower.top/Article/details/gtpsaqetae.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jqgfzy.top/Article/details/gtigqitfnv.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yonumen.top/Article/details/gthhiuyodv.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.guannengcc.top/Article/details/gtfvwltnld.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sweek.top/Article/details/gtqfifjhnc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yuanzhike.top/Article/details/gtfjyrybhy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guowangkeji.top/Article/details/gtufcghmsz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yvedp.cn/Article/details/gtclqbowwt.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.quarkkingdee.top/Article/details/gtogcibdjy.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.0kj1m.cn/Article/details/gtxvghzyac.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ehwqpu.com/Article/details/gthqhytfqb.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.meibo888.top/Article/details/gtakjnfcyk.html

[I07] 忽略大小写与多行模式
来源：http://dali.hongshengwenyu.top/Article/details/gtvuecbfla.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.nwbrower.top/Article/details/gtwdwqdtcj.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hysaishi.cn/Article/details/gtennzszpk.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.haohaochexian.top/Article/details/gtugefkvdp.html

TS:   /error/gim
来源：http://dali.daxiang520.top/Article/details/gtvyyssslw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpchzajuc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zycfv.cn/Article/details/gtaktxhehu.html

Ruby: s.scan(/error/i)
来源：http://dali.fzhhl.top/Article/details/gtmijkrzku.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.nanxuanxn.top/Article/details/gtomuruchz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gotoacloud.top/Article/details/gtihknjvcn.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.quarkkingdee.top/Article/details/gtsaaxsvdj.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.nanxuanxn.top/Article/details/gtnptnjjla.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.iojbl.cn/Article/details/gtfninmikj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yuanzhike.top/Article/details/gtqhxcotxb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.chenzaomai.com/Article/details/gtiaeciknt.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlnflbrdb.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.fzhhl.top/Article/details/gtbpmkizok.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgqyqxlfb.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtsnwrkhhv.html

J. 日期与时间
来源：http://dali.316326.xyz/Article/details/gtzacmlekc.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtlkmkbtte.html

[J01] 获取当前时间
来源：http://dali.cdnleiting.top/Article/details/gtmhltqqnh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cqqwz.cn/Article/details/gtkabxgcqa.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhoulong.xyz/Article/details/gtsrhcirzr.html

JS:   new Date();  Date.now()
来源：http://dali.9152youxi.cn/Article/details/gtivvtotmw.html

TS:   new Date();  Date.now()
来源：http://dali.yongpay.top/Article/details/gtisqriawf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.aibaodan.cn/Article/details/gtxnkvozqf.html

Go:   time.Now()
来源：http://dali.jlsjyb.cn/Article/details/gtxdheamjx.html

Ruby: Time.now
来源：http://dali.cheryme.top/Article/details/gtnihudjsn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jianghu66.top/Article/details/gtdjukpkcj.html

[J02] 格式化输出
来源：http://dali.zhoulong.xyz/Article/details/gtizguubos.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tanke756.top/Article/details/gtnuyjuhxd.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jyoumei.cn/Article/details/gtfiyplbyl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinqigufen.top/Article/details/gtunanbdvo.html

TS:   d.toISOString()
来源：http://dali.wangdashe.top/Article/details/gtxgtsrujk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nanxuanxn.top/Article/details/gtrphzeowf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhiwuduotai.top/Article/details/gtpncyhdih.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ehwqpu.com/Article/details/gtcngxpnnk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nwbrower.top/Article/details/gtoodkllgs.html

[J03] 字符串解析为日期
来源：http://dali.tanke756.top/Article/details/gttocqrkiz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yuanzhike.top/Article/details/gtrpanqycf.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jianghu66.top/Article/details/gtsrksrhif.html

JS:   new Date("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gtqsjnfsbi.html

TS:   new Date("2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gtdphfjzyo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gtagdulhow.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gtjaojtxyo.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtbmypjjtf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cheryme.top/Article/details/gttgknqpqb.html

[J04] 时间戳与日期互转
来源：http://dali.cdnleiting.top/Article/details/gtoynhfgak.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yvedp.cn/Article/details/gtisnibdhq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hammf.cn/Article/details/gtgawskism.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yuanzhike.top/Article/details/gtgvzbmrgh.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.tianlin.xyz/Article/details/gtvyvxccnk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.c1oappe.top/Article/details/gtnwafxcxw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtmunouwvr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.guowangkeji.top/Article/details/gtvsfebgrv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ehwqpu.com/Article/details/gtnllqawej.html

[J05] 时间加减（加 7 天）
来源：http://dali.havefunace.top/Article/details/gtfxovselg.html

Py:   now + timedelta(days=7)
来源：http://dali.andypj.xyz/Article/details/gtqmtxrnxf.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xziqi.cn/Article/details/gtukcerkgw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gotoacloud.top/Article/details/gtobbaoqdt.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daria6918.cn/Article/details/gtpxaoexgs.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yangfankeji.com/Article/details/gtpnvzbpbo.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yj20258.top/Article/details/gtjccnusmd.html

Ruby: Time.now + 7 * 86400
来源：http://dali.meibo888.top/Article/details/gtxtosmhyn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.aizwys.cn/Article/details/gtbxbkvhzr.html

[J06] 计算两时间之差
来源：http://dali.yonumen.top/Article/details/gtxeqreubq.html

Py:   (end - start).total_seconds()
来源：http://dali.yj20258.top/Article/details/gtpvfnmjpj.html

PHP:  $end->diff($start)->days;
来源：http://dali.daria6918.cn/Article/details/gtxymbgovv.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hywenlv.cn/Article/details/gtkkxohtrc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yvedp.cn/Article/details/gtuqiauypn.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfddwbicv.html

Go:   end.Sub(start).Hours()
来源：http://dali.xuanzx.com/Article/details/gtywvqlwnf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gotoacloud.top/Article/details/gtycqbfpjs.html

C#:   (end - start).TotalSeconds
来源：http://dali.nanxinkj.top/Article/details/gtjrdirhrt.html

[J07] 比较两个日期
来源：http://dali.tian-w.cn/Article/details/gtkpyncdwq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xuanzx.com/Article/details/gtdafbzkqp.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.aizwys.cn/Article/details/gtcypepyra.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shangyingyoupin.top/Article/details/gtwcbgvzhg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.havefunace.top/Article/details/gtmdayrokg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhijiandao.cn/Article/details/gtvoouklrg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sxryk.cn/Article/details/gtvlczekdk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gtkpdnsiry.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yvedp.cn/Article/details/gteacteqcj.html

[J08] 提取年月日与星期
来源：http://dali.jianghu66.top/Article/details/gtqyckgyeq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.vqdsnc.cn/Article/details/gtbqzlhkqt.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.meibo888.top/Article/details/gtceksccza.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jqgfzy.top/Article/details/gtupzcuwgv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gogol.net.cn/Article/details/gtaldxczvg.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhengqikj.top/Article/details/gtvkatwdcn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jqgufenzy.top/Article/details/gtqxvudtli.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sxryk.cn/Article/details/gtnjtmlqkc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.quarkkingdee.top/Article/details/gtycmlqaam.html

[J09] 时区处理
来源：http://dali.hywenlv.cn/Article/details/gtzudilaei.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sweek.top/Article/details/gtgatbztkj.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gaohongyu789.top/Article/details/gtqmswerva.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cucudq.cn/Article/details/gtziewjahl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nwbrower.top/Article/details/gtwcboeekq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.tian-w.cn/Article/details/gtuazvtxjl.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.c1oappe.top/Article/details/gtuxisamoz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jqgufenzy.top/Article/details/gtnspsplek.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenzaomai.com/Article/details/gtongvwloa.html

[J10] 取今天 / 本月第一天
来源：http://dali.nwbrower.top/Article/details/gtyjywvaiz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinqigufen.top/Article/details/gtcnuwuybx.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhixingplan.top/Article/details/gtqrpcgjls.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sxryk.cn/Article/details/gtwvbhzlta.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sweek.top/Article/details/gtrljvbwne.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xuanzx.com/Article/details/gtepmsrbdl.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zdqjudy.top/Article/details/gtuuurxzdn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yuxming.cn/Article/details/gtqevrtbox.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jqgufenzy.top/Article/details/gtrubwpxvg.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtmprkdnio.html

K. JSON 与序列化
来源：http://dali.zhengqikj.top/Article/details/gttgthjorw.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtnwsyythz.html

[K01] 对象转 JSON 字符串
来源：http://dali.ppjwa.cn/Article/details/gtdmwlmcaa.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yonumen.top/Article/details/gtzqcnijza.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gzhubu.top/Article/details/gtkettanik.html

JS:   JSON.stringify(obj)
来源：http://dali.chenlongwang.top/Article/details/gtmwmlowpy.html

TS:   JSON.stringify(obj)
来源：http://dali.pycfn.com/Article/details/gtuheqquiz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gtimldhcpx.html

Go:   json.Marshal(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmlkdtkor.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hywenlv.cn/Article/details/gtnoqtdrso.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xuanzx.com/Article/details/gtluagvabc.html

[K02] JSON 字符串转对象
来源：http://dali.fengsongda.top/Article/details/gtbkdrkcrp.html

Py:   json.loads(s)
来源：http://dali.9152youxi.cn/Article/details/gtdfsonfmj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhengqikj.top/Article/details/gthnzfdhkd.html

JS:   JSON.parse(s)
来源：http://dali.cqqwz.cn/Article/details/gthoymvlvr.html

TS:   JSON.parse(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtteylqfwe.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jlsjyb.cn/Article/details/gtkajxivfe.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hnqzz.top/Article/details/gtsbkhuqlu.html

Ruby: JSON.parse(s)
来源：http://dali.zhengqikj.top/Article/details/gtxirlbisi.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsuokrtit.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.snrcjt.cn/Article/details/gtguthwkxg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.meibo888.top/Article/details/gtvdgxdqui.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.pycfn.com/Article/details/gtbnwybimi.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnqzz.top/Article/details/gtbswcpywm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gtvufhyoed.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtfaeefnym.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ehwqpu.com/Article/details/gtehrgawap.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwjfjesxd.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shanyushiyangtech.top/Article/details/gtblijieed.html

[K04] 读取 JSON 文件
来源：http://dali.kuanghao11.cn/Article/details/gtzvwxnvfu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yonumen.top/Article/details/gtdxxxwzgq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hnxiangtu.top/Article/details/gtgtpmuobi.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.bjfxy.top/Article/details/gtgarfqpuv.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xuetiantiany.cn/Article/details/gtuykpmqmr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.0kj1m.cn/Article/details/gtmspgeaxd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlhejlqiz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjrelggpp.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yvedp.cn/Article/details/gtuhhavofz.html

[K05] 深拷贝对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdilysggd.html

Py:   copy.deepcopy(obj)
来源：http://dali.gotoacloud.top/Article/details/gtpukvenmg.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yj20258888.top/Article/details/gtpsgfblzc.html

JS:   structuredClone(obj)
来源：http://dali.hysaishi.cn/Article/details/gtdbwrdbsf.html

TS:   structuredClone(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtkuunmerb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ybcxt.top/Article/details/gtmjvbelsu.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hysaishi.cn/Article/details/gtykjymcba.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhongyouzk.top/Article/details/gteoclclrt.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteqwlnicj.html

[K06] 解析 URL 查询串
来源：http://dali.wangshuangyany.cn/Article/details/gtdtnfewsj.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shzxlz.cn/Article/details/gtadsmwasc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkybjspjo.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tanke756.top/Article/details/gtboerkevv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.svipenyu.cn/Article/details/gtmnpxrqtb.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hnqzz.top/Article/details/gtlyhrrlaq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yj20258.top/Article/details/gtogrdgjle.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gtjpwrwcue.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gtjbsfwknt.html

[K07] 进制转换
来源：http://dali.jqgufenzy.top/Article/details/gtdewzsahp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtpenufcwi.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hywenlv.cn/Article/details/gtwbxdzzxs.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtmdzluxqs.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gtemwyjxfg.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cheryme.top/Article/details/gtkxnvuqqt.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yj20258888.top/Article/details/gtdukyxfrh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.0kj1m.cn/Article/details/gteotsijus.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yongpay.top/Article/details/gtdoswdzgn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hammf.cn/Article/details/gtfvjhondt.html

Py:   pickle.dumps(obj)
来源：http://dali.ivvv.top/Article/details/gtlcislrjo.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jianghu66.top/Article/details/gtxfvdpjcn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jqgfzy.top/Article/details/gtpfuringr.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xuanzx.com/Article/details/gtcikozbcy.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.guannengcc.top/Article/details/gtmiyyxwtn.html

Go:   encoding/gob
来源：http://dali.shanyushiyangtech.top/Article/details/gtxiqlbiok.html

Ruby: Marshal.dump(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtelqvqawr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.dianchejie.cn/Article/details/gtiyrnxrtl.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtcfvyrpbz.html

L. 网络请求
来源：http://dali.snrcjt.cn/Article/details/gtfdflafhc.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtdyjgsuvo.html

[L01] 发送 GET 请求
来源：http://dali.tanke756.top/Article/details/gtnahbxusi.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yonumen.top/Article/details/gtxygvsksd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gaohongyu789.top/Article/details/gtriorxdzs.html

JS:   await fetch(url)
来源：http://dali.yueranfly.top/Article/details/gtgqkwclki.html

TS:   await fetch(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtorotuynr.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.c1oappe.top/Article/details/gtvephblbp.html

Go:   resp, err := http.Get(url)
来源：http://dali.havefunace.top/Article/details/gtmsxnolai.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jyoumei.cn/Article/details/gtlrwnahri.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sxryk.cn/Article/details/gtaooshspd.html

[L02] 发送 POST JSON
来源：http://dali.andypj.xyz/Article/details/gtbrljliej.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hywenlv.cn/Article/details/gtcaoqdmuq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yonumen.top/Article/details/gthzymnohk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzzxdhfij.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.snrcjt.cn/Article/details/gtpqspqfvw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.dashuyun.cn/Article/details/gtafxrecuh.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.quarkkingdee.top/Article/details/gtrhxmxpto.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.havefunace.top/Article/details/gtdeyzcueu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gaohongyu789.top/Article/details/gtiudmtprv.html

[L03] 设置自定义请求头
来源：http://dali.xinyue.icu/Article/details/gtiwwheerq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xziqi.cn/Article/details/gtohijctdu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xziqi.cn/Article/details/gtyynsrnlj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.andypj.xyz/Article/details/gthwhmqnfk.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.snrcjt.cn/Article/details/gtlicnstzv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.iojbl.cn/Article/details/gtumotqtmm.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.pengpengdd.cyou/Article/details/gtnfunfjcn.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.havefunace.top/Article/details/gtuwzpwlpg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.tanke756.top/Article/details/gtayzotdso.html

[L04] 设置超时
来源：http://dali.yueranfly.top/Article/details/gtcnqcjlwg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yongpay.top/Article/details/gtvyqxhmil.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shangyingyoupin.top/Article/details/gtacfapblm.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jianghu66.top/Article/details/gtdubkjvdw.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gtodvgefgl.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.snrcjt.cn/Article/details/gtefnafjmg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cheryme.top/Article/details/gtljazndgz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtudxyhjnb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jqgufenzy.top/Article/details/gtagyqyjmc.html

[L05] 上传文件（multipart）
来源：http://dali.yongpay.top/Article/details/gtjwvkuveg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nwbrower.top/Article/details/gtirmczxiu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.chenjidiqi.icu/Article/details/gtjqggnsnn.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cashguo.top/Article/details/gtfskleqnz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.smart0.xyz/Article/details/gtwpvcfvve.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.quarkkingdee.top/Article/details/gtwegmrugo.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gzhubu.top/Article/details/gtavajlszt.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hnxiangtu.top/Article/details/gtfetubcpw.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.tian-w.cn/Article/details/gtnzoctemt.html

[L06] 解析响应为 JSON
来源：http://dali.xuanzx.com/Article/details/gtrovcmmea.html

Py:   resp.json()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaqxvdjdv.html

PHP:  json_decode($body, true);
来源：http://dali.shzxlz.cn/Article/details/gtbtwgrsnc.html

JS:   await resp.json()
来源：http://dali.sysykeji.top/Article/details/gtuxeoufbf.html

TS:   await resp.json()
来源：http://dali.ybcxt.top/Article/details/gtedpnbjzj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gtaffsfysh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yj20258888.top/Article/details/gtbvidxtsu.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cucudq.cn/Article/details/gtcclzgcav.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nanxuanxn.top/Article/details/gtowirggyn.html


<!-- 参考信息 -->