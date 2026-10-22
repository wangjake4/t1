代发 wailian999

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.havefunace.top/Article/details/gtupexyses.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.chenjidiqi.icu/Article/details/gtorjaknwb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfvmtzaoh.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.feifeiyinyue.top/Article/details/gtbufgyuwv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.9152youxi.cn/Article/details/gtttogegcy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gtgwyxvror.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xylfe.cn/Article/details/gtinkbphmh.html

[H10] 资源自动释放
来源：http://dali.yanxiufei.cn/Article/details/gtbvhwtmrp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.haohaochexian.top/Article/details/gtirxvuzkn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hfpthk.cn/Article/details/gtaiaoqvyq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yongpay.top/Article/details/gthfsvavji.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yueranfly.top/Article/details/gtcrkhgvcd.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.fengsongda.top/Article/details/gtztlhyzok.html

Go:   defer f.Close()
来源：http://dali.hywenlv.cn/Article/details/gtzczmfpja.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxkptkold.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtyaroawry.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtzwizhmky.html

I. 正则表达式
来源：http://dali.ivvv.top/Article/details/gtujquukqn.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtnbzgwquw.html

[I01] 判断是否匹配
来源：http://dali.gaohongyu789.top/Article/details/gtxgmnmicu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.quarkkingdee.top/Article/details/gtyhvgvydj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtbyydzynr.html

JS:   /\d+/.test(s)
来源：http://dali.sweek.top/Article/details/gtyakmihof.html

TS:   /\d+/.test(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtcorpykni.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cqqwz.cn/Article/details/gtuqbeltkc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xylfe.cn/Article/details/gtfpguuihy.html

Ruby: s.match?(/\d+/)
来源：http://dali.tanke756.top/Article/details/gtcwusqxdl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.0kj1m.cn/Article/details/gtvobpbyho.html

[I02] 提取所有匹配
来源：http://dali.cucudq.cn/Article/details/gtzunpmkxd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shzxlz.cn/Article/details/gtmpdqrrvt.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cucudq.cn/Article/details/gtcwpumlvt.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.havefunace.top/Article/details/gtskeiwxcs.html

TS:   s.match(/\d+/g)
来源：http://dali.daxiang520.top/Article/details/gtmkgudcty.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gogol.net.cn/Article/details/gtrskruptu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.mhx1999.top/Article/details/gtflkxcops.html

Ruby: s.scan(/\d+/)
来源：http://dali.mhx1999.top/Article/details/gtkzhyqnya.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gtkscjicyl.html

[I03] 提取捕获分组
来源：http://dali.xylfe.cn/Article/details/gtbucbvhlj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtwxsytjyf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.kuanghao11.cn/Article/details/gtkzksvkcl.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xylfe.cn/Article/details/gtkijsvlnh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.birdmap.top/Article/details/gtsxrrbrtu.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.aibaodan.cn/Article/details/gtuuidzqcy.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.guannengcc.top/Article/details/gtnfsfzgik.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gtaheswpiu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.dashuyun.cn/Article/details/gtpimnwukz.html

[I04] 正则替换
来源：http://dali.cqqwz.cn/Article/details/gtgznzcqko.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhoulong.xyz/Article/details/gtcubninec.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtbnnpoqpu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zycfv.cn/Article/details/gtaletannl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jyoumei.cn/Article/details/gthjiugkie.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gtadmsgpmw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gogol.net.cn/Article/details/gtktthjmut.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ivvv.top/Article/details/gtrfkuuzxf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcsqnznhn.html

[I05] 按正则拆分
来源：http://dali.jianghu66.top/Article/details/gttktxmsos.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.dashuyun.cn/Article/details/gtkznbjmzx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenlongwang.top/Article/details/gtvohrmdwj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ivvv.top/Article/details/gtpvkpveqx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.aibaodan.cn/Article/details/gtaebgjxlb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sxryk.cn/Article/details/gtucaxujzy.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.chenlongwang.top/Article/details/gtqipuymrb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cdnleiting.top/Article/details/gttfbcvpeb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.iojbl.cn/Article/details/gtmyrdwfyf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.tianlin.xyz/Article/details/gtyfytqphi.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hysaishi.cn/Article/details/gtbdzxqquv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.nanxuanxn.top/Article/details/gtitatmsbw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuanzx.com/Article/details/gtwrckmjsp.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.snrcjt.cn/Article/details/gtnvhgoknc.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.guowangkeji.top/Article/details/gtvysywnhu.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.quarkkingdee.top/Article/details/gtzakneejg.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gogol.net.cn/Article/details/gtnagjgbwx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yangfankeji.com/Article/details/gtvicvpkrp.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinqigufen.top/Article/details/gttpbssklg.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xinyue.icu/Article/details/gtiuyeiiec.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ppjwa.cn/Article/details/gtluukyvem.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.smart0.xyz/Article/details/gtmtzcnyba.html

TS:   /error/gim
来源：http://dali.nwbrower.top/Article/details/gtarlzkyck.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.pengpengdd.cyou/Article/details/gtzcycnhua.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.vqdsnc.cn/Article/details/gtwfdqgvvg.html

Ruby: s.scan(/error/i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcshagzal.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cucudq.cn/Article/details/gtfzjmfrhy.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jyoumei.cn/Article/details/gtdsifybjr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.wangshuangyany.cn/Article/details/gtpsemcdsq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinqigufen.top/Article/details/gtqeihjpfh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gtffrfggis.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.svipenyu.cn/Article/details/gtplsvbsup.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jiagoushi.top/Article/details/gtrqoaxiwa.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.9152youxi.cn/Article/details/gtivwtcypp.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jqgfzy.top/Article/details/gtltarfjjm.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gtrmalchjs.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtxvgrrfcu.html

J. 日期与时间
来源：http://dali.chenjidiqi.icu/Article/details/gtdpbezenl.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtzpavbyag.html

[J01] 获取当前时间
来源：http://dali.pengpengdd.cyou/Article/details/gtllmvjrjd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmrhdbure.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.svipenyu.cn/Article/details/gtmwdkxwdr.html

JS:   new Date();  Date.now()
来源：http://dali.redwolf501.top/Article/details/gtckdnbivo.html

TS:   new Date();  Date.now()
来源：http://dali.sxryk.cn/Article/details/gtrzzxowdd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.mhx1999.top/Article/details/gtryteovgz.html

Go:   time.Now()
来源：http://dali.ybcxt.top/Article/details/gtcrecyznt.html

Ruby: Time.now
来源：http://dali.zhoulong.xyz/Article/details/gtriqygrgv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenlongwang.top/Article/details/gtgzqpzlcw.html

[J02] 格式化输出
来源：http://dali.fengsongda.top/Article/details/gtakkvjmyt.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenzaomai.com/Article/details/gtspluqdza.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shanyushiyangkeji.top/Article/details/gttvvtwmxs.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shanyushiyangtech.top/Article/details/gtpcxaapau.html

TS:   d.toISOString()
来源：http://dali.aizwys.cn/Article/details/gtcaiaujbs.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.kuanghao11.cn/Article/details/gtwtosvlhx.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ehwqpu.com/Article/details/gtoaosgkjt.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cashguo.top/Article/details/gtkimapyvc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.0kj1m.cn/Article/details/gtuvhxtshz.html

[J03] 字符串解析为日期
来源：http://dali.redwolf501.top/Article/details/gtgimsxntv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.c1oappe.top/Article/details/gtlbgeermv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.smart0.xyz/Article/details/gtanrvtina.html

JS:   new Date("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gtrvjcelxx.html

TS:   new Date("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gthtrilznw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gttfkrmohd.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yj202588.top/Article/details/gtulrznnoi.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gthdklnkxu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxezxrxgy.html

[J04] 时间戳与日期互转
来源：http://dali.nanxuanxn.top/Article/details/gttaazevgj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.bjfxy.top/Article/details/gttcqpfsfg.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.bjfxy.top/Article/details/gtoavvvycq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.birdmap.top/Article/details/gtmqizjmtt.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.tianlin.xyz/Article/details/gthrhiklqd.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.smart0.xyz/Article/details/gtojygneqq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shzxlz.cn/Article/details/gtllylzjdg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sysykeji.top/Article/details/gtxlczeurn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gtsekwgart.html

[J05] 时间加减（加 7 天）
来源：http://dali.cheryme.top/Article/details/gtidkbuizb.html

Py:   now + timedelta(days=7)
来源：http://dali.0kj1m.cn/Article/details/gtnmiarnpp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.vqdsnc.cn/Article/details/gtjurpoddz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gaohongyu789.top/Article/details/gtgaivxzze.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hammf.cn/Article/details/gtzzhjdxhk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ydzc1.top/Article/details/gtnhlliwsi.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.tian-w.cn/Article/details/gtkdxrxyef.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cqqwz.cn/Article/details/gtzkhrwmpk.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hammf.cn/Article/details/gtwpwomfsr.html

[J06] 计算两时间之差
来源：http://dali.sufxvd.cn/Article/details/gtirgdxoyw.html

Py:   (end - start).total_seconds()
来源：http://dali.zhiwuduotai.top/Article/details/gtconkkdut.html

PHP:  $end->diff($start)->days;
来源：http://dali.sufxvd.cn/Article/details/gtwguccwcv.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hnqzz.top/Article/details/gtxrdyjmre.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.nanxinkj.top/Article/details/gtzqrwclat.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yueranfly.top/Article/details/gtuvsgstkd.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinqigufen.top/Article/details/gtrgknmsqo.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hysaishi.cn/Article/details/gtkkjviyup.html

C#:   (end - start).TotalSeconds
来源：http://dali.jiagoushi.top/Article/details/gtyjnbgmvd.html

[J07] 比较两个日期
来源：http://dali.jqgfzy.top/Article/details/gtouwewviu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gtokbgxtcm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.aizwys.cn/Article/details/gtpdhhflpi.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zycfv.cn/Article/details/gtawuihghz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhengqikj.top/Article/details/gtleyiqcms.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.guowangkeji.top/Article/details/gtvpqktrhw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gogol.net.cn/Article/details/gtaqxlqxqb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.pycfn.com/Article/details/gtuxckzvwv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.0kj1m.cn/Article/details/gtdpvcdldo.html

[J08] 提取年月日与星期
来源：http://dali.hywenlv.cn/Article/details/gtsupqxnoy.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhiwuduotai.top/Article/details/gtabafwgoi.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gotoacloud.top/Article/details/gtbytytjye.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cucudq.cn/Article/details/gtwtgupykj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.snrcjt.cn/Article/details/gtlwimqkwq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cdnleiting.top/Article/details/gtaeaarpkw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.guannengcc.top/Article/details/gtwqmaswrf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.fengsongda.top/Article/details/gtdwqzowkp.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hammf.cn/Article/details/gtbfldsszu.html

[J09] 时区处理
来源：http://dali.yongpay.top/Article/details/gtxhioprcq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.316326.xyz/Article/details/gthguyjimd.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.guannengcc.top/Article/details/gtcfmrrmea.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhiwuduotai.top/Article/details/gtueqezjpd.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgufenzy.top/Article/details/gtuadkodfq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jianghu66.top/Article/details/gtgzywhwcs.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.fzhhl.top/Article/details/gtydaiylnn.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.havefunace.top/Article/details/gteewqtjou.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtotbmnbwa.html

[J10] 取今天 / 本月第一天
来源：http://dali.aibaodan.cn/Article/details/gtygnnmwid.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.guannengcc.top/Article/details/gtjnqazbbn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yangfankeji.com/Article/details/gtfhquylxw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jlsjyb.cn/Article/details/gtsrcledes.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.fengsongda.top/Article/details/gtohrdankf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.mhx1999.top/Article/details/gtqzenvood.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zycfv.cn/Article/details/gtgprbdbuj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sufxvd.cn/Article/details/gtcgrbiijo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.svipenyu.cn/Article/details/gttqfjseke.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtucfkwocb.html

K. JSON 与序列化
来源：http://dali.aizwys.cn/Article/details/gtvivgzgly.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtyhdjcdyx.html

[K01] 对象转 JSON 字符串
来源：http://dali.hammf.cn/Article/details/gtdxqytdnp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtscopoiir.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hnxiangtu.top/Article/details/gtexhnilzo.html

JS:   JSON.stringify(obj)
来源：http://dali.ehwqpu.com/Article/details/gtbkvzapfs.html

TS:   JSON.stringify(obj)
来源：http://dali.iojbl.cn/Article/details/gtlqnglqem.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.tanke756.top/Article/details/gtedhttwsl.html

Go:   json.Marshal(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtnketaaqn.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.316326.xyz/Article/details/gtrwmivwwm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jyoumei.cn/Article/details/gtvmlqrtpp.html

[K02] JSON 字符串转对象
来源：http://dali.daria6918.cn/Article/details/gtosviqncu.html

Py:   json.loads(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtqeuekovd.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.iojbl.cn/Article/details/gtcipmfhww.html

JS:   JSON.parse(s)
来源：http://dali.nanxuanxn.top/Article/details/gthtmkwqbl.html

TS:   JSON.parse(s)
来源：http://dali.hnxiangtu.top/Article/details/gtyjikzgsv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xziqi.cn/Article/details/gtfuhnlexa.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.svipenyu.cn/Article/details/gtlureelmf.html

Ruby: JSON.parse(s)
来源：http://dali.quarkkingdee.top/Article/details/gtebnycjwz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.vqdsnc.cn/Article/details/gtoyyfxswm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zycfv.cn/Article/details/gtiwmvpxgn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.0kj1m.cn/Article/details/gtyfgminzn.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yueranfly.top/Article/details/gtimrnnica.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgufenzy.top/Article/details/gtnxidnrxc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hammf.cn/Article/details/gtoqazwoax.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shuidangran.top/Article/details/gtuxrzigjl.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sysykeji.top/Article/details/gtgqihykkc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.guannengcc.top/Article/details/gtpkzpkhhc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinghuilouyu.cn/Article/details/gtcfyizkgj.html

[K04] 读取 JSON 文件
来源：http://dali.daxiang520.top/Article/details/gtxscdgmst.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.chenzaomai.com/Article/details/gttqbpqejw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.nanxinkj.top/Article/details/gtcayqtxhf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shangyingyoupin.top/Article/details/gtmorngphh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tian-w.cn/Article/details/gtkizhzsrb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.andypj.xyz/Article/details/gtoqjxofrf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sweek.top/Article/details/gtbwomyefc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shzxlz.cn/Article/details/gtlrztjkya.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.tianlin.xyz/Article/details/gtcrunmzwb.html

[K05] 深拷贝对象
来源：http://dali.jiagoushi.top/Article/details/gtyeglzpsr.html

Py:   copy.deepcopy(obj)
来源：http://dali.sufxvd.cn/Article/details/gthljmxnmv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.svipenyu.cn/Article/details/gtylmkzphp.html

JS:   structuredClone(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtrxzxptit.html

TS:   structuredClone(obj)
来源：http://dali.sxryk.cn/Article/details/gtjwncrtwa.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sweek.top/Article/details/gticdzptun.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xylfe.cn/Article/details/gtjmtygfyv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.0kj1m.cn/Article/details/gtqzrsqeax.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yj202588.top/Article/details/gtjzgolgvl.html

[K06] 解析 URL 查询串
来源：http://dali.jiagoushi.top/Article/details/gtxjcngksn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cdnleiting.top/Article/details/gtaywmeuiw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cqqwz.cn/Article/details/gthsmnojll.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daria6918.cn/Article/details/gthsplxkbq.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yanxiufei.cn/Article/details/gtpacpdymi.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.havefunace.top/Article/details/gtevujduir.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xuetiantiany.cn/Article/details/gtsqkyhcow.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.guannengcc.top/Article/details/gtibqelhbb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.fzhhl.top/Article/details/gtqvkxsldy.html

[K07] 进制转换
来源：http://dali.chenlongwang.top/Article/details/gtrcuwoggv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gtmknoemxx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gtaxkdcnqh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gtryivovby.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gtymmdrwyw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gthbiizjbr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnueqbcbf.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yanxiufei.cn/Article/details/gtjzhnhujt.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gtlctegcmf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinghuilouyu.cn/Article/details/gteqzdthta.html

Py:   pickle.dumps(obj)
来源：http://dali.yueranfly.top/Article/details/gtasclwgcx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.guowangkeji.top/Article/details/gtxujepirs.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.quarkkingdee.top/Article/details/gtzywngenh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.chenlongwang.top/Article/details/gttnyvvmqr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ydzc1.top/Article/details/gtpngnfnzi.html

Go:   encoding/gob
来源：http://dali.yueranfly.top/Article/details/gtecrqwhen.html

Ruby: Marshal.dump(obj)
来源：http://dali.ybcxt.top/Article/details/gtidzxvqfv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ppjwa.cn/Article/details/gtljoywagy.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtsjfxnyuk.html

L. 网络请求
来源：http://dali.shanyushiyangtech.top/Article/details/gtzuuwstdh.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gteuptxqae.html

[L01] 发送 GET 请求
来源：http://dali.yj202588.top/Article/details/gtnzjhushy.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.aibaodan.cn/Article/details/gtplwlnvqc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xziqi.cn/Article/details/gtjmspddrz.html

JS:   await fetch(url)
来源：http://dali.zhongyouzk.top/Article/details/gtykradeje.html

TS:   await fetch(url)
来源：http://dali.pengpengdd.cyou/Article/details/gtiwfdkykl.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yongpay.top/Article/details/gtcxkealao.html

Go:   resp, err := http.Get(url)
来源：http://dali.guannengcc.top/Article/details/gtdahgawzb.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sysykeji.top/Article/details/gtjdxugsos.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yvedp.cn/Article/details/gtapgpscyp.html

[L02] 发送 POST JSON
来源：http://dali.tanke756.top/Article/details/gtdnuuzuzn.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhiwuduotai.top/Article/details/gtoyvtftsx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhixingplan.top/Article/details/gtdwhmpqac.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fengsongda.top/Article/details/gtldninzdi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.bjfxy.top/Article/details/gtlgmtqjej.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shuidangran.top/Article/details/gttmejtdzv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gtnzlewwcd.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shuidangran.top/Article/details/gtbwjqcdol.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.c1oappe.top/Article/details/gtejhfsulg.html

[L03] 设置自定义请求头
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtizphtxmr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yongpay.top/Article/details/gtrsjzwedu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gogol.net.cn/Article/details/gtqioipfpu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xylfe.cn/Article/details/gtqnhxzbfq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hongshengwenyu.top/Article/details/gtjmeiogwb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shuidangran.top/Article/details/gttjjujgoq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.tanke756.top/Article/details/gttpcjdnyx.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yvedp.cn/Article/details/gttagbqeph.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yj202588.top/Article/details/gtysbokhid.html

[L04] 设置超时
来源：http://dali.hammf.cn/Article/details/gtirkbhcgp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cashguo.top/Article/details/gtkbwltbtg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sweek.top/Article/details/gthclafhrg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.guannengcc.top/Article/details/gtkpqneshd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jqgufenzy.top/Article/details/gtziwwfaag.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.snrcjt.cn/Article/details/gtzfycskoq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.nwbrower.top/Article/details/gtxbvgwniy.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.chenzaomai.com/Article/details/gtsbenigth.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.guannengcc.top/Article/details/gtwdppsjhg.html

[L05] 上传文件（multipart）
来源：http://dali.yueranfly.top/Article/details/gtoshsbnmy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sweek.top/Article/details/gtnndixcwi.html


<!-- 参考信息 -->