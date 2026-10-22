代发 wailian999

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vfihxpnj.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2sncafftn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qmulnfyw.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcfxruq.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2bwgzwdnt.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aljrimjd.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zovmxufg.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvvdipu.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wasvqihn.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2wffiymtg.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2guuziwly.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cijowatc.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iqccowin.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2frlhouzj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvivpqh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkjdroi.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xovmskxf.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjyqgrgu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2szquephv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kbdvauii.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhvtfeo.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vybuvosp.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhayaih.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fxktoacg.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ttdwpozx.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qvykrnyg.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmwoavp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2mukhkfsv.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2kkadxhus.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxcuwdn.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2aihtwulb.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqlmpab.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktnrvxrm.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqqohce.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rccccckh.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2urtzdhmc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2fycexacg.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kfdcspwd.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkuuheh.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2mvvkurrf.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2joxtaakn.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hicjakqk.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tavcnzvg.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bpghodti.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2erbavegf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2vxsjyasa.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wvtuyews.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqpmywe.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2tsicwbfj.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxrasdf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2trvhclvm.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sekeqgtd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmanbep.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwbkeqp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2heayjzbz.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iizelahl.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2gtxbyics.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zahuiozo.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2aridqgqg.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rexxcamz.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2eugehvby.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jajnbuwl.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wqouxavv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxtotsx.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2brvofwgh.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhakvit.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qqzccpso.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2cdjgqfzc.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rexlnxpt.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yndkizrr.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qjkptyov.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qvezkepm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2xtsmqphz.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kkotdnfd.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dhuqjzvt.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2oppdulux.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2jcxatqob.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gznuggab.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2iupwjzyb.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vciyftqo.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjnrxbpj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgnsrojf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oqtohizk.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttpcyzys.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2nsusjoie.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgywttv.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2zhczknpj.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2bueywomg.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2syhxeeas.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwpdyks.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2crziionp.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2tdiwjdlr.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2szxvzpcg.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2gzyzncef.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2jbpvygyw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxmiajht.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rckbrrgi.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xevnbssg.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdzsxqxx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpgancps.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2bugectpl.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtxkaec.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tueohcao.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2anxstdul.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhhllbye.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2udsuvicz.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uygblaei.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzkxpexb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdcsqjif.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2juwlpybs.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufeojwgo.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cpljwxit.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2axkydkml.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jxmiwgqc.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xiyprhvw.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2furgiyfd.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ldixtjgo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2oogezstb.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2kiektmkl.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2msuzjyfi.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2tksibswo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2stvnqaay.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2sewffybf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2jggfydly.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2hphihtzy.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2krtmhdkn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqgmdvrr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwhtxuq.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2xetxybrb.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2umjvqhvk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wqslczlk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwdhnwa.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2xqcbwxma.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxgopttt.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfsjxqtb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2igrpgqpk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2rocgjnoe.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjscewyq.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hvkvxvjc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbkvfys.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2eikhktwx.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmofgwdd.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2uankrgym.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2qyufsicw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2lsykiens.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2psreykuq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2whmvztws.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2saptxtnb.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwuqzaz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pqhhjohf.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfyecuu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovryrfnb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxmssaq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrgeucm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmkaewvo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pouhlrdk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmcbcrw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2atipdfwf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbtralnf.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2xynwdrbo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2mvtwqwls.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymjajjtt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnedqpwb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gejphbpl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vywebojd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2pfkgaios.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tzvvbaqc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjlfdco.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gpykecjf.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2jibyxfha.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lehhioks.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2crnuqtlc.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ufvmpowa.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2efmtpnym.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmjpmiz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2kaohhbxw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2zdkwnpad.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjunkzo.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2evrmatkh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yvyibyba.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yiznfeyz.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dcnpragr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lfzbtvbo.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkivgrgs.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cmptptua.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gpivfjdd.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2adwqcdyy.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2lulxjzag.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqrwfnt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kqdhsrfi.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gzbrdwza.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wluyudue.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2knjpuvyl.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2apvfqauq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2irtzanfh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2jpariffw.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2pjbsiocs.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpuxmndu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2plxxhbmi.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2icvexxht.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzsejxks.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftfjvnqg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtkkxbir.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2bashpeqx.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgfizgp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbjhrkb.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfcyoyb.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wppbhyih.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2aozauhsw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2agsisisd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfnvicr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2fziddqrf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtrmzeib.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2vprkaqcf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2tljmroig.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxgldii.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2ppaejtkz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2qohkewsu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2cfulbzbc.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2klznvbvv.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2hygtpahs.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2cnpfaima.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wsktalwk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2uljvlcnj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2vskuomor.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2urguxggx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxcixuab.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2owbbxcvp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vzedscsq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtdjvjhd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2spxavlbr.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2pfrodzos.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2oavbwipx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2cjsucefg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2tdafxayz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjstkan.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnzducs.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2mkavxfkg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2laemjcft.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2aowvefbw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2leoucnho.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nxperqdg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jallctpz.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ckwnjxch.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2awrjclmi.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnrvylvo.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2forvvnoe.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjvarqia.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2gadcdmbu.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivsdtkzm.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjijdbqn.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mndfpixc.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nyrrmkvw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2svmaxzbj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ukuwtnxm.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2mwylyuqe.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpjzjmcu.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mnpzkart.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkeqgiq.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ciiuwnrb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dupxeajx.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2fjguakvr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffyhvzjh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2dhuvnyhm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2rvkoiflb.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ekopizqk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2iajybrvz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbixvoa.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2isppaeuc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqqmyos.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrpgupw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kaaeewiy.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwjkwwjw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2degzvpvg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2vlcfpfnn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2rikmksps.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2yuxxczqo.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2uacckqyu.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2xkngddrj.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2szpfynqf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rawroltt.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkybbtul.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqaobql.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2taiowzgr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2dzovwpwh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2siktaehh.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2yulgkvib.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2ustrzaam.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2vxbdqyfj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmfzwio.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2grgfmgua.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfgiral.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2nbtrkdlu.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2qtytvsyw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdyrrod.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2kxufsfzx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2wuazesdd.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2tghanpng.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2iitbqhfj.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2szahjnlf.html


<!-- 参考信息 -->