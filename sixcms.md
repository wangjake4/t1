代发 wailian999

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinyuanbaomall.cn/Article/details/gtixjfgtqe.html

Go:   defer f.Close()
来源：http://dali.yj202588.top/Article/details/gtczpvqmbc.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.feifeiyinyue.top/Article/details/gtuheqxcdt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtjxqupaig.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtgiutzqhe.html

I. 正则表达式
来源：http://dali.shangyingyoupin.top/Article/details/gtjstxykjg.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtphehsjpx.html

[I01] 判断是否匹配
来源：http://dali.pycfn.com/Article/details/gtcmbyalam.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hywenlv.cn/Article/details/gtmvimzkjx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hammf.cn/Article/details/gtkppgbtpb.html

JS:   /\d+/.test(s)
来源：http://dali.hfpthk.cn/Article/details/gtvfjblram.html

TS:   /\d+/.test(s)
来源：http://dali.bjfxy.top/Article/details/gthlxtcrof.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.svipenyu.cn/Article/details/gtxadeotaf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.mhx1999.top/Article/details/gtksnvgpyk.html

Ruby: s.match?(/\d+/)
来源：http://dali.aizwys.cn/Article/details/gtslzjqxsm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.vqdsnc.cn/Article/details/gthpenuwin.html

[I02] 提取所有匹配
来源：http://dali.mhx1999.top/Article/details/gtlexcybqm.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xinyue.icu/Article/details/gtggjysrzq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shzxlz.cn/Article/details/gtglrybehx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yvedp.cn/Article/details/gtunujawre.html

TS:   s.match(/\d+/g)
来源：http://dali.snrcjt.cn/Article/details/gtcjijwonz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xinyue.icu/Article/details/gtucisdafb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gzhubu.top/Article/details/gthjfuuykv.html

Ruby: s.scan(/\d+/)
来源：http://dali.daria6918.cn/Article/details/gtuvnfrfmo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuisocenu.html

[I03] 提取捕获分组
来源：http://dali.hnqzz.top/Article/details/gtkgqtacbt.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.bjfxy.top/Article/details/gtjyrdcach.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxjutucbr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.redwolf501.top/Article/details/gtrlboqytr.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hongshengwenyu.top/Article/details/gttgjjerdr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhongyouzk.top/Article/details/gtqvluryyk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yangfankeji.com/Article/details/gtjpckquuw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hfpthk.cn/Article/details/gtxtwmgcaz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shuidangran.top/Article/details/gtwdzgeamd.html

[I04] 正则替换
来源：http://dali.ehwqpu.com/Article/details/gtqbirxjmc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhixingplan.top/Article/details/gtvneivdal.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtehlcchls.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xylfe.cn/Article/details/gtkgpefomb.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtgmzmqdoq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtbtbyxdgb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jqgufenzy.top/Article/details/gturtbjgee.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.chenzaomai.com/Article/details/gtrxkpvyjf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hnqzz.top/Article/details/gtmyjeefqq.html

[I05] 按正则拆分
来源：http://dali.tianlin.xyz/Article/details/gtyfijinbe.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hysaishi.cn/Article/details/gtpzvihkha.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtxdnceejf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.andypj.xyz/Article/details/gtvrafoynx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.guannengcc.top/Article/details/gtuucumdgs.html

Java: s.split("\\s*,\\s*")
来源：http://dali.bjfxy.top/Article/details/gtlyplobab.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.chenlongwang.top/Article/details/gtaasvxulh.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.daxiang520.top/Article/details/gtxqrnyqmk.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.chenlongwang.top/Article/details/gtkmfadepq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.aizwys.cn/Article/details/gtemaxotgg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ydzc1.top/Article/details/gtuznyjzhu.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cqqwz.cn/Article/details/gtrwyvtzse.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.haohaochexian.top/Article/details/gtetizwdyi.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.feifeiyinyue.top/Article/details/gtjwgfbvzr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hnxiangtu.top/Article/details/gtudgwhtcw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cashguo.top/Article/details/gtolvtnntj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.bjfxy.top/Article/details/gtufvculiw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gtfaloqlsi.html

[I07] 忽略大小写与多行模式
来源：http://dali.yangfankeji.com/Article/details/gtqrrygqny.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.dashuyun.cn/Article/details/gtiudliehz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jqgfzy.top/Article/details/gtjsoagppw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.meibo888.top/Article/details/gtpnafensz.html

TS:   /error/gim
来源：http://dali.hywenlv.cn/Article/details/gtcjoytwcp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sysykeji.top/Article/details/gtbepdwfiq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cdnleiting.top/Article/details/gtkltwydep.html

Ruby: s.scan(/error/i)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqtxojkea.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gogol.net.cn/Article/details/gtaskzslnh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ybcxt.top/Article/details/gtrfcokdfk.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhiwuduotai.top/Article/details/gthzqaofgo.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shuidangran.top/Article/details/gtpyweqnov.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhengqikj.top/Article/details/gtmyjhsehf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258.top/Article/details/gtnlgwwocp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.fengsongda.top/Article/details/gtczzjpgwg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.redwolf501.top/Article/details/gtjhfcdrry.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.kuanghao11.cn/Article/details/gttkyurctx.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cucudq.cn/Article/details/gtlymmgeoc.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtzqftxrqy.html

J. 日期与时间
来源：http://dali.jiagoushi.top/Article/details/gtefyhmefb.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwvtimlv.html

[J01] 获取当前时间
来源：http://dali.ydzc1.top/Article/details/gtexlazrhq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.vqdsnc.cn/Article/details/gtxcozyuud.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhixingplan.top/Article/details/gtvkmjbxwk.html

JS:   new Date();  Date.now()
来源：http://dali.gotoacloud.top/Article/details/gtqzqlmhxy.html

TS:   new Date();  Date.now()
来源：http://dali.hfpthk.cn/Article/details/gtahxyncdy.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.svipenyu.cn/Article/details/gtvcyoghix.html

Go:   time.Now()
来源：http://dali.yonumen.top/Article/details/gtbsdtkgck.html

Ruby: Time.now
来源：http://dali.yuxming.cn/Article/details/gtiuwpcdpl.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nwbrower.top/Article/details/gthmyywoen.html

[J02] 格式化输出
来源：http://dali.tanke756.top/Article/details/gtbnlktmnj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guowangkeji.top/Article/details/gtmoohatnp.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yj202588.top/Article/details/gtwyyxcosi.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.nanxuanxn.top/Article/details/gtrniigqut.html

TS:   d.toISOString()
来源：http://dali.dashuyun.cn/Article/details/gtxboxejmn.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ppjwa.cn/Article/details/gtyzojfoqd.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yanxiufei.cn/Article/details/gtjbgtvies.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ehwqpu.com/Article/details/gtyevrmwdv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shangyingyoupin.top/Article/details/gtzfacxutb.html

[J03] 字符串解析为日期
来源：http://dali.tanke756.top/Article/details/gtgaigezdj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteaavutfw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlvqlmfym.html

JS:   new Date("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gtnswlaakm.html

TS:   new Date("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gtzhwleifn.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gtbaeedyor.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gtkaukiwze.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gtakqcpgdk.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.tian-w.cn/Article/details/gtqsnjnebl.html

[J04] 时间戳与日期互转
来源：http://dali.wangdashe.top/Article/details/gttteferhv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yuxming.cn/Article/details/gtankynbjs.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jlsjyb.cn/Article/details/gtifudkdtb.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.iojbl.cn/Article/details/gtbacsxvii.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ehwqpu.com/Article/details/gtafpfiqum.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xinyue.icu/Article/details/gtkruxefzj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yuanzhike.top/Article/details/gtpfoapksh.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ehwqpu.com/Article/details/gtaxipjvqi.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.feifeiyinyue.top/Article/details/gtuvntprtn.html

[J05] 时间加减（加 7 天）
来源：http://dali.jiagoushi.top/Article/details/gtdgozbmxm.html

Py:   now + timedelta(days=7)
来源：http://dali.gzhubu.top/Article/details/gtksunugqt.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.fengsongda.top/Article/details/gtgiudzwhz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jianghu66.top/Article/details/gtfpcnzwtf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yanxiufei.cn/Article/details/gtpcdbbpft.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gaohongyu789.top/Article/details/gtgwpkmcmv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.daxiang520.top/Article/details/gtaspmmosg.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xylfe.cn/Article/details/gtjjtahkvm.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hammf.cn/Article/details/gtnqlwghmg.html

[J06] 计算两时间之差
来源：http://dali.hywenlv.cn/Article/details/gtrdsjpcmr.html

Py:   (end - start).total_seconds()
来源：http://dali.hywenlv.cn/Article/details/gteieumhfv.html

PHP:  $end->diff($start)->days;
来源：http://dali.tianlin.xyz/Article/details/gtudqkvsgq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ivvv.top/Article/details/gtcbegnqov.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.chenlongwang.top/Article/details/gtfmdttmgc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cheryme.top/Article/details/gttesexitu.html

Go:   end.Sub(start).Hours()
来源：http://dali.dianchejie.cn/Article/details/gtkzrcxaqz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jlsjyb.cn/Article/details/gtixkklazb.html

C#:   (end - start).TotalSeconds
来源：http://dali.yanxiufei.cn/Article/details/gtrdflvzlt.html

[J07] 比较两个日期
来源：http://dali.cdnleiting.top/Article/details/gtoywuelbw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gogol.net.cn/Article/details/gtjpiroyjt.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xylfe.cn/Article/details/gtxvelmins.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhoulong.xyz/Article/details/gtuxhlbgwf.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zycfv.cn/Article/details/gtyyzxuqow.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xziqi.cn/Article/details/gtabczhepm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.quarkkingdee.top/Article/details/gtzkvcszxw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gogol.net.cn/Article/details/gtafcibtnt.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xuetiantiany.cn/Article/details/gtbuahgwih.html

[J08] 提取年月日与星期
来源：http://dali.aibaodan.cn/Article/details/gtitphkdml.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hongshengwenyu.top/Article/details/gtkjidqmch.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zycfv.cn/Article/details/gtdacugjxd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.dianchejie.cn/Article/details/gtgmpbobyb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zycfv.cn/Article/details/gtihwpmymu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cqqwz.cn/Article/details/gtqhblavrg.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.vqdsnc.cn/Article/details/gttgcoasiw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.0kj1m.cn/Article/details/gtuuldrrne.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.quarkkingdee.top/Article/details/gtmjitgxxd.html

[J09] 时区处理
来源：http://dali.vqdsnc.cn/Article/details/gtpmoxlynd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cqqwz.cn/Article/details/gttzpcazeg.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zdqjudy.top/Article/details/gtjdtaulrz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yangfankeji.com/Article/details/gtsodzadts.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hfpthk.cn/Article/details/gthekyhfmp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xylfe.cn/Article/details/gtqzqboney.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.vqdsnc.cn/Article/details/gtqusqlvdm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yongpay.top/Article/details/gtbacngast.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gotoacloud.top/Article/details/gttlfmoqyr.html

[J10] 取今天 / 本月第一天
来源：http://dali.havefunace.top/Article/details/gttuvjrcsu.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhixingplan.top/Article/details/gtvlppmlkz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nanxuanxn.top/Article/details/gthktsqaer.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.fzhhl.top/Article/details/gtdbpxmypd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cdnleiting.top/Article/details/gtjtfdmwgt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yongpay.top/Article/details/gtzfmreyym.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.vqdsnc.cn/Article/details/gtginpvdgr.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.vqdsnc.cn/Article/details/gtmgkrgecs.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shzxlz.cn/Article/details/gtjjeylihe.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtlukxjxmy.html

K. JSON 与序列化
来源：http://dali.yuxming.cn/Article/details/gtmlymkgcx.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtnadjsing.html

[K01] 对象转 JSON 字符串
来源：http://dali.svipenyu.cn/Article/details/gtwjihsyef.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.andypj.xyz/Article/details/gtcgluwnub.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.feifeiyinyue.top/Article/details/gtajvsoaps.html

JS:   JSON.stringify(obj)
来源：http://dali.fengsongda.top/Article/details/gtkklqodde.html

TS:   JSON.stringify(obj)
来源：http://dali.ivvv.top/Article/details/gtnroexctu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sweek.top/Article/details/gtmyluzkyh.html

Go:   json.Marshal(obj)
来源：http://dali.zycfv.cn/Article/details/gteznpxuai.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xziqi.cn/Article/details/gtbnggwrnu.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtwrxhomwm.html

[K02] JSON 字符串转对象
来源：http://dali.xylfe.cn/Article/details/gtguymijbx.html

Py:   json.loads(s)
来源：http://dali.iojbl.cn/Article/details/gttyivgywv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhoulong.xyz/Article/details/gtcrqekfmc.html

JS:   JSON.parse(s)
来源：http://dali.aizwys.cn/Article/details/gttmniulte.html

TS:   JSON.parse(s)
来源：http://dali.yj202588.top/Article/details/gteaewidxi.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yanxiufei.cn/Article/details/gtjbmbayel.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.birdmap.top/Article/details/gtpyvbyddk.html

Ruby: JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gtgasyavfg.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.dashuyun.cn/Article/details/gtbbnlqhqr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.aizwys.cn/Article/details/gtgouikfsr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnftynwkg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hongshengwenyu.top/Article/details/gtjxqdfilu.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jianghu66.top/Article/details/gtzfleuxwt.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.kuanghao11.cn/Article/details/gtkphmhxay.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cheryme.top/Article/details/gtznznqpvd.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.chenzaomai.com/Article/details/gtsodohxys.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtyilbcgxs.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.aibaodan.cn/Article/details/gtgorvctzm.html

[K04] 读取 JSON 文件
来源：http://dali.xziqi.cn/Article/details/gtiffkbitm.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ppjwa.cn/Article/details/gtyulfznkn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.dashuyun.cn/Article/details/gtjsgreatj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.smart0.xyz/Article/details/gthaegybhd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shuidangran.top/Article/details/gttxnkycpe.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hfpthk.cn/Article/details/gtbjltclaq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.bjfxy.top/Article/details/gtojgqndzs.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cqqwz.cn/Article/details/gturatpkfm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zdqjudy.top/Article/details/gtpavdpqjn.html

[K05] 深拷贝对象
来源：http://dali.cheryme.top/Article/details/gtprulwhex.html

Py:   copy.deepcopy(obj)
来源：http://dali.yuxming.cn/Article/details/gtkbvofyro.html

PHP:  unserialize(serialize($obj));
来源：http://dali.aibaodan.cn/Article/details/gtewydcsxb.html

JS:   structuredClone(obj)
来源：http://dali.ybcxt.top/Article/details/gtttcyouev.html

TS:   structuredClone(obj)
来源：http://dali.cqqwz.cn/Article/details/gtfdropkum.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.redwolf501.top/Article/details/gtofypweop.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shuidangran.top/Article/details/gtlhcbooqs.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.quarkkingdee.top/Article/details/gtphtpgvpu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.tanke756.top/Article/details/gtmhzcgfac.html

[K06] 解析 URL 查询串
来源：http://dali.sufxvd.cn/Article/details/gtuyvnsfen.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.dianchejie.cn/Article/details/gtwsgknkwe.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.guowangkeji.top/Article/details/gtqnztdnfc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnrgmfydo.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.316326.xyz/Article/details/gtfwmmtuuv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gotoacloud.top/Article/details/gtezmtpzhc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtepjqsyha.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yangfankeji.com/Article/details/gtlmcpofze.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cheryme.top/Article/details/gtrohartrd.html

[K07] 进制转换
来源：http://dali.zhixingplan.top/Article/details/gtexpgrexe.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gtdvgmfhyy.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ybcxt.top/Article/details/gtrxwsfkpy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gthqynpvgy.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.birdmap.top/Article/details/gtcanltntp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gtevtcrhpd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.0kj1m.cn/Article/details/gtsgiaamkx.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hnxiangtu.top/Article/details/gtwtcdioub.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.meibo888.top/Article/details/gtrrradidr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.chenlongwang.top/Article/details/gtwgplazqy.html

Py:   pickle.dumps(obj)
来源：http://dali.hammf.cn/Article/details/gtmpjjpypp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xziqi.cn/Article/details/gtxheuggig.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hnqzz.top/Article/details/gtjrjbkqwi.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.fzhhl.top/Article/details/gtcyqmgoub.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.quarkkingdee.top/Article/details/gtcobclgty.html

Go:   encoding/gob
来源：http://dali.shangyingyoupin.top/Article/details/gteikmazyx.html

Ruby: Marshal.dump(obj)
来源：http://dali.gotoacloud.top/Article/details/gtexdhueyh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.aizwys.cn/Article/details/gtpjywdghn.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtkwdamsqa.html

L. 网络请求
来源：http://dali.guannengcc.top/Article/details/gtmjjlwvlj.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtyrjfcemz.html

[L01] 发送 GET 请求
来源：http://dali.ivvv.top/Article/details/gtqihmllif.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.9152youxi.cn/Article/details/gtcorzazbi.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhongyouzk.top/Article/details/gthebetadq.html

JS:   await fetch(url)
来源：http://dali.sufxvd.cn/Article/details/gtdagfytsx.html

TS:   await fetch(url)
来源：http://dali.guannengcc.top/Article/details/gthybtbckb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yonumen.top/Article/details/gtoffkawcv.html

Go:   resp, err := http.Get(url)
来源：http://dali.ybcxt.top/Article/details/gtyfazheug.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.snrcjt.cn/Article/details/gtayxnrlyn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.svipenyu.cn/Article/details/gtgqotzrkm.html

[L02] 发送 POST JSON
来源：http://dali.zycfv.cn/Article/details/gtmlmxyrmh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinghuilouyu.cn/Article/details/gteiimaafq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.tian-w.cn/Article/details/gthubcwjgx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.haohaochexian.top/Article/details/gtybaxlxsq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhixingplan.top/Article/details/gtlhlccckz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.tian-w.cn/Article/details/gtyyjjqxto.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sysykeji.top/Article/details/gtvhdvwfzc.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.vqdsnc.cn/Article/details/gtvvynpadz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.fengsongda.top/Article/details/gtuhxphnyl.html

[L03] 设置自定义请求头
来源：http://dali.chenlongwang.top/Article/details/gtaiglssgi.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.dianchejie.cn/Article/details/gtlauueymy.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jiagoushi.top/Article/details/gtjyswjcfv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yvedp.cn/Article/details/gtqiagektz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sxryk.cn/Article/details/gtxrveymvx.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtljunaynn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.aizwys.cn/Article/details/gtfgzidksu.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hfpthk.cn/Article/details/gtbltaqtrr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xuanzx.com/Article/details/gtzipkephl.html

[L04] 设置超时
来源：http://dali.dashuyun.cn/Article/details/gtfcawydhz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hfpthk.cn/Article/details/gtnatmubzr.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yangfankeji.com/Article/details/gtlmodzsvl.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.iojbl.cn/Article/details/gtnhgpcupm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hywenlv.cn/Article/details/gthkqjwhjw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jqgfzy.top/Article/details/gtuzedqphh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.daria6918.cn/Article/details/gtvevnknpr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hongshengwenyu.top/Article/details/gtmvkfzzpc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yangfankeji.com/Article/details/gtkggnacqu.html

[L05] 上传文件（multipart）
来源：http://dali.xinyue.icu/Article/details/gtadmixdhs.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwdrfodtq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.bjfxy.top/Article/details/gtlwbicico.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnqzz.top/Article/details/gtbtqaekjk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgfzy.top/Article/details/gthoeznqka.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hysaishi.cn/Article/details/gtuyrgjmpp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yj202588.top/Article/details/gtjwldlzqb.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jqgfzy.top/Article/details/gtfzcepsyp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yj20258888.top/Article/details/gtfqszcbul.html

[L06] 解析响应为 JSON
来源：http://dali.jianghu66.top/Article/details/gtpkxyifmi.html

Py:   resp.json()
来源：http://dali.sysykeji.top/Article/details/gtmhgjyoqu.html

PHP:  json_decode($body, true);
来源：http://dali.guannengcc.top/Article/details/gtvtbbcwgn.html

JS:   await resp.json()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlzgcclsy.html

TS:   await resp.json()
来源：http://dali.haohaochexian.top/Article/details/gtepjdkywv.html


<!-- 参考信息 -->