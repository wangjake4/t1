代发 wailian999

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yanxiufei.cn/Article/details/gt2yrfityef.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yangfankeji.com/Article/details/gt2pysyrjom.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.aizwys.cn/Article/details/gt2qncjyblz.html

[H10] 资源自动释放
来源：http://dali.ivvv.top/Article/details/gt2bwogqiao.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.nanxinkj.top/Article/details/gt2huxihipf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.pycfn.com/Article/details/gt2txgdtjpy.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.vqdsnc.cn/Article/details/gt2clyvhoot.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.kuanghao11.cn/Article/details/gt2peimycra.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.mhx1999.top/Article/details/gt2jffvffil.html

Go:   defer f.Close()
来源：http://dali.yanxiufei.cn/Article/details/gt2kffzatyq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rizreutm.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xinyue.icu/Article/details/gt2rlyfbxtq.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2fmelhynj.html

I. 正则表达式
来源：http://dali.gogol.net.cn/Article/details/gt2mrxmnxpj.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2spxqxnwp.html

[I01] 判断是否匹配
来源：http://dali.aizwys.cn/Article/details/gt2kcqyqmlu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sxryk.cn/Article/details/gt2dbztzcid.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gt2eitewaor.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijqykjap.html

TS:   /\d+/.test(s)
来源：http://dali.iojbl.cn/Article/details/gt2jrkrfjgu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jqgfzy.top/Article/details/gt2ywzswrtn.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xylfe.cn/Article/details/gt2btlcfsar.html

Ruby: s.match?(/\d+/)
来源：http://dali.sweek.top/Article/details/gt2rooyyvzj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.gotoacloud.top/Article/details/gt2feriqaoa.html

[I02] 提取所有匹配
来源：http://dali.sysykeji.top/Article/details/gt2qkbdpgrx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yvedp.cn/Article/details/gt2olswhyhy.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.meibo888.top/Article/details/gt2unwigspi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.chenlongwang.top/Article/details/gt2ixbhlwsr.html

TS:   s.match(/\d+/g)
来源：http://dali.svipenyu.cn/Article/details/gt2bmsgaevx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.guowangkeji.top/Article/details/gt2rgpnddnt.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ehwqpu.com/Article/details/gt2qgzikscb.html

Ruby: s.scan(/\d+/)
来源：http://dali.316326.xyz/Article/details/gt2hjkuptwz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2iqjoflcv.html

[I03] 提取捕获分组
来源：http://dali.tian-w.cn/Article/details/gt2rylscfgu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jyoumei.cn/Article/details/gt2kwiahrkp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.pengpengdd.cyou/Article/details/gt2njchxzms.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.nwbrower.top/Article/details/gt2fgtydcxs.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ehwqpu.com/Article/details/gt2oyotmlzi.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.aibaodan.cn/Article/details/gt2ffewdvvu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xylfe.cn/Article/details/gt2dcrloden.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hammf.cn/Article/details/gt2anwrevie.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ehwqpu.com/Article/details/gt2rzaapibn.html

[I04] 正则替换
来源：http://dali.snrcjt.cn/Article/details/gt2hxdiskuk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.tian-w.cn/Article/details/gt2sdruspme.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj202588.top/Article/details/gt2tduuhdnm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.meibo888.top/Article/details/gt2icgedfpr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hfpthk.cn/Article/details/gt2avkkfswy.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.nanxinkj.top/Article/details/gt2gpfbqdzp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinqigfzy.top/Article/details/gt2jfxtemvd.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gzhubu.top/Article/details/gt2ucxgthum.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gogol.net.cn/Article/details/gt2ellpteef.html

[I05] 按正则拆分
来源：http://dali.zhoulong.xyz/Article/details/gt2xhievudx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.chenzaomai.com/Article/details/gt2rrtbhifz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rzebxhgm.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gt2cwqjfqgp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhoulong.xyz/Article/details/gt2debfxfka.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yangfankeji.com/Article/details/gt2qpvyfnpi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.meibo888.top/Article/details/gt2befwioiy.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gt2ruwpcklf.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gotoacloud.top/Article/details/gt2itsmkeoz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhiwuduotai.top/Article/details/gt2dzjorbhd.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cheryme.top/Article/details/gt2gugxpyvj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gaohongyu789.top/Article/details/gt2wvmhfwuv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xylfe.cn/Article/details/gt2imdpygck.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.iojbl.cn/Article/details/gt2kdktzswq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.chenzaomai.com/Article/details/gt2ysnyuobt.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.snrcjt.cn/Article/details/gt2kqcrnwlo.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xylfe.cn/Article/details/gt2fzhxydlo.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gotoacloud.top/Article/details/gt2squlobzn.html

[I07] 忽略大小写与多行模式
来源：http://dali.jqgufenzy.top/Article/details/gt2owjqvnxb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ppjwa.cn/Article/details/gt2hxdswljo.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenlongwang.top/Article/details/gt2qntlgrnq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yyadrpob.html

TS:   /error/gim
来源：http://dali.0kj1m.cn/Article/details/gt2jlknyfkr.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.guowangkeji.top/Article/details/gt2wvdwgdmh.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.guannengcc.top/Article/details/gt2wtbjvsim.html

Ruby: s.scan(/error/i)
来源：http://dali.zycfv.cn/Article/details/gt2gturwsqq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgbdptg.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.aibaodan.cn/Article/details/gt2uglxhjai.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cucudq.cn/Article/details/gt2ynnpikzq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jyoumei.cn/Article/details/gt2wqdljuqh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.svipenyu.cn/Article/details/gt2syqkoqoh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gzhubu.top/Article/details/gt2tphamymv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.svipenyu.cn/Article/details/gt2tirkahpr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yj202588.top/Article/details/gt2pnxwhfyo.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj20258.top/Article/details/gt2pxvjpfha.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hammf.cn/Article/details/gt2fyaidpmk.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2mrmfvrbz.html

J. 日期与时间
来源：http://dali.havefunace.top/Article/details/gt2zklaoyew.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2rwhdiejt.html

[J01] 获取当前时间
来源：http://dali.svipenyu.cn/Article/details/gt2wpesgydr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.tanke756.top/Article/details/gt2ozpvlpui.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zdqjudy.top/Article/details/gt2xiuoqbiy.html

JS:   new Date();  Date.now()
来源：http://dali.shzxlz.cn/Article/details/gt2tcsvfmtn.html

TS:   new Date();  Date.now()
来源：http://dali.aibaodan.cn/Article/details/gt2ndwacrqp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.daria6918.cn/Article/details/gt2yxhysvna.html

Go:   time.Now()
来源：http://dali.wangshuangyany.cn/Article/details/gt2lblhcwnr.html

Ruby: Time.now
来源：http://dali.vqdsnc.cn/Article/details/gt2gracfmde.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.fengsongda.top/Article/details/gt2lidhrrnd.html

[J02] 格式化输出
来源：http://dali.ppjwa.cn/Article/details/gt2miidddfe.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.316326.xyz/Article/details/gt2pcgfnesm.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jianghu66.top/Article/details/gt2qffvpyim.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jyoumei.cn/Article/details/gt2jhtlyfmt.html

TS:   d.toISOString()
来源：http://dali.pengpengdd.cyou/Article/details/gt2dadqgeyq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.feifeiyinyue.top/Article/details/gt2tlpqcqjq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zdqjudy.top/Article/details/gt2vzcjzasx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yvedp.cn/Article/details/gt2tisjcbgl.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ouczizky.html

[J03] 字符串解析为日期
来源：http://dali.chenjidiqi.icu/Article/details/gt2pawqadsf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.wangshuangyany.cn/Article/details/gt2qffmftnf.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj20258888.top/Article/details/gt2tkfkprfd.html

JS:   new Date("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gt2dqlepvfu.html

TS:   new Date("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gt2ynlmccaq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gt2zpjbnfig.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gt2pypnpajp.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gt2vqruieki.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wggcotkj.html

[J04] 时间戳与日期互转
来源：http://dali.shangyingyoupin.top/Article/details/gt2cvgwomra.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hnxiangtu.top/Article/details/gt2nilvxole.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jqgufenzy.top/Article/details/gt2wukzrsht.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jiagoushi.top/Article/details/gt2ajxmmgfa.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.daxiang520.top/Article/details/gt2fsdzzzhk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gt2dnarydqz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2qpxuzdlo.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jinqigfzy.top/Article/details/gt2sfztvkfu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sufxvd.cn/Article/details/gt2sriismry.html

[J05] 时间加减（加 7 天）
来源：http://dali.gogol.net.cn/Article/details/gt2uqazgwin.html

Py:   now + timedelta(days=7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dzkhwdda.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yj20258888.top/Article/details/gt2dpwxuafj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yonumen.top/Article/details/gt2ezvrktmh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.haohaochexian.top/Article/details/gt2xqviapjo.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.aizwys.cn/Article/details/gt2jpvpiifr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gaohongyu789.top/Article/details/gt2cgujfudu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zxjbbhly.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wygcihlc.html

[J06] 计算两时间之差
来源：http://dali.zhijiandao.cn/Article/details/gt2xsucuker.html

Py:   (end - start).total_seconds()
来源：http://dali.aibaodan.cn/Article/details/gt2qhcisnqp.html

PHP:  $end->diff($start)->days;
来源：http://dali.nwbrower.top/Article/details/gt2siqyjinh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yvedp.cn/Article/details/gt2cvhjpufx.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2owjsdevf.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.aibaodan.cn/Article/details/gt2lvaorngv.html

Go:   end.Sub(start).Hours()
来源：http://dali.ydzc1.top/Article/details/gt2fugurhft.html

Ruby: end - start                 # 返回秒数
来源：http://dali.c1oappe.top/Article/details/gt2nxupitlv.html

C#:   (end - start).TotalSeconds
来源：http://dali.xuanzx.com/Article/details/gt2gclbwpce.html

[J07] 比较两个日期
来源：http://dali.ppjwa.cn/Article/details/gt2tkriilnn.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cashguo.top/Article/details/gt2eqyxjhwj.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.haohaochexian.top/Article/details/gt2qbhztqgd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xuetiantiany.cn/Article/details/gt2trrszuea.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cqqwz.cn/Article/details/gt2pkbmqhtc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sufxvd.cn/Article/details/gt2yopqtqzn.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhengqikj.top/Article/details/gt2fevtgsvh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xinyue.icu/Article/details/gt2koczucqs.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.feifeiyinyue.top/Article/details/gt2eunermrt.html

[J08] 提取年月日与星期
来源：http://dali.xziqi.cn/Article/details/gt2hadltfdr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yuanzhike.top/Article/details/gt2eghhhnpb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hexcvirn.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.dianchejie.cn/Article/details/gt2luslyjjy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.guowangkeji.top/Article/details/gt2prwyejiv.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yj20258.top/Article/details/gt2pxqbfwsu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.smart0.xyz/Article/details/gt2rpwlhyzp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yj202588.top/Article/details/gt2jnobsiqr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.wangdashe.top/Article/details/gt2ahsnbmxo.html

[J09] 时区处理
来源：http://dali.yongpay.top/Article/details/gt2mjttyemf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.wangdashe.top/Article/details/gt2bgsqwyak.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yj20258.top/Article/details/gt2humuijap.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenzaomai.com/Article/details/gt2xgaeamyf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.iojbl.cn/Article/details/gt2yuvrljbd.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hongshengwenyu.top/Article/details/gt2sdskhgis.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.316326.xyz/Article/details/gt2ebbsqkpg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nanxinkj.top/Article/details/gt2dipffpoz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.9152youxi.cn/Article/details/gt2tvzdlypk.html

[J10] 取今天 / 本月第一天
来源：http://dali.pycfn.com/Article/details/gt2wmcmwtpz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tegakyxy.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.chenlongwang.top/Article/details/gt2yzvcienk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhoulong.xyz/Article/details/gt2qmqmalee.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yueranfly.top/Article/details/gt2ryzmfcgo.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.bjfxy.top/Article/details/gt2liwincuu.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hfpthk.cn/Article/details/gt2nteslaiu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.havefunace.top/Article/details/gt2idlyhqik.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.tanke756.top/Article/details/gt2yoqkdgrb.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2zfirmxjq.html

K. JSON 与序列化
来源：http://dali.pengpengdd.cyou/Article/details/gt2fkrihetg.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2bncrsoex.html

[K01] 对象转 JSON 字符串
来源：http://dali.birdmap.top/Article/details/gt2ddfqvcms.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jyoumei.cn/Article/details/gt2czgcwgaz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgufenzy.top/Article/details/gt2hkzdxkpo.html

JS:   JSON.stringify(obj)
来源：http://dali.xinyue.icu/Article/details/gt2whrmjnco.html

TS:   JSON.stringify(obj)
来源：http://dali.yj20258.top/Article/details/gt2wzwinwuh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gaohongyu789.top/Article/details/gt2apupwvhu.html

Go:   json.Marshal(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2iycbzwgx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.kuanghao11.cn/Article/details/gt2xwupqyre.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2jlmewbco.html

[K02] JSON 字符串转对象
来源：http://dali.pycfn.com/Article/details/gt2pmhswnne.html

Py:   json.loads(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2siljhkpc.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sysykeji.top/Article/details/gt2xxqjmkhm.html

JS:   JSON.parse(s)
来源：http://dali.hnqzz.top/Article/details/gt2mqdecpbv.html

TS:   JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gt2gxzoyafq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ghfcjpnb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.chenzaomai.com/Article/details/gt2pglaluac.html

Ruby: JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gt2hakslqam.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ybcxt.top/Article/details/gt2ybugxwpj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ridehqna.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nanxuanxn.top/Article/details/gt2cogzkvmt.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.svipenyu.cn/Article/details/gt2ysxcaumq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gt2uzofohsh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2rbxigxea.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2psnqpyob.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.smart0.xyz/Article/details/gt2kzznyfju.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.andypj.xyz/Article/details/gt2cjobpulm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yonumen.top/Article/details/gt2gfcqpnkc.html

[K04] 读取 JSON 文件
来源：http://dali.guannengcc.top/Article/details/gt2qcjodjbz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.aizwys.cn/Article/details/gt2nlymbcgv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hysaishi.cn/Article/details/gt2vobmfgfw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnqzz.top/Article/details/gt2ybxelnle.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2pofiooyi.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.pengpengdd.cyou/Article/details/gt2avxszgjv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.316326.xyz/Article/details/gt2tbbqxigk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.meibo888.top/Article/details/gt2ytunbwxi.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ivvv.top/Article/details/gt2rpvncefh.html

[K05] 深拷贝对象
来源：http://dali.yj20258.top/Article/details/gt2dqpxbclo.html

Py:   copy.deepcopy(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2rpagjqfo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hfpthk.cn/Article/details/gt2jttuluay.html

JS:   structuredClone(obj)
来源：http://dali.shuidangran.top/Article/details/gt2rdqimkpm.html

TS:   structuredClone(obj)
来源：http://dali.hnqzz.top/Article/details/gt2zlczeurx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ehwqpu.com/Article/details/gt2nnigzsxz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.redwolf501.top/Article/details/gt2egdvhysv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.0kj1m.cn/Article/details/gt2ejrbsgch.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yongpay.top/Article/details/gt2ilkafwce.html

[K06] 解析 URL 查询串
来源：http://dali.aizwys.cn/Article/details/gt2lrzoljrm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hfpthk.cn/Article/details/gt2pclqmlmq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.chenjidiqi.icu/Article/details/gt2fnjwechc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cqqwz.cn/Article/details/gt2mrbfdhvl.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhiwuduotai.top/Article/details/gt2hyuyosnu.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ppjwa.cn/Article/details/gt2yyekejmt.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yueranfly.top/Article/details/gt2iwcjfvun.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.meibo888.top/Article/details/gt2rnatwubo.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gt2zivsjtzv.html

[K07] 进制转换
来源：http://dali.gotoacloud.top/Article/details/gt2hanlaqgi.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gt2swkcqhkg.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.feifeiyinyue.top/Article/details/gt2ueurmbgp.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gt2wjjckctp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gt2waxddmcv.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gt2qwhvktcn.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cqqwz.cn/Article/details/gt2mismqmvv.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xinyue.icu/Article/details/gt2wvyvuswz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gt2pkxjgjvi.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.bjfxy.top/Article/details/gt2gjxfodlu.html

Py:   pickle.dumps(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2xfswfzxb.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.snrcjt.cn/Article/details/gt2rndgrsxx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.316326.xyz/Article/details/gt2kdnxysgg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.nanxuanxn.top/Article/details/gt2oumljxbe.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.wangdashe.top/Article/details/gt2tymvpxlf.html

Go:   encoding/gob
来源：http://dali.mhx1999.top/Article/details/gt2swkipmlz.html

Ruby: Marshal.dump(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lfcfsavv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yueranfly.top/Article/details/gt2gclthjfx.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2yumgufwj.html

L. 网络请求
来源：http://dali.ehwqpu.com/Article/details/gt2lbyxfxek.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2ucedhbft.html

[L01] 发送 GET 请求
来源：http://dali.yueranfly.top/Article/details/gt2dkiywmns.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.haohaochexian.top/Article/details/gt2soscgzxr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.c1oappe.top/Article/details/gt2qarogaqo.html

JS:   await fetch(url)
来源：http://dali.hfpthk.cn/Article/details/gt2ivxpqjrx.html

TS:   await fetch(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bqlfnovn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cheryme.top/Article/details/gt2mhpceyae.html

Go:   resp, err := http.Get(url)
来源：http://dali.shuidangran.top/Article/details/gt2bjsulutj.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2moecajnm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhiwuduotai.top/Article/details/gt2nxrxlgzq.html

[L02] 发送 POST JSON
来源：http://dali.nanxuanxn.top/Article/details/gt2wpasctih.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhixingplan.top/Article/details/gt2dyenrvka.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.pengpengdd.cyou/Article/details/gt2rjqpntbi.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cheryme.top/Article/details/gt2agtfeozn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hnqzz.top/Article/details/gt2yzsacebx.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.nanxuanxn.top/Article/details/gt2htrukprt.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhengqikj.top/Article/details/gt2xkxftxcn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tydycyjb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.mhx1999.top/Article/details/gt2avonijbi.html

[L03] 设置自定义请求头
来源：http://dali.kuanghao11.cn/Article/details/gt2tzxowlag.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cucudq.cn/Article/details/gt2ujzjgqzd.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.9152youxi.cn/Article/details/gt2kxgzitjq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj202588.top/Article/details/gt2vrouajxc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aibaodan.cn/Article/details/gt2mxisuext.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.redwolf501.top/Article/details/gt2qaxncapi.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hammf.cn/Article/details/gt2aqdlnmor.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yuanzhike.top/Article/details/gt2riiaeqdw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cqqwz.cn/Article/details/gt2bpncitch.html

[L04] 设置超时
来源：http://dali.cqqwz.cn/Article/details/gt2dgkzqppa.html

Py:   requests.get(url, timeout=5)
来源：http://dali.feifeiyinyue.top/Article/details/gt2iyccegji.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.316326.xyz/Article/details/gt2zqhlcgij.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.svipenyu.cn/Article/details/gt2qtygwdvn.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sweek.top/Article/details/gt2tdivajel.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gzhubu.top/Article/details/gt2ijolshje.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.meibo888.top/Article/details/gt2gxwpzmvw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xylfe.cn/Article/details/gt2grwvxots.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenlongwang.top/Article/details/gt2jcoyduba.html

[L05] 上传文件（multipart）
来源：http://dali.nanxinkj.top/Article/details/gt2aaksfnnx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.snrcjt.cn/Article/details/gt2uwoyzoli.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.vqdsnc.cn/Article/details/gt2ptmhdlpo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.kuanghao11.cn/Article/details/gt2eufftxaj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.redwolf501.top/Article/details/gt2uemmkdyf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cheryme.top/Article/details/gt2wvmphaao.html


<!-- 参考信息 -->