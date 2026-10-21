代发 wailian999

Ruby: e.message;  e.backtrace
来源：http://dali.cqqwz.cn/Article/details/gtvylcfdxm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ppjwa.cn/Article/details/gtdxtpzglu.html

[H09] 带错误码的异常
来源：http://dali.redwolf501.top/Article/details/gtrdhvlibb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.nanxuanxn.top/Article/details/gtbibrpvxw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ivvv.top/Article/details/gttytguheo.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ydzc1.top/Article/details/gtymxhigha.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jiagoushi.top/Article/details/gtxntsubju.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.bjfxy.top/Article/details/gttnnkfrtl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gzhubu.top/Article/details/gtrtozvgpd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.0kj1m.cn/Article/details/gthdwihtvm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ydzc1.top/Article/details/gtwsqashvc.html

[H10] 资源自动释放
来源：http://dali.iojbl.cn/Article/details/gtpwdcwzcc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.bjfxy.top/Article/details/gtwvkrethn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tanke756.top/Article/details/gtquhotlsm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangdashe.top/Article/details/gtaylvnisu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yanxiufei.cn/Article/details/gtzhwoguqa.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.vqdsnc.cn/Article/details/gtfndvyaoy.html

Go:   defer f.Close()
来源：http://dali.dashuyun.cn/Article/details/gtwfkdncpt.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.0kj1m.cn/Article/details/gtmiqvbwwx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hammf.cn/Article/details/gtpfsfeayn.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtzggkkecj.html

I. 正则表达式
来源：http://dali.yongpay.top/Article/details/gtpserdsde.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtespapuos.html

[I01] 判断是否匹配
来源：http://dali.gaohongyu789.top/Article/details/gtorodzbyn.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkxzwkyrk.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.meibo888.top/Article/details/gtyderparp.html

JS:   /\d+/.test(s)
来源：http://dali.0kj1m.cn/Article/details/gtllbrwweu.html

TS:   /\d+/.test(s)
来源：http://dali.shuidangran.top/Article/details/gtaoezbqwo.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jyoumei.cn/Article/details/gtvnnnffmd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hfpthk.cn/Article/details/gtjydncssp.html

Ruby: s.match?(/\d+/)
来源：http://dali.svipenyu.cn/Article/details/gtiktxglqs.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.9152youxi.cn/Article/details/gtnkgdspng.html

[I02] 提取所有匹配
来源：http://dali.jiagoushi.top/Article/details/gtleiqpvpg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.svipenyu.cn/Article/details/gtfogufadh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.0kj1m.cn/Article/details/gticcfysjh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shzxlz.cn/Article/details/gtqmdoqmyf.html

TS:   s.match(/\d+/g)
来源：http://dali.iojbl.cn/Article/details/gtfhxwxguf.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.pycfn.com/Article/details/gtdfcwmqbo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjczkqaat.html

Ruby: s.scan(/\d+/)
来源：http://dali.yvedp.cn/Article/details/gtynuokumo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinqigufen.top/Article/details/gtcffmjztl.html

[I03] 提取捕获分组
来源：http://dali.nwbrower.top/Article/details/gthnglnrpv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.aizwys.cn/Article/details/gtnegdlguz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhixingplan.top/Article/details/gtivflybqb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hnqzz.top/Article/details/gtnbloshok.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.tanke756.top/Article/details/gtfwjqznge.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yangfankeji.com/Article/details/gtsfcdysgk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhiwuduotai.top/Article/details/gtdalhkbja.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yj20258888.top/Article/details/gtirsvtbuc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.nanxinkj.top/Article/details/gtanniwthn.html

[I04] 正则替换
来源：http://dali.dianchejie.cn/Article/details/gtecgeygid.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinqigfzy.top/Article/details/gtereychor.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sufxvd.cn/Article/details/gtetuvlsym.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yuxming.cn/Article/details/gtnoacvewj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxuanxn.top/Article/details/gtjjfsbytc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xuanzx.com/Article/details/gtbcgydpbc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zdqjudy.top/Article/details/gtryemaqvp.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.kuanghao11.cn/Article/details/gtmwmofrob.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.nanxuanxn.top/Article/details/gtwtoofsnl.html

[I05] 按正则拆分
来源：http://dali.ydzc1.top/Article/details/gtczhrhmot.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hysaishi.cn/Article/details/gtsmlkeqcc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.svipenyu.cn/Article/details/gtztrnqccg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hywenlv.cn/Article/details/gtnmjrreqt.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hysaishi.cn/Article/details/gtataimges.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cheryme.top/Article/details/gtcdiysxaa.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jlsjyb.cn/Article/details/gtbqinnsld.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gtapadwrif.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.andypj.xyz/Article/details/gtrjxluhym.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ybcxt.top/Article/details/gtqgttvajx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xuetiantiany.cn/Article/details/gtzssnitqf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hywenlv.cn/Article/details/gtelfvjhmn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hywenlv.cn/Article/details/gtxyemcuwm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cqqwz.cn/Article/details/gtcpuwimlt.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.nanxinkj.top/Article/details/gtcmwihfvy.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.tanke756.top/Article/details/gtajyofuap.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.andypj.xyz/Article/details/gtssgyejzk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jyoumei.cn/Article/details/gtgactdyes.html

[I07] 忽略大小写与多行模式
来源：http://dali.nanxinkj.top/Article/details/gtdxlvyxib.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gotoacloud.top/Article/details/gtzajrusuz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ppjwa.cn/Article/details/gtiulmuvar.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.pengpengdd.cyou/Article/details/gtobianquv.html

TS:   /error/gim
来源：http://dali.cucudq.cn/Article/details/gtyzergien.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhixingplan.top/Article/details/gtocyxqxzt.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.c1oappe.top/Article/details/gtthlxzxbu.html

Ruby: s.scan(/error/i)
来源：http://dali.svipenyu.cn/Article/details/gtwgkgvppa.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbntmotcl.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtksqkgvvb.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.dianchejie.cn/Article/details/gtsbnanwnz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sweek.top/Article/details/gtrfecreeb.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sysykeji.top/Article/details/gtvydfjbah.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jiagoushi.top/Article/details/gtfwpvpqwa.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yongpay.top/Article/details/gtigtbqxbp.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gtabwetcyu.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hongshengwenyu.top/Article/details/gtyqifcxlg.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.pycfn.com/Article/details/gtvipzcfin.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtwgpcxxyp.html

J. 日期与时间
来源：http://dali.kuanghao11.cn/Article/details/gtiymzpcoq.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtemjbzhro.html

[J01] 获取当前时间
来源：http://dali.cucudq.cn/Article/details/gtspdokqdg.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xuetiantiany.cn/Article/details/gtebvpbwuw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sufxvd.cn/Article/details/gtemuxcypi.html

JS:   new Date();  Date.now()
来源：http://dali.xuanzx.com/Article/details/gteptsqntf.html

TS:   new Date();  Date.now()
来源：http://dali.yangfankeji.com/Article/details/gtleqikegn.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhixingplan.top/Article/details/gtiayetjwl.html

Go:   time.Now()
来源：http://dali.jianghu66.top/Article/details/gtthyscdic.html

Ruby: Time.now
来源：http://dali.guannengcc.top/Article/details/gtwkxctrbe.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yonumen.top/Article/details/gtitvhfgej.html

[J02] 格式化输出
来源：http://dali.hysaishi.cn/Article/details/gtmebibrlu.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.redwolf501.top/Article/details/gthucrrmzk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.fengsongda.top/Article/details/gtrnbmvmhq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthznkvixv.html

TS:   d.toISOString()
来源：http://dali.tianlin.xyz/Article/details/gtvzzkioah.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.snrcjt.cn/Article/details/gtacxsosgk.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhoulong.xyz/Article/details/gttgsrcsas.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfwgzpdqo.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhiwuduotai.top/Article/details/gtbcwnhnmk.html

[J03] 字符串解析为日期
来源：http://dali.aizwys.cn/Article/details/gtluubttoa.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cqqwz.cn/Article/details/gtourmdfjk.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj20258888.top/Article/details/gttgbagjbc.html

JS:   new Date("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gtkrbejlrb.html

TS:   new Date("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gtqyhxnxvh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gtzvkbpcku.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gtivujnvva.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfgijxfvk.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zycfv.cn/Article/details/gtxlrjewad.html

[J04] 时间戳与日期互转
来源：http://dali.chenzaomai.com/Article/details/gtcqvxtqjd.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xinyue.icu/Article/details/gtyjkatjnv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.0kj1m.cn/Article/details/gthkwlfmcf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.tian-w.cn/Article/details/gtwpzhtlel.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.redwolf501.top/Article/details/gtuyinttin.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gtpmkxojlj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinqigfzy.top/Article/details/gthgcpkjsv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aibaodan.cn/Article/details/gtubwkfbkp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.guannengcc.top/Article/details/gtenwvomat.html

[J05] 时间加减（加 7 天）
来源：http://dali.aibaodan.cn/Article/details/gtkfpeoxdf.html

Py:   now + timedelta(days=7)
来源：http://dali.meibo888.top/Article/details/gtmbnnekpb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gotoacloud.top/Article/details/gttdgokpki.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shuidangran.top/Article/details/gtpzimfakq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guowangkeji.top/Article/details/gtloxrhonx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhiwuduotai.top/Article/details/gtqqyiacpk.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.0kj1m.cn/Article/details/gtqrpybzfs.html

Ruby: Time.now + 7 * 86400
来源：http://dali.0kj1m.cn/Article/details/gtihewnixm.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.chenlongwang.top/Article/details/gtybsihrmo.html

[J06] 计算两时间之差
来源：http://dali.xuanzx.com/Article/details/gtnezsygdf.html

Py:   (end - start).total_seconds()
来源：http://dali.ivvv.top/Article/details/gtaogurmrg.html

PHP:  $end->diff($start)->days;
来源：http://dali.gogol.net.cn/Article/details/gtncuaztwk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhijiandao.cn/Article/details/gtlmgtoiuv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.316326.xyz/Article/details/gtowhueubc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinghuilouyu.cn/Article/details/gtonsdbumw.html

Go:   end.Sub(start).Hours()
来源：http://dali.xylfe.cn/Article/details/gthjtmrpba.html

Ruby: end - start                 # 返回秒数
来源：http://dali.aibaodan.cn/Article/details/gtpnlkoegf.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj20258.top/Article/details/gtkojeizyb.html

[J07] 比较两个日期
来源：http://dali.pycfn.com/Article/details/gtswkenhae.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gtbmyamgpq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhixingplan.top/Article/details/gtlmorauzo.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.0kj1m.cn/Article/details/gtbdkkqwfp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yanxiufei.cn/Article/details/gtrlwaahyq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.aibaodan.cn/Article/details/gtebwjznob.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.feifeiyinyue.top/Article/details/gtkavzpiqz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.mhx1999.top/Article/details/gtuhsznxwb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gtvslmvnas.html

[J08] 提取年月日与星期
来源：http://dali.zdqjudy.top/Article/details/gtpksesymn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hammf.cn/Article/details/gtjfbxiwob.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.quarkkingdee.top/Article/details/gtwmhpqpjh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinqigufen.top/Article/details/gttniccoag.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shuidangran.top/Article/details/gtmrzxbllg.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shzxlz.cn/Article/details/gthqwgnzvv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.wangdashe.top/Article/details/gtxnfohvxk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.haohaochexian.top/Article/details/gtjwfpobgf.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nanxuanxn.top/Article/details/gtakfefjqt.html

[J09] 时区处理
来源：http://dali.smart0.xyz/Article/details/gtwlfjbnfu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zycfv.cn/Article/details/gtmlgluhqz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.daxiang520.top/Article/details/gtmwsbykrl.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhongyouzk.top/Article/details/gtvzgihcyj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrpyfepzh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.guowangkeji.top/Article/details/gtjoehdkyx.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.316326.xyz/Article/details/gtoigifuzx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shangyingyoupin.top/Article/details/gtpxolihou.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.316326.xyz/Article/details/gtalyxocgx.html

[J10] 取今天 / 本月第一天
来源：http://dali.ivvv.top/Article/details/gtydpgiegv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.daria6918.cn/Article/details/gtdklvhlqv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nwbrower.top/Article/details/gtnlvodzfu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.aibaodan.cn/Article/details/gtvfkdtbme.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jqgufenzy.top/Article/details/gttsfxjcwa.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.fzhhl.top/Article/details/gtfqaxkcsj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.svipenyu.cn/Article/details/gtlrahlwvy.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhiwuduotai.top/Article/details/gtpnmzsjtu.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtcunagfon.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtfwlcuwbj.html

K. JSON 与序列化
来源：http://dali.aizwys.cn/Article/details/gtgaeyadrw.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtxjymwdqm.html

[K01] 对象转 JSON 字符串
来源：http://dali.jqgufenzy.top/Article/details/gtlcgvgulw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gogol.net.cn/Article/details/gtclfpzmrt.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hongshengwenyu.top/Article/details/gtdspizxue.html

JS:   JSON.stringify(obj)
来源：http://dali.guannengcc.top/Article/details/gtkvgihacz.html

TS:   JSON.stringify(obj)
来源：http://dali.redwolf501.top/Article/details/gtjarwhmjo.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xinyue.icu/Article/details/gtovkzhrmv.html

Go:   json.Marshal(obj)
来源：http://dali.cdnleiting.top/Article/details/gtardtnxgj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sxryk.cn/Article/details/gttjvtvtcy.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtunxcucfd.html

[K02] JSON 字符串转对象
来源：http://dali.yanxiufei.cn/Article/details/gtvbsfkukg.html

Py:   json.loads(s)
来源：http://dali.yvedp.cn/Article/details/gtovuunlhp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jiagoushi.top/Article/details/gtdvwnyrko.html

JS:   JSON.parse(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtywifxtju.html

TS:   JSON.parse(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtsgjowfsr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.birdmap.top/Article/details/gtutqjgmvk.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.chenlongwang.top/Article/details/gtvmjelwkj.html

Ruby: JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gtdpcejkvj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.haohaochexian.top/Article/details/gtvuqsivip.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.bjfxy.top/Article/details/gtuqmgpsrz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhongyouzk.top/Article/details/gtfskzhwcw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbdoybpcv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cucudq.cn/Article/details/gtkfemsdph.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.quarkkingdee.top/Article/details/gtjtoaawst.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.aizwys.cn/Article/details/gtrjrgeisp.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hfpthk.cn/Article/details/gtbxhfcxli.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtjkllzjcm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.birdmap.top/Article/details/gtrfxsndef.html

[K04] 读取 JSON 文件
来源：http://dali.chenzaomai.com/Article/details/gtlrgeixcq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jqgufenzy.top/Article/details/gtfionfbzb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.kuanghao11.cn/Article/details/gtxriwucsv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ehwqpu.com/Article/details/gtrutkugux.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jyoumei.cn/Article/details/gtxuyhzabh.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yuxming.cn/Article/details/gtcxvdecpg.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinqigufen.top/Article/details/gtuyeofquy.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yuanzhike.top/Article/details/gtjjmedvnb.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.meibo888.top/Article/details/gttgtiabam.html

[K05] 深拷贝对象
来源：http://dali.aizwys.cn/Article/details/gtwcvnrbaq.html

Py:   copy.deepcopy(obj)
来源：http://dali.andypj.xyz/Article/details/gtpddwjzop.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinghuilouyu.cn/Article/details/gtafcovitd.html

JS:   structuredClone(obj)
来源：http://dali.sysykeji.top/Article/details/gtvsliatrx.html

TS:   structuredClone(obj)
来源：http://dali.jinqigufen.top/Article/details/gtbsytesqb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hfpthk.cn/Article/details/gtnbmmvbbe.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhiwuduotai.top/Article/details/gtanrbtuyo.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xuanzx.com/Article/details/gtgwemijjj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.daria6918.cn/Article/details/gtiqqxdmkz.html

[K06] 解析 URL 查询串
来源：http://dali.hywenlv.cn/Article/details/gthzyhuqrw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.tianlin.xyz/Article/details/gtqkrzmvsl.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cdnleiting.top/Article/details/gttflgqftv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.mhx1999.top/Article/details/gthjeopsmf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cdnleiting.top/Article/details/gttbhmleda.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yuanzhike.top/Article/details/gtrsaarapk.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gtkkxkiavs.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xuanzx.com/Article/details/gtwgbobsik.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ydzc1.top/Article/details/gtqjtjzwfb.html

[K07] 进制转换
来源：http://dali.bjfxy.top/Article/details/gthihoewmf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gtuvyeqxtu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hfpthk.cn/Article/details/gtvujjhftp.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gtysdfduub.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yj202588.top/Article/details/gtowhpoxfe.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gtkalgdgqh.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhoulong.xyz/Article/details/gtsxsywbzp.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.feifeiyinyue.top/Article/details/gtsqhrobwa.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gtsyijowun.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.tian-w.cn/Article/details/gtktuydehh.html

Py:   pickle.dumps(obj)
来源：http://dali.guowangkeji.top/Article/details/gtmifezzkk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nanxuanxn.top/Article/details/gtbwsfgkvb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.dianchejie.cn/Article/details/gtqkbectde.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gzhubu.top/Article/details/gtomikvvkp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenlongwang.top/Article/details/gtbgxebwlq.html

Go:   encoding/gob
来源：http://dali.yanxiufei.cn/Article/details/gtaxxuhgmo.html

Ruby: Marshal.dump(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtlsonycej.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.316326.xyz/Article/details/gtqnrmbcfh.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gthnzmvwzn.html

L. 网络请求
来源：http://dali.cdnleiting.top/Article/details/gtqrwfjggs.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtycvuvmxx.html

[L01] 发送 GET 请求
来源：http://dali.tanke756.top/Article/details/gtiysnkjge.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ybcxt.top/Article/details/gtktfqvkqy.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.0kj1m.cn/Article/details/gtdueuadhj.html

JS:   await fetch(url)
来源：http://dali.shuidangran.top/Article/details/gtbqantbke.html

TS:   await fetch(url)
来源：http://dali.chenjidiqi.icu/Article/details/gttpvqlgbt.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.guannengcc.top/Article/details/gtyrfglrid.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gtaqiclogc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yangfankeji.com/Article/details/gtryiioroh.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.birdmap.top/Article/details/gtprjmchyt.html

[L02] 发送 POST JSON
来源：http://dali.zdqjudy.top/Article/details/gtfperpflx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhixingplan.top/Article/details/gtriolrfzu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xinyue.icu/Article/details/gtoqydcoey.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pengpengdd.cyou/Article/details/gtvecsfzec.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigufen.top/Article/details/gtslxxiecq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.pycfn.com/Article/details/gtwtbjrang.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.havefunace.top/Article/details/gtqrtospoc.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.guannengcc.top/Article/details/gtxzaxhkgh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtgojkwyvl.html

[L03] 设置自定义请求头
来源：http://dali.ehwqpu.com/Article/details/gtgzjthrtk.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xylfe.cn/Article/details/gtjzrjwkzk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhiwuduotai.top/Article/details/gtgfyczfvd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxinkj.top/Article/details/gtesimpkbl.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangdashe.top/Article/details/gtnvyxgrwg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.dianchejie.cn/Article/details/gtjbzroeat.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jinqigfzy.top/Article/details/gtalmtmnhy.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.316326.xyz/Article/details/gtakeksnhh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cdnleiting.top/Article/details/gtvckcvzsm.html

[L04] 设置超时
来源：http://dali.zdqjudy.top/Article/details/gtputeiunv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.smart0.xyz/Article/details/gtnsfsqdrp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.snrcjt.cn/Article/details/gtwtttkvbm.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cucudq.cn/Article/details/gtkpcitvcf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.kuanghao11.cn/Article/details/gtumncgatb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.fengsongda.top/Article/details/gtxbghvqmh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gogol.net.cn/Article/details/gtamgogqed.html


<!-- 参考信息 -->