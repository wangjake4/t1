代发 wailian999

JS:   e.message;  e.stack
来源：http://dali.hammf.cn/Article/details/gtljmylwqy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.aizwys.cn/Article/details/gtmigurnwb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xinyue.icu/Article/details/gtstxbhqkb.html

Go:   err.Error()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiknieiae.html

Ruby: e.message;  e.backtrace
来源：http://dali.zycfv.cn/Article/details/gtbhawvpnc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.havefunace.top/Article/details/gtxmtzapcb.html

[H09] 带错误码的异常
来源：http://dali.shuidangran.top/Article/details/gtlqqbmqsd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhiwuduotai.top/Article/details/gtmfiyltie.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xuanzx.com/Article/details/gtkbbuzhaz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jianghu66.top/Article/details/gtovzlktzy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.nanxuanxn.top/Article/details/gtsxfroeap.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hnxiangtu.top/Article/details/gtrgognskh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yj202588.top/Article/details/gtemgvasfk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.chenzaomai.com/Article/details/gtqcebsbeu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ivvv.top/Article/details/gtvgrwsbop.html

[H10] 资源自动释放
来源：http://dali.jinghuilouyu.cn/Article/details/gtjnovrfre.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cheryme.top/Article/details/gtevwlwjek.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hfpthk.cn/Article/details/gtpmploeif.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.9152youxi.cn/Article/details/gtujtvmsub.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.svipenyu.cn/Article/details/gtjpuxnadd.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cheryme.top/Article/details/gtcdcuuhah.html

Go:   defer f.Close()
来源：http://dali.yj20258888.top/Article/details/gtwcrxdssd.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xinyue.icu/Article/details/gttojehcxb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cashguo.top/Article/details/gtfbccetig.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtusajqyyt.html

I. 正则表达式
来源：http://dali.shuidangran.top/Article/details/gtsrhmuipe.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtcoqekisj.html

[I01] 判断是否匹配
来源：http://dali.ybcxt.top/Article/details/gtsoywfbdf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xuetiantiany.cn/Article/details/gttlpolsxh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yj20258.top/Article/details/gtrfvujdvy.html

JS:   /\d+/.test(s)
来源：http://dali.cashguo.top/Article/details/gtplkusjfx.html

TS:   /\d+/.test(s)
来源：http://dali.hywenlv.cn/Article/details/gttorntord.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jqgfzy.top/Article/details/gtdbbvfynn.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gotoacloud.top/Article/details/gtoilyvlyf.html

Ruby: s.match?(/\d+/)
来源：http://dali.pengpengdd.cyou/Article/details/gtsjtrvlfx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.nanxinkj.top/Article/details/gtcdewvuzu.html

[I02] 提取所有匹配
来源：http://dali.dashuyun.cn/Article/details/gtciylknqu.html

Py:   re.findall(r"\d+", s)
来源：http://dali.c1oappe.top/Article/details/gtgdyduevl.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.redwolf501.top/Article/details/gtcplyimal.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.nanxuanxn.top/Article/details/gtlqkzanuk.html

TS:   s.match(/\d+/g)
来源：http://dali.jqgufenzy.top/Article/details/gtutvxaodz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.redwolf501.top/Article/details/gtnncbnkhk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yonumen.top/Article/details/gtwqqhwiwt.html

Ruby: s.scan(/\d+/)
来源：http://dali.yj202588.top/Article/details/gtmbmanahp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtktclnfrp.html

[I03] 提取捕获分组
来源：http://dali.aibaodan.cn/Article/details/gtxgbtvadg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhongyouzk.top/Article/details/gtgwjeahwf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhengqikj.top/Article/details/gtxdcsaqye.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gthuvcphtn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.chenlongwang.top/Article/details/gtswhyhyar.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hammf.cn/Article/details/gtulsmhztz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.mhx1999.top/Article/details/gtfmwauldw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yongpay.top/Article/details/gtjnlsdsnz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.dashuyun.cn/Article/details/gtihqfeqkm.html

[I04] 正则替换
来源：http://dali.sweek.top/Article/details/gtdrqvrfcu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shuidangran.top/Article/details/gtupoemzzv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shuidangran.top/Article/details/gtqbzsdrut.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yongpay.top/Article/details/gtjwosphcz.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gaohongyu789.top/Article/details/gtotjfodoa.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gotoacloud.top/Article/details/gtpxcyspac.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.haohaochexian.top/Article/details/gtazslgaxn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ppjwa.cn/Article/details/gttbiejdvm.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.feifeiyinyue.top/Article/details/gtrgfiufno.html

[I05] 按正则拆分
来源：http://dali.guowangkeji.top/Article/details/gtallsxezq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.c1oappe.top/Article/details/gttplygrjr.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.fengsongda.top/Article/details/gtpwyekcze.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.nanxinkj.top/Article/details/gtkvqnxpwy.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tanke756.top/Article/details/gtnoxrtbdp.html

Java: s.split("\\s*,\\s*")
来源：http://dali.dashuyun.cn/Article/details/gtqdwimhpi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ivvv.top/Article/details/gtcntqqfie.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.quarkkingdee.top/Article/details/gthlhncriv.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yueranfly.top/Article/details/gtqjfgszsl.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.316326.xyz/Article/details/gtzsljbwdu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hysaishi.cn/Article/details/gtflgsvzip.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ppjwa.cn/Article/details/gtctwxudjy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnxiangtu.top/Article/details/gtipwuddvx.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.iojbl.cn/Article/details/gtyslrixda.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkozaseyj.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.meibo888.top/Article/details/gtpuknekjv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.nanxinkj.top/Article/details/gtcjxekhcx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzyvxfrkp.html

[I07] 忽略大小写与多行模式
来源：http://dali.ivvv.top/Article/details/gtmywhbzbj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.andypj.xyz/Article/details/gttudamkoq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.kuanghao11.cn/Article/details/gtqxlnneau.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmuunxlqa.html

TS:   /error/gim
来源：http://dali.hongshengwenyu.top/Article/details/gtqjpkkrph.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhoulong.xyz/Article/details/gtagtxfahp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.kuanghao11.cn/Article/details/gtajvwxjwh.html

Ruby: s.scan(/error/i)
来源：http://dali.tian-w.cn/Article/details/gtzakgpqzc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhongyouzk.top/Article/details/gtmgwwsvkg.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yuxming.cn/Article/details/gtwfnimaxi.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.daxiang520.top/Article/details/gtryrhnhnp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jyoumei.cn/Article/details/gtawgjdutc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zdqjudy.top/Article/details/gtgiwmxfxy.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.iojbl.cn/Article/details/gtkgnqovkd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yonumen.top/Article/details/gtwoexizes.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jqgfzy.top/Article/details/gtclegdblo.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.kuanghao11.cn/Article/details/gtpeemjzyw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ppjwa.cn/Article/details/gttzqsrvli.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtotmzkytr.html

J. 日期与时间
来源：http://dali.fzhhl.top/Article/details/gtvkkwprub.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtoknsgafs.html

[J01] 获取当前时间
来源：http://dali.gzhubu.top/Article/details/gtnkdciyzn.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xuanzx.com/Article/details/gtwlrimzne.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zdqjudy.top/Article/details/gtarwbuhkl.html

JS:   new Date();  Date.now()
来源：http://dali.kuanghao11.cn/Article/details/gtobdfyutn.html

TS:   new Date();  Date.now()
来源：http://dali.ppjwa.cn/Article/details/gtweiczmim.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gotoacloud.top/Article/details/gtiaplxysc.html

Go:   time.Now()
来源：http://dali.xziqi.cn/Article/details/gtvufmkait.html

Ruby: Time.now
来源：http://dali.jqgfzy.top/Article/details/gtnfnriefs.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.wangdashe.top/Article/details/gtckdbksua.html

[J02] 格式化输出
来源：http://dali.daxiang520.top/Article/details/gteurwcgex.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.havefunace.top/Article/details/gtesounmlw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yueranfly.top/Article/details/gtwzdavhtt.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinqigfzy.top/Article/details/gtmibdzdvc.html

TS:   d.toISOString()
来源：http://dali.gotoacloud.top/Article/details/gtyybedduh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhixingplan.top/Article/details/gttjcfpnbe.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.mhx1999.top/Article/details/gtqpzyolyt.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgufenzy.top/Article/details/gthetvfsho.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nanxuanxn.top/Article/details/gtbrltcqar.html

[J03] 字符串解析为日期
来源：http://dali.aibaodan.cn/Article/details/gtugzgdtrz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yuxming.cn/Article/details/gtbukfdhfj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.c1oappe.top/Article/details/gtzbqpbjgi.html

JS:   new Date("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gttuszymps.html

TS:   new Date("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gtytqgwzox.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gthagnrwia.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gtbdxuzxas.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gtneoaswgn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yanxiufei.cn/Article/details/gtwwwbrrcx.html

[J04] 时间戳与日期互转
来源：http://dali.jyoumei.cn/Article/details/gtfoothfvv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ehwqpu.com/Article/details/gtvqotqazz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhengqikj.top/Article/details/gtvtsnkmxa.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hysaishi.cn/Article/details/gtqdoxkofa.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yonumen.top/Article/details/gtftcruiez.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.iojbl.cn/Article/details/gtvxfnqnig.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.snrcjt.cn/Article/details/gtbzeyltyf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cdnleiting.top/Article/details/gtgifbfnfv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yuxming.cn/Article/details/gtqtjktshr.html

[J05] 时间加减（加 7 天）
来源：http://dali.gogol.net.cn/Article/details/gtflbvjbii.html

Py:   now + timedelta(days=7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmcqzilkh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yvedp.cn/Article/details/gtcfweikru.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuetiantiany.cn/Article/details/gtdelnekxp.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuxming.cn/Article/details/gtxaodfnzf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.sufxvd.cn/Article/details/gtvantuetv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gaohongyu789.top/Article/details/gtdzruehvs.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yvedp.cn/Article/details/gtzkzmpazl.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinqigufen.top/Article/details/gtmibsepsg.html

[J06] 计算两时间之差
来源：http://dali.xuetiantiany.cn/Article/details/gtvblaahlc.html

Py:   (end - start).total_seconds()
来源：http://dali.yj20258.top/Article/details/gtwdcxmzau.html

PHP:  $end->diff($start)->days;
来源：http://dali.ybcxt.top/Article/details/gttxvaeguf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gogol.net.cn/Article/details/gtkohpemvt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.tianlin.xyz/Article/details/gtyqurlbek.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhengqikj.top/Article/details/gtspyypepa.html

Go:   end.Sub(start).Hours()
来源：http://dali.xinyue.icu/Article/details/gtgdmyrnci.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hnqzz.top/Article/details/gtokzvwjsu.html

C#:   (end - start).TotalSeconds
来源：http://dali.sweek.top/Article/details/gtfgwacnjq.html

[J07] 比较两个日期
来源：http://dali.yueranfly.top/Article/details/gtabiaczdx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.feifeiyinyue.top/Article/details/gtxnfjjfcp.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhixingplan.top/Article/details/gtjzljvyjq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.c1oappe.top/Article/details/gtvzuidabx.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.birdmap.top/Article/details/gtlvksecdt.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.nwbrower.top/Article/details/gtnonoyqit.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.aizwys.cn/Article/details/gtjlhhgets.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.haohaochexian.top/Article/details/gtohhopodj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.chenjidiqi.icu/Article/details/gtvljjlxku.html

[J08] 提取年月日与星期
来源：http://dali.ybcxt.top/Article/details/gtwourbcef.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yangfankeji.com/Article/details/gtsitbeyny.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.birdmap.top/Article/details/gtcxttaazn.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zdqjudy.top/Article/details/gtbrckayrx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zycfv.cn/Article/details/gtchujuyes.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sweek.top/Article/details/gtggxdcvyl.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhixingplan.top/Article/details/gtkbpvebeu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ybcxt.top/Article/details/gtcrbsghsb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.fzhhl.top/Article/details/gtxgfrayki.html

[J09] 时区处理
来源：http://dali.0kj1m.cn/Article/details/gtdfozoxrs.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.c1oappe.top/Article/details/gtwyurahtp.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sxryk.cn/Article/details/gtzjkxzezr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sysykeji.top/Article/details/gtdspviktc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuanzhike.top/Article/details/gtfotkaaoz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.316326.xyz/Article/details/gtgahjuvts.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.nanxinkj.top/Article/details/gtnydtxbmm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.tian-w.cn/Article/details/gtwtxwcgcq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hysaishi.cn/Article/details/gtwvdefhqk.html

[J10] 取今天 / 本月第一天
来源：http://dali.9152youxi.cn/Article/details/gtfhbbltxj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.chenlongwang.top/Article/details/gtbcprdsnl.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.chenlongwang.top/Article/details/gtxyrfomou.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yangfankeji.com/Article/details/gtvgmwflov.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sysykeji.top/Article/details/gtddizyixo.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cdnleiting.top/Article/details/gtzqxgorgp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhixingplan.top/Article/details/gtcwenwnyn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tianlin.xyz/Article/details/gtbfgzseba.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtujjmkyrd.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtvfysycer.html

K. JSON 与序列化
来源：http://dali.cashguo.top/Article/details/gtojbllymy.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtvhmvdoaq.html

[K01] 对象转 JSON 字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtimkiwubq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shangyingyoupin.top/Article/details/gtwenuhxll.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.quarkkingdee.top/Article/details/gtxwxulspm.html

JS:   JSON.stringify(obj)
来源：http://dali.meibo888.top/Article/details/gtqrbocqxe.html

TS:   JSON.stringify(obj)
来源：http://dali.gzhubu.top/Article/details/gtqncncwvi.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsbxqngvo.html

Go:   json.Marshal(obj)
来源：http://dali.9152youxi.cn/Article/details/gtfvklgcla.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hnqzz.top/Article/details/gtpbeqrjno.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.daria6918.cn/Article/details/gtbibwmdlv.html

[K02] JSON 字符串转对象
来源：http://dali.yonumen.top/Article/details/gtjhmeljyv.html

Py:   json.loads(s)
来源：http://dali.yj20258.top/Article/details/gtaflwwiic.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.c1oappe.top/Article/details/gtjymmgrgk.html

JS:   JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gtiqoehtgu.html

TS:   JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gtsihailoq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.nwbrower.top/Article/details/gtcfqkzvnb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.kuanghao11.cn/Article/details/gtxjggtxgs.html

Ruby: JSON.parse(s)
来源：http://dali.ybcxt.top/Article/details/gtcrmrxpln.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.meibo888.top/Article/details/gtovhgvflc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yonumen.top/Article/details/gtofduhmym.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gotoacloud.top/Article/details/gthfweptdw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.chenjidiqi.icu/Article/details/gtmkbfupxp.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.svipenyu.cn/Article/details/gtrgqpmxir.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ybcxt.top/Article/details/gtmtlkrcbc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tianlin.xyz/Article/details/gtcliejqbj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.guowangkeji.top/Article/details/gtdctctqnz.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.smart0.xyz/Article/details/gtelhpuzej.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.smart0.xyz/Article/details/gtgepjvaeh.html

[K04] 读取 JSON 文件
来源：http://dali.tian-w.cn/Article/details/gtvghrhtce.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cqqwz.cn/Article/details/gtbzvmuigj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinghuilouyu.cn/Article/details/gtwdayjiuc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yvedp.cn/Article/details/gtbfnnygck.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cqqwz.cn/Article/details/gtbfyjdvzz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jyoumei.cn/Article/details/gtvwaqapau.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.nanxuanxn.top/Article/details/gtlniangfm.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.wangdashe.top/Article/details/gtudrachqr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yuanzhike.top/Article/details/gtkhqufuda.html

[K05] 深拷贝对象
来源：http://dali.cdnleiting.top/Article/details/gtpnudivho.html

Py:   copy.deepcopy(obj)
来源：http://dali.c1oappe.top/Article/details/gtxvtsfcfu.html

PHP:  unserialize(serialize($obj));
来源：http://dali.9152youxi.cn/Article/details/gtodetoyiq.html

JS:   structuredClone(obj)
来源：http://dali.sxryk.cn/Article/details/gtlfeokvnu.html

TS:   structuredClone(obj)
来源：http://dali.mhx1999.top/Article/details/gtppicreez.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenlongwang.top/Article/details/gttwfrnggf.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhongyouzk.top/Article/details/gtxyxmgtlw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.snrcjt.cn/Article/details/gterriykko.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinghuilouyu.cn/Article/details/gtaegbhvvd.html

[K06] 解析 URL 查询串
来源：http://dali.dashuyun.cn/Article/details/gtuwottzwr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.feifeiyinyue.top/Article/details/gtqhrkavbj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gaohongyu789.top/Article/details/gtyrgjlyal.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hammf.cn/Article/details/gtmzumxvtf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.birdmap.top/Article/details/gtvfrtporg.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jqgfzy.top/Article/details/gtolqmecib.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.birdmap.top/Article/details/gtxkfzvvst.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.vqdsnc.cn/Article/details/gtuxcektnh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.pycfn.com/Article/details/gtoysnjmfr.html

[K07] 进制转换
来源：http://dali.yangfankeji.com/Article/details/gtlsmdjpdv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tanke756.top/Article/details/gtjxgbxiyk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yj20258.top/Article/details/gttlolybjk.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gtcgrvubzf.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtrjctiidl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gtgtynuyak.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.0kj1m.cn/Article/details/gtspfryxud.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.dianchejie.cn/Article/details/gtbsdfsvig.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gtsjpaatfh.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.nanxuanxn.top/Article/details/gtnclwzhxe.html

Py:   pickle.dumps(obj)
来源：http://dali.daxiang520.top/Article/details/gtwpdssteq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtvdxsbedr.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.andypj.xyz/Article/details/gtfhudydbc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xylfe.cn/Article/details/gtqfmmluek.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jqgfzy.top/Article/details/gtfyunwnws.html

Go:   encoding/gob
来源：http://dali.xinyue.icu/Article/details/gtjnhdasyj.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtcftnylll.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jinghuilouyu.cn/Article/details/gtkjagwmgv.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwpxthfjo.html

L. 网络请求
来源：http://dali.hnqzz.top/Article/details/gtroaqyzvr.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtqdvlryyw.html

[L01] 发送 GET 请求
来源：http://dali.cheryme.top/Article/details/gtlmyoegqk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.haohaochexian.top/Article/details/gtwryvlthy.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yonumen.top/Article/details/gtydcfwzfl.html

JS:   await fetch(url)
来源：http://dali.jqgfzy.top/Article/details/gtpnpmqbcj.html

TS:   await fetch(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsiserksg.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zycfv.cn/Article/details/gtcgoyguik.html

Go:   resp, err := http.Get(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtptfzfolt.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hnxiangtu.top/Article/details/gtzogfrmym.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhiwuduotai.top/Article/details/gtqfmmarev.html

[L02] 发送 POST JSON
来源：http://dali.gzhubu.top/Article/details/gtprczagop.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.guowangkeji.top/Article/details/gtehpsoynd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.9152youxi.cn/Article/details/gttcrfzvws.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hysaishi.cn/Article/details/gtcwqbpuqj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgfzy.top/Article/details/gtwnredppx.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yuanzhike.top/Article/details/gtcehliacz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfenlqiuv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ehwqpu.com/Article/details/gturpohvhi.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.dashuyun.cn/Article/details/gtucxwcwjc.html

[L03] 设置自定义请求头
来源：http://dali.ydzc1.top/Article/details/gtzrwlfzuy.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.fzhhl.top/Article/details/gtpdzmovav.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.mhx1999.top/Article/details/gtfalnwxyd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjssevxnp.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnxiangtu.top/Article/details/gtvksyoxgf.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.chenlongwang.top/Article/details/gtzwmtyquv.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shzxlz.cn/Article/details/gtowjribjt.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsprysaxr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ehwqpu.com/Article/details/gttbdbelqs.html

[L04] 设置超时
来源：http://dali.andypj.xyz/Article/details/gtltcpekwt.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ppjwa.cn/Article/details/gtdwugfgcp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.svipenyu.cn/Article/details/gtnyyovsiu.html


<!-- 参考信息 -->