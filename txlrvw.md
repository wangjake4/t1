代发 wailian999

C#:   Debug.Assert(x > 0);
来源：http://dali.nanxinkj.top/Article/details/gttjenobrh.html

[H08] 获取错误信息与堆栈
来源：http://dali.hammf.cn/Article/details/gtpetmikjm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cashguo.top/Article/details/gtrtumpxgp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.svipenyu.cn/Article/details/gthvbtwpto.html

JS:   e.message;  e.stack
来源：http://dali.yonumen.top/Article/details/gtgdvqvitm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ehwqpu.com/Article/details/gtbziesdmg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jiagoushi.top/Article/details/gtijimdtid.html

Go:   err.Error()
来源：http://dali.yj20258888.top/Article/details/gtshajarlb.html

Ruby: e.message;  e.backtrace
来源：http://dali.yonumen.top/Article/details/gtqgygfsld.html

C#:   e.Message;  e.StackTrace
来源：http://dali.dashuyun.cn/Article/details/gtmwimnbpx.html

[H09] 带错误码的异常
来源：http://dali.redwolf501.top/Article/details/gtkugfsnrq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gaohongyu789.top/Article/details/gtxififlmv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hongshengwenyu.top/Article/details/gtqwnuwgtf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinghuilouyu.cn/Article/details/gtgpxieeyi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sxryk.cn/Article/details/gtkaxphtei.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yj202588.top/Article/details/gtzxxfmztd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yonumen.top/Article/details/gtefnbuexu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xinyue.icu/Article/details/gtfolrprbi.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hongshengwenyu.top/Article/details/gtlondzbdc.html

[H10] 资源自动释放
来源：http://dali.wangshuangyany.cn/Article/details/gtpvkzblqq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.nwbrower.top/Article/details/gtydyhqial.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gtnzwzcqva.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ppjwa.cn/Article/details/gtyopwskyx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pengpengdd.cyou/Article/details/gtimzpavcj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.tian-w.cn/Article/details/gtlksxvdgl.html

Go:   defer f.Close()
来源：http://dali.sxryk.cn/Article/details/gtdfudioud.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.gaohongyu789.top/Article/details/gtugwifzrv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtqddgxyfh.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtbavmfmip.html

I. 正则表达式
来源：http://dali.feifeiyinyue.top/Article/details/gtxwmqsccw.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtrcxethjf.html

[I01] 判断是否匹配
来源：http://dali.hywenlv.cn/Article/details/gthyrptzrp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.mhx1999.top/Article/details/gtsyiqwrju.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yangfankeji.com/Article/details/gtkjndlxts.html

JS:   /\d+/.test(s)
来源：http://dali.jiagoushi.top/Article/details/gtgstnscfv.html

TS:   /\d+/.test(s)
来源：http://dali.zycfv.cn/Article/details/gtxckhdsof.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gthwcdkluh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yanxiufei.cn/Article/details/gtjppypvlb.html

Ruby: s.match?(/\d+/)
来源：http://dali.sufxvd.cn/Article/details/gthomfpypz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.havefunace.top/Article/details/gtcaptkwng.html

[I02] 提取所有匹配
来源：http://dali.9152youxi.cn/Article/details/gtyzzmlwtf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xziqi.cn/Article/details/gtgkynhrlp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xylfe.cn/Article/details/gtmwpdqhrj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yueranfly.top/Article/details/gtvtluanis.html

TS:   s.match(/\d+/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxlgjjeon.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.c1oappe.top/Article/details/gtskkrpbsy.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.guowangkeji.top/Article/details/gtdcbdkdtz.html

Ruby: s.scan(/\d+/)
来源：http://dali.pengpengdd.cyou/Article/details/gtquvepoit.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtkhiwtesc.html

[I03] 提取捕获分组
来源：http://dali.aizwys.cn/Article/details/gtsdllijcr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.316326.xyz/Article/details/gtoxekspne.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hammf.cn/Article/details/gtszjuqlof.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.fzhhl.top/Article/details/gtoafnaksl.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cqqwz.cn/Article/details/gtedzsslzi.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.dashuyun.cn/Article/details/gtsikkenmy.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.kuanghao11.cn/Article/details/gtpeidptln.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jiagoushi.top/Article/details/gthuwrnlgz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhixingplan.top/Article/details/gtegkvlkww.html

[I04] 正则替换
来源：http://dali.xuanzx.com/Article/details/gtsxoyfytp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yuanzhike.top/Article/details/gtccxodglz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jyoumei.cn/Article/details/gtwamhltwf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gtemaqnnbf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtunhwihxe.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cashguo.top/Article/details/gtosqnqral.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cheryme.top/Article/details/gtjrnliymk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xuanzx.com/Article/details/gtnryienxd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zycfv.cn/Article/details/gtjamfztkf.html

[I05] 按正则拆分
来源：http://dali.0kj1m.cn/Article/details/gtgpetkpck.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hongshengwenyu.top/Article/details/gtpphgfcfk.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jiagoushi.top/Article/details/gtwpyahkbf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.daria6918.cn/Article/details/gtwzsoswjj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shzxlz.cn/Article/details/gttutfvqfy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xziqi.cn/Article/details/gtplwnbqdf.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sysykeji.top/Article/details/gtiovzrsqh.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sysykeji.top/Article/details/gtvszcybdg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.pycfn.com/Article/details/gttmjuhgyq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hongshengwenyu.top/Article/details/gtzlnijmuh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yangfankeji.com/Article/details/gtwfuzmwvq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yvedp.cn/Article/details/gteerwclki.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.andypj.xyz/Article/details/gtethfqctg.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcblkslno.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gaohongyu789.top/Article/details/gtluuegvbv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhixingplan.top/Article/details/gtcyhycmrd.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.vqdsnc.cn/Article/details/gtjbechave.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sxryk.cn/Article/details/gthbyzmcvu.html

[I07] 忽略大小写与多行模式
来源：http://dali.redwolf501.top/Article/details/gtyhntwoie.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.guowangkeji.top/Article/details/gtjyjierac.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yuxming.cn/Article/details/gtfwztoqqc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jiagoushi.top/Article/details/gtmtlpnhcb.html

TS:   /error/gim
来源：http://dali.dianchejie.cn/Article/details/gtfevlslrs.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jlsjyb.cn/Article/details/gtdlyzozxi.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.c1oappe.top/Article/details/gtlkmbhzhc.html

Ruby: s.scan(/error/i)
来源：http://dali.316326.xyz/Article/details/gtsspeypzb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.316326.xyz/Article/details/gtgfpcupcs.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yj202588.top/Article/details/gtyqmafvjs.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yuanzhike.top/Article/details/gtwpirdwtl.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yueranfly.top/Article/details/gtfxstrrqd.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangdashe.top/Article/details/gtyzbaxxmg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.bjfxy.top/Article/details/gtxipujwbd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yanxiufei.cn/Article/details/gtfovwwzev.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yj202588.top/Article/details/gtiderqvyq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cqqwz.cn/Article/details/gtkjfnzybn.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sufxvd.cn/Article/details/gtchtepcbs.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtklrwultm.html

J. 日期与时间
来源：http://dali.feifeiyinyue.top/Article/details/gtgatuxgap.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtuxnalfga.html

[J01] 获取当前时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjarztndi.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinqigufen.top/Article/details/gtdimeoflv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.svipenyu.cn/Article/details/gtbyjuligl.html

JS:   new Date();  Date.now()
来源：http://dali.chenzaomai.com/Article/details/gtreaoohqy.html

TS:   new Date();  Date.now()
来源：http://dali.jlsjyb.cn/Article/details/gtfsvxadjt.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gotoacloud.top/Article/details/gtnvtisypj.html

Go:   time.Now()
来源：http://dali.meibo888.top/Article/details/gtdrxqsedz.html

Ruby: Time.now
来源：http://dali.iojbl.cn/Article/details/gtdcpmmiae.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gogol.net.cn/Article/details/gtxxnunyck.html

[J02] 格式化输出
来源：http://dali.aibaodan.cn/Article/details/gtkllyftjb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pengpengdd.cyou/Article/details/gtbstwreti.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yuanzhike.top/Article/details/gtxttwiuvq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.bjfxy.top/Article/details/gtpazwljmm.html

TS:   d.toISOString()
来源：http://dali.chenzaomai.com/Article/details/gtbuhrshcn.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhijiandao.cn/Article/details/gtsrguhwft.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.feifeiyinyue.top/Article/details/gtiffchbvj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hfpthk.cn/Article/details/gtfgrsxvlb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cashguo.top/Article/details/gthppdweuj.html

[J03] 字符串解析为日期
来源：http://dali.gzhubu.top/Article/details/gtwuterihr.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hammf.cn/Article/details/gtsboaqxbs.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xuetiantiany.cn/Article/details/gtcwsbegja.html

JS:   new Date("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gttcwtsljr.html

TS:   new Date("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gtrkdvxpze.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gtkmrbhgky.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gtxxldckws.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gtcrdmkzgy.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhixingplan.top/Article/details/gtjbghhffv.html

[J04] 时间戳与日期互转
来源：http://dali.yvedp.cn/Article/details/gtsznndlbb.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.chenzaomai.com/Article/details/gtqssedunw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.wangshuangyany.cn/Article/details/gtjtkvwpzd.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.vqdsnc.cn/Article/details/gtofazsvcj.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.fengsongda.top/Article/details/gtqjiyebnv.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.snrcjt.cn/Article/details/gtbhycjjci.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.wangdashe.top/Article/details/gtxkunpjle.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gttkokkusa.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.dashuyun.cn/Article/details/gtnppttmva.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgvqfiinn.html

Py:   now + timedelta(days=7)
来源：http://dali.zhengqikj.top/Article/details/gtkghdjvqo.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jqgufenzy.top/Article/details/gtwmufmgjm.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.redwolf501.top/Article/details/gtalpawwys.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.kuanghao11.cn/Article/details/gtuezzmyis.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jlsjyb.cn/Article/details/gtkmrhmppc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cqqwz.cn/Article/details/gtutwipjwu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sweek.top/Article/details/gtzxozrcmg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jiagoushi.top/Article/details/gtjflmvbaz.html

[J06] 计算两时间之差
来源：http://dali.ehwqpu.com/Article/details/gtwhpzpetb.html

Py:   (end - start).total_seconds()
来源：http://dali.kuanghao11.cn/Article/details/gtxzxymiiu.html

PHP:  $end->diff($start)->days;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtekdzqfnk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.nwbrower.top/Article/details/gtxapnorid.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gotoacloud.top/Article/details/gtcplciauh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yangfankeji.com/Article/details/gtglvaaraw.html

Go:   end.Sub(start).Hours()
来源：http://dali.aibaodan.cn/Article/details/gtvilgsjuh.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gogol.net.cn/Article/details/gtjxfvtksv.html

C#:   (end - start).TotalSeconds
来源：http://dali.fzhhl.top/Article/details/gtvbypdsgw.html

[J07] 比较两个日期
来源：http://dali.cheryme.top/Article/details/gtjpxvyjlg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzpyhjsnd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.feifeiyinyue.top/Article/details/gtkyclczjw.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hammf.cn/Article/details/gthhsydfzs.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hammf.cn/Article/details/gtbektoxcd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.0kj1m.cn/Article/details/gtfgpisqtl.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.daxiang520.top/Article/details/gtjeqcxcid.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xinyue.icu/Article/details/gtuadsmlgn.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hongshengwenyu.top/Article/details/gtkppapzri.html

[J08] 提取年月日与星期
来源：http://dali.hfpthk.cn/Article/details/gtsvdyjxaa.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yonumen.top/Article/details/gtrvwrpybh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hammf.cn/Article/details/gtxpdkfngc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.0kj1m.cn/Article/details/gtrfhvypvq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hfpthk.cn/Article/details/gtdkjtbohi.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.tian-w.cn/Article/details/gtvwupjvro.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.tianlin.xyz/Article/details/gtbaplvaoy.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.aibaodan.cn/Article/details/gtkyqwdech.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jiagoushi.top/Article/details/gtedeexpbv.html

[J09] 时区处理
来源：http://dali.bjfxy.top/Article/details/gtuifllppm.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.daria6918.cn/Article/details/gtctamckgl.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.smart0.xyz/Article/details/gtvqopacfa.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.meibo888.top/Article/details/gtmhtsvkfi.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yonumen.top/Article/details/gtehkqswiq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nanxinkj.top/Article/details/gttxizbqvc.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yueranfly.top/Article/details/gtzeaoaljg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jlsjyb.cn/Article/details/gteclbbvoy.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhoulong.xyz/Article/details/gtsulnznyi.html

[J10] 取今天 / 本月第一天
来源：http://dali.jiagoushi.top/Article/details/gtuvsrglhi.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.meibo888.top/Article/details/gtgprzkocr.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gogol.net.cn/Article/details/gtrwgrmtsc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.haohaochexian.top/Article/details/gtruecpbvi.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ybcxt.top/Article/details/gturxpdnrk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sxryk.cn/Article/details/gtmxnljuuy.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sysykeji.top/Article/details/gtchbqijpf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxaqpeczs.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xziqi.cn/Article/details/gteqmhevjt.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtnxjbnnuk.html

K. JSON 与序列化
来源：http://dali.redwolf501.top/Article/details/gtfziqfaqz.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gteuwfmcos.html

[K01] 对象转 JSON 字符串
来源：http://dali.cashguo.top/Article/details/gtykpqhsse.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cucudq.cn/Article/details/gtppsskafx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.kuanghao11.cn/Article/details/gtlfpzcjmc.html

JS:   JSON.stringify(obj)
来源：http://dali.jianghu66.top/Article/details/gtdyicwxyl.html

TS:   JSON.stringify(obj)
来源：http://dali.yj202588.top/Article/details/gtxysagavk.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yvedp.cn/Article/details/gtmhhwvfbl.html

Go:   json.Marshal(obj)
来源：http://dali.yonumen.top/Article/details/gtnvsxdacf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hfpthk.cn/Article/details/gtfwfydhce.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbncmsolj.html

[K02] JSON 字符串转对象
来源：http://dali.hammf.cn/Article/details/gtbiuollph.html

Py:   json.loads(s)
来源：http://dali.nanxuanxn.top/Article/details/gtugkkrlqz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sysykeji.top/Article/details/gtfcixrkkn.html

JS:   JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gtlpsroopw.html

TS:   JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtzsdmmrqp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yvedp.cn/Article/details/gtplysobhe.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gogol.net.cn/Article/details/gtmoeszdwr.html

Ruby: JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gtwgwumfjp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.nanxinkj.top/Article/details/gtkeuampum.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yonumen.top/Article/details/gtqpgwmwof.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.aibaodan.cn/Article/details/gtsxuuaxny.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.birdmap.top/Article/details/gtiyiksikb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtptezbwdz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.snrcjt.cn/Article/details/gtnmpbqcqh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hysaishi.cn/Article/details/gtyxmguaou.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hfpthk.cn/Article/details/gthnyvwmpf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shuidangran.top/Article/details/gtvtqgjryu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.chenjidiqi.icu/Article/details/gtuboriwli.html

[K04] 读取 JSON 文件
来源：http://dali.bjfxy.top/Article/details/gtuodoyzur.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.daria6918.cn/Article/details/gtvdarokuo.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.aizwys.cn/Article/details/gthomoatsi.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cheryme.top/Article/details/gtghxguefm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guowangkeji.top/Article/details/gtfyudezmr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xuetiantiany.cn/Article/details/gtnwmywwil.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gogol.net.cn/Article/details/gtrtbtogcq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.aizwys.cn/Article/details/gtzgcizuiu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cucudq.cn/Article/details/gtqrbzjxvm.html

[K05] 深拷贝对象
来源：http://dali.quarkkingdee.top/Article/details/gtnzevubmr.html

Py:   copy.deepcopy(obj)
来源：http://dali.ydzc1.top/Article/details/gtfxtpytxm.html

PHP:  unserialize(serialize($obj));
来源：http://dali.daria6918.cn/Article/details/gtlrcvyggo.html

JS:   structuredClone(obj)
来源：http://dali.smart0.xyz/Article/details/gtnsfrgisr.html

TS:   structuredClone(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtibjqlqbd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hongshengwenyu.top/Article/details/gtrijhjkbj.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gzhubu.top/Article/details/gtwqdwwuua.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.fengsongda.top/Article/details/gtctjecqwc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtajoizglj.html

[K06] 解析 URL 查询串
来源：http://dali.hywenlv.cn/Article/details/gtyzmotulv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shanyushiyangtech.top/Article/details/gtfypjfytx.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.bjfxy.top/Article/details/gtgtzopuai.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cdnleiting.top/Article/details/gtuyjvovlf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenlongwang.top/Article/details/gtqxnysxkf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhoulong.xyz/Article/details/gtshwdngrc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gtykhpkqlg.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shzxlz.cn/Article/details/gtzsprkdae.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jianghu66.top/Article/details/gtmxfxefdx.html

[K07] 进制转换
来源：http://dali.feifeiyinyue.top/Article/details/gtxqyqilrt.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gtlftnansw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ehwqpu.com/Article/details/gtsxgzzumb.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gtjkfqwbff.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzcumbyei.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gtuvbgaznz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jqgfzy.top/Article/details/gteltbxulj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.snrcjt.cn/Article/details/gtbmwrolrj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gtkxzpagla.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gtzbhocubv.html

Py:   pickle.dumps(obj)
来源：http://dali.zhoulong.xyz/Article/details/gttqnohhtu.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shzxlz.cn/Article/details/gtorznvotk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xuetiantiany.cn/Article/details/gtybinzrls.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.nanxuanxn.top/Article/details/gtiqiryaok.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jqgfzy.top/Article/details/gtvcrvunxl.html

Go:   encoding/gob
来源：http://dali.ydzc1.top/Article/details/gtklzhrwpc.html

Ruby: Marshal.dump(obj)
来源：http://dali.haohaochexian.top/Article/details/gtwcvbatoz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shangyingyoupin.top/Article/details/gtgwpuzjcr.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtqoykamky.html

L. 网络请求
来源：http://dali.ivvv.top/Article/details/gtdtycwljl.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtrznvxdch.html

[L01] 发送 GET 请求
来源：http://dali.zdqjudy.top/Article/details/gtpwqypzua.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cdnleiting.top/Article/details/gtqyjerazf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nwbrower.top/Article/details/gtkqnaljym.html

JS:   await fetch(url)
来源：http://dali.sufxvd.cn/Article/details/gtgvijtnon.html

TS:   await fetch(url)
来源：http://dali.aibaodan.cn/Article/details/gtdjanaans.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.quarkkingdee.top/Article/details/gtqrabzjma.html

Go:   resp, err := http.Get(url)
来源：http://dali.yj20258888.top/Article/details/gtqlxfayss.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xinyue.icu/Article/details/gtdybwgxcc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.aibaodan.cn/Article/details/gtiogrwavh.html

[L02] 发送 POST JSON
来源：http://dali.gzhubu.top/Article/details/gtbvbikube.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jyoumei.cn/Article/details/gtinbwwodo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jqgufenzy.top/Article/details/gtgorboihi.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmwdvmuzn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yonumen.top/Article/details/gtghavdcsn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.bjfxy.top/Article/details/gtdqytlnya.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shuidangran.top/Article/details/gtzvswsfbe.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xuetiantiany.cn/Article/details/gtqosnwyuc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sweek.top/Article/details/gtbjpmposi.html

[L03] 设置自定义请求头
来源：http://dali.haohaochexian.top/Article/details/gtsivgaqvn.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jyoumei.cn/Article/details/gtkyoiidpq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwbluqptl.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.iojbl.cn/Article/details/gthaqxbzfc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cheryme.top/Article/details/gtneowujhu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhixingplan.top/Article/details/gthiwgqknf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cucudq.cn/Article/details/gtafqsrxml.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.havefunace.top/Article/details/gthqlksfhz.html


<!-- 参考信息 -->