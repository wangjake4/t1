代发 wailian999

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvbvzms.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2xhotmkij.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfymdbt.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2agzqtbkd.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqwfnvx.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xwfhqrsn.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqxkjjk.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnuktynh.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmwsklx.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2vehphdqj.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hwyrlcec.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2maxowrxh.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hpreqgbn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2yjoiffut.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pmjkpxai.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcuiycnd.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jzwihwms.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbbxlwl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2akqlpucv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2epidoetv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcshdckl.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bajsrmnr.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbelhwm.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wscrvrth.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2arnlakax.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2cmkeseqk.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcbnbne.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvavmob.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ovnuvfze.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kbznrmvd.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfsyfoi.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2klyitirm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uaualllc.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkpaumcq.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2okophoum.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjnguaj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrufuynx.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2whgjctkm.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhmnpkb.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2dnbadrhq.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2sdsvabpk.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2afjbgllx.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vxowgfqg.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjxqeih.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qfskkjsi.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2lapruqdf.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xztbnhxb.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kbctjhdg.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wpgirfyj.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqchrbl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wykttkqd.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2knxuftfd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xduitlab.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcglgwba.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2jljsowlq.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qahebdty.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2dlcltxcz.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2tovjqukm.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ozohxnit.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jjbneged.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wevtfqol.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpexoxv.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mxfkivns.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xzfwbfqv.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2ykwhjsti.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmqzopa.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xxljjazi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2zgsrifso.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zeqxvkic.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jkmkhdia.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wmuegebr.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zypklnui.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2fxflyndf.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbdmxmo.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ukcbnqbx.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2luifmshr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2fbclqjsn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdsbkxvu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2absibzhr.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fiflsqoj.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqzeynqi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwxslkk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ovdctaaf.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fekhgocy.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2vpyfpmkm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2exeruqkx.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2dzljyxpz.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2fplujkjl.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2gcwifvmq.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2gmaeledz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2nucnopbm.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2zuggtpqz.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2clwblwrx.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2oigfbrll.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2kvunnfhb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nytvsjvr.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2npnrstdj.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gptralqc.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hszkjftl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wofllbfj.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2zyprwerk.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gooszbvs.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbsqsrh.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2pncbxrfj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuldoixi.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hulyxgba.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iemwrdrv.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmwruui.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfblobqw.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2brenpkwm.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fstrjvey.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpfojkr.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2owzjzwat.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2drsopxxc.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2sdpdweff.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjnshgx.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wpcfasvz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2mmosyrqb.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcetxhgf.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2sajyqaat.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjwellh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmbyszo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbgdxab.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhlrlqx.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdjbhie.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vjozdnqd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghjkjskd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2wfsylnpp.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2eohvcicr.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2epasczsx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kojsxpud.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsaquicq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2hhyjwiok.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqaiagcg.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvnahba.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2wijosput.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2lyafmtva.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtgafsdb.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cjltwhhd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2igjvfnbx.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2aiayxtho.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2eeeurgiz.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2scifcyvc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2cubrvigl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2stofyzeq.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2uhcqnfdg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2zhftvlgy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jyyxkdmr.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ljyqufub.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cevmidwv.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2mmuddaqj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwmvglu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrzutlbh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rssguxva.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2trgxjksi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gecxyyvn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ttuyewms.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vrkgxlxe.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xittmafb.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2uhpkpupz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2opipatmb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2niaxvdiq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2apusafsg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvfyjyoe.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyyntuyb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdxolps.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gezihvgc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdpriygi.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2igpxgqya.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtckeva.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2brtscgra.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2deyjymjk.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2evdptzsq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2nwheenfy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnxynyr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2enyvwelq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gqvzvnpm.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dujywurl.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ezjskgwe.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2riulfaou.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wotozbvf.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zmdjbehm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmfhurm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2uipvilfo.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jqzbenof.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2itnrgaqq.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfjmrer.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2baejmunr.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uoxjtlpw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iehypguo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lajflanw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wlqgibed.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2evhwaxor.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2hrepryiy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iyyfujvf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfpmhqu.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2xmfpmmol.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhhuojle.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2bihqrsri.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2jdrfgrtn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2krvkqqog.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvhvsjns.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uokriywi.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2vvogohdh.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2whclbjbe.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2seuwdgvi.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcqivuya.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqmzcmp.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2liicedht.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjeabgs.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2oobzmuaz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2oqzisbnn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2epjrlmpi.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2tpiiqpit.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2ooaylvtr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqodxwy.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2jkrvlwsv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldxindkc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2jdlougea.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbddxlx.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2itglssai.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2mcwdwvoa.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lconxryo.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2gdgelcul.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqwcmmrp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhclizwy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmvaejy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2shbpfowp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kseucomd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojisyqcw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2srvwxzma.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2wakpswpg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2qlpcxgxu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2krbirqmg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2kghkhccc.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwtdxbe.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2gewacrdm.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2zhkcsnjp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjaopor.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rpatfnjz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mrlynvgp.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ecilptkf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gwukpbfz.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2woeqduhv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjigdcx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzflslon.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdrangj.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxpzghom.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmdmpio.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujihosfy.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfqcjhvn.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2uwyjarjg.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xefldzjq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywuplnzx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2impbhwde.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2jqirmfgl.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwtzdhh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hoakkdbq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmkemgh.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcuoulsf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qtrgyzuu.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwyqeau.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbbljrl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2xviyrwyy.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwippcl.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2gszwkxdn.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhkwjedi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2dripnutq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2arzgoexi.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvuxfcg.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zhpadwbd.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjhonym.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vosxzwkp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzkarmp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2zmnkgxgu.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2lfzoromz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxcnzya.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvybqbq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxlqntt.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2eefzfktm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yleyavai.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2quqwgwde.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2aydsgtpk.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2idbzxxer.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2ivkbbqqv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwmigag.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2idhonric.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2omwmulvx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2knltvedp.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqduqhh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2nxxrwzer.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2eumqmvbq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2cnpzkglu.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2dgbhksbl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2guxsokto.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2feyafwhj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhcgucj.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2yqizgwaq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzkhnha.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2alnmatdh.html


<!-- 参考信息 -->