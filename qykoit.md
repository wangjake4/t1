代发 wailian999

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwbcusd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xndokojf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgbgqaom.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2etelsulp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzscprm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2juqhnduh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2tswubooe.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2mbithapr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2niiyqean.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2navxhvuh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2kccojnya.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2urxhjgnf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bajpxcjk.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2vpcjqgfm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjpcrfn.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2tygmxvyl.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2oxsfuzpn.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwhacmt.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wkprejho.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgyygpvr.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wrlbclcb.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmaiidqt.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qsoujrvq.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdnfqch.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jnccuogh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2dozeapol.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2taptaixf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dccjdqvh.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mauzqajs.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2houmfaic.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvstfyxk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vqkktwbd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jksvjphh.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jmobbmgg.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2iorzeazz.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrzhhbp.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2yysaociy.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxajabl.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmnwobtt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2hqlczaqv.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2mckswfov.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jeumzlty.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mpuxlnns.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2gxuevjpz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwkncdrv.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvztalux.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzrtpzmp.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2atrzgzuo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfplgwy.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwwonxz.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgobviot.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ouslcvug.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2nkogwxqc.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2prxztwju.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2itimmolg.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zhpbklbp.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rkcdzids.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2kdestpom.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ehigocnn.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ffevumax.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xryojfkt.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbevrgy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpgiblfq.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2abiegrvu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhcycax.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gljbnard.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2volgtoma.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cujxcjqt.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2ftnvdipf.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zyucxpxk.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ncedmgug.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2yqursstz.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qfjpmjrb.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qmtjvmvn.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rmfjnans.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ztucnrbj.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2ubzcvxrv.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqkinrc.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ybxxrdej.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrvgary.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxmmzne.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjyzunb.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dpozgngq.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gqsgbnks.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2thxtdqky.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dvvumpfr.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ibrapand.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2gufmvung.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrtysls.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jovsijqu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2wbldelfu.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcnawxsj.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2derbtxua.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2thihyzma.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xrtyqbru.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxonekn.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2acvlcsun.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2dvqknlhu.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2gryrnkug.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2wlgbdpjv.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2acipckjl.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2wstxvugk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2bldicyiu.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2gwmjdqnh.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2telwfian.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmbxqkj.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ajrdctkw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryponzaa.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2souiqxdx.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2orgscppo.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbgfsze.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2mchvncls.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2zegkswpa.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oroduwel.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cypwxwho.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2youpuxcw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogguekpv.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yeumvzzg.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2palzwwao.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggqchesp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfblcxce.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vrlsakkl.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vuckftxo.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxqvwpb.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsgtfjwu.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2utvugath.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lgeiljzc.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2nomyahae.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hpolfgjf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2oxansuig.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrjuyah.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhbwnxa.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2ttgorcir.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2dcjdwkiy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrwtmmb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2aghuxbtt.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2voonpsoc.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgexnyt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwyktpiq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2gjarkrdp.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjhmumia.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mugityei.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjtuoxq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwoyhvf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2sexqzeul.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjpvvva.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtzurci.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvmznyae.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2bsdbdwow.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2alklcrrq.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nslmkrck.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2tppucuhu.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2atreqzdz.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2munaqrdo.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrtsuqf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2awnouacz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2bkirrctr.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2qnzcrdql.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2asdqdjtu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvwhwwv.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wrwrfpbv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2agnrplqh.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2heslodcn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzuixlgx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqstgliz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujczcbzm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptgzvwqb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xysbygcx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2bqbyszxf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2slbnmemt.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2czwfigdb.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlmtbbr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2nibevtih.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqaeeiln.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrfmhnpe.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmosqqv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2epayetdz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2fsyafhtm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjhkfvt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uekjjuvy.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2aaslihjx.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqnfkkbf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vkiiyyyl.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lymehata.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2sxycjawg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2yctbvmwl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjnnrly.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2grvdwvlw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2szprdern.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dvdxeuta.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2cafkgxib.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnbgsmo.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rfimzdpl.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tamzgtxk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgygreu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpmczmjh.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rnlthzxv.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hcrsxzqb.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sddnhytb.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2nihzpbjd.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2txpfalnm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gbyqqmsr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbdgmwp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bmptetph.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqecknvu.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2icgxxkzt.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2namzesja.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvehmgw.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2ixnhdhag.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2cuscjxmw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2jthpopiq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2fwzmtjqm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2puznzrce.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2sudxlfxq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezurdfyw.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2vwdklaqm.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hriffdas.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxubfim.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2grrkjwet.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytknctak.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2llflnumb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2kprztdri.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2frzotugv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxtqset.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ruqqmbam.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2louzaskc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2zprxpaqm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2gzlkuegq.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwwlbuo.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2icjzejnj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2hkswcxqr.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwxflhs.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2lrsseofr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2okcsxhdh.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2etsaiwrh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2czlzeqoq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqosbvj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhgjhfms.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rueytchk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmcjxye.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ztiufyhw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2tovmqvrf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qxjypdku.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2msozmvkj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2diofxlfs.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2ayfakaak.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvjktoo.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2yxeyfiyc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2ovfdlpng.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2flikjvzt.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2owwhiwfs.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wuensrca.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2plidsizf.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yyrglmas.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2irssgrgb.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qgsiyvxd.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2msfkvyiq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2himfcybe.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2teelrthw.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxpxdhqr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2inmgczcs.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdytwcei.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvtwmsw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tsnutajy.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rewdlrhy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2utqwjetr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ocycgxsa.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2lubbmmbc.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2phqczdjs.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dvwjkvuc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2piiebmur.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxguluny.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tdijprjb.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2iusaijvv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhpfoiy.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2quixjdtg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2mbojcyjz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2zwahtcqp.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2okjcnhhk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2zwktfefv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxvzvzr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmxwhmp.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hsaysgwt.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpmtxje.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmxwpmmc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ahgsvajo.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2saqzvuio.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2dtkcifxg.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2vpuzbsce.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2iujabzry.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2oafeujbh.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2dfarosbi.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kclsgrmx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2boxnthjy.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxwkhfm.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwbromd.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbwqppkt.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xieqskqu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2jehpmxyj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2vbmvnxlv.html


<!-- 参考信息 -->