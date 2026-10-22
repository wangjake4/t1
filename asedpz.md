代发 wailian999

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2odflrops.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hliyldfe.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2rjumrdnd.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvsuoxyb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2daplucxv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlouohr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqazlao.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mhtuigpu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sacwpcnk.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrqcveo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2oniatnts.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxnngdn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2elzfcamm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tgokuktc.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmdfuzl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yiaywlmf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ggodwplo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wduaiztu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lzfhpvgx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2secfqihd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2jzgrebkk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kayemzwd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qaumiccq.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2yxlnugug.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyssiktw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2odcovqsb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2zefgqngx.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhgwuob.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtiftcb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2rcnxtmxf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2utmszqec.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ptagsyoz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtvvepr.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ekziemek.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fvszmlkc.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2scpgjlxe.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2btxsyont.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sltjxxqc.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qidyvwog.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2enxeczrs.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ymectlkw.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocnfpttm.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jjukmkyl.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvakxyf.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wrbmwgbn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2itmznirg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqnmmew.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqmxkju.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvfzkop.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhkeqcsr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2evpnxvyr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjvxcjj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdpsdswt.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmhiosf.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2sogzxezx.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xzthbyhx.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2slysodfw.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2nmugaxzs.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mruevkzv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2frltkrgx.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2qcdzwsnb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwhqpri.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mbevfdno.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2jkglvrcr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yngetlbz.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2amawmbfo.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytglidar.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmhcyvf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2aprowlzp.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ugrnqszx.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2khasnyeb.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxpijvj.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxgicrx.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxgqliu.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zmepwrcu.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgqvshh.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ikeovgln.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzecaqg.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2obyqowbk.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hoslbvml.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xtwimukf.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2laldzeax.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2joenjmlz.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxgcvxd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jthuedxf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2triwmmlb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjmcqdq.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxeivug.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvpbmrc.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vyartfgj.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2hyskmmem.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2yapxnrsf.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jvgmzrzp.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrjkduh.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qramqwfz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2deauuaph.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2fjslrhee.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ypsspzjy.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2weirargf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2httwfbpz.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqdmbgy.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2usaoeigk.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eccoyfpj.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oaeazcfm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ugvhyiin.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vzrjwigm.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xjmnwxfj.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2rgaiqqah.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2yufikrsz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hatuffuw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2fezbjutv.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nercijkg.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2walggymw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pemaxeda.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oppigoeq.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2liinaarp.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2gwjbrxbk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2eaarxklf.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2umqhntth.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfsdhyx.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvdwgln.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2ykrxqgaq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2tqtaauwa.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2rriiykzy.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2dexsddfd.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqduxom.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2xcvcobhr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqgsjwn.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdydxbky.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtlaprrf.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsiaunfv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvdsbcx.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2yxibaxpv.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycytpduh.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2utbkvwzr.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2dspvxqxk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkzhrxv.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmawfxjc.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uthqetfq.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2waqfrllj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyiqapws.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjkpafl.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2elbgyfjy.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxensbg.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2jadihzgs.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2whluuoqo.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkpwjim.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxitagm.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ingsgwug.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqrjovt.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2srpscole.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2myterhzu.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2jiqymwuu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2smtwuzie.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2tifdzmrf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2fbreylsq.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2huobqvsa.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yrxitgmc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlzvkjkk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2rrodbyxs.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejukjrth.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qalmahsz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rnqgfpqc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2btdxaims.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2cnoyasxi.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqxejzpd.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnucdfyu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2aejvqcka.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2xfytdvnu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2prcbgghd.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqxwclx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2exaxbxzv.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2bwttpigw.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebdxoixr.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlchfqg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2hibiuxlk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2molwsbrs.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2avhowqdl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2dlxyrlok.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkpeoot.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2aedejewl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rjuwbwhw.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2cekaxhtv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfziehyy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdwlbtq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtpwuwos.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbdygra.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwuzxgjf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbxlbgm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yfyyzwue.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2adjhmscv.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2psacdnwi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2lsnypwhr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2juugktrl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwlpmxr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubabkmvq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2efhxjbkh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2dszxqpkf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdbnyfz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfkjpngi.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ncarnvid.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2icuzppjk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqwfmus.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhyxmpm.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jijayris.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2usbxfsmw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwhkqyqw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2inmdlorq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2otvapvjp.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2busljymd.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ghpsfdrh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2afebjkiw.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2smbdyyew.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jzrtypsd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvzsipe.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyaokyvv.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rylxfodr.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rrrtmzbb.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrvzlsx.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgwdsgo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqlgwpg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bwforwhk.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uuuognxr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdseqdl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlolipra.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2dxfocopu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jagcqhxt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2pxaneeri.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2dmgeyejf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2cehielrw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2lpbhyalo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmxauio.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhyhtfak.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyurwont.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nughxqpl.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2jevhlawc.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2evxoovbw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2aekbgfsl.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbhyhhqf.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlveyco.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcfkqrgc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2klqdovsu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2fzdpacfp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2mjlhjcrl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2oapmkryk.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2wnvihjdk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzfktth.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2rthduibj.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2zwnqbvgx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2hucbkfkt.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqhkiyn.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2tzayapzk.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2wlznzwwc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2mfscuara.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ifrypyeg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2rkyyfvbe.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbeziue.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzpnxtkp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2slronwdf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fanoneyx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xbmvsjqw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2feafnuzk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2edewoefu.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2yytncoew.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2ahagnynw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2rdorbzwy.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2lnrkffme.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2hehuyihu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2toxsjtcd.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2czommsbn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftcmyttj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2eivduhzy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbrxblt.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wqartsnx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2euiurktb.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ihowsbqo.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozirqsxi.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mubmcuao.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdudnwi.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dybodaqb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2zwrtoacf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lelmdgse.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2yejxnzvj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cbkopwpw.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxqkzle.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2euzbgror.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2msbputcp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2jzergxpt.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntidxxql.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2aylwktkg.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2udrgaine.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwurdrt.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oeiylpuy.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2syuedizk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpthyze.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2iomnjllu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ptphfvew.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2uegvjvaa.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2saurxvoa.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2uztwwocc.html


<!-- 参考信息 -->