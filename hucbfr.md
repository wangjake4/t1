代发 wailian999

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekonzspy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywtwrlyd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmawvax.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xkpmypra.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzvpwzy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqoncdpt.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jvadyvct.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2sawpfeqa.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkijfmic.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hampwtwx.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2spbgyqgf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xkgrjxsc.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2shzebvke.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nthvayem.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vmllxtoh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2eskigydu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2povmhogg.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pushlzxt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2pgrshutw.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdbxrmr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2zixroare.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2uvortbbl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2keueikdw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdhleei.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqmvqrs.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxlxoplj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvyndvc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bdvyqagy.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewlsiams.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2crswvwmi.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pddwpwww.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkyyxsvl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qugabidp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mkpduslp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sifdqiei.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocbqncaf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2cyqvnvcm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvthavgo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2coolbgqz.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2prynqqvm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyusnpsn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfomfta.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2olteuzbm.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ilyfcjxf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2ccoihwiv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2bgpqnleb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrcbpsj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2hvwywftv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uixvlzmw.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvvevwv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2konzjkac.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2guyxbpuf.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2xbjhkczn.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zzyhpplg.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtgteri.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqirqxid.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wjumsgur.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2vplqxrpv.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrgttwg.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjwbesk.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgwxdty.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2dilwbvnl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bautigoe.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oggvtdww.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dygaassk.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssopoxdy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxzrqvb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ysanipkb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpduvnrf.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xxsceeck.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmcorkk.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jumdmrur.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2svuaioir.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2shdyftde.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2keokdbse.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ctcrvxop.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2bavarpnl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ltahuotz.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gzaczzfg.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2shzaflue.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnfsipxn.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iavxdvdm.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2okgjrwvv.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqqdcvr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqtcsdtl.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ldgiuqqg.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwkuulsx.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcsktdp.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2eedgnwgl.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hebkwpmr.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2biipzgxf.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yxzdsbvk.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uhmqszmf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2oeanrahy.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kdlnaabd.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2syvxhraa.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqlsuio.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2clkvhmqn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptnozfqg.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iftatvlc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwkhgldn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvvtflq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxllrtx.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmihnon.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2iewqgkgb.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpocuel.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2wywdtqvw.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjqttwt.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fwktchnr.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lsqfyrdt.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xbgogzng.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rsduykcq.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2fylmoksg.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dtuiktoa.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xgovqmpp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2kxgnlhzu.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eltyvypt.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yufvpyqm.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qmdgaizs.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jyzewbda.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhcewcz.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nctltvjm.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvlvcgb.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2sihjxlnu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2aiymlmxd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2epnjmwki.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2mwflaent.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzxjxhkv.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrviafap.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdehcqpt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2toykxecw.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcymolwp.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2lubunyqz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2undxeekx.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzdvpee.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ewccfykq.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2sowdlxil.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2gqxadquk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2dfcbecsq.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2lewdbsdl.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2leglzhjm.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2lprerpnr.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2jlsqkifb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvvtrlrd.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzttrwgo.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwpupli.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aiyiyorh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvttvvj.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2uzibkuvv.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2memlusxt.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqweyuz.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2sobwvrce.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2paijnzqq.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2szchakdj.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2alqknjmp.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltyygljc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2brpuaekj.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ofwhbewe.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxgnsycv.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmtusfy.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbwusurv.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2raupdjgw.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqiizus.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rkgxfvrf.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bxsxwskw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2eitkfqci.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2cirtjimc.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2grshihjs.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2vpirklfm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2erbvdsix.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2fhacdjyf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2flcchnfw.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2trcstxsx.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2irqqsdza.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqodkajs.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2gayzmlsx.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzibocvv.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jroxrwmw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2naaardgj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nervwppo.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2wfndbomn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohoejyzo.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptaqizwv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzoahyn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2hzthxkts.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsizusgg.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2crpkjura.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2tiqyxzhn.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2tafosave.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2anezwjud.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvyvcmc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrvjycl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2uakajafl.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2zapofgks.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2wgoekebs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnkdnic.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fjxhiobo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rrbelqrb.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2thfchpqi.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2wanhovsw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fazzfccg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdrgtcwl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvevjmk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfkomuud.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ufxiitcx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhdnutu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qielrsrw.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2kztjicfp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2zxidpkgr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmyrpmgn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjszxfd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxhozzhu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzqbhth.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdxafss.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fkziflqe.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxsbsels.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdssewi.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2yawfomwx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vfifeoxl.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2maqiqeza.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2rhsphrwm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mkjtixqs.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2jenkikfd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2jvmgofdj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ymcsetrl.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxxnyar.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2upnsdnqa.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gstrpdlx.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2glcfethc.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2khknikpn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oiweyuey.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdxvjpe.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fnpfnqjm.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2opwbgite.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2teqcmbbq.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjxlnck.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kpuktyqz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpfkhmf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2slonpqpt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ebczvspp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkhbhmdj.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2iatkphev.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2petfaaqh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2npolglqk.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmjauiz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2nuyicmbs.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2atctytzh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2dhyyhmqk.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxadpdq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fescjwoy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfidwit.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2lpmrdafa.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2kocaopib.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzuhoik.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lexqtapj.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdvmlyb.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjlxahip.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2htmpdovb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpazgyx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2dfyjytqs.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfueacwl.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2puphcsqt.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2hoickdap.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqptnll.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2fylcdtew.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2baolntkb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2twvusbue.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbwlgjm.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2swfeiubl.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgqewjn.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mhpkaldf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2sxrnlycm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntpfxzxj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2nuezgpps.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wepkydnk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eeuyzxqt.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ykkwijoi.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2niwsvauk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2smvhwyot.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2sjzvikok.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxaqosk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2gvcxpfnv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2iibzrhks.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2waeemoui.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2sjetlqpm.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2bzsdpnix.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2uttkuyyn.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqvzfpf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uglgwjjy.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2redidmlq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tkremjnc.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qomgoyxb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgqjdmkl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2eptkigha.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xiwoipxt.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxfoggi.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2sbklcadd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvfrxags.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmjfmmk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hgotgwte.html


<!-- 参考信息 -->