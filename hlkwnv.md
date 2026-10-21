代发 wailian999

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.guowangkeji.top/Article/details/gtkmkcknwm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cheryme.top/Article/details/gtinftldml.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sufxvd.cn/Article/details/gtlzzddekk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hongshengwenyu.top/Article/details/gtudbnmujs.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sysykeji.top/Article/details/gtfdawkpmv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hongshengwenyu.top/Article/details/gtnkezoqdd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhiwuduotai.top/Article/details/gtkjcmmgin.html

[H10] 资源自动释放
来源：http://dali.ybcxt.top/Article/details/gtrrdnnsjq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.9152youxi.cn/Article/details/gtwfnqiolo.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.nanxinkj.top/Article/details/gtyaqxvrgt.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpzvgiixe.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yongpay.top/Article/details/gtadbnpgcf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhaomingkeji.xyz/Article/details/gtldbmwvmd.html

Go:   defer f.Close()
来源：http://dali.hfpthk.cn/Article/details/gtiklajasn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.chenlongwang.top/Article/details/gtzcnglppl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtpoexiqbn.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtfvyvawug.html

I. 正则表达式
来源：http://dali.xinyue.icu/Article/details/gtoudixoen.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtzmtgramp.html

[I01] 判断是否匹配
来源：http://dali.jinqigfzy.top/Article/details/gthiypdllv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sweek.top/Article/details/gtqpehvdwt.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ppjwa.cn/Article/details/gtykihywik.html

JS:   /\d+/.test(s)
来源：http://dali.9152youxi.cn/Article/details/gtxzguffxa.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gtjzqhwqiy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlbqedpjh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hnxiangtu.top/Article/details/gtmixkbpek.html

Ruby: s.match?(/\d+/)
来源：http://dali.jqgufenzy.top/Article/details/gtiqrjwhmb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.sufxvd.cn/Article/details/gtmqnsaebi.html

[I02] 提取所有匹配
来源：http://dali.wangdashe.top/Article/details/gtaehrxvap.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cheryme.top/Article/details/gtrfietklg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ydzc1.top/Article/details/gtvqdqsztu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.iojbl.cn/Article/details/gtbxqagufu.html

TS:   s.match(/\d+/g)
来源：http://dali.chenlongwang.top/Article/details/gtmvewndju.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.andypj.xyz/Article/details/gtqteyxjmn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhixingplan.top/Article/details/gtjvwkpyax.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkmlknbtm.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gtbbcaiclw.html

[I03] 提取捕获分组
来源：http://dali.c1oappe.top/Article/details/gthajontcr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sweek.top/Article/details/gtzplucorp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xziqi.cn/Article/details/gtcfrkxllo.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jqgfzy.top/Article/details/gtcslzkxhv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gtcmghxlic.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cqqwz.cn/Article/details/gthuwgyquh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.nwbrower.top/Article/details/gtvkowqadl.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.aibaodan.cn/Article/details/gtvardlcur.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hnxiangtu.top/Article/details/gtkxqsnane.html

[I04] 正则替换
来源：http://dali.zdqjudy.top/Article/details/gtblolbepc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gzhubu.top/Article/details/gtlhtekroz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.9152youxi.cn/Article/details/gtcgkrfnmn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xuanzx.com/Article/details/gtbddmcqiw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258.top/Article/details/gtsgvyjwas.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.kuanghao11.cn/Article/details/gthrcrkrpy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.dianchejie.cn/Article/details/gttftmdzei.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hywenlv.cn/Article/details/gtcqogicqm.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gtixikzitd.html

[I05] 按正则拆分
来源：http://dali.cqqwz.cn/Article/details/gtoixfvexb.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hnxiangtu.top/Article/details/gtnyqhntdu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yueranfly.top/Article/details/gtxzglhdgg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gtutexjcad.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.chenzaomai.com/Article/details/gtonqvaevt.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sweek.top/Article/details/gtxivdnsnt.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hywenlv.cn/Article/details/gtdewtsnsy.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hywenlv.cn/Article/details/gtvmgutial.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.birdmap.top/Article/details/gtatyxgsdn.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenzaomai.com/Article/details/gttjcohebk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zycfv.cn/Article/details/gtblbqyuvl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gaohongyu789.top/Article/details/gtayoybgdu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigfzy.top/Article/details/gtwgxxabvo.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hammf.cn/Article/details/gtwrhbvhpf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hongshengwenyu.top/Article/details/gtwqqmgadu.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sufxvd.cn/Article/details/gtsdljnkga.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.nanxinkj.top/Article/details/gtkpwqyrtg.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sxryk.cn/Article/details/gtiyxkfedb.html

[I07] 忽略大小写与多行模式
来源：http://dali.cqqwz.cn/Article/details/gtprenfmlq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.havefunace.top/Article/details/gtvzmllifn.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jqgufenzy.top/Article/details/gtgijrfibo.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj202588.top/Article/details/gtunfpxdil.html

TS:   /error/gim
来源：http://dali.shzxlz.cn/Article/details/gtazruzxgu.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.feifeiyinyue.top/Article/details/gtylmrauif.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtelywdstp.html

Ruby: s.scan(/error/i)
来源：http://dali.andypj.xyz/Article/details/gtpnktqven.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shzxlz.cn/Article/details/gtunoltikq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nanxinkj.top/Article/details/gtteultxiw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cqqwz.cn/Article/details/gtmlhudldt.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinghuilouyu.cn/Article/details/gtqowwlszf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttjztamfe.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.316326.xyz/Article/details/gtraovgtvj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxoftsgzf.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhengqikj.top/Article/details/gtobxqaxty.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.fengsongda.top/Article/details/gtcqoxphru.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.kuanghao11.cn/Article/details/gtmvwignjn.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gteaadltto.html

J. 日期与时间
来源：http://dali.cashguo.top/Article/details/gtoonlxcmn.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtitfqwmvf.html

[J01] 获取当前时间
来源：http://dali.yj20258.top/Article/details/gtalkaxjsx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.guannengcc.top/Article/details/gtxysvzvwz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.nanxuanxn.top/Article/details/gtxavgcfyx.html

JS:   new Date();  Date.now()
来源：http://dali.vqdsnc.cn/Article/details/gtaomwbegc.html

TS:   new Date();  Date.now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfalzvlwi.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinqigfzy.top/Article/details/gtgdplsfcs.html

Go:   time.Now()
来源：http://dali.iojbl.cn/Article/details/gttdwgbtbh.html

Ruby: Time.now
来源：http://dali.hysaishi.cn/Article/details/gtmqlgobwm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hongshengwenyu.top/Article/details/gtcicxzvxw.html

[J02] 格式化输出
来源：http://dali.vqdsnc.cn/Article/details/gtsjltdosk.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yanxiufei.cn/Article/details/gtcnfhpgbr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.dashuyun.cn/Article/details/gtsqmgwcth.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.daria6918.cn/Article/details/gtxopalifz.html

TS:   d.toISOString()
来源：http://dali.jinghuilouyu.cn/Article/details/gteppndlgs.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ehwqpu.com/Article/details/gtnyzcvqhp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.tian-w.cn/Article/details/gtkchbdmjf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.bjfxy.top/Article/details/gtjuurwouj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtehnlxawg.html

[J03] 字符串解析为日期
来源：http://dali.tianlin.xyz/Article/details/gtxjriumvl.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yuanzhike.top/Article/details/gtdlpxamwr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jianghu66.top/Article/details/gtzmwqqggs.html

JS:   new Date("2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gtnfxjpvav.html

TS:   new Date("2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gtjyghgfvr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gtcpyiwfzb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlhwtozzx.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gtgxqtspyj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.andypj.xyz/Article/details/gtxsyruoxo.html

[J04] 时间戳与日期互转
来源：http://dali.gzhubu.top/Article/details/gtnpkedyul.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jianghu66.top/Article/details/gtvfszwqrj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cashguo.top/Article/details/gtoyivbxxh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhoulong.xyz/Article/details/gtyrrdlluq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xylfe.cn/Article/details/gtouqqwqsa.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yanxiufei.cn/Article/details/gtgkdfwxev.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sxryk.cn/Article/details/gtkhycnmjk.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jinqigufen.top/Article/details/gthmhkpksb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinghuilouyu.cn/Article/details/gttvsvegdv.html

[J05] 时间加减（加 7 天）
来源：http://dali.hnxiangtu.top/Article/details/gtxbeoydnf.html

Py:   now + timedelta(days=7)
来源：http://dali.daxiang520.top/Article/details/gtmyitycve.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.pycfn.com/Article/details/gtmvqypeqy.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.316326.xyz/Article/details/gtjayivhzy.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtetwoxpkk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.dianchejie.cn/Article/details/gtdmdegxhi.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.bjfxy.top/Article/details/gtsmdladhm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jianghu66.top/Article/details/gtajiwffbt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sysykeji.top/Article/details/gtkaiqsfgd.html

[J06] 计算两时间之差
来源：http://dali.cqqwz.cn/Article/details/gtemafddal.html

Py:   (end - start).total_seconds()
来源：http://dali.xylfe.cn/Article/details/gtuyiewzxo.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinghuilouyu.cn/Article/details/gthvzkxkde.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.feifeiyinyue.top/Article/details/gtrfuhhirb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.daxiang520.top/Article/details/gtgqpzhxzi.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ybcxt.top/Article/details/gtlhgmtfjg.html

Go:   end.Sub(start).Hours()
来源：http://dali.cucudq.cn/Article/details/gtoydgeqqm.html

Ruby: end - start                 # 返回秒数
来源：http://dali.chenzaomai.com/Article/details/gtlqcrtmok.html

C#:   (end - start).TotalSeconds
来源：http://dali.zdqjudy.top/Article/details/gtwdoussen.html

[J07] 比较两个日期
来源：http://dali.daxiang520.top/Article/details/gtocyjzugu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinqigfzy.top/Article/details/gtevimdupg.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.tian-w.cn/Article/details/gtodmngash.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.meibo888.top/Article/details/gtkbsyugqb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gtfbjonivp.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yanxiufei.cn/Article/details/gtzdxpnjpv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.haohaochexian.top/Article/details/gtiustewmp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zdqjudy.top/Article/details/gthgdpqgom.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.havefunace.top/Article/details/gtlopjacyg.html

[J08] 提取年月日与星期
来源：http://dali.ehwqpu.com/Article/details/gtcfirgfbv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.9152youxi.cn/Article/details/gtkgxfqgvf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.redwolf501.top/Article/details/gtqdviibdc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhixingplan.top/Article/details/gtjrukavpw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhixingplan.top/Article/details/gtopzmbzhg.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.fzhhl.top/Article/details/gtuilycwbl.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xylfe.cn/Article/details/gthqfehfgs.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gotoacloud.top/Article/details/gtpkwjpmaj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sxryk.cn/Article/details/gtrqtnbuen.html

[J09] 时区处理
来源：http://dali.xziqi.cn/Article/details/gtinwoqwjs.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shuidangran.top/Article/details/gtxuayxymo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhijiandao.cn/Article/details/gtcvutepix.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.andypj.xyz/Article/details/gtorioqrlk.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangshuangyany.cn/Article/details/gtuyguldan.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yj202588.top/Article/details/gtessdkppp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shangyingyoupin.top/Article/details/gtlfbcckwt.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.birdmap.top/Article/details/gtjrzaqoco.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ydzc1.top/Article/details/gtxedkvfts.html

[J10] 取今天 / 本月第一天
来源：http://dali.dashuyun.cn/Article/details/gtydpofcyc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cheryme.top/Article/details/gtqmeqafju.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yonumen.top/Article/details/gtjabbslov.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.nanxinkj.top/Article/details/gtbintaqsc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cucudq.cn/Article/details/gtbqtzmktf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gaohongyu789.top/Article/details/gtdhhvmsgo.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xylfe.cn/Article/details/gtvflichuf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yj20258.top/Article/details/gtfcnnljxw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuchxaaut.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gteyfeybyq.html

K. JSON 与序列化
来源：http://dali.zhoulong.xyz/Article/details/gtyvbjbihp.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtfkqimbtx.html

[K01] 对象转 JSON 字符串
来源：http://dali.mhx1999.top/Article/details/gtakzwxtau.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jqgfzy.top/Article/details/gtdwdyehlt.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhixingplan.top/Article/details/gtkwbudjjv.html

JS:   JSON.stringify(obj)
来源：http://dali.hammf.cn/Article/details/gtkpeasvbs.html

TS:   JSON.stringify(obj)
来源：http://dali.yj20258.top/Article/details/gtwxqjvkwm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ybcxt.top/Article/details/gtntrbdlpw.html

Go:   json.Marshal(obj)
来源：http://dali.fzhhl.top/Article/details/gtuniuaref.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jiagoushi.top/Article/details/gtvmozrvez.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtqpmbhljj.html

[K02] JSON 字符串转对象
来源：http://dali.bjfxy.top/Article/details/gttxcuzhix.html

Py:   json.loads(s)
来源：http://dali.meibo888.top/Article/details/gtqjenipnj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hnxiangtu.top/Article/details/gtwpvzavxy.html

JS:   JSON.parse(s)
来源：http://dali.haohaochexian.top/Article/details/gtkrmwoptq.html

TS:   JSON.parse(s)
来源：http://dali.zhixingplan.top/Article/details/gtpbsywtoq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gotoacloud.top/Article/details/gtxsfcewbh.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yongpay.top/Article/details/gtiwtyhbjg.html

Ruby: JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtobzxxksl.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gotoacloud.top/Article/details/gtpphpqzil.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.c1oappe.top/Article/details/gtwbxihmno.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.dashuyun.cn/Article/details/gtqogujbqg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cqqwz.cn/Article/details/gttqmuncev.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yueranfly.top/Article/details/gtuikoblof.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtggyyauip.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.redwolf501.top/Article/details/gtzmngrqev.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gtvayqptuw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jyoumei.cn/Article/details/gtmpywevqv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hongshengwenyu.top/Article/details/gtjfogpxsd.html

[K04] 读取 JSON 文件
来源：http://dali.ydzc1.top/Article/details/gtnwjyvttu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yj20258.top/Article/details/gtmipzcfdm.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvgmyezgy.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hywenlv.cn/Article/details/gteqrvrjkj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xuetiantiany.cn/Article/details/gtioilrngc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.guowangkeji.top/Article/details/gtimnqjgac.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtluvxranv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.fengsongda.top/Article/details/gtwqjaxagk.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgcmmlvib.html

[K05] 深拷贝对象
来源：http://dali.yvedp.cn/Article/details/gtboagbflr.html

Py:   copy.deepcopy(obj)
来源：http://dali.hywenlv.cn/Article/details/gtvksfgkta.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhixingplan.top/Article/details/gtnevtreav.html

JS:   structuredClone(obj)
来源：http://dali.yj202588.top/Article/details/gtdrqhmckz.html

TS:   structuredClone(obj)
来源：http://dali.zycfv.cn/Article/details/gtpqkkwaqy.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.316326.xyz/Article/details/gtmebkscyp.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yueranfly.top/Article/details/gtifeubqyy.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.guowangkeji.top/Article/details/gtkyjdqxov.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.feifeiyinyue.top/Article/details/gthbzdjkny.html

[K06] 解析 URL 查询串
来源：http://dali.yj20258888.top/Article/details/gtwetvaxzt.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gogol.net.cn/Article/details/gtqygqocgh.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xuetiantiany.cn/Article/details/gtpyotredn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jlsjyb.cn/Article/details/gtlqhrageo.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zdqjudy.top/Article/details/gtsvruotgx.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.havefunace.top/Article/details/gtruwotrad.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yongpay.top/Article/details/gtmtyczwnn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqhaymzwn.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.wangshuangyany.cn/Article/details/gtzlamfzcx.html

[K07] 进制转换
来源：http://dali.hammf.cn/Article/details/gtfaffuzuz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.316326.xyz/Article/details/gtlkspazdu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yj20258.top/Article/details/gthycfhwhn.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.birdmap.top/Article/details/gtsmnmvcie.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtdwgicukx.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gtcluvtqow.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinqigufen.top/Article/details/gteklrafed.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.dianchejie.cn/Article/details/gtsymtqxke.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrxaijpxm.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.snrcjt.cn/Article/details/gtlveogxcd.html

Py:   pickle.dumps(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtclkkuiuy.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hywenlv.cn/Article/details/gtsuwpcpau.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.mhx1999.top/Article/details/gtdshapzeh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yueranfly.top/Article/details/gtceaywlvg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.feifeiyinyue.top/Article/details/gtawjgppbs.html

Go:   encoding/gob
来源：http://dali.shzxlz.cn/Article/details/gtbwbsgrop.html

Ruby: Marshal.dump(obj)
来源：http://dali.nwbrower.top/Article/details/gtbpwxmuiu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xylfe.cn/Article/details/gtouflvpwa.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtcihrrcfd.html

L. 网络请求
来源：http://dali.cdnleiting.top/Article/details/gtvismgwwp.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gttqmcduof.html

[L01] 发送 GET 请求
来源：http://dali.yvedp.cn/Article/details/gtwvhjkgtb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hysaishi.cn/Article/details/gtfamvmovj.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.9152youxi.cn/Article/details/gtockbetzd.html

JS:   await fetch(url)
来源：http://dali.yonumen.top/Article/details/gtoxludwjn.html

TS:   await fetch(url)
来源：http://dali.vqdsnc.cn/Article/details/gtwvrvirsg.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.feifeiyinyue.top/Article/details/gtmmfsnhtg.html

Go:   resp, err := http.Get(url)
来源：http://dali.snrcjt.cn/Article/details/gttbkhptkj.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cdnleiting.top/Article/details/gtupfbiriv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhiwuduotai.top/Article/details/gtwrztuqau.html

[L02] 发送 POST JSON
来源：http://dali.feifeiyinyue.top/Article/details/gtmwhexapw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hongshengwenyu.top/Article/details/gterzuekab.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.haohaochexian.top/Article/details/gtbeijjgjr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoahezqhh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigfzy.top/Article/details/gtmiytzlsa.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.mhx1999.top/Article/details/gtwjgabjxl.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yonumen.top/Article/details/gtzgygbjzk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cdnleiting.top/Article/details/gtqvijulyo.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yonumen.top/Article/details/gtqunnjsog.html

[L03] 设置自定义请求头
来源：http://dali.zhixingplan.top/Article/details/gtrlaprivv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.smart0.xyz/Article/details/gtfnqlcjmg.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yueranfly.top/Article/details/gtbfrkgluh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cucudq.cn/Article/details/gtnusceerb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yonumen.top/Article/details/gtnpjstqrv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cheryme.top/Article/details/gtoxjfctpc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yonumen.top/Article/details/gtgnmpdxbl.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yuanzhike.top/Article/details/gtnvrstkch.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yonumen.top/Article/details/gtssztfren.html

[L04] 设置超时
来源：http://dali.yj20258888.top/Article/details/gtcrpzeaee.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hongshengwenyu.top/Article/details/gtbaodwzkg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.chenlongwang.top/Article/details/gtjibnmkty.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shangyingyoupin.top/Article/details/gtgccjkzkp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenjidiqi.icu/Article/details/gtagngklbw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cdnleiting.top/Article/details/gtpclofbvq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.pengpengdd.cyou/Article/details/gtfksepirw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yuxming.cn/Article/details/gtgrezrvxo.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.bjfxy.top/Article/details/gtbhgljuiv.html

[L05] 上传文件（multipart）
来源：http://dali.yueranfly.top/Article/details/gtxflrjbpq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cdnleiting.top/Article/details/gtkwvnvrse.html


<!-- 参考信息 -->