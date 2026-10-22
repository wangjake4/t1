代发 wailian999

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmltjjd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2mcujotac.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2khmviuyt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2bzyhufye.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2khuzvxce.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2cufxgyvm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hragtqar.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxdskfy.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2kljikjhn.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ykebmquu.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2otvhlxly.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ammqgczs.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vakspsnh.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2lijnzdsh.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxxnpvz.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gjpoircv.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xgynabmc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhoqmmr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gaphrusi.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqyzaul.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhfzoch.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibojbqkn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2brqxwngh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ysnngndr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjodjuz.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zwsoyunj.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkodacm.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxudnyf.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bstecjwa.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2lqnkejrh.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzxrocxt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2mbpgefxc.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2hrelimek.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2lirmlryr.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2bxxnxsmj.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2johmllrw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2odikfrld.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzudtcq.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2caiqbwym.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhzbewbl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2oasjwtuc.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uggbqrpz.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhtsqolu.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2jnivefiv.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgrbcbg.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqilxyc.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jojddcba.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ariesygb.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dghddoxy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2lgndjmft.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cqpvflck.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ugtfimqx.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2bnutxmhe.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2ziqirgme.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zouclfoc.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2emecmkzq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hoetxwgu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbtdybnk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2qxblomrj.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bdcurgww.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2vbtcdunb.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqwbxiv.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2wwdahydr.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdolejz.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ftotxtul.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fjjphnqs.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bynftceb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xwpyqnhd.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2rfzoibld.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qyotkefs.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vuamtggg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrqugrk.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbscghs.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gyyutmov.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mozqkune.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yjrbkpsi.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2cyuulked.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxnaarb.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2djzesoim.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2dybjfxxi.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2qefpotkz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bithpbcp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqtokbd.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqzzfhqa.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwcipzyj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbzykvp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gkoutqpw.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bogfdrrk.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2arjtvrwp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2kjquvffu.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvqheer.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnpskhd.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2kulupoua.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdmxlwm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqvygyh.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2adueqoxg.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxjwlsl.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2wnpazznp.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2igxjzqsp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2htdnaiqw.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2evsulnkx.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2apkxjbmb.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmuvqxq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzijoxkr.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2udwgpdzc.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uveiyyfh.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2irvtcdhg.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvooagd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbfczbba.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dflielkx.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2arpopila.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wctosjxi.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2erqctqyd.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ehyjegyi.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfsjzaxl.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lankaytl.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywfcbnyj.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2elupzsfe.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2uglyfoaw.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rpmnowrf.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tfwkuypy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2czkfdxbb.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2pooljtqq.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfppkhl.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2fsimzihv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2qovdikji.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhypjzt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2hsoaacdh.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2mauitasz.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmvvtxb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2jquesegp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvaevib.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzgchkw.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2unzqsbsf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2atvibdjs.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2evwvfosz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2rxwzdusq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2obwpbdgi.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvffjsei.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2eoscjuus.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2isyteqlo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2agplduid.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qzyayuwf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtaagge.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2facapmfo.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyfuxyos.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgrubmjy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2qafpxzis.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2bivtotdj.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2ptyaevaq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2mdhgnhnx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrslhbb.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zisaxkax.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxyzuwo.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2jldxldau.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgoftxid.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2safnmwvx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdhpimj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bplelcer.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdzcuacg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2svnifczl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dwbtayiq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvsluqqd.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2wpnymwzp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2jubuugjh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2reatkvtw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2etfpxpst.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pssuxzpe.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nycthjhp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ornhrain.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtkqxxq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2weukqgta.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fmulslwk.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqsftey.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwataos.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgxpihj.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2truaybxm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2cplvanij.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxxcrynp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2wdiuzmtv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ulawhumd.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2srvzqmsz.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2gybobsbh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cxamizcn.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2covydthm.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oorippfg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cvckynpk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2ummqokwb.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qqulhkjz.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhrfsuv.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkwoilk.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzxbhgj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mffxizwo.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2flelndlq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hdofamzp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ujrkprmt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjpptmf.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2xyekxgmf.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rabrlhsk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2jbsyawso.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2ryobcsjk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2pshjlmuz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2gktjwral.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2uojncsng.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2sipscvif.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrwlxkg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgwrcoy.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ucgxzwdu.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2cihxysmm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2obvrxohb.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrlzgmx.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhboqiy.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvrrgzjp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2wtsdgcgy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2rtjdomxe.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2uskjbxqg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zyuhazab.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2uqlzxdll.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwukfwb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2utlhxcsn.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2dhtmpddf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqduqogc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2zjnzncyi.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2zqcgzldw.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjvjlfi.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2tibgscxm.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zrjdtbxx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2icseifao.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfnqcgb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbbtpcth.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjoslafx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwcqyadw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2nnisqwai.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbdfcsan.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jsaybfmp.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2rstijuhz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgrzroo.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2nqrvruyq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2racpeeum.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwdmxwb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2gbrmgtyy.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2jgxpwwhq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrjwsfeg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pymknagn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dfueaevx.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2terznlan.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rnywzvxs.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uboahmhv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tusevlto.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2efchhbcw.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjfcnjv.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzlqbza.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrhvgop.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nelecypw.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsdwjadu.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2txmmgqvg.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jehpttot.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqedfmlf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxcdjeq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2torutumi.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtzstlb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmbithd.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jquaulma.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocduaacj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wpssyrmy.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2swaaktti.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdkiilqe.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2dujhvrmk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxlujgx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2klkcaukf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqduriye.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2iodwvrta.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2bfrmxvio.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2ctpbgeta.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzyxguo.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kexeykts.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzolkglh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtnmepl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2haydbtwm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ifzizshd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2eydbjwqd.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2edvzibqf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2iihnjkho.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwclsin.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hglfegus.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hshrgroz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlljtwwq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2koisddoh.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2fnisxmst.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwalqqkm.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2coepcdcj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2peyxtgoj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2yswttfjw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwagipa.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2blgmuhuy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2plcfzswi.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2crycdwxz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbqyjbl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2fupddvex.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2rzibtgzk.html


<!-- 参考信息 -->