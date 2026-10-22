代发 wailian999

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yevplyzq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxyakvq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgxmtjk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktbqqnbn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2aonytdez.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2svsjhhuw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqcwchgl.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2yynwnhex.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzjtbelh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2qlmdwggy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2afuqcodp.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2jdfjpbds.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2jqgfkptl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ribujnto.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbydrgf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2vfpwozbn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qrynmrlq.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2dukwzgxl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbhihjf.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2xhhlmzrt.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2xwfcrlxd.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2crrccxth.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2abnqwgar.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqpovqr.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lfrualar.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwzodtn.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ehmooryq.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jicihbag.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2icfeapmi.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2bgepbolm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vcefbnmm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2japjdoyj.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zlszvtxl.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhcgjhwp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzoonxl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iapljzgc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxeemed.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wrwnoukr.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdazcwu.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2paizhgzy.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bllcpexn.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pfppqbej.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrmersnq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2xyhdhtoa.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhctgmk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkoeeap.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zetcwzzt.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2aksaudlf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iddbjhyt.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2olgxeihd.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gawxphyy.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2trvbkvyz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2uikluliy.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2njfjqrnr.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpuheaw.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2qhlzppio.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2msocyhqs.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vktybooa.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2svnhsrqf.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvofmqo.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ertpdcjb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2tbkgubtc.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sezjsvna.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwktcdv.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rwziewqe.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2pluzyfdb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cboftkkd.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2woejekko.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqzbcsld.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxlcdsv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2jmzuusov.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtzjzri.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2eeyazfnx.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2usxmvdox.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2txsblevm.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbutknc.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wykdudco.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qlontndx.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qzptqloa.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2blgktovs.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2lskicmtm.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tztujdfr.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2txjpkvgo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2naemxuur.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwwmvuw.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gzievono.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pptxfjrv.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqzipit.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2wucofpmy.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmhrcyt.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oxdnjspw.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2npkegxrz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2qpemrocw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldaionmx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2oxgvvbwa.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2enxdnfvq.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgbkqcuq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyeuswwl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pgpddxzq.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lytufjcr.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2emfdlona.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2eauggxrn.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjzpyll.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2bkzctekp.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrbfxap.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqclcoi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2xrfovdrg.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qujtchts.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdnpvob.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdbutos.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2dorfrdzj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2obavsifr.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrlycvyh.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpdcqgey.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyddemvh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zekppkxy.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2krvxpavy.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqppiizw.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnnqujz.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2lalhznqh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgjpkrw.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyipmvcz.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqdkgug.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtwkelld.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyiokyto.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cjduczlx.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2nggbyltq.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pwziujde.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2pczcidnt.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgyoxvn.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ryrfdoau.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fxoehtpt.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2dmecosen.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwrrjex.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2icsjdslx.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2euzhbdul.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2auipobcq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2qunlbyuu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2fvnooycr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2rgsrhsyl.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2lkqlpysi.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qoivefgc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2celoxbqs.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2aszldoiq.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2xurwbbmm.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kxhfvzvr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qcwrqpsx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zyriujzr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwzyzud.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylohnkzm.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2faqocamm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2krxrrvew.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2nbyyitxo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2keigxoty.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwcpppn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2swuooxtg.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbpdqym.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpuwttoa.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbehmfez.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2hedyfmdi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2pdyuiamp.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2ublfrhuj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2epcjarqj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2krtorael.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwwbiuy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tahmmdcp.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqlkphy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2obkofudr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kavasfjp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlenvny.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgrrmhnl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgimgggs.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqdcwaf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fwssfzmo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbywkyjz.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2fguvtlhh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2cqloufue.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrjsoczm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mualphkr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2otxwmpgy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjsxvgj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2dybohmgp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lozleqgd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2luhsnpfs.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tblbnwdv.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2rberlpli.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxugxul.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwwtglu.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2txgtasbr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2elnzyqor.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvfwxoyh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdxlzdu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qvzuemhg.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2abkuikdn.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2koxkltib.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bhrfxtzb.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qspucxrp.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2taggdevm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2exwakwoi.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2katxnrbd.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pavrpgcm.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pyalukrf.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xthexlpx.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2fxzbwace.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2moobmcjf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sxiiydpa.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxmafng.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vzlhmopi.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwcyjloq.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2qowacnvh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dpvqydag.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2jfpatvkq.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2wvruddii.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucklokak.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2rieyuxht.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ikximcfl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcuojbq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsfgbrko.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2agaifoqv.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2kemfgcpo.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jhslrfkv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2icliskug.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hllbiqpi.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxcdgor.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hshrkzpl.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbdswll.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2vaaaahgv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2kavklcsf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zndwggpk.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2jclcxpko.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2igoyqyqq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2bdcjbbcn.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2emuckwth.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhyvghl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2eadggbex.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2pmavidqw.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2jztzryes.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2plahqrok.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ptdsbhfd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2skayvvao.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqzkcyrg.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2zavchucp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvtihkkm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtxmlej.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cjnnbrlo.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2eojhfmsa.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2saobksey.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2lvkltoiw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwmbzwk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2tcvdkzrg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2bumknaob.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2uaskgzbz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwiefax.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjpdgih.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqojsyo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wsweynzd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ifitmjxx.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vlptmzox.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vypecfue.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yuhybtik.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyuwhqpb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkhjuii.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkfesavz.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bogiyhqq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2xczxybig.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbiodkyx.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2kaaytfvr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhyircu.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hhaqtgtr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhqrjjb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ybeiphtb.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2paycjglx.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2yldcsljr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ffqhoevl.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2frocvnmo.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2hobvivvp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ahxllpez.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2jshvptgl.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkuncinw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxabxud.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2wqsakdok.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2uskbfoyf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lghlobvi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2oeoaajrc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2qpglgbxk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2yebpuctd.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdpeidz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2swjicruq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2apbblacr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehustzvb.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2pdayfdtk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2qeudqubp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2gnjkhtnm.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2puustufe.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2krmgqfwn.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2axiepctj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxwtohx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkuuwqek.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2stvthvvz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2mberqaai.html


<!-- 参考信息 -->