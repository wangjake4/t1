代发 wailian999

Py:   isinstance(u, User)
来源：http://dali.yangfankeji.com/Article/details/gtokymfxcb.html

PHP:  $u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gtqcjuxgej.html

JS:   u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gtgwcwzpql.html

TS:   u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gtzcgxzmxr.html

Java: u instanceof User
来源：http://dali.yuxming.cn/Article/details/gtiisneymk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gaohongyu789.top/Article/details/gtjgozbqxf.html

Ruby: u.is_a?(User)
来源：http://dali.chenzaomai.com/Article/details/gtgccmdfqk.html

C#:   u is User
来源：http://dali.ppjwa.cn/Article/details/gtjjzwdkel.html

[G14] 数据类 / record
来源：http://dali.quarkkingdee.top/Article/details/gtwqkzcide.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.daxiang520.top/Article/details/gtzgieszsm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.snrcjt.cn/Article/details/gtxmpoorew.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.guowangkeji.top/Article/details/gtazpamrqo.html

TS:   type User = { name: string; age: number };
来源：http://dali.wangdashe.top/Article/details/gtlkycjnrl.html

Java: record User(String name, int age) {}
来源：http://dali.jiagoushi.top/Article/details/gtdszhzjfz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.nanxinkj.top/Article/details/gtfxatnwwt.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.smart0.xyz/Article/details/gtpxxbifpk.html

C#:   record User(string Name, int Age);
来源：http://dali.mhx1999.top/Article/details/gtotlbeuja.html

[G15] 枚举
来源：http://dali.jlsjyb.cn/Article/details/gtuanlgupt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.bjfxy.top/Article/details/gtfnlbkzsr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yonumen.top/Article/details/gtpzjgpddi.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yuanzhike.top/Article/details/gtlvpwezqk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dashuyun.cn/Article/details/gtwzovrykk.html

Java: enum Color { RED, GREEN }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcirypekh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.kuanghao11.cn/Article/details/gtxpokrfwz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shanyushiyangkeji.top/Article/details/gthwcptrnn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnxiangtu.top/Article/details/gtjujhfzku.html

[G16] 对象转数组 / 字典
来源：http://dali.sweek.top/Article/details/gtjqqurtvf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.0kj1m.cn/Article/details/gtytqtwqsm.html

PHP:  get_object_vars($obj);
来源：http://dali.xinyue.icu/Article/details/gtcaawfumt.html

JS:   Object.entries(obj)
来源：http://dali.ehwqpu.com/Article/details/gthlxtcdat.html

TS:   Object.entries(obj)
来源：http://dali.shzxlz.cn/Article/details/gtzpgwjuvs.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.meibo888.top/Article/details/gtobseuyfz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.redwolf501.top/Article/details/gtrjgavuef.html

Ruby: obj.instance_variables
来源：http://dali.daria6918.cn/Article/details/gtsubewhfi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.redwolf501.top/Article/details/gtxulnghgz.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gttkvqruwc.html

H. 异常与错误处理
来源：http://dali.ehwqpu.com/Article/details/gtwghicoqy.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtuecjlemb.html

[H01] try / catch 基础
来源：http://dali.aibaodan.cn/Article/details/gtxtbsxpma.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.vqdsnc.cn/Article/details/gtvhagszjv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhixingplan.top/Article/details/gtocsrsqlf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcadljnou.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.haohaochexian.top/Article/details/gtzcybgsba.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.smart0.xyz/Article/details/gtxmnhwxvg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.pengpengdd.cyou/Article/details/gtqbpdfolu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.meibo888.top/Article/details/gtgezhylfc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yj202588.top/Article/details/gthiatgqmv.html

[H02] finally / ensure 收尾
来源：http://dali.zdqjudy.top/Article/details/gtofevyarx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cdnleiting.top/Article/details/gtgcvknwte.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gtacxxlsjq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtwbduqofz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtgfuwjyba.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtpsoqydaq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.daxiang520.top/Article/details/gtgjqyyxud.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cqqwz.cn/Article/details/gtczijxgqw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtiopspqfr.html

[H03] 主动抛出异常
来源：http://dali.yangfankeji.com/Article/details/gtvyuccont.html

Py:   raise ValueError("错误信息")
来源：http://dali.shangyingyoupin.top/Article/details/gtducmjzkh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gtgczfrlyg.html

JS:   throw new Error("错误信息");
来源：http://dali.nwbrower.top/Article/details/gttjzhmmbf.html

TS:   throw new Error("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtarxkjvya.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gtrjbjejje.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gaohongyu789.top/Article/details/gtejrjqkyp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj20258888.top/Article/details/gtdoertgsx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cheryme.top/Article/details/gtoniupgaw.html

[H04] 自定义异常类型
来源：http://dali.xuetiantiany.cn/Article/details/gtwnjckfpw.html

Py:   class MyError(Exception): pass
来源：http://dali.nwbrower.top/Article/details/gtybhmplmn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hnxiangtu.top/Article/details/gtrkmrrzzo.html

JS:   class MyError extends Error {}
来源：http://dali.haohaochexian.top/Article/details/gttgdxbose.html

TS:   class MyError extends Error {}
来源：http://dali.jiagoushi.top/Article/details/gtxrhprqmn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yongpay.top/Article/details/gtnlijmhbj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ybcxt.top/Article/details/gteirvdfza.html

Ruby: class MyError < StandardError; end
来源：http://dali.yj20258.top/Article/details/gtfithnuxf.html

C#:   class MyException : Exception {}
来源：http://dali.vqdsnc.cn/Article/details/gtdrwnuexl.html

[H05] 捕获特定类型
来源：http://dali.zhixingplan.top/Article/details/gtpggtxbkx.html

Py:   except ValueError as e:
来源：http://dali.yvedp.cn/Article/details/gtanppiali.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hammf.cn/Article/details/gtbsblrfbt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tianlin.xyz/Article/details/gtdwtwtsxa.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.quarkkingdee.top/Article/details/gtlurjtoqq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinqigfzy.top/Article/details/gtnnsbhavh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sweek.top/Article/details/gtslltodkr.html

Ruby: rescue ArgumentError => e
来源：http://dali.xuetiantiany.cn/Article/details/gtnuowqpnp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.bjfxy.top/Article/details/gtaanihayj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj20258888.top/Article/details/gtkzjkjtsq.html

Py:   value = d.get("k") or default
来源：http://dali.gaohongyu789.top/Article/details/gtzweakvvt.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.dashuyun.cn/Article/details/gtjppgfnwe.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gaohongyu789.top/Article/details/gtygnbygll.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sysykeji.top/Article/details/gtifqsinno.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhixingplan.top/Article/details/gtwophxxsw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.meibo888.top/Article/details/gtfmjsmqff.html

Ruby: d&.dig(:a, :b)
来源：http://dali.pycfn.com/Article/details/gtvleswgse.html

C#:   obj?.A?.B ?? default
来源：http://dali.sxryk.cn/Article/details/gtxegawwgu.html

[H07] 断言
来源：http://dali.quarkkingdee.top/Article/details/gtvbsfxqtl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj202588.top/Article/details/gtnfcoahlq.html

PHP:  assert($x > 0);
来源：http://dali.dianchejie.cn/Article/details/gtpmlmrkmy.html

JS:   console.assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gtggpywomg.html

TS:   console.assert(x > 0);
来源：http://dali.zdqjudy.top/Article/details/gtcgduifiy.html

Java: assert x > 0 : "必须为正";
来源：http://dali.iojbl.cn/Article/details/gtgmcezhrr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ybcxt.top/Article/details/gtdkdkmvwa.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.fengsongda.top/Article/details/gtxiogjeat.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gtzkmcehbo.html

[H08] 获取错误信息与堆栈
来源：http://dali.meibo888.top/Article/details/gtteupxwpy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shuidangran.top/Article/details/gtjvfnpzkf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ppjwa.cn/Article/details/gtadenfqso.html

JS:   e.message;  e.stack
来源：http://dali.sxryk.cn/Article/details/gtivjgvqmb.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hammf.cn/Article/details/gtqgfpgzfl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sxryk.cn/Article/details/gtofpsketb.html

Go:   err.Error()
来源：http://dali.zhixingplan.top/Article/details/gtbgokpfmc.html

Ruby: e.message;  e.backtrace
来源：http://dali.jqgfzy.top/Article/details/gtklyauvyh.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinqigufen.top/Article/details/gtexrlzgvd.html

[H09] 带错误码的异常
来源：http://dali.svipenyu.cn/Article/details/gtfnqvomxr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.chenlongwang.top/Article/details/gtxhvfeddd.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.meibo888.top/Article/details/gtpvrbsdmf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgasfmezz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cdnleiting.top/Article/details/gtnshozjrx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.wangshuangyany.cn/Article/details/gtmuoenzpo.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.wangshuangyany.cn/Article/details/gtoccqlfdc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tianlin.xyz/Article/details/gtvpjsytwb.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ppjwa.cn/Article/details/gtxjdtvdnc.html

[H10] 资源自动释放
来源：http://dali.aibaodan.cn/Article/details/gtdaylcnia.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gogol.net.cn/Article/details/gtjvwjfxev.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jqgufenzy.top/Article/details/gtyjpgmuud.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tianlin.xyz/Article/details/gtlencrcaf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yongpay.top/Article/details/gtwyfkyrfi.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinghuilouyu.cn/Article/details/gtrjeojikv.html

Go:   defer f.Close()
来源：http://dali.yueranfly.top/Article/details/gtgwtjbpaf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hongshengwenyu.top/Article/details/gtxfutbrxq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtgjwdsjlp.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtrmaljdfh.html

I. 正则表达式
来源：http://dali.gaohongyu789.top/Article/details/gtcepiskdb.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtjwotbraq.html

[I01] 判断是否匹配
来源：http://dali.jqgfzy.top/Article/details/gtykniwxot.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sufxvd.cn/Article/details/gtldikbtkw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cheryme.top/Article/details/gtdfgvantr.html

JS:   /\d+/.test(s)
来源：http://dali.ybcxt.top/Article/details/gtxmcgokvu.html

TS:   /\d+/.test(s)
来源：http://dali.bjfxy.top/Article/details/gtvqeptgcn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hysaishi.cn/Article/details/gtovghrajf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.tanke756.top/Article/details/gtquemfpmq.html

Ruby: s.match?(/\d+/)
来源：http://dali.yongpay.top/Article/details/gtpycwolts.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zycfv.cn/Article/details/gtuzdplzua.html

[I02] 提取所有匹配
来源：http://dali.yj20258888.top/Article/details/gtmssreqyz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ppjwa.cn/Article/details/gtzsvueobi.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hfpthk.cn/Article/details/gtmmmghtja.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cashguo.top/Article/details/gtcpsggser.html

TS:   s.match(/\d+/g)
来源：http://dali.hfpthk.cn/Article/details/gtzekxbofx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.vqdsnc.cn/Article/details/gtyzhofkiy.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.tianlin.xyz/Article/details/gteyakpupm.html

Ruby: s.scan(/\d+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtropahhzc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.haohaochexian.top/Article/details/gtccnxrmzf.html

[I03] 提取捕获分组
来源：http://dali.aibaodan.cn/Article/details/gtgwveoohj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sysykeji.top/Article/details/gtyiobfinl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.wangdashe.top/Article/details/gtjnuyzqwv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.haohaochexian.top/Article/details/gtbfswudgl.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hongshengwenyu.top/Article/details/gtixjvflkr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.daxiang520.top/Article/details/gtldqlswqb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shuidangran.top/Article/details/gtsgrrcjnx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jlsjyb.cn/Article/details/gtjfsubhwy.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jyoumei.cn/Article/details/gttbnnswve.html

[I04] 正则替换
来源：http://dali.hnxiangtu.top/Article/details/gtyhxeblta.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.bjfxy.top/Article/details/gtardpgzuv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtaxndaqsf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zycfv.cn/Article/details/gtodocyial.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.chenlongwang.top/Article/details/gtsmekhdoo.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gogol.net.cn/Article/details/gtkwvtkbku.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gzhubu.top/Article/details/gttzmnalry.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.meibo888.top/Article/details/gttromkqox.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hammf.cn/Article/details/gtbxyazwsg.html

[I05] 按正则拆分
来源：http://dali.yj20258888.top/Article/details/gtiqclsafx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hnxiangtu.top/Article/details/gtcyshftha.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj20258.top/Article/details/gtvjyxtrst.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.316326.xyz/Article/details/gtrdfoeoqk.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258.top/Article/details/gtcblmcigz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhiwuduotai.top/Article/details/gtwiwhvqje.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.iojbl.cn/Article/details/gtvhgpuamp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shuidangran.top/Article/details/gtxllocuvf.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yj202588.top/Article/details/gtjagznwdu.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.aibaodan.cn/Article/details/gtnewvnwhg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ehwqpu.com/Article/details/gtdzfysgpo.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jianghu66.top/Article/details/gtogwfvrlq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.mhx1999.top/Article/details/gtufuigfpc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cucudq.cn/Article/details/gtodwrkjzr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gtfiwotqvo.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gaohongyu789.top/Article/details/gtqoydcjky.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.guowangkeji.top/Article/details/gtvvdljyhq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gtnxfjkrxb.html

[I07] 忽略大小写与多行模式
来源：http://dali.svipenyu.cn/Article/details/gtqfegsspj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ppjwa.cn/Article/details/gtzpflqbke.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.wangshuangyany.cn/Article/details/gtxaqgozds.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhixingplan.top/Article/details/gtdtqhjhaa.html

TS:   /error/gim
来源：http://dali.tanke756.top/Article/details/gtxzgulndb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.smart0.xyz/Article/details/gtityfxgub.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.pycfn.com/Article/details/gtvjiqmakw.html

Ruby: s.scan(/error/i)
来源：http://dali.sufxvd.cn/Article/details/gtkgpqivox.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xziqi.cn/Article/details/gtjzrkkmbi.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.c1oappe.top/Article/details/gthrealyab.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sxryk.cn/Article/details/gtqihilccn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.redwolf501.top/Article/details/gtuxtcqvym.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.kuanghao11.cn/Article/details/gtqdrhludw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jlsjyb.cn/Article/details/gttnqwtxeq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.9152youxi.cn/Article/details/gtsxqsxptw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gtjhlaoeyz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtiewscbit.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ydzc1.top/Article/details/gtfaryktgt.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtwsrbprig.html

J. 日期与时间
来源：http://dali.meibo888.top/Article/details/gtaylvhlyu.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gthzzcxjkq.html

[J01] 获取当前时间
来源：http://dali.zhoulong.xyz/Article/details/gtszfkgtsg.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhiwuduotai.top/Article/details/gtssgpkwed.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ehwqpu.com/Article/details/gtiytxarkl.html

JS:   new Date();  Date.now()
来源：http://dali.hnxiangtu.top/Article/details/gtqosdueeg.html

TS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gtgrlyealz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sxryk.cn/Article/details/gtngalwgci.html

Go:   time.Now()
来源：http://dali.9152youxi.cn/Article/details/gteoskmxte.html

Ruby: Time.now
来源：http://dali.sweek.top/Article/details/gtvruubjju.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhoulong.xyz/Article/details/gtnopehczq.html

[J02] 格式化输出
来源：http://dali.andypj.xyz/Article/details/gtaczkytpn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yvedp.cn/Article/details/gtdclgsxqi.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shangyingyoupin.top/Article/details/gttdvibkdo.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.redwolf501.top/Article/details/gtfpvbklmn.html

TS:   d.toISOString()
来源：http://dali.wangshuangyany.cn/Article/details/gtrvfewquo.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenzaomai.com/Article/details/gtznoxynzt.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.nanxinkj.top/Article/details/gtnokikypo.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenjidiqi.icu/Article/details/gtjnlizgay.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.mhx1999.top/Article/details/gtjrjxznbb.html

[J03] 字符串解析为日期
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqlgujylh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhiwuduotai.top/Article/details/gtvydhhbde.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtohzoahhh.html

JS:   new Date("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gtobgipzkg.html

TS:   new Date("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gtgwudehfw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtjrwbvauq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.pycfn.com/Article/details/gtuhhpmskf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtijnysuhv.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.redwolf501.top/Article/details/gtydytajzq.html

[J04] 时间戳与日期互转
来源：http://dali.cqqwz.cn/Article/details/gtpjkuwodj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ydzc1.top/Article/details/gtpdphjszn.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yangfankeji.com/Article/details/gtdxnzmlpr.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpszsorut.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gotoacloud.top/Article/details/gtmlgzkbrb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinqigfzy.top/Article/details/gtxoukymik.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.tian-w.cn/Article/details/gtwzlhupdv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.guannengcc.top/Article/details/gtcxqtupwx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sysykeji.top/Article/details/gtwtwocpin.html

[J05] 时间加减（加 7 天）
来源：http://dali.yangfankeji.com/Article/details/gturfcqhyl.html

Py:   now + timedelta(days=7)
来源：http://dali.ydzc1.top/Article/details/gtamdjpaxn.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gogol.net.cn/Article/details/gtdlwobnlk.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnqzz.top/Article/details/gtodzohvrd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinghuilouyu.cn/Article/details/gtiurwmcpq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gotoacloud.top/Article/details/gtzpbcsmxo.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.snrcjt.cn/Article/details/gtgrodqlpl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.316326.xyz/Article/details/gtkzmajris.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.smart0.xyz/Article/details/gtvxfriivh.html

[J06] 计算两时间之差
来源：http://dali.hfpthk.cn/Article/details/gtqwnpnwtv.html

Py:   (end - start).total_seconds()
来源：http://dali.hnqzz.top/Article/details/gtrlqsqnzi.html

PHP:  $end->diff($start)->days;
来源：http://dali.kuanghao11.cn/Article/details/gtbhupqhfr.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gzhubu.top/Article/details/gtuwdnakmw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj20258.top/Article/details/gtvkwzkapd.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xziqi.cn/Article/details/gtgcvcjbwt.html

Go:   end.Sub(start).Hours()
来源：http://dali.gaohongyu789.top/Article/details/gtxincnukq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jqgufenzy.top/Article/details/gtqdjsibvr.html

C#:   (end - start).TotalSeconds
来源：http://dali.sysykeji.top/Article/details/gtpkhqlbyb.html

[J07] 比较两个日期
来源：http://dali.yuxming.cn/Article/details/gtrgmoiufs.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.kuanghao11.cn/Article/details/gtqvacuesc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.pycfn.com/Article/details/gtymikpdda.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.wangshuangyany.cn/Article/details/gtpgoxyysm.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.meibo888.top/Article/details/gtvaxjjwpv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.fzhhl.top/Article/details/gtajdxpasw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shuidangran.top/Article/details/gtqmohadtl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shangyingyoupin.top/Article/details/gttdqklhep.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jlsjyb.cn/Article/details/gtxvyxzfas.html

[J08] 提取年月日与星期
来源：http://dali.zhengqikj.top/Article/details/gtanhqqrru.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.snrcjt.cn/Article/details/gtetoxnedk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhengqikj.top/Article/details/gtpttjwuze.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvnsyvmie.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cheryme.top/Article/details/gtjnubpgzp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.9152youxi.cn/Article/details/gtdbmifedq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zycfv.cn/Article/details/gtrqqgnwhh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyvuswsvj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.chenjidiqi.icu/Article/details/gthpzwankm.html

[J09] 时区处理
来源：http://dali.kuanghao11.cn/Article/details/gtaeciryjd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yanxiufei.cn/Article/details/gtaesssxis.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.redwolf501.top/Article/details/gtpmtycqyo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guannengcc.top/Article/details/gtzkhdgiof.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnqzz.top/Article/details/gtnimzrmdy.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgevbjzoc.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xylfe.cn/Article/details/gtaeslggya.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.chenjidiqi.icu/Article/details/gtbdrypxlv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpsefalkg.html

[J10] 取今天 / 本月第一天
来源：http://dali.gzhubu.top/Article/details/gtcsrkntvx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.feifeiyinyue.top/Article/details/gtafqvpmqi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.havefunace.top/Article/details/gtmptzzatn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hammf.cn/Article/details/gtncatwrfg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sysykeji.top/Article/details/gtdwbzwblm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jianghu66.top/Article/details/gtxibzkmmt.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hnqzz.top/Article/details/gtsusrczid.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.guannengcc.top/Article/details/gtxlajfeyb.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.svipenyu.cn/Article/details/gtlhznirxi.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtkgfrssll.html

K. JSON 与序列化
来源：http://dali.xinyue.icu/Article/details/gtrvdtvowg.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtvnatqmch.html

[K01] 对象转 JSON 字符串
来源：http://dali.yangfankeji.com/Article/details/gtgrtjvkfl.html


<!-- 参考信息 -->