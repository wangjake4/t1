代发 wailian999

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2lualujaa.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ydbpwvot.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbbwdku.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnlimdua.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2onkigzvp.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbtsmaq.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ddsyplxb.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzhsxfd.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pvubulgq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjbqasm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jgplbthe.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ictgnypd.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rdafxhqq.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyukyehw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrrgalvz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nugrfkef.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnunkojj.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2lmeygjzm.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2nlytpmec.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2yvdacbtp.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rjyvxpli.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgevlyz.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugaspzkz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2feksundw.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2atdemfmx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kyngegrw.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ajgfhvns.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2toktdlvz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwhgnsn.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrphulmb.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqnudbkw.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljzohyyf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhqftix.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ruafevwd.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2btglcwve.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkipzen.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ixlpjtpd.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2glrthfsb.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2suyxledg.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfvqdhd.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cxummzmj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2rawiviaa.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2syyvrage.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oerqnsuj.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2nqylobxk.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2ywroixgj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdwnqef.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqcovyd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxebecth.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbfsndmw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2tcccchrl.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hjzxuuqk.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2bbrkbjjc.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dtkhetwk.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2qswkrvdh.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jsrxfojg.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2aqfzpvvs.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rqxrjhkk.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2eobffxoo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2uaswruwo.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2rpctjoun.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2poxixeag.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlcqzbh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2hdkbznan.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dczzsobi.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wjmaawww.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxdajai.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2geiecepv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2xxzhzsnn.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tczccona.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jrlggdpp.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2htzyctya.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2agjhyrxy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2seabzlgj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2edxnhpcb.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxpaizcy.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlesgitf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkzshpbn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jpttgnxw.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycaeuduk.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgyzpjp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2edfwfylv.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ispyautu.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2qqgyrlng.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ltnnzfpr.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2mqsuwgpg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2wdsqaugc.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2lilxplov.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2vzlkkqri.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjoyrwq.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2wkyvscjj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpeimkjx.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uygsrbmu.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvwfalg.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wiaeeigs.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hraydcbz.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpwmywr.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhsacpmw.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqvkuat.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2opqizajs.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2odqasijp.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnmpwjzi.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnoknjn.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypymfxth.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtubuxvx.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ywugzykh.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwoujbr.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sadmkofc.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymclqwoq.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ufushmrw.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2elateaje.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pihxquah.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lvaizxgc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2spbbdtyv.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjfcrka.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpghend.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2duznejfx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2osycvjnl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2xiqzetpt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2jtuoqxjw.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2nbtlhebb.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qdeotmdd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyijbyee.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2ipyxbnde.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvsusfmj.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bovbbqta.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2iupppfrv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrnptutm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2hupnbfjo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpnnzriw.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2jojioixr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjshulo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2zoidcpuy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2apgtovqy.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rrbnwceg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ejaykdpn.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjthyav.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfdxvlnl.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2aukvsgyl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjxcfvy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdgbxxa.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2tcexilri.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2obmrvxao.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2udionfsg.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yqdmwlot.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lwkmshea.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2hxugumpg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2amlnfadb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2shfaogey.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yswlzrhx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqfmyvt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2comupnhq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2umavykwa.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sxkrrpfl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2woiwtaqn.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2mruuzfxv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2usjdighj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfxcgmo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2okmfxfxo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkumiklh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2peyqxrrc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2kjbqgbdc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjozubc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmybdywq.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2sxedbtkr.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2qpkajbjs.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvlmhnc.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2zixamgwz.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bklkcxyg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2myyqnxwb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlyauomh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2zsopmqry.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2rqetznfh.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2omwvagkl.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2svkulvlx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hqucuzyn.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kseevcin.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2stedkeax.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rbpohify.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2yapizmel.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rsqdcaym.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfznped.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2odupiqkb.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2xylulrpp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vazwvmdn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rwyldveq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rktexqec.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qabgyqxn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpuziqec.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2brfbnvem.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnffalg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2yzcfloto.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2aiuljmuv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2utxovsia.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2exouirhb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ucwmymfw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2cegdzlqf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbsvzzdf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwazbfp.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ascvzgsc.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2odenqefp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2lngfvtpt.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dogziehp.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfegaxkh.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2aelssknd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2hqiokpvt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2winkpdjx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2evjmekdr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2irzufawz.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2lxeskder.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2vcnqltof.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2efhgpzeo.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2kjfkwgxp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfvunnun.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2owjebxqr.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcncrvi.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2xfmxepdf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2tbodtutv.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gmuepahi.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2ojvflgkj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2llghuzph.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2fekodnrv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhvhzch.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2htibwkfn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cgpvikrq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfaxiwca.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xhkhjwuf.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbugvdl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmhsqvm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2fsyzixni.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2fboldusz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2aktciwlr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2yntefhsf.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvfukvg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2etefewlo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2plallowa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2krlnoyou.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwestsp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iwklujxr.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cedlbmvf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmczlgwt.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2izcvgejm.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhfckiff.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wasrkncq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2twnawfik.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yclyrpme.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2iozcaypq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2sagzzalo.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2agzqynzl.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzgmqmfy.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2xjlcnyto.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2efjzlrbs.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2kytymluq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gxlmydql.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldsugeld.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2igngbwbc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oawjrbuw.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2rdynifre.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fizluyjm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2zpryjtjg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2gcbztnof.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2agjvrccr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ioaxyyku.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrgzeqn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2mrnxnvcu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2ygrwvhey.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fzocznny.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbycgfvy.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bavulscq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrwjhta.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwnyccwo.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2bflokygc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2kcdlerkv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzrvatn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgehjoir.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2eunvnruj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2typpehuc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbgmcmwt.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtdduoy.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzcezhqk.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2nypvwmgc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2clwgarrf.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2msgxrudc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdoztla.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmogsnv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2yydeclky.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2uxnulnzh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjwauts.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2xipgjctl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2onjvetts.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gt2qflsaxwm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2tujebdfq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2sxlbzvks.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2swoakoht.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvzmwgte.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpiaqqih.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjvrgga.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2anecmrkr.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmihihjh.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsusjvwr.html


<!-- 参考信息 -->