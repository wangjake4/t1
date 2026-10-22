代发 wailian999

C#:   record User(string Name, int Age);
来源：http://dali.ydzc1.top/Article/details/gtycisvylp.html

[G15] 枚举
来源：http://dali.haohaochexian.top/Article/details/gtbcxqigso.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sweek.top/Article/details/gtdaqbxuko.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj202588.top/Article/details/gtqouiktgu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hnqzz.top/Article/details/gtckrcvjvv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.meibo888.top/Article/details/gtlvhrkmfu.html

Java: enum Color { RED, GREEN }
来源：http://dali.snrcjt.cn/Article/details/gtrfqisimr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tian-w.cn/Article/details/gtavjhukwj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.daria6918.cn/Article/details/gtcykckklb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pycfn.com/Article/details/gtczdkgsuu.html

[G16] 对象转数组 / 字典
来源：http://dali.xziqi.cn/Article/details/gtgxqcyrtv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sweek.top/Article/details/gtdxsouyfw.html

PHP:  get_object_vars($obj);
来源：http://dali.zhoulong.xyz/Article/details/gtgxalcrmo.html

JS:   Object.entries(obj)
来源：http://dali.316326.xyz/Article/details/gtidymtgcs.html

TS:   Object.entries(obj)
来源：http://dali.guowangkeji.top/Article/details/gtvlsbcgsr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgonrhzlq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.fzhhl.top/Article/details/gtfxohwmqf.html

Ruby: obj.instance_variables
来源：http://dali.c1oappe.top/Article/details/gtasrqaumn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtylpgfxdu.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtllzsfieh.html

H. 异常与错误处理
来源：http://dali.hongshengwenyu.top/Article/details/gtotxixhnz.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtfcddbsaq.html

[H01] try / catch 基础
来源：http://dali.dashuyun.cn/Article/details/gtbozytgbp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ppjwa.cn/Article/details/gtejxpqlqn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhengqikj.top/Article/details/gthtwlkrmu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sxryk.cn/Article/details/gtvmuesjbt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jyoumei.cn/Article/details/gtqyitptrm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jqgfzy.top/Article/details/gtknhnayww.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hysaishi.cn/Article/details/gtvsnqwtvd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gotoacloud.top/Article/details/gtgyrvoqnz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xinyue.icu/Article/details/gtneynsfxb.html

[H02] finally / ensure 收尾
来源：http://dali.dianchejie.cn/Article/details/gtcgdiecry.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xinyue.icu/Article/details/gteijcuwuq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtfbdunujm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gtztgstflz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gtcotnxcfr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gtvjfwnpjs.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.bjfxy.top/Article/details/gtxiasckvy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hammf.cn/Article/details/gtxjstgmdd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gtwtmcbzgv.html

[H03] 主动抛出异常
来源：http://dali.guowangkeji.top/Article/details/gtebjylvbc.html

Py:   raise ValueError("错误信息")
来源：http://dali.havefunace.top/Article/details/gtedwsutuc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtmxmsgkhz.html

JS:   throw new Error("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtrslebqpu.html

TS:   throw new Error("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtxqsjmmfu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gtfttrxlck.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.havefunace.top/Article/details/gtuhwbsbjv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.0kj1m.cn/Article/details/gtgbbehmsa.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gtaaiokjhl.html

[H04] 自定义异常类型
来源：http://dali.yuxming.cn/Article/details/gtrfdrffdu.html

Py:   class MyError(Exception): pass
来源：http://dali.9152youxi.cn/Article/details/gtwmgemfdb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ydzc1.top/Article/details/gtideeokcs.html

JS:   class MyError extends Error {}
来源：http://dali.yj20258888.top/Article/details/gtokulpppx.html

TS:   class MyError extends Error {}
来源：http://dali.9152youxi.cn/Article/details/gtxoreuwcp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shzxlz.cn/Article/details/gtfzmamaew.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinqigfzy.top/Article/details/gtyjsmyics.html

Ruby: class MyError < StandardError; end
来源：http://dali.guowangkeji.top/Article/details/gtlfkcedqi.html

C#:   class MyException : Exception {}
来源：http://dali.ivvv.top/Article/details/gtlpmpxpoc.html

[H05] 捕获特定类型
来源：http://dali.chenjidiqi.icu/Article/details/gtyybamzco.html

Py:   except ValueError as e:
来源：http://dali.havefunace.top/Article/details/gtbzjbmhwd.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yueranfly.top/Article/details/gtmweajlei.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yuxming.cn/Article/details/gtzbtxtnll.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtwcyvsmut.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ybcxt.top/Article/details/gtcqgrcoxp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yj20258888.top/Article/details/gtmjonlymf.html

Ruby: rescue ArgumentError => e
来源：http://dali.fengsongda.top/Article/details/gtckjxfdys.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cqqwz.cn/Article/details/gtfrzuyvux.html

[H06] 可选值 / 空值安全访问
来源：http://dali.aibaodan.cn/Article/details/gtessqyndi.html

Py:   value = d.get("k") or default
来源：http://dali.wangshuangyany.cn/Article/details/gtfztmjyfw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hnqzz.top/Article/details/gtonolceil.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yonumen.top/Article/details/gtsdtrfpop.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkcnvajin.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpxhnaybi.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jqgufenzy.top/Article/details/gtmyhlumlg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tianlin.xyz/Article/details/gtlmibmfhn.html

C#:   obj?.A?.B ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gtdnmqorrn.html

[H07] 断言
来源：http://dali.cashguo.top/Article/details/gtrknrbgnq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cashguo.top/Article/details/gtwtvomqnn.html

PHP:  assert($x > 0);
来源：http://dali.ehwqpu.com/Article/details/gtmffntdhj.html

JS:   console.assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gtuvkjxvho.html

TS:   console.assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gtkjieyypc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hongshengwenyu.top/Article/details/gtetwgbgmh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gzhubu.top/Article/details/gtbqwkvesw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.pycfn.com/Article/details/gteizmneet.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yj20258888.top/Article/details/gtzisdocnb.html

[H08] 获取错误信息与堆栈
来源：http://dali.yj202588.top/Article/details/gtecdlvowe.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xziqi.cn/Article/details/gtyemxrusu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.redwolf501.top/Article/details/gtaksguydo.html

JS:   e.message;  e.stack
来源：http://dali.redwolf501.top/Article/details/gtzqjygtle.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zycfv.cn/Article/details/gtpxnmdqrc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.pycfn.com/Article/details/gtvfdvlndl.html

Go:   err.Error()
来源：http://dali.aizwys.cn/Article/details/gtmwoctaju.html

Ruby: e.message;  e.backtrace
来源：http://dali.ehwqpu.com/Article/details/gtkbqwaovp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcehaaspv.html

[H09] 带错误码的异常
来源：http://dali.vqdsnc.cn/Article/details/gtlgcgyylj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.tianlin.xyz/Article/details/gtduvzstly.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhongyouzk.top/Article/details/gtdwbzwdpa.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gzhubu.top/Article/details/gtacxuxzyo.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.redwolf501.top/Article/details/gtkbhucdqs.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.pengpengdd.cyou/Article/details/gtdlllttoq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinghuilouyu.cn/Article/details/gtytzgywjm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jiagoushi.top/Article/details/gtqgvczrwr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhiwuduotai.top/Article/details/gtaoojccer.html

[H10] 资源自动释放
来源：http://dali.iojbl.cn/Article/details/gthxijxnce.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yonumen.top/Article/details/gtbcacxepn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gaohongyu789.top/Article/details/gtjbgnnzcc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.bjfxy.top/Article/details/gteobrkcxr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sufxvd.cn/Article/details/gtwincopfq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.haohaochexian.top/Article/details/gtxvvzatpw.html

Go:   defer f.Close()
来源：http://dali.zhongyouzk.top/Article/details/gtkqabcdvk.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrtkavxnp.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtllvpaprk.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gthpanghdo.html

I. 正则表达式
来源：http://dali.sysykeji.top/Article/details/gtrghideob.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtytathxxo.html

[I01] 判断是否匹配
来源：http://dali.wangdashe.top/Article/details/gtmnpdppyg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hysaishi.cn/Article/details/gtrtacagbu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinqigufen.top/Article/details/gtuwlhealp.html

JS:   /\d+/.test(s)
来源：http://dali.hfpthk.cn/Article/details/gtwfctqyfe.html

TS:   /\d+/.test(s)
来源：http://dali.svipenyu.cn/Article/details/gtbozwwimb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.pengpengdd.cyou/Article/details/gtddflwztm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sweek.top/Article/details/gtjvvczpuz.html

Ruby: s.match?(/\d+/)
来源：http://dali.yueranfly.top/Article/details/gtfmfiyehf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.sweek.top/Article/details/gtlxiuuadd.html

[I02] 提取所有匹配
来源：http://dali.chenjidiqi.icu/Article/details/gtrnaezene.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yanxiufei.cn/Article/details/gtwqylsouf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hammf.cn/Article/details/gtgfvaylef.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.smart0.xyz/Article/details/gtdaoyjlmz.html

TS:   s.match(/\d+/g)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmlypuakz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cashguo.top/Article/details/gtaomdbqss.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yongpay.top/Article/details/gtfasjvrbx.html

Ruby: s.scan(/\d+/)
来源：http://dali.guannengcc.top/Article/details/gtewzitsrx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cashguo.top/Article/details/gthlmloxal.html

[I03] 提取捕获分组
来源：http://dali.shzxlz.cn/Article/details/gtmvhbwnoq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.snrcjt.cn/Article/details/gtzgtgtqtu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhengqikj.top/Article/details/gtxudzhtjw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zdqjudy.top/Article/details/gtwgfdgkal.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gotoacloud.top/Article/details/gtpalxzcyv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yuanzhike.top/Article/details/gtrgcjqvhj.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jqgufenzy.top/Article/details/gtkegodkzz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yuanzhike.top/Article/details/gttzepapee.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.c1oappe.top/Article/details/gtbsywnpfs.html

[I04] 正则替换
来源：http://dali.chenlongwang.top/Article/details/gttvvjnjfc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.redwolf501.top/Article/details/gtgvzncnlq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtjzjtslnw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hysaishi.cn/Article/details/gtwjwbnkwj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ehwqpu.com/Article/details/gthpixyknb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hysaishi.cn/Article/details/gtucvdhbwu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.aizwys.cn/Article/details/gtdfnysozp.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jlsjyb.cn/Article/details/gtsgwddgvw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sufxvd.cn/Article/details/gtuhlkkeap.html

[I05] 按正则拆分
来源：http://dali.smart0.xyz/Article/details/gtroqyuphq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.svipenyu.cn/Article/details/gtgjhensat.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hnqzz.top/Article/details/gttjbixjmd.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gtisuzvzby.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gogol.net.cn/Article/details/gtwupnxrji.html

Java: s.split("\\s*,\\s*")
来源：http://dali.chenlongwang.top/Article/details/gtmkhobjef.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yonumen.top/Article/details/gteydznqnb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sxryk.cn/Article/details/gtkhtjhnhi.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jlsjyb.cn/Article/details/gtpmkztrst.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.smart0.xyz/Article/details/gtssmfdvae.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhongyouzk.top/Article/details/gtqafyqmis.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sxryk.cn/Article/details/gtxwlbcdqm.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangshuangyany.cn/Article/details/gtqupxibbc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xylfe.cn/Article/details/gtarnazcnq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.tanke756.top/Article/details/gtzgrtxvlq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shuidangran.top/Article/details/gtjsqindom.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hysaishi.cn/Article/details/gtfmyhgcpx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.nanxuanxn.top/Article/details/gtkwdouckh.html

[I07] 忽略大小写与多行模式
来源：http://dali.xinyue.icu/Article/details/gtikxbxexu.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.quarkkingdee.top/Article/details/gtfhyugrqp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenzaomai.com/Article/details/gtinojfgcx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.wangshuangyany.cn/Article/details/gtcbbeoqfb.html

TS:   /error/gim
来源：http://dali.kuanghao11.cn/Article/details/gtdcwstoxq.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.tian-w.cn/Article/details/gtejlnzgpi.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yueranfly.top/Article/details/gtxrwxscwd.html

Ruby: s.scan(/error/i)
来源：http://dali.shuidangran.top/Article/details/gtaiusacsy.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinqigufen.top/Article/details/gttuajzhhd.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cucudq.cn/Article/details/gthaebjkkq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.feifeiyinyue.top/Article/details/gtopwcbayo.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.andypj.xyz/Article/details/gtexjxyffi.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yonumen.top/Article/details/gtrjoxkjra.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenlongwang.top/Article/details/gthzqifhab.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tian-w.cn/Article/details/gtjzhslqld.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.tanke756.top/Article/details/gtavniqjnt.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.0kj1m.cn/Article/details/gtbystesgs.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jqgfzy.top/Article/details/gtmxjqynql.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtfchknikn.html

J. 日期与时间
来源：http://dali.fzhhl.top/Article/details/gtinltpqnp.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtuwnfqxby.html

[J01] 获取当前时间
来源：http://dali.quarkkingdee.top/Article/details/gthopvtwhy.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shangyingyoupin.top/Article/details/gtjetttvbe.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.daria6918.cn/Article/details/gtoiaxsyzz.html

JS:   new Date();  Date.now()
来源：http://dali.cucudq.cn/Article/details/gtprnndntz.html

TS:   new Date();  Date.now()
来源：http://dali.xziqi.cn/Article/details/gtdutkzify.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yangfankeji.com/Article/details/gtgquokeck.html

Go:   time.Now()
来源：http://dali.yangfankeji.com/Article/details/gterixgzjf.html

Ruby: Time.now
来源：http://dali.tian-w.cn/Article/details/gtefluriok.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yongpay.top/Article/details/gtoahvilpx.html

[J02] 格式化输出
来源：http://dali.wangdashe.top/Article/details/gteqgshdyz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fzhhl.top/Article/details/gtvsrlwleu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jiagoushi.top/Article/details/gtosujhudf.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xylfe.cn/Article/details/gtaistgste.html

TS:   d.toISOString()
来源：http://dali.sweek.top/Article/details/gtlmditpqt.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ydzc1.top/Article/details/gtyqfumvwo.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sweek.top/Article/details/gtslfmcalv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hammf.cn/Article/details/gtydfzvlzg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.quarkkingdee.top/Article/details/gtexlijyxm.html

[J03] 字符串解析为日期
来源：http://dali.jlsjyb.cn/Article/details/gtpursdjgh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.fengsongda.top/Article/details/gtwbpyvgkt.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hfpthk.cn/Article/details/gtfxpwrrpk.html

JS:   new Date("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gteirxkezi.html

TS:   new Date("2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gtmtdepdcg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gtnzdrygcw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gtzhsnokjx.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gtebakmqbc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.316326.xyz/Article/details/gtcqjjrwrc.html

[J04] 时间戳与日期互转
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwjeectxm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gtppvednlw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.nanxuanxn.top/Article/details/gtciubffhz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.dashuyun.cn/Article/details/gtrxntmsvp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hongshengwenyu.top/Article/details/gtahfipxul.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gogol.net.cn/Article/details/gtlldjyjmp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xziqi.cn/Article/details/gttrwccryi.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.chenjidiqi.icu/Article/details/gtujhlnzgj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.smart0.xyz/Article/details/gttvkwlwis.html

[J05] 时间加减（加 7 天）
来源：http://dali.0kj1m.cn/Article/details/gtafwuqxpl.html

Py:   now + timedelta(days=7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtalzevyjv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jianghu66.top/Article/details/gtxewqlvwi.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.bjfxy.top/Article/details/gtkzdypyvg.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yanxiufei.cn/Article/details/gtfpgbrrzs.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ppjwa.cn/Article/details/gtupwewgvc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yueranfly.top/Article/details/gtdlqvyzqz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hnqzz.top/Article/details/gthsoahlgp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.daxiang520.top/Article/details/gtpoghugsx.html

[J06] 计算两时间之差
来源：http://dali.cqqwz.cn/Article/details/gtftulhsst.html

Py:   (end - start).total_seconds()
来源：http://dali.zdqjudy.top/Article/details/gtxvkctjuw.html

PHP:  $end->diff($start)->days;
来源：http://dali.svipenyu.cn/Article/details/gtsjgijntt.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ehwqpu.com/Article/details/gtbttylgzq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cqqwz.cn/Article/details/gtmccvrmaa.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwonvunii.html

Go:   end.Sub(start).Hours()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmeclzags.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cheryme.top/Article/details/gttyyrrgcq.html

C#:   (end - start).TotalSeconds
来源：http://dali.jiagoushi.top/Article/details/gtpkcjyere.html

[J07] 比较两个日期
来源：http://dali.svipenyu.cn/Article/details/gtafskjnai.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shangyingyoupin.top/Article/details/gteftkcvib.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.pengpengdd.cyou/Article/details/gtrxfephmi.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhongyouzk.top/Article/details/gtbfxikjbo.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.daria6918.cn/Article/details/gttcnemyqh.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.pengpengdd.cyou/Article/details/gtsnmkjevb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhengqikj.top/Article/details/gtcphuffen.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnkzajnao.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.nwbrower.top/Article/details/gtpbhmalkx.html

[J08] 提取年月日与星期
来源：http://dali.xuetiantiany.cn/Article/details/gtkyzjorxv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.nanxuanxn.top/Article/details/gtvkfkgnhv.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.bjfxy.top/Article/details/gtfyeqooha.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinqigufen.top/Article/details/gtghxvsljp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cqqwz.cn/Article/details/gtpycdyfxl.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.meibo888.top/Article/details/gtzaokljpg.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yuxming.cn/Article/details/gtrmddqcog.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.nanxinkj.top/Article/details/gtkieqwkvm.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.dashuyun.cn/Article/details/gtfarteesi.html

[J09] 时区处理
来源：http://dali.sysykeji.top/Article/details/gtdezakekb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.svipenyu.cn/Article/details/gtckgvzbjh.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.kuanghao11.cn/Article/details/gtqawbbptj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sweek.top/Article/details/gtekzmhncs.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.vqdsnc.cn/Article/details/gthtkbgket.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.dianchejie.cn/Article/details/gtufjcmiwl.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.guannengcc.top/Article/details/gtbhflfykq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhiwuduotai.top/Article/details/gtwmzwyuui.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.iojbl.cn/Article/details/gtpppjbjtp.html

[J10] 取今天 / 本月第一天
来源：http://dali.iojbl.cn/Article/details/gtftdngymk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shzxlz.cn/Article/details/gtctsiynpn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhengqikj.top/Article/details/gtlrgtvrsj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.chenzaomai.com/Article/details/gttcapksla.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtaxuztjun.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hywenlv.cn/Article/details/gtheariasz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hammf.cn/Article/details/gtjpnwltvo.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.mhx1999.top/Article/details/gthywkgqcr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sweek.top/Article/details/gtteujrpyj.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtxyeemaqp.html

K. JSON 与序列化
来源：http://dali.cashguo.top/Article/details/gtntmyfiwl.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtrnndmsfi.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhengqikj.top/Article/details/gtglfzvbiz.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.nwbrower.top/Article/details/gtfkovvnop.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.fengsongda.top/Article/details/gtihohxjqt.html

JS:   JSON.stringify(obj)
来源：http://dali.sxryk.cn/Article/details/gtfrjnefbv.html

TS:   JSON.stringify(obj)
来源：http://dali.wangdashe.top/Article/details/gteozmczvu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.0kj1m.cn/Article/details/gtjewaddmy.html

Go:   json.Marshal(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtolhpnekh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.quarkkingdee.top/Article/details/gtufhehopx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yj20258888.top/Article/details/gtqgyhauix.html

[K02] JSON 字符串转对象
来源：http://dali.zhijiandao.cn/Article/details/gtsfozpqgk.html

Py:   json.loads(s)
来源：http://dali.hysaishi.cn/Article/details/gtewwywobi.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xuanzx.com/Article/details/gtqkpfccoe.html

JS:   JSON.parse(s)
来源：http://dali.cheryme.top/Article/details/gtpwonqtyb.html

TS:   JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gtegwyywlc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hysaishi.cn/Article/details/gtcsqzecmo.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.fzhhl.top/Article/details/gtzeryurip.html

Ruby: JSON.parse(s)
来源：http://dali.ybcxt.top/Article/details/gtmzkalkwh.html


<!-- 参考信息 -->