代发 wailian999

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gthzurjbmd.html

Py:   def greet(self): return "admin"
来源：http://dali.hongshengwenyu.top/Article/details/gtdgxvrcoh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gteffzxhzs.html

JS:   greet() { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gttkuqdsmo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gtbamwymym.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtqgpamttc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.wangshuangyany.cn/Article/details/gtlopgmfeu.html

Ruby: def greet; "admin"; end
来源：http://dali.yueranfly.top/Article/details/gtdzkbjrka.html

C#:   public override string Greet() => "admin";
来源：http://dali.sweek.top/Article/details/gtkbwuucez.html

[G07] 调用父类方法
来源：http://dali.zycfv.cn/Article/details/gtkwadhlws.html

Py:   super().greet()
来源：http://dali.cdnleiting.top/Article/details/gtyrcrdhzi.html

PHP:  parent::greet();
来源：http://dali.yj20258888.top/Article/details/gtvfgmiaez.html

JS:   super.greet();
来源：http://dali.iojbl.cn/Article/details/gtxvquaaqn.html

TS:   super.greet();
来源：http://dali.jianghu66.top/Article/details/gtolvngekc.html

Java: super.greet();
来源：http://dali.mhx1999.top/Article/details/gtvrnjjbdg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xziqi.cn/Article/details/gtguuokmhw.html

Ruby: super
来源：http://dali.dashuyun.cn/Article/details/gtrnvjuiru.html

C#:   base.Greet();
来源：http://dali.yonumen.top/Article/details/gtdnorrzwy.html

[G08] 静态方法与属性
来源：http://dali.fzhhl.top/Article/details/gtnftkrgoo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cqqwz.cn/Article/details/gtmyxvpvao.html

PHP:  public static function f() {}
来源：http://dali.jianghu66.top/Article/details/gtrodbjghx.html

JS:   static f() {}
来源：http://dali.sxryk.cn/Article/details/gtagabodtz.html

TS:   static f(): void {}
来源：http://dali.dashuyun.cn/Article/details/gtwenqlmdw.html

Java: static void f() {}
来源：http://dali.quarkkingdee.top/Article/details/gtxmltfdhx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.316326.xyz/Article/details/gtngurjgae.html

Ruby: def self.f; end
来源：http://dali.kuanghao11.cn/Article/details/gtedaxmubh.html

C#:   public static void F() {}
来源：http://dali.iojbl.cn/Article/details/gtkwlthhuv.html

[G09] 接口 / 抽象类
来源：http://dali.jiagoushi.top/Article/details/gtiaccngij.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hywenlv.cn/Article/details/gtpopcgmmh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.aibaodan.cn/Article/details/gtnlnqrulj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ehwqpu.com/Article/details/gtlciefmvp.html

TS:   interface Shape { area(): number; }
来源：http://dali.redwolf501.top/Article/details/gtmpzurjfe.html

Java: interface Shape { double area(); }
来源：http://dali.kuanghao11.cn/Article/details/gtxasadnjx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yongpay.top/Article/details/gtbihacchm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yuxming.cn/Article/details/gtznfgovte.html

C#:   interface IShape { double Area(); }
来源：http://dali.fengsongda.top/Article/details/gtikdcnrnd.html

[G10] 访问控制
来源：http://dali.smart0.xyz/Article/details/gtbkzngmpr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jqgufenzy.top/Article/details/gtvrhgeklz.html

PHP:  public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gtodkkyqun.html

JS:   #private 字段；其余公开
来源：http://dali.chenjidiqi.icu/Article/details/gtrvooqjxs.html

TS:   public / protected / private
来源：http://dali.yueranfly.top/Article/details/gtxqetjgln.html

Java: public / protected / private / 默认包级
来源：http://dali.gzhubu.top/Article/details/gtrszehmcl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gzhubu.top/Article/details/gtfsswfbcj.html

Ruby: public / protected / private
来源：http://dali.nanxuanxn.top/Article/details/gtyslxmzvv.html

C#:   public / protected / private / internal
来源：http://dali.yj202588.top/Article/details/gttckopjuf.html

[G11] getter / setter
来源：http://dali.vqdsnc.cn/Article/details/gtsejgnjcp.html

Py:   @property 与 @x.setter
来源：http://dali.bjfxy.top/Article/details/gtyvcljtjb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.c1oappe.top/Article/details/gtxwqmklkl.html

JS:   get name() { return this._name; }
来源：http://dali.zhengqikj.top/Article/details/gtnxailqay.html

TS:   get name(): string { return this._name; }
来源：http://dali.yj202588.top/Article/details/gtjnwgewjw.html

Java: public String getName() { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gtetpzkngd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gtlvspvnqs.html

Ruby: attr_accessor :name
来源：http://dali.quarkkingdee.top/Article/details/gteyteintb.html

C#:   public string Name { get; set; }
来源：http://dali.shzxlz.cn/Article/details/gtkeqjvdpa.html

[G12] 对象转字符串
来源：http://dali.shzxlz.cn/Article/details/gtqexfamwf.html

Py:   def __str__(self): return self.name
来源：http://dali.snrcjt.cn/Article/details/gteqpmwhux.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gtdwnvvmqe.html

JS:   toString() { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gtrkbtjkdr.html

TS:   toString(): string { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gtiyugwneb.html

Java: @Override public String toString() { return name; }
来源：http://dali.yj20258888.top/Article/details/gtaodxompx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gtkmzxshwy.html

Ruby: def to_s; @name; end
来源：http://dali.c1oappe.top/Article/details/gtuvzocojp.html

C#:   public override string ToString() => Name;
来源：http://dali.zycfv.cn/Article/details/gtibpwbsyo.html

[G13] 判断对象类型
来源：http://dali.daxiang520.top/Article/details/gtpqwcphmn.html

Py:   isinstance(u, User)
来源：http://dali.zhengqikj.top/Article/details/gtzkzuuirh.html

PHP:  $u instanceof User
来源：http://dali.meibo888.top/Article/details/gtdejxyxia.html

JS:   u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gtvqkwjvyk.html

TS:   u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gtjizkzwgk.html

Java: u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gtzeiblavu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.9152youxi.cn/Article/details/gtehmakola.html

Ruby: u.is_a?(User)
来源：http://dali.zhongyouzk.top/Article/details/gtddlxzupw.html

C#:   u is User
来源：http://dali.cucudq.cn/Article/details/gtllvmfetc.html

[G14] 数据类 / record
来源：http://dali.smart0.xyz/Article/details/gtgczcixil.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.svipenyu.cn/Article/details/gtnogotcre.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yonumen.top/Article/details/gtpoxmwtwm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.guannengcc.top/Article/details/gtmoglplzx.html

TS:   type User = { name: string; age: number };
来源：http://dali.cheryme.top/Article/details/gttmrgylcg.html

Java: record User(String name, int age) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsqbcbdpi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gtsurwdgkd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhixingplan.top/Article/details/gtfrpsxgxn.html

C#:   record User(string Name, int Age);
来源：http://dali.zhongyouzk.top/Article/details/gtaktejhdw.html

[G15] 枚举
来源：http://dali.ydzc1.top/Article/details/gtxbofogdb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.feifeiyinyue.top/Article/details/gtmiaimrnw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.nanxinkj.top/Article/details/gthjcyqhis.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.guannengcc.top/Article/details/gtguzxllue.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fengsongda.top/Article/details/gtpdodkhcg.html

Java: enum Color { RED, GREEN }
来源：http://dali.316326.xyz/Article/details/gtztnqcpev.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinqigufen.top/Article/details/gtroorhxzt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ivvv.top/Article/details/gtyfthaspa.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guannengcc.top/Article/details/gtmgkynzuo.html

[G16] 对象转数组 / 字典
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuiotaime.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.316326.xyz/Article/details/gtcradjujp.html

PHP:  get_object_vars($obj);
来源：http://dali.ehwqpu.com/Article/details/gtfbigyhzz.html

JS:   Object.entries(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqopataka.html

TS:   Object.entries(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtzbvopens.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.iojbl.cn/Article/details/gtsrsqvwtq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.iojbl.cn/Article/details/gtriczcdwj.html

Ruby: obj.instance_variables
来源：http://dali.zhiwuduotai.top/Article/details/gtzzniplmn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jiagoushi.top/Article/details/gtldluiuzz.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtlnzdnnmw.html

H. 异常与错误处理
来源：http://dali.yj20258.top/Article/details/gtclpmgfca.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtvollownc.html

[H01] try / catch 基础
来源：http://dali.jqgufenzy.top/Article/details/gtixppyvjy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jianghu66.top/Article/details/gtguttthaw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.wangdashe.top/Article/details/gtihxjgusg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yonumen.top/Article/details/gtjtjgqjzt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tian-w.cn/Article/details/gteeelicas.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhengqikj.top/Article/details/gtusizyhos.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cucudq.cn/Article/details/gtsooywzyb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhengqikj.top/Article/details/gtxgcqqglm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.aizwys.cn/Article/details/gtssyaaave.html

[H02] finally / ensure 收尾
来源：http://dali.jiagoushi.top/Article/details/gtutqbijvb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yuanzhike.top/Article/details/gtntkoigho.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gthhxgnxui.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtlzxuhgyu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtewhdgimp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gtlqrajnrk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.fengsongda.top/Article/details/gtejgcquko.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nanxuanxn.top/Article/details/gtpwdbjoma.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gtcaaluald.html

[H03] 主动抛出异常
来源：http://dali.shanyushiyangtech.top/Article/details/gtlflvmzvp.html

Py:   raise ValueError("错误信息")
来源：http://dali.xuetiantiany.cn/Article/details/gtxjfcyvcp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtympgvrjp.html

JS:   throw new Error("错误信息");
来源：http://dali.cheryme.top/Article/details/gtiwqkojhl.html

TS:   throw new Error("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtkkohnvqw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtwdkdsqhm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ivvv.top/Article/details/gtewhpbgxz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hammf.cn/Article/details/gtogbgeduz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtkfyxurdz.html

[H04] 自定义异常类型
来源：http://dali.hongshengwenyu.top/Article/details/gttwosiuxf.html

Py:   class MyError(Exception): pass
来源：http://dali.pengpengdd.cyou/Article/details/gtgvsopqkt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj20258888.top/Article/details/gtqjaenrwq.html

JS:   class MyError extends Error {}
来源：http://dali.bjfxy.top/Article/details/gtugbmxtib.html

TS:   class MyError extends Error {}
来源：http://dali.chenjidiqi.icu/Article/details/gtzyseiiqi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sxryk.cn/Article/details/gtdppxqvxm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jlsjyb.cn/Article/details/gtmzemedbl.html

Ruby: class MyError < StandardError; end
来源：http://dali.tianlin.xyz/Article/details/gtvbvbedto.html

C#:   class MyException : Exception {}
来源：http://dali.feifeiyinyue.top/Article/details/gtnkfwsbli.html

[H05] 捕获特定类型
来源：http://dali.sysykeji.top/Article/details/gtewlawfle.html

Py:   except ValueError as e:
来源：http://dali.xylfe.cn/Article/details/gtzekrxbqq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shangyingyoupin.top/Article/details/gtgqljdzpu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gaohongyu789.top/Article/details/gtsnmpkxeu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258888.top/Article/details/gtwqbosohd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenlongwang.top/Article/details/gtitytsyvk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yvedp.cn/Article/details/gtnrrqomxh.html

Ruby: rescue ArgumentError => e
来源：http://dali.xziqi.cn/Article/details/gtmppybjme.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zycfv.cn/Article/details/gtgwomuokd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cheryme.top/Article/details/gtbrbbpuai.html

Py:   value = d.get("k") or default
来源：http://dali.quarkkingdee.top/Article/details/gtmqekqtat.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hammf.cn/Article/details/gtycninqbk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cdnleiting.top/Article/details/gtplamitwu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cqqwz.cn/Article/details/gttxdwfedf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xinyue.icu/Article/details/gtmlfxnxjb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cqqwz.cn/Article/details/gtztbbhnvf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtymdjkdyi.html

C#:   obj?.A?.B ?? default
来源：http://dali.shuidangran.top/Article/details/gtioryypjt.html

[H07] 断言
来源：http://dali.yuxming.cn/Article/details/gtanziepbk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinqigufen.top/Article/details/gtsxcdbcly.html

PHP:  assert($x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtuzxbapyb.html

JS:   console.assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gtxziibvtr.html

TS:   console.assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gthbesixrh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.kuanghao11.cn/Article/details/gtnkyofcls.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.316326.xyz/Article/details/gtcfomprwz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jqgufenzy.top/Article/details/gtoarlngos.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yuxming.cn/Article/details/gtnwjqobze.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhiwuduotai.top/Article/details/gttwmuwpno.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinghuilouyu.cn/Article/details/gtfptnxjtz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.svipenyu.cn/Article/details/gtkycvclbg.html

JS:   e.message;  e.stack
来源：http://dali.yj20258888.top/Article/details/gtolhlspjz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhongyouzk.top/Article/details/gtyunfkfwz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.aibaodan.cn/Article/details/gtvveyunuy.html

Go:   err.Error()
来源：http://dali.shzxlz.cn/Article/details/gtitcbsaba.html

Ruby: e.message;  e.backtrace
来源：http://dali.hongshengwenyu.top/Article/details/gtunndbanv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gthidkyskq.html

[H09] 带错误码的异常
来源：http://dali.shanyushiyangtech.top/Article/details/gthkrjdupz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xinyue.icu/Article/details/gtuwmruspt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnsxpgcap.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.aibaodan.cn/Article/details/gtuywraara.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.smart0.xyz/Article/details/gtksnpbtue.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.fengsongda.top/Article/details/gtrcucpzcv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.daxiang520.top/Article/details/gtbtdqcmaw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.bjfxy.top/Article/details/gtznnkhcus.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenjidiqi.icu/Article/details/gtjhsvxmvg.html

[H10] 资源自动释放
来源：http://dali.zhoulong.xyz/Article/details/gthykdikkc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cashguo.top/Article/details/gtnoxzctdm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zycfv.cn/Article/details/gtencrvgpx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgfzy.top/Article/details/gtknldhrgm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbrpjalom.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yueranfly.top/Article/details/gtegfuqoso.html

Go:   defer f.Close()
来源：http://dali.chenzaomai.com/Article/details/gtfyutdmwt.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhixingplan.top/Article/details/gtlkryeyxh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtykwziovw.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtvzqmgkpa.html

I. 正则表达式
来源：http://dali.zhixingplan.top/Article/details/gtrrqruitb.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtlkhnsqde.html

[I01] 判断是否匹配
来源：http://dali.yj20258888.top/Article/details/gtlozrmemt.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhongyouzk.top/Article/details/gtdzvmxhip.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.iojbl.cn/Article/details/gtmicvenfh.html

JS:   /\d+/.test(s)
来源：http://dali.ppjwa.cn/Article/details/gtfuswodpo.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gtswhzblwv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tianlin.xyz/Article/details/gtrxignikd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxtuqcakp.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlijjolhi.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.havefunace.top/Article/details/gtxxxgauxy.html

[I02] 提取所有匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtkytcwbsd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gaohongyu789.top/Article/details/gtqxvrutlz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hfpthk.cn/Article/details/gtoppsypig.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ybcxt.top/Article/details/gttonrhoqd.html

TS:   s.match(/\d+/g)
来源：http://dali.cashguo.top/Article/details/gttduqytpl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yonumen.top/Article/details/gttbhomsft.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.tianlin.xyz/Article/details/gtuhweebwh.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqrlocweo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zycfv.cn/Article/details/gtfhsfcxjb.html

[I03] 提取捕获分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfduefcvs.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.wangdashe.top/Article/details/gtytlxoiwm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.snrcjt.cn/Article/details/gtxgfanppm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gtrorbwsko.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gotoacloud.top/Article/details/gttnicfwbr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhiwuduotai.top/Article/details/gtoimjzthx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenlongwang.top/Article/details/gtiwcvuezn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yvedp.cn/Article/details/gtgdzaqwnm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cqqwz.cn/Article/details/gtvbafgjzx.html

[I04] 正则替换
来源：http://dali.jyoumei.cn/Article/details/gtqdjlxexm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jyoumei.cn/Article/details/gtluycwbmn.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cucudq.cn/Article/details/gtjakqnjpe.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yvedp.cn/Article/details/gtkgvqgkfi.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.316326.xyz/Article/details/gtgwyyiidw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gogol.net.cn/Article/details/gtwhfozfyc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ybcxt.top/Article/details/gtgmcjiuki.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xinyue.icu/Article/details/gtzkkietob.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yj202588.top/Article/details/gtsyjzcafr.html

[I05] 按正则拆分
来源：http://dali.nanxuanxn.top/Article/details/gtctlvshrl.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhoulong.xyz/Article/details/gtilftpxnc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtguistraq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.nanxuanxn.top/Article/details/gtejdlycmy.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.316326.xyz/Article/details/gtwhpwvdmu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.guowangkeji.top/Article/details/gtcfyiqjhr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhoulong.xyz/Article/details/gtxmzjmakw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yuanzhike.top/Article/details/gtmzlbltzf.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.fzhhl.top/Article/details/gtnvxjlmjr.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gotoacloud.top/Article/details/gtvmvsbiiy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jyoumei.cn/Article/details/gtrazgsasd.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gogol.net.cn/Article/details/gtiryjblhc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.svipenyu.cn/Article/details/gtncfcvrzt.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangtech.top/Article/details/gtzyerorzp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.chenjidiqi.icu/Article/details/gtysxtyyux.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xuanzx.com/Article/details/gtystdoben.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinghuilouyu.cn/Article/details/gtwfruzpud.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gtkgmjbzyd.html

[I07] 忽略大小写与多行模式
来源：http://dali.zdqjudy.top/Article/details/gtdcckdmpr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yuxming.cn/Article/details/gtdqnzakvi.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.9152youxi.cn/Article/details/gtoxogccwq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.tanke756.top/Article/details/gthdghxdse.html

TS:   /error/gim
来源：http://dali.ydzc1.top/Article/details/gtviciuvwh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.tian-w.cn/Article/details/gtzeadxepd.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfnulupso.html

Ruby: s.scan(/error/i)
来源：http://dali.chenjidiqi.icu/Article/details/gtdcnrcpxx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.aibaodan.cn/Article/details/gtgiteroih.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cucudq.cn/Article/details/gtwuzvhbbs.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sweek.top/Article/details/gtegbnggeb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hfpthk.cn/Article/details/gttdafchrg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.bjfxy.top/Article/details/gttjszfhar.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ppjwa.cn/Article/details/gtvjaswhjt.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtosmhqsbv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hfpthk.cn/Article/details/gtagrzmjoq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.havefunace.top/Article/details/gttquotbbs.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yj202588.top/Article/details/gtpdvnbqkd.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtxlqrucey.html

J. 日期与时间
来源：http://dali.shzxlz.cn/Article/details/gtnxffxbwo.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtinnfjnoe.html

[J01] 获取当前时间
来源：http://dali.sweek.top/Article/details/gtjqhxoxpd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinghuilouyu.cn/Article/details/gtogllprsv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinqigfzy.top/Article/details/gtgtwvaodv.html

JS:   new Date();  Date.now()
来源：http://dali.9152youxi.cn/Article/details/gtdwakzlkh.html

TS:   new Date();  Date.now()
来源：http://dali.birdmap.top/Article/details/gtqsbfflkc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtycnoovqc.html

Go:   time.Now()
来源：http://dali.fzhhl.top/Article/details/gthqxhqbce.html

Ruby: Time.now
来源：http://dali.jiagoushi.top/Article/details/gtqjxesbta.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.pycfn.com/Article/details/gtuccgusze.html

[J02] 格式化输出
来源：http://dali.gogol.net.cn/Article/details/gtbzvgezki.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sysykeji.top/Article/details/gtoruoaocv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.nanxuanxn.top/Article/details/gttjclsvqf.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cqqwz.cn/Article/details/gtqelhsfac.html

TS:   d.toISOString()
来源：http://dali.jinqigufen.top/Article/details/gtwtbulgdw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sufxvd.cn/Article/details/gthuasknvo.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ehwqpu.com/Article/details/gtwgypajqq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hammf.cn/Article/details/gtsgarlhsw.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xuanzx.com/Article/details/gthguuzmoj.html

[J03] 字符串解析为日期
来源：http://dali.xinyue.icu/Article/details/gtizsonbgl.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.daria6918.cn/Article/details/gtersqdnhs.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.pycfn.com/Article/details/gtlkbsacwa.html

JS:   new Date("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gtqvzteyfb.html

TS:   new Date("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtrsfpjmnq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gtdlximbhy.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.316326.xyz/Article/details/gtidqfloyi.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gtlbkvymmz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.daria6918.cn/Article/details/gtezahxbxi.html

[J04] 时间戳与日期互转
来源：http://dali.ivvv.top/Article/details/gtmpwrjkjf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.guowangkeji.top/Article/details/gtawpukfvj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.nwbrower.top/Article/details/gtokwnjbcm.html


<!-- 参考信息 -->