代发 wailian999

C#:   record User(string Name, int Age);
来源：http://dali.ppjwa.cn/Article/details/gttzijudfv.html

[G15] 枚举
来源：http://dali.dianchejie.cn/Article/details/gteyhkrgzo.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yanxiufei.cn/Article/details/gtrqioxdjz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.fengsongda.top/Article/details/gtinwmftsl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xziqi.cn/Article/details/gtualxaqpb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhengqikj.top/Article/details/gtwzgxcgwa.html

Java: enum Color { RED, GREEN }
来源：http://dali.guowangkeji.top/Article/details/gtfchnaeyu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.svipenyu.cn/Article/details/gttkafipnr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yongpay.top/Article/details/gtnlggtryi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gtpfpjydwx.html

[G16] 对象转数组 / 字典
来源：http://dali.guowangkeji.top/Article/details/gtuvpoatpn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tian-w.cn/Article/details/gtqisghcyj.html

PHP:  get_object_vars($obj);
来源：http://dali.yongpay.top/Article/details/gtljoxhwsv.html

JS:   Object.entries(obj)
来源：http://dali.sysykeji.top/Article/details/gtnwrwaida.html

TS:   Object.entries(obj)
来源：http://dali.xuanzx.com/Article/details/gtzofcyhtx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ydzc1.top/Article/details/gtnmumboeg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinqigfzy.top/Article/details/gtulnrihsm.html

Ruby: obj.instance_variables
来源：http://dali.xziqi.cn/Article/details/gtdkevmzpl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqnjasivh.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtzuskyogc.html

H. 异常与错误处理
来源：http://dali.jinqigfzy.top/Article/details/gtetrtjsai.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtafpjxzxy.html

[H01] try / catch 基础
来源：http://dali.birdmap.top/Article/details/gtgcuruzrc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.daria6918.cn/Article/details/gtlpdugcwy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jianghu66.top/Article/details/gtbjttioep.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.smart0.xyz/Article/details/gtjxhxkssu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yuxming.cn/Article/details/gtunyxdqhd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.tianlin.xyz/Article/details/gtlstgbhum.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shzxlz.cn/Article/details/gtzmzeifgb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gaohongyu789.top/Article/details/gtjypxlhex.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhiwuduotai.top/Article/details/gtfvfhntfw.html

[H02] finally / ensure 收尾
来源：http://dali.jinqigufen.top/Article/details/gtbfdctaqa.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.fzhhl.top/Article/details/gtjjblcwvx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtrufyebws.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gtjcclpjzz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtbmooyyya.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gttbhcybto.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gaohongyu789.top/Article/details/gtegxyshez.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xinyue.icu/Article/details/gtnqehgkel.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtwtogcqxh.html

[H03] 主动抛出异常
来源：http://dali.gogol.net.cn/Article/details/gtduxgcpdq.html

Py:   raise ValueError("错误信息")
来源：http://dali.sweek.top/Article/details/gtejhobmjr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtwkuqgxbj.html

JS:   throw new Error("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtyoppvhzc.html

TS:   throw new Error("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtsrblgksh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.316326.xyz/Article/details/gtrgyqgiax.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nanxinkj.top/Article/details/gtzkjxdzva.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.316326.xyz/Article/details/gtauetjihm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gtrjdlvwkk.html

[H04] 自定义异常类型
来源：http://dali.vqdsnc.cn/Article/details/gtffnmnrnt.html

Py:   class MyError(Exception): pass
来源：http://dali.jinghuilouyu.cn/Article/details/gtmnywpegx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.havefunace.top/Article/details/gtgilgzusk.html

JS:   class MyError extends Error {}
来源：http://dali.snrcjt.cn/Article/details/gtobivcumh.html

TS:   class MyError extends Error {}
来源：http://dali.nanxuanxn.top/Article/details/gtkxjsysks.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqxmiduqt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.daria6918.cn/Article/details/gtawrsmzmn.html

Ruby: class MyError < StandardError; end
来源：http://dali.havefunace.top/Article/details/gtyvwksbyg.html

C#:   class MyException : Exception {}
来源：http://dali.dashuyun.cn/Article/details/gtaeivjfqv.html

[H05] 捕获特定类型
来源：http://dali.cdnleiting.top/Article/details/gtonublnef.html

Py:   except ValueError as e:
来源：http://dali.nanxinkj.top/Article/details/gtcpzclwtw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gaohongyu789.top/Article/details/gtpxogfljq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhongyouzk.top/Article/details/gtdcxgpuxj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xinyue.icu/Article/details/gtxwftoamv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yuanzhike.top/Article/details/gtlepnqwma.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.daria6918.cn/Article/details/gtyygqhaxf.html

Ruby: rescue ArgumentError => e
来源：http://dali.zycfv.cn/Article/details/gttngrnqae.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yj20258888.top/Article/details/gtpkwftyny.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ybcxt.top/Article/details/gtzsgyrqfj.html

Py:   value = d.get("k") or default
来源：http://dali.nanxuanxn.top/Article/details/gtfqsxapmp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zdqjudy.top/Article/details/gtwprubzox.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zdqjudy.top/Article/details/gtudwcpbzc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgfzy.top/Article/details/gtapbudzwg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.andypj.xyz/Article/details/gtpbwwxmrp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinqigfzy.top/Article/details/gtysmsyhog.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gtijjllyuy.html

C#:   obj?.A?.B ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gtjchofrte.html

[H07] 断言
来源：http://dali.yuanzhike.top/Article/details/gtzmvchfmi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinqigufen.top/Article/details/gtntxkxges.html

PHP:  assert($x > 0);
来源：http://dali.0kj1m.cn/Article/details/gtivxcnbgt.html

JS:   console.assert(x > 0);
来源：http://dali.zdqjudy.top/Article/details/gthidxyayb.html

TS:   console.assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gtxkqljezh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj20258888.top/Article/details/gtcgnlwbpo.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.bjfxy.top/Article/details/gtykmzlofy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yangfankeji.com/Article/details/gtzuomvuke.html

C#:   Debug.Assert(x > 0);
来源：http://dali.havefunace.top/Article/details/gtoyalgawl.html

[H08] 获取错误信息与堆栈
来源：http://dali.cucudq.cn/Article/details/gtzxgqgvap.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zdqjudy.top/Article/details/gtnhkycghp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcfeticsa.html

JS:   e.message;  e.stack
来源：http://dali.316326.xyz/Article/details/gtvuuoqvas.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yj20258.top/Article/details/gtfqlyzacx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shangyingyoupin.top/Article/details/gthbxnharv.html

Go:   err.Error()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnscqjcmt.html

Ruby: e.message;  e.backtrace
来源：http://dali.tianlin.xyz/Article/details/gtwszqubvy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hysaishi.cn/Article/details/gtkxgwdzwb.html

[H09] 带错误码的异常
来源：http://dali.shanyushiyangtech.top/Article/details/gtnpbklkni.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.dashuyun.cn/Article/details/gtzizriqcj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yongpay.top/Article/details/gtjlogbqsu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.nanxinkj.top/Article/details/gtomqabxhg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yanxiufei.cn/Article/details/gtquuatsmh.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sweek.top/Article/details/gtwtxgyqco.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yuxming.cn/Article/details/gtmpbfxekv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shuidangran.top/Article/details/gtyrigprdd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.fengsongda.top/Article/details/gthjzmlmzn.html

[H10] 资源自动释放
来源：http://dali.bjfxy.top/Article/details/gtxvcdnxcu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.dianchejie.cn/Article/details/gtzhymgunf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gtsylxnhjd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuanzx.com/Article/details/gtswhdechn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gotoacloud.top/Article/details/gtghxeglaj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gogol.net.cn/Article/details/gtzqtyhxmx.html

Go:   defer f.Close()
来源：http://dali.snrcjt.cn/Article/details/gtqxxdnbqx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nanxuanxn.top/Article/details/gtlrbxuyst.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtkgiquxfd.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gticlmtjbr.html

I. 正则表达式
来源：http://dali.yuxming.cn/Article/details/gtjumjqpwi.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtoxgkixds.html

[I01] 判断是否匹配
来源：http://dali.iojbl.cn/Article/details/gtuqjgxhyz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yangfankeji.com/Article/details/gtlmxmysqq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.mhx1999.top/Article/details/gtmixbcvui.html

JS:   /\d+/.test(s)
来源：http://dali.c1oappe.top/Article/details/gttpwqooej.html

TS:   /\d+/.test(s)
来源：http://dali.hfpthk.cn/Article/details/gtkboarocb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhoulong.xyz/Article/details/gtqhdforiy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hywenlv.cn/Article/details/gtlfifgauj.html

Ruby: s.match?(/\d+/)
来源：http://dali.aibaodan.cn/Article/details/gtfpomnoqi.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yongpay.top/Article/details/gtnezrhowc.html

[I02] 提取所有匹配
来源：http://dali.birdmap.top/Article/details/gtgvznghhr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yanxiufei.cn/Article/details/gtnkvfdnvy.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shuidangran.top/Article/details/gtroruhmah.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jlsjyb.cn/Article/details/gtxfcsrsjb.html

TS:   s.match(/\d+/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gtirilopvt.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtboibhivq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yuxming.cn/Article/details/gtuskjobqg.html

Ruby: s.scan(/\d+/)
来源：http://dali.guowangkeji.top/Article/details/gtyufwxjcr.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gtvskymkqe.html

[I03] 提取捕获分组
来源：http://dali.yuanzhike.top/Article/details/gthmbymypj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.0kj1m.cn/Article/details/gterixrrry.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.316326.xyz/Article/details/gtpuxqokqp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.iojbl.cn/Article/details/gtdzbusbvw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.tian-w.cn/Article/details/gtjdlvmavf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ppjwa.cn/Article/details/gthcngenya.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yvedp.cn/Article/details/gtsefabezq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.nanxuanxn.top/Article/details/gtvodkqxsk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gotoacloud.top/Article/details/gtgitdwich.html

[I04] 正则替换
来源：http://dali.haohaochexian.top/Article/details/gthntlkukx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gogol.net.cn/Article/details/gtfwgnryzy.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cucudq.cn/Article/details/gtcpzgkcdz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.nwbrower.top/Article/details/gtceedghrb.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.andypj.xyz/Article/details/gtavzmdmkr.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yj20258.top/Article/details/gtqwwbwpes.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yuxming.cn/Article/details/gtsgdrvixf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cashguo.top/Article/details/gtqoirabrk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhongyouzk.top/Article/details/gtgqdoajpm.html

[I05] 按正则拆分
来源：http://dali.zdqjudy.top/Article/details/gtzzdrgpwx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.chenzaomai.com/Article/details/gtggyghmvs.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sufxvd.cn/Article/details/gtrbdzqstb.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hywenlv.cn/Article/details/gtutvehdad.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhixingplan.top/Article/details/gtsqiddirw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shuidangran.top/Article/details/gtvnorveei.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.mhx1999.top/Article/details/gtfpzxbtxs.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hongshengwenyu.top/Article/details/gtgsqafkqj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.chenzaomai.com/Article/details/gttyfrkdib.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.tanke756.top/Article/details/gtahactudf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nanxuanxn.top/Article/details/gtpymcmvny.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.316326.xyz/Article/details/gthfkkjzck.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.redwolf501.top/Article/details/gtesysjvzk.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tian-w.cn/Article/details/gtshfsrxqq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.haohaochexian.top/Article/details/gtjkmbxmpu.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinqigufen.top/Article/details/gtvizyhvub.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.iojbl.cn/Article/details/gtjavdstqg.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gtsnbzalml.html

[I07] 忽略大小写与多行模式
来源：http://dali.daria6918.cn/Article/details/gtpbjplllb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ppjwa.cn/Article/details/gtotdaouko.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.svipenyu.cn/Article/details/gtuppapbfm.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.fzhhl.top/Article/details/gtkgzxyzml.html

TS:   /error/gim
来源：http://dali.0kj1m.cn/Article/details/gtutgfhgxe.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.aizwys.cn/Article/details/gtnqvnpmsm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ivvv.top/Article/details/gtkbyowndh.html

Ruby: s.scan(/error/i)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuwwwhxxd.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sufxvd.cn/Article/details/gtiqwaiczs.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.quarkkingdee.top/Article/details/gtchuhkpxt.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yj202588.top/Article/details/gtuuggwyww.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sxryk.cn/Article/details/gtaizhlmru.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hfpthk.cn/Article/details/gtzrzpnhpz.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fzhhl.top/Article/details/gtrnvyvuay.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yuxming.cn/Article/details/gtopkjpsqo.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hongshengwenyu.top/Article/details/gtjnakvqgl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gogol.net.cn/Article/details/gtthgqpcru.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.c1oappe.top/Article/details/gtumnwverd.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtvyffjicn.html

J. 日期与时间
来源：http://dali.cheryme.top/Article/details/gtsonkejbg.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtjledtodw.html

[J01] 获取当前时间
来源：http://dali.yj202588.top/Article/details/gtpxflfhwp.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.pycfn.com/Article/details/gtfynhbpgl.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yuanzhike.top/Article/details/gtltkhnpte.html

JS:   new Date();  Date.now()
来源：http://dali.chenlongwang.top/Article/details/gtjdgqzvkl.html

TS:   new Date();  Date.now()
来源：http://dali.jlsjyb.cn/Article/details/gtgwbryydk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nanxinkj.top/Article/details/gtycyhhvxb.html

Go:   time.Now()
来源：http://dali.guowangkeji.top/Article/details/gtqanfanhw.html

Ruby: Time.now
来源：http://dali.shzxlz.cn/Article/details/gtnnhzvgrd.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.feifeiyinyue.top/Article/details/gthtnxfniq.html

[J02] 格式化输出
来源：http://dali.yueranfly.top/Article/details/gtribrlsrk.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.havefunace.top/Article/details/gtfnexhxzz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ydzc1.top/Article/details/gtjjmfhkie.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hnqzz.top/Article/details/gtjznndoss.html

TS:   d.toISOString()
来源：http://dali.xylfe.cn/Article/details/gtqhrdjgwk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shzxlz.cn/Article/details/gtzupgkjbl.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cucudq.cn/Article/details/gtzjaibosb.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenlongwang.top/Article/details/gtpzgnizqy.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.dashuyun.cn/Article/details/gtacttyurb.html

[J03] 字符串解析为日期
来源：http://dali.sxryk.cn/Article/details/gtammsfter.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yj20258888.top/Article/details/gtdvypfyyh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.iojbl.cn/Article/details/gtkvwpqhuf.html

JS:   new Date("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gtrtilcbya.html

TS:   new Date("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtzsnhplee.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gtjjtkyivs.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gtpjbvfjpw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gtsnzazolw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hnxiangtu.top/Article/details/gtlnzgjepi.html

[J04] 时间戳与日期互转
来源：http://dali.pengpengdd.cyou/Article/details/gtidlwvnml.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xylfe.cn/Article/details/gtpjjpfcpw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.pengpengdd.cyou/Article/details/gtrcsldgzz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ydzc1.top/Article/details/gtaekqqrlb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.0kj1m.cn/Article/details/gtupqigvbg.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthxkvxmyw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cashguo.top/Article/details/gtcdvapxfg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jyoumei.cn/Article/details/gtcyiwrdoi.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.dashuyun.cn/Article/details/gtglskwagw.html

[J05] 时间加减（加 7 天）
来源：http://dali.jqgufenzy.top/Article/details/gtvichibiz.html

Py:   now + timedelta(days=7)
来源：http://dali.yj202588.top/Article/details/gtmbhjpgfh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.andypj.xyz/Article/details/gtxsdutjoi.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zdqjudy.top/Article/details/gtzsfbqczn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aizwys.cn/Article/details/gtvafpirgk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.dianchejie.cn/Article/details/gtogczqcnb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.pycfn.com/Article/details/gtfqfxzhsg.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hnxiangtu.top/Article/details/gtwumqrgzt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.pycfn.com/Article/details/gtichpeubr.html

[J06] 计算两时间之差
来源：http://dali.vqdsnc.cn/Article/details/gtbuukxogt.html

Py:   (end - start).total_seconds()
来源：http://dali.wangshuangyany.cn/Article/details/gtdfxbamsy.html

PHP:  $end->diff($start)->days;
来源：http://dali.gzhubu.top/Article/details/gtxjuzniaa.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zdqjudy.top/Article/details/gtfqtfsfxr.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.guowangkeji.top/Article/details/gtvmvofalv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.tianlin.xyz/Article/details/gtlzfuyzhr.html

Go:   end.Sub(start).Hours()
来源：http://dali.hongshengwenyu.top/Article/details/gtwyzdiopi.html

Ruby: end - start                 # 返回秒数
来源：http://dali.chenlongwang.top/Article/details/gtqrdjwywh.html

C#:   (end - start).TotalSeconds
来源：http://dali.jiagoushi.top/Article/details/gtahyyhpgo.html

[J07] 比较两个日期
来源：http://dali.wangdashe.top/Article/details/gtgsgciesr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hongshengwenyu.top/Article/details/gtowbgfurf.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ydzc1.top/Article/details/gthxavhkcq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhengqikj.top/Article/details/gtpwetuwxw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sweek.top/Article/details/gtoiocurkm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.chenjidiqi.icu/Article/details/gthrjkelft.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xuanzx.com/Article/details/gtypertqzs.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jiagoushi.top/Article/details/gtqpgxlwfi.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.sxryk.cn/Article/details/gtchigbaql.html

[J08] 提取年月日与星期
来源：http://dali.yueranfly.top/Article/details/gtmrpmebvr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.chenzaomai.com/Article/details/gtybbdbnho.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.snrcjt.cn/Article/details/gtzgfomtyk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.guowangkeji.top/Article/details/gtzjcronnv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.svipenyu.cn/Article/details/gtuqgxczjj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.birdmap.top/Article/details/gtbtsbjfqi.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinqigufen.top/Article/details/gtscfcqnkk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.wangdashe.top/Article/details/gtrucvonkt.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.chenzaomai.com/Article/details/gtmdsmkkrf.html

[J09] 时区处理
来源：http://dali.wangdashe.top/Article/details/gtxtxdpftu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hfpthk.cn/Article/details/gtjbubzgyc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cucudq.cn/Article/details/gtmwodntxc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sxryk.cn/Article/details/gtutmrjvaj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ppjwa.cn/Article/details/gtqgqenhyz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ydzc1.top/Article/details/gtxbplvrfn.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.daria6918.cn/Article/details/gtzjtlqqfg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yj20258888.top/Article/details/gtxocmmyea.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.havefunace.top/Article/details/gtxnxowbzf.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinqigufen.top/Article/details/gtoeidycyy.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlcgfymbt.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.daria6918.cn/Article/details/gtkvbxredn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.haohaochexian.top/Article/details/gtffmzxeta.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hysaishi.cn/Article/details/gtnfvqzsta.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jiagoushi.top/Article/details/gtqbekkbpm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.nwbrower.top/Article/details/gtuuumgzbf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hysaishi.cn/Article/details/gtyumpghrk.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.nwbrower.top/Article/details/gtntcnzyjs.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtnzcgcpji.html

K. JSON 与序列化
来源：http://dali.redwolf501.top/Article/details/gtygfvurwk.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtucpazdit.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinqigfzy.top/Article/details/gtlxbfwljt.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.tanke756.top/Article/details/gtolfthakm.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.9152youxi.cn/Article/details/gtldzuckaf.html

JS:   JSON.stringify(obj)
来源：http://dali.sxryk.cn/Article/details/gtwdunrnev.html

TS:   JSON.stringify(obj)
来源：http://dali.cqqwz.cn/Article/details/gtzzpedgzp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yj20258888.top/Article/details/gtxinfkhtw.html

Go:   json.Marshal(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqfeypwju.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yuxming.cn/Article/details/gtxwzlhyoh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.svipenyu.cn/Article/details/gtnwhyewjr.html

[K02] JSON 字符串转对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gteusmjnyz.html

Py:   json.loads(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtiqizrler.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.guannengcc.top/Article/details/gtnbyvxeew.html

JS:   JSON.parse(s)
来源：http://dali.jinqigufen.top/Article/details/gtbhdypptk.html

TS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gtglasxuud.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.nanxinkj.top/Article/details/gtyimwkykc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhiwuduotai.top/Article/details/gtingllhsl.html

Ruby: JSON.parse(s)
来源：http://dali.yuanzhike.top/Article/details/gtxzpujkhz.html


<!-- 参考信息 -->