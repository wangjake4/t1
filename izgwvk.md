代发 wailian999

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.meibo888.top/Article/details/gtyqqgwlux.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.chenlongwang.top/Article/details/gtfbmawcvg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tianlin.xyz/Article/details/gtrujaibrq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.fengsongda.top/Article/details/gtgnbjmlzv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtjtkqluok.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hywenlv.cn/Article/details/gteknprjua.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhongyouzk.top/Article/details/gtchbypcrt.html

[H10] 资源自动释放
来源：http://dali.gaohongyu789.top/Article/details/gtrzonytqq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yvedp.cn/Article/details/gtihbduodw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.vqdsnc.cn/Article/details/gtdnbfrxaj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dianchejie.cn/Article/details/gtulawnkfd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.iojbl.cn/Article/details/gtgwrpvujy.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yuxming.cn/Article/details/gtnmftmpjb.html

Go:   defer f.Close()
来源：http://dali.yonumen.top/Article/details/gtkqyfmuik.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.haohaochexian.top/Article/details/gtddngylnu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtwcmacuxc.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtuuwzmmpv.html

I. 正则表达式
来源：http://dali.aizwys.cn/Article/details/gtfuyeoudm.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtingpkoor.html

[I01] 判断是否匹配
来源：http://dali.daxiang520.top/Article/details/gtwjazjvbf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cashguo.top/Article/details/gtgtebelmh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.aibaodan.cn/Article/details/gtuujkfqbm.html

JS:   /\d+/.test(s)
来源：http://dali.cheryme.top/Article/details/gtwukcexsw.html

TS:   /\d+/.test(s)
来源：http://dali.jqgfzy.top/Article/details/gtocqfnhqd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.meibo888.top/Article/details/gtmjwlkpcb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.svipenyu.cn/Article/details/gtlahnsuff.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqgszuxxt.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zycfv.cn/Article/details/gtkrrkjhsp.html

[I02] 提取所有匹配
来源：http://dali.gzhubu.top/Article/details/gtzdyfscqc.html

Py:   re.findall(r"\d+", s)
来源：http://dali.dashuyun.cn/Article/details/gtbfwxzirh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ehwqpu.com/Article/details/gtznstteli.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zdqjudy.top/Article/details/gtcixjgzqa.html

TS:   s.match(/\d+/g)
来源：http://dali.cdnleiting.top/Article/details/gtdbkckqlu.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhixingplan.top/Article/details/gtbmgloykh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.tian-w.cn/Article/details/gtpevnqzzh.html

Ruby: s.scan(/\d+/)
来源：http://dali.redwolf501.top/Article/details/gtrlavnwvz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.316326.xyz/Article/details/gtysmburel.html

[I03] 提取捕获分组
来源：http://dali.xziqi.cn/Article/details/gtpptfgskf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sxryk.cn/Article/details/gtxiylqlby.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.guannengcc.top/Article/details/gtxkpxkyoi.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ehwqpu.com/Article/details/gtevppugwi.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.316326.xyz/Article/details/gtvrkxvrrt.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jlsjyb.cn/Article/details/gtaosfcrnc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ydzc1.top/Article/details/gtreaujfaf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sweek.top/Article/details/gtmcvvbzki.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jqgfzy.top/Article/details/gtncjglgvp.html

[I04] 正则替换
来源：http://dali.jiagoushi.top/Article/details/gtfxgkaxyp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinqigfzy.top/Article/details/gtdnespbrv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hysaishi.cn/Article/details/gtfzrehxlt.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhiwuduotai.top/Article/details/gtafjjrayb.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.haohaochexian.top/Article/details/gtovomednx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hywenlv.cn/Article/details/gtacojkxab.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tian-w.cn/Article/details/gtyidilhpq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.smart0.xyz/Article/details/gtlrnnfltx.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sufxvd.cn/Article/details/gtvtkwpavi.html

[I05] 按正则拆分
来源：http://dali.cdnleiting.top/Article/details/gtrtfsurmg.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yvedp.cn/Article/details/gtqlihxitw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.dianchejie.cn/Article/details/gtlowyqinu.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hywenlv.cn/Article/details/gtyqotjvjd.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.aibaodan.cn/Article/details/gtxjlrscfs.html

Java: s.split("\\s*,\\s*")
来源：http://dali.aibaodan.cn/Article/details/gthfuuwmls.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.quarkkingdee.top/Article/details/gtiymzzqah.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gtttkzcsnc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hywenlv.cn/Article/details/gteeyqnoym.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.fengsongda.top/Article/details/gtrnhcruop.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yuxming.cn/Article/details/gtzhqwawfd.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.snrcjt.cn/Article/details/gtqvtysmyh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenlongwang.top/Article/details/gttsrwvunj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinghuilouyu.cn/Article/details/gtiajhwpno.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.feifeiyinyue.top/Article/details/gtkyoljnlk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shuidangran.top/Article/details/gtjfswazxt.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.kuanghao11.cn/Article/details/gtmhvawyya.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yangfankeji.com/Article/details/gtaphiiqfc.html

[I07] 忽略大小写与多行模式
来源：http://dali.cdnleiting.top/Article/details/gtktpqmifn.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sysykeji.top/Article/details/gtbchsqdll.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cheryme.top/Article/details/gtikxcpizu.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hongshengwenyu.top/Article/details/gthnezguuv.html

TS:   /error/gim
来源：http://dali.yj202588.top/Article/details/gtmbywuzvi.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhixingplan.top/Article/details/gtbwwmiqnf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ehwqpu.com/Article/details/gtjuglnctb.html

Ruby: s.scan(/error/i)
来源：http://dali.shanyushiyangtech.top/Article/details/gthpoojjry.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinqigfzy.top/Article/details/gtfbsredde.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gogol.net.cn/Article/details/gtghrcvagj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.birdmap.top/Article/details/gtcxhwlusz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hywenlv.cn/Article/details/gtuocdymtt.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xinyue.icu/Article/details/gtbezkcity.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cqqwz.cn/Article/details/gthhfqvyqk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.wangdashe.top/Article/details/gtvfhvlnxx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.birdmap.top/Article/details/gtxqxoyukk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.aibaodan.cn/Article/details/gtqysmkecd.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cucudq.cn/Article/details/gtdumigdyq.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtjxgbyhoz.html

J. 日期与时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtidetmddc.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtdluwdrnj.html

[J01] 获取当前时间
来源：http://dali.jqgfzy.top/Article/details/gtvibtxkfy.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.snrcjt.cn/Article/details/gtjwsbdhes.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hywenlv.cn/Article/details/gtandyoamx.html

JS:   new Date();  Date.now()
来源：http://dali.zhiwuduotai.top/Article/details/gtwydtsgns.html

TS:   new Date();  Date.now()
来源：http://dali.daxiang520.top/Article/details/gtpmenqrii.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.svipenyu.cn/Article/details/gtwjenberw.html

Go:   time.Now()
来源：http://dali.gaohongyu789.top/Article/details/gtkwybngev.html

Ruby: Time.now
来源：http://dali.jianghu66.top/Article/details/gtkttdnnyh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jlsjyb.cn/Article/details/gtfzrpkdbx.html

[J02] 格式化输出
来源：http://dali.guannengcc.top/Article/details/gtqnhtkelm.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangdashe.top/Article/details/gtcalpcyot.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.smart0.xyz/Article/details/gtthtfpchv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.vqdsnc.cn/Article/details/gtdgntjaqv.html

TS:   d.toISOString()
来源：http://dali.yangfankeji.com/Article/details/gtnsbgbhlc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.tian-w.cn/Article/details/gtuvrovntc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhixingplan.top/Article/details/gtcwreuhjp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuxming.cn/Article/details/gtrridqmyn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.9152youxi.cn/Article/details/gtlztzouid.html

[J03] 字符串解析为日期
来源：http://dali.xinyue.icu/Article/details/gtniwksyrb.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hysaishi.cn/Article/details/gtknpkztbz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrecpflpo.html

JS:   new Date("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtytxnpmmg.html

TS:   new Date("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gtjqxiflhg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gtvqavuliv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtmoxneokb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gtfjepajob.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.fzhhl.top/Article/details/gtfqygdtks.html

[J04] 时间戳与日期互转
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfeavzxnj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.0kj1m.cn/Article/details/gtkbcwbepg.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cqqwz.cn/Article/details/gtrnodpove.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sweek.top/Article/details/gtcdzvnksd.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.aizwys.cn/Article/details/gtjqlnhlzg.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sweek.top/Article/details/gtuarojtae.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.guannengcc.top/Article/details/gtegpcujle.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gtmfjgpmma.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinqigfzy.top/Article/details/gttioudcgj.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenzaomai.com/Article/details/gtqywxsqka.html

Py:   now + timedelta(days=7)
来源：http://dali.sysykeji.top/Article/details/gtvwprnush.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shzxlz.cn/Article/details/gtjcvtbgoh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsranyivo.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfvcvlsbj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsvbcnggm.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jiagoushi.top/Article/details/gtbjbdvnlc.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbvvbdyxa.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xuetiantiany.cn/Article/details/gtdvwuqzna.html

[J06] 计算两时间之差
来源：http://dali.gotoacloud.top/Article/details/gtrwboqhyb.html

Py:   (end - start).total_seconds()
来源：http://dali.nwbrower.top/Article/details/gtmvhebpge.html

PHP:  $end->diff($start)->days;
来源：http://dali.hongshengwenyu.top/Article/details/gtsuvqwyaf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sweek.top/Article/details/gthhnkewbt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gaohongyu789.top/Article/details/gtxxmrdmno.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ivvv.top/Article/details/gtaipwwhgv.html

Go:   end.Sub(start).Hours()
来源：http://dali.yangfankeji.com/Article/details/gtvhwqrgkl.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shanyushiyangtech.top/Article/details/gtrfhbmebm.html

C#:   (end - start).TotalSeconds
来源：http://dali.ppjwa.cn/Article/details/gtdnirofpl.html

[J07] 比较两个日期
来源：http://dali.yuxming.cn/Article/details/gtvrorlckb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gtgxhnciiw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.chenjidiqi.icu/Article/details/gtktkoggpw.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hongshengwenyu.top/Article/details/gtujalhzml.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.quarkkingdee.top/Article/details/gtmszmlwcu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtosalpxot.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.tianlin.xyz/Article/details/gthaqhtqzm.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gtcmzwihgn.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.dianchejie.cn/Article/details/gtmyonpxkk.html

[J08] 提取年月日与星期
来源：http://dali.chenzaomai.com/Article/details/gtogghrhix.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.svipenyu.cn/Article/details/gtyslbokun.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.guowangkeji.top/Article/details/gtdneupsgf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yonumen.top/Article/details/gtyvlzatxg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhixingplan.top/Article/details/gtfkrkiykr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xuetiantiany.cn/Article/details/gthsipxbww.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.9152youxi.cn/Article/details/gtiwdbpnbo.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ppjwa.cn/Article/details/gtldadkjpb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gotoacloud.top/Article/details/gtnuofsduf.html

[J09] 时区处理
来源：http://dali.shanyushiyangtech.top/Article/details/gtpwrdrixx.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.kuanghao11.cn/Article/details/gtlsvmocnt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.chenjidiqi.icu/Article/details/gtlbzqcmfc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hfpthk.cn/Article/details/gtieilwccc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pycfn.com/Article/details/gtrhagxlqj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yuanzhike.top/Article/details/gtvdbkezep.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.guannengcc.top/Article/details/gtcqturqmo.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sysykeji.top/Article/details/gtfswrvkrm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.andypj.xyz/Article/details/gtwewiowha.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinqigfzy.top/Article/details/gtfusqpzov.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinqigufen.top/Article/details/gtsvmcabgj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.guannengcc.top/Article/details/gtakyeyvoc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yonumen.top/Article/details/gtptaoxdcq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.wangdashe.top/Article/details/gtgtodjtgi.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtpdgbubok.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zycfv.cn/Article/details/gtmsvqnbkg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gogol.net.cn/Article/details/gtsmoazclw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.daxiang520.top/Article/details/gtbuhwhndk.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtsmkiwuaf.html

K. JSON 与序列化
来源：http://dali.andypj.xyz/Article/details/gtjkjyxgrz.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtapjsqwax.html

[K01] 对象转 JSON 字符串
来源：http://dali.zycfv.cn/Article/details/gtwrswwhfv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhengqikj.top/Article/details/gtsjoggano.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.guannengcc.top/Article/details/gtwjhatzel.html

JS:   JSON.stringify(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtwlvwmdhg.html

TS:   JSON.stringify(obj)
来源：http://dali.havefunace.top/Article/details/gtesjmffor.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yuanzhike.top/Article/details/gtqenhmffh.html

Go:   json.Marshal(obj)
来源：http://dali.ppjwa.cn/Article/details/gtsmodutyp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.guowangkeji.top/Article/details/gttadwtczd.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtdeqtijqk.html

[K02] JSON 字符串转对象
来源：http://dali.pycfn.com/Article/details/gtpxnluhwe.html

Py:   json.loads(s)
来源：http://dali.wangdashe.top/Article/details/gtpyxhjlct.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.snrcjt.cn/Article/details/gtlhcpgwcu.html

JS:   JSON.parse(s)
来源：http://dali.wangdashe.top/Article/details/gtlmgllvfg.html

TS:   JSON.parse(s)
来源：http://dali.ydzc1.top/Article/details/gtbgglcscs.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinghuilouyu.cn/Article/details/gtltokfzom.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.mhx1999.top/Article/details/gtiijegcew.html

Ruby: JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gtaoppxfbo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ehwqpu.com/Article/details/gtgdjmybtc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yanxiufei.cn/Article/details/gtgmpppcak.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nanxuanxn.top/Article/details/gtikuhqjiz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.chenzaomai.com/Article/details/gtzefnfvrj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.fzhhl.top/Article/details/gttqjkfcwu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtepwziekm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmbfskdej.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.wangshuangyany.cn/Article/details/gtjyeiugma.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.chenlongwang.top/Article/details/gtmvomhzak.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.dashuyun.cn/Article/details/gtxiawysfb.html

[K04] 读取 JSON 文件
来源：http://dali.jinqigufen.top/Article/details/gtnacbszsb.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.feifeiyinyue.top/Article/details/gtwqrisqbz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.guowangkeji.top/Article/details/gtrirmtwox.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guannengcc.top/Article/details/gtqqowskis.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.c1oappe.top/Article/details/gtnobzeiky.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.chenjidiqi.icu/Article/details/gtfgljlyow.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xinyue.icu/Article/details/gtfleiihrw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.wangdashe.top/Article/details/gtetsdepoq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.havefunace.top/Article/details/gtofiptkxy.html

[K05] 深拷贝对象
来源：http://dali.vqdsnc.cn/Article/details/gtlvpdtlfc.html

Py:   copy.deepcopy(obj)
来源：http://dali.wangdashe.top/Article/details/gtbztawvgh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.nanxinkj.top/Article/details/gtptkfnxrr.html

JS:   structuredClone(obj)
来源：http://dali.hywenlv.cn/Article/details/gtbhgmieoq.html

TS:   structuredClone(obj)
来源：http://dali.haohaochexian.top/Article/details/gtmkoazfay.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.fzhhl.top/Article/details/gtwyidayqb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jlsjyb.cn/Article/details/gtrricbabq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.chenjidiqi.icu/Article/details/gtugrokwnz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sweek.top/Article/details/gtkmhvhirs.html

[K06] 解析 URL 查询串
来源：http://dali.zdqjudy.top/Article/details/gtllhjlmqv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinqigfzy.top/Article/details/gtkrrjnfoj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.bjfxy.top/Article/details/gtcivwvepi.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangdashe.top/Article/details/gtrsjnvucj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shzxlz.cn/Article/details/gtfpjocjpj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.chenjidiqi.icu/Article/details/gtwkpkcili.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gtdukpuhaj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shuidangran.top/Article/details/gtsovgrnvc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gtbgkmpifh.html

[K07] 进制转换
来源：http://dali.gogol.net.cn/Article/details/gtvtzggotk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgtaqevan.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hnqzz.top/Article/details/gttmlwfywi.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yonumen.top/Article/details/gtgombjjus.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwfejrubq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtycznecib.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkunqvcez.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.vqdsnc.cn/Article/details/gtejyhobul.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gtgohtmwyg.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.dashuyun.cn/Article/details/gttpkvpqhf.html

Py:   pickle.dumps(obj)
来源：http://dali.hysaishi.cn/Article/details/gtbjubzvok.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.andypj.xyz/Article/details/gtzmwwvhtm.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.pycfn.com/Article/details/gtrimrfzta.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.svipenyu.cn/Article/details/gtcyivzqia.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gotoacloud.top/Article/details/gtigwqyzin.html

Go:   encoding/gob
来源：http://dali.shuidangran.top/Article/details/gtrwxqzvzn.html

Ruby: Marshal.dump(obj)
来源：http://dali.jyoumei.cn/Article/details/gtniifxaxi.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.birdmap.top/Article/details/gttixogjey.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtsasoirym.html

L. 网络请求
来源：http://dali.xuetiantiany.cn/Article/details/gtxefhbmls.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtntvgzeen.html

[L01] 发送 GET 请求
来源：http://dali.tian-w.cn/Article/details/gtxqyldxix.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.dashuyun.cn/Article/details/gtyustydqp.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sweek.top/Article/details/gtsfsouvtk.html

JS:   await fetch(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtviwmjlrb.html

TS:   await fetch(url)
来源：http://dali.ydzc1.top/Article/details/gtebwmqwyd.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sxryk.cn/Article/details/gtnozhsnxy.html

Go:   resp, err := http.Get(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gthsfukqag.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gaohongyu789.top/Article/details/gtiyamopee.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yongpay.top/Article/details/gtuupxtces.html

[L02] 发送 POST JSON
来源：http://dali.redwolf501.top/Article/details/gtcmlkqvvz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenlongwang.top/Article/details/gtjoghlwxn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hammf.cn/Article/details/gtgmltmlft.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cheryme.top/Article/details/gthcrxuklw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cashguo.top/Article/details/gtjhelnjvw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenzaomai.com/Article/details/gtthnaodjv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.guowangkeji.top/Article/details/gtantglbcm.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.kuanghao11.cn/Article/details/gthdjfstan.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.tian-w.cn/Article/details/gtsohfixlg.html

[L03] 设置自定义请求头
来源：http://dali.hnxiangtu.top/Article/details/gtdvgszidf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.tianlin.xyz/Article/details/gtcbwvopxr.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.daria6918.cn/Article/details/gtsgzjyuip.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.andypj.xyz/Article/details/gtqzlvijks.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinghuilouyu.cn/Article/details/gtkagcyhpq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xuetiantiany.cn/Article/details/gtudenablm.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.nwbrower.top/Article/details/gtgesujsdv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xuetiantiany.cn/Article/details/gtmnbowqkt.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hongshengwenyu.top/Article/details/gthoazbsff.html

[L04] 设置超时
来源：http://dali.gotoacloud.top/Article/details/gtkfaubfig.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shanyushiyangtech.top/Article/details/gtotrkqbpj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.birdmap.top/Article/details/gtwxzqrhdo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gaohongyu789.top/Article/details/gtawcyrvop.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjerfmjyy.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hfpthk.cn/Article/details/gtzsuzzwnh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhengqikj.top/Article/details/gttbmnojxn.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.haohaochexian.top/Article/details/gtvmdyrhcm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.feifeiyinyue.top/Article/details/gtcbircxdx.html

[L05] 上传文件（multipart）
来源：http://dali.cdnleiting.top/Article/details/gthjndnggq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.tian-w.cn/Article/details/gtcwdbcznr.html


<!-- 参考信息 -->