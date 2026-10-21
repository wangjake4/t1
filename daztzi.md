代发 wailian999

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.nanxinkj.top/Article/details/gtmsagsvrn.html

Go:   defer f.Close()
来源：http://dali.jqgfzy.top/Article/details/gtjamsxjdq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ivvv.top/Article/details/gtwbpzuqnq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtgxylsalf.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtfdqrmwid.html

I. 正则表达式
来源：http://dali.cqqwz.cn/Article/details/gtyuqdfzrc.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtkybuyeln.html

[I01] 判断是否匹配
来源：http://dali.bjfxy.top/Article/details/gtyzoigdie.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbzutyori.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.guowangkeji.top/Article/details/gtuygnukmr.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gtxyrvmubn.html

TS:   /\d+/.test(s)
来源：http://dali.mhx1999.top/Article/details/gtialvzkop.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hfpthk.cn/Article/details/gtctixvpfq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yuanzhike.top/Article/details/gtakzyllta.html

Ruby: s.match?(/\d+/)
来源：http://dali.gaohongyu789.top/Article/details/gtmkwrbvoa.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hnxiangtu.top/Article/details/gtztayfriy.html

[I02] 提取所有匹配
来源：http://dali.cashguo.top/Article/details/gtbtkculyb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xinyue.icu/Article/details/gtyfyfvqqu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.wangshuangyany.cn/Article/details/gtzsbodrfp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.wangshuangyany.cn/Article/details/gtwslhduid.html

TS:   s.match(/\d+/g)
来源：http://dali.jqgfzy.top/Article/details/gtcgukbmqz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzobkzsoj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.guowangkeji.top/Article/details/gtgxszquwo.html

Ruby: s.scan(/\d+/)
来源：http://dali.haohaochexian.top/Article/details/gtlawcfvsh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtkapsnwtl.html

[I03] 提取捕获分组
来源：http://dali.jyoumei.cn/Article/details/gtfwwrlajz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nanxuanxn.top/Article/details/gtkewfrlht.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cqqwz.cn/Article/details/gtsvqitajy.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhoulong.xyz/Article/details/gterpatlmo.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yueranfly.top/Article/details/gtprtaqwqt.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.quarkkingdee.top/Article/details/gtqrmlrpef.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tianlin.xyz/Article/details/gtnvuhxoeh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shzxlz.cn/Article/details/gtwlfivtuy.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhongyouzk.top/Article/details/gtzgiqpvfw.html

[I04] 正则替换
来源：http://dali.jqgfzy.top/Article/details/gtqvmkhplq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhoulong.xyz/Article/details/gtmfbycvnr.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gzhubu.top/Article/details/gtkfiqjfvu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhengqikj.top/Article/details/gtvrpvaqzx.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxqdvznpn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cheryme.top/Article/details/gtfworqsva.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sysykeji.top/Article/details/gtpwcsgrus.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cucudq.cn/Article/details/gtmnrswdjh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yuxming.cn/Article/details/gtzkmojzwf.html

[I05] 按正则拆分
来源：http://dali.yj202588.top/Article/details/gtlwhpoqwf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.fzhhl.top/Article/details/gtomxvqykf.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsclaypcz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hysaishi.cn/Article/details/gtzftuqbdt.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xuetiantiany.cn/Article/details/gtjunoyldn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xuetiantiany.cn/Article/details/gtiinwnhhs.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cucudq.cn/Article/details/gtclzcidzx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jiagoushi.top/Article/details/gtcknlxdpj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.vqdsnc.cn/Article/details/gtsqefufdg.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jqgufenzy.top/Article/details/gtybppfvmt.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hysaishi.cn/Article/details/gtgegfgevt.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.0kj1m.cn/Article/details/gtqqaeqxzw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.kuanghao11.cn/Article/details/gtivjcijsd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zdqjudy.top/Article/details/gtcqvoapkb.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinghuilouyu.cn/Article/details/gtzjxjjuco.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hysaishi.cn/Article/details/gtlzetvbvx.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.0kj1m.cn/Article/details/gtelcqnncc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.tanke756.top/Article/details/gtmdppqqng.html

[I07] 忽略大小写与多行模式
来源：http://dali.hnqzz.top/Article/details/gtsndgnjpa.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.9152youxi.cn/Article/details/gtsoszxohf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gogol.net.cn/Article/details/gtrulgmjoz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sxryk.cn/Article/details/gtktffvpap.html

TS:   /error/gim
来源：http://dali.yanxiufei.cn/Article/details/gtbknseciz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hnxiangtu.top/Article/details/gtpcmoprau.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.guannengcc.top/Article/details/gtijvriphu.html

Ruby: s.scan(/error/i)
来源：http://dali.316326.xyz/Article/details/gtxijfxslh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyuiosiyj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shuidangran.top/Article/details/gtvapezhay.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zdqjudy.top/Article/details/gtwsdattfh.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzifwrxxh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fengsongda.top/Article/details/gtdpedxiqm.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfgsssgrf.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.kuanghao11.cn/Article/details/gtlfgemyew.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.smart0.xyz/Article/details/gtgldmkozk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sweek.top/Article/details/gtsyfzxlrn.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hongshengwenyu.top/Article/details/gtnrpvppda.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtupauzxuv.html

J. 日期与时间
来源：http://dali.vqdsnc.cn/Article/details/gtghklljyh.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtcwitwpgj.html

[J01] 获取当前时间
来源：http://dali.jinqigufen.top/Article/details/gtbyqdnmlu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.daria6918.cn/Article/details/gtcpjqmxtz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yanxiufei.cn/Article/details/gtfrtsupva.html

JS:   new Date();  Date.now()
来源：http://dali.zhoulong.xyz/Article/details/gtabkhqcpb.html

TS:   new Date();  Date.now()
来源：http://dali.chenjidiqi.icu/Article/details/gtlqhzxcsy.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shuidangran.top/Article/details/gttnxyqnkt.html

Go:   time.Now()
来源：http://dali.zhixingplan.top/Article/details/gtzjdkpfel.html

Ruby: Time.now
来源：http://dali.ehwqpu.com/Article/details/gteadvbmpu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shzxlz.cn/Article/details/gtxxorhnsf.html

[J02] 格式化输出
来源：http://dali.hywenlv.cn/Article/details/gtbjneupen.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnqzz.top/Article/details/gtrikhttun.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.0kj1m.cn/Article/details/gtuooafejy.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.nwbrower.top/Article/details/gtrrmuooex.html

TS:   d.toISOString()
来源：http://dali.kuanghao11.cn/Article/details/gtcajcevyo.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.wangshuangyany.cn/Article/details/gtjixyauji.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.svipenyu.cn/Article/details/gtihxmeuub.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvdezfldi.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shzxlz.cn/Article/details/gthlzibeug.html

[J03] 字符串解析为日期
来源：http://dali.zycfv.cn/Article/details/gtoqfmkuhu.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.tian-w.cn/Article/details/gtccpwnsbe.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.316326.xyz/Article/details/gttgxlwdms.html

JS:   new Date("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gttqabywiu.html

TS:   new Date("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gtkdhtrgkz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtzanvmpsa.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtxilrhudk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gtnsmvqyal.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yvedp.cn/Article/details/gtwjvrgjcz.html

[J04] 时间戳与日期互转
来源：http://dali.xuetiantiany.cn/Article/details/gtmmuelmqh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.feifeiyinyue.top/Article/details/gtnfhtcmvt.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jyoumei.cn/Article/details/gtthkaltpy.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.9152youxi.cn/Article/details/gtnsmvujnn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yj20258888.top/Article/details/gtdrciaykp.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xinyue.icu/Article/details/gtksyhqxgc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinqigufen.top/Article/details/gtqynjezus.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shangyingyoupin.top/Article/details/gtwywsavuz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hnqzz.top/Article/details/gtjyxhfrvu.html

[J05] 时间加减（加 7 天）
来源：http://dali.daria6918.cn/Article/details/gtdimkgsks.html

Py:   now + timedelta(days=7)
来源：http://dali.yuxming.cn/Article/details/gtriecdgqs.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.chenjidiqi.icu/Article/details/gtvaemwknn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yonumen.top/Article/details/gtineeqzms.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xinyue.icu/Article/details/gtmwsbrrlj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hysaishi.cn/Article/details/gtwdcayytb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yangfankeji.com/Article/details/gtixmzhtit.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xuetiantiany.cn/Article/details/gtxedykfal.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ybcxt.top/Article/details/gttcyirgpa.html

[J06] 计算两时间之差
来源：http://dali.guowangkeji.top/Article/details/gthmulsymj.html

Py:   (end - start).total_seconds()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpplgbrbb.html

PHP:  $end->diff($start)->days;
来源：http://dali.zycfv.cn/Article/details/gtxdsifhun.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zdqjudy.top/Article/details/gtagkqchsd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yanxiufei.cn/Article/details/gtfhxpesrb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sysykeji.top/Article/details/gtxsiqrwff.html

Go:   end.Sub(start).Hours()
来源：http://dali.0kj1m.cn/Article/details/gthfgotzyv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cdnleiting.top/Article/details/gtphiqejve.html

C#:   (end - start).TotalSeconds
来源：http://dali.cucudq.cn/Article/details/gtuiscbcnb.html

[J07] 比较两个日期
来源：http://dali.xuetiantiany.cn/Article/details/gtnvkgoqen.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gtohrxkciq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yj20258888.top/Article/details/gtohbdsnpe.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jyoumei.cn/Article/details/gtiluiakpn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.wangshuangyany.cn/Article/details/gtoaojtfrp.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ydzc1.top/Article/details/gtpobofaav.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhongyouzk.top/Article/details/gtwprgjyqc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.meibo888.top/Article/details/gtiyfjwcvw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jqgfzy.top/Article/details/gtdkwbxkjs.html

[J08] 提取年月日与星期
来源：http://dali.chenjidiqi.icu/Article/details/gtjouilful.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yanxiufei.cn/Article/details/gtzwnqfexi.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jiagoushi.top/Article/details/gtonxpmmnj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.guowangkeji.top/Article/details/gttgimtivh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gaohongyu789.top/Article/details/gtnnsvtbbg.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.aizwys.cn/Article/details/gtjgpvtjlu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.chenlongwang.top/Article/details/gtiijkkxvo.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.feifeiyinyue.top/Article/details/gtqkogzfvj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sweek.top/Article/details/gtfziprlfp.html

[J09] 时区处理
来源：http://dali.316326.xyz/Article/details/gtbtdpozly.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xylfe.cn/Article/details/gtfkeiford.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinqigfzy.top/Article/details/gtvhoeiqtu.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.haohaochexian.top/Article/details/gtdodlvpcz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtinhmcyar.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ybcxt.top/Article/details/gtncmbzopi.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinghuilouyu.cn/Article/details/gtoxwwunyl.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.snrcjt.cn/Article/details/gtrzbilkee.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.andypj.xyz/Article/details/gtuktaflpd.html

[J10] 取今天 / 本月第一天
来源：http://dali.hysaishi.cn/Article/details/gtdlkahsfb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shzxlz.cn/Article/details/gtiofabtmd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sxryk.cn/Article/details/gtmlktrbtr.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtdwdcmpfj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sxryk.cn/Article/details/gtcbnzdedr.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.meibo888.top/Article/details/gtczoxaqsh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.meibo888.top/Article/details/gtdskyysjh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jiagoushi.top/Article/details/gtjeiuoiyu.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sufxvd.cn/Article/details/gtdylmmamb.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtmlpesspu.html

K. JSON 与序列化
来源：http://dali.chenzaomai.com/Article/details/gtjwknbzum.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtmcuzvoip.html

[K01] 对象转 JSON 字符串
来源：http://dali.haohaochexian.top/Article/details/gtcnrofnuq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yanxiufei.cn/Article/details/gtngkksahx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.sweek.top/Article/details/gtohkiaokx.html

JS:   JSON.stringify(obj)
来源：http://dali.daria6918.cn/Article/details/gtmdskncfi.html

TS:   JSON.stringify(obj)
来源：http://dali.cheryme.top/Article/details/gthqhjegdz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.0kj1m.cn/Article/details/gtbhvrkozj.html

Go:   json.Marshal(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtnwymsqyp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ydzc1.top/Article/details/gtqbdqmdxd.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xylfe.cn/Article/details/gtzxpcqwwz.html

[K02] JSON 字符串转对象
来源：http://dali.ppjwa.cn/Article/details/gtdeqdnqls.html

Py:   json.loads(s)
来源：http://dali.jqgfzy.top/Article/details/gtdinrtofm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hywenlv.cn/Article/details/gtlsgbdbmd.html

JS:   JSON.parse(s)
来源：http://dali.sxryk.cn/Article/details/gtjqcniawb.html

TS:   JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtmgkilxnn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zycfv.cn/Article/details/gtzgdmgpny.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.tian-w.cn/Article/details/gtwigpqjpd.html

Ruby: JSON.parse(s)
来源：http://dali.mhx1999.top/Article/details/gtzcjuktom.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jianghu66.top/Article/details/gtgtbazugb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.nwbrower.top/Article/details/gtvwhdhmco.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.fzhhl.top/Article/details/gtxajiwfmz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigfzy.top/Article/details/gtwpxcckvr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenlongwang.top/Article/details/gtejodjuvd.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gteyfabslu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yuanzhike.top/Article/details/gtuxegkegy.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xuanzx.com/Article/details/gtnplnfwso.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.wangdashe.top/Article/details/gtgcpoiprj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jqgfzy.top/Article/details/gtdmolarsf.html

[K04] 读取 JSON 文件
来源：http://dali.chenlongwang.top/Article/details/gtermsybsl.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yangfankeji.com/Article/details/gtdxixwvmv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.pengpengdd.cyou/Article/details/gtgofyetzy.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.316326.xyz/Article/details/gtclspsajc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daria6918.cn/Article/details/gtbubfghal.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nanxinkj.top/Article/details/gtqmxldsxa.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xinyue.icu/Article/details/gtumqfaglm.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yongpay.top/Article/details/gtmrjrzszq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sxryk.cn/Article/details/gtwohfpfio.html

[K05] 深拷贝对象
来源：http://dali.nanxinkj.top/Article/details/gtmpvuhwvy.html

Py:   copy.deepcopy(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtbxaszuyg.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yonumen.top/Article/details/gtswmitlej.html

JS:   structuredClone(obj)
来源：http://dali.gzhubu.top/Article/details/gtlvtltpyx.html

TS:   structuredClone(obj)
来源：http://dali.chenzaomai.com/Article/details/gtzcgufohw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinqigufen.top/Article/details/gtzfscilva.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhiwuduotai.top/Article/details/gtdzfoahma.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yvedp.cn/Article/details/gtpoltfquo.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zdqjudy.top/Article/details/gttqiijhxd.html

[K06] 解析 URL 查询串
来源：http://dali.zhoulong.xyz/Article/details/gtbmigackp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhiwuduotai.top/Article/details/gttgrrnwyn.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.9152youxi.cn/Article/details/gtclgtdunm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yueranfly.top/Article/details/gtkadyfhse.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tianlin.xyz/Article/details/gtgdtitpvt.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gogol.net.cn/Article/details/gtklhdjebr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jiagoushi.top/Article/details/gtcceplwdp.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sufxvd.cn/Article/details/gtzmivfguh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gtkzwsajay.html

[K07] 进制转换
来源：http://dali.dashuyun.cn/Article/details/gttaysqazm.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gtzytbppuq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.tian-w.cn/Article/details/gtsrrjertj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gtjxpqwisl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtchbvzaig.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.sweek.top/Article/details/gtrvhrcrmz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.feifeiyinyue.top/Article/details/gtihyaxgtl.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.nanxuanxn.top/Article/details/gtiwdgbrlq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtocqqjjuu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtctdsjlfo.html

Py:   pickle.dumps(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkrwfvacv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.redwolf501.top/Article/details/gtttxelkkw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.feifeiyinyue.top/Article/details/gtknpnxeia.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sweek.top/Article/details/gtihegsudd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yanxiufei.cn/Article/details/gtehfhnmhi.html

Go:   encoding/gob
来源：http://dali.jlsjyb.cn/Article/details/gtlgvyvwyd.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gttewqkmsd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jinqigfzy.top/Article/details/gtaqaqcnrh.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtdnbaowok.html

L. 网络请求
来源：http://dali.zdqjudy.top/Article/details/gtfqhslbld.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gteatmlvte.html

[L01] 发送 GET 请求
来源：http://dali.ppjwa.cn/Article/details/gtxrgeyiea.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xziqi.cn/Article/details/gtnmbonpvw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxvvnfspo.html

JS:   await fetch(url)
来源：http://dali.jinqigfzy.top/Article/details/gtbwuavosh.html

TS:   await fetch(url)
来源：http://dali.shuidangran.top/Article/details/gtighyiqxp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zycfv.cn/Article/details/gtlddsorpq.html

Go:   resp, err := http.Get(url)
来源：http://dali.iojbl.cn/Article/details/gtxcbnkexh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvbahsgue.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yvedp.cn/Article/details/gttyqyvsin.html

[L02] 发送 POST JSON
来源：http://dali.ppjwa.cn/Article/details/gtbflrmfsb.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.bjfxy.top/Article/details/gtumfyhyjt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jqgfzy.top/Article/details/gtnzjtqzxl.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sysykeji.top/Article/details/gtnhfebnxb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuetiantiany.cn/Article/details/gtuwhxrcul.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hfpthk.cn/Article/details/gtieakuiid.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gogol.net.cn/Article/details/gtsilpbjea.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.chenlongwang.top/Article/details/gtpcnamwge.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yueranfly.top/Article/details/gtwvhumhww.html

[L03] 设置自定义请求头
来源：http://dali.jyoumei.cn/Article/details/gtybmytzdx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ehwqpu.com/Article/details/gtroadmoao.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.vqdsnc.cn/Article/details/gtglswilup.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cucudq.cn/Article/details/gtxbsaumcs.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hammf.cn/Article/details/gtnvrnwvif.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ivvv.top/Article/details/gtgzrbubwd.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.pengpengdd.cyou/Article/details/gtotmgxtal.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.tanke756.top/Article/details/gtpdampijh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hysaishi.cn/Article/details/gtjcyqmixp.html

[L04] 设置超时
来源：http://dali.sweek.top/Article/details/gtatyssszc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.mhx1999.top/Article/details/gtlxxtyimf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gaohongyu789.top/Article/details/gtlliyndkf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sxryk.cn/Article/details/gtametbsax.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnxiangtu.top/Article/details/gtjrrxhddx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.chenlongwang.top/Article/details/gtfzinqrbq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hongshengwenyu.top/Article/details/gtctqvcpbe.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.bjfxy.top/Article/details/gtoyugfpwg.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.guowangkeji.top/Article/details/gtwhoaxsqn.html

[L05] 上传文件（multipart）
来源：http://dali.gotoacloud.top/Article/details/gtzjljwuqb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yuanzhike.top/Article/details/gtcqglxcir.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hongshengwenyu.top/Article/details/gtbpxahgwp.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sysykeji.top/Article/details/gtzhmzqter.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.quarkkingdee.top/Article/details/gtwauzggjg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yj20258888.top/Article/details/gtdhlabgfb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hammf.cn/Article/details/gtoxuywprc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.meibo888.top/Article/details/gtovpepmof.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtixqeonue.html

[L06] 解析响应为 JSON
来源：http://dali.jlsjyb.cn/Article/details/gtgjeinlrw.html

Py:   resp.json()
来源：http://dali.zhixingplan.top/Article/details/gtwpzcnvim.html

PHP:  json_decode($body, true);
来源：http://dali.nwbrower.top/Article/details/gtslszdeqr.html

JS:   await resp.json()
来源：http://dali.kuanghao11.cn/Article/details/gtuayvoqvy.html

TS:   await resp.json()
来源：http://dali.pengpengdd.cyou/Article/details/gtpnudgqdm.html


<!-- 参考信息 -->