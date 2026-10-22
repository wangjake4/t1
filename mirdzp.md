代发 wailian999

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yongpay.top/Article/details/gt2gdmygzrf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shuidangran.top/Article/details/gt2tguxjbec.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.meibo888.top/Article/details/gt2fnvqueks.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.smart0.xyz/Article/details/gt2qbhzpknx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhixingplan.top/Article/details/gt2uzegdykl.html

Go:   defer f.Close()
来源：http://dali.meibo888.top/Article/details/gt2emmfmwci.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinqigufen.top/Article/details/gt2qzuyzcgd.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hammf.cn/Article/details/gt2todvmjpo.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2thrjzniz.html

I. 正则表达式
来源：http://dali.andypj.xyz/Article/details/gt2opbkppdi.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2ujvrcusp.html

[I01] 判断是否匹配
来源：http://dali.wangshuangyany.cn/Article/details/gt2nnfeibux.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xinyue.icu/Article/details/gt2bpuwvvhi.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinqigufen.top/Article/details/gt2csnpetzx.html

JS:   /\d+/.test(s)
来源：http://dali.ybcxt.top/Article/details/gt2zrnvrbyk.html

TS:   /\d+/.test(s)
来源：http://dali.yuanzhike.top/Article/details/gt2zlbudmbs.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.mhx1999.top/Article/details/gt2cigtwkvy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zycfv.cn/Article/details/gt2wwcfldsq.html

Ruby: s.match?(/\d+/)
来源：http://dali.gzhubu.top/Article/details/gt2arwfrhxk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.snrcjt.cn/Article/details/gt2fhkfdhmu.html

[I02] 提取所有匹配
来源：http://dali.xziqi.cn/Article/details/gt2yunrparg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yuxming.cn/Article/details/gt2bkysrput.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.wangshuangyany.cn/Article/details/gt2iiubsqpf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.chenzaomai.com/Article/details/gt2xcmmnlzt.html

TS:   s.match(/\d+/g)
来源：http://dali.gaohongyu789.top/Article/details/gt2tolejtoa.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pwlobfty.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ivvv.top/Article/details/gt2gastinot.html

Ruby: s.scan(/\d+/)
来源：http://dali.redwolf501.top/Article/details/gt2pdvrtmzy.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xziqi.cn/Article/details/gt2igpmlbtq.html

[I03] 提取捕获分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ysppgcgk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2zoerbfwq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yj20258.top/Article/details/gt2wucaadjq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.fzhhl.top/Article/details/gt2yzgfyhmr.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.dashuyun.cn/Article/details/gt2ogdlvilp.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinqigfzy.top/Article/details/gt2bkbrayfs.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jianghu66.top/Article/details/gt2coevkzyg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yvedp.cn/Article/details/gt2mmrnqpge.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.kuanghao11.cn/Article/details/gt2skjjsxgd.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjsstdg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hfpthk.cn/Article/details/gt2nekjouty.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.birdmap.top/Article/details/gt2zsavxmva.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.mhx1999.top/Article/details/gt2enhlvsrr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhengqikj.top/Article/details/gt2nwoxgqiy.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ydzc1.top/Article/details/gt2xtmvrthj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xylfe.cn/Article/details/gt2dwqouzqc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xziqi.cn/Article/details/gt2dvsfxlcf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.kuanghao11.cn/Article/details/gt2rwlrtnsn.html

[I05] 按正则拆分
来源：http://dali.fzhhl.top/Article/details/gt2ttsjodvz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.sweek.top/Article/details/gt2rrlhxamq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gotoacloud.top/Article/details/gt2ozdieckk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.tanke756.top/Article/details/gt2jflqwrfs.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cqqwz.cn/Article/details/gt2jjhkcgcm.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nanxinkj.top/Article/details/gt2lmmeguxq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.nwbrower.top/Article/details/gt2kedjhcae.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.tian-w.cn/Article/details/gt2cgbssbkj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yvedp.cn/Article/details/gt2lnicdtsc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ivvv.top/Article/details/gt2nlwwrinl.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.guowangkeji.top/Article/details/gt2zakrpbvs.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinghuilouyu.cn/Article/details/gt2flpucjpm.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cheryme.top/Article/details/gt2eeskylfv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aizwys.cn/Article/details/gt2ckayrqyo.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.smart0.xyz/Article/details/gt2uhcimxkt.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jqgfzy.top/Article/details/gt2caqqisiq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.fzhhl.top/Article/details/gt2ihtlocug.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2totbehfc.html

[I07] 忽略大小写与多行模式
来源：http://dali.yuanzhike.top/Article/details/gt2mxlzbmkz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yonumen.top/Article/details/gt2teebzgit.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.aibaodan.cn/Article/details/gt2auuvmmqn.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.tian-w.cn/Article/details/gt2youvjraw.html

TS:   /error/gim
来源：http://dali.jianghu66.top/Article/details/gt2kgvmbfgi.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ydzc1.top/Article/details/gt2hrnqvqqi.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yonumen.top/Article/details/gt2jmfbpdmx.html

Ruby: s.scan(/error/i)
来源：http://dali.jinqigufen.top/Article/details/gt2riecofja.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zdqjudy.top/Article/details/gt2jhtbcneb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yuanzhike.top/Article/details/gt2vaatkalm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhoulong.xyz/Article/details/gt2yrnmpsna.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hnxiangtu.top/Article/details/gt2wdeweyfg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenzaomai.com/Article/details/gt2aklmkynr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guannengcc.top/Article/details/gt2vjiurftz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yj20258.top/Article/details/gt2zezqugsn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.smart0.xyz/Article/details/gt2bxqqlwhr.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.tian-w.cn/Article/details/gt2zfknvuzt.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenzaomai.com/Article/details/gt2fuqeptko.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2zocjqlmi.html

J. 日期与时间
来源：http://dali.yongpay.top/Article/details/gt2szudwfbj.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2myqzkuoe.html

[J01] 获取当前时间
来源：http://dali.zhongyouzk.top/Article/details/gt2vxfgpdyr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cucudq.cn/Article/details/gt2zrewckop.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.316326.xyz/Article/details/gt2veykpwng.html

JS:   new Date();  Date.now()
来源：http://dali.redwolf501.top/Article/details/gt2wmtlkxpw.html

TS:   new Date();  Date.now()
来源：http://dali.gzhubu.top/Article/details/gt2otfzirni.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.vqdsnc.cn/Article/details/gt2fthciiee.html

Go:   time.Now()
来源：http://dali.zdqjudy.top/Article/details/gt2zqgeserh.html

Ruby: Time.now
来源：http://dali.kuanghao11.cn/Article/details/gt2djfjcphu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.316326.xyz/Article/details/gt2ikiyojuv.html

[J02] 格式化输出
来源：http://dali.hongshengwenyu.top/Article/details/gt2asucbyxr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ybcxt.top/Article/details/gt2zdlgphjq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ivvv.top/Article/details/gt2popmhzgk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mpohelyb.html

TS:   d.toISOString()
来源：http://dali.shuidangran.top/Article/details/gt2piyzrrzn.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gzhubu.top/Article/details/gt2ojqdgygq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhoulong.xyz/Article/details/gt2xkodgjrf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cheryme.top/Article/details/gt2txxabvpi.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hnxiangtu.top/Article/details/gt2gkiykqcj.html

[J03] 字符串解析为日期
来源：http://dali.jqgfzy.top/Article/details/gt2xkrxtpnv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xuetiantiany.cn/Article/details/gt2lgjqmghe.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sweek.top/Article/details/gt2gcenskrl.html

JS:   new Date("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gt2jaijbyxo.html

TS:   new Date("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gt2eahwtcvh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gt2mkvmvtlc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gt2fueoocmd.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gt2nyxkxxsk.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.birdmap.top/Article/details/gt2rakpnzqq.html

[J04] 时间戳与日期互转
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ykvhuqpg.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.chenzaomai.com/Article/details/gt2wqjggymr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eembmvyn.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xylfe.cn/Article/details/gt2wtdfkqia.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hysaishi.cn/Article/details/gt2rtbkjuqk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.316326.xyz/Article/details/gt2hkbejlho.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ppjwa.cn/Article/details/gt2pdgyylww.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.nanxuanxn.top/Article/details/gt2aoohwedr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ehwqpu.com/Article/details/gt2nsrgmkes.html

[J05] 时间加减（加 7 天）
来源：http://dali.316326.xyz/Article/details/gt2fwirasbn.html

Py:   now + timedelta(days=7)
来源：http://dali.meibo888.top/Article/details/gt2jonqmrsi.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.vqdsnc.cn/Article/details/gt2whmrfmdm.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jlsjyb.cn/Article/details/gt2tymbeqiw.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cdnleiting.top/Article/details/gt2aquomnao.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xuetiantiany.cn/Article/details/gt2taibomkj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.chenzaomai.com/Article/details/gt2ofmsikhq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.pengpengdd.cyou/Article/details/gt2syawmijy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.daxiang520.top/Article/details/gt2adzkpreu.html

[J06] 计算两时间之差
来源：http://dali.9152youxi.cn/Article/details/gt2njxrdlna.html

Py:   (end - start).total_seconds()
来源：http://dali.quarkkingdee.top/Article/details/gt2pbqkgefu.html

PHP:  $end->diff($start)->days;
来源：http://dali.tanke756.top/Article/details/gt2nytquyaf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sweek.top/Article/details/gt2qlylczzw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.andypj.xyz/Article/details/gt2wltrjabc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yvedp.cn/Article/details/gt2dbqczupe.html

Go:   end.Sub(start).Hours()
来源：http://dali.cdnleiting.top/Article/details/gt2nuacwipk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hongshengwenyu.top/Article/details/gt2pqoimuwd.html

C#:   (end - start).TotalSeconds
来源：http://dali.iojbl.cn/Article/details/gt2levjledb.html

[J07] 比较两个日期
来源：http://dali.hammf.cn/Article/details/gt2dtlczvqq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yuanzhike.top/Article/details/gt2eaggjhmn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cucudq.cn/Article/details/gt2hawpeqye.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhengqikj.top/Article/details/gt2tksflofg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cashguo.top/Article/details/gt2bnvndsoh.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cbrhxkvc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yuanzhike.top/Article/details/gt2meilwobd.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.nwbrower.top/Article/details/gt2avvywtip.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yanxiufei.cn/Article/details/gt2lxuystis.html

[J08] 提取年月日与星期
来源：http://dali.cashguo.top/Article/details/gt2vgsxsbrr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cheryme.top/Article/details/gt2ncrftlcp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.feifeiyinyue.top/Article/details/gt2scvljngh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.snrcjt.cn/Article/details/gt2eealknox.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yj20258888.top/Article/details/gt2druvvicb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fuczwymu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.wangdashe.top/Article/details/gt2fcbiymhi.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sxryk.cn/Article/details/gt2ahmmayab.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cheryme.top/Article/details/gt2vitydmpv.html

[J09] 时区处理
来源：http://dali.zhengqikj.top/Article/details/gt2prifdcvr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.mhx1999.top/Article/details/gt2bbcbywrr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hywenlv.cn/Article/details/gt2fibdjdsn.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258.top/Article/details/gt2wiepvjhi.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vwcyzmio.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.chenlongwang.top/Article/details/gt2bwdyzchm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sxryk.cn/Article/details/gt2xeinutgc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yongpay.top/Article/details/gt2prgjsgib.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.guannengcc.top/Article/details/gt2emfltpid.html

[J10] 取今天 / 本月第一天
来源：http://dali.yonumen.top/Article/details/gt2cdogmstk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.havefunace.top/Article/details/gt2pulommgj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.wangshuangyany.cn/Article/details/gt2vootumsu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gaohongyu789.top/Article/details/gt2ormugvnq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shuidangran.top/Article/details/gt2hovtkluo.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.guannengcc.top/Article/details/gt2ueedepoq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xuetiantiany.cn/Article/details/gt2ephuyzrn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.pycfn.com/Article/details/gt2eirnzkcx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hnxiangtu.top/Article/details/gt2yxnkbrfl.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2okqpeklx.html

K. JSON 与序列化
来源：http://dali.bjfxy.top/Article/details/gt2cmitokqg.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nwoqcdtx.html

[K01] 对象转 JSON 字符串
来源：http://dali.iojbl.cn/Article/details/gt2vdabgmeo.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hammf.cn/Article/details/gt2gzvmcujc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zdqjudy.top/Article/details/gt2mlsnoxth.html

JS:   JSON.stringify(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2wcidtdld.html

TS:   JSON.stringify(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2anylcnpq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cqqwz.cn/Article/details/gt2vfnziykl.html

Go:   json.Marshal(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2tlonzmqp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xuetiantiany.cn/Article/details/gt2lhealkyt.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bqkcpodd.html

[K02] JSON 字符串转对象
来源：http://dali.gotoacloud.top/Article/details/gt2nndnfkyo.html

Py:   json.loads(s)
来源：http://dali.yuanzhike.top/Article/details/gt2yjxszpee.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.havefunace.top/Article/details/gt2afelqyth.html

JS:   JSON.parse(s)
来源：http://dali.andypj.xyz/Article/details/gt2vwurqygj.html

TS:   JSON.parse(s)
来源：http://dali.cucudq.cn/Article/details/gt2revfzkgw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jianghu66.top/Article/details/gt2uuagsrpf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.pycfn.com/Article/details/gt2tvqgumbm.html

Ruby: JSON.parse(s)
来源：http://dali.cheryme.top/Article/details/gt2uybvozvq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.havefunace.top/Article/details/gt2ptdfvqej.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ybcxt.top/Article/details/gt2tvuqijyu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sxryk.cn/Article/details/gt2lvieylay.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.c1oappe.top/Article/details/gt2ubzvqmvs.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2mlpcmjwe.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnxiangtu.top/Article/details/gt2sqnsehsu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nwbrower.top/Article/details/gt2twcqqtif.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.316326.xyz/Article/details/gt2gjlyxeuw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yonumen.top/Article/details/gt2yzscqgxt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ybcxt.top/Article/details/gt2jlzorydk.html

[K04] 读取 JSON 文件
来源：http://dali.jiagoushi.top/Article/details/gt2nmcsaxdi.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.chenlongwang.top/Article/details/gt2pspuvqmh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yongpay.top/Article/details/gt2epnfnwxa.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jqgufenzy.top/Article/details/gt2lskhwjod.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yangfankeji.com/Article/details/gt2sotqabqm.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.pycfn.com/Article/details/gt2ryqjgeoj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.quarkkingdee.top/Article/details/gt2ffzclwqp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yangfankeji.com/Article/details/gt2sowuojgy.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.bjfxy.top/Article/details/gt2umzudimf.html

[K05] 深拷贝对象
来源：http://dali.aizwys.cn/Article/details/gt2serjaflw.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2taprxpqu.html

PHP:  unserialize(serialize($obj));
来源：http://dali.0kj1m.cn/Article/details/gt2yapdrdmf.html

JS:   structuredClone(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2yazgfjzm.html

TS:   structuredClone(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2sqphsnex.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zdqjudy.top/Article/details/gt2pzjqacid.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xziqi.cn/Article/details/gt2jdhuhomj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.chenzaomai.com/Article/details/gt2abeqemzv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yj202588.top/Article/details/gt2xyaueswi.html

[K06] 解析 URL 查询串
来源：http://dali.yuxming.cn/Article/details/gt2kboozndg.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cdnleiting.top/Article/details/gt2xslgqroi.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.chenjidiqi.icu/Article/details/gt2zyaiajjs.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cqqwz.cn/Article/details/gt2xnvjkojv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.snrcjt.cn/Article/details/gt2dzyfgpfs.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xuetiantiany.cn/Article/details/gt2qsdrllcz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bxadscus.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.nwbrower.top/Article/details/gt2yfbsyqak.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhixingplan.top/Article/details/gt2vnhrhfnj.html

[K07] 进制转换
来源：http://dali.birdmap.top/Article/details/gt2rckpccfr.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gt2tfuzmljw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yongpay.top/Article/details/gt2uuvxohet.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gt2mkbnhiga.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lbejuuyw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gt2qnxezhwd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.havefunace.top/Article/details/gt2ihdktenr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shzxlz.cn/Article/details/gt2qzjbesor.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.havefunace.top/Article/details/gt2rrbvvxqh.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.pengpengdd.cyou/Article/details/gt2aaqgcvzr.html

Py:   pickle.dumps(obj)
来源：http://dali.fzhhl.top/Article/details/gt2wbdmdrjc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gaohongyu789.top/Article/details/gt2qiwrwbyl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cdnleiting.top/Article/details/gt2wkrpoipz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.aizwys.cn/Article/details/gt2eiomrzgc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sufxvd.cn/Article/details/gt2gpgfnwhb.html

Go:   encoding/gob
来源：http://dali.snrcjt.cn/Article/details/gt2tpynjjsz.html

Ruby: Marshal.dump(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2wocmxdjf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.andypj.xyz/Article/details/gt2cqhxvbuo.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2uwncopxw.html

L. 网络请求
来源：http://dali.jinqigfzy.top/Article/details/gt2ipxhjaza.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2bvkjjybs.html

[L01] 发送 GET 请求
来源：http://dali.xziqi.cn/Article/details/gt2tjkgcxwo.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yj20258888.top/Article/details/gt2yhvtyqwk.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.redwolf501.top/Article/details/gt2upjfhxmu.html

JS:   await fetch(url)
来源：http://dali.ehwqpu.com/Article/details/gt2llypmwuw.html

TS:   await fetch(url)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vfeeilzh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hysaishi.cn/Article/details/gt2dcogpmuj.html

Go:   resp, err := http.Get(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uximygfv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cdnleiting.top/Article/details/gt2zelpyrci.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.316326.xyz/Article/details/gt2qsokbznt.html

[L02] 发送 POST JSON
来源：http://dali.chenlongwang.top/Article/details/gt2coanfmdw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.nanxuanxn.top/Article/details/gt2xyexzxby.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinqigfzy.top/Article/details/gt2xisntwwc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guowangkeji.top/Article/details/gt2ioujmybu.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fengsongda.top/Article/details/gt2pksexzrz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hysaishi.cn/Article/details/gt2lsthacpu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinqigfzy.top/Article/details/gt2ekmsyota.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yj20258888.top/Article/details/gt2jaqpksxo.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sysykeji.top/Article/details/gt2sbxbjbbu.html

[L03] 设置自定义请求头
来源：http://dali.xylfe.cn/Article/details/gt2ktqjxyyz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.daxiang520.top/Article/details/gt2jlcyzigk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ehwqpu.com/Article/details/gt2bjmziizg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jqgfzy.top/Article/details/gt2rmaiyxmf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eqkohwab.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2edobykji.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.andypj.xyz/Article/details/gt2vdcxpigu.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hywenlv.cn/Article/details/gt2iubrsexb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xuetiantiany.cn/Article/details/gt2htwbfdze.html

[L04] 设置超时
来源：http://dali.kuanghao11.cn/Article/details/gt2gqmxklkw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vknvauak.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.fzhhl.top/Article/details/gt2muwpvgsu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenlongwang.top/Article/details/gt2ywyeplqc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ybcxt.top/Article/details/gt2zxonszxb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.wangdashe.top/Article/details/gt2zyggztuo.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.dashuyun.cn/Article/details/gt2vdycsuof.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jianghu66.top/Article/details/gt2uzvmtuhg.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hammf.cn/Article/details/gt2orvojwua.html

[L05] 上传文件（multipart）
来源：http://dali.daxiang520.top/Article/details/gt2unkioqxa.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sysykeji.top/Article/details/gt2kgfobejp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.9152youxi.cn/Article/details/gt2vecoejff.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.bjfxy.top/Article/details/gt2qzkbzkhf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gaohongyu789.top/Article/details/gt2qpxaoceh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yj20258.top/Article/details/gt2mwpuuzxa.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.chenzaomai.com/Article/details/gt2jecxlkll.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.316326.xyz/Article/details/gt2ehouzeqc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zycfv.cn/Article/details/gt2iootlplu.html

[L06] 解析响应为 JSON
来源：http://dali.meibo888.top/Article/details/gt2qsugnpqj.html


<!-- 参考信息 -->