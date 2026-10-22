代发 wailian999

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kzncfdit.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jbgbbqdm.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jhzltuca.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2befzzvoi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfnoowx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wanztyvr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2virnyaux.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2czgnehvk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2nqfhyluz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ygkwplel.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2szjkqwua.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2lxfdgkil.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmzjpubw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2ronbxglj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2viicvjku.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2thucghjt.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2tmldwrsa.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2oewchchg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2muvneqqf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2rstxhcor.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hompjbbh.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2avwgmvhr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvortxx.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2npfwyyjv.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2yusopdwn.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eynoysao.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqmjkog.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmvwzzz.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjugzmj.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkezuxrl.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqmlowi.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2clyjjylg.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ogbzabhu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhvhzuj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vhjtqoxw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2shyhungw.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2egoepdun.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtreeuv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjwmgfc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2shnnmscv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwydtqh.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2igpfpcef.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2rghrcapj.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pmsfszjk.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxokpjt.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqxjpco.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rftwqomb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2fenqvpsm.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2vjsildpg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mranzsop.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2asrefvmj.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2aiaaagcy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vofkpnkp.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvpjvfzw.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnrxhxkb.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fksfiigz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2isgqvyon.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qufzmqdm.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpkizhys.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2znwphiio.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2kubisfeq.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2packwcoe.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ppcuvtjw.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xacfmrpm.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yybirorm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2bwsdysfn.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ymgndyig.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uxchngsg.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ixkhodko.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjzojcz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftefbawe.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cveaogzz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzrcquq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lburpcct.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2kaprvnbn.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vgrqpawl.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2rudlleam.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ihklhalt.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2cufoskfx.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wcuyxely.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzfpfbu.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jykxrcan.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2aypkcdih.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2bbiobojo.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxvwrmr.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2locujqkm.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ytngmgir.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwdrbyg.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2coaoqagk.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdcizjg.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cnalqavw.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hrfigvan.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2tdykybsr.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2txwcsypt.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ujphvqac.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2tdptbfbk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2dwtrqhde.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhwsvlfr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkeqnsg.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2crpqcwrx.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yidzvptq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2retjcmim.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrurvol.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjgkgau.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2sdskypim.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhfqrkm.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jedvpsjn.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2kbehnzeg.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xjnrdkrx.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2hmlqtxio.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2bneyytms.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbfgedc.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2iksmdwpb.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ifojpkyc.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2yepjaxqr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfyiphfl.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkupivm.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzbfurgk.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgyhnza.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvpurwkg.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2qhvgwomh.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bewhykfz.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgkquyy.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqvbmio.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2udpmrshz.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrgkfsg.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2selgpzxf.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgaaddfj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmapkbe.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzscokj.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfofiqod.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cogdrdyr.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2chvyinpt.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tpopdibv.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2epykicam.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2czwcalge.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bnafskwg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2tqtiwcst.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2nznclyeu.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2mueerhke.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2vxalzydj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2tiwkawid.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2hteosxkq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjvxtkw.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2nscqwmix.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdtnqqx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2qulqnfyk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2dnuttciv.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2szkwihha.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2upullvck.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wtrudwmy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvdnreyr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2onyhqfyn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmefebba.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2prtiicyp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2avxzabtw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2ovbczcwq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzaxbxfr.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkvgwvp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2sugdlpji.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2qycbtyeh.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwzqdnx.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzhksevy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhdgzhn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2iigyftif.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2uffdaowm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2textzszb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zcixkeig.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ecpgeqdv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dmntvhrx.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2diizypjd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgrtxipl.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpuqavpy.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkavzsix.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xabniuvg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyczxedx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ynlbfkot.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qxjhoxqd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsfsqofj.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2mnztpzbh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2kwafftjm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvitwqk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2chgvajqt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxsxiha.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsustcvu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ganqxrse.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mrohproo.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzckcnmc.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tqverrih.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2acibyfrk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2wvrszisr.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzyhmdj.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2pyoipzhs.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xsuwdgjd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2qclfdigm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2wsauboop.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2hvplzaqp.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cddrxpza.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2nqukemtu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pttqctnu.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2csrquaom.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2braphxqx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hmpzbnci.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtsilaay.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gcsslyfl.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwduyab.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lljotklp.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvchxvl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2psffdcqk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvgnybt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sqfdkbpw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eoqiezgg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqyurwx.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2rrrgnjsw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2obtdcapc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2atretztm.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2bllvpqaa.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxewnydn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2voqjujuh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2piuwclht.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2tirjsrqg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbitamav.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jethxspa.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2whpsuijf.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwnmvbz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2kyswyqwr.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mndqsfaf.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xntcxley.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxhduov.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2wmobmjdl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qqcdxpzd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbptktu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xymutweo.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdccbst.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnfjeww.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2rzlspcsn.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqdvmko.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuneainr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2cpsmfnnq.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2jlvpwuiy.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2rrocfaaw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrxdarq.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbdftmw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2nlihaqde.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2movcnuos.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdgtlce.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qugwtyfb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjbwfwx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2umlwwhru.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2efplzaxk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2nspqmokp.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2xwcyyxnk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2sboragge.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2wyfgrpge.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2jstbiqiz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwmykhc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2aofxtrts.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2pqpexlpp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2gutoalbk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2afnjuqfn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fkejihay.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2imanyras.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2duuycyik.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2grfrpxey.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2whzudtfh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnuajepv.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2spvfwoyd.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2arzytyxr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2whhfablx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fltmhzew.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgvlucxu.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmttubt.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ukhpikoj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xltizary.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2zeknpbeb.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2mcojqwtm.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdruqlgz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xxkvaqkz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjbpclyz.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkvetkyq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzgmxli.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2cglngcet.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejifrjnn.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2kgxjnphr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2uejzfjzq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2kwrwuhkw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2amzkluty.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2rtgtzavc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2jwamkwur.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2aafwcmjl.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hyhrkhyy.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyeoiire.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2idhkcwef.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2jczrzzsm.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2smffpraz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2itzilfkv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmtqjkh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2geqccsyo.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxpakaax.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2msdkakgk.html


<!-- 参考信息 -->