代发 wailian999

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dskdwrxq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jiagoushi.top/Article/details/gt2fvculjnx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.nanxinkj.top/Article/details/gt2bwoxsaqa.html

[H10] 资源自动释放
来源：http://dali.hywenlv.cn/Article/details/gt2ipgmxzhg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2invxcbcl.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xinyue.icu/Article/details/gt2dcmutugq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuanzhike.top/Article/details/gt2iahfbegj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cqqwz.cn/Article/details/gt2qqleflkb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinqigufen.top/Article/details/gt2ikbwunrj.html

Go:   defer f.Close()
来源：http://dali.hysaishi.cn/Article/details/gt2dtlwfjzz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.daxiang520.top/Article/details/gt2cbajyyip.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.316326.xyz/Article/details/gt2olxepibr.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2qgcsyxfu.html

I. 正则表达式
来源：http://dali.vqdsnc.cn/Article/details/gt2rqpgyspp.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2uvedlchm.html

[I01] 判断是否匹配
来源：http://dali.ydzc1.top/Article/details/gt2skztvgpq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.c1oappe.top/Article/details/gt2jguccdhw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tianlin.xyz/Article/details/gt2qdhzgqsr.html

JS:   /\d+/.test(s)
来源：http://dali.cqqwz.cn/Article/details/gt2svzhfxbv.html

TS:   /\d+/.test(s)
来源：http://dali.sweek.top/Article/details/gt2rgjsopvo.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sxryk.cn/Article/details/gt2axqyxqmc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yuanzhike.top/Article/details/gt2tlmrtyry.html

Ruby: s.match?(/\d+/)
来源：http://dali.jianghu66.top/Article/details/gt2sdpwrcey.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ffcvenre.html

[I02] 提取所有匹配
来源：http://dali.hnxiangtu.top/Article/details/gt2sxywdgul.html

Py:   re.findall(r"\d+", s)
来源：http://dali.vqdsnc.cn/Article/details/gt2pcxarbpd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.pycfn.com/Article/details/gt2fnnzruhp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shzxlz.cn/Article/details/gt2ytldxllw.html

TS:   s.match(/\d+/g)
来源：http://dali.dashuyun.cn/Article/details/gt2pmyxicvx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sysykeji.top/Article/details/gt2xcizotkq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.meibo888.top/Article/details/gt2epzmpeps.html

Ruby: s.scan(/\d+/)
来源：http://dali.xziqi.cn/Article/details/gt2mrkobywp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hysaishi.cn/Article/details/gt2rvrokrys.html

[I03] 提取捕获分组
来源：http://dali.yvedp.cn/Article/details/gt2idgirfuh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2npcneovd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gzhubu.top/Article/details/gt2evrxhmry.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yanxiufei.cn/Article/details/gt2hikuxyyk.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.daria6918.cn/Article/details/gt2bmezrsqr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.guowangkeji.top/Article/details/gt2jguirwjx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhoulong.xyz/Article/details/gt2zvsozwnh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sbfeoskw.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.wangdashe.top/Article/details/gt2tldxyvnw.html

[I04] 正则替换
来源：http://dali.pengpengdd.cyou/Article/details/gt2riidjdcm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.fengsongda.top/Article/details/gt2fhiijouq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenlongwang.top/Article/details/gt2mzfbalif.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhongyouzk.top/Article/details/gt2wjcrlzdn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.aizwys.cn/Article/details/gt2muwylmho.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.c1oappe.top/Article/details/gt2bpseffcb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinqigfzy.top/Article/details/gt2kwsfhztj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinqigufen.top/Article/details/gt2sokmalks.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yj20258.top/Article/details/gt2jinssyoq.html

[I05] 按正则拆分
来源：http://dali.hysaishi.cn/Article/details/gt2fjtcuduw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xziqi.cn/Article/details/gt2evhpcgcb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yonumen.top/Article/details/gt2cqthukqg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yongpay.top/Article/details/gt2pklxiica.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wikfbrvm.html

Java: s.split("\\s*,\\s*")
来源：http://dali.guannengcc.top/Article/details/gt2rwomqixi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2uhagtgrt.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.tanke756.top/Article/details/gt2ltjghwin.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.pycfn.com/Article/details/gt2wcngnurf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yueranfly.top/Article/details/gt2rwsyctpy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ciqpvpnx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxndeqd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jiagoushi.top/Article/details/gt2szjpgooh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sysykeji.top/Article/details/gt2ajfjemdc.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.meibo888.top/Article/details/gt2izevlbtl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.haohaochexian.top/Article/details/gt2rbkdpekr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.mhx1999.top/Article/details/gt2bgumjaoa.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.dianchejie.cn/Article/details/gt2pqfhpytv.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhoulong.xyz/Article/details/gt2ulycgqfn.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.0kj1m.cn/Article/details/gt2wsvyvkcy.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jianghu66.top/Article/details/gt2yhxfbomc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hysaishi.cn/Article/details/gt2jvtdsyoy.html

TS:   /error/gim
来源：http://dali.bjfxy.top/Article/details/gt2pedqflsn.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.havefunace.top/Article/details/gt2vzfwgtpr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.dashuyun.cn/Article/details/gt2hjjbopma.html

Ruby: s.scan(/error/i)
来源：http://dali.yanxiufei.cn/Article/details/gt2jzswaqli.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yanxiufei.cn/Article/details/gt2sniprdge.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gaohongyu789.top/Article/details/gt2duhedwyk.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ybcxt.top/Article/details/gt2xkymafbg.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.fengsongda.top/Article/details/gt2tsiepmqd.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhongyouzk.top/Article/details/gt2yglczhck.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sweek.top/Article/details/gt2fyzrsoba.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.c1oappe.top/Article/details/gt2efdmqzsw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yj20258.top/Article/details/gt2wlhsbguo.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jiagoushi.top/Article/details/gt2eauoxhnp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhixingplan.top/Article/details/gt2aidgaqvm.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2cekimrpo.html

J. 日期与时间
来源：http://dali.tianlin.xyz/Article/details/gt2ncpszskt.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2asugifzh.html

[J01] 获取当前时间
来源：http://dali.sufxvd.cn/Article/details/gt2fghelndu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.guowangkeji.top/Article/details/gt2ceobcitq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.guowangkeji.top/Article/details/gt2zmaxvkki.html

JS:   new Date();  Date.now()
来源：http://dali.redwolf501.top/Article/details/gt2tdiawqam.html

TS:   new Date();  Date.now()
来源：http://dali.feifeiyinyue.top/Article/details/gt2dsvhefyk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nanxinkj.top/Article/details/gt2luxzgiie.html

Go:   time.Now()
来源：http://dali.jlsjyb.cn/Article/details/gt2ivubcbiu.html

Ruby: Time.now
来源：http://dali.birdmap.top/Article/details/gt2jaxrjgkq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vhaagfko.html

[J02] 格式化输出
来源：http://dali.mhx1999.top/Article/details/gt2yhhwqwvr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.316326.xyz/Article/details/gt2fjohjhro.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.sufxvd.cn/Article/details/gt2mzncutxt.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hnxiangtu.top/Article/details/gt2esmldsnj.html

TS:   d.toISOString()
来源：http://dali.hywenlv.cn/Article/details/gt2tbpyefui.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.feifeiyinyue.top/Article/details/gt2bvppbafm.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sxryk.cn/Article/details/gt2rkhrulgm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangdashe.top/Article/details/gt2fwlzqice.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xziqi.cn/Article/details/gt2pwwsjnfx.html

[J03] 字符串解析为日期
来源：http://dali.xylfe.cn/Article/details/gt2rcmndbos.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.smart0.xyz/Article/details/gt2flwmoxwj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.chenzaomai.com/Article/details/gt2lybhkkjz.html

JS:   new Date("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gt2unitxcqi.html

TS:   new Date("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gt2aufeweee.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gt2ywxbjmhs.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gt2cetsnawb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gt2pkwmiuzc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jlsjyb.cn/Article/details/gt2lsshwzuk.html

[J04] 时间戳与日期互转
来源：http://dali.sxryk.cn/Article/details/gt2ddkpugox.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.quarkkingdee.top/Article/details/gt2btoczktm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.c1oappe.top/Article/details/gt2ebvigfqj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhengqikj.top/Article/details/gt2zvhztvgy.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2acyqsukz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cheryme.top/Article/details/gt2eseugvnp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.tanke756.top/Article/details/gt2scaiujee.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gt2huuxjceo.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.havefunace.top/Article/details/gt2nibndefh.html

[J05] 时间加减（加 7 天）
来源：http://dali.ppjwa.cn/Article/details/gt2xttmdtdq.html

Py:   now + timedelta(days=7)
来源：http://dali.shuidangran.top/Article/details/gt2rttsespy.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.wangdashe.top/Article/details/gt2rascgyra.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.mhx1999.top/Article/details/gt2jmdqjnhf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cucudq.cn/Article/details/gt2oweokntt.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cashguo.top/Article/details/gt2deosoezx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yangfankeji.com/Article/details/gt2dzwddtlv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yj20258888.top/Article/details/gt2hatfnpld.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cucudq.cn/Article/details/gt2ukvpgyct.html

[J06] 计算两时间之差
来源：http://dali.yj20258888.top/Article/details/gt2vmambvdj.html

Py:   (end - start).total_seconds()
来源：http://dali.cucudq.cn/Article/details/gt2ynmgfhww.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenlongwang.top/Article/details/gt2evmcidfm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.9152youxi.cn/Article/details/gt2trwvoqwf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.mhx1999.top/Article/details/gt2izcnphaz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.0kj1m.cn/Article/details/gt2ghuaaeia.html

Go:   end.Sub(start).Hours()
来源：http://dali.svipenyu.cn/Article/details/gt2lvspkaxo.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhiwuduotai.top/Article/details/gt2zxmapscp.html

C#:   (end - start).TotalSeconds
来源：http://dali.hfpthk.cn/Article/details/gt2ldwezzcp.html

[J07] 比较两个日期
来源：http://dali.kuanghao11.cn/Article/details/gt2azxmajjw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yuanzhike.top/Article/details/gt2meintfwl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hnxiangtu.top/Article/details/gt2zixnezjk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258.top/Article/details/gt2dhhqzecj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.c1oappe.top/Article/details/gt2pvqqalmv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hnxiangtu.top/Article/details/gt2xshnozrx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.guannengcc.top/Article/details/gt2xjtfztnw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hfpthk.cn/Article/details/gt2oqbvlkvg.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ydzc1.top/Article/details/gt2iyplwrlx.html

[J08] 提取年月日与星期
来源：http://dali.yuanzhike.top/Article/details/gt2vqwgxtef.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.haohaochexian.top/Article/details/gt2poajxxhp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sxryk.cn/Article/details/gt2latnfsqx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenzaomai.com/Article/details/gt2aemkkcsd.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cucudq.cn/Article/details/gt2irepfevt.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhixingplan.top/Article/details/gt2efehsjnk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.nwbrower.top/Article/details/gt2uovmsqmb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.316326.xyz/Article/details/gt2eoxiftvj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.vqdsnc.cn/Article/details/gt2zwonpfoi.html

[J09] 时区处理
来源：http://dali.zhongyouzk.top/Article/details/gt2iokhhrtu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.meibo888.top/Article/details/gt2sqmtmcdd.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.svipenyu.cn/Article/details/gt2patvaawh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hwmhxyjr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sufxvd.cn/Article/details/gt2atfknwef.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2waigyhrk.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gaohongyu789.top/Article/details/gt2pxwjoovw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yongpay.top/Article/details/gt2hlmcelsh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.aibaodan.cn/Article/details/gt2ugmlljrr.html

[J10] 取今天 / 本月第一天
来源：http://dali.cdnleiting.top/Article/details/gt2mjxdudlt.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.quarkkingdee.top/Article/details/gt2ojuybzrm.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.chenzaomai.com/Article/details/gt2trrpjpnk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yanxiufei.cn/Article/details/gt2fsxlywmo.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ppjwa.cn/Article/details/gt2abyofenw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yueranfly.top/Article/details/gt2sqqscudv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jiagoushi.top/Article/details/gt2ypcbcvoc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yj20258.top/Article/details/gt2pnpnnjtd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.wangdashe.top/Article/details/gt2vdtoubyg.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2vkzulkkf.html

K. JSON 与序列化
来源：http://dali.yonumen.top/Article/details/gt2qndtahdv.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2efiynfya.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhengqikj.top/Article/details/gt2oiooryrg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.wangdashe.top/Article/details/gt2xtrafcip.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jlsjyb.cn/Article/details/gt2qcelshru.html

JS:   JSON.stringify(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2vftfedld.html

TS:   JSON.stringify(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2bnqlyyjk.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shzxlz.cn/Article/details/gt2pwzvyqwc.html

Go:   json.Marshal(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2txntokex.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.316326.xyz/Article/details/gt2ovjlsgvr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2apvsghli.html

[K02] JSON 字符串转对象
来源：http://dali.ivvv.top/Article/details/gt2qqssqpqe.html

Py:   json.loads(s)
来源：http://dali.tanke756.top/Article/details/gt2hqflayyj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tanke756.top/Article/details/gt2ueazfcyn.html

JS:   JSON.parse(s)
来源：http://dali.jyoumei.cn/Article/details/gt2nwmwmrzw.html

TS:   JSON.parse(s)
来源：http://dali.birdmap.top/Article/details/gt2kkpcofmn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.316326.xyz/Article/details/gt2lypcvtan.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.nanxuanxn.top/Article/details/gt2ppudgsvw.html

Ruby: JSON.parse(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qdjkbjtc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jdeptmdl.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2auqlajwo.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shzxlz.cn/Article/details/gt2gemhcaok.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.guannengcc.top/Article/details/gt2pbdhvivu.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jbtvuwbc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.guannengcc.top/Article/details/gt2dxopdtyg.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2wvshagbu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ydzc1.top/Article/details/gt2hmuhabyd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2zkmasfdz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nanxuanxn.top/Article/details/gt2ntfhukld.html

[K04] 读取 JSON 文件
来源：http://dali.quarkkingdee.top/Article/details/gt2szmsuceo.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cdnleiting.top/Article/details/gt2rttwtwwy.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sufxvd.cn/Article/details/gt2wuijeadn.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xylfe.cn/Article/details/gt2qxdgrheq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tanke756.top/Article/details/gt2kapwjjud.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hfpthk.cn/Article/details/gt2mmmyswax.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.c1oappe.top/Article/details/gt2eppczlax.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gogol.net.cn/Article/details/gt2ltobrrzw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.haohaochexian.top/Article/details/gt2dwqpiuci.html

[K05] 深拷贝对象
来源：http://dali.tanke756.top/Article/details/gt2yhkkpfmw.html

Py:   copy.deepcopy(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2enxsiust.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hnxiangtu.top/Article/details/gt2zikdevbi.html

JS:   structuredClone(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2gxblpcvu.html

TS:   structuredClone(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2gyyptrco.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.tianlin.xyz/Article/details/gt2qasnhupq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shuidangran.top/Article/details/gt2kluogoje.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hongshengwenyu.top/Article/details/gt2bbdgvmej.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.chenlongwang.top/Article/details/gt2hruudyxp.html

[K06] 解析 URL 查询串
来源：http://dali.ppjwa.cn/Article/details/gt2psjkvhth.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jyoumei.cn/Article/details/gt2afnaefzw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ybcxt.top/Article/details/gt2rmnijutg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xziqi.cn/Article/details/gt2hcawknqq.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jianghu66.top/Article/details/gt2ehxttmnz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.svipenyu.cn/Article/details/gt2xxfyinet.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kuaaqyjw.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ivvv.top/Article/details/gt2xkjojtoy.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gt2parjbmxx.html

[K07] 进制转换
来源：http://dali.hongshengwenyu.top/Article/details/gt2fhdvrwce.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gt2tslgdjpt.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.aizwys.cn/Article/details/gt2nilpkqij.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gt2dndlawzs.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qwzhrdor.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gt2ooyzzuyc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ydzc1.top/Article/details/gt2yekryefs.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.tanke756.top/Article/details/gt2nurmstse.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gt2kkrtmgco.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.dashuyun.cn/Article/details/gt2eaopvjqz.html

Py:   pickle.dumps(obj)
来源：http://dali.yj20258888.top/Article/details/gt2nnkthvpj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yuanzhike.top/Article/details/gt2lxtkbbpl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cheryme.top/Article/details/gt2lvahvlxw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jianghu66.top/Article/details/gt2iyldliva.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ydzc1.top/Article/details/gt2tzhbkgct.html

Go:   encoding/gob
来源：http://dali.316326.xyz/Article/details/gt2uyrpands.html

Ruby: Marshal.dump(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2aputmbob.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.sxryk.cn/Article/details/gt2beffctzy.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2cnzhphtd.html

L. 网络请求
来源：http://dali.tanke756.top/Article/details/gt2gdtlmjxi.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2icieqieu.html

[L01] 发送 GET 请求
来源：http://dali.c1oappe.top/Article/details/gt2iqktfhpv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.nanxuanxn.top/Article/details/gt2ttaybgyp.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.tianlin.xyz/Article/details/gt2diguvqcs.html

JS:   await fetch(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2idjlrzkf.html

TS:   await fetch(url)
来源：http://dali.chenzaomai.com/Article/details/gt2mjcreowx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gaohongyu789.top/Article/details/gt2kvzufiff.html

Go:   resp, err := http.Get(url)
来源：http://dali.chenlongwang.top/Article/details/gt2lwbcakfm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2dfpifmnn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jlsjyb.cn/Article/details/gt2lwhbcyks.html

[L02] 发送 POST JSON
来源：http://dali.yj20258.top/Article/details/gt2sztyddae.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gaohongyu789.top/Article/details/gt2wppqrftt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.aizwys.cn/Article/details/gt2ymowhcny.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj20258888.top/Article/details/gt2hyoqlxui.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xylfe.cn/Article/details/gt2wgekqpqi.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhoulong.xyz/Article/details/gt2zexiaqtx.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.mhx1999.top/Article/details/gt2pjdyxutj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rlheuzxd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cqqwz.cn/Article/details/gt2bmuxgdlr.html

[L03] 设置自定义请求头
来源：http://dali.sysykeji.top/Article/details/gt2irziuwja.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hqujneis.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hammf.cn/Article/details/gt2tlulrckh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2znjaqwdi.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuxming.cn/Article/details/gt2phzlzjqg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jyoumei.cn/Article/details/gt2kryzlgmw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.fzhhl.top/Article/details/gt2wqmqeilp.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.c1oappe.top/Article/details/gt2kszwvnec.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.bjfxy.top/Article/details/gt2xkfavhqv.html

[L04] 设置超时
来源：http://dali.gzhubu.top/Article/details/gt2xavyhawc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jqgufenzy.top/Article/details/gt2biviiflg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sufxvd.cn/Article/details/gt2prdptgnw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dashuyun.cn/Article/details/gt2gnggtdpv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cashguo.top/Article/details/gt2ifhrzhgs.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.tanke756.top/Article/details/gt2exantskb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhoulong.xyz/Article/details/gt2vrvufawc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rpqfkbuj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sxryk.cn/Article/details/gt2trygrnro.html

[L05] 上传文件（multipart）
来源：http://dali.gogol.net.cn/Article/details/gt2mktqzvea.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hammf.cn/Article/details/gt2kjbszkxl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.tanke756.top/Article/details/gt2fhhtfoxn.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gzsqfxcc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xinyue.icu/Article/details/gt2drulbrum.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.svipenyu.cn/Article/details/gt2apdsxlix.html


<!-- 参考信息 -->