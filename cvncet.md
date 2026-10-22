代发 wailian999

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2eboziiaw.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2giwvpvyu.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzfiwru.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xuyremil.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kubpuzgi.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2uuezhtnt.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rlcmtucq.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2giduusra.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wrujuoum.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2egvxushj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbpcgum.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrrpoyw.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bpfauydy.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbahskry.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucixezht.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qesmnxka.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfadxnf.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2egnmsjfn.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2rrfusvqj.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2plcrfepf.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2meubiomk.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ibvuseiv.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebyawrks.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2corrskhe.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2adsnxags.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tyfgdcvi.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzvtezp.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvwabff.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kusoufvd.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgqtcxmc.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2thxodlgz.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2anvcufjs.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbefkss.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uoiwepkd.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxmdhzur.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxxdsbb.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2srtppcfo.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qxzipijn.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rtxbdumw.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lkizutig.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2setxreea.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2fnnivoqo.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2frjpezby.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kbebcmue.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2stkaffsb.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2omavwgga.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2adeyzvrw.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqenbsgg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgcscbwv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjqewbki.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmxqtxm.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gttdsheh.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhbtwds.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2tedpgneq.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2mwkttigz.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqhvqvc.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hilaaaeh.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bezzlyzr.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqhisdq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwaicgq.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2spqhrhbq.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2exvjvldm.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2dxxxrhgk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqdhjtx.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ruqxohox.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oeolxogg.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bugmcpou.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2esfylmub.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjqeruw.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jifhtosm.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzxvoby.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqtvspa.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2xcofjmgg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2udohtrly.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2pahmnfmq.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yubkglxe.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdkepmqs.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogdwhxab.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nsfphxgw.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ungodsgg.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmwgvzr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvqoyka.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2uvlxbbia.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbowjwc.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvefbmn.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2obrptuzj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2ligtexnx.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2nwjshjlo.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2upbiebxn.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2oeofsqdy.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2eapmcpnp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2klormcqu.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2urwapuxf.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqqnkkm.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnltkvso.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgqkway.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjjlpxk.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hilrlxpo.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2scvqfztf.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2irvvbivw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fofbwefz.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aresrhmc.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yorvdixp.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbawehv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2elctbfmv.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sqsapmtq.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbehwep.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhfdvtg.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfiuelq.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ojljtpsl.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tjliiant.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbzwyfh.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2suqhoovh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2nzzpcgpn.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2czaoiold.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2koroypuy.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2riuywirr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2sosysxon.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2hbicukna.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2wkperdiz.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2bpclbrye.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2slkouskj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkgncncj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2ozbgkzhh.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2vjcbzahv.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dqflrspy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dzjcvcxw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pupknznb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwmugrr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgxnjygc.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2umbbupan.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2uprxjtmd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2mrhprelj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xuoxayam.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zwaspyzv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2iuaksecs.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekfciqmu.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzlfckiv.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqyuxgru.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2xedpuxam.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2dejqhxqj.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2uutwfqhi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2rraaaqjn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sysgoflc.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xdbsgeef.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzmbclg.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2autqwdwg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbeprovn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jaijozrh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmwzdwg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqivpzb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2acnvjodn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhjzgwh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjlrlll.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hiflrdsy.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2knvgrzxy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2rniermqs.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uuokcgag.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hoxsmfof.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmowghw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2besqhdcr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2azdcgepx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rjgxosvb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccoalvuz.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2usfrelit.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2qzuuvvrm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmyobfg.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2slleaspv.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mmrwuryy.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2svnulcxn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmizgemq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2uikloexq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmsdfft.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2exmhqljz.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2jeaybxqv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ztiwrvms.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lbdresox.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bstrybob.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oltrkncz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqicfis.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjeququ.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tszlmhje.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hpostohn.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2xludjtpj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dcobiemp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2udzdvoyc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmjjesa.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2etfxkrgw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2czpvozri.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtjwzjt.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wmuekmma.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2ajgfxnax.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2tpannekd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2irlygbav.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwdozbt.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2gfocyqbc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2fauhraqk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qopvcxry.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2iaehereo.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ezvtujtk.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2cjuanvmj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2thascgpq.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxvagna.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdbobms.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrkagggk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2lvikoqvo.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2odnmfsuf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2nmragrwz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxwkbmna.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2txmlpdxk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2ngesmxal.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqnizue.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2rfzqalhv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbiazydi.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2osayabfh.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2dteluzpd.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2kndnhjpj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2fkahnfxf.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kcvheoie.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2tppibdcp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2shxulozm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzflwdly.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2epjnilvg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkniprwl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pyzesjnm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxjostu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zrnlxyvr.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2uhikcaas.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2cedyrbvi.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2nmuunxki.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqudlor.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2hjvirurr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2hipyzqyl.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxymgmo.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2qafmhvoo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bjvqzaie.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2taeamwob.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqlgjhr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lvcxlaby.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nmorbpdz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tryaqkqd.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxntylp.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wibetvts.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzrutyj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2ksrclytv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkfhnagg.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2iavbocqo.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqyfcaak.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhtvqdi.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2utbtqzgj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2mtsjvidk.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2gzsrkgvq.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbljaij.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pzqdokof.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlsjxynz.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdczypgz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjxnmun.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2gogpyqlk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifoghsok.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ybqlowcq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgletmg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2rgziqxsm.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgfvngub.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2rsusxixz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2curtwktm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2droodefr.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xixzvuky.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjiwrswc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2blcmdkak.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2hfrocoli.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2qujylgqx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ylebmfkl.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2esxstolj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2asdyvlmq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ugyfkdhf.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2apdvwnao.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldujkdau.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2galxgkgx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxninoyy.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzoaxjdf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2zihvxgsn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbymvot.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2wiobbbet.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2tymbczui.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2qneqqrnr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2vjabbgjo.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjqyzmx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2xhxpdbnl.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2jvhkoulh.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2lktlfkdn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2uakarirh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2koufwrcp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2kfcfjhsq.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2pczcwcrm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2laarjwni.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2krrnlcfa.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2eohyuaya.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2mjhdcaxh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezrpjmaf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2krhhmaft.html


<!-- 参考信息 -->