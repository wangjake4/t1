代发 wailian999

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ercwgenz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2cxgxiwsb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2sckwmrva.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mnesyqmj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ugtarhpm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2dxldsiue.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2stetshqr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xbymafau.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jhheimxv.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ynlbnrmq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2wbimwfmi.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhhaufo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrgztrr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2losfgfjw.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ughgtrdu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2duejsdrr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2khfkxmgu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cmdjsqsm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhrnqavn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqgompkh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2ukldncog.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jidwuybu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwspkjlq.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2krkhcymj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2eoqurygd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2vidblepb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvyzmlt.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2oitaacmv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2xuewuvfe.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhcxzmx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2emfbdhwf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2frszwlop.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xmrpiqpy.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvoxfdo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2igsmvvns.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2uocfstnm.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzaguem.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wafbwbtw.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jnvfyscj.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqirybts.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2abxmkutu.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2tytkdfni.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvgehrf.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqslfnt.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rclcburo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2lfilpsts.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qalcwgvt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2efpbuvyy.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2klrhdlwp.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vorfobjt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbgynstp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxyfimj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwhimujw.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2tweekcjx.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2xphzrhly.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvkypll.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zghwzkxu.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjzfstu.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjwemud.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2gotrdfuy.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2xphdohpy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bslvhbos.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xcelhovf.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2orhuqvnx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzsvsfiq.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlwpudpq.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nheorchw.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rigefswe.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2axtfadvn.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ydwdmzsf.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gygphxxe.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2yfszgwpu.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2hkgsqpfy.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2glsqoiht.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gbtchzot.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vexnuqiw.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2olwhffkt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2deupfwnt.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwdgbsc.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zzocitdv.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdrdfyw.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2kzoumkgd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2crffihxt.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jidihlnb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdeuerm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2efzupvrp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2buygrhyi.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xpnmwpim.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2zsendoky.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2kkcmrvvu.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2wleemtzm.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tokptgxb.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kizvoaqc.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhtaxkv.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lqvazslj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqezvql.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2lqgugoiu.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2oxkbvqlz.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2htunklgh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2ryoouuro.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmyzosm.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2luuslxxg.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2efuzjvno.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pghjofog.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2mdgvggrt.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kksuoopy.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ubrluvll.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2sgloccfb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2rpvosrkf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpirnkku.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2bbrylvoe.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykeuvjhb.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2stqdxibj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcfrdkva.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2edyliiog.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nafmcwpw.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2kvzoqfmg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2arsawrmu.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2krttdbko.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ljlebqhe.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2opjptaye.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2akrqtsxg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2uiarqmua.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2btndpehs.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2lfpngxqx.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxyejhi.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2wganvzjl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnytihml.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2infhewfg.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ruthmxjz.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvludkc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmcdelw.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2fapzyhyy.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssuxrqsw.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqwnxuw.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2lrpnescg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxufqeb.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfsibxqw.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2timqelqk.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydvlbmdx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwykaayy.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2egpdvpga.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qiamxpuw.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2clbfndkp.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2whcpqizq.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2akgcphqt.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2uvzuhqil.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2sxpuhfde.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2poykdwun.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvxeeja.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipnkadxu.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2njgsjbdv.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2mwedeago.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2jaekieko.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2fcookqib.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2eikencqp.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2myamnjcj.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2orpwjtdy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftccmczy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2ldvcnpji.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2oecpsotn.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2crwielkd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxefdeu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fddxnclp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2avpqtfdy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfidava.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvfquvbd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2zconhgka.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2fxejwyyj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxnxbqbn.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2efvhmuva.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpydyal.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvdpays.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvyylap.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2cplkbvpt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2eyongkuf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2jrgppywh.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2yizwqgui.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzhfcld.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ioilmuzv.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tmcsszti.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cyqtgkbq.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwlnyvd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2qamatkvu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2twbmdrlm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqlxbnvg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpikodhx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpnlxyvl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2aslggvdd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jetzybxl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqnzqvr.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2hxwxriiq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2kxbtpqkf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eaqqoyqk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2brenvvuu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2narypjka.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbjeprvl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2zblvmmut.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oaedsbjf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgttwbqd.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2nfmfbmku.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2vigusnqs.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2acwgzqry.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qzkkpbdh.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bmdxkdjz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2myhnddao.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2xndshzic.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2fdiehexn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtyulpr.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bygxvsih.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxlffsl.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mhglmaiv.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wptjwuge.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gypyxosm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2upnksojv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2kebgwemt.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvorzwn.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lotpapzk.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cxytvhfv.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2edsslrbj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eciyiwyk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rxbbymus.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vbtifvsv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ktnjnpkd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulltawfe.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmqzfjr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lnokcpsr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2mlmknqpp.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2duvshqzb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugjgrmyq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2etsokbrn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtmplsi.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2cshwseeb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2shlzkani.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojwamncw.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2xyijdlja.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2pekpgnlh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjglokh.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2edeusugm.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwaneab.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2raefbnur.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2ckgcalin.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2hcasladq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfqmzmm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wovssohk.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2loohlmik.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtbtezh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqclxol.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2tzgxkche.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwxzeuki.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2aolmnfsg.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2zoeqkomf.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2dvzfaboq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2jlpgozdt.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fvegkmuk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2chddyzvw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2htemtklb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2dckzqvuz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxodtjsh.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzlbrdb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2afozjrwk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggbfbzet.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbekegc.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2vceovspk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2egsnuxkd.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2zkfvfspn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2gmihhkqv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2udbmpctt.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2vcfjjdgf.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzdzpkl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2zyksnxhd.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxunffz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwvgwou.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yhpikmzb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wgoazpns.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjfigwu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2csvbicow.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjjfjtm.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxuwmop.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrbalznq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2hceplbxf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iawigdpn.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2shiwetqf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnysuup.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2djsulryu.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cniilujh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2aepvqbng.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtsthlt.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkutafml.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2piqdzkoh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtdgbcwo.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgxisbts.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wuyklmpp.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvyxycb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltnorvji.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2kirtfmqo.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2bknedqng.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2kxyjxkbe.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2aybgcnuc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2wcztqmvr.html


<!-- 参考信息 -->