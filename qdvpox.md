代发 wailian999

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2sbrmijml.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2erzuxiod.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbxupjda.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ffgefawg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wdsvpeil.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sltneabv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2hxpjqoma.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjhxwga.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zgdzzgpn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnownju.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmtywdx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2thybotmw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2knfrwtev.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eectogio.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgthfzy.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqvehds.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2actxzafz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qshdcxfe.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2omqtwhjj.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2cclajagj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdbjuyo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2fchhifuq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2fjypbhqj.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2kokxqnao.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbifngv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2xavkmobi.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2wihdqujt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2adhwcode.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2egmiocsz.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2qttgrssq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ulgswdwf.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2wydvckvb.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2vshjutxd.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ybxubdmn.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jixhwshw.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pijscnod.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nwiquude.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbbtpzs.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2knmxcowr.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdjhrzd.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2thiyoaui.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2hzqpbctg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jqgadnec.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdeceufc.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vimizddp.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjvjxbz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2erruudzo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2crffjszh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uifofumc.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbtjoqb.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfhfwuf.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2viasbdjz.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mfactbnz.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wwnzdrsp.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvuivun.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxfriah.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2sodhlovf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2epsuzzkr.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2tvydmfnb.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2oysizmyx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzmfzbi.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2csratzvh.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjsgzpti.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvlryof.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntmdllhe.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uxnhdyrx.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fekbmzgm.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ffiijaoz.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2gpnsokvi.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2glyvqmpj.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mdfigpbg.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xgupyoua.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xlkzsdcd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2lrirpffn.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uvlbpxyf.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rxkmpzwz.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2uybnrjvn.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtzcbec.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hddepksw.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2drgjxfai.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iodbsiom.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcjwqxcn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgvxdlt.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mmwnsvom.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2ntpoxift.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2nmgbtgph.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2weixodlt.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2adduezld.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqgummv.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ikugtcqx.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2muyjfmes.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cglyjxdl.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2wfzhwgna.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ixothowk.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2fgpuzlrw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2wfnlghxv.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tdogxqfz.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qgjtbtmv.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dpmnltaq.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tgocdrrc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2tvimaeha.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2svwelbmv.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xouesjli.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2nuenftht.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2hjayzpge.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdvlkax.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2tzatmega.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkmznjuk.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlgtdrq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncplsliv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2egjhydpj.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbqxsdm.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2lqqjnsaw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2oayjnoyb.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2dmlgcxsd.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2backvmzr.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwdkslu.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2cpssclaf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2jbecrffv.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2rtdbbrxs.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbkbjnt.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ooccjfbk.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2uexwrfwn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2osdqdmig.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhwjwjj.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbcidqpt.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2evjayubx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ioxbxjew.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2zaiquujb.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cekhoosd.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jmpuqbig.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqfdzoh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktscgqjb.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aixqdqxu.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zczbvdcv.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdfviocd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhredguf.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkyojtk.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijuqfzfi.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2amngnbox.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxyicbyt.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lgprizec.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wapjdwwl.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2matebzif.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xgevzqet.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xyaamdws.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxuhcax.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbqnqnm.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2uxxvglcw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2biesbsep.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2gyezmbqw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2chmjekdy.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2wbmznmgq.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vvphyekv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhxlhaj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2puwldobw.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixbfwbst.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qykbqvgv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwpbxfz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2urlhqrxq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2kceqfsrk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnyubtjo.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2acelamaw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2nafppntl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2ikkxjqgp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtgwraq.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qtutiikr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2wcutxkjm.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2sivmkuyy.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxlnraxj.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsiymbs.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2rogpraui.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2qquznjwd.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2jirtkxrk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2zoizenul.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tlngyztp.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2iepjqprw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ouukwltw.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2fqoqjfba.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2dubmnevq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpspiady.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewovbziw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hracmytc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhalupa.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqginkj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xbwfcsxf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddaymtgq.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2gyctpsqy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2ecajjlzo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjbmxwe.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uurnsxuo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhqhjzs.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzgrises.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2fcbntqts.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2itywnejj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwavgqny.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dodaqqvx.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2tsszlpkf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gabiwyly.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vznlcgxo.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2djxmgwhq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2dzzdkbtq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihyksmrj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2pxefkreb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjxctrw.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ajkothvu.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2sickrfpv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjivkjs.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vkavxmmv.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sjgefeni.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2azgurjys.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqrzaijs.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2akvrppyz.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jkavqzwh.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gkckpyoe.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2uoklzenh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbvkibl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zkkxwkxd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tyyuhvji.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oodozvvs.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmrlsgb.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwkuwtg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qoumrwpl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2oseiglmo.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwfqcsg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2zludqksw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2dxqmzyur.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhadfwh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2uukpedbb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxxinzf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oplkhfaw.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2qzaludjv.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2huwwrngl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2ethaoeoy.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2aduytqmk.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbiuhxoj.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2idlikymn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2recrnzkm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2uocsdsaq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2fzzmpbqv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvfrwke.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2nmltuudy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbzmaqm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2uscndzin.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2pydzcybe.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhpdhhnk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2goqpkprk.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzvulha.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2conbtlgg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2jxnaqscb.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrxutpl.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2gdcteowu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjaixxbl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2llqwwbey.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqrxktmy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtlzlvf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqebubn.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2twewegsa.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2brqqjizh.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjoqlpp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2wpbxxhik.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2lhhgisit.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2hvwrfwob.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2lpdsjaha.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdxtsdq.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2ssugaebh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2myxcyfcs.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kjjqmtbw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwnnynf.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2imfslmey.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kqgnbgmo.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ibtheoni.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2feezqvny.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqapdznd.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqxszxy.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjuvops.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2unclikwf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kskrydkh.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbzvehh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ceekftzo.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fipdlxaj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmevhsd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2fwazztyf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2tncekqly.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2zssfgsjd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wdsfwwru.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdaqwysq.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrwdqfbc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ecvslvge.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zvaplwkt.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfrwrykj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbfbocq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2fscipsaw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ikfjviiz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2azgvgggc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2surlscgs.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2tokkzthz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2sxwqkocn.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnpjbee.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2chnekftt.html


<!-- 参考信息 -->