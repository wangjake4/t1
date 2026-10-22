代发 wailian999

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgnreqn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2spkztvfg.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lonszqti.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxajqfgn.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbkjppx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2obgjoquc.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhcivrp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2shexsxix.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2wqkggiqj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzlfrbw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfzwniy.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wgsnlpzh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ehgrsurr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2ifkuezrm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gfujkuhn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2scleckte.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fmgctcvr.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hljesgex.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwpslig.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zflhwpsw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2apdfxfvm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wyetdzok.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2myxfsfam.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpwyavd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2frwusjww.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2movwftzk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2darkagzw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvbsogs.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2lmiwdhmo.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxhzxfe.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwcuoysu.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2gaubxfam.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufangnsm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjqnmck.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2apaxsvky.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2grbusuqz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2sxnsvdvz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2uwyoqynq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvpfczm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2iurmogas.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2thczlrdo.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2fyaktoha.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlhfmbj.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrskvod.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2bajpqbdr.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mwbtbscx.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fradiobq.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhfthske.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aorqikxw.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfoncdy.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbisvxb.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2euzwxqcq.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uldujzca.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2eyenmrqf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxbiovf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iymvubuv.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2whnpsgtt.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tifhsieq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2igptqvsp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uzbmawcu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwwtdyum.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjouany.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvcrgpq.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2phzfaytv.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2lhaduhis.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bvcdzauu.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxenmmu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2jhqjpdfx.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2exhroqsy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2oeuxnxqc.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2atueqtuo.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2pkvocqau.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgimwslq.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxnioovk.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulcwbcvz.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqfdxzt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrryxhv.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qrckttib.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bboulujv.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtepmwb.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2veskkvzn.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sexfffes.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2egqfbyjl.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dwcfshzg.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ftigkyoc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2girthhgp.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jzhuklvx.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wxbalvks.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2oyeuubzh.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdlgnlo.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2clyphtvu.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvxkzlld.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njxjqghu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2itkkpwms.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2hnusnxxj.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ueluofvr.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2vzlrjams.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xwpnlsfh.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2qxjugfut.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hzsysibd.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xqygcmqx.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fyyqswnz.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2llhphgoh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2fjnbuyzf.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2tjncagbt.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tnsybgcu.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zynvfeeh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnhbyvf.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwohfsv.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2flzpxjjc.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bunmsvia.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2irbrzpdl.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ddljduzw.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rilhybvp.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kiacfdbx.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxpeprl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmhhuwh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fokuzdam.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2xlflmdnn.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hedbshrv.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xijjjkvq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqkjsvvf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2knyjedgy.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2amjkvzqh.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2nxnykgpi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2jgcbmdci.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfwbfxb.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2wrkrnmpz.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2rciftqdu.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2okmmgtwi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2uvcivmir.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2snelxfsl.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2cylqzsun.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2roipwjqc.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfhjiqb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2donulpsh.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iojvkpqj.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vakgdftu.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcisjtsk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgelaswp.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2fijpunzu.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhcooxs.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2epbgskbr.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2vocntrpa.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjuwkdmd.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocooyofe.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rumdklou.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjctilt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2umxqmbhm.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lfnqemxu.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxubgfot.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yherqifj.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzxfedy.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lzidegfm.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmlmrxp.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwhoqdp.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzskxzm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2arvfsopb.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyhwspue.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2ttovreif.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2nehrazgn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2mjapsata.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2odjikcdz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2ulatmdew.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2zxuhocsb.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2etjzveip.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2twcyodgx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2hgdudlfz.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxzajre.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lfyrrsjx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ntatmgub.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jaenvlyt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2gtcqnheb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzwdile.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydvvkamz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqlmcdy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlmcybr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccemkusz.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2iprbabkd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2cnrtikbw.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvcfmuj.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhzjnak.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmzykumu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2pblkxwuo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2isbvcokf.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2vrratrxz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2pxobjmqg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cdkrwgug.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yooylkrh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qdgmjapb.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2uyikrmgw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2lardyywk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iducdpfi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uklzcdou.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvjinib.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfybalhk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xvqkhjsu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yoifxskk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwydhru.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2doumdlyq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2gbpeyrgm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwufrqxh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2guyoalrk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbbeiezz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjlzjixg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2djtxgfqy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdivtaj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovazxwed.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xjrllatl.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2skbtdakz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2aeeouryf.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2sfdndsmd.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2makaunwt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ksirihvg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqenmpkr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2igvyhbwd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdqitlh.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iewiqseg.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2piinkpsn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zqcnddhb.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pewvvfoz.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fetgrcea.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hwamsqih.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwammlmx.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2scuyvdvu.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dmgdqkti.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lngsbgtr.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvfppfi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tydlkyai.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhdaopl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2evaltmxd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oozfjhkb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfpfrmck.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2ucblvjvu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gorjbhal.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2dcpihefp.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmetsts.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjlhyvjb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2hnkiuyhg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2mimiphcl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2swxmcxzv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2srupjrby.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdwmxufk.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2pxupoggj.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmrdems.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2bdzxjxqz.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgflpjal.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2titwbcmj.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxsjuqvb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2ndebxyru.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2hcszxfee.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2enewsqfh.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qucrjlmg.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2psijvigx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2phxvqgto.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2xtwabppn.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmovubu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzuewro.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvhvhue.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2sceckixy.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhabdzr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2tfitkpat.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxkzyif.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2intvsztu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2uyrzrhcy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwjrwmco.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyrrxind.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbjckkqf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjnfzlx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfovkepf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2uvlwkxws.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqxojfv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2xstpiqeu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2crkizmlk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfihuvb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjlfmzc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2mliqsgqp.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2xdodqmqn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzpkrurs.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2arrfuott.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2klrcykpl.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ofpfziew.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cubrtpuj.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lfahdyam.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2neobwjir.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2suiojglr.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2whpbyyii.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sehaesrl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbherpv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdgggoa.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2nszusler.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jgepzpil.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hrycstoj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqvuocq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ffyodhac.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2pwydujtm.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2eiocgtqp.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtxcjpk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jeclrpdo.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmkbimv.html


<!-- 参考信息 -->