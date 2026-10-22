代发 wailian999

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfunmwu.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ajvlvtkj.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2izfluzhr.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wghqckcj.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jpyfakrh.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2niijpqqz.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtlewgr.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jnflrqos.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2olcrlqer.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdfozht.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjvakka.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcwqrvgb.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eueqojny.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2snrwstzf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2efvedxqd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpneeai.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjjfzcj.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjdmffq.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2kikvcahw.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jvsxkfdu.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ginbtbbr.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2uttrzqaq.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmftuxmz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2tibpufoh.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjtldrc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2oojqexlx.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2kxmqwbvu.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2apvhciyu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfynnyyn.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gscnljoa.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzcahfb.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xabcgwko.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgyzcpdd.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vulziuzw.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlqvjadb.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2wzisjxml.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqsdize.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cewtgqlt.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aekbyuwx.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cjytoiad.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gszmjass.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2hmllexek.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oehuijvm.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vmcmsqvq.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jrumgkkj.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2zlixrdoq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2beceggas.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkukaocm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rknuqxgq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdprcomx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtllmcq.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmbzfke.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2jqioeocf.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ivajnycp.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2gouejnjm.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ufnbasmn.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xzutvilr.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wedwqcld.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2abvkdvjb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gpsvvmod.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2omzudrfv.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mnlnwhiw.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2trvfblgl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2krvolwmv.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2exobgayb.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2saofqobn.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2snbthdpt.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2edgbjskx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2jscdphcb.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2scjsxabn.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqqqjae.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2ygckmwpw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2finmitra.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2scjijmow.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2gbqfemkg.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xscmfmmv.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytztpkko.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffksjnvf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ekhddbzr.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbiiodze.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2tlecvean.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2tzknbnxm.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwsmbxk.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2guzptyto.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2poribkby.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdfemvn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2xtsuwwfa.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qipszbim.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2uggbazkx.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2wudktmam.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ddaohxts.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvuwvyxc.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgfurjun.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmwaelv.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqgxowwa.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdmuadi.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxbdwpc.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmskatvx.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rseeolzc.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2yoakabkg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytsklkid.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmyznhw.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqbhmsb.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2diphgblo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffgniojk.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jlnexytn.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xclobihj.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uslgcohj.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyutghaz.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ysszainz.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ilyzshit.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2igebrhrk.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2foyrllnm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vewtdpvq.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqdsayvv.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2hmksaffe.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2dtujapnc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2dqtvhlvx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2eeearlql.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtqgmxi.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2plfashga.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtwamkj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2aurveaym.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2xoiwkgxc.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzblpplc.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2oydnfcio.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2plgztafk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcrtgovx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2djtbcmhb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hirfuypf.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2hiaqqreg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfgiiddx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2izrienkz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2aescpdpb.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ldwcrqyf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2hnpregxm.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqwtzwg.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2popzvria.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdaieju.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvfhwze.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2gvajtaik.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2ftoylpkx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2vezvrmoy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lczibniy.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2anezcfoc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzcmbzc.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2etksbpju.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2voznuydt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zozmhiaq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kravuomz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgnspfmj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvprrso.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rxekaywc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yvqevhvm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jexkutlu.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmkxjwo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2ptgzzqji.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdroezc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jednxffh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2syhaecqo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2atnivdjn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2lxshypph.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qgyvnwex.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2edqjmnlz.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lrwnmysx.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2fwgzmfyk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qiixglnk.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2oidnzvnu.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2iictppog.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2buulzwgd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhdlkqw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2inlhhwbc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2tkoczyba.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ssilzncu.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgohrsw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2imbwscvp.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hnatueyb.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ivphpomw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ktlmcfhm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2syfhhnuo.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rtlajilt.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vdhwpbky.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qwplzaxe.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2pwyvlyaf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2enpkjyek.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2senlwqxp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2freldxcn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sqprscgi.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2qoftctld.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkqvbip.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hqdindry.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2isjrfosb.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2shoedgkw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnpnjyoy.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqtohqv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2zvkdlxje.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgknllsl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2raozadkm.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdqloie.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2vamjxxom.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2kmditzvu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2elbdsppr.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2grybhurl.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhimmis.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhfsout.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2fafdcszi.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2gmgakhev.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2eotoxyup.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2emjrjhgf.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2gtegusip.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2xmptjmle.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2ggpkteqg.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2yfpltplh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2kttmgkrn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2fnckfzuq.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2hycahouz.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2viaqqzft.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2dwupzuaw.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ktsvorxk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2bvonhszn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfobcchu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2faeeiwfg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxmbrtt.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwbnszmd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ojrlkfvp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2uejmnoma.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2uxiaprqh.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2adqohhvv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2zkyqbcwm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2totsvcqc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2xpkagcjo.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2idetodas.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2uaixxpcu.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvbcjgq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpbohxkd.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqhhojy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ilrrsyke.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkdblgz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fsagyxng.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2erpyiqty.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfseympr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qsinkvem.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjcemeki.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsnojaba.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2oalkyngw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sogxdokf.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2nalchccw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2wgiayaxc.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pikweelq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tllakkcw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2eubzkkue.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2awhdnbkx.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfdblhrc.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2czfunyuf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjzqbuv.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2muuihcxg.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gumqvexb.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2nozdmzkw.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2avqzamdo.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2awfmkxcv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2lvffpidy.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2qxggxtll.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvqxnyhe.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2coqknpvz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2cwsypvqx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2apvhtcax.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzexnqj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kooraxsa.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxkiepjv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2teqzweey.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbaadsa.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ugimsvie.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2qpidrouu.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2nwnfflxo.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ovughxnq.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2fysaqngy.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfarckuy.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxehxqf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2nchvpnkr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2zchsltsw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2ezrhyazn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2itahidoc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxymhgsb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2qqzkrzew.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2irgzpsif.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2djfthaim.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2vslxmfzw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2gxziozva.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2htbeudyn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqvphas.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2xlbnilbi.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2ojuqogam.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2roxyyjrd.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2bdkopqgw.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxjhwwb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugbsjyzf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2rajncjhf.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2qemzybtx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdpamoky.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2idbtdotm.html


<!-- 参考信息 -->