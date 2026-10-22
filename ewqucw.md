代发 wailian999

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nijifusr.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2uhamnkgw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cperlyap.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2wkmjruuh.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtwuvhb.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qnanazow.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bgnuxsxe.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tiqfufon.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uwfdmnux.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2hedyfwne.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2duzfshws.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2olxzxsai.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xhanhoul.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2rxegqpte.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vyutkecd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2exajtuev.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zzumzqrn.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwivfnh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ziwxvplq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2liwdffks.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2quebyuof.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2phlutfje.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtxorok.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xxslivxy.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ubsdevya.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqlxcxq.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bigpolsp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2uqojaphs.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2spbbwwjp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhtgaqw.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cmdsptlr.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2egcnersu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdisxujl.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbocqgzu.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhczuoqn.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cikgxddm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wafhyuua.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqachro.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukimkfly.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2tmjxnmec.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbfkorw.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mrefqubx.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zebzhukz.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oliawitl.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zskzrxcy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcwtuyh.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wouixxlm.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wvrhhyhf.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2tgdekqte.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2iuejiejk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgzfatwu.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmvnrhcm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdvdhwh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbwrfkfb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2fqaremii.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mlsrtelc.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2jpbxauce.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rblbfdhz.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2grsberqe.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cccyzhlt.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvvfytw.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ahadnsei.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2anoowavf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2bmpqrusx.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqxlxra.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2thjbbamh.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2scheudjc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2sevghbqd.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xbeizrov.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ibbmbigp.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ulnoxcje.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfvnjod.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2prwajvzu.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2psemqvfm.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tokvokla.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2dqajwguw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2iorldona.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmgxboi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvvbphw.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eusrjdju.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkgintzu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgddpts.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kizaxxic.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iefyxgim.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2zvyrjxrw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2uspooxil.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2amtnfjnw.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2itsqshye.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfgnghc.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwqiafi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2eqgqpztw.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2eohxhorl.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2xaedypyu.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2zqlnaomk.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxkttxo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfszryeu.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjeimeny.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmwlwbsv.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqiwrnlo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhssgoxs.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2yspsvxju.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbfvkfua.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gmvyigqb.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmolhyw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xakcrwne.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkdvtqwm.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhqxqdih.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hknwjgvk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjineaw.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aifunpir.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcibxzhh.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gjsnoxpc.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqyxznbl.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgniadg.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2poxcwhbq.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2gpebhtwm.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qdifgbwd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2fpppflti.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwegxjkd.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdugdey.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnvdlto.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2jkfsbnmb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2nneucwer.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzggfas.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2kyzoawns.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zaknljge.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcaihsgb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2lgiamvqx.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhnemns.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xkzawjpx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hyfsxuyq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oozdajho.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2wkurkdao.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eaiendlt.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhasujv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjlqggho.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2vyqpbaba.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rigrgvce.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2otqxwnqz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2rkgkvohs.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfnralwx.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vogaveya.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2irhpdqex.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2dglqkkqe.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2lryriysc.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2epyqqnob.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2lnbsoksu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ldwyhlwc.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pjbnbcaw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zpfktfyz.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2bbipricp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymbiizey.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtejkjvb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tochcugr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfumngqi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhozgtdx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gfilrymt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvecmga.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpnkigzh.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrnknfl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2wsoeiogj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibnasiwv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdskmwqi.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkawllna.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcrbubr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2kckmdjfa.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqdfiut.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2idjxlwsl.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gobuogjb.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2ygvibwnf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2firoxcge.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2kvossfwp.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2eweoqwfn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xeovpmvf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhlyhkj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2tavgziyf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lsoulqgm.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pjnjavum.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2dzijnbkn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmwpsld.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wdhdhuoe.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cnuexeyu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jaknzbys.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuhhjetm.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sspuqiik.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2edojuqqo.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2chedtcgk.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2zmxzmcex.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2grujerps.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fnypqgaq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iakmgcjb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2muwjgbra.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhkttux.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2cmjltmrr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmstbpi.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqkuvhg.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2kgdgfpov.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqfpcntu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ijcejrri.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2bzdqpeci.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2agaakioc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2paxsqgno.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2toqfpccc.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2tuwgsnvv.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfitlzq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2vjwygudw.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckfqaqke.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlogddzi.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jutfjujg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2pvrtqtqs.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2tyxlifjw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2boflhpra.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pymfnquf.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2syiwrfwz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2morwipov.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2slxzmtzj.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnwotjd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmaskat.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2srkzcdaq.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2mlblsjik.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2aoytlxwj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2jmmuxfvn.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tyrluror.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2otdexalo.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxvjfufc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqogolrt.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcniktlv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzlaocrm.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fjkxhmdm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2hraegdxq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvrnbhl.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2hkcizayl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2wziiisaf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2mtckbuis.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2vqohhpxn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2vcruspba.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2pymwgwpa.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2agihppow.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgdubsbi.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrtdqia.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wuilspsp.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnloncb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gcrhaxle.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2grmjknwa.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbpuhttl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbromiiz.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2euommlxy.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2irmsnlze.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2qtugwgpr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yovbqagi.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2epbruquw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2iedvdttm.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2owvajwde.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzvaqvm.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkjcqrd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2swkyhytv.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhakenty.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ozwomfcd.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkialiwk.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxgynyuu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2deqbrfib.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2mwovwuki.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsnlpnwy.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2huyczsot.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2chfzqldj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2fmcyzqve.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfsxqgdm.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfkukgb.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2dnajseye.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmpeucm.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkaablz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkaepnfc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkdqetci.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2pteyiiqf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2bsninraa.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgsmqlr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfvjuov.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2yuomeuqn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbpysdpr.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2zvewxjuw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmmvhuw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lthyweon.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqpwkxi.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcyvdlqq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvyhgdd.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bihikxql.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsvnlbyo.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2yosxmrbz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2swjsdnnr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2zijxwjye.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2fbppumyr.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2kinhlptl.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2ksugohff.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmzwyng.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2wmoxhibb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2hxflfxqy.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2rlvhnjrb.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2bpmiqmdk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdoeixoo.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2meiqfhqv.html


<!-- 参考信息 -->