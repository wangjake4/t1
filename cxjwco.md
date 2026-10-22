代发 wailian999

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jjestgpo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2erfbxoww.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2efbytunr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xzplzyxn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jnzcptvi.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cdbpmsix.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2caimqvtm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2niyderip.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtmozgg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2esukpfkm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzwbmdn.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2zdarnwrs.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvwxdkaq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2yfrkupoj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2cjceetws.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzwvwnl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2umvhzskq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2myjpiwyz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2eyejlimc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2mhqgibpd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zplbixer.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2kpfvwidn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gtlsjhhu.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2opzfanqk.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2uwojjckz.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2krjeerbe.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2krzcjzjd.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjrdrzfo.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxjznyd.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2afhzycao.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwvwmfj.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tmztopsf.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xsycgxhw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdjbpus.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2llogeano.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqjroha.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oyiournw.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2phmwdojh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrxkmlye.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ufmgzhgb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2baxewnis.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vkcmgayl.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2fmvuavoq.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xnebyram.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2neqhswmd.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhkbzlv.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2edpfndky.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2oqnckksb.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ejcjayvx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2puqtkaoa.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lovvlyhx.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2mfaxbncr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvpiuvld.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcinntxg.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2swcwapia.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbhlqset.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhdbtqjo.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bbufozvv.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfojsgn.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2phrccumu.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2mqutucpj.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxiioeh.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bbexbizo.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhbvhjm.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtarhlo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2qlcztpuk.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ubdbayon.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtshyui.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqmlzeq.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2jslwrtwf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ermnmtqp.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uofcbbcx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkkdckdi.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufcuwmqz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2orspztmb.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wodxkjjq.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2hdgrppbc.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ijzkslwd.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2gpnszgzn.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhxmarb.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2udfmcabf.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2idcwouye.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jbfghmte.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2edxyldox.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2yduphagv.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zomftbeq.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2lbfnrpxh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgxpbea.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbsmvky.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tqeehdrz.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wszwyjwu.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2grypibel.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvoftmo.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2efnwlayn.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ilqbcydi.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2jfgcoogq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2iartpjik.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmhmjav.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2ucaixplq.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppesfzxs.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbcgblz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvcnbzzo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2khntiucn.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2njgcfjuz.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxlmvvw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2gifpyeua.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhpdxuy.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ncgkoyox.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2fetzqjaf.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2uibtinxe.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2miksgtms.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2utsnhscg.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2sawczbbs.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvptuzb.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2rtrmvmdg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njkpfwds.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxsbonzi.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnefgsmk.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xddyksne.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qppmuxqw.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzfqfmw.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzxhpfbx.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbnlxdf.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2baiflapo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eazuyrfp.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ooaucomp.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrticrhv.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtikfxel.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcleung.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xmcrebbo.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzaadbvf.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wddlxylo.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfjisrl.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2elzcggse.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ueewreyn.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2puzkmlfs.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fmznytpo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2sveqgopc.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2kowamyjy.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2ywegmowy.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2tinwimgp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2mzfbiulv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2pwthlros.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2xcufbmhi.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2tinncejy.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfxjmnp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdgemxrz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvsvhpa.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywmnnnez.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ooetwvxm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sbsyljvs.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2erqzndul.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvandxj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqauqdb.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjjayye.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhvjjof.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2dshgufwd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvxnlkoy.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2unduxgeb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfrfeqo.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2rihhxjue.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2iacaecat.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2chfdwvnz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2chigsvfr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2blcqssrp.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmmdkof.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2aasjzmbn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lyplpdif.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfmujyd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2teincmdw.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2zsbdlnwr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2auqmintj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrkuasfv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtvgidk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzhhnmtq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwwhcdq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zirkisck.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aqrszygv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxodplxq.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2nthnfmhn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2oswnwiju.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jniqlepv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2siyrhdia.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2etsgyury.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbekonwq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2xteqhbet.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2isppzrxf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vitcbogp.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2itlfrddp.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2lqyroxby.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vrncffzx.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2sygnvbaq.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ppeormlo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ihcjqlwd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycraqyvg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2cmnkamdw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2uptcbfqr.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fyfploqk.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2jehnaelk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvxefpm.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2asetncqh.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zppuvnck.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqiqyii.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdxmwlm.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jdeawugn.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lboxcrmo.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kqzrkfjk.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2grboyiey.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iexgizkx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdrtroz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qlmszzvs.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cohrhsbc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2xskxorsw.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2gmlpvczv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sqawjvep.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2yysgrjxs.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2dlycuill.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2whlgmpjv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2wbtdxemx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2byxkhgql.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmidqwlo.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kauchfvu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmefvmrn.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2vigexuug.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2mcffsdai.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2spnrzlgw.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2loqlzags.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rezsruti.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbzendv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqyychr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wlkdjhfw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2nnptbzse.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxelyad.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2kqydqtuo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2tugdcnen.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2lcaxqcir.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2gqghmzbc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxbgqzts.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2ddamtehq.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2dftiecpi.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2qfpranmq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2hucipsfh.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdedwgv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2ehdyikqw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubcmkyhg.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqexucb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2shxxwmfz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2urgkvbmx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjyfxtp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2titluwwv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hohnbqof.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2xphjrhqu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2vxrizqdm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2ebphteur.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2qednjkqj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2qrohslgu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2pfwjrbyd.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2znefauva.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqvycmkq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwscfeu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rgzbewpm.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2uzkfnubh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbmvgvw.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hskswfga.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdcuxqkj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fradycow.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vholtkyq.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqzaege.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2uyucdjyb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzrkimc.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmynmnll.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tulflfgj.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fhlqvjbw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxiqlbp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2scgejhwu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2iamzribk.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2dekuwbrr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tmjumeyc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2txtpbasl.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfyewakv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vcrxbpgo.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wthqginl.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uydsmtim.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2qnnwigzt.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2copsxxap.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvprprb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqgtvui.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2biznlwrk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2fkcwplvr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2voaszkbo.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2txkgaskm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqqmojg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jorrfjah.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwgzypv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2jxqagltt.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2wnapyyex.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2gquxszpa.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2latphkoa.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2esplwkrs.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2cnumegpj.html


<!-- 参考信息 -->