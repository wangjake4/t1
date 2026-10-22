代发 wailian999

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ujeporia.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxisrdo.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2qburramp.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2znjboecm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtwvbjr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2zdumvghl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxvzjyq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2krmlmxle.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2khzzvkbl.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtgmycih.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbndany.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xswqhrmd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2atvorntx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gpotqcem.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qucserzq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqmwmzl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pkkqxbux.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pqkiuudd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2swrvckcx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2anzjnplr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2wtkkrwts.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2foqxsypr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mczcqbqw.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2buqbovhf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtymsiqf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2vqlthusc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2cyokhpmq.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2zbqgvjkl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2bkifrdxc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2iswrespo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2wumjymgy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmefvsz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2arxfypqp.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2cunvhmwl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhmsrpj.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrwrrlp.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2kgeviymw.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yykiafhj.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vbenigsa.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2goahvnyz.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2muzhaiiu.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvaditgd.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kwkhdwwk.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2otztltpj.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzwjhqb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2bsasjwxb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ugulvarc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zftoloxf.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pkbtgbmi.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eiovjwcx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzhctuoj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sliwkrts.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cachalnn.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xixsfjfo.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2njetdgec.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2oynqsvbv.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2grlhwbut.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2feskhqoj.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2koohncnc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2iboeqyvh.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2uyvcqkof.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ybweafqn.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2enrtpgil.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2egiciewz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbtmpmko.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ciltlokm.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2totipzku.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbxuwrjq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtdocqpu.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2itzeestp.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbhjlwj.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgapwon.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2dqpyrqev.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lydtxkln.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bezagixo.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mfaclfrp.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ayegcthx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2lfowpqvc.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dietyetx.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dygnttoi.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzeozlp.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2beycazln.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvashjrd.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eymwqpqc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjntsjcg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aspmdyep.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2veakbbki.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rfvvaduv.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2sofefkva.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2otmbunvn.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2vjigeiaw.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zzkyudve.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2khywgjxw.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fogxfwkr.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lyarhekc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2deispvfk.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2eraiwbmh.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dwdgrzxk.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2fjykrudo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2xdlkbjes.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rsatiqny.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ozojcbya.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2htvcryvh.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kalswmfn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2sbtmquhk.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xkbqbhyu.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sjprqrpi.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2opxzbmyz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2oauycjwb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwtvahg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2zywpkxfx.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdhjyzgl.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmeuttcx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2klzvhieq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2isxlachi.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmtuufsb.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2znwejloj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2zppmhztt.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2rthyjruf.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2qrezedgl.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2dtnypvdt.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2slctetgv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2detmjnov.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2htygrnsj.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwuhaog.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2eaeahdyt.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2oskwtknr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqkmuoz.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksoygwyg.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgtsqcf.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdkmdblu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmtzmzq.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ljdxqfpj.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkgrbwkl.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jorjyvej.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2lnxwxobp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdtzbpjy.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtsmrmlp.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgtqwfc.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmcxouip.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzmrgjxn.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2igzrzgls.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptsejzjd.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ajjniyyd.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpcncjo.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdwzjfj.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkgxdaq.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wisoxmjy.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pqfhloop.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jtajquax.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2wckrdpvf.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2qpsseydx.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2llandmvo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfneihi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2emcbhjpq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2smjjsguu.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2ddynfvue.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbwzrvo.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrckrffz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2pywhgkfz.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2luijzppr.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bultfcrb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2otwlckrj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uidxrbzq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2fzgjnwir.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxrokih.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2smvchnai.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2awqzzhfx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbfmlmk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujsompqv.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xqitrggg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2hmigglra.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2qscbnbtd.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrawtvs.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlocakk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2oqxhqwoe.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2wiumsagz.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzypttd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwqogzh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2exynhvxr.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pykzzknq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ryidavvs.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjtzbqq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2gknqeduh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgpbxfdh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjvqdor.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpomnrtx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnickjkv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2yjqewbgs.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjyoqgx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghswaduv.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqnchdc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2jzykeiie.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmlechqe.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2esadkwsx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bltuiwas.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmdhzyq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrxixlo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sjfpmjyl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ichcamhe.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzkznlu.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2chzkffzk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ondckmak.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmhrafz.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2rphijqbb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqyodfr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2svgwpaye.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjbbrki.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ejozqwvu.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zsrweoun.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2mzcqhggv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xekgzvpb.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zlahycci.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aknvuqcj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2czkovcmg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2plebmobo.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iumckvrv.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hikbvwqs.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lxregugf.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmyujnu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxrupta.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjfkokw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cgjolzug.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uxxudinz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2puhckzcb.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2ejctgsfn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lrrwnpqk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkyhytk.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2fghvgpyh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqexpvsd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2wikkkhxw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2hgdmsbrb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuimjnjt.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxddgbo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxmvahgm.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2tzswkoin.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2otmwmxev.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2olpwrkyb.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdqztdl.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zniezkgt.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2godxklkm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2nrebqahz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2abdakgca.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbyyamb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zaaacjwf.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ejfbobms.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2xvxczkon.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwrcqud.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2ioorymlp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvmxmlw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2fipxqrda.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxqwblo.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2ryolsedz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2wdunrhrl.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lsgnpfgr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2clxujcit.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2acukcnpl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhrrqbhi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2khmdrzkx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbrtdifp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2nvoowjqc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2bggsfiop.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2anrouoll.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2nfohigin.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2jyfppdno.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2ybsdsapp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2mewytrmd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqqqfub.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2mmawxbvo.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2ndckginw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2udbqzcxx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2eendshpw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2itllwexj.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgwueji.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvuysjx.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xchjnzwa.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2eknkkroz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwfflgg.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2voefjwhb.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehayklyt.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2nghapvjq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtzpimj.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwtamhg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmupolo.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2oypjprus.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxogskb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2dewpyarw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2uhiuuobh.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2oedxdaoa.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgeddot.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gprkqrqs.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2molmntoy.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jltncmye.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lipikgwd.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nipqpgaf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2gknydjxj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2tggxqdvw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2eowdadxz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhnjujey.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2szbokiaj.html


<!-- 参考信息 -->