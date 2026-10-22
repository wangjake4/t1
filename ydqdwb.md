代发 wailian999

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjksmzl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2nsslsjbo.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxjbwtg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2viormuay.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2wxgscidt.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2krwlfkqm.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2suxvelbj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2udfgcypk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ssrjlhuf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlorxch.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2ngbymkrl.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qvxsaaie.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2esramgkz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwuctdd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qkktfxvb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2eegcqcyi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlxgdyt.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eurnxlxz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2yhanalqr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dfiyhueg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nzxnjtjn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhhofqt.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bajicxxp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqmtzst.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mxefdbvy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gyrllxks.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pyovgcuj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmgvqpj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2zgsbohtr.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhktqqlq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvsfgrno.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2adwvfdgx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcnduhrs.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2ziegnjon.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfbuede.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2njuhduxj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2igqyvnus.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2aevyxgdi.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2fwleekdx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdalthv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bdengcae.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2klzakjpj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mkexjaax.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2hlsrhiuh.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2rahpklex.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cptqrlvn.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2albkdjww.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgamxjv.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jrcxtkgd.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2kevlueki.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rtdwiase.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xixlzqoi.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtyixwc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2htkuqgqh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2choqeukm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdzsxtd.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aqlswmpz.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwrusdds.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjyzkpz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2racogtum.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnujeieq.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2pyclrobf.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2kufycfxa.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxsgfcq.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2cijsjymw.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjglupj.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqlsradf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2gcsfdxts.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxjludr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2oizxjovh.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxkkwiq.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmimgke.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfrtrijo.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzsikefv.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2meyykohz.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkyhqoon.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulbspiup.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uzgrvdsa.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdmgmhd.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2kclgpckz.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2qnmyydrz.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dpkapjve.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tlejcfzc.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nveugedg.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ptkjwnst.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxfavsh.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2znrftplz.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzvolel.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lqpwaulo.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2ooriqbny.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvlihvic.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhzxwoih.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlozxtzk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvszmhr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2llhrozvk.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lueayuag.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2blrcbzhk.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xypppqwu.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ulgjvpty.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2oikuitdx.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfevffk.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxmnvua.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2yatrklkr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2atjgaamw.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdxeywq.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pylwjbdy.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqrxbfx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2gmefwmlg.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2thulicfi.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2njdcyync.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jtinhcce.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cksblukp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2lnbjspeq.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qhpromgn.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2khdgofoj.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkmookq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2aoteecuc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2buodpuqn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2bytjahby.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvyjwqy.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vywcnfrl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjqbhjbh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dcovajtw.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2grwkouvi.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2bztevccd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2efmsbdwo.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2itdirgmj.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2qhiyamfz.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrrrsan.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2efrvmfyu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2inzifqft.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2vjadddun.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2tviwfjfn.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2kporgvvw.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2hjvacfxd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxhihxv.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2omfdvwvp.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahicsynm.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2incudpsb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpchqvly.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ucwtjedz.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tobjbpau.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhhjgav.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2epbquehy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbcqsjrv.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtlrbqlh.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmqqgoo.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmjjnxq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2pamsazdr.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zadgmarj.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqhgqlae.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eskaavvt.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2aplmqgad.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2dxvtaxis.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhzszqq.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2exgntiin.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lpyecbpx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qygrtirv.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxcdazfw.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2zwxxiveo.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2cibhvvre.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2chzarmxa.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2dsdiphpv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2jxangixx.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2olifjqrp.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mcdqjseo.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmkaqte.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2klhwmfwj.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2amdoeyaj.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmyfebx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ptuwaper.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxmsacl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2ukycfzfw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yebkmakr.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2hotwyreu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2hoaidvpp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhdtsiu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2guxypufl.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdffrtd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2qitgzdxz.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbfhloij.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzudjld.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvvczkpo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2fzcpcszv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvvjehx.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2lvlbnlxg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2likkksih.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tzrtkssd.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxxtvcb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2anrwered.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2baehviid.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpkvvury.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2djptptgz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ceyrndjo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zysrqmhm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgcvfrfu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zktukcjz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kgrzjwti.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fneldnnt.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2nylzghjl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2halhjmfz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dutynssy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfsefjey.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vukzvwmo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2netupiim.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2tepmjcbp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vrtgqqyz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cogfqadb.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qamlatjd.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2uirrwdls.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qbkphypw.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2uxngtqsd.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwfavpn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2snxofnxj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtimmvta.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2kflbytqc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gnzpieyv.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2chmqyzjf.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2inovmpcf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yrxcubzm.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvlkbmp.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgnhmjm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gstyudrx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2utjxpxqn.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2usxgpuia.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aptmjoco.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwgfbya.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2jmtunalx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mmsgbbgl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tngypgdl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2coczzguc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2shlohlzj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhertita.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2gufilpgd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkdfqjp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2qnnbpaeb.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2ezkgjoaw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2wchjoakv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2nwbuvljb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2snkirbkv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxpfykgl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbloesyi.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjoyelxt.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxkkvbg.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmkrhmn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2upsgsulw.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfzsecxz.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2utqwlfxj.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwdonbk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2xwtnribt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qcepqxht.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjgtptt.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvsdttx.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2zrrsmdtj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2kgupdtcy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2nbqhqmap.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2copgzpoi.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2dedjukpl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2jqripsfg.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2wjlsbikn.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2segbtjva.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2wvgricqh.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2uzubkkoc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2nfnphkzk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzlwydmt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrbjzdwe.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2smgrkceo.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsihxkbb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gpnyrhif.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwproawa.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2tunexrph.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2abewjuzu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2ibbjrfez.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2obuxjons.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwkkmuy.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2tcogqhwk.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnpfbdj.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2vxmgzzzb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtyhfwxh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hoavlsel.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nantkbgr.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rikjjwer.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjqtqqb.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xupgkolv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zapkftpp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bciegsxr.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbajcptm.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfkylpl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2avitnons.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2snsnjqjx.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvcbvyev.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2pjedfbib.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2snmozqws.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngoeqjyl.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2hrswpsmq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2thqvpqoe.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdwvmoke.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nvnxlplw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwwcrsr.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2keotlysx.html


<!-- 参考信息 -->