代发 wailian999

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxadimo.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2nzkkmglx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ufsifuqp.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2ssrwpwbf.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2wnmqucpr.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwmscto.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrziftv.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yafqozau.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rtcsudog.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2swpqvxzb.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xwzueeok.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjiaczf.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dyticjjx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfgulau.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2beukkglf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oakctuvm.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tdgumyyw.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygobxncc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2axlpvtcl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uetmeqfw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2svjsvqgk.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2suarwecq.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2sokfnvxr.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pqkzkggr.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hogkwxzn.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dhnsizzp.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2eoksicpu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2eosrxndo.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ruekulio.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ybylvxhm.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2onrpzjcr.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2qmkhrsfr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrtdxfx.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqsewezu.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcxzlaix.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2skeqnrfo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkjhzzpq.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ecazugxe.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2asbicvcl.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2pjqfghog.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2yowyjkjv.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zxvnouws.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2muschuvz.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tiabovcj.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtisnpn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ymxjuuro.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jdglblcj.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2omtbxeoj.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cjnqjhfj.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2dgsevshb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzckoox.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oisrzetu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsqfsyyh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2drigjezl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2qyqynpcm.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqlkbky.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnxgkgy.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2nfdimcqk.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ktnaidme.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ubuqusre.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jwhodmwk.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hbvjjjuq.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zxwjddle.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hljozehh.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2prsdulyr.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2edzzbnnd.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bsefvkxt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2ezqxczzu.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eeaddsme.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vxrtwwzq.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbolyzr.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbkpste.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2jnkowudv.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aviwwbjs.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kfzlxmvz.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2gwjaopyq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2mntapavh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfyjzmh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjywgbs.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqaopfnn.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhpsdxo.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cuadvrtb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2szwvwzsb.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbxayynp.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2okmrkdqw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwgwqoj.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2gmchiivw.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2chirhixf.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2gveiegvf.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2ahegzbgs.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2kxhscrsn.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2arnjykqb.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2niftdqrv.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2apchnngj.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2aliyrouo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvjctcuh.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdljuun.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrazryiz.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhuojchk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvxznax.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2khcywpem.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2soaqjgda.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2udnejqmv.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2zvieauok.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvrwmiv.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzugajrj.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oaixrfme.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwnpahqq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcfdlqw.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dcodkwll.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2cozkinmx.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ezidofeu.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2fldvaxcx.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbeixly.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mhdilfyz.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2syldrigz.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqunwoi.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2thsanpwf.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2pracbely.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2mpcthrzg.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2djwskgmi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2dktwndwn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2roxxfxnq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqnucgw.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2sbeyfagx.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ggimqzka.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfiucvf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2izudovhr.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2wanqytrh.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dmcbgqyu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2izcdxnah.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyutrksn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfuwuje.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hacmlmcz.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbrcqtdf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2trqvdrsl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2wujnvpes.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mswetuhm.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qzhmotaw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmjleza.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxlrjvwj.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbawvmg.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgdplire.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2admbitet.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2apmdjzfm.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjwpael.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2vxbjdpdm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2umuljpvh.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2efheulhe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fzgvozjn.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2dspbayhu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxyezyd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbwkyzyr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywfxsujb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iuamccyx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zntoeirj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2chzyuzgk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oorhkoui.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrxuvjp.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdjkikg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2qkugnoam.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdejwize.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgakyhlf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kamobobb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ceflbmkq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ggrooslq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fekdupbt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2opgedfsl.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2sdgokthg.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2jqgzdlhl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2kvylerlh.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2cmlucqgq.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2isncxxrd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2njbsocxz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzgnlfi.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2xnnvqsrj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gsiolqxf.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgcuill.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2tdcqmjxz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fthwvrzg.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kpcntaft.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2usgkzmsl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfxfwbd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihknvwpy.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2clvbtiax.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbcgvjp.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zeuggyvz.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2fucafisc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2agorckvy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ymlsinbj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hivwvhzv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cdhemncn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnaypnrd.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2avosojih.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sqdltsct.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2qytlziyr.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2isvpqcjo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqfpwoq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2wcaoceie.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2deiwblha.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnmhlbw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjuhtaua.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyelancd.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2wlljqlgx.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2dtfcoahm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2juitxzeq.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwraptpj.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpruquy.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjzoavsw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2ucjfnjmt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ztiffegw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2aftpjiaw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2izequeqz.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2yilqnarr.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2actgyifz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2ufpjqjjj.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2bmfazuxj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxywflpw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2qpngzjor.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwimuih.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2xacpwnri.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2evvmbnmu.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mnbengne.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2sasmeqpo.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2aumntczp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhvhzpgk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujpmztxi.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgmmrccb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxvblly.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuykgqak.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qkletwgi.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfergrz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2kmeuifka.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2gxalyonn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2vxppmqmn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2ofneuxzg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2plxmrtpl.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2vdzbhwms.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbihiev.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jpubiwci.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2prsxwwfv.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2akyfgtwz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cmumgayr.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2akhjzocb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2haasuqcc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhprfnw.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnktzvft.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvkyizdt.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2ddzegnah.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yddighmw.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwtmaec.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cqkqqnzr.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2inmdtiwu.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdjsone.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtifeuo.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvezaoo.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtengsze.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hujollau.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvcriugb.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhtpkqii.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yngvkaua.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2jnrskiym.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2blamgvqr.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwglapm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2uilqkoie.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2oalwicqs.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcumhosw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2dpojyumz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnfaxfy.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2wkvjceza.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vrqjmean.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gltfbvub.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrsqnnox.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ymferduq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2sewrcnfq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2zguypbdu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzaqucja.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2eipmsngy.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmdfeba.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2lpouetoh.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yenfzwcw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvifbmcs.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2clxtqvrg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2irdijvzk.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2nioahfrb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gccwzafd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcscdkct.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2drndxhxl.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2yxfwedmf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2fjigutvo.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2fqammesn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2awecnswi.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmhnukr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2lonmtqaq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2hacqwciy.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2bofutffk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2fsslwqco.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2qsdmlydv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkvanyu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2evgkfqyv.html


<!-- 参考信息 -->