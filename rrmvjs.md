代发 wailian999

Ruby: super
来源：http://dali.jiagoushi.top/Article/details/gtcsogygpx.html

C#:   base.Greet();
来源：http://dali.aibaodan.cn/Article/details/gtnevdpxed.html

[G08] 静态方法与属性
来源：http://dali.jiagoushi.top/Article/details/gtsfsfmgjn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yuanzhike.top/Article/details/gtwnduzgdb.html

PHP:  public static function f() {}
来源：http://dali.xuanzx.com/Article/details/gtcankwkdy.html

JS:   static f() {}
来源：http://dali.nanxuanxn.top/Article/details/gtsczbnuhl.html

TS:   static f(): void {}
来源：http://dali.jqgufenzy.top/Article/details/gtapwkqtxo.html

Java: static void f() {}
来源：http://dali.fzhhl.top/Article/details/gtppjveyhn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ydzc1.top/Article/details/gtmuyupkvb.html

Ruby: def self.f; end
来源：http://dali.zhongyouzk.top/Article/details/gtzecowqeu.html

C#:   public static void F() {}
来源：http://dali.ivvv.top/Article/details/gtdymlbkvp.html

[G09] 接口 / 抽象类
来源：http://dali.quarkkingdee.top/Article/details/gtuzuzltpt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tianlin.xyz/Article/details/gtqrsebfcx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yangfankeji.com/Article/details/gtzrviuhqa.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gtrclwdaem.html

TS:   interface Shape { area(): number; }
来源：http://dali.daxiang520.top/Article/details/gtwknrxwra.html

Java: interface Shape { double area(); }
来源：http://dali.hysaishi.cn/Article/details/gtvzpsghgd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.chenzaomai.com/Article/details/gtilxkqaqc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xinyue.icu/Article/details/gtvzablfjs.html

C#:   interface IShape { double Area(); }
来源：http://dali.yj20258.top/Article/details/gteurduqry.html

[G10] 访问控制
来源：http://dali.chenjidiqi.icu/Article/details/gtfrokrooy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sysykeji.top/Article/details/gtloihqbqd.html

PHP:  public / protected / private
来源：http://dali.nanxinkj.top/Article/details/gtinpejkva.html

JS:   #private 字段；其余公开
来源：http://dali.smart0.xyz/Article/details/gttmicrxob.html

TS:   public / protected / private
来源：http://dali.dianchejie.cn/Article/details/gtfqgyylbu.html

Java: public / protected / private / 默认包级
来源：http://dali.ydzc1.top/Article/details/gtwjfaehri.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinghuilouyu.cn/Article/details/gtompcmahp.html

Ruby: public / protected / private
来源：http://dali.xuanzx.com/Article/details/gtqnjdhbks.html

C#:   public / protected / private / internal
来源：http://dali.chenlongwang.top/Article/details/gtwvgooehd.html

[G11] getter / setter
来源：http://dali.yuxming.cn/Article/details/gtalfsnice.html

Py:   @property 与 @x.setter
来源：http://dali.havefunace.top/Article/details/gtdtkfvolj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.c1oappe.top/Article/details/gtowqfenvr.html

JS:   get name() { return this._name; }
来源：http://dali.nanxuanxn.top/Article/details/gtncdelixo.html

TS:   get name(): string { return this._name; }
来源：http://dali.yj20258.top/Article/details/gtdfuyawjf.html

Java: public String getName() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gtzmzvqdwg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gtvzqurgxq.html

Ruby: attr_accessor :name
来源：http://dali.0kj1m.cn/Article/details/gtbcrjmyfo.html

C#:   public string Name { get; set; }
来源：http://dali.wangshuangyany.cn/Article/details/gtvduzlumr.html

[G12] 对象转字符串
来源：http://dali.hywenlv.cn/Article/details/gtqeoponuw.html

Py:   def __str__(self): return self.name
来源：http://dali.jiagoushi.top/Article/details/gtzpxwxozj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gtjxtyzvne.html

JS:   toString() { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtagwkzyuo.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinqigufen.top/Article/details/gtavpuiupb.html

Java: @Override public String toString() { return name; }
来源：http://dali.yongpay.top/Article/details/gtpmsgpnah.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gtcikswvrg.html

Ruby: def to_s; @name; end
来源：http://dali.daria6918.cn/Article/details/gtymcuetek.html

C#:   public override string ToString() => Name;
来源：http://dali.jianghu66.top/Article/details/gtgsxchulj.html

[G13] 判断对象类型
来源：http://dali.gzhubu.top/Article/details/gtzgpzuida.html

Py:   isinstance(u, User)
来源：http://dali.tanke756.top/Article/details/gthfxdbwxu.html

PHP:  $u instanceof User
来源：http://dali.sxryk.cn/Article/details/gttjufbbmn.html

JS:   u instanceof User
来源：http://dali.guannengcc.top/Article/details/gtjsuexfuq.html

TS:   u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gtwclrynfp.html

Java: u instanceof User
来源：http://dali.xylfe.cn/Article/details/gtwargjkco.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sufxvd.cn/Article/details/gtgqzzozpx.html

Ruby: u.is_a?(User)
来源：http://dali.shangyingyoupin.top/Article/details/gtyzivyevu.html

C#:   u is User
来源：http://dali.shuidangran.top/Article/details/gtzdtgucho.html

[G14] 数据类 / record
来源：http://dali.sysykeji.top/Article/details/gtcsybszoq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinqigufen.top/Article/details/gtxezefojd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.havefunace.top/Article/details/gtpfeaghcj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.0kj1m.cn/Article/details/gtldvseimm.html

TS:   type User = { name: string; age: number };
来源：http://dali.andypj.xyz/Article/details/gtyuvkdrqj.html

Java: record User(String name, int age) {}
来源：http://dali.daxiang520.top/Article/details/gtqkmstxnf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.meibo888.top/Article/details/gttqwecmom.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shuidangran.top/Article/details/gtouiwhjgu.html

C#:   record User(string Name, int Age);
来源：http://dali.c1oappe.top/Article/details/gtywksjwzc.html

[G15] 枚举
来源：http://dali.iojbl.cn/Article/details/gtgxbchqng.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xinyue.icu/Article/details/gtlxwyhfww.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zycfv.cn/Article/details/gtqquqlyrv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ywan-chungtsiang.top/Article/details/gtghqsyygd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258888.top/Article/details/gtpbpecwwn.html

Java: enum Color { RED, GREEN }
来源：http://dali.nwbrower.top/Article/details/gtpcmsbsol.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ivvv.top/Article/details/gtexgjrrfg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ybcxt.top/Article/details/gtbulayfaz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvrulezmn.html

[G16] 对象转数组 / 字典
来源：http://dali.jinqigufen.top/Article/details/gtkjjjhfkw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhiwuduotai.top/Article/details/gtteypiqbf.html

PHP:  get_object_vars($obj);
来源：http://dali.tianlin.xyz/Article/details/gthnybwjfp.html

JS:   Object.entries(obj)
来源：http://dali.hysaishi.cn/Article/details/gtihdubakt.html

TS:   Object.entries(obj)
来源：http://dali.ppjwa.cn/Article/details/gtirmxtlqy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.bjfxy.top/Article/details/gtrvvglpns.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.andypj.xyz/Article/details/gtgnhfakqi.html

Ruby: obj.instance_variables
来源：http://dali.xinyue.icu/Article/details/gtzaojsish.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shanyushiyangtech.top/Article/details/gtkqsvrqec.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtxduseicj.html

H. 异常与错误处理
来源：http://dali.jqgfzy.top/Article/details/gtpivmmdpv.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtawjgpfrr.html

[H01] try / catch 基础
来源：http://dali.jyoumei.cn/Article/details/gtxdbfivda.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sysykeji.top/Article/details/gtfbuyipyc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yuanzhike.top/Article/details/gtorqpajdq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.chenjidiqi.icu/Article/details/gtfcklkffj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jlsjyb.cn/Article/details/gtubpciuuu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.mhx1999.top/Article/details/gtyrcfucso.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinqigufen.top/Article/details/gtovdicnaj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.kuanghao11.cn/Article/details/gtdcfnshih.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yj20258888.top/Article/details/gtricgshap.html

[H02] finally / ensure 收尾
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkyihfsng.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.svipenyu.cn/Article/details/gtmgpmjkoc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gthddruzyb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtcoudcvhb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtrjwmkonw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtsoykzoqh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj20258888.top/Article/details/gtaoowvsal.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.kuanghao11.cn/Article/details/gtijlokcym.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtijmbmedu.html

[H03] 主动抛出异常
来源：http://dali.wangshuangyany.cn/Article/details/gtrsrysfof.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhengqikj.top/Article/details/gtcztwigss.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.fengsongda.top/Article/details/gtkrxfxkla.html

JS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlfkgewhn.html

TS:   throw new Error("错误信息");
来源：http://dali.316326.xyz/Article/details/gtxqvcopeo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gthhrlhdgw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.feifeiyinyue.top/Article/details/gtoddrlcbm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hammf.cn/Article/details/gthjmhxzhp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtbgpylhzg.html

[H04] 自定义异常类型
来源：http://dali.cashguo.top/Article/details/gtogfnkhas.html

Py:   class MyError(Exception): pass
来源：http://dali.cucudq.cn/Article/details/gtwnhthpgx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nwbrower.top/Article/details/gtkzkhmycx.html

JS:   class MyError extends Error {}
来源：http://dali.sufxvd.cn/Article/details/gtavtalecc.html

TS:   class MyError extends Error {}
来源：http://dali.quarkkingdee.top/Article/details/gtlpybyutf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jqgufenzy.top/Article/details/gtiljfskjx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jqgufenzy.top/Article/details/gtvsqzmvxi.html

Ruby: class MyError < StandardError; end
来源：http://dali.mhx1999.top/Article/details/gtnclmrbdl.html

C#:   class MyException : Exception {}
来源：http://dali.jqgufenzy.top/Article/details/gtbtjmmohh.html

[H05] 捕获特定类型
来源：http://dali.yj20258.top/Article/details/gtzktaxmcw.html

Py:   except ValueError as e:
来源：http://dali.guannengcc.top/Article/details/gtabsqqekz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhoulong.xyz/Article/details/gtdrdncdkp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hfpthk.cn/Article/details/gtvtscazik.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.redwolf501.top/Article/details/gttyphdvgx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gaohongyu789.top/Article/details/gteatujfuh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shzxlz.cn/Article/details/gtrbgjxynz.html

Ruby: rescue ArgumentError => e
来源：http://dali.yanxiufei.cn/Article/details/gtngqapqad.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nanxuanxn.top/Article/details/gtcjkztpvp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.daxiang520.top/Article/details/gtsvfcriqh.html

Py:   value = d.get("k") or default
来源：http://dali.xuanzx.com/Article/details/gtxopmnles.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gtvcqgelsa.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xuanzx.com/Article/details/gtgzqcknfn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258.top/Article/details/gthblmiral.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfpuxsusd.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xylfe.cn/Article/details/gtavxqsvep.html

Ruby: d&.dig(:a, :b)
来源：http://dali.dashuyun.cn/Article/details/gtzkthzaxe.html

C#:   obj?.A?.B ?? default
来源：http://dali.yanxiufei.cn/Article/details/gtwsibbmge.html

[H07] 断言
来源：http://dali.cucudq.cn/Article/details/gtdkgtlqjo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.aizwys.cn/Article/details/gtqbugrnxb.html

PHP:  assert($x > 0);
来源：http://dali.wangdashe.top/Article/details/gtgjejfbip.html

JS:   console.assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gtgfqjilho.html

TS:   console.assert(x > 0);
来源：http://dali.9152youxi.cn/Article/details/gtjtlzsjcr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.aizwys.cn/Article/details/gtcmxnqety.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hongshengwenyu.top/Article/details/gtxkufflfd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.9152youxi.cn/Article/details/gtkuirkvio.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yangfankeji.com/Article/details/gtsqxekzba.html

[H08] 获取错误信息与堆栈
来源：http://dali.cucudq.cn/Article/details/gtyqalignq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hnxiangtu.top/Article/details/gtcfuduvaq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhixingplan.top/Article/details/gtujwvtxkg.html

JS:   e.message;  e.stack
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdnbkrfee.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.guowangkeji.top/Article/details/gtixernrsq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.c1oappe.top/Article/details/gtoltvipxz.html

Go:   err.Error()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfzknlwoq.html

Ruby: e.message;  e.backtrace
来源：http://dali.tian-w.cn/Article/details/gttnbbjhky.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ydzc1.top/Article/details/gtwflxjciq.html

[H09] 带错误码的异常
来源：http://dali.xylfe.cn/Article/details/gtfwhmseem.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.aizwys.cn/Article/details/gtyzbzrshy.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.chenlongwang.top/Article/details/gtcmmmoptd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.fzhhl.top/Article/details/gtqvohfudj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.pengpengdd.cyou/Article/details/gtpjwkwucy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yangfankeji.com/Article/details/gtoklepqen.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sufxvd.cn/Article/details/gtrxyritqj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlmyddvwl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.smart0.xyz/Article/details/gtzcpzqflu.html

[H10] 资源自动释放
来源：http://dali.gogol.net.cn/Article/details/gtabzjrlcj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sweek.top/Article/details/gthiamptrz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gotoacloud.top/Article/details/gtjhpyskku.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgufenzy.top/Article/details/gtlwoterzp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.mhx1999.top/Article/details/gtbzrewvyq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.wangdashe.top/Article/details/gtfvxyaeqg.html

Go:   defer f.Close()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpgecchgb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yj202588.top/Article/details/gtebmvzsol.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cashguo.top/Article/details/gtqermisct.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtdyresoyy.html

I. 正则表达式
来源：http://dali.aizwys.cn/Article/details/gtixgdxzhc.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtkqbxertv.html

[I01] 判断是否匹配
来源：http://dali.guannengcc.top/Article/details/gtguijuzxr.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yj20258888.top/Article/details/gtgujsulth.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ehwqpu.com/Article/details/gtajeqsnxm.html

JS:   /\d+/.test(s)
来源：http://dali.guannengcc.top/Article/details/gtmuayulrw.html

TS:   /\d+/.test(s)
来源：http://dali.havefunace.top/Article/details/gtiigmdfxx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.pengpengdd.cyou/Article/details/gteykqabga.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xuanzx.com/Article/details/gtnsvkolii.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyubwgfdj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.gotoacloud.top/Article/details/gtovopkjlg.html

[I02] 提取所有匹配
来源：http://dali.hysaishi.cn/Article/details/gtfrsmrmli.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yj20258.top/Article/details/gtdnqbibmw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.nanxuanxn.top/Article/details/gtgwrrlnxr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.pycfn.com/Article/details/gtgpadyfvv.html

TS:   s.match(/\d+/g)
来源：http://dali.shanyushiyangtech.top/Article/details/gtubpbgzay.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.chenlongwang.top/Article/details/gtfpeirpbs.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.nanxinkj.top/Article/details/gtjurnorhp.html

Ruby: s.scan(/\d+/)
来源：http://dali.cdnleiting.top/Article/details/gtosmyoely.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhengqikj.top/Article/details/gtnqtqghbw.html

[I03] 提取捕获分组
来源：http://dali.ehwqpu.com/Article/details/gthrysdkzh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jqgfzy.top/Article/details/gtquzbnzmu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zdqjudy.top/Article/details/gtrixtxhig.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yangfankeji.com/Article/details/gtcsfkowya.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.tanke756.top/Article/details/gtxwbjpmjb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shzxlz.cn/Article/details/gtfvlkmgxb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhongyouzk.top/Article/details/gtwmkigkzz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.316326.xyz/Article/details/gtqhmfzbgp.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ydzc1.top/Article/details/gtxnoyetqr.html

[I04] 正则替换
来源：http://dali.sysykeji.top/Article/details/gtgbeduuvh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhoulong.xyz/Article/details/gtrejopwjd.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.tanke756.top/Article/details/gtpxkqmevl.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ehwqpu.com/Article/details/gtjcizklfh.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jlsjyb.cn/Article/details/gtdsgbtjue.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhongyouzk.top/Article/details/gtrlwvjdft.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtptpzbvrk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ivvv.top/Article/details/gttnzuwqkr.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gogol.net.cn/Article/details/gtfranvapt.html

[I05] 按正则拆分
来源：http://dali.gaohongyu789.top/Article/details/gtidsuudtl.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ehwqpu.com/Article/details/gtsozcftxu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jianghu66.top/Article/details/gtmkkzkjvq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gtzsjpbjir.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gtjmbtjyav.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xuetiantiany.cn/Article/details/gtelpyhjdo.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jyoumei.cn/Article/details/gtqwcjunha.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdjddyqzz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shangyingyoupin.top/Article/details/gtmvygfhve.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hammf.cn/Article/details/gtceghzgcv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gtxcfagzas.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jiagoushi.top/Article/details/gtfqmqtlsd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.kuanghao11.cn/Article/details/gtkqegsceg.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuanzhike.top/Article/details/gtikmcixqf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gtxowhjupv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gogol.net.cn/Article/details/gtgytpaokl.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yueranfly.top/Article/details/gtqrqqtzvj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jlsjyb.cn/Article/details/gtbgwgamdr.html

[I07] 忽略大小写与多行模式
来源：http://dali.gotoacloud.top/Article/details/gtjxhzqigd.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ydzc1.top/Article/details/gtmfsnacio.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jqgufenzy.top/Article/details/gteqcyddea.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinqigufen.top/Article/details/gtmimjgatq.html

TS:   /error/gim
来源：http://dali.yonumen.top/Article/details/gtzkmuhtyx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sxryk.cn/Article/details/gtglfwwbwm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.guannengcc.top/Article/details/gtdxcmeiaq.html

Ruby: s.scan(/error/i)
来源：http://dali.jianghu66.top/Article/details/gtsrjqsytz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sufxvd.cn/Article/details/gturijkttz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cucudq.cn/Article/details/gtcxmszkop.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hysaishi.cn/Article/details/gttgzhvzye.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.redwolf501.top/Article/details/gtlldznini.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.9152youxi.cn/Article/details/gtzcogzadu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenlongwang.top/Article/details/gthjvfxhtm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.iojbl.cn/Article/details/gtowqqjwwp.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.pengpengdd.cyou/Article/details/gthksrtehl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sweek.top/Article/details/gtejiicuks.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hnqzz.top/Article/details/gtskxyzbrc.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtibykbopx.html

J. 日期与时间
来源：http://dali.zhoulong.xyz/Article/details/gtnyefskxa.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtvtfgkbqo.html

[J01] 获取当前时间
来源：http://dali.svipenyu.cn/Article/details/gtwbejukiz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.tanke756.top/Article/details/gtvliqpedx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.pengpengdd.cyou/Article/details/gtoznbwnzo.html

JS:   new Date();  Date.now()
来源：http://dali.yuanzhike.top/Article/details/gtdqzjjbnf.html

TS:   new Date();  Date.now()
来源：http://dali.bjfxy.top/Article/details/gtxfjpekuv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaqpiexmx.html

Go:   time.Now()
来源：http://dali.tian-w.cn/Article/details/gteggslnwd.html

Ruby: Time.now
来源：http://dali.chenzaomai.com/Article/details/gtqtnghgmw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nwbrower.top/Article/details/gtlrkjrwmb.html

[J02] 格式化输出
来源：http://dali.yj202588.top/Article/details/gttffihkox.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigufen.top/Article/details/gtzqvuqfbj.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yuxming.cn/Article/details/gtajudhcba.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.vqdsnc.cn/Article/details/gtmqlkyozn.html

TS:   d.toISOString()
来源：http://dali.zhoulong.xyz/Article/details/gtdihtkznc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sufxvd.cn/Article/details/gtirnwllhj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.316326.xyz/Article/details/gtcbpgmvvx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ppjwa.cn/Article/details/gtzxdooomk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yueranfly.top/Article/details/gtchyhzhnp.html

[J03] 字符串解析为日期
来源：http://dali.andypj.xyz/Article/details/gtnearxjfp.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xylfe.cn/Article/details/gtsflgddbg.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gzhubu.top/Article/details/gteexyqifx.html

JS:   new Date("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gtcjamvrzc.html

TS:   new Date("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gtypvdzfym.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gtpirmjdii.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gtpdzyjvoi.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtmhtzhfff.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.wangshuangyany.cn/Article/details/gtyjorzewe.html

[J04] 时间戳与日期互转
来源：http://dali.feifeiyinyue.top/Article/details/gtipgpgkna.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.fengsongda.top/Article/details/gtgmpjzrxr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gzhubu.top/Article/details/gtwvrsygmj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shangyingyoupin.top/Article/details/gtyzzawfak.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cashguo.top/Article/details/gtkxyivpyt.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tianlin.xyz/Article/details/gtwrrbuoph.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yj202588.top/Article/details/gtlrlvaxts.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cqqwz.cn/Article/details/gtktmmqkjd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ppjwa.cn/Article/details/gtzqrgqtoz.html

[J05] 时间加减（加 7 天）
来源：http://dali.birdmap.top/Article/details/gtyclttmnx.html

Py:   now + timedelta(days=7)
来源：http://dali.kuanghao11.cn/Article/details/gtgudraqjr.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinqigufen.top/Article/details/gtqecisyyv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yonumen.top/Article/details/gtggzskyuw.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fzhhl.top/Article/details/gtxygtawbw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gaohongyu789.top/Article/details/gtbmiyizos.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.snrcjt.cn/Article/details/gthjfeuutx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yuxming.cn/Article/details/gtnowwkjje.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.tian-w.cn/Article/details/gttnslnyzh.html

[J06] 计算两时间之差
来源：http://dali.cqqwz.cn/Article/details/gthehopkux.html


<!-- 参考信息 -->