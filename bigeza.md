代发 wailian999

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqlettt.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2xiygmvkz.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qbgsrpti.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rfvofyur.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cytgkfdq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmfrduq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qudwllqp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmujaqcm.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jutcmwce.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mspbhssz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkupmuvm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wtuhehut.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfcyeqis.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2szgycvpu.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2xtcnngas.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vfuiqnlb.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kprpdkzo.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhfauym.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsboffeb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2dwatrgsr.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2zbmrkmld.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xtihwipe.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qkyjxtag.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2albchcya.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2imvnupuj.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eztkutud.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzfepmje.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtmfcbo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqzlxjr.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rslpsqvh.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcctcmxd.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvcwcuz.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2pemrqdvb.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sacoacjv.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tywnyzwd.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzqrgfx.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bityvrir.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2xmkqqokv.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fxglssgx.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbafpdx.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rtlbpile.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2jumbcvny.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2spszxsfx.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2amqeulfx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmckdum.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eavtfsam.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkbdilk.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2crkfvicw.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2jkszyquv.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2altxbuka.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2tbuqtsub.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wtyiqvwh.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pvlhxwgw.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qffouxvl.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pfigvbjo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pzrptxka.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2uyprvjdc.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fntswxkl.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2aiesowds.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2kndpfrbo.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tpbbfaib.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2opnckopk.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzpcjkc.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kszdepwd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2chpagpqk.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qjvjmdpu.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wwkidjtv.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2fgmjnvkq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2elfimyih.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkuwlxr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2yqkldgdq.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2blldpavd.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkbelxw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yamvxzay.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zkdvnlqy.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnsrwruu.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2juhysjpp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2htdjehjs.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2krwujmyg.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2olcdcpvj.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2wyccjomt.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2zwvmlcgo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2ngghztlt.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xupnnwvl.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2tewkypru.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrlcanz.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ipercflz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyarqaro.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ealdithh.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgowjxbo.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzvhjqkh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qczmtrve.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzpnykj.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkubcqxh.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2huvgwphn.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ygslbgvp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyyipmbv.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldavruyw.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dszwurol.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjpwadpn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2znefldfb.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ilspdoue.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecidttvw.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ettvlvgp.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdylbcmu.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxmjemw.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwmjzel.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2uofhtvvg.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lyyexuhv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2fteqzblq.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2khyndrsy.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxlxwie.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwontgo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2gniaxkdn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2xqqcmkae.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2yalabpgg.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2wtpotxnv.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aqtvvkuc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzljqzx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2hlalnekr.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdhttnqm.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2svlszyhb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wujiftqz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpsucuzk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2mctgettl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2akwpczso.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2iogouled.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdcwtwlb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2jpzvnxnr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjistkc.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ymtuczip.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2frbtjlyq.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujukksaj.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2frosgqtw.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lognfzra.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2mxktlrex.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2yakaktsx.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2vulkaphi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2lnhylhjh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhbtnst.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vdqhosjy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrwjjad.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2yycsbfpu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwseqfwd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmsqeqb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrghbak.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsvwrjwm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uavjaxfn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vogosjjo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hxqjuchm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjsqoenp.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2gedjvxce.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2sjpgpnty.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrgziro.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmiqgtx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryytfrul.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipiuvqch.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2uybwfzev.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mqemfggr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfltzlay.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2janivlpe.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2exnebcsy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2djnnlwql.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2tskleuet.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qmzdbeyo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2nwipchox.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkgbueia.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2yfrerqax.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2kpikilml.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dflsdzsv.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2jquohvvs.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xgmkonad.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2grtcdwcr.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtcbgrq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2msuelris.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrfwqcmy.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2smjnbyep.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkslcuq.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lqfbijkf.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2ujiunuyc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cozvukur.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2stelenvd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uitvdrnl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2unsjyujp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2somyghki.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2zlaqddwg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cuufbswh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2fwizomft.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2ygpjdodp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjlwygo.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2mlexgtoc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2hwkbilad.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttvqvdox.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2petyqyit.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgmxlmty.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2wasohzel.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qqekbjgf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2chpeiyxb.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tncmlfoq.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2edwfhaar.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdfbuxy.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2blaihbsc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2fliujupu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2zkrqhmcy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbcvnmm.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2sxnpzkai.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2ttkstufh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2acsmxajm.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2miwkvdzt.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2govoqjks.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2jssjgzts.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2iqkpqhul.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2uumjyscs.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2ryovwekg.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2nzpbwrsa.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjzdxjz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkvrrkzl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqazeza.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2slpvqnfg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpkwpgwd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dfqnfvtb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2oaelsfmm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ropkoedw.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbkapyk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2xvlymjpy.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwofjei.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2adkfeqyg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkvxkns.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2mystfpfo.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbcxawr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlwcdbkj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wdkythix.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ldoakjuh.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2knsyzrwy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ecryoykr.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fytftzee.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdhecqua.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdtylxz.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qshzgjvm.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sziswnhf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2qnybuedg.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2alwfhrur.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2odmtulfs.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2svgavhib.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xbkqztzg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmktfivu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2glodqynx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2viflausc.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzqwgwm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnguwqj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2swrrlqbk.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmevrpo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2haluexxy.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2cjmtztnu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rztcltmn.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2mhqrlkyq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2xpveqhjc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2yvzdwqjb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbailxw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2unxbpelz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbcmnje.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2efofpwwg.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2akqhphzx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2olwwrmlw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zshgprpe.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgksqgeb.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2nbhfhfoc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2gsghixhz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqhsmfcg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzajorwj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2qvlekfak.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2qrijmjzz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2abyxwccg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2agcbryjp.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdbdnbcj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsejwukg.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2umycwwzv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhivqlvl.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwpjtoig.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2zsoxmdct.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2akhslfqw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtdvvpg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2bsclawnv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2iahxsxkh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2elunasug.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2pvainbqn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqegqvk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdvdaru.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2jblobcyi.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2hzorrsgj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxckuqzm.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmtzxhp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxcfmfd.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwqgfky.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrhzspxk.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwijulf.html

Ruby: s.scan(/error/i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvhrpzox.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjsllkyf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2omfyjsjr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gt2ebspldbz.html


<!-- 参考信息 -->