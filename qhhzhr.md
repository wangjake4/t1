代发 wailian999

TS:   console.assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gtxphjnrxl.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jianghu66.top/Article/details/gtspsxrvcj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jiagoushi.top/Article/details/gtozdnaqre.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.wangshuangyany.cn/Article/details/gtvldbaryb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yangfankeji.com/Article/details/gthsepakgg.html

[H08] 获取错误信息与堆栈
来源：http://dali.ppjwa.cn/Article/details/gtelnurtvu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ehwqpu.com/Article/details/gtqstocykl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.redwolf501.top/Article/details/gtaezlpotr.html

JS:   e.message;  e.stack
来源：http://dali.zdqjudy.top/Article/details/gtxhgnrpyp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gogol.net.cn/Article/details/gtugkemylw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hongshengwenyu.top/Article/details/gtapwigcdt.html

Go:   err.Error()
来源：http://dali.fzhhl.top/Article/details/gtqblxbmju.html

Ruby: e.message;  e.backtrace
来源：http://dali.smart0.xyz/Article/details/gtjhgaasff.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yongpay.top/Article/details/gtobansjdp.html

[H09] 带错误码的异常
来源：http://dali.yj202588.top/Article/details/gtsoxeuusw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.9152youxi.cn/Article/details/gtqculzxon.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.havefunace.top/Article/details/gtsurxiqan.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.tian-w.cn/Article/details/gtmfoxijvu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yueranfly.top/Article/details/gtmqtdrhwq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xinyue.icu/Article/details/gtiruropoy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jqgufenzy.top/Article/details/gtkzfqpogn.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ppjwa.cn/Article/details/gtyewqeowz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.nanxuanxn.top/Article/details/gtnuywivhr.html

[H10] 资源自动释放
来源：http://dali.jqgfzy.top/Article/details/gtlpbljwqp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xinyue.icu/Article/details/gtccpduhul.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.nwbrower.top/Article/details/gtxcjzwpij.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrlkntkmm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.meibo888.top/Article/details/gtyvdlqgux.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.aibaodan.cn/Article/details/gtuiikaalh.html

Go:   defer f.Close()
来源：http://dali.shzxlz.cn/Article/details/gtfbsgfhco.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.vqdsnc.cn/Article/details/gtdlbflkwd.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtthbwrxms.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtcfsfwmts.html

I. 正则表达式
来源：http://dali.shuidangran.top/Article/details/gtijwfjuon.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtmzefpxnp.html

[I01] 判断是否匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrqkfjbei.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cheryme.top/Article/details/gtunoukprn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zdqjudy.top/Article/details/gtvwfydnhg.html

JS:   /\d+/.test(s)
来源：http://dali.tianlin.xyz/Article/details/gtgiqpmjfu.html

TS:   /\d+/.test(s)
来源：http://dali.yueranfly.top/Article/details/gtfqjsnlcw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.meibo888.top/Article/details/gtkvplzgnn.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shzxlz.cn/Article/details/gtgngtntug.html

Ruby: s.match?(/\d+/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbtrpmxgv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtelsykehq.html

[I02] 提取所有匹配
来源：http://dali.zhoulong.xyz/Article/details/gtuegvxlqx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xinyue.icu/Article/details/gtfxenwwfb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shuidangran.top/Article/details/gtebjvvwki.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yueranfly.top/Article/details/gtxstvfdwz.html

TS:   s.match(/\d+/g)
来源：http://dali.sxryk.cn/Article/details/gtodlfznxw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtcqbejbbj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.kuanghao11.cn/Article/details/gtdwmogzbr.html

Ruby: s.scan(/\d+/)
来源：http://dali.wangshuangyany.cn/Article/details/gtgmfsqdyh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gotoacloud.top/Article/details/gtpmknmdpl.html

[I03] 提取捕获分组
来源：http://dali.jiagoushi.top/Article/details/gtgcqchrro.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yongpay.top/Article/details/gtvyflylzm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.dashuyun.cn/Article/details/gtfiwzicye.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhixingplan.top/Article/details/gtlzmtylni.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaverxpzd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sysykeji.top/Article/details/gtwigcedft.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sxryk.cn/Article/details/gtfpevekkp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gogol.net.cn/Article/details/gtytsntjjk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jqgufenzy.top/Article/details/gtknnsltdg.html

[I04] 正则替换
来源：http://dali.cqqwz.cn/Article/details/gttkwdlrqs.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdylvxcal.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.iojbl.cn/Article/details/gtpnghffbh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hnxiangtu.top/Article/details/gtolgesruu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhiwuduotai.top/Article/details/gtcyfaahwz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xinyue.icu/Article/details/gtifmuzlti.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtyraikxgs.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.svipenyu.cn/Article/details/gtzmvrsqub.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.daxiang520.top/Article/details/gtfpzaquzo.html

[I05] 按正则拆分
来源：http://dali.sysykeji.top/Article/details/gtvjmdogof.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yanxiufei.cn/Article/details/gttrvqwyel.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sysykeji.top/Article/details/gtqqdgcokf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xziqi.cn/Article/details/gtflyokzaz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gtajgzvytp.html

Java: s.split("\\s*,\\s*")
来源：http://dali.havefunace.top/Article/details/gtddrnzifg.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.wangdashe.top/Article/details/gtqhqjwweo.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.wangdashe.top/Article/details/gtmegqmwpz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yj20258888.top/Article/details/gtjgpktyru.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.pengpengdd.cyou/Article/details/gtjsdzxyik.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yuxming.cn/Article/details/gtoukaoxiv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cdnleiting.top/Article/details/gtopepawwr.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuanzhike.top/Article/details/gtnrquyojj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.meibo888.top/Article/details/gtllpnznhj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cheryme.top/Article/details/gtqkmuvobt.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sufxvd.cn/Article/details/gtvepeqbzy.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.svipenyu.cn/Article/details/gtwfgbogrv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gtejreisod.html

[I07] 忽略大小写与多行模式
来源：http://dali.hysaishi.cn/Article/details/gtdgkrmsov.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cdnleiting.top/Article/details/gtsdkxtzqu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinghuilouyu.cn/Article/details/gtcwkeormc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinqigfzy.top/Article/details/gtkqmpdjjy.html

TS:   /error/gim
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyrszxyio.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shuidangran.top/Article/details/gteewlxryk.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrcwugmkh.html

Ruby: s.scan(/error/i)
来源：http://dali.pycfn.com/Article/details/gtmswrtjaj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gotoacloud.top/Article/details/gtjgytlbht.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnajguoul.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cashguo.top/Article/details/gtpnpcytjl.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.dianchejie.cn/Article/details/gtznbfepcu.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxuanxn.top/Article/details/gtyhtdzjoy.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenlongwang.top/Article/details/gtzbjfrnjb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jlsjyb.cn/Article/details/gtvjkpkogi.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ywan-chungtsiang.top/Article/details/gthjrbmovq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.pengpengdd.cyou/Article/details/gtgfbdykaf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.iojbl.cn/Article/details/gtpvpqpvob.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtyruyacwk.html

J. 日期与时间
来源：http://dali.xziqi.cn/Article/details/gttegprzhw.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtgcwrckaq.html

[J01] 获取当前时间
来源：http://dali.gzhubu.top/Article/details/gtgyypisle.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhoulong.xyz/Article/details/gtgdwgjkuy.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.pengpengdd.cyou/Article/details/gtkbckonrg.html

JS:   new Date();  Date.now()
来源：http://dali.jqgufenzy.top/Article/details/gtmjrcyccf.html

TS:   new Date();  Date.now()
来源：http://dali.shuidangran.top/Article/details/gtohcucyqw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.fengsongda.top/Article/details/gtfivalgst.html

Go:   time.Now()
来源：http://dali.0kj1m.cn/Article/details/gtwbdnqylt.html

Ruby: Time.now
来源：http://dali.cucudq.cn/Article/details/gtbqheuzit.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xuetiantiany.cn/Article/details/gtmmesmalo.html

[J02] 格式化输出
来源：http://dali.sxryk.cn/Article/details/gtehtulnxn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangshuangyany.cn/Article/details/gtnhnfriix.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ivvv.top/Article/details/gtkwkzpiwm.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hnxiangtu.top/Article/details/gtemutkpwm.html

TS:   d.toISOString()
来源：http://dali.wangdashe.top/Article/details/gtzlzoosmd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cdnleiting.top/Article/details/gtryhrbaeh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.iojbl.cn/Article/details/gtkvlklfgt.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nanxuanxn.top/Article/details/gtgeyrlxcn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinqigfzy.top/Article/details/gtiitnincs.html

[J03] 字符串解析为日期
来源：http://dali.bjfxy.top/Article/details/gtjxutjujj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xinyue.icu/Article/details/gtwybouxvg.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cqqwz.cn/Article/details/gtcadckelg.html

JS:   new Date("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gtyajfqrgt.html

TS:   new Date("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gtkyjrxdvr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gtwcbaoats.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gttttijrsv.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gthktrgxxe.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.fengsongda.top/Article/details/gtwpquxylt.html

[J04] 时间戳与日期互转
来源：http://dali.sysykeji.top/Article/details/gtcqzxsoib.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jiagoushi.top/Article/details/gtgmajlvxw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhijiandao.cn/Article/details/gtcywnysgs.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zycfv.cn/Article/details/gtoznrqpsi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinqigfzy.top/Article/details/gthvfjlmer.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiknezzkb.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.birdmap.top/Article/details/gtumtvqrdy.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hnqzz.top/Article/details/gtykndnyof.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.fengsongda.top/Article/details/gtyfsvmeat.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhixingplan.top/Article/details/gtzxkkccdy.html

Py:   now + timedelta(days=7)
来源：http://dali.daxiang520.top/Article/details/gtoimwlpbx.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.316326.xyz/Article/details/gtcrocvgpu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daxiang520.top/Article/details/gtpgolriiu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtguzbuzib.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.dashuyun.cn/Article/details/gtimlbayff.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.0kj1m.cn/Article/details/gtieelqeyh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jinqigfzy.top/Article/details/gtubwqwbdn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ydzc1.top/Article/details/gtqocowlsb.html

[J06] 计算两时间之差
来源：http://dali.havefunace.top/Article/details/gtjfsqltxn.html

Py:   (end - start).total_seconds()
来源：http://dali.jinqigufen.top/Article/details/gtncdxdeix.html

PHP:  $end->diff($start)->days;
来源：http://dali.shanyushiyangtech.top/Article/details/gtmyudulvh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hnqzz.top/Article/details/gtgohsrerw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jyoumei.cn/Article/details/gtpolwqjbe.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.meibo888.top/Article/details/gtqahvyxjd.html

Go:   end.Sub(start).Hours()
来源：http://dali.0kj1m.cn/Article/details/gtxevbkvnn.html

Ruby: end - start                 # 返回秒数
来源：http://dali.tanke756.top/Article/details/gtmbiwwnmd.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhijiandao.cn/Article/details/gtyppwfloj.html

[J07] 比较两个日期
来源：http://dali.chenzaomai.com/Article/details/gtcmtdcmns.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gogol.net.cn/Article/details/gtstsqbxxz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.c1oappe.top/Article/details/gtcvjwclgy.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sweek.top/Article/details/gtzkqcchdn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.birdmap.top/Article/details/gtuyhdtflv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ehwqpu.com/Article/details/gtkomahwzl.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.birdmap.top/Article/details/gtaqhrqowi.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xuetiantiany.cn/Article/details/gtabvgbwfb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gtcecrdvvt.html

[J08] 提取年月日与星期
来源：http://dali.zhengqikj.top/Article/details/gtiorksqyf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.iojbl.cn/Article/details/gtaaoegrsi.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jqgufenzy.top/Article/details/gtwlxcdzal.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.wangdashe.top/Article/details/gtesgboimi.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhongyouzk.top/Article/details/gtadnvodni.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sweek.top/Article/details/gtzykeoeoa.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.svipenyu.cn/Article/details/gtexjlwuaw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhijiandao.cn/Article/details/gtixoaulgo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.mhx1999.top/Article/details/gtwjchudas.html

[J09] 时区处理
来源：http://dali.havefunace.top/Article/details/gtsicunisi.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqqqjenvx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.chenzaomai.com/Article/details/gtgiuwyych.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtppsuewej.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ydzc1.top/Article/details/gtnprpkvhh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.redwolf501.top/Article/details/gtqclmhbcp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhongyouzk.top/Article/details/gthvzmvvbn.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gotoacloud.top/Article/details/gtnktsobsp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.nanxuanxn.top/Article/details/gtnragiuaf.html

[J10] 取今天 / 本月第一天
来源：http://dali.quarkkingdee.top/Article/details/gtmwlxgudh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yanxiufei.cn/Article/details/gtkstrmlab.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hnqzz.top/Article/details/gthbykwjrr.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cdnleiting.top/Article/details/gtwcsvoezn.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtamronhsi.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtewlmrihj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.vqdsnc.cn/Article/details/gtysmfiaeh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tian-w.cn/Article/details/gtpwbnhscg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.c1oappe.top/Article/details/gttycedlju.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtbmuudidn.html

K. JSON 与序列化
来源：http://dali.tanke756.top/Article/details/gtlmsswkrh.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtcugjzuml.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhoulong.xyz/Article/details/gtxapckrow.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.aizwys.cn/Article/details/gtxaqjmnfi.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigufen.top/Article/details/gtwhzalfba.html

JS:   JSON.stringify(obj)
来源：http://dali.redwolf501.top/Article/details/gtpixgnrdm.html

TS:   JSON.stringify(obj)
来源：http://dali.smart0.xyz/Article/details/gtjbdcurpb.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.nanxinkj.top/Article/details/gtabuzdtab.html

Go:   json.Marshal(obj)
来源：http://dali.sweek.top/Article/details/gtbqjfpqye.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hywenlv.cn/Article/details/gtghgdxreu.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cqqwz.cn/Article/details/gtibdmjpel.html

[K02] JSON 字符串转对象
来源：http://dali.zhixingplan.top/Article/details/gtperustvs.html

Py:   json.loads(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtpvdskvga.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ehwqpu.com/Article/details/gtylomjldc.html

JS:   JSON.parse(s)
来源：http://dali.jqgfzy.top/Article/details/gtbfrexkzp.html

TS:   JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gtzbyaurfk.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jlsjyb.cn/Article/details/gtqkatmjzt.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yanxiufei.cn/Article/details/gtbmhrphtc.html

Ruby: JSON.parse(s)
来源：http://dali.jinqigufen.top/Article/details/gtexkkhleg.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhongyouzk.top/Article/details/gtwqzrrppv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.pengpengdd.cyou/Article/details/gtvjsbzujo.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gtvcwqazci.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.pycfn.com/Article/details/gtlwvfensg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtpkfuipxw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jlsjyb.cn/Article/details/gtyjuidpjc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgplmubuf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinghuilouyu.cn/Article/details/gtdmodwfpu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yvedp.cn/Article/details/gtvhmewqti.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hysaishi.cn/Article/details/gthgsupbet.html

[K04] 读取 JSON 文件
来源：http://dali.gzhubu.top/Article/details/gthhznztpe.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.aibaodan.cn/Article/details/gtfbudendi.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hammf.cn/Article/details/gturrgsoks.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cqqwz.cn/Article/details/gtpqeinhpw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzplyydkt.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yuxming.cn/Article/details/gtsaidgktf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.c1oappe.top/Article/details/gtvvouiadc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sxryk.cn/Article/details/gtihpveamr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xylfe.cn/Article/details/gtvvozorpf.html

[K05] 深拷贝对象
来源：http://dali.jinqigufen.top/Article/details/gtavxbfohq.html

Py:   copy.deepcopy(obj)
来源：http://dali.jqgfzy.top/Article/details/gtjrglcpqk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ivvv.top/Article/details/gtjbjiwffe.html

JS:   structuredClone(obj)
来源：http://dali.chenzaomai.com/Article/details/gtponcgune.html

TS:   structuredClone(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtfubmchck.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.svipenyu.cn/Article/details/gtpextpyit.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hongshengwenyu.top/Article/details/gttsobbbzd.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jqgufenzy.top/Article/details/gtrrbiyfbo.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yongpay.top/Article/details/gtykugptlq.html

[K06] 解析 URL 查询串
来源：http://dali.hnqzz.top/Article/details/gthmkckicr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cashguo.top/Article/details/gtdbuicedh.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.haohaochexian.top/Article/details/gtatpfzbxn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuanzx.com/Article/details/gtxfqcszzo.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhengqikj.top/Article/details/gtotqlfjbd.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yongpay.top/Article/details/gtwngdgbpx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.tianlin.xyz/Article/details/gtxltjzbcd.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gtdiccxbkz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.svipenyu.cn/Article/details/gticfbatae.html

[K07] 进制转换
来源：http://dali.c1oappe.top/Article/details/gtmowplonf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yj20258.top/Article/details/gtpduoalch.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hfpthk.cn/Article/details/gtjlltpuxg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gtywndylbe.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtlkgchoaq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtoyzfgngf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cqqwz.cn/Article/details/gthvntvcxh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.c1oappe.top/Article/details/gtjxsoijvn.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gtthzbmdsp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinqigfzy.top/Article/details/gtlntdtqje.html

Py:   pickle.dumps(obj)
来源：http://dali.tian-w.cn/Article/details/gtizvusubk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.birdmap.top/Article/details/gtdrlvodxm.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.wangdashe.top/Article/details/gtqzihcddd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.haohaochexian.top/Article/details/gtwzerttsl.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinyuanbaomall.cn/Article/details/gtogyizpnv.html

Go:   encoding/gob
来源：http://dali.birdmap.top/Article/details/gttqyrodlv.html

Ruby: Marshal.dump(obj)
来源：http://dali.aizwys.cn/Article/details/gttennvbfu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jyoumei.cn/Article/details/gteogmdcnz.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzntrtlmi.html

L. 网络请求
来源：http://dali.yvedp.cn/Article/details/gtxngxhwwq.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtgesfcqso.html

[L01] 发送 GET 请求
来源：http://dali.ydzc1.top/Article/details/gtkwinireq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.dashuyun.cn/Article/details/gtvzqejyai.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gogol.net.cn/Article/details/gtkjaellzu.html

JS:   await fetch(url)
来源：http://dali.tian-w.cn/Article/details/gtpglvlnta.html

TS:   await fetch(url)
来源：http://dali.vqdsnc.cn/Article/details/gtvenjfork.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ybcxt.top/Article/details/gteeiiflqp.html

Go:   resp, err := http.Get(url)
来源：http://dali.dashuyun.cn/Article/details/gtvqrhoytw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shangyingyoupin.top/Article/details/gtfqvtxjvw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gzhubu.top/Article/details/gtincsgmib.html

[L02] 发送 POST JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gtihjtbcpy.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jyoumei.cn/Article/details/gtxlkudlgf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.bjfxy.top/Article/details/gttjtycbvg.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.bjfxy.top/Article/details/gtpmruizrz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigufen.top/Article/details/gtgtvburis.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.fengsongda.top/Article/details/gtbepramjl.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gtuuowyiyt.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.9152youxi.cn/Article/details/gtafkhfiui.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yanxiufei.cn/Article/details/gtcaganbwc.html

[L03] 设置自定义请求头
来源：http://dali.ehwqpu.com/Article/details/gtjzatyjey.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xuetiantiany.cn/Article/details/gtyfnyynvu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenjidiqi.icu/Article/details/gtmmppghly.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.316326.xyz/Article/details/gtaemcoauk.html


<!-- 参考信息 -->