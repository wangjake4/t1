代发 wailian999

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebnrcruv.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2offahcvu.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzdkqcoq.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2azsuxtlp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2tiluswky.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ifspqdnm.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqexsrt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxrobtmn.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbpmvos.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjknxan.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lifcwrie.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2voakhhus.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2hdtllbgq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhngeua.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2meigzcmc.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dcpafwby.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2embinkme.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2uiubxxfb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqrqjfo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgjkcwj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwbhismv.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2veqonxbc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2ltqzaqlq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbbuqyy.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dzrllndl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvowmup.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvxxbnx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzqpreu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgdrott.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2abplbigp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhghbrwt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2djlmufwi.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2iackvfpi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvrokne.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrkfqdly.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2hjdkivtu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2glqrwfmu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2qjgvkeqr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ecatzovx.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2xidziwak.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2yxczddew.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ptlcwrmo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2inmrqpmj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2guxjznoc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ctpawbge.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2dlniowpr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbhcxqj.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2vyfsjxcv.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkqlazq.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dwbxqbzd.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uobkxgna.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkektzyr.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2knysknbe.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtklwlbf.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iqahnsgm.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhtqdhm.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vtylomja.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2oglbwnoa.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2estsgyuc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibkbjzzg.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmdnhsm.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2shysqvff.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwaqedid.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xitifmjy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2haaesneo.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2shckxlyb.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2bpjldaih.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2nxykvdoq.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdfmnlz.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbhkewd.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzsynbqz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2nfvdwnjd.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2tfwazszu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2khvpyjoo.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2svzvobcp.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2lmhgsamz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2onizjpvs.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fipltaoa.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbcnnhxa.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2keebjufn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2cevnmapv.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mizbccij.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2voespkmp.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2mlucwksp.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2judnzmzo.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdnxhtq.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qytteizw.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rirmyyaz.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zedipxwi.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2emhthwyz.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vwgyxkcw.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtxnzvy.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dwgdehjf.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2wudxqqse.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2prkfbnup.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmuvvcf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2glgeyavx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvmegplt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2bcyhybjz.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmvnhhp.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2esefgump.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ogahnynf.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2lighelln.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mnihpwja.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2airarxxp.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mregleyv.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hgpntxnv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zvqsrsst.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2dltfykxs.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xxydiapx.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzctpbv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2pwmlxvvc.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qszspzee.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2knypyagd.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfsmhtq.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ltqjufup.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxfxapl.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jxlgoaco.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ctyoybji.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2uqlgvbaq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2gyyswduj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2inxifkuu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2evcvvvof.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmgqrfy.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghsrpfnc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbehjwhe.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nxbkmgnu.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2webpfdvr.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2snobjkbs.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2jtihqimv.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhzgciw.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2lqoqkbpv.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ftcgdlkd.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2uaecdgwj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2ixziiqlo.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdxvtcw.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2dcfcqjxj.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2jzaiatgz.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwthrqk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2keumcvmb.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxrgasrm.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqllemen.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbibmzys.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2evmrtcau.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2pbgmtrfv.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qivofwaz.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pdctzhms.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2mcwtqqms.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdbvefq.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aonxuleq.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sophdzvx.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwbuhen.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjctiplx.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2eykrsdik.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzrpipe.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtspdis.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2efaigtlh.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qbmoffor.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zndpedkp.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2sudqwpff.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xovfmajy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2sbhorbru.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2iipoebnu.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2skzrvwta.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2umwjkdxj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbfpeav.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjawlfh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2hvdxbokq.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2imgtdabv.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdgcdzp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyceodmp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2ykwielbi.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2hyimqcmt.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bfpiqtia.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjfcdvf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aklfberk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqtotkl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtmaahk.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwscyzdf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjpwduj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2waspywex.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzlhuco.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqkasvr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2azbydpjj.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnypdhyb.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqflnds.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnyxupc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2gbisywto.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxayrjd.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2lrnlvyku.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2yhrhdifm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yodeiaog.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jthnqjvv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pfoyqzej.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2lgpqplgm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmuqnzkm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqlmqry.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2towwqccq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnibzwkp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fackabza.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2oihmjkog.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kxougrvd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjsifvfu.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2szkaclua.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2tyhbwtnc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zugfnmds.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2snhekfxz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2axdasiss.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvjnswat.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2swqeoajs.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zeuqguor.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmsmnoqz.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2prmnpqam.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqzeelr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bedrnpcm.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jreoknnm.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdepabi.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2rtvzulwk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckcsjahc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2lvcyccng.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2egmlwlee.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fjvubenv.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2njbaeklj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ztlqnjdh.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gnntldwz.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2erfsbrdo.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qdgsokdd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgyiubze.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iigisyxm.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2skmojoic.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sphcvmde.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2fyukmtpv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tfnmtyzq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tixrrpxb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gbrjwhpu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zngogrcv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2exftarog.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2dbrdqedi.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lflrurne.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2suvrgpzm.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2wuigslqo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxiycdmo.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2sfvixgqg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzhfwfl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2noubxlef.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcwzfbms.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrsgkljk.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2cmcvhofk.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hvpjecvt.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2ncjcgawt.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqxnuzzb.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qljzikyr.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvnzwiek.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2trsrsxyb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zudkjcpw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xneyezji.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqymgboz.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwlbxlb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2cypxtpzd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2wecpjzyi.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbrowdy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2emmepogp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhblxkg.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxgolwc.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2qyyvgixe.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2mosoqpvg.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2iewlabtp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2tgebfujh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2jilgdrri.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlgixnsx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xidwmkpj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwycfdq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhpjpiu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2obmnigcy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2samxztnv.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2kuiiwrhu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2isuwqocl.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqqkmse.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2pnhlkaue.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjlmteh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2erwreepu.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdqmzve.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbtbcjh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xcyfodeu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mwtvuvsp.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ngpjpwmb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2shrtpkgr.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tggifbvf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuygyqwz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlluycvq.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2phwfadyx.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2enebrvei.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2xiqmebze.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhnyetsa.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2xynrwuew.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jihtaggn.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqwymgp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2frowzsgh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2cslbhnkd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvezlwp.html


<!-- 参考信息 -->