代发 wailian999

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtqxnaaprb.html

I. 正则表达式
来源：http://dali.xuetiantiany.cn/Article/details/gtcgihpihs.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtfubhsqzo.html

[I01] 判断是否匹配
来源：http://dali.zhixingplan.top/Article/details/gtbkgqngwq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.svipenyu.cn/Article/details/gtuajtxlhk.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cheryme.top/Article/details/gtuvrqkxzj.html

JS:   /\d+/.test(s)
来源：http://dali.zhengqikj.top/Article/details/gtopelxafw.html

TS:   /\d+/.test(s)
来源：http://dali.0kj1m.cn/Article/details/gtdjicgdxo.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yj202588.top/Article/details/gtzuhchywa.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.smart0.xyz/Article/details/gtcvziwknb.html

Ruby: s.match?(/\d+/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmxrswuyl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hongshengwenyu.top/Article/details/gtdmnzrclr.html

[I02] 提取所有匹配
来源：http://dali.gotoacloud.top/Article/details/gttndesvvq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.havefunace.top/Article/details/gtknfcczrz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhongyouzk.top/Article/details/gtrigxtwat.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj20258.top/Article/details/gtojbpefab.html

TS:   s.match(/\d+/g)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpbculokn.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgyndzsgh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.aibaodan.cn/Article/details/gtxjkqbtbr.html

Ruby: s.scan(/\d+/)
来源：http://dali.pycfn.com/Article/details/gtevgtfvpd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtjbawyuat.html

[I03] 提取捕获分组
来源：http://dali.cqqwz.cn/Article/details/gtxnidueyi.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cucudq.cn/Article/details/gtgrhsykaw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.havefunace.top/Article/details/gtzshfbtnc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gotoacloud.top/Article/details/gtkxdqbgzn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yj20258888.top/Article/details/gtdubpiudk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sxryk.cn/Article/details/gtuojpshto.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.andypj.xyz/Article/details/gtfqfqnmfc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jlsjyb.cn/Article/details/gtpmuwgepj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cqqwz.cn/Article/details/gtukxzjxqh.html

[I04] 正则替换
来源：http://dali.yanxiufei.cn/Article/details/gtxhnwuwyc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.redwolf501.top/Article/details/gtnuzpcpzp.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtfzgyudxc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.dianchejie.cn/Article/details/gtfxurdvnk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ehwqpu.com/Article/details/gtqpjfdhrt.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbfulewef.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jqgfzy.top/Article/details/gtbojbbclv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.9152youxi.cn/Article/details/gtbymdnvzh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.fengsongda.top/Article/details/gtymgcycla.html

[I05] 按正则拆分
来源：http://dali.xuanzx.com/Article/details/gtamfsmadk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jlsjyb.cn/Article/details/gtvtarebfs.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.daria6918.cn/Article/details/gtewaznpyw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.birdmap.top/Article/details/gtffbzaruw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gttnuhlbmy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ppjwa.cn/Article/details/gteduyhqfe.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ybcxt.top/Article/details/gtfuzgqhnu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.iojbl.cn/Article/details/gtqucnnqwd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ydzc1.top/Article/details/gtiurnqsfe.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hnqzz.top/Article/details/gttcktcpux.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gtvsdkdhkd.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yonumen.top/Article/details/gtvaocnciz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yueranfly.top/Article/details/gtmrxedgat.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxuanxn.top/Article/details/gtuujjgkij.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yangfankeji.com/Article/details/gtzetpufax.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jianghu66.top/Article/details/gtufkyfvup.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhiwuduotai.top/Article/details/gtoklstsoy.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hnxiangtu.top/Article/details/gtlzhhtvjx.html

[I07] 忽略大小写与多行模式
来源：http://dali.tian-w.cn/Article/details/gtnqacwmok.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.kuanghao11.cn/Article/details/gtstzmlqoz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hfpthk.cn/Article/details/gtdjfgldtc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.wangdashe.top/Article/details/gtlwbjquus.html

TS:   /error/gim
来源：http://dali.aibaodan.cn/Article/details/gttkmymvxl.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yonumen.top/Article/details/gtpiccqmei.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yangfankeji.com/Article/details/gtadlvcgtk.html

Ruby: s.scan(/error/i)
来源：http://dali.xziqi.cn/Article/details/gtllwfijef.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.guowangkeji.top/Article/details/gtifynryml.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtvolatndt.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhongyouzk.top/Article/details/gtyclknwmd.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhongyouzk.top/Article/details/gtmjtvytol.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pycfn.com/Article/details/gtbifzelbi.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xinyue.icu/Article/details/gtniodlfvz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yueranfly.top/Article/details/gtkcvwnjqo.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cheryme.top/Article/details/gtjdhtsoxj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.guowangkeji.top/Article/details/gtpxdsackg.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.c1oappe.top/Article/details/gtyhispmig.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtfidywvwy.html

J. 日期与时间
来源：http://dali.tianlin.xyz/Article/details/gtbkbjefgj.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtdtbxqedf.html

[J01] 获取当前时间
来源：http://dali.zdqjudy.top/Article/details/gthonjcdjk.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj20258888.top/Article/details/gtzhtbecvh.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yueranfly.top/Article/details/gtqviqvggy.html

JS:   new Date();  Date.now()
来源：http://dali.feifeiyinyue.top/Article/details/gtyyzhggpl.html

TS:   new Date();  Date.now()
来源：http://dali.xziqi.cn/Article/details/gtvetvayls.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gzhubu.top/Article/details/gtbfytbkcq.html

Go:   time.Now()
来源：http://dali.cheryme.top/Article/details/gtfqazdntg.html

Ruby: Time.now
来源：http://dali.zycfv.cn/Article/details/gthmxaovhl.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yj20258.top/Article/details/gtjbaqfbfd.html

[J02] 格式化输出
来源：http://dali.hnqzz.top/Article/details/gtkrjzatfd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tanke756.top/Article/details/gtsaaggvhs.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.chenlongwang.top/Article/details/gtnkzagrwv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.pengpengdd.cyou/Article/details/gtastkluaf.html

TS:   d.toISOString()
来源：http://dali.wangshuangyany.cn/Article/details/gtpzrsttii.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhixingplan.top/Article/details/gtudxdohel.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.kuanghao11.cn/Article/details/gtxfvflyri.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgufenzy.top/Article/details/gtjojricmc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cheryme.top/Article/details/gtljvqjoxc.html

[J03] 字符串解析为日期
来源：http://dali.jiagoushi.top/Article/details/gtcmwjojsu.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhixingplan.top/Article/details/gtznfmagcj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yongpay.top/Article/details/gtniiyvray.html

JS:   new Date("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gttdmhhqbx.html

TS:   new Date("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtxykajxms.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gtipmknkxh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gtkpnezzfs.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sweek.top/Article/details/gtadpdtlwk.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.guowangkeji.top/Article/details/gthzjrfuli.html

[J04] 时间戳与日期互转
来源：http://dali.redwolf501.top/Article/details/gtgzrzxtko.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.9152youxi.cn/Article/details/gtqnbzxumj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.haohaochexian.top/Article/details/gtderpzuzq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.mhx1999.top/Article/details/gtoquletxz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhongyouzk.top/Article/details/gtwdsaegic.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sysykeji.top/Article/details/gtnjuaadev.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cdnleiting.top/Article/details/gtynjxusop.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yj202588.top/Article/details/gtjxhhjjbh.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gtskmkuffm.html

[J05] 时间加减（加 7 天）
来源：http://dali.hammf.cn/Article/details/gtcdhvrhhj.html

Py:   now + timedelta(days=7)
来源：http://dali.cashguo.top/Article/details/gtodefebme.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhijiandao.cn/Article/details/gtmfbmboro.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigfzy.top/Article/details/gtnphkcfdn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jyoumei.cn/Article/details/gterqzzqal.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhiwuduotai.top/Article/details/gtgmgeubje.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.quarkkingdee.top/Article/details/gtjugavipo.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sufxvd.cn/Article/details/gttviqylcu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sxryk.cn/Article/details/gtnakvdhpo.html

[J06] 计算两时间之差
来源：http://dali.iojbl.cn/Article/details/gtookrifme.html

Py:   (end - start).total_seconds()
来源：http://dali.hammf.cn/Article/details/gtbveosizk.html

PHP:  $end->diff($start)->days;
来源：http://dali.sweek.top/Article/details/gtjpdpdxwj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shanyushiyangtech.top/Article/details/gtfzeevrli.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hnqzz.top/Article/details/gtoixlmkry.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.daria6918.cn/Article/details/gtxqlcipig.html

Go:   end.Sub(start).Hours()
来源：http://dali.hnqzz.top/Article/details/gtojtdocyo.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hnqzz.top/Article/details/gtmwcaunrq.html

C#:   (end - start).TotalSeconds
来源：http://dali.yuxming.cn/Article/details/gtjzwfdiyh.html

[J07] 比较两个日期
来源：http://dali.zhijiandao.cn/Article/details/gtssrcwjgf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgaluijpk.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sysykeji.top/Article/details/gtgxmsoqaq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.fzhhl.top/Article/details/gteregvttj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.aibaodan.cn/Article/details/gtoxiubgpd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.nwbrower.top/Article/details/gtyfavehku.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.haohaochexian.top/Article/details/gtyttgicfg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cucudq.cn/Article/details/gthmfzchzq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ehwqpu.com/Article/details/gttwbbncqk.html

[J08] 提取年月日与星期
来源：http://dali.yonumen.top/Article/details/gtkowfagdk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.aibaodan.cn/Article/details/gtdiqtcupo.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.wangdashe.top/Article/details/gtmsvwpexy.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jqgufenzy.top/Article/details/gtapbkwrjw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.feifeiyinyue.top/Article/details/gtcskgkonr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yanxiufei.cn/Article/details/gtjtgzuebk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yangfankeji.com/Article/details/gtenyhzrvx.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shzxlz.cn/Article/details/gtmgtwxnza.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zdqjudy.top/Article/details/gtfhpvzexz.html

[J09] 时区处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbkprafxe.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.vqdsnc.cn/Article/details/gtvonhtvuv.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxhrxmtnp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hysaishi.cn/Article/details/gtxdrobmpj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxuanxn.top/Article/details/gtzdqasvzh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zycfv.cn/Article/details/gtebeisknh.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.nanxuanxn.top/Article/details/gtouzmdjan.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.tianlin.xyz/Article/details/gtegvexbbo.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xziqi.cn/Article/details/gtjrkyphnc.html

[J10] 取今天 / 本月第一天
来源：http://dali.feifeiyinyue.top/Article/details/gtjdkielce.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tanke756.top/Article/details/gtvkskoqjs.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.feifeiyinyue.top/Article/details/gtjoxviqaa.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xylfe.cn/Article/details/gtuwxrbkxv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.daxiang520.top/Article/details/gtlxgmuemn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.haohaochexian.top/Article/details/gtainbozzr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yonumen.top/Article/details/gtconigbxe.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.feifeiyinyue.top/Article/details/gtrzsxuibv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhijiandao.cn/Article/details/gtoelkliwb.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtmvtyutdq.html

K. JSON 与序列化
来源：http://dali.hysaishi.cn/Article/details/gtpyvryirw.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtifmodvjr.html

[K01] 对象转 JSON 字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtkqdweadd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sufxvd.cn/Article/details/gtetxihruz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhengqikj.top/Article/details/gtmngztpmg.html

JS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrmbclooi.html

TS:   JSON.stringify(obj)
来源：http://dali.wangdashe.top/Article/details/gtfboshnhw.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hnxiangtu.top/Article/details/gtmlreduif.html

Go:   json.Marshal(obj)
来源：http://dali.chenlongwang.top/Article/details/gtduclqkse.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yj20258888.top/Article/details/gtenbfbyng.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtygbuouck.html

[K02] JSON 字符串转对象
来源：http://dali.jiagoushi.top/Article/details/gtrfrbqwjz.html

Py:   json.loads(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuqoeunvp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.quarkkingdee.top/Article/details/gtjqbxthmv.html

JS:   JSON.parse(s)
来源：http://dali.andypj.xyz/Article/details/gtkjtssgmr.html

TS:   JSON.parse(s)
来源：http://dali.zdqjudy.top/Article/details/gtwstijyiq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.bjfxy.top/Article/details/gtjbedirbk.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yonumen.top/Article/details/gtisgywgor.html

Ruby: JSON.parse(s)
来源：http://dali.xuanzx.com/Article/details/gtxicqtfsq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtghehdlqd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gzhubu.top/Article/details/gtigdhoslj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xylfe.cn/Article/details/gtqdwxzmcm.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ivvv.top/Article/details/gtizcwmuvl.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xylfe.cn/Article/details/gtwtxcquvp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yangfankeji.com/Article/details/gttacezons.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.iojbl.cn/Article/details/gtyrlvfcmh.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.kuanghao11.cn/Article/details/gtpscqjhcm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.tian-w.cn/Article/details/gttejahhmv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.aizwys.cn/Article/details/gtfkqhdnep.html

[K04] 读取 JSON 文件
来源：http://dali.ydzc1.top/Article/details/gtdofubvmq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hysaishi.cn/Article/details/gtautrmffj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.wangdashe.top/Article/details/gtykobjjqs.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guannengcc.top/Article/details/gtxsbbgelr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangdashe.top/Article/details/gtzggunawh.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ehwqpu.com/Article/details/gtcjqiumec.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jyoumei.cn/Article/details/gtmlmcyfnb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.feifeiyinyue.top/Article/details/gtmrpdwhmg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhongyouzk.top/Article/details/gtblnmkyba.html

[K05] 深拷贝对象
来源：http://dali.zhongyouzk.top/Article/details/gtexmuiuiu.html

Py:   copy.deepcopy(obj)
来源：http://dali.cucudq.cn/Article/details/gtinznwkso.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cdnleiting.top/Article/details/gtrphpvzko.html

JS:   structuredClone(obj)
来源：http://dali.pycfn.com/Article/details/gtvlcmnecx.html

TS:   structuredClone(obj)
来源：http://dali.snrcjt.cn/Article/details/gtgdciwrkw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.bjfxy.top/Article/details/gtnqnrpmbk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gotoacloud.top/Article/details/gtfggebbab.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.meibo888.top/Article/details/gtykahbjok.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.dianchejie.cn/Article/details/gtxojdudeo.html

[K06] 解析 URL 查询串
来源：http://dali.mhx1999.top/Article/details/gtcbitowau.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xuetiantiany.cn/Article/details/gtsaedrdse.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.smart0.xyz/Article/details/gtgzvghyhq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangshuangyany.cn/Article/details/gtfoysrcyf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.dashuyun.cn/Article/details/gtuuajgvve.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.aibaodan.cn/Article/details/gtttmhawun.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jlsjyb.cn/Article/details/gtnhghljvl.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gogol.net.cn/Article/details/gtnnfjlfem.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhixingplan.top/Article/details/gtvlctbpnf.html

[K07] 进制转换
来源：http://dali.xinyue.icu/Article/details/gtxgbwzzjl.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ivvv.top/Article/details/gtqbtncvvo.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cashguo.top/Article/details/gtuachvefa.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtzgecooxr.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gtnbthbmpz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtlkjaxvmx.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.tanke756.top/Article/details/gtphypwtwj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ppjwa.cn/Article/details/gtrymcaqkb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gtyzwmxeyb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hnxiangtu.top/Article/details/gtepshqicg.html

Py:   pickle.dumps(obj)
来源：http://dali.iojbl.cn/Article/details/gtkockzbbr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sxryk.cn/Article/details/gtdjaompha.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hfpthk.cn/Article/details/gtafnoqqzn.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cheryme.top/Article/details/gtvejrdute.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.daria6918.cn/Article/details/gtdltqydlt.html

Go:   encoding/gob
来源：http://dali.gotoacloud.top/Article/details/gtzxwwcbrn.html

Ruby: Marshal.dump(obj)
来源：http://dali.dashuyun.cn/Article/details/gtnqlhrmkr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yanxiufei.cn/Article/details/gtsxibgejb.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtuqsbkgfg.html

L. 网络请求
来源：http://dali.chenlongwang.top/Article/details/gtfzknahwg.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtfwajrsxe.html

[L01] 发送 GET 请求
来源：http://dali.sysykeji.top/Article/details/gtiocbsiiu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinqigufen.top/Article/details/gthsynuybz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ydzc1.top/Article/details/gtizntqbct.html

JS:   await fetch(url)
来源：http://dali.yj202588.top/Article/details/gtclpbnnau.html

TS:   await fetch(url)
来源：http://dali.nanxuanxn.top/Article/details/gtslrkpads.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xuetiantiany.cn/Article/details/gtusrxazkl.html

Go:   resp, err := http.Get(url)
来源：http://dali.zycfv.cn/Article/details/gtelkmtssq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hammf.cn/Article/details/gtusjcimjp.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hywenlv.cn/Article/details/gtcxkskyox.html

[L02] 发送 POST JSON
来源：http://dali.jianghu66.top/Article/details/gtbdokzqgs.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ydzc1.top/Article/details/gtmzbxpqin.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpensrano.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.andypj.xyz/Article/details/gtuewkdwhb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.kuanghao11.cn/Article/details/gtgsookhag.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.daria6918.cn/Article/details/gtrrsuokxs.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.tianlin.xyz/Article/details/gttjrdkxiy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hammf.cn/Article/details/gtrbvsobae.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.chenlongwang.top/Article/details/gtututipdz.html

[L03] 设置自定义请求头
来源：http://dali.hywenlv.cn/Article/details/gtowoavqfy.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cheryme.top/Article/details/gtmkcopoor.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.guowangkeji.top/Article/details/gtyivipjwr.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gtbbsrjkcl.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmoymcykx.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cheryme.top/Article/details/gtricwgmmb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.pengpengdd.cyou/Article/details/gtnbidntdg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.guannengcc.top/Article/details/gtnhngjvrf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.316326.xyz/Article/details/gtkcievfjg.html

[L04] 设置超时
来源：http://dali.hnxiangtu.top/Article/details/gtycxaedwl.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ydzc1.top/Article/details/gtjcksfhbi.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gzhubu.top/Article/details/gtxvxvitgj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangdashe.top/Article/details/gtdmrehikf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aizwys.cn/Article/details/gtcfuphrhu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.vqdsnc.cn/Article/details/gtddjavyel.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yongpay.top/Article/details/gtgkfvtvkg.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.tanke756.top/Article/details/gttsbwedlx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shangyingyoupin.top/Article/details/gtjmromklb.html

[L05] 上传文件（multipart）
来源：http://dali.hongshengwenyu.top/Article/details/gtovhuvkaz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cqqwz.cn/Article/details/gtlhduibaq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.birdmap.top/Article/details/gtazhjxovg.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yanxiufei.cn/Article/details/gtraedxygm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cucudq.cn/Article/details/gtauhnpiib.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yuanzhike.top/Article/details/gteeajqhdl.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hfpthk.cn/Article/details/gtqjixrrwy.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.c1oappe.top/Article/details/gthlptlxyy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ehwqpu.com/Article/details/gthukejqhr.html

[L06] 解析响应为 JSON
来源：http://dali.cashguo.top/Article/details/gthqcnxgnk.html

Py:   resp.json()
来源：http://dali.nanxinkj.top/Article/details/gtrsslssyn.html

PHP:  json_decode($body, true);
来源：http://dali.cqqwz.cn/Article/details/gtyngcmhgv.html

JS:   await resp.json()
来源：http://dali.mhx1999.top/Article/details/gtblzealug.html

TS:   await resp.json()
来源：http://dali.nanxinkj.top/Article/details/gtxpukgooc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.iojbl.cn/Article/details/gtpzeycqvd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yanxiufei.cn/Article/details/gtdaajdiby.html

Ruby: JSON.parse(resp.body)
来源：http://dali.chenzaomai.com/Article/details/gtggdyigxu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhixingplan.top/Article/details/gtxqqedqwq.html


<!-- 参考信息 -->