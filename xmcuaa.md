代发 wailian999

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2brvyefxt.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxptmxsf.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqupems.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hagjlstp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdogllov.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2txhinksv.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kesttagm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2orpigcle.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2bsjcntpt.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2umzuwrev.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bjctrqgi.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmjzunb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2enoshyrd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqzrilu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2wdppajdt.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ergcvwba.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2niyhnftk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2tmyjxwfm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjuhipa.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xxralxck.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tsyilhsq.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nmuanuoa.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2qyydqndz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dibtnwwi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjouigj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pfhpnnpf.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iediceaq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbnutan.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2besdfkyg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwqqbgi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhrkteh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmbuqtd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2cxqhqqmb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmhaquxe.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvrjcxx.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2zgfnvtxm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzqupzl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwjhqmd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2vwgoyzwm.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2katokend.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2cawsxhbz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2zlruweij.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2ypgkdzyw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2xbyzgdci.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbliucg.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2sowszbwk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ifybuzbc.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjppgej.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ergzxqvc.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2arztdjnx.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zcxpzpdf.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsjndxnu.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wsowibvw.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmjvdbv.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2irwigrwh.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vzihgduv.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxvlksn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjvtqxm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ewrwwrvp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjuphwy.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtihmti.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibkejsrm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdpcidr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2coopaabn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yefrirqe.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxygwuw.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2jiqgonwt.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrxvllm.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2sqvwachw.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fxqldrcv.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwiyimpb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2amgbswnm.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2jjsefvaf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbyaypy.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hzoyjlfy.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2fndgdxfb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2itfwjesu.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdpwsuzz.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2argrqytu.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gaifqbcz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzpnkuim.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vikjnpnt.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2aabtnhvm.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2keibwfvk.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2zacqhwyl.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mcogkzvw.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ubsvydcd.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jczjalvu.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2riruerox.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2dzthrwgw.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cqaxnkwl.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqpsrav.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wghdxjmo.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2ofplbxyx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2usutyxjm.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnvykdyq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tewfcqcl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdofoeyn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2kfzriban.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwcqvqp.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2wwkuhuej.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2soaqykfb.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhmpqyq.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2sbarpanj.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxasaaq.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jteelslv.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hdaqylse.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfwqzlh.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2prmsralp.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kineudlf.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2rxuwcgam.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2plfepwnq.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xlydajab.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gadrwjvm.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2idnwxwvn.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwuibov.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2zyjetvbd.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bfoxvhpu.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gqmfrphp.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2vonuwkop.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2xqmesavq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjhtqeg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2mimrxbam.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mydgxmyq.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmbnoofl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sddtgthh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lmonqqmg.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxbhecx.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2fivulmdt.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2zyazcjys.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2bckzgton.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhkegcb.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xhleppyt.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2zyesqamd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2blzaihwe.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2firjcnll.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2lvshktkd.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2bqlpxcgt.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2kkaxupwx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zidajbxu.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwgtocw.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwtjnyot.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmzrxilb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2mofdhgzp.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnpabov.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2snndzpvq.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lwuxiagg.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjfamdi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rixyctnl.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xosuhnlq.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyagvsqi.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cptgbwef.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsfmpioy.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfxpwox.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzslgrm.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uymsllwr.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgbglnn.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2dartkltg.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ujnwwmig.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ewospruy.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmclxuh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2drgofksx.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2llvwvszd.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2chmbeqyo.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2rntrpkmw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzsjnhn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2rumamxto.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2rngssmnv.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2qnudxzcu.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jtusewjf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2pukjiuqr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2uujwywys.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwaygcvn.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jyukfijn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ekpjgjsv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bofdvcql.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2ghivnxto.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rssrcmid.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdlqbskp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2onjjnsmz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2jdhfuarh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2epcxxlfb.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fybbqddt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ngfziuni.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfwazmt.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2uiciznsh.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2blitentb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2mpefodaj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2qeghehhb.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2orgrcoyy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2palenmss.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vnhhnehw.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhvpidu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bsaphseg.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2byvuobnk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2wclxgreb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmmkxuje.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2upjxpzly.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrdjnkev.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtyutub.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fklzstbp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lcknyuty.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctpddvgc.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2rdfhioik.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2xyezmzfb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvbnlzo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtdktkqo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkpepggv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2avxrdzeo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxdfybk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqeejor.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2znuuejxw.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rwiceaun.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2pzuuwzrb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fdxyavhl.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2tatvvbmm.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bqumwgwy.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2rylhajfo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdeyqprn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2pridcohu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2srbjourn.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2olabqipo.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2yflfxmos.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpeeyfw.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jqclfqho.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjtvpwp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ymxoelex.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2azxbzrtj.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gttyalhd.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zycnhttr.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yhndwyrh.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqufqob.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtqxtzv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dnerfzrw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cybctysa.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pukchxun.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2uokemxkn.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxflzpw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lbdfkyln.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2kazryvjm.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmgipzf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2frdsefpq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ofacjvow.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2mbudmdvw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzylmxut.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2usrutwvt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hikitoqu.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmfovpn.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrtjxgi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2aniqdyzw.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqeekrr.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ouhfnzyk.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzlxinkc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbcutet.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2mvsjskta.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2tbtqtzbx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbfvwjb.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ssrywesb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2wzmuacqv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2prcqnosu.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2jcozezxf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2xaoqgrgh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2rcborpoc.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2gxrwczwh.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2ttcqgabh.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2webesmay.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2cksudobv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2kcsxlmrd.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhktllu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2topmxejk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqiazhwh.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxlpndoi.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2suwzkcye.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmltrww.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jbsccxwd.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2llajxcla.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2elpdqnhu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpivlmf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2inihvlcw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2cbrmvnka.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2nezprhfu.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2qhociyzv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxprfnkl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dzfoghgi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gdgofvsy.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdpsoxz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ufryjreq.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kgosftvj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjtqxixp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2eokgzatz.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqvkalyr.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hefzprph.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2obqmonui.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2joaojjfv.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2hevrdheo.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmemsopa.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gzskasio.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtogeiaz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2megqztro.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2tdquczft.html


<!-- 参考信息 -->