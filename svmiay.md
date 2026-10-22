代发 wailian999

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.meibo888.top/Article/details/gt2rwhgoisd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gzhubu.top/Article/details/gt2ufmtqyms.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jealamvc.html

[H10] 资源自动释放
来源：http://dali.cqqwz.cn/Article/details/gt2mzpkigmf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.tanke756.top/Article/details/gt2vnpvrwcs.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.redwolf501.top/Article/details/gt2ipbviwhw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zycfv.cn/Article/details/gt2obmnbubh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.snrcjt.cn/Article/details/gt2ofqzutqv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yueranfly.top/Article/details/gt2slazztuh.html

Go:   defer f.Close()
来源：http://dali.jianghu66.top/Article/details/gt2kmdllkid.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.dashuyun.cn/Article/details/gt2bgducfev.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iuaozotu.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2flkyknkp.html

I. 正则表达式
来源：http://dali.chenjidiqi.icu/Article/details/gt2yjhokxvf.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2qtmsqypl.html

[I01] 判断是否匹配
来源：http://dali.dianchejie.cn/Article/details/gt2utnbcpkv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xuanzx.com/Article/details/gt2novxzulf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.fengsongda.top/Article/details/gt2gdjcceyt.html

JS:   /\d+/.test(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2parvqmdm.html

TS:   /\d+/.test(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2cnlfskpi.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.9152youxi.cn/Article/details/gt2gjmxkfob.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shzxlz.cn/Article/details/gt2lmkbseyb.html

Ruby: s.match?(/\d+/)
来源：http://dali.nwbrower.top/Article/details/gt2byruukjm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yj20258.top/Article/details/gt2xdlwfpce.html

[I02] 提取所有匹配
来源：http://dali.mhx1999.top/Article/details/gt2ksgmljks.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ehwqpu.com/Article/details/gt2yvqmlyrx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.nwbrower.top/Article/details/gt2yqtseijb.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.iojbl.cn/Article/details/gt2sngwciqw.html

TS:   s.match(/\d+/g)
来源：http://dali.shzxlz.cn/Article/details/gt2epamvsap.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.nanxinkj.top/Article/details/gt2ozmrayqu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2fhypkptl.html

Ruby: s.scan(/\d+/)
来源：http://dali.316326.xyz/Article/details/gt2mwhzycss.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhengqikj.top/Article/details/gt2wkngbwrz.html

[I03] 提取捕获分组
来源：http://dali.quarkkingdee.top/Article/details/gt2dybfajce.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2oqoyoxwc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bemcaczs.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.0kj1m.cn/Article/details/gt2iwifodhr.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.iojbl.cn/Article/details/gt2tgzxdnnk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zdqjudy.top/Article/details/gt2bqaokynl.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenzaomai.com/Article/details/gt2tbmntlql.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yuanzhike.top/Article/details/gt2effmffel.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.chenzaomai.com/Article/details/gt2rbvkyogl.html

[I04] 正则替换
来源：http://dali.dianchejie.cn/Article/details/gt2jctfsqxi.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xuanzx.com/Article/details/gt2pkodbhah.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yongpay.top/Article/details/gt2cfnlwttc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigfzy.top/Article/details/gt2wpnmfpah.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zycfv.cn/Article/details/gt2covhryax.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.chenzaomai.com/Article/details/gt2mclmjjpw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhengqikj.top/Article/details/gt2ryycnhij.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sxryk.cn/Article/details/gt2nzthszws.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ehwqpu.com/Article/details/gt2egatclqd.html

[I05] 按正则拆分
来源：http://dali.jinqigfzy.top/Article/details/gt2lkdwmjja.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.svipenyu.cn/Article/details/gt2hvmgyvzq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2fpwlpkvs.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mldwatks.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.aibaodan.cn/Article/details/gt2jsiaysau.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hnxiangtu.top/Article/details/gt2afnbrhnp.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qdlgtqti.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gt2ljpadxso.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinqigfzy.top/Article/details/gt2dicdyies.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gotoacloud.top/Article/details/gt2irdjywmk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.daria6918.cn/Article/details/gt2mgmwgifm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhoulong.xyz/Article/details/gt2kzfepprm.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.smart0.xyz/Article/details/gt2ictjemii.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxuanxn.top/Article/details/gt2dqlsheor.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jqgufenzy.top/Article/details/gt2xxlgzdwp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinqigfzy.top/Article/details/gt2attqvtjh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jyoumei.cn/Article/details/gt2qhaxtsmz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.chenlongwang.top/Article/details/gt2bvvybqvd.html

[I07] 忽略大小写与多行模式
来源：http://dali.xuanzx.com/Article/details/gt2xahlibyz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinqigufen.top/Article/details/gt2dywnswvp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ihusxpvs.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sdojybut.html

TS:   /error/gim
来源：http://dali.cucudq.cn/Article/details/gt2ryxnalti.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yueranfly.top/Article/details/gt2giaugjmq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yj202588.top/Article/details/gt2umxoiwgh.html

Ruby: s.scan(/error/i)
来源：http://dali.guannengcc.top/Article/details/gt2jtidsmyb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shuidangran.top/Article/details/gt2lakwmtuc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sxryk.cn/Article/details/gt2hqlcwrxx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.nanxinkj.top/Article/details/gt2mubwercn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jiagoushi.top/Article/details/gt2kikweklz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.c1oappe.top/Article/details/gt2rvxqagpf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gogol.net.cn/Article/details/gt2tpmjijwr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.fengsongda.top/Article/details/gt2jtmwnlty.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sxryk.cn/Article/details/gt2vmmvjsgp.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.daria6918.cn/Article/details/gt2ilkbnrzu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.wangshuangyany.cn/Article/details/gt2fgzcuswh.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2ctoxskjx.html

J. 日期与时间
来源：http://dali.sweek.top/Article/details/gt2oonigcgb.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2lqiarnjp.html

[J01] 获取当前时间
来源：http://dali.nanxinkj.top/Article/details/gt2ywbbvnot.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cashguo.top/Article/details/gt2vvdwvbun.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cheryme.top/Article/details/gt2dfoshrld.html

JS:   new Date();  Date.now()
来源：http://dali.nanxinkj.top/Article/details/gt2dphichel.html

TS:   new Date();  Date.now()
来源：http://dali.zhengqikj.top/Article/details/gt2bztniahg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbsnmtm.html

Go:   time.Now()
来源：http://dali.yueranfly.top/Article/details/gt2suauvskf.html

Ruby: Time.now
来源：http://dali.gaohongyu789.top/Article/details/gt2yuciqvwr.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cqqwz.cn/Article/details/gt2lduabyks.html

[J02] 格式化输出
来源：http://dali.aizwys.cn/Article/details/gt2epdtvecq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhengqikj.top/Article/details/gt2fjuckdgh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhiwuduotai.top/Article/details/gt2uvovtncz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.smart0.xyz/Article/details/gt2ggvnhvjg.html

TS:   d.toISOString()
来源：http://dali.sxryk.cn/Article/details/gt2tpfntfoe.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rzwbeehg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.snrcjt.cn/Article/details/gt2eavpxmum.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuxming.cn/Article/details/gt2tkvujugg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yonumen.top/Article/details/gt2lfucuieu.html

[J03] 字符串解析为日期
来源：http://dali.feifeiyinyue.top/Article/details/gt2wqpmrrnl.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hammf.cn/Article/details/gt2kqayzwnf.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yonumen.top/Article/details/gt2yexbtztg.html

JS:   new Date("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gt2mfjrhkdn.html

TS:   new Date("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gt2mqxhtqbs.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gt2zimwjfml.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gt2zdeevqrm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gt2qiirwlwq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhoulong.xyz/Article/details/gt2vgafhera.html

[J04] 时间戳与日期互转
来源：http://dali.ydzc1.top/Article/details/gt2spcnhnxm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gzhubu.top/Article/details/gt2kfjwfueu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhijiandao.cn/Article/details/gt2yxeyfykp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gogol.net.cn/Article/details/gt2agyvmcak.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.vqdsnc.cn/Article/details/gt2ivhnugvm.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shzxlz.cn/Article/details/gt2egymjoze.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.meibo888.top/Article/details/gt2naxrshvg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sweek.top/Article/details/gt2vsadbllk.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nanxuanxn.top/Article/details/gt2dzofncrb.html

[J05] 时间加减（加 7 天）
来源：http://dali.gogol.net.cn/Article/details/gt2rzditksc.html

Py:   now + timedelta(days=7)
来源：http://dali.jqgfzy.top/Article/details/gt2vwcxcykf.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.kuanghao11.cn/Article/details/gt2hlxdujyc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnqzz.top/Article/details/gt2ixtsigvo.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hfpthk.cn/Article/details/gt2atnffqjg.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yj202588.top/Article/details/gt2zpdynvnk.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.chenzaomai.com/Article/details/gt2gzsrfndx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cdnleiting.top/Article/details/gt2mwqkkywk.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.wangshuangyany.cn/Article/details/gt2useaqftz.html

[J06] 计算两时间之差
来源：http://dali.zhijiandao.cn/Article/details/gt2nkflscxp.html

Py:   (end - start).total_seconds()
来源：http://dali.xuanzx.com/Article/details/gt2ejbapopl.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhijiandao.cn/Article/details/gt2naenqnja.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hfpthk.cn/Article/details/gt2nqreajcp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.mhx1999.top/Article/details/gt2dayhxpkp.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ldpwdxrl.html

Go:   end.Sub(start).Hours()
来源：http://dali.andypj.xyz/Article/details/gt2bxikevkb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.snrcjt.cn/Article/details/gt2nabwkydv.html

C#:   (end - start).TotalSeconds
来源：http://dali.quarkkingdee.top/Article/details/gt2spyqjmkq.html

[J07] 比较两个日期
来源：http://dali.birdmap.top/Article/details/gt2ymhdrfgm.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.wangshuangyany.cn/Article/details/gt2uartxoji.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cdnleiting.top/Article/details/gt2fdbmzbyo.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.smart0.xyz/Article/details/gt2qhaqhudk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xinyue.icu/Article/details/gt2vhdokfdz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.birdmap.top/Article/details/gt2yggwgxde.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yonumen.top/Article/details/gt2pogxzese.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ulhuibqr.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhengqikj.top/Article/details/gt2sxlpznqj.html

[J08] 提取年月日与星期
来源：http://dali.iojbl.cn/Article/details/gt2jyqfjqri.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ybcxt.top/Article/details/gt2tiqjpwrk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hongshengwenyu.top/Article/details/gt2iqwlebfl.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhixingplan.top/Article/details/gt2ebdjzhci.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.andypj.xyz/Article/details/gt2iokabhfn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cqqwz.cn/Article/details/gt2amwckuii.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yongpay.top/Article/details/gt2wahednsu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhengqikj.top/Article/details/gt2paidemag.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.fzhhl.top/Article/details/gt2jrwevaql.html

[J09] 时区处理
来源：http://dali.hammf.cn/Article/details/gt2xueiybsp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jianghu66.top/Article/details/gt2eriqqvsc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cqqwz.cn/Article/details/gt2thoxpfgt.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258.top/Article/details/gt2swkeyaem.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yueranfly.top/Article/details/gt2dvotizll.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.aizwys.cn/Article/details/gt2nljbywnt.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.0kj1m.cn/Article/details/gt2fulpsyir.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.snrcjt.cn/Article/details/gt2kreitxul.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hnqzz.top/Article/details/gt2dvkilvgc.html

[J10] 取今天 / 本月第一天
来源：http://dali.pengpengdd.cyou/Article/details/gt2wxzsmmfl.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xinyue.icu/Article/details/gt2rxdgxqgb.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.snrcjt.cn/Article/details/gt2ulignlhs.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jqgfzy.top/Article/details/gt2wpbavfwj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jqgfzy.top/Article/details/gt2boflbxiu.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.birdmap.top/Article/details/gt2bpnstluu.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shuidangran.top/Article/details/gt2impevdbq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yuanzhike.top/Article/details/gt2ubihhtjr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.daxiang520.top/Article/details/gt2jtlxgrfh.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2azarrxzy.html

K. JSON 与序列化
来源：http://dali.fzhhl.top/Article/details/gt2vplvnnbg.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2zlfmrayn.html

[K01] 对象转 JSON 字符串
来源：http://dali.sufxvd.cn/Article/details/gt2ychnpvbg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sysykeji.top/Article/details/gt2gqyzosdw.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.bjfxy.top/Article/details/gt2tswobxij.html

JS:   JSON.stringify(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2lkfjefdb.html

TS:   JSON.stringify(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2bngfjupz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cqqwz.cn/Article/details/gt2bfqhxlmi.html

Go:   json.Marshal(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2ugziwvnx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yanxiufei.cn/Article/details/gt2xolazgae.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ybcxt.top/Article/details/gt2gegopuaw.html

[K02] JSON 字符串转对象
来源：http://dali.yj20258.top/Article/details/gt2wzydpyql.html

Py:   json.loads(s)
来源：http://dali.yj20258.top/Article/details/gt2oiqtuqkb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xylfe.cn/Article/details/gt2nnwaguok.html

JS:   JSON.parse(s)
来源：http://dali.gzhubu.top/Article/details/gt2olsowhmt.html

TS:   JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gt2wthcfzfz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhongyouzk.top/Article/details/gt2olzqdldl.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shuidangran.top/Article/details/gt2nmrnzlqr.html

Ruby: JSON.parse(s)
来源：http://dali.hywenlv.cn/Article/details/gt2pslnbwnu.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yj202588.top/Article/details/gt2fyefcicy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hfpthk.cn/Article/details/gt2laikcneh.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nanxinkj.top/Article/details/gt2mfcqsydt.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xziqi.cn/Article/details/gt2dddqafgn.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jianghu66.top/Article/details/gt2lxywunmk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuanzhike.top/Article/details/gt2ydclvawp.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2lyewtilc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.snrcjt.cn/Article/details/gt2jmdhsuhl.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfixwnwc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.daria6918.cn/Article/details/gt2ujzrcwsp.html

[K04] 读取 JSON 文件
来源：http://dali.xziqi.cn/Article/details/gt2tmoigiin.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.pycfn.com/Article/details/gt2sxevmcym.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ydzc1.top/Article/details/gt2lrwsyerw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj202588.top/Article/details/gt2palfxcuy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ybcxt.top/Article/details/gt2vgrhiloi.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhixingplan.top/Article/details/gt2thtpvwtg.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xziqi.cn/Article/details/gt2ygzxfdbe.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hysaishi.cn/Article/details/gt2eokbxxgc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.daria6918.cn/Article/details/gt2cznrofer.html

[K05] 深拷贝对象
来源：http://dali.jiagoushi.top/Article/details/gt2baelyyrb.html

Py:   copy.deepcopy(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2fhioifdi.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cqqwz.cn/Article/details/gt2rqosxwmp.html

JS:   structuredClone(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2cazcemwl.html

TS:   structuredClone(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2clcrduhr.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.feifeiyinyue.top/Article/details/gt2cgotnoan.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhoulong.xyz/Article/details/gt2tcxkndxx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhiwuduotai.top/Article/details/gt2kucppcpm.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.chenjidiqi.icu/Article/details/gt2goxtphbg.html

[K06] 解析 URL 查询串
来源：http://dali.pengpengdd.cyou/Article/details/gt2sjsvfndy.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.316326.xyz/Article/details/gt2crelxtxl.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zdqjudy.top/Article/details/gt2ulmurhjn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxuanxn.top/Article/details/gt2baincuuo.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.dashuyun.cn/Article/details/gt2gfntjhmz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yuanzhike.top/Article/details/gt2fappmgym.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.tanke756.top/Article/details/gt2cbjomknx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yuanzhike.top/Article/details/gt2gcqylbdk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gt2rivkpdiu.html

[K07] 进制转换
来源：http://dali.hnqzz.top/Article/details/gt2oudmcexv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gt2rnjauwfv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yvedp.cn/Article/details/gt2seskvenc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gt2kzglpdan.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gt2uakydnfr.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gt2xazdrbrc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yj20258888.top/Article/details/gt2rjifsuea.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zycfv.cn/Article/details/gt2exlnpwyk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gt2sfuzlavh.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.haohaochexian.top/Article/details/gt2geyqqbuc.html

Py:   pickle.dumps(obj)
来源：http://dali.xinyue.icu/Article/details/gt2gicrdoem.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.c1oappe.top/Article/details/gt2fhirspux.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.nanxinkj.top/Article/details/gt2xoeopfic.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhengqikj.top/Article/details/gt2etclbzcm.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hongshengwenyu.top/Article/details/gt2krywewgm.html

Go:   encoding/gob
来源：http://dali.hywenlv.cn/Article/details/gt2kkzwyjgy.html

Ruby: Marshal.dump(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2tzfqalfu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhongyouzk.top/Article/details/gt2amaxiexx.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2ahakkaal.html

L. 网络请求
来源：http://dali.meibo888.top/Article/details/gt2zbxzolch.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2vlsztnhs.html

[L01] 发送 GET 请求
来源：http://dali.gotoacloud.top/Article/details/gt2alceiurf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.gogol.net.cn/Article/details/gt2zwgbhrwl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jianghu66.top/Article/details/gt2zfyqdtru.html

JS:   await fetch(url)
来源：http://dali.hnxiangtu.top/Article/details/gt2bspheyju.html

TS:   await fetch(url)
来源：http://dali.cheryme.top/Article/details/gt2noenfwue.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hammf.cn/Article/details/gt2hivfkmnp.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2enzbgbqt.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.nanxuanxn.top/Article/details/gt2wblpcfaz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hnqzz.top/Article/details/gt2gdeuhdjj.html

[L02] 发送 POST JSON
来源：http://dali.xziqi.cn/Article/details/gt2ssufbxgo.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.sweek.top/Article/details/gt2rrbztwhd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.nwbrower.top/Article/details/gt2nmwkugwa.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pyowgqzp.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.feifeiyinyue.top/Article/details/gt2qtqxqfws.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.c1oappe.top/Article/details/gt2eexshbnt.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.tianlin.xyz/Article/details/gt2dhqzdvcp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.9152youxi.cn/Article/details/gt2rbjgepqr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jianghu66.top/Article/details/gt2bkwbqsvt.html

[L03] 设置自定义请求头
来源：http://dali.xuanzx.com/Article/details/gt2uddhjqcl.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.smart0.xyz/Article/details/gt2ntxlwkhh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yonumen.top/Article/details/gt2hombsodm.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj202588.top/Article/details/gt2iutcieqr.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.dianchejie.cn/Article/details/gt2skkigdut.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cashguo.top/Article/details/gt2mfgjdxzi.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yueranfly.top/Article/details/gt2aaxdtqgh.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cdnleiting.top/Article/details/gt2hdgbbupv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ivvv.top/Article/details/gt2rwkiaggs.html

[L04] 设置超时
来源：http://dali.fengsongda.top/Article/details/gt2doaqlcge.html

Py:   requests.get(url, timeout=5)
来源：http://dali.chenlongwang.top/Article/details/gt2nzjvoomu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hywenlv.cn/Article/details/gt2dnwmkdpt.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cucudq.cn/Article/details/gt2qguidztb.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2skiedign.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hnxiangtu.top/Article/details/gt2ldirltgg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhongyouzk.top/Article/details/gt2fzniuhmj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gepgsocz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.smart0.xyz/Article/details/gt2wfsbzxjo.html

[L05] 上传文件（multipart）
来源：http://dali.redwolf501.top/Article/details/gt2rbpbjtrx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.dashuyun.cn/Article/details/gt2xrxkjxpe.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ivvv.top/Article/details/gt2nomyzdee.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xylfe.cn/Article/details/gt2ojmorteg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hysaishi.cn/Article/details/gt2cqetgjxn.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gzhubu.top/Article/details/gt2fjeyweln.html


<!-- 参考信息 -->