代发 wailian999

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gtgcczcsig.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xylfe.cn/Article/details/gtlldkmujy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ybcxt.top/Article/details/gtzhobczej.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtogfplzkm.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gtyjahxzgx.html

Py:   raise ValueError("错误信息")
来源：http://dali.wangdashe.top/Article/details/gtpcrgvhsp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xuanzx.com/Article/details/gtezowrkpl.html

JS:   throw new Error("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gtvsbicrzz.html

TS:   throw new Error("错误信息");
来源：http://dali.havefunace.top/Article/details/gtsruyvpjh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gtubpgmtss.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hammf.cn/Article/details/gtvjsiutfu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gzhubu.top/Article/details/gtnszlybad.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtuvvcblzo.html

[H04] 自定义异常类型
来源：http://dali.0kj1m.cn/Article/details/gtwdjurbss.html

Py:   class MyError(Exception): pass
来源：http://dali.shangyingyoupin.top/Article/details/gtaoduckcc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.c1oappe.top/Article/details/gtnrhiokyi.html

JS:   class MyError extends Error {}
来源：http://dali.ppjwa.cn/Article/details/gtusjfcxir.html

TS:   class MyError extends Error {}
来源：http://dali.ehwqpu.com/Article/details/gtdixroryd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.andypj.xyz/Article/details/gtgvyacnzs.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthdlzfcwp.html

Ruby: class MyError < StandardError; end
来源：http://dali.tanke756.top/Article/details/gtvwmsgixx.html

C#:   class MyException : Exception {}
来源：http://dali.c1oappe.top/Article/details/gtwzwhhqbg.html

[H05] 捕获特定类型
来源：http://dali.jqgufenzy.top/Article/details/gtpcbwbrhr.html

Py:   except ValueError as e:
来源：http://dali.mhx1999.top/Article/details/gtcxcbajaf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cdnleiting.top/Article/details/gthxymdlwu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.svipenyu.cn/Article/details/gtiwlqcrnf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gtxvbmcszk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sweek.top/Article/details/gttctgakki.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.haohaochexian.top/Article/details/gtupbdjomu.html

Ruby: rescue ArgumentError => e
来源：http://dali.yvedp.cn/Article/details/gtrcohumun.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jiagoushi.top/Article/details/gtywvfrrum.html

[H06] 可选值 / 空值安全访问
来源：http://dali.aizwys.cn/Article/details/gtanjudjax.html

Py:   value = d.get("k") or default
来源：http://dali.jianghu66.top/Article/details/gtxcaqqfcb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.316326.xyz/Article/details/gtfahasksg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sufxvd.cn/Article/details/gtliljrfit.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhiwuduotai.top/Article/details/gtawazatwi.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yueranfly.top/Article/details/gtkkmvosug.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ehwqpu.com/Article/details/gthqcjtisx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yvedp.cn/Article/details/gtbpdlgrpz.html

C#:   obj?.A?.B ?? default
来源：http://dali.aizwys.cn/Article/details/gtwkgkwtza.html

[H07] 断言
来源：http://dali.zhiwuduotai.top/Article/details/gtqjodpobs.html

Py:   assert x > 0, "必须为正"
来源：http://dali.iojbl.cn/Article/details/gtyvdclioi.html

PHP:  assert($x > 0);
来源：http://dali.tianlin.xyz/Article/details/gtcerpejet.html

JS:   console.assert(x > 0);
来源：http://dali.ybcxt.top/Article/details/gtjzhnikfw.html

TS:   console.assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gtlqsvqgbk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.pengpengdd.cyou/Article/details/gtnkzhuszp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.tanke756.top/Article/details/gtyuvtrtkd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.fzhhl.top/Article/details/gtcqhruxsf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gtrsbczxbi.html

[H08] 获取错误信息与堆栈
来源：http://dali.quarkkingdee.top/Article/details/gtrzgmbwvf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhengqikj.top/Article/details/gtctslachc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.wangdashe.top/Article/details/gtzaxmfmty.html

JS:   e.message;  e.stack
来源：http://dali.tianlin.xyz/Article/details/gtmuqxcurs.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.wangshuangyany.cn/Article/details/gtwjcxsbna.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.haohaochexian.top/Article/details/gtuqefqmja.html

Go:   err.Error()
来源：http://dali.ehwqpu.com/Article/details/gtihadtsoe.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinqigufen.top/Article/details/gtikgqnfun.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gaohongyu789.top/Article/details/gtnjvczdbg.html

[H09] 带错误码的异常
来源：http://dali.gzhubu.top/Article/details/gtebsdqdfs.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yuanzhike.top/Article/details/gttwhgoulr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhengqikj.top/Article/details/gtzawkzkrv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.fengsongda.top/Article/details/gtqmuskgur.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.dashuyun.cn/Article/details/gtqadkfhgd.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xziqi.cn/Article/details/gtzccfzhot.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinqigufen.top/Article/details/gttazwgvvn.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.0kj1m.cn/Article/details/gtlzreenve.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hfpthk.cn/Article/details/gtojoiobpv.html

[H10] 资源自动释放
来源：http://dali.shzxlz.cn/Article/details/gtnazluajj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.birdmap.top/Article/details/gtgmkcwfpq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.andypj.xyz/Article/details/gtprtuybjt.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hongshengwenyu.top/Article/details/gtlcopzywi.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cheryme.top/Article/details/gtdnztidae.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.pengpengdd.cyou/Article/details/gtkgjexihh.html

Go:   defer f.Close()
来源：http://dali.zhengqikj.top/Article/details/gtwufofjtg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ydzc1.top/Article/details/gticatsayy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtidyiciwx.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtmxteharn.html

I. 正则表达式
来源：http://dali.gogol.net.cn/Article/details/gtymemuvlr.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtpydzlsrh.html

[I01] 判断是否匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvupbstjc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.birdmap.top/Article/details/gtulnuhvlq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yj202588.top/Article/details/gtglrxuvlk.html

JS:   /\d+/.test(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtlaxjyrfk.html

TS:   /\d+/.test(s)
来源：http://dali.yonumen.top/Article/details/gtnrrjkycn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhongyouzk.top/Article/details/gtpvfltqpx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtirgpynox.html

Ruby: s.match?(/\d+/)
来源：http://dali.sweek.top/Article/details/gtmfbqntdn.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.smart0.xyz/Article/details/gtnfmyygwj.html

[I02] 提取所有匹配
来源：http://dali.tanke756.top/Article/details/gtwerkynmh.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yueranfly.top/Article/details/gtdmflwzmw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.havefunace.top/Article/details/gtovprzwoq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.daria6918.cn/Article/details/gtoksywqol.html

TS:   s.match(/\d+/g)
来源：http://dali.tanke756.top/Article/details/gtczfvmqtv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.nanxuanxn.top/Article/details/gtccquqtbp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.aibaodan.cn/Article/details/gtwazvagpu.html

Ruby: s.scan(/\d+/)
来源：http://dali.fzhhl.top/Article/details/gtxinluzhf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtlelwtrhx.html

[I03] 提取捕获分组
来源：http://dali.hongshengwenyu.top/Article/details/gtvxixlxbs.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtexpbucow.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sufxvd.cn/Article/details/gtfvfiszdm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.daxiang520.top/Article/details/gthbwcuwym.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sweek.top/Article/details/gtgoukyszh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqeggceql.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gotoacloud.top/Article/details/gtsppslbkw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.snrcjt.cn/Article/details/gteytwlonj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yj202588.top/Article/details/gtwtjrnvto.html

[I04] 正则替换
来源：http://dali.cdnleiting.top/Article/details/gtzcjzrfyx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xuetiantiany.cn/Article/details/gtzyskramj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cashguo.top/Article/details/gtvmvcsiog.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hnqzz.top/Article/details/gtvdthqkgf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ydzc1.top/Article/details/gtedajtqya.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.guowangkeji.top/Article/details/gtamgfhlco.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hfpthk.cn/Article/details/gtbtbkejdb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.wangdashe.top/Article/details/gthmvzgagn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinqigfzy.top/Article/details/gtikwldzoc.html

[I05] 按正则拆分
来源：http://dali.cucudq.cn/Article/details/gtqhrsqtuf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.pycfn.com/Article/details/gtydegofoi.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hnqzz.top/Article/details/gtegmpolit.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ppjwa.cn/Article/details/gtbzvtqfob.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.c1oappe.top/Article/details/gtrvbreeyo.html

Java: s.split("\\s*,\\s*")
来源：http://dali.daria6918.cn/Article/details/gtmsjfnjcy.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.guannengcc.top/Article/details/gtmjtvrkzl.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.chenzaomai.com/Article/details/gtbnvwdgbm.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yj202588.top/Article/details/gtmtqcsfwi.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.tanke756.top/Article/details/gtzgqefwgu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.chenjidiqi.icu/Article/details/gtfqpyohol.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cucudq.cn/Article/details/gtjhxzzwbm.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gzhubu.top/Article/details/gtmykgyyvc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.redwolf501.top/Article/details/gtbqngcofe.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.mhx1999.top/Article/details/gthowtqgig.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.smart0.xyz/Article/details/gtpfxitseq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xuanzx.com/Article/details/gtylaphjmm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinghuilouyu.cn/Article/details/gtkaaxesoe.html

[I07] 忽略大小写与多行模式
来源：http://dali.hfpthk.cn/Article/details/gtgwkelnvj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.pycfn.com/Article/details/gtdcmfyyig.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinqigfzy.top/Article/details/gtmljzeaoi.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxivtvprf.html

TS:   /error/gim
来源：http://dali.sxryk.cn/Article/details/gtieedmgkn.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hongshengwenyu.top/Article/details/gthtlrkfxi.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.andypj.xyz/Article/details/gtbfrfyezy.html

Ruby: s.scan(/error/i)
来源：http://dali.bjfxy.top/Article/details/gtnbktmkrk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.wangdashe.top/Article/details/gtpwfqchdl.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hysaishi.cn/Article/details/gtfebxucpm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shanyushiyangtech.top/Article/details/gtwqgugmcr.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.bjfxy.top/Article/details/gtlubnkcij.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zycfv.cn/Article/details/gttybdjhff.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinqigufen.top/Article/details/gtiruczhad.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hfpthk.cn/Article/details/gtkpdjwkam.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cucudq.cn/Article/details/gtumekfspf.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yangfankeji.com/Article/details/gtrisablcv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sufxvd.cn/Article/details/gtefnbhnkz.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtapwkjpga.html

J. 日期与时间
来源：http://dali.feifeiyinyue.top/Article/details/gtvxrwqcom.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmejipbyt.html

[J01] 获取当前时间
来源：http://dali.yuanzhike.top/Article/details/gtgdvahmfm.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jqgfzy.top/Article/details/gtqtadiwbm.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hnqzz.top/Article/details/gttfsncsfo.html

JS:   new Date();  Date.now()
来源：http://dali.chenjidiqi.icu/Article/details/gtvgwtsdbx.html

TS:   new Date();  Date.now()
来源：http://dali.yuanzhike.top/Article/details/gtqwnfgtbt.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.iojbl.cn/Article/details/gtzvilzogq.html

Go:   time.Now()
来源：http://dali.aizwys.cn/Article/details/gtacxbuqxl.html

Ruby: Time.now
来源：http://dali.zhoulong.xyz/Article/details/gtmoedmwgg.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenzaomai.com/Article/details/gteicvbozs.html

[J02] 格式化输出
来源：http://dali.gaohongyu789.top/Article/details/gtkmhjkqyv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jlsjyb.cn/Article/details/gtrplayfbs.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.dashuyun.cn/Article/details/gtfnagaaml.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yueranfly.top/Article/details/gtfgwbbads.html

TS:   d.toISOString()
来源：http://dali.316326.xyz/Article/details/gtqzpaeoxa.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cqqwz.cn/Article/details/gtjkdhwiol.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.quarkkingdee.top/Article/details/gtvuomujwv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ybcxt.top/Article/details/gtlcpzynoz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yj20258888.top/Article/details/gtimepteos.html

[J03] 字符串解析为日期
来源：http://dali.guannengcc.top/Article/details/gtlarhwcew.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cqqwz.cn/Article/details/gtqrkxbytm.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yueranfly.top/Article/details/gtqquxyhhn.html

JS:   new Date("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gtlkbliobr.html

TS:   new Date("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gtfiogtcur.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gtzagzzmll.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gtwadzbtny.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gtuetwpcvw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yvedp.cn/Article/details/gtdqisuuep.html

[J04] 时间戳与日期互转
来源：http://dali.zhixingplan.top/Article/details/gtfzfaenzf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.dianchejie.cn/Article/details/gtpihakdsy.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.iojbl.cn/Article/details/gtqktnqinc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cqqwz.cn/Article/details/gtnrtjhfjr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yueranfly.top/Article/details/gtmlzpmsrj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hfpthk.cn/Article/details/gtbzscdrpv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtgxxzekaa.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.tianlin.xyz/Article/details/gtpygijyzg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jyoumei.cn/Article/details/gtybbknica.html

[J05] 时间加减（加 7 天）
来源：http://dali.dianchejie.cn/Article/details/gtyzwbffwr.html

Py:   now + timedelta(days=7)
来源：http://dali.yongpay.top/Article/details/gtmzepkwpu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gotoacloud.top/Article/details/gtagmsfdjl.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guannengcc.top/Article/details/gtvyirddze.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gtzobfgtgx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.kuanghao11.cn/Article/details/gthwvbizpl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinqigufen.top/Article/details/gtqzkozlge.html

Ruby: Time.now + 7 * 86400
来源：http://dali.tanke756.top/Article/details/gttxipwofm.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hywenlv.cn/Article/details/gtgbqklcxw.html

[J06] 计算两时间之差
来源：http://dali.zhijiandao.cn/Article/details/gtaocoieyv.html

Py:   (end - start).total_seconds()
来源：http://dali.tanke756.top/Article/details/gtkzbippdz.html

PHP:  $end->diff($start)->days;
来源：http://dali.dashuyun.cn/Article/details/gtunzvwpme.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cucudq.cn/Article/details/gtrkvdbetz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hywenlv.cn/Article/details/gtnwvwumwt.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jqgufenzy.top/Article/details/gtphomfwxw.html

Go:   end.Sub(start).Hours()
来源：http://dali.hongshengwenyu.top/Article/details/gtmdkvilqd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.andypj.xyz/Article/details/gtqwrdgsej.html

C#:   (end - start).TotalSeconds
来源：http://dali.birdmap.top/Article/details/gtjraukare.html

[J07] 比较两个日期
来源：http://dali.aizwys.cn/Article/details/gtvfhxulrb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gtowyvmfsn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.0kj1m.cn/Article/details/gtlullkptd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhengqikj.top/Article/details/gtrflthtww.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.quarkkingdee.top/Article/details/gtbnpyovad.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ivvv.top/Article/details/gtayceesao.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hnxiangtu.top/Article/details/gttlbhstro.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuxhkohvc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yuxming.cn/Article/details/gtkvaqmykl.html

[J08] 提取年月日与星期
来源：http://dali.jyoumei.cn/Article/details/gtxhebvsss.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.snrcjt.cn/Article/details/gtnijjptie.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.snrcjt.cn/Article/details/gtkkzxfctr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yonumen.top/Article/details/gtaluncrcr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.chenzaomai.com/Article/details/gttefbejvo.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.feifeiyinyue.top/Article/details/gtjubzowxh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.wangdashe.top/Article/details/gtunyllesj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.fengsongda.top/Article/details/gtxekduqxt.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jyoumei.cn/Article/details/gtbplsuxav.html

[J09] 时区处理
来源：http://dali.9152youxi.cn/Article/details/gtxvlovdfd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinqigfzy.top/Article/details/gtvmtdpsek.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.tanke756.top/Article/details/gtnfwfczkp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sysykeji.top/Article/details/gtaokahlxb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnxiangtu.top/Article/details/gthiorbnjx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gogol.net.cn/Article/details/gtgcvbagsi.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.daxiang520.top/Article/details/gtyyalomcb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cheryme.top/Article/details/gtcogkqxgg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shangyingyoupin.top/Article/details/gtirgwhtfb.html

[J10] 取今天 / 本月第一天
来源：http://dali.fzhhl.top/Article/details/gtcezinamb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tian-w.cn/Article/details/gtyabxofle.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ppjwa.cn/Article/details/gtntbrwrnu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.haohaochexian.top/Article/details/gtugyafkkr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hywenlv.cn/Article/details/gtbxjjambu.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yvedp.cn/Article/details/gtnnuskevz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.9152youxi.cn/Article/details/gtniozcsbr.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.pengpengdd.cyou/Article/details/gtefofvrst.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jqgfzy.top/Article/details/gtgrygcnij.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtkxmhbfrq.html

K. JSON 与序列化
来源：http://dali.jinyuanbaomall.cn/Article/details/gttjndtlqh.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtgotarajl.html

[K01] 对象转 JSON 字符串
来源：http://dali.daxiang520.top/Article/details/gtmwbimtec.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.feifeiyinyue.top/Article/details/gtyqpzprsn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangtech.top/Article/details/gtyqtazsbk.html

JS:   JSON.stringify(obj)
来源：http://dali.jinqigufen.top/Article/details/gttxsymnok.html

TS:   JSON.stringify(obj)
来源：http://dali.zdqjudy.top/Article/details/gtyfesvimx.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yueranfly.top/Article/details/gtvizwbfho.html

Go:   json.Marshal(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvavrcwok.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yonumen.top/Article/details/gtgbrwvrdl.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhixingplan.top/Article/details/gtnzcsjzlr.html

[K02] JSON 字符串转对象
来源：http://dali.zhengqikj.top/Article/details/gtuxihpbpt.html

Py:   json.loads(s)
来源：http://dali.chenzaomai.com/Article/details/gtdruggtha.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenjidiqi.icu/Article/details/gtxonybonv.html

JS:   JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtwtxnjkcg.html

TS:   JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gtycuzpyoc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gtiufgshyl.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.chenlongwang.top/Article/details/gtgneyruxk.html

Ruby: JSON.parse(s)
来源：http://dali.ydzc1.top/Article/details/gtplzwstkq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.vqdsnc.cn/Article/details/gthamobfxw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.andypj.xyz/Article/details/gtawsmistg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgyblzipd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.mhx1999.top/Article/details/gtpgvjtdlt.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.svipenyu.cn/Article/details/gtwgxlidtr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.guowangkeji.top/Article/details/gtdoadynct.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.sufxvd.cn/Article/details/gttfrwhsml.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.haohaochexian.top/Article/details/gtymxwogxu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cheryme.top/Article/details/gtgkgwxeiz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.haohaochexian.top/Article/details/gtkbcalfuj.html

[K04] 读取 JSON 文件
来源：http://dali.gaohongyu789.top/Article/details/gtpdigotpt.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jyoumei.cn/Article/details/gtsrggeara.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.andypj.xyz/Article/details/gtgtnvcssb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ydzc1.top/Article/details/gtnniaahfh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwbbgwtnh.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yj20258.top/Article/details/gtvyeycjwy.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhixingplan.top/Article/details/gtmxrjblas.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gaohongyu789.top/Article/details/gtlsmmcwhh.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.kuanghao11.cn/Article/details/gtivkxvrvk.html

[K05] 深拷贝对象
来源：http://dali.mhx1999.top/Article/details/gtymrytgri.html

Py:   copy.deepcopy(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyajhiwie.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhoulong.xyz/Article/details/gtpolcnjzw.html

JS:   structuredClone(obj)
来源：http://dali.zhixingplan.top/Article/details/gtmclubwpq.html

TS:   structuredClone(obj)
来源：http://dali.jinqigufen.top/Article/details/gtioaffncz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yvedp.cn/Article/details/gtlcwdshva.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.snrcjt.cn/Article/details/gtnfxmrjjg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yongpay.top/Article/details/gtbapqdqeb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.dianchejie.cn/Article/details/gthsgkgtjk.html

[K06] 解析 URL 查询串
来源：http://dali.andypj.xyz/Article/details/gtgdrvsliq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.fzhhl.top/Article/details/gtvpfsjjtl.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.wangshuangyany.cn/Article/details/gtjxvcdzpa.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shuidangran.top/Article/details/gtchxmmewf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenlongwang.top/Article/details/gtpgvybffn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaeyfqout.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhixingplan.top/Article/details/gtsomzpxld.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.redwolf501.top/Article/details/gtuivekzxv.html


<!-- 参考信息 -->