代发 wailian999

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mfiwjztk.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2owjyjzub.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jeofyahy.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2pjremmup.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ywppodlc.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mskawngn.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qxuegyvj.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2evuflyoe.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qfyqryyx.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnsmsjjc.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gdndbweb.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzxhosk.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2babxjupp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2ruuqeejn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hpbzhulb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2perjvzrz.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lxeugucr.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzcdtnuu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2kamkqjpv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pknsulqh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggqpewhb.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2opkhhpvg.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2komwzgwi.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ydlrggoe.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2uhbcqwuf.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pcotvors.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhwpdfps.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2qayuibmv.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2sbyfglxr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rocqurpr.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rzogeuov.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2amdcqfmx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbezrbv.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnkygscd.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmnrxlfn.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgomwrrt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnnvcfze.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpipcrj.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtexqdcg.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2yjpacgdg.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmlrrpc.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fbqyfvug.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2byywcmsh.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jlcesmjs.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tmexqzsa.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ovugksrv.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nerlweyq.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cohkgozy.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwugqsi.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2seqjujgv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2egrufmkt.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppbhfdng.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vegsfvfv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uukoyeyz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjbpzhk.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fhogwzhq.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2clicvvtd.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2czbacwpv.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvjxbmo.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2torcosnw.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ymcllydl.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2labyzyez.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mcfpbebi.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvsjwjr.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2zjevpcum.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jlopjbtp.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2owygcjeq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2svedhanj.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iigwezol.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dtodmxyd.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ageqshft.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xxeglcgy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2grqbbycr.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmxejbd.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dtuovcly.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwmkxqk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2kxcegwtv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbinxxrw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2rsohwnvs.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pphflnhd.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwiqbvu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2htriiyfr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fakmygwo.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qeknjalt.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2bnmjtwyc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2zrwfbcah.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2emzmrkir.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2etfkxdrs.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2cevcliff.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2zeodmdhq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2kdekqvdq.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2pxsmtxxm.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2mhdirrdh.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2xrzwulup.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwfvigc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqushag.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2odcckcdm.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwcxwmq.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axrohfnm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2slffwagw.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2cnnoovmi.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yajxejvt.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jtahhswr.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2gqfxncvs.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iznuwamx.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vglwdnty.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvlhwcnf.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxuxavdg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssoexpxr.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tfyegqtj.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzovbuuh.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwtdugm.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2frvlsvqg.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2exmrptdo.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ifobqrhe.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2abygzfdz.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ylyfsudl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ypeyfcjr.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2zazbsfwh.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2dryewxnv.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbmppti.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2dbynaqkl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvltjej.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2drsvakbr.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2cpyamiso.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dvckufpt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2buudkuxc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2hqfnczrg.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2jodylcmw.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dddkgkkn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gjckwezc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kczkjnpz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2iuhloffx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2raljbgpk.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2hiacycmr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxidaaus.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2tvetoqsi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2citqatzm.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2eatmyhds.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ncnzffvj.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2vecnoqfk.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvczmhop.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlfrkqiv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2fxpillld.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2adqpvgzz.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxhfmpd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2hmitiyjz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2egdifdaz.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmobytd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2usektocs.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2flirhlun.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztksghkl.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2emomqdnc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eiknnyqx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2duufhkos.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzjihzpq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2oymktwlb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2agpriiwa.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fadeyvns.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2jpsfkzsl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqdygbv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2enviqxil.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ceaweqrw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kahaiqex.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2enskdxtk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2gollzjil.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2svpuqmof.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxwhkti.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fgxjhavv.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2fklrvxim.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lbzsgohj.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ftoyyiif.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2tdudlgkr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2kntvyvag.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjwqtiu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2szjosqgk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzeonso.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lfycjwck.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2rqgfylcz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbendco.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ecizgnnc.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hddpeyar.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2slfqnfqw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzqtqbhc.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2davvigca.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mhkzwvhd.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmxpjwl.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2vctrmbgc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmwkzcq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zblqrgog.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lrepzhix.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zyaegdle.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmqqgju.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfuwckm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ansshbpi.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2glhrshqs.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2qyxucvwj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2yonayqua.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2gvnviiic.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ormbotss.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfliwil.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlpdovpo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tthezazm.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqryljb.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2krkfutwg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvzrtqz.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjuwuulu.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2shjqfnfq.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqqlecx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2fsbujylt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2hieskyif.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2offauhnj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2epjdkdup.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2menajmcd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2qsojbtgy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxprtnv.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2dnffgxcd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnnextnw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2yytniojz.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2cwcbqror.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2eepsfazg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgdnsch.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcmwejj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2jdifeoqw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2btorxrho.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2qeegsbfm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofpluvix.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2weyrpppl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2sixjmfsc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxuxxue.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ahuotuge.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2tnldiqdx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2iopspuxu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2lwloqjrr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2rvpqvvjl.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2qigzffna.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2ludhglrx.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzomtfw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2swfhicvp.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kjnybcyy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2faxvxlzs.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2reejlmpr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjinlvn.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bpraugrg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnglafxg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2oclepzhd.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2skdvqmlr.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqqabkou.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2rjfyeddn.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vallffth.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2haxhxcjl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hqdskzqs.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kbnncssa.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjfrzees.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxhrfgw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgvnmyn.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjkzgcew.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2piyulziw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybkmoeon.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbnvfhfb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cngoexum.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjwsamb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2svutbwgp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2twnntpld.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqicsle.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2boaerpzx.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2khzqxqlq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2wjsscdyh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2vbsnqpxx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2okevnklt.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nrtirnfu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwgssoc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cylunlnc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2jimjdwcy.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2xusxbmaz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ipnkqgzf.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2vyxfotsj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2mfehxibu.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqicpkpt.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvaptqa.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2illxawhx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwywveac.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfivnwfy.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcsqnoez.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2aksiubri.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcoozacy.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtsswyi.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2cxuqqfvd.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2xvygkckb.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2flpsextt.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2jembxoyd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhpalvj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2tjymnoaq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2oevnaigy.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2bammzscw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2awthfiuw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2ozpwghgm.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2tccusrlz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxiyeby.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdcwmonv.html


<!-- 参考信息 -->