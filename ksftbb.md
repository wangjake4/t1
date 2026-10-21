代发 wailian999

C#:   Debug.Assert(x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqvnuuiod.html

[H08] 获取错误信息与堆栈
来源：http://dali.smart0.xyz/Article/details/gtyagkhrfc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.havefunace.top/Article/details/gtnldfahav.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.iojbl.cn/Article/details/gtzrireqcy.html

JS:   e.message;  e.stack
来源：http://dali.svipenyu.cn/Article/details/gtglxnhfhq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zycfv.cn/Article/details/gtaqixjtpl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sxryk.cn/Article/details/gtonperqtb.html

Go:   err.Error()
来源：http://dali.gotoacloud.top/Article/details/gtmalcndoh.html

Ruby: e.message;  e.backtrace
来源：http://dali.daria6918.cn/Article/details/gtgpcqkucz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hywenlv.cn/Article/details/gtvviuuhej.html

[H09] 带错误码的异常
来源：http://dali.yj202588.top/Article/details/gttotcgbcu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ehwqpu.com/Article/details/gtzverfcdn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tianlin.xyz/Article/details/gthnukjvah.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yangfankeji.com/Article/details/gtubfuqrxd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgikewqau.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.snrcjt.cn/Article/details/gtconzcnih.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jqgufenzy.top/Article/details/gtwpllwqgo.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tanke756.top/Article/details/gtieiuumip.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.aizwys.cn/Article/details/gtezzwrglk.html

[H10] 资源自动释放
来源：http://dali.nanxuanxn.top/Article/details/gtqjekisys.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hysaishi.cn/Article/details/gtkmyxbztk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tanke756.top/Article/details/gtkqannyou.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.meibo888.top/Article/details/gtqekejaww.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sxryk.cn/Article/details/gtfqxoilsa.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.pycfn.com/Article/details/gtcwlxvyez.html

Go:   defer f.Close()
来源：http://dali.cashguo.top/Article/details/gtpnymruxf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.wangshuangyany.cn/Article/details/gtbqbferll.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtfzqdozyt.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtudqcudkm.html

I. 正则表达式
来源：http://dali.tanke756.top/Article/details/gtzmmfllnd.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtoouvwmny.html

[I01] 判断是否匹配
来源：http://dali.jianghu66.top/Article/details/gthuipurfn.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shzxlz.cn/Article/details/gtzjxvcyie.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sweek.top/Article/details/gtlbkvjvxd.html

JS:   /\d+/.test(s)
来源：http://dali.fengsongda.top/Article/details/gtkvdrxbsd.html

TS:   /\d+/.test(s)
来源：http://dali.iojbl.cn/Article/details/gtnflpwtik.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.9152youxi.cn/Article/details/gtgomafftt.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtegdiuplt.html

Ruby: s.match?(/\d+/)
来源：http://dali.cqqwz.cn/Article/details/gtmvtxpkai.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.guannengcc.top/Article/details/gtbivdtoov.html

[I02] 提取所有匹配
来源：http://dali.shzxlz.cn/Article/details/gtnakwfwdp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gttebmhgar.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.pycfn.com/Article/details/gtzgrjuetu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhengqikj.top/Article/details/gtntyboyaa.html

TS:   s.match(/\d+/g)
来源：http://dali.aibaodan.cn/Article/details/gthoaiftgi.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zycfv.cn/Article/details/gtpijmiaxh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhiwuduotai.top/Article/details/gtboisbasg.html

Ruby: s.scan(/\d+/)
来源：http://dali.316326.xyz/Article/details/gtwewfhkpf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtpsidbrce.html

[I03] 提取捕获分组
来源：http://dali.dashuyun.cn/Article/details/gtfovlitwj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.andypj.xyz/Article/details/gtnnohhwdl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpybxhjtz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.pycfn.com/Article/details/gtpjbyiama.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hongshengwenyu.top/Article/details/gtdjavtndj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jyoumei.cn/Article/details/gtgktxhodm.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.quarkkingdee.top/Article/details/gtyzuprtlu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xinyue.icu/Article/details/gthpiytmzr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hysaishi.cn/Article/details/gtatftzcwy.html

[I04] 正则替换
来源：http://dali.zdqjudy.top/Article/details/gtqhxvwvlg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hammf.cn/Article/details/gtjxdrdfwd.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zdqjudy.top/Article/details/gthuqipjyg.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.tianlin.xyz/Article/details/gterhawntv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gzhubu.top/Article/details/gtijdrxsis.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.c1oappe.top/Article/details/gtwzyacoqu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gtnndrhopx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtvajbgprk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xziqi.cn/Article/details/gthfjliyob.html

[I05] 按正则拆分
来源：http://dali.sysykeji.top/Article/details/gtieccajvs.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ppjwa.cn/Article/details/gtwdmysdlb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jqgfzy.top/Article/details/gtyqwykcxq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gtlnqvjrbv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sufxvd.cn/Article/details/gtupbgtcuq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.0kj1m.cn/Article/details/gtobbtcbge.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ydzc1.top/Article/details/gtwuilvxhk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.0kj1m.cn/Article/details/gthwjbfgrj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhoulong.xyz/Article/details/gtflutaexa.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gotoacloud.top/Article/details/gtfkrvszpc.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yuxming.cn/Article/details/gtsnxeqwgx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hfpthk.cn/Article/details/gtgsxkcaif.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhiwuduotai.top/Article/details/gttljktcns.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangkeji.top/Article/details/gtglhqqdny.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sweek.top/Article/details/gtqwbapfqn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.9152youxi.cn/Article/details/gtoxkddiwl.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yuxming.cn/Article/details/gtidouuyjj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gtlkrpdbft.html

[I07] 忽略大小写与多行模式
来源：http://dali.haohaochexian.top/Article/details/gtywyadaoz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hywenlv.cn/Article/details/gtdqccnjll.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zycfv.cn/Article/details/gtkjkcuexf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jqgufenzy.top/Article/details/gtiwfsyzwp.html

TS:   /error/gim
来源：http://dali.jinqigufen.top/Article/details/gtuvdcinom.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ivvv.top/Article/details/gtjqnhnjpv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.bjfxy.top/Article/details/gthfyjmudw.html

Ruby: s.scan(/error/i)
来源：http://dali.fengsongda.top/Article/details/gtprkjcwwy.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ybcxt.top/Article/details/gtmsfeggno.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.mhx1999.top/Article/details/gtuckglwyy.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cqqwz.cn/Article/details/gtjcfujidw.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.aibaodan.cn/Article/details/gtyxxbcdpc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinqigfzy.top/Article/details/gtgxvzalth.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.vqdsnc.cn/Article/details/gtidtbyymw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhixingplan.top/Article/details/gtcibcrgkm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.wangdashe.top/Article/details/gtlnygdkxx.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.dashuyun.cn/Article/details/gtltmapzxk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hongshengwenyu.top/Article/details/gtagswskgc.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtqlbkgtww.html

J. 日期与时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqycgnspn.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtciezetal.html

[J01] 获取当前时间
来源：http://dali.mhx1999.top/Article/details/gtogjkladc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj20258.top/Article/details/gtfydkwtyu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xinyue.icu/Article/details/gtrpkwmqhr.html

JS:   new Date();  Date.now()
来源：http://dali.ivvv.top/Article/details/gtdtalynbs.html

TS:   new Date();  Date.now()
来源：http://dali.feifeiyinyue.top/Article/details/gtqdoulfdl.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.birdmap.top/Article/details/gtqlzrnwzt.html

Go:   time.Now()
来源：http://dali.c1oappe.top/Article/details/gtibsnmgsj.html

Ruby: Time.now
来源：http://dali.zhaomingkeji.xyz/Article/details/gtybmpdplp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shuidangran.top/Article/details/gtyzyfuyng.html

[J02] 格式化输出
来源：http://dali.yj202588.top/Article/details/gtkwecejqi.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258888.top/Article/details/gtelezftss.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.mhx1999.top/Article/details/gtojxnspze.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jyoumei.cn/Article/details/gtgxrospym.html

TS:   d.toISOString()
来源：http://dali.xziqi.cn/Article/details/gtpamrqcbx.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenlongwang.top/Article/details/gtuwgndwsu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.tanke756.top/Article/details/gtdavuaobc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkffherxl.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.fzhhl.top/Article/details/gtdbmjjzsk.html

[J03] 字符串解析为日期
来源：http://dali.yanxiufei.cn/Article/details/gtvhremntj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hfpthk.cn/Article/details/gtknvytghu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nanxuanxn.top/Article/details/gthiqprcdm.html

JS:   new Date("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtynlpqtzb.html

TS:   new Date("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gtjwfssbsk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gtuehjsfuc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gtjykxlfmk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gtmclkysat.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.vqdsnc.cn/Article/details/gtvlmyqogu.html

[J04] 时间戳与日期互转
来源：http://dali.tian-w.cn/Article/details/gtrkzgyocp.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.havefunace.top/Article/details/gtrdxqmdou.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqszfkrbo.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yongpay.top/Article/details/gtbigtymkq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.pycfn.com/Article/details/gthbhstlgt.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gtdgykkidz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtgnwdslrj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.9152youxi.cn/Article/details/gtnaepofjz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ppjwa.cn/Article/details/gttuhfdarj.html

[J05] 时间加减（加 7 天）
来源：http://dali.vqdsnc.cn/Article/details/gtujhvknen.html

Py:   now + timedelta(days=7)
来源：http://dali.zhoulong.xyz/Article/details/gtwvizbope.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.wangdashe.top/Article/details/gteietgqce.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.birdmap.top/Article/details/gtbletvltf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.meibo888.top/Article/details/gttmswzpmh.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.c1oappe.top/Article/details/gtcxpmqwjz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.birdmap.top/Article/details/gtzxmxiwmx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ivvv.top/Article/details/gtwqagaxlq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cdnleiting.top/Article/details/gtzbblpuzn.html

[J06] 计算两时间之差
来源：http://dali.hysaishi.cn/Article/details/gttqejlfse.html

Py:   (end - start).total_seconds()
来源：http://dali.jinqigfzy.top/Article/details/gtdcvvlmgy.html

PHP:  $end->diff($start)->days;
来源：http://dali.yj20258888.top/Article/details/gtkqtrmlfb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.svipenyu.cn/Article/details/gtfzglcnlt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hammf.cn/Article/details/gtrlqsgnrc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.dashuyun.cn/Article/details/gtygxyveuq.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhixingplan.top/Article/details/gtpwwxpvzi.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sysykeji.top/Article/details/gtmtkepmyn.html

C#:   (end - start).TotalSeconds
来源：http://dali.haohaochexian.top/Article/details/gtbauoxcvy.html

[J07] 比较两个日期
来源：http://dali.jianghu66.top/Article/details/gtaoevmpxy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.nwbrower.top/Article/details/gtofxzjuwl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hfpthk.cn/Article/details/gthhtlxpnz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.dianchejie.cn/Article/details/gtmodkfvms.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sxryk.cn/Article/details/gtwonpisno.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.9152youxi.cn/Article/details/gtkvauzarg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfwxzlcld.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.quarkkingdee.top/Article/details/gtuxnqtbga.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.quarkkingdee.top/Article/details/gtpfkaxtma.html

[J08] 提取年月日与星期
来源：http://dali.hnxiangtu.top/Article/details/gtnqtgyobp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhixingplan.top/Article/details/gthcrglnxf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ehwqpu.com/Article/details/gttsecoihj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.haohaochexian.top/Article/details/gtagfxiasd.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nanxuanxn.top/Article/details/gtwiwmrcbj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.0kj1m.cn/Article/details/gtdwipnmll.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hnqzz.top/Article/details/gtrdprcbno.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.nanxinkj.top/Article/details/gtgeknmpzx.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zycfv.cn/Article/details/gtormrlvkn.html

[J09] 时区处理
来源：http://dali.xylfe.cn/Article/details/gtfkdwdwzz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.chenjidiqi.icu/Article/details/gtoijiqmgp.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jqgfzy.top/Article/details/gtcdfcgxqv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hfpthk.cn/Article/details/gteimvhygb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ehwqpu.com/Article/details/gtnetpnsue.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hnxiangtu.top/Article/details/gtevhzesiq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.pengpengdd.cyou/Article/details/gtobpzchxn.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yangfankeji.com/Article/details/gtouawmmog.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.birdmap.top/Article/details/gtgqnvrhcw.html

[J10] 取今天 / 本月第一天
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtckbcsqvj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhiwuduotai.top/Article/details/gtxdxtfafv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.redwolf501.top/Article/details/gtecuuadlw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfbkfgdlj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gotoacloud.top/Article/details/gttiuzahph.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yanxiufei.cn/Article/details/gtlxvqokye.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xinyue.icu/Article/details/gtdzxrlaon.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tian-w.cn/Article/details/gtsrngfwyv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtoqjxpowv.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtaeoxjkhy.html

K. JSON 与序列化
来源：http://dali.shanyushiyangtech.top/Article/details/gtijvbyukm.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtotqdiesm.html

[K01] 对象转 JSON 字符串
来源：http://dali.fzhhl.top/Article/details/gtfhyvzkxy.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.bjfxy.top/Article/details/gtxjiqfkbw.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxuanxn.top/Article/details/gtzzdhijno.html

JS:   JSON.stringify(obj)
来源：http://dali.cdnleiting.top/Article/details/gtkuhydeks.html

TS:   JSON.stringify(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyisnfqqk.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.wangshuangyany.cn/Article/details/gtprkydexf.html

Go:   json.Marshal(obj)
来源：http://dali.fengsongda.top/Article/details/gtnndaijoa.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.mhx1999.top/Article/details/gtjkeqcvqv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sxryk.cn/Article/details/gttsrlvezf.html

[K02] JSON 字符串转对象
来源：http://dali.hywenlv.cn/Article/details/gttvvzgeif.html

Py:   json.loads(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcwvwqtoe.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yuxming.cn/Article/details/gtntgvqudv.html

JS:   JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gthoxkfkfe.html

TS:   JSON.parse(s)
来源：http://dali.hnxiangtu.top/Article/details/gttppyloqr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cheryme.top/Article/details/gttnnqgexb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xziqi.cn/Article/details/gtjobltupw.html

Ruby: JSON.parse(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtricayjwm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ydzc1.top/Article/details/gtsplnqgcg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yvedp.cn/Article/details/gtwzhxyklt.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yongpay.top/Article/details/gtrhunffpu.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cdnleiting.top/Article/details/gtgliumiwr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxuanxn.top/Article/details/gtqgjrmmkm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gzhubu.top/Article/details/gtdjsnzsgb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.fzhhl.top/Article/details/gtauqpedzb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yueranfly.top/Article/details/gtjdtxgkvb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yuanzhike.top/Article/details/gtcifvoqcy.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.316326.xyz/Article/details/gtbqwxqhgc.html

[K04] 读取 JSON 文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpotbrxox.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.c1oappe.top/Article/details/gtxasubcpj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sysykeji.top/Article/details/gtsvlpfoiv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhixingplan.top/Article/details/gtdsyxzdst.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guannengcc.top/Article/details/gtsbvxtoqe.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gzhubu.top/Article/details/gtifnurwgv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zdqjudy.top/Article/details/gtexggktgr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sufxvd.cn/Article/details/gtcgzzolgn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nanxuanxn.top/Article/details/gtovsrclnm.html

[K05] 深拷贝对象
来源：http://dali.svipenyu.cn/Article/details/gtrqvcojiy.html

Py:   copy.deepcopy(obj)
来源：http://dali.daxiang520.top/Article/details/gtfpttxppk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shzxlz.cn/Article/details/gtfnususmt.html

JS:   structuredClone(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtisyrvagi.html

TS:   structuredClone(obj)
来源：http://dali.havefunace.top/Article/details/gtcdqnymaw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.dianchejie.cn/Article/details/gtyalmnlbi.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xuetiantiany.cn/Article/details/gtrglemvrr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hfpthk.cn/Article/details/gtprpuobtb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.mhx1999.top/Article/details/gtnwnmejwv.html

[K06] 解析 URL 查询串
来源：http://dali.yvedp.cn/Article/details/gtiokwyujc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hnxiangtu.top/Article/details/gtfhvzglso.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yongpay.top/Article/details/gtfagynnxr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ivvv.top/Article/details/gtkecfoxta.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shzxlz.cn/Article/details/gtrxxywjvf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gtlfqgerxz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.kuanghao11.cn/Article/details/gtyyfuwuhp.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.daria6918.cn/Article/details/gtbyjdjpfq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jiagoushi.top/Article/details/gtilglwbig.html

[K07] 进制转换
来源：http://dali.hammf.cn/Article/details/gthpdnhnef.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gttkowklpe.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.316326.xyz/Article/details/gtghorusvr.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gtmmmgqfzv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gtoipgxxha.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gtkemqzfsh.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jyoumei.cn/Article/details/gtnzqcheaq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ppjwa.cn/Article/details/gtxgddzccz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gtwocppfus.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.wangdashe.top/Article/details/gtdsyezdoy.html

Py:   pickle.dumps(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjpxucnld.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.chenlongwang.top/Article/details/gtgllqayqz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.fzhhl.top/Article/details/gtnfkatpvv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhiwuduotai.top/Article/details/gtddqmogdz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hysaishi.cn/Article/details/gtgqkcbhqy.html

Go:   encoding/gob
来源：http://dali.gaohongyu789.top/Article/details/gtaomdxwjf.html

Ruby: Marshal.dump(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtzdzqxfsj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.tanke756.top/Article/details/gtnwrljmpp.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtsitydivu.html

L. 网络请求
来源：http://dali.ivvv.top/Article/details/gtldayhaew.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtpvytfcde.html

[L01] 发送 GET 请求
来源：http://dali.xuanzx.com/Article/details/gtgoiqvkne.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.dianchejie.cn/Article/details/gtevxwllgx.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jiagoushi.top/Article/details/gtgxqyyctd.html

JS:   await fetch(url)
来源：http://dali.redwolf501.top/Article/details/gtsokuvfsq.html

TS:   await fetch(url)
来源：http://dali.shangyingyoupin.top/Article/details/gtvcvijzqp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.aizwys.cn/Article/details/gtqpnjnbco.html

Go:   resp, err := http.Get(url)
来源：http://dali.tanke756.top/Article/details/gtfxgascup.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpivlkitm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.nanxinkj.top/Article/details/gtcaqriiab.html

[L02] 发送 POST JSON
来源：http://dali.shzxlz.cn/Article/details/gtxkcxlpij.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gzhubu.top/Article/details/gtefexpoon.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.c1oappe.top/Article/details/gtdlyohtts.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sysykeji.top/Article/details/gtktkvputw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sufxvd.cn/Article/details/gtvazjquoh.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinqigfzy.top/Article/details/gtwdasmrtu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cheryme.top/Article/details/gtoxgdyuzm.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.tanke756.top/Article/details/gtlxpeydul.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.tanke756.top/Article/details/gtdqxdnzag.html

[L03] 设置自定义请求头
来源：http://dali.hongshengwenyu.top/Article/details/gtjqebyyit.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sufxvd.cn/Article/details/gtaggfkbje.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hysaishi.cn/Article/details/gtuagytmvc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxuanxn.top/Article/details/gtketfxdqv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tianlin.xyz/Article/details/gtnlzzzagy.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yuanzhike.top/Article/details/gtchrscxbo.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cqqwz.cn/Article/details/gtgjlawqwu.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jiagoushi.top/Article/details/gtbmzmhjsf.html


<!-- 参考信息 -->