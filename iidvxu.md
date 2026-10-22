代发 wailian999

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2lohvilau.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2mhnhmbel.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2lyommanx.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2kfuzltcn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2yltwpswu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmlapmgg.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jqcvogxt.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kmlvjazb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2schkhaqj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pdvliqsv.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2csrnuguj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2nonhfwpc.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2nzogtdjy.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjgqggr.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zgfpgvke.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2zvoioyvl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2yvspmhpp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxggqwv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdbjmds.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2altqljmj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxliohl.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2bieffyya.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jukmhmym.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nbsatyxg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwbkvsf.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2waxknpdc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2bfngnilu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmstzoj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lqcfpahm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhxqcld.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jftlcomf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxnnlej.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jwersfwt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2reqwofkt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aujsqgiq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnmkodha.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvtjwvg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yqteblzl.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvbbiti.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2eggtvskh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwaslrlg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2mnkzyqnt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2xlplzxjq.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2frrvttrj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2mplwalol.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2htqktjoz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjbuskq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbgvpse.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2deggcksb.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2aaownrwg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2alinpsfy.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2mihuqaql.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvrzxcr.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kvffione.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kgrouzzf.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfpittji.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zeailmwm.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2whloiyjt.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cotqhtuj.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpgwolg.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpaisxz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2dueveyvs.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zccelwwt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zswdklho.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gildgolt.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkkajul.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfjubpfz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wgrvncdt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2unehswbc.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jhehftcw.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2lovybuky.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dmbwzztm.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2doysenlv.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rhtvqvri.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhaidpwr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2xqaqzdct.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2mluhastv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2knmfzgas.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2felbnlvt.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ktiieirp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdklwpp.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmkvzou.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwljmald.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfkghktw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvophndr.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kkgqpfrs.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnckesiu.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ndwkmaxg.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2tukaltzj.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pwnwwsuj.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxvlyam.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bjeivkye.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vcscptom.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmqrthw.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lexeidwy.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vnarnoqf.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2crxmwirq.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2miwwaujb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngevrkdf.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjihkpeo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptxlxdun.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jujhilvq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2applrity.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cugedjni.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2dfeqapqn.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gppsfgtu.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2eeivmtmt.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2oxxpksee.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2uyddyefc.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2besnevio.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hjqvssbf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rydlpcga.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvztyeo.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xdqxgwor.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkpyfgf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2zhkzmyyc.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ydrpcnsi.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aplifsmb.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qlyokngb.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhxpvfi.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2hisxifoj.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yshzurpz.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2drmnuqzu.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2bkrgedgk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2dnljzwsj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvbllbf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnvbaui.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqvqmbxb.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbveusn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmelimgm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2intjjczg.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2irdkykpi.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2ssmesosq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmvfbxv.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2uuecfswq.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdeahzj.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbpznmt.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2goatnbgs.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2ldzelxtl.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2nzyjnied.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2wmrhfgnx.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2gyproxbl.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmwhdxi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzsquayo.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xztkntza.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhamwqku.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrzbxcao.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwwwrvih.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2xwlwreqn.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gotjqfbu.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2metceeei.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2htwimjno.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uclzuphd.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2avolnszz.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkxdbft.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnyjorwr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgpyovn.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zleckfro.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vezpuyqb.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gdufoijf.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxccwjby.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2aqfmngbr.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xeixumvt.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hdigkopq.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qxekuirj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2oegwnaou.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkuuvkaj.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2ypfdjqsm.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqyobhs.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkekqhn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2lherlwjt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2whthoahf.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2ezqwfytq.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rjiesche.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2huyvznty.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2gaugfoep.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlvydwej.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lelubdlz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zhzimmit.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dengbnmq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvtisln.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmjmjbn.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgirjwhj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2irnvoyjw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwxspol.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2osxukqyo.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2uzetwrzq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2kdxbmxck.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkreqhr.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgcfmnzx.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvkltfk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2ybkvudqm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2lziybgjp.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2mlogktos.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2lqfxnsug.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uiiozxvy.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2aehrhyxn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nrmixtim.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2bzcbmbrv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmejriw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2crlugqjd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygerpfvl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvkpucv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2atgzkikf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zyfayjkf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vhldsznu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2npwauvla.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2wgovngbe.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2bmigvmqv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2udzmsnex.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tllzntsf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfuamfuv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgldbctp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2xikovvsl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2avwwqulo.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnfwzhgo.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2anilxhee.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2fuummpwi.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ebgmipbh.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qgnkiktm.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhqnpne.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ashibeqs.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdloyzfl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2vtueacxv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2yondrwyn.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wcpsjyga.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2whtiktrr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2brqfcmsp.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ikutcpgk.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwdxqqu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxmzeza.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2aprhbqve.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mmtrdmil.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nsfdlpqg.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nyrysqkj.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvgghrb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxgwamj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tclipogo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fxyufzhg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zxarzzjy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2rycnqpny.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2mrhfdgez.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bhyskbju.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmgqqjc.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2qcukvysc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2myijquhx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqotsnh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2swgdydfi.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrbrydte.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzwgclv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kilbkipv.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmpyxim.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xyniztgg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2oomahqwu.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldsyybir.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqezwbn.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pobgvhek.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2ojewwhkh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2cktdikvl.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2vhoahoep.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zeowgzit.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwncids.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2snyvigde.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2sykrwosr.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2qcwjumgw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2zswmiaoj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjsqjzt.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlbosva.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2mxpdjoue.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2soswreot.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmqsivh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2jpncuxah.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzfmntx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2heqwmvof.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cldykqwh.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2exxhjlrp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gyconpkn.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvkkssp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjgpldb.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2bdkslogj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2xtokndcl.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2rzafilts.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2muzptbqx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2esxbpcqa.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2sdsgbvsa.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2uclighvz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjqbzrs.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdbgwgv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvrlxfd.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ginfeeww.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fsuubrmh.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvmzirh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbufdlui.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2apfxixiy.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifguozdo.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxdgjbj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2rhtixrsb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvbrzlqz.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2cswjxkvz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ojnxmryz.html


<!-- 参考信息 -->