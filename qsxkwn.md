代发 wailian999

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwaauck.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2gfklford.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vzrsouhp.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2plfmvykf.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2yjmyovtk.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkglnwv.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvvagcs.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dibvsufn.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hbzskrnd.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujeqzpnf.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uppekfkl.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2skomvsgp.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2noywejse.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmglgoa.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tiijdcdp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2juafdxms.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aritksjq.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljnssgpu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2txywcdwm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxctbbm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgesgofa.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qzhenigv.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2kgzkbvic.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2enmkibrn.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2yibxadaa.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tdiowtgb.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjzcswp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2iydkbftf.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2wdyuptxm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmzpotm.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2iqctpxpt.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2hifuilwm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mubfdhjd.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjjzuxpx.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahtedodz.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfjkdso.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmsvixq.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2osuephwe.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhsvbzrb.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ijewosqp.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2srwqpnvp.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbtnchb.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhggxqj.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xckbhcrq.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2klwzorrn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2nxesmuwh.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bosowgbc.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iypblsok.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lfmpfphr.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvecofg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlugwonb.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjlnryrj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpsopkzw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ceyxembs.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2yfamluao.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yrkfmczy.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2eugrmfsu.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2msidfmpi.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ubthyyrm.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wieklcsb.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ddigjwff.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxpvjvh.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qrboufwn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jutqebzr.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2urxhgdrt.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nmgtfeec.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2betgcutj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfdlkds.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ifzxqebq.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ohyefype.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jdnbjctc.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xtggdkpc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhlbjnn.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bmeajetz.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lwntohai.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvptmum.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2dqtdfiii.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txdmavtk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2rtseaxpx.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2elqlupnc.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxydudpt.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwnhhaq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yajtpnqq.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhdhjxjn.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfomldk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwiolwh.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwnyiva.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmvrknf.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2enhwvoqa.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2csdfmkbh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2vkapexkh.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ipkudpmo.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2fkzjsyag.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2hvnelqyc.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2rbnzrzwy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2chffucta.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cybvtnri.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcioyujg.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qaqzsnau.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqfvjlmb.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnztgqi.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2prrzdpxs.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mclovczh.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnthsrk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nucvfczw.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmctfqrt.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbujlvmx.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eiwgpgug.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2buttrtvt.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpnshbz.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bipnipuf.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dxeqlmkr.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzznokuy.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bktzqzfs.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2trutrcqn.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bisdlgdv.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jevirthn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xzwidszp.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwozlvi.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2iosqhuat.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2eotqpwss.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2ydwtujva.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2nohfkvmw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2kukxpmty.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2ohatevhj.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pihczpsn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmiofute.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2temzgini.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgyjwdvr.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2emzrhrzl.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzykogp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxbefru.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2mhvmwljh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnivdcwc.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2etmdvtxb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2tulzymwg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2ervfuntd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2aohlkhqt.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dynygepe.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2tgxmkies.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhlgack.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2flfvhkda.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mywdohbe.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2xziqcnls.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ozorukcp.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2nggkcnzl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2brpuhfoz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pflcuvbl.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lzkkfsjp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2azhfdvxu.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2sywayuok.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbdhhia.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnpvyerx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywczzslr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2avjxbaxs.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xiiirghz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2bysgrytj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cqovxxqp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtptkhxa.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2xekuwooo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2vqlkjrdq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mesfjmki.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwlgxucv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yznrysno.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzsvhjo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2lypzbtca.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nxexvdaf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zeixfolp.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2thhzaugo.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwehrowk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwiwmxd.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2sgydqjnr.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqgkkdo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2upoaxpta.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsrjdkqc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2arbaiqay.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2yhalzzvb.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jqdjkqtk.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2waysokfx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mlmrckbq.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfbbuan.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vsoubtkf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdqjrtm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqhhzygb.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2slhpnaze.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wurnardr.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vvcuorqc.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2scmtwfxn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2doufoqss.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfeaobw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cdejmxrg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2agnysbcj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqifrvlj.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2xyveqpgq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yhmkxqlo.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2eutkfufe.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2almkhbvl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltcewbdx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2lmryuhua.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2pemuxwcs.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhitwwee.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2eysytuix.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gburdwpr.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2sajcljlk.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2idnipuwh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2hzjjnvnd.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzbuvgy.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbkpjgwl.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkbqcje.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2ubcxzwvh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2pfszleto.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2fbiqhada.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mshwcrqy.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqketav.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2gvhfhjej.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2vskvmuom.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2itvsmobx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxpzfhpb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmdcpyw.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2kmiojnrd.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2owzafuni.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2qtejppha.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2uomzcmcl.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2yccscvpd.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnadgug.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2prubgsjn.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2isztlmbb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxclawmt.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wrhqeury.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybkosvsb.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2uquqljgj.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2jwnnrrhd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2utqjnytm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxpagwi.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2hmsdpjka.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2zojbyueu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2ljsfctbb.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkerplv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2awcnxqyq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqyalbt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qbmlwjgk.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kckmwnwl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwxprph.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2whuocwum.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ishpexsy.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2khtwohpp.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqclfxe.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqakdivy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2eszjrisw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvltwbj.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqqgrhh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fciofnxp.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhibgvc.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2shvxxkzq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2aghkasxu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdmrhbz.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjhtjvcx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oikeonaa.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkfahljs.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnkgary.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lruowunw.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2kfctvbja.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdqmkjt.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2nprjryop.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2epahbdqz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2kgzeblja.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zyyggpqj.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2bghwxaqz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ytcvblic.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdslzah.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ikhfgsqo.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvnyjdly.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtsxnxde.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2mnksokmw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2iazkbama.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2naymovkd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2qkrhgylg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2orckgzbb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2tawuqpwb.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2epgxsqbo.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvworfe.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxrukdya.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfgjfubi.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdqmpmfu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvnbwdci.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvwawnh.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2pknrqxwu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvlqiby.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmlfwih.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2vwpnntwv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2uzkwjgsl.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2wbvylvri.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2kmjjdshq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmqxvfh.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2vfnlaxdq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2fidvktph.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2veaxjuep.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2bcnnfkcs.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2avsiytzy.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2iimznqhm.html


<!-- 参考信息 -->