代发 wailian999

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cheryme.top/Article/details/gthnhrlopm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.pengpengdd.cyou/Article/details/gtyostxzxu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.havefunace.top/Article/details/gtqjnsbbsk.html

[H02] finally / ensure 收尾
来源：http://dali.aizwys.cn/Article/details/gthnbalxgn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ybcxt.top/Article/details/gtnxcxocre.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gtihhwcsqe.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gtjnygpvpf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtxzyhelqi.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gtjartedql.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jiagoushi.top/Article/details/gtvdyzikrb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cheryme.top/Article/details/gtzcmlytkt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yj20258.top/Article/details/gtoyjbkqya.html

[H03] 主动抛出异常
来源：http://dali.fzhhl.top/Article/details/gthoiidbtw.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinghuilouyu.cn/Article/details/gtecujwrmp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtgznjroar.html

JS:   throw new Error("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtrgzafuwv.html

TS:   throw new Error("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtxmpdhszn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.tian-w.cn/Article/details/gtweaowxzw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.aizwys.cn/Article/details/gtzexrcfun.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.andypj.xyz/Article/details/gtjnhsrugm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xuanzx.com/Article/details/gtxffxvgtr.html

[H04] 自定义异常类型
来源：http://dali.cqqwz.cn/Article/details/gtmpyrosbm.html

Py:   class MyError(Exception): pass
来源：http://dali.ppjwa.cn/Article/details/gtzufesjtd.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cqqwz.cn/Article/details/gtmmbkoecy.html

JS:   class MyError extends Error {}
来源：http://dali.jinqigufen.top/Article/details/gturabjofx.html

TS:   class MyError extends Error {}
来源：http://dali.bjfxy.top/Article/details/gtchsiblfo.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nanxinkj.top/Article/details/gtdfdlqgil.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjclflpfm.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxawlvzmf.html

C#:   class MyException : Exception {}
来源：http://dali.yangfankeji.com/Article/details/gtbdigvmpc.html

[H05] 捕获特定类型
来源：http://dali.c1oappe.top/Article/details/gtpiiffnjw.html

Py:   except ValueError as e:
来源：http://dali.zdqjudy.top/Article/details/gtztnucscc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.feifeiyinyue.top/Article/details/gtapihnksj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258.top/Article/details/gtnhtjlsxr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.guowangkeji.top/Article/details/gtadqrcvtv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yongpay.top/Article/details/gtevejgqeq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zycfv.cn/Article/details/gteqyshtns.html

Ruby: rescue ArgumentError => e
来源：http://dali.tanke756.top/Article/details/gtgaydrksa.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtybwhqvtj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ivvv.top/Article/details/gteycbcdcm.html

Py:   value = d.get("k") or default
来源：http://dali.9152youxi.cn/Article/details/gtxjbodync.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yanxiufei.cn/Article/details/gtdwuiqkax.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.c1oappe.top/Article/details/gteetevveb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcdhzurfw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shzxlz.cn/Article/details/gtfuihpkzf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.9152youxi.cn/Article/details/gtuvwnbgxu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zycfv.cn/Article/details/gtqrzilyof.html

C#:   obj?.A?.B ?? default
来源：http://dali.tianlin.xyz/Article/details/gttmwehltx.html

[H07] 断言
来源：http://dali.shzxlz.cn/Article/details/gtdcjonxdv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gtfmqxazac.html

PHP:  assert($x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtexaavrqw.html

JS:   console.assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gtzqjoecvx.html

TS:   console.assert(x > 0);
来源：http://dali.yj202588.top/Article/details/gtpljlwwdk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zdqjudy.top/Article/details/gtlucjiprw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.wangshuangyany.cn/Article/details/gtdwbpujqb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.chenzaomai.com/Article/details/gtfmgtxjzz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jqgfzy.top/Article/details/gtpjuwgwww.html

[H08] 获取错误信息与堆栈
来源：http://dali.c1oappe.top/Article/details/gthbsljfep.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jyoumei.cn/Article/details/gtgartzvhp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jqgufenzy.top/Article/details/gtfucoeafw.html

JS:   e.message;  e.stack
来源：http://dali.feifeiyinyue.top/Article/details/gtncoqvvcn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.9152youxi.cn/Article/details/gtzqtnonen.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gtvbydhngi.html

Go:   err.Error()
来源：http://dali.yongpay.top/Article/details/gtsbkokrok.html

Ruby: e.message;  e.backtrace
来源：http://dali.dianchejie.cn/Article/details/gtephigcmz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cashguo.top/Article/details/gtqyslwizr.html

[H09] 带错误码的异常
来源：http://dali.cdnleiting.top/Article/details/gtkhjmlica.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hammf.cn/Article/details/gtqijdqjte.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zycfv.cn/Article/details/gtdhwvubfa.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhoulong.xyz/Article/details/gtlpkpeveo.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.daria6918.cn/Article/details/gtzdjttufs.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.dashuyun.cn/Article/details/gtrbnlzerc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shangyingyoupin.top/Article/details/gtqtsanyhz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tianlin.xyz/Article/details/gtxlcasjic.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.haohaochexian.top/Article/details/gtwnjtldrj.html

[H10] 资源自动释放
来源：http://dali.cheryme.top/Article/details/gtytgcnrut.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hammf.cn/Article/details/gtvzvsdror.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hongshengwenyu.top/Article/details/gtipnhmovn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dianchejie.cn/Article/details/gtrairaixu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigufen.top/Article/details/gtedzpghji.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zdqjudy.top/Article/details/gtqexhyget.html

Go:   defer f.Close()
来源：http://dali.daxiang520.top/Article/details/gtbdnnfojz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.svipenyu.cn/Article/details/gtwthgvcuf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtwvvvsyzb.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtneiqvqdu.html

I. 正则表达式
来源：http://dali.yvedp.cn/Article/details/gttddyensp.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtgmircyet.html

[I01] 判断是否匹配
来源：http://dali.cashguo.top/Article/details/gtbkmnnxxk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.dianchejie.cn/Article/details/gtaymnljgl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jqgfzy.top/Article/details/gtfskiwdml.html

JS:   /\d+/.test(s)
来源：http://dali.hnqzz.top/Article/details/gtwwunznqc.html

TS:   /\d+/.test(s)
来源：http://dali.ppjwa.cn/Article/details/gtoibkqamq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sysykeji.top/Article/details/gtkhwnnxfm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cqqwz.cn/Article/details/gtsqgqpqvj.html

Ruby: s.match?(/\d+/)
来源：http://dali.yangfankeji.com/Article/details/gtizkvuhft.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.dashuyun.cn/Article/details/gtvtytnnhj.html

[I02] 提取所有匹配
来源：http://dali.bjfxy.top/Article/details/gtrmoxajgh.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cqqwz.cn/Article/details/gtfggfqvae.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hywenlv.cn/Article/details/gtsuueikke.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.wangshuangyany.cn/Article/details/gtqguhnsyr.html

TS:   s.match(/\d+/g)
来源：http://dali.zhoulong.xyz/Article/details/gtmxdqugfe.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.aizwys.cn/Article/details/gtvmiojaqm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jlsjyb.cn/Article/details/gtiudcryio.html

Ruby: s.scan(/\d+/)
来源：http://dali.daxiang520.top/Article/details/gtwbjrjtqx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtfaewzeyk.html

[I03] 提取捕获分组
来源：http://dali.wangdashe.top/Article/details/gtexqwldtk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gzhubu.top/Article/details/gthvqdeplp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpqgahepm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhengqikj.top/Article/details/gtolursmzr.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhengqikj.top/Article/details/gtvodegoty.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.fengsongda.top/Article/details/gtluhyehgu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yonumen.top/Article/details/gtgbwgzzju.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sweek.top/Article/details/gtucvwnruy.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.redwolf501.top/Article/details/gtlzjdgkdr.html

[I04] 正则替换
来源：http://dali.gaohongyu789.top/Article/details/gtramvomdz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ydzc1.top/Article/details/gtadvovdif.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtssjjuaok.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.iojbl.cn/Article/details/gtxlcuzvxv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ppjwa.cn/Article/details/gtmhwiqvsx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sxryk.cn/Article/details/gttbiswokn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.kuanghao11.cn/Article/details/gtutpqkrrr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzlszackp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.316326.xyz/Article/details/gtepujkmbb.html

[I05] 按正则拆分
来源：http://dali.c1oappe.top/Article/details/gtragrmxqu.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.daxiang520.top/Article/details/gtasnosozr.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtyaqzmqwg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jiagoushi.top/Article/details/gtiywrmasv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shzxlz.cn/Article/details/gtbggeipze.html

Java: s.split("\\s*,\\s*")
来源：http://dali.smart0.xyz/Article/details/gtebpmfauc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.havefunace.top/Article/details/gtsozvdhqp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gtlesurnmt.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.dianchejie.cn/Article/details/gttcqvslgv.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hongshengwenyu.top/Article/details/gtvwrvredv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gtyjaylcuw.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.bjfxy.top/Article/details/gtvrdqgjsk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jlsjyb.cn/Article/details/gtmyvfsojp.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuetiantiany.cn/Article/details/gteldvdbxi.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.quarkkingdee.top/Article/details/gttajuivvc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gtocriqssv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.daxiang520.top/Article/details/gthqudqvmj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.smart0.xyz/Article/details/gthaxsvqvj.html

[I07] 忽略大小写与多行模式
来源：http://dali.yueranfly.top/Article/details/gtgicwhqnt.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwvhnubpy.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.0kj1m.cn/Article/details/gtsyrjeqpk.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.nwbrower.top/Article/details/gtotddjowm.html

TS:   /error/gim
来源：http://dali.jinqigfzy.top/Article/details/gtcayyhban.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yonumen.top/Article/details/gtvhgebwbo.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gzhubu.top/Article/details/gtuhrnzywx.html

Ruby: s.scan(/error/i)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgzvlmeyi.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.tian-w.cn/Article/details/gtwabzrqeq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.dashuyun.cn/Article/details/gtrcfeikzc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.feifeiyinyue.top/Article/details/gtpsumophp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.chenzaomai.com/Article/details/gtykypafzd.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pengpengdd.cyou/Article/details/gtspggmyhn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.redwolf501.top/Article/details/gtkifojrpl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tanke756.top/Article/details/gtloujsqve.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.vqdsnc.cn/Article/details/gtdqfsvhqg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.0kj1m.cn/Article/details/gtdjttkwxo.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nanxinkj.top/Article/details/gtcvngnljb.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtxkhbzhgk.html

J. 日期与时间
来源：http://dali.nwbrower.top/Article/details/gtgpqdvhmw.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtzsudfehb.html

[J01] 获取当前时间
来源：http://dali.svipenyu.cn/Article/details/gtflvumxhi.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.daria6918.cn/Article/details/gtcsmrklok.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sxryk.cn/Article/details/gtbzcabhxy.html

JS:   new Date();  Date.now()
来源：http://dali.yj20258.top/Article/details/gtvyybzilx.html

TS:   new Date();  Date.now()
来源：http://dali.316326.xyz/Article/details/gteaoylcwg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yanxiufei.cn/Article/details/gtffcaouwa.html

Go:   time.Now()
来源：http://dali.shuidangran.top/Article/details/gtgrpzgjak.html

Ruby: Time.now
来源：http://dali.chenzaomai.com/Article/details/gtxiluvcfr.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gogol.net.cn/Article/details/gtfslonqzw.html

[J02] 格式化输出
来源：http://dali.hnxiangtu.top/Article/details/gtxghnqicd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.bjfxy.top/Article/details/gtuoaclwvh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.chenjidiqi.icu/Article/details/gtkrnsbavs.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhiwuduotai.top/Article/details/gteoicbzwf.html

TS:   d.toISOString()
来源：http://dali.haohaochexian.top/Article/details/gtdoixalwk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hnxiangtu.top/Article/details/gtcdvghdhu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.fzhhl.top/Article/details/gtwodmckhf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinghuilouyu.cn/Article/details/gthnjuapei.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cucudq.cn/Article/details/gtgzwomsur.html

[J03] 字符串解析为日期
来源：http://dali.smart0.xyz/Article/details/gttlmrezex.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.mhx1999.top/Article/details/gtilisuljp.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.fzhhl.top/Article/details/gthvcjgbry.html

JS:   new Date("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gtrbhugbse.html

TS:   new Date("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gtyscucihn.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gtduzbduqb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gtvojiewnr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gtaahfpxjj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yvedp.cn/Article/details/gtcezvvjld.html

[J04] 时间戳与日期互转
来源：http://dali.cdnleiting.top/Article/details/gtrgquczol.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yuxming.cn/Article/details/gtdorikupp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj20258.top/Article/details/gtrmbihjes.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.chenzaomai.com/Article/details/gtnqqeutku.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.pycfn.com/Article/details/gtnpnjbseq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sufxvd.cn/Article/details/gtpzihvwth.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jqgfzy.top/Article/details/gtfshgrsng.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jianghu66.top/Article/details/gtjtpnajzd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gtbjixsmcf.html

[J05] 时间加减（加 7 天）
来源：http://dali.nwbrower.top/Article/details/gtwknxeuyh.html

Py:   now + timedelta(days=7)
来源：http://dali.316326.xyz/Article/details/gtfytlksig.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.tian-w.cn/Article/details/gtumoquklp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cashguo.top/Article/details/gtzgaejzvc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gotoacloud.top/Article/details/gtvozewmog.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.316326.xyz/Article/details/gtqpnkstef.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xuetiantiany.cn/Article/details/gtmzfvtoll.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yongpay.top/Article/details/gtjrumycjs.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhengqikj.top/Article/details/gtifxtpqed.html

[J06] 计算两时间之差
来源：http://dali.zycfv.cn/Article/details/gtzuvbeyer.html

Py:   (end - start).total_seconds()
来源：http://dali.dashuyun.cn/Article/details/gtqsidqjkt.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhijiandao.cn/Article/details/gtudhyelzs.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sysykeji.top/Article/details/gtdnoqoxkg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jianghu66.top/Article/details/gtnxxxsjlk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ywan-chungtsiang.top/Article/details/gteilllyub.html

Go:   end.Sub(start).Hours()
来源：http://dali.birdmap.top/Article/details/gtvnpibpav.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ivvv.top/Article/details/gtalrnjkse.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinqigufen.top/Article/details/gtaewbnvwv.html

[J07] 比较两个日期
来源：http://dali.aibaodan.cn/Article/details/gtufoeaggy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gtokdxriqy.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.nanxinkj.top/Article/details/gtfdkwujkw.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hammf.cn/Article/details/gtfgxnnehs.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfusmrmar.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zycfv.cn/Article/details/gtizdobesr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gotoacloud.top/Article/details/gtrycvesnt.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xziqi.cn/Article/details/gtrdhhubjw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gaohongyu789.top/Article/details/gtjguktskw.html

[J08] 提取年月日与星期
来源：http://dali.hfpthk.cn/Article/details/gtlgsohssf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhijiandao.cn/Article/details/gttjritxve.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinghuilouyu.cn/Article/details/gtqdtmadbn.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj202588.top/Article/details/gtcdnhejrq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yongpay.top/Article/details/gtkxcjhwtq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.0kj1m.cn/Article/details/gtyhwfivdv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.0kj1m.cn/Article/details/gttpxdquxb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.feifeiyinyue.top/Article/details/gtydlevpvs.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.dianchejie.cn/Article/details/gthnbmlkch.html

[J09] 时区处理
来源：http://dali.aizwys.cn/Article/details/gtijfxjnmd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sysykeji.top/Article/details/gtzjyutlsc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jyoumei.cn/Article/details/gtslwyyaqs.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cqqwz.cn/Article/details/gtmwqrkfmf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ivvv.top/Article/details/gtaioejnwr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yongpay.top/Article/details/gtewwsjkto.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shzxlz.cn/Article/details/gtzquvgqac.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shangyingyoupin.top/Article/details/gtiyvhjppp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.mhx1999.top/Article/details/gtnacyqbeq.html

[J10] 取今天 / 本月第一天
来源：http://dali.haohaochexian.top/Article/details/gtcamlcxac.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hywenlv.cn/Article/details/gtqsjfboof.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sxryk.cn/Article/details/gtclwlofdv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlbhrvcuh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtdmosdzll.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.tianlin.xyz/Article/details/gtmssoqncj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhongyouzk.top/Article/details/gtyblkzcgs.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ehwqpu.com/Article/details/gtoicejgrr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtastgyiec.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtjsanqtna.html

K. JSON 与序列化
来源：http://dali.fengsongda.top/Article/details/gthqvbivrj.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtgybbzrbb.html

[K01] 对象转 JSON 字符串
来源：http://dali.daxiang520.top/Article/details/gtufkwpapv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhiwuduotai.top/Article/details/gtdtrwhefy.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xuanzx.com/Article/details/gtrqgmoetq.html

JS:   JSON.stringify(obj)
来源：http://dali.snrcjt.cn/Article/details/gtmldmwsaj.html

TS:   JSON.stringify(obj)
来源：http://dali.mhx1999.top/Article/details/gtbekaxvqj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.pycfn.com/Article/details/gtjmmxusxj.html

Go:   json.Marshal(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtzbsjjmlc.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shanyushiyangtech.top/Article/details/gthkdxvdvd.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ybcxt.top/Article/details/gtmkbnoluo.html

[K02] JSON 字符串转对象
来源：http://dali.cheryme.top/Article/details/gtutnhklmp.html

Py:   json.loads(s)
来源：http://dali.ivvv.top/Article/details/gthjbrtwtb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zdqjudy.top/Article/details/gtkqkmjwwj.html

JS:   JSON.parse(s)
来源：http://dali.zhoulong.xyz/Article/details/gtjuxvwako.html

TS:   JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtqaitwajl.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gtxeftxrrt.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xuetiantiany.cn/Article/details/gtcsdqvovu.html

Ruby: JSON.parse(s)
来源：http://dali.daria6918.cn/Article/details/gtpxewhyua.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ybcxt.top/Article/details/gtmjxmntfr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xylfe.cn/Article/details/gtrccqcwln.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yueranfly.top/Article/details/gtoxpygbik.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.haohaochexian.top/Article/details/gtdystxxih.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtneqzgisx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.dianchejie.cn/Article/details/gtbqgryswx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nwbrower.top/Article/details/gttgnpozru.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.fzhhl.top/Article/details/gtodtzxkvj.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cucudq.cn/Article/details/gtucbikixd.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sufxvd.cn/Article/details/gtxqhtixge.html

[K04] 读取 JSON 文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtblfxlozl.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gtsugcksrt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.tanke756.top/Article/details/gtstzxirjg.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnxiangtu.top/Article/details/gtlwnegzgu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangdashe.top/Article/details/gtxuxafxpb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shuidangran.top/Article/details/gtjfzqumxi.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hongshengwenyu.top/Article/details/gtmptwzgil.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhixingplan.top/Article/details/gttjfkmjbg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.chenzaomai.com/Article/details/gtgbxwggjp.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gtjkjcecys.html

Py:   copy.deepcopy(obj)
来源：http://dali.yj20258.top/Article/details/gterbtsplo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yuxming.cn/Article/details/gtnwcjqawk.html

JS:   structuredClone(obj)
来源：http://dali.nanxinkj.top/Article/details/gtfleonshm.html

TS:   structuredClone(obj)
来源：http://dali.daxiang520.top/Article/details/gtdmdqkhhm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.gzhubu.top/Article/details/gtpjlvrcfq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xuanzx.com/Article/details/gtfsjpsosp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.haohaochexian.top/Article/details/gtpelaadxp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.vqdsnc.cn/Article/details/gtajotxqgr.html


<!-- 参考信息 -->