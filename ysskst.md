代发 wailian999

TS:   greet(): string { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gtcykljyhd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gtevysgusq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hywenlv.cn/Article/details/gtpoiqddqf.html

Ruby: def greet; "admin"; end
来源：http://dali.cucudq.cn/Article/details/gtvbzwhcut.html

C#:   public override string Greet() => "admin";
来源：http://dali.snrcjt.cn/Article/details/gtohahtqkx.html

[G07] 调用父类方法
来源：http://dali.xziqi.cn/Article/details/gtcikecvcg.html

Py:   super().greet()
来源：http://dali.yj20258888.top/Article/details/gtvfcmpyxd.html

PHP:  parent::greet();
来源：http://dali.dashuyun.cn/Article/details/gtawweknxv.html

JS:   super.greet();
来源：http://dali.tianlin.xyz/Article/details/gtevhhkbja.html

TS:   super.greet();
来源：http://dali.nanxuanxn.top/Article/details/gtmunssxjf.html

Java: super.greet();
来源：http://dali.aibaodan.cn/Article/details/gtekaaduhx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sweek.top/Article/details/gtmbdbwlsb.html

Ruby: super
来源：http://dali.xuetiantiany.cn/Article/details/gtjvvokqcu.html

C#:   base.Greet();
来源：http://dali.iojbl.cn/Article/details/gtengcbpky.html

[G08] 静态方法与属性
来源：http://dali.tian-w.cn/Article/details/gtxpldaycj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinqigufen.top/Article/details/gtwoglkpan.html

PHP:  public static function f() {}
来源：http://dali.zdqjudy.top/Article/details/gtofpdzntx.html

JS:   static f() {}
来源：http://dali.aizwys.cn/Article/details/gtoqweqdrs.html

TS:   static f(): void {}
来源：http://dali.sufxvd.cn/Article/details/gtrvrzvhcn.html

Java: static void f() {}
来源：http://dali.yueranfly.top/Article/details/gtqgzbsuyx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jqgfzy.top/Article/details/gtyddnitjz.html

Ruby: def self.f; end
来源：http://dali.shzxlz.cn/Article/details/gtbmhibcbs.html

C#:   public static void F() {}
来源：http://dali.jqgufenzy.top/Article/details/gtujotufft.html

[G09] 接口 / 抽象类
来源：http://dali.fzhhl.top/Article/details/gtkzokeofu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gaohongyu789.top/Article/details/gtxcgajamw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hfpthk.cn/Article/details/gtmdlgqtiv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.fzhhl.top/Article/details/gtqlfstsnh.html

TS:   interface Shape { area(): number; }
来源：http://dali.daria6918.cn/Article/details/gtjveksnqv.html

Java: interface Shape { double area(); }
来源：http://dali.cdnleiting.top/Article/details/gtjuheswjq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.feifeiyinyue.top/Article/details/gthleokile.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.fzhhl.top/Article/details/gtiapeljuq.html

C#:   interface IShape { double Area(); }
来源：http://dali.hysaishi.cn/Article/details/gtsnfyrbby.html

[G10] 访问控制
来源：http://dali.pycfn.com/Article/details/gtvgmdiegl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.guowangkeji.top/Article/details/gtnvdrhkoo.html

PHP:  public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gtrvsjxmvm.html

JS:   #private 字段；其余公开
来源：http://dali.ybcxt.top/Article/details/gtcbizofiq.html

TS:   public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gtekfazsrc.html

Java: public / protected / private / 默认包级
来源：http://dali.sweek.top/Article/details/gtrbojsrvo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.feifeiyinyue.top/Article/details/gteknezqys.html

Ruby: public / protected / private
来源：http://dali.daxiang520.top/Article/details/gttptgvdiv.html

C#:   public / protected / private / internal
来源：http://dali.sysykeji.top/Article/details/gtgkevttue.html

[G11] getter / setter
来源：http://dali.svipenyu.cn/Article/details/gteblexuqd.html

Py:   @property 与 @x.setter
来源：http://dali.chenzaomai.com/Article/details/gtwvirwzgp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jyoumei.cn/Article/details/gtwkweobpn.html

JS:   get name() { return this._name; }
来源：http://dali.sweek.top/Article/details/gtdjnipilw.html

TS:   get name(): string { return this._name; }
来源：http://dali.meibo888.top/Article/details/gtswkalskd.html

Java: public String getName() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtfaqiihxk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gtfzhvygtf.html

Ruby: attr_accessor :name
来源：http://dali.zhixingplan.top/Article/details/gtztfbnxwm.html

C#:   public string Name { get; set; }
来源：http://dali.316326.xyz/Article/details/gtvkxzjkih.html

[G12] 对象转字符串
来源：http://dali.tanke756.top/Article/details/gtokgatnjm.html

Py:   def __str__(self): return self.name
来源：http://dali.yangfankeji.com/Article/details/gthgbtimpa.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gtdawaixfw.html

JS:   toString() { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gtvnxxgork.html

TS:   toString(): string { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gtmkkiahhe.html

Java: @Override public String toString() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gtmcctzylq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.9152youxi.cn/Article/details/gtpnkenazj.html

Ruby: def to_s; @name; end
来源：http://dali.zhoulong.xyz/Article/details/gtpmlchjzd.html

C#:   public override string ToString() => Name;
来源：http://dali.zdqjudy.top/Article/details/gtuwngrvyx.html

[G13] 判断对象类型
来源：http://dali.cashguo.top/Article/details/gthfizacrl.html

Py:   isinstance(u, User)
来源：http://dali.daxiang520.top/Article/details/gtzmxrxjen.html

PHP:  $u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gtqeutbdty.html

JS:   u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gtouupvyok.html

TS:   u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gtmnlcgrlj.html

Java: u instanceof User
来源：http://dali.yueranfly.top/Article/details/gtljfgpswx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shanyushiyangtech.top/Article/details/gtpoetocxt.html

Ruby: u.is_a?(User)
来源：http://dali.sysykeji.top/Article/details/gtyqgzvijz.html

C#:   u is User
来源：http://dali.nanxinkj.top/Article/details/gtmdjdyeyn.html

[G14] 数据类 / record
来源：http://dali.pycfn.com/Article/details/gttjonmkgy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtudbfjymx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yangfankeji.com/Article/details/gtqhuomzfa.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.aizwys.cn/Article/details/gtwwxuxald.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gtjxacdwhl.html

Java: record User(String name, int age) {}
来源：http://dali.zhixingplan.top/Article/details/gtqoqgrrif.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqtbozsut.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cheryme.top/Article/details/gtyhyyoepe.html

C#:   record User(string Name, int Age);
来源：http://dali.yj20258888.top/Article/details/gtqcltinaz.html

[G15] 枚举
来源：http://dali.chenjidiqi.icu/Article/details/gtsrvxeuhf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.nwbrower.top/Article/details/gtvctxufhl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ydzc1.top/Article/details/gtqjskmkkh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.havefunace.top/Article/details/gtoypowfgm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dianchejie.cn/Article/details/gtyjolqvpx.html

Java: enum Color { RED, GREEN }
来源：http://dali.sysykeji.top/Article/details/gtuxojxnda.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.havefunace.top/Article/details/gtrbshdxeg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sufxvd.cn/Article/details/gtnqwllunu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxinkj.top/Article/details/gtkzpefmhw.html

[G16] 对象转数组 / 字典
来源：http://dali.ybcxt.top/Article/details/gtbsbsfyik.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhiwuduotai.top/Article/details/gtsiqveesq.html

PHP:  get_object_vars($obj);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmsqgkblx.html

JS:   Object.entries(obj)
来源：http://dali.jinqigufen.top/Article/details/gthaekvioz.html

TS:   Object.entries(obj)
来源：http://dali.fzhhl.top/Article/details/gtslnrcghz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.guannengcc.top/Article/details/gtpdcmbsjm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.guannengcc.top/Article/details/gtnxmxmbsw.html

Ruby: obj.instance_variables
来源：http://dali.ivvv.top/Article/details/gtrbkxmgab.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhaomingkeji.xyz/Article/details/gtejswgnyz.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtapqmzfpp.html

H. 异常与错误处理
来源：http://dali.cashguo.top/Article/details/gtjczrspsw.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtamalrewr.html

[H01] try / catch 基础
来源：http://dali.shuidangran.top/Article/details/gtclevoydo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.fzhhl.top/Article/details/gtjqfkreod.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.snrcjt.cn/Article/details/gtbxjlntra.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.daxiang520.top/Article/details/gtiukgqihr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.aibaodan.cn/Article/details/gtmygufepq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhoulong.xyz/Article/details/gtioqvhkld.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shzxlz.cn/Article/details/gtjeortxko.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zdqjudy.top/Article/details/gtktxnwgsz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sysykeji.top/Article/details/gtjdbebesm.html

[H02] finally / ensure 收尾
来源：http://dali.redwolf501.top/Article/details/gtcfeqcbai.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.feifeiyinyue.top/Article/details/gtqnasbliw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtcwwfewpr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtugtuebyf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gtrtyumrzm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtbmukgrzi.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.havefunace.top/Article/details/gtoockvtro.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ivvv.top/Article/details/gtqiotvkwh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gtiqpuykcl.html

[H03] 主动抛出异常
来源：http://dali.gaohongyu789.top/Article/details/gtubhwipmy.html

Py:   raise ValueError("错误信息")
来源：http://dali.nwbrower.top/Article/details/gtffttokof.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtfzlljgme.html

JS:   throw new Error("错误信息");
来源：http://dali.tanke756.top/Article/details/gtjpmpmesy.html

TS:   throw new Error("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gthapknnny.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtsclewywk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xylfe.cn/Article/details/gtaxnzfrzg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shzxlz.cn/Article/details/gteavskako.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gtolibpblc.html

[H04] 自定义异常类型
来源：http://dali.316326.xyz/Article/details/gtuunzntnn.html

Py:   class MyError(Exception): pass
来源：http://dali.feifeiyinyue.top/Article/details/gtbrxiivai.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhengqikj.top/Article/details/gtapmakbgu.html

JS:   class MyError extends Error {}
来源：http://dali.c1oappe.top/Article/details/gtxloypfsu.html

TS:   class MyError extends Error {}
来源：http://dali.yj202588.top/Article/details/gtmmtklmgg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shuidangran.top/Article/details/gtjlvoxxin.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.chenlongwang.top/Article/details/gtourgodao.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmnfstqqx.html

C#:   class MyException : Exception {}
来源：http://dali.ydzc1.top/Article/details/gtopppvehe.html

[H05] 捕获特定类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwfzlbrwx.html

Py:   except ValueError as e:
来源：http://dali.chenzaomai.com/Article/details/gtiwgqymat.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jqgufenzy.top/Article/details/gtusycssyv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gogol.net.cn/Article/details/gtdfjxvzbm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.daria6918.cn/Article/details/gthntwlwod.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cheryme.top/Article/details/gtpwgpqbnu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.aibaodan.cn/Article/details/gteqioquef.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhongyouzk.top/Article/details/gtthtltfvp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.0kj1m.cn/Article/details/gttakfsifu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yvedp.cn/Article/details/gtcroioggl.html

Py:   value = d.get("k") or default
来源：http://dali.tian-w.cn/Article/details/gtoyvluvxk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jlsjyb.cn/Article/details/gtxvcgkjbt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.svipenyu.cn/Article/details/gtkmwwwvqb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hnqzz.top/Article/details/gtkqykdjmy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.kuanghao11.cn/Article/details/gtxhbrqqfe.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.quarkkingdee.top/Article/details/gtiwuuuyex.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ivvv.top/Article/details/gtgsuwzpbx.html

C#:   obj?.A?.B ?? default
来源：http://dali.hfpthk.cn/Article/details/gtnvacadnb.html

[H07] 断言
来源：http://dali.zycfv.cn/Article/details/gtuezxyrvv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ppjwa.cn/Article/details/gtogiktzsm.html

PHP:  assert($x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gtlzckazak.html

JS:   console.assert(x > 0);
来源：http://dali.sufxvd.cn/Article/details/gtuokvngmr.html

TS:   console.assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gtwrspfgna.html

Java: assert x > 0 : "必须为正";
来源：http://dali.pycfn.com/Article/details/gtehaujova.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj20258888.top/Article/details/gtoftpytfr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zdqjudy.top/Article/details/gtsokvmdkn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gtckhttitn.html

[H08] 获取错误信息与堆栈
来源：http://dali.cqqwz.cn/Article/details/gtbgxqxusz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.dashuyun.cn/Article/details/gtkuxuivha.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shzxlz.cn/Article/details/gtpjchnhuf.html

JS:   e.message;  e.stack
来源：http://dali.dianchejie.cn/Article/details/gtvytalect.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cheryme.top/Article/details/gtoykhhagy.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hywenlv.cn/Article/details/gtpdkpwgjq.html

Go:   err.Error()
来源：http://dali.yongpay.top/Article/details/gtkrsgwbhx.html

Ruby: e.message;  e.backtrace
来源：http://dali.ppjwa.cn/Article/details/gtedtbfnde.html

C#:   e.Message;  e.StackTrace
来源：http://dali.chenlongwang.top/Article/details/gtpbvduzcj.html

[H09] 带错误码的异常
来源：http://dali.ivvv.top/Article/details/gtlgnybxjr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cheryme.top/Article/details/gtvbkmxllk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sxryk.cn/Article/details/gtmrqkjqdo.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ehwqpu.com/Article/details/gtnfctvcdc.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shzxlz.cn/Article/details/gtzxtakxur.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shzxlz.cn/Article/details/gtghbmbgfz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yj202588.top/Article/details/gtsanzhpew.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ppjwa.cn/Article/details/gtvfnoemtc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.316326.xyz/Article/details/gttevitalc.html

[H10] 资源自动释放
来源：http://dali.yongpay.top/Article/details/gtyfmtlbfl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jqgufenzy.top/Article/details/gtmuvfnfvp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cashguo.top/Article/details/gtpygmrajv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ivvv.top/Article/details/gtqpjssqss.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hammf.cn/Article/details/gtidnvireo.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhiwuduotai.top/Article/details/gtjxzcbvqo.html

Go:   defer f.Close()
来源：http://dali.shuidangran.top/Article/details/gtyyasktoi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yj20258.top/Article/details/gtrncqcsse.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtzqhnfiyu.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtzxyfjdip.html

I. 正则表达式
来源：http://dali.vqdsnc.cn/Article/details/gtvnjyojeg.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtivuadlev.html

[I01] 判断是否匹配
来源：http://dali.yj20258888.top/Article/details/gtthjlntao.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.dashuyun.cn/Article/details/gtolbjrinz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtjwajahvr.html

JS:   /\d+/.test(s)
来源：http://dali.pycfn.com/Article/details/gtynjxsrok.html

TS:   /\d+/.test(s)
来源：http://dali.quarkkingdee.top/Article/details/gtsfshoxkm.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ybcxt.top/Article/details/gtetkjetwa.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmziwtoct.html

Ruby: s.match?(/\d+/)
来源：http://dali.yanxiufei.cn/Article/details/gttmdrjwcz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinghuilouyu.cn/Article/details/gthvrjprxs.html

[I02] 提取所有匹配
来源：http://dali.gzhubu.top/Article/details/gtyzypffxh.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxiijvqer.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sufxvd.cn/Article/details/gtnlkyzhon.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.tianlin.xyz/Article/details/gtlzdyyeil.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gtbufgetah.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ppjwa.cn/Article/details/gtctqaohck.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yvedp.cn/Article/details/gtrnqmurem.html

Ruby: s.scan(/\d+/)
来源：http://dali.sufxvd.cn/Article/details/gtbbudgksu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jiagoushi.top/Article/details/gtnpfcsuem.html

[I03] 提取捕获分组
来源：http://dali.chenjidiqi.icu/Article/details/gtapvmgrdh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.iojbl.cn/Article/details/gtmaqipxss.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hnxiangtu.top/Article/details/gtclbslboc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.havefunace.top/Article/details/gtnjlxmlyn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gtnphzjlsz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ppjwa.cn/Article/details/gttwdkeysw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yueranfly.top/Article/details/gtjrepswou.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hfpthk.cn/Article/details/gtzckelnki.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xuetiantiany.cn/Article/details/gteryfvswh.html

[I04] 正则替换
来源：http://dali.zhengqikj.top/Article/details/gtrejfycwt.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jlsjyb.cn/Article/details/gtgvemyvkq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cdnleiting.top/Article/details/gtiosrmyyp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xuanzx.com/Article/details/gtpzpeynqu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.meibo888.top/Article/details/gtmwtotlwk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhiwuduotai.top/Article/details/gtmgwbdolm.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.andypj.xyz/Article/details/gtkxdfddmh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cqqwz.cn/Article/details/gtvcqujhnm.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.wangdashe.top/Article/details/gtknmytkwi.html

[I05] 按正则拆分
来源：http://dali.guowangkeji.top/Article/details/gteyfgfvnl.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zdqjudy.top/Article/details/gtkupycudc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yvedp.cn/Article/details/gtfezzepbh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gtzhhnjsyk.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.birdmap.top/Article/details/gtiylygzfm.html

Java: s.split("\\s*,\\s*")
来源：http://dali.snrcjt.cn/Article/details/gtgstefscg.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.birdmap.top/Article/details/gtumxdaelx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.9152youxi.cn/Article/details/gtacavqanr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ybcxt.top/Article/details/gtheljgkuc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yj202588.top/Article/details/gtpdiicpmv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hnqzz.top/Article/details/gtmyuzfpxc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ydzc1.top/Article/details/gttojipanf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cheryme.top/Article/details/gtijygetbg.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgfzy.top/Article/details/gtjvyaoifp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gtbzyzshxg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgarfgisz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jyoumei.cn/Article/details/gtcvpzxkby.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gtdzvbkffj.html

[I07] 忽略大小写与多行模式
来源：http://dali.hysaishi.cn/Article/details/gtmbfddzea.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhoulong.xyz/Article/details/gtapripuuy.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnxoezets.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zycfv.cn/Article/details/gtzqqhyznq.html

TS:   /error/gim
来源：http://dali.sufxvd.cn/Article/details/gtszfwcvnn.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yuxming.cn/Article/details/gtetxkafsr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yuxming.cn/Article/details/gttwgnbnlx.html

Ruby: s.scan(/error/i)
来源：http://dali.jianghu66.top/Article/details/gtdbzdffkc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shzxlz.cn/Article/details/gtmqhsrtlo.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.andypj.xyz/Article/details/gtnfeuflux.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yuxming.cn/Article/details/gtmsjdhukw.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jianghu66.top/Article/details/gtfgxyjykr.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gtibtzgdse.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenlongwang.top/Article/details/gtowkpitac.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gogol.net.cn/Article/details/gtbwtpbjnu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.tanke756.top/Article/details/gtznhnjaaz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.9152youxi.cn/Article/details/gtcbbqkegb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sxryk.cn/Article/details/gtyncalkep.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtqabdxock.html

J. 日期与时间
来源：http://dali.vqdsnc.cn/Article/details/gtwkrtysyn.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtpxulwscb.html

[J01] 获取当前时间
来源：http://dali.jiagoushi.top/Article/details/gtuhndorzw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yvedp.cn/Article/details/gtigryckge.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.9152youxi.cn/Article/details/gtcxxweglg.html

JS:   new Date();  Date.now()
来源：http://dali.c1oappe.top/Article/details/gtlqfpnwte.html

TS:   new Date();  Date.now()
来源：http://dali.jiagoushi.top/Article/details/gtrubahllu.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.fengsongda.top/Article/details/gtuvsnejho.html

Go:   time.Now()
来源：http://dali.jinghuilouyu.cn/Article/details/gtvqvlruac.html

Ruby: Time.now
来源：http://dali.yanxiufei.cn/Article/details/gtlvunpxom.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shanyushiyangtech.top/Article/details/gtwavifpfn.html

[J02] 格式化输出
来源：http://dali.ydzc1.top/Article/details/gtlxxjzgcl.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dianchejie.cn/Article/details/gtykzheraf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gtnepuwcqc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.sweek.top/Article/details/gttrmvmlxv.html

TS:   d.toISOString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtmsjaezer.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ppjwa.cn/Article/details/gttrpkjlto.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yj20258888.top/Article/details/gtxswzljbo.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.feifeiyinyue.top/Article/details/gtfphlltes.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ehwqpu.com/Article/details/gthvonlyxh.html

[J03] 字符串解析为日期
来源：http://dali.pycfn.com/Article/details/gtghlzjxsm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sufxvd.cn/Article/details/gttvkoqbvg.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhengqikj.top/Article/details/gtxlrmwtto.html

JS:   new Date("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gtfbgkvjzr.html

TS:   new Date("2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gtlzenwzcz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gtjmesrwwh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gtegvufpzg.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gtktqszorh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hysaishi.cn/Article/details/gtrteyyico.html

[J04] 时间戳与日期互转
来源：http://dali.vqdsnc.cn/Article/details/gtinwdcywv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cashguo.top/Article/details/gtyuhfmvhb.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ydzc1.top/Article/details/gtxtrcpzus.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.vqdsnc.cn/Article/details/gtkmnfnoaw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zdqjudy.top/Article/details/gtduzxmorz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yanxiufei.cn/Article/details/gtpiibndic.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.316326.xyz/Article/details/gtnybwnohy.html


<!-- 参考信息 -->