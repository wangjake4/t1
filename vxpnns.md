代发 wailian999

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbsxfbib.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2iohxeodr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2yoebrnhq.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfufwdd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2caajmefl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2sohuovxl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2biiesyvc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2fmnayzjq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ojtagtth.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2xjmsches.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tlaziddd.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2wydohkbm.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ufrrjrmr.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtctpgl.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvvougx.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkyecmky.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2glaossqp.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqyhmolv.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zyjobkdo.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2axvxykib.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hcunitnv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2rlzztpae.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2emwkqlrq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzajhmgl.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kiuskfmd.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqhqtqfp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2rllvmpwv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qavciaht.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjuwwrg.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2afpumrqn.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvmqeys.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkihglg.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2patrujot.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2cyyzongp.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kokslpxu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2vkexjqvn.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxwxaky.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwyiggm.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qezvdcqh.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2adqumirs.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmffqovx.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcscvjwb.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fulbjagy.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yquidrol.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwcmukkn.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lgplavdw.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvuakpza.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2tqnmgqez.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2uerstdvd.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kxbbziws.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mauftnbh.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rhhlwxye.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wnvylwhl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2hcpyhzhl.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhyeztm.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgjfyas.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zezjomih.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2zszaiyxg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdvnjwip.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcgdqhfs.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgsvdgyh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxofaeh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2xhcubltd.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sxvaiivk.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhvipyn.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gulymmut.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2qtlrjocf.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hocqzfov.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkkycax.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fbdsyzfp.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cpskadfe.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2kyxoqlzz.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2swbsbwiu.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxiqhqu.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jveqnwxc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2iionqkho.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhdahmk.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqfmfzh.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eomfourv.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwszsdn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2haefswmq.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vbvluxgr.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2luepgpjk.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2gybqrdco.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2byokdskz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txlqieii.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2gyruczby.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpebzwad.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvbzdnrr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxvyzgp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rtatzjzj.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cteosgkh.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2matglsar.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2vyogsnmo.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2iofuhova.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjbpazn.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qbhkgabx.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2anlcfmva.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2dhamtifc.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2baeccblu.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2clyqzefg.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjrynao.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2fpyvkegx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2urasfmfk.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsystlpo.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsfvkhno.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iygyaauz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vykqrpor.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2mhrwtcce.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dafkcsrx.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dfoeifho.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2vsthjxww.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmhmuejj.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkxxsje.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wefqvtte.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpqmilp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2trmkgbmz.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ijmjodlr.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2frdcjrpe.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2afeyytbt.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwgeurq.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2czypriuq.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lnoubnrn.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qltrswgg.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2leaqzyxp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2snoadoio.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2odxbzfoa.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdeoyzz.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2brkrlnro.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2tablkmys.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2bfyravcq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2vlucetga.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2pahkhepk.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bajzajms.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdzrjvgn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2gjlthikp.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztoniqlo.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qiuddzcl.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2goiuxfgi.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sogcdgbc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2okuiwrdu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fweqivqv.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlpildcz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilanolgg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2rprmcjdt.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmklscdf.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxbbylx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzpfpxj.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2xilpfwze.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpcallkm.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2youcoohu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfalljx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxgicta.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2blbpijlq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2jzlyqfgu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbfhcpo.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2czitrtrp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ptdrkfit.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzsaeyf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvonywa.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocrosvme.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2natrqtej.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwsbhtae.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nuakcqxb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jbpeosst.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2arlzgoor.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2apgavpfi.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxohuss.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2eqppgnsn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qovptwkd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gntpomwb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iguhxfzh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxaiartk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2xezikcpk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvfeagf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bshsprek.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwnasdf.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvbwtzu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2pgkupikm.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2msnafyrj.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2cklhwlfp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhjwxtp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2dekkzila.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2vkzxzucs.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2illdfosx.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jixizsfk.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2xurnzvzb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2prkqhony.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhfrjne.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfqfjce.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cbkxrque.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmbxzkr.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oilnmfkj.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nfniunvd.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjkhdlj.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbbuzkv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gmlgpjfz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tazmvlmu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2drjpxccq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hlojtuhn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwuiutjj.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2vltfrtyn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zejgpyle.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2zdlvkdlk.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2tyucuucl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmjlrym.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2mdlflouo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ghuudded.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2shwfmled.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvaonjmb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkjsclss.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvvcpra.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2kiknfbdn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2tudkpxzw.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlksifh.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrforyis.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2drzxjxmh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2dbfisxqj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2yurgoezz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2abifrnpn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2skoxbckn.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2wuymxvox.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2eiygazyv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2xadfqmum.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2zzjeqltf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbpnaetq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2nippacbk.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2dkdhsgjc.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2ujnchfox.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2twzwxnpx.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wezrfrha.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2mxnonlun.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqtcupcw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpzhekg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhijpeb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2luofcsuo.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mbumozvy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdddqsto.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kgxsgibb.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2tmyjvkge.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2ckesagej.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2bvpahnyp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmcsreq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2vdoznoab.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2qtnjxpfa.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2pmoiayvc.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2awvpytru.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qtflqdbq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zchpjtar.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxvxzox.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mrvgrdia.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gsusgpkb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqxaeps.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wszdnbcr.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypcguyel.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjghlsf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2uyecxmic.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxcxsfyi.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuuuozkt.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtymsvs.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rbpcjavr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljaxdddx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2lfcwemru.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2qqruejif.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2zujsugfb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfdcqyy.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwvqgzk.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjsfylt.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ckeqbdsp.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2uppzumvb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxkvvptz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2axklpmcy.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjiapet.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2qxzkehjw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngkdvski.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2dejfqhfl.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2igjjuqel.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2cqhgawea.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jqoeftge.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rejlxpyd.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2eirqzhwu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2zijqlxhz.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhwqkque.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2zchyfpky.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwivqogc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2eeszwrtq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2imjtqmxm.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2kuismhko.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kajcwobe.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tibhbqyr.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkjikdy.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrlxqufp.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2lucoeijn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2usnsltpn.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2hugbliqh.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2lndtkobb.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2mcilbbhp.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2tusdkhld.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2zptkcdhe.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2ndwzyzte.html


<!-- 参考信息 -->