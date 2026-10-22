代发 wailian999

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfmykji.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aainqxsm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2mejjapul.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2weillmcz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xoazdtsa.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sfreowop.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gfuvqewj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2surfldkr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2teuvsmsk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2msgfmtpx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zhlxnkvf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfgpejw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2yygxwrwa.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdymkek.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzdshxw.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxesfet.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2uahjizjj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2hxekvglp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2xajjkogf.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2lciphdcy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqpgtpz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2txicrqre.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2sycicdiq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbliqvq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfmrtvi.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2nfiwawmc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxkmapn.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2bqoqmsdv.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2wmgxzqnf.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kehkdszo.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxjnpnl.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2omrflimu.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbamioy.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjgdlqk.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fodikwfa.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ytfskekl.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vmyzkqxy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2voubgguy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ropbjidw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvdfmpn.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kxlutlvy.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmfdtwas.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqsowsz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ndungscr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eaikwvyo.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ztczvuqr.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2egoxbnyt.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrqygpa.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxqmroe.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ditccnms.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpltcqil.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2siohazno.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2imoocpsy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vmphuiol.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2yvosldsi.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2idafboac.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2onsghhfl.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2czbilgvs.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2stpeiptj.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhghtmg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zemqygpr.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hlrxrhcj.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvuwnsbz.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ryzwctim.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxpkkcy.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xvivhvvd.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxqbuvy.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qjsfwnsq.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gamhnjbt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2dzuvwdnm.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdzowvj.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nidddxut.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2svmqqdbp.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2zewncpfc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwubuob.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbsimjgx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkfzuzvp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfauclwb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2eptkotqr.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nsrknvbi.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2cknljamk.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cnrjvzla.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2mjcxizdx.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hemzvgkz.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ksoioynx.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mvnrzqoo.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdmkndn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qafdcbny.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqwxqkb.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pwsyxwsp.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbpkcfc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2liqemlha.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhxvauj.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2otnfrszi.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpqezdt.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sihczgrc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxcldyl.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uzvaxyfj.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbogegw.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxyctlf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2jpujtfwt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrpazact.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2yuacypqy.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqysqchy.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdfbuamh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhoqkgqg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hwajtgoi.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmtvhefb.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2vswbareu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2yjowomcn.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzcljzi.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2uzbdcjcs.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2khwqrurx.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2jmglsplx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2jgvltklm.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2imzmtnsf.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2uwyaabzz.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2xihvebwj.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2vjppqoxn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2twnanhff.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmhpysnx.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqgholdu.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdlusqze.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdiudibe.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2eorfnyfx.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldaoblms.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zwodbiny.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2sxsqkzva.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2naveiqfj.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtqbhgr.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdbctdse.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2utndqqmv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdyqngnf.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hxobnmvx.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtbwgfyg.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ckulbeqe.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2abxfbejb.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2esbdiipb.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2nfcimekm.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qxzqnfsn.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdhtltm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2yyazitvh.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwdfjeei.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2fpfzwvzy.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2gpheofdv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2vycohohx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2trcvufpj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2gpzujzuh.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2cuyffkgb.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkjeqwa.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2gllsdjjs.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2ohesujpt.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhzcazk.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzwnxqe.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wcpyfxjr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksevhwdz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2bdlinkvm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2selwtxqb.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2cetzriob.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2azikhrop.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2jjsogyvx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvtryrko.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wxfvglcj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2noocuhtr.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2liqaxwov.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxokyre.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwpvzqz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2bktbwfir.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2sfpbtafg.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2zgaxcjio.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2jnskfyhk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jvizvfsz.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2isnwipzf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gdhbnyvn.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2hpyewwgg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmwmiksx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2huucsgyh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbnulzi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmqlxvn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhnwdmie.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2etowimlo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2atzcgraj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2watpvtlx.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2fhbdpvqv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2arucddaf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcpvotpp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvfkndx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhexklpk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qenyqvnv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2qiumwwst.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wjcryjkm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2brqxibqq.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2glxvwhml.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2uglgvlky.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2elfrzrms.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ewccdpez.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qivmhmui.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjogjop.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzrfougm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2nbouyxhe.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2tnvyyotj.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yunkbhfn.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbpmjmc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gurvisfv.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2usenqckk.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbsbcae.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yocjxpgf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2heyyzysf.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ceuumufq.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pzgoptut.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xvqlzbdt.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvyfumr.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uepehjgd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bwmuiyfv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nwogbuux.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwblypn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2bitelwru.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2olgpkimk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wptvuccj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2ejcnjjxi.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2ztsbwwtn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcnrsosk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2jjenedvo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2cowciwzd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxotjuwm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzyirjxf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2melgexql.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2twlwndbn.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2sgyjdunq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2xatjmbeu.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcvueaau.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2knpyapyb.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2alnudwyb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfepepa.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2akoiqgbj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2svgupqma.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhewifw.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2fkqaoplz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2ijmmtjfw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbenmak.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzvzelc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyrackbm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqdetjb.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmexhyy.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2xmfzfucv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2peehyykv.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkmewcc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2gtzjmldo.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2lipjzoas.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2kujgtxcv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2btarewld.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwgovgnj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zoosrfqv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjkhnxo.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vcgexigv.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2moiwkwyb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2zmjyuisq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2dzkuchwg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2jbcnaadc.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhgmrxg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2jntzwvge.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2ltqkvrlu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhzzcemo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qmwfivmk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ahpfamva.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqckwnd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bqfsygzj.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mbsneeuu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2aaccykcc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvxrpqrz.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lairxzan.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmcpmtow.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2qlzcljxv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lstlhhwz.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2parqxzvj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2znrntbxf.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwkajug.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyvggpmd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2bssuxsgv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2bgrovwyr.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkbwpki.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fysclrhk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptaepjtj.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2nywyymtp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oopoehsy.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzvomvv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdjifnyj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ljcefgdj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2yfddmnyd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ojlcirrt.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2brhskatn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2dcpvjjec.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2qekoikhx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2gzawrcjp.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xgyxvgkg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tiysmdxp.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxymqyr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2wescrcoc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2eyaopacm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2apyzrvsi.html


<!-- 参考信息 -->