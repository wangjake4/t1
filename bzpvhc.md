代发 wailian999

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jlsjyb.cn/Article/details/gt2hnsqyoxu.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.0kj1m.cn/Article/details/gt2jgmdsukh.html

Ruby: s.match?(/\d+/)
来源：http://dali.cdnleiting.top/Article/details/gt2fysitxpr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.c1oappe.top/Article/details/gt2qshgacjs.html

[I02] 提取所有匹配
来源：http://dali.tianlin.xyz/Article/details/gt2exewtzwc.html

Py:   re.findall(r"\d+", s)
来源：http://dali.daxiang520.top/Article/details/gt2ywyahbsh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cqqwz.cn/Article/details/gt2brzmsxat.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bilqdzch.html

TS:   s.match(/\d+/g)
来源：http://dali.zdqjudy.top/Article/details/gt2twpwhnrh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cheryme.top/Article/details/gt2iubvgphe.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.smart0.xyz/Article/details/gt2pwktucba.html

Ruby: s.scan(/\d+/)
来源：http://dali.hfpthk.cn/Article/details/gt2jdgegtzu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2luwecnvb.html

[I03] 提取捕获分组
来源：http://dali.fengsongda.top/Article/details/gt2lnktwijv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.tianlin.xyz/Article/details/gt2gniwzrqb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.wangdashe.top/Article/details/gt2zseanqtv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.316326.xyz/Article/details/gt2zfedkdud.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hnqzz.top/Article/details/gt2yrhdqzbx.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.pycfn.com/Article/details/gt2triucnhz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xinyue.icu/Article/details/gt2ykcfhzze.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.316326.xyz/Article/details/gt2ikfbeydo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.0kj1m.cn/Article/details/gt2xcdkpmhc.html

[I04] 正则替换
来源：http://dali.smart0.xyz/Article/details/gt2xfnuyrgw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhixingplan.top/Article/details/gt2xsmldqwh.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sxryk.cn/Article/details/gt2ejegttbd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gt2cjjtufln.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.dianchejie.cn/Article/details/gt2ghmexrck.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cqqwz.cn/Article/details/gt2nbvcmwyc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jianghu66.top/Article/details/gt2zrkypinh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gzhubu.top/Article/details/gt2dqrtkjft.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.tian-w.cn/Article/details/gt2mqvgwhah.html

[I05] 按正则拆分
来源：http://dali.ivvv.top/Article/details/gt2pzclqchh.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yuanzhike.top/Article/details/gt2urwcruuh.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2elgiypgj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yonumen.top/Article/details/gt2meuatpfj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.meibo888.top/Article/details/gt2xcexaxlu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sxryk.cn/Article/details/gt2eqxwbmyx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jqgufenzy.top/Article/details/gt2hgkxqftm.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.svipenyu.cn/Article/details/gt2olsqlshd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hysaishi.cn/Article/details/gt2vzmhhmbs.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yuxming.cn/Article/details/gt2wlsnpwuo.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sufxvd.cn/Article/details/gt2wtimfmae.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.bjfxy.top/Article/details/gt2biwxjiki.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daria6918.cn/Article/details/gt2hpffijpu.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuanzhike.top/Article/details/gt2yiuvjazg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ijdmrjty.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ivvv.top/Article/details/gt2waxrqqyk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.meibo888.top/Article/details/gt2afxdidvy.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gt2hjiktvdp.html

[I07] 忽略大小写与多行模式
来源：http://dali.xuetiantiany.cn/Article/details/gt2izfdgufk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fneiedor.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.tanke756.top/Article/details/gt2uaarhafq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cqqwz.cn/Article/details/gt2cejstsxi.html

TS:   /error/gim
来源：http://dali.ehwqpu.com/Article/details/gt2djoxkbdb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.redwolf501.top/Article/details/gt2ghdtxbpg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.nanxuanxn.top/Article/details/gt2xvosfytz.html

Ruby: s.scan(/error/i)
来源：http://dali.yonumen.top/Article/details/gt2udjaniwt.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shangyingyoupin.top/Article/details/gt2yssbeint.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jiagoushi.top/Article/details/gt2kamwtdzr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhongyouzk.top/Article/details/gt2lszekujy.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yuanzhike.top/Article/details/gt2cvidysls.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wfgvlznj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenzaomai.com/Article/details/gt2pttuwckq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ajglneqf.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cucudq.cn/Article/details/gt2gcmxkbse.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.smart0.xyz/Article/details/gt2qrlmxfbo.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yj20258.top/Article/details/gt2ycosrpcc.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2sdfwfanj.html

J. 日期与时间
来源：http://dali.quarkkingdee.top/Article/details/gt2ujrpevll.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fuoukrhn.html

[J01] 获取当前时间
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jrpoubay.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhoulong.xyz/Article/details/gt2ejletzvd.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hfpthk.cn/Article/details/gt2dlkrnbhs.html

JS:   new Date();  Date.now()
来源：http://dali.snrcjt.cn/Article/details/gt2azokmvmq.html

TS:   new Date();  Date.now()
来源：http://dali.chenlongwang.top/Article/details/gt2htuyutkf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.chenjidiqi.icu/Article/details/gt2xpztvugy.html

Go:   time.Now()
来源：http://dali.c1oappe.top/Article/details/gt2azcfmnex.html

Ruby: Time.now
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ugnasgcu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jqgfzy.top/Article/details/gt2idzhrajr.html

[J02] 格式化输出
来源：http://dali.yongpay.top/Article/details/gt2wygobxct.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guowangkeji.top/Article/details/gt2vjgcwzvx.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hysaishi.cn/Article/details/gt2dcadeqyt.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jqgfzy.top/Article/details/gt2afihpzsl.html

TS:   d.toISOString()
来源：http://dali.jianghu66.top/Article/details/gt2humeawvs.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zycfv.cn/Article/details/gt2rwlxidgj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yueranfly.top/Article/details/gt2rynmxune.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yongpay.top/Article/details/gt2vitgmcso.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.tianlin.xyz/Article/details/gt2dlwxqxaj.html

[J03] 字符串解析为日期
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yoxyuazn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yangfankeji.com/Article/details/gt2vdentfhx.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qdfvyaay.html

JS:   new Date("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gt2wlgzqela.html

TS:   new Date("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gt2qbfumjqe.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gt2pntwnssl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rcojzdyn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gt2mxfihyaa.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xziqi.cn/Article/details/gt2qpwnrjiw.html

[J04] 时间戳与日期互转
来源：http://dali.redwolf501.top/Article/details/gt2jgeeutfw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.aizwys.cn/Article/details/gt2plpviyml.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jlsjyb.cn/Article/details/gt2xttmegoy.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jqgufenzy.top/Article/details/gt2xcywkqzf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhixingplan.top/Article/details/gt2yxxrsmuz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hnqzz.top/Article/details/gt2tuucvpbe.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.fengsongda.top/Article/details/gt2aolrqxoe.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.tianlin.xyz/Article/details/gt2ytfxuinn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shuidangran.top/Article/details/gt2trqybygm.html

[J05] 时间加减（加 7 天）
来源：http://dali.meibo888.top/Article/details/gt2xfodrclx.html

Py:   now + timedelta(days=7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vyizcgbi.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.chenlongwang.top/Article/details/gt2rpgfmzpb.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cdnleiting.top/Article/details/gt2kzgghgfi.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zcvzqbvv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lwzhttbd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xylfe.cn/Article/details/gt2tdkufrif.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gaohongyu789.top/Article/details/gt2cielxeic.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zdqjudy.top/Article/details/gt2xgxrsitq.html

[J06] 计算两时间之差
来源：http://dali.yj202588.top/Article/details/gt2akmgyyqe.html

Py:   (end - start).total_seconds()
来源：http://dali.daria6918.cn/Article/details/gt2dilqpzxb.html

PHP:  $end->diff($start)->days;
来源：http://dali.jyoumei.cn/Article/details/gt2frbhareu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2raqxytyt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sxryk.cn/Article/details/gt2rbqwybbl.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yangfankeji.com/Article/details/gt2ihupbbfx.html

Go:   end.Sub(start).Hours()
来源：http://dali.cucudq.cn/Article/details/gt2spaugjpu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xuanzx.com/Article/details/gt2zxvfjkcj.html

C#:   (end - start).TotalSeconds
来源：http://dali.wangshuangyany.cn/Article/details/gt2xekvkoxh.html

[J07] 比较两个日期
来源：http://dali.hnqzz.top/Article/details/gt2qmlmvqsq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.pengpengdd.cyou/Article/details/gt2gyivkvqw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.9152youxi.cn/Article/details/gt2trczxzlt.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.wangshuangyany.cn/Article/details/gt2holoqaqf.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.mhx1999.top/Article/details/gt2iwwanztc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jqgufenzy.top/Article/details/gt2qfiasdru.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ehwqpu.com/Article/details/gt2klqrmhkh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gotoacloud.top/Article/details/gt2uqqjyzff.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.dianchejie.cn/Article/details/gt2gcnoivrv.html

[J08] 提取年月日与星期
来源：http://dali.zhengqikj.top/Article/details/gt2wpecszzf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cheryme.top/Article/details/gt2krbtncgr.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cheryme.top/Article/details/gt2vzcbvfel.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenjidiqi.icu/Article/details/gt2gvmagiuc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhengqikj.top/Article/details/gt2jcmqiyxq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhijiandao.cn/Article/details/gt2mfijvlqi.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xuanzx.com/Article/details/gt2zajgludb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.vqdsnc.cn/Article/details/gt2luvialyd.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yj20258888.top/Article/details/gt2fxxekngz.html

[J09] 时区处理
来源：http://dali.kuanghao11.cn/Article/details/gt2yeqypvsq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yangfankeji.com/Article/details/gt2tekwupag.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xinyue.icu/Article/details/gt2ejeidreo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zycfv.cn/Article/details/gt2zarytbxs.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.mhx1999.top/Article/details/gt2ajnwqjso.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bvyesuip.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jiagoushi.top/Article/details/gt2hfvbsqcw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.9152youxi.cn/Article/details/gt2geiimcbv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2znymbcjf.html

[J10] 取今天 / 本月第一天
来源：http://dali.guannengcc.top/Article/details/gt2aokefxyp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cdnleiting.top/Article/details/gt2tfidkdyy.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xziqi.cn/Article/details/gt2bhjihuyp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yongpay.top/Article/details/gt2qorznifh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ppjwa.cn/Article/details/gt2yfhqynra.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.chenlongwang.top/Article/details/gt2gpulpbhq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.9152youxi.cn/Article/details/gt2xrudbgqk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tian-w.cn/Article/details/gt2gmfwlses.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ppjwa.cn/Article/details/gt2oxfralpx.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2mmkfimaj.html

K. JSON 与序列化
来源：http://dali.yonumen.top/Article/details/gt2xapucpey.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qeckaqno.html

[K01] 对象转 JSON 字符串
来源：http://dali.sufxvd.cn/Article/details/gt2erfquvpp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ydzc1.top/Article/details/gt2wqudxeon.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhengqikj.top/Article/details/gt2fshcaufm.html

JS:   JSON.stringify(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2sxonlvqv.html

TS:   JSON.stringify(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qsuofvcs.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shangyingyoupin.top/Article/details/gt2wxwiyedj.html

Go:   json.Marshal(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2tjsnarjz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yuxming.cn/Article/details/gt2ufnfhxiq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xylfe.cn/Article/details/gt2gldydrus.html

[K02] JSON 字符串转对象
来源：http://dali.jinqigufen.top/Article/details/gt2shvqmtsv.html

Py:   json.loads(s)
来源：http://dali.jiagoushi.top/Article/details/gt2lpwqqbbs.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fluyxzdj.html

JS:   JSON.parse(s)
来源：http://dali.cdnleiting.top/Article/details/gt2oeysoyyp.html

TS:   JSON.parse(s)
来源：http://dali.zhixingplan.top/Article/details/gt2nzarynva.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hnxiangtu.top/Article/details/gt2poxbwrqa.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.tianlin.xyz/Article/details/gt2vgewqsoz.html

Ruby: JSON.parse(s)
来源：http://dali.hywenlv.cn/Article/details/gt2leiubnbw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.aizwys.cn/Article/details/gt2dmdjkspw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sxryk.cn/Article/details/gt2hdxxmbhr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nanxuanxn.top/Article/details/gt2gwnapxpm.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.guowangkeji.top/Article/details/gt2vdmavsdz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.aibaodan.cn/Article/details/gt2mbstqlpg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj202588.top/Article/details/gt2zvaknrwb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nwbrower.top/Article/details/gt2kwdocwwk.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yueranfly.top/Article/details/gt2eagwosnb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yj20258.top/Article/details/gt2ysfwqwtq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.chenzaomai.com/Article/details/gt2tcxplxth.html

[K04] 读取 JSON 文件
来源：http://dali.jqgufenzy.top/Article/details/gt2cwhtadxe.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sweek.top/Article/details/gt2xytfglwn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhixingplan.top/Article/details/gt2wxyureib.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cashguo.top/Article/details/gt2auysilhb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhixingplan.top/Article/details/gt2qhjilemg.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.guannengcc.top/Article/details/gt2mlfvqiwy.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.fengsongda.top/Article/details/gt2zyuxmodh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shzxlz.cn/Article/details/gt2yebzhzne.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.tianlin.xyz/Article/details/gt2enqfejil.html

[K05] 深拷贝对象
来源：http://dali.ydzc1.top/Article/details/gt2amqbfnhy.html

Py:   copy.deepcopy(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2tspudies.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhixingplan.top/Article/details/gt2sfvrydda.html

JS:   structuredClone(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2zghkkvik.html

TS:   structuredClone(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2awxhhjcr.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.smart0.xyz/Article/details/gt2kffxxkhy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.316326.xyz/Article/details/gt2txipxavm.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhixingplan.top/Article/details/gt2xwnsuccr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yj20258888.top/Article/details/gt2kzvtdvqw.html

[K06] 解析 URL 查询串
来源：http://dali.yangfankeji.com/Article/details/gt2uhahadka.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shuidangran.top/Article/details/gt2kpjksyuv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.haohaochexian.top/Article/details/gt2ctsxsjrj.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yvedp.cn/Article/details/gt2xknhohfp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.quarkkingdee.top/Article/details/gt2jfomognl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.c1oappe.top/Article/details/gt2fqclthsw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ivvv.top/Article/details/gt2grucnuhi.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.iojbl.cn/Article/details/gt2mzmrbawl.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2xqodawbu.html

[K07] 进制转换
来源：http://dali.gaohongyu789.top/Article/details/gt2rynrzmag.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gt2qbiqrhmb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.svipenyu.cn/Article/details/gt2yqpuergr.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gt2kgzskspv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gt2wguzgdcc.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gt2rhpibeva.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.iojbl.cn/Article/details/gt2yganeucg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ybcxt.top/Article/details/gt2hpiqjnfb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gt2hqlwnmao.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yangfankeji.com/Article/details/gt2qakzhwbv.html

Py:   pickle.dumps(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wrkgzhlq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kzsuhpnx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.haohaochexian.top/Article/details/gt2kwhwtuzb.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cashguo.top/Article/details/gt2oaukeyys.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj20258.top/Article/details/gt2hauzmkom.html

Go:   encoding/gob
来源：http://dali.gotoacloud.top/Article/details/gt2sodttaxy.html

Ruby: Marshal.dump(obj)
来源：http://dali.xylfe.cn/Article/details/gt2hxyvztxg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xinyue.icu/Article/details/gt2gsxpqfov.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2clkjencm.html

L. 网络请求
来源：http://dali.xinyue.icu/Article/details/gt2qjyklxcz.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2jesomiqr.html

[L01] 发送 GET 请求
来源：http://dali.nanxinkj.top/Article/details/gt2ljtwgcij.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.c1oappe.top/Article/details/gt2eckjpdqk.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gotoacloud.top/Article/details/gt2phewspsu.html

JS:   await fetch(url)
来源：http://dali.gotoacloud.top/Article/details/gt2iuzrbkme.html

TS:   await fetch(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vwfotvto.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.meibo888.top/Article/details/gt2gniqtxsb.html

Go:   resp, err := http.Get(url)
来源：http://dali.dashuyun.cn/Article/details/gt2xtolxcvc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.quarkkingdee.top/Article/details/gt2vdebrldq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jlsjyb.cn/Article/details/gt2jubxwile.html

[L02] 发送 POST JSON
来源：http://dali.xuetiantiany.cn/Article/details/gt2zkzoxinh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hywenlv.cn/Article/details/gt2bckoolpd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jyoumei.cn/Article/details/gt2fsvlbqtb.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yonumen.top/Article/details/gt2kpalsdkm.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yanxiufei.cn/Article/details/gt2dsobdflx.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.sysykeji.top/Article/details/gt2ikwadwps.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yuxming.cn/Article/details/gt2vtcstwza.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.andypj.xyz/Article/details/gt2yceleryj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hfpthk.cn/Article/details/gt2agcxhhyr.html

[L03] 设置自定义请求头
来源：http://dali.jiagoushi.top/Article/details/gt2frodkdji.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.quarkkingdee.top/Article/details/gt2ibucbdie.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hfpthk.cn/Article/details/gt2ftdhlxpn.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.haohaochexian.top/Article/details/gt2tsajvhkp.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenjidiqi.icu/Article/details/gt2rpgabefs.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hnxiangtu.top/Article/details/gt2svollcpd.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.nanxinkj.top/Article/details/gt2ydaxxpur.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xylfe.cn/Article/details/gt2ysepjpet.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.kuanghao11.cn/Article/details/gt2peudndmz.html

[L04] 设置超时
来源：http://dali.hfpthk.cn/Article/details/gt2mtlgeyzi.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yangfankeji.com/Article/details/gt2fwfhvmdh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhongyouzk.top/Article/details/gt2vtysmzky.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.kuanghao11.cn/Article/details/gt2umaompwq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jlsjyb.cn/Article/details/gt2cjllpser.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ielqedls.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.vqdsnc.cn/Article/details/gt2msslzgvi.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hactovkd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yonumen.top/Article/details/gt2uoagytun.html

[L05] 上传文件（multipart）
来源：http://dali.yj20258.top/Article/details/gt2xgpeffic.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cheryme.top/Article/details/gt2lmwkmlnq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj202588.top/Article/details/gt2nshycdyo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xinyue.icu/Article/details/gt2kqwjafmq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zycfv.cn/Article/details/gt2dddrfudj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.tanke756.top/Article/details/gt2fpfywjsd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.fzhhl.top/Article/details/gt2bpatdbwc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hnxiangtu.top/Article/details/gt2stimpqcs.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2zwqssuib.html

[L06] 解析响应为 JSON
来源：http://dali.jlsjyb.cn/Article/details/gt2dslddtyj.html

Py:   resp.json()
来源：http://dali.yongpay.top/Article/details/gt2awrohyuz.html

PHP:  json_decode($body, true);
来源：http://dali.xinyue.icu/Article/details/gt2efxwzctx.html

JS:   await resp.json()
来源：http://dali.redwolf501.top/Article/details/gt2bqxwawpb.html

TS:   await resp.json()
来源：http://dali.daria6918.cn/Article/details/gt2zyrbvybl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hammf.cn/Article/details/gt2ahuvjice.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.gaohongyu789.top/Article/details/gt2ojihdqcp.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hywenlv.cn/Article/details/gt2skwxngji.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hywenlv.cn/Article/details/gt2uthinzqe.html

[L07] 处理 HTTP 状态码
来源：http://dali.shangyingyoupin.top/Article/details/gt2njowrxak.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tanke756.top/Article/details/gt2slzxplif.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nanxuanxn.top/Article/details/gt2vdstecmp.html

JS:   resp.ok;  resp.status
来源：http://dali.hywenlv.cn/Article/details/gt2ncxtohwp.html

TS:   resp.ok;  resp.status
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jfkbvbpu.html

Java: resp.statusCode()
来源：http://dali.fzhhl.top/Article/details/gt2jhduwhhv.html

Go:   resp.StatusCode
来源：http://dali.cashguo.top/Article/details/gt2idhpoacb.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2fntpibns.html


<!-- 参考信息 -->