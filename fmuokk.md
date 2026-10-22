代发 wailian999

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhkhjxz.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfldcct.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2exvpaaup.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2izopdulw.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbmunij.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2wcihuqje.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wlihyfdc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2swtwwvdz.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pwfeegba.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2omktrmxb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrfiwrfe.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vvotqduw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2irekbjeq.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2rnrqzpoo.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvxjnpj.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2oghxprbv.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2yoiszswu.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnagdpp.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtsciifq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2pcsjbrxa.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvoibsm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2chgjclzx.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pikmfflg.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ddbyuobz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrnvcnjy.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqdidax.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eplguiye.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdprqbv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2dewwpens.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdtkdhy.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2stfscsbl.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2jylsbsbe.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2auhwigse.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfaesmb.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjqwjiu.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ckzktndx.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eqtwkafd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2nbtvbxsl.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bptojvrs.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dsmvovvy.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfeucaw.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2mrzjubjh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwgsvgjl.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqatbdsp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbchpacz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjigceam.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjjuqpm.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2duxulzuh.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrsrjhb.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ienjdwqz.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2jdgaeini.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzzzesq.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2iflbcouc.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zaymncao.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hukwltie.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ysvgktvt.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqnumdz.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bpuvvger.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdthtbz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2vqcwfbfi.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zoajolqf.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mldksomy.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjmrwov.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jueseemg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2swmaiazm.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yqcbnpwi.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2auvsmalk.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2nobvdwxr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2nqhwrplt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncedbpvl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2jhcmlmli.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmkqxot.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfmumthl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2swrkkwgx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hbgiwdwl.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyputbhh.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2mxffyurw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2yptsmbbz.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qfzouqzp.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdiqzlt.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2epyuvzzo.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2xthhgaqo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2ttoencac.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzofyon.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2preesazh.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2xgmduezl.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2tsfvuvyz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkizgnvt.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2spdteybp.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjvhjrfh.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhuzkzs.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2piizyutl.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2igmetdau.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxmahpa.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2spnnosox.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2kvzfcxup.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkbgscml.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yksxqxqg.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccglabsc.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbesprap.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rynsmoqx.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2esqfidzp.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqfjows.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2orangxhg.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjkmtbtv.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbqynog.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wefpypmc.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xwpdzbcz.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qpckbwhw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2noggobdj.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxvlrboh.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2dnnpxeeq.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2dritcomh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2xfcqstbu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2mfzjzobz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2omqdozpf.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2sullxymy.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tbikpmin.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2llgehych.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2yszztpik.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2hoyfdjkp.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxnxmxn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2emoomweb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgjqxfgo.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2loqzafps.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxfpwajp.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2azybvebg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovputaqg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2ypslvqsr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqcviuly.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tywgjcvq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnvantd.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2snxeibqi.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbmsskok.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzymfvb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2tcjduuxb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2edqqkyak.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2kqogiulk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2jkjurqdj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rcesiohp.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2oigaddzj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkrnyqz.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2vusoymvb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2kppbqhah.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfcomui.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjpfquem.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmmgjjz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2losjgjho.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kihhavoh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnuojym.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfhoxyh.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2icpyepew.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2oxuzavzl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbsiyswf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2buicgxlx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbniwop.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkehalzj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2acufowdi.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tpswtdut.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eijhucfu.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2oblcwgtl.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmkoqlyj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2opcohabw.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ginwgozq.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2yqcoayea.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2chhjcxpz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2eirimaev.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2ydbovgjo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2pbnsxxwv.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bvuebgqs.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2vjejxsat.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2toblypgd.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wwdfikcn.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2isqynfxj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rmswhnti.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2befxulwu.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aqrkivil.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iirfhkhw.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jnambzej.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2terkhzkx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2aihjywvh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2phqsbwht.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ivgoxxxg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdgvabq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2oevuxwpy.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2eybkjbyp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2enuivyfw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2lzscmqpr.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2znjlcrnr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2joycemrl.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2jseteaxx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2wrshvbvh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvmzsbk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2swpalccl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugisehwm.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2lnpbsvae.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2iducqrqs.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxbwfky.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lyrqtvnd.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifknyoue.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxelbaxb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxzodsz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jtafyjnc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2yyemhqme.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2umxnlirj.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxvriln.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2yqcdlgwk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2ioavclnm.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2ndutvgfk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmkikksd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2ffvkewyj.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2byhvkchs.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2norstqnb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2kwcuohvs.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2txjmgplx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2hvvjtrrw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkpvqrax.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcerargi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2afkkxqac.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwywbkwl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mzoizkrq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqdertku.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zwcjihck.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2pndhiosl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2onbxgqnj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2zohljepr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2vopgiann.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2bciqsafo.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2frjnejwh.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdcehgv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2izkicevn.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gpefqigx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xivkowyp.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvuphxx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sxrigdoe.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdxuupm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fglynhkc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ostymitr.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbddtpmx.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2oonccxrv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2vdifpzxe.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xybqncua.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkfgofls.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mpqknxae.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wnxjcywq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftfqaxbf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2iqgwckko.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ocuhfaxu.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2oswxqtmb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gqccekck.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbeflafz.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2gehnvmlj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tfuhqobx.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2banyjotf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxtsrcu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ovymgpes.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2jpnruwby.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2pgdxxjze.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgsisbzs.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2wmcjikkr.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2pmgdtuxn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2pwzkqcxe.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vlrftrgf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcicznio.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdexiqcn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2lfqzvzhb.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2kchqfudf.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2reqrwhql.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2akdifjoz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2fuswzlfd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqkbzid.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2tvqrpyco.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvyqfagx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfvreqkg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovpbddkq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ueparrsl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixluyewe.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hphjdbcw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpdrcjaf.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2fipvclnw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2eemajvda.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2zutxhvsq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2utuunwmu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqxddgs.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2vbduttvw.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2mhoiwygx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2dncphlwm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2ritvfbqu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2lcndruyg.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2okxbufpe.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcnosrov.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhreoxx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2hcrpnsvm.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2hpkpiplp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gt2nobdjujo.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2octjcouz.html

Ruby: s.scan(/error/i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxkzmpd.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gt2unxyruaw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgebhbg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gt2xzemmfqb.html


<!-- 参考信息 -->