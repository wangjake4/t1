代发 wailian999

H. 异常与错误处理
来源：http://dali.kuanghao11.cn/Article/details/gtigufjedz.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtevingsgq.html

[H01] try / catch 基础
来源：http://dali.yj20258.top/Article/details/gthlqjrzbd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.meibo888.top/Article/details/gteovfcxup.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtmhecomtt.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmcqxnsaf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ivvv.top/Article/details/gtwnguzbup.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hfpthk.cn/Article/details/gtrmkoezgl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ppjwa.cn/Article/details/gtwnroesje.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.c1oappe.top/Article/details/gtubwsyqom.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zycfv.cn/Article/details/gthbtmtned.html

[H02] finally / ensure 收尾
来源：http://dali.ehwqpu.com/Article/details/gtczcjvjnv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gtxnhurcng.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtmcrnqjgv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gttylnhsha.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gtsdrhbdpu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gtlglpdfxp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.quarkkingdee.top/Article/details/gtmqzfupja.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.aizwys.cn/Article/details/gtswktinbb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtlfewwgdi.html

[H03] 主动抛出异常
来源：http://dali.xuetiantiany.cn/Article/details/gtpatxcjvk.html

Py:   raise ValueError("错误信息")
来源：http://dali.cucudq.cn/Article/details/gtfwmqwnsj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtccqravzu.html

JS:   throw new Error("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gtsxnzehoc.html

TS:   throw new Error("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gtqwwvgwhy.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.316326.xyz/Article/details/gtlucyouuc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hfpthk.cn/Article/details/gtcnkjfayk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tian-w.cn/Article/details/gthkdgqqry.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gtrnpegaqk.html

[H04] 自定义异常类型
来源：http://dali.yueranfly.top/Article/details/gtbrhhhmwi.html

Py:   class MyError(Exception): pass
来源：http://dali.nwbrower.top/Article/details/gtlgwxfkfv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shangyingyoupin.top/Article/details/gtiqpvudyt.html

JS:   class MyError extends Error {}
来源：http://dali.hammf.cn/Article/details/gtlnwwnzsx.html

TS:   class MyError extends Error {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrfbrjaen.html

Java: class MyException extends RuntimeException {}
来源：http://dali.chenlongwang.top/Article/details/gtawhcyqjt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gzhubu.top/Article/details/gttqdsedbm.html

Ruby: class MyError < StandardError; end
来源：http://dali.bjfxy.top/Article/details/gtheuqqmll.html

C#:   class MyException : Exception {}
来源：http://dali.cqqwz.cn/Article/details/gtfuhbvwau.html

[H05] 捕获特定类型
来源：http://dali.bjfxy.top/Article/details/gtfioqcpvl.html

Py:   except ValueError as e:
来源：http://dali.yangfankeji.com/Article/details/gtitqxeiez.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhengqikj.top/Article/details/gtbvgehdvh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.c1oappe.top/Article/details/gtnmsjyfai.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.daria6918.cn/Article/details/gtgymajtpi.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.0kj1m.cn/Article/details/gtbpmkigri.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsdqninxe.html

Ruby: rescue ArgumentError => e
来源：http://dali.jiagoushi.top/Article/details/gtezlmmxhx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.0kj1m.cn/Article/details/gtcqxjdocb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hywenlv.cn/Article/details/gthncppcyp.html

Py:   value = d.get("k") or default
来源：http://dali.xinyue.icu/Article/details/gtykefhtho.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yueranfly.top/Article/details/gtclpownba.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.mhx1999.top/Article/details/gtprbmwfwa.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.0kj1m.cn/Article/details/gtkpmexcbv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.nwbrower.top/Article/details/gtyqyynklz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gaohongyu789.top/Article/details/gtxepijwri.html

Ruby: d&.dig(:a, :b)
来源：http://dali.guannengcc.top/Article/details/gtssjyurfe.html

C#:   obj?.A?.B ?? default
来源：http://dali.sysykeji.top/Article/details/gtejedcxcp.html

[H07] 断言
来源：http://dali.shangyingyoupin.top/Article/details/gtmilbkqfw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ppjwa.cn/Article/details/gtgxrptvym.html

PHP:  assert($x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdwhgzurc.html

JS:   console.assert(x > 0);
来源：http://dali.smart0.xyz/Article/details/gtgxlzkelr.html

TS:   console.assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gtvbjxphfe.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tian-w.cn/Article/details/gtatspnqan.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hysaishi.cn/Article/details/gtujypwrtr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yongpay.top/Article/details/gthksvwszn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yangfankeji.com/Article/details/gtzpogcomn.html

[H08] 获取错误信息与堆栈
来源：http://dali.chenjidiqi.icu/Article/details/gtrxylivds.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hysaishi.cn/Article/details/gtkpqaxzxo.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.mhx1999.top/Article/details/gtndwllpea.html

JS:   e.message;  e.stack
来源：http://dali.chenzaomai.com/Article/details/gthszmphid.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenzaomai.com/Article/details/gtfnfavjpc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.0kj1m.cn/Article/details/gtjwaxsjpx.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gtatqnefhv.html

Ruby: e.message;  e.backtrace
来源：http://dali.havefunace.top/Article/details/gtsujafxwh.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhengqikj.top/Article/details/gteldughxx.html

[H09] 带错误码的异常
来源：http://dali.snrcjt.cn/Article/details/gtkdiytnwp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinghuilouyu.cn/Article/details/gtbkfjoxfq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.kuanghao11.cn/Article/details/gtsuvjetyl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.iojbl.cn/Article/details/gtvnavfrmh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jiagoushi.top/Article/details/gttmriusfk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenzaomai.com/Article/details/gtinuemnqv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gtughknkbd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tian-w.cn/Article/details/gtvouttxud.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jiagoushi.top/Article/details/gtwzgxztfk.html

[H10] 资源自动释放
来源：http://dali.shuidangran.top/Article/details/gtinotijvj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.9152youxi.cn/Article/details/gtsaejxhwz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jianghu66.top/Article/details/gtsrvnwgcy.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigufen.top/Article/details/gtizjowcto.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ehwqpu.com/Article/details/gtwnynsopz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yangfankeji.com/Article/details/gtaghuoxkh.html

Go:   defer f.Close()
来源：http://dali.zhoulong.xyz/Article/details/gtwhhonoao.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jianghu66.top/Article/details/gtjohikefl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtbgdlvygi.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gthjsjqcfv.html

I. 正则表达式
来源：http://dali.yonumen.top/Article/details/gtaakichef.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtirxiaupl.html

[I01] 判断是否匹配
来源：http://dali.gogol.net.cn/Article/details/gtjnwfzcjr.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jinqigufen.top/Article/details/gteuplpaix.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtdgjnbnfy.html

JS:   /\d+/.test(s)
来源：http://dali.gzhubu.top/Article/details/gtnpybgktj.html

TS:   /\d+/.test(s)
来源：http://dali.sweek.top/Article/details/gtkmyyprdd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtedzpunjj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.chenzaomai.com/Article/details/gtiixbxbst.html

Ruby: s.match?(/\d+/)
来源：http://dali.chenlongwang.top/Article/details/gtzjbfwajo.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.vqdsnc.cn/Article/details/gtvklkbfix.html

[I02] 提取所有匹配
来源：http://dali.tianlin.xyz/Article/details/gtfugayaho.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdvkffhxo.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yuanzhike.top/Article/details/gtrugfirns.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yvedp.cn/Article/details/gtkgatwljg.html

TS:   s.match(/\d+/g)
来源：http://dali.smart0.xyz/Article/details/gtumudufgt.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.bjfxy.top/Article/details/gtbqzvyngv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinqigufen.top/Article/details/gthywzsabu.html

Ruby: s.scan(/\d+/)
来源：http://dali.smart0.xyz/Article/details/gtpmawmsnr.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xylfe.cn/Article/details/gtpvhnymkp.html

[I03] 提取捕获分组
来源：http://dali.dashuyun.cn/Article/details/gtxnosochy.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nwbrower.top/Article/details/gteawlluod.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hnqzz.top/Article/details/gtvkdcifsr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhoulong.xyz/Article/details/gtoubvrlqy.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sxryk.cn/Article/details/gtablhijst.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhixingplan.top/Article/details/gttoqzmwnw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.svipenyu.cn/Article/details/gtkcxnwoce.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.aizwys.cn/Article/details/gtpbglswwx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jqgufenzy.top/Article/details/gtitfvcilf.html

[I04] 正则替换
来源：http://dali.ybcxt.top/Article/details/gtujffphhd.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.birdmap.top/Article/details/gtfcyabwfx.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.guowangkeji.top/Article/details/gtldwzeury.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ivvv.top/Article/details/gtuidvohcc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.smart0.xyz/Article/details/gtdcprdonz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.guannengcc.top/Article/details/gtbzjbqtir.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhixingplan.top/Article/details/gtyxnbkvvq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtoqyduyhu.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gotoacloud.top/Article/details/gtszbrifml.html

[I05] 按正则拆分
来源：http://dali.jianghu66.top/Article/details/gtgyhuinel.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shangyingyoupin.top/Article/details/gtohqhjyrq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ehwqpu.com/Article/details/gtxcczxqyt.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.snrcjt.cn/Article/details/gtfzwvkmkj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xinyue.icu/Article/details/gtufhahmee.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xuanzx.com/Article/details/gtiyfaloyr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gotoacloud.top/Article/details/gtoiceencb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jianghu66.top/Article/details/gtxswbhbsj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.quarkkingdee.top/Article/details/gtavmtwxib.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.pengpengdd.cyou/Article/details/gtbdoaqsxm.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zdqjudy.top/Article/details/gtklkhqjlo.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.tanke756.top/Article/details/gtrduakhom.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgfzy.top/Article/details/gtbjwyjqrt.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvgoipsfm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gtduwbteje.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.0kj1m.cn/Article/details/gtbxuqlotf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shzxlz.cn/Article/details/gtdnlkafxc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sufxvd.cn/Article/details/gtfhbddgjr.html

[I07] 忽略大小写与多行模式
来源：http://dali.tianlin.xyz/Article/details/gtwujwnzvi.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.daxiang520.top/Article/details/gtzroiepel.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ybcxt.top/Article/details/gtxqwhkzuk.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gotoacloud.top/Article/details/gtghgcvcvz.html

TS:   /error/gim
来源：http://dali.chenzaomai.com/Article/details/gtelcqxjcx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.vqdsnc.cn/Article/details/gtcxangrhg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.havefunace.top/Article/details/gtbimyknvz.html

Ruby: s.scan(/error/i)
来源：http://dali.zhengqikj.top/Article/details/gtmqrqznei.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zdqjudy.top/Article/details/gtelcnhrsn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yanxiufei.cn/Article/details/gtaptocria.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yongpay.top/Article/details/gtqtbyjzuc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.pengpengdd.cyou/Article/details/gtydvfjidv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ybcxt.top/Article/details/gtgndmzuwj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.c1oappe.top/Article/details/gttvkbplob.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.andypj.xyz/Article/details/gtbwgfdkgr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.pycfn.com/Article/details/gtpsabukyr.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cheryme.top/Article/details/gtwdaskniv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.mhx1999.top/Article/details/gtcbsysrno.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtwhvlrjjt.html

J. 日期与时间
来源：http://dali.yueranfly.top/Article/details/gtwpjisdzz.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtozjrqlhv.html

[J01] 获取当前时间
来源：http://dali.fzhhl.top/Article/details/gtunegygfw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hammf.cn/Article/details/gtuiygzfhj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.nanxuanxn.top/Article/details/gtmsldweyw.html

JS:   new Date();  Date.now()
来源：http://dali.chenjidiqi.icu/Article/details/gtwevimdxn.html

TS:   new Date();  Date.now()
来源：http://dali.wangshuangyany.cn/Article/details/gtawvmvdbo.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.chenjidiqi.icu/Article/details/gtqjejmtyn.html

Go:   time.Now()
来源：http://dali.zhoulong.xyz/Article/details/gtdqfahzzk.html

Ruby: Time.now
来源：http://dali.daria6918.cn/Article/details/gtkpzadbch.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhixingplan.top/Article/details/gtfkrljpbi.html

[J02] 格式化输出
来源：http://dali.nanxuanxn.top/Article/details/gtrkkbflym.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fzhhl.top/Article/details/gtfphzvaoe.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xinyue.icu/Article/details/gtyiawafny.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinqigfzy.top/Article/details/gtbuahgjsj.html

TS:   d.toISOString()
来源：http://dali.jinqigufen.top/Article/details/gtaqecjgan.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhijiandao.cn/Article/details/gtqepbxejt.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xziqi.cn/Article/details/gtlyisidqs.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yangfankeji.com/Article/details/gtsqniwsgf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.316326.xyz/Article/details/gteauyhkpn.html

[J03] 字符串解析为日期
来源：http://dali.andypj.xyz/Article/details/gtggesxtae.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.316326.xyz/Article/details/gtqnwsetei.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xziqi.cn/Article/details/gtpjqgtsyk.html

JS:   new Date("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gtugrvsvkh.html

TS:   new Date("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gtwljxcbzb.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gtqcutgoyv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gtjaavcuez.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gtugbmveof.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yvedp.cn/Article/details/gtolaoxtia.html

[J04] 时间戳与日期互转
来源：http://dali.tianlin.xyz/Article/details/gtzyofbafh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yj20258888.top/Article/details/gtekuvusyi.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.kuanghao11.cn/Article/details/gtvtmbvzjv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ybcxt.top/Article/details/gthkqswmgz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.9152youxi.cn/Article/details/gttpznsisj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.0kj1m.cn/Article/details/gthtiboryv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yvedp.cn/Article/details/gthrgabkce.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jyoumei.cn/Article/details/gtakpdlplb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhengqikj.top/Article/details/gtjovfutwk.html

[J05] 时间加减（加 7 天）
来源：http://dali.quarkkingdee.top/Article/details/gtwltvueos.html

Py:   now + timedelta(days=7)
来源：http://dali.yongpay.top/Article/details/gtqhlisuju.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.tian-w.cn/Article/details/gtwhmonaxd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangdashe.top/Article/details/gteubgikac.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shangyingyoupin.top/Article/details/gtauikhjnb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.haohaochexian.top/Article/details/gtpzyhubhk.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmkdkchlu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hnxiangtu.top/Article/details/gtawtewkyb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.meibo888.top/Article/details/gtbbzjhnhz.html

[J06] 计算两时间之差
来源：http://dali.0kj1m.cn/Article/details/gtgyyqflqr.html

Py:   (end - start).total_seconds()
来源：http://dali.gogol.net.cn/Article/details/gtrnftbllp.html

PHP:  $end->diff($start)->days;
来源：http://dali.vqdsnc.cn/Article/details/gtishuzqor.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yangfankeji.com/Article/details/gtebhnkehv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.pycfn.com/Article/details/gtohucvscq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jiagoushi.top/Article/details/gtiaxjuonf.html

Go:   end.Sub(start).Hours()
来源：http://dali.bjfxy.top/Article/details/gtxjeofyot.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xuetiantiany.cn/Article/details/gtzfcpyard.html

C#:   (end - start).TotalSeconds
来源：http://dali.sysykeji.top/Article/details/gthhnqimun.html

[J07] 比较两个日期
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtefkpkcur.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gtzdnvihkr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yueranfly.top/Article/details/gtcyepqjld.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigufen.top/Article/details/gtphehtwfs.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shzxlz.cn/Article/details/gtmesucyzs.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hfpthk.cn/Article/details/gtrjxjgqze.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ybcxt.top/Article/details/gtxmyfumkz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cdnleiting.top/Article/details/gterhsijdp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.9152youxi.cn/Article/details/gtpycefpgy.html

[J08] 提取年月日与星期
来源：http://dali.mhx1999.top/Article/details/gtmaznwous.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfsbaoops.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jyoumei.cn/Article/details/gtfzthlatm.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xylfe.cn/Article/details/gtugptsjmx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yangfankeji.com/Article/details/gtvsldgdjc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shzxlz.cn/Article/details/gtscakkzae.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hysaishi.cn/Article/details/gtkutafzgs.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.9152youxi.cn/Article/details/gtfubwrsvf.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinghuilouyu.cn/Article/details/gtczmcpakj.html

[J09] 时区处理
来源：http://dali.zhoulong.xyz/Article/details/gtwoqanceu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjgmuojgn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.nanxuanxn.top/Article/details/gtjgkapzhw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.meibo888.top/Article/details/gtbcrihydp.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xziqi.cn/Article/details/gtrvjbqwcp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yuanzhike.top/Article/details/gtiwkjiiyx.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinqigufen.top/Article/details/gthziztolw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.svipenyu.cn/Article/details/gtggcgkwfq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhijiandao.cn/Article/details/gthtpylrsi.html

[J10] 取今天 / 本月第一天
来源：http://dali.shanyushiyangtech.top/Article/details/gtxbtwului.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvkmwrnim.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ydzc1.top/Article/details/gtuhlczclc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cucudq.cn/Article/details/gtanavmrjf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtcdoxuodr.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cqqwz.cn/Article/details/gtggogbzqo.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yueranfly.top/Article/details/gtefnklgoc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gaohongyu789.top/Article/details/gtthrwmrpn.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhixingplan.top/Article/details/gtnszjgxoe.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtnogxaqst.html

K. JSON 与序列化
来源：http://dali.haohaochexian.top/Article/details/gtdiyctygd.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gteqhiktet.html

[K01] 对象转 JSON 字符串
来源：http://dali.0kj1m.cn/Article/details/gtmzhylgjr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.svipenyu.cn/Article/details/gtftpvuoev.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.quarkkingdee.top/Article/details/gtlpbiygvn.html

JS:   JSON.stringify(obj)
来源：http://dali.yj20258888.top/Article/details/gtsrmsovde.html

TS:   JSON.stringify(obj)
来源：http://dali.guannengcc.top/Article/details/gttbkyzdha.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinyuanbaomall.cn/Article/details/gtipurcgzr.html

Go:   json.Marshal(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtmfnrujfj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sweek.top/Article/details/gthhnwwelx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtpywiizdg.html

[K02] JSON 字符串转对象
来源：http://dali.yj202588.top/Article/details/gtbiukkczg.html

Py:   json.loads(s)
来源：http://dali.jinqigfzy.top/Article/details/gtniposoaa.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuhctvoxg.html

JS:   JSON.parse(s)
来源：http://dali.yuanzhike.top/Article/details/gtkgroedaf.html

TS:   JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gtgswdvfqd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yvedp.cn/Article/details/gtirsentho.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yj20258.top/Article/details/gthqmnugmb.html

Ruby: JSON.parse(s)
来源：http://dali.fzhhl.top/Article/details/gtlzkbedir.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gotoacloud.top/Article/details/gtrnvmccbj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.chenjidiqi.icu/Article/details/gtwtleyxsb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ehwqpu.com/Article/details/gtqejiwsqv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jlsjyb.cn/Article/details/gtqkhnwkts.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xziqi.cn/Article/details/gtleestjxg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gtgmginkns.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ybcxt.top/Article/details/gtbapdqnws.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.haohaochexian.top/Article/details/gtivqfraxi.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xylfe.cn/Article/details/gtqevillub.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.haohaochexian.top/Article/details/gttliomsqv.html

[K04] 读取 JSON 文件
来源：http://dali.andypj.xyz/Article/details/gtfhqgsrib.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.guannengcc.top/Article/details/gtrrlpiwrn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zdqjudy.top/Article/details/gtqjruxphp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xziqi.cn/Article/details/gtoltlwppl.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.c1oappe.top/Article/details/gtvdvbvwln.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cashguo.top/Article/details/gtaneltxcd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cashguo.top/Article/details/gtzejfnjqv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinqigufen.top/Article/details/gteqhnqqzf.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ybcxt.top/Article/details/gtkgpxeuqw.html

[K05] 深拷贝对象
来源：http://dali.wangdashe.top/Article/details/gtanhmhneh.html


<!-- 参考信息 -->