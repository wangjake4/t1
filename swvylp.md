代发 wailian999

[H03] 主动抛出异常
来源：http://dali.feifeiyinyue.top/Article/details/gtmvbnzdsh.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhongyouzk.top/Article/details/gtsbminyml.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtckwddjdf.html

JS:   throw new Error("错误信息");
来源：http://dali.birdmap.top/Article/details/gthidlhhsq.html

TS:   throw new Error("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtifwolcvc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gttgznekvp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cqqwz.cn/Article/details/gtkxvohvuu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xylfe.cn/Article/details/gtiusaomkt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtqckmsgqp.html

[H04] 自定义异常类型
来源：http://dali.aibaodan.cn/Article/details/gtrxipdsso.html

Py:   class MyError(Exception): pass
来源：http://dali.yangfankeji.com/Article/details/gtfdwiorbe.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sxryk.cn/Article/details/gtcnvlfmlt.html

JS:   class MyError extends Error {}
来源：http://dali.kuanghao11.cn/Article/details/gtnrrfewli.html

TS:   class MyError extends Error {}
来源：http://dali.bjfxy.top/Article/details/gtdsmytyxd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.tianlin.xyz/Article/details/gtieetnupy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ydzc1.top/Article/details/gttundluge.html

Ruby: class MyError < StandardError; end
来源：http://dali.xinyue.icu/Article/details/gtivntsxbp.html

C#:   class MyException : Exception {}
来源：http://dali.aizwys.cn/Article/details/gtvtkeizfg.html

[H05] 捕获特定类型
来源：http://dali.hongshengwenyu.top/Article/details/gtvonsmxno.html

Py:   except ValueError as e:
来源：http://dali.tianlin.xyz/Article/details/gtvfpzwfpv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xuetiantiany.cn/Article/details/gtourveolv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ydzc1.top/Article/details/gtzywmpjxg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.wangdashe.top/Article/details/gterrisjqi.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shuidangran.top/Article/details/gterbplgwx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.c1oappe.top/Article/details/gtgdcgnhod.html

Ruby: rescue ArgumentError => e
来源：http://dali.0kj1m.cn/Article/details/gtxtqidqal.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jqgfzy.top/Article/details/gthnkxapjj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cheryme.top/Article/details/gtecrfedcu.html

Py:   value = d.get("k") or default
来源：http://dali.jqgfzy.top/Article/details/gtitnbigbv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhoulong.xyz/Article/details/gtpcxboyid.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.pycfn.com/Article/details/gtdmrsxxad.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ydzc1.top/Article/details/gtefzkxrom.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyojwxtty.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yuxming.cn/Article/details/gtfysalgnu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.bjfxy.top/Article/details/gtewsfeppg.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gtuvfbpqmm.html

[H07] 断言
来源：http://dali.birdmap.top/Article/details/gttdwdzbuj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhixingplan.top/Article/details/gtqiyjvbpq.html

PHP:  assert($x > 0);
来源：http://dali.hnxiangtu.top/Article/details/gtjesgyuxv.html

JS:   console.assert(x > 0);
来源：http://dali.sxryk.cn/Article/details/gtsaikcuyi.html

TS:   console.assert(x > 0);
来源：http://dali.zhixingplan.top/Article/details/gthrrxezdt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.kuanghao11.cn/Article/details/gtdgzkixxh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shanyushiyangtech.top/Article/details/gtnnvcnmnx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shangyingyoupin.top/Article/details/gtcdmregzb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gtwypkskdx.html

[H08] 获取错误信息与堆栈
来源：http://dali.jyoumei.cn/Article/details/gtmuchufom.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhoulong.xyz/Article/details/gtuvazxpwm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.aizwys.cn/Article/details/gtenbporkk.html

JS:   e.message;  e.stack
来源：http://dali.guowangkeji.top/Article/details/gtecogrumn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gaohongyu789.top/Article/details/gthgyqpvjh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtknbzongd.html

Go:   err.Error()
来源：http://dali.yj202588.top/Article/details/gtlsuziyqk.html

Ruby: e.message;  e.backtrace
来源：http://dali.shanyushiyangtech.top/Article/details/gtnxnbpfwx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.fengsongda.top/Article/details/gthhfqowdl.html

[H09] 带错误码的异常
来源：http://dali.yangfankeji.com/Article/details/gtkqghtcnb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yanxiufei.cn/Article/details/gtyljtnlki.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.guannengcc.top/Article/details/gtoisfveuj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.chenjidiqi.icu/Article/details/gtkbkkxpdr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ydzc1.top/Article/details/gtxkmvzkrx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xylfe.cn/Article/details/gttieroxeq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinqigfzy.top/Article/details/gtxyhktyoq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.havefunace.top/Article/details/gtxjjhidjb.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cucudq.cn/Article/details/gtdiaxpbcu.html

[H10] 资源自动释放
来源：http://dali.yongpay.top/Article/details/gtegcdlpxr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj20258888.top/Article/details/gtcvhdhzgt.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gzhubu.top/Article/details/gtrzyfxrct.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sufxvd.cn/Article/details/gtwywjcuol.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhongyouzk.top/Article/details/gtcvhwxjyp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.smart0.xyz/Article/details/gtfnsofbnq.html

Go:   defer f.Close()
来源：http://dali.dashuyun.cn/Article/details/gtwtjbiiqm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.wangdashe.top/Article/details/gtupqsjimo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtqjrvwnju.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtridnoyrl.html

I. 正则表达式
来源：http://dali.yj20258.top/Article/details/gtylvyssug.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtyabstued.html

[I01] 判断是否匹配
来源：http://dali.zhongyouzk.top/Article/details/gtvtpurope.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.wangshuangyany.cn/Article/details/gtuvigsspw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.9152youxi.cn/Article/details/gtalrcjbcr.html

JS:   /\d+/.test(s)
来源：http://dali.mhx1999.top/Article/details/gtsuuryozx.html

TS:   /\d+/.test(s)
来源：http://dali.yonumen.top/Article/details/gtwfbodval.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtarmtozux.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.tianlin.xyz/Article/details/gtyimfxhrg.html

Ruby: s.match?(/\d+/)
来源：http://dali.haohaochexian.top/Article/details/gtepbgwgeo.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.guannengcc.top/Article/details/gtyvmnwlbc.html

[I02] 提取所有匹配
来源：http://dali.cucudq.cn/Article/details/gtcystxeyr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.0kj1m.cn/Article/details/gtmmbkpdmc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.mhx1999.top/Article/details/gtejzrkrer.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.wangdashe.top/Article/details/gtrzvdsius.html

TS:   s.match(/\d+/g)
来源：http://dali.xuetiantiany.cn/Article/details/gtjjslbhba.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.smart0.xyz/Article/details/gtgvrlcbdp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yuxming.cn/Article/details/gticfftfxi.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtobvjyzuy.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gtzxrhukjq.html

[I03] 提取捕获分组
来源：http://dali.c1oappe.top/Article/details/gthuiuohex.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhoulong.xyz/Article/details/gtiqzyrxym.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hnxiangtu.top/Article/details/gtbbqpfgsb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yuxming.cn/Article/details/gtzpdmksvw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gotoacloud.top/Article/details/gtcvggovjd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jqgufenzy.top/Article/details/gtjkvlssso.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tianlin.xyz/Article/details/gtwdjlzrkf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhoulong.xyz/Article/details/gtpajzwezj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinghuilouyu.cn/Article/details/gtwkwdmxyb.html

[I04] 正则替换
来源：http://dali.fengsongda.top/Article/details/gtxcgijgxe.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yvedp.cn/Article/details/gtteigrsrs.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.guowangkeji.top/Article/details/gtysinerft.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gttidlyiqp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hywenlv.cn/Article/details/gtpihuuxiw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.daria6918.cn/Article/details/gtskniuhnb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.guowangkeji.top/Article/details/gtxwxdqiii.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jiagoushi.top/Article/details/gtpghauzzn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjkybugcd.html

[I05] 按正则拆分
来源：http://dali.xylfe.cn/Article/details/gtmshcposs.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ydzc1.top/Article/details/gtckoznwyi.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj20258888.top/Article/details/gtaqcovkjb.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtomscwrsu.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpubwmrju.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hysaishi.cn/Article/details/gtnsrkvgwi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhoulong.xyz/Article/details/gttyntfnsw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.dashuyun.cn/Article/details/gtnnehmgmy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gaohongyu789.top/Article/details/gtnlghkjkc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.tianlin.xyz/Article/details/gtwmvdiyki.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.chenzaomai.com/Article/details/gthtictlik.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ybcxt.top/Article/details/gtzrhqqluq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yueranfly.top/Article/details/gtaaugzoio.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.redwolf501.top/Article/details/gtndcuyqil.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gttazgloei.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhiwuduotai.top/Article/details/gtmkzuhnyp.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.daria6918.cn/Article/details/gtfnslgawe.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinqigufen.top/Article/details/gtkbvwvxhn.html

[I07] 忽略大小写与多行模式
来源：http://dali.hfpthk.cn/Article/details/gtmjgszcpe.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sysykeji.top/Article/details/gtzjhugbgw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.wangdashe.top/Article/details/gtjuinoiwt.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.fzhhl.top/Article/details/gtvocblxev.html

TS:   /error/gim
来源：http://dali.ydzc1.top/Article/details/gtgxjibeyt.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttphjolyy.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shzxlz.cn/Article/details/gtxxrjtgef.html

Ruby: s.scan(/error/i)
来源：http://dali.gotoacloud.top/Article/details/gtqxofgvjw.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinqigfzy.top/Article/details/gtsrxsfali.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.vqdsnc.cn/Article/details/gtdmalbddb.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shangyingyoupin.top/Article/details/gtjevbfosu.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hfpthk.cn/Article/details/gtphynpefr.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xziqi.cn/Article/details/gtuxsdvfhs.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yangfankeji.com/Article/details/gtgfocrbms.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gtadowuydi.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.chenjidiqi.icu/Article/details/gtvurgseqr.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.pycfn.com/Article/details/gtyjrybvba.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yj20258.top/Article/details/gtvcuyfwtn.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtoorwqary.html

J. 日期与时间
来源：http://dali.cashguo.top/Article/details/gtsmixtbjy.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtjmdyzbmm.html

[J01] 获取当前时间
来源：http://dali.hysaishi.cn/Article/details/gttwoyerlc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jiagoushi.top/Article/details/gtucunzzep.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.snrcjt.cn/Article/details/gtbsykgcuf.html

JS:   new Date();  Date.now()
来源：http://dali.jqgufenzy.top/Article/details/gtlvpicyob.html

TS:   new Date();  Date.now()
来源：http://dali.yuxming.cn/Article/details/gtphnbcexk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gaohongyu789.top/Article/details/gtanaxjcph.html

Go:   time.Now()
来源：http://dali.yj20258.top/Article/details/gtjcapfypz.html

Ruby: Time.now
来源：http://dali.nwbrower.top/Article/details/gtcofkdtro.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yanxiufei.cn/Article/details/gtjtfhhiuo.html

[J02] 格式化输出
来源：http://dali.yj20258.top/Article/details/gtryveaqwo.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgufenzy.top/Article/details/gtasqumgrw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhengqikj.top/Article/details/gtrvkouljz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhixingplan.top/Article/details/gtggibabtj.html

TS:   d.toISOString()
来源：http://dali.yonumen.top/Article/details/gtyvfwkson.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zycfv.cn/Article/details/gthpgkqojn.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.snrcjt.cn/Article/details/gtruynluiq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sxryk.cn/Article/details/gtlsfeycgd.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.birdmap.top/Article/details/gtuzumdcrk.html

[J03] 字符串解析为日期
来源：http://dali.quarkkingdee.top/Article/details/gtldnmjavj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gotoacloud.top/Article/details/gtopuotmok.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.chenlongwang.top/Article/details/gtwniphibp.html

JS:   new Date("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gtaamkepus.html

TS:   new Date("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gtxrmlirkn.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gtgjiysnlr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gtvzdbdhls.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gtpdwiagfd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhixingplan.top/Article/details/gtwjfbdwij.html

[J04] 时间戳与日期互转
来源：http://dali.0kj1m.cn/Article/details/gtqgpnzuuv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shangyingyoupin.top/Article/details/gtjiuoxdyi.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yonumen.top/Article/details/gthhfnoazb.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhijiandao.cn/Article/details/gtoioqhxao.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yj202588.top/Article/details/gtzzgyqqgz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tianlin.xyz/Article/details/gtsialgggi.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtiyjgcvdq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xylfe.cn/Article/details/gtirorsenp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yuanzhike.top/Article/details/gtqzammbqy.html

[J05] 时间加减（加 7 天）
来源：http://dali.aibaodan.cn/Article/details/gtocmxdzfx.html

Py:   now + timedelta(days=7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvlunlpxp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yj20258.top/Article/details/gtyeqollrv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqdwetgjm.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ehwqpu.com/Article/details/gtpoevywup.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yj20258.top/Article/details/gtezkwqjls.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cdnleiting.top/Article/details/gtrxpkihoh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.tian-w.cn/Article/details/gtnxuhojga.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjzdwblbt.html

[J06] 计算两时间之差
来源：http://dali.aibaodan.cn/Article/details/gtjxevhotl.html

Py:   (end - start).total_seconds()
来源：http://dali.cucudq.cn/Article/details/gteqjyfdet.html

PHP:  $end->diff($start)->days;
来源：http://dali.yuanzhike.top/Article/details/gtvqabcsnb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.guowangkeji.top/Article/details/gtajkpigrl.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jlsjyb.cn/Article/details/gtlkwjbbrw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hammf.cn/Article/details/gtoibnfeup.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhengqikj.top/Article/details/gthpsnkkmf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gzhubu.top/Article/details/gtvyzrsufp.html

C#:   (end - start).TotalSeconds
来源：http://dali.ehwqpu.com/Article/details/gtispmwkcp.html

[J07] 比较两个日期
来源：http://dali.fzhhl.top/Article/details/gtoiesivgu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gtvmdcfxgm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.snrcjt.cn/Article/details/gtnseeqlmf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.bjfxy.top/Article/details/gticnwzqmf.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbjdridjb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jlsjyb.cn/Article/details/gthqrczovn.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinqigfzy.top/Article/details/gtpjyxjzfl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yj202588.top/Article/details/gtspvvfgew.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.kuanghao11.cn/Article/details/gtvnfyimjy.html

[J08] 提取年月日与星期
来源：http://dali.xylfe.cn/Article/details/gtyhqnsucg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zycfv.cn/Article/details/gtghraexxj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhengqikj.top/Article/details/gteleiicop.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jyoumei.cn/Article/details/gtaiagdilk.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yanxiufei.cn/Article/details/gttujyonrb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yuxming.cn/Article/details/gtcmuzhhbl.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.c1oappe.top/Article/details/gtdngvuhcb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.daria6918.cn/Article/details/gtupvlpcrg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shanyushiyangkeji.top/Article/details/gtelyulvup.html

[J09] 时区处理
来源：http://dali.yuxming.cn/Article/details/gtcorkhcak.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzzkgvgmw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.aizwys.cn/Article/details/gtfqzbgjml.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tianlin.xyz/Article/details/gtlwqhegao.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cdnleiting.top/Article/details/gttmlgfxat.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvvrydpkv.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmvddxamt.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nwbrower.top/Article/details/gtdpcerxju.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenlongwang.top/Article/details/gttwxxmpkb.html

[J10] 取今天 / 本月第一天
来源：http://dali.cdnleiting.top/Article/details/gtebvevzwq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuesmsysw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zdqjudy.top/Article/details/gtdxvkreuu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.svipenyu.cn/Article/details/gthzpclfip.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpvmuldhi.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gzhubu.top/Article/details/gtcrgmwjql.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xziqi.cn/Article/details/gtkfudvgqu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.dianchejie.cn/Article/details/gtoircyrhr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cucudq.cn/Article/details/gttpcjbjsu.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtdzywwqou.html

K. JSON 与序列化
来源：http://dali.havefunace.top/Article/details/gtddagbwfg.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtmsdkbesl.html

[K01] 对象转 JSON 字符串
来源：http://dali.wangdashe.top/Article/details/gtdvemsmrr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.nanxuanxn.top/Article/details/gtnxwnxqgz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jianghu66.top/Article/details/gttknvsjid.html

JS:   JSON.stringify(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtfnljcuqq.html

TS:   JSON.stringify(obj)
来源：http://dali.fzhhl.top/Article/details/gtdlvcxzpz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.tian-w.cn/Article/details/gtbiystrzq.html

Go:   json.Marshal(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtuetugxjt.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtomyduliq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.aibaodan.cn/Article/details/gtdlltxjtu.html

[K02] JSON 字符串转对象
来源：http://dali.shangyingyoupin.top/Article/details/gtlmjbuiob.html

Py:   json.loads(s)
来源：http://dali.gaohongyu789.top/Article/details/gtivaaasrn.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.aibaodan.cn/Article/details/gtehxezvwd.html

JS:   JSON.parse(s)
来源：http://dali.yuanzhike.top/Article/details/gthddluipa.html

TS:   JSON.parse(s)
来源：http://dali.yj20258888.top/Article/details/gtcslkdkfe.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.bjfxy.top/Article/details/gtmbuhotea.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shzxlz.cn/Article/details/gtnmjjpllu.html

Ruby: JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gtgoknqkdy.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yongpay.top/Article/details/gtkdntmiwm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.nwbrower.top/Article/details/gtacwardjj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.fengsongda.top/Article/details/gtybbiuqkm.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtavtfklhm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhongyouzk.top/Article/details/gtbrusbxka.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlpdeduet.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.0kj1m.cn/Article/details/gtzkamkeeo.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.quarkkingdee.top/Article/details/gtculzlyrm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.fzhhl.top/Article/details/gtkmizyudr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hywenlv.cn/Article/details/gtdwooxwhs.html

[K04] 读取 JSON 文件
来源：http://dali.wangdashe.top/Article/details/gterxikzdq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shzxlz.cn/Article/details/gtlnjduoug.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.nwbrower.top/Article/details/gtcbkngovd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangdashe.top/Article/details/gtdogddvjq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.haohaochexian.top/Article/details/gttopuhchb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gtlnvbbinz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.0kj1m.cn/Article/details/gtcxlpakec.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.mhx1999.top/Article/details/gtlhafkgck.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zdqjudy.top/Article/details/gtunmgzpwp.html

[K05] 深拷贝对象
来源：http://dali.ehwqpu.com/Article/details/gtklhgxwce.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhengqikj.top/Article/details/gtsoepqpof.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yuxming.cn/Article/details/gtlhymoldi.html

JS:   structuredClone(obj)
来源：http://dali.316326.xyz/Article/details/gtjvjgwgqc.html

TS:   structuredClone(obj)
来源：http://dali.jianghu66.top/Article/details/gtcsxonqum.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.havefunace.top/Article/details/gtapizycev.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hywenlv.cn/Article/details/gtdsjshpkw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.pycfn.com/Article/details/gtztbunfvo.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hnqzz.top/Article/details/gtyivaisqp.html

[K06] 解析 URL 查询串
来源：http://dali.316326.xyz/Article/details/gtskeqlagn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.fzhhl.top/Article/details/gtyriuicrv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hywenlv.cn/Article/details/gtlxmyyuqo.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yongpay.top/Article/details/gtbojmeqcd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.0kj1m.cn/Article/details/gtsdybhzdz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhongyouzk.top/Article/details/gtfbuvmiab.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.quarkkingdee.top/Article/details/gtweiwgnxz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.feifeiyinyue.top/Article/details/gtouodvlbm.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.dashuyun.cn/Article/details/gtzgohpzup.html

[K07] 进制转换
来源：http://dali.cqqwz.cn/Article/details/gtlzorzovx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yj20258.top/Article/details/gtxqghjlkk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sweek.top/Article/details/gtrorfpntu.html


<!-- 参考信息 -->