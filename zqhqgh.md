代发 wailian999

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmjpfjm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2cowbpewu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2aktlfluq.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2yzvjwwls.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtxsdmu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwbwbvd.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ymiagwab.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2evatnbjp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkrsaphs.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2riqwuqmt.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2fygapcdq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kesxaiqx.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2sluolzkt.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2woecelzh.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2okulyqec.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2zwyghqxs.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ilmcsmip.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmyzgea.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2iadpltyn.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mylbhoxh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2gmvpaqvx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2mlvskrmx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxinnsmg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qxszzlpu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2svnpjcmu.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nilumnox.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmtqfpx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ovfkxfvk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xkgmwuyq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqheagf.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2owkjgyrs.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xpdikgvi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qgmmahdq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yocbecia.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjmyqku.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2okrbwzgp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2vjyyzice.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vihiewkm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtrqutc.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjofbzd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2uapnbuck.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2egifsvwy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2kfajhtki.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2eunvrcok.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtncuht.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdladvf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2pfpdniyw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2pboyxljo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lmticzrm.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2reoqtdqd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xmcodyyg.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2tasldjpw.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2xioonahr.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vijnboud.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dojaqrxm.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2edlmiwel.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxmnxog.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvqqjvkh.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2htgeypnn.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zqlyqdrj.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kewbifwd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2umoxeqkm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmkbuvi.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2llpjxkrp.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbgjrxx.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2phmshmfm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2seztmkul.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbcbvcr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdysbee.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2appeqged.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2igujuvpv.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2npeypmtp.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xdgbpgmu.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzmgvbs.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2cipoijlw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2bxsxihkv.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2kqloqiyy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tjekzijp.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2phymigeq.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2vribqhvq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhmfheh.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdrsplax.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fllmyanz.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzsjfzob.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2gomsrwdj.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmvceti.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2narwmjyv.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2sgejchxd.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqryipl.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2noccvmgh.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2auukkovh.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eymocywd.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wxsncyki.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgbmwso.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2twwdjdeu.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fwcutile.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2tzundvtg.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2vluyzpvb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xemtqqux.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fncazmby.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwtvaxfx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlopaden.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2gttpprdl.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qzrvaafn.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2ovzduyww.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ilheukza.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2jxohwdcl.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jsudwggq.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2djizdiun.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mercofum.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2airwkhuk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2stxclheh.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxwmzlq.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpnxrba.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gabltnlv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2fzytrviy.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zonttiyo.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uosfvcvu.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dvskukss.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bcchyvoj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2otzedzpe.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fagowqrp.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iwscklec.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2xxuavplh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2hldpzifb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbdnmxrg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2aedkdwug.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlrtxvfu.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2enxfneog.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqzbsjk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tfuvtzbp.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2azjsjeqp.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2fnrzaotu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfqadow.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2sgplmbxr.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2mwpxduxt.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2nywbqbmf.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2qampxnkp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2bgbdnnje.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2hnhtqnfb.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2zckyjxoe.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhxlgdz.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2scvilixi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2usgwcpmy.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2edktoxyf.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqllzhgs.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovunwqtz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqqxmmtn.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ablpsrxa.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kijnsakq.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwsatie.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2betfizra.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njxdzkeg.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehcyhzod.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzcllgnz.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctiezton.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqiaclxt.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sekknjsg.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbtyrff.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wojaaezz.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqnbziax.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2sowofhpu.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pyeztabj.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2unoexhmy.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zommhdmm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2gygwdnew.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrsuhvq.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzzvner.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmvkwdr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2ytecbcar.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2guldlggy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrzwdtf.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2htycjskc.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tljnjzjz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ougiwvrc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2ntrqygnh.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgdmqrox.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jaaytjav.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nwvpjnvr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrvqxosl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2dozfakyt.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewyeqzbn.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2xaeqlhjc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrfhpbhf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxeekjy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmvlykth.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2anmcsegw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2syeploxf.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2typlsztx.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpzlyyhe.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2afobcygg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2qtvlmfmi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2qqzicqwz.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2nrkjogjr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdnngdx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdjfukb.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rojudvgj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kndazmxq.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2djfotuxw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2omsrvqoq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmckbra.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2brsrtozt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2whjohyxn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ellgiooo.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2nnibmvsc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tjullmdp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejpeuvhw.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2tehnwcyo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2obekmepb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jynhgxko.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnsuuhdn.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2degfkmah.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozxifbux.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2cuiqubsm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dtderivx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahjsftcr.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2uanajsly.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2dutwtpxy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gtywvvtk.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lqvcgmpt.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vbfckyqc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ripcacjj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzgbpxgt.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2abwjtxfr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bupbpasu.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xgygulha.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2odhhijsh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdwdpec.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2voenhgcj.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nartmtui.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yhijpkmo.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvucvqbp.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fyirinuz.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xteholkw.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mycojknu.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmpuajz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pixqbgui.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xfuxavcs.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xeynzlbm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ftuucybu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2jitxdvfn.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2aabawako.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmijzhx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2svytgvxb.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvojzof.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2alzzvysu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmlggcp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2cpdnsrww.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdyqtplk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyrhsrjp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkdubaaa.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2twpmqjbu.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2dotzyofy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2ivfddqgh.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhemhvh.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxnaeczt.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uweimwwa.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2bzbwjtlo.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2eywyqjep.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjrqkut.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebpwvzou.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjeitxf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2wygpkziq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2bzlpkpod.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwcyuiq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdbbioe.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2wjrdsbxc.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2juptanaq.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbmlora.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2uibkrnfa.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2flgjdmzh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2xbsjxkgu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2swfghayd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbeiumgi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwyjnanm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uizsgvff.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2eyctxlgh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmefahzy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmabtxc.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2alijnyrc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2qmsnmiun.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2fssuglwn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2livdsvxq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2mwoxwaht.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2lwfdugul.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2ciovnvoy.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvdusos.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ziassdph.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sefdfovv.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kzrwicsr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzegpqy.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kewvudzx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlqemdlo.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2skfywnwo.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xivwhozt.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxuiyjvg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2wdcnbftz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujeyslpt.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2prcfdgle.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2woacufgi.html


<!-- 参考信息 -->