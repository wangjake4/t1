代发 wailian999

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2pkrjapvu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ajsmccsw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2kntgzclo.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ikifeqnn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2oywzoftn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2ibkpxpmj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ngsfriko.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zsknjgtp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mzsbmubk.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gnasbvyr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2pkllftnu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dycyixmy.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkarxia.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvzutqzj.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pjoyvrlp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nroodnji.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2obhfhfgm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxoanfe.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gxatgvti.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmxhqsij.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmbtaax.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2erqkmaim.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2gckkjqtx.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2vpieveaj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmicfsy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxcqyjh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjrsxwa.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2tqsneppp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2ruqxoxmv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2gsyrkhkm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2ggjqmmin.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2jjyggigi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oppgwnvb.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2mrrozkow.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ctfhfntm.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhoqyvs.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2qunznegw.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ouooeoum.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2esfcvocj.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oafatovb.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pbehobct.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehpnxxqt.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vqdiltnc.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cdjbfpia.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mnufvtmy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2mefconvt.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2utmazeav.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohguzaxi.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xzbztwev.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aujavhio.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdetwpuu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oiwbzqoh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yoebwwkn.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2npusnxwg.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2zxljbuwa.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnsykhu.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxhftrt.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hdgecpsl.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ispazhgq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhznqla.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ogqmstdl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hoenhort.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lftbejbm.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2qujnwngh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynfppufk.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2frxvrumj.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qaisggad.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojosdgyp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkzcsimh.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2shqhlhvm.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtymdrrk.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2tcfppuel.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2jiocdshh.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xcdieiwr.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lwlqaxca.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jwlqffml.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kvzpiqjr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2xqlbmioi.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qzkxxzvq.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rysappsm.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2fgrvejyq.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2deiqyrlw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxqawnal.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkywkmtu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmckjfqt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpoejwfm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvsuzmq.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2otqpdqjt.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2gozzgqpw.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ttvjzxru.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2kboqciwa.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2olqerxfy.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fsakrpmr.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tynlnprn.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dybddsit.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2amqeuzsp.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2ufnkkfvl.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cpdbdirx.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2dghxlwbn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2weyjxbyz.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oevxmbsm.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wpeqrrny.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tiurpsjj.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dfxcdyaw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2hilwpxsj.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2grdzilhq.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wfzcvmte.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2rqalpufs.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2isoxwuxd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxlgwyq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2fikuxsez.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmiuzxb.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbfdmxjq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhftjibg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxyowfx.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzunjqwv.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2uzkdwhzb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2pjgclxiz.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2zeozdgdf.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2sifzdsye.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2vbamsced.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2lipppfor.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvzjjbu.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ckspzkkm.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2larsfnfv.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2bxzuzucb.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2umvruvew.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjbmlvq.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgctqlvt.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2agkguqnv.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvboobf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2noiqmvbo.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjhpxex.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzkigchk.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vygisscy.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2oyusugiq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2djwnamkv.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvzrzyoa.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjsmwiyv.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqtzdwyh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhkepfex.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uhcpoxqm.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpfvvyhx.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2idgjcyqm.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2mglitawj.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2onojbdum.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2netgujyl.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzormzg.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fluogenw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkmrdcv.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnctdedp.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2bgkmfbvb.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2btyidmll.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2lqsubdjg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2xiypguys.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2skfhmlmh.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2itzmqwqn.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lqpigsma.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2oeavvhhn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2vehbytmz.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubxoqvcw.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmqotxw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lidqiodn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfssdrau.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkpfclk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwkkquqk.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2oancsahr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhkjgqqd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2wnsyhpkb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwakzmu.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxxlwtj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2shtphfkm.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2anfkxmhu.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2juqmzicl.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnrkmjvd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2rdiqdruk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2vkimbvwt.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2peyrxgvn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2qmukhbol.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2shxqbvlo.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkrhhml.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqtdiet.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2rmurhyvo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvxpiwna.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhghtsn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdugtqz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2czzdcblr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdpdzeqa.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fvumlsem.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zoykelyg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2faptrzmk.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2tectsduf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvxwddz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyfoptjq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdgghlt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aypomwcn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpkdzvjw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2lbsbczyi.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxwmwpf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhwqsppd.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2peufflau.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhmmcvn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2hjhmufmp.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2kfejhwyc.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ftorcbtw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qzlgeyki.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdagjcvx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2fxhnrqzl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ihckujql.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ntyzzlzg.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2yrtyjsey.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2skvhymjt.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2avqzzmty.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzbqojy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zldmlkqs.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2bluphywj.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oqfdjnaq.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxlszgd.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdlhnek.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2bcnutjfi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2luskvupv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2edlewyin.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2crfkguli.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xaxbpdso.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcnfmmsb.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2eyltkkbj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2shhfbjli.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2rxemwysx.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2discsbwa.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrupblq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhcbwxa.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2nspebhwf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2etlahimy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2drojdxfn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfzffrkj.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2pusdlcmy.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2recjsfhh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2izfpobib.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkivlhlc.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxhubdt.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zivyxqho.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2mkkkseez.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2sjprvruh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2uhtdszwk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tsoyayjv.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2inlsmhmu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzlxugd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2erkowqew.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2jwrgttbj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2kirvykyi.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2mzsibnaa.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmczcab.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2fvactyew.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2igmwojfd.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvmldmk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2foafmrae.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtedrvk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlyuemib.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzirfbox.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyamxkzt.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qudjfevg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpckezmj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2yvayxmfs.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2btqzoham.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2pytjftlp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2kidkpfhk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmgfhps.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2joqiuhov.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpbcuoa.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbjbnry.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqoxvya.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xknmdzfu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vewzfesa.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2oaswkwzo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvdtxpj.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjwbvbb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpyqyuj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2iohhyqnd.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffsvrfnv.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbviqtbn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhzdbxo.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2evsffngf.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2cudslxfq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xixcsvun.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2enyzctxd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2msloncih.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxboxgm.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2forrkurt.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxryajmf.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dehisbwb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgezqglh.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdkrexqt.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbdrkum.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zkjcbctw.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cntgfyuj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2qaerjtwz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2qhswqjyi.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxqthup.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbfexruu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2khlfzrhn.html


<!-- 参考信息 -->