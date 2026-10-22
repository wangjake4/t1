代发 wailian999

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2oziayyzc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmeuweu.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2yihmchgt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrjvtuo.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2dqqgyjin.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wdqeysig.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjtqoff.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2spnpuofm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2gkepuzcv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ebcxrrip.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2iixebawr.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2muyhchmd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwmebpn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2nviiptrj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2viyspsen.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pkzrnpcw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhepdop.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rppaucii.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2wlidbreu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ozaxlkul.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rflgofit.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yaupsmzt.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrehuit.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2peqxidab.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhnejqw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qltlzzey.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvqjfry.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2spfeivbj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2wbnxmlcy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vntvqvmk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvuqafhv.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2uckzsglj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvismah.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2ixspsxcq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2wgsqxyar.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbeszsw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2kojwctmx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2znjsfhpv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2plfexkad.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2bihgaqlg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hptcnchr.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2jiptzpxt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dwogisio.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvcicwn.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2gtmcvsrn.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2chxguevc.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqrykse.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcptvbgf.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jilxrgyg.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2aiusrmzl.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xwtomayf.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lndcymrt.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2niumfrey.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2yewsjjij.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qprddwim.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tptzuldd.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tpocuxif.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwttdrs.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcfxxdi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fbqttgmz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2svwgkxsg.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbvmdgh.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2xzyogwhe.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hdonaxnd.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ymilbbms.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjopjsn.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2iswupzdi.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2qqgnngcg.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2njmzcnnr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2lylinfrk.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2psxrpjlw.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxkiwvi.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2orvwucqa.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aoljonrt.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdgdljfi.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlpqlemj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2untasxpf.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zjthmepy.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxcbgvys.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2peqwrxze.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjvuwsw.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wdeqdgdh.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iwnpnirp.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bjaijxdz.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwoxvea.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2kwoipake.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjzkifm.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvfhken.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2uasqewnc.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfsymcr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2toqfkvtr.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwlatqqx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2whntgqmj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xekxzhfb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2ugloxkng.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rxpkushz.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2lknsplcl.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvgbhad.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2pdfhwsne.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vkrkzlbb.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ggisonrc.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cmkozies.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mzchaoey.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ntivzhhb.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2bwazshfw.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2udtrmdde.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hvguqmoi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2baqfwjqn.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2opqdeipl.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2keppmjvv.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zhqjgnrn.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwfkgjc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2wvnheseb.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jvykwwau.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dvulehow.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2msecuxhx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2aomrqkub.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhqnwhz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxumkmh.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzesaiei.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdueczmo.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbronfx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxfeeoe.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtcwnkek.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2laelnrch.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2gpnaypdy.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwrfpjj.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2dertybtn.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ngohruts.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2nejtsbdv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2mesmbeeb.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfidvjy.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbdovcw.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpjnepd.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2mzabwnhb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujufxzmc.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2skkjiuko.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbnspxk.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgxzvfdn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcixglqf.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvzxonf.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdaschvl.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2inpmebuy.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2coilewwn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmlylkiz.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpmswjec.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2orhtxaxx.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhuciuii.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2twxmzvor.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aupyvoyj.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqgyegfr.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uxrjqqqt.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnoblodw.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqagwzv.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fkygcpwn.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kyblyaqz.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2sfvniblz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2gpgxvvsh.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgvyusy.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxywimk.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2mawxreku.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2jgkufsoy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2lfqfmvop.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2egpnuthr.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmysjno.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wutmeywk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2yantdicw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2bgascjnq.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2eaqmckjg.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2irhlprxx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dbxiqfvm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zelbtozy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2xreljexz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zztkbjkf.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2nncjgevq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2hefgusjn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2kghpnecr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubfotbza.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2oaizpitz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxkpjto.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnqvhqwa.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2iusqeeui.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfuxfgps.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2emeliazz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ksprmwgj.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2ojwlirxe.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2tgagpxvn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzuhqjz.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdhalaq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpltbnf.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqtkguv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbyhmwbf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqqwbfi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmufxfe.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bykgcguc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekyxhbax.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2olhxcnlf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdjboxx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwibnrcu.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrydqpp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2hquzrqlt.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2prrsejrt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzapivng.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjxorwgf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqgnneng.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgpjola.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ajbdztop.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtkwmkac.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2crmqgkjw.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2hsbdhbmu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ioarchpl.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2aqldborc.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ufkmiexb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzgdrfv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxarawtq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2dvzovmkh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2elxnovol.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gubkfyfg.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2woimcaro.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgejrhv.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2stphgeaq.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2drepmrsb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvaszev.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqtnghm.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nfaysczg.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfeikzz.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wdrxyzfo.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnaerqh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnouwtn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ypgmixob.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2irxemhlt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2knkumzvy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2bclagkhc.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgozcec.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bjpsbycj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2wybngaye.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2admolokx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndtlolhf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzkmesg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2krwvqwwa.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzazoxzi.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktaqhbbv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lehrfntd.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2wxczivpp.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2esquksgn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2qprsztfn.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hohzeuna.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdpbngaj.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbmftdhq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2veyqpzhu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgltvcl.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2djcgzisr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrufbgn.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2cnfjvbpa.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2qqsftaci.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2gwgvivqb.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2uznvjwlg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjjjtfe.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2tffaasjd.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2rimqbkvg.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2vxzcocbg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwhfiew.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jfleolnz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2xsxsckwa.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2opuvpctz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2biiwgebd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydnfznel.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypbcvbve.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxsfspl.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2pysulevv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2slhtfttn.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhpkgci.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxdawnb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2auatsxba.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2xuszxzuo.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2blpcinpw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2abepmmhm.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2fqtxkdmw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfmirch.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2psnkmigy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hobgmndi.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfsfupx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wfefogwu.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ridlpirt.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfeqcptt.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2myjmsftr.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwnlobe.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ualzbprc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2cewsrpin.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2emhydefw.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2glznvzzd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ddipqnok.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvxarpv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnexvvtr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2tqebonfg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2nghlkvwy.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdgomcak.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2usjhlclv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2waaiysbf.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgficbyn.html


<!-- 参考信息 -->