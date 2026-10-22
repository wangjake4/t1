代发 wailian999

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bxpaeorb.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2tajcxaob.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtpgzir.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2osimmhrc.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2tygtjbpo.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rzkxyukx.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2petvfbwo.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qitylpod.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2klfqwjdv.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjxxsox.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2snrhxbfc.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lycebgap.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jgkzxzgd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2iqrqkapw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2loyksibd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjvvfhy.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zdwratiu.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uumzmxqd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2docezmlw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iloerowo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrfrdpy.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2cnoohsgc.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvjqpaa.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2friteuea.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqqbmwm.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2puumivpc.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucieijyw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2xhxlgmdy.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2gmvhnhui.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gxwcomxl.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdvatgv.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2yplsxntj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjyltre.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrvubtmw.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqrnioe.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuaoemxw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzuhqnn.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzstjhu.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebismqlb.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2blmcterk.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2mcowzdyp.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cakatjgl.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ziahbhap.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kifqybzk.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jtymcfby.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2uoaxiozh.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vjlefpmx.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mwqompau.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cvdgzppb.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrlodga.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gseqsqkf.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdmtloq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijoyards.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pacdfbyn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2seyavzuf.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xjvzonjq.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdxbxcm.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dmeevfej.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2uxfotimq.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tszriagh.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2uddwycxo.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwpfdco.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vbvnzqch.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2kehouyvc.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2aktnaoge.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2beaevbaf.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hhpaewul.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2axtrtpkl.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2detkobwi.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ejtiyrrl.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkwdqjg.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2auqdmthf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2yztowgwf.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oeckgzig.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hhuecdyi.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2vprwqxii.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2uwocwztj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2arqmdzaq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2izvhzhhy.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ledgsibo.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjzmbxm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxkdixd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qzoncpoj.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwkrotg.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2tihdgezr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ccpnjfwr.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2rcijhaqc.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdcjrqa.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ivukcxuq.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2nehbnqll.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2pvndjqrq.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jemlgtou.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2mckssvra.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2epbreyex.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2iymybywf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwlojop.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmaitnj.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkqkhqcz.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfmzvnhp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2evtvwmto.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2gfnffzdt.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2phnsqceu.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kqlzevdx.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvyestm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhdyaojs.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iibsrquf.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axmxfkjm.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2snjmmpfn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmflqvaa.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2flztgxiu.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tohyliqu.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qeupzgif.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqkncri.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ihutipjx.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qzggpxiv.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hkgdudoz.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2toudtnnj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2nuedtmpg.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtwpqclp.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2rdvrokkp.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtxyrxw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2mcncsljd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2cknkxeww.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2iipiddnb.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2veenrhmp.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jqmsbtxi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2egwzrtgv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2jvsqetba.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwlkiogj.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2unknavrv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2adjvimgh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qotmrmjr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2otylrtxn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzkuogte.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfoskrsh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxngngo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2lkvmlank.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyedkhbb.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2upnynisj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2dauzmkya.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcrnjhe.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2sulpepaq.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkzblzqn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2ujouqqtg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2aperfoia.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2aocfliit.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2rsppncer.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvpofxy.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxtykbi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rzhputjw.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqetkgz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmcsaiy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbkqkgp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdaygrkx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbtgsmxo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjompxeg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wvuntliy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzjqahs.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltpquxms.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2pbncutqa.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2uaniflyc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtxqztmd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbwivsfb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqivbwpj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdkpqqlx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2jklsvlkg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2icwxhjhh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvromdka.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2afivkttm.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxahcdr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gweyvccw.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jtpztlfn.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjkkagt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqkewko.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2befelnnb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2elmzxfee.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhevaex.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ntyyihnc.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2twtfptoc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2skvtynob.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kpldxjep.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uhzdpwhc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bvuvpwbh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2piwqveyx.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2prhueeuf.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjezjyl.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdmegtf.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2gimnpjro.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2esbnicxk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gemvzwgw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2taurslek.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jdauvioz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvntejuq.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2gwrsafka.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xphgsxfj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjibsbs.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdzfszg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2aytvodgu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqwvjog.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdioayd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2ublpbpmw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2emylkshv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jszmymss.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2jlovwowi.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2lgobmmoa.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2valurlwx.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmzaokti.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwmclez.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2betjgvng.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2lidoztst.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xqrtmcvt.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2epwijhmq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxdfwcq.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2xwplajbv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2tffcfluu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2rkwwejad.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2tlelwbzo.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2errvawzl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2ktnsimhu.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxxfxyx.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqlxqrm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2mayvrucf.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2cagnlmqj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2luhryznq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2taslfryu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2wueoqzxk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqzgtitn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcqyysxv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2sslnbmrx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnlvwhzy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kemmifkw.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2apdfwupz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmrhuux.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2qnzwbuvs.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgwswyx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2inyzvhtn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2zievioqg.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2xzisypmq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2farauziy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wnynsnmw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqwxuft.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cwpbsfrx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tmaxifyp.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqzymtn.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnicahhe.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjgskxj.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2paxlwqbl.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgszuaam.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2ryeuepbp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gliwoohj.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxurjnyc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2stviyvfb.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vtfpjsxm.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2apgzaekk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2pjksifyn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2rszuwvpy.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtxcblkm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdzwifv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2csklwzeu.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2iakkzido.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zusabvsv.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vplwztuh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzrwtvrt.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2qcrmesrx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ouidabad.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2qxatuxfl.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvwfewuh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2rzpmphzc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2nhpfimur.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2neyrqfma.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ktehcwlz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltzazzyl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrjhsyh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2xclkobao.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2nejsyiui.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxtijiv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqfolik.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ylfprmvk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2javjotrr.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2irovkjcv.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2biezcjkk.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgupzkwl.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipdzwzzq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnhpktuz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2hnoxcyld.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2epjpqdez.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmeabubc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2frkrhoha.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2hvdmmuzr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2vmaysewm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2zypbnenn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2yuisircq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2qycjelyt.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2hferazvy.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzidvuj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2gsderrhv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtdeotj.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2awcjgpry.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvnehkl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtsolvno.html


<!-- 参考信息 -->