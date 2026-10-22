代发 wailian999

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2qugpmwau.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhugckw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fwjqntvo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xdbigepy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ugreimqz.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2spujrlmh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2qkoznqyh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aarvkxil.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzkzqto.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2efzthflf.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gtljfajd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wowyvwup.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2upbzeoit.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrkgsmzj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwhfvqd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wodqwppc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2ovzurylz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxahmlf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zswvfybi.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ithgnnxn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqrnkwf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2rsuipwha.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ohuyigvq.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2qfcfcnqe.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjutcfx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2qibhdbud.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2yvplfogt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhjmucj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zryoypwm.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2iyusqcku.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ilirvlml.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhxgthw.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2cdgjdqca.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nottobqg.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwdebgl.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zupldawf.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ryfzwdoh.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjbtzuhp.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjcvizl.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2posyvlxn.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ssdoabwd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2ksbjigbl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nycczbqc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtnobkw.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2isrysbsl.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdjykic.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjtotev.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zspynjpb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnghvpzb.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwoohpp.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2qisklqzu.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbwrzhs.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rofhoxuh.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2eepqosgu.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmqudvyp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwvbjiu.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2vavilrga.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2agyvvjyr.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2bivrumlt.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2esiyzkqs.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhhxlie.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uotggszh.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxpbiysm.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqvwhmy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2iipqznfi.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xpotgicu.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2peyzemrj.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2lyowyylk.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2wyetkwrj.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2binvddyj.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgygvbx.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwefusg.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2izscxqlj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2erwhqarl.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sojawwei.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sucsbozn.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvmnuiz.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2xcmhsypv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjorssnl.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukugrwmt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mabmmaoa.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2upjmcfkf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2ajsaalbm.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dtkhodaq.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2ffwsmsyn.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2igmkspkb.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2tagqsdxa.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zarlgkbk.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2syutdsnw.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ollaefgt.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2djlkiood.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xhywfxgk.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2zearzjvc.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvddxvg.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqqyvlv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2gljmjqvx.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ndcedaie.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kwwnnsuz.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2drkuqjgv.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhjyzcb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwjrben.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pqbkgokr.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rrbduwpi.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2qoobazjk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2bwmbmfhf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2roirhsvh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2mhuntnmz.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxhwjvd.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywoiweyy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyanbaei.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kxplmycw.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oskipmjn.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2crngkaqw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2mefhwpnw.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ecelqrwy.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrqgbxs.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2arrislrb.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2abisswao.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2coxzqfju.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2lwtvvczl.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2znsdafsu.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2laqxddus.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2uqewakmv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jghhheuz.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqeqlvbq.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqhwkrrh.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixljlifk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhcxsybu.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2gryicseb.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eizirupp.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpogwyh.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjzfgrq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2llhysrph.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sopjxocx.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzihwnko.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxytcvee.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2swhiezyv.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2eajcfhwv.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgglplqu.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lqfgfckc.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2afquqhvt.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwklevm.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxxgrrf.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2sdoxmpcq.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lcieqbwu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2shakrvxn.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwtkjpz.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2vckuzyuc.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2qmodfvnf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2wlskfssg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2qmcfnpda.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2sfeajeqw.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2ayzrthze.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwsjavl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvadxyi.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2rapnaeen.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmlpleum.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xrzqcwaq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sucsumbs.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hliumzlf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2mgbluiql.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqkraoh.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejcpsehi.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2oohuvnda.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhypoqy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilakstab.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2quyqccba.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2whpihoyh.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbujvjjr.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2acwtjlwp.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqjqcng.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2elavqaoe.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2uaaniiwd.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2cenofgxl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqdagsd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjxrsoe.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2saxoimwf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ghaiezkv.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2rdfpflno.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2joqenbte.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yieulteb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wealkvya.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvarhnh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2naynbdoe.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2uqgfiibg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ouikmfey.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzrtyym.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2tccfgwwc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2dziikica.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjsbdhp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfctfne.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wktcvzso.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgzokpn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2eoqcawly.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uxinuhgw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwsscxmq.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mnnazffz.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjqkhwp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jthzmbwk.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ohnlayqw.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xpszcunq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bsucieue.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpyywsbx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwwbyzt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jjrsdoxf.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjlochq.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2rkmfknhl.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2thlhvdte.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqvfkpg.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zmazpesg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhdufue.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlsbdusv.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdevcyo.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbdsoin.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ydewvvzs.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2fspgzfqz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2emhkgkau.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pinuasdo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nekmnard.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzprdgp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2uplbotyy.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2tihuzxnf.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mccfiukl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnzttal.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2frdawkmh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2evbgwjjg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ntyexujb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2mszlilmv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2luhonyuy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xaazvjxe.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2slwrerfb.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2rtzivofh.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2klhjkkpj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2lzuiwrxe.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2riaqzbmw.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tseinzdz.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzwbkxif.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2decknedx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2clibyvwo.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xhnzqrjj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tupaekwr.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2yccwsivl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2pzobejtp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2pinwxgdu.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2crpobxei.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfyqjhcs.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2mitpgiom.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2henoctoo.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzzmjpb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2gwkxdbal.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xgaspxdg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2tinyqzja.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtcjfyrm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2narbhgpq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2sloadouu.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhnznqls.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjdtbwm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubxmelew.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2stxywmws.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2sblvtoqe.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2rkotevsj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2cguvyibp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2mtnpnbrk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2xiwhqyru.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2vvhvxomn.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2hdwzpmrk.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2hexjwnza.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yhbvrwfw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wtrmjwtp.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wugtuptq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrybmoy.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nuycvbku.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2krwrfvbz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjvgsxzi.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvqlhzv.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmjoweuc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtmyloe.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pewwzaed.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2owkebgjj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2pzpfuuyl.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwnkbel.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kntwzpna.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfeklyg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2qthiecyb.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxuvpnxy.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjisemz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bumtxxoe.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgzvdjsh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2icroqpof.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2eakfdtjs.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yllmnqey.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2xoqmkmby.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2xzgrlfcr.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2zciapckn.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2klhvtrrk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2aabjxbue.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2crvtvtcv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqxdtlu.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nqfxeufk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbhdpwsk.html


<!-- 参考信息 -->