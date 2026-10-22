代发 wailian999

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2iockicxy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2auehxfkp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gt2mxzneooo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gt2oynmaitp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gt2eodobvum.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gzhubu.top/Article/details/gt2crodlmal.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.bjfxy.top/Article/details/gt2wfmdpgek.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gt2eiksvonc.html

[H03] 主动抛出异常
来源：http://dali.dashuyun.cn/Article/details/gt2igmyodom.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj202588.top/Article/details/gt2drmwebnm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gt2cfujpecr.html

JS:   throw new Error("错误信息");
来源：http://dali.smart0.xyz/Article/details/gt2caceuagx.html

TS:   throw new Error("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gt2wipkkeog.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.daria6918.cn/Article/details/gt2rikzibix.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ujdwvedq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.aibaodan.cn/Article/details/gt2ppyoopuh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gt2fideaitf.html

[H04] 自定义异常类型
来源：http://dali.jlsjyb.cn/Article/details/gt2hguybxzp.html

Py:   class MyError(Exception): pass
来源：http://dali.pycfn.com/Article/details/gt2fyuudjte.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.daxiang520.top/Article/details/gt2mixaqkth.html

JS:   class MyError extends Error {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2slqvagjd.html

TS:   class MyError extends Error {}
来源：http://dali.sufxvd.cn/Article/details/gt2kcbyxdde.html

Java: class MyException extends RuntimeException {}
来源：http://dali.smart0.xyz/Article/details/gt2zgbbtbmq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fyyfwmza.html

Ruby: class MyError < StandardError; end
来源：http://dali.kuanghao11.cn/Article/details/gt2lsnitrva.html

C#:   class MyException : Exception {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2cdaoeafv.html

[H05] 捕获特定类型
来源：http://dali.xziqi.cn/Article/details/gt2uyhujyiw.html

Py:   except ValueError as e:
来源：http://dali.pycfn.com/Article/details/gt2oesbcfvo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yj20258888.top/Article/details/gt2gyvkufoa.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hnqzz.top/Article/details/gt2qdltaeeh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yonumen.top/Article/details/gt2mgzbtihd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.daria6918.cn/Article/details/gt2jdtyrpiq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gzhubu.top/Article/details/gt2sxtbomri.html

Ruby: rescue ArgumentError => e
来源：http://dali.316326.xyz/Article/details/gt2nuikofgm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zdqjudy.top/Article/details/gt2weiyqwkf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shzxlz.cn/Article/details/gt2vepcletw.html

Py:   value = d.get("k") or default
来源：http://dali.sxryk.cn/Article/details/gt2qrkbtmye.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.quarkkingdee.top/Article/details/gt2feuocamc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jiagoushi.top/Article/details/gt2mqlxbdwc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgfzy.top/Article/details/gt2jgcjlalc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xylfe.cn/Article/details/gt2yxmsqmtq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ppjwa.cn/Article/details/gt2evmtmwbc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jthnsscq.html

C#:   obj?.A?.B ?? default
来源：http://dali.cucudq.cn/Article/details/gt2nosgwppl.html

[H07] 断言
来源：http://dali.daxiang520.top/Article/details/gt2rzeqqfmh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.nanxuanxn.top/Article/details/gt2kwcirnjf.html

PHP:  assert($x > 0);
来源：http://dali.yongpay.top/Article/details/gt2isbxnzta.html

JS:   console.assert(x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gt2mxgatxhh.html

TS:   console.assert(x > 0);
来源：http://dali.meibo888.top/Article/details/gt2dbhlmgfr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hammf.cn/Article/details/gt2opqelrav.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ehbrezcs.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yueranfly.top/Article/details/gt2kcdrzqle.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2skqvsact.html

[H08] 获取错误信息与堆栈
来源：http://dali.yj20258.top/Article/details/gt2tdprtltx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cqqwz.cn/Article/details/gt2loowtdxg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.bjfxy.top/Article/details/gt2xjbrjfby.html

JS:   e.message;  e.stack
来源：http://dali.yuxming.cn/Article/details/gt2ueybdmer.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.wangshuangyany.cn/Article/details/gt2nszpkygi.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kjytgnsc.html

Go:   err.Error()
来源：http://dali.yj202588.top/Article/details/gt2bvxpsejk.html

Ruby: e.message;  e.backtrace
来源：http://dali.hfpthk.cn/Article/details/gt2yymqcuht.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mvljbspy.html

[H09] 带错误码的异常
来源：http://dali.xuetiantiany.cn/Article/details/gt2bxkmzfpb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shangyingyoupin.top/Article/details/gt2cdbcrbsf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iccpfrfw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.aizwys.cn/Article/details/gt2qxjbjskh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.chenzaomai.com/Article/details/gt2zigttavh.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yongpay.top/Article/details/gt2twymrfke.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yonumen.top/Article/details/gt2lfgqcncb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gogol.net.cn/Article/details/gt2pgdadewu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.c1oappe.top/Article/details/gt2eujbrdaf.html

[H10] 资源自动释放
来源：http://dali.zhiwuduotai.top/Article/details/gt2ulrpxwfg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.dianchejie.cn/Article/details/gt2pyxibahg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2odcquhhr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhiwuduotai.top/Article/details/gt2alxlmpaj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tian-w.cn/Article/details/gt2fyrtrzob.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.svipenyu.cn/Article/details/gt2srhgyytl.html

Go:   defer f.Close()
来源：http://dali.birdmap.top/Article/details/gt2ytzcvrii.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.gogol.net.cn/Article/details/gt2imgrfvvb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xuanzx.com/Article/details/gt2uyambsee.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uilugxqj.html

I. 正则表达式
来源：http://dali.tian-w.cn/Article/details/gt2oygknujn.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2tuvlfwbi.html

[I01] 判断是否匹配
来源：http://dali.tianlin.xyz/Article/details/gt2ycdmoirj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.aizwys.cn/Article/details/gt2cbahfrgq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.redwolf501.top/Article/details/gt2hhmdgziu.html

JS:   /\d+/.test(s)
来源：http://dali.cheryme.top/Article/details/gt2fcweojsv.html

TS:   /\d+/.test(s)
来源：http://dali.yueranfly.top/Article/details/gt2ovnmtehs.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cheryme.top/Article/details/gt2ecrvwdci.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.snrcjt.cn/Article/details/gt2irazxtgu.html

Ruby: s.match?(/\d+/)
来源：http://dali.birdmap.top/Article/details/gt2icgqpozd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.pengpengdd.cyou/Article/details/gt2zhzmieta.html

[I02] 提取所有匹配
来源：http://dali.nanxinkj.top/Article/details/gt2ltytvsbr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gaohongyu789.top/Article/details/gt2kitzbglu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ozcxntex.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yanxiufei.cn/Article/details/gt2zyqhlawr.html

TS:   s.match(/\d+/g)
来源：http://dali.cdnleiting.top/Article/details/gt2vljynycz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dvurouub.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sufxvd.cn/Article/details/gt2aklnigur.html

Ruby: s.scan(/\d+/)
来源：http://dali.birdmap.top/Article/details/gt2mzujohyh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gt2yxonwzhi.html

[I03] 提取捕获分组
来源：http://dali.jlsjyb.cn/Article/details/gt2ifrmaqjk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.316326.xyz/Article/details/gt2oghawvxi.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jqgfzy.top/Article/details/gt2olzmamis.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.nanxuanxn.top/Article/details/gt2hdayvqzi.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.redwolf501.top/Article/details/gt2ozgommbg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eglwxike.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.0kj1m.cn/Article/details/gt2yhgaijma.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jqgfzy.top/Article/details/gt2nthqejuo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yongpay.top/Article/details/gt2zmiovpkv.html

[I04] 正则替换
来源：http://dali.hnqzz.top/Article/details/gt2bsuahnlz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rdltngei.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxinkj.top/Article/details/gt2saosxbka.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gt2fqtivhpk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sweek.top/Article/details/gt2fmtrrrfk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.chenlongwang.top/Article/details/gt2jvcuzzsa.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.kuanghao11.cn/Article/details/gt2gxhgnwnc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gt2yaqooyjs.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinqigfzy.top/Article/details/gt2tvwstqac.html

[I05] 按正则拆分
来源：http://dali.xuetiantiany.cn/Article/details/gt2qgwadrqo.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xziqi.cn/Article/details/gt2jxluxpyn.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.guowangkeji.top/Article/details/gt2rallwsxh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.0kj1m.cn/Article/details/gt2tyyotspr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pduennfe.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jqgfzy.top/Article/details/gt2wdiglboq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.dashuyun.cn/Article/details/gt2naicfbpk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gt2rcvptsei.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dvesmzxs.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zycfv.cn/Article/details/gt2vwefbscg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shangyingyoupin.top/Article/details/gt2bzoebqkz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jlsjyb.cn/Article/details/gt2ylczxthm.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yonumen.top/Article/details/gt2iqkksfcf.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.quarkkingdee.top/Article/details/gt2sfydpfqv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.pycfn.com/Article/details/gt2brzgpojl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zmqtnhgb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.dianchejie.cn/Article/details/gt2fysrslrf.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jqgfzy.top/Article/details/gt2xbmjxmnq.html

[I07] 忽略大小写与多行模式
来源：http://dali.jqgfzy.top/Article/details/gt2jigcpdyf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yuanzhike.top/Article/details/gt2riyehprd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ybcxt.top/Article/details/gt2wsebzmvq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.dianchejie.cn/Article/details/gt2qtsxkmfc.html

TS:   /error/gim
来源：http://dali.ydzc1.top/Article/details/gt2qxwdljpi.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.dashuyun.cn/Article/details/gt2ylhlvwfj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.chenlongwang.top/Article/details/gt2slaxcckl.html

Ruby: s.scan(/error/i)
来源：http://dali.yj20258888.top/Article/details/gt2dceeqyul.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zdqjudy.top/Article/details/gt2trknmeqn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ehwqpu.com/Article/details/gt2zjoavfza.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.316326.xyz/Article/details/gt2qszlacvl.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cdnleiting.top/Article/details/gt2cumczygw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fzhhl.top/Article/details/gt2uiwxztrf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenlongwang.top/Article/details/gt2aoxacaep.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jiagoushi.top/Article/details/gt2mohqgcbs.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ivvv.top/Article/details/gt2hecxvnmy.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.smart0.xyz/Article/details/gt2cmqejlej.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cqqwz.cn/Article/details/gt2zeassavf.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2ygjgwnpp.html

J. 日期与时间
来源：http://dali.tanke756.top/Article/details/gt2qcpcfcxy.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2hvaeuqza.html

[J01] 获取当前时间
来源：http://dali.aibaodan.cn/Article/details/gt2iumobtxo.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.c1oappe.top/Article/details/gt2cbepqggh.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hnxiangtu.top/Article/details/gt2salycfsx.html

JS:   new Date();  Date.now()
来源：http://dali.kuanghao11.cn/Article/details/gt2yiyyrkqz.html

TS:   new Date();  Date.now()
来源：http://dali.ydzc1.top/Article/details/gt2qrymhrur.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.snrcjt.cn/Article/details/gt2nzpgeeua.html

Go:   time.Now()
来源：http://dali.chenlongwang.top/Article/details/gt2rorebvir.html

Ruby: Time.now
来源：http://dali.jinqigufen.top/Article/details/gt2wnxiuzci.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sysykeji.top/Article/details/gt2jeobhtsu.html

[J02] 格式化输出
来源：http://dali.yueranfly.top/Article/details/gt2mosxomhy.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xylfe.cn/Article/details/gt2seawkibj.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2swhhlipy.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.iojbl.cn/Article/details/gt2lnjwuckg.html

TS:   d.toISOString()
来源：http://dali.zhongyouzk.top/Article/details/gt2fbhjibcs.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.redwolf501.top/Article/details/gt2ircqxbmc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hnxiangtu.top/Article/details/gt2vframpmk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zycfv.cn/Article/details/gt2wjmzdawe.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cheryme.top/Article/details/gt2wzfgpsgy.html

[J03] 字符串解析为日期
来源：http://dali.jinqigfzy.top/Article/details/gt2ngqlitzl.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yj20258.top/Article/details/gt2uxyyolif.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.dashuyun.cn/Article/details/gt2gzhvzeyr.html

JS:   new Date("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gt2mpqjzknb.html

TS:   new Date("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gt2rfsdcvrb.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gt2xzcqyopd.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gt2pzvcyzvo.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gt2jphmjpgk.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hfpthk.cn/Article/details/gt2livmakrj.html

[J04] 时间戳与日期互转
来源：http://dali.sufxvd.cn/Article/details/gt2vbijmttu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.bjfxy.top/Article/details/gt2dsrmsjpr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.dashuyun.cn/Article/details/gt2ikwbusuv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.tianlin.xyz/Article/details/gt2ywmrsoxc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cheryme.top/Article/details/gt2wipxtiou.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tian-w.cn/Article/details/gt2yctumvgk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ppjwa.cn/Article/details/gt2qkozmves.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sufxvd.cn/Article/details/gt2gvatkwhf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xuanzx.com/Article/details/gt2tsvonril.html

[J05] 时间加减（加 7 天）
来源：http://dali.redwolf501.top/Article/details/gt2cezcztxv.html

Py:   now + timedelta(days=7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kqstoisl.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xylfe.cn/Article/details/gt2fdmrvmty.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nanxinkj.top/Article/details/gt2hhlzjdoj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenlongwang.top/Article/details/gt2qbghwznp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.chenlongwang.top/Article/details/gt2lwpnxpgl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qbcrofil.html

Ruby: Time.now + 7 * 86400
来源：http://dali.nwbrower.top/Article/details/gt2aaomfnjd.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.andypj.xyz/Article/details/gt2nnksoxgx.html

[J06] 计算两时间之差
来源：http://dali.quarkkingdee.top/Article/details/gt2xouqprrg.html

Py:   (end - start).total_seconds()
来源：http://dali.shzxlz.cn/Article/details/gt2zkugihcb.html

PHP:  $end->diff($start)->days;
来源：http://dali.xziqi.cn/Article/details/gt2rpihhlus.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.nanxinkj.top/Article/details/gt2lnjkskre.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.chenlongwang.top/Article/details/gt2nxxrzgqy.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yueranfly.top/Article/details/gt2iulejhzz.html

Go:   end.Sub(start).Hours()
来源：http://dali.yj20258.top/Article/details/gt2jtyvcrse.html

Ruby: end - start                 # 返回秒数
来源：http://dali.daria6918.cn/Article/details/gt2srexvjzq.html

C#:   (end - start).TotalSeconds
来源：http://dali.9152youxi.cn/Article/details/gt2ejtutlzs.html

[J07] 比较两个日期
来源：http://dali.shzxlz.cn/Article/details/gt2rtkemzls.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.daria6918.cn/Article/details/gt2uzbvfxab.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.feifeiyinyue.top/Article/details/gt2wqlrbzte.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.vqdsnc.cn/Article/details/gt2vjqsdqrp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhixingplan.top/Article/details/gt2cxoxucea.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.quarkkingdee.top/Article/details/gt2rgpboqyo.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhengqikj.top/Article/details/gt2gpyuatdw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gt2gveycqmv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.kuanghao11.cn/Article/details/gt2afqjbjiy.html

[J08] 提取年月日与星期
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yfdnppem.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yanxiufei.cn/Article/details/gt2uizxrsmd.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.guannengcc.top/Article/details/gt2ltkfxbxd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj202588.top/Article/details/gt2oppoyksl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhengqikj.top/Article/details/gt2hkpxuzka.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yongpay.top/Article/details/gt2nnplmcgz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gogol.net.cn/Article/details/gt2cqmmnivw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.aizwys.cn/Article/details/gt2eeuqyjtc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hammf.cn/Article/details/gt2urrhshlg.html

[J09] 时区处理
来源：http://dali.ivvv.top/Article/details/gt2wxwrshec.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yuanzhike.top/Article/details/gt2wkfehqne.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.daria6918.cn/Article/details/gt2urbvqoss.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tanke756.top/Article/details/gt2cqrekngr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tanke756.top/Article/details/gt2nttduplp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jianghu66.top/Article/details/gt2aaxdiprm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yuxming.cn/Article/details/gt2mnwosrke.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.kuanghao11.cn/Article/details/gt2sawtpmpy.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yongpay.top/Article/details/gt2iygjefup.html

[J10] 取今天 / 本月第一天
来源：http://dali.jiagoushi.top/Article/details/gt2kwtzatnj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yj20258888.top/Article/details/gt2aacgmmkt.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dzloceqf.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.kuanghao11.cn/Article/details/gt2aplgqcpd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yangfankeji.com/Article/details/gt2awkwyuvd.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ppjwa.cn/Article/details/gt2ujrcyxsj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xziqi.cn/Article/details/gt2vcyyokwn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ydzc1.top/Article/details/gt2hvdqtwdw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hnxiangtu.top/Article/details/gt2rpvbwluc.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2jzzpqjdp.html

K. JSON 与序列化
来源：http://dali.ybcxt.top/Article/details/gt2esxjswrl.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2zkvwvrqr.html

[K01] 对象转 JSON 字符串
来源：http://dali.sysykeji.top/Article/details/gt2fcrufzcf.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hysaishi.cn/Article/details/gt2bhpyefnu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2tsfnemee.html

JS:   JSON.stringify(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2ttbplxxk.html

TS:   JSON.stringify(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2ugbqvikm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hywenlv.cn/Article/details/gt2rixfchls.html

Go:   json.Marshal(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2tnltexjt.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yj202588.top/Article/details/gt2xbmlleed.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2nqcdowim.html

[K02] JSON 字符串转对象
来源：http://dali.xuanzx.com/Article/details/gt2rstniqld.html

Py:   json.loads(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2texxcbqj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xziqi.cn/Article/details/gt2ktoogfcp.html

JS:   JSON.parse(s)
来源：http://dali.xylfe.cn/Article/details/gt2zimrrmva.html

TS:   JSON.parse(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2azrrnghz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hammf.cn/Article/details/gt2sgxnnwvb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tfykigfr.html

Ruby: JSON.parse(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2dicwrufj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.wangdashe.top/Article/details/gt2suktmunr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gotoacloud.top/Article/details/gt2wfaytaxr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinqigufen.top/Article/details/gt2zlaicvfq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yuxming.cn/Article/details/gt2foaskwpm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hywenlv.cn/Article/details/gt2wkdvzyjh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sxryk.cn/Article/details/gt2brooitoy.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yj20258888.top/Article/details/gt2hxnzjott.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.dashuyun.cn/Article/details/gt2fuzzwibm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2boxskqon.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yonumen.top/Article/details/gt2bizjzqwq.html

[K04] 读取 JSON 文件
来源：http://dali.xinyue.icu/Article/details/gt2ufzggdrt.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.snrcjt.cn/Article/details/gt2sngeawzh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sufxvd.cn/Article/details/gt2tbkgbfla.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2anskkgyy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shzxlz.cn/Article/details/gt2wrbvtzdb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.pycfn.com/Article/details/gt2jafoshzx.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sxryk.cn/Article/details/gt2sqmsualu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ybcxt.top/Article/details/gt2tkmdqnav.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.quarkkingdee.top/Article/details/gt2oqeslfkj.html

[K05] 深拷贝对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rgvjhozx.html

Py:   copy.deepcopy(obj)
来源：http://dali.aizwys.cn/Article/details/gt2cxllfquj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hnqzz.top/Article/details/gt2ofuglxri.html

JS:   structuredClone(obj)
来源：http://dali.hammf.cn/Article/details/gt2ivbelzyg.html

TS:   structuredClone(obj)
来源：http://dali.andypj.xyz/Article/details/gt2hhyqkgan.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.daxiang520.top/Article/details/gt2zrzlopij.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.dianchejie.cn/Article/details/gt2jzkvnfmb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sswohlii.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sufxvd.cn/Article/details/gt2lllpwmio.html

[K06] 解析 URL 查询串
来源：http://dali.fengsongda.top/Article/details/gt2svbohusx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jqgfzy.top/Article/details/gt2msnkiaho.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.meibo888.top/Article/details/gt2sswpttxp.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnxiangtu.top/Article/details/gt2kfuwwkww.html


<!-- 参考信息 -->