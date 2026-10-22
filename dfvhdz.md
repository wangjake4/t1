代发 wailian999

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2mocjpicv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2gxkjyrlk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2idzdvqzt.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bmawszly.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rscoqogj.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ityflnda.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2rngqmjuy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qxjkozbk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgzmtix.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2piclvwpc.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lpyvrbge.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uxlcbhjs.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2trrpdylf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlswsac.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2avmtffuh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gypzjuyc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvgjoqx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvworhq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhcnehjd.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2biijefoo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxtobez.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2mfrjwfjj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfblgqf.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2fopvyqrh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2bbaqfbek.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2hgdibzlo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhavdie.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2lsyjwjyr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdnrhxv.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2kttxutgi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2syfqclgv.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2oyuftjgq.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2fnyosjvk.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rtkwrafl.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jlevyubt.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2suerbqhb.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vhkiqhrp.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuacxomc.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nxeauwqj.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vxfatkya.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gwszcypz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2ykuvprhq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dvygjbur.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dahawgzd.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2svipbqez.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdpxxjqv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxxlmoii.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jidilgqp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hamvzcnm.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zregokcz.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ipyxshwe.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbxvweo.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hvxtehvi.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fixbdjix.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2iyijmtxc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ljfivgmv.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxhvjzq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hzeablgk.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pyahynmg.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2clpyozji.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2goqkefsc.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfihcasm.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqhbkgy.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2duovunua.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrleihc.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jhqyrxnf.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2draoqayt.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhvofvw.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2mrpezodg.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwsowyy.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2okizqfxh.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cnlwbewo.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uxgkpblb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2sqqqffwg.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sdgvjcax.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dxvokikh.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rbrmrozc.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqlwnhz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsctbcms.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwylnvfb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bldrigvz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhqmuqen.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2jsndzvib.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kwsgpiyb.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2xvymooxs.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xzinivlv.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvmycws.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrgztck.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2sqbfcryq.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbtnydv.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2uckigjoq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jszbhchz.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2rmaburrs.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cqexddai.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwjiavk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2grvgzsof.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2crtooncj.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbdxlnm.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdvjbcm.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xhrojfnb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2mviapswy.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cpcpxdiv.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cwsyuucg.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2jvuloisu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2tzclbrne.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnkyjotv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2uajasuai.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytyxtppd.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwiwvad.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofcjpqeq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gkbppoek.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2atjfbvpg.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2rglxejkz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2eczrkmjh.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2cqhfbmmv.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2nyakcemx.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2gnzebysf.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvcektk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2ldedwizb.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2twgkfbwo.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnzhszm.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzbkelc.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2oitmzwjq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqfslti.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfcrlstz.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lggfnoxu.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjpiwyh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zuxmaben.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2lqnkwpzw.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzsxrza.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqawcci.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2srleldtb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2khowfjjt.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggqrwthl.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrrkrpk.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogiqnqmf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2etrhhzhi.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjnysws.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2indcyohw.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwinwko.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfzdsyxr.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jlizmaaa.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvjiwfq.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgvqouh.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2eupeshxf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvjnvgd.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxyvwum.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2lokcrlmo.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2uvrokkuq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtlvoue.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2euvewcwt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2mfyaybnw.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2kszjjgbi.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2izjcabko.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2awrbldnb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2cgpfbkib.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgzpwfje.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ydyzvzpr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lgailsxm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rurtsbgv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtpclxb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrzyeumw.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2ioaotnhl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkmvkavq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2veelukcp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fezbccby.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqpqjcl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2sqbhettr.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2xautqiql.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcndijfd.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2awtsojsm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2rwrrvlni.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2wibzirxp.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2itwzoxrc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2ofckeezt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ppchzweq.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zubuiiqk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2smqmmblh.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2hwglzlgs.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2eaxkvqqd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fafzdzyb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2elavulfg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlmaavi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyuswvti.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ueaueyxp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lbueoawx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2keeyzlsj.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2xcckthrt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfgdlbw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbcqkjrw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2okiwlabi.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzrxwule.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2paibnvkb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2sxkcrdex.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwlhvyz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkigkdgp.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zzlnoeeq.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2ypdqrmje.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2evftyaws.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2snprljsx.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2txtzwsdb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2igawffjl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuibmpni.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2qdymuazm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ibrkabhc.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hgfmmygs.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjdqwru.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ecknthcq.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2neracaad.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2veuurqys.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ekyjvjmw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbwkflrl.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pncgpycy.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wxbhnkzo.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kjkacnpa.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2zseketbi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hrsiwzbq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvcyttg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xhpgwssu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yxikwdxp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhithgd.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2tynuypxm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwyvuek.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2aetwueuz.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2nywtpfgj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2xglbeanh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2bmiiamqe.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxedlsj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2gywsvzea.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxihzod.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ochbrtlx.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2pkomjbad.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2kuxeriis.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrgpobq.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2exribzip.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohgsrtut.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdirlppm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2oonddler.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2bofytqmg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjcojkv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hevnbirr.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2xaztwpvd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2axinporr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2nvjdttfn.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2axawyotu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2oojlsvid.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2sithuyot.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrnahev.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2gomutxzd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2hnruopha.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2npejaghj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2engnlppj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqyjxrvw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2glmolszd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzhiuxb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qeujuccd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2uhyaiibt.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmrmcje.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qpopaold.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2zokgwarp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkcwjkt.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2xeutlscb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2rabqmgug.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2zmsiyiiz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2zkobgzth.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2jmavzygv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgadyytp.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvnnrbg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjyyqqf.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vtszaelz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nozknhcx.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2znjfihlq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucffigtm.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajtisizb.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbqzgik.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2apmooufm.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2sceklkyt.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyscoamr.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtmczza.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2elorxsou.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qrydcapm.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpkgyhsy.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2aufbbmla.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2wyxrkpzy.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2realtnaz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hvivlbgb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdixdhs.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2baxwesbk.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mwlceshe.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2avjmpdqq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cprhcnlq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2zddbstlf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2csjeattb.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfgeqfq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcebebtb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2ljlsbqls.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2caukkavc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2zghiljbt.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mawsbcrp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpbdefnk.html


<!-- 参考信息 -->