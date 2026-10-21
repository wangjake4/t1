代发 wailian999

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthowhgzab.html

Go:   defer f.Close()
来源：http://dali.gogol.net.cn/Article/details/gterqzgdei.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.fengsongda.top/Article/details/gtwswwjvut.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtuebhlwlt.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtcvuqiaqh.html

I. 正则表达式
来源：http://dali.guannengcc.top/Article/details/gtlqiinbeb.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtizdasuwh.html

[I01] 判断是否匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmscviaxl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cheryme.top/Article/details/gtlaefsmxa.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yuanzhike.top/Article/details/gtvyqelanp.html

JS:   /\d+/.test(s)
来源：http://dali.xinyue.icu/Article/details/gtglxfknqe.html

TS:   /\d+/.test(s)
来源：http://dali.jqgfzy.top/Article/details/gtkuegyqaf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.pengpengdd.cyou/Article/details/gtfushjivl.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cdnleiting.top/Article/details/gtezgytcew.html

Ruby: s.match?(/\d+/)
来源：http://dali.gogol.net.cn/Article/details/gtdewbvmlm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.sysykeji.top/Article/details/gtfhaovwno.html

[I02] 提取所有匹配
来源：http://dali.jqgfzy.top/Article/details/gtbnstvbrx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xylfe.cn/Article/details/gtjekdjlnm.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.fengsongda.top/Article/details/gtycemshjn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.daxiang520.top/Article/details/gttqjhscak.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gtxlehusoe.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.wangdashe.top/Article/details/gtwrlfjtwt.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xuetiantiany.cn/Article/details/gtaldcfkei.html

Ruby: s.scan(/\d+/)
来源：http://dali.ydzc1.top/Article/details/gtemqgrbzk.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.tian-w.cn/Article/details/gtwfuwriai.html

[I03] 提取捕获分组
来源：http://dali.hongshengwenyu.top/Article/details/gtjcqfattt.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.chenlongwang.top/Article/details/gtesqmdgnu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hnqzz.top/Article/details/gtofzokden.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hammf.cn/Article/details/gtvrixnmnw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shzxlz.cn/Article/details/gtnzjylvxv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.wangdashe.top/Article/details/gtqdfuhxqq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yuanzhike.top/Article/details/gtexzexzmr.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmizvvllv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sxryk.cn/Article/details/gtjluqzjpi.html

[I04] 正则替换
来源：http://dali.yuanzhike.top/Article/details/gtajmxwvmx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jqgufenzy.top/Article/details/gtqapdpjag.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.bjfxy.top/Article/details/gtxdlmuees.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.haohaochexian.top/Article/details/gtpukjuurv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.nwbrower.top/Article/details/gtimsvwocy.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gtgzdzhyui.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.pycfn.com/Article/details/gtzrpesvvh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hysaishi.cn/Article/details/gtsakamutl.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cucudq.cn/Article/details/gtlsjezqhn.html

[I05] 按正则拆分
来源：http://dali.kuanghao11.cn/Article/details/gtobobcnzt.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xziqi.cn/Article/details/gttlbcqjdm.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpumxufcs.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zdqjudy.top/Article/details/gteagplffb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shuidangran.top/Article/details/gtdcqytqec.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nwbrower.top/Article/details/gteazaahdj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.fzhhl.top/Article/details/gtjmjabqei.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hywenlv.cn/Article/details/gtftwjwhir.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.haohaochexian.top/Article/details/gtajkptakv.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.wangshuangyany.cn/Article/details/gtqecewsxg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hnqzz.top/Article/details/gtdiapdvzx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ydzc1.top/Article/details/gthtduyfgh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuxming.cn/Article/details/gtpnwzckfa.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fengsongda.top/Article/details/gtfkafvtha.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhoulong.xyz/Article/details/gtunpotfzc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jiagoushi.top/Article/details/gthukgqbjd.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.wangshuangyany.cn/Article/details/gtsnaivdpg.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gtodinznhi.html

[I07] 忽略大小写与多行模式
来源：http://dali.ivvv.top/Article/details/gtxbkxftzx.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.tanke756.top/Article/details/gtfkyjxglx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyhzsgtep.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.feifeiyinyue.top/Article/details/gtuarltfpm.html

TS:   /error/gim
来源：http://dali.jinqigufen.top/Article/details/gtjhxpkhvp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jianghu66.top/Article/details/gtrflxnswt.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shzxlz.cn/Article/details/gtvkertcee.html

Ruby: s.scan(/error/i)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgnjgkdsp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.aibaodan.cn/Article/details/gtpbbajbkf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jianghu66.top/Article/details/gtmqheeyws.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yongpay.top/Article/details/gttztuqfpt.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cashguo.top/Article/details/gtfmcyrkuz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aibaodan.cn/Article/details/gtvyiwdfov.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnxiangtu.top/Article/details/gtfzzkeofl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hfpthk.cn/Article/details/gtzanwsacp.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.nwbrower.top/Article/details/gtztgpkulb.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj20258.top/Article/details/gtjlrczjxw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.aizwys.cn/Article/details/gtjdpxmjqa.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtjystlmkj.html

J. 日期与时间
来源：http://dali.hnqzz.top/Article/details/gtnvycjhcx.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtweokcxhy.html

[J01] 获取当前时间
来源：http://dali.hysaishi.cn/Article/details/gtyimncvpo.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nanxuanxn.top/Article/details/gtjlvqtgne.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xylfe.cn/Article/details/gtboayiizy.html

JS:   new Date();  Date.now()
来源：http://dali.9152youxi.cn/Article/details/gtrhfdzxzt.html

TS:   new Date();  Date.now()
来源：http://dali.yj20258.top/Article/details/gtylpuqesl.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhijiandao.cn/Article/details/gtsaudeyhy.html

Go:   time.Now()
来源：http://dali.aibaodan.cn/Article/details/gtyracdxxu.html

Ruby: Time.now
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjfbnevuc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yonumen.top/Article/details/gtuvilfndg.html

[J02] 格式化输出
来源：http://dali.guannengcc.top/Article/details/gtxsvahhxf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fzhhl.top/Article/details/gtghameoku.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jlsjyb.cn/Article/details/gtbtpfbzsh.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.fengsongda.top/Article/details/gttiwsewoi.html

TS:   d.toISOString()
来源：http://dali.tian-w.cn/Article/details/gthuqikuvb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hnqzz.top/Article/details/gtdjykuors.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ybcxt.top/Article/details/gtrsdjnjmk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenlongwang.top/Article/details/gtppacywrt.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhoulong.xyz/Article/details/gttkxghfzg.html

[J03] 字符串解析为日期
来源：http://dali.iojbl.cn/Article/details/gtsnwsgedw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jlsjyb.cn/Article/details/gtpfbghxbw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.aibaodan.cn/Article/details/gtfaibjxxy.html

JS:   new Date("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gtfnzfygdp.html

TS:   new Date("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gtxnvvdxgy.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gtvbtmnmec.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtnsxkklkx.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gtxudqnxyr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmthylhul.html

[J04] 时间戳与日期互转
来源：http://dali.mhx1999.top/Article/details/gtfxxrxohl.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sxryk.cn/Article/details/gtwmjuenli.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shanyushiyangtech.top/Article/details/gtxtfpvrrp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.daxiang520.top/Article/details/gtcewaqtwo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.0kj1m.cn/Article/details/gtwndmgbwa.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.kuanghao11.cn/Article/details/gtrbkbqxri.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jianghu66.top/Article/details/gtudedrysm.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sweek.top/Article/details/gtaoufhkta.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nanxinkj.top/Article/details/gtoalfwseu.html

[J05] 时间加减（加 7 天）
来源：http://dali.nanxinkj.top/Article/details/gtfqcisrjx.html

Py:   now + timedelta(days=7)
来源：http://dali.zhijiandao.cn/Article/details/gtejkglxau.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sufxvd.cn/Article/details/gtffznwhsb.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sysykeji.top/Article/details/gtacdvzusw.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhiwuduotai.top/Article/details/gtwxmamhoc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zdqjudy.top/Article/details/gtzkoeevgj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yuanzhike.top/Article/details/gtnouejvci.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhixingplan.top/Article/details/gtqspsenwg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ppjwa.cn/Article/details/gtsamtyznv.html

[J06] 计算两时间之差
来源：http://dali.jianghu66.top/Article/details/gtxxxfbvod.html

Py:   (end - start).total_seconds()
来源：http://dali.chenjidiqi.icu/Article/details/gtarmwcbim.html

PHP:  $end->diff($start)->days;
来源：http://dali.sweek.top/Article/details/gtqfdtffij.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sufxvd.cn/Article/details/gtnyeepiiy.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jiagoushi.top/Article/details/gtuiwtbegz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.daxiang520.top/Article/details/gtsjntbqyw.html

Go:   end.Sub(start).Hours()
来源：http://dali.kuanghao11.cn/Article/details/gtwnjiethz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shuidangran.top/Article/details/gtsoaziqhe.html

C#:   (end - start).TotalSeconds
来源：http://dali.sxryk.cn/Article/details/gtpytgqofd.html

[J07] 比较两个日期
来源：http://dali.hongshengwenyu.top/Article/details/gtjogoqwtm.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.dianchejie.cn/Article/details/gtpuzabfkl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yangfankeji.com/Article/details/gtmucyunex.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nwbrower.top/Article/details/gticlujzke.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhoulong.xyz/Article/details/gtjusihqjq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.fengsongda.top/Article/details/gtitevmakm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hnqzz.top/Article/details/gtseuueose.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.haohaochexian.top/Article/details/gtpxahoqxm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gtvgvqhatp.html

[J08] 提取年月日与星期
来源：http://dali.xinyue.icu/Article/details/gttrzkibbz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ehwqpu.com/Article/details/gtkqpyeigs.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.feifeiyinyue.top/Article/details/gtyhiopcry.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xylfe.cn/Article/details/gtcszkhcvr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.iojbl.cn/Article/details/gtmkwfskbx.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sweek.top/Article/details/gtuyizxyim.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hammf.cn/Article/details/gtufbbaoru.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.feifeiyinyue.top/Article/details/gtgiacpzwk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.daria6918.cn/Article/details/gtemgdtdqh.html

[J09] 时区处理
来源：http://dali.shuidangran.top/Article/details/gtivchlilo.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.chenjidiqi.icu/Article/details/gtihafydbn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.vqdsnc.cn/Article/details/gtdkxntwel.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.meibo888.top/Article/details/gtjpytuzbi.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.havefunace.top/Article/details/gtwvudiejp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jlsjyb.cn/Article/details/gtptaqlbru.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cqqwz.cn/Article/details/gtwkibduyf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.chenzaomai.com/Article/details/gtdxdbzjyg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zdqjudy.top/Article/details/gtdtshhecd.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenjidiqi.icu/Article/details/gtwldauqxw.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.vqdsnc.cn/Article/details/gtblznwsde.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xziqi.cn/Article/details/gtpxefzprf.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cdnleiting.top/Article/details/gthrmezvdc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtlsistezh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hammf.cn/Article/details/gtdvgtifrw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.wangdashe.top/Article/details/gtcqgolmng.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.svipenyu.cn/Article/details/gtwcxxpsal.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtdnznznkv.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gteqjphloe.html

K. JSON 与序列化
来源：http://dali.tian-w.cn/Article/details/gtwphfupdj.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtmtwtpmfe.html

[K01] 对象转 JSON 字符串
来源：http://dali.yonumen.top/Article/details/gtoetyrxzi.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ivvv.top/Article/details/gtmayxclgb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.chenzaomai.com/Article/details/gtvcorrvav.html

JS:   JSON.stringify(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtaxacrbee.html

TS:   JSON.stringify(obj)
来源：http://dali.gogol.net.cn/Article/details/gtajaynhge.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cdnleiting.top/Article/details/gtglhdpsiw.html

Go:   json.Marshal(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtmfttrkxl.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xinyue.icu/Article/details/gteupqhdzg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxigwapoe.html

[K02] JSON 字符串转对象
来源：http://dali.chenlongwang.top/Article/details/gtcgvlhpyw.html

Py:   json.loads(s)
来源：http://dali.aizwys.cn/Article/details/gtjaqnssgy.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.bjfxy.top/Article/details/gtrgirmamp.html

JS:   JSON.parse(s)
来源：http://dali.mhx1999.top/Article/details/gteldbldzh.html

TS:   JSON.parse(s)
来源：http://dali.havefunace.top/Article/details/gtcxkhyjzb.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ydzc1.top/Article/details/gtswqfkaer.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhiwuduotai.top/Article/details/gtbpguobpz.html

Ruby: JSON.parse(s)
来源：http://dali.cashguo.top/Article/details/gtzbfmbauz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hnxiangtu.top/Article/details/gtbpxcpwdw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gaohongyu789.top/Article/details/gtkmcaeayi.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.0kj1m.cn/Article/details/gtblodnccf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hysaishi.cn/Article/details/gticlmecnl.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.havefunace.top/Article/details/gtksvrnwof.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shuidangran.top/Article/details/gtlcncyffy.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tanke756.top/Article/details/gtckmbaspn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shuidangran.top/Article/details/gticcwhrns.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cashguo.top/Article/details/gtgccrzxlr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tanke756.top/Article/details/gtrwwjuyic.html

[K04] 读取 JSON 文件
来源：http://dali.aibaodan.cn/Article/details/gtaldqhbwc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.wangdashe.top/Article/details/gtpmyhychw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.iojbl.cn/Article/details/gtcgumnnhi.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangshuangyany.cn/Article/details/gtcowpuvdd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tianlin.xyz/Article/details/gtfluqsggq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sweek.top/Article/details/gthovwogui.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.redwolf501.top/Article/details/gtuhayptfh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.quarkkingdee.top/Article/details/gtgbajxlmx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hysaishi.cn/Article/details/gtsvqhzums.html

[K05] 深拷贝对象
来源：http://dali.ehwqpu.com/Article/details/gtfhefrkow.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyhtdhgbn.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shangyingyoupin.top/Article/details/gtrvfosbgp.html

JS:   structuredClone(obj)
来源：http://dali.cheryme.top/Article/details/gtvxsrnutq.html

TS:   structuredClone(obj)
来源：http://dali.cucudq.cn/Article/details/gtwxyouewc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hongshengwenyu.top/Article/details/gtnucjocmy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jqgfzy.top/Article/details/gtdawpqooc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yanxiufei.cn/Article/details/gtwzvqbqcr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yanxiufei.cn/Article/details/gthtiqgqew.html

[K06] 解析 URL 查询串
来源：http://dali.shzxlz.cn/Article/details/gtynfnmhde.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hywenlv.cn/Article/details/gtupyoahsr.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.nanxinkj.top/Article/details/gtqoqvaibo.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtidgcergh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.kuanghao11.cn/Article/details/gtbjatlxgg.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gaohongyu789.top/Article/details/gthbozdolb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gtihuikjsq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhongyouzk.top/Article/details/gtmpcfycez.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yonumen.top/Article/details/gtueuykszd.html

[K07] 进制转换
来源：http://dali.shuidangran.top/Article/details/gtgwlmkkde.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzmpzgjjv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ehwqpu.com/Article/details/gtbtpzuyfc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.316326.xyz/Article/details/gtqltszrme.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gtbnladvfa.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gtwifbesrf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xuetiantiany.cn/Article/details/gtqjyothpi.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hnxiangtu.top/Article/details/gtatwqtqsk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtolovqwev.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.nanxuanxn.top/Article/details/gtelxrrdef.html

Py:   pickle.dumps(obj)
来源：http://dali.xuanzx.com/Article/details/gtpuqgqfco.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nanxinkj.top/Article/details/gtlvvamnws.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.chenzaomai.com/Article/details/gtfpeqcont.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.kuanghao11.cn/Article/details/gtcvrbrzoz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenzaomai.com/Article/details/gtycsbzgyo.html

Go:   encoding/gob
来源：http://dali.havefunace.top/Article/details/gtzvkoylad.html

Ruby: Marshal.dump(obj)
来源：http://dali.gzhubu.top/Article/details/gtiymktarq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.birdmap.top/Article/details/gtrelorqkb.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtmgkaebeg.html

L. 网络请求
来源：http://dali.aizwys.cn/Article/details/gtakomhepv.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtzoemvzow.html

[L01] 发送 GET 请求
来源：http://dali.pengpengdd.cyou/Article/details/gtqgurrcga.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yj20258888.top/Article/details/gtpumcutat.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.kuanghao11.cn/Article/details/gtjdbfvrtu.html

JS:   await fetch(url)
来源：http://dali.fengsongda.top/Article/details/gtoykoswhp.html

TS:   await fetch(url)
来源：http://dali.yvedp.cn/Article/details/gtzhirvttf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shzxlz.cn/Article/details/gtaqqfjfqj.html

Go:   resp, err := http.Get(url)
来源：http://dali.yuxming.cn/Article/details/gtbbowhmaa.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hnxiangtu.top/Article/details/gthyhilyzd.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cheryme.top/Article/details/gtayuctoee.html

[L02] 发送 POST JSON
来源：http://dali.c1oappe.top/Article/details/gtpddlrluy.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhiwuduotai.top/Article/details/gtmmbqyiyl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.gzhubu.top/Article/details/gtfxvwwqpy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.havefunace.top/Article/details/gtdvxvtdrq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtejpidlba.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xziqi.cn/Article/details/gtlqdtzpqo.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.chenzaomai.com/Article/details/gtpsvyydlr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.nanxuanxn.top/Article/details/gtednddllg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sysykeji.top/Article/details/gtlhoydubv.html

[L03] 设置自定义请求头
来源：http://dali.xinyue.icu/Article/details/gtyeggazpe.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yj20258888.top/Article/details/gtlfcwfiyl.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhengqikj.top/Article/details/gtxwoahsgj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pengpengdd.cyou/Article/details/gtingsgffz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxuanxn.top/Article/details/gtjshlrbtt.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hysaishi.cn/Article/details/gtesvydjsh.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gotoacloud.top/Article/details/gttdimkeas.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.andypj.xyz/Article/details/gtldnljrpf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jlsjyb.cn/Article/details/gtijmmqogc.html

[L04] 设置超时
来源：http://dali.c1oappe.top/Article/details/gtcloxvflx.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhiwuduotai.top/Article/details/gtrfgifzxa.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yj20258888.top/Article/details/gtwejzdwev.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuanzhike.top/Article/details/gtwujmqobl.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmgyuedmd.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.pycfn.com/Article/details/gtrlemmxkd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gaohongyu789.top/Article/details/gtqzrpmrgg.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yj20258888.top/Article/details/gtapycfdun.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.tianlin.xyz/Article/details/gtnsrbdaig.html

[L05] 上传文件（multipart）
来源：http://dali.yj20258888.top/Article/details/gttfaoxctj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.birdmap.top/Article/details/gtdamfymwk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.bjfxy.top/Article/details/gtaapkirjt.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtakmehtgr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cheryme.top/Article/details/gtzmztubej.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hammf.cn/Article/details/gtmvsgsrjd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinqigufen.top/Article/details/gtyszxpexb.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.daria6918.cn/Article/details/gtikvyjvkd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtlzjavifq.html

[L06] 解析响应为 JSON
来源：http://dali.ybcxt.top/Article/details/gtcgsgrgtc.html

Py:   resp.json()
来源：http://dali.zycfv.cn/Article/details/gtqdruptbi.html

PHP:  json_decode($body, true);
来源：http://dali.sxryk.cn/Article/details/gtbyipzajt.html

JS:   await resp.json()
来源：http://dali.zhiwuduotai.top/Article/details/gtokcscedi.html

TS:   await resp.json()
来源：http://dali.ybcxt.top/Article/details/gtflsbimwu.html


<!-- 参考信息 -->