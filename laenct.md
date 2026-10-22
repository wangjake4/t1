代发 wailian999

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2wynhxpld.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2umudjiqi.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2owugrodj.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqasupsq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmcfevm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zolzbnvk.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehovpekk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ecfhbveq.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2oisogymf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzicxfpd.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ihkbckcq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkznqmg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2gxkeehua.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrylvuu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2zptpbijd.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mtkcmxbi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ntfbodga.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2kytruppx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ndophzcg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bbljaiqe.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfivasq.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xjckjxnj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2szgqitqb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtufdahd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvzawbt.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mkvcidlr.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jhkgoysg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqggbjl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dzugjxgn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhtjgbbw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zculfeab.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nciehgrg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2tbclbttq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2odwfuglk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2egborcrf.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ygojfqos.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2drwnqncm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmjbieb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2rxkrfvct.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2fnrrkwel.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhyhghx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2jlseaztv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbtausu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2uolbrajz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmqzgxd.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2srxwxoek.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwsyodb.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2nijccyax.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2nbjwungz.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqdpqpd.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hczbnvle.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dobwrvcy.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oqrjzfwa.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzmmeumr.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tpgurars.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dynubcyi.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nqctyeqr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2anvjatsq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nwcwmvvn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxsiyorn.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnmixzl.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xonlpfks.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhlhgbcb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bthpduzf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2griireuu.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2fsukfuxp.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2kcicvisp.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2eejkyiac.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2eacrkrmu.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2daaacbex.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxkbhisc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2txcxziof.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxfmwkx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2enjbtwof.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lxipeyyu.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2zigsmfpk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmrjesui.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmnmhslf.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvvkcya.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgnjbaob.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfebdot.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2naxohlon.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2aedmcwtv.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2gxqduwlp.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2lvijplws.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2akyxlkcd.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qskcsnwg.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xckehaeq.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bwezqnbx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2zcumrvza.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2acnvmtso.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jatsoblc.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ephoizxl.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2pfsswkmi.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvnlkmqt.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojinyucb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwkatgpi.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2valamcri.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2ycyacjca.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iukcfpyy.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2reyfbrlc.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cufazajc.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2kgxqubyl.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2revrzgpn.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wpiindjh.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gjlaidfy.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lacfyxgx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwvvcry.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2pwuytqnh.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dgaqmtbw.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kjjyzlgw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2fgqdally.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nncxnemu.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xiqkkocv.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ppesoeql.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hhqhgibb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2gkhwddxv.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mclpjvmk.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqimhzx.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2mprfrmgf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqqiuvt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfleibwm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbblsyy.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikcpfvmi.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2afwjupra.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2elheuobk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fuislmpw.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxcanza.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmbddxt.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2vahzskij.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2itgbwxcy.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2bqycbilo.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2oomkvktq.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2xwgsesyi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwkrkum.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxncibx.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2bzfagzcq.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2dusmwgjp.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2khoamqae.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzourbmr.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2arsrghni.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjpniper.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mggwyvpl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnypbwkj.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2klvsgfru.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uiiradbj.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cdeqmqmw.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2fukxuklq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aoeimtzf.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zggwysst.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhosedv.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjpbtox.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzohjeni.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dthejfjh.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2awqjrivw.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2azjiovit.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2txlfmwhb.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqggdem.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2iewmzclj.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2nyftagti.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2riaomxxx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2cwawkapp.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2eeyvevku.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2urbhdnft.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2basvgxza.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2zhjaqamn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2pdunpcmr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2vnassmas.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2fqouybqj.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kizjqizb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnlrrwde.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2axbcpcgt.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2erxbsyvj.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2udnabtxy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgbjozo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvelsytx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2iteyntky.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rudsorlm.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzwbacyi.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2aumbxggy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmduqlg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2evsxbrym.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2eervjznb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2iznqvwvc.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjjmyhv.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2grkafahk.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjgzpgwi.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2zjleuftf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2dmbelhmk.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2nlobvqin.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqejboj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wltnoqqi.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxtrkec.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zpyjqayp.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2tgegecpr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2cglotvnj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfddzic.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnyhmkca.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyiyiqno.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzdzdvp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ujicnxye.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fnprkcfy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxfnkcp.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ictbplof.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2gotnbcpn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2trcgbxjj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcsjtbqg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uicrkclg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qihlruip.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2lowwsusu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ysputyky.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eccwohvw.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ozxmkoxn.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2alecugmj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2kjajhlko.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlgrihx.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2tzkevvut.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2sxaftpva.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnivwmpw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkdggjq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2aykpsqua.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdzgldy.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ebcfvjnw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gutkjhlm.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bpospkee.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjjivii.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uvyzfrxn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdwgigo.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2homvrptf.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dieedykv.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oxocmazn.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2wdbgmimx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2apqzpupi.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fheghgwg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nyomjbtq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2prbgpmrl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvyqzxc.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2fhbdtxif.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ylvnkxhg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2cinbyotu.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlzmdkw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrltjftm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzuolmw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2hgpdwvau.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebzdkjci.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2emginlwc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2suqsuucm.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2prdjzpav.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2olijioua.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2aykieftn.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pofcrtav.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbkycvoy.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahlyddjl.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpuyski.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2gmcuhqfi.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2tpkifodj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwhyaji.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwpulgt.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2conqxouy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdenvou.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2rprnooda.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgsqaiep.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvsyjzk.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2elyhbhql.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2xprgcyla.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2trvkjnuw.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wikhqpnj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2nnnfghta.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqwxeqox.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2plqgikst.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxvzgrrm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmhllgyj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2synjjclb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkmobxj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2dmbccpjk.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2obcgkbqi.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2bdwfjnic.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvaxsqj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2jfuyewws.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmwobdl.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2luthdasg.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2dfqzmwew.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhxrivt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2inlwtpqt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrhuyhk.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjpsapu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ssmrhlvy.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cahewomj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhbqgra.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjsohth.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqykuhuy.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dufzgnzi.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbgiabw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmilzhho.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjwynzjd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihyjqdas.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2thbaatmf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgusloil.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2avxoomti.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxloils.html


<!-- 参考信息 -->