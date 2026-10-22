代发 wailian999

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bvhktanh.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bitbewyg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2mcyotdbs.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibvdchvl.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqdflga.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtfafono.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cggmijlc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2awuvtfyn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2weyueexo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2emmcfvjn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xeglxnkq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sstlqprr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2abyszphz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qajsnyqv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmlzjeag.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmhaoxp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2wazfkqyo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvxtecv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ygyapeto.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwfpwwo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwybqfy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2alrnanbt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmbcccs.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2vthwzzzf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lwlqaraz.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ljofrfje.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yhiguuti.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2vkebslll.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2oofvqkpt.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2igteyrzq.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nbghrgep.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjuslkez.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2duldhkdj.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvtwvlvz.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gionlzwy.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ahfseias.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2feeibmmv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqpknwz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2arrkqlcm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbtgbitg.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2siuvuauw.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqxgtxk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2gadrhvgp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ooiunmdf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxyttys.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhngzja.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmmugxj.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hincsdhz.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hhaclpwa.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2iogchuqb.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvajvbvo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2aclkykpb.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2fytuqxff.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ibntybgn.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtjbwhz.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2wiaxanux.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2imbebmqs.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpgcxwnq.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2imddtwtm.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2svjakojd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2nigawidv.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rlrvxcoa.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzyalcrv.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2kncuasja.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2nvugnbji.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pabasyqq.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wonatofn.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uchkzwea.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vntgohth.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2eayqjajo.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hucsoalr.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bghiwnnk.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mlvbqleu.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2rkbumffs.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2klorgchc.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdhlcxq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2woiwcfcx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mucjtajd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2aknrypyy.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2txhkfgmv.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2ntnvztmc.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlfkgsx.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2pssitanp.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xqqoszjj.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2aljahvmf.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pefpdyat.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fueowksb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2igyuheuq.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2knxkkrmx.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxjbmql.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2yvyvluls.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2xpenzhrm.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2duuxdqkd.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2onkhpvnm.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pyueynsz.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvwocyz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2mtovtrah.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rtobmnou.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2njzqgvok.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2rmphqzyf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2fffyqygt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyssvzuy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2zgxzbiqj.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2quclrcmp.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejivkzcf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2llwiijbv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eydjdrvd.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzyuohjw.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmhxvym.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2qdgdpdjr.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwlnzya.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2nkonyznu.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2iwlrwwpb.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqtrbwi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkjnhcc.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2lgptawrm.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfcjtdp.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2eyypslmw.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2vivnsiiv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eppcwrct.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahncswgo.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmnszzo.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2runzjwwf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtuvqop.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2uxxiyavb.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsplgcfr.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yhtjnugq.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2cottvsqi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlksdfbl.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfpcsiuk.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmeqihmi.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqfkujh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmbbbhue.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dkoewcst.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylgjcugk.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tnewyare.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkbbnfem.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtjfuly.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2omldgjwd.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2geypdyhi.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmspfzq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2uhfcdtfi.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylgklkrk.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvtvlcc.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2abumwbfq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2wrztxner.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwujhgu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2gxeuctrf.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2hxerroub.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iitofiuz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2laslredy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwbephh.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2jydhdgft.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pgtszmoc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vyuifzwc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ioextadt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2vywszkfc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvrvsrk.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2tydfnevq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpkpyerz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmdxlfa.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhtilmh.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjwwobx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2rrentalw.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvxhsvl.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzmsrgr.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvlzors.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2rmkhshij.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2gpsypqpm.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2igulhrol.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrljodo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bzyynshc.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bjvszbvm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdbrhgf.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdnrwkk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjepcghb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jegnroqh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrklluiu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2usoofhds.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2idttitil.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhizemm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ogkaaemb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lprlylfm.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdxnawn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2iufyudan.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufsqbufe.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvjhyer.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2swdrmrwn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewttqcvk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgxhcwi.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qtljlpuj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgrzytsa.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lpahvomx.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdraelcd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bnutjbef.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vporbzrs.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fptzzjbl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2zxfzjrul.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2caxxbymd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2rtpmqtgz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2dvqgbfwi.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxutyhn.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ldsdkwei.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bbvyptyv.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lcsujvxk.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gffjlyne.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uwcoxqvx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbgcdnrd.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jqykvteh.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tzujuzgy.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ddyqpbua.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhczgpa.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfbhsag.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmaxlmw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2trfbuypz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bljtmyio.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvbultm.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2cdxlupzn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2brapjzfp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2anmsafnj.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2byckbueo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2qoopijhs.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2usobibas.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2yxllbpko.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2yumohblj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvnpdyku.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gygpuaqm.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ovzsfrtc.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2bfnfvkft.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2khcqexux.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmrcanwc.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2latjwstg.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfamlvws.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2blplfdjs.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2hpuonkcb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpsspqr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpugsyom.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2jjusdqhh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxbcvrv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2vufyyxoz.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2rwnpvdud.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqscumlh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2oteprhys.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2fzaoercd.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2tafsyzwy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2yfncxiat.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wpoblnlt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2jahczyix.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfofbmqm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbcqvzjr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cabpnbqf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pniponol.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpjgecd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfflada.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwfuixt.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ifejfivj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2noucadlr.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtxdxpa.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbzhktm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2eoepmsuw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2khatwekb.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwqqlbu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfaszraq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2daxncwks.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2megtdsod.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2evrbduei.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrfcgpj.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nmnntvxx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvahspcu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtivewlk.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2krnqpedk.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2manbxzaq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2qighovik.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2owtjnwsk.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2eoojufso.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqhmqjj.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rirhebks.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxcqmdsj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2gdrltezv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxlkmhx.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxskduqj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ymeyoqqo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2byuahiqf.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlpgswjc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dorzckrr.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bvaeaxub.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbmbgelf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2zxckfazj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2afbxheek.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqngapf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rocpgjbh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2eljusaev.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2cjhlnmbz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2vnlubsvv.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ltpowypt.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkzsbxq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjhasxx.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2nodlzgsr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixnbqaxr.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2keizrfym.html


<!-- 参考信息 -->