代发 wailian999

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2wfglxrpo.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2ypugqrpf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrwwsgy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2psnyeyjx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbcdpoo.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnvbzhq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2rmikmtfl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qgdvicdt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nynkxjom.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mszntxcm.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpdlprk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgocxzhe.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uikteyol.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dczppcab.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgapgspq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2techthtb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmzgnlg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mrswfxls.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2avksrssi.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2occchqsk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2usfvtwip.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2uebfzgkz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2obxsveih.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfskzei.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2vqsyurfl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2jylbcfpl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2kezvchaz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2byydmcrz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmfqwyx.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ockfoskk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2efgizaui.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2mxffxpnu.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ekimayns.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2idthmbyr.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjbjvhl.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxdtkan.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2alcjfztc.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwsacdm.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtrrxbn.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ujeyutek.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fjukhqtr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2tjviomai.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zcpiucql.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfqvrbgg.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjunaqu.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhfdbqj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjyusev.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2acnaaazp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtyomblr.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvvlqsd.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2xfofgboh.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbhbbgr.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jewkoakw.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2cgyavdoq.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2esiaezfp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2kihmbobx.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2lwkvqqfq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqwbltj.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qnalrtwi.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwbfjsc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrvyqrt.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2joyxbcko.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbkfmkhi.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cafjftyl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2cluknkrj.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uevvodpr.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2msndknhw.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ekgkbqzd.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2dqdfybus.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mgcfwfkk.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jcetgjfj.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zlksxzpd.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jvsulnbz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2gonoazxg.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2etqabpsx.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ybofpsnx.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gahuejbq.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2taxsvola.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2svqnxily.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2thvvqlfl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxjohqbc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecwtasiy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2knnthvuw.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xgovmlwr.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2vefzuyxq.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2afqcshiu.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2opdyarbt.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvlsjub.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgfhiot.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqcpjis.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xnleavsa.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrirnqb.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2vkgpmrma.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxkfhge.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2lpiyxwgj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrfwdud.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2czzxfdnx.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxypesx.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmhlpch.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxkznez.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2yyycumbk.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2spojbizo.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dddlitav.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2obbvaago.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2xsfrzcru.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrgdqpn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvuguvs.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2elxgdokn.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujxrfvuy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2znucjdua.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yiwjqnrc.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvmoyjc.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2niucotiw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2jrlaoxfv.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2sakfwoah.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2plgmdvxb.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2oxytvsqa.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfmxygv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2yntfgmle.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2unezzwdm.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2uxwazjob.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2dsasnroa.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2dmcgjiez.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2driluzkl.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdygcsw.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwpqoxi.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqvoljnn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbjwgqq.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtlygyx.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2igqpxnpu.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tawluaun.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2jbnhfbym.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvtmbfhk.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cukpwelv.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmuzrqbs.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wapazniw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmaikli.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqyssog.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2punthwvn.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uvctqdme.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcewpjrq.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zhsfduzp.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmjveqm.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2htcwhsrs.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqopipo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wspwcvru.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2qeodhjcc.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2hlcliupc.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2kknxwzed.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2yrhsehuc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgsbtpw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2hbrbblzo.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2veilmwoh.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqcaqdl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2opdxdrqf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2kxiwaezq.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2qsfdbbce.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgyotwd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kitlqqnf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjnbdltz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2sxbdxwbp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjlbred.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2apbsspma.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtovlqzf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2qnfixqhq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdgkfwxl.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vetomfiw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2jwltogow.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjaoqpzj.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2clgrrevm.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtuwqdsz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2swbtthbg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2fiygaorx.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2czvhljci.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhvzcya.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bisufsjr.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2snihtuul.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wreunpxb.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhehuqq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzorfzxp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzkrfcth.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mainfedi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcsaocqe.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2afuzgetm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2pahqjbsd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oytcwswi.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mncgnuzd.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2skdbxsry.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2bxakhhba.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnzjaonc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2flxvpcjq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvmovfq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fotfulru.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ukzecqck.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tarypzqu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejhzjtdd.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2oabulbmt.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2dgvboisy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2axqmmrmd.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2uilgurvy.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjnumrv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mkijbjof.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdcrwyu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2hmiugzjs.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xewchkrq.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lwpagxrr.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2crzxpcse.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xtfxhljj.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2srukvwhf.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2omjermaw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qwygynaq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqyqenui.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzqndhc.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzalusz.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pscsrsdn.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2gabexmhi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wjroplky.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xmiqpikm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvopvdi.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2werzrzhx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyscleod.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2pjrccmmh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qjixlhib.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2jkcfioll.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2fobaafoq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgtdzwf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2lnnwjiuj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2hbieknhl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2mooiisrc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqyqedqx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tztovwya.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2litbbpnf.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvtuhnq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2uscenojg.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ooteovdn.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2aissxwmy.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdrceam.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2nblcqgde.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2gblrwahp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2taolkidk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqaydqwa.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2xqflbvzu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2zalwokkz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2ircdkmvc.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2baiihwwg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2yuiwiswi.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwdnqqw.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkinirb.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2cwgldyxv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqbihkf.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zftrjepi.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2edpppdwf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2xevukmnx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2abkdcofg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2amfnnhrr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2inzznhco.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lyqgalkc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2knsvhtkk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zidycmcd.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2fmskhmao.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2ujnwtanf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2erehrlqs.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2ywrmkfoa.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2txwagtnp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2xoufdtpv.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2zhgzcbfc.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2sceaclko.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dsnzczdz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwwcxcg.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbsumau.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjaojrb.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2emsjwfci.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uluidgtt.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxxkqqv.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ziplkqmo.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgisaqyj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxpzovc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2oztwozjo.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcunpvom.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2kjpeothh.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vtknzcep.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmdgmny.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ersljbyc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2imzscskz.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrpyknl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtvwnmb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgqcrqww.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfflvnr.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2broeiakd.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2nmsaetmb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbgobqmn.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2lcovqrng.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2paypgjam.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2idlmhule.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2oillmyek.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2xwnqqpqh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmchifi.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2cylzymln.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tnekkpiz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2oasxsikw.html


<!-- 参考信息 -->