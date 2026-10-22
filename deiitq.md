代发 wailian999

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xuanzx.com/Article/details/gt2gtuyrcjd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhiwuduotai.top/Article/details/gt2aedgypiv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.chenzaomai.com/Article/details/gt2almjnyxw.html

[H02] finally / ensure 收尾
来源：http://dali.iojbl.cn/Article/details/gt2tmtogwjp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shzxlz.cn/Article/details/gt2jafakjxq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gt2ahyrllri.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gt2xtwbpcwn.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lihlhdem.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gt2xaywpuzd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj202588.top/Article/details/gt2osnqssiw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.guowangkeji.top/Article/details/gt2ysqaggpw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2sgtizoid.html

[H03] 主动抛出异常
来源：http://dali.hywenlv.cn/Article/details/gt2cqiehivs.html

Py:   raise ValueError("错误信息")
来源：http://dali.hnxiangtu.top/Article/details/gt2vrnoeuwd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gt2rooyluue.html

JS:   throw new Error("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gt2rkybztav.html

TS:   throw new Error("错误信息");
来源：http://dali.yvedp.cn/Article/details/gt2qsqhgqun.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gt2djgmchbo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ybcxt.top/Article/details/gt2yriqgvaz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinqigfzy.top/Article/details/gt2oglxkvrf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gt2ruxhxyem.html

[H04] 自定义异常类型
来源：http://dali.fzhhl.top/Article/details/gt2ktqpygxb.html

Py:   class MyError(Exception): pass
来源：http://dali.sysykeji.top/Article/details/gt2sjiinlec.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.aibaodan.cn/Article/details/gt2nsijakxh.html

JS:   class MyError extends Error {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xgxjpvtr.html

TS:   class MyError extends Error {}
来源：http://dali.nwbrower.top/Article/details/gt2cjugkhmn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hfpthk.cn/Article/details/gt2kobaowhp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gogol.net.cn/Article/details/gt2tyefjwhn.html

Ruby: class MyError < StandardError; end
来源：http://dali.shuidangran.top/Article/details/gt2zjzmjsbx.html

C#:   class MyException : Exception {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2aczuzbea.html

[H05] 捕获特定类型
来源：http://dali.sysykeji.top/Article/details/gt2ekithdih.html

Py:   except ValueError as e:
来源：http://dali.ppjwa.cn/Article/details/gt2djrrjflf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.fzhhl.top/Article/details/gt2rvfvomcw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.fengsongda.top/Article/details/gt2dlkpytkl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jianghu66.top/Article/details/gt2kbcjxurj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yj20258.top/Article/details/gt2lbyyevrs.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hnxiangtu.top/Article/details/gt2pirfkzqo.html

Ruby: rescue ArgumentError => e
来源：http://dali.316326.xyz/Article/details/gt2fujlcjel.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2vebfhxcx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nwbrower.top/Article/details/gt2qmldojht.html

Py:   value = d.get("k") or default
来源：http://dali.daria6918.cn/Article/details/gt2yewbkoki.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.bjfxy.top/Article/details/gt2khpemurn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ydzc1.top/Article/details/gt2kzqmenfs.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258888.top/Article/details/gt2mimpxoxg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.mhx1999.top/Article/details/gt2jvhnxczb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jianghu66.top/Article/details/gt2wiibruel.html

Ruby: d&.dig(:a, :b)
来源：http://dali.redwolf501.top/Article/details/gt2mwyhaetq.html

C#:   obj?.A?.B ?? default
来源：http://dali.jyoumei.cn/Article/details/gt2obgpvuoh.html

[H07] 断言
来源：http://dali.guowangkeji.top/Article/details/gt2gxkliqep.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dsvbwqci.html

PHP:  assert($x > 0);
来源：http://dali.0kj1m.cn/Article/details/gt2jffcjsbi.html

JS:   console.assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gt2gembxgwj.html

TS:   console.assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gt2pailkyvz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2epotbadx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xuanzx.com/Article/details/gt2dszcdldx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.guowangkeji.top/Article/details/gt2yxlgciqy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gt2otrcemht.html

[H08] 获取错误信息与堆栈
来源：http://dali.ybcxt.top/Article/details/gt2srwnwuoq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.guowangkeji.top/Article/details/gt2khpacmrg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.meibo888.top/Article/details/gt2nocihkjh.html

JS:   e.message;  e.stack
来源：http://dali.haohaochexian.top/Article/details/gt2eoakhakb.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yuxming.cn/Article/details/gt2lphuwrqd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.vqdsnc.cn/Article/details/gt2vmqvtvul.html

Go:   err.Error()
来源：http://dali.sweek.top/Article/details/gt2tgeltjhz.html

Ruby: e.message;  e.backtrace
来源：http://dali.kuanghao11.cn/Article/details/gt2aazodlcs.html

C#:   e.Message;  e.StackTrace
来源：http://dali.dianchejie.cn/Article/details/gt2whaznbwz.html

[H09] 带错误码的异常
来源：http://dali.sufxvd.cn/Article/details/gt2ubjppouf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.chenzaomai.com/Article/details/gt2jcwxipun.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.aizwys.cn/Article/details/gt2fuccforz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.quarkkingdee.top/Article/details/gt2jcpgmcde.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yj20258.top/Article/details/gt2dgrvzmum.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yj20258888.top/Article/details/gt2unmidsav.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yanxiufei.cn/Article/details/gt2tnbhhrru.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhixingplan.top/Article/details/gt2ppqsmxct.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ybcxt.top/Article/details/gt2wrkcldtm.html

[H10] 资源自动释放
来源：http://dali.tian-w.cn/Article/details/gt2fjdbfuun.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hywenlv.cn/Article/details/gt2yoezyqgv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhongyouzk.top/Article/details/gt2rnkmxclj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hongshengwenyu.top/Article/details/gt2kknsoffi.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tian-w.cn/Article/details/gt2pubojbxs.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.aizwys.cn/Article/details/gt2hhyfemse.html

Go:   defer f.Close()
来源：http://dali.haohaochexian.top/Article/details/gt2nuhtibqg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yj20258888.top/Article/details/gt2hzpogxmu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yvedp.cn/Article/details/gt2ufvsuexg.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2qiwkqmfb.html

I. 正则表达式
来源：http://dali.316326.xyz/Article/details/gt2aaseqmlg.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2rbqukosj.html

[I01] 判断是否匹配
来源：http://dali.guannengcc.top/Article/details/gt2zuxdqwvd.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cqqwz.cn/Article/details/gt2mpkbioje.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.0kj1m.cn/Article/details/gt2uosvkptv.html

JS:   /\d+/.test(s)
来源：http://dali.c1oappe.top/Article/details/gt2rvnyodli.html

TS:   /\d+/.test(s)
来源：http://dali.redwolf501.top/Article/details/gt2jxppowmx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yj202588.top/Article/details/gt2eufkyjkz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj202588.top/Article/details/gt2boqbhawy.html

Ruby: s.match?(/\d+/)
来源：http://dali.yvedp.cn/Article/details/gt2rlimzzfz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.tianlin.xyz/Article/details/gt2bcrdbsrl.html

[I02] 提取所有匹配
来源：http://dali.jiagoushi.top/Article/details/gt2jrlxotzk.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ydzc1.top/Article/details/gt2hgrdsysh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.tian-w.cn/Article/details/gt2zmnxhghw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.nanxuanxn.top/Article/details/gt2gsalatet.html

TS:   s.match(/\d+/g)
来源：http://dali.xinyue.icu/Article/details/gt2gzhqvztl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yuanzhike.top/Article/details/gt2lcgukvpz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.vqdsnc.cn/Article/details/gt2qnneoazz.html

Ruby: s.scan(/\d+/)
来源：http://dali.wangshuangyany.cn/Article/details/gt2fysxgrzj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jyoumei.cn/Article/details/gt2sqyjdldn.html

[I03] 提取捕获分组
来源：http://dali.chenjidiqi.icu/Article/details/gt2damlomsr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cucudq.cn/Article/details/gt2zmmhnkyw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.pengpengdd.cyou/Article/details/gt2aexnkwmo.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.pengpengdd.cyou/Article/details/gt2vbtooxmy.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xylfe.cn/Article/details/gt2vutbckvg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hfpthk.cn/Article/details/gt2szehhdih.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.pengpengdd.cyou/Article/details/gt2pcirccfp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yj20258.top/Article/details/gt2zmzscnuj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cheryme.top/Article/details/gt2spwrrfmq.html

[I04] 正则替换
来源：http://dali.xinyue.icu/Article/details/gt2pqubrqkr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.aizwys.cn/Article/details/gt2dwodeefb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.c1oappe.top/Article/details/gt2xthtkgsg.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ppjwa.cn/Article/details/gt2fspnmhgf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hywenlv.cn/Article/details/gt2sdxoxiie.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sxryk.cn/Article/details/gt2bcuwvizl.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.aibaodan.cn/Article/details/gt2lladtbaw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.nanxuanxn.top/Article/details/gt2jjjtkgeo.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xziqi.cn/Article/details/gt2bxxcnxpl.html

[I05] 按正则拆分
来源：http://dali.zhiwuduotai.top/Article/details/gt2vrkvjisw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.fengsongda.top/Article/details/gt2sefnwhuk.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xziqi.cn/Article/details/gt2bxhylzhf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2otcfimcf.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lgxicpdl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jqgufenzy.top/Article/details/gt2zubkrpmv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.iojbl.cn/Article/details/gt2ohgvsxib.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gt2wiyrunfp.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.meibo888.top/Article/details/gt2trmclozt.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.nanxinkj.top/Article/details/gt2ehuocqie.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gt2orbjyjko.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cashguo.top/Article/details/gt2xiadjclz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.redwolf501.top/Article/details/gt2fgfwlzph.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cucudq.cn/Article/details/gt2tppdsqkt.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hysaishi.cn/Article/details/gt2qvfeuvum.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yongpay.top/Article/details/gt2plslvakb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hywenlv.cn/Article/details/gt2axvzszlp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gt2vojdqlcr.html

[I07] 忽略大小写与多行模式
来源：http://dali.ehwqpu.com/Article/details/gt2zibimeir.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.quarkkingdee.top/Article/details/gt2khbtgawc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yanxiufei.cn/Article/details/gt2npulhhnw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jlsjyb.cn/Article/details/gt2fcikgkyu.html

TS:   /error/gim
来源：http://dali.zhongyouzk.top/Article/details/gt2cqmvyerp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jyoumei.cn/Article/details/gt2dvqqiaxp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.dianchejie.cn/Article/details/gt2zxgngzlv.html

Ruby: s.scan(/error/i)
来源：http://dali.jqgufenzy.top/Article/details/gt2cubgnpgx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shangyingyoupin.top/Article/details/gt2dzoldyps.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhengqikj.top/Article/details/gt2kyckvikx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sxryk.cn/Article/details/gt2qaoillic.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.316326.xyz/Article/details/gt2tlpwhfsi.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daxiang520.top/Article/details/gt2frthuxfd.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ydzc1.top/Article/details/gt2hlpkclpi.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.chenjidiqi.icu/Article/details/gt2zvvzczkm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.tian-w.cn/Article/details/gt2kqbqbwth.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jqgfzy.top/Article/details/gt2btypusdc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xqzfakgl.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2fsttxtmx.html

J. 日期与时间
来源：http://dali.ehwqpu.com/Article/details/gt2potoazei.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2yjdnoojs.html

[J01] 获取当前时间
来源：http://dali.kuanghao11.cn/Article/details/gt2tlgqfrmr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj20258.top/Article/details/gt2fduqaqaa.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jiagoushi.top/Article/details/gt2tjnyssoe.html

JS:   new Date();  Date.now()
来源：http://dali.yongpay.top/Article/details/gt2fmbkdkjq.html

TS:   new Date();  Date.now()
来源：http://dali.meibo888.top/Article/details/gt2bcgjjgyh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cqqwz.cn/Article/details/gt2vqhurjxf.html

Go:   time.Now()
来源：http://dali.tianlin.xyz/Article/details/gt2aeoqrdqu.html

Ruby: Time.now
来源：http://dali.hfpthk.cn/Article/details/gt2fiztreji.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yongpay.top/Article/details/gt2ejhxrktp.html

[J02] 格式化输出
来源：http://dali.jlsjyb.cn/Article/details/gt2omlbyxag.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangshuangyany.cn/Article/details/gt2hgncdnph.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhiwuduotai.top/Article/details/gt2yrkvkonj.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhijiandao.cn/Article/details/gt2msppxfgc.html

TS:   d.toISOString()
来源：http://dali.gzhubu.top/Article/details/gt2ojgidlcd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cdnleiting.top/Article/details/gt2qwydwmfo.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ralutpgp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhongyouzk.top/Article/details/gt2xftbvqys.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yj202588.top/Article/details/gt2yxqdiifr.html

[J03] 字符串解析为日期
来源：http://dali.tanke756.top/Article/details/gt2qdjdgjqp.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xuanzx.com/Article/details/gt2jiuccibp.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj20258.top/Article/details/gt2mugjfpmf.html

JS:   new Date("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gt2oxmzjait.html

TS:   new Date("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gt2axydrhbt.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gt2zxltacvy.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gt2idfokapt.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gt2zpzxphui.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.fengsongda.top/Article/details/gt2mgnyrlwi.html

[J04] 时间戳与日期互转
来源：http://dali.zhijiandao.cn/Article/details/gt2otjokjgf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rnclcvmw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yueranfly.top/Article/details/gt2rwzeesxd.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.guannengcc.top/Article/details/gt2rllfpjcz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zyepnjal.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yanxiufei.cn/Article/details/gt2mnvnfphz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2fznaftlf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hysaishi.cn/Article/details/gt2bltypdkg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hfpthk.cn/Article/details/gt2pqwsgcti.html

[J05] 时间加减（加 7 天）
来源：http://dali.gogol.net.cn/Article/details/gt2gqkeahrr.html

Py:   now + timedelta(days=7)
来源：http://dali.birdmap.top/Article/details/gt2mtijmzfh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uyxjlbrn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fzhhl.top/Article/details/gt2wlbabzwv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hfpthk.cn/Article/details/gt2bjekglbf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.birdmap.top/Article/details/gt2jfdturzs.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hnxiangtu.top/Article/details/gt2ytgplrxf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.tanke756.top/Article/details/gt2tpasqswn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xuanzx.com/Article/details/gt2bohbogcu.html

[J06] 计算两时间之差
来源：http://dali.xziqi.cn/Article/details/gt2zzdlqhcl.html

Py:   (end - start).total_seconds()
来源：http://dali.yonumen.top/Article/details/gt2idaeztow.html

PHP:  $end->diff($start)->days;
来源：http://dali.andypj.xyz/Article/details/gt2ziqqifrf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aaoultza.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sysykeji.top/Article/details/gt2cjfcxzih.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cqqwz.cn/Article/details/gt2rolvgmdv.html

Go:   end.Sub(start).Hours()
来源：http://dali.kuanghao11.cn/Article/details/gt2zmpodmlh.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sweek.top/Article/details/gt2uihwrwoo.html

C#:   (end - start).TotalSeconds
来源：http://dali.svipenyu.cn/Article/details/gt2hbcpzwhr.html

[J07] 比较两个日期
来源：http://dali.nanxuanxn.top/Article/details/gt2asjfeeyv.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xuanzx.com/Article/details/gt2rxldejpm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.snrcjt.cn/Article/details/gt2rausdwck.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.aibaodan.cn/Article/details/gt2temtaphp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.tanke756.top/Article/details/gt2kutzkqgo.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.nwbrower.top/Article/details/gt2qlkhjknd.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.aizwys.cn/Article/details/gt2oxpkrssu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sufxvd.cn/Article/details/gt2qjksmgqe.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.tianlin.xyz/Article/details/gt2krxydvmm.html

[J08] 提取年月日与星期
来源：http://dali.gogol.net.cn/Article/details/gt2ogtwbbcv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yanxiufei.cn/Article/details/gt2nrqyckyx.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.feifeiyinyue.top/Article/details/gt2edfjkevk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hnxiangtu.top/Article/details/gt2sotyojcs.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.svipenyu.cn/Article/details/gt2enpfjeus.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.bjfxy.top/Article/details/gt2oqpkpyvk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jppwnhdd.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.316326.xyz/Article/details/gt2jmoooswt.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yj20258.top/Article/details/gt2xflhphda.html

[J09] 时区处理
来源：http://dali.jqgfzy.top/Article/details/gt2fsohuupp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gotoacloud.top/Article/details/gt2gmyljcte.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gaohongyu789.top/Article/details/gt2iejbxbzo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.kuanghao11.cn/Article/details/gt2qtwygddm.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.quarkkingdee.top/Article/details/gt2avwmonfc.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.0kj1m.cn/Article/details/gt2ohmwqatd.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bayjtgvm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.tianlin.xyz/Article/details/gt2tntvodos.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.daria6918.cn/Article/details/gt2fsxejqep.html

[J10] 取今天 / 本月第一天
来源：http://dali.jiagoushi.top/Article/details/gt2yjjrhmci.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.dashuyun.cn/Article/details/gt2ngplxbmf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yvedp.cn/Article/details/gt2lchhdpni.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sxryk.cn/Article/details/gt2vpcpyvpf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zdqjudy.top/Article/details/gt2pnnzbgpr.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sufxvd.cn/Article/details/gt2uudybdzz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinqigufen.top/Article/details/gt2jbnghxfw.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.nanxuanxn.top/Article/details/gt2nyqxtcfs.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jlsjyb.cn/Article/details/gt2hznyyobe.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2hrlnpehv.html

K. JSON 与序列化
来源：http://dali.nanxinkj.top/Article/details/gt2przyoicw.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2abqamuhd.html

[K01] 对象转 JSON 字符串
来源：http://dali.hongshengwenyu.top/Article/details/gt2dexseydc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.pycfn.com/Article/details/gt2fkvszyga.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kffmvgcv.html

JS:   JSON.stringify(obj)
来源：http://dali.c1oappe.top/Article/details/gt2hewnlcrr.html

TS:   JSON.stringify(obj)
来源：http://dali.yueranfly.top/Article/details/gt2pyhcgvuj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.daria6918.cn/Article/details/gt2ixxzwobu.html

Go:   json.Marshal(obj)
来源：http://dali.guannengcc.top/Article/details/gt2bgjgapzy.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yanxiufei.cn/Article/details/gt2nbralrfu.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cashguo.top/Article/details/gt2uacwrtzz.html

[K02] JSON 字符串转对象
来源：http://dali.havefunace.top/Article/details/gt2npksskzd.html

Py:   json.loads(s)
来源：http://dali.jiagoushi.top/Article/details/gt2iuvgqpua.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ydzc1.top/Article/details/gt2fdqxxmxl.html

JS:   JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gt2ysfbhbkc.html

TS:   JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gt2grozwwai.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jyoumei.cn/Article/details/gt2itdfjyxw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2luyhgwcz.html

Ruby: JSON.parse(s)
来源：http://dali.nwbrower.top/Article/details/gt2vthslstz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yj20258888.top/Article/details/gt2mrbhrord.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinqigfzy.top/Article/details/gt2repzdjkt.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.birdmap.top/Article/details/gt2avilbhno.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.nwbrower.top/Article/details/gt2eukjlwjc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gt2ksogersu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekbzujqw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.pycfn.com/Article/details/gt2psbcizee.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.0kj1m.cn/Article/details/gt2sgiatwla.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2mxeuugqz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jyoumei.cn/Article/details/gt2zcmmqtlk.html

[K04] 读取 JSON 文件
来源：http://dali.fzhhl.top/Article/details/gt2nxjlolmq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sysykeji.top/Article/details/gt2uatmyycp.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hnxiangtu.top/Article/details/gt2gazsucfi.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hammf.cn/Article/details/gt2hfcthtsj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cheryme.top/Article/details/gt2ugqnobja.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nanxuanxn.top/Article/details/gt2esucdfso.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.mhx1999.top/Article/details/gt2llrvjwpd.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2cmujgxrn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mvhvtjru.html

[K05] 深拷贝对象
来源：http://dali.c1oappe.top/Article/details/gt2wmdvisfw.html

Py:   copy.deepcopy(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vtmcplxt.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vdnedgwt.html

JS:   structuredClone(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qyozfwkz.html

TS:   structuredClone(obj)
来源：http://dali.sysykeji.top/Article/details/gt2jpwzkamf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xuetiantiany.cn/Article/details/gt2nvboffqr.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jiagoushi.top/Article/details/gt2rvknhzhj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jinqigufen.top/Article/details/gt2jjuixmrw.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.dianchejie.cn/Article/details/gt2xpxkdnzr.html


<!-- 参考信息 -->