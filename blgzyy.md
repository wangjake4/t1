代发 wailian999

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzpcaqjk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ricwflsu.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qimfrczj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2fejuimwe.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2biajowfz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eltgdlva.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nacxxerl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2rnuvfyhf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2xxojiomn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2aktbboox.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2maefgneu.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewkrlwjz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2fdevgyvj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2anmfqlww.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iecrpean.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbrvqka.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bmvxvbja.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2erkqader.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2haqugdvk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ffifkdhu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mzubwbyi.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkadlty.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbwexoe.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubaefeai.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qznfzxdz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fyclfwim.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2moalefvg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2usvdlbtp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2tpoaggvc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2suvfpxzl.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzhzmylk.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2pcreqtdo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2hymfdsjx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbpgesk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2cncqhrwd.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2osuifwwj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2wqlzoexf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2yiiopexo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqqbnqq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2zoplmphl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eyejflxd.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2embfmbzm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2irtycsqj.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2zojstulw.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2acylgdzp.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nkmxides.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbkbzxy.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2emdbkizs.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hctejikz.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzxvpdl.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rpoonprj.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uzsjjjgi.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pgwsokfj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2rxsjeorf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrqpqlc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjkhsqm.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqdlacn.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqsbqon.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqbabmko.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2khdktboi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvzejhk.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwxdiaq.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2oelvqmtw.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wpochusw.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtyrmzy.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qffohudm.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghjzkqlj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjrtwxx.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ocyjvfpy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hocxdxjh.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2invxrduo.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ydihefgr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yobkppoj.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fibhxeku.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mncicizo.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2caqblisu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgmafgh.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wvddzhww.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnqvrrnp.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2wvznduop.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2fnuygvlt.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmuaeox.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjqnjoa.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ixkkrgrx.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pbdhiwuo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2mhqkgirf.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ybukgack.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gvvgjxwx.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mvheyoek.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2kkhuxski.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxbxrjju.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2siujnwxp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtczrrms.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eecorsgt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2xddiqfpp.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vhbgtjgn.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2pwsalyqd.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbuxikt.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfarpmo.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lemxcozy.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vjjirwqb.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ardjycry.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2sickfetc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpmvrdf.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2sffzpvuy.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2awsrameq.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2cfbwwxgh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2uxurxmav.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qyjdrrbc.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhinsym.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xavxwxrm.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cvwdrcxo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvsgngr.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ynpputfb.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kybktzla.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2zlntmpez.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2dssheodf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkilyowj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2ugceafoz.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2megeatoj.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmbkqgl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwjeebq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2unrbrmif.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xegiijnh.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjjbvny.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzngwmy.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2efwwpeik.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvrkrkh.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2wugiiamm.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2iaygjbps.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdulvgm.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jdlwitoi.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2pefmysxk.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2capdiszz.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2uzkyonla.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbincvsz.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxofwwup.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjsvhbbu.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oejulcct.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxnodxqb.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjimveb.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxqgjuaz.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oevgmlcv.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2kybgakfz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2grpurkeg.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsjfshvm.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqensfdc.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjgrzzzl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgivfts.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fulovgpi.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2smbysjaq.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wffwpuda.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2gleyhjxw.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvobjhj.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2eopmbrks.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hfnvhwxi.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kdguyhav.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2dxaxaxta.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbmhigk.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2tlstfrqw.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2elqlpyuz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjmywpm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2nadhkdll.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2bnhwxrdq.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2bqoaqjia.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vwyrdhfl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjhieuy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2jyzrhdxj.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2wduhlisr.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tklrievi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qktbkiwq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvkzqubs.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2osvutuoo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2otcsgnrg.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2akmyripr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2iercobsf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2sihnxlar.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfsingna.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xlebkxvu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2bttxaksc.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqzptnus.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2siltinok.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2llxfkaao.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2wnshbfvs.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2hxarbaob.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzqjnrb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqgifqi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dqsxenvr.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnwango.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxmuacn.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2kobfidrb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2akeaezxk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrwddber.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjvphtbk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2thexfxrm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2puojobun.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2duxmsine.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtvciki.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2amtcaasy.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2brrcljjj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwlcsvf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2spgyxnfm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yazwpiff.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pstnwzlq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2myiftvmc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ytnwvnbn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rnlkpfyq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxqkqkq.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hybjswqx.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdwpmsa.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbsznty.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2oabmnzdf.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2slfyhoza.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xrufjbis.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkgmoadg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2vtirjnbi.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qhvdfbyh.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pjijjeto.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2gxydqpmv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxgwiuf.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iblanlhe.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iiyfhzxt.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdwcgpw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcnvnaio.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2najsgcaz.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwskhcu.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mqbhdell.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2nydpmvvk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ywnwzlfh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2srzdtfhq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2opzfnhxm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uvgkjokw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcjiwsxx.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2idojdryw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwetddq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2skdkgesv.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2ajcusfno.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzixvrvt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2oplkqclr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2stcfnxmm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2giduacab.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwgvhlo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zizemqld.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbetqcw.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2riheispx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2porpgwmw.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvztxsi.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqrvonci.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrmitnp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2ugbacuhz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zjfbnsis.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2mavidoad.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2viqmodzv.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2wcaigthv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2acuicwoq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2wdqcauaf.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2uhupjirv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2heuddecs.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2aduqpjwq.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2wfopzlnk.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2swgewkai.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2idglkvux.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2igiqxtrs.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2shnxtysq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpfjaqvk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxdihxw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vseglyng.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2clilhezq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rmqhfoba.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbedroc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2mctbjdwv.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgwnyfs.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2uhzqcxgz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzrcipd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2whsuoxsp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2nztfnsve.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmttfcd.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2xqnpnudv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfyitbqv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhgqgyf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gdsivbtl.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cnaiuxhf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2newqamhp.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2elvpecou.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgenpmvb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2oeblozbm.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdzwfsg.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uappviol.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2neyleilm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmhdguw.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqrhbrhh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ugopjenh.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvsobze.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2awaixyfy.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgdgezv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2whdkonpc.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujaplyww.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ddejnubm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qugblckf.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyfrwcyl.html


<!-- 参考信息 -->