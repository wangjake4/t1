代发 wailian999

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwsixhdf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2paztdjrm.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lemoqurc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yusdamdo.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjqnert.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vroqdfcy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dyacuanx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2godbkrjv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2givpplkz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzlmdwdi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2aexhydks.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2iuumvjth.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfkgfrb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2qtjizfut.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2yxddulgk.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2oepwxgib.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2jstbbzeg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrhhlod.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2naymmbvc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2bdfeayhd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqhbrio.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtulyss.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vxglorlo.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2jgdpvoui.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2fngimpjh.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2euencjbw.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2glaozqpr.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqfqhykj.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nolmfvnp.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2qoybuxir.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2unvzlmon.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmnzjvx.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbyvjqr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjpjlef.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2emexdzqi.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnbatvee.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zvanfqdk.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqhalmzq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2frqrgqji.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqpvvxq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2muofghki.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmjiuah.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2zggjsuea.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2eiieqyaz.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxmrbsn.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jsyhcvfx.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnnvvywo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2bgghyusd.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqwgpxy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfbupkg.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2siwgzgcf.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2zprqykwa.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwnzycx.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqrrbduw.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2devjfovn.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkjedsyb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymbnrdgs.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nolhvlgv.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjldgmjv.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjjoekp.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzhizef.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2udnotwbx.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmwkyfz.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lqhaekou.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zvprqbrn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqbjawg.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2utcfvfof.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rtpsmvma.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vfolgjcb.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2htuxomcc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzolmmbo.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lowuwxhp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2geowdugf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxfhdyvh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmkvqlj.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2puiyzrud.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2trhnpqai.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2prasmqiy.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2upavjswf.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2sfultqeq.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jhsxggzt.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwpxbcr.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cujgrzpe.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2fhyuwbgg.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqedmvq.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdzwwhp.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2metjkuqo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjovlba.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dygsimhp.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pushxzdb.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqagszq.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dytiswdw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2xipcsdxk.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zlsvdtct.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kkegusqe.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2hqaqvgja.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2qunlyiqi.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iiwywjbd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2sejvnesd.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtkwtlyr.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfdqawx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2btjawgic.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtlyqqx.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcnsdnls.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2kuuwvzip.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqkleda.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ufcozkql.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2yhiqsosc.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ygoqjlwy.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2bcrpgsdn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2izhkkbty.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2uuxaiijs.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2rappnmdr.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmamaxk.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2uyexufls.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxuhrepn.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eltgkrgk.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjmenvvi.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzzfflvp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2voyjonxp.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgirgao.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2irnvtewv.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2grageopo.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2wwziskif.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbblcvef.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vblnirdt.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2duhrsqeg.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2stqhnroq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wevvcwtl.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zxptmnvw.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqqntaa.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbrvhwn.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ottanvlt.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwusxgg.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zfutcbfy.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vkznsmoy.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxrptyb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2yfojbbne.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2btczsnpp.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2mwpxlmvq.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2suxyqhzg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2orntjpki.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2gwptfuxa.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2xpntksqu.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2bvelahbu.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2brrksoov.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewcknjhe.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2iscqjqma.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2nptqrynw.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jeafbjnn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zypetwfa.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbxeidii.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2ahyylwsg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjdegvr.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxbfsfq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvsoqnvx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmvnsux.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygpybnaj.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ysneodul.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqdqahm.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfvqgvh.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjutheh.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2upcknlmi.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2ljldlvum.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2meohsjgh.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2ezgumrfi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2hnpuafnv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sbltqyqz.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ihzgdcct.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2joexawip.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2vguipjhz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2poflpwgb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvzokplu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2htquigor.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivzawyxm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhsnswp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tvcbdpbi.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nrahrpja.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jobqfvsg.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2qoqkchfb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxwisiw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtuvzhd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbhjufw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2plclsjux.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmsjelc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ewrsovds.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ohglaose.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtgsntt.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqrhayn.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhlupbt.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2impriiud.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vvhahxeq.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xktkxmeo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2atvqawhp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgyklvcc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2ozfqmize.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2sjefnfdb.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzayrlj.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2opkxbevh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bopxdsbc.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hnfgohyo.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qezqkwbf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ochoveav.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlhngbxe.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uaujtccd.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmpewmr.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zprydilt.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2iftoired.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ubywzunc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wlijoxdn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ylvlwvjl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xstrljdh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2afapripa.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqryxfh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dfbwhioc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2jajgemtz.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2ujsuftpl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvnvbjhq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2hzrxiybk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2pkahifyr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqualxvx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdygjtdz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2utxmonlm.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2bxrkuewf.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qmvzmqcd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2lhclqiba.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfpxhlr.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmrmcpzm.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2stytdzos.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2fveltwpk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2guearxnn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2rnkqnjfe.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2flhgfuwo.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2kotoenoa.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2lwcifoml.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2ozpvaggc.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2vgicwxfh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2rogymdwb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2jykwcwtu.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2oeawbzfx.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2wbtrxfki.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2fulagnlm.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2flqwtpcw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2idsccbyv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ayyyzuwj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2ickxskfs.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2daegfhta.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wybgiows.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kpyaulkf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnwyseu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vdisopoz.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2wzyykaus.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2tqsujwac.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2gtljygvg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2sqehnmbt.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2cispoebm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2anzkjyvf.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2sugcwufr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkheuvsx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbcbbqb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrmtbxb.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kwchdzsp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wvpfgzco.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ahxstqwj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahiundpp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgetpami.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2akuacrzh.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfyxpoaw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2atheqwzm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2imttdrwc.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxagury.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2uapktpjp.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hqrrfqsf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tarnyxhk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2smpnbfsn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjfqwsw.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwwotqks.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hblggfji.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kraoigbt.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldmpgbia.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gylwpsvt.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2chrhzgtv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlzlrlxg.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2nrmxawsm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2spvimusu.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2dgvbcqsi.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pyufyeol.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2njildyyn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2iumqmuin.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtfkxns.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxesmit.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2riqfdnbr.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmtvzxk.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvofdrad.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvnvgvil.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2skqxxqvg.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2hinzkeqi.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixcwiveg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhtsihwm.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2ncvlejus.html


<!-- 参考信息 -->