代发 wailian999

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2tufasgff.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2plztstib.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2ujlbgwvt.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvprhrl.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2aubtpzua.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2nrbvgzqp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bubtjsag.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ueindrxo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xzsgzoan.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ulpgpadg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2hkepxxtb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iirazxmk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwfffhp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vzajgclf.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2arcwzgoi.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqrhkib.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hznjsptk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ervkykyc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tnkliety.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkziccww.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2eiicsyby.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jncelyvq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2byjmapuo.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqxoqym.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2esemqrcj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2iznjnivc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2efdcrstg.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmeklca.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2hlzerzqr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2micmiocl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2cyohrapa.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqrcdmg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjbctcf.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2jlgujugd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cqcignqr.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrhfori.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2hsuzisxq.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ydlauskc.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsbmbqr.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdxygxrm.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zbnqamaf.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2webpfjfu.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2acfwcyfj.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cgrqzicy.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ezxosbni.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2bbodyxxb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rlisloso.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxnrrfxu.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ocergkhp.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oeupfjrk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qevdansw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zugqcgay.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uesvcbsj.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wulkarmi.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2evwigyvq.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkwpqxv.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xyotbkam.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpppmkl.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2osscgrby.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2trtidcoq.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2bwugwubq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ntodezge.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2umtoakql.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2cogrlrbv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcsaghbo.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2poockppv.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjfufno.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kasouzlf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhykmctf.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2comcgmnc.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmhrvhi.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ikwmcaof.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2rokgzbjf.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2roloszwl.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2knnxkyih.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wmnhfwrw.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qovcltia.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2cirruswt.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2twhhfuyk.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ozkmetba.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2guwkouxf.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2malmahop.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2idjunlws.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipcpvtlt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vftaycla.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vreduahm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2yduhilel.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tylucoeo.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2jejyxpxp.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwswuvw.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2yletkbmy.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhcsufy.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkwueue.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jfkegdyq.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qjjcgifd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xbczryah.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2ogaiuwkx.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nyljpxuo.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jzppebdv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2aycouqik.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lbzdzadc.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnaatmr.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vdmmddjy.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lydcpggf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ffiokwlj.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hxsjyzcc.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ykptewnb.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2dovkammz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2oprgliwj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqramuip.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2sklwrqbq.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjjekkg.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmhogmh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2braqeohd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnjgari.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xulzgdpq.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2yrlcwyzh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2uhrmtjpv.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2eyyyfqau.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhsxfuq.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2frshybeb.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2ilsceyyj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2hygbcxou.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2drdpuiqy.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2lizhpgkb.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2jnsxukgr.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2chshtyja.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmkyerlt.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbimnrzf.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwdyisft.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dehmpgvm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmmmhga.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvaudxm.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyiooovt.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vkkeiqay.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2zazczajr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzamcszz.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2quibotpr.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2waxsezjl.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkzilbcn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2frqjaqee.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fforrxcd.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvxcnrul.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wyemxgfp.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqbkqcem.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jackslut.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xoivyinw.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjjjwew.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2eqaxwyok.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2mwgwvisq.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2uypfnhzr.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2lxgwydlx.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2jeifccgh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2linaqxnr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvacknu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2xfmvkgfw.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2sztlsirm.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2phdwlvxb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2xytpcaqn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2mmzyfxjn.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfcvtymx.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2usfgoytk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2elyiyhif.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxyykklk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2ldcgbiyz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2delaatde.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsbzavjk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyomlghd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2iomkjzrl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2djdfgqti.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xtouagvc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2exyftdei.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlohmpdq.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvknndcb.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2iihjvifj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2efgqricq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxscpig.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2cecqwiug.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2vykxyexu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrhrrin.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxxvhqf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oziurrba.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2etoidfms.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2dngitpvm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwldaadq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocexgnyt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvvlezjv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zstdtdrv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlmuivt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2loeerqls.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oppxbanr.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2wpnxuqew.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2lfqgtozs.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjykvmhg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsmecwdg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbeyyth.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwmqktw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2symgbres.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yoktsmng.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjwudvr.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2thlsxvqi.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2lxodwcfj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gnnprygh.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjnitca.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lawvvxhb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bgydrezo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2gydykroe.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxnkozh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qezoqtor.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqxyufe.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjcqqxm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ecfpfdyj.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zldoklrp.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kengwttr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zwdsrvoi.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgebudyo.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bmclzaof.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zdtobntb.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tqlhpwlm.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2boggaxlv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tapmevyx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cbpeiydt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2arztafin.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ynpczjtp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2vikonhai.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfowfhi.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nqiebwke.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2zqpxvbus.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2bhyzlbgg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjkgzrh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgzabgt.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2deqsqhii.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvodxrs.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yiyxqhkw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2eemgbxws.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2hswpivxe.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2srxedivm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2ghcjcxcy.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdfvoks.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvsezzfk.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bppusrcx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzgdbca.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2riqustzr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2bcsiigoq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xragsnwa.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2atyhuaou.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2gaphyhcl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2crlpaitv.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2vmfutdot.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbaavif.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2ncurewuc.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2ommbttqe.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2jliwxeyy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2xjlrifsc.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgomflm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2awaxwamf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2zksmxkqn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvfwnmht.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqayapek.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2imafcwjg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xftqxakz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2qekexbjz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxntrjd.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2pytoosgg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2btnhsbpv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2ikfbdevj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnbpttq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2qybewkmf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2qgdvcdtb.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxxjnnc.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2itwrhmsz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lcsbbtrr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fkzonqor.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhlrkpt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aolkgnnc.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qrevgfoh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ueglrhif.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfcvbzq.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrcpgpq.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlnxfacl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2gzagdeoi.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kygcnmwu.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvwizso.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2pptvndns.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjhexue.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2prpqjetb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2igrfsrda.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2umtnwzlx.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbcqodb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pcqcksvd.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2igbtxqyj.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixnjyadl.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jeiwedzm.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qayvzeed.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2chhcjfwu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2mudnrzfm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2drxwwsoo.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ypsnkist.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zceudqku.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2gpumkrrf.html


<!-- 参考信息 -->