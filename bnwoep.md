代发 wailian999

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.redwolf501.top/Article/details/gt2juruexqs.html

Go:   defer f.Close()
来源：http://dali.mhx1999.top/Article/details/gt2qojzjwre.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhixingplan.top/Article/details/gt2emhccrcb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2uxcoxmcv.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2sxndkmfq.html

I. 正则表达式
来源：http://dali.hongshengwenyu.top/Article/details/gt2dxotexaj.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2bfhzotxm.html

[I01] 判断是否匹配
来源：http://dali.zhongyouzk.top/Article/details/gt2chkjruds.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sxryk.cn/Article/details/gt2oaazyawg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.bjfxy.top/Article/details/gt2hroxuudt.html

JS:   /\d+/.test(s)
来源：http://dali.cucudq.cn/Article/details/gt2ustgankx.html

TS:   /\d+/.test(s)
来源：http://dali.tianlin.xyz/Article/details/gt2shgzqlrp.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.andypj.xyz/Article/details/gt2ctknorbh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.meibo888.top/Article/details/gt2dsvyvzeh.html

Ruby: s.match?(/\d+/)
来源：http://dali.nanxinkj.top/Article/details/gt2pseclpnb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhiwuduotai.top/Article/details/gt2sgkghzgw.html

[I02] 提取所有匹配
来源：http://dali.pengpengdd.cyou/Article/details/gt2ynobwkmg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jqgufenzy.top/Article/details/gt2kpywqxls.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yanxiufei.cn/Article/details/gt2bpbdfkjf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xuanzx.com/Article/details/gt2loxybjtt.html

TS:   s.match(/\d+/g)
来源：http://dali.cdnleiting.top/Article/details/gt2llebsixn.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2npwduqbn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.pycfn.com/Article/details/gt2ddqvekrb.html

Ruby: s.scan(/\d+/)
来源：http://dali.sufxvd.cn/Article/details/gt2zmjkphtp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ppjwa.cn/Article/details/gt2qujhsqvy.html

[I03] 提取捕获分组
来源：http://dali.meibo888.top/Article/details/gt2qecotbzb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yj20258.top/Article/details/gt2gmbypeix.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ivvv.top/Article/details/gt2soogunat.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.chenzaomai.com/Article/details/gt2uhhiaapk.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jyoumei.cn/Article/details/gt2lljhwpsk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jianghu66.top/Article/details/gt2isajxfli.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sufxvd.cn/Article/details/gt2zlknjslq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.guowangkeji.top/Article/details/gt2ycatkgts.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.guowangkeji.top/Article/details/gt2caexhxqo.html

[I04] 正则替换
来源：http://dali.mhx1999.top/Article/details/gt2mrjgexis.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xinyue.icu/Article/details/gt2czrmivaw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.kuanghao11.cn/Article/details/gt2dvbsuaao.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gogol.net.cn/Article/details/gt2suzisxwf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gaohongyu789.top/Article/details/gt2risrgcel.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shzxlz.cn/Article/details/gt2gsaroosq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.havefunace.top/Article/details/gt2pcfnhslg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cqqwz.cn/Article/details/gt2gtaczqje.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.aibaodan.cn/Article/details/gt2shmiibpv.html

[I05] 按正则拆分
来源：http://dali.daria6918.cn/Article/details/gt2ozvgkzna.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2kleijyjz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rypkeibb.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2fmgpzsmt.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gt2gggwzszt.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gzhubu.top/Article/details/gt2uydweamu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xziqi.cn/Article/details/gt2kqkzgvlv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.havefunace.top/Article/details/gt2dkvfshmu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ehwqpu.com/Article/details/gt2hnfqindb.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.daria6918.cn/Article/details/gt2stvjgcsz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xuetiantiany.cn/Article/details/gt2wfpymvcc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kyyhhhtw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigfzy.top/Article/details/gt2huaqkcgd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aizwys.cn/Article/details/gt2aceqgdqj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.redwolf501.top/Article/details/gt2gqyzfhcv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.aibaodan.cn/Article/details/gt2vfxxahlf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.redwolf501.top/Article/details/gt2wetshifk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.wangdashe.top/Article/details/gt2ubzetcbc.html

[I07] 忽略大小写与多行模式
来源：http://dali.redwolf501.top/Article/details/gt2rhjtrjpu.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yanxiufei.cn/Article/details/gt2qjhtpyhg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.c1oappe.top/Article/details/gt2xqdnwhov.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jqgufenzy.top/Article/details/gt2dpidskka.html

TS:   /error/gim
来源：http://dali.mhx1999.top/Article/details/gt2fzgbflas.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jianghu66.top/Article/details/gt2sytkccud.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.9152youxi.cn/Article/details/gt2jzvlarjd.html

Ruby: s.scan(/error/i)
来源：http://dali.gogol.net.cn/Article/details/gt2vwsxknud.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.havefunace.top/Article/details/gt2dywmcfmy.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xuetiantiany.cn/Article/details/gt2oayovwuq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yueranfly.top/Article/details/gt2wxtitcfl.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xuanzx.com/Article/details/gt2rtknhsxs.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sufxvd.cn/Article/details/gt2ungetpsx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sxryk.cn/Article/details/gt2qrrevusr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sxryk.cn/Article/details/gt2sgsynljy.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.c1oappe.top/Article/details/gt2jcuwjrji.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ppjwa.cn/Article/details/gt2tbaunjcj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.havefunace.top/Article/details/gt2pjsdtosw.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2yorhvnai.html

J. 日期与时间
来源：http://dali.haohaochexian.top/Article/details/gt2uivmvjhx.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2btuwgmye.html

[J01] 获取当前时间
来源：http://dali.cdnleiting.top/Article/details/gt2uwtslmle.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sxryk.cn/Article/details/gt2bhcmlnig.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.iojbl.cn/Article/details/gt2auvbxthn.html

JS:   new Date();  Date.now()
来源：http://dali.guowangkeji.top/Article/details/gt2kvzlchif.html

TS:   new Date();  Date.now()
来源：http://dali.xuetiantiany.cn/Article/details/gt2ubvtquyz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.havefunace.top/Article/details/gt2khfkngzc.html

Go:   time.Now()
来源：http://dali.tanke756.top/Article/details/gt2fqfipwwx.html

Ruby: Time.now
来源：http://dali.cucudq.cn/Article/details/gt2byahiyap.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.tanke756.top/Article/details/gt2qiujpqrq.html

[J02] 格式化输出
来源：http://dali.bjfxy.top/Article/details/gt2geimzdhs.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hysaishi.cn/Article/details/gt2qdxjnkzf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.birdmap.top/Article/details/gt2ibeqcuyb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hysaishi.cn/Article/details/gt2yptfzmie.html

TS:   d.toISOString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kylprxqh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.birdmap.top/Article/details/gt2piofumag.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yueranfly.top/Article/details/gt2wpjtemcj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cqqwz.cn/Article/details/gt2yoksxtsl.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinqigfzy.top/Article/details/gt2ltoxnzpf.html

[J03] 字符串解析为日期
来源：http://dali.wangshuangyany.cn/Article/details/gt2ipqzzkyy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.tian-w.cn/Article/details/gt2xfyebeoj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gogol.net.cn/Article/details/gt2ldtnlndh.html

JS:   new Date("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gt2tqknidmr.html

TS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxnarzq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gt2kgiyxgyb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2orrnacpi.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gt2cxwknpct.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.birdmap.top/Article/details/gt2bwtpzoym.html

[J04] 时间戳与日期互转
来源：http://dali.jinghuilouyu.cn/Article/details/gt2poczaooh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.9152youxi.cn/Article/details/gt2cnoezlsp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jqgufenzy.top/Article/details/gt2jilwuizv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xylfe.cn/Article/details/gt2bfxxcgcp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ivvv.top/Article/details/gt2nsdpwknb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cdnleiting.top/Article/details/gt2qxjpssox.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hammf.cn/Article/details/gt2oacwaxsn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2iquhdctu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gt2eqwlryrq.html

[J05] 时间加减（加 7 天）
来源：http://dali.jqgfzy.top/Article/details/gt2gashggup.html

Py:   now + timedelta(days=7)
来源：http://dali.snrcjt.cn/Article/details/gt2boghdyss.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.pengpengdd.cyou/Article/details/gt2eejqltzj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenlongwang.top/Article/details/gt2melucxaw.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hfpthk.cn/Article/details/gt2ofljdkbq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cuaukbtv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.redwolf501.top/Article/details/gt2qzhmmeso.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jinqigufen.top/Article/details/gt2pipjlvkj.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xobbqbqx.html

[J06] 计算两时间之差
来源：http://dali.gogol.net.cn/Article/details/gt2azttylqo.html

Py:   (end - start).total_seconds()
来源：http://dali.chenlongwang.top/Article/details/gt2rtkahbhb.html

PHP:  $end->diff($start)->days;
来源：http://dali.hongshengwenyu.top/Article/details/gt2eyppmmls.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhiwuduotai.top/Article/details/gt2laaobohf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yueranfly.top/Article/details/gt2rzpccozq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.quarkkingdee.top/Article/details/gt2brzobulg.html

Go:   end.Sub(start).Hours()
来源：http://dali.nanxuanxn.top/Article/details/gt2ldzwrvem.html

Ruby: end - start                 # 返回秒数
来源：http://dali.316326.xyz/Article/details/gt2sfllhmoy.html

C#:   (end - start).TotalSeconds
来源：http://dali.ivvv.top/Article/details/gt2ifegtdgh.html

[J07] 比较两个日期
来源：http://dali.kuanghao11.cn/Article/details/gt2mmknyuil.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.mhx1999.top/Article/details/gt2tkznqqid.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.wangshuangyany.cn/Article/details/gt2kzlrvjqg.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.kuanghao11.cn/Article/details/gt2xsgdypoy.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hnqzz.top/Article/details/gt2gykwjlxw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.tian-w.cn/Article/details/gt2ynsmwenl.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yueranfly.top/Article/details/gt2qahrfnva.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.haohaochexian.top/Article/details/gt2kfflhyvm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shzxlz.cn/Article/details/gt2wdapfgti.html

[J08] 提取年月日与星期
来源：http://dali.bjfxy.top/Article/details/gt2ssryxynt.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.bjfxy.top/Article/details/gt2colbggfk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.feifeiyinyue.top/Article/details/gt2dmriaehj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.316326.xyz/Article/details/gt2bhezbfmr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.316326.xyz/Article/details/gt2dhthibnz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jqgfzy.top/Article/details/gt2suxeembx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gaohongyu789.top/Article/details/gt2obponaiz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhoulong.xyz/Article/details/gt2nqczwnzx.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.aibaodan.cn/Article/details/gt2xfivxrde.html

[J09] 时区处理
来源：http://dali.zdqjudy.top/Article/details/gt2wgjkkkck.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2glvvsneq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yanxiufei.cn/Article/details/gt2axwycvmq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnxiangtu.top/Article/details/gt2bdelgxep.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zsyzzrgf.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.c1oappe.top/Article/details/gt2mmandjeq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.pycfn.com/Article/details/gt2xelzafsj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.snrcjt.cn/Article/details/gt2snytczsz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenlongwang.top/Article/details/gt2tgnwszyz.html

[J10] 取今天 / 本月第一天
来源：http://dali.wangdashe.top/Article/details/gt2ibdwfgle.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sysykeji.top/Article/details/gt2udnwnsxi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.smart0.xyz/Article/details/gt2ezifupfb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.aibaodan.cn/Article/details/gt2mjecpudr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.nanxinkj.top/Article/details/gt2jqgwqaer.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yuanzhike.top/Article/details/gt2sjxzbpmn.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hnxiangtu.top/Article/details/gt2uypgxvwo.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.guowangkeji.top/Article/details/gt2qmbqzarf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gogol.net.cn/Article/details/gt2nbihqmcn.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2lyaqynni.html

K. JSON 与序列化
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bwbnurck.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2jrpooqoi.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bxsawezq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xinyue.icu/Article/details/gt2xrnhgeof.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgufenzy.top/Article/details/gt2jgtgtncf.html

JS:   JSON.stringify(obj)
来源：http://dali.yuxming.cn/Article/details/gt2bfhdhhxb.html

TS:   JSON.stringify(obj)
来源：http://dali.wangdashe.top/Article/details/gt2nojjmldl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.chenlongwang.top/Article/details/gt2qcwqbfyk.html

Go:   json.Marshal(obj)
来源：http://dali.tian-w.cn/Article/details/gt2yumvajql.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.daxiang520.top/Article/details/gt2uiodsuta.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2mqqwsgyt.html

[K02] JSON 字符串转对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jkdowove.html

Py:   json.loads(s)
来源：http://dali.cashguo.top/Article/details/gt2rcnjlgta.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hongshengwenyu.top/Article/details/gt2qnjnjluu.html

JS:   JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gt2cchumsap.html

TS:   JSON.parse(s)
来源：http://dali.yuanzhike.top/Article/details/gt2ahhdizmd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qouusikm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ivvv.top/Article/details/gt2fvoudnap.html

Ruby: JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gt2eapuddsx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cucudq.cn/Article/details/gt2rgfeqtyj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yj202588.top/Article/details/gt2jtnvnkqr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhixingplan.top/Article/details/gt2xxelletn.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xziqi.cn/Article/details/gt2sjnyhpcv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.fengsongda.top/Article/details/gt2xltrbvdk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.9152youxi.cn/Article/details/gt2jtzuzboo.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.birdmap.top/Article/details/gt2pkxiqdfl.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xuanzx.com/Article/details/gt2nllpeudw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xinyue.icu/Article/details/gt2txuhsweu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xuetiantiany.cn/Article/details/gt2wgflwenf.html

[K04] 读取 JSON 文件
来源：http://dali.meibo888.top/Article/details/gt2bnrsraem.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2ivhbvvjz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.316326.xyz/Article/details/gt2kzslbkdj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.9152youxi.cn/Article/details/gt2aksumopa.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhoulong.xyz/Article/details/gt2flsdyoyf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dksmoijk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yj20258888.top/Article/details/gt2qfmnjegc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhengqikj.top/Article/details/gt2mjfhjvui.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hnqzz.top/Article/details/gt2rdqqvttu.html

[K05] 深拷贝对象
来源：http://dali.ydzc1.top/Article/details/gt2tnmswdot.html

Py:   copy.deepcopy(obj)
来源：http://dali.andypj.xyz/Article/details/gt2wwydzxpc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hammf.cn/Article/details/gt2lockriil.html

JS:   structuredClone(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2honficxc.html

TS:   structuredClone(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2bdgvrfuf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.haohaochexian.top/Article/details/gt2wkjxpfed.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.guowangkeji.top/Article/details/gt2wfguuifs.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zycfv.cn/Article/details/gt2lshiiafw.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hnxiangtu.top/Article/details/gt2uijfryvu.html

[K06] 解析 URL 查询串
来源：http://dali.cucudq.cn/Article/details/gt2hobsfril.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.quarkkingdee.top/Article/details/gt2trdoydkz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.birdmap.top/Article/details/gt2idwbmske.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shzxlz.cn/Article/details/gt2ybhimgph.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gogol.net.cn/Article/details/gt2kpoqlmtu.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yvedp.cn/Article/details/gt2wqxrtxma.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.birdmap.top/Article/details/gt2dxrqkbrx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jianghu66.top/Article/details/gt2avbleatn.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.iojbl.cn/Article/details/gt2vekgzsyb.html

[K07] 进制转换
来源：http://dali.jyoumei.cn/Article/details/gt2zzhklsrt.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gt2qlvqwyfv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.mhx1999.top/Article/details/gt2dhjlnoqc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gt2wvgdorij.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gt2dxiefxwi.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.birdmap.top/Article/details/gt2qeshyuql.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhoulong.xyz/Article/details/gt2axqpxqix.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jiagoushi.top/Article/details/gt2ecekkljf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gt2vptewzvy.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.chenlongwang.top/Article/details/gt2tvjnersd.html

Py:   pickle.dumps(obj)
来源：http://dali.hnqzz.top/Article/details/gt2pdeerxjw.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ybcxt.top/Article/details/gt2oyadolol.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.smart0.xyz/Article/details/gt2wxjfjdqg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.haohaochexian.top/Article/details/gt2ovguktkf.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cashguo.top/Article/details/gt2bjpstwnf.html

Go:   encoding/gob
来源：http://dali.cqqwz.cn/Article/details/gt2vsfaxtgl.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2ydijqvkm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ybcxt.top/Article/details/gt2wbgnkuxa.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2yxgbglls.html

L. 网络请求
来源：http://dali.andypj.xyz/Article/details/gt2xclwwngw.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tgmuwvzs.html

[L01] 发送 GET 请求
来源：http://dali.iojbl.cn/Article/details/gt2feftonop.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ehwqpu.com/Article/details/gt2fwpwqznj.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.chenzaomai.com/Article/details/gt2myztsexv.html

JS:   await fetch(url)
来源：http://dali.haohaochexian.top/Article/details/gt2qmiiyrvj.html

TS:   await fetch(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ujkrhbwu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hysaishi.cn/Article/details/gt2exglewlw.html

Go:   resp, err := http.Get(url)
来源：http://dali.hongshengwenyu.top/Article/details/gt2abpootsb.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hywenlv.cn/Article/details/gt2dzmlbmos.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yuanzhike.top/Article/details/gt2kdlnrctd.html

[L02] 发送 POST JSON
来源：http://dali.nwbrower.top/Article/details/gt2lcmmzvot.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.wangdashe.top/Article/details/gt2funzevjq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.svipenyu.cn/Article/details/gt2laalhogz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2odwweqiy.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hnqzz.top/Article/details/gt2utibwopp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yonumen.top/Article/details/gt2gphcaavr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.iojbl.cn/Article/details/gt2pqwcjjlk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.tianlin.xyz/Article/details/gt2jvfvdsfr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.daxiang520.top/Article/details/gt2vnysppgd.html

[L03] 设置自定义请求头
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pxjjyfoz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.aizwys.cn/Article/details/gt2atkxfmgv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.0kj1m.cn/Article/details/gt2rsidlsyv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gaohongyu789.top/Article/details/gt2ksekqfbn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nwbrower.top/Article/details/gt2pwitmwkq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.316326.xyz/Article/details/gt2eaxpqlpv.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sufxvd.cn/Article/details/gt2icnnlwzm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hfpthk.cn/Article/details/gt2cbmkwoen.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zycfv.cn/Article/details/gt2dadmzzte.html

[L04] 设置超时
来源：http://dali.tianlin.xyz/Article/details/gt2hkixcbzk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinqigfzy.top/Article/details/gt2yovwjbvu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jlsjyb.cn/Article/details/gt2frbyroba.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dashuyun.cn/Article/details/gt2pbjjetcu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangshuangyany.cn/Article/details/gt2oipnnqbf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.kuanghao11.cn/Article/details/gt2xnfgukrj.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shzxlz.cn/Article/details/gt2axyfnxcz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.feifeiyinyue.top/Article/details/gt2gkvmbncr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.birdmap.top/Article/details/gt2yulbwuud.html

[L05] 上传文件（multipart）
来源：http://dali.snrcjt.cn/Article/details/gt2paufudlg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhoulong.xyz/Article/details/gt2jgxujpca.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.smart0.xyz/Article/details/gt2yelbzjwn.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gzhubu.top/Article/details/gt2tifgsivz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gotoacloud.top/Article/details/gt2iojexdsr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.pycfn.com/Article/details/gt2fqlyzcri.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yonumen.top/Article/details/gt2ejwuokvo.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.nanxuanxn.top/Article/details/gt2qepslfbd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xfvgrguj.html

[L06] 解析响应为 JSON
来源：http://dali.cheryme.top/Article/details/gt2kkelpfdl.html

Py:   resp.json()
来源：http://dali.sxryk.cn/Article/details/gt2qxetxynt.html

PHP:  json_decode($body, true);
来源：http://dali.tanke756.top/Article/details/gt2ztboifrn.html

JS:   await resp.json()
来源：http://dali.cheryme.top/Article/details/gt2woykskdu.html

TS:   await resp.json()
来源：http://dali.zhiwuduotai.top/Article/details/gt2iysjmzcb.html


<!-- 参考信息 -->