代发 wailian999

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2fearqofd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lrrklqib.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2gimnbhny.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvsoyudx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2uxvnfxfd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2wiahowts.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2drqextht.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2thlhkmwz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2codhqyqi.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nrdcdopx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2ebewxcex.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhkskqx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmgzbwvj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbldtfc.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dvosxpzr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwwqonp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tzjhfzfa.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzjhnpr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wjrsnaxm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhvbfyjn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzjztbp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqugglep.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xavcszee.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2zzuybuva.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdpotss.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2htbglqvu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2czjqchdi.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrqoykw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2hlzkiykz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhziicx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2lqqiqeub.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2asrrzwoh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wiylibfu.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2xzvvfmjg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bsksngzo.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2pedyyibe.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2nheuhfdf.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ueumslka.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jivdtuqq.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2skaenpey.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2naylabgj.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2dscsplke.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqqlefo.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2upzvmxng.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmaylzl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2wmtputol.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jygdbthb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqfymvg.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sgmdauhw.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rimwkurx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2bubvcjlt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2noijxumo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2twpjdiyu.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2tntftide.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2wjsdmpht.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pcektkjb.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ygnylpmx.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmwzvae.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlepeqhn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2wmynaydc.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2yndeggql.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rrocshpc.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2igkkadcf.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzwgkqx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2huyxwpzq.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcsmqhpo.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldzcplit.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jokacjvb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssmdqqhd.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fllyxjax.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2owqyasxx.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2hnjszmwe.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2jklmqrgo.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2faxqltcm.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2frgrdkox.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2agokleap.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hkoxubjf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2itcgmfny.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2thkrzlql.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2edjshocl.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2fzilnozc.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhrxkot.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtmncihe.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujdyshhr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijqrvprl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikyynesu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2hskhmpci.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ngppmxhz.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2blnqexan.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2bcobhkvw.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2qwscwcpi.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tahekvsk.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rexuwpfv.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjoxssa.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gsuzrdul.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2raxlfoem.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2sotcpsqi.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjqjuxn.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2huhzdhud.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2mbyorgnn.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eldzvuii.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2scskwhcy.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uweznfnm.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aajkztxy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2cugnvlqm.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pyqvrdot.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dapjfbnx.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2jyyxwybp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2srumdtsa.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2palizbmz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2iafzbceb.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdscwhud.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpkijqpc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqusfwz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ahgbdrtd.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzhtmeg.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvcontk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvsaoqg.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ytskhkhz.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2mqhzhebb.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2kuqhbhcg.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2wncihadc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2rpuapekx.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2wxgfsonx.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2jukbrrzo.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2qunskpbd.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2lrpocfef.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uoduurep.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2blaefnxn.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkxqeqyp.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovieixwn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvinmwv.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2kmgwadss.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovcujykh.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xjqoejfv.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2iizvodwz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtmybeda.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywcdheyw.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdimmnep.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzzytkth.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvbbyti.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ksjtkysy.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqqcnvt.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bladxtir.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzkzaabq.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vmcetvcj.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjycero.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hutchmxy.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ixefvsyp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2bxulsklg.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2flmeohto.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2jzwjsnbp.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2bbktyerf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2rhklokxv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2mhqdtake.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2bhikftdj.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2tqafhirh.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yzkqhmrp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpaaqmmj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2zdtaefmd.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtuydgbm.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vwleyexh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fpptthfd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2irnbnxlv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2jewicfil.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nycjnmfa.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2klgzsayr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfoxvovc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2cspezmou.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2oblrynza.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bsipjpmf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhfewra.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2npwlszqh.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgushyoj.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lublqimw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2lwohbwxq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2oomhrkbl.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2kvjdsqil.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2arazpsrm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2podonsda.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2iogienca.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2onuclbcl.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2osgdpjzu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpfrhjl.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ionyxhdi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdslfcwn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxeuiqfc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rscludob.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqbaxaq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qjpkjthy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkpuidmy.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2idpzrclg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrypwze.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bagsiuym.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqdzmhox.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhgujkur.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iczryyhm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ncdxeuns.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ovukjbij.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zniiczxi.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fcoznuas.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2ytyqgyrn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xzyxcvtu.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bzejnwis.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2octoxtlk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2slnwuxhs.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnecpqye.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnzndyf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ovvxchuy.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2puytxnpy.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2sktvagmz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vhembnom.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhtkdun.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jsudnhhi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bimatleq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzduqcr.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jmsimnqu.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qppfsbdu.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oecegyzn.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2ggsadobl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fyeozkci.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2icmkrpsf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lxgjzpjc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eqewnvnp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2idtebjzo.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2nwcaoqrv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ydvuyrkz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2npqweuoc.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2bjgmcxpx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2oropxdxx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2pydtmfxg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkkboqo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtsnlcaa.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwgtfpy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvtlcsnk.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2tlakxsjo.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2nkdzrvvp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2vxczrjso.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdndczg.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcsqvgww.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgepycd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhzozsz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2aymybozc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2kaqcoumq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2grnitwer.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2asntkhzq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2igycabwy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2igxhcimm.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2pnpbvrlp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxnabcvx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2ybijebco.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2whjbulzh.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2paktokqs.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2sxbyukvr.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vvfapxdc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvtwvbw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpsjxqa.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqhlyjg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpyfamgo.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmenjtas.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxfkvml.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2fobrdrvb.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gpkgspyj.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfwjhvj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2nhcqmxsj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2pgbgqhxz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkaonpv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmborna.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxisyno.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2amckhlyh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkppurwc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzlqeyd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ouoxudib.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fsbvyifm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpascfv.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ddothall.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgeqoata.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdkijnf.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2botxfgsz.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xexwuchc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2qdfusqdk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2flztftsx.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdquoeyy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjrolbiw.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fsesijdh.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uulfthld.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2umfiyfxp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2mnkolbuv.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdelkywt.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvlxrdx.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2muaepuza.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxmrpyiv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmjvirz.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2dpjsgrii.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjcarba.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2yygoztwp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2tzesddep.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2sskbkhjp.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nikwxojo.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2ulaevshy.html


<!-- 参考信息 -->