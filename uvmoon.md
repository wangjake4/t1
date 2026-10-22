代发 wailian999

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqglypy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2febqquor.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgyckji.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lcrrvrrz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlaptjiv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ddztogsp.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwkvjhci.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hpegilri.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2mjhzqvxt.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mglqefvh.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vgeatjsf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2kxyzszam.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxvekah.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rvlqmftc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2aklbaxel.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yyrrekfk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ivlplehe.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjoltzl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2drfdxlem.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yssuzvlz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpfudjr.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2srdmnggy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmawirc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jmovcmbc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2chhpwmyx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gryacats.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jkbyoock.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ivfoehbp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2apngfyqh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttabrkgw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fdlyjztl.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgkfofju.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2khyqrtmm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rctdmrkx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2dahhbvgv.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrozvzw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqklevv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2phsfpetf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2skpmpjit.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxheglr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2inpgphte.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2mgosjpxv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2xsrecjcw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtvsyey.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pbnhleky.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2qlasjjql.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2evzivfok.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqhldqu.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2nirxvgzr.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pexvnmcn.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yquroqcp.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2btspqzwa.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jbzshezs.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpfpdjws.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtopwjy.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2efllnfnc.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2utbpjrpd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2rnsllaky.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2flpbihew.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2utkpibkv.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2weqebvml.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvriksl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndbyypct.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oahvnjkz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjamhsfw.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2tziqzfuy.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjzyixk.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxnrvwi.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bhltvuxa.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fwkvokep.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwwoauf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2jpcuukwr.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2gqtxccjn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jbnjbwml.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2flsrnrlv.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjbzucx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbbzrtu.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcolkpvq.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2apkdnqlm.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dngjmlyn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2dszhtvao.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ofuespms.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2atfrkjyd.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ewlbkeoa.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2aekgwpis.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ynqasokl.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2umeconun.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jagdsofq.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2svuabvdu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2uquqpkmu.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2biyqdodt.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2syxuqdnf.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2brqxbnjf.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2zeckrgjk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mysmfxlj.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsneqydx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmpafpwl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zyszgblu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2wvctwsho.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yijfleoj.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2lwnhsjcm.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmhpccd.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2utbobmeg.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dwptrxhe.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2srbxvpaw.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2skfmftzp.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrkhxbl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ezojgcgi.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2rovexscg.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2baizrgkl.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gehirmcn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2mwkyuaum.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbalanl.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzpubfr.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjbmosl.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jtyfwflz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2nvajxttr.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ztxitsxt.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qndgcykd.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2spfnskgx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdxrkpe.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmoqwriv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjlyghu.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvznobtj.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxefjbd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pywakcto.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wyrhbgpp.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxeybzqt.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2pbeqmivc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdlzbkm.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2urbqqjin.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2plzhmlte.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2thjecinn.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2tkrgnsms.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2lctiieom.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdcrbmf.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2uhuukvmj.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfhffuv.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtvxucn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2epipsdbw.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssaicoly.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwnimkh.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2slolkeqe.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctlsgxvs.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2mkyqzemj.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqgdpuo.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wyepdzfk.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2isblnfxn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkywqlow.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrkbgaod.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxkbtdsz.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlutbuac.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxnraay.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kjexumul.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2shosyiah.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hybcmqik.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqrnusyi.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xhvjwtyq.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xomnhkbu.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qfpprump.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2cnlwemrw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2enmdafoc.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnrjmgak.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2ohgonhaa.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2ghktkykf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2vvnyfppo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2zpnaqizf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2netyrrtu.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2oolpofda.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2phwcdzja.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2jekjenyw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2qmblvkne.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbplncg.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2cwzfqtwx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ytpxniqn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvgynvuh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2tarfoqam.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvtruzkw.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqbysdmx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtrkphtn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2bavahhka.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2crtlpscv.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2avahcyfo.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2qujdygdn.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcyzocsq.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2kttbtuei.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbadamh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2qnmsfydo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2scwtlqrg.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2pbdvmgwa.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2enqwxbjt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xupoiwjy.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmgcyqr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wbohemvz.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2qjkzkjnt.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffqmntnp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjmqxqd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2frxietcy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzrwrwu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfquxeoj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jscyjkid.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2euhsvwcp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2surftqsz.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2tawgdiyw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2opezjgvb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbfsmvqk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2veitkheb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oedrvsac.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvysskh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2pbofenky.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxfstfw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypuxroao.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2bptqgimz.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhkrozu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2wqoyusyl.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrimglb.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwatyqn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxxagfn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqczohk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbjfahp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2iaofxtws.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2onyrezrb.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2uqyqfusq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2azrnbkzz.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvvizcs.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hssexole.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2acobfzzh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjkngarn.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jqhcinbj.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2txcmjgdv.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gmgsrtbv.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2lfyulpwv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxlnpbc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iwweabvo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iuffcrcw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ltaagpke.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2bivvuamz.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2nhknkgqd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nksuscha.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2tgnkiweu.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2cedblakg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzthwcga.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2behftamd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ieaqfctc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2drikdsmf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvxueqb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2udxjkwlg.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2xretnlfx.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmjszwq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2abvndcpx.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkjxkomr.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2abwhhrgx.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvztttzk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2rnkxnhrd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2soffuubt.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ejdfrcmr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2npiqnnft.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2yfosszwe.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2cuilgmwo.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2mhnssnzi.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2kexrjxac.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrkbivet.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2diqqarog.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvsbqpy.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2wcryqeev.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbmcegp.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2pcyrhavc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjpupbl.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyclaasu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrnbsbbp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2picglgiq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjurnzhp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zxnoznvk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhurkcp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhqcfkj.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2dzniyvsp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2fkaebbui.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgojevy.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2hphopigy.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2kryyqxuk.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2dhdusslx.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2dwznicih.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxeppdcg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tilnmkxe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ynueigdw.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvklpjv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqkimal.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2twqxwlss.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjuijlz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjqhghy.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkqiyof.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtiirwmq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2ueodkpqd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2asnmlaxp.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnufyug.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2obfxtemx.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnlurvc.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvxxxahe.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwdwwqw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2rqycrnyy.html


<!-- 参考信息 -->