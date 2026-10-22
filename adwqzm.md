代发 wailian999

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbnqpeb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2einnzxaz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwuepri.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lxowdkbb.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hsthppbz.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ugyrcouj.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2drvwoduv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbwkohp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqpibjug.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2skipwmlv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ljabrfcp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tzcvbmyd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozdzlprz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnreexp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2neqjwsvn.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ksjbvuvc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2pagyyoty.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yogcvivl.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvnytuuj.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2eojdxabi.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfkcvrjj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwbnjvl.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtakbjih.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqngyhaj.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2zmoszmhl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gtyaeoro.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2riyuztyd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwmlqsr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2kenzvjms.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2sxlcqtdt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2fyuczuhp.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxxvlcl.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzhyzil.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2zgbpsxpp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vgishsff.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nchotgji.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2audglakv.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2egmbhcyz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2ittqnaiy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwazpbzr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvkdwrng.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmznwku.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lwpzpiha.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yilhkmxi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ordimfad.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwbntfi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmnhdmy.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhnnmqgb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2shcrshuq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cswofgvs.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2adlbzivw.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2rtlakpom.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpfzjejv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2qscjkypv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbphuyl.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ipigsbjz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2tgimqmyv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2evwxtque.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2zdfcuqcl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2vsigfeei.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xlclvhlu.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2micxfeos.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yhaysteu.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2qjqasagg.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2fetanint.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2onjwwwvy.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2achoxscp.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkjgzfub.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xymxgfjv.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmopbrz.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdmmnhq.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvnpdth.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gehgdkty.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2hotfjkny.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qoavwtvn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfekbzqc.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rzekbpqg.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvvuplxq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdcqfqhh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkjbcjo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjyvwzek.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ktknnljj.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2swujzuov.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2veomsigc.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fojxgnmi.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkzxbnw.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdotwxms.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqbzakh.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ojwqcbdz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pefoxjvm.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvionas.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2zmeurmsr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2glpjhnik.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyncxosr.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yojroihx.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpdexil.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2oluzhiae.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vdltvoie.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hudrocgx.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpxayhd.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2rqxtfgjs.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nwywspkz.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sudfdzmf.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cmhoxbhu.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2atqqnzyj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ddndvajj.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kaetyzft.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2buddrwpr.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hztiparh.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxzdrjj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgrircea.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wosvuhaw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzizrnip.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzirjszc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2rwwsmpzs.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2taeoysou.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfilpqu.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hibvtivr.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwiiboq.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dlgjljrg.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ojadjvds.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zwyosnrc.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2regcrpiq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hgvffvqp.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2dklndnzq.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rejprhla.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2rggbftyn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2choqapif.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fpenqwft.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nfcpgagt.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zrjnhkxn.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2phqntlwy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2knntzqnt.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jkatcmhn.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uuonplio.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmxflco.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2jbnstiau.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ciyavian.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2pbcndlpv.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjrvodx.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzvmfnoh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eixgyaym.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzfkvla.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2acbmqoks.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2kiamcogd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2vtlknkjz.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2tguyycnv.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2kqevcdxy.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ufawoebx.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2tsbeebev.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2mfeyhkpn.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2iitnnzxb.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2nwycbswa.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbsjzko.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqhdrqp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2euqfeyki.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjyhvsq.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eydrbyrn.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2okmjxhjs.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzeyaibf.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ofemcqnr.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2efjqyoio.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdsuvpd.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2wnppcxds.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgfinwn.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fchtczie.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyoureom.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmsqnniw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2uanpazsq.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2euyyerdc.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbsasgz.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xixedeft.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyihwsdo.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ioyrjgav.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vshujodc.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wykzvips.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2oquxedkd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2frcugpgg.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2gutncpgr.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzzljpn.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2apynlwvx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2klsnxtzi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2xnirggob.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2afgumavg.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2zurlfihi.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rwazzpyy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvrbqsbx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2coyscsux.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezqcsyru.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjbipzm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ucdrhppg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tagjllus.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2udianzod.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2smimvmxk.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2txsiopmc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjytnabf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmnamyo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxujbjjt.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gmkgkldh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwxvath.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2srixhrss.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlpsrgvs.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfeylued.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2iicyokun.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2buhuzqwt.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2mtudxtvz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2kywgeqqj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2maykudrt.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2locvofnh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bacftddk.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2glnvurto.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvoaihev.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iagaamdj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkjkkooq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbuztunf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecauzstg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ajbhunoa.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hdlxucyh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzulumkh.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2jesalhlr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2jwegresu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnetgatl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnzspirc.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2coivzsjv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjfwknu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2xfcnqqak.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tlskagzk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzickdos.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhwklwr.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2abyqmzew.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ftuuzsxc.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfaduuf.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfsuewf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnhfeli.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnihmiim.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2runcscja.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lefxqrwp.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ngijyejq.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2xpuualpa.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vauwxnzm.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rwsqragr.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ouflsivx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cjaccxip.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2mezfwykv.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wnvoipfm.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dsinnmvy.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mwxsiqcj.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjwocxf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wsctdcpo.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jodrtdyj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2whluovss.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvinbvr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2coeocjxk.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2rprcrhho.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2teuuxwcr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmvygfj.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2xiomehsm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjeacetz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2eeykcxwt.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2vinkaubq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnplxrbr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nihpqnwt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvofoblv.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2pupbmapz.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qjsbnnxh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2yjklulcc.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpoopdb.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvdvppsv.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghkzfssd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2baxcexli.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2kmsgltdo.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxgdlnx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtkcprsy.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2subfctto.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2hfspitrb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbxtimz.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2xhycfteb.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjrtyjd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2mpukpadr.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjldksj.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvdlszf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2lwtzxoik.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2yosqyqxi.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2sxtzixyu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2meqqdvii.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2doojfkpn.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwaslhuj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2juwmbtei.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qlomqmut.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2llvpvpmx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2cwcxljsr.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2hltgmhsu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzbcaaz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzyhykm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2bijlqvvq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2qtmskuhm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2cgpamouq.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2gbeclosg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgagzmfh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tpoltfhf.html


<!-- 参考信息 -->