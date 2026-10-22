代发 wailian999

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jqgfzy.top/Article/details/gt2yfocqnoh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yj20258888.top/Article/details/gt2zmmfouje.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.birdmap.top/Article/details/gt2kldybhrw.html

[H10] 资源自动释放
来源：http://dali.svipenyu.cn/Article/details/gt2mtxumluk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.fzhhl.top/Article/details/gt2kipvvptv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.guannengcc.top/Article/details/gt2smswvmdc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.havefunace.top/Article/details/gt2mmcacdde.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.redwolf501.top/Article/details/gt2xqfxbsbe.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ppjwa.cn/Article/details/gt2zbmlygxg.html

Go:   defer f.Close()
来源：http://dali.wangshuangyany.cn/Article/details/gt2qmjysrra.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.birdmap.top/Article/details/gt2sabejxld.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xziqi.cn/Article/details/gt2sqgrnwta.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2slaczecb.html

I. 正则表达式
来源：http://dali.zhiwuduotai.top/Article/details/gt2qstqkqrw.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2tvsvkwot.html

[I01] 判断是否匹配
来源：http://dali.hammf.cn/Article/details/gt2dnrrjatp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jqgufenzy.top/Article/details/gt2oaxjqplc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yonumen.top/Article/details/gt2fahybgbp.html

JS:   /\d+/.test(s)
来源：http://dali.aibaodan.cn/Article/details/gt2kthyxulv.html

TS:   /\d+/.test(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ibvwyzvr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2akpnrsim.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gotoacloud.top/Article/details/gt2dgqliuhj.html

Ruby: s.match?(/\d+/)
来源：http://dali.shzxlz.cn/Article/details/gt2gwpezedb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.vqdsnc.cn/Article/details/gt2jexjatpn.html

[I02] 提取所有匹配
来源：http://dali.shangyingyoupin.top/Article/details/gt2idvdyqrf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.meibo888.top/Article/details/gt2iyjbpepf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.tian-w.cn/Article/details/gt2jzbwxikx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ydzc1.top/Article/details/gt2rnsvdwst.html

TS:   s.match(/\d+/g)
来源：http://dali.zhongyouzk.top/Article/details/gt2tqhukojh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.fengsongda.top/Article/details/gt2wzdsxchy.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jiagoushi.top/Article/details/gt2spuzmcxv.html

Ruby: s.scan(/\d+/)
来源：http://dali.quarkkingdee.top/Article/details/gt2itganfsx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sysykeji.top/Article/details/gt2yytyrasf.html

[I03] 提取捕获分组
来源：http://dali.xziqi.cn/Article/details/gt2syysurlv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.guannengcc.top/Article/details/gt2vbhwkcci.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yuanzhike.top/Article/details/gt2onbaotip.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.sysykeji.top/Article/details/gt2xdfvsvxd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shuidangran.top/Article/details/gt2hynwagtc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.chenlongwang.top/Article/details/gt2mqcdlvon.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yangfankeji.com/Article/details/gt2iqbbkgdz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ghzeuzib.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sweek.top/Article/details/gt2hwskddnf.html

[I04] 正则替换
来源：http://dali.yongpay.top/Article/details/gt2bjvpbevk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hysaishi.cn/Article/details/gt2kqvwqsew.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.guannengcc.top/Article/details/gt2ghdfbefm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xylfe.cn/Article/details/gt2lvveudir.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hysaishi.cn/Article/details/gt2wlzaxadn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xinyue.icu/Article/details/gt2zelnwbsx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yangfankeji.com/Article/details/gt2dehavhkx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yuanzhike.top/Article/details/gt2tgpbphwa.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.wangdashe.top/Article/details/gt2htfbrjyu.html

[I05] 按正则拆分
来源：http://dali.chenlongwang.top/Article/details/gt2mmuavbdg.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.guannengcc.top/Article/details/gt2dolzngfc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.tian-w.cn/Article/details/gt2jxkdiyxp.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.c1oappe.top/Article/details/gt2ttrbrufs.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.wangdashe.top/Article/details/gt2pmpeylyx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ydzc1.top/Article/details/gt2mclvfavo.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.316326.xyz/Article/details/gt2cnlyclvo.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.dianchejie.cn/Article/details/gt2vupldgdn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jlsjyb.cn/Article/details/gt2myxpopbm.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.kuanghao11.cn/Article/details/gt2ktlxoakj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhoulong.xyz/Article/details/gt2rfqrrskf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yj20258.top/Article/details/gt2hthbzwgl.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yonumen.top/Article/details/gt2ytfjnxop.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnxiangtu.top/Article/details/gt2qgoskozg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xuetiantiany.cn/Article/details/gt2liwwtnyx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yvedp.cn/Article/details/gt2bkzvurxl.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinghuilouyu.cn/Article/details/gt2unbohbqw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cheryme.top/Article/details/gt2xcechmyy.html

[I07] 忽略大小写与多行模式
来源：http://dali.cashguo.top/Article/details/gt2ofngxsnh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.daxiang520.top/Article/details/gt2snbucvmq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cdnleiting.top/Article/details/gt2kxhtrhhk.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.dianchejie.cn/Article/details/gt2slytyugu.html

TS:   /error/gim
来源：http://dali.cqqwz.cn/Article/details/gt2gpucjpff.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhongyouzk.top/Article/details/gt2fbaqdwkg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yueranfly.top/Article/details/gt2pczdknzq.html

Ruby: s.scan(/error/i)
来源：http://dali.zhiwuduotai.top/Article/details/gt2tuzbmzun.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhoulong.xyz/Article/details/gt2zploleon.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.chenzaomai.com/Article/details/gt2cboetajp.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hnqzz.top/Article/details/gt2zxjvmque.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jyoumei.cn/Article/details/gt2ojzmzavz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuetiantiany.cn/Article/details/gt2kkwxksye.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenzaomai.com/Article/details/gt2qrwcijsr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yuanzhike.top/Article/details/gt2ymhumwny.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.pengpengdd.cyou/Article/details/gt2eiogspmq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ztapqkpt.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.smart0.xyz/Article/details/gt2lpwrjkkw.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2ineqliks.html

J. 日期与时间
来源：http://dali.chenzaomai.com/Article/details/gt2rspphjdd.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2hjjtlxyn.html

[J01] 获取当前时间
来源：http://dali.yj202588.top/Article/details/gt2sdaumnhp.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhengqikj.top/Article/details/gt2fdmwimru.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zdqjudy.top/Article/details/gt2ecqbxchm.html

JS:   new Date();  Date.now()
来源：http://dali.cdnleiting.top/Article/details/gt2jayvsekt.html

TS:   new Date();  Date.now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rvnsqove.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hongshengwenyu.top/Article/details/gt2gbpjcbwb.html

Go:   time.Now()
来源：http://dali.chenjidiqi.icu/Article/details/gt2xqpiivxw.html

Ruby: Time.now
来源：http://dali.daria6918.cn/Article/details/gt2glzkwcol.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.wangshuangyany.cn/Article/details/gt2cdxneasq.html

[J02] 格式化输出
来源：http://dali.gogol.net.cn/Article/details/gt2qamkskte.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhengqikj.top/Article/details/gt2rabmdcnf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jqgufenzy.top/Article/details/gt2xeybdueu.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zdqjudy.top/Article/details/gt2tdlbmxjf.html

TS:   d.toISOString()
来源：http://dali.zycfv.cn/Article/details/gt2kyznxsby.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.dashuyun.cn/Article/details/gt2mjfyeegn.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hfpthk.cn/Article/details/gt2zjplitrc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daria6918.cn/Article/details/gt2joddmxjr.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.wangdashe.top/Article/details/gt2cfbyfayn.html

[J03] 字符串解析为日期
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yfizlybv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ivvv.top/Article/details/gt2micntrgi.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cashguo.top/Article/details/gt2vsrlaedz.html

JS:   new Date("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gt2yyzduful.html

TS:   new Date("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gt2kdxczrbk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gt2mjccdkfg.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gt2vwtdsiix.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gt2kczlgqdk.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.quarkkingdee.top/Article/details/gt2boyqduqz.html

[J04] 时间戳与日期互转
来源：http://dali.wangdashe.top/Article/details/gt2drvdrjfx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gotoacloud.top/Article/details/gt2mixdtufo.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhiwuduotai.top/Article/details/gt2tcrujfcd.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yueranfly.top/Article/details/gt2spwisahl.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.aibaodan.cn/Article/details/gt2dhuswmqf.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.birdmap.top/Article/details/gt2rasqsefh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.bjfxy.top/Article/details/gt2hynvrrhd.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xinyue.icu/Article/details/gt2oddiqdut.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.kuanghao11.cn/Article/details/gt2favkyyao.html

[J05] 时间加减（加 7 天）
来源：http://dali.hammf.cn/Article/details/gt2eznairqf.html

Py:   now + timedelta(days=7)
来源：http://dali.tanke756.top/Article/details/gt2nywtbhgt.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zycfv.cn/Article/details/gt2afmrjlzz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.feifeiyinyue.top/Article/details/gt2cebqdtfk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258.top/Article/details/gt2vhuadies.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.fzhhl.top/Article/details/gt2dsdfpgwq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ivvv.top/Article/details/gt2iydzghin.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hysaishi.cn/Article/details/gt2xvfjpcsh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hnxiangtu.top/Article/details/gt2eiytoicr.html

[J06] 计算两时间之差
来源：http://dali.ivvv.top/Article/details/gt2knmfcpuo.html

Py:   (end - start).total_seconds()
来源：http://dali.yj20258888.top/Article/details/gt2vqytlujr.html

PHP:  $end->diff($start)->days;
来源：http://dali.ehwqpu.com/Article/details/gt2hepqxspj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhongyouzk.top/Article/details/gt2ejdlrhtr.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.quarkkingdee.top/Article/details/gt2hniqfofv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.guowangkeji.top/Article/details/gt2lxonvgov.html

Go:   end.Sub(start).Hours()
来源：http://dali.hammf.cn/Article/details/gt2qyaeckus.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shuidangran.top/Article/details/gt2vvycvdpy.html

C#:   (end - start).TotalSeconds
来源：http://dali.gaohongyu789.top/Article/details/gt2dlveauoz.html

[J07] 比较两个日期
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pqhaznps.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.mhx1999.top/Article/details/gt2afzbdrut.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhongyouzk.top/Article/details/gt2nwjiifpq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ybcxt.top/Article/details/gt2aeayuesg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.nwbrower.top/Article/details/gt2ryblkzaw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sxryk.cn/Article/details/gt2jdtxpuxe.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yvedp.cn/Article/details/gt2vrrdwhoz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ydzc1.top/Article/details/gt2vymsksxm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hfpthk.cn/Article/details/gt2kgfhyhhx.html

[J08] 提取年月日与星期
来源：http://dali.daxiang520.top/Article/details/gt2hbanzbum.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yj20258888.top/Article/details/gt2yybnhxak.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gogol.net.cn/Article/details/gt2uhjulxbs.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hnqzz.top/Article/details/gt2eepjihwt.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.dianchejie.cn/Article/details/gt2wcutobhb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mpenndcn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhoulong.xyz/Article/details/gt2zsrlonhe.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.fengsongda.top/Article/details/gt2ycvpuqnx.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sufxvd.cn/Article/details/gt2jaznccrk.html

[J09] 时区处理
来源：http://dali.guannengcc.top/Article/details/gt2fulpipcd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shuidangran.top/Article/details/gt2xfhubmuu.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.snrcjt.cn/Article/details/gt2ddvoymyk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ivvv.top/Article/details/gt2kxltdwrs.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tian-w.cn/Article/details/gt2ztsvynqc.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yj202588.top/Article/details/gt2ozvmbkxu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.feifeiyinyue.top/Article/details/gt2yijrsiba.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nanxinkj.top/Article/details/gt2nqfobjse.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenzaomai.com/Article/details/gt2dqxhnxsa.html

[J10] 取今天 / 本月第一天
来源：http://dali.wangdashe.top/Article/details/gt2zlemetax.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zycfv.cn/Article/details/gt2idhzyysp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gaohongyu789.top/Article/details/gt2ldqldeci.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kqxmuyzq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.9152youxi.cn/Article/details/gt2oagxnyad.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.aibaodan.cn/Article/details/gt2dhpjwlzl.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinqigfzy.top/Article/details/gt2zaekswff.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.fzhhl.top/Article/details/gt2lugtibap.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ygmjdaea.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2smyozzcq.html

K. JSON 与序列化
来源：http://dali.jinqigfzy.top/Article/details/gt2xcsdxxyy.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2pwhdkrqz.html

[K01] 对象转 JSON 字符串
来源：http://dali.cqqwz.cn/Article/details/gt2udlrrrku.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jlsjyb.cn/Article/details/gt2lwtfeycn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.havefunace.top/Article/details/gt2lzbxgbfp.html

JS:   JSON.stringify(obj)
来源：http://dali.yj20258.top/Article/details/gt2lrbburhe.html

TS:   JSON.stringify(obj)
来源：http://dali.redwolf501.top/Article/details/gt2hkanqytk.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.aizwys.cn/Article/details/gt2galdbuvl.html

Go:   json.Marshal(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2lxgkxjmj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jlsjyb.cn/Article/details/gt2joxxqgyh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.nwbrower.top/Article/details/gt2fmhnegkz.html

[K02] JSON 字符串转对象
来源：http://dali.cashguo.top/Article/details/gt2mitjnkvb.html

Py:   json.loads(s)
来源：http://dali.daxiang520.top/Article/details/gt2efahzwgt.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xuetiantiany.cn/Article/details/gt2ejjsugye.html

JS:   JSON.parse(s)
来源：http://dali.zhengqikj.top/Article/details/gt2vywqmbme.html

TS:   JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gt2kpwkgvah.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ruihbeir.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fctzbugl.html

Ruby: JSON.parse(s)
来源：http://dali.yonumen.top/Article/details/gt2bewauhlc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ehwqpu.com/Article/details/gt2rzpjhwak.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.pycfn.com/Article/details/gt2bljhopee.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shuidangran.top/Article/details/gt2vblccmgl.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fiqughot.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnqzz.top/Article/details/gt2zieafmzi.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xebzqpqx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2ckggpddb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yj20258.top/Article/details/gt2eyzalkbs.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2kgazrrgd.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.chenjidiqi.icu/Article/details/gt2tnznsczd.html

[K04] 读取 JSON 文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2swnpmycq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.iojbl.cn/Article/details/gt2rqnilvkb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhengqikj.top/Article/details/gt2jnjameyg.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258.top/Article/details/gt2mwvqoyns.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2mxrlitop.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gotoacloud.top/Article/details/gt2viaxglcy.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sufxvd.cn/Article/details/gt2nunxyvhp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xylfe.cn/Article/details/gt2tqmmfaqj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.dashuyun.cn/Article/details/gt2iicrnolm.html

[K05] 深拷贝对象
来源：http://dali.pengpengdd.cyou/Article/details/gt2orupnfoi.html

Py:   copy.deepcopy(obj)
来源：http://dali.hammf.cn/Article/details/gt2dhknreel.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zcvjzrsr.html

JS:   structuredClone(obj)
来源：http://dali.zycfv.cn/Article/details/gt2gpcdtcun.html

TS:   structuredClone(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2rrmwvbmk.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rhgaljwt.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.birdmap.top/Article/details/gt2dbxmzply.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.redwolf501.top/Article/details/gt2dorxtgpp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shanyushiyangtech.top/Article/details/gt2syzlowtg.html

[K06] 解析 URL 查询串
来源：http://dali.haohaochexian.top/Article/details/gt2tczpnjcp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.pengpengdd.cyou/Article/details/gt2utmqjnpn.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.guannengcc.top/Article/details/gt2hifwdull.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.mhx1999.top/Article/details/gt2xhhftsnc.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ehwqpu.com/Article/details/gt2eytpqchr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.fengsongda.top/Article/details/gt2qmvbmwcr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yj202588.top/Article/details/gt2psudhglp.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2udlqejsu.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xuetiantiany.cn/Article/details/gt2cvymqaet.html

[K07] 进制转换
来源：http://dali.zhoulong.xyz/Article/details/gt2hgifyswc.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gt2qsputxda.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cheryme.top/Article/details/gt2jumzmbbt.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gt2hsnypsfp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gt2wsrmsmxq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gt2reackffd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xxfglqfw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shangyingyoupin.top/Article/details/gt2tthbxhym.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gt2ajaosfid.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sysykeji.top/Article/details/gt2mtfmmgxr.html

Py:   pickle.dumps(obj)
来源：http://dali.hnqzz.top/Article/details/gt2qshchuem.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinqigfzy.top/Article/details/gt2wzmprqre.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.kuanghao11.cn/Article/details/gt2vjuuaivo.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.svipenyu.cn/Article/details/gt2ddlrnqqg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jqgufenzy.top/Article/details/gt2jxwnusnb.html

Go:   encoding/gob
来源：http://dali.hywenlv.cn/Article/details/gt2ydhgckgs.html

Ruby: Marshal.dump(obj)
来源：http://dali.daxiang520.top/Article/details/gt2hnecazhx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ybcxt.top/Article/details/gt2iwkboszl.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2ghvuugzj.html

L. 网络请求
来源：http://dali.tian-w.cn/Article/details/gt2qmjkfzfm.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hsrhzogr.html

[L01] 发送 GET 请求
来源：http://dali.hfpthk.cn/Article/details/gt2phwrwihr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.feifeiyinyue.top/Article/details/gt2hlhbujbv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2djezjnkp.html

JS:   await fetch(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wldqommz.html

TS:   await fetch(url)
来源：http://dali.bjfxy.top/Article/details/gt2ujhliqod.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xuetiantiany.cn/Article/details/gt2xpvrkgfk.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinqigufen.top/Article/details/gt2eiuacwrr.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.316326.xyz/Article/details/gt2dbzuabjd.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ybcxt.top/Article/details/gt2qwnfyebe.html

[L02] 发送 POST JSON
来源：http://dali.haohaochexian.top/Article/details/gt2bjaanaim.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.nanxinkj.top/Article/details/gt2nljnkebc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ykecnexx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuanzx.com/Article/details/gt2qkycoaiq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shuidangran.top/Article/details/gt2paasselo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhixingplan.top/Article/details/gt2fpzypgue.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.guannengcc.top/Article/details/gt2qvosqpul.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shzxlz.cn/Article/details/gt2eglyzuiv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shuidangran.top/Article/details/gt2uwsraawr.html

[L03] 设置自定义请求头
来源：http://dali.mhx1999.top/Article/details/gt2zmqzykbt.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.chenlongwang.top/Article/details/gt2uqpxiuke.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jqgfzy.top/Article/details/gt2xipeirgs.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.birdmap.top/Article/details/gt2bmkprdii.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sxryk.cn/Article/details/gt2moiiqjqe.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sxryk.cn/Article/details/gt2ypvoxpiu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.smart0.xyz/Article/details/gt2axfbapjo.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ehwqpu.com/Article/details/gt2cjwhsvxd.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hnxiangtu.top/Article/details/gt2gtuhboeh.html

[L04] 设置超时
来源：http://dali.daxiang520.top/Article/details/gt2wlmezzxt.html

Py:   requests.get(url, timeout=5)
来源：http://dali.fengsongda.top/Article/details/gt2ialmdnxb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hnxiangtu.top/Article/details/gt2cfqdpzrl.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhengqikj.top/Article/details/gt2ecmbzsoc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dashuyun.cn/Article/details/gt2hytktpuk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.pycfn.com/Article/details/gt2nfktyffo.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yongpay.top/Article/details/gt2mimksfif.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.redwolf501.top/Article/details/gt2xoolfxbv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mkykxxkn.html

[L05] 上传文件（multipart）
来源：http://dali.yonumen.top/Article/details/gt2jafssedw.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cheryme.top/Article/details/gt2knmlayhz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.guowangkeji.top/Article/details/gt2wpkrkchr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cdnleiting.top/Article/details/gt2fidgizcr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zdqjudy.top/Article/details/gt2yghaybel.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.nwbrower.top/Article/details/gt2kgrsbrdl.html


<!-- 参考信息 -->