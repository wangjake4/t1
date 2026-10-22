代发 wailian999

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdabqst.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lmsyfkfd.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ceaywqui.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hiamvxwh.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2odrsxlgr.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzeqygvc.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2eqcqudre.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ttptsxpl.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dyefxkaf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2nptvelzr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrwehwv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukccwywj.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eszfxysm.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtlymza.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2txvacoee.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ljaiyuwt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkwnalg.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhxhumj.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmtzudp.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jqhmyhhv.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hcecdotf.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2crndfdxp.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqzkzxk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2buacbuep.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ktklobzn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pjclaqyh.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2exvhtkpo.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhvninv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2esssejzo.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqstrkp.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndftnozc.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxigvgf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgylwdzk.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xogzzfdj.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsakjbis.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2jgvztzgh.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzpgcjg.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hifnwnnc.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2somyijgs.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lyknziuo.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rraniubv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2yuadefxn.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2eipgftox.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aoplrull.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtrfslt.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2gdhrlwcu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2znqthxwn.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sczspfal.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddguavil.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2onpssvba.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2hcajikgn.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jnenwdfl.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2llknjabv.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lyanwvxc.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2qxpmseiz.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ixzkbdcg.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fglnwoch.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bciocrxl.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqyqrxw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2arpoxcud.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2lctmfjdt.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcqhzip.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtmxrto.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2bbkgdegc.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hwcnlhav.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qcjnxdon.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdsakab.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbpcnes.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2tijufewr.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qcfpofkn.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2botfkeig.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2mcfphomt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2tdiihulu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvpqvcvx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2fudgwnmu.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qayoudes.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfkbixq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrsddadw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2szaekwai.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyetltop.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2bonesvmc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2glwrdmlx.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2yjszrxtj.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgzbcdg.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2krnodlmh.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2qdimlaqz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2grzjbcfg.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqsfant.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2zettmgdk.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ycfkshxq.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2xosiiwkn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmevwtt.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqsocsu.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2smlaobip.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2atfpxban.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhpglwju.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2hdavbxfp.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2flirabxc.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwngsbl.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2phpmfvwd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvqmaqa.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wneynnlq.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhvbpmul.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxzqwaul.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocbnnien.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yntzpdkv.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbxxdjn.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kwaukklk.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzlxqas.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqtrfsg.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zlfjvpig.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxlgqxq.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2syzbwgpr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2pcvolddr.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2byvhxrzp.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2rqzsworr.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2bytsjqhb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2ikbfrexi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2msgryuwz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2aaharzjy.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfooesd.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fxzmgzjd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqzvhoi.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2ubdihjwv.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdbcvfw.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jieyqmow.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hgnbcvll.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzloqgj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2enwstuas.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2relfjedf.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2qblbwnbd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2qghjtjhn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2ezejytgp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnetmjhz.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2klaarcoj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ifnutgwt.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnzywlsd.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2amrtasre.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifijbuvf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2wpcojtxo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2zewjvzdt.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2ewavcwnx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkpzamk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tbmdsnlc.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxcxses.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdfcgbi.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2ubpdtscl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhnfxua.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhjsjou.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dawgrtbc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xiygmuoc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2trcyujhk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfzrcxv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2irukrogi.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzjdozbf.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2oyufkaac.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2jmffwdgl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2thjvrqny.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ropelsrc.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttguqwcc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbyjfbnq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2lqhdibhc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jljesfoh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqkusgk.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjeknjy.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxipjuk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvwklwf.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vcqouafc.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2blywlypp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2grpytivc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyarlwht.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2eqqvylyn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2hcaatadc.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rnykfqvg.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ebatnckt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ovstuevm.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2emxfbjfd.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xoaqudov.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kfshgity.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2faggoehb.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hmlyxyjc.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rewploud.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ywkwhixi.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2uqssyvoy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvbgobv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bclwxelp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbduduy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gchfxxmi.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2adkfxupp.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2drjlmzvi.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhktngb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2daucwkoq.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2zuchbtdp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlsvizee.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhnsxzz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpwxnnd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwcbmap.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxhbliu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wztipsmy.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdxkjrd.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xczunzav.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2jaclxjfe.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zaivqrny.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmicxstb.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qsejbjff.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjuhpvg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ptingopv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2sgsfrshg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2itcqkbxo.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2sigrgyqz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2czitbfkb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2srrrlkvn.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2gngkfrou.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajittusl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2ietszodq.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2qtcnmbdk.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2givcvcoi.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2ajholsop.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2sckmlvae.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2zbuihvnh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjwkyepk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2blpfwyvr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdfvhdmm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqcczubm.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmdxxfy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvfwcpx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2extshpci.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2hpudyjqe.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2rducyszz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2qncmnich.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2mhugpjvi.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2pghejmwf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2hzuuaxbc.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2jskzbuqo.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqckfuw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jqmhkhgr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uhyzjbar.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2phlqmihz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xeuothus.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rmubaxve.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkpmmpae.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nsfmgwya.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjcbgmc.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqrwbaiv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2txtfkymr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2esdxtfbj.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2dphehowi.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bmpijwdo.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2chztcmrf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntrdiagc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2dttpgspw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2clsjyixb.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2bymqqjmr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrodubw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwepfvky.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtlvrls.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2potwejso.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xmiigycy.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjoqwmd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2dxgmqkwe.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2snqcqgfu.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2eagzhexw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2adtnfhqi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqppjbq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhmyjrk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2ovguuurk.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qvbaosbi.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2klnqbefp.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2drypfhzp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvxltpu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2eiwqnthg.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2frmmofwj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2igevctuc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2abpoxxac.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2vrblelzv.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrkcvcd.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbryvlkn.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdteirla.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpsvyxtm.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2fiowkjcy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2hpbjmmdi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2usshowxv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwcxzfvk.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2myjvtpcz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2jhqjnywa.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2mpjdwour.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2oljhsbif.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrqmvdz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2aokdzfiz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2hckrvgrt.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfoghku.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2teahkzbk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjqrwar.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2khpimymw.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhhsxmb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2crtffree.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2wglvjqot.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2avqqehsh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gt2hknskgat.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgljznca.html


<!-- 参考信息 -->