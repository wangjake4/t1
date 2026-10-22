代发 wailian999

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2amsesrdf.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwfxcma.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sygplpdv.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfayvar.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvcmshq.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2gixcmdme.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwordfc.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pmzwqwho.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vjpfkolq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2myrvsheu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhlhlbp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvdxcnm.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ymmvosap.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmyxpsx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2clmrvifl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2elthseva.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkzbmgns.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2oumfplvp.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbcuqhw.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrmxsme.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjuzpbc.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xehrvmqo.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2umhynqtg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2gblfxtch.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2gvnyoari.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmwnpjg.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2faqennhx.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2gsnzksap.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wluoygrh.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2igdwaqxg.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwkgiwk.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwdnumb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjoduhsv.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bqyiziup.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jduabyxx.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2urzokpzm.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2kcacdmzw.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2czewfakr.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rppisjqx.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2npjttdvs.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kivbjfqf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2gjesqcyi.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2grzvibqf.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jmygmnqh.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmksgzt.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2agsjtkfa.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ginklsom.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbynzqoy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lduhwgpa.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2laujsgjl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2luumdqdo.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wgswwusc.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdlnowc.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2synpgvdv.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2pwbxvqqk.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2buwfvhpb.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqaaxmg.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2augtsykr.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pkshjkvj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cujwxgwk.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2knxnvbne.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lwiqaieg.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2dgpwrhjo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2brihuxfi.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aqteekgu.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xozrjgvk.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjatbri.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dqtankga.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2gguwrbri.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bsfdbcef.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2canopcjx.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgzkeeh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxbvfbh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjdesgr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtsqrtj.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhhzoqb.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcxnkuba.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtugrnpt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wxgutgya.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnrvqnsc.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2ojwukpxn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2xofdstkd.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2gyuahmol.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2zscxpgfr.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkbizfv.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2qwatzohp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxdfjbp.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2rgkrmdyh.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpadbdn.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2zvijhrvj.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2jifzeigi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2goboxepg.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsvamsym.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2omquxuvg.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2juhgdxqw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2imtvwbcy.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2iwnuwfjb.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qftqvdih.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rdikhpnx.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2lrdpddrz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzvamxy.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxyujpjm.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tchkwvgb.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvbixtu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgpxuvrs.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vfasfjqf.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxicwfiu.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cgvdmlwq.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfcpirvg.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ndsqcoij.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kawnsvvk.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vqionfop.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2nnacpyax.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hdixqnui.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmaeras.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlppkyv.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2dlscjkdb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2mofqqugv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2wprnnqnt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2xinnftvw.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2mnedeqia.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nyaaxfnl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2kysshgnm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2jihnshpv.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpmoydco.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2stqvozbg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxreerg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkrwttyx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2wstaelyu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfitinr.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggepfwid.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2saiwupjx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2wpavmncr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfuohfgk.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjqgner.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2kjgkbshv.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2iihlhzkp.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rubvweyh.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouctwiyc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2qodtwehd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2xxcyntlx.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2gqeyjgil.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2dmnrwyea.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2odkmysgq.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rwrvynrq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvxfgox.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2dysjaxxl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtffkfe.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfmghmr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2moqulbry.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aafgocjd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekohlxdx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2cezddzaq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ecieozgj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdhdkdf.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2cvniritc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2hykkijfx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mudratxm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eelfgagl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsqsvieo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2udzsifia.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2uiptfyqj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mybrmlcv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwxfzhl.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mpazdegb.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2dnfkzzap.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2pswjqusf.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkfqstr.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fzbnjtnl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgxctfk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2njnpibru.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqwrbud.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrkgbyw.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lacgoghj.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2mxpjitqd.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qidmqdko.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gulvtsvr.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zlyajmxs.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hrtjnuzs.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2boiksdje.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zmlmjamk.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xjfshpkl.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2aohuiskd.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2pdtstvbp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqeynbb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kzuenwbq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2quzubokm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cxngsxtb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwoyceqx.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2vggmmlyv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lctunaoh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2emookfvm.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2aoslfjvp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtyvnkm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2gvcfaujc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjnbvpw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvvegee.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxcxmoy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxyupob.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2uzolgsvl.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2oqbofxoe.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2sbrefugg.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vknanscw.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2raymarwf.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2spvfcgyz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2giteusmr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2iwgypdao.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdpnhuf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmjqkwt.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2znurrrbc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqugurs.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2irkynqog.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwbvcir.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjploqtf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2bcsczphw.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2atucuszr.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2qhvcrbma.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2jchsfali.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dwxcvwek.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2wbgvrdob.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2erxiobwj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpycgrmw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpaniziw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2afwxnhjj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qamaizkg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhankvt.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2rpvjixqz.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2uwbkiyek.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzrwvrw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2pzqkpthy.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2kinkudow.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2hpfauscq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbbjhxq.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxqidil.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzouuvck.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ebivnehw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2woahyotr.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rkhggzvn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ykwszikc.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ijtpaxbu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ochtfduk.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsetynea.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjlyueu.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgghozsz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2xywaugve.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2trztprqg.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmfsbmc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2nefkxdxp.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rofsdllo.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzjjcae.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2tomimumq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2bbcvfunr.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjcafsq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qgnopcsn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvkxuhpa.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2sybarkuf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uctifyct.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xpzpzdop.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2axhmvxev.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2dnfzayji.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmjfvko.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2dckxpotp.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjliush.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2bzibdicd.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2txbnnjmd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmlpuae.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tezmulbc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2idtktdxc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijtuhuhd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2iskpoqkx.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzitpko.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2mxabxfxl.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2vcomapuc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ynnscqgk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ndwbsvmx.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2whperjui.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdhjmju.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvupftwb.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnrbbzjf.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2wilgbmoc.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2ikgzgdaa.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezxgocyn.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ochoydyp.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2fjodjepz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2udlceuzw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2owglosbk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2iiufroeq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2koqzqisw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmnolnt.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2ximawowd.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2yekahdlb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2zofddjse.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2lfofldly.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2mbdacuwu.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2mckoeypy.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzuhiugk.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2bmebhzji.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbuboff.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdhfvbmn.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjilddob.html


<!-- 参考信息 -->