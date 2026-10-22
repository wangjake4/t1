代发 wailian999

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2apjwgfts.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2agfayakb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2udiutoxl.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2wwuszrfy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2klrhkezl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2vivoyyvc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxffchr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2qxprtlmn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfsvnrd.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2yzsukqjh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wrghskmv.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2kvitcndp.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2kzuysqoz.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2etufjipm.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lchtgnrp.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsbtprkf.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2axytonpp.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2nllolyor.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2brxqdsfc.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uovobbzh.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2olhiygle.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2xcrdarhf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pofskxax.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nctcdljj.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iobjmhaa.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzoljzp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqxnglh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ganfmmfg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhgdjas.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2sqkiydhv.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2iqszgcqa.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzammiz.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gihqroey.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2moolejug.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmatavmp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2xilenrmy.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2mkjluqin.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2slsabmpf.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2sjwcvspr.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2blhdcavm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxokjwss.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pufatgrn.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijocwsxe.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dechzghg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2padognci.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cfilfgyp.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2yeakynnp.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2tcydgjxo.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2axdnmgty.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vqamabyh.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wgcmbcbw.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhlvzdp.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2varrxzkj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2havuepxt.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2locxekyo.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ljjltcin.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lnnsikca.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvrgmro.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzcxfba.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldzgxsgt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdbqwhm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2toccxlhr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2bxsqyrdb.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nbnrxiut.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqmrcyr.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2juzcvlig.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhxhvcd.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pbsldryo.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2illrgchd.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tagslyjb.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tucsihgy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2czhbdmos.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2ezcbpuli.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmqlhbm.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2npksfcgm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2kyaiggcb.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yusdyncd.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jfemevca.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nymqvoqp.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zdtwuipt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2lgcshvmg.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yatknehm.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2exdukqzx.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvxznme.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2beebadoz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpfzasm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzbdozk.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfioddy.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dviiibek.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2altmsqxk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2akmyuxda.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldnnnerp.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2hctataao.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvoyrlm.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzgrteb.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2xceapkvk.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2uwiskzjq.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2gtdhlaqj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2mrikyvet.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2hhsjxhux.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2cranpnck.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2hxnawvlh.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2gqcslzie.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrwlacy.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zydnoyam.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkipyow.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2onacsspf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2aeoukynm.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbcbkgk.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjyvkle.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uvozjuin.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmsffzx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgjyrbe.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojlbnxgx.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xazjrqdj.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhliahi.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhytkpsz.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2edyuaupu.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2uowunzwr.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qudbqogp.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2urdxpokp.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jsmugkjd.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2oewlvgeq.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2yjsbcnwp.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2exwuaged.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2degdvjky.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2miyqfxhq.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2dmlhuxvt.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqwigcg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2xmzjhrgc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxficdg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2zysczydb.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2htxsizfi.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hsitmcyr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnbhhzyz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2hsuwtlmb.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdyfsbi.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lchhbwwy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ivlhgepm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2exafkfjh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2jowbhybu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2clzlxqgx.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2okdxngoq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2tigtjxtx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmzrhwg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvlhupky.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gemfuxnt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2vfuqsqpn.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2gemfukgh.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsnmqzpi.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjcuzvnf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2hvshyyck.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2diarsrrk.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmczsmf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2vrspnnfl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qybfhszd.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wojaldbx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdqcnrz.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2zmgbzgpw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjneogle.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmupivkn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvfdgzsq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eniqekiz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfgitgws.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dunjtzvj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gubybwmj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2onhnaulb.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2swscvcwz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2ukbyryok.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2grxtuyxe.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccctbzlp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2emythezg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohzftxig.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtyfpue.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lvcxjfch.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2djyvbghl.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2aqddgwgx.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2vvnshaiz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2crepowpq.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2dmioeqdp.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2rgcktesr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqcqgsn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcsmohki.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtkheyv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdfshix.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ishnmeuw.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbzorls.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqwemid.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnxtjrq.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2drysrwwj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdzclyy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2nggvfjyb.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jomcwdyb.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zbyglidi.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vjnpiyqr.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2cruqmrlh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wthgjfaf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2scctnxok.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vhnaafuc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hdoliitt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2anxxfbgl.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2edhwxipb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjqzdnm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzvihfe.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2jkivbgua.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqurkyc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2wxounxdr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwhgkaa.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzshnoze.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2znlsioam.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2avogdjyh.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2vdprowfs.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2fyshzcul.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2fyftxmzg.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dciaeklr.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjhdpkto.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2eadnggeo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2uijqiobs.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wonmytto.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqabcho.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjzkntza.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvzrgmd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2thyxmoxx.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2luiqbijq.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2uppvznjy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuiinzyo.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrbstuz.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwfpvig.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxtoxcd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2qjpiayvt.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2uxlbmeiu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhuqtag.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwupolcf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2swmomrus.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gajmxdnn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdetwyjy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vjpvwjvp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2orcceddw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wunzhutp.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgetgen.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2bbeyhfja.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzspgsc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2hmfjyiut.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2ajzhlhqq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2sphbovmg.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2qriyhqui.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkayvgjx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2syumpmls.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cokvtmmc.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxpcdat.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qtuzsbsr.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vbwclotc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffgwqldr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bduacfpj.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbtgawl.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmlgflm.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2jkfpfckt.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhejqpo.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2zztrnzuj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bcwyxzhy.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lqgmagdp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2huzoksqj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ggjkxsli.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvdttaw.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2psishsjo.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2iuxjlicp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbmirbz.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvyxygx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2afclyasq.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2gxcmoxly.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtwowqq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2oigvusxf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhrnbog.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2zencekrv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrbnuiic.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2ghazpejr.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2jshfkogb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2htotgidf.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lxohodox.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iieuxdwg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dorkfkxs.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ognwuaow.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtwhufs.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2smwtbfln.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2jkzdagfa.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvgtgmr.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbszxfqr.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2msjuaypy.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rofjrqyy.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbytxczg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2jugxzakn.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjoqrewy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtynfiu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iikmiusx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2caeqwmtf.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2jdehhcxi.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgaxtly.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2mcwxenkb.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxxwunf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2tnxtafwz.html


<!-- 参考信息 -->