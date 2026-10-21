代发 wailian999

Py:   try: f()⏎finally: cleanup()
来源：http://dali.nwbrower.top/Article/details/gtkinjwebs.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gthzidlayj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gtowbtsgjy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtjlqaehpw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtggzvecxs.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gaohongyu789.top/Article/details/gtwlrfjgsn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shangyingyoupin.top/Article/details/gtimbjhpav.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtakijjcrv.html

[H03] 主动抛出异常
来源：http://dali.jqgfzy.top/Article/details/gtzewxwriu.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtisnozubr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gtgojkjuso.html

JS:   throw new Error("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtrmyyyopl.html

TS:   throw new Error("错误信息");
来源：http://dali.yvedp.cn/Article/details/gtnxrolnrs.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gtpyabcdle.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shzxlz.cn/Article/details/gttzavjcgk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.9152youxi.cn/Article/details/gtvaljkrak.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gttvbhhvrc.html

[H04] 自定义异常类型
来源：http://dali.hnxiangtu.top/Article/details/gtpaqkgivh.html

Py:   class MyError(Exception): pass
来源：http://dali.cashguo.top/Article/details/gtplxfazwo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.chenzaomai.com/Article/details/gtxxznncqs.html

JS:   class MyError extends Error {}
来源：http://dali.fzhhl.top/Article/details/gtqqfwwvoo.html

TS:   class MyError extends Error {}
来源：http://dali.fzhhl.top/Article/details/gtcsvphvmh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sufxvd.cn/Article/details/gthtbbnwgt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhixingplan.top/Article/details/gtgqrxojkr.html

Ruby: class MyError < StandardError; end
来源：http://dali.guowangkeji.top/Article/details/gtwumvusap.html

C#:   class MyException : Exception {}
来源：http://dali.cucudq.cn/Article/details/gtalsnhesj.html

[H05] 捕获特定类型
来源：http://dali.zhengqikj.top/Article/details/gtikovscvu.html

Py:   except ValueError as e:
来源：http://dali.yueranfly.top/Article/details/gtsqbirlcq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.snrcjt.cn/Article/details/gtpksxdufp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sxryk.cn/Article/details/gtdzowaukp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.andypj.xyz/Article/details/gtwksofbnz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hammf.cn/Article/details/gtuwbwzrou.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yj202588.top/Article/details/gthkcgtmwd.html

Ruby: rescue ArgumentError => e
来源：http://dali.meibo888.top/Article/details/gtephnyddy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xylfe.cn/Article/details/gtghfjofrv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ydzc1.top/Article/details/gtqwrrnlaq.html

Py:   value = d.get("k") or default
来源：http://dali.gogol.net.cn/Article/details/gtxhysqfjr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yuanzhike.top/Article/details/gtixbvaezq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ppjwa.cn/Article/details/gtzrgtocut.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yueranfly.top/Article/details/gtlzzkzqll.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.daria6918.cn/Article/details/gtykniicjl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.daxiang520.top/Article/details/gtgjyngzql.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xuanzx.com/Article/details/gtgagejkbh.html

C#:   obj?.A?.B ?? default
来源：http://dali.yangfankeji.com/Article/details/gtbqrzvnqh.html

[H07] 断言
来源：http://dali.chenjidiqi.icu/Article/details/gtmcbesoae.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jqgfzy.top/Article/details/gtmlzqdajv.html

PHP:  assert($x > 0);
来源：http://dali.sufxvd.cn/Article/details/gtdghvrkcn.html

JS:   console.assert(x > 0);
来源：http://dali.yueranfly.top/Article/details/gtqnakezoj.html

TS:   console.assert(x > 0);
来源：http://dali.cqqwz.cn/Article/details/gtkdqujzro.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinghuilouyu.cn/Article/details/gttjcvhlva.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.pengpengdd.cyou/Article/details/gtfafxvlvk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgqvnmpar.html

C#:   Debug.Assert(x > 0);
来源：http://dali.316326.xyz/Article/details/gtkvyvtsmr.html

[H08] 获取错误信息与堆栈
来源：http://dali.ydzc1.top/Article/details/gtrqgtfatf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zycfv.cn/Article/details/gtxhcarwgg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xziqi.cn/Article/details/gtrsugxtec.html

JS:   e.message;  e.stack
来源：http://dali.pengpengdd.cyou/Article/details/gtomyrrfti.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yj202588.top/Article/details/gtrnbunscc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinqigfzy.top/Article/details/gtpniiezhh.html

Go:   err.Error()
来源：http://dali.xinyue.icu/Article/details/gthvjaceib.html

Ruby: e.message;  e.backtrace
来源：http://dali.haohaochexian.top/Article/details/gtmunhxxuu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xziqi.cn/Article/details/gtpqudwbqx.html

[H09] 带错误码的异常
来源：http://dali.sufxvd.cn/Article/details/gtnsnuhszn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.smart0.xyz/Article/details/gtjplvnzow.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yuanzhike.top/Article/details/gtgxssgajk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdyavwtbx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.andypj.xyz/Article/details/gtsfntjooo.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.bjfxy.top/Article/details/gtajyzfyjg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yvedp.cn/Article/details/gtdqslavvj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.quarkkingdee.top/Article/details/gtrldmrtmx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.pycfn.com/Article/details/gtgyahumci.html

[H10] 资源自动释放
来源：http://dali.sxryk.cn/Article/details/gtirsnybvx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.aibaodan.cn/Article/details/gtzsnaiqgk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhoulong.xyz/Article/details/gtqhfjfjsf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.iojbl.cn/Article/details/gtuxpcjnmj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hammf.cn/Article/details/gtpyzxpbni.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.nanxuanxn.top/Article/details/gtwyyoyxbj.html

Go:   defer f.Close()
来源：http://dali.xuetiantiany.cn/Article/details/gtbnobmizn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhiwuduotai.top/Article/details/gtcxjhhwna.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtfdmbwhog.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtkpsdhpks.html

I. 正则表达式
来源：http://dali.yvedp.cn/Article/details/gtqkkwucro.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtrcrmkvli.html

[I01] 判断是否匹配
来源：http://dali.xuetiantiany.cn/Article/details/gthntgkkxl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.wangdashe.top/Article/details/gtbajpjtul.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yongpay.top/Article/details/gtfacrneqd.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gtkfvllpxk.html

TS:   /\d+/.test(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtwkvbminy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jlsjyb.cn/Article/details/gtdofjawka.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtgaawoxxl.html

Ruby: s.match?(/\d+/)
来源：http://dali.xuanzx.com/Article/details/gthzutvbuv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.sysykeji.top/Article/details/gtmccbzsix.html

[I02] 提取所有匹配
来源：http://dali.sxryk.cn/Article/details/gtbpuxpxum.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gogol.net.cn/Article/details/gtmkzmzzkf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jiagoushi.top/Article/details/gtztqchccg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xylfe.cn/Article/details/gtcawqitxh.html

TS:   s.match(/\d+/g)
来源：http://dali.quarkkingdee.top/Article/details/gtfvruerem.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtlgbkaygg.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jqgfzy.top/Article/details/gtswmrfzgy.html

Ruby: s.scan(/\d+/)
来源：http://dali.cdnleiting.top/Article/details/gthdnwkzty.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yuanzhike.top/Article/details/gtgjzintnu.html

[I03] 提取捕获分组
来源：http://dali.hysaishi.cn/Article/details/gtxoacddxv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtjwersduy.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gttwsardau.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.dashuyun.cn/Article/details/gtppslkzjj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yvedp.cn/Article/details/gtzdklsnuf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shangyingyoupin.top/Article/details/gttkwzwkbv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.feifeiyinyue.top/Article/details/gtsajkfydk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gotoacloud.top/Article/details/gtlzvpwybg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.pycfn.com/Article/details/gtydkhxvps.html

[I04] 正则替换
来源：http://dali.hammf.cn/Article/details/gttkirrgrk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinqigufen.top/Article/details/gtrkntovni.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xuanzx.com/Article/details/gtasdjhamp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.bjfxy.top/Article/details/gtaeipycry.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.pycfn.com/Article/details/gttrkqirvg.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinqigufen.top/Article/details/gtheiapwti.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.andypj.xyz/Article/details/gtryarivxo.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.wangshuangyany.cn/Article/details/gtypiwxxso.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gogol.net.cn/Article/details/gtifdgxctw.html

[I05] 按正则拆分
来源：http://dali.aizwys.cn/Article/details/gtazxwbctr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yj20258.top/Article/details/gtexhqvgyg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.meibo888.top/Article/details/gtdmbiafcu.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hammf.cn/Article/details/gtwqvohmyc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.aizwys.cn/Article/details/gtzauvtxdt.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yj20258888.top/Article/details/gtzpaagtcv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hnqzz.top/Article/details/gtciigbwqt.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.tanke756.top/Article/details/gtrhstzcni.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jqgfzy.top/Article/details/gttxyfoxnu.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhoulong.xyz/Article/details/gtuogswypj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hnqzz.top/Article/details/gtovlgkuuc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhiwuduotai.top/Article/details/gtwllsaoxr.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.316326.xyz/Article/details/gtrfrmaigk.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cucudq.cn/Article/details/gtqplubcrb.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.tianlin.xyz/Article/details/gtuymuousm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.aibaodan.cn/Article/details/gttxjdqlxy.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.havefunace.top/Article/details/gtjvduyxet.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zdqjudy.top/Article/details/gtxokgipux.html

[I07] 忽略大小写与多行模式
来源：http://dali.havefunace.top/Article/details/gtiortokof.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.nwbrower.top/Article/details/gtkidximtm.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkociaiwe.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gzhubu.top/Article/details/gtevdapqui.html

TS:   /error/gim
来源：http://dali.ehwqpu.com/Article/details/gtggunyuep.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cashguo.top/Article/details/gtparqbdxp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhongyouzk.top/Article/details/gtabnbvwxo.html

Ruby: s.scan(/error/i)
来源：http://dali.fengsongda.top/Article/details/gtstvvlyna.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gtkzutlrgv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gotoacloud.top/Article/details/gtbrdqwbfz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jiagoushi.top/Article/details/gtkfinmyog.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ppjwa.cn/Article/details/gtnjloskqc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cheryme.top/Article/details/gtcxpvsrri.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.redwolf501.top/Article/details/gtryhmkabe.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shanyushiyangtech.top/Article/details/gtmiipnzth.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cqqwz.cn/Article/details/gtmzbjzgdz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gzhubu.top/Article/details/gtsrrphqub.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenlongwang.top/Article/details/gtecgenoml.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwoudojtd.html

J. 日期与时间
来源：http://dali.ehwqpu.com/Article/details/gtrobfsaaa.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtwajsjqsx.html

[J01] 获取当前时间
来源：http://dali.jqgufenzy.top/Article/details/gtpoemqksa.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gzhubu.top/Article/details/gtlgjefkcu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.dianchejie.cn/Article/details/gttbmsdsdu.html

JS:   new Date();  Date.now()
来源：http://dali.sxryk.cn/Article/details/gtjlegzyfx.html

TS:   new Date();  Date.now()
来源：http://dali.yongpay.top/Article/details/gtpiuldbpo.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinghuilouyu.cn/Article/details/gtddaigpyt.html

Go:   time.Now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsiwxpbwg.html

Ruby: Time.now
来源：http://dali.gogol.net.cn/Article/details/gtcjpqeqfz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sufxvd.cn/Article/details/gthvpnlavu.html

[J02] 格式化输出
来源：http://dali.vqdsnc.cn/Article/details/gtjycxdely.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xziqi.cn/Article/details/gtrvswlewn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.wangshuangyany.cn/Article/details/gtmmlsqknz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.wangdashe.top/Article/details/gtfhiluxak.html

TS:   d.toISOString()
来源：http://dali.xziqi.cn/Article/details/gtlgjkxxhj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.dianchejie.cn/Article/details/gtwecxiqop.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.quarkkingdee.top/Article/details/gtcnvbldbe.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnqzz.top/Article/details/gtrilscwcu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yonumen.top/Article/details/gtnbhvszrh.html

[J03] 字符串解析为日期
来源：http://dali.jqgufenzy.top/Article/details/gtriynktrj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.wangdashe.top/Article/details/gtlceqnzvp.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.havefunace.top/Article/details/gtedbssqwv.html

JS:   new Date("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gtzxffuier.html

TS:   new Date("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gtpwxedxuv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gtpvphrhvh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gtbzozrkvc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtdxpdibew.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.meibo888.top/Article/details/gtimxsprjb.html

[J04] 时间戳与日期互转
来源：http://dali.yongpay.top/Article/details/gtqacdqhpq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gotoacloud.top/Article/details/gtrhwbngbl.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj20258888.top/Article/details/gtjaxasdvp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nwbrower.top/Article/details/gtuqlgzxik.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.birdmap.top/Article/details/gtfzmgavup.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cashguo.top/Article/details/gtsglgwoyr.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shuidangran.top/Article/details/gtnurhvnls.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jinqigfzy.top/Article/details/gtdctgojxc.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.fzhhl.top/Article/details/gtqwkqnytu.html

[J05] 时间加减（加 7 天）
来源：http://dali.cdnleiting.top/Article/details/gtqryywwcs.html

Py:   now + timedelta(days=7)
来源：http://dali.fzhhl.top/Article/details/gtoqdouoxt.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cdnleiting.top/Article/details/gtwdtxcamf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigufen.top/Article/details/gtxkwfbvge.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnqzz.top/Article/details/gtndlazkee.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.daxiang520.top/Article/details/gthebdftye.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ybcxt.top/Article/details/gtfubvjkrs.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhixingplan.top/Article/details/gtgvjgdhfl.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yvedp.cn/Article/details/gtyxowtclm.html

[J06] 计算两时间之差
来源：http://dali.nwbrower.top/Article/details/gtqkcaraih.html

Py:   (end - start).total_seconds()
来源：http://dali.jqgufenzy.top/Article/details/gtfzzyozhn.html

PHP:  $end->diff($start)->days;
来源：http://dali.gogol.net.cn/Article/details/gtaewmffpx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hysaishi.cn/Article/details/gtobwpyrhd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.mhx1999.top/Article/details/gtydpxybfm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhengqikj.top/Article/details/gtnqdyvhdg.html

Go:   end.Sub(start).Hours()
来源：http://dali.ydzc1.top/Article/details/gtytmrfvvh.html

Ruby: end - start                 # 返回秒数
来源：http://dali.aibaodan.cn/Article/details/gtuhubqnnu.html

C#:   (end - start).TotalSeconds
来源：http://dali.daxiang520.top/Article/details/gtyomqcesf.html

[J07] 比较两个日期
来源：http://dali.cqqwz.cn/Article/details/gtpwfvfjwc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cheryme.top/Article/details/gtzmdnbpwr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhiwuduotai.top/Article/details/gtdcrcnlwp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhengqikj.top/Article/details/gtuebsidnb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.gaohongyu789.top/Article/details/gtqikzwmaq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.wangdashe.top/Article/details/gtojxqkkbq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jianghu66.top/Article/details/gtmkxfafwe.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.tian-w.cn/Article/details/gtgakvqybs.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gtydomdeus.html

[J08] 提取年月日与星期
来源：http://dali.kuanghao11.cn/Article/details/gtavfzvwlw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.havefunace.top/Article/details/gtoovggywl.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hammf.cn/Article/details/gtolxiukcg.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.dashuyun.cn/Article/details/gtnuuqsbvu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.aibaodan.cn/Article/details/gtamcancdf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.andypj.xyz/Article/details/gtvztlekfj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhijiandao.cn/Article/details/gtombehnca.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.fengsongda.top/Article/details/gtwjmxwxvn.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.quarkkingdee.top/Article/details/gttmpswsst.html

[J09] 时区处理
来源：http://dali.ivvv.top/Article/details/gthihjxllm.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.0kj1m.cn/Article/details/gtnzjrdwyv.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.c1oappe.top/Article/details/gtrqdysdbp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvfhnshfn.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangdashe.top/Article/details/gtryyhxbxl.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttqxursxp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hnxiangtu.top/Article/details/gtcmfmetjh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xylfe.cn/Article/details/gtwdavzsvr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.vqdsnc.cn/Article/details/gtmlqowgvl.html

[J10] 取今天 / 本月第一天
来源：http://dali.wangdashe.top/Article/details/gtxjrqorlk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ybcxt.top/Article/details/gthpnvtmma.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sweek.top/Article/details/gtatpidncp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ydzc1.top/Article/details/gthdnvxhrn.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.wangdashe.top/Article/details/gtslihcmfd.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.9152youxi.cn/Article/details/gtspsrjwtm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.aizwys.cn/Article/details/gtqebeiwta.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ydzc1.top/Article/details/gttazctdbr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yj202588.top/Article/details/gtalsiwjsr.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gthcszemst.html

K. JSON 与序列化
来源：http://dali.haohaochexian.top/Article/details/gtftjikqpx.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtklukhaks.html

[K01] 对象转 JSON 字符串
来源：http://dali.yangfankeji.com/Article/details/gtdubqmjpv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxqpowayu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.quarkkingdee.top/Article/details/gtpxtxeqyn.html

JS:   JSON.stringify(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgkaamkrn.html

TS:   JSON.stringify(obj)
来源：http://dali.guowangkeji.top/Article/details/gthxjtvbkn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jqgfzy.top/Article/details/gtgoeeqats.html

Go:   json.Marshal(obj)
来源：http://dali.andypj.xyz/Article/details/gtrekqlaeu.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrymhlrnt.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.meibo888.top/Article/details/gtzoytbtdo.html

[K02] JSON 字符串转对象
来源：http://dali.9152youxi.cn/Article/details/gtfpbolodm.html

Py:   json.loads(s)
来源：http://dali.hywenlv.cn/Article/details/gtxszulzit.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhengqikj.top/Article/details/gtogxcnzfn.html

JS:   JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gthdlkbkfs.html

TS:   JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gtpfdsydpc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cashguo.top/Article/details/gtccejyauc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.nwbrower.top/Article/details/gtefurxpny.html

Ruby: JSON.parse(s)
来源：http://dali.haohaochexian.top/Article/details/gtpynylxqq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cqqwz.cn/Article/details/gtxagbnbjo.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.fzhhl.top/Article/details/gtsvmgnyhj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.daxiang520.top/Article/details/gtkypzgpxz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.tianlin.xyz/Article/details/gtqezoavkl.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shzxlz.cn/Article/details/gtfrvqzwsi.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.fengsongda.top/Article/details/gtsgcicyzu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtptuotkcu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zycfv.cn/Article/details/gtmxypirdc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zycfv.cn/Article/details/gtjbwetdtr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xziqi.cn/Article/details/gtrhdusdhf.html

[K04] 读取 JSON 文件
来源：http://dali.birdmap.top/Article/details/gtcsvlavuo.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.quarkkingdee.top/Article/details/gtghdxcrjt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ivvv.top/Article/details/gteikgyteo.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.kuanghao11.cn/Article/details/gttvxqvsha.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cheryme.top/Article/details/gtwokggyml.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.tanke756.top/Article/details/gtxcaorwcy.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.nanxinkj.top/Article/details/gtdlnogxlg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenzaomai.com/Article/details/gtcncroerb.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.guowangkeji.top/Article/details/gtpjewibrq.html

[K05] 深拷贝对象
来源：http://dali.guannengcc.top/Article/details/gtsurecowx.html

Py:   copy.deepcopy(obj)
来源：http://dali.hywenlv.cn/Article/details/gtgpiecbac.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yonumen.top/Article/details/gtikagwomw.html

JS:   structuredClone(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtbexobedr.html

TS:   structuredClone(obj)
来源：http://dali.guannengcc.top/Article/details/gtrfbwhaad.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.daxiang520.top/Article/details/gtpaaprdgh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zycfv.cn/Article/details/gtqarqiese.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.kuanghao11.cn/Article/details/gtirjmgqpx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.redwolf501.top/Article/details/gthrutognv.html

[K06] 解析 URL 查询串
来源：http://dali.hammf.cn/Article/details/gtsrneohfc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.nwbrower.top/Article/details/gtehjxcfnc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jqgufenzy.top/Article/details/gttrtvwfhi.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cqqwz.cn/Article/details/gtgktvcsxx.html


<!-- 参考信息 -->