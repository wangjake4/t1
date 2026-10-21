代发 wailian999

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.nanxinkj.top/Article/details/gtjlmkwxng.html

Go:   defer f.Close()
来源：http://dali.aizwys.cn/Article/details/gtrnlokozu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shuidangran.top/Article/details/gtxxemntxl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtlgodrvmg.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gttjaicamu.html

I. 正则表达式
来源：http://dali.birdmap.top/Article/details/gtmpwsvpjl.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtnsuhvtec.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gtjmuibgvq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.birdmap.top/Article/details/gtzaijsvwd.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yongpay.top/Article/details/gtizjskqfn.html

JS:   /\d+/.test(s)
来源：http://dali.pengpengdd.cyou/Article/details/gthmhwcjmp.html

TS:   /\d+/.test(s)
来源：http://dali.hnqzz.top/Article/details/gtbcprvtkm.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tanke756.top/Article/details/gtberejupg.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhongyouzk.top/Article/details/gtrtkighie.html

Ruby: s.match?(/\d+/)
来源：http://dali.dianchejie.cn/Article/details/gthmeivlad.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.aibaodan.cn/Article/details/gtyaiegmzc.html

[I02] 提取所有匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwtcrdvlc.html

Py:   re.findall(r"\d+", s)
来源：http://dali.svipenyu.cn/Article/details/gtjsnkhmwp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.quarkkingdee.top/Article/details/gtfwvkoumj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jiagoushi.top/Article/details/gthtticzdi.html

TS:   s.match(/\d+/g)
来源：http://dali.yj20258.top/Article/details/gtmovwqqeh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cashguo.top/Article/details/gtdnmqpujp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.fzhhl.top/Article/details/gtrwrayarx.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinqigufen.top/Article/details/gtablzjill.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.bjfxy.top/Article/details/gthafdbwqp.html

[I03] 提取捕获分组
来源：http://dali.shuidangran.top/Article/details/gtostpwfti.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yueranfly.top/Article/details/gtpextjebj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xuetiantiany.cn/Article/details/gtlzqruvmk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cucudq.cn/Article/details/gtmutfkrin.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.kuanghao11.cn/Article/details/gtyepahwlz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.pycfn.com/Article/details/gtrwpnmwew.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ehwqpu.com/Article/details/gtortneicq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hongshengwenyu.top/Article/details/gtwvjhihjx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.fzhhl.top/Article/details/gtywibrkif.html

[I04] 正则替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuqtmmzxw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gotoacloud.top/Article/details/gtqoahnbjn.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zdqjudy.top/Article/details/gttkblydve.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yongpay.top/Article/details/gtrpbvjfda.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigfzy.top/Article/details/gtkecjfkmy.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zdqjudy.top/Article/details/gtbihjzdoq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zycfv.cn/Article/details/gtxdlyfpqo.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ppjwa.cn/Article/details/gtzblwsovy.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shuidangran.top/Article/details/gtswntfbxo.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gtxiolnspw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.havefunace.top/Article/details/gttntubext.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.meibo888.top/Article/details/gteekgjpiq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yanxiufei.cn/Article/details/gtsxkwywlh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gtgcufjgeu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.9152youxi.cn/Article/details/gtxlzkjuqw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhixingplan.top/Article/details/gtbercsqor.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sysykeji.top/Article/details/gtbmllzhre.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ydzc1.top/Article/details/gtirusgzqa.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cheryme.top/Article/details/gtbmulzuru.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zdqjudy.top/Article/details/gtioimrjrn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiycxlsgu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhixingplan.top/Article/details/gtfwaovbzy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jianghu66.top/Article/details/gtpohqafkj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sxryk.cn/Article/details/gthsovkeqn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.quarkkingdee.top/Article/details/gtcfxsiexq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.quarkkingdee.top/Article/details/gttdizctra.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hysaishi.cn/Article/details/gtxnqmlqgm.html

[I07] 忽略大小写与多行模式
来源：http://dali.tianlin.xyz/Article/details/gtxpjqbina.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zdqjudy.top/Article/details/gtbcpokkjh.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.daria6918.cn/Article/details/gtupfspvzt.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.daria6918.cn/Article/details/gtvwkirgii.html

TS:   /error/gim
来源：http://dali.yvedp.cn/Article/details/gtkzwyzzab.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlmfrepjf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hammf.cn/Article/details/gtdltjjnjg.html

Ruby: s.scan(/error/i)
来源：http://dali.hfpthk.cn/Article/details/gteczprsrh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yvedp.cn/Article/details/gtkriyshej.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdbvlift.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.snrcjt.cn/Article/details/gtaiyeeljy.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jyoumei.cn/Article/details/gtwgvrkjmc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cdnleiting.top/Article/details/gtqkxoizuu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangshuangyany.cn/Article/details/gtrzooxlqd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmumjgpeb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cheryme.top/Article/details/gtstujzuou.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.chenzaomai.com/Article/details/gtjpnmnvxw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hysaishi.cn/Article/details/gtbpbiorjz.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtbrafvmft.html

J. 日期与时间
来源：http://dali.zycfv.cn/Article/details/gtvgxlbsya.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtbgegqipe.html

[J01] 获取当前时间
来源：http://dali.svipenyu.cn/Article/details/gtwqdckipa.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.dianchejie.cn/Article/details/gtfvdfeuzz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shzxlz.cn/Article/details/gttuqtxjjj.html

JS:   new Date();  Date.now()
来源：http://dali.xziqi.cn/Article/details/gtfkaeedvw.html

TS:   new Date();  Date.now()
来源：http://dali.pengpengdd.cyou/Article/details/gtewjrzgnn.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yj202588.top/Article/details/gtmjkuvglp.html

Go:   time.Now()
来源：http://dali.haohaochexian.top/Article/details/gtlhkrjysb.html

Ruby: Time.now
来源：http://dali.feifeiyinyue.top/Article/details/gttzasbfti.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nanxinkj.top/Article/details/gtclaxscsx.html

[J02] 格式化输出
来源：http://dali.jlsjyb.cn/Article/details/gtxgxwxzaa.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenzaomai.com/Article/details/gtcmfzdibh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cucudq.cn/Article/details/gtlqngzulh.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.meibo888.top/Article/details/gtfamlxrah.html

TS:   d.toISOString()
来源：http://dali.guannengcc.top/Article/details/gtrynexawq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.wangdashe.top/Article/details/gthccrlkoa.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.wangshuangyany.cn/Article/details/gtoetijioy.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhongyouzk.top/Article/details/gthemqwouk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cheryme.top/Article/details/gtuajxuhpw.html

[J03] 字符串解析为日期
来源：http://dali.guowangkeji.top/Article/details/gtuijcvmqs.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hongshengwenyu.top/Article/details/gtokfkttuy.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.redwolf501.top/Article/details/gttnuyfpqj.html

JS:   new Date("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gtmyksbwno.html

TS:   new Date("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gthxuxliga.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gtlaxpuwym.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtnjsrrhyx.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwnlisrjl.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.tian-w.cn/Article/details/gtzunzrqss.html

[J04] 时间戳与日期互转
来源：http://dali.zdqjudy.top/Article/details/gttziftxml.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.dashuyun.cn/Article/details/gtxduwhphi.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zdqjudy.top/Article/details/gtuppaqkhd.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yueranfly.top/Article/details/gtukjgfuxj.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yj202588.top/Article/details/gtjflwkbem.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.chenjidiqi.icu/Article/details/gtwuppgcxh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.bjfxy.top/Article/details/gtrfxcnyud.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.chenzaomai.com/Article/details/gtrqyzjfid.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yuanzhike.top/Article/details/gteyarewgz.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhijiandao.cn/Article/details/gtngmxwzlo.html

Py:   now + timedelta(days=7)
来源：http://dali.nanxuanxn.top/Article/details/gtqikbccoi.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.andypj.xyz/Article/details/gtfxktokke.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.snrcjt.cn/Article/details/gtgejpddgg.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.feifeiyinyue.top/Article/details/gtdrpkrsdj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.quarkkingdee.top/Article/details/gtuhptszxe.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xuetiantiany.cn/Article/details/gtfljkrcot.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yj20258.top/Article/details/gtksaspghi.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinqigufen.top/Article/details/gtbhyuhgsb.html

[J06] 计算两时间之差
来源：http://dali.shangyingyoupin.top/Article/details/gtmxsujbmv.html

Py:   (end - start).total_seconds()
来源：http://dali.hnqzz.top/Article/details/gtvbmgbrzu.html

PHP:  $end->diff($start)->days;
来源：http://dali.wangdashe.top/Article/details/gtjnbnmffv.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yuanzhike.top/Article/details/gtyovisghw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj20258888.top/Article/details/gtvcjfgbiu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yvedp.cn/Article/details/gtptrgqzoo.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhixingplan.top/Article/details/gtmqjmbrzy.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ydzc1.top/Article/details/gtvqrzynas.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinyuanbaomall.cn/Article/details/gthyudawld.html

[J07] 比较两个日期
来源：http://dali.jiagoushi.top/Article/details/gtbicvyeis.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhongyouzk.top/Article/details/gtermoqzyr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.wangshuangyany.cn/Article/details/gtkgvmshao.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gzhubu.top/Article/details/gtalsfloni.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yanxiufei.cn/Article/details/gtgkxeohkn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.chenzaomai.com/Article/details/gthvvagxnu.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sufxvd.cn/Article/details/gtinocxdwq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shzxlz.cn/Article/details/gtzrudfgot.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.c1oappe.top/Article/details/gtandyrash.html

[J08] 提取年月日与星期
来源：http://dali.quarkkingdee.top/Article/details/gtasnjxppr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jqgfzy.top/Article/details/gtxdurpuey.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zycfv.cn/Article/details/gtdzoywpet.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenjidiqi.icu/Article/details/gtzrgostjj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tanke756.top/Article/details/gtnoslqmnj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhengqikj.top/Article/details/gtjgpghqbm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jlsjyb.cn/Article/details/gtwsmdueuh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hywenlv.cn/Article/details/gtikzqmxay.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.chenjidiqi.icu/Article/details/gtmpdyxunc.html

[J09] 时区处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnbwaabcw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gaohongyu789.top/Article/details/gtuzkxvmaw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shanyushiyangtech.top/Article/details/gtyumxqlqt.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj202588.top/Article/details/gtzuitengw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ivvv.top/Article/details/gtyvvehdgt.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.daria6918.cn/Article/details/gtaglqqgao.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hfpthk.cn/Article/details/gthjdzzatc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hysaishi.cn/Article/details/gtdwvkcxqm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.dianchejie.cn/Article/details/gtgmlrezau.html

[J10] 取今天 / 本月第一天
来源：http://dali.zycfv.cn/Article/details/gtfwwahhtc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yanxiufei.cn/Article/details/gtpgocmcwk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yj20258.top/Article/details/gtdcratqud.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhijiandao.cn/Article/details/gtgfmbvyah.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hywenlv.cn/Article/details/gtksvtgghn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zdqjudy.top/Article/details/gtoovqecvc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zycfv.cn/Article/details/gtgijvkmff.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hywenlv.cn/Article/details/gtnfljsoej.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenlongwang.top/Article/details/gtvcxghqgl.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcxeicbbr.html

K. JSON 与序列化
来源：http://dali.snrcjt.cn/Article/details/gtxemwtcjo.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcicospxx.html

[K01] 对象转 JSON 字符串
来源：http://dali.yj20258888.top/Article/details/gtimnfvcey.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnzgcsmmx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.pycfn.com/Article/details/gtaobgrwsi.html

JS:   JSON.stringify(obj)
来源：http://dali.gogol.net.cn/Article/details/gtleuoxliy.html

TS:   JSON.stringify(obj)
来源：http://dali.9152youxi.cn/Article/details/gttksmharf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sxryk.cn/Article/details/gtjcgpxdwd.html

Go:   json.Marshal(obj)
来源：http://dali.xziqi.cn/Article/details/gtxwhxxftc.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ppjwa.cn/Article/details/gtuxhtlefw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.aizwys.cn/Article/details/gtqkzltlqv.html

[K02] JSON 字符串转对象
来源：http://dali.c1oappe.top/Article/details/gtstldbxev.html

Py:   json.loads(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtpzcpgdyv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhengqikj.top/Article/details/gttscmemii.html

JS:   JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gtqnavzuoa.html

TS:   JSON.parse(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gteftkjztp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.chenlongwang.top/Article/details/gthsknxkoz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.nanxinkj.top/Article/details/gtqflcgxqn.html

Ruby: JSON.parse(s)
来源：http://dali.zdqjudy.top/Article/details/gtehasylvn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.pycfn.com/Article/details/gtndqaeqsh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yanxiufei.cn/Article/details/gtojeukehu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xziqi.cn/Article/details/gtwehgfnic.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ivvv.top/Article/details/gtqtbtiutp.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cdnleiting.top/Article/details/gtonlycyrb.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zycfv.cn/Article/details/gtfeugpnln.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hysaishi.cn/Article/details/gtykzznmkf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.0kj1m.cn/Article/details/gtujvzptsp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmqvwjusl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ybcxt.top/Article/details/gtdrwjabte.html

[K04] 读取 JSON 文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwzmvmunu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yuanzhike.top/Article/details/gtzrxqxdvd.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.pengpengdd.cyou/Article/details/gtbkwhxyhb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shangyingyoupin.top/Article/details/gtuontjvxy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aizwys.cn/Article/details/gtfcevzpoa.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cucudq.cn/Article/details/gteytjzvji.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.pengpengdd.cyou/Article/details/gtatmfxitq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtzhpokjwp.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shzxlz.cn/Article/details/gtxwgzjfot.html

[K05] 深拷贝对象
来源：http://dali.haohaochexian.top/Article/details/gthhnwmrar.html

Py:   copy.deepcopy(obj)
来源：http://dali.smart0.xyz/Article/details/gtbtxuxhmd.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hnxiangtu.top/Article/details/gtgbidnlcw.html

JS:   structuredClone(obj)
来源：http://dali.iojbl.cn/Article/details/gtsqyascox.html

TS:   structuredClone(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtvvzwypqu.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinyuanbaomall.cn/Article/details/gtguxzcmbs.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.tian-w.cn/Article/details/gtzsvwglqs.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gtxmiosonr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.nwbrower.top/Article/details/gtiqwdoisf.html

[K06] 解析 URL 查询串
来源：http://dali.tianlin.xyz/Article/details/gtsidhqqil.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinqigfzy.top/Article/details/gtmtgqjxhj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jianghu66.top/Article/details/gtuvcicojr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xylfe.cn/Article/details/gthyiyfnmb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.kuanghao11.cn/Article/details/gtlwuxwuox.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.smart0.xyz/Article/details/gtlijkjxxu.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.tanke756.top/Article/details/gtwhpxvddj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gtzfrnzlck.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhixingplan.top/Article/details/gtklgbhrjb.html

[K07] 进制转换
来源：http://dali.birdmap.top/Article/details/gtdrpwhkvh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gtqrjfcxqq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hfpthk.cn/Article/details/gtddwgretb.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.tanke756.top/Article/details/gtotssfkvv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gtzxhhxliy.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yj20258.top/Article/details/gtwgonecsc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yongpay.top/Article/details/gtdmfvgxqd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zdqjudy.top/Article/details/gtqvzluugo.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpsznkwyr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.bjfxy.top/Article/details/gtzuvdzetd.html

Py:   pickle.dumps(obj)
来源：http://dali.jiagoushi.top/Article/details/gtacvnaoep.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hnqzz.top/Article/details/gtoclotjjg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.redwolf501.top/Article/details/gtxiiebald.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.9152youxi.cn/Article/details/gtakhddrtc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yanxiufei.cn/Article/details/gtobxgbqzy.html

Go:   encoding/gob
来源：http://dali.fengsongda.top/Article/details/gtppyfhudq.html

Ruby: Marshal.dump(obj)
来源：http://dali.aizwys.cn/Article/details/gtfysrognq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtihsvqyek.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtfoisdcgt.html

L. 网络请求
来源：http://dali.zhengqikj.top/Article/details/gtalorayxw.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtfbmqfmek.html

[L01] 发送 GET 请求
来源：http://dali.feifeiyinyue.top/Article/details/gtamvzhngl.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yonumen.top/Article/details/gtzaluasnu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.dashuyun.cn/Article/details/gtsybmoaev.html

JS:   await fetch(url)
来源：http://dali.nanxuanxn.top/Article/details/gtxyqvdgbi.html

TS:   await fetch(url)
来源：http://dali.xuanzx.com/Article/details/gtaerslyeb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinqigufen.top/Article/details/gtplsbsreu.html

Go:   resp, err := http.Get(url)
来源：http://dali.quarkkingdee.top/Article/details/gtkqnwmuff.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yueranfly.top/Article/details/gtrhpznlex.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yj202588.top/Article/details/gtjeomjxhm.html

[L02] 发送 POST JSON
来源：http://dali.kuanghao11.cn/Article/details/gtohczujst.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gogol.net.cn/Article/details/gtugjjfmyi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zdqjudy.top/Article/details/gtcvlmtqur.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sweek.top/Article/details/gtmaghagxh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj202588.top/Article/details/gtxvzutxso.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shanyushiyangtech.top/Article/details/gtuttgvznx.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xuetiantiany.cn/Article/details/gtekqtbtmv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.9152youxi.cn/Article/details/gtrhxawboh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ydzc1.top/Article/details/gththdgxnx.html

[L03] 设置自定义请求头
来源：http://dali.gogol.net.cn/Article/details/gtaylptqhs.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cashguo.top/Article/details/gtobxihcfi.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.birdmap.top/Article/details/gttgndqrle.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangshuangyany.cn/Article/details/gtsqlucgek.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cdnleiting.top/Article/details/gthxssgwmg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.316326.xyz/Article/details/gttqgydaen.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.9152youxi.cn/Article/details/gtrrxsewzt.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cdnleiting.top/Article/details/gtjgpfzagt.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjgikzzhw.html

[L04] 设置超时
来源：http://dali.bjfxy.top/Article/details/gtnvjvxsfe.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gogol.net.cn/Article/details/gtgwczssco.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shanyushiyangtech.top/Article/details/gteabsibqe.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtysrxqlra.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ydzc1.top/Article/details/gtjcgnsjlc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jlsjyb.cn/Article/details/gtyvonfuoh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrolagikx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.snrcjt.cn/Article/details/gthramjfka.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yj20258888.top/Article/details/gtmsxwssiv.html

[L05] 上传文件（multipart）
来源：http://dali.smart0.xyz/Article/details/gtcxexkdxv.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.9152youxi.cn/Article/details/gtxdvvqkmz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.aizwys.cn/Article/details/gtanmfvyqi.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.aibaodan.cn/Article/details/gthandwwij.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.dianchejie.cn/Article/details/gtxymdvpjp.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.dashuyun.cn/Article/details/gtgqcmbjsc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sufxvd.cn/Article/details/gtxlkfnsxw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yj20258.top/Article/details/gtqmjuxylp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtivkhwmnk.html

[L06] 解析响应为 JSON
来源：http://dali.xinyue.icu/Article/details/gtdnpfuncj.html

Py:   resp.json()
来源：http://dali.ybcxt.top/Article/details/gtovrjhdfy.html

PHP:  json_decode($body, true);
来源：http://dali.fengsongda.top/Article/details/gttwwpvavu.html

JS:   await resp.json()
来源：http://dali.smart0.xyz/Article/details/gtcihpqlpe.html

TS:   await resp.json()
来源：http://dali.dashuyun.cn/Article/details/gtitagtdko.html


<!-- 参考信息 -->