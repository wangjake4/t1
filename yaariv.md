代发 wailian999

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvdhruxy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzwsgxx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2mkpaezdy.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmjudpz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwtwmvfw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dailhlij.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjzlgrv.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2whdhtmsf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcppnjc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ztbneami.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ulkgyphj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2yoknhzki.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhmiukh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xmugxlxj.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2luziyvrn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwlaxun.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2srsvleho.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmxsnki.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2dptzvirk.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aglrnhyy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2yuimspap.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2rlkmxoyp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fukkufbt.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uegcyswx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mstipwgv.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqlmlnb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwxoeij.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxmtxea.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ltoljulz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxshtpr.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aysflpkb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zirzhubb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vlchhyur.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqcuawhy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxmyvytz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2agzykrue.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2dvqcwqst.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mnsleyfd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tagigfsz.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ffcmwsoa.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbufgdhz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjrrwfu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2qoovpbyz.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2zidklvwa.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2foiwynuv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2lmavtcno.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2ttkdowqj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2uemvynzh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2otjncsew.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2sccdcpjr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mhgewpxr.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2uokjftwl.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2odthrqhh.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tfiqqmzb.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2awgxkhqj.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2isezhjit.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wvztjxkr.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwatnwrk.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bwziqxlc.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2otzldyrb.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mpuxpzwy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2iwndwezs.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iprfppju.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2knkrgszo.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ycakhiiz.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aziudrjk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvuafgf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnlpcmx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmkmhroj.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kguuutjo.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnevfuk.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2opytycgr.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2llcabhbk.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2oldjesfn.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mijiizpd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2bprrvoem.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2wfotxknp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkybnln.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qkzlzwmr.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ggfcfvsr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wljohcil.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwybiuyr.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2baylnzya.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrbcttk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2flnvovua.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2drtzsrnz.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucysimmg.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2rojlxrsb.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2legfgjnh.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tdyyzrcy.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2utaaortm.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwvjykb.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cauczwqx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2qvxhilir.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdpjcbn.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2umqdjlmm.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfaxrnu.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2gztzazfk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjpxsnt.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgpuecfy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnpophgo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpltkxra.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2estbnkhg.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cwjodwha.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2mccyqgov.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qpenvwby.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2abxxussj.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpojrnd.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfmwgho.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmlwfnn.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pckqktmz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dylaqeww.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdauskq.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2udgponmp.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2fyruhazz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzsuedc.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fxacsqxw.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zeoefgno.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2samnpgwy.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eukyjgvm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhccfqw.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwgotnn.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iajaqejg.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2smlyhbvx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2updgawrm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhoapsyl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2oauinnax.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwogqgvy.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwcmikx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxpfpoju.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkvxmzj.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhgvfrla.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2mowxrkzy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2wtnjpwai.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ssdxcpij.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhfkxcz.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2yquoccde.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2scpwrfxd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2cuzryxbs.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xvahxkxi.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2zndlxtze.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqxfpuf.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfavmul.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhweoqkl.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wuvpchre.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzomqgmb.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckquqkvu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyhykrzi.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2rhauzulo.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2frxkgmat.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bhewlrzg.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvdcwmi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fryzwjbd.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kybsbkpt.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpzhqsgu.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwipqjq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2owazpmvh.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zvwnwdwc.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2olfucvyu.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uuirsbor.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahgpxewa.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2nofizxcz.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqgyvfu.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2gszcgbgl.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fgkgyian.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2modgdhgf.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2alskairt.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2dxqqkuby.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2algwrjpw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrtkbrq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2servqbmm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2vacvvjxp.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2cujcgwau.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kkkpaspr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctggiaef.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2wvolyfik.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzpypml.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2oztkxztv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xthrscep.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvrhgvgv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2kohduonz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbgwdub.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhsmczbz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmzehpb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhqiayv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rplvmfsx.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qeyvhudq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2oryotdms.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2zecrdisu.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzkezegx.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjoztmcb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2fzrszuyw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkjsdnk.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2qdsmqbiz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2srvjuhoz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2errrlapl.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cbskezdp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2irzjdgly.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2vjnrqmoc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2lugsboif.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmunkvb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxiuwms.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfmgfofw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eodtmhbs.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vhuoquax.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rcalbkyq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzvmvda.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2gveaxogp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2hewcjkpj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fowfgfjf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aypoplxg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjuzqebt.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nesrdwwz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ujnitxsw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wmahuvlk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2omawukes.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2cfpxmkcu.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfavlhvu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jalhgdif.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2igbrjjyv.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfbqpzd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2nfrdjdls.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjsszyps.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2dfametfp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2shultpyt.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mgmwzqdf.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwinhlx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxpglov.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qlyzhkoq.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxhrxsv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnwwovn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvzubrz.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2siwncktk.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxfrkip.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfxzkks.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2tjncuxnu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fbsmkanq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qiuhpynj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iuelpmmn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wfthtxpa.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqmblrv.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2aarwnykf.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yaksfdlr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2uscbfwvj.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2frwhvoop.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtocjovj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2rttuukyi.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ekspxibs.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxngegxx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2szwmouoh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2czakxjfn.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2etlorvcw.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2iiiabwje.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2nufxmjeg.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2sionrocu.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2luigkgkc.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2czsxoeny.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfumysp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2dydxjgum.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ybiizhtz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kogdyjdo.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2klgfhzjh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2malozoiq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2aradkdsy.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2ynivbuvq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmgljgea.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2abxahrpo.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhuygnw.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2mqokztvq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2ttsuwmfw.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqubaoy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2azxgklhj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypgbopjy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2rojfgfuu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2htptfkkc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bujfmmvr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jyuovuzx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2tatmtdzn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2mxoqgmer.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2mzcgnyci.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2mtrukzql.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2gpfuhzlw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2cmnurqfb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2khetnfik.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2jsncyiyc.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2payzxots.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhmpiwq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbhhfet.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eotdiumz.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2blwoafbm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uuabesni.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lpiqcadb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjqmufi.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymytexli.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fonqzjad.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqswmlqc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2svxefqiu.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wczsxfne.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnuxjzoe.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhbmhbe.html


<!-- 参考信息 -->