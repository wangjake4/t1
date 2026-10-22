代发 wailian999

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mgkdqmew.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dfsnghvg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2shnnxqla.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ifeskhvc.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lzkevdyq.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gdpabktn.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwputmr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksybdsph.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwocptxr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmmterf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2wcjuceev.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pnpmkhwf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxlnxlx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2ovooiwhd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2tnqdpinv.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2cigfekzo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyyaqtuo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iutnlxhn.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dhczfbmp.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2natfkbaw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2eucsrzzu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jsdavqxr.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hrndcqwc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhsymgmx.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2euyovxig.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kockargf.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjnmyss.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2eckxxjfh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzxttyd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhpoefo.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2anmljjhf.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmnoocc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2zbbyifza.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlljysg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dtixcnzn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2arfievab.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzatqakg.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjpmjeq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2ewotqdje.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2awocipbj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fttmjorj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ciydpinj.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uupsibxb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dsnkeojv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vgkxldvn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdhvyim.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjhaums.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2giklqbgb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2grtnviye.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iekzkdrm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ayareijg.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2pdfgyaxm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2joyliwzz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2abpsrddt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ovvzmxil.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2upgxhfke.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmfhrjh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdkftzc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2hsovrejl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2bjfdvjrg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2thopjilk.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2aruhgsjj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qpivpotw.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2mnibviks.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2fumcmrme.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hggzerln.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdzdbwg.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnheiemy.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kztmbled.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2unopxxdr.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2szlxambv.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ftujhcoc.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfxunit.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2adubhajq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2reygwjyk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qijztdhw.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lefnevdu.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wippwlch.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfzmjszs.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2edlrmxgb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjqxaquj.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kppkzmjx.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2vozmavsw.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2alzudhrf.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkcsjiz.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dalqbzwg.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2uclxsscg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2zmllwqiy.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtqfofs.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqvcyvz.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2egcqxfvl.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2cckkqrrv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfyszljx.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmzvqlda.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wodkchvc.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eukpamzo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykqrinfx.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wquihwhj.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqmngbj.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2vphekvgq.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2pnycbkkp.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gjguehoe.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gzntbhkv.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xdzohuxq.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tpkkmeag.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2wlqrphlw.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mpolufwz.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tovjseem.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pvmlcflr.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqamxlv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibtqgrzz.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylfwldoq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvfngtc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2habzaaro.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2uiuyjvzu.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2okpqzmeu.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2tbhscaxu.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xwccvibv.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2rmaorjez.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zpcnuizc.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvetjqr.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tnsfiymj.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fgilvdks.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdvpzmg.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2jeyewzcr.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjbareh.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2yrtrttmu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2yisqddwq.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uxrbfmvh.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xiybjazh.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwjpobm.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qrpwxgpn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlxpgct.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mhnhkwnj.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jerltevv.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2hqlhznax.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2pbydccmo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oiuosuci.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2tfunelgi.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecevwrao.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmhupke.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2njpqnlrd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qqcyarzg.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2izfuylfi.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2xlbovvcs.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2rtoryysu.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2elxfsawl.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2icchvtzh.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2tidhwmfx.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2anqwtdyr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2cyznabpp.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2lwwmjzsa.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2wvkfkxvl.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhdpkjw.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxrmpqf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsgpjwan.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2caoqwwky.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqhddao.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2umylpicj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbyweznl.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxjgfby.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2grbignmj.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzgjcis.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2dluirdyz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2toxdssjk.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxnflxm.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lakixuqr.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2htcvhosn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdtvtzwt.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgyljmk.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2moefasjq.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dbgkacko.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsslhhwd.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2naeqxwwq.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2beqaktuj.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxjowol.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zkfbmwfe.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqgsvvi.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2tabiwjfc.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2phchyuos.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2sidjpckn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2wytzoavt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2yzlttzvn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvgyjhy.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2dlaijqoz.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxdzskm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlfuwxvd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2yyeumpan.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2suozcprs.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rtplevlo.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zorgrzlp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwipdtj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2qemvtuak.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzgkpnqa.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddfjezdq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwztdarw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2hamsgzmq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2orgbbnqg.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nazmbsth.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwytzic.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2qruufreu.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwkspbay.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dasrsjem.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2ejsdeows.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnedudp.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2icavxbgt.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2mjnypppr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ivzwkokx.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tstpsmdl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxgxypf.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2jhvgtikp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqyjfsh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iblyhgxg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2maqktcrf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdejuojx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2onqybnge.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2femzwhfw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjnhlgv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pggktquw.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2xdnebrvw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2syegcpzi.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnyibdaj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvsdxmr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2esobpajr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vscviadm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfrhrhx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2phoiokez.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2otjxznpd.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lubsqqjz.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwwwjkg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2peslujea.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2noyuwwbz.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2wekroogh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2kmpvotpn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohnsmean.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2pxrxnjti.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2rdyjfplc.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wkexdthh.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2paibqutv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rmfmdhfn.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpnjeqb.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vptpqmny.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjrdyvu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2xraynyxq.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tgondjfp.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjvdmtr.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hwonoeeu.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2lyyetfxx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjvpkfh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zxpuprfm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wjibhuyr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hwitkakq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvoxnwf.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2mernovue.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pynqhcmr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2kymkztne.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2ojwtzkis.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2sklpqrzb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2nvbohyim.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2txaxstwd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlfzedzy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwuscujh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgzoqokq.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2abjeqhfx.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdyfjdo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2mpfyctez.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fadddncn.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhefewqo.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2etydpfdf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2mqeqldcq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvxyxsr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2zbuqbrgn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uazssofh.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvqlxxw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2msfcbfgb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2raisbrnk.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2dqpvlozz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqgsfuc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2cbcgoeop.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbjyvfm.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2mgkpkqms.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxzfumz.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wusghgii.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2sxyttnsx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2fthsqhrb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnloesnf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzkxnnv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmngmxr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2elvikbkn.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdooyumk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2urdpozre.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwmbhxl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2acjqflrr.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqttztm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2yafiwkmx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2okddjiiq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2akypfyct.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2dnbotprm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpyfbful.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gqlfhzpa.html


<!-- 参考信息 -->