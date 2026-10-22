代发 wailian999

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2sfnhhziv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2hepondiw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2lstawigd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhqghll.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2esxsadmq.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ruczsncg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ztfmnkij.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2wixbmpzx.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhukuui.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iouytezx.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vjpblsgg.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdbhsyod.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhvbnnw.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2hapxvrwr.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wocreixg.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tevmrftw.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eobjlgic.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqesefi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rebnasva.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mixraqbr.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qevigwho.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlsntfuk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrnqmmdc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ujhtxhlf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmenfhcu.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xsgoyoaa.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtndrxt.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vjwtufxd.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvgdsuu.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bnswbyno.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhuzasij.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2vndmrcin.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2alswzuft.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2onygrxet.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2kotlakcn.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ztcrlsxy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2momuoymh.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrjjjtl.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkifpsrs.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2emgrsimp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwnggmzr.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2azksgmnd.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwyzjcni.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmypvjx.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtjejol.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ucakehdf.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2liukpvlv.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yqetyhpm.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rpczviec.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ziagrkjz.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yokuayoe.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2icnowvwx.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gziaovpd.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2tddlauzx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2znzzsfqh.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yazjennq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwkwsgsr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyixcarn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2twmfhfyf.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rkhjuvah.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2skfcenqu.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qgmjfbpb.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2beedphpj.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2agozhbtp.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqqlstl.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtxzqqq.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2oapnqzve.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xtudsppl.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2rwawnkxq.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2uxwpdnem.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfdctgf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqwpdpv.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mpncgrdp.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ehwucyrd.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dmupzpir.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nzogyxda.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2kerssnir.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrgbewo.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbhtepf.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2jhsbltok.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2ppftljfv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtsaznpv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2nqhcxnsw.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxrrhrj.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2howvwlzc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2svmymwpo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2svuxwvsk.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjkucdhs.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqaxlso.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2uioixiap.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2foficuia.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2xofgxdrw.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2osmclkqr.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2xwobcllu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2uvcienge.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2coswloch.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2chcynldx.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2yxlkqwnc.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdizuxe.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rllotauz.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnthayjv.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qivksfkv.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wftgobse.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2awlftmhv.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdsxpky.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2optekuvf.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wedouqtm.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2wntltcbh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kejzsrck.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxycneq.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uoknhxrh.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ittwlfoy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2cndjkqaa.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcxrqwb.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pywydyrv.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fmdxylyg.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2worgcupc.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wwyfbjcl.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xvyexqnu.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhnucqb.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xetamdfi.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfpzrhi.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvophokt.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2whpbghla.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2dfqobluh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlxxicu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2snohhbft.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2odseynuh.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzlzgpu.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbiwcuv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsfdqnzd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2uonvrays.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2vihuysxa.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2iybldptb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2iziautic.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzmvjnd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2wqldulul.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjzsdmi.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwhsxjp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmiiqxee.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2ujirbuct.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lafxrjyt.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2prmhtvcq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2utkuqvst.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2kakrykwq.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmkhervx.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2plbftetr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2hikaozxi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2mkjcognj.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2anzfgrmp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2fqludnjz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvzotex.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgyqxvi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qpejtkxy.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2bfobbpaw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2pakwmlgn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrlxbszr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggquzoko.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbsxgfgq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxumvqmq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tjejxcjl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2revmegut.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rymfvzvw.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2pulkgzra.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2inajjngy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjqilgv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbflllxh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsuqyqmu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppbnhssq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ehmhywxt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wwyabodo.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajglhfqx.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2pmchoroh.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2guimhnuv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2hshbluqf.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ejpalqsj.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gdpyhgch.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2hqlpytyk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxnqnsfr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2agpivpzq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2pexfllxq.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zbrlvyil.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2bknbhbsq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2slgqyqzg.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hvidvdti.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2frefspjv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eoeldeqe.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2gngmcolh.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ftemwafb.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ihleyqay.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jibceact.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2didwynwl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2idssheua.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzktbhw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aoloioff.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eerxpzlc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjjdszf.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxmpdgd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bxcfjnlm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2etsuspkl.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2htgigtlz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdanszg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2lmcwecmc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2dgfinljw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqstviyt.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzuzyft.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubnjegkz.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2gbylbaya.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ilrckoex.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2gejedhkh.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2khkcmdix.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nrntkffv.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxsckfce.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2kyoqazuq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2erttovdc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2oomrolbh.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kanjfiwx.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2cchwdaaz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2nndzatew.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2grrgqlul.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxfedoj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2icscuhiz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2omjqpatb.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2udiylmsk.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2qreigwjk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2leoqqkwu.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmnghwq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2zdmnfllv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2odokdlfi.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlbjruwr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxahewyf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdvucete.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjftbnr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2etiucura.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bdvwaevy.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2xrtmwzix.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2wifdtsak.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2jyogdtrs.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2ozruvfcx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2eecuiyad.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2ekyunnum.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2wkxljiru.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlpfonvz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxqoqfg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2livqtbva.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2evwetolk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kzndvstc.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jbgqtlvt.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrlhuard.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkahltje.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzpcjhve.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtmrmuwv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2avdgnato.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbnuqsbq.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxncrfus.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2yprudcku.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rmnyetvq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2teakauhj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2vbvmmuho.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2gawlfkfw.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2vddnpika.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hmyuvgnn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2btwslfml.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzmpihrp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kgfbtrzz.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjjusdu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwrhkzf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2bopydduc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2fxrguihy.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ahlkhnhp.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpspeotb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2kvlnolmc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvnpwiv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2ufdefjij.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvrmumn.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rovtysjv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymquikai.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2eexrevwl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmfafgu.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqkgypt.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2avjkqsxb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2abtzdlwb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2nezrsvbc.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2effqlpco.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iysgufme.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftckgjig.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgnsuxof.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbhkhzz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2bjnygoce.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgolfmti.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwuqbbsj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2budkmrzc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2szeuppho.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbxrgwc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2aaignyvv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2mvjubpkl.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2ctlnmcib.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2xezllwlq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2dncwrpbl.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2vtkhalsu.html


<!-- 参考信息 -->