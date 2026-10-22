代发 wailian999

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2nudgjeyj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2olaefapy.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2kxynjtpq.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xwaxymqj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmtwajw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2klvodmxe.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2gdikekbg.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2timocufu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvjbtrt.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2itdjcgmm.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hqeeleaf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmnyaht.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2zccbculg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxdpvqd.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2prqjnwah.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqkytbm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwlropw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wremyjds.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2rtxsxodt.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2imvzmpez.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2joigviag.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2monjchkb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrfbwwt.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxxmyqv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjlzdxs.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ktfmgpdt.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2wdesxzcg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2psebttov.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gatbyboc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2imjnefpb.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dscyzhcv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2faektrfc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gogxwkok.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjqoumj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjpfnswa.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpsckpki.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2ziggsrtj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xattfhok.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqpvrdi.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2atxriwyp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2srpqftmy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2vgoevfyw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2chiyfycg.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2okptfgex.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2gzesqnmp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2sopfrqiq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2ekhxtiis.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2opsrbsuf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yzijevwn.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2dyuesdoj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2otnjjnoo.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2jlbbxjvo.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxnzajy.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tthchbfa.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lqkjoyvf.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzfhndoa.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvkpgew.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgegeiz.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wukruonm.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqbwnzy.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eukwrrtp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2aggvyqur.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2valxvwfk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqblvve.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2japmgpxt.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2enasgfbq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptqyiwkd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uydreyoe.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2slopnpem.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hyssbbuw.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2pazvyyin.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2lnktthga.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2leymxput.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2izgqimvd.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcdxepou.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ippwqrzp.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2hfullbnc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2trxulhkz.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2whmzpiqo.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ppktorvt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwvgtaj.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvowang.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhctmxhz.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2btsifmue.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2momctbih.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfhabvq.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xszogyod.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2jedgafyt.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2kddvsjcw.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ztonukox.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sasjbrlg.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxpyhsm.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eadmqwcp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2itbeeebf.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jhuudwtk.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2npweupby.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xxzlfizm.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2coizvnlb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksrrqrxt.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkkjhrwm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgpydxkl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2itzbmzpj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2ozkzqlql.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2voiawjlt.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2jolqyfov.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cewtnfpc.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhntvoq.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zmcliwov.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hrelctkx.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rahlqltz.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxdiqcv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pagyfwxd.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2navzkmio.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ykevuddh.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2cggunyxe.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2xmndlddf.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vmyantxm.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vwawanvy.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmrywdi.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2frytrqxx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2suulccba.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jupwyulj.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjminbq.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2qxpgykzl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2zehnezns.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbcvywpo.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2ectndowj.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhvhiio.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpabcukl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmiiqylb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2etzdrmrv.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2whjzfhbs.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2lxwrnixo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2pdnvixjs.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmpriaj.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2xrsziyee.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ejduwnqd.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2ihhdmqyg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2qvwvvhpf.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2koltlcwo.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzzivzn.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgicbqb.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2yrpkmqjg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgdhnop.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nckjowwb.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsydnyuw.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjiyveyh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2pccamogb.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2fvlvwbig.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgipujlg.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sptsdjng.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvrtrbt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajomnghn.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qarkskxq.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwlelwb.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxysffba.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrfgmabl.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vtfkvzxp.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2aldxedkv.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qoolfyye.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2djczunyw.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vuvnoxxl.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2igaiyncq.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jztiyawd.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lycunscx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2nnyqvwnh.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2alyfmggt.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2jauabeyg.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2aurimshu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2zxqgusgo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2wghesdft.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2rxnhunsb.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2zghmhqsf.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbqbwih.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2yljgsxxx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2qimwgbde.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzetsaud.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ophlmbtf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxmmhiy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qiuwoupm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2grvjdtti.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2muzkktko.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfaohugn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgndsuqq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2stdablqr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fngcaxao.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qllyjfro.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfatvkt.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxdhqbjv.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xllgbuuc.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnyfjmry.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2yckdamwh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2sqbgthxy.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2mrayisxv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2eixfegil.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wmeimdbv.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2piuwranh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2njzmneww.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2zgfdalon.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjmxitdq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dchoezyb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2odbzxvbz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbsidaul.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbydccsu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvwwpwu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2japyyoai.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cewuzxsv.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2gwjyiqpd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2wucrzowh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukaqwvzm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuhlezdr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqmcfox.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbnlkqp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2eshcemxd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mybepyqw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvezgzgs.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zrvqqsjf.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2upkzruzy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2nyznrfgf.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2wuyciosx.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2amhddzjn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vmotjkgn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyetwggc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2qohuafxs.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jyashwzd.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gncbqywc.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2lwpqxngp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2onswpqvr.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ofcxnmgd.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ysiemhtl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfixmhi.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwdvvhc.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2boxhloss.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pjkendpw.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zuggzdgk.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfkzjhe.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sdcqjubd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lylzdcvx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2asvxoakt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hhrhqrcu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhwnqkep.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2wzkrerli.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gontqtie.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2bnubwvwj.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2zsfyobyu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvekktwt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ikrexnob.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2vuiejhyu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxqxwovh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2etslcjte.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmropiyw.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2twvsqmqv.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2nzyffxtr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2bisrsull.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mialmxwh.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jljehdnn.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahutpjbz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2qomyzxjz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2addpxuku.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbnslqn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjdltcr.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2hrbhfhft.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2akofgudg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2djgzarka.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2ooigeazw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2wndvtmpy.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkhrtyb.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2swoiexdn.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2dgmfvlyz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2lqienawz.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2eyupakre.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2eezuqyta.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgrsqumo.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikswmfbx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvcfnegb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2clvnbykv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2sobbvatb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkyplhvp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qkptyivb.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2tsiwxsnq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2ywcrqnsa.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2pquvrqal.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2umomoafp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2echykgjw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2vabtdfsw.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2qriffvcs.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwmelra.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2npocpkjs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gsmrqgyp.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjcwsmz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqkoxsz.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2sirosejo.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbovtgg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wifwzzvw.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2snhydgvu.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkvakywa.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2vzyvfhcu.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jayduqya.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2judzyjum.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2srsyfdki.html


<!-- 参考信息 -->