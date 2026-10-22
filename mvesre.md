代发 wailian999

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fgvlrgvh.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2imyiwitn.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aywviwuh.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2suvetjnc.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgptuyf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2xzziujao.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qabnbfov.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xesyditw.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmiigfm.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpcnzfas.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxvgbqn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nroqmncq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2etkqynzx.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qwrgxbel.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2wliazbyv.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gwiregan.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tdjbrrhx.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2lniwfequ.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wadtxeiy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2stxgxtfy.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2onioipax.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2uiszefrt.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jpbwrrtp.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2sreokaap.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mapdgcld.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aedfcptr.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzmkvjjl.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxgokhv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfiwuamf.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnrvhcu.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2coiwwecm.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2djucbaub.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2xyerjcxr.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ksesycyo.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrjjspl.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iggvptsf.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mgnenogb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2jfpsegzg.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dqyghctr.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yxenfzbz.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqopcik.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2jydkjfvt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzghcdf.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhwjlgaj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfrbhhir.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxcsebi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2yttbfzcy.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yqpcdlpa.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmjknpz.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2bgasizjk.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2duwuldqb.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mukjdqyv.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2grefeqmi.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2keobfmal.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qinuiajd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2sjwchtuu.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2dhrlcxde.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2peiangdq.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2mxokrxsk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2drgnwxay.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mjoakmhd.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lfpbyiqe.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2swieszvs.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxcgjyd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkqdzus.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2htryxuym.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rwsdxyit.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2rlhxrhsd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2ivnnlfjk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cymcgaww.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2lefmioaz.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvabsfe.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxfaejku.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2aifmclhh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ouuurrzq.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2evddgujy.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2opcrleff.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2rdyngmff.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2pqwvrdmm.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2svcjeucn.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2iovhgody.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2apdydvbi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmeqhpy.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2pltpdsob.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2tnxppzml.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2yofajpvx.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2xtaajnbm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezedvqlz.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwpieqmc.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qknkdizf.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvsdxhfz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwcbeil.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2svgmmgpo.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sijjvbsh.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2woznagdu.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2broeqgeb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aketqrml.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxrcwtw.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lytqafaz.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnabqvpa.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2cauxeflb.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vbtwdgkp.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntaugiaa.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hkduwyig.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2nduzyqrv.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hwgewwmw.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wfhlvikt.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ozkftjzv.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2psfvqsto.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2fjtyrjnp.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzoulpbf.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2rqeqxzan.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2qktsdwmy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2fbqmoqhb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdqflgi.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2jcsezklj.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2nsuztnqy.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2unizvvts.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2tchnoawk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2waayugeu.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2geusbmdf.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gmchyrwf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqauvtn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2stexetog.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2bjcvtkzr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqcrvjga.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwhccmc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktagwdtg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2dtyrhoye.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwrhlln.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ndaltxah.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtqsmfh.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2thmxvjcg.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwmgnoj.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wplknypm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2qcisemjo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2xymrvhjy.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2jvjdsidt.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2pevvavmh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hmaaupdd.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gpffionh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxgtyez.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxkpvrz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmlyyrv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzawdxti.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2swjibhzk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzeeqiuv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajcincck.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tznifain.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmagmhn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2blwizdnr.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2mivfxsia.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2vajuvmiu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkqxajt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cywafzmu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzskpgup.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbzppgjw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfgtdrg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxqadub.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2afigjzhv.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqgstsn.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujobrcck.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ivisixpv.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2idaqgqmz.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2wdsifivg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2moepikvr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnfaukem.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2hynaxixt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ftiessfi.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dtnizkha.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2kengiqrv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mmzoiwtp.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2twfpbsvi.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2scjopgie.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fupnwjug.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2twrbkrmj.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ovipyddg.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ktvhwvaj.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bxveoayk.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxeypiu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vsuwfwrg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbwvagl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xkfglfzw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yeluoaul.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsklgjyl.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2zkfaehbb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ozbmomwu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2isxdgcij.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2esqgburx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2flnshvdq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2owktnqxb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2yweouqxr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2keidwczf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjrmsgq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqlxqwdm.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2wdqshxlb.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjrszjv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2glydbxdy.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2esrhsxxi.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lshpjmgw.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cznkchxr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2acbvcahu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jhntquef.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2fudgxgni.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxsrpfwm.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2vadnqwsu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmvsfec.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2krniupjn.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2gfeyxuwl.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2spcrznmd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxvndao.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdrtgon.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2wdjmmkvh.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2uilvhatl.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2acfhrtjw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmjczfl.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmyautcp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhtioyd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuykrrmy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yczygchy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wdkiklhd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfgdgrbl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ahunurjj.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2gubquccy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2bxbkpace.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2khehxvml.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2vpexaabd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2xawfvixi.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2mhutwizw.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2kkznosec.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2oehgiflj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xzhimlde.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sgeqjjck.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2drevhvfn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dsgdysma.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gslzxqlm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozoxyjak.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcfnzlbk.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxrrpft.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsaplxtu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2bduadgsg.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyygdddx.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2frqprrwf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tnobnokq.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2sqyghnba.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xokaonpr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2xfefxesk.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ulsnehjz.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwwpptx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mbknmnwz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jisamwei.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcvceead.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxjmzpj.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hahsafpq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbovcozu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqvpafz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2nqoxodzi.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2jdtqpfng.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fyufywcn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2lzyzcizw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2umjbjerb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2bopzxbyi.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kxglbqmt.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wczptmxl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwllunrr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxcbetch.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2wltzdzyi.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ivdvmrpb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkvjivl.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2nyomhidc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2awkynzrp.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2naglmgbr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mojzqejp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kujtynpy.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2fiywfioo.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2onasanta.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2qpufmwls.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ephzidxt.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2fiafilni.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2ebslmjdq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2tyrtgrbv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2nitaovor.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2cffkjdrh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2dgacnmnr.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2wsurrgex.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2oiwkkpmo.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2xlqjaynx.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjrbser.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2eaykuspa.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2wgrjtasr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2conivwqj.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpksupez.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2pltgfori.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2tugbvpeg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxswbonp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2unzlbjds.html

Ruby: s.scan(/error/i)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbwjlgq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gt2onyiibsl.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhxkluu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gt2bhtdecfk.html


<!-- 参考信息 -->