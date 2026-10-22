代发 wailian999

C#:   record User(string Name, int Age);
来源：http://dali.yangfankeji.com/Article/details/gtufqoayoe.html

[G15] 枚举
来源：http://dali.kuanghao11.cn/Article/details/gtqvajilyw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.havefunace.top/Article/details/gtqomemyoy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj202588.top/Article/details/gtwpfujddt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenzaomai.com/Article/details/gtzfnhgoyy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pycfn.com/Article/details/gtfckdyojv.html

Java: enum Color { RED, GREEN }
来源：http://dali.sweek.top/Article/details/gtqhtuamvk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ydzc1.top/Article/details/gterngndpr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.mhx1999.top/Article/details/gtpejgcbua.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dianchejie.cn/Article/details/gtziustgqj.html

[G16] 对象转数组 / 字典
来源：http://dali.shuidangran.top/Article/details/gtuwmeafdk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ydzc1.top/Article/details/gtlutrwaff.html

PHP:  get_object_vars($obj);
来源：http://dali.aizwys.cn/Article/details/gtofajwvez.html

JS:   Object.entries(obj)
来源：http://dali.svipenyu.cn/Article/details/gtxuetltom.html

TS:   Object.entries(obj)
来源：http://dali.gogol.net.cn/Article/details/gtqlsbpviw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hnqzz.top/Article/details/gttohqyhoz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gogol.net.cn/Article/details/gtfeovyher.html

Ruby: obj.instance_variables
来源：http://dali.meibo888.top/Article/details/gtbkohxkow.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj202588.top/Article/details/gthpjihhod.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtodpaxlch.html

H. 异常与错误处理
来源：http://dali.haohaochexian.top/Article/details/gtgdmfulhu.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtrheyprsy.html

[H01] try / catch 基础
来源：http://dali.gogol.net.cn/Article/details/gtvngkrxls.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.havefunace.top/Article/details/gtfemdgjmi.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhixingplan.top/Article/details/gtjmddfpde.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.fengsongda.top/Article/details/gtrabnzxsw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.snrcjt.cn/Article/details/gtzipqooem.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cqqwz.cn/Article/details/gththzfnch.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xuanzx.com/Article/details/gtyaxlijhp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.smart0.xyz/Article/details/gtmtclxbfq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.chenjidiqi.icu/Article/details/gtlyfeynjm.html

[H02] finally / ensure 收尾
来源：http://dali.316326.xyz/Article/details/gtzpihimdx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmybshbye.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gtbpvvgklm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gthvoewavb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtluhgyvon.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtcacqznap.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.fzhhl.top/Article/details/gtasyuoigt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yonumen.top/Article/details/gtttefcyhy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gttvbrxkyn.html

[H03] 主动抛出异常
来源：http://dali.mhx1999.top/Article/details/gtjrdvpiam.html

Py:   raise ValueError("错误信息")
来源：http://dali.ppjwa.cn/Article/details/gtubvhqbod.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gtpmfkysru.html

JS:   throw new Error("错误信息");
来源：http://dali.hammf.cn/Article/details/gtzcntzmfu.html

TS:   throw new Error("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtntwhchol.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtwduwhkkw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.aizwys.cn/Article/details/gtbcbykvrf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tian-w.cn/Article/details/gtophdmwez.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtynthxpyk.html

[H04] 自定义异常类型
来源：http://dali.sufxvd.cn/Article/details/gtdwoypzmd.html

Py:   class MyError(Exception): pass
来源：http://dali.guowangkeji.top/Article/details/gttinvtzdf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jianghu66.top/Article/details/gtqicpazrr.html

JS:   class MyError extends Error {}
来源：http://dali.guowangkeji.top/Article/details/gtelstpumj.html

TS:   class MyError extends Error {}
来源：http://dali.cdnleiting.top/Article/details/gtspqoatah.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hnxiangtu.top/Article/details/gtakxhvgqc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.mhx1999.top/Article/details/gtfkxxnmez.html

Ruby: class MyError < StandardError; end
来源：http://dali.dashuyun.cn/Article/details/gtwdxavvst.html

C#:   class MyException : Exception {}
来源：http://dali.smart0.xyz/Article/details/gthtlvkltt.html

[H05] 捕获特定类型
来源：http://dali.xziqi.cn/Article/details/gtgayvctro.html

Py:   except ValueError as e:
来源：http://dali.c1oappe.top/Article/details/gtoyotzncc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cucudq.cn/Article/details/gtkdeobsxu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtrfcscrfp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.iojbl.cn/Article/details/gtprlozeui.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nanxinkj.top/Article/details/gtqegmffes.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hysaishi.cn/Article/details/gtmrpmvcfq.html

Ruby: rescue ArgumentError => e
来源：http://dali.nanxinkj.top/Article/details/gtbninyglr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtgwuxzxxd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.meibo888.top/Article/details/gtsqpezvms.html

Py:   value = d.get("k") or default
来源：http://dali.0kj1m.cn/Article/details/gtrqrauyya.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hysaishi.cn/Article/details/gtmcedazic.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sysykeji.top/Article/details/gtqdxvybyj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.iojbl.cn/Article/details/gtgzqfcvxz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ppjwa.cn/Article/details/gtpcwaangh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.snrcjt.cn/Article/details/gtaisteczn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shzxlz.cn/Article/details/gtcoishcxv.html

C#:   obj?.A?.B ?? default
来源：http://dali.yangfankeji.com/Article/details/gteqvgsaos.html

[H07] 断言
来源：http://dali.xziqi.cn/Article/details/gtfjamziyv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zdqjudy.top/Article/details/gtfucyknza.html

PHP:  assert($x > 0);
来源：http://dali.hammf.cn/Article/details/gtytsoyquu.html

JS:   console.assert(x > 0);
来源：http://dali.snrcjt.cn/Article/details/gtvhtaxwbu.html

TS:   console.assert(x > 0);
来源：http://dali.xylfe.cn/Article/details/gtifsgtkej.html

Java: assert x > 0 : "必须为正";
来源：http://dali.andypj.xyz/Article/details/gtbhryqmco.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.quarkkingdee.top/Article/details/gtjzzfeltl.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sufxvd.cn/Article/details/gtoqvvqwgg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yongpay.top/Article/details/gtwcndwuds.html

[H08] 获取错误信息与堆栈
来源：http://dali.mhx1999.top/Article/details/gtnanrfayq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zycfv.cn/Article/details/gtuahnpwhn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.chenjidiqi.icu/Article/details/gtdfotmero.html

JS:   e.message;  e.stack
来源：http://dali.shuidangran.top/Article/details/gtuwfedcxt.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ppjwa.cn/Article/details/gtjklmuvwk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yuanzhike.top/Article/details/gtubdkqqsm.html

Go:   err.Error()
来源：http://dali.zhoulong.xyz/Article/details/gtsohuopgd.html

Ruby: e.message;  e.backtrace
来源：http://dali.jyoumei.cn/Article/details/gtvrkxjqwt.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yonumen.top/Article/details/gtgcbuklmb.html

[H09] 带错误码的异常
来源：http://dali.zhengqikj.top/Article/details/gtlplcuyiq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jyoumei.cn/Article/details/gtjfyoofue.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yuanzhike.top/Article/details/gtlifsxsee.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.aibaodan.cn/Article/details/gtvkzfvsla.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sxryk.cn/Article/details/gttchqugin.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.daxiang520.top/Article/details/gtejipesta.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hywenlv.cn/Article/details/gtbemtourf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.quarkkingdee.top/Article/details/gtclnrcqmr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hfpthk.cn/Article/details/gtagmwootm.html

[H10] 资源自动释放
来源：http://dali.yongpay.top/Article/details/gtfbawxxhe.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.guowangkeji.top/Article/details/gtncvwriez.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yongpay.top/Article/details/gtldtfrkhw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ehwqpu.com/Article/details/gtdhqbaavn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxinkj.top/Article/details/gtcdwtquja.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yvedp.cn/Article/details/gtzqofcxnt.html

Go:   defer f.Close()
来源：http://dali.xziqi.cn/Article/details/gtrdjljewc.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.pycfn.com/Article/details/gttlnpolih.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtqvtgsdhn.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtwydjsacn.html

I. 正则表达式
来源：http://dali.gotoacloud.top/Article/details/gtxmdywsae.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtpwtpdzwa.html

[I01] 判断是否匹配
来源：http://dali.xuanzx.com/Article/details/gtadvackqq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.iojbl.cn/Article/details/gtvudarbtr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hfpthk.cn/Article/details/gtekhgfmql.html

JS:   /\d+/.test(s)
来源：http://dali.tianlin.xyz/Article/details/gtlyzdgqje.html

TS:   /\d+/.test(s)
来源：http://dali.aibaodan.cn/Article/details/gtrrfxxyxx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shanyushiyangtech.top/Article/details/gtvtitqqxn.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cqqwz.cn/Article/details/gtpisaduuf.html

Ruby: s.match?(/\d+/)
来源：http://dali.nanxinkj.top/Article/details/gtowuzjtdh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.haohaochexian.top/Article/details/gtnnoaxvwt.html

[I02] 提取所有匹配
来源：http://dali.xziqi.cn/Article/details/gtuzeqoozl.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cqqwz.cn/Article/details/gtkciobxch.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sysykeji.top/Article/details/gtzyjipkkw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.chenzaomai.com/Article/details/gtkbycrudz.html

TS:   s.match(/\d+/g)
来源：http://dali.nwbrower.top/Article/details/gtdgtnzcpe.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtxqjmonrz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.nanxinkj.top/Article/details/gtzwqrulas.html

Ruby: s.scan(/\d+/)
来源：http://dali.nanxinkj.top/Article/details/gtdlvdfbdj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.fzhhl.top/Article/details/gtuvlthllf.html

[I03] 提取捕获分组
来源：http://dali.pengpengdd.cyou/Article/details/gtjxcvuasu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ehwqpu.com/Article/details/gtzdmsemff.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.chenzaomai.com/Article/details/gtbdgnkvpg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.dianchejie.cn/Article/details/gtzgeqplnj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xinyue.icu/Article/details/gtjynksgws.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.pengpengdd.cyou/Article/details/gtpfllgxbi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yj20258.top/Article/details/gtbpvxtwwv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.haohaochexian.top/Article/details/gtwokbeaxi.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gtplspdhbo.html

[I04] 正则替换
来源：http://dali.yanxiufei.cn/Article/details/gtktutjaqc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gzhubu.top/Article/details/gtfgjsbtsy.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtzrjjkyxi.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gttvzcyaqa.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxuanxn.top/Article/details/gtyluzwsix.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.wangdashe.top/Article/details/gttxmfphud.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hysaishi.cn/Article/details/gtobnmoiha.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cheryme.top/Article/details/gtsfryjtjx.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shuidangran.top/Article/details/gtdyejgwpi.html

[I05] 按正则拆分
来源：http://dali.hnxiangtu.top/Article/details/gtmjxqwkgs.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.wangshuangyany.cn/Article/details/gtppfzszhu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yuxming.cn/Article/details/gtuvyokzwc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zdqjudy.top/Article/details/gtudxwrtti.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hysaishi.cn/Article/details/gthkxmbgar.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yj202588.top/Article/details/gtjuahztqr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.birdmap.top/Article/details/gtgokilttl.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.bjfxy.top/Article/details/gtjehlxfrs.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hysaishi.cn/Article/details/gtrkoqoqig.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xziqi.cn/Article/details/gttqxagkbk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.tanke756.top/Article/details/gthlogdpzp.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.dashuyun.cn/Article/details/gtxambrozi.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigfzy.top/Article/details/gtpcqqrjen.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xinyue.icu/Article/details/gtscsqsueu.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gtvvyfffzt.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sufxvd.cn/Article/details/gtlkmohacz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.dashuyun.cn/Article/details/gtaltobzru.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gtolkhzgba.html

[I07] 忽略大小写与多行模式
来源：http://dali.daria6918.cn/Article/details/gtbusslyex.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jlsjyb.cn/Article/details/gtytazszho.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.dashuyun.cn/Article/details/gthzyulgeq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yuanzhike.top/Article/details/gtgrpgtorv.html

TS:   /error/gim
来源：http://dali.tianlin.xyz/Article/details/gtkwsbkpps.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.chenlongwang.top/Article/details/gtmhwmytji.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhixingplan.top/Article/details/gtohzxqowg.html

Ruby: s.scan(/error/i)
来源：http://dali.yj202588.top/Article/details/gtlavmjilr.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhoulong.xyz/Article/details/gtcrgrqlbc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hammf.cn/Article/details/gtmmjbuqbm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yueranfly.top/Article/details/gtkzacimxx.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gtzhdjpbdf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxinkj.top/Article/details/gtzjokujjz.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhongyouzk.top/Article/details/gtiwyjkswl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.pycfn.com/Article/details/gtlzykcphn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhoulong.xyz/Article/details/gtnayasnhp.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yuxming.cn/Article/details/gtxuarqscm.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.havefunace.top/Article/details/gtugqwurul.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtktfwrjqt.html

J. 日期与时间
来源：http://dali.vqdsnc.cn/Article/details/gtjutegbjn.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtrnjyccgm.html

[J01] 获取当前时间
来源：http://dali.zycfv.cn/Article/details/gtaixtnjiz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yongpay.top/Article/details/gtwgzqktcn.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.nanxinkj.top/Article/details/gtrhngtolp.html

JS:   new Date();  Date.now()
来源：http://dali.haohaochexian.top/Article/details/gtktuhzqub.html

TS:   new Date();  Date.now()
来源：http://dali.cashguo.top/Article/details/gtlacjnufd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.daxiang520.top/Article/details/gtulgkeltc.html

Go:   time.Now()
来源：http://dali.zhiwuduotai.top/Article/details/gthteydgmq.html

Ruby: Time.now
来源：http://dali.guannengcc.top/Article/details/gtlloixhsl.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.dashuyun.cn/Article/details/gtdkflwxsx.html

[J02] 格式化输出
来源：http://dali.snrcjt.cn/Article/details/gtdmjrxfew.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenzaomai.com/Article/details/gtbgakfkdx.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.iojbl.cn/Article/details/gtmnlmkqzz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.redwolf501.top/Article/details/gtlrqgnvnf.html

TS:   d.toISOString()
来源：http://dali.jqgfzy.top/Article/details/gtkkcnxqly.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jianghu66.top/Article/details/gtnrvbqvus.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sufxvd.cn/Article/details/gtetsihygm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgufenzy.top/Article/details/gtgalmcipa.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gogol.net.cn/Article/details/gtdhduupau.html

[J03] 字符串解析为日期
来源：http://dali.hnqzz.top/Article/details/gthyktkcjx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xuetiantiany.cn/Article/details/gtyhyqvtgi.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ehwqpu.com/Article/details/gtykmwktso.html

JS:   new Date("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gtmfqjyulb.html

TS:   new Date("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gtqylrtcps.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gtxdouflna.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtdwojyprz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtkryenolf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jyoumei.cn/Article/details/gtcgqrflqb.html

[J04] 时间戳与日期互转
来源：http://dali.yj20258888.top/Article/details/gtmdaysmmb.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shangyingyoupin.top/Article/details/gtizexjodj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cheryme.top/Article/details/gtjmcuauay.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nanxuanxn.top/Article/details/gthrqnogkw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gaohongyu789.top/Article/details/gtdcskjbmj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.havefunace.top/Article/details/gtrgjllzpz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hfpthk.cn/Article/details/gtdsrnopya.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtteaoofep.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cucudq.cn/Article/details/gtotbyplrz.html

[J05] 时间加减（加 7 天）
来源：http://dali.sxryk.cn/Article/details/gtzfjjeujf.html

Py:   now + timedelta(days=7)
来源：http://dali.zhongyouzk.top/Article/details/gtjufektmc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.meibo888.top/Article/details/gteinathrg.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sweek.top/Article/details/gtfsapabwq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guannengcc.top/Article/details/gtoforsser.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gotoacloud.top/Article/details/gtxpyvxlao.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hammf.cn/Article/details/gtpzrtrzrl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ppjwa.cn/Article/details/gtffdtnfdv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.bjfxy.top/Article/details/gtkrnakjca.html

[J06] 计算两时间之差
来源：http://dali.daria6918.cn/Article/details/gtjtarjowt.html

Py:   (end - start).total_seconds()
来源：http://dali.hnxiangtu.top/Article/details/gttkuoulbo.html

PHP:  $end->diff($start)->days;
来源：http://dali.cucudq.cn/Article/details/gtzdochmwn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sxryk.cn/Article/details/gtimwllghv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.guannengcc.top/Article/details/gtwswqvbfs.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shzxlz.cn/Article/details/gtwbbtkewf.html

Go:   end.Sub(start).Hours()
来源：http://dali.hnxiangtu.top/Article/details/gtvbqkdlpr.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yonumen.top/Article/details/gtfqhnohkk.html

C#:   (end - start).TotalSeconds
来源：http://dali.xuanzx.com/Article/details/gtrwrxdois.html

[J07] 比较两个日期
来源：http://dali.daxiang520.top/Article/details/gtxqhjkpjf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.aibaodan.cn/Article/details/gtvowmaagn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.tian-w.cn/Article/details/gtswitvumn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.c1oappe.top/Article/details/gtynqhatfx.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.fengsongda.top/Article/details/gteuuubdqz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hnxiangtu.top/Article/details/gtaninmqoj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.nanxuanxn.top/Article/details/gtbegfomtb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.iojbl.cn/Article/details/gtyexfehcl.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.pengpengdd.cyou/Article/details/gtcjpvdcrq.html

[J08] 提取年月日与星期
来源：http://dali.hnxiangtu.top/Article/details/gtdihcqwht.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhongyouzk.top/Article/details/gtwfomxkbk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.tanke756.top/Article/details/gtthltbbic.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ybcxt.top/Article/details/gtuflwbmmn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yuxming.cn/Article/details/gthlxofutl.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.redwolf501.top/Article/details/gtzlosgrag.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.0kj1m.cn/Article/details/gtprdviswc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwpfuugqi.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hfpthk.cn/Article/details/gtbfqnykxh.html

[J09] 时区处理
来源：http://dali.gogol.net.cn/Article/details/gtgqxffcgj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gotoacloud.top/Article/details/gtamjzzogx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.tian-w.cn/Article/details/gtdxxlpckh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guowangkeji.top/Article/details/gtxydemxzh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuetiantiany.cn/Article/details/gtbnmlacki.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.0kj1m.cn/Article/details/gtonlmvksa.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jianghu66.top/Article/details/gtboecynnb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hfpthk.cn/Article/details/gtqjeomrmb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.smart0.xyz/Article/details/gtorsjjryn.html

[J10] 取今天 / 本月第一天
来源：http://dali.haohaochexian.top/Article/details/gtxjfbxbvm.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hysaishi.cn/Article/details/gtgzselygc.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zycfv.cn/Article/details/gtfsgfjopi.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yanxiufei.cn/Article/details/gtufiyqkaf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sweek.top/Article/details/gtdwxytmoq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.dianchejie.cn/Article/details/gtblsjopaw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xinyue.icu/Article/details/gtytmxjmbs.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.chenzaomai.com/Article/details/gtvjvpcjkn.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cashguo.top/Article/details/gtacnrxbtk.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtvrkzdqgs.html

K. JSON 与序列化
来源：http://dali.xuetiantiany.cn/Article/details/gtvxehjpkw.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtyjyzadfa.html

[K01] 对象转 JSON 字符串
来源：http://dali.jlsjyb.cn/Article/details/gtplkxaxmx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yvedp.cn/Article/details/gtblpulllt.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangtech.top/Article/details/gtefmhppmt.html

JS:   JSON.stringify(obj)
来源：http://dali.jqgfzy.top/Article/details/gtlszrlztz.html

TS:   JSON.stringify(obj)
来源：http://dali.dashuyun.cn/Article/details/gtqfyuyfwu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cashguo.top/Article/details/gtbuiyvkfi.html

Go:   json.Marshal(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtfejwtsnr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.aizwys.cn/Article/details/gtlsjqhaqf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtubhylqyt.html

[K02] JSON 字符串转对象
来源：http://dali.redwolf501.top/Article/details/gtomxizapo.html

Py:   json.loads(s)
来源：http://dali.yj202588.top/Article/details/gtrdqczkhn.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tanke756.top/Article/details/gthmrbmhci.html

JS:   JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gtmzhnkdjs.html

TS:   JSON.parse(s)
来源：http://dali.cdnleiting.top/Article/details/gtkcmgpqxv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yj202588.top/Article/details/gtqwekppqm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.chenjidiqi.icu/Article/details/gtjpgxicci.html

Ruby: JSON.parse(s)
来源：http://dali.zhoulong.xyz/Article/details/gtehuobzwq.html


<!-- 参考信息 -->