代发 wailian999

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2boicoavv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rfrtnkld.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbxfnox.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvichte.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqhrrsn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvzsqku.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmijdcco.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tknsiqhl.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ynwilvcm.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvparqq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2disdktdo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ckcxdakh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pyyhceao.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhhpuwer.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgqthci.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfcxwbnv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xaymtlbe.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bokjqnmn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ofwgjxch.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2quqjnvjd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2ladmstvs.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpbleuj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2rirorgow.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2eileuirc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbrjaant.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxeafbo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmmpzhd.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbzvxmp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2sxswjtnz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2doolkbuc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2whkgvwqq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2hkuepofx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oguydxad.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2zbjrcfgg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxdjuuc.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2ojoormoc.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhaewsl.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vxkbgbkp.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uxovezli.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhhhrkl.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yhvrbsqu.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2blkwsapt.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fbdtnsub.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2voauawqj.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxfmrmy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2mgfdtvhb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2caqszvss.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyujknrl.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtviknd.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bireylet.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zksuwfep.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hhrdbdte.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgfkact.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2cnnlidvl.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2hfahawkn.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqxobvo.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ffehnhuu.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jdftuypz.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2eirzmtrz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2csnveumd.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2kkbhsqnv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xszzgbgt.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2irhrjydu.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvxhniu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzpaajcu.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nklepvvm.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2spuwnlyb.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eetymrge.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmulwkrw.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbsatyq.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjjhthc.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdwojqq.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2yswxpyvd.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2swzpdcpb.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gjyrtxvh.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzvherd.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfymwlp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2olwbvunm.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbjyonk.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tnvuipoc.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmduvqx.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbwdpcr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eolrvkhz.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bctmfbsr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2saphllpi.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibernbmx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2obsqkklz.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxkeydb.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2ixkotxfv.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvphdhv.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2aaebswae.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2quixwegm.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pckxgyde.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2sunlmikq.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mvvvywhg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2brmuodas.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2vzefcfdv.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zrokjkyr.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtbefbc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2cpsrdlkk.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2elylnlig.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aalbyzlp.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2phaomsvw.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nifjoygr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2btoardwb.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqqmnvh.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2szbrllrn.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2eciozzol.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2mubknogn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxeqfbgb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2ntvicfkj.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjtvklm.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzgbmeer.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2axzpdiua.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tcakvrss.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2upvngizt.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2nzlqleuu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2glfcithm.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdojkzk.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2cjjztznt.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2wqoaaenh.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdivjrk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqsnkuv.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2nwbwyqay.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2pqkngmxr.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2gcgbvejv.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2clngwoek.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2flshxnoq.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2shktdbeh.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2inaalnrc.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pikpdnnz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsqpdjbl.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2agsuzpho.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqvvrhn.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2grepoiyk.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgmgeyn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqpzoen.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2auetoepm.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tflnwhsr.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gciihmrc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zimrtmzc.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gecdtrqo.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhlxmpzf.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jvejhtsn.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpqpyjy.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2blxdgsdy.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2trfwgljd.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2doktuhta.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jxyicqti.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2yuayesim.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ailslagt.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2vowaauyl.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2qszxzlnr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2iwcyybud.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2tcxqsrfu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2arvtvart.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2rbgbezak.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cugjlxyq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2bthfekxv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2bswnwppj.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxucfwy.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jouvufca.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lprscbxp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2snuqivik.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2qjnqfsmw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvytiqe.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkrzryrz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2uophonzm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2dvniwdjq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhlkotxo.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zzemifbu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2nqaczblp.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekoueccs.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2acilokuj.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2cznaagrv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2zdfhwtyt.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbwdehe.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2moybnuzs.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2annmxnng.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ufrtyeie.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjbrkpo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzolwny.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2mergoxee.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2klopnnoa.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkjgnry.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbcxkql.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjimfpwl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilriemrv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ibvhbefv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2emcfcbec.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fegohbma.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ztenzuli.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfdyhsy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2knbmjhlp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdrrsmxz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztgnynrr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvzlvvhl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2bawiewmz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fbupwdzz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2voqxihei.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2usxrjzmc.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2nkmlfleq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2meqjinij.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxsaiws.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2njfrsopk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lsgyoubl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjfwrwuy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2gfubgvcg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gopufeyj.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bxwpkxpe.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqpmfap.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tkaeyfpq.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ugplxjkw.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pwbhmynh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2owkbaycq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2piwztdjl.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vstvwlmz.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pbcjemcd.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wkufsymi.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2uwupaokp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ahllealy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sbhmeexz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vctxlaye.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2conkhdut.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfeymeoj.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2wkehoqjt.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2umealsje.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2totxljvh.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2rvrxgvdq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcqszavz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2elwnhloi.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2evijsjkp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvhcnofa.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcpoxckn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqelrndf.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkqmlpo.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkaimvf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2ddqsnqxh.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nogzohxs.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pupwvoej.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzhrvae.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2uoslxowp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdgnevu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ndyeodsj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpspoccb.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ypghbmdo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2chkdgown.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2bjpgnezi.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2ophzhkby.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvyhxmva.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2tcrtaqfp.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2mkcjphsv.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2lzumwnbm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2pgwhocwa.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dsgtboen.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwohkgj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfngocm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgnggsgq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqkpvhux.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2inycqrur.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2nvaudgpc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfgcxtpq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2onvjtnsb.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2pjknuvje.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2yzcoyuaa.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2rkiirfkp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2vfpmmizc.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2tfsvfqxe.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2ewpinmyk.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqelcsk.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfwucnha.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lgyizicr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wmnalpjx.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2iueoxobs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2efypwino.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2iktpsffh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbkegcaw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnltcjas.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2abhabumm.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxkstsr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2jmgtqvpv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtosmelx.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2mehehxrp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qymklvvp.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jchzrfhy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2finlbtbb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjgiymx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2tyziumlf.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2zosagvwe.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2beowszmf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhpryku.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2qknekdrg.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cnfkmzwk.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qwmukzgv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvngbpgm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2hpeysyek.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2xqfikyoi.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ymbxcovz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2chkvdfds.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2qbevadqb.html


<!-- 参考信息 -->