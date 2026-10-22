代发 wailian999

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2qttiumtg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjxklcc.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2aaqkauqm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwhpzbs.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2relxlbrm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nwenhevc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2keerzowp.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2effwkbfn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2itnkzzte.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2giiuoioj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2toqhynyb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvqczwp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bevcfbxf.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zbbveyhh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2dpitskpb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnzftes.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbcoeujr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzvpnmri.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwyyvry.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bheptcyr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ufdaqsyx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yegnggjz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlrvjng.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhgqkbl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2firlnnig.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjkgnjf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnikjdag.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2mzfzymhq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdszgedv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2nteyzkuy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2iytorhjw.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2xcgqvysk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2hgcndwhg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqqgity.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2nlsutexp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2zymutkia.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pbteflwz.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2akndouvd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dkzbnhxd.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2qbwalglw.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2kahiygnq.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjtolqy.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bsaqcgzv.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvpzxlhv.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ewizunyh.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxxjuqwq.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrifdnn.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2noazbtcm.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uewuwcsa.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2wtkamomr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kohkhczs.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdqaxdi.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nljthbho.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpfybwbm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvsvbnzf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmkhzyj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzzmexpp.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gkzuiuxl.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2rslpqpqm.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmlldzy.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2itcgqllv.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jpzompet.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqcorvbr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2xkomlyfp.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgkduva.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2sywbgfkz.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwufjja.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2uwodsxfi.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjhyrcpp.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnhamqe.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrougem.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmnbkcnn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghrtoytd.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ufpmfqcs.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxsltrf.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2rwemzmph.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2vpeqxqek.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qqladlro.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ehiptzag.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ofakahou.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2velkyqnf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2grbcxuja.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjznibk.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qoftamko.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2uucxvtcn.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2tvijikoa.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uexdtaxz.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbsaesv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hokfbfgj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvpguchz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2zembygwg.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sonmpyka.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2wuhwlyfi.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jurzdhvg.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2foxyraav.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rcubtlnh.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ecrzjnkd.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pmcykcwl.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mestleft.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2yjooksug.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2tbyaoxwo.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2phnikatv.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2oencijih.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2hbsfheig.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2alnzbtsv.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2upwtthgn.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nrojwcrl.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wiofrmab.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvxdhaq.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hgutrtcr.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sgvxljgt.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2nkztaypc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvvygzb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqsypouw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2mxubpbkg.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2icrrpjph.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bddkrbvx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkzlvuyv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hmrrhxvo.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrxpefl.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2nddihjjo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2awnmclpk.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2azbhzdgd.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2egzmjkje.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2eaffahfw.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxeegoq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2naepqpyo.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ecegsqnp.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2zcnqygja.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2nlkrbhwb.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2gsymvjeo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lovmycgj.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kudgigps.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvkbukht.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqcpdndd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2igpaiavi.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ubeunukx.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tolwdonl.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2drhuyfjw.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2flqbashu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqzxxmse.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2slblvgas.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qevnhhgj.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnkafsby.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqticmw.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gdncugrj.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdhbbqe.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtbwccm.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2qthzftst.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwwuwrg.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ioxowunw.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhptgul.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ujuxpwco.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2gzuedvta.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbhbtiju.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzzcsbg.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2umuztnjw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqxcfsm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2wjcgospy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2ybubharw.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2tkprwvln.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmsbqrv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyeqfeyg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2mymweobr.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtliyhnz.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hzifmhqs.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bnrhaadx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxwrsga.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2jczobybl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jevwevfs.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2twjvyoxj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2fliwwbne.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2wbugmgvl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2leuawhfk.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lcsresde.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2prkljqzz.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvhxenm.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2olblzdnu.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfnxblvm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2htauctfm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2erwblsck.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2ysopfwwf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjsmvja.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yokwyras.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwhgnbz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2btxdbsiq.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2vtsnntiq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzafyxt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqussdv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqlvtqnq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2maxbtdyg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfflibo.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2yikttpnp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2eadhwopy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2evoejotl.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2chvgwzmw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2mttyneje.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqwierz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzgloemw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgxkhxua.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqonrro.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2sgldcyay.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xxfuyzhf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdanuxz.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrvutvg.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfaqzrxw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ucsgbqia.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2dkvslhhn.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ogcubans.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbjhvyw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2rulgvqyr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2dlitoadf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ezwwcqaf.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uocfspiq.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2zwihkzob.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2slsmvtef.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mpruabco.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gqyexmtk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uxelwoch.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwljjpd.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjrholr.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pklhratb.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2enxgrkac.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2nceayawv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2riilmuay.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2taxluqkz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2peperpzd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mljgfloa.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjnfklf.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2mniwwuam.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2alyzkzxj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2xbcvpwvd.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2vjclffwg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjriktl.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2hngngpjc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2wzyndpvw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpiavmww.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2sekbjflg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxhddpmf.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2hdzvgegz.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlglacg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2ziliskct.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfguzah.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2omxvloxv.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubdtzbsa.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2kgzayzfg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqcfoyz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzwntjn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2knqhrelr.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2jizkxsur.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2uxogrffr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2mypjitez.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2dwficvtj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2wljomvay.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2meoxyvjk.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqqvrwb.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2etabhije.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2ughfrbvz.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2onxzdivv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2tgnzcasp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqxubra.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfsqvtye.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcjhbxl.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtaatgio.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jcinrang.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2yofmfzji.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wmmaabdz.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2mgsusjll.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhmdydf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2acskijru.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2zcklavwg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2vtaylhoi.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2wsysfotp.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2zyzizpwp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2scdnzful.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2txambqoe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tznyzwor.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rrltkbwk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rfrrfqqs.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2prlmhtye.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2izhxbnox.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2aimzlfyq.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjdzylh.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kitgdhzy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2gopinslh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2enencxmt.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffgeuvdx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2kffdbhds.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2eimuicgg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtlrdqf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2zgbovzvt.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2nnngvfar.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxwhqymr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wikaumtk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvirrtlf.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxrnechp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgpurdm.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2awhjzusu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzliniph.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2olsahbkr.html


<!-- 参考信息 -->