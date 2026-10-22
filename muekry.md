代发 wailian999

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.316326.xyz/Article/details/gt2kqkqyijv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.pengpengdd.cyou/Article/details/gt2tseyssqi.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sysykeji.top/Article/details/gt2henlblhu.html

[H10] 资源自动释放
来源：http://dali.shangyingyoupin.top/Article/details/gt2yikmotml.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.0kj1m.cn/Article/details/gt2rygvwacd.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yuanzhike.top/Article/details/gt2fuokfvbo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhiwuduotai.top/Article/details/gt2zrzcxtsb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhiwuduotai.top/Article/details/gt2cziamerj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hammf.cn/Article/details/gt2myaxqxbv.html

Go:   defer f.Close()
来源：http://dali.zhiwuduotai.top/Article/details/gt2renxaugz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nwehnvsf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gt2otvifyce.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2qqxxrtgb.html

I. 正则表达式
来源：http://dali.chenzaomai.com/Article/details/gt2lirbnvzr.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2gwevjamv.html

[I01] 判断是否匹配
来源：http://dali.chenlongwang.top/Article/details/gt2nomlpers.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.nanxuanxn.top/Article/details/gt2tnhamtsh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.guowangkeji.top/Article/details/gt2ivmkffox.html

JS:   /\d+/.test(s)
来源：http://dali.hammf.cn/Article/details/gt2kxkybotn.html

TS:   /\d+/.test(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yldbpuij.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cdnleiting.top/Article/details/gt2jrqgzlec.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.fzhhl.top/Article/details/gt2lqnxvuut.html

Ruby: s.match?(/\d+/)
来源：http://dali.xuanzx.com/Article/details/gt2zfkxyjuh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xylfe.cn/Article/details/gt2njcksslu.html

[I02] 提取所有匹配
来源：http://dali.smart0.xyz/Article/details/gt2xgljuxhw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.guowangkeji.top/Article/details/gt2xdxphxds.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.daxiang520.top/Article/details/gt2leeudffy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jianghu66.top/Article/details/gt2tjjqcnmp.html

TS:   s.match(/\d+/g)
来源：http://dali.316326.xyz/Article/details/gt2bjggxnny.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.daria6918.cn/Article/details/gt2rnxxibsv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhongyouzk.top/Article/details/gt2fozhrier.html

Ruby: s.scan(/\d+/)
来源：http://dali.nwbrower.top/Article/details/gt2jknyqbra.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bajwxovk.html

[I03] 提取捕获分组
来源：http://dali.mhx1999.top/Article/details/gt2rrafkocn.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yj20258.top/Article/details/gt2fwcillem.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sweek.top/Article/details/gt2wxbpghal.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.mhx1999.top/Article/details/gt2eopppvgq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jiagoushi.top/Article/details/gt2awcxyweh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.aizwys.cn/Article/details/gt2buzsvdgj.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gogol.net.cn/Article/details/gt2dvzvrenu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yonumen.top/Article/details/gt2qfkgzouh.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zycfv.cn/Article/details/gt2vlgzbzhn.html

[I04] 正则替换
来源：http://dali.tanke756.top/Article/details/gt2slvyrtkb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhongyouzk.top/Article/details/gt2thquzjoe.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jqgfzy.top/Article/details/gt2mdtplbsw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhiwuduotai.top/Article/details/gt2hxgxqzez.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.pycfn.com/Article/details/gt2endlgsen.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xuanzx.com/Article/details/gt2afilgukm.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.fzhhl.top/Article/details/gt2qnocrvvy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sufxvd.cn/Article/details/gt2gqxzerff.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.wangdashe.top/Article/details/gt2rvlcptxd.html

[I05] 按正则拆分
来源：http://dali.shuidangran.top/Article/details/gt2esujtnqh.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jianghu66.top/Article/details/gt2uaycdvap.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.guannengcc.top/Article/details/gt2cgnkcnak.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.tian-w.cn/Article/details/gt2nlqpuvza.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xziqi.cn/Article/details/gt2kjdvleyn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.guannengcc.top/Article/details/gt2lslphmwq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jlsjyb.cn/Article/details/gt2zrwpnrtt.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gt2dgjhhrug.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yongpay.top/Article/details/gt2zrwygbjz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.tanke756.top/Article/details/gt2mrfnhybq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2pubfnazc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tlpsvdcu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.haohaochexian.top/Article/details/gt2ktcylejw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jiagoushi.top/Article/details/gt2sxwnyhdd.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yueranfly.top/Article/details/gt2pgdtqpup.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ydzc1.top/Article/details/gt2glnkkyrn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yuxming.cn/Article/details/gt2vuyiizpx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yongpay.top/Article/details/gt2pwemqcfj.html

[I07] 忽略大小写与多行模式
来源：http://dali.yueranfly.top/Article/details/gt2ylvzglnm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ppjwa.cn/Article/details/gt2ifzogapi.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.guannengcc.top/Article/details/gt2mmruflrq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.guowangkeji.top/Article/details/gt2wiypqrvz.html

TS:   /error/gim
来源：http://dali.hammf.cn/Article/details/gt2urpauwsw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.bjfxy.top/Article/details/gt2kzlpjsqm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wgfbnvhp.html

Ruby: s.scan(/error/i)
来源：http://dali.xuetiantiany.cn/Article/details/gt2llyszlth.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yuxming.cn/Article/details/gt2fnezdoky.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jqgufenzy.top/Article/details/gt2sceibmtb.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yongpay.top/Article/details/gt2pvpmlhct.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.svipenyu.cn/Article/details/gt2jingpjgh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ytxyhttz.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cqqwz.cn/Article/details/gt2qkjhnqzd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zuppdhco.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nyhukwwa.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hfpthk.cn/Article/details/gt2vazltply.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.vqdsnc.cn/Article/details/gt2lwlshhow.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2mqcayeix.html

J. 日期与时间
来源：http://dali.aibaodan.cn/Article/details/gt2zwquuorm.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2hcolqufq.html

[J01] 获取当前时间
来源：http://dali.0kj1m.cn/Article/details/gt2qesimqek.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.pengpengdd.cyou/Article/details/gt2svnosayp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.bjfxy.top/Article/details/gt2jmsuljub.html

JS:   new Date();  Date.now()
来源：http://dali.shangyingyoupin.top/Article/details/gt2mxvaxqrl.html

TS:   new Date();  Date.now()
来源：http://dali.hammf.cn/Article/details/gt2dqimbctz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jqgfzy.top/Article/details/gt2smdetzni.html

Go:   time.Now()
来源：http://dali.aizwys.cn/Article/details/gt2eqdpgsml.html

Ruby: Time.now
来源：http://dali.yongpay.top/Article/details/gt2gspvsexn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenjidiqi.icu/Article/details/gt2dhxfgqti.html

[J02] 格式化输出
来源：http://dali.xziqi.cn/Article/details/gt2inirjikv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.birdmap.top/Article/details/gt2ervdaaru.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shangyingyoupin.top/Article/details/gt2feeemiou.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinqigfzy.top/Article/details/gt2crfyfdvp.html

TS:   d.toISOString()
来源：http://dali.xuetiantiany.cn/Article/details/gt2wohofhmd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jianghu66.top/Article/details/gt2exlkrwgr.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhongyouzk.top/Article/details/gt2epljaagn.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xinyue.icu/Article/details/gt2xdzlbbep.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tqylmfxn.html

[J03] 字符串解析为日期
来源：http://dali.yj202588.top/Article/details/gt2fuwurnti.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.dianchejie.cn/Article/details/gt2htupggcd.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shangyingyoupin.top/Article/details/gt2maopegqy.html

JS:   new Date("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gt2aghoqruc.html

TS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bpolxewr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gt2sviadwls.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gt2xokxujle.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hzpmiylm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jiagoushi.top/Article/details/gt2fnmdgurq.html

[J04] 时间戳与日期互转
来源：http://dali.yuxming.cn/Article/details/gt2odkofqbd.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yangfankeji.com/Article/details/gt2wvszxxas.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.daxiang520.top/Article/details/gt2jgyduhqd.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aymhedcq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.chenzaomai.com/Article/details/gt2qkhrwyxc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sweek.top/Article/details/gt2fyoleexy.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xinyue.icu/Article/details/gt2myzsvjda.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zdqjudy.top/Article/details/gt2hiwkrdec.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nwbrower.top/Article/details/gt2lmmsjawx.html

[J05] 时间加减（加 7 天）
来源：http://dali.yongpay.top/Article/details/gt2mbhczrhe.html

Py:   now + timedelta(days=7)
来源：http://dali.svipenyu.cn/Article/details/gt2eoxymnui.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zycfv.cn/Article/details/gt2enmltpbh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xinyue.icu/Article/details/gt2ptjpposl.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.redwolf501.top/Article/details/gt2fxmsaqlj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpurtmfz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cvvglejv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jinqigfzy.top/Article/details/gt2frflxdbh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2czurfeuo.html

[J06] 计算两时间之差
来源：http://dali.cqqwz.cn/Article/details/gt2rgjpumhk.html

Py:   (end - start).total_seconds()
来源：http://dali.nanxuanxn.top/Article/details/gt2qrecdvma.html

PHP:  $end->diff($start)->days;
来源：http://dali.wangshuangyany.cn/Article/details/gt2bhporscp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ppjwa.cn/Article/details/gt2yruhgjgc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xziqi.cn/Article/details/gt2giiztzut.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gzhubu.top/Article/details/gt2dqrkarky.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhixingplan.top/Article/details/gt2jpdzindx.html

Ruby: end - start                 # 返回秒数
来源：http://dali.nwbrower.top/Article/details/gt2zofyvlxb.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj20258.top/Article/details/gt2auvwmwsy.html

[J07] 比较两个日期
来源：http://dali.jqgufenzy.top/Article/details/gt2seudfsnv.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gnilleiy.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.aizwys.cn/Article/details/gt2ivizqbti.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.316326.xyz/Article/details/gt2qfeknctx.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sxryk.cn/Article/details/gt2kyvbgxot.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.chenlongwang.top/Article/details/gt2zssjptsc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yuxming.cn/Article/details/gt2hwwydwdk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yj20258888.top/Article/details/gt2njvmmktk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xuetiantiany.cn/Article/details/gt2ycohhepr.html

[J08] 提取年月日与星期
来源：http://dali.guannengcc.top/Article/details/gt2zgipsffd.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.snrcjt.cn/Article/details/gt2tryybehy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ybrbkkgj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jianghu66.top/Article/details/gt2sxbwkpgw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.havefunace.top/Article/details/gt2ggnlmiec.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jianghu66.top/Article/details/gt2xgqcsyyt.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sufxvd.cn/Article/details/gt2leqngzyi.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tanke756.top/Article/details/gt2ftbjdrlk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yueranfly.top/Article/details/gt2tqnstxiz.html

[J09] 时区处理
来源：http://dali.yj20258.top/Article/details/gt2fwckjopo.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2utsquuwf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.9152youxi.cn/Article/details/gt2ruaainws.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yongpay.top/Article/details/gt2znvsqefp.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hxjwvviq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.0kj1m.cn/Article/details/gt2qorzdxoo.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkvftlrh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.wangdashe.top/Article/details/gt2haszbeyz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.aibaodan.cn/Article/details/gt2jnwiqsje.html

[J10] 取今天 / 本月第一天
来源：http://dali.gotoacloud.top/Article/details/gt2rsxzypok.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.fzhhl.top/Article/details/gt2ghecmpka.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sysykeji.top/Article/details/gt2qejjlxhc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ydzc1.top/Article/details/gt2vucottex.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gt2pjeqgxmj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xziqi.cn/Article/details/gt2uwhdhhip.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shangyingyoupin.top/Article/details/gt2iwgxmbkm.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jianghu66.top/Article/details/gt2fymwlysa.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jiagoushi.top/Article/details/gt2nqxihkce.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2gjukmazj.html

K. JSON 与序列化
来源：http://dali.nanxinkj.top/Article/details/gt2onmncabm.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2dawylaby.html

[K01] 对象转 JSON 字符串
来源：http://dali.sxryk.cn/Article/details/gt2haumomof.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ivvv.top/Article/details/gt2jbwkofww.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2injuxivp.html

JS:   JSON.stringify(obj)
来源：http://dali.redwolf501.top/Article/details/gt2rexifbeu.html

TS:   JSON.stringify(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2angmlkwd.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ydzc1.top/Article/details/gt2fogbbmiz.html

Go:   json.Marshal(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2dcvclstm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yj20258.top/Article/details/gt2pggcbagc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xinyue.icu/Article/details/gt2mdgmjjzl.html

[K02] JSON 字符串转对象
来源：http://dali.hnqzz.top/Article/details/gt2jwwednzb.html

Py:   json.loads(s)
来源：http://dali.meibo888.top/Article/details/gt2wyiixthw.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.birdmap.top/Article/details/gt2rjjfltva.html

JS:   JSON.parse(s)
来源：http://dali.aizwys.cn/Article/details/gt2zkzeajfx.html

TS:   JSON.parse(s)
来源：http://dali.yangfankeji.com/Article/details/gt2bbvkntmp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gt2ncsatguy.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sxryk.cn/Article/details/gt2yfyhslod.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qewvedht.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.havefunace.top/Article/details/gt2vnpdyeql.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xuanzx.com/Article/details/gt2zzeysipi.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yj20258888.top/Article/details/gt2bxczbfdq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ivvv.top/Article/details/gt2dfapleob.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.0kj1m.cn/Article/details/gt2pxhasntn.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xinyue.icu/Article/details/gt2czrxpmrn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2mtaptzwp.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cheryme.top/Article/details/gt2zztcwhyg.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.tanke756.top/Article/details/gt2nbgqhpgu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.316326.xyz/Article/details/gt2ngrltitz.html

[K04] 读取 JSON 文件
来源：http://dali.aibaodan.cn/Article/details/gt2bkcqwqpy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.quarkkingdee.top/Article/details/gt2alswwpty.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.fengsongda.top/Article/details/gt2gszrioou.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gotoacloud.top/Article/details/gt2mniwecae.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ehwqpu.com/Article/details/gt2fmdmfgut.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhcsawtq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cqqwz.cn/Article/details/gt2qtwgquga.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gotoacloud.top/Article/details/gt2jhnczvna.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.fengsongda.top/Article/details/gt2miteeife.html

[K05] 深拷贝对象
来源：http://dali.ydzc1.top/Article/details/gt2yrcmgkio.html

Py:   copy.deepcopy(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2smthqegw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.quarkkingdee.top/Article/details/gt2hnyethzy.html

JS:   structuredClone(obj)
来源：http://dali.tian-w.cn/Article/details/gt2ywfhxrfj.html

TS:   structuredClone(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2wokylgkq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xuetiantiany.cn/Article/details/gt2vlktptbm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hnxiangtu.top/Article/details/gt2mehrxocw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.dianchejie.cn/Article/details/gt2hhvyxpgc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sysykeji.top/Article/details/gt2owgknryq.html

[K06] 解析 URL 查询串
来源：http://dali.tanke756.top/Article/details/gt2ecalfthy.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xinyue.icu/Article/details/gt2zkskkqql.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.redwolf501.top/Article/details/gt2tlbhzudk.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aibaodan.cn/Article/details/gt2vwjwpmhd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258.top/Article/details/gt2wdfglmhb.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.tanke756.top/Article/details/gt2emetbgkk.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gt2aakgiqwt.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.kuanghao11.cn/Article/details/gt2bstmyhgj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.andypj.xyz/Article/details/gt2ufjzzdym.html

[K07] 进制转换
来源：http://dali.jlsjyb.cn/Article/details/gt2ookdsfep.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gt2fziqjbmh.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhongyouzk.top/Article/details/gt2mlgupxsj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gt2qivuoufc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.pycfn.com/Article/details/gt2lvpxszfh.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gt2kjbhprld.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yj202588.top/Article/details/gt2iomdyjfv.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jqgfzy.top/Article/details/gt2vagalzxy.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gt2tyymiela.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.aibaodan.cn/Article/details/gt2jakztsao.html

Py:   pickle.dumps(obj)
来源：http://dali.smart0.xyz/Article/details/gt2fenkzzcv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hnxiangtu.top/Article/details/gt2deoyvmcw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gogol.net.cn/Article/details/gt2eznyvwmg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xuetiantiany.cn/Article/details/gt2ilwugicj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2pmatlyqu.html

Go:   encoding/gob
来源：http://dali.yangfankeji.com/Article/details/gt2zetrpktf.html

Ruby: Marshal.dump(obj)
来源：http://dali.yueranfly.top/Article/details/gt2ffbgxjnb.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ydzc1.top/Article/details/gt2vepdcbrh.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2wxukftth.html

L. 网络请求
来源：http://dali.hammf.cn/Article/details/gt2apkeetjc.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2frvcatfa.html

[L01] 发送 GET 请求
来源：http://dali.chenlongwang.top/Article/details/gt2uvxllsck.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.aizwys.cn/Article/details/gt2mpludxpp.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cheryme.top/Article/details/gt2uvtfofpv.html

JS:   await fetch(url)
来源：http://dali.shuidangran.top/Article/details/gt2nfkgcfar.html

TS:   await fetch(url)
来源：http://dali.meibo888.top/Article/details/gt2amdtrvzu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cucudq.cn/Article/details/gt2xrctdzhs.html

Go:   resp, err := http.Get(url)
来源：http://dali.chenzaomai.com/Article/details/gt2fjjugpsv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.feifeiyinyue.top/Article/details/gt2luyjsbtf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yangfankeji.com/Article/details/gt2bevereay.html

[L02] 发送 POST JSON
来源：http://dali.aizwys.cn/Article/details/gt2cytqfnpz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2oxccyule.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yongpay.top/Article/details/gt2nqzvhekb.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuxming.cn/Article/details/gt2ktcactqg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.feifeiyinyue.top/Article/details/gt2uzuuvobh.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.pengpengdd.cyou/Article/details/gt2bronefuu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.guowangkeji.top/Article/details/gt2ubhgofqf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.aizwys.cn/Article/details/gt2obhlpwpo.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhengqikj.top/Article/details/gt2ytcwleur.html

[L03] 设置自定义请求头
来源：http://dali.jinqigfzy.top/Article/details/gt2iexomixf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jqgufenzy.top/Article/details/gt2ihontvjs.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.aizwys.cn/Article/details/gt2qlvrzndi.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.smart0.xyz/Article/details/gt2wbyddtqn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gogol.net.cn/Article/details/gt2gcpbpvyc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.daxiang520.top/Article/details/gt2cxuxhfcu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jqgfzy.top/Article/details/gt2sofdfntt.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhiwuduotai.top/Article/details/gt2oeerhjxw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shzxlz.cn/Article/details/gt2gpyhmgsp.html

[L04] 设置超时
来源：http://dali.dashuyun.cn/Article/details/gt2xcorbsdg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yanxiufei.cn/Article/details/gt2ofttezpb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cashguo.top/Article/details/gt2csuntone.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2amheysxm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cucudq.cn/Article/details/gt2sqiovfhv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.quarkkingdee.top/Article/details/gt2nkuqobzh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.redwolf501.top/Article/details/gt2ekjamxfx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hongshengwenyu.top/Article/details/gt2eonuvnmf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sysykeji.top/Article/details/gt2dqmllcfu.html

[L05] 上传文件（multipart）
来源：http://dali.ehwqpu.com/Article/details/gt2gynfgsvz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gogol.net.cn/Article/details/gt2qhkhnkxy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.nanxinkj.top/Article/details/gt2knaajhui.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhixingplan.top/Article/details/gt2dcnhpdkg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jianghu66.top/Article/details/gt2psiuatdc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cheryme.top/Article/details/gt2bxivtmjn.html


<!-- 参考信息 -->