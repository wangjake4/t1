代发 wailian999

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwhjwcd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecywcazd.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2chresmbg.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jrdikuyp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqlpiqha.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2cxynccsa.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rrktrkqb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rclxjwfp.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2mdhykrkc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fyeefpyx.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2koghodeg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2pgujcknf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2yxzexbcg.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lmrzmfqi.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2vubrhigy.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmoamceq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2leuftpmr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2ppyprtmt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fpofqyou.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zbsuhspd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fruaylww.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixtwdixl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2oadthnzz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2klmrxajg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvbkmnw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2elzlltve.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qhoufjxs.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wdmmpqlg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zvsvlzqt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kmcwrpgo.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbdpjve.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjmmlnw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2rkspmzrd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dbfdvpit.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrzhigsk.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2jxsomajk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqgyrqa.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2cvtxjayo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpzdfpl.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2xybtlokm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxlwbxs.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2blgdwdao.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2mvroyxly.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbbxowq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wzidbiiw.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2rdeezslo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xcynqriv.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2qjahuyal.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2chvkphpq.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kzajjkus.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xoqyxlom.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zobvxwnq.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ksgvaeva.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbxwgqcn.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nlltlypx.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kghcfptq.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ptycwqoh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2krsupvpa.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aqwozdfv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxoykoyz.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bshzdljp.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldpcyiww.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlklgwae.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqnwgfx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcpsaddo.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bigbeayv.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2izdlmaqi.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bohenlnc.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxddpqv.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xbplzptm.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcfwcspu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrgscfu.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2xqirdkeb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtyphcq.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmomxfg.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2mzloxopy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzvzslq.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iakwllkc.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzpmiyfc.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2drixowjz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2iaphgqep.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mpejwton.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqkjsrij.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2bsotriti.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2svqjjrdq.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lhiuxrqp.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aaurqicq.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbyhubc.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sxeccdph.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2hietzqkx.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzucnrq.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfjtmad.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qzortjxu.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2nemwrraw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmvpedh.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2khwsovzn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qoqmjsad.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2adqfbdsh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2zzhfwuop.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvpeulp.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2jldwelta.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2damfyzuj.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2nezrwrkn.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vujgsdba.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xcezndti.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tmzccxsl.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxppabk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2unrtpixq.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2rvuarlbu.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2frzlnzys.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2mmhrlkan.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2pjpinitq.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2umdapnbc.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mbavehth.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tnqvehjv.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xanxooqn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ttvlfyso.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2etbjevon.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eaenqong.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2hglkvwad.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2xzolrpnj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbkicuv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2mnaqndge.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmmaqzgi.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uigcmomo.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmjllkt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xlpyooya.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fayjpwgz.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2hsqaemzb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2kkckbavy.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2morntshc.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwrzgws.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2fzgbvmik.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2osgxfujc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2bqfkjaex.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhbiorq.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfayvqs.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2rnidhikh.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ydovxldq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2drncdsgb.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2itwesbja.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bawohryw.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwgzftu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2czgtudpa.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2rpsryydd.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnedxew.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rsszznlv.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2typzttuw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmomddvo.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjrttumy.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvihityk.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwljaslw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnnwksgm.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wluqqnbb.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xniyelmm.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjtivgl.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2amhkyzrn.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjixhgj.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2awsjxwwb.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lgknerrp.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rkovvdpa.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2mejtoauf.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtmivfu.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2aupegrgc.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdzhnrc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2llieowuf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2ukovlpvo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmwdfoz.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjfjwul.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bufowdje.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2svgmpzvz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmbjqnr.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkytcgzn.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmmsazh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gsijhlhb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtvkwxk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2lociktzd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzhbipwx.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwyuvuni.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2isihzajp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2druvoiov.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqxrxoi.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pplsrbne.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2vszvimdv.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkirtvzx.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwgtaxjo.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2oonbgmqi.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2cotmjkgs.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2eoewostz.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqqbqux.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2qeugcjpt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zucbsrgt.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjpkgqn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xsslmuwj.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2fewegcpq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2isshjvyu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fobfbcll.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqfjjfe.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqcfcqix.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2atbovvwu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2irdlggcz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nzmscspt.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2grjiaqjt.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2conrbzbs.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2hyustmym.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbwjegq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbiwkhde.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhmeuov.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2alqrrhbo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2cezfsbsw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rhucgmgo.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kufnjeig.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjklxqc.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2pthxtcqj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fomyvjwp.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fgyxbpfc.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbgulwy.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2cwtkdhdu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2nawtpyir.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2qymbzjix.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qqcsjmgp.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jhicczur.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2wjkenmux.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwghvir.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zfmqeidu.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2akmxcfvr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xafzkvpo.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwfnhfm.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tdomunbz.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2crkwqynt.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2noyikdlp.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvfwolt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ciixpdwk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mzmyhpjw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dgirkune.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdntmjg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2agbvbkzt.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgadyad.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xosncdwx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2luceamhh.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2fbyuwssh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2lstzptyw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2pxtrdwzr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2yomkqeub.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgpaevhn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhaqefua.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvcugfm.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ojvkgzdr.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2btazqszm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2ldgsnvpm.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xppxlctx.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztxezzpp.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxkofehx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2kkkntoxo.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qgspnsol.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2avahuiqr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftyhjmay.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjdkkrg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2khsqebol.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2xwcsrnhl.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2gtwmsvnc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjbvgrze.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjooecb.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2rubkjxso.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2kcolzkoz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2sndffdnk.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2erybfpko.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2hxiuyxat.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcuacngn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2nyglwfed.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtfkeny.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzgoyeno.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2puoqdwss.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghsvafpf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2halatgpv.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtzzing.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2wttrlxtf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjdznsg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2hrskdguh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcgucyr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2yojablwe.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2rsyvsicb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2feybtxmb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbfkueb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aaiwfcza.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nnnfamsu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjghixo.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yoasuyno.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnthwnb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zharggkq.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtxantu.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjikrsfh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2ctcixzca.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmnwcarp.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbyrfqz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvoqukcw.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wbuijeft.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zupvpvxd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2vlruhadh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2gpmcgyjg.html


<!-- 参考信息 -->