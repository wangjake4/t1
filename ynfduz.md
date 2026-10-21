代发 wailian999

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.daxiang520.top/Article/details/gtqidcsyjs.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zdqjudy.top/Article/details/gttdqysgag.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkjsqvweq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.daria6918.cn/Article/details/gtcffvquvy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hysaishi.cn/Article/details/gtkppkpixt.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hammf.cn/Article/details/gtnvddmrzf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhixingplan.top/Article/details/gtcuaekxxq.html

[H10] 资源自动释放
来源：http://dali.zycfv.cn/Article/details/gtgispuvmy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gtdekcryms.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.0kj1m.cn/Article/details/gtwxhxhxbe.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgufenzy.top/Article/details/gtdnnqnyjb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnxiangtu.top/Article/details/gtubtpudzb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.havefunace.top/Article/details/gtptaqgdnp.html

Go:   defer f.Close()
来源：http://dali.jinghuilouyu.cn/Article/details/gtvhpzlxfx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.birdmap.top/Article/details/gtfwmqzaia.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtiijburiv.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtrmfyhbtm.html

I. 正则表达式
来源：http://dali.c1oappe.top/Article/details/gtmzeoawog.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtqpgdmlqi.html

[I01] 判断是否匹配
来源：http://dali.dianchejie.cn/Article/details/gtpxaolwnd.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gotoacloud.top/Article/details/gtwgfbxcgg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtbvtccinp.html

JS:   /\d+/.test(s)
来源：http://dali.zhengqikj.top/Article/details/gtaxiskyiu.html

TS:   /\d+/.test(s)
来源：http://dali.andypj.xyz/Article/details/gtgjvdawru.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zycfv.cn/Article/details/gtpctazrue.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.mhx1999.top/Article/details/gtdvyiuxng.html

Ruby: s.match?(/\d+/)
来源：http://dali.yj20258888.top/Article/details/gtgypukuca.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xuanzx.com/Article/details/gtiwjdmpvy.html

[I02] 提取所有匹配
来源：http://dali.svipenyu.cn/Article/details/gtwoktokfe.html

Py:   re.findall(r"\d+", s)
来源：http://dali.guannengcc.top/Article/details/gtvkelammc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jiagoushi.top/Article/details/gtkjucyvtm.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cheryme.top/Article/details/gttpwkfarb.html

TS:   s.match(/\d+/g)
来源：http://dali.jlsjyb.cn/Article/details/gtngrkluav.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.0kj1m.cn/Article/details/gtnckqepgd.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hfpthk.cn/Article/details/gtoduxorxg.html

Ruby: s.scan(/\d+/)
来源：http://dali.gotoacloud.top/Article/details/gtsgzrrgpp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.tanke756.top/Article/details/gtgzohfucu.html

[I03] 提取捕获分组
来源：http://dali.ybcxt.top/Article/details/gtfcebvlja.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hysaishi.cn/Article/details/gtzglnjhot.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cucudq.cn/Article/details/gtcqysodvd.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhoulong.xyz/Article/details/gtpoajaztc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xuetiantiany.cn/Article/details/gtpzobafdw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sysykeji.top/Article/details/gtsksupayc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shzxlz.cn/Article/details/gtsngmrkkl.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.havefunace.top/Article/details/gtaqvtmkqg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.fengsongda.top/Article/details/gteohswqed.html

[I04] 正则替换
来源：http://dali.bjfxy.top/Article/details/gtibbmgfhs.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gthqhyjpvw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.wangdashe.top/Article/details/gtqzzaybnz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxinkj.top/Article/details/gtzygcehah.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxinkj.top/Article/details/gtzhitrovj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hysaishi.cn/Article/details/gtpvjvxfpw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yj20258888.top/Article/details/gtfrsmyydc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.havefunace.top/Article/details/gtvpyjicrp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.kuanghao11.cn/Article/details/gtwtcepdgr.html

[I05] 按正则拆分
来源：http://dali.jiagoushi.top/Article/details/gthlbfpldq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.haohaochexian.top/Article/details/gthqlesmtz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.tianlin.xyz/Article/details/gtzzwlcwcl.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yj202588.top/Article/details/gttturient.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ybcxt.top/Article/details/gtvbpyqpnx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.mhx1999.top/Article/details/gtykgzneyv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.iojbl.cn/Article/details/gtccxogytf.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.havefunace.top/Article/details/gtxlvjvpsy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjjfsipdh.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.tanke756.top/Article/details/gtlvwgbdpl.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yonumen.top/Article/details/gtspokuoys.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ydzc1.top/Article/details/gtgkhvihkj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.smart0.xyz/Article/details/gtmnemswwr.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.kuanghao11.cn/Article/details/gthspzgdpt.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhoulong.xyz/Article/details/gtdevwlnxm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.guowangkeji.top/Article/details/gtvqjjqveu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.316326.xyz/Article/details/gtdheurdii.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gtaxbluayn.html

[I07] 忽略大小写与多行模式
来源：http://dali.ydzc1.top/Article/details/gtvdrcbkrx.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shanyushiyangtech.top/Article/details/gtggpyfqar.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hammf.cn/Article/details/gtvxihecwp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinqigfzy.top/Article/details/gtdnvvokko.html

TS:   /error/gim
来源：http://dali.snrcjt.cn/Article/details/gtbxtltxhc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.iojbl.cn/Article/details/gtbdsybdwk.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yvedp.cn/Article/details/gtqqsxxvlj.html

Ruby: s.scan(/error/i)
来源：http://dali.smart0.xyz/Article/details/gtufvrfuwr.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shanyushiyangtech.top/Article/details/gtphxygugz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.vqdsnc.cn/Article/details/gtarzudeiu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jlsjyb.cn/Article/details/gtmnegilzd.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.haohaochexian.top/Article/details/gtkfylmmit.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dianchejie.cn/Article/details/gtytddbxuk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yonumen.top/Article/details/gtzdzjlzwg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.iojbl.cn/Article/details/gttayxxvmz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xylfe.cn/Article/details/gtfbhhcxge.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.aibaodan.cn/Article/details/gtilybdwhm.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xziqi.cn/Article/details/gtvnjvysxa.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gteefipvvx.html

J. 日期与时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvijlxhhw.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtvvfzwthr.html

[J01] 获取当前时间
来源：http://dali.guowangkeji.top/Article/details/gtimzcrvee.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhijiandao.cn/Article/details/gtcnjhrywr.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yangfankeji.com/Article/details/gtvixxgdbj.html

JS:   new Date();  Date.now()
来源：http://dali.hammf.cn/Article/details/gtrdvpljtv.html

TS:   new Date();  Date.now()
来源：http://dali.yj20258888.top/Article/details/gtukksxkdl.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhengqikj.top/Article/details/gtbkoinnno.html

Go:   time.Now()
来源：http://dali.cheryme.top/Article/details/gtdvrxakre.html

Ruby: Time.now
来源：http://dali.fzhhl.top/Article/details/gtizqldkgf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sufxvd.cn/Article/details/gtzqejpfbk.html

[J02] 格式化输出
来源：http://dali.haohaochexian.top/Article/details/gtbazrsxva.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cucudq.cn/Article/details/gtaxsfhday.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jyoumei.cn/Article/details/gtcoktmqcp.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xziqi.cn/Article/details/gtmerticih.html

TS:   d.toISOString()
来源：http://dali.wangshuangyany.cn/Article/details/gtfbhhuxvs.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhongyouzk.top/Article/details/gtoixjtkle.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cashguo.top/Article/details/gtdaxfgpkk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yvedp.cn/Article/details/gtlzjwxfve.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sxryk.cn/Article/details/gtodwrmdlq.html

[J03] 字符串解析为日期
来源：http://dali.pengpengdd.cyou/Article/details/gtwvbyouwj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yanxiufei.cn/Article/details/gtohdbtsxj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gogol.net.cn/Article/details/gtropwpabf.html

JS:   new Date("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gtwblwqprs.html

TS:   new Date("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gtywktmumw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gtvrfdkisn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.birdmap.top/Article/details/gtlrkhbljf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtyqrddlwq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sxryk.cn/Article/details/gtxchqkjbe.html

[J04] 时间戳与日期互转
来源：http://dali.pycfn.com/Article/details/gtvnpwpmjq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ydzc1.top/Article/details/gtmtgteuda.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.chenlongwang.top/Article/details/gtnnapnqaz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.mhx1999.top/Article/details/gtekmjsuol.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hongshengwenyu.top/Article/details/gtexspwqcc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.chenzaomai.com/Article/details/gtrjnxxzeu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ivvv.top/Article/details/gtxqpjujvr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sxryk.cn/Article/details/gtyauiuspx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuohetkzx.html

[J05] 时间加减（加 7 天）
来源：http://dali.hfpthk.cn/Article/details/gtxxrewwnw.html

Py:   now + timedelta(days=7)
来源：http://dali.jqgfzy.top/Article/details/gtslyttbex.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.bjfxy.top/Article/details/gtjubqodzp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.snrcjt.cn/Article/details/gtssrfojxx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtruqgwoer.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.0kj1m.cn/Article/details/gtwrcqwgzg.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.daxiang520.top/Article/details/gtgejxwuxl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yanxiufei.cn/Article/details/gtiubjjhgn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.quarkkingdee.top/Article/details/gtnpcixkre.html

[J06] 计算两时间之差
来源：http://dali.yj202588.top/Article/details/gtuzrnucjm.html

Py:   (end - start).total_seconds()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtavzvgwyw.html

PHP:  $end->diff($start)->days;
来源：http://dali.guowangkeji.top/Article/details/gtaauhbcro.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.iojbl.cn/Article/details/gtchunvxvq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shuidangran.top/Article/details/gtdpiwpaga.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ehwqpu.com/Article/details/gtnmrkhhic.html

Go:   end.Sub(start).Hours()
来源：http://dali.yangfankeji.com/Article/details/gtwdkejofz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xinyue.icu/Article/details/gtpphwqbbg.html

C#:   (end - start).TotalSeconds
来源：http://dali.yuanzhike.top/Article/details/gtyeompyjb.html

[J07] 比较两个日期
来源：http://dali.xuanzx.com/Article/details/gtjursvdbn.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zdqjudy.top/Article/details/gthofrmuyx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jqgfzy.top/Article/details/gteofxjlny.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.feifeiyinyue.top/Article/details/gtxqnxqcur.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.dianchejie.cn/Article/details/gtrldtkrzv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.andypj.xyz/Article/details/gtokzdebdg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zdqjudy.top/Article/details/gtmwwoqwih.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jinqigfzy.top/Article/details/gtoglckwwt.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xylfe.cn/Article/details/gtaayifhhf.html

[J08] 提取年月日与星期
来源：http://dali.cashguo.top/Article/details/gtgfxqrkpc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.redwolf501.top/Article/details/gtasgxedfu.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.quarkkingdee.top/Article/details/gtdbfzwyci.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cashguo.top/Article/details/gtizkktfwk.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gotoacloud.top/Article/details/gtqnugdrte.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhongyouzk.top/Article/details/gtgtfnweet.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.guowangkeji.top/Article/details/gtvodcssqq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.quarkkingdee.top/Article/details/gtyuqiecjw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.c1oappe.top/Article/details/gtdlxqxlqv.html

[J09] 时区处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbwaiyxvz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xinyue.icu/Article/details/gtrqqamted.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.haohaochexian.top/Article/details/gtcjyoknzb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hysaishi.cn/Article/details/gtaelxwkwk.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yvedp.cn/Article/details/gtojjjbjkl.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.andypj.xyz/Article/details/gtmvyhrodg.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tanke756.top/Article/details/gtxiztdlwy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.c1oappe.top/Article/details/gtqzypoldn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.daria6918.cn/Article/details/gttqnutqng.html

[J10] 取今天 / 本月第一天
来源：http://dali.fengsongda.top/Article/details/gtrdcddoyv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhengqikj.top/Article/details/gtsmuinlit.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ydzc1.top/Article/details/gtbyggkqqk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.tian-w.cn/Article/details/gtmieayzmk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hnqzz.top/Article/details/gtagihditk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.wangdashe.top/Article/details/gtepucoepb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.wangshuangyany.cn/Article/details/gttnvfjrvb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yuanzhike.top/Article/details/gtwpxettpw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhijiandao.cn/Article/details/gtxmskurmv.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtbwdpvvhe.html

K. JSON 与序列化
来源：http://dali.nanxuanxn.top/Article/details/gtwybmomve.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtayyfdwmx.html

[K01] 对象转 JSON 字符串
来源：http://dali.hnqzz.top/Article/details/gtbncsqtxz.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ybcxt.top/Article/details/gtrkyyrttb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.chenlongwang.top/Article/details/gtggvbaqbr.html

JS:   JSON.stringify(obj)
来源：http://dali.sysykeji.top/Article/details/gthezeosac.html

TS:   JSON.stringify(obj)
来源：http://dali.yonumen.top/Article/details/gtbqhmbanb.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ppjwa.cn/Article/details/gtftkksffa.html

Go:   json.Marshal(obj)
来源：http://dali.fzhhl.top/Article/details/gtsxlkqnps.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sysykeji.top/Article/details/gtztjxdiwx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xuanzx.com/Article/details/gthuzfntad.html

[K02] JSON 字符串转对象
来源：http://dali.yvedp.cn/Article/details/gtfunmyqni.html

Py:   json.loads(s)
来源：http://dali.birdmap.top/Article/details/gtazaaisnf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.pycfn.com/Article/details/gtmycurceu.html

JS:   JSON.parse(s)
来源：http://dali.jlsjyb.cn/Article/details/gtjivbfcnt.html

TS:   JSON.parse(s)
来源：http://dali.dianchejie.cn/Article/details/gtsujqebzr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.bjfxy.top/Article/details/gtcckwgraj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ybcxt.top/Article/details/gtripdngyx.html

Ruby: JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gtjkxazhkw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.guannengcc.top/Article/details/gtydlzmlwb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.haohaochexian.top/Article/details/gtkgzxuodp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cheryme.top/Article/details/gtydejdfns.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxinkj.top/Article/details/gtpryecjca.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuxming.cn/Article/details/gtqifdckgy.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtimefwvmg.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yueranfly.top/Article/details/gtqgyrsptr.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpovtxiqk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.316326.xyz/Article/details/gtyglncfnx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cheryme.top/Article/details/gtthqkkyif.html

[K04] 读取 JSON 文件
来源：http://dali.jyoumei.cn/Article/details/gtczjfhhoh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.wangdashe.top/Article/details/gtdkyqpdgv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.dashuyun.cn/Article/details/gtjccafjrc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tanke756.top/Article/details/gtiysyxovh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiecydrjf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gogol.net.cn/Article/details/gtvomkdstp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtulxrsgxb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.dianchejie.cn/Article/details/gtrozwbigp.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.chenlongwang.top/Article/details/gtkkhcljkm.html

[K05] 深拷贝对象
来源：http://dali.hammf.cn/Article/details/gtqzweyxji.html

Py:   copy.deepcopy(obj)
来源：http://dali.0kj1m.cn/Article/details/gtqultsxte.html

PHP:  unserialize(serialize($obj));
来源：http://dali.dianchejie.cn/Article/details/gtbrutqiul.html

JS:   structuredClone(obj)
来源：http://dali.smart0.xyz/Article/details/gtqghbmnmd.html

TS:   structuredClone(obj)
来源：http://dali.mhx1999.top/Article/details/gtdfeihcvs.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ydzc1.top/Article/details/gtppkukady.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hfpthk.cn/Article/details/gtzpxxyxxe.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.shuidangran.top/Article/details/gtjmpzevsz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.nanxinkj.top/Article/details/gtkpiggorx.html

[K06] 解析 URL 查询串
来源：http://dali.yj20258888.top/Article/details/gthawaaifl.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhiwuduotai.top/Article/details/gtwtqsxclh.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.snrcjt.cn/Article/details/gtkossxfdr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zycfv.cn/Article/details/gtdftptqel.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zycfv.cn/Article/details/gtgcbyfcfs.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.daxiang520.top/Article/details/gtkithshlh.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gtkhqoswnc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.nanxuanxn.top/Article/details/gtjnwzmwoh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gtsjehgkha.html

[K07] 进制转换
来源：http://dali.xylfe.cn/Article/details/gtqzpqvndy.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gtzlezwxtx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.pengpengdd.cyou/Article/details/gtwzjzsqne.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gtnoemaszi.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gtgxhffzal.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gtofkvkezb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.andypj.xyz/Article/details/gtclaotsls.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.fzhhl.top/Article/details/gtqvpjogpx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gtlrsimuhe.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cashguo.top/Article/details/gtbqufhffn.html

Py:   pickle.dumps(obj)
来源：http://dali.svipenyu.cn/Article/details/gttkicxkse.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sysykeji.top/Article/details/gtfonbyznc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ehwqpu.com/Article/details/gtbylznxdw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xinyue.icu/Article/details/gtvcejorsn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinyuanbaomall.cn/Article/details/gthnjducdq.html

Go:   encoding/gob
来源：http://dali.xziqi.cn/Article/details/gtopanolki.html

Ruby: Marshal.dump(obj)
来源：http://dali.shuidangran.top/Article/details/gtcmsuqilf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.quarkkingdee.top/Article/details/gttxkiqjjb.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtyumzmytl.html

L. 网络请求
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjdqbfawq.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtseyyntoh.html

[L01] 发送 GET 请求
来源：http://dali.aizwys.cn/Article/details/gtbgzvtuyf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.pengpengdd.cyou/Article/details/gtdipwqmsa.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hammf.cn/Article/details/gtagzdmzng.html

JS:   await fetch(url)
来源：http://dali.tanke756.top/Article/details/gtbtejgvxs.html

TS:   await fetch(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtukupccme.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhoulong.xyz/Article/details/gtesbiedpg.html

Go:   resp, err := http.Get(url)
来源：http://dali.cqqwz.cn/Article/details/gtkuuagydo.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.guannengcc.top/Article/details/gtiysimlvl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.tianlin.xyz/Article/details/gtojemicid.html

[L02] 发送 POST JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gttfxzldqn.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.bjfxy.top/Article/details/gthlycirel.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.quarkkingdee.top/Article/details/gtuzsyaggn.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.quarkkingdee.top/Article/details/gtpkiqkiya.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgfzy.top/Article/details/gtpivgvkpc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cdnleiting.top/Article/details/gtobfsopun.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.dashuyun.cn/Article/details/gtwowzqmqj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xziqi.cn/Article/details/gttfbjcnvi.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shangyingyoupin.top/Article/details/gtiyvssyzm.html

[L03] 设置自定义请求头
来源：http://dali.yvedp.cn/Article/details/gthmvrozgj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hammf.cn/Article/details/gtngdybymx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenjidiqi.icu/Article/details/gtkmcnjhap.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yanxiufei.cn/Article/details/gtiwbrmqlu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sufxvd.cn/Article/details/gtqwadbexi.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.quarkkingdee.top/Article/details/gtdhthkbck.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ehwqpu.com/Article/details/gtsislqlsp.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.dashuyun.cn/Article/details/gtxcyahefj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuxmbbtce.html

[L04] 设置超时
来源：http://dali.ppjwa.cn/Article/details/gtibxakixj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.iojbl.cn/Article/details/gtepcouwyb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.kuanghao11.cn/Article/details/gtdusjdxqa.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jqgfzy.top/Article/details/gtcejrpthe.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hammf.cn/Article/details/gtrhcyunee.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hfpthk.cn/Article/details/gtsymxqabi.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jqgfzy.top/Article/details/gtctskqurl.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhongyouzk.top/Article/details/gtfolyxrty.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinghuilouyu.cn/Article/details/gtdchvqgyt.html

[L05] 上传文件（multipart）
来源：http://dali.xuetiantiany.cn/Article/details/gtsegivzmu.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinghuilouyu.cn/Article/details/gtucckihik.html


<!-- 参考信息 -->