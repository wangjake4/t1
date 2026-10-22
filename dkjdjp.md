代发 wailian999

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2xyaobuvr.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oobjyeuv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2goxujptu.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2aciwowdx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2kddwzqki.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwfmuso.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqekjme.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2egpbojuw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2eijeelkl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqayqiy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2afxrnhvd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2iigdbzvw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dhcxjjlq.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2dgukdtfh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqwdoku.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2vrcptivj.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2tngbloca.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xhmrzpud.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qgcsjjva.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzotakzo.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqpralk.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhdqhmmg.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lscbqsun.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxgmlxh.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wgginama.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2llutakzq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qrlveiwm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqxewrjj.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2emxahpfl.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnowdbht.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2llwhdlnb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ckfbpgth.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnuxmfmw.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wsukqasx.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2hiameztg.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkjrcbw.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fodcwfwv.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2cqthqreg.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhnuwpml.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2gtfsiglt.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2vimbusas.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qsujhuqg.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ufkduyfc.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2cnnnyfam.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxgarnn.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oytigghj.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bowzttzj.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajqizvki.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qaplhmgl.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nguqpzgz.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2iovkqopm.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2pjaksfnr.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2eifhypoo.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2odbwkotb.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ysyiuelf.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qxyzfoot.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkchttl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2kclastvr.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uteyqcis.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ajzxnnnz.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ytginrdt.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2nxqmcxeg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpzrvgko.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lasqlkua.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2owacmxic.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfsjkqai.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2gypelrao.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tuoppczo.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2qogalahw.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2spzbpnwa.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2umvkzwjs.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2trwewiqj.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2efwjrkza.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pddlieag.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbafvve.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtaefia.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2hfladaav.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2guqhcykx.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbrpgbm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2pklsguyy.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2emsqrvjg.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yaajixnj.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tcsdamrg.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2csyomwel.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbssjop.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ncgtyfth.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rprcxsrj.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2wxsydaxz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2nzmashlb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2brkqrkie.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2wnavqrhu.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nepmezwu.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2psbpllax.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukirywus.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nyoysduj.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihpxqydd.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2hvvnkxoi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjsdhqk.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2zyzclxbx.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2wajmscfh.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2snukhbqa.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2drbytini.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2jyfyyqqw.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwabtut.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmyvpxw.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2qooyjvxw.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2pmzozvtm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjrulsv.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2seedoezn.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwylazyi.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkytysfp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2helphavu.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2gwfacfde.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfrzhhbe.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2aqepqyqg.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2hljodlpf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpeuadjo.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyjvmdrt.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtacixhh.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fihuhhax.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuoyizle.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rhgbywnl.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvywcmew.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hjlxrfll.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2auebhzhi.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2dgnlxizy.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rxsycbnd.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hrbmufmy.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qytxdtrq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2nnaikjqm.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2hckmstpo.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtagjpw.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2wrssepwb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2qcfaoznu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2nuolqfhb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2ocyzxltv.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2nurxpwpx.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vhkonqdq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhcnpva.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2vwdmwope.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvegsiln.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2iazvolcl.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pkolwxfw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oplzmlim.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2tqrghlej.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2trlhfady.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtunzmjx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfcolzg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2lqkdoxzg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrfpbrjo.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gjcgsmae.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2rnnixkxa.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2autbnwez.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzennjfh.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzuafohl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2vdsenodl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2kkklzzea.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjghnxy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2hzumftkv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dianaddz.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2crdumiqq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2szhfabeu.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2ivyrdgij.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2dffnivlj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xueimzjq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqvswrl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibcszcmu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvwrfie.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2glkelsct.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mfzkiovr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjzbkgp.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2dihrpbcs.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2tgsiwcor.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2livcbfwt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvoecexr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjroorc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbswjwx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2vbddvpeo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2utdijbqv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxdboba.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gtpwwxpo.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmuaslic.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2negfjvqs.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2frngincb.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2dcpsqgzl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2sfkhvagi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkzofreh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2znvmlbyh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2byxdskfe.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dnimeniz.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2dlpwhrgh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pvcnrlnx.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eyoiudqs.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ipbyccgw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lunrcipu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwlaxcd.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wagszcmd.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ewpxuuzu.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2daqhtmiv.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2sqecuzag.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ycddvxuc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pdkxwzbr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fmtggjzi.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oypgwmtw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2drhybiws.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2clequbil.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vvhjbfwf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2fggvolsd.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2zshljlst.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdzvtpe.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2jvcussvx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2idnqmsdd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgqklntr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwijolnp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwughbz.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2bxibdocs.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfasjmi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbsvdlk.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajughtpg.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvdsvlif.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2igwwrjzu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2lwkrliia.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2tdknsgyi.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2fxythdhr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2znpdhbbw.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2xnycnyyu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2dcowjshc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2pyndmeuz.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2oyywvccw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2aatanqcv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2ftykxwnk.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2zsscoknw.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2rsszmdwd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2qaurdiqk.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qyymfukg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2jjusivdu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdjhnprc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhaqbqzk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2erlpjrfd.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vevvctir.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2prtscuwf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvkuhmo.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zwvroghg.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2yznxkodi.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbstkmg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbahoxj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2xvsjovbt.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2vtdeazqy.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2vchsoksy.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2qmrngynn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwbtesa.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvuxpzx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rkawgkne.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hkzseaww.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvkkqxy.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zmwdozhh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhsfqmrq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqqlsqv.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2izcolfyl.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2eufljcxz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2qobslrpu.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2csylwzqf.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdaijej.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hmadpkkb.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yskqupyr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxlgvsp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2oygnjqnh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2eotfzuon.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2isevashg.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vlepbuhm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvgfayb.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbcqmfyg.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2favajxir.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ueumkxhs.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2phpbfmgt.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2wxramtww.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2gygqsjvn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2eejtrsrp.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnmzkamf.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2qabdlbtb.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdkgjaf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2voeittos.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2frkglsvk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2foqqfrtl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrmwxix.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2gagfsltj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2mrknathh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2omvehudi.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2bovjacam.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttullhsl.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrarvlhn.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2fhftekbu.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgoxflbk.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mixbcphw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2qejbyrzq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2picdkmpr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2pzpwfoap.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyucwscz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwoxvmwo.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2btroocts.html


<!-- 参考信息 -->