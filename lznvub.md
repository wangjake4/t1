代发 wailian999

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvxajpql.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqieumwo.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2cskvdfuq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwssxnd.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhvfxrg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lylqqtri.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2efpqrrxl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2towabzne.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2zeuqalxf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lpzswvis.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjlqeqj.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lihnfqlb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjngecy.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2olewmqre.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdhiibl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2eapvnyqd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2skrysvcs.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2teiiuwdh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtnpfqz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmsmigjb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sbuaoxsi.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2svxvrnwe.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xnogjibe.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfjvixg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2etdmidoo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bbombyti.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2syjbdftb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqtakfe.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2tzitskgg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmiqtfjg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnuklejc.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2rusxmbbz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2frxyrfpp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2nzsxfxlr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2lqerzcrk.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2pljzuhuy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2camaaodk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2qeyovhse.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2deacjwzj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2eeyjtlvd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfbweso.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ynuryrcp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aurejlwi.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhdocwb.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2klyxlubq.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uqsrqqkg.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yitucnpz.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gozrdwck.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jkgkszwl.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxzbimp.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zcmwvaqe.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2deynrata.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lbcjnefy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2iboumuwk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pkylhzsh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjwcalx.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbdwrls.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjyqedl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkhegzbf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xccknmwy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmzyanh.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gyluwmqu.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2olsofgte.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdzopzz.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxnodsu.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2iaqgwdzf.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqazxys.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2cmdjldtx.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2cphgyzrg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2famxqjti.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2eeixigpy.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2vxasoolw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2chbcubss.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bitkeodd.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ioqajbkr.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvzymka.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdsibvj.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nxvogitx.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wooznrvb.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2mleikova.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxsrrfc.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ttvfgtio.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jpjujirr.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xzhgefal.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2duwjoyhe.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2eduvzaho.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yqbnmzzu.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxkfqun.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mfibztkk.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2knuclatd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnhabbb.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2czpvyalr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfujnbzf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dloohgqo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2larvxusq.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrjglqd.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqxryws.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2evmhfroc.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2etfhspxl.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxwchcn.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2imbgklph.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pzlurbpk.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhhfcvz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qfalyrun.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjphosx.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2arjyxfjk.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qdwniumy.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2nmqvwdex.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2enrzltoh.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oqxuowlt.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mfyputwq.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbblwkw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2mikvmfhd.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xirochgi.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvfjpia.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2lrzksmqk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2ceufcxgw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkbpqnol.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2futoprde.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2owdpjvdi.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvlgzwck.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwxtbbh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gajphsrk.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2shezberr.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2omnpncmm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2bczyqedz.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2zurmczzm.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgiwqrs.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2nviybkvu.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2jjlcwibm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxygijl.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qzrxphcf.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2ubidrlah.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ajsjpiln.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2iisjaorv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtmmfmsw.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2filntfuv.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqjlxvjk.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2epmjkrkk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2isqfugsw.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2twfytzlr.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfilbtmv.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2amoufydm.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2cucnnmdd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nymphviw.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcjqmmbw.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtltdmg.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxfxyqcv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpzwdeaw.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bwsexqhw.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbcstiug.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hxeamqsa.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovssarvm.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bccnihsa.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vlaonsow.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2smnmbcov.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wxaceocy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2zhufckly.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwpljwx.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2snvvwcee.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgvuuhz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2qipgfpqc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmcwdia.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2luyapeqo.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmccnls.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2utgnrvyx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2xphvydlt.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2yruolxtd.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2obkeawex.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2newdtaxm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uwhwluuv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oulccfug.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2uctcdgqc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcciqkks.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptacdfyk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2lendlhvj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2lowwgyer.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmtgdmit.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxkqrhg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbvyahg.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2epqvecbj.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2kffbswcv.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hysaulet.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2amumopuf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqnhpeh.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2zkptvbro.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2sophwjep.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmoknup.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qvpkqatd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbvkbkj.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2swfvloid.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2apwjxwll.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcnjoehh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uakxphjk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2btooimru.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uuomoqwv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gfeofkub.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ijyswbce.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmwsahd.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2tbnaidic.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2nufaejvs.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yunnthih.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfcqzofe.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhkhkrz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkyljeeu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2xwkgokls.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hnhyoecp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2anhpusbv.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvvuxgl.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2jowuvdvc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lctatswt.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ojybgbex.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2dzruikst.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzjepzd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqwjoce.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwlosgq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2nsnknixv.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2egyjgbhw.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2vpkiredc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wgnenyjb.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jjsulpfd.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pwurcgsz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2baqarndv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2vexvphdc.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tcyqntjz.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hjbkkvoq.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vafuojxr.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2psmisfip.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2izlhlwfp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hdbshwgx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rozahxja.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iofcmipi.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekhwfajl.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2gxlhrslh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2unvpurqo.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqykoow.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2iubobccp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvcunnnn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ahgrlwhb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2weuptedp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqkbtwcs.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vctykaqx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxzrrpey.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgaldfa.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2obztipmb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2zknofrtg.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqajlibg.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2meiarsav.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2yznfqkiu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2dnukfnee.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ntenfcxj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2uxthukvb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqarpvbo.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjhfeff.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2bsaxertl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2biuuvoxg.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmeaydk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhidhess.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2ggpqnkbh.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2oenppsyw.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2awfyocwe.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjfwzta.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2npktpvhj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2emsydlbs.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgrczhez.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqkfbis.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzytsplj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbblwbw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvawuar.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhxomrjw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2fubgzxkj.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2gwskbeez.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2crjlilnn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwibgcf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2tkuvzhlz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2englrsvl.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2zxizlphr.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2qmnrbbps.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2eisafqof.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qwuxecol.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vcnfxdms.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bvogymbe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgjaaov.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lqckqkix.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jveqbvxl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wypsmwbn.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdejlmag.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgacwkwf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2untsexcb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kualzvft.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcjqigz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfmfqzr.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ezppmkan.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjcgnamy.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjgrdqn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqubfuq.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqinttin.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgbukpm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fefxehcx.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2imqbkeas.html


<!-- 参考信息 -->